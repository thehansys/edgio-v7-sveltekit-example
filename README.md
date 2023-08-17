# Deploy Sveltekit example to Edgio v7

A demo deployment of Sveltekit app to Edgio v7 platform. 
This project is using the experimental version **7.1.2-next-1692303882-f106e67.0** of Edgio packages with ESM support. 
Please note that this version is still in testing and has not been released officially yet.

## Deployed demo of this project

Edge: https://edg-test-edgio-v7-sveltekit-example-default.edgio.link/

## Getting Started

### Clone This Repo

Use `git clone https://github.com/thehansys/edgio-v7-sveltekit-example` to get the files within this repository onto your local machine.

### Install dependencies

On the command line, in the project root directory, run the following command:

```bash
npm install
```
Optionally, you can install the CLI package globally by running:
```bash
npm install -g @edgio/cli
```

### Run the Sveltekit app locally on Edgio

Run the Sveltekit app with the command:

```bash
npx edgio dev
```

Load the site: http://127.0.0.1:3000

### Testing production build locally with Edgio

You can do a production build of your app and test it locally using:

```bash
npx edgio build
npx edgio run -p
```

Setting --production runs your app exactly as it will be uploaded to the Edgio cloud using serverless-offline.

## Deploying to Edgio

Deploying requires an account on Edgio. [Sign up here for free](https://edgio.app/signup). Once you have an account, you can deploy to Edgio by running the following in the root folder of your project:

```bash
npx edgio deploy
```

See [deploying](https://docs.edg.io/guides/v7/basics/deployments) for more information.
