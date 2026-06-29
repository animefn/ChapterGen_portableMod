# ChapterGen_portableMod.rar
A ChapterGen 1.0.8 mod that is fully portable





## About ChapterGen
Chaptergen is a simple chapter editor. Manipulate with chapters in various i/o formats, with CLI support. Additional features: Converting between framerates, Stream selector when Blu-Ray, HD DVD, DVD media or folder selected, Command line support, Drag & Drop support.



##Download:
To download this version: https://github.com/animefn/ChapterGen_portableMod/archive/refs/tags/1.08.zip
Original source for this software: https://www.videohelp.com/software/ChapterGen

## What changed in this version:
In the original version the manifest explicitly requires the execution level to be `requireAdministrator` (aka requires admin priveleges to simply run the portable executable file), I have simply recompiled a new binary, that is really a true portable mod that runs as Invoker (i.e works for non-admin users). Everything else was left untouched and nothing in the software itself was changed or improved.

## My motivation behind this repo
The tool is just simply great, it never got the publicity it deserved.

It supports converting between different chapter formats, the main motivation for me was to convert chapters from DVD .ifo files to mkv supported format such as OGG txt as well as extracting X264 QP text file.


### List of accepted input formats (inferred from GUI, not confirmed):
- Supported Files
- OGG Chapter Files (*.txt)
- Celltimes Files (*.txt)
- Blu-Ray Playlist (*.mpls)
- HD-DVD Playlist (*.xpl)
- DVD Playlist (*.ifo)

### Full list of support output formats:
- OGG Text File
- x264 QP Text File
- HC Enc Text File
- CCE SP Text File
- Sonic Cinevision CSV File
- Sonic Scenarist CSV File
- Spruce DVD Maestro CHP File
- tsMuxer Meta File
- Timecodes Text File
- Celltimes Text File
- DVDAuthor Text File
- Muxman

For cli usage refer to CMDhelp.txt file

## Screenshots:

<img width="247" height="332" alt="Screenshot 2026-06-29 154853" src="https://github.com/user-attachments/assets/7ea37599-0b54-4421-a4ad-b295007d08fa" />

<img width="397" height="330" alt="Screenshot 2026-06-29 154606" src="https://github.com/user-attachments/assets/7f3e1fea-dc1e-4159-af25-0c8489e7260f" />
