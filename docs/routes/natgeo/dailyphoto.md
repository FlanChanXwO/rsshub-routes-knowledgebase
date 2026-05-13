# National Geographic - Daily Photo

## Coverage
`index-only`

## Route
- Namespace: `natgeo`
- Namespace Name: `National Geographic`
- Route Path: `/dailyphoto`
- Route Name: `Daily Photo`
- Example: `/natgeo/dailyphoto`
- URL: `nationalgeographic.com/photo-of-the-day/*`
- Language: `en`
- Categories: `picture`
- Maintainers: `LogicJake, OrangeEd1t, TonyRL, pseudoyu`
- Source Location: `dailyphoto.tsx`
- Source Module: `() => import('@/routes/natgeo/dailyphoto.tsx')`

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
  - `nationalgeographic.com/photo-of-the-day/*`
  - `nationalgeographic.com/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/natgeo/dailyphoto",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dailyphoto.tsx",
  "maintainers": [
    "LogicJake",
    "OrangeEd1t",
    "TonyRL",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/natgeo/dailyphoto.tsx')",
  "name": "Daily Photo",
  "parameters": {},
  "path": "/dailyphoto",
  "radar": [
    {
      "source": [
        "nationalgeographic.com/photo-of-the-day/*",
        "nationalgeographic.com/"
      ]
    }
  ],
  "url": "nationalgeographic.com/photo-of-the-day/*",
  "view": 2
}
```
