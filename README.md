# Animal Crossing: Happy Home Designer save file checksum updater

This is a simple, quick and dirty program to fix/update the checksums in a save file of **Animal Crossing: Happy Home Designer** (takumi.dat).

The program runs directly on the computer and in the command line. There is no need to run a program on the 3DS, other than the save file import/export tool.

Simply run `build.sh` and then `./checksum takumi.dat`. It should also work on Windows, but you'll probably need a different compiler command.

The fixed file will be saved in the same location, with the additional extension `.CRCFIXED` to avoid overwriting existing files.

This program is based on the `/core/source/utils/checksum.cpp` file from [Happy-Home-Editor](https://github.com/SuperSaiyajinStackZ/Happy-Home-Editor/), the work of **RedShyGuy** and **SuperSaiyajinStackZ**.

The software is licensed under the GNU General Public License, see the LICENSE file for more information.

The provided software comes with NO WARRANTY. Always have a backup of the unmodified save file. Unexpected things can happen to your game if you use this program to fix a corrupted or hand-edited save file. Use at your own risk.
The program does not in any way verify the validity of the actual data in the save file.
