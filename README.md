# Tryout Docsify

[![docsify](https://img.shields.io/badge/maintained%20with-docsify-cc00ff.svg)](https://docsify.js.org/)
![GitHub repo size](https://img.shields.io/github/repo-size/alertbox/devcontainers-try-docsify)

This repo serves as a ready-to-go docsify template that requires no build steps.

<p align="center">
  <img alt="The docsify site in action" src="Screenshot.png" width="1024">
</p>


> The dead simple docsify template in action.

### What's included:

Technically, this includes nothing but:

- A simple template found in [@docsifyjs/docsify-template][docsify-template-repo] repo, and
- Configured to preview locally

[docsify-template-repo]: https://github.com/docsifyjs/docsify-template

## Requirements

See [Docker dev environments][docker-dev-envs-overview] to get started at the most basic level, and:
- A GitHub account, and
- A [Markdown][github-markdown-guides] editor, like [Typora][typora-install], a lightweight and easy-to-use syntax for all forms of writing on the GitHub platform

[docker-dev-envs-overview]: https://docs.docker.com/desktop/dev-environments/
[github-markdown-guides]: https://guides.github.com/features/mastering-markdown/
[typora-install]: https://www.typora.io/

## Quick Start

If you are completely new to docsify, the [Quick Start guide][docsify-quick-start] is a good source of information.

Just upload the files to any static web server. Or follow this generic pattern:

First, you want a copy of this repo. It is marked as a `Template` so you will only have to [Use this template][use-this-template] and follow the instructions. Read more about this in [the GitHub's Template Repositories][github-template-repos-help] document.

Then, you can [write more contents][docsify-write-more] and preview on [localhost:3000](http://localhost:3000). Just run `docker compose -f compose-dev.yaml -d` in the repo.

That's it!

[docsify-quick-start]: https://docsify.js.org/#/quickstart
[use-this-template]: https://github.com/alertbox/devcontainers-try-docsify/generate/
[github-template-repos-help]: https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template
[docsify-write-more]: https://docsify.js.org/#/more-pages

## Feedback
If you have any technical problems with Docsify, you are better off [asking Docsify Support directly][docsify-support], since you'll end up getting a much faster response back that way.

[docsify-support]: https://discord.gg/3NwKFyR

## Contributing
The official repo to contribute would be [@docsifyjs][docsify-github].

[docsify-github]: https://github.com/docsifyjs

## License
Copyright (c) Alertbox Inc. All rights reserved.

The source code is license under the [MIT License](LICENSE).
