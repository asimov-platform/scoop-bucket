# Scoop Bucket for ASIMOV Platform

[![Tests](https://github.com/asimov-platform/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/asimov-platform/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/asimov-platform/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/asimov-platform/scoop-bucket/actions/workflows/excavator.yml)

This repository contains public [Scoop] manifests for the [ASIMOV Platform].

## Prerequisites

- [Scoop], the Windows command-line installer

## Configuration

To use this bucket in Scoop you must first register it with:

```pwsh
scoop bucket add asimov-platform https://github.com/asimov-platform/scoop-bucket
```

## Installation

### Install [ASIMOV CLI]

```pwsh
scoop install asimov-platform/asimov-cli
```

## Troubleshooting

See [Scoop's documentation](https://github.com/ScoopInstaller/Scoop/wiki) in
case of any trouble.

[ASIMOV Platform]: https://github.com/asimov-platform
[ASIMOV CLI]: https://github.com/asimov-platform/asimov-cli
[Scoop]: https://scoop.sh
