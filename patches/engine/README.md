# Engine changes for this branch

The engine is a submodule from danielgomesvieira2000/ps2-port-engine, pinned at
its upstream commit. This branch's engine changes (#26 stutter fix, IOP log
flood fix, C++20 build fix) are kept here as patches. Apply them after cloning:

    git submodule update --init
    git -C engine am "$PWD"/patches/engine/*.patch
