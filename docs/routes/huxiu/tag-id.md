# 虎嗅 - 标签

## Coverage
`index-only`

## Route
- Namespace: `huxiu`
- Namespace Name: `虎嗅`
- Route Path: `/tag/:id`
- Route Name: `标签`
- Example: `/huxiu/tag/291`
- URL: `huxiu.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `xyqfer, HenryQW, nczitzk, TimoYoung`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/huxiu/tag.ts')`

## Description
更多标签请参见 [标签](https://www.huxiu.com/tags)

## Parameters
- `id`: 标签 id，可在对应标签页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "更多标签请参见 [标签](https://www.huxiu.com/tags)",
  "example": "/huxiu/tag/291",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "xyqfer",
    "HenryQW",
    "nczitzk",
    "TimoYoung"
  ],
  "module": "() => import('@/routes/huxiu/tag.ts')",
  "name": "标签",
  "parameters": {
    "id": "标签 id，可在对应标签页 URL 中找到"
  },
  "path": "/tag/:id"
}
```
