# Highland Group RDA Website 🐴

Welcome to the official website project for the **Highland Group Riding for the Disabled Association (RDA)**! This site is lovingly crafted with [Astro](https://astro.build) to help share our mission and connect with our community.

Our goal is to showcase the wonderful work we do enriching lives through horses in the Highlands.

## 🚀 Project Structure

Here's a map of our digital stables:

```text
/
├── public/               # Static assets (images, fonts, etc.)
│   ├── assets/
│   │   └── img/          # Site images
│   └── favicon.ico       # Site favicon
├── src/
│   └── pages/
│       └── index.astro   # Main homepage
├── astro.config.mjs      # Astro configuration
├── package.json          # Project dependencies and scripts
├── tsconfig.json         # TypeScript configuration
└── README.md             # This file
```

Our Astro site looks for `.astro` or `.md` files in the `src/pages/` directory. Each page becomes a route based on its file name – simple as that!

All our lovely images and other static bits and bobs live in the `public/` directory. Specifically, you'll find the site's images nestled in `public/assets/img/`.

## 🧞 Getting Started & Commands

Ready to saddle up and work on the site? All commands are run from the root of the project in your terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs all the necessary bits and pieces       |
| `npm run dev`             | Starts a local development server (usually at `localhost:4321`) |
| `npm run build`           | Prepares the site for its grand debut on the web! (builds to `./dist/`) |
| `npm run preview`         | Lets you take a peek at the built site locally before it goes live |
| `npm run astro ...`       | Handy for various Astro CLI tasks like `astro add` or `astro check` |
| `npm run astro -- --help` | Your go-to for help with the Astro CLI           |

## 👀 Curious about Astro?

If you want to learn more about the magic behind the scenes (that's Astro!), feel free to check out [their fantastic documentation](https://docs.astro.build) or say hello in their friendly [Discord server](https://astro.build/chat).

--- 

Thank you for contributing to the Highland Group RDA's online presence! 🎉
