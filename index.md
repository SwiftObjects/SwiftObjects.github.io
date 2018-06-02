---
layout: default
title: SwiftObjects
tags: xcode swift server side webobjects
---

<p>
  <img src="https://img.shields.io/badge/swift-4-blue.svg" />
  <img src="https://img.shields.io/badge/os-macOS-green.svg?style=flat" />
  <img src="https://img.shields.io/homebrew/v/cake.svg" />
  <img src="https://travis-ci.org/SwiftObjects/SwiftObjects.svg?branch=develop" />
</p>

A **very important** first note:
This is a **demo** and an experiment to see whether and how the 
[WebObjects](https://en.wikipedia.org/wiki/WebObjects) API
might work in Swift.
Do **not** try this at home, it is not how you write web servers nowadays!
Nor is it optimized, or fast at all, to the contrary.

## Blog

This is part of a blog entry, called:
[An Introduction to WebObjects, in Swift](http://www.alwaysrightinstitute.com/wo-intro/).

## Install

<a href="https://swiftxcode.github.io" target="extlink"><img src="http://zeezide.com/img/SwiftXcodePkgIcon.svg"
     align="right" width="86" height="86" style="padding: 0 0 0.5em 0.5em;" /></a>
We use [Homebrew](https://brew.sh) to install the SwiftObjects
development environment.
To install the
[swift xcode](https://swiftxcode.github.io)
[SwiftObjects image](https://github.com/SwiftXcode/SwiftObjects_XcodeImage)
image, simply run those commands:
```shell
brew install swiftxcode/swiftxcode/swift-xcode-wo
swift xcode link-templates
```

That will take a moment to install and compile, but then we are ready to go!

## Screenshot

<center><img src="http://www.alwaysrightinstitute.com/images/swiftobjects/74-semui-card-nice.png" /></center>

## Create a new WOApp

Within Xcode, create a new project (⌘-Shift-N),
go to the "macOS" section and select the "WOApplication"
template, very much at the bottom of the inspector
(pro tip: type "wo" in the filter field at the upper right):

<center><img src=
  "http://www.alwaysrightinstitute.com/images/swiftobjects/01-so-create-project-1.png" 
  /></center>

Give your project a name, say "HelloWOrld" create it somewhere, and you should
end up with something like this:

<center><img src=
  "http://www.alwaysrightinstitute.com/images/swiftobjects/05-so-create-project-5.png" 
  /></center>
  
Press the Play/Run button to build and start the application. Open your
favorite browser and navigate to
[http://localhost:1337/](http://localhost:1337/):

<center><img src=
  "http://www.alwaysrightinstitute.com/images/swiftobjects/21-main-page.png" 
  /></center>

Yay. History is up and running!



### Who

**SwiftObjects** is brought to you by
[ZeeZide](http://zeezide.de).
We like feedback, GitHub stars, cool contract work,
presumably any form of praise you can think of.

There is a channel on the [Noze.io Slack](http://slack.noze.io).
