# 🪐 Planet Patrol

"Planet Patrol" is a demonstration monitoring and notification system for the [Planetary Data System](https://pds.nasa.gov/). It keeps tabs of essential websites, APIs, and other online endpoints, files tickets when things aren't working, makes notifications (when configured to do so), and keeps things up and running, and neat and tidy.

## 🏃‍♀️ Getting Started

Check the documentation for [Upptime](https://upptime.js.org/) first. Then do a `git pull` because the [GitHub Actions](https://github.com/features/actions) that powers this make numerous commits to the repository _all the time_. Then edit the `.upptimerc.yml` file and commit and push.

You can then view the results at [the Planet Patrol website](https://nasa-pds.github.io/PlanetPatrol/) (powered by [GitHub Pages](https://pages.github.com)).

As systems go down, [issues are automatically filed and assigned](https://github.com/nasa-pds/PlanetPatrol/issues) (powered by [GitHub Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)).


## 🚨 Notificatios

Email notifications are currently being tested. They're being sent using JPL SMTP using a "service" account managed by @nutjob4life. They're allegedly going to four different addresses (the `NOTIFICATION_EMAIL_TO` secret). The documentation doesn't make it clear what the delimiter is between multiple email addresses, so we're trying commas (`,`) for now.

Other notification options in the future include Teams messages, Slack pings, Discord integration, SMS messages, and so forth.


## 🖥 The Software

This effort is based on [Upptime](https://upptime.js.org/).

## 👥 Contributing

You can always look at [open issues](https://github.com/nasa-pds/PlanetPatrol/issues) and/or make [pull requests](https://github.com/nasa-pds/PlanetPatrol/pulls).

## 📃 License

The project is licensed under the [Apache version 2](LICENSE.md) license. It's based on [Upptime](https://upptime.js.org/), which is license under the [MIT](LICENSE) license.

The planet logo on the status page is the courtesy of <a href="https://pixabay.com/users/program_solaris-16735824/?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7123123">Wojciech Ciecierski</a> from <a href="https://pixabay.com//?utm_source=link-attribution&utm_medium=referral&utm_campaign=image&utm_content=7123123">Pixabay</a>.
