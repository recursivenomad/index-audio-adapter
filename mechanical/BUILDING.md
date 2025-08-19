# Build Instructions


> &nbsp;
> ### These are instructions on how to build output files from source.
> ### If you are looking for hardware assembly instructions, please refer to this project's [README.md](../README.md) file instead.
> &nbsp;



## Overview

Parametric modelling software: [FreeCAD 1.0.2][URL-FreeCAD]

If you plan on committing changes to the .FCStd document and want (somewhat) trackable commits, then from the repository root call:

```bash
mkdir -p .git/hooks
cp .githooks/pre-commit.sh .git/hooks/pre-commit
git config --local core.hooksPath .git/hooks
```

*(If you are already using a `pre-commit` git hook, then manually add the content of `pre-commit.sh` to the existing hook instead)*

> *Copying the file at a known state curbs the security concerns of remote changes to a hook.  Always audit scripts before using them.*



## Build process

*Coming soon...*



## Assembling a release

*Coming soon...*






[URL-FreeCAD]: <https://github.com/FreeCAD/FreeCAD/releases/tag/1.0.2>
