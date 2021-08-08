## OSD32MP1-BRK Kicad project

This is a Kicad project for the OSD32MP1-BRK breakout board from Octavo Systems. 
It requires Kicad v5.99 or later (aka Kicad 6). 

I converted the Altium project files for this board as best I could, using Kicad's built-in Altium importer.
The Kicad project here passes ERC and DRC, and has sane project settings (track thickness, clearance, etc.). You can view the steps I had to take to manually correct the automatic import script by viewing the git commit log.

The symbols and footprints are all extracted from the Altium project.

There are some minor font differences on the silk-screen layers, and the zones may have different clearances. I do not have access to the original gerbers, so I haven't compared them.
I have not produced this board (nor do I intend to), so I don't know if it even works.

#### Disclaimer:
I am in no way associated with Octavo Systems, and the files in this repository may contain errors or have issues, so I make no warranty as to anything. I also make no claims to ownership.
I believe I am allowed to publish this under the same license as the original files, but if I am incorrect then I will remove this repository.

The OSD32MP1-BRK Altium files are available on Octavo Systems website [here](https://octavosystems.com/octavo_products/osd32mp1-brk/#Design%20Files).



