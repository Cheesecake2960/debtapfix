debtapfix
======

fork of debtap
A script for converting .deb packages into Arch Linux packages

## How to use

`Syntax: debtap -o output_directory [other_options] package_filename`

For example: `debtap world-of-goo-demo_1.0_i386.deb`

Available options:
==================

    -h  --help        Prints help
    -u  --update      Update debtapfix database
    -q  --quiet       Bypass all questions, except for editing metadata file(s)
    -Q  --Quiet       Bypass all questions (not recommended)
    -s  --pseudo      Create a pseudo-64-bit package from a 32-bit .deb package
    -w  --wipeout     Wipeout versions from all dependencies, conflicts etc.
    -p  --pkgbuild    Additionally generate a PKGBUILD file
    -P  --Pkgbuild    Generate a PKGBUILD file only
    -o  --output      Output directory for generated package and/or PKGBUILD (optional)
    -v  --version     Print version
