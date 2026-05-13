# PuTTY - Change Log

## Coverage
`index-only`

## Route
- Namespace: `putty`
- Namespace Name: `PuTTY`
- Route Path: `/changes`
- Route Name: `Change Log`
- Example: `/putty/changes`
- URL: `www.chiark.greenend.org.uk/~sgtatham/putty/changes.html`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changes.ts`
- Source Module: `() => import('@/routes/putty/changes.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.chiark.greenend.org.uk/~sgtatham/putty/changes.html`
  - `www.chiark.greenend.org.uk/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/putty/changes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "changes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/putty/changes.ts')",
  "name": "Change Log",
  "parameters": {},
  "path": "/changes",
  "radar": [
    {
      "source": [
        "www.chiark.greenend.org.uk/~sgtatham/putty/changes.html",
        "www.chiark.greenend.org.uk/"
      ]
    }
  ],
  "url": "www.chiark.greenend.org.uk/~sgtatham/putty/changes.html"
}
```
