# hameln - chapter

## Coverage
`index-only`

## Route
- Namespace: `hameln`
- Namespace Name: `hameln`
- Route Path: `/chapter/:id`
- Route Name: `chapter`
- Example: `/hameln/chapter/264928`
- URL: `syosetu.org`
- Language: `ja`
- Categories: `reading`
- Maintainers: `huangliangshusheng`
- Source Location: `chapter.ts`
- Source Module: `() => import('@/routes/hameln/chapter.ts')`

## Description
Eg: [https://syosetu.org/novel/264928](https://syosetu.org/novel/264928)

## Parameters
- `id`: Novel id, can be found in URL


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
  - `syosetu.org/novel/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "Eg: [https://syosetu.org/novel/264928](https://syosetu.org/novel/264928)",
  "example": "/hameln/chapter/264928",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "chapter.ts",
  "maintainers": [
    "huangliangshusheng"
  ],
  "module": "() => import('@/routes/hameln/chapter.ts')",
  "name": "chapter",
  "parameters": {
    "id": "Novel id, can be found in URL"
  },
  "path": "/chapter/:id",
  "radar": [
    {
      "source": [
        "syosetu.org/novel/:id"
      ]
    }
  ]
}
```
