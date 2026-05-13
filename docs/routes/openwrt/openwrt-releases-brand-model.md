# OpenWrt - Unknown

## Coverage
`index-only`

## Route
- Namespace: `openwrt`
- Namespace Name: `OpenWrt`
- Route Path: `/openwrt/releases/:brand/:model`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `openwrt.org`
- Language: `_None_`
- Categories: `other`
- Maintainers: `None`
- Source Location: `releases.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `openwrt.org/toh/:band/:model`
- `target`: `/releases/:model`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "heat": 0,
  "location": "releases.ts",
  "maintainers": [],
  "name": "Unknown",
  "path": "/releases/:brand/:model",
  "radar": [
    {
      "source": [
        "openwrt.org/toh/:band/:model"
      ],
      "target": "/releases/:model"
    }
  ],
  "topFeeds": []
}
```
