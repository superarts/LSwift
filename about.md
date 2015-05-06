---
layout: page
title: About
permalink: /about/
---

LSwift
---

LSwift is a `swift` library that contains various extensions and classes, including a refelection model, a REST client, etc. L stands for `lib`.

Install
---
Installation for LSwift is pretty poor at the moment.

Manually
===
Clone this repo and copy all the source files under `src` into your project manually, and then remove LExtension.swift if you don't have the dependency.

Cocoapods / Carthage
===
Dynamic framework is only supported in iOS 8, and I still need to support iOS 7 for a while, besides LSwift is still under development (it has fewer feature than LFramework so far). So the plan is that when iOS 9 is released and iOS 8 becomes the common deployment target, I'll split LSwift into several parts (LExtension, LRestClient, etc.) and release as different frameworks.

Dependency
---
LExtension depends on some projects I've been using, e.g. `MBProgressHUD` and all the other parts depends on common frameworks from Apple like UIKit, MapKit, etc.

Version history
---

0.1
===
- under development

Powered by Jekyll
---
This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](http://jekyllrb.com/)

You can find the source code for the Jekyll new theme at: [github.com/jglovier/jekyll-new](https://github.com/jglovier/jekyll-new)

You can find the source code for Jekyll at [github.com/jekyll/jekyll](https://github.com/jekyll/jekyll)