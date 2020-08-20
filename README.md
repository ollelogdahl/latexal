# latexal
### A tool for copiling LaTeX remotely
Olle Logdahl, 10 March 2020
---
**latexal** is a bash script for remotely compiling LaTeX documents.

The script comes packaged along with **latexal_s**. This is the serverside, and is to be installed on server.

## Usage

**latexal update hostname** for updating remote with std/ resources.

**latexal build hostname filename** for building project.

## Installation

Move **latexal_s** to the server, making sure the root is a part of ´´´$PATH´´´.

Modify constants in latexal script:
- ´´´$STDPATH´´´ equal standard include folder
- ´´´$SSCRIPTPATH´´´ equal to 
