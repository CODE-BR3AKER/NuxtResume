# :zap: Nuxt Resume

[![Netlify Status](https://api.netlify.com/api/v1/badges/4d0ab666-0fbe-4fbd-864f-aeeb7175505e/deploy-status)](https://app.netlify.com/sites/modern-resume/deploys)

:clipboard: A modern simple static resume template and theme. Powered by Nuxt & Netlify.  

*Host your own resume on Github for **free!***

[View Demo](https://nuxt-resume.netlify.app/)

----

## Features Highlight:

- :zap: Blazing fast
- :printer: Printable
- :hourglass: Setup in less than 3 min
- :iphone: Responsive
- :moon: ~~Dark mood~~

----

![img](screenshot.png)

---
## Roadmap :round_pushpin:

- [x] Setup with nuxt :construction:
- [x] Replace bootstrap with tailwindcss :art:
- [x] Replace font-awesome icons with vectors :heart_decoration:
- [ ] Split up the page sections into components
- [ ] Implement nuxt/content & netlify cms
- [ ] Add dark mood support :moon:
- [ ] Make a video demo & share with community :arrow_forward:
- [ ] Add metadata
- [ ] Score 100 in lighthouse :vertical_traffic_light:
- [ ] Optimize the printable version :printer:


----

## Installation & setup guide
This template is designed to be hosted using Netlify and so that's what these instructions will cover. If you plan on hosting it seperately then there might be some extra steps that we wont cover.

Before starting it might be useful to familiarise yourself with [Netlify CMS](https://netlifycms.com), [Markdown](https://www.markdownguide.org/getting-started) and [Netlify](https://netlify.com/).

### Step 1 - GitHub
Start by creating an account on [GitHub](https://github.com/join)

### Step 2 - Create Repository
Create a repository on GitHub to hold your files and host your resume.

### Step 3 - Download Resume Template
Download this rpoject as zip and extract it into the git repository you have just created.

### Step 4 - Push it
Commit and push the resume template to github
```
$ git add --all
$ git commit -m "Initial resume setup"
$ git push -u origin main
```
### Step 5 - Netlify setup

1. Create a netlify account if not already.
2. Link your github & add the resume respository as a new site.
3. Enable netlify identity (to use the CMS) & add a user from settings.
You should now be able to see the demo resume template using this theme at `[your-site-name].netlify.app`
4. Now navigate to `[your-site-url]/admin` , edit the information & hit publish :tada:

----


## Run locally

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).


----

## Credits:

This project was forked :hocho: originally from : http://www.github.com/sproogen/resume-theme , powered by jekyll/bootstrap & github pages, I rebuild it in Nuxt / tailwind & netlify cms.

----

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).