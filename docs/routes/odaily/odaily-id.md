# Odaily 星球日报 - 文章

## Coverage
`index-only`

## Route
- Namespace: `odaily`
- Namespace Name: `Odaily 星球日报`
- Route Path: `/odaily/:id?`
- Route Name: `文章`
- Example: `/odaily`
- URL: `0daily.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `post.ts`
- Source Module: `_None_`

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
  "heat": 114,
  "location": "post.ts",
  "maintainers": [
    "nczitzk"
  ],
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
  "topFeeds": [
    {
      "description": "最新 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": "2025-07-24T19:29:20.919Z",
      "errorMessage": "[GET] \"https://www.odaily.news/api/pp/api/app-front/feed-stream?feed_id=280&b_id=&per_page=25\": 404 Not Found\n[GET] \"https://www.odaily.news/api/pp/api/app-front/feed-stream?feed_id=280&b_id=&per_page=25\": 404 Not Found\n",
      "id": "56204588915011597",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/",
      "title": "最新 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily"
    },
    {
      "description": "最新 - Odaily星球日报 - Powered by RSSHub",
      "errorAt": "2025-07-24T20:18:06.864Z",
      "errorMessage": "[GET] \"https://www.odaily.news/api/pp/api/app-front/feed-stream?feed_id=280&b_id=&per_page=25\": 404 Not Found\n",
      "id": "85203770103696384",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.odaily.news/",
      "title": "最新 - Odaily星球日报",
      "type": "feed",
      "url": "rsshub://odaily/280"
    }
  ],
  "url": "0daily.com/"
}
```
