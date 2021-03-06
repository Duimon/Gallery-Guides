---
layout: "post"
title: "Install With Git"
subtitle: "Installing &ldquo;Duimon-Mega-Bezel&rdquo; Graphics and Presets Using Git"
active: "guides"
image:
  feature: "guides-header.jpg"
date: "2021-09-28"
header-img: "img/guides-bg.jpg"
tags: [Preset]
categories: [MegaBezel]
comments: "false"
---

The Mega Bezel Community is a collaboration between a growing collection of artists and the shader developer.

We have agreed, in an effort to create cohesion among our various projects, to intend 
our works reside in a "Mega Bezel Community" folder. (Within the RA shader folder.) This
keeps the shader folder tidy while still allowing for a relatively short browse to the 
artists presets.

To that end our presets are using relative paths to the assets, and absolute paths to the Mega Bezel base presets.

It should be noted that the Mega Bezel Community folder is not a requirement. As long as each of our work 
remains in it's distributed folder, the folder can reside anywhere under the Retroarch root path.

The following instructions assume a Mega Bezel Community folder.

___

So the file structures is...

    Retroarch/shaders/Mega_Bezel_Community/Duimon-Mega-Bezel
        	/Graphics
        	/Presets


An example presets folder and contents is...

    Retroarch/shaders/Mega_Bezel_Community/Duimon-Mega-Bezel
    		/Presets
    			/Nintendo_3DS
    				3DS-[ADV]-[LCD-GRID].slangp
    				3DS-[ADV]-[LCD-GRID]-[Night].slangp
    				3DS-[STD]-[LCD-GRID].slangp
    				3DS-[STD]-[LCD-GRID]-[Night].slangp
    				3DS_Vertical-[ADV]-[LCD-GRID]-[Integer].slangp
    				3DS_Vertical-[ADV]-[LCD-GRID]-[Integer]-[Night].slangp
    				3DS_Vertical-[STD]-[LCD-GRID]-[Integer].slangp
    				3DS_Vertical-[STD]-[LCD-GRID]-[Integer]-[Night].slangp
    				3DS_Vertical_Alt-[ADV]-[Guest].slangp
    				3DS_Vertical_Alt-[ADV]-[Guest]-[Night].slangp
    				3DS_Vertical_Alt-[STD]-[Guest].slangp
    				3DS_Vertical_Alt-[STD]-[Guest]-[Night].slangp


You can install everything to a local clone and update using the following method.

1. Install Git. [https://git-scm.com/downloads](https://git-scm.com/downloads) using the default settings.
2. Enter the *"/Retroarch/shaders"* folder and create a *"Mega_Bezel_Community"* folder if one does not exist.
3. Enter the *"Retroarch/shaders/Mega_Bezel_Community"* folder and from the command-line run:

```
git clone https://github.com/Duimon/Duimon-Mega-Bezel
```

It will create a *"Duimon-Mega-Bezel"* folder inside the *"Mega_Bezel_Community"* folder. 

To update, go into the *"Duimon-Mega-Bezel"* folder (note the path difference) and run

```
git pull
```
___

**Thanks @drstupid for the method.**