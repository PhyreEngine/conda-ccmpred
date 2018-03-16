This repository contains a [conda][conda] recipe for building [CCMPred][cc], a
tool for detecting residue-residue contacts from correlated mutations.

## Prerequisites

1. You will need an installation of [conda][miniconda].

2. Your root conda installation must have the `conda-build` installed.

## Building

You should be able to build this package by simply running `conda build .`.
This package will build binaries for several different CPU architectures, each
with all optimisations enabled.

## Patches

This recipe comes with a patch that alters the CCMPred build system so that
conda can pass its compiler flags.

[conda]: https://conda.io
[miniconda]: https://conda.io/miniconda.html
[cc]: https://github.com/soedinglab/hh-suit://github.com/soedinglab/CCMpred
