![CSGO](http://i.imgur.com/vdVmWSu.png)  
====
# CSGO sh4rkman's Configuration

![Download_logo](http://i.imgur.com/6FsLBIu.png?3)  
[Download latest version](https://github.com/sh4rkman/CSGO_CONFIG/releases/ "Dowload!")  


## Sommaire

- [Introduction](#introduction)
- [Installation](#installation)
- [Additional Tools](#additional_Tools)
 	- [SimpleRadar](#simple-radar)
	- [VibranceGUI](#vibrancegui)
	- [Mousefix noaccel](#the-markc-windows-mouse-acceleration-fix)
	- [CSGO Notepad++ Theme](#csgo-notepad++-theme)


## Introduction


In this package, you'll find my whole *go-to* setup for Counter Strike Global Offensive, witch include :  

#####Configurations Files  :
- **autoexec.cfg** with all my personal sweet binds and alias
- **video.txt** with low graphic settings (and a custom 1440*1080 4/3 resolution)
- **training.cfg** for flash/smoke practicing (require sv_cheats 1)  

##### Various Tools & Guides :  
- Raw_input Fix for Windows
- CSGO language for Notepad++  
- Link to the amazing VibranceGUI


## Installation  

:warning:  
##### Disclamer :  
**If you need a tutorial for using my autoexec & others things, you should probably stop there.  
You are going to mess with your CSGO Install.**


 If you know how an autoexec work, here's some advices anyway :  
 
 1. [Download ](https://github.com/sh4rkman/CSGO_CONFIG/archive/master.zip)  the package and unzip it.  
   
 2.  Copy & Replace the `cfg` folder to your CSGO config folder (usually `..\Steam\steamapps\CounterStrickGlobalOffensive\csgo\cfg\`   
 
 3.  **Edit autoexec.cfg with your own preference**  
 
	 I use `unbind all` ***then*** re-bind every keys i use in my autoexec. This way i make sure that nothing will move.  You ***have*** to replace my keys with yours in the autoexec, otherwise changes will be lost the next time you launch CSGO. 
	
	Or You can erase all my binds (you lazy fucks, they are great).  
	 
	 ![binds](http://i.imgur.com/C5t4uRX.png?2)

 4.  **Choose your Resolution**   
 


	Copy & Replace `video.txt` into `..\Steam\steamapps\CounterStrickGlobalOffensive\csgo\`  
	
	There is nothing to edit in this file. It contains the lowest/best video settings for the game. If you still want to change some settings because you prefere anti-aliasing x8 or whatever, use the game menu; it will write this file with your changes.
	
	![Vibrance](http://i.imgur.com/KUcpO8l.png)  
	
	FYI, I use a *custom-non-standard* **1440\*1080** resolution in `video.txt`. This is a 4/3 stretched resolution that i like.  If you want to be able to use it, you need to create it first in your Nvidia Control Panel. ([Tutorial here for Nvidia](http://www.nvidia.com/object/custom_resolutions.html))
  
 5. **Setup your launch options**   

	Right-Click CSGO in your Steam library > Options > Launch Options.
	
	##### My Personal CSGO launch options :
	
	> *-novid  -freq 144 -language english*  
	 
	
	**`-novid`** Skip the Valve™ logo & shit at startup  
	**`-freq 144`** force the monitor refreshrate to 144hz. (only if you are using a 144hz monitor. If you have no idea, let get 		it straight : you don't have a 144hz monitor; don't use -freq.)  
	**`-language english`** overwrite english over my french CSGO version  
	
	
	
	##### Others :  
	
	I'm 99,99% sure this options don't do shit but you can still use it if you're into placebo effect
	
	**`-console`** Open Console at startup  
	Was usefull back when Source was the thing. Not anymore.  
	**`-w` & `-h`** resolution  
	It gets forced by autoexec & video.txt anyway    
	**`-high`** high-priority mode  
	Every two months, a random guy on the internet claim that this will make you gain 150FPS.  
	Every two months, 2 thousands people try *-high* and it doesn't do shit. 




## Additional Tools


### Simple Radar

The best CSGO Radar right now.  
You need to check it out if you don't know it yet.


![Simple Radar](http://simpleradar.com/asdf.png?1)

Here you can download our radar for all finished maps. After downloading, you'll have to replace original game files located in 
\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\resource\overviews 

- [Official Website](http://simpleradar.com/ "Dowload")  


### VibranceGUI

If you have an Nvdia GPU (and if you don't you should) you probably want to activate [Digital Vibrance Control](http://www.nvidia.com/object/feature_dvc.html) :

![Vibrance](http://i.imgur.com/ZnDDuFC.png?1)

  
But if you want to activate DVC for CSGO only, you should use the Amazing/Open-source tool **VibranceGui** :

- [Official Website](http://vibrancegui.com/ "Dowload")  
- [Repo on GitHub](https://github.com/juvlarN "Code")  


### The MarkC Windows Mouse Acceleration Fix

Only if you are stuck on a old Windows version  (XP/7/8/8.1), you might want to use MarkC fix for real rawinput.  

Registry Fix for win7+win8 for no mouse accel - 100 DPI
- courtesy of http://donewmouseaccel.blogspot.fr/2010/04/markc-mouse-acceleration-fix-builder.html


### CSGO Notepad++ Theme 


If you are a true autoexec maniac like me, you maybe want this Notepad++ theme :
- Copy the xml file
- Open Notepad++ and go to Language > Define your Language > Import
- Select the file
- Tadaaaaa magic happends

![Screenshot](http://i.imgur.com/a697ncN.png)

