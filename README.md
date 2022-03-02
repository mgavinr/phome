# phome
Rules for Project Management
* Featrues listed are tagged DEV if any dev work otherwise they are like testing or integration work, or mechanical building, or purchasing tasks.
* Features without a name beside them can be grabbed
* Features have DONE somewhere when done, move them to the bottom when done
* Features have a ||||| where each bar means half a days work done on them
* Featuers have an indent if they need something to be done first before they can start
* Features are small amounts of work ideally <10
* Notes are notes that need not be read

Tasks are as above, but are small things like bugs or something that are deleted once done, except if they are post release.

No more rules, is a rule.  The introduction should date and time and describe the major releases.

<!--ts-->
   * [phome](#phome)
   * [Hardware](#hardware)
      * [Study](#study)
      * [Hot air baloon](#hot-air-baloon)
      * [Creeper](#creeper)
         * [Features](#features)
         * [Tasks](#tasks)
      * [Darts board](#darts-board)
      * [Golf tracker](#golf-tracker)
      * [Outdoor disco](#outdoor-disco)
         * [Tasks](#tasks-1)
      * [Gardening Goal Zero Timer](#gardening-goal-zero-timer)
         * [Notes](#notes)
         * [Features](#features-1)
      * [Gardening HUB](#gardening-hub)
      * [Gardening Watering Device Basic](#gardening-watering-device-basic)
         * [Features](#features-2)
      * [Gardening Watering Device Luxuary](#gardening-watering-device-luxuary)
         * [Features](#features-3)
      * [Gardening reading station](#gardening-reading-station)
      * [Gardening weather station](#gardening-weather-station)
      * [Gardening hose device](#gardening-hose-device)
         * [Features](#features-4)
   * [Amiga](#amiga)
      * [Study](#study-1)
      * [Soft: Putty and friends remake](#soft-putty-and-friends-remake)
      * [Soft: Alien](#soft-alien)
      * [Soft: XOut Murders](#soft-xout-murders)
      * [Hard: Music](#hard-music)
      * [Hard: Clockports](#hard-clockports)
      * [Hard: PCI](#hard-pci)
         * [Features](#features-5)
      * [GUI and multiplatform Dev Env](#gui-and-multiplatform-dev-env)
         * [Notes](#notes-1)
         * [Features](#features-6)
         * [Task](#task)
   * [PC](#pc)
      * [Website](#website)
      * [Paint package](#paint-package)
      * [Ressurection](#ressurection)
      * [GHIDE](#ghide)
   * [ANDROID](#android)
      * [Diary of the worlds most angriest man](#diary-of-the-worlds-most-angriest-man)
      * [Vaxine remake](#vaxine-remake)

<!-- Added by: gavinr, at: Sun Apr 25 19:02:26 IST 2021 -->

<!--te-->

---

Hardware
===========
Should try some sort of order here...

Study
-------------------------
This is a catchall for study not related to any project

* 2021 DEV ||||

Hot air baloon
-------------------------
We need a hot air baloon and camera to observe the plants.  It will be controllable by 5V fans or fins for the outside one.  It also should be able to go outside and be tied down with fishing wire or something.

Creeper
-------------------------
The creeper version one was released in October 2019.

### Features ###
* [DEV] add proper sounds
* [DEV] better battery life for mist

### Tasks ###
* No bugs

Darts board
-------------------------
I will create a darts board

Golf tracker
-------------------------
I have no memory of my shots so bought a rosery bead for golf.  Unfortunetly I have no memory for that either and forget to push the beads around.  Therefore I will create an automatic golf scoring distance thingymagig, that other people have made.

Outdoor disco
-------------------------
I will create a pi/ard light based music lightshow disco dance floor, outdoors.  I have the space already.

### Tasks ###
* Get the floor (I have already confirmed the size) has to be waterproof
* Get the lights
* Get the power?
* [DEV] Ard/pi it

Gardening Goal Zero Timer
-------------------------
Create a device that can turn on a Goal Zero USB PLUG or CIG socket via a button or timer, as the original buttons are either covered, and do not have a timer feature.

### Notes ###

My solenoid with 12v AA battery 1300mA could not push the on/off buttons, it was successful 1/10 times.  I thought maybe making a magnet that would repel the button with enough force that that would work but no; I created the magnet and turned it on.  It was successful and lifted something almost as big as the coil around which it was wound.  Unfortunetly it had zero to no repelling force.  I switched to 1850 batteries instead of AA ones, and it now pushes the on/off buttons aok.  So .. 

### Features ###
* [DEV] a USB powered device and a AA battery backup device with a light indicating when USB is gone [||]
* [DEV] Investigate low power modes
* [DEV] A on off button is needed individually for each device
* [DEV] A 7 segment display timer is needed along with buttons to control it
*   Create a case for the above

Gardening HUB
-------------------------
A Hub is needed to display the gardening stuff, with alexa, spotify, and online web page.

Gardening Watering Device Basic
-------------------------
A pump will be used to water the large seed bed.
A pump will be used to water the heated seed bed too.
So two pumps needed.

### Features ###
* [DEV] Turn on water when the time says so [||]
* [DEV] Turn on water when the soil moisture sensor says dry
* [DEV] Add a temperature sensor, and a soil temperature sensor
* [DEV] Talk to the hub with feedback status, via .. 
* --Case needed

Gardening Watering Device Luxuary
-------------------------
As above but also capable of watering a stack of shelves each pot individually. You could have individual pumps, but that's alot of batteries, I guess you could switch over the battery to each pump?  Or 1 pump that splits out the tube and water everything, but then somethings drown.  So I propose a rail system vertical lane and 5 horizontal lanes, with motors.  And each pot is indivudally addressable and waterable, then thing then just uses 1 pump, 1 water soil sensor and wheels, goes around and checks each pot. Ahaha ha ha ha.

### Features ###
* [DEV] Motor control vertical, we can skip horizontal and individually for v2
* [DEV] Is switchable battery and many pumps possible too
* [DEV] Ability to insert a soil moisture sensor in each pot, or each pot already has one and it just connects to it.
* --Case needed, wheel tracks needed

Gardening reading station
-------------------------
A device that does no watering as that would need a large pump, but one that measures temperature of air, soil, and humidity and fowards it to the hub for review.  It works indoors and outdoors.

Gardening weather station
-------------------------
Aswell as the above, need a wind speed, and direction and rain device.

Gardening hose device
-------------------------
A device that times a hose.  Everyone I've bought broke, so you have nothing to live up to hear.  Can you also build one that doesn't drip constantly?  Expect millions of investment if you can.  My USP this device will be inline.  Inline??? wow, big bucks on the way.

### Features ###
* [DEV] Use battery knowledge from above 
* [DEV] use the other pump thing that needs x PSI
*   Case needed, need to prototype one first in any mat
*   Case needed, redisgn in 3D and waterproof it

---

Amiga
===========

Study
-------------------------
This is a catchall for study not related to any project

* 2021 DEV 

Soft: Putty and friends remake
-------
I proposed to make putty with friends.

Soft: Alien
-------
I also proposed to make alien

Soft: XOut Murders
-------
I have an idea here

Hard: Music
-------
A music studio with MIDI and a custom built drum machine

Hard: Clockports
-------
Connect the clockport to an Ard or Pi.

Hard: PCI
-------
Develop a PCI card, probably to start with something that can address a pi or ard.

### Features ###
* Maybe also get a linux box to help with the development, I have no linux box with pci card slots

GUI and multiplatform Dev Env
-------
Need a dev environment that uses modern tools like git and backups and IDEs.  I used to use Samba at work, but found that Amiga Samba is a bit old and does not support samba filesystem on linux, and is more like ftp.  Then I discovered ftp can work as a filesystem on linux so, here is to create a dev environment, ideally Amiga centered, rather than unix centered, as it currently is, as I find I don't really use the amiga.  So the idea is:
```
      [                 ]     [                         ]
      [ Amiga Monitory  ]     [  PC Widescreen          ]
      [   4.3 non rtg   ]     [                         ]
      [                 ]     [                         ]  VESA RPi4 === ethernet
            DVI                                

                             DVI  MOUSE      
                  [                        ]
                  [  Amiga 1200 Wedge      ] 
                  [                        ]
       wifi       [                        ]
       or prefer  [                        ]
       ethernet===[                        ]
                  [                        ]
```

And you would control the PI with synergy from the Amiga Mouse and Keyboard.  It would then encourage you to use the Amiga rather than a PC centered dev environment.  Though who knows.. you'd be using PC tools.. anyway lets see what it will turn out like:
### Notes ###

Started a trad gtk ui, it was going slowly so switched to a web ui.  The UI should not be needed for anything.

### Features ###
* [DEV] Create a filesystem on linux of the amiga [DONE]
* [DEV] Create a GUI for the above [||] but should finish it [ABANDONED]
* [DEV] Create a WEBUI for the above [||||]
*       [DEV] Create a Linux SERVICE/PACKAGE for the above  [NEARLY DONE,OHDEAR|||||]
* [DEV] Create a Amiga SERVICE/PACKAGE for the above 
* [DEV] Create synergy on amiga
* [DEV] Autoboot RPI/unix settings for automatically connecting to amiga polling on startup [NEARLY DONE]
* Create a video cross compilers with the above
* Create a video or something using ide with amiga compilers, a reverse rabit hole?  Fox hole i will call it..
* Create a video or something QT amiga gui building
* Create a video or something Gadtools amiga gui building
* Create a video or something AROS gui building
* Create a video or something Your mans new thing for AROS MUI is it
* Create a video or something as all the above but on windows

### Task ###
* FTP filesystem on PC does not work for some god unknown reason

---

PC
===========

Website
-------
Do a website

Paint package
-------
I had an idea here, I have since forgotten it..

Ressurection
-------
You could resurrect your old projects and see what's there.

GHIDE
-------
Version 1 was released ...

---

ANDROID
===========

Diary of the worlds most angriest man
-------
Create a journal app that creates a PDF book automatically for printing.

Vaxine remake
-------
Don't forget to do this sometime with tilt access.
