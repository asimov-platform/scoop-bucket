# Scoop Bucket for ASIMOV Platform

[![Tests](https://github.com/AsimovPlatform/scoop-bucket/actions/workflows/ci.yml/badge.svg)](https://github.com/AsimovPlatform/scoop-bucket/actions/workflows/ci.yml)
[![Excavator](https://github.com/AsimovPlatform/scoop-bucket/actions/workflows/excavator.yml/badge.svg)](https://github.com/AsimovPlatform/scoop-bucket/actions/workflows/excavator.yml)

This repository contains public [Scoop] manifests for the [ASIMOV Platform].

## Prerequisites

- [Scoop], the Windows command-line installer

## Configuration

Firstly, register this bucket in your local Scoop installation with:

```pwsh
scoop bucket add AsimovPlatform https://github.com/AsimovPlatform/scoop-bucket
```

## Installation

### Install [Protoflow]

```pwsh
scoop install AsimovPlatform/protoflow
```

## Troubleshooting

See [Scoop's documentation](https://github.com/ScoopInstaller/Scoop/wiki) in
case of any trouble.

[ASIMOV Platform]: https://github.com/AsimovPlatform
[Protoflow]:       https://github.com/AsimovPlatform/protoflow
[Scoop]:           https://scoop.sh
