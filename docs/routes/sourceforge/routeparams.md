# SourceForge - Software

## Coverage
`index-only`

## Route
- Namespace: `sourceforge`
- Namespace Name: `SourceForge`
- Route Path: `/:routeParams?`
- Route Name: `Software`
- Example: `/sourceforge/topic=artificial-intelligence&os=windows`
- URL: `www.sourceforge.net`
- Language: `en`
- Categories: `program-update`
- Maintainers: `JimenezLi`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/sourceforge/index.ts')`

## Description
For some URL like [https://sourceforge.net/directory/artificial-intelligence/windows/](https://sourceforge.net/directory/artificial-intelligence/windows/), it is equal to [https://sourceforge.net/directory/?topic=artificial-intelligence&os=windows"](https://sourceforge.net/directory/?topic=artificial-intelligence&os=windows), thus subscribing to `/sourceforge/topic=artificial-intelligence&os=windows`.

  URL params can duplicate, such as `/sourceforge/topic=artificial-intelligence&os=windows&os=linux`.

## Parameters
- `routeParams`: route params, see below


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "For some URL like [https://sourceforge.net/directory/artificial-intelligence/windows/](https://sourceforge.net/directory/artificial-intelligence/windows/), it is equal to [https://sourceforge.net/directory/?topic=artificial-intelligence&os=windows\"](https://sourceforge.net/directory/?topic=artificial-intelligence&os=windows), thus subscribing to `/sourceforge/topic=artificial-intelligence&os=windows`.\n\n  URL params can duplicate, such as `/sourceforge/topic=artificial-intelligence&os=windows&os=linux`.",
  "example": "/sourceforge/topic=artificial-intelligence&os=windows",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/sourceforge/index.ts')",
  "name": "Software",
  "parameters": {
    "routeParams": "route params, see below"
  },
  "path": "/:routeParams?"
}
```
