# Repo List

List all PL repos. Currently, this script lists all Go & JavaScript repos in the following orgs:

- ipfs
- ipfs-shipyard
- ipld
- libp2p
- multiformats

It outputs them in a format suitable for `.github/workflows/config.json`.

## Install

Before usage, you'll need to install the dependencies.

```go
$ npm install
```

## Usage

To update `.github/workflows/config.json`, run:

```bash
$ node index.js > ../../.github/workflows/config.json
```
