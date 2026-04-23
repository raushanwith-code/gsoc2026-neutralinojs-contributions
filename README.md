<div align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="media/nllogo-light-theme.png" width="300"/>
    <source media="(prefers-color-scheme: dark)" srcset="media/nllogo-dark-theme.png" width="300"/>
    <img alt="Neutralinojs logo" src="media/nllogo-light-theme.png" width="300"/>
  </picture>
 </div>

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/neutralinojs/neutralinojs)](https://github.com/neutralinojs/neutralinojs/releases)
[![GitHub last commit](https://img.shields.io/github/last-commit/neutralinojs/neutralinojs.svg)](https://github.com/neutralinojs/neutralinojs/commits/main)
![Build status](https://github.com/neutralinojs/neutralinojs/actions/workflows/test_suite.yml/badge.svg)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fneutralinojs%2Fneutralinojs.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fneutralinojs%2Fneutralinojs?ref=badge_shield)

Neutralinojs is a lightweight and portable desktop application development framework. It lets you develop lightweight cross-platform desktop applications using JavaScript, HTML and CSS. Apps built with Neutralinojs can run on Linux, macOS, Windows, Web, and Chrome. Also, you can extend Neutralinojs with any programming language (via extensions IPC) and use Neutralinojs as a part of any source file (via child processes IPC).

- [Neutralinojs vs. Electron, NW.JS, Tauri, NodeGui, Flutter, .Net MAUI, Wails](https://github.com/Elanis/web-to-desktop-framework-comparison)
- [Roadmap 2025](https://github.com/neutralinojs/roadmap)
- [Release notes](https://neutralino.js.org/docs/release-notes/framework)

Get started with the neu CLI:

```bash
# Creating a new app
npm i -g @neutralinojs/neu
neu create hello-world
cd hello-world
neu run

# Building your app (No compilation - takes less than a second)
neu build
```

You can use your favorite frontend frameworks:

```bash
# Creating a new React-based app
neu create hello-react -t codezri/neutralinojs-react
```

Start building apps: [neutralino.js.org/docs](https://neutralino.js.org/docs)

## Why Neutralinojs?

In Electron and NWjs, you have to install NodeJs and hundreds of dependency libraries. Embedded Chromium and Node make simple apps bloaty. Neutralinojs offers a lightweight and portable SDK which is an alternative for Electron and NW.js. Neutralinojs doesn't bundle Chromium and uses the existing web browser library in the operating system (Eg: gtk-webkit2 on Linux). Neutralinojs implements a WebSocket connection for native operations and embeds a static web server to serve the web content. Also, it offers a built-in [JavaScript client library](https://github.com/neutralinojs/neutralino.js) for developers.

Ask questions on StackOverflow using the tag [neutralinojs](https://stackoverflow.com/questions/tagged/neutralinojs)

## Contributing

Please check the [contribution guide](https://neutralino.js.org/docs/contributing/framework-developer-guide). We use GitHub Discussions and Discord for quick discussions.
  * [Join on Discord](https://discord.gg/cybpp4guTJ)
  * [Start a thread on Discussions](https://github.com/neutralinojs/neutralinojs/discussions)

Neutralinojs contributors:

<a href="https://github.com/neutralinojs/neutralinojs/graphs/contributors">
  <img src="https://contributors-img.firebaseapp.com/image?repo=neutralinojs/neutralinojs" />
</a>

Image created with [contributors-img](https://contributors-img.firebaseapp.com).

## Subprojects

- Releases are powered by [ReleaseZri](https://codezri.org/docs/releasezri/intro)
- Previous binary builds were powered by [BuildZri](https://codezri.org/docs/buildzri/intro) (now the project uses CMake + Ninja)

## Sponsors and Donators

Organizations and individuals support Neutralinojs development. See: https://codezri.org/sponsors

If you like to support our work, you can donate to Neutralinojs via [Patreon](https://www.patreon.com/shalithasuranga) or [GitHub Sponsors](https://github.com/sponsors/shalithasuranga).

[![Become a Patreon](https://c5.patreon.com/external/logo/become_a_patron_button.png)](https://www.patreon.com/shalithasuranga)

#

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fneutralinojs%2Fneutralinojs.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fneutralinojs%2Fneutralinojs?ref=badge_large)

