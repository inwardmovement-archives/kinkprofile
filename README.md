## KinkProfile
[kinkprofile.netlify.app](https://kinkprofile.netlify.app/)  
A spreadsheet to share one's kinks

> Inspired by [Goctionni/KinkList](https://github.com/Goctionni/KinkList)

## To develop locally
- Install [Hugo](https://gohugo.io/getting-started/installing#binary-cross-platform) (see version in [workflow file](/.github/workflows/ci-cd-develop.yml#L10))
- Install [Node.js via nvm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) (see version in [workflow file](/.github/workflows/ci-cd-develop.yml#L11))
  - On Windows:
    - Install [nvm-windows](https://github.com/coreybutler/nvm-windows#installation--upgrades)
    - Run `nvm install [Node.js version]` (in an Admin shell)
    - Run `nvm use [Node.js version]` (in an Admin shell)
  - On OSX and Linux:
    - Install [nvm](https://github.com/nvm-sh/nvm#installation-and-update)
    - Run `nvm install [Node.js version]`
    - Run `nvm use [Node.js version]`
- Install dependencies: `npm i`
- Install [PostCSS CLI](https://github.com/postcss/postcss-cli) and [Autoprefixer](https://github.com/postcss/autoprefixer) globally: `npm i -g postcss-cli autoprefixer`
- Clone the repo and run `npm start` from root
