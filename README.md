# A simple C99-only example of a CLAP audio effect

Really, you don't want to use this musically, The DSP is painfully naive. But this
shows a simple set of wave folder / distortions in a 3 param state saving pure C99
CLAP Audio Effect.

Documentation coming soon

To build

```
git clone (this repo)
cd clap-c99-distortion
git submodule update --init --recursive
cmake -Bignore/bld
cmake --build ignore/bld
```

and you will get ignore/bld/clap-c99-distortion.clap
