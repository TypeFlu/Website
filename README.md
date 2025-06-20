# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.
## Status
[![Netlify Status](https://api.netlify.com/api/v1/badges/bb54def6-9a1b-4c50-8d43-d79973ea26c7/deploy-status)](https://app.netlify.com/projects/sukisuweb/deploys)

## Installation

```bash
yarn
```

## Local Development

```bash
yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

## Build

```bash
yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

## Deployment

Using SSH:

```bash
USE_SSH=true yarn deploy
```

Not using SSH:

```bash
GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
