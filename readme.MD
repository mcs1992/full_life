# Full-Life

Mod for proposing marriage.

## Tools

- [VHLT version 34](https://sites.google.com/site/gshltools/compiler-tools) - for map compiling
- [GIMP VTF](https://github.com/Artfunkel/gimp-vtf) - to export from gimp to vtf
- [Wally](https://valvedev.info/tools/wally/) - for vtf and vmt management and compile to wad.

## Compile

- Images max size is 512x512.
- Export xcf image as bmp in GIMP. Make sure `Image > Mode > Indexed` is checked. When exporting, make sure `Compatiblity Options > Do not write color space information` is checked.
- Blender material should be named as the bmp image.
- Export xcf image as vtf. No options different than default for now.
- Copy WAD to mod folder, and to valve folder.
- Add WAD from valve folder to map file (c1a0).