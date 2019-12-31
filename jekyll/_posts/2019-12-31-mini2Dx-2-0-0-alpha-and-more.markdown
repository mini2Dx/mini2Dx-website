---
layout: post
author: Thomas Cashman
title:  "mini2Dx 2.0.0 Alpha + More"
date:   2019-10-31 12:00:00 +0000
---

New UI XML Format
-----------------------

We've just released mini2Dx 2.0.0-alpha.15 which contains a new XML format for UI thanks to Dan Dudley. Originally, we had planned on working on a new format in 2.1 but thanks to Dan's massive contribution this will be part of 2.0.

The new format is much simpler and comes with an [XML schema](https://raw.githubusercontent.com/mini2Dx/mini2Dx/master/ui/src/main/resources/mini2dx-ui.xsd) so that IDEs can auto-complete and validate your XML.

A sample of the new format can be found below. As always, follow the [updating mini2Dx](https://github.com/mini2Dx/mini2Dx/wiki/Updating-mini2Dx) page to update your version.

```xml
<container xmlns="https://github.com/mini2Dx/mini2Dx">
	<flex-row>
		<div id="firstColumn" layout="xs-12 sm-10 sm-offset-1 md-3" style="">
			<label style="default" text="Label text"/>
		</div>
		<div layout="xs-12 sm-10 sm-offset-2 md-3">
			<select id="select1" style="default">
				<option value="1">Option 1</option>
				<option value="2">Option 2</option>
				<option value="3">Option 3</option>
				<option value="4">Option 4</option>
			</select>
		</div>
		<div layout="xs-12 sm-10 sm-offset-2 md-3">
			<text-button id="button1" text="" style="default"/>
			<image-button id="button2" style="default">
				<normal-texture>button.png</normal-texture>
			</image-button>
		</div>
		<div layout="xs-12 sm-10 sm-offset-2 md-3">
			<text-box id="textBox1" style="default"/>
		</div>
	</flex-row>
</container>
```

Roadmap
-----------------------

We're still working on minor fixes to support games consoles. Once we have a stable build running in January/February, we'll transition 2.0 to beta. As mentioned before, the alpha version is considered stable for desktop and mobile platforms and the API is near-final.

We're also working on a new website as part of 2.0 and hope to launch the new site during the beta. The new website will feature a whole new design with more documentation, tutorials and sample projects.

In the meantime, make sure to [join our community on Discord](https://mini2dx.org/community.html)!
