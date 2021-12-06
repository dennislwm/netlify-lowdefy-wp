# netlify-lowdefy-wp

[![Netlify Status](https://api.netlify.com/api/v1/badges/8446944d-d95a-4280-88d2-cd554e733054/deploy-status)](https://app.netlify.com/sites/wp-lowdefy/deploys)

**netlify-lowdefy-wp** starter project.

# Deploy to Netlify

Lowdefy apps can be deployed to **Netlify**. Netlify integrates with `git` providers to automatically deploy your app when you merge changes into the main branch of your repository and deploy previews of pull requests.

<details>
    <summary>Click here to <strong>deploy to Netlify</strong></summary>

**Step 1**

Your project will need to be hosted as a **GitHub** repository.

**Step 2**

Link your GitHub project to Netlify.

* Once logged in to Netlify, click the "**New site from git**" button.
* Choose GitHub, and authorize Netlify to access your repositories.
* Select your repository.
If your repository isn't found, click "**Configure Netlify on Github**", and give Netlify access to your repository.

**Step 3**

Configure your Netlify deployment.

* Set your build command to `npx lowdefy@3 build-netlify`.
* Set your publish directory to `.lowdefy/publish`.

**Step 4**

Configure the Lowdefy server.

* Click the "**Advanced build settings**" button.
* Set the functions directory to `.lowdefy/functions`.

**Step 5**

Deploy your site.

* Click "Deploy site"
On the "**Site overview**" tab you will find your site url.

**Step 6**

* To set Lowdefy secrets, go to "**Site settings**", then "**Build and deploy**" in the left menu. 
* Scroll down and select "**Edit variables**" in the "**Environment**" section. Here you can set the `LOWDEFY_SECRET_` environment variables.
</details>

# Requirements

* [Node.js 12+](https://nodejs.org/en/download/)

# Getting Started

