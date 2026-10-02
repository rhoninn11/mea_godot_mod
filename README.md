# mea custom godot mod

modified godot engine in area of mesh generation

git format-patch -1 HEAD

git submodule update --init --recursive
cd engine && git am ../*patch
pacman -S scons pkgconfig gcc glibc linux-api-headers
