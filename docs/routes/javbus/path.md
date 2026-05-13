# JavBus - Works

## Coverage
`index-only`

## Route
- Namespace: `javbus`
- Namespace Name: `JavBus`
- Route Path: `/:path{.+}?`
- Route Name: `Works`
- Example: `/javbus/star/rwt`
- URL: `www.javbus.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `MegrezZhu, CoderTonyChan, nczitzk, Felix2yu`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/javbus/index.tsx')`

## Description
_None_

## Parameters
- `path`: {"description": "Any path of list page on javbus"}


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.javbus.com/:path*`
- `target`: `/:path`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javbus/star/rwt",
  "features": {
    "nsfw": true
  },
  "location": "index.tsx",
  "maintainers": [
    "MegrezZhu",
    "CoderTonyChan",
    "nczitzk",
    "Felix2yu"
  ],
  "module": "() => import('@/routes/javbus/index.tsx')",
  "name": "Works",
  "parameters": {
    "path": {
      "description": "Any path of list page on javbus"
    }
  },
  "path": "/:path{.+}?",
  "radar": [
    {
      "source": [
        "www.javbus.com/:path*"
      ],
      "target": "/:path"
    }
  ],
  "url": "www.javbus.com",
  "view": 3
}
```
