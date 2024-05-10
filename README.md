# Docker extension for GitHub Copilot

> [!NOTE]
> The Docker extension for GitHub Copilot is current in a limited public beta, accessible by invitation only.

The Docker extension for GitHub Copilot (`@docker`) is a plugin that extends GitHub Copilot's technology to assist developers in working with Docker. 

This repository is for providing feedback and documentation on the [Docker extension for GitHub Copilot ](https://github.com/apps/docker) in GitHub Copilot Chat. You can use the repository to report issues or submit feature requests. 

# Quick Start

1. Install the [Docker GitHub App](https://github.com/apps/docker) in your organization.
1. Invoke the extension using `@docker` in any context where GitHub Copilot is available.

# Current Features

![](add url here)

- **Initiate a conversation with the Docker extension**: In GitHub Copilot Chat, get in the extension context by using `@docker` at the beginning of your session
Refer to documentation from your current context: Access [docs.docker.com](https://docs.docker.com) right from within Copilot Chat by asking questions like `“@docker, What does containerizing an application mean?”` or even `“@docker how can I start a container with a volume?”`

- **Generate the right Docker assets for your project**: Get help containerizing your application and watch it generate the `Dockerfile`s, `docker-compose.yml`, and `.dockerignore` files tailored to your project’s languages and file structure: `“@docker How would I use Docker to containerize this project?” `

- **Open a Pull Request with the assets to save you time**: With your consent, the Docker extension can even ask if you want to open a PR with these generated Docker assets on GitHub, allowing you to review and merge them at your convenience.

- **Find project vulnerabilities with Docker Scout**: The Docker extension also integrates with Docker Scout to surface a high-level summary of detected vulnerabilities and provide the next steps to continue using Scout in your terminal via CLI: `“@docker can you help me find vulnerabilities in my project?”`

See the [changelog](CHANGELOG.md) for the latest release.

# Troubleshooting

Known issues are documented in [TROUBLESHOOTING](TROUBLESHOOTING.md).

# Feedback

-   File a bug in [GitHub Issues](https://github.com/docker/copilot-issues/issues/new/choose)
-   [Tweet us](https://twitter.com/docker) with other feedback

# License

See [LICENSE](LICENSE) for more information.