# Front-end
[![Backers on Open Collective](https://opencollective.com/speedtracker/backers/badge.svg)](#backers) [![Sponsors on Open Collective](https://opencollective.com/speedtracker/sponsors/badge.svg)](#sponsors) 
> v1.2.3

*Visualisation layer and data store for SpeedTracker*

---

[![js-standard-style](https://cdn.rawgit.com/feross/standard/master/badge.svg)](http://standardjs.com)

## Installation

1. [Click here](https://www.webpagetest.org/getkey.php) to request a WebPageTest API key.
1. Fork this repository into your own GitHub account or organisation.
1. Enable GitHub Pages for the repository under *Settings* > *Options* > *GitHub Pages*. Select the branch you want to serve your site from (typically **master**).
1. Add **speedtracker-bot** as a collaborator on your repository (under *Settings* > *Collaborators*).
1. Use the [connect tool](https://speedtracker.org/connect) to establish a connection between SpeedTracker and your repository.
1. Edit the main configuration file (`speedtracker.yml`).
1. Edit `_profiles/default.html` to define your first profile.
1. Commit and push the changed files.
1. Use the [test tool](https://speedtracker.org/test) to run a test.

## Development

1. Install dependencies

  ```
  npm install
  ```

1. Start the Jekyll server

  ```
  jekyll serve --watch --port SOME_PORT
  ```

1. Start Webpack

  ```
  npm run watch
  ```

1. When you're done with your changes, build the bundle for production

  ```
  npm run build
  ```

---

