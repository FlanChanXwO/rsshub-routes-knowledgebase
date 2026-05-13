# 奇葩买家秀 - 频道

## Coverage
`index-only`

## Route
- Namespace: `qipamaijia`
- Namespace Name: `奇葩买家秀`
- Route Path: `/:cate?`
- Route Name: `频道`
- Example: `/qipamaijia/fuli`
- URL: `qipamaijia.com/`
- Language: `zh-CN`
- Categories: `picture`
- Maintainers: `Fatpandac, nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/qipamaijia/index.ts')`

## Description
_None_

## Parameters
- `cate`: 频道名，可在对应网址中找到，默认为最新


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `qipamaijia.com/`
  - `qipamaijia.com/:cate`
- `target`: `/:cate`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/qipamaijia/fuli",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Fatpandac",
    "nczitzk"
  ],
  "module": "() => import('@/routes/qipamaijia/index.ts')",
  "name": "频道",
  "parameters": {
    "cate": "频道名，可在对应网址中找到，默认为最新"
  },
  "path": "/:cate?",
  "radar": [
    {
      "source": [
        "qipamaijia.com/",
        "qipamaijia.com/:cate"
      ],
      "target": "/:cate"
    }
  ],
  "url": "qipamaijia.com/"
}
```
