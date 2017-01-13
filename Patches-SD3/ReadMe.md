Because some patches require both core and SD3 file modifications, I have created this folder to store SD3 patches.

Place patch file in src/modules/SD3/ and patch. Basic example:

git submodule init
git submodule update
(copy desired patch files)
cd src/modules/SD3
patch -p1 < file_moved_from_Patches-SD3_folder.patch