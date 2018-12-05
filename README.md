# sails-react-boilerplate

:warning: This project is still under development. Please do not use in
a production environment

Features:
* [Sails 1.0](https://sailsjs.com)
* React 16.6.3
* Webpack

## Why
If you want to use these technologies combo (Sails and React)
you have three options:

* Install sails and customize it untill it meets your needs
* Use a mix between Sails and Sails hooks
* Find and use one of the available boilerplates on github

The best thing to do is to create a custom sails configuration to fit all your
needs. The downside is that create your own perfect environment requires time
and energy. You have to make sure that everything works and, if you work for a web
agency, you propbably can't waste that amount of time in configuration.

The real world, often, is not the utopical one that we would it to be.
Sometimes you have the chance to work on well planned projects, with clear
requirements, tests, deadlines, roadmaps and whatever.
Other times, the project requirements aren't even written. You have to install
the product in no time and every day you work in rush.
Suddenly the code quality does not matter anymore.

This kind of things contribute to create an unhealthy environment for developers,
that leads to a low quality product, full of bugs and almost unusable.
It also means that you'll have to work on it later to fix all the problems that
you have created in the first place.

So, this project is an attempt to create a clean start point, already configured
with the latest technologies to let you focus on the product, not on the
prject configuration.

The mission is to create a reusable boilerplate that allows you to deploy your
product faster, **without too much configuration**.

There are a lot of ready to use boilerplates with sails and react out there.
Anyway, I still can't find one that fits my needs.
Sometimes they still use grunt (too slow), or they don't let me use multiples
webpacks configurations (dev vs prod).

So this is the boilerplate that fits **my needs**, I hope it will fits yours too.

## Features
Work in progress

* [x] Sails Blueprints (Powered by Waterline)
* [x] Webpack with `common`, `dev` and `prod` configuration files
* [x] Webpack Sass Loader
* [x] Webpack File Loader (.svg, .woff2 etc..)
* [x] Babel (ES6)
* [x] EsLint
* [ ] React and ReactDom
