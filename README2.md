# MCEdit-Unified-Linux-Preview

<hr>

This repository hosts Linux development releases of __[MCEdit-Unified](https://github.com/Podshot/MCEdit-Unified)__.

You'll also find there the `.so` files for Pocket Edition support.
These files are also embedded in the installer.

You'll also find here the installer documentation.

This repository, and the releases here, are made like [Podshot's one](https://github.com/Podshot/MCEdit-Unified-Preview).
Please have also a look there. The same ideas apply here :smile:  
However, the Linux builds are not triggered on a regular basis.


## IMPORTANT

* Be very careful with these builds; they are development builds and may not behave as expected!
  * Backup you data, especially the one related to the game and this program.  
    MCEdit-Unified configuration files are located in `~/.mcedit` if you're running 'fixed'.
* These testing releases are roughly tested and may not work at all.
  * If the installer do not work, or MCEdit do not start, please report **here**.
  * All other issues shall be reported to [the source code repository](https://github.com/Podshot/MCEdit-Unified/issues).
* [RTFD](https://github.com/LaChal/MCEdit-Unified-Linux-Preview). (Also found in the archives below.)

Note that I'm not responsible in case of data loss or corruption!


## REPOSITORY CONTENT

This repository contains:

* `README.md`: This file.
* `LINUX_INSTALL.txt`: Installation notes for Linux systems.
* `RELEASE-VERSION.json`: Version information.
* `doc/`: The installer documents
  * `content.txt`: List of all the files contained in the installer. Unsorted.
  * `install.txt`: The installer specific `--help` output.
  * `MCEdit-XXXXXX.ctrl`: The self-extractable CRC and MD5 hashes for integrity verification.
  * `MCEdit-XXXXXX.txt`: The self-extractable `--help` output.
* `pymclevel/`
  * libleveldb.so`: Symbolic link to `libleveldb.so.1.20`
  * libleveldb.so.1`: Symbolic link to `libleveldb.so.1.20`
  * libleveldb.so`: Binary support for PE (and Bedrock?) worlds.

The releases `.tar.gz` and `.zip` archives contains this repository files, not the installer.  
The `.run` file is the actual installer, it does not contain this repository files.


## WHAT IS THIS FUZZY NUMBER AT THE END OF THE VERSION?

This is sort of identifier.
Precisely, it is the number of seconds since `epoch`.

