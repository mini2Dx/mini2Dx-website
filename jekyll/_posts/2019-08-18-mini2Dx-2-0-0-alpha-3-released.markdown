---
layout: post
author: Thomas Cashman
title:  "mini2Dx 2.0.0-alpha.3 released"
date:   2019-08-18 20:00:00 +0000
---

We've just released mini2Dx 2.0.0-alpha.3 with the following fixes/improvements. Once again a big thanks to Augusto Zanellato for his contributions :)

 * Added QuadTreeAware interface to allow inverse searching of QuadTrees
 * Added additional primitive implementations of Map and TreeMap (ByteMap, ByteTreeMap, etc.)
 * Added Input.isKeyDown(int) and Input.isKeyUp(int)
 * Added PlatformUtils class
 * Added primitive Queue implementations (IntQueue, LongQueue, etc.)
 * Added PerformanceTracker API
 * Optimized LibGDX Graphics class when rendering shapes
 * Fixed Rectangle with width and height of 0 always returns true for contains() method
 * Fixed UI input when a viewport is applied
 * Fixed TilingDrawable rendering only entire textureregions

As always, follow the [updating mini2Dx](https://github.com/mini2Dx/mini2Dx/wiki/Updating-mini2Dx) page to update your version.