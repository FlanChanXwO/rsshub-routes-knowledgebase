# OpenWrt - Unknown

## Coverage
`index-only`

## Route
- Namespace: `openwrt`
- Namespace Name: `OpenWrt`
- Route Path: `/releases/:brand/:model`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `openwrt.org`
- Language: `en`
- Categories: `None`
- Maintainers: `None`
- Source Location: `releases.ts`
- Source Module: `() => import('@/routes/openwrt/releases.ts')`

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
  "location": "releases.ts",
  "maintainers": [],
  "module": "() => import('@/routes/openwrt/releases.ts')",
  "name": "Unknown",
  "path": "/releases/:brand/:model",
  "radar": [
    {
      "source": [
        "openwrt.org/toh/:band/:model"
      ],
      "target": "/releases/:model"
    }
  ]
}
```
