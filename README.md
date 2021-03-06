# slow-tree

[![Build Status](https://travis-ci.com/PatrickSachs/slow-tree.svg?branch=master)](https://travis-ci.com/PatrickSachs/slow-tree)

A web based 2D-tree creation application.

![Game Screenshot](https://data.patrick-sachs.de/content/slow-tree/github-banner.png)

## Features

* Create a tree from **different tree types**.
* **Export the tree as an image** and show off your awesome tree creation skills!
* Download the tree project file and **continue building it on another computer**.
* Save/cache the tree to your **local storage**.
* Full **undo-redo support using** a command pattern implementation.
* **PWA support**: Add slow-tree to your desktop/home screen

## Why?

This project was created as a class project to **practice design pattern implementation**. Actions such as adding a branch, changing the background, etc. are encapsulated into command classes that can be done and undone.

The UI is written in Vue.js and the application itself in Phaser 3. We use TypeScript as programming language.

## Contributions

Feel free to shoot issues and PRs at us. Just keep in mind that this was designed as a fun little side project without serious production usage in mind.

New commits to master are automatically deployed to tree.sahnee.de. However, due to highly aggressive caching(Cloudflare, Service Worker & GitHub Pages) it may take a while for the changes to be visible on your machine.

Please make all Pull Requests against the `develop` branch only. We will merge `develop` into `master` once it is time for a new release.
