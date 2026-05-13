# Aqara - 社区

## Coverage
`index-only`

## Route
- Namespace: `aqara`
- Namespace Name: `Aqara`
- Route Path: `/community/:id?/:keyword?`
- Route Name: `社区`
- Example: `/aqara/community`
- URL: `aqara.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `community.ts`
- Source Module: `() => import('@/routes/aqara/community.ts')`

## Description
_None_

## Parameters
- `id`: 分类 id，可在对应分类页 URL 中找到，默认为全部
- `keyword`: 关键字，默认为空


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/aqara/community",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "community.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/aqara/community.ts')",
  "name": "社区",
  "parameters": {
    "id": "分类 id，可在对应分类页 URL 中找到，默认为全部",
    "keyword": "关键字，默认为空"
  },
  "path": "/community/:id?/:keyword?"
}
```
