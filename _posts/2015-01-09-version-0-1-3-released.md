---
layout: post
title: "CloudCoder version 0.1.3 released"
description: ""
category: ""
tags: [cloudcoder, release, userprogress]
author: "Dave"
authorurl: "http://faculty.ycp.edu/~dhovemey/"
---

I found a few minor issues in [version 0.1.2](/2015/01/06/version-0-1-2-released.html), so there is now a 0.1.3 release.

Here are the specific improvements:

* C language submissions are now compiled with `-std=gnu99`: this allows, for example, loop variables to be declared in the initialization of a for loop
* Fixed a regression where clicking on a module didn't restrict the problems shown to just that module
* The problem list and progress summary on the home page now list exercises in order of due date
* The progress summary now uses color to visually distinguish not started exercises from started exercises
* Tweaked the colors used for test outcomes in the test outcome view

As always, see the [Installation instructions](https://github.com/cloudcoderdotorg/CloudCoder/wiki/Install) for information on installing CloudCoder, and [drop me a line](mailto:dhovemey@ycp.edu) if you run into any issues.
