  # DivaDocs
  WIP documentation for Project Diva F 2nd modding

  this repository serves as a hub for documenting discoveries, tools formats and other useful info to assist with modding *Hatsune Miku: Project Diva F 2nd* on original hardware. the repository will be updated as new info is discovered.

  ## current findings
  - the game uses common formats like `.avc`, `.ogg` and `.psarc`, as well as proprietary formats specific to SEGA like `.farc` (possibly standing for File Archive?)
  - the game installs assets on first launch. comparing the installed data size with the `data.psarc` file reveals that those files will likely have to be modified on disk
  - `data.psarc` features encrypted `.farc` files, as well as a few `.txt` files encrypted with the custom DIVAFILE protocol
  - DIVAFILE's decryption routine can be found within the Japanese copy of the game
  - stage lighting is stored in "XX###_STAGE.LIT" as well as fog parameters in "XX###.FOG"

  ## tools
  useful tools to help with manipulating and packing files:
  - QuickBMS - all purpose general archive unpacking/repacking with game/format specific scripts (in this case, the Virtua Fighter 5 script)
  - UnPSARC - `.psarc` file unpacking
  - ffmpeg - media format transcoding (`.avc` and `.ogg`)
  - ps3dec - `.iso` decryption and extraction
  - multiMAN - general purpose back-up and file manager for PS3

  # to-do
  - [x] investigate `.LIT` and `.FOG` files
  - [ ] check if removing data.psarc changes anything after the install process is completed
  - [x] find out why QuickBMS complains about the file header being `FARC` instead of `FArC`

  # contributing
  if you have any knowledge on this game's inner workings, either submit a pull request with your findings or contact @memroyleak on Discord