# Testing out the cluster

This repository contains code for testing the cluster at scale.

## Compiling the executable

```bash
$ g++ cluster_test.cpp -L/share/apps/cmic/nifticlib/lib/ -lniftiio -lznz -lz -I/share/apps/cmic/nifticlib/include/nifti/ -o nifti_test
```
