# 8KCosplay - 标签

## Coverage
`index-only`

## Route
- Namespace: `8kcos`
- Namespace Name: `8KCosplay`
- Route Path: `/tag/:tag`
- Route Name: `标签`
- Example: `/8kcos/tag/cosplay`
- URL: `8kcosplay.com/`
- Language: `zh-CN`
- Categories: `picture`
- Maintainers: `KotoriK`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/8kcos/tag.ts')`

## Description
_None_

## Parameters
- `tag`: 标签名


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
  - `8kcosplay.com/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/8kcos/tag/cosplay",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "KotoriK"
  ],
  "module": "() => import('@/routes/8kcos/tag.ts')",
  "name": "标签",
  "parameters": {
    "tag": "标签名"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "8kcosplay.com/tag/:tag"
      ]
    }
  ],
  "url": "8kcosplay.com/"
}
```
