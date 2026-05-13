# 小宇宙 - 播客

## Coverage
`index-only`

## Route
- Namespace: `xiaoyuzhou`
- Namespace Name: `小宇宙`
- Route Path: `/podcast/:id`
- Route Name: `播客`
- Example: `/xiaoyuzhou/podcast/6021f949a789fca4eff4492c`
- URL: `xiaoyuzhoufm.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `hondajojo, jtsang4, pseudoyu, cscnk52`
- Source Location: `podcast.ts`
- Source Module: `() => import('@/routes/xiaoyuzhou/podcast.ts')`

## Description
_None_

## Parameters
- `id`: 播客 id 或单集 id，可以在小宇宙播客的 URL 中找到


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
  - `xiaoyuzhoufm.com/podcast/:id`
  - `xiaoyuzhoufm.com/episode/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/xiaoyuzhou/podcast/6021f949a789fca4eff4492c",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "podcast.ts",
  "maintainers": [
    "hondajojo",
    "jtsang4",
    "pseudoyu",
    "cscnk52"
  ],
  "module": "() => import('@/routes/xiaoyuzhou/podcast.ts')",
  "name": "播客",
  "parameters": {
    "id": "播客 id 或单集 id，可以在小宇宙播客的 URL 中找到"
  },
  "path": "/podcast/:id",
  "radar": [
    {
      "source": [
        "xiaoyuzhoufm.com/podcast/:id",
        "xiaoyuzhoufm.com/episode/:id"
      ]
    }
  ],
  "url": "xiaoyuzhoufm.com/",
  "view": 4
}
```
