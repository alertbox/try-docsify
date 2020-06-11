# Quick Start

> In order create your own Docsify-enabled GitHub repository, you need internet access.

## Requirements

We (`@alertbox`) use `gh-quickstart` for our GitHub Pages and documentation sites of all sort when using Docsify. First, you will need followings to get started at the most basic level:

- A GitHub account
- An editor, like VS Code
- Git, and
- Docker Desktop

For new projects, luckily, we have enabled [gh-quickstart](https://github.com/alertbox/gh-quickstart/generate/) as a GitHub Template so you can simply Docsify yourself without having to install any tools and dependencies via `npm` or `yarn`. You will want to follow this generic pattern:

- [Use this template](#use-this-template) to create a copy
- [Preview locally](#preview-locally) to keep writing content
- Do some [final touches](#final-touches) to make it yours

## Use This Template

First, you will have to create a GitHub account if you don't have one already. [GitHub Guide]() is a good source of information. Sign in to GitHub using your credentials, otherwise.

Next, you want to create a copy of this source code. The `gh-quickstart` is marked as a `Template` repository so you will only have to [Use This Template](https://github.com/alertbox/gh-quickstart/generate/) and follow the instructions. Read more about this in the [Using GitHub Templates]() document.

That's it. You now have a Docsify-enabled minimal GitHub repo, and is ready to preview locally.

## Preview Locally

Once you have your copy of GitHub Quick Start source code, you will have to download the artifacts. Typically that is done using the Terminal, that is Command Prompt if you are a Windows user. Luckily, even if you are not familiar, these steps should be pretty easy to follow. [GitHub's Guide to install Git]() is a good source of information.

First, spin up a Terminal and clone the newly created repository. For example, we will use one of our contributors, [@kosalanuwan](https://github.com/kosalanuwan), to keep the conversation alive.

```bash
git clone https://github.com/kosalanuwan/my-awesome-docsify
```

You will want to replace `kosalanuwan` with your username or your organization handler name if that's where you created the repository, and `my-awesome-docsify` is the name he has given when [Using This Template](#use-this-template). You will want to replace that too with the name you have given.

Then, you can have a look at this site locally. In order to do this, you will have to use [Docsify Served](https://alertbox.github.io/docsify-served). But you will not have to do anything other than following:

```bash
cd my-awesome-docsify
docker-compose up -d
```

That's it. Go to your favorite browser and visit [localhost:8020](https://localhost:8020).

<p align="center">
  <img alt="The template markdown in action" src="https://user-images.githubusercontent.com/958227/84351159-6b515780-abd8-11ea-8a28-cb5524eb1e6e.png" width="786">
</p>

## Final Touches

Once the project is up and running, you will want to tweak its content as you wish, for obvious reasons:

- Replace the repository paths to yours. Find and replace all `alertbox/gh-quickstart`, for example: `kosalanuwan/my-awesome-docsify`
- Then replace the remaining repository names to yours. Find and replace all occurrences of `gh-quickstart`, for example: `my-awesome-docsify`
- Next, replace the website name to your site name. Find and replace all `GitHub Quick Start`, for example: `My Awesome Docsify`
- Replace all the screenshots too

Next, refresh the browser, navigate around the site to see your updated content. [Docsify's Getting Started]() guide is a good source of information to further tweak your site.
