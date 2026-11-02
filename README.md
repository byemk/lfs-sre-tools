# LFS SRE Tools for Blender

Import, edit and export Live for Speed vehicle-editor `.sre` models in Blender 4.2 or newer.

- Open any `.sre` from your LFS `data\3dob` folder, see it with the LFS look, edit it with Blender's modelling tools and export it back for the vehicle editor.
- Parts you do not touch are written back byte for byte; edited parts keep their maps, mirror flags, LODs and smoothing groups.
- Dish / curve wheels, smoothing-group tools, texture baking for models from other formats (FBX, OBJ...).

## Install (with automatic updates)

1. Open **https://byemk.github.io/lfs-sre-tools/**
2. Drag the **lfs_sre_tools** link from that page onto your Blender window and confirm.
3. Blender shows an update button whenever a new version is out (it needs *Allow Online Access* in Preferences > System).

Or: Preferences > Get Extensions > Repositories > **+** > *Add Remote Repository* and paste `https://byemk.github.io/lfs-sre-tools/index.json`.

A copy installed by dragging the zip file in by hand does not update itself - remove it and install from the link.

## Guide

- [Illustrated guide (web page)](LFS_SRE_Tools_Guide.html) - also as [PDF](LFS_SRE_Tools_Guide.pdf)
- [One-page quick start (PDF)](LFS_SRE_Tools_Quick_Start.pdf)

## Credits and licence

Made by Mk (Discord @byeeeeeeeeeeeeeeeeeeeeeeeeeeeeee), with code and guide written together with Claude.
GPL-3.0-or-later, see [LICENSE](LICENSE). A fan-made tool, not made by or connected to the Live for Speed developers.
