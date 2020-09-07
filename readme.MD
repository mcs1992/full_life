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

## The good documentation <3

Nothing beats looking at the original Half Life code

- http://the303.org/tutorials/gold_mdl_fix.htm
- https://superuser.com/questions/678434/export-file-as-palleted-8bit-per-pixel-bmp-from-gimp/678886#:~:text=Yes%2C%20in%20GIMP%20you%20can,it's%20a%20quite%20simple%20operation.&text=8%20bit%20image%20means%20256,palette%20could%20be%20modified%20afterwards.
- https://twhl.info/thread/view/17115?page=1#post-284066
- https://twhl.info/wiki/page/Tutorial%3A_Modelling_for_Goldsource
- https://twhl.info/wiki/page/Tutorial%3A_Source_Modelling_Setup (might be too new to be good)
- https://developer.valvesoftware.com/wiki/Studiomdl (newer version, a lot of stuff here is not needed, for example, the `-game` flag)


C:/Program Files (x86)/Steam/steamapps/common/Half-Life/full_life/models/goose.mdl