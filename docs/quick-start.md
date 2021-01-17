# Quick Start

> In order create your own Docsify-enabled static site, you need internet access.

## Requirements

We (`@alertbox`) used [Quickstart](https://github.com/alertbox/vscode-remote-try-docsify/generate/) for some of our static sties of all sort. First, you will need the followings to get started at the most basic level:

- A GitHub account
- Git
- VS Code and Remote - Container extension
- Docker Desktop, and
- Markdown editor, like Paper app

For new projects, luckily, we have enabled [Quickstart](https://github.com/alertbox/vscode-remote-try-docsify/generate/) as a Template repository so you can simply Docsify yourself without having to install any tools and dependencies via `npm` or `yarn`. You will want to follow this generic pattern:

- [Use this template](#use-this-template) to create a copy
- [Preview locally](#preview-locally) to keep writing content
- Do some [final touches](#final-touches) to make it yours

## Use This Template

First, you will have to create a GitHub account if you don't have one already. [GitHub's Learning Lab](https://lab.github.com/) is a good source of information. Sign in to GitHub using your credentials, otherwise.

Next, you want to create a copy of this repository. It is marked as a `Template` so you will only have to [Use This Template](https://github.com/alertbox/vscode-remote-try-docsify/generate/) and follow the instructions. Read more about this in [the GitHub's Template Repositories](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) document.

That's it. You now have a Docsify-enabled minimal GitHub repo, and is ready to preview locally.

## Preview Locally

Once you obtain your own copy of the repository, you will have to download the artifacts. Typically that is done using the Terminal, that is Command Prompt if you are a Windows user. Luckily, even if you are not familiar, these steps should be pretty easy to follow. [Git or GitHub CLI](https://try.github.io/) is a good source of information.

First, spin up a Terminal and clone the newly created repository. For example, we will use one of our contributors, [@kosalanuwan](https://github.com/kosalanuwan), to keep the conversation alive.

```zsh
#!/bin/zsh
gh repo clone kosalanuwan/vscode-remote-try-docsify
code vscode-remote-try-docsify/
```

You will want to replace `kosalanuwan` with your username or your organization handler name if that's where you created the repository, and `vscode-remote-try-docsify` is the name he has given when [Using This Template](#use-this-template). You will want to replace that too with the name you have given.

Then, you can have a look at this site locally. In order to do this, you will have to use [VS Code Remote - Container extension](https://github.com/kosalanuwan/devcontainers). But you will not have to do anything other than following with VS Code:

- Run task: `Reopen in Container`
- Press `F5` to preview locally

That's it. Go to your favorite browser and visit [localhost:3000](http://localhost:3000).

<p align="center">
  <img alt="The quickstart template markdown in action" src="https://user-images.githubusercontent.com/958227/104834940-19d51d80-58c9-11eb-9543-e3a5a1ca57b4.png" width="786">
</p>

## Final Touches

Once the project is up and running, you will want to tweak its content as you wish, for obvious reasons:

- Replace the repository paths to yours. Find and replace all `alertbox/vscode-remote-try-docsify`, for example: `kosalanuwan/vscode-remote-try-docsify`.
- Then replace the remaining repository names to yours. Find and replace all occurrences of `vscode-remote-try-docsify`.
- Next, replace the website name to your site name. Find and replace all `Quickstart`, for example: `My Awesome Docsify`
- Replace all the screenshots too

Next, refresh the browser, navigate around the site to see your updated content. [Docsify's Quick start](https://docsify.js.org/#/quickstart) guide is a good source of information to further tweak your site.
