# LFS SRE Tools for Blender

Import, edit and export Live for Speed vehicle-editor `.sre` models in Blender 4.2 or newer.

- Open any `.sre` from your LFS `data\3dob` folder, see it with the LFS look, edit it with Blender's modelling tools and export it back for the vehicle editor.
- Parts you do not touch are written back byte for byte; edited parts keep their maps, mirror flags, LODs and smoothing groups.
- Dish / curve wheels, smoothing-group tools, texture baking for models from other formats (FBX, OBJ...).

## Install (it updates itself afterwards)

1. Blender 4.2 or newer: *Edit > Preferences > System*, tick **Allow Online Access**.
2. *Preferences > Get Extensions*, the arrow menu at the top right > *Repositories* > **+** > *Add Remote Repository*.
3. Paste `https://byemk.github.io/lfs-sre-tools/index.json`, tick **Check for Updates on Startup**, click *Create*.
4. Search **LFS** in Get Extensions and click **Install**. The tools are in the 3D View sidebar (press N), tab *LFS*.

Blender then shows an **Update** button in Get Extensions whenever a new version is out.
Website: https://byemk.github.io/lfs-sre-tools/ - its *lfs_sre_tools* link can also be dragged onto Blender (not every browser supports that).
A copy installed by dragging the zip file in by hand does not update itself - remove it and install as above.

## Guide

- [Illustrated guide (web page)](LFS_SRE_Tools_Guide.html) - also as [PDF](LFS_SRE_Tools_Guide.pdf)
- [One-page quick start (PDF)](LFS_SRE_Tools_Quick_Start.pdf)

## Credits and licence

Made by Mk (Discord @byeeeeeeeeeeeeeeeeeeeeeeeeeeeeee), with code and guide written together with Claude.
GPL-3.0-or-later, see [LICENSE](LICENSE). A fan-made tool, not made by or connected to the Live for Speed developers.
