# ASUS - GPU Tweak

## Coverage
`index-only`

## Route
- Namespace: `asus`
- Namespace Name: `ASUS`
- Route Path: `/gpu-tweak`
- Route Name: `GPU Tweak`
- Example: `/asus/gpu-tweak`
- URL: `asus.com/campaign/GPU-Tweak-III/*`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `gpu-tweak.ts`
- Source Module: `() => import('@/routes/asus/gpu-tweak.ts')`

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
  - `asus.com/campaign/GPU-Tweak-III/*`
  - `asus.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/asus/gpu-tweak",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gpu-tweak.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/asus/gpu-tweak.ts')",
  "name": "GPU Tweak",
  "parameters": {},
  "path": "/gpu-tweak",
  "radar": [
    {
      "source": [
        "asus.com/campaign/GPU-Tweak-III/*",
        "asus.com/"
      ]
    }
  ],
  "url": "asus.com/campaign/GPU-Tweak-III/*"
}
```
