
# The Su Lab's Website

Visit **[sulab.org](https://sulab.org)** 🚀

## Lab members actions

Lab members, please do any/all of the following!

* **Update your user profile**. See the markdown files at https://github.com/SuLab/sulab.org/tree/main/_members.  For info on the format, see the other examples there. There is also documentation at https://greene-lab.gitbook.io/lab-website-template-docs/basics/team-members and examples in the [testbed](testbed.md) ([rendered](https://sulab.org/testbed)). To create a new profile, just add a new `.md` file to the `_members` directory. To update your info, just edit the `.md` file that already exists.  In either case, create a pull request or commit your changes directly.
    * Here is a blank template for a user profile; fill in as much info as you like:

```
---
name: 
image: 
role:  
group:  
aliases:
years_worked:
pronouns: 
links:
   linkedin: 
   github:
   orcid: 
   google-scholar:
   twitter:
   facebook:
   instagram: 
   youtube:
   home-page:
   email:
   website:
--
```

* **Add photos from lab events**. Add your photos to https://github.com/SuLab/sulab.org/tree/main/images/gallery (again, via commit or pull request), and add them to https://github.com/SuLab/sulab.org/blob/main/team/photos.md. (The format of that photo page is still TBD.)
* **Add to the lab handbook**. If there's stuff about how our lab works that you think everyone should know, add it to the [lab handbook section](https://github.com/SuLab/sulab.org/tree/main/handbook). There is also stuff that has yet to be migrated from https://archive.sulab.org/intranet/.

## Local development

Most people won't need to create a local instance, but if you are making extensive edits and want to view changes before committing them, a local instance can be helpful. Based on the directions in the [Lab Website Template docs](https://greene-lab.gitbook.io/lab-website-template-docs/getting-started/preview-your-site#on-your-computer-locally), these are the steps to get a local development version of the website running:

* clone this repository locally
* Install [Docker Desktop](https://www.docker.com/products/docker-desktop/) (recommended) or just [Docker](https://docs.docker.com/get-docker/) and start it.
* Run `./.docker/run.sh`.
* Wait for Docker to build a sandbox with all the languages and packages the template needs. Should take ~2 min the first time and be almost instant on subsequent runs.
* Wait for Docker to start the preview. You should shortly get a `localhost` link that you can open in your browser to see your site preview.


## Credits
_Built with [Lab Website Template](https://greene-lab.gitbook.io/lab-website-template-docs)_

