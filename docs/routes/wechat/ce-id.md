# 微信小程序 - 公众号（CareerEngine 来源）

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/ce/:id`
- Route Name: `公众号（CareerEngine 来源）`
- Example: `/wechat/ce/595a5b14d7164e53908f1606`
- URL: `posts.careerengine.us`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `HenryQW`
- Source Location: `ce.ts`
- Source Module: `() => import('@/routes/wechat/ce.ts')`

## Description
_None_

## Parameters
- `id`: 公众号 id，在 [CareerEngine](https://search.careerengine.us/) 搜索公众号，通过 URL 中找到对应的公众号 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cimidata.com/a/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/wechat/ce/595a5b14d7164e53908f1606",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ce.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/wechat/ce.ts')",
  "name": "公众号（CareerEngine 来源）",
  "parameters": {
    "id": "公众号 id，在 [CareerEngine](https://search.careerengine.us/) 搜索公众号，通过 URL 中找到对应的公众号 id"
  },
  "path": "/ce/:id",
  "radar": [
    {
      "source": [
        "cimidata.com/a/:id"
      ]
    }
  ]
}
```
