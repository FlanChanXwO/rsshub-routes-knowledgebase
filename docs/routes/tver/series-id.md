# TVer - Series

## Coverage
`index-only`

## Route
- Namespace: `tver`
- Namespace Name: `TVer`
- Route Path: `/series/:id`
- Route Name: `Series`
- Example: `/tver/series/srx2o7o3c8`
- URL: `tver.jp`
- Language: `ja`
- Categories: `traditional-media`
- Maintainers: `yuikisaito`
- Source Location: `series.ts`
- Source Module: `() => import('@/routes/tver/series.ts')`

## Description
_None_

## Parameters
- `id`: Series ID (as it appears in URLs). For example, in https://tver.jp/series/srx2o7o3c8, the ID is "srx2o7o3c8".


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `tver.jp/series/:id`
- `target`: `/series/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/tver/series/srx2o7o3c8",
  "location": "series.ts",
  "maintainers": [
    "yuikisaito"
  ],
  "module": "() => import('@/routes/tver/series.ts')",
  "name": "Series",
  "parameters": {
    "id": "Series ID (as it appears in URLs). For example, in https://tver.jp/series/srx2o7o3c8, the ID is \"srx2o7o3c8\"."
  },
  "path": "/series/:id",
  "radar": [
    {
      "source": [
        "tver.jp/series/:id"
      ],
      "target": "/series/:id"
    }
  ]
}
```
