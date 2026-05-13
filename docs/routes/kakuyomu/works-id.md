# カクヨム - 投稿

## Coverage
`index-only`

## Route
- Namespace: `kakuyomu`
- Namespace Name: `カクヨム`
- Route Path: `/works/:id`
- Route Name: `投稿`
- Example: `/kakuyomu/works/1177354054894027232`
- URL: `kakuyomu.jp`
- Language: `ja`
- Categories: `reading`
- Maintainers: `KarasuShin`
- Source Location: `works.ts`
- Source Module: `() => import('@/routes/kakuyomu/works.ts')`

## Description
_None_

## Parameters
- `id`: 投稿 ID


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `kakuyomu.jp/works/:id`
- `target`: `/works/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/kakuyomu/works/1177354054894027232",
  "features": {
    "supportRadar": true
  },
  "location": "works.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/kakuyomu/works.ts')",
  "name": "投稿",
  "parameters": {
    "id": "投稿 ID"
  },
  "path": "/works/:id",
  "radar": [
    {
      "source": [
        "kakuyomu.jp/works/:id"
      ],
      "target": "/works/:id"
    }
  ]
}
```
