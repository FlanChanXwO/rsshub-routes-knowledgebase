# JavTrailers - Casts

## Coverage
`index-only`

## Route
- Namespace: `javtrailers`
- Namespace Name: `JavTrailers`
- Route Path: `/casts/:cast`
- Route Name: `Casts`
- Example: `/javtrailers/casts/hibiki-otsuki`
- URL: `javtrailers.com/casts`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `casts.ts`
- Source Module: `() => import('@/routes/javtrailers/casts.ts')`

## Description
_None_

## Parameters
- `cast`: Cast name, can be found in the URL of the cast page


## Features
- `nsfw`: true
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `javtrailers.com/casts/:category`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javtrailers/casts/hibiki-otsuki",
  "features": {
    "nsfw": true,
    "requirePuppeteer": true
  },
  "location": "casts.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/javtrailers/casts.ts')",
  "name": "Casts",
  "parameters": {
    "cast": "Cast name, can be found in the URL of the cast page"
  },
  "path": "/casts/:cast",
  "radar": [
    {
      "source": [
        "javtrailers.com/casts/:category"
      ]
    }
  ],
  "url": "javtrailers.com/casts"
}
```
