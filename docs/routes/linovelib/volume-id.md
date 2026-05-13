# 哔哩轻小说 - 卷

## Coverage
`index-only`

## Route
- Namespace: `linovelib`
- Namespace Name: `哔哩轻小说`
- Route Path: `/volume/:id`
- Route Name: `卷`
- Example: `/linovelib/volume/8`
- URL: `linovelib.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `rkscv`
- Source Location: `volume.ts`
- Source Module: `() => import('@/routes/linovelib/volume.ts')`

## Description
_None_

## Parameters
- `id`: 小说 ID，可在小说页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.linovelib.com/novel/:id/catalog`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/linovelib/volume/8",
  "location": "volume.ts",
  "maintainers": [
    "rkscv"
  ],
  "module": "() => import('@/routes/linovelib/volume.ts')",
  "name": "卷",
  "parameters": {
    "id": "小说 ID，可在小说页 URL 中找到"
  },
  "path": "/volume/:id",
  "radar": [
    {
      "source": [
        "www.linovelib.com/novel/:id/catalog"
      ]
    }
  ]
}
```
