# latexal
### A bash-tool for copiling LaTeX remotely over ssh
Olle Logdahl, 10 March 2020

[![made-with-bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)](https://www.gnu.org/software/bash/)
![licence](https://img.shields.io/github/license/ollelogdahl/latexal)
![issues](https://img.shields.io/github/issues-raw/ollelogdahl/latexal)

---

**latexal** is a bash script for remotely compiling LaTeX documents.

The script comes packaged along with **latexal_s**, run on remote.

## Installation

Depends on *pdflatex*, make sure it's installed on remote.
`pacman -S texlive-bin`

After installation, run 
`latexal update <hostname>` to update remote with remoteside script.

### Constants may be modified!
- `$STDPATH` points to standard include folder. All files in this directory will be copied to remote on `latexal update`, and included to every project built.

## Usage

`latexal update <hostname>` for updating remote with std/ resources.

`latexal build <hostname> <filename>` for building project.

## Licensing

This project, and all code it contains, is licensed under *The Unlicense* and can be read [here](UNLICENSE).
