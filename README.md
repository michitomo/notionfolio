[![Stargazers][stars-shield]][stars-url][![Forks][forks-shield]][forks-url][![Contributors][contributors-shield]][contributors-url][![MIT License][license-shield]][license-url][![Issues][issues-shield]][issues-url]

<br/>
<div align="center">
  <a href="https://github.com/Mehdi-BHA/notionfolio">
    <img src="https://www.notionfol.io/images/logo.png" alt="Logo" width="80" height="80">
  </a>
  <h1 align="center">Notionfolio</h1>
  <p align="center">
    Make your own portfolio + Notion-powered blog in minutes with Next.js and Vercel.
  </p>
  <p>
    
   <a href="https://www.notionfol.io">View Demo</a>
    ·
    <a href="https://github.com/Mehdi-BHA/notionfolio/issues">Report Bug</a>
    ·
    <a href="https://github.com/Mehdi-BHA/notionfolio/issues">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#sites-using-notionfolio">Sites using notionfol.io</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contributors">Contributors</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

This repo is what I use to power my personal blog and portfolio site [mehdibha.com](https://www.mehdibha.com).

<details open><summary>Screenshot</summary>
<img src="https://www.notionfol.io/images/screenshots/screenshot01.png" />
</details>

### Features

- 📒 Writing posts using Notion as CMS
- 👀 Pretty URLs & SEO friendly
- 🤖 Entirely customisable through one config file
- 🚀 Fast page views
- 🌓 Dark and light mode
- 📱 Responsive
- ♻️ Incremental static regeneration (Every x minutes re-update website content so no need to redeploy)
- 🚀 Deploy on Vercel in minutes
- 🔍 Search
- 📰 RSS feed (coming soon)
  

### Built with

- Next.js (v13 with app dir) and React
- Typescript
- Tailwind CSS
- Shadcn-ui as starter components
- React-notion-x

## Getting Started

If you want to clone the project and make you personal notionfolio

### Configuratuion
- Star the repo
- Duplicate this Notion [template](https://mehdibha.notion.site/11efa51a4fb34073acfe8ef1f70aa0cb), and share it to the public
- Fork this project
- Customize /src/config/site.ts
- Replace favicons and images /public
- Add NOTION_PAGE_ID as an env variable (see .env.exemple)
- Deploy on Vercel (do not forget to add env variables)
- Run script to update website for new features (yarn run update-template) (it syncs with this repo without changing config file and /public)

## Roadmap

- [ ] Make the website responsive
- [ ] Projects archive page
- [ ] Missing cover image in blog posts
- [ ] Fix display date in posts
- [ ] Infinite scroll in blog page
- [ ] Make config more optionnal (config/site.ts)
- [ ] Switch from react-notion-x to a custom component
- [ ] CI / pre-commit hooks
- [ ] Fix all linting and type errors
- [ ] Generate a sitemap
- [ ] Implement RSS feed
- [ ] Implement analytics
- [ ] Auth + comments
- [ ] Collect emails to continue reading an article
- [ ] Introduce courses feature
- [ ] Introduce tools feature
- [ ] Automatically generate a resume on build (using LaTeX and maybe with different variants)
- [ ] PWA
- [ ] Add themes and variants for components
- [ ] implement i18n
- [ ] Make a website to generate notionfolios from it directly

## Sites using notionfol.io

We will be happy to mention you here, just make a pull request and we will add you

- [mehdibha.co](https://www.mehdibha.co)
- [hamza-bouissa.blog](https://hamza-bouissa.blog)
- [iyed.dev](https://www.iyed.dev)

<!-- CONTRIBUTING -->

## Contributing

See the [contribution guide](contributing.md) and join our amazing list of [contributors](https://github.com/mehdibha/notionfolio/graphs/contributors)!

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contributors

<table><tr align="left">
  <td align="center"><a href="https://github.com/mehdi-bha"><img src="https://avatars.githubusercontent.com/u/12223900?v=4" width="64px;"alt="Mehdi BHA"/><br/><sub><b>Mehdi BHA</b></sub></a></td>
</tr></table>

[contributors-shield]: https://img.shields.io/github/contributors/Mehdi-BHA/notionfolio.svg?style=for-the-badge
[contributors-url]: https://github.com/Mehdi-BHA/notionfolio/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Mehdi-BHA/notionfolio.svg?style=for-the-badge
[forks-url]: https://github.com/Mehdi-BHA/notionfolio.svg/network/members
[stars-shield]: https://img.shields.io/github/stars/Mehdi-BHA/notionfolio.svg?style=for-the-badge
[stars-url]: https://github.com/Mehdi-BHA/notionfolio.svg/stargazers
[issues-shield]: https://img.shields.io/github/issues/Mehdi-BHA/notionfolio.svg?style=for-the-badge
[issues-url]: https://github.com/Mehdi-BHA/notionfolio.svg/issues
[license-shield]: https://img.shields.io/github/license/Mehdi-BHA/notionfolio.svg?style=for-the-badge
[license-url]: https://github.com/Mehdi-BHA/notionfolio.svg/blob/master/LICENSE.txt
