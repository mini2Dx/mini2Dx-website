---
layout: post
author: Thomas Cashman
title:  "mini2Dx 2.0.0-alpha.11 released + Roadmap"
date:   2019-10-27 15:00:00 +0000
---

2.0.0-alpha.11
-----------------------

We've just released mini2Dx 2.0.0-alpha.11 which contains the following changes:

 * Added setVisible/isVisible methods to CustomCursor
 * Added AOT (ahead of time) utilities for game console runtimes
 * A lot of fixes/performance optimisations to MonoGame runtime
 * Fixed duplicate calls to Shape#dispose resulting in shapes being queued into pools twice
 * Fixed UI input source changing when using controllers with dead zone issues
 * Fixed incorrect UI render node being returned under certain circumstances.

As always, follow the [updating mini2Dx](https://github.com/mini2Dx/mini2Dx/wiki/Updating-mini2Dx) page to update your version.

Roadmap
-----------------------

2.0.0-alpha.11 will be the last alpha build of 2.0.0. This version is considered the near-final API that will be used for the final 2.0.0 release.

Normally alpha/beta would be considered unstable, however, we have been using the alpha builds for [Alchemic Cutie](https://alchemiccutie.com/) without issue. In fact, 2.0.0-alpha.11 performs better than the latest 1.9.x release! So if you'll be upgrading to mini2Dx 2.0 in the future, we recommend using alpha.11 to test your code.

Up next will be 2.0.0-beta.1 which will be the first build supporting games consoles. There's still a few issues left for us to fix but we're really close to having a build of Alchemic Cutie running on Nintendo Switch. As mentioned before, the console runtime will require a license for a cross-compiler (more info on pricing/availability soon).

After 2.0 is released, we'll be focusing on fixes and optimisations before moving on to 2.1. If there are features you'd like to see in 2.1, make sure to add them to the [Issue Tracker](https://github.com/mini2Dx/mini2Dx/issues)!

