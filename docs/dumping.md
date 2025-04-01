# Dumping Guide
this guide will walk you through the basic process of dumping the game using **multiMAN**. you are free to use any other backup manager if you so choose, as long as it has the ability to dump folder games.

## Intro
dumping the game to an external drive will significantly speed up file management as opposed to manually transferring files onto the console every time something is modified. it can also be used to avoid destructive editing.

## What You'll Need
- a PS3 with either Custom Firmware (CFW) or Homebrew Enabler (HEN)
- a copy of Diva F 2nd
- an external drive formatted as FAT32 with at least 5-6 GB of free space

## Step 1: Dump the Game
if you have a physical copy of Diva F 2nd, follow this process:
1. install multiMAN if you haven't already.
2. insert the disc into your console. 
3. open multiMAN and locate the game. it should be the first entry in the list.
4. hit the △ button and select Backup/Copy.
5. multiMAN will ask you where you'd like to dump the game. insert a thumb drive or external hard drive and select it. multiMAN will automatically make a GAMES folder, where your game will be dumped.

if you have a digital copy of Diva F 2nd, follow this process:
1. install multiMAN if you haven't already.
2. open multiMAN and hit R1. this should bring you into desktop mode.
3. double click the "PS3 Root" icon and find the "game" folder.
4. select the "BLUS34131" folder and hit the ○ button: this will bring up a context menu. select Copy.
5. navigate to your external drive, press ○ again and select Paste.
6. wait for the process to finish: this could take a while, since external drive speed maxes out at around 20MB/s

## Step 2: Locate the Files
finally locate the files which should now be on your external drive. if you did everything right, you should have 2 folders and a file in the game's root.

you're ready to start modifying files!

## Appendix: ISO Dump
you could also dump the game as an ISO, but that introduces extra steps. if you're using a FAT32 drive your ISO will be split due to the 4GB file limit, having to recombine the ISO and decrypt it after. the recommended method is to dump the game as a **folder game**.