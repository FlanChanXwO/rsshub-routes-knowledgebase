# 欧乐影院 - 视频

## Coverage
`index-only`

## Route
- Namespace: `olevod`
- Namespace Name: `欧乐影院`
- Route Path: `/vod/:id`
- Route Name: `视频`
- Example: `/olevod/vod/202449091`
- URL: `olevod.one`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `fang63625`
- Source Location: `vod.ts`
- Source Module: `() => import('@/routes/olevod/vod.ts')`

## Description
_None_

## Parameters
- `id`: 视频id号


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.olevod.one/vod/:id`
- `target`: `/vod/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/olevod/vod/202449091",
  "features": {
    "nsfw": true
  },
  "location": "vod.ts",
  "maintainers": [
    "fang63625"
  ],
  "module": "() => import('@/routes/olevod/vod.ts')",
  "name": "视频",
  "parameters": {
    "id": "视频id号"
  },
  "path": "/vod/:id",
  "radar": [
    {
      "source": [
        "www.olevod.one/vod/:id"
      ],
      "target": "/vod/:id"
    }
  ]
}
```
