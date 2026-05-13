# USENIX - ;login:

## Coverage
`index-only`

## Route
- Namespace: `usenix`
- Namespace Name: `USENIX`
- Route Path: `/loginonline`
- Route Name: `;login:`
- Example: `/usenix/loginonline`
- URL: `usenix.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `wu-yufei`
- Source Location: `loginonline.ts`
- Source Module: `() => import('@/routes/usenix/loginonline.ts')`

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
  - `usenix.org/publications/loginonline`
  - `usenix.org/publications`
  - `usenix.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/usenix/loginonline",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "loginonline.ts",
  "maintainers": [
    "wu-yufei"
  ],
  "module": "() => import('@/routes/usenix/loginonline.ts')",
  "name": ";login:",
  "parameters": {},
  "path": "/loginonline",
  "radar": [
    {
      "source": [
        "usenix.org/publications/loginonline",
        "usenix.org/publications",
        "usenix.org/"
      ]
    }
  ]
}
```
