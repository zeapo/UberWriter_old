UberWriter
==========
UberWriter (*without* debian in mind)

## Python3 ##
The editor is more and more python3 compliant, using `with` statements, assuming good unicode. Removing deprecated methods (PEP400).

## Python2 ##
Trying to keep backward compatibility here. People should move to python3...

## Debian? ##
Managed to make the code work on *ArchLinux* and *Fedora*. Checking for `TexLive` supports both `apt` package and classical `which`-like search for a `latex` binary.

## Issues ##
I don't know if it's related to my installation, have to check but the theme is not perfect.

## Instructions ##
- python3 bin/uberwriter

Requirements (SEVERELY INCOMPLETE):
- via apt-get:

		sudo apt-get install python3-gi python3-gi-cairo pandoc texlive python3-enchant python3-apt python3-cairo

> Readme written using UberWriter on *ArchLinux* o/
> Originally forked from jonalmeida/UberWriter
> Original repo at [Launchpad](https://launchpad.net/uberwriter)
