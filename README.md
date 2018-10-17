# Ruby on Rails App with GitHub Actions and Pulumi ⚡️

A simple Ruby on Rails App, deployed to Kubernetes using GitHub Actions and Pulumi! ☁️

![Architecture](./arch.png)

This leverages Pulumi's GitHub Actions support for deploying any cloud application and infrastructure to
your cloud of choice. In this particular example, we're deploying to Google Cloud Platform, but it supports
AWS, Azure, and even on-premises too. Read more on
[pulumi.io's GitHub Actions Getting Started page](https://pulumi.io/github).

## Running the Example

To use this, simply perform these steps:

1. Fork this repo.
2. Register for Pulumi, and download the CLI.
3. Run `pulumi stack init` to create a new stack which we'll deploy into.
4. Configure your `PULUMI_ACCESS_TOKEN` and `GOOGLE_CREDENTIALS`, per [the instructions over on pulumi.io](https://pulumi.io/github).

Commit or open a PR, and watch GitHub Actions plus Pulumi work its magic! ✨
