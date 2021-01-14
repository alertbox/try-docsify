# Try out Docsify-enabled static site

[![docsify](https://img.shields.io/badge/maintained%20with-docsify-cc00ff.svg)](https://docsify.js.org/)
![GitHub repo size](https://img.shields.io/github/repo-size/alertbox/vscode-remote-try-docsify)

This repository demonstrates developing a Docsify-enabled static site using Markdown and Development Containers. 

<p align="center">
  <img alt="The gh-quickstart in action" src="https://user-images.githubusercontent.com/958227/84496654-f1e66180-acca-11ea-8aa9-8b78ac53b4b2.png" width="1024">
</p>

> The docsify-enabled site in action.

### What's included:
- Uses node development container found in [@kosalanuwan/devcontainers](https://github.com/kosalanuwan/devcontainers)
- Uses [@docsifyjs/docsify-cli](https://github.com/docsifyjs/docsify-cli) latest version for serving static site
- Configured to build and run from VS Code
- Contains boilerplate docs for a quick preview

## Requirements
See [@kosalanuwan/devcontainers](https://github.com/kosalanuwan/devcontainers) repository to get started at the most basic level, and:
- A [Markdown](https://guides.github.com/features/mastering-markdown/) editor, the lightweight and easy-to-use syntax for all forms of writing on GitHub platform.

## Quick Start
If you are completely new to docsify, the [Quick Start guide](https://alertbox.github.io/vscode-remote-try-docsify/#/quick-start) is a good source of information.

### Build and run from source
First, you want a copy of this repo. It is marked as a `Template` so you will only have to [Use This Template](https://github.com/alertbox/vscode-remote-try-docsify/generate/) and follow the instructions. Read more about this in [the GitHub's Template Repositories](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template) document.

Next is clone the repo, then open in VS Code. You can  use [@github/cli](https://cli.github.com/) for this.
```
#!/bin/zsh
gh repo clone kosalanuwan/vscode-remote-try-docsify
code vscode-remote-try-docsify/
```
Then, re-open the source in development container to install minimal required setup for you.

With VS Code:
- Run task: `Reopen in Container`
- Press `F5` to to preview locally

## Feedback
If you have any technical problems with Docsify, you are better off [asking Docsify Support directly](https://gitter.im/docsifyjs), since you'll end up getting a much faster response back that way.

## Contributing
The official repo to contribute would be [@docsifyjs/docsify](https://github.com/docsifyjs/docsify).

## License
Copyright &copy; Alertbox Inc. All rights reserved.

The source code is license under the [MIT License](LICENSE).
