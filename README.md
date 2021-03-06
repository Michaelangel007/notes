# Notes

[![Join the chat at https://gitter.im/sanctuary/notes](https://badges.gitter.im/sanctuary/notes.svg)](https://gitter.im/sanctuary/notes)

The aim of this project is to organize and cross-reference a collection of notes related to the inner workings of the Diablo 1 game engine. The initial work has focused on creating a foundation and high-level structure (think documentation skeleton) for organizing these notes. A few function declarations and global variable declarations have already been documented, but mainly to provide a reference for how the structure of the documentation may look like. Future work will focus on documenting the remaining relevant function declarations, global variable declarations, structure definitions and enumerate definitions of the Diablo 1 game engine.

The notes are currently organized into the following categories.

* [Functions](functions/README.md): function declarations.
* [Global variables (read-only)](rdata/README.md): global variable declarations in the read-only data section.
* [Global variables (read-write)](data/README.md): global variable declarations in the read-write data section.
* [Global variables (uninitialized)](bss/README.md): global variable declarations in the uninitialized data section.
* [Structures](structures.md): structure definitions.
* [Enumerates](enumerates.md): enumerate definitions.
* [Storm ordinals](storm.md): Storm.dll function declarations based on ordinal numbers.

## Progress

| Category                                          | Progess                        |
|---------------------------------------------------|--------------------------------|
| [Functions](functions/README.md)                  | 12% (243/1955 functions)       |
| [Global variables (read-only)](rdata/README.md)   | 94% (26804/28372 bytes)        |
| [Global variables (read-write)](data/README.md)   | 95% (187436/196860 bytes)      |
| [Global variables (uninitialized)](bss/README.md) | 22% (468048/2048516 bytes)     |
| [Storm ordinals](storm.md)                        | 63% (37/58 functions)          |

The README of each sub-project tracks the progress for each of its source files.

## Contributing

Anyone interested in contributing to the project may do so in whichever way they desire. This may include:

1. Provide ideas on how to better structure the information
2. Point out mistakes or inconsistencies in the notes
3. Improve the existing notes
4. Add documentation for
	- function declarations (e.g. [drlg_l1_place_door](https://github.com/sanctuary/notes/blob/master/functions/drlg_l1.md#0x40b56f))
	- global variable declarations (e.g. [cathedral_stairway_down_piece_ids](https://github.com/sanctuary/notes/blob/master/data/trigs.md#0x4b3008))
	- structure definitions (e.g. [Shadow](https://github.com/sanctuary/notes/blob/master/structures.md#shadow))
	- enumerate definitions (e.g. [quest_level](https://github.com/sanctuary/notes/blob/master/enumerates.md#quest_level))
5. ...

## Credits

None of this work would have been possible without [Jarulf's Guide to Diablo and Hellfire](http://www.lurkerlounge.com/diablo/jarulf/jarulf162.pdf), one of few truly amazing resources on the Internet.

## Public domain

The source code and any original content of this repository is hereby released into the [public domain].

[public domain]: https://creativecommons.org/publicdomain/zero/1.0/
