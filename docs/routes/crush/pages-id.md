# CrushNinja - 匿名投稿頁面

## Coverage
`index-only`

## Route
- Namespace: `crush`
- Namespace Name: `CrushNinja`
- Route Path: `/pages/:id`
- Route Name: `匿名投稿頁面`
- Example: `/crush/pages/141719909033861`
- URL: `www.crush.ninja`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Tsuyumi25`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/crush/index.ts')`

## Description
_None_

## Parameters
- `id`: {"description": "頁面 ID 或代稱，例如 `141719909033861` 或 `awkward87poland`"}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.crush.ninja/:locale/pages/:id`
- `target`: `/pages/:id`

## Raw JSON
```json
{
  "example": "/crush/pages/141719909033861",
  "location": "index.ts",
  "maintainers": [
    "Tsuyumi25"
  ],
  "module": "() => import('@/routes/crush/index.ts')",
  "name": "匿名投稿頁面",
  "parameters": {
    "id": {
      "description": "頁面 ID 或代稱，例如 `141719909033861` 或 `awkward87poland`"
    }
  },
  "path": "/pages/:id",
  "radar": [
    {
      "source": [
        "www.crush.ninja/:locale/pages/:id"
      ],
      "target": "/pages/:id"
    }
  ],
  "url": "www.crush.ninja"
}
```
