# 🪐 Planet Patrol

"Planet Patrol" is a demonstration monitoring and notification system for the [Planetary Data System](https://pds.nasa.gov/). It keeps tabs of essential websites, APIs, and other online endpoints, files tickets when things aren't working, makes notifications (when configured to do so), and keeps things up and running, and neat and tidy.

## 🏃‍♀️ Getting Started

Check the documentation for [Upptime](https://upptime.js.org/) first. Then do a `git pull` because the [GitHub Actions](https://github.com/features/actions) that powers this make numerous commits to the repository _all the time_. Then edit the `.upptimerc.yml` file and commit and push.

You can then view the results at [the Planet Patrol website](https://nasa-pds-engineering-node.github.io/PlanetPatrol/), (powered by [GitHub Pages](https://pages.github.com)).

As systems go down, [issues are automatically filed and assigned](https://github.com/nasa-pds-engineering-node/PlanetPatrol/issues) (powered by [GitHub Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)).

Email notifications, Teams messages, Slack pings, Discord integration, SMS messages, and so forth, have not yet been configured.

### 🤫 Secrets

The following [repository secrets](https://github.com/nasa-pds-engineering-node/PlanetPatrol/settings/secrets/actions) are in use:

- `GH_PAT`: a personal access token with Actions, Contents, Issues, and Workflows scopes so Planet Patrol can run

And that's it for now!

## 🖥 The Software

This effort is based on [Upptime](https://upptime.js.org/).

## 👥 Contributing

You can always look at [open issues](https://github.com/nasa-pds-engineering-node/PlanetPatrol/issues) and/or make [pull requests](https://github.com/nasa-pds-engineering-node/PlanetPatrol/pulls).

## 📃 License

The project is licensed under the [Apache version 2](LICENSE.md) license. It's based on [Upptime](https://upptime.js.org/), which is license under the [MIT](LICENSE) license.
