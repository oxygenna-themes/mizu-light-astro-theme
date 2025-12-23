# Mizu Light Astro Theme

Mizu Light is a product launch template designed specifically for modern SaaS products, digital launches, and ambitious startups. Perfect for landing pages, beta signups, and early access campaigns.

![mizu](https://oxygenna-themes.b-cdn.net/mizu-light-astro/mizu-light-02.jpg)

[![View live Demo](https://oxygenna-themes.b-cdn.net/mizu-astro/demo-button.svg)](https://mizu-light-theme.netlify.app/) [![Page Speed Insights (100%)](https://oxygenna-themes.b-cdn.net/mizu-astro/button-pagespeed.svg)](https://pagespeed.web.dev/analysis/https-mizu-light-theme-netlify-app/r1kw15xyy9?form_factor=desktop)

## Introduction

### About

Mizu Light is a product launch template designed for modern SaaS companies, digital products, and ambitious startups. With its clean design, intuitive layout, and focus on user experience, it’s the perfect solution for promoting beta programs, early access signups, or pre-launch campaigns.

### Features

- **Pre-Built Pages:** Get started quickly with a full set of professionally designed pages, ready to launch right out of the box.
- **Optimized 100/100 PageSpeed:** Mizu Light is built for speed, delivering lightning-fast load times and perfect scores on Google PageSpeed.
- **Flexible Modular Blocks:** Every page is made from reusable, flexible blocks—easily add, rearrange, or expand content using our ever-growing library.
- **Reusable UI Components:** Keep your design consistent and save time with a complete set of customizable, reusable components.
- **Built with Astro v5 & Tailwind CSS v4:** Harness the latest frameworks for blazing-fast development and modern, utility-first styling.
- **Light & Dark Mode:** Let users switch seamlessly between light and dark themes for a fully customizable experience.
- **SEO-Ready:** Crafted with clean, semantic HTML and optimized metadata to help your site rank higher in search engines.
- **Content Collections:** Organize, manage, and display content efficiently with Astro’s powerful content collections system.
- **Smooth Animations:** Enhance the user experience with subtle transitions and page effects.
- **Analytics Ready:** Supports Google Analytics and Tag Manager for easy tracking and insights.
- **Responsive Design:** Fully responsive across desktops, tablets, and mobile devices.

## Getting Started

### Commands

After downloading the theme, install the dependencies and run it on your local server. Check the `package.json` file for available scripts.

> **Note**: Requires Node.js version 20.3.0 or later.

| Command           | Action                                       |
| :---------------- | :------------------------------------------- |
| `npm install`     | Installs dependencies                        |
| `npm run dev`     | Starts local dev server at `localhost:4321`  |
| `npm run build`   | Build your production site to `./dist/`      |
| `npm run preview` | Preview your build locally, before deploying |

### Folder structure

Inside Toki Astro project, you'll see the following folders and files:

```plaintext
/
├── public/
│   └── favicon.svg
├── src/
│   ├── assets/
│   ├── components/
│   │   ├── blocks/
│   │   │   └── ...
│   │   ├── scripts/
│   │   │   └── ...
│   │   └── ui/
│   │       └── ...
│   ├── config/
│   │   └── ...
│   ├── content/
│   │   └── blog/
│   ├── data/
│   │   └── ...
│   ├── icons/
│   │   └── ...
│   ├── layouts/
│   │   └── ...
│   └── pages/
│       └── ...
└── package.json
```

| Directory/File           | Description                                                                                                                        |
| ------------------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| `public/`                | Contains static assets like images and the favicon. These files are served directly at the root URL.                               |
| `src/assets/`            | Contains all images and assets used in the project.                                                                                |
| `src/components/`        | Contains reusable components for your site. This directory is divided into `ui` for UI components and `blocks` for section blocks. |
| `src/components/blocks/` | Contains Section blocks used throughout the site.                                                                                  |
| `src/components/ui/`     | Contains individual UI components.                                                                                                 |
| `src/config/`            | Contains configuration files for the project in typescript format.                                                                 |
| `src/content/`           | Holds collection data, such as case studies.                                                                                       |
| `src/data/`              | Contains JSON files with content data (like features, testimonials etc).                                                           |
| `src/icons/`             | Contains all icons used in the project, most are sourced from [Heroicons](https://heroicons.com/).                                 |
| `src/layouts/`           | Contains layout components that define the overall structure of your pages.                                                        |
| `src/pages/`             | Contains `.astro` files for each page. Each file here is exposed as a route based on its file name.                                |
| `package.json`           | Lists dependencies and scripts for your project, including metadata and various package requirements.                              |

## Theme Configuration

The configuration files are located in the `src/config` directory, written in TypeScript. They contain various settings for the theme, including:

| Configuration Files        | Description                                                              |
| -------------------------- | ------------------------------------------------------------------------ |
| `src/config/config.ts`     | Basic configuration settings including SEO, mode, and scroll animations. |
| `src/config/navigation.ts` | Menu TypeScript interface options and JSON files for navigation.         |
| `src/config/analytics.ts`  | Analytics configuration file.                                            |

## Theme Customization

### Customize the Colors

The theme uses two main colors: primary and neutral. These colors are defined in the Tailwind CSS configuration file. To personalize the color scheme of your project, you can easily modify these color values.

To customize the colors, follow these steps:

1. Open the `global.css` file.
2. Find the `theme` section within the file.
3. Under `theme`, locate the `Colors`.
4. Modify the color values for `primary` and `neutral` to suit your preferred color palette.

You can use the [tailwind CSS colors](https://nodejs.org/en/download/) or create your [own palette](https://uicolors.app/create) .

### Customize the Fonts

To customize the fonts used in your project, follow these steps:

1. **Add Your Custom Font Files**
   Replace or add the desired font files in the public directory of your project.

2. **Update the Tailwind CSS Configuration**

   Open the `global.css` file. In the `@font-face` section, find the `font-family` property and update the `font-family` object.

### Dark/Light Mode

By default, the site uses forced modes, which can be either light or dark, depending on the chosen layout. The light layout sets the class to **`mode-light`** and the dark layout sets it to **`mode-dark`**. This setting allows you to maintain a fixed appearance across the site regardless of user preferences or system settings.

However, if you want to give users the ability to switch between themes, you can configure the theme to use the **`mode-auto`** class. You can easily do this by adding the **`mode-auto`** class to the **`src/layouts/Layout.astro`** file instead of using **`mode-light`** or **`mode-dark`** and uncommenting the ThemeSwitcher component in the NavigationBar component.

## Want more themes?

### Mizu

Check out **Mizu**, a product launch template, it comes with 13 pre-built pages—and more on the way—making it easy to showcase your product and get started quickly.

![mizu](https://oxygenna-themes.b-cdn.net/mizu-astro/mizu-theme.png)

[![Get Mizu](https://oxygenna-themes.b-cdn.net/mizu-astro/primary-button-get-mizu.svg)](https://astro.build/themes/details/mizu/)
[![View live Demo](https://oxygenna-themes.b-cdn.net/mizu-astro/secondary-button-mizu-demo.svg)](https://mizu-theme.netlify.app/)

### Toki

Check out **Toki**, a standout agency template with striking design, blazing speed, built for modern agencies and creatives.

![toki-theme](https://oxygenna-themes.b-cdn.net/toki-astro/promo/toki-theme-promo.png)

[![Get Toki](https://oxygenna-themes.b-cdn.net/toki-astro/promo/primary-button-get-toki.svg)](https://astro.build/themes/details/toki/)
[![View live Demo](https://oxygenna-themes.b-cdn.net/toki-astro/promo/secondary-button-toki-demo.svg)](https://toki-theme.netlify.app/)

### Foxi Pro

Check out **Foxi Pro**, our premium Astro website template with fully responsive, customizable Tailwind CSS components.

![foxi-pro](https://oxygenna-themes.b-cdn.net/foxi-pro-astro/foxi-pro.png)

[![Get Foxi Pro](https://oxygenna-themes.b-cdn.net/foxi-pro-astro/primary-button-get-foxi-pro.svg)](https://astro.build/themes/details/foxi-pro/)
[![View live Demo](https://oxygenna-themes.b-cdn.net/foxi-pro-astro/secondary-button-foxi-pro-demo.svg)](https://foxi-pro.netlify.app)

## License

Copyright 2026 - Designed & Developed by [Oxygenna](http://www.oxygenna.com/)

[![Hire Us](https://oxygenna-themes.b-cdn.net/foxi-astro/hireus.png)](mailto:themes@oxygenna.com,christos@oxygenna.com)
