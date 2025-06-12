<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome Dokku [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![lint](https://github.com/kot-behemoth/awesome-dokku/actions/workflows/lint.yaml/badge.svg)](https://github.com/kot-behemoth/awesome-dokku/actions/workflows/lint.yaml)

<!-- image -->

<a href="https://dokku.com/"><img src="https://dokku.com/assets/dokku-logo.svg" alt="Dokku Logo" align="left" style="margin-right: 25px" width=150></a>

<!-- description -->

[Dokku](https://dokku.com/) is an open source PAAS alternative to Heroku. Dokku helps you build and manage the lifecycle of applications from building to scaling.

</div>

<!-- TOC -->

## Contents

- [Official Resources](#official-resources)
- [Blogs & Tutorials](#blogs-tutorials)
- [Tools](#tools)
- [Contributing](#contributing)

<!-- CONTENT -->

## Official Resources

- [Dokku Documentation](https://dokku.com/docs/getting-started/installation/)
- [Official Plugins](https://dokku.com/docs/community/plugins/#official-plugins)
- [Community Plugins](https://dokku.com/docs/community/plugins/#community-plugins)
- [Dokku Tutorials](https://dokku.com/tutorials/)
- [app.json file format](https://dokku.com/docs/appendices/file-formats/app-json/) - `app.json` is a manifest format for describing web apps. It declares cron tasks, healthchecks, and other information required to run an app on Dokku.
- [.buildpacks file format](https://dokku.com/docs/appendices/file-formats/buildpacks-file/) - The `.buildpacks` file is used to specify the buildpacks for an application.
- [GitHub Discussions](https://github.com/dokku/dokku/discussions)
- [Gliderlabs Slack](https://slack.dokku.com/) (Join the `#dokku` channel) 
- [Dokku Discord](https://discord.gg/YQjANGMZvu)

## Blogs & Tutorials

- [How to self-host your app, the right way](https://ben-makes-stuff.beehiiv.com/p/selfhost-app-2024-right-way) - Comparison of Dokku vs Coolify, k3, Caprover. Covers basic Dokku deployment, as well as production security hardening with Cloudflare.
- [Dokku: my favorite personal serverless platform](https://hamel.dev/blog/posts/dokku/#static-sites) - Covers minimal Dokku examples, deploying with Github Actions, and various tips.
- [Deploying Ruby on Rails with Dokku (Redis, Sidekiq, ARM servers and Docker)](https://railsnotes.xyz/blog/deploying-ruby-on-rails-with-dokku-redis-sidekiq-arm-docker-hetzner) - "I've tried to put together the ultimate Dokku + Ruby on Rails guide. This guide covers all the basics— deploying to x86 and ARM machines, deploying Sidekiq and Redis, dockerizing our Rails app, adding post-deploy scripts, adding LetsEncrypt for SSL and HTTPS, adding backups to S3, and adding an automatic deploy script to GitHub."
- [Deploy Ghost blog with Dokku](https://okhlopkov.com/deploy-ghost-blog-with-dokku/) - Step-by-step guide on how to deploy production-ready & scalable Ghost.io blog with Dokku PaaS.

## Tools

- [aaronstillwell/terraform-provider-dokku](https://github.com/aaronstillwell/terraform-provider-dokku) - A terraform provider for provisioning applications on the Dokku.
- [pedropaf/dokku-migration](https://github.com/pedropaf/dokku-migration)
  - Announcement blog post: [Dokku Migrations: Introducing the Open Source Dokku Migration Tool](https://www.pedroalonso.net/blog/dokku-migration-tool/).
- [Dokku DigitalOcean Marketplace 1-Click App](https://marketplace.digitalocean.com/apps/dokku)

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

