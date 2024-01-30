# Blog-in-a-Box Container

A repository that hosts the container for [blog-in-a-box](https://github.com/excellalabs/blog-in-a-box).

We maintain and publish the container separately so that we can reference it in Blog-in-a-Box to start the dev container quickly.

We try to keep it up to date with [the GitHub Pages dependencies](https://pages.github.com/versions), though this is currently a manual process.

## What the Container Includes

* Ruby, at the specified version (currently publish with 2.7.3 to match GitHub pages preferred version)
* Git, tzdata updates, and the latest `bundler` gem at the time of build
* Node at the specified major version (currently 16.x)
* the following npm packages globally installed:
  * `cSpell`
  * `markdownlint-cli`
  * `markdownlint-cli2`
* Port 4000 exposed, as this is what Jekyll publishes on.

## Get Involved

We're always up to learn and improve! We'd love your input and suggestions; feel free to create a GitHub issue here and tell us where we can take things next or how we can improve our build & release process.
