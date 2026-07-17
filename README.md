# Word Hunter Scoop Bucket

[![Tests](https://github.com/Ironship/scoop-wordhunter/actions/workflows/ci.yml/badge.svg)](https://github.com/Ironship/scoop-wordhunter/actions/workflows/ci.yml)
[![Excavator](https://github.com/Ironship/scoop-wordhunter/actions/workflows/excavator.yml/badge.svg)](https://github.com/Ironship/scoop-wordhunter/actions/workflows/excavator.yml)

Official [Scoop](https://scoop.sh) bucket for
[Word Hunter](https://github.com/Ironship/WordHunter), a local-first reader and
vocabulary trainer.

## Install

```powershell
scoop bucket add wordhunter https://github.com/Ironship/scoop-wordhunter
scoop install wordhunter/wordhunter
```

The manifest installs the official 64-bit portable ZIP from the latest stable
GitHub Release. Its release URL and SHA-256 are checked by this repository's CI.

## Updates

Scoop Excavator checks the upstream GitHub release tag and updates the manifest
through its `checkver` and `autoupdate` definitions. Every change is validated
on both Windows PowerShell and PowerShell before it is published.

Issues about the application belong in the
[Word Hunter issue tracker](https://github.com/Ironship/WordHunter/issues).
Bucket or manifest issues can be reported in this repository.
