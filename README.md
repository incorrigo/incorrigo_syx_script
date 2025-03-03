# incorrigo_syx_script
A mIRC script created for an UnrealIRCd network, that deploys anope services

## Find us on IRC
Incorrigo Syx IRC network is relatively new, even though it has been around for several years. My favourite IRC client is mIRC, you do the maths.
- ircs://irc.incorrigo.io:+6697/
- https://incorrigo.io/web?ch=westid
- https://incorrigo.io/irc?ch=westid

## Installation Guide
Here are the instructions to install:
- **(a)** Download mIRC
- **(b)** During setup **_check "Run as Portable Application_** and make sure it does
- **(c)** Complete setup, but don't run mIRC
- **(d)** Download the latest copy of Incorrigo Syx
- **(e)** _(i)_ go into the main folder of the archive (where you will find _mirc.ini_)
- _(ii)_ from this position in the repository, select all files and folders and drop them into the same folder as **mirc.exe** ... here's how you do it  
- This link will always give you the most recent files for Incorrigo Syx:  
  https://github.com/incorrigo/incorrigo_syx_script/archive/refs/heads/main.zip  

  Here are the files you need to drag into the **_mirc.exe folder_** and you **must overwrite all files and replace** before you    first run mirc.exe  

  Note that you need to go into the first folder and copy across the **_files and folders selected in the screenshot_**

  ![A screenshot of the files you need to drag in WinRAR](https://incorrigo.io/script/screeni20.png)  
  Once you have done this part, the rest is relatively simple
- **(f)** Overwrite all files, replacing them from the archive as detailed above
- **(g)** Run _mirc.exe_ ... you may need to use your registration code to continue
- **(h)** This is the part where the script kicks in and gives it to you

Some of the messages / the way that things are laid out might come across as _patronising_. But I prefer the term _better_. I will try to keep up with IRC each time it is re-made in another very competitive way

## The Network
It's quite simple to detail the features of the network - it's a map of nodes running the latest stable UnrealIRCd and a network manager in the form of anope services. But to us, it's more than that. It's a text based virtual world.

## This Script
There are a number of targets that have been reached by this classic honest-to-god script for mIRC, and this has led to some defining results not possible with other scripts

### IRCv3 +draft/reply Supported by mIRC
* Update: +reply now supported also  
There is no reason to suspect that this feature - already successfully implemented and supported by a range of leading IRC clients in the v3 movement - awaits any further refinement than removing _draft/_ from the tag name. So now +reply is supported as well (but it will only process one of these tags, not both of them, so don't get clever)
  
mIRC now officially supports +draft/reply= and it's all thanks to this glorious script. It works with other clients in exactly the same way that they support it  
![A screenshot demonstrating the original layout of the completed +draft/reply implementation once it had successfully met all of the specifications and confirmed as being compatible with any other client](https://incorrigo.io/script/screeni11.png)  

This felt like something that was going to elude mIRC for a while but some classic features it supported already for many years, combined with chat history playback / playback on join, made it quite straightforward to implement and in just the right compatibility to function well with other clients  

### Away Manager Reminders
It's difficult to tell you the good points about our script without mentioning **_away manager_**, which brings raw functionality right down to the command level so when someone mentions your name in a channel that you're on, they can be certain their witty retort to what you said a few hours ago definitely didn't land
![Away manager control panel console with convenient reminders that will not replace server away messages](https://incorrigo.io/script/screeni18.png)

### Opt-out Readable Mode Activity
Modes seldom change throughout the course of a given day when in an IRC session, especially when it's gone full on idle for days. Considerable care has gone into showing you the permissions that were altered as a result of a mode change. This feature is for new users primarily, and can be switched off completely in one click
![An example of how mode activity can be simplified to report only what matters is going on in the channel](https://incorrigo.io/script/screeni14.png)

### Your Journey Starts Here
Unfortunately I can't provide anyone with [mIRC](https://www.mirc.com/) and it is not free software. You will have to make that arrangement separately - but once you have done, this script will give you your money's worth

### Release notes for 2025-03-03 -- v2.1a8

https://github.com/incorrigo/incorrigo_syx_script/releases/tag/v2.1a8

### Release notes for github debut -- v2.1a7

https://github.com/incorrigo/incorrigo_syx_script/releases/tag/incorrigo-syx
