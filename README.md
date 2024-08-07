<a name="readme-top"></a>

[![Stargazers][stars-shield]][stars-url]
[![MIT License][license-shield]][license-url]
[![Release][release-shield]][release-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/gaomingzhao666/nano-portfolio">
    <img src="/public/favicon.ico" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">AI Prompts</h3>

  <p align="center">
    💖 A list of useful and favorite AI/GPT prompts 💖
    <br />
    <br />
    <a href="https://github.com/gaomingzhao666/nano-portfolio/blob/master/README.md">English</a>
      <strong> · </strong>
    <a href="https://github.com/gaomingzhao666/nano-portfolio/blob/master/README-CN.md">简体中文</a>
      <strong> · </strong>
    <a href="https://github.com/gaomingzhao666/nano-portfolio/blob/master/README-JP.md">日本語</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details open>
  <summary>Directory</summary>
  <ul>
    <li><a href="#introduction-of-project">About The Project</a> </li>
    <li><a href="#build-with">Tech Stack</a></li>
    <li><a href="#build-with">Questions</a></li>
    <li><a href="#Runtime-requirement">Prerequisites</a></li>
    <li><a href="#how-to-run-this-application">Getting Started</a></li>
    <li><a href="#about-cors-error">References</a></li>
    <li><a href="#contributor">Contributor</a></li>
    <li><a href="#license">LICENSE</a></li>
  </ul>
</details>

<!-- ABOUT THE PROJECT -->

## Introduction of Project

<!-- IMAGE OF PROJECT -->

<p align="center">
    <img src="/SCREENSHOT/index-mockup.png">
</p>

> The image shown here is a about-page for laptop-size, [click here](https://github.com/gaomingzhao666/nano-portfolio/tree/main/SCREENSHOT) to see more detailed screenshot for this application.

Nano-portfolio is a developer introduction web application integrated with Github Octokit and Nuxt3 ecosystem that includes `Nuxt-UI` `Nuxt-Mongoose` `Pinia` `i18n` etc. All of the modules are officially compatible with Nuxt3, and all of the code inside of this project uses composition API and ESM.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Build With

- Nuxt3 with composition API
- Pinia
- Vite
- TailwindCSS
- Nuxt-UI
- MongoDB with Mongoose
- localize with i18n
- Typescript with ES6+ syntax
- Dockerfile

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Runtime Requirement

- NodeJS LTS 20+

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## How to run this application

### Clone this project

```sh
$ https://github.com/gaomingzhao666/nano-portfolio.git # clone the project
$ cd nano-portfolio
$ pnpm install # install dependencies that this project needs
$ pnpm dev # run
```

### Use a Dockerfile to Create a Container

1. Clone or download this project.
2. Ensure you have `Docker Desktop` installed on your computer.
3. Install the `Docker extension` in your `VScode`.
4. Right-click the `Dockerfile` in this project and select the `Build Image` option.
5. Open `Docker Desktop` and run the container.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## How to Use This Project for Your Case

### Overview

Utilize this completely open-source project, released under the MIT license, to create your own portfolio. It automatically imports information from your GitHub repositories and your profile using your GitHub account. Let's explore how!

### Quick Start

- [Generate a GitHub Personal Access Token](https://docs.github.com/en/enterprise-server@3.9/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens).
- Navigate to the `githubInfo.ts` file located in the `utils` folder within the `server` directory
- Replace the placeholder token with your own `Personal Access Token` to enable server-side APIs to return your GitHub information
- Update the data on the `About` and `Contact` pages with appropriate information
- Have fun and enjoy customizing your portfolio

## References

https://github.com/tc39/proposal-type-annotations/issues/176
https://stackoverflow.com/questions/16181295/i18n-for-static-html-content
https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Internationalization
http://i18njs.com/#simples_case
日本语：https://coliss.com/articles/build-websites/operation/css/css-reset-for-modern-browser.html

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributor

The project developed by gaomingzhao666@Nano

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## LICENSE

[MIT License](https://github.com/gaomingzhao666/nano-portfolio/blob/main/LICENSE)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[stars-shield]: https://img.shields.io/github/stars/gaomingzhao666/nano-portfolio?style=for-the-badge
[stars-url]: https://github.com/gaomingzhao666/nano-portfolio/stargazers
[license-shield]: https://img.shields.io/badge/license-MIT-green?style=for-the-badge
[license-url]: https://github.com/gaomingzhao666/nano-portfolio/blob/main/LICENSE
[release-shield]: https://img.shields.io/github/v/release/gaomingzhao666/nano-portfolio?style=for-the-badge
[release-url]: https://github.com/gaomingzhao666/nano-portfolio/releases
