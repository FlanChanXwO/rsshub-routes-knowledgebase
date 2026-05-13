# 龙腾网 - 网站翻译

## Coverage
`index-only`

## Route
- Namespace: `ltaaa`
- Namespace Name: `龙腾网`
- Route Path: `/article`
- Route Name: `网站翻译`
- Example: `/ltaaa/article`
- URL: `www.ltaaa.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/ltaaa/article.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.ltaaa.cn/article`
- `target`: `/article`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ltaaa/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/ltaaa/article.ts')",
  "name": "网站翻译",
  "path": "/article",
  "radar": [
    {
      "source": [
        "www.ltaaa.cn/article"
      ],
      "target": "/article"
    }
  ],
  "url": "www.ltaaa.cn",
  "view": 0
}
```
