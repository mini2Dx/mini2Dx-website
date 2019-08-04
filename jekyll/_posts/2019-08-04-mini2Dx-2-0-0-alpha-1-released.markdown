---
layout: post
author: Thomas Cashman
title:  "mini2Dx 2.0.0-alpha.1 released"
date:   2019-08-04 19:00:00 +0000
---

I'm excited to reveal the first alpha of mini2Dx 2.0 :)

As [previously announced](https://mini2dx.org/2018/06/10/mini2Dx-1-7-0-released-and-roadmap-ahead.html), 2.0 de-couples LibGDX to allow for more platforms. A special thanks to Augusto Zanellato for his major contributions to the new MonoGame-based runtime on games consoles. For anyone using 1.9.x, the upgrade path should be easy as we've aimed to keep the API as close as possible in 2.0.

__New Library Structure__

The following is the new library/dependency structure for mini2Dx.

 * mini2Dx-core (Cross-platform APIs)
 * mini2Dx-libgdx (Common code for LibGDX-based runtimes)
 * mini2Dx-libgdx-desktop (LibGDX runtime for Windows/Mac/Linux)
 * mini2Dx-libgdx-android (LibGDX runtime for Android)
 * mini2Dx-libgdx-ios (LibGDX runtime for iOS - Note: This is not release in alpha.1 but will be in alpha.2)
 * mini2Dx-monogame (Common code for MonoGame-based runtimes)

__Upgrading to 2.0__

mini2Dx 2.0 now provides cross-platform APIs for Sprite, Texture, TextureRegion, etc. However, if you use a LibGDX-specific API not provided by mini2Dx, you'll need to find/implement a cross-platform solution. If you don't plan on porting to consoles, you can simply add a dependency on _mini2Dx-libgdx_ to your core project and continue using the LibGDX APIs.

Simply follow the [updating mini2Dx](https://github.com/mini2Dx/mini2Dx/wiki/Updating-mini2Dx) page and set your version to _2.0.0-alpha.1_

__Desktop/Mobile Runtimes__

Since the desktop/mobile runtimes are based on 1.9.x, these should already be stable. As always if you find any issues please add them to the [Issue Tracker](https://github.com/mini2Dx/mini2Dx/issues).

__Console Runtimes__

mini2Dx 2.0 will add games console support via MonoGame. However, please note the following:

 * You must be a registered developer with the console provider to gain access to the runtime for that platform
 * The console-specific runtimes are held in private repositories
 * You will need to purchase the appropriate development hardware as required
 * You will need to purchase a license for a cross-compiler to target the platform (more info available soon)

 __Future__

 We'll be continuing with bug fixes until 2.0 is stable on all platforms. We encourage developers to test the alpha/beta builds and help us find issues. As previous stated, 1.9.x will only receive bug fixes and optimisations going forward. Once 2.0 is released, 1.9.x will be 100% community-driven on the [mini2Dx Vintage Edition repository](https://github.com/mini2Dx/mini2Dx-ve).