# pkg

Package tool for 
- build , build file from definition to artifact.
- install, adding package to system (`pkgadd`) and connect it with ecosystem (`pkgset`).
- remove, remove symlink (`pkgset`) and remove it artifact (`pkgdel`)
- query, looking information about the packages (`pkginfo`)
- serve, serve you package reserve to other a.k.a be a motherepo (`pkgsrv`)

Kartini adopt GoboLinux Filesystem Hierarchy as it filesystem layout, so this script might be work only here.

Philosophy:
- Compile, archive file, extract archive, symlinks

This package tool inspired by pkgutil from CRUX Linux, KISS Linux package system and GoboLinux tool.

## How to Run

- Install janet interpreter.
- Just run script `./<script>`

## Contribution

- Follow contributor convenat.
- If you found bug or want to improve this piece of code then welcome but create issues ticket in this repo first.
- If you familiar with the usage of this code then want to improve but no have idea how, here I give one. This script role is mainly a backend package manager, just CRUD to your filesystem not frontend that does dependencies checking and sort of that make live easier. then make one to improve UX and utilize this code for handle job with filesystem.