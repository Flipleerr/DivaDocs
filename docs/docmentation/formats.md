# Formats
a guide to the more obscure file formats found in Project Diva F 2nd.

|format|extension| notes|
|------|---------|------|
|FARC|.farc|proprietary file archive format|
|PSARC|.psarc|archive format found in many games on PS3 and later|
|Cg Shaders|.fp/.vp|Nvidia's flavor of HLSL, found in `shaders_ps3.farc`|
|TXI|.txi|texture atlas/database|
|TXD|.txd|texture data|
|OSI|.osi|object database|
|OSD|.osd|object data|
|DIVAFILE|any extension|proprietary single file encrypted archive|
|LITC|.lit|stage lighting data|
|FOGC|.fog|fog parameters|
|DLT|.dlt|DLC config|
|BIN|.bin|used in DLC to, for example, control an item's price in the shop|

## Tools
- `.farc`: QuickBMS, farc (diva-rust-modding)
- `.psarc`: UnPSARC
- Cg Shaders: none as of now, but a disassembler probably exists in Cg Toolkit
- `.txi/.txd/.osi/.osd`: MikuMikuLibrary
- DIVAFILE: DIVAFILE_Tool
- `.lit`: none, as of now
- `.fog`: none, as of now
- `.bin`: any code editor, QuickBMS, farc (diva-rust-modding)

## Caveats
- `.farc`: the farc tool does not decrypt archives. use QuickBMS if an error is thrown
- `.lit` and `.fog`: while their purpose is known, how to modify them is not. they are currently under investigation
- `.dlt`: while the file's contents are just ASCII, it also features boilerplate which can be automated.
- `.bin`: these files are always wrapped in a `.farc`