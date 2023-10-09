# daviswhitehead.com-ghost

This is a custom ghost theme for entrepreneurs. It powers daviswhitehead.com and acts as a portfolio that allows you to highlight products & services alongside your writing.

**Demo: daviswhitehead.com**

# Instructions

1. [Download this theme](https://github.com/TryGhost/Solo/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/solo.zip`, which you can then upload to your site.

```bash
yarn zip
```

## Resources

https://ghost.org/tutorials/local-ghost/#install-ghost-locally
https://www.npmjs.com/package/@tryghost/shared-theme-assets?activeTab=readme
https://ghost.org/tutorials/build-css-files/

## Process for cloning templates

- Download the template
- Find the section in the code using developer tools
- Iteratively clone each file and put it in its own folder
- Prefix all new css with template your cloning from

# Contribution

This repo is synced automatically with [TryGhost/Themes](https://github.com/TryGhost/Themes) monorepo. If you're looking to contribute or raise an issue, head over to the main repository [TryGhost/Themes](https://github.com/TryGhost/Themes) where our official themes are developed.

## Copyright & License

Copyright (c) 2013-2023 Ghost Foundation - Released under the [MIT license](LICENSE).
