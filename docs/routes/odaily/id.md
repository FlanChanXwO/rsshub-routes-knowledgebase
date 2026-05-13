# Odaily 星球日报 - 文章

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/:id?`
- Route Name: `文章`
- Example: `/odaily`
- URL: `0daily.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/odaily/post.ts')`

## Description
| 最新 | 新品 | DeFi | NFT | 存储 | 波卡 | 行情 | 活动 |
| ---- | ---- | ---- | --- | ---- | ---- | ---- | ---- |
| 280  | 333  | 331  | 334 | 332  | 330  | 297  | 296  |

## Parameters
- `id`: id，见下表，默认为最新


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
  - `0daily.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新 | 新品 | DeFi | NFT | 存储 | 波卡 | 行情 | 活动 |\n| ---- | ---- | ---- | --- | ---- | ---- | ---- | ---- |\n| 280  | 333  | 331  | 334 | 332  | 330  | 297  | 296  |",
  "example": "/odaily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/odaily/post.ts')",
  "name": "文章",
  "parameters": {
    "id": "id，见下表，默认为最新"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "0daily.com/"
      ]
    }
  ],
  "url": "0daily.com/"
}
```
