# .NET Notts Blog

![.NET Notts Blog Build](https://github.com/dotnetnotts/dotnetnotts-blog/workflows/.NET%20Notts%20Blog%20Build/badge.svg) 
![.NET Notts Blog Deploy](https://github.com/dotnetnotts/dotnetnotts-blog/workflows/.NET%20Notts%20Blog%20Deploy/badge.svg?branch=main)

<br>

# Contents
 - [Local Development](#local-development)
   - [Setup Jekyll](#setup-jekyll)
   - [Building Locally](#building-locally)
   - [Running Locally](#running-locally)
   - [Gotchas](#gotchas)
 - [Build Tool](#build-tool)
 - [Branding](#branding)
 - [Code Of Conduct](#code-of-conduct)
 - [Contributing](#contributing)
  
<br/>

# Local Development 

## Setup Jekyll

- [Follow the instruction to set up Jekyll on your machine](https://jekyllrb.com/docs/)

## Building Locally

- Run `jekyll build` to build the project

## Running Locally

To run the project locally use the command `bundle exec jekyll serve` in the terminal of your choice. This make the site available on `http://localhost:4000/`. Access that address in the browser of your choice to see your local version of the website.

## Gotchas

- When running locally, you will only see posts that are in the past or dated for the current day.

<br/>

# Build Tool

GitHub Actions is set up to build and run tests from Pull Requests so that we can ensure the project builds and tests pass from nay changes made within branches before they are merged in. 

GitHub Actions is also used to deploy on merge into master.

![.NET Notts Blog Build](https://github.com/dotnetnotts/dotnetnotts-blog/workflows/.NET%20Notts%20Blog%20Build/badge.svg) 
![.NET Notts Blog Deploy](https://github.com/dotnetnotts/dotnetnotts-blog/workflows/.NET%20Notts%20Blog%20Deploy/badge.svg?branch=main)

<br/>

# Branding

![.NET Notts Branding](https://res.cloudinary.com/dsfcrod4r/image/upload/v1598552467/branding_ydno1a.png)

**Primary Colour:** #05bd9e

**Secondary Colour:** #fffff

**Font:** Bahnschrift

<br/>

# Code Of Conduct

Please see [the Code Of Conduct File.](CODE_OF_CONDUCT.md)

<br/>

# Contributing

Please see [the contribution guidelines.](.github/contributing.md). We also have a blog post you can read with instructions [here](http://blog.dotnetnotts.co.uk/2020/09/24/hacktober-post.html)