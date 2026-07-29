# Source code library for the Elite Universe Editor

<details>
<summary>Links to my other software archaeology repositories</summary>
<hr>

**Elite sources:** [BBC Micro (cassette)](https://github.com/markmoxon/elite-source-code-bbc-micro-cassette) | [BBC Micro (disc)](https://github.com/markmoxon/elite-source-code-bbc-micro-disc) | [Elite Demonstration Disc](https://github.com/markmoxon/elite-demo-source-code-bbc-micro) | [Acorn Electron](https://github.com/markmoxon/elite-source-code-acorn-electron) | [6502 Second Processor](https://github.com/markmoxon/elite-source-code-6502-second-processor) | [Commodore 64](https://github.com/markmoxon/elite-source-code-commodore-64) | [Apple II](https://github.com/markmoxon/elite-source-code-apple-ii) | [BBC Master](https://github.com/markmoxon/elite-source-code-bbc-master) | [NES](https://github.com/markmoxon/elite-source-code-nes)

**Elite hacks:** [Elite-A](https://github.com/markmoxon/elite-a-source-code-bbc-micro) | [Teletext Elite](https://github.com/markmoxon/teletext-elite) | [Elite 3D](https://github.com/markmoxon/elite-3d) | [Elite Universe Editor](https://github.com/markmoxon/elite-universe-editor) | [Flicker-free Commodore 64 Elite](https://github.com/markmoxon/c64-elite-flicker-free) | [Elite over Econet](https://github.com/markmoxon/elite-over-econet) | [!EliteNet](https://github.com/markmoxon/elite-over-econet-acorn-archimedes)

**Elite Compendium:** [BBC Master](https://github.com/markmoxon/elite-compendium-bbc-master) | [BBC Micro](https://github.com/markmoxon/elite-compendium-bbc-micro) | [BBC Micro B+](https://github.com/markmoxon/elite-compendium-bbc-micro-b-plus) | [Acorn Electron](https://github.com/markmoxon/elite-compendium-acorn-electron)

**Other sources:** [Aviator (BBC Micro)](https://github.com/markmoxon/aviator-source-code-bbc-micro) | [Revs (BBC Micro)](https://github.com/markmoxon/revs-source-code-bbc-micro) | [The Sentinel (BBC Micro)](https://github.com/markmoxon/the-sentinel-source-code-bbc-micro) | [Lander (Acorn Archimedes)](https://github.com/markmoxon/lander-source-code-acorn-archimedes)

**Other repositories:** [Scripts for generating bbcelite.com](https://github.com/markmoxon/bbcelite-scripts) | [Static content for bbcelite.com](https://github.com/markmoxon/bbcelite-websites) | [Elite source code library](https://github.com/markmoxon/elite-source-code-library) | [Elite Universe Editor library](https://github.com/markmoxon/elite-universe-editor-library) | [Elite over Econet fileserver menu](https://github.com/markmoxon/elite-over-econet-fileserver-menu)

See [my profile](https://github.com/markmoxon) for more repositories to explore.
<hr>
</details>

This repository contains a source code library for the Elite Universe Editor. It contains code that is common to all versions of the Universe Editor:

* [BBC Master Elite Universe Editor](https://github.com/markmoxon/elite-universe-editor-bbc-master)
* [6502 Second Processor Elite Universe Editor](https://github.com/markmoxon/elite-universe-editor-6502-second-processor)
* [Commodore 64 Elite Universe Editor](https://github.com/markmoxon/elite-universe-editor-commodore-64)

It is also used when building the combined Universe Editor disc and the Elite Compendium:

* [Elite Universe Editor](https://github.com/markmoxon/elite-universe-editor)
* [Elite Compendium (BBC Master)](https://github.com/markmoxon/elite-compendium-bbc-master)
* [Elite Compendium (BBC Micro)](https://github.com/markmoxon/elite-compendium-bbc-micro)

In all cases, the library code is included in the repository as a submodule.

## Acknowledgements

6502 Second Processor Elite was written by Ian Bell and David Braben and is copyright &copy; Acornsoft 1985.

The 6502 Second Processor code on this site is identical to the source discs released on [Ian Bell's personal website](http://www.elitehomepage.org/) (it's just been reformatted to be more readable).

BBC Master Elite was written by Ian Bell and David Braben and is copyright &copy; Acornsoft 1986.

The BBC Master code on this site has been reconstructed from a disassembly of the version released on [Ian Bell's personal website](http://www.elitehomepage.org/).

Commodore 64 Elite was written by Ian Bell and David Braben and published by Firebird, and is copyright &copy; D. Braben and I. Bell 1985.

The commentary is copyright &copy; Mark Moxon. Any misunderstandings or mistakes in the documentation are entirely my fault.

Huge thanks are due to the original authors for not only creating such an important piece of my childhood, but also for releasing the source code for us to play with; to Paul Brink for his annotated disassembly; and to Kieran Connell for his [BeebAsm version](https://github.com/kieranhj/elite-beebasm), which I forked as the original basis for this project. You can find more information about this project in the [accompanying website's project page](https://elite.bbcelite.com/about_site/about_this_project.html).

The following archives from Ian Bell's personal website form the basis for this project:

* [6502 Second Processor sources as a disc image](http://www.elitehomepage.org/archive/a/a5022201.zip)

* [BBC Elite, Master version](http://www.elitehomepage.org/archive/a/b8020001.zip)

The Commodore 64 game disks in this repository are very similar to those released on [Ian Bell's personal website](http://www.elitehomepage.org/), but to ensure accuracy to the released versions, I've used disk images from the [Commodore 64 Preservation Project](https://archive.org/details/C64_Preservation_Project_10th_Anniversary_Collection) (it turns out that the disk images on Ian Bell's site differ slightly from the official versions). The Commodore Plus/4 version is based on the disk image from Ian Bell's site.

# A note on licences, copyright etc.

This repository is _not_ provided with a licence, and there is intentionally no `LICENSE` file provided.

According to [GitHub's licensing documentation](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/licensing-a-repository), this means that "the default copyright laws apply, meaning that you retain all rights to your source code and no one may reproduce, distribute, or create derivative works from your work".

The reason for this is that the Universe Editor is intertwined with the original source code for Elite, and the original source code is copyright. The whole site is therefore covered by default copyright law, to ensure that this copyright is respected.

Under GitHub's rules, you have the right to read and fork this repository... but that's it. No other use is permitted, I'm afraid.

My hope is that the educational and non-profit intentions of this repository will enable it to stay hosted and available, but the original copyright holders do have the right to ask for it to be taken down, in which case I will comply without hesitation. I do hope, though, that along with the various other disassemblies and commentaries of this source, it will remain viable.

---

Right on, Commanders!

_Mark Moxon_