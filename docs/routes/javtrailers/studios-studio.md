# JavTrailers - Studios

## Coverage
`index-only`

## Route
- Namespace: `javtrailers`
- Namespace Name: `JavTrailers`
- Route Path: `/studios/:studio`
- Route Name: `Studios`
- Example: `/javtrailers/studios/s1-no-1-style`
- URL: `javtrailers.com`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `studios.ts`
- Source Module: `() => import('@/routes/javtrailers/studios.ts')`

## Description
_None_

## Parameters
- `studio`: Studio name, can be found in the URL of the studio page


## Features
- `nsfw`: true
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `javtrailers.com/studios/:category`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javtrailers/studios/s1-no-1-style",
  "features": {
    "nsfw": true,
    "requirePuppeteer": true
  },
  "location": "studios.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/javtrailers/studios.ts')",
  "name": "Studios",
  "parameters": {
    "studio": "Studio name, can be found in the URL of the studio page"
  },
  "path": "/studios/:studio",
  "radar": [
    {
      "source": [
        "javtrailers.com/studios/:category"
      ]
    }
  ]
}
```
