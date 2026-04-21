# Gatsby Portfolio Website

[![Stars](https://img.shields.io/github/stars/hardlygospel/gatsby-datocms-starter?style=for-the-badge&color=yellow)](https://github.com/hardlygospel/gatsby-datocms-starter/stargazers) [![Forks](https://img.shields.io/github/forks/hardlygospel/gatsby-datocms-starter?style=for-the-badge&color=blue)](https://github.com/hardlygospel/gatsby-datocms-starter/network/members) [![Issues](https://img.shields.io/github/issues/hardlygospel/gatsby-datocms-starter?style=for-the-badge&color=red)](https://github.com/hardlygospel/gatsby-datocms-starter/issues) [![Last Commit](https://img.shields.io/github/last-commit/hardlygospel/gatsby-datocms-starter?style=for-the-badge&color=green)](https://github.com/hardlygospel/gatsby-datocms-starter/commits) [![License](https://img.shields.io/badge/License-GPL_v3-blue?style=for-the-badge)](https://github.com/hardlygospel/gatsby-datocms-starter/blob/main/LICENSE) [![macOS](https://img.shields.io/badge/macOS-supported-brightgreen?style=for-the-badge&logo=apple)](https://github.com/hardlygospel/gatsby-datocms-starter) [![Linux](https://img.shields.io/badge/Linux-supported-brightgreen?style=for-the-badge&logo=linux)](https://github.com/hardlygospel/gatsby-datocms-starter) [![Shell](https://img.shields.io/badge/Shell-Bash-4EAA25?style=for-the-badge&logo=gnubash)](https://github.com/hardlygospel/gatsby-datocms-starter) [![Docker](https://img.shields.io/badge/Docker-ready-2496ED?style=for-the-badge&logo=docker)](https://github.com/hardlygospel/gatsby-datocms-starter) [![Maintained](https://img.shields.io/badge/Maintained-yes-brightgreen?style=for-the-badge)](https://github.com/hardlygospel/gatsby-datocms-starter) [![Repo Size](https://img.shields.io/github/repo-size/hardlygospel/gatsby-datocms-starter?style=for-the-badge)](https://github.com/hardlygospel/gatsby-datocms-starter) [![Code Size](https://img.shields.io/github/languages/code-size/hardlygospel/gatsby-datocms-starter?style=for-the-badge)](https://github.com/hardlygospel/gatsby-datocms-starter)
This repo contains a static website written with [GatsbyJS](https://www.gatsbyjs.org/), integrated with content coming from [DatoCMS](https://www.datocms.com).

![Preview](preview.png)

[See the live demo](https://demo-datocms-gatsby.netlify.com/)

If you want to use try this out yourself, you first need to set up a project on DatoCMS which will host your data.

You can [sign up for a free account](https://dashboard.datocms.com/signup) and then you can simply click this button:

[![Deploy with DatoCMS](https://dashboard.datocms.com/deploy/button.svg)](https://dashboard.datocms.com/projects/new-from-template/static-website/gatsby-portfolio)

## Repo usage

First, install the dependencies of this project:

```
npm install
```

Add an `.env` file containing the read-only API token of your DatoCMS site:

```
echo 'DATO_API_TOKEN=abc123' >> .env
```

Then, to run this website in development mode (with live-reload):

```
npm run develop
```

To build the final, production ready static website:

```
npm run build
```

The final result will be saved in the `public` directory.

## About

The goal of this project is to show how easily you can create static sites using the content (text, images, links, etc.) stored on [DatoCMS](https://www.datocms.com). This project is configured to fetch data from a specific administrative area using [the API DatoCMS provides](https://www.datocms.com/docs/content-management-api).

You can find further information about how to integrate DatoCMS with Gatsby in [our documentation](https://www.datocms.com/docs/static-generators/gatsbyjs).

This websites uses:

- [GatsbyJS](https://github.com/gatsbyjs/gatsby) as website generator;
- [gatsby-source-datocms](https://github.com/datocms/gatsby-source-datocms) to integrate the website with DatoCMS.

---

## 📄 Licence

This project is licensed under the **GNU General Public License v3.0**.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg?style=for-the-badge)](https://github.com/hardlygospel/jellyfin-mediastack/blob/main/LICENSE)

You are free to use, modify, and distribute this software under the terms of the GPL-3.0. See the [full licence](https://github.com/hardlygospel/jellyfin-mediastack/blob/main/LICENSE) for details.
