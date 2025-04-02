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

## Tools
tools to extract most files:
- `.farc`: QuickBMS, farc (diva-rust-modding)
- `.psarc`: UnPSARC
- Cg Shaders: none as of now, but a disassembler probably exists in Cg Toolkit
- `.txi/.txd/.osi/.osd`: MikuMikuLibrary
- DIVAFILE: DIVAFILE_Tool
- `.lit`: none, as of now
- `.fog`: none, as of now
