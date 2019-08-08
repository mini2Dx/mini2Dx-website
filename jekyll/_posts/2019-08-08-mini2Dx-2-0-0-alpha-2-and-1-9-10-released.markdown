---
layout: post
author: Thomas Cashman
title:  "mini2Dx 2.0.0-alpha.2 and 1.9.10 released"
date:   2019-08-08 19:00:00 +0000
---

We've just released mini2Dx 2.0.0-alpha.2 and 1.9.10 with loads of fixes.

__2.0.0-alpha.2__

The following fixes/improvements have been made in 2.0.0-alpha.2. Once again a big thanks to Augusto Zanellato for his contributions :)

 * Update to latest RoboVM to support iOS 12
 * (Re-)Added artemis-odb library and iOS runtime
 * Implemented TilingDrawable
 * Added SpriteCache interface and implementations
 * Added ReadOnlyColor class for primary colors to avoid manipulation issues
 * Reduced memory usage in MonoGame runtime
 * Fixed dependency injection not injecting prototypes correctly
 * (#175) Fixed FileHandle.listFiles() not working correctly
 * (#88) Fixed clipping not working when rendering shapes

__1.9.10__

mini2Dx 1.9.10 also contains the following changes:

 * Update to latest RoboVM to support iOS 12
 * (#88) Fixed clipping not working when rendering shapes

As always, follow the [updating mini2Dx](https://github.com/mini2Dx/mini2Dx/wiki/Updating-mini2Dx) page to update your version.