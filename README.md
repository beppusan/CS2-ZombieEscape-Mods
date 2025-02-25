# CS2 ZE Modifications

This repository is a central place to manage custom modifications for Counter-Strike 2 Zombie Escape maps. It collects each map’s own repository as a Git submodule, making it easy to find and update them all in one place.

> [!IMPORTANT]
> This collection is a community-driven initiative and is ***not*** an official release by the original map authors or map porters.  
> Some of the strippers have been ported from CS:GO, and ***none*** of these releases are official products by the original stage creators.

> [!NOTE]
> Feel free to use any content in this collection on your server, whether for training servers or not.

## Prerequisites

Before you begin, make sure you have the following installed and configured:

- [Metamod:Source](https://www.metamodsource.net/downloads.php/?branch=master)
- [CS2Fixes](https://github.com/Source2ZE/CS2Fixes)
- [StripperCS2](https://github.com/Source2ZE/StripperCS2)

## Installation

1. Clone the Repository with Submodules

   Make sure to clone the repository recursively so that all submodules are included:

   ```bash
   git clone --recursive https://github.com/beppusan/CS2-ZombieEscape-Mods.git
   ```

   If you have already cloned without the `--recursive` flag or downloaded manually, you can initialize and update the submodules later by running:

   ```bash
   git submodule update --init --recursive
   ```

2. Refer to Individual Module Instructions

   Each submodule includes its own README file. Open the relevant folder and follow the instructions.

## License

This collection is released under the [MIT License](LICENSE). The submodules included in this repository are subject to their respective licenses.

### Acknowledgments

We would like to express our sincere gratitude to the original map authors, map porters, and all creators of extra stages, as well as to the developers behind Metamod:Source, CS2Fixes, and StripperCS2. Their contributions and dedication have made this project possible.
