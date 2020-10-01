---
layout: post
title: Contributing to the .NET Notts Repositories
description: "Do you want to take part in Hacktoberfest? Or want some guidance on how to contribute to Open Source Repositories? This post outlines how to contribute to the .NET Notts repositories, and other repositories, both during Hacktoberfest and going forward."
date: 2020-09-24
cover: "/assets/header-image.png"
author: Jessica White
categories: [organisation]
comments: false
share: true
---

----
<center>
<h3 class="quote"><i>Contributing during Hacktober.</i> </h3>
</center>

---
<br/>

Here at .NET Notts we want to help you contribute to open source, and take part in <a href="https://hacktoberfest.digitalocean.com/" target="_blank">Hacktoberfest</a>. This post goes through the various repositories we have set up that you can contribute to, and how to make contributions.


## What is Hacktoberfest and how to sign up

Hacktoberfest is an event where the aim is to encourage participation on the open source community. In exchange for a number of pull requests on OSS repositories, participants are rewarded with a t-shirt and some stickers, or you can chose to have a tree planted for your efforts. 

To sign up, <a href="https://hacktoberfest.digitalocean.com/" target="_blank"> head over to the Hacktoberfest website</a>.


<br/>

# What contributions you could make

Contributions can come in many forms. You can contribute code changes, correct spelling, write documentation, raise issues, conduct testing and more. All forms of contributions are incredibly valuable and appreciated.

## .NET Notts Website

There is a brand new repository: <a href="https://github.com/dotnetnotts/dotnetnotts-web" target="_blank">dotnetnotts-web</a>. This repository has been made so that you, the community, can help us build a website for the .NET Notts website that suits your needs.

This website will be written in <a href="https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor" target="_blank">Blazor</a>, in keeping with the .NET theme of the meetup. It will be written from the ground up with your help, meaning that there will be issues for developers at all levels and in all specialties.

Please help us by picking up issues and raising issues we may have missed.

## .NET Notts Blog

Our other repository is the one this page is built with: <a href="https://github.com/dotnetnotts/dotnetnotts-blog" target="_blank"> the dotnetnotts-blog repository</a>. Here you can contribute by writing a blog about anything .NET related.

<br/>

# How To Contribute

This sections details how to contribute to each of our sites.

#### Check the contribution guidelines of the projects

Open Source repositories often have contribution guidelines. This is often documented in a `contribution.md` file, and outlines what behaviours are expected and what to do when contributing to the project.

#### Make it clear on any related issues that you are picking up the work

Check the issues tab on the project to see if the changes you want to make are highlighted in there as a bug, feature or otherwise. Check that no one else has picked up the work and that it is still available to work on. 

If you have found something that you would like to pick up:

- Comment on the issue saying you would like to pick it up.
- An owner will let you know if you are the first to comment and if it is yours. They will then add a label of `in progress` and assign the issue to you.

#### Fork the repository

<a href="https://guides.github.com/activities/forking/" target="_blank">Fork the repository</a> and clone it locally. <a href="https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/configuring-a-remote-for-a-fork" target="_blank">Configure your remote fork to have the original projects main branch as it's upstream.</a> If you regularly pull in changes from this remote "upstream" repository, your fork will remain up to date, reducing the chance of later complex merge conflicts.

<br/>
<img src="/assets/posts/2020-09-24/fork.png" alt="alttext" width="100%"/>
<center>
<i>Screen shot from forking the repository</i>
</center>
<br/>

#### Create a branch

In your forked repository create a branch, which is named according to the contribution guidelines for the repository. If there are no guidelines available, give your branch a short name that summarises your changes.

#### Clear commits

While working on your changes, make sure to keep commits small and clear. If possible, each commit should be a change which builds and has any tests passing. There are a few advantages to having small, clear commits. One of which is that the owners of the repositories will be able to read through your commits when a PR is raised to see what changes you made, in what order and what your thought processes were.

#### Test your changes

Whether manually or not, test your changes and gather evidence of them working. Run any existing tests as well to ensure the project is still working. Instructions for how to run the projects locally can be found in the repositories README.

#### Be detailed when raising the Pull Request

You can raise a Pull Request at the end of your changes, or open a draft pull request early so that others can see your changes as they progress. When filling out the details of the Pull Request, I would advise including the following:

- A reference to any issue you are addressing. This is done using a # followed by the number of your issue. For example `#97`.
- A short description of the problem you are solving and the benefits of your changes.
- Evidence of your changes working. This can include screen shots from manual tests and instructions for replicating the result locally.

All of the .NET Notts repositories have templates depicting what information is needed in the Pull Request description section.

#### Double check you've met the contribution guidelines

Go back to the contribution guidelines and check that you've met the instructions/requirements outlined in them. 

<br/>

# Code Of Conduct

The code of for our events also applies to the .NET Notts repositories. If you are made to feel uncomfortable or harrassed in any way, please get in touch with the repository owners.

<br/>

# Overview

The above steps will hopefully give you some guidance on how to contribute to the .NET Notts repositories. We hope you have an awesome time contributing and helping us out! Let us know how you get on, on any of our social media sites.

<br/>

<div style="text-align:center; width:20%; margin-left: 10%;" markdown="1">
<img src="{{site.baseurl}}/assets/logo.png" alt="Logo">
</div>
