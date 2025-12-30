---
title: Retrofitting Tundra TRD Hub Caps on TSS Wheels
date: 2025-12-29 12:00:00
categories: [Toyota, Tundra]
tags: [tss, toyota, tundra, 3dprinting]     # TAG names should always be lowercase
description: A 3D printable converter to allow the use of TRD hubcaps on 2014 TSS Toyota Tundra wheels
image:
  path: /assets/img/posts/TSSHubCapConversion/truck.JPEG
---
I recently had my T-Force wheels powder coated since the chrome was peeling off. The hubcaps that came with the wheels were also chrome, so I needed to either paint them black or use something else as a hubcap. I came across a forum post where someone glued on the newer TRD hubcaps to their TSS wheels, and it looked pretty solid so I decided to create a mount that wouldn't require me to glue the hubcaps on. After a few hours of modeling and careful work with some dial calipers, I came up with the following design in FreeCAD:

![FreeCAD 3D model](/assets/img/posts/TSSHubCapConversion/CADview.png){: .w-50 w="857" h="740"}

To use the design, the TRD hubcaps will have to be modified since the two tapped bolt holes in the TSS wheels are located right where the tabs are on the rear of the hubcap. The hubcap also has rings that circle the lug nuts on the wheel it was designed for, which will need to be removed as well. I used a Dremel with a plastic cutting wheel to do this, which ended up working pretty well. I was worried that it would just gum up and/or melt the plastic, but neither of those were issues for me. 

Here is what the hubcap looks like before making any modifications to it:

![TRD hubcap before cutting](/assets/img/posts/TSSHubCapConversion/precuts.JPEG){: .w-50}

Here it is after cutting off the two tabs and the rings that circle the lugs:

![TRD hubcap after cutting](/assets/img/posts/TSSHubCapConversion/tabcuts.JPEG){: .w-25 .normal }
![TRD hubcap after cutting](/assets/img/posts/TSSHubCapConversion/roundedcorners.JPEG){: .w-25 .normal }
![TRD hubcap after cutting](/assets/img/posts/TSSHubCapConversion/roundedcorners2.JPEG){: .w-25 .normal }

Here is what it looks like installed on the TSS wheel: 

![TRD hubcap on TSS wheel](/assets/img/posts/TSSHubCapConversion/tire1.JPEG){: .w-25 .normal }
![TRD hubcap on TSS wheel](/assets/img/posts/TSSHubCapConversion/tire2.JPEG){: .w-25 .normal }

The bolts to secure this converter on are 1/4-20 x 1". I used blue Loctite and lock washers to ensure the bolts wouldn't back out. If you are really worried about the hubcaps coming off, you can also apply glue to the center post on the converter. It was designed so that it presses directly up against the back of the hubcaps. 

I printed mine out of ABS with a wall thickness of four, which seemed to work well (didn't crush when the bolts were tightened). 

The STL and FreeCAD files are uploaded to [thingiverse](https://www.thingiverse.com/thing:7249188) so you can print and modify it as you see fit. Enjoy! 
