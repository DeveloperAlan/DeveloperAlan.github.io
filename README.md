<h1 align="center">
  DeveloperAlan's Portfolio website
</h1>

<p align="center">
  <a href="https://github.com/LekoArts/gatsby-starter-portfolio-cara/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="Gatsby Starter Portfolio: Cara is released under the MIT license." />
  </a>
  <a href="https://twitter.com/intent/follow?screen_name=DeveloperAlan">
    <img src="https://img.shields.io/twitter/follow/DeveloperAlan.svg?label=Follow%20@DeveloperAlan" alt="Follow @DeveloperAlan" />
  </a>
  <a href="https://app.netlify.com/sites/portfolio-cara/deploys">
      <img src="https://api.netlify.com/api/v1/badges/88bbaef1-6f83-4894-8acd-e6512ff39265/deploy-status" alt="Netlify Status" />
    </a>
</p>

My portfolio based on the Gatsby Theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara).

[**Demo Website**](https://cara.lekoarts.de)

Also be sure to checkout other [Free & Open Source Gatsby Themes](https://themes.lekoarts.de)

## ✨ Features

- Theme UI-based theming
- react-spring parallax effect
- CSS Animations on Shapes

## 🚀 Getting Started

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/LekoArts/gatsby-starter-portfolio-cara) [![Edit gatsby-starter-portfolio-cara](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/github/LekoArts/gatsby-starter-portfolio-cara/tree/master/)

1. **Create a Gatsby site.**

Use the Gatsby CLI to create a new site, specifying this project

```sh
gatsby new project-name https://github.com/LekoArts/gatsby-starter-portfolio-cara
```

2. **Start developing.**

Navigate into your new site's directory and start it up.

```sh
cd project-name
gatsby develop
```

3. **Open the code and start customizing!**

Your site is now running at `http://localhost:8000`!

If you want to learn more about how you can use a Gatsby starter that is configured with a Gatsby theme, you can checkout this [shorter](https://www.gatsbyjs.org/docs/themes/using-a-gatsby-theme/) or [longer](https://www.gatsbyjs.org/tutorial/using-a-theme/) tutorial. The tutorials don't exactly apply to this starter however the concepts are the same.

## 📝 Using and modifying this starter

This starter creates a new Gatsby site that installs and configures the theme [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara).

Please have a look at the theme's README and files to see what options are available and how you can shadow the various components including Theme UI.

### Changing content

The content of this project is defined in four `.mdx` files inside the theme's `sections` folder. You can override the files `intro.mdx`, `projects.mdx`, `about.mdx` and `contact.mdx`. This starter has overriden the `intro.mdx` file as an example. Place the other files in the same `src/@lekoarts/gatsby-theme-cara/sections/` folder.

You have to use the `<ProjectCard />` component inside `projects.mdx` to display the cards. Example:

```md
## Projects

<ProjectCard title="Freiheit" link="https://www.behance.net/gallery/58937147/Freiheit" bg="linear-gradient(to right, #D4145A 0%, #FBB03B 100%)">
This project is my entry to Adobe's #ChallengeYourPerspective contest.
</ProjectCard>
```

### Change your `static` folder

The `static` folder contains the icons, social media images and robots.txt. Don't forget to change these files, too!

### Modifying components & this starter

Please have a look at [`@lekoarts/gatsby-theme-cara`](https://github.com/LekoArts/gatsby-themes/tree/master/themes/gatsby-theme-cara)'s README to see how you can change/shadow components. Generally speaking you will want to place your files into `src/@lekoarts/gatsby-theme-cara/` to shadow/override files.

## 🤔 Questions or problems?

Please open up an issue on the main repository: [LekoArts/gatsby-themes](https://github.com/LekoArts/gatsby-themes). Thanks!