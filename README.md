# VyOS ISO Automation Build
[![VyOS v1.4 Rolling Release](https://github.com/w4xzr/vyosbot/actions/workflows/vyos-v1.4-rolling-release.yml/badge.svg)](https://github.com/w4xzr/vyosbot/actions/workflows/vyos-v1.4-rolling-release.yml) [![VyOS v1.3 LTS Release](https://github.com/w4xzr/vyosbot/actions/workflows/vyos-v1.3-equuleus.yml/badge.svg)](https://github.com/w4xzr/vyosbot/actions/workflows/vyos-v1.3-equuleus.yml)

Automate build VyOS v1.3 LTS Release and v1.4 Rolling Release files.

## About this repository

Use the official build script provided by VyOS [https://github.com/vyos/vyos-build](https://github.com/vyos/vyos-build).

Manual build VyOS instructions can be found in VyOS official [Documentation - Build VyOS](https://docs.vyos.io/en/latest/contributing/build-vyos.html).

## Github Action workflow files

Github Action automate the build process and save you some times.

There are two workflow files:

[vyos-v1.3.x-equuleus.yml](.github/workflows/vyos-v1.3.x-equuleus.yml)

For VyOS v1.3.x LTS release, action trigger on schedule every Friday.

[vyos-v1.4-rolling-release.yml](.github/workflows/vyos-v1.4-rolling-release.yml)

For VyOS v1.4 rolling release, action trigger on schedule every day.

```
