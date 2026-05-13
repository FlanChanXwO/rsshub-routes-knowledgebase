# 知园 - Newsletter

## Coverage
`index-only`

## Route
- Namespace: `zhiy`
- Namespace Name: `知园`
- Route Path: `/letters/:author`
- Route Name: `Newsletter`
- Example: `/zhiy/letters/messy`
- URL: `zhiy.cc`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `letter.ts`
- Source Module: `() => import('@/routes/zhiy/letter.ts')`

## Description
_None_

## Parameters
- `author`: 作者 ID，可在URL中找到


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
  - `zhiy.cc/:author`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/zhiy/letters/messy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "letter.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/zhiy/letter.ts')",
  "name": "Newsletter",
  "parameters": {
    "author": "作者 ID，可在URL中找到"
  },
  "path": "/letters/:author",
  "radar": [
    {
      "source": [
        "zhiy.cc/:author"
      ]
    }
  ]
}
```
