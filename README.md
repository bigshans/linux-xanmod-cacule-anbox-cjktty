# Linux-Xanmod-Anbox-Cjktty

## Introduction

This is my personal linux-xanmod-anbox-tty kernel repository.

## Differences from Linux-Xanmod-Caucle

- Add anbox config
- Add cjktty
- Added some make parameters to fit my computer's hardware

## Build And Install

If you have compiled code in the past, you can use the `./clean.sh` script to clean up the directory.

``` shell
./clean.sh
```

Then run it,

``` shell
makepkg -sfi
```

If your compilation is interrupted in the middle, you can use the following command to partially clean up the directory.

``` shell
./clean.sh -p
```

Of course, you can also download it from the release. Only the default configuration.
