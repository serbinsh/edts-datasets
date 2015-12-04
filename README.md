# edts-datasets
This is a repository of public datasets for the Ecosystem Demography Test Suite (EDTS)

YOU MUST BE USING GIT VERSION 1.8+  , AND...
YOU MUST HAVE GIT-LFS INSTALLED TO USE THIS REPO!

see: https://git-lfs.github.com/

This repository is composed of archives.  The user must "un-tar" all of the archives before use.  The user may find this tedious, but it is a compromise.  There is simply too much data here to place in a single archive, it is too much for git LSF to handle.  If we dont use any archiving, it (will/may?) compromise data transfer rates with the local host.  Either way, just step into each directory and un-tar where necessary.

When running the tests in EDTS the user can point to the location of the dataset archive using symbolic links.

There are no special requirements to clone this repository other than the two stated above.  As long as git LFS is installed and setup on your system correctly, LFS file handling software will correctly identify large files in the repository and pull them down.