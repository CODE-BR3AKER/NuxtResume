# :zap: Nuxt Resume

[![Netlify Status](https://api.netlify.com/api/v1/badges/67f0f105-00e5-4537-977b-3809823d1cc3/deploy-status)](https://app.netlify.com/sites/modern-resume/deploys)

:clipboard: A modern simple static resume template and theme. Powered by Nuxt & Netlify.  

*Host your own resume on Github for **free!***

[View Demo](https://modern-resume.netlify.app/)

----

## Features Highlight:

- :zap: Blazing fast
- :printer: Printable
- :hourglass: Setup in less than 3 min
- :iphone: Responsive
- :moon: Dark mood

----

![img](screenshot.png)

---
## Roadmap :round_pushpin:

- [x] Setup with nuxt :construction:
- [x] Replace bootstrap with tailwindcss :art:
- [x] Replace font-awesome icons with vectors :heart_decoration:
- [x] Split up the page sections into components
- [x] Implement nuxt/content & netlify cms
- [x] Add dark mood support :moon:
- [ ] Add metadata
- [ ] Make a demo & share with community :heavy_check_mark:
- [ ] Optimize CSS
- [ ] Optimize the printable version :printer:
- [ ] Emoji support
- [ ] Score 100 in lighthouse :vertical_traffic_light:
- [ ] More customizable sections



----

## Installation & setup guide
This template is designed to be hosted using Netlify and so that's what these instructions will cover. If you plan on hosting it seperately then there might be some extra steps that we wont cover.

Before starting it might be useful to familiarise yourself with [Netlify CMS](https://netlifycms.com), [Markdown](https://www.markdownguide.org/getting-started) and [Netlify](https://netlify.com/).

### Step 1 - Click the magic button:

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/CODE-BR3AKER/NuxtResume&stack=cms)

### Step 2 - Connect your github

Login to your github account to create your own copy of the project.

### Step 3 - Publish it

Publish it & change your website name if wanted.

### Step 4 - Admin & configuration

1. Enable netlify identity & github gateway from settings (in your netlify dashboard).
2. Add a new user from netlify identity tab.
2. Now navigate to `[your-site-url]/admin` , and create a password.
3. Edit the collections & hit publish :tada:

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