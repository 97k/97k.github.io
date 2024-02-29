<div align="center">
  <img alt="Logo" src="https://github.com/97k/97k.github.io/blob/source/src/images/logo.png" width="100" />
</div>
<h1 align="center">
  techyaditya.xyz - Aditya's Digital Garden
</h1>
<p align="center">
  <a href="https://techyaditya.xyz" target="_blank">techyaditya.xyz</a> built with <a href="https://www.gatsbyjs.org/" target="_blank">Gatsby</a> and hosted with <a href="https://pages.github.com/" target="_blank">Github Pages</a>
</p>
<p align="center">
  <a href="https://github.com/97k/97k.github.io/actions/workflows/pages/pages-build-deployment" target="_blank">
    <img src="https://github.com/97k/97k.github.io/actions/workflows/pages/pages-build-deployment/badge.svg" alt="Github Build Status" />
  </a>
</p>

![demo](https://github.com/97k/97k.github.io/blob/source/src/images/demo.png)

## 🚨 Forking this repo (please read!)

Many people have contacted me asking me if they can use this code for their own website, and the answer to that question is usually **yes, with attribution**.

This site is not built with the intention of being a starter theme, so if you have questions about implementation, please refer to the [Gatsby docs](https://www.gatsbyjs.org/docs/).

I have revised this from [brittanychiang.com](https://brittanychiang.com). Thanks to Brittany for publishing the source!

### TL;DR

Yes, you can fork this repo. Please give proper credit by linking back to [brittanychiang.com]. Thanks!

## 🛠 Installation & Set Up

1. Install the Gatsby CLI

   ```sh
   npm install -g gatsby-cli
   ```

2. Install and use the correct version of Node using [NVM](https://github.com/nvm-sh/nvm) and update the dependencies in package.json

   ```sh
   nvm install
   ```

3. Install dependencies

   ```sh
   npm install 
   ```

4. Start the development server

   ```sh
   gatsby develop
   ```

## 🚀 Building and Running for Production

1. Generate a full static production build

   ```sh
   gatsby build
   ```

1. I have deployed the website via github pages

   ```sh
   npm install gh-pages
   ```

   [Follow the github-pages deployment docs by gatsby](https://www.gatsbyjs.com/docs/how-to/previews-deploys-hosting/how-gatsby-works-with-github-pages/)

## 💡 Tips and Tricks

  ### Updating the logo
  The logo is made via svg, so you need to update [logo.js](https://github.com/97k/97k.github.io/blob/source/
  src/components/icons/logo.js)

  ### Tweaks
  Brittany has done a magnificient job in writing clean code, I am a python guy and new to gatsby js, it took me a while to understand the internsals and hence I am writing my two cents which will save your time in figuring out what to change and where.

  - Follow this [tutorial series by NetNinja](https://www.youtube.com/playlist?list=PL4cUxeGkcC9hw1g77I35ZivVLe8k2nvjB) if you literally don't have any idea and want to replicate, this will teach you the project structure and how gatsby as SSR is solving a big problem in the industry.
  - run `gatsby clean` and re-reun `gatsby develop` as sometimes the change you have done is correct but have not reflected on the website
  - Deploy with github pages, latest gh-pages doesn't have problem with SSR local images
  - Make custom thumbains with Adobe Express / Canva
  - Be unique and use your mind and AI to write clean content
  - If you have any queries feel free to reach out to me!

## 🎨 Color Reference

| Color          | Hex                                                                |
| -------------- | ------------------------------------------------------------------ |
| Navy           | ![#0a192f](https://via.placeholder.com/10/0a192f?text=+) `#0a192f` |
| Light Navy     | ![#112240](https://via.placeholder.com/10/0a192f?text=+) `#112240` |
| Lightest Navy  | ![#233554](https://via.placeholder.com/10/303C55?text=+) `#233554` |
| Slate          | ![#8892b0](https://via.placeholder.com/10/8892b0?text=+) `#8892b0` |
| Light Slate    | ![#a8b2d1](https://via.placeholder.com/10/a8b2d1?text=+) `#a8b2d1` |
| Lightest Slate | ![#ccd6f6](https://via.placeholder.com/10/ccd6f6?text=+) `#ccd6f6` |
| White          | ![#e6f1ff](https://via.placeholder.com/10/e6f1ff?text=+) `#e6f1ff` |
| Green          | ![#64ffda](https://via.placeholder.com/10/64ffda?text=+) `#64ffda` |
