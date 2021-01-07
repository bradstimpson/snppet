![snppet](./assets/logo.svg)

![GitHub Workflow Status](https://github.com/bradstimpson/snppet/workflows/CI/badge.svg)
[![GoDev](https://img.shields.io/badge/go.dev-reference-007d9c?logo=go&logoColor=white&style=flat-square)](https://pkg.go.dev/github.com/bradstimpson/snppet?tab=doc)
[![codecov](https://codecov.io/gh/bradstimpson/snppet/branch/master/graph/badge.svg)](https://codecov.io/gh/bradstimpson/snppet)
[![Go Report Card](https://goreportcard.com/badge/bradstimpson/snppet)](https://goreportcard.com/report/bradstimpson/snppet)
[![Docker Image](https://img.shields.io/static/v1?label=image&message=Docker&color=1488C6&logo=docker)](https://hub.docker.com/r/bradstimpson/snppet)
[![Deploy Heroku](https://img.shields.io/static/v1?label=deploy&message=Heroku&color=430098&logo=heroku)](https://heroku.com/deploy)
## Overview

**snppet** is a bookmark tool that is intended to be self-hosted and give the user a convenient location for his/her bookmarks but with a couple added cool features.  We generate smart summaries of the website, take fingerprints of its images, and more - plus it is written entirely in Go.  This is inspired by the excellent project [Shiori](https://github.com/go-shiori/shiori) but moves in a couple different directions.

- Website: tbd
- Slack: tbd
- Demo: tbd

## Sponsors

Click on sponsor, above, for more information on sponsorship.

## Goals

- compact binary that is portable between OS
- command line tools to interact when web not available or for scripting
- GRPC and REST to allow interworking between other services
- as fast as possible with low memory/cpu/disk usage
- little to no javascript in the WebUI
- support for embeddable DB and cache (sqlite and badger)
- support for non-embeddable DB and cache (postgresql/cockroachdb and redis)

## Features

- basic bookmark management (CRUD), with collections, and areas
- import bookmarks from any plaintext format by scraping for html://<> addresses
- simple cli with accompanying scripts that can be run to update bookmarks (or standard CRUD)
- simple webui that uses as little javascript as possible
- supports locales with english and french included
- GRPC and REST API to interact with service
- portable in single binary format
- support for sqlite, postgresql, cockroachdb, badger, and redis
- crawl bookmarks to: summarize content, fingerprint images, shorten URLs, take snapshot of the page
- ability to select different icons for a bookmark, use the favicon, or the snapshot
- convenience utilities to shorten URLs, unshorten URLs, or generate a QR code
- chrome/firefox/alfred extensions/plugins

## Contributing

Please see [CONTRIBUTING.md](/CONTRIBUTING.md).
Thank you, [contributors](https://github.com/bradstimpson/snppet/graphs/contributors)!

## Related Projects

1. [Shiori](https://github.com/go-shiori/shiori) - excellent bookmark manager and the inspiration for this project

## Dependencies
| Name | License |
|---|---|
|pkger| MIT |
