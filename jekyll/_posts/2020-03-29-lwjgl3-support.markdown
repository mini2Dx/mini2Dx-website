---
layout: post
author: Thomas Cashman
title:  "LWJGL3 Support"
date:   2020-03-29 18:00:00 +0000
---

We've just released mini2Dx 2.0.0-alpha.22 which adds support for LibGDX's LWJGL 3 runtime. This will provide improved support for many things including internationalized input handling, ARM architecture, multi-monitor setups and more!

Moving forward there will be two LibGDX desktop runtimes:

```
compile "org.mini2Dx:mini2Dx-libgdx-desktop-lwjgl2:2.0.0-alpha.22"

OR

compile "org.mini2Dx:mini2Dx-libgdx-desktop-lwjgl3:2.0.0-alpha.22"
```

DesktopMini2DxConfig has now been replaced with Lwjgl2Mini2DxConfig and Lwjgl3Mini2DxConfig.

If you haven't upgraded to the 2.0.0 alpha yet, you can find more info [here](/2019/08/04/mini2Dx-2-0-0-alpha-1-released.html) page to update your version. If you find any issues, please report them on the [Issue Tracker](https://github.com/mini2Dx/mini2Dx/issues).

Roadmap
-----------------------

We're still working on supporting games consoles but have been delayed due to everyone being busy with work. However, progress is being made and we hope to have a beta version soom(TM)!

In the meantime, make sure to [join our community on Discord](https://mini2dx.org/community.html)!
