# 得到 - 知识城邦

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/knowledge/:topic?/:type?`
- Route Name: `知识城邦`
- Example: `/dedao/knowledge`
- URL: `dedao.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `knowledge.tsx`
- Source Module: `() => import('@/routes/dedao/knowledge.tsx')`

## Description
_None_

## Parameters
- `topic`: 话题 id，可在对应话题页 URL 中找到
- `type`: 分享类型，`true` 指精选，`false` 指最新，默认为精选


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
  - `dedao.cn/knowledge/topic/:topic`
  - `dedao.cn/knowledge`
  - `dedao.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/dedao/knowledge",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "knowledge.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dedao/knowledge.tsx')",
  "name": "知识城邦",
  "parameters": {
    "topic": "话题 id，可在对应话题页 URL 中找到",
    "type": "分享类型，`true` 指精选，`false` 指最新，默认为精选"
  },
  "path": "/knowledge/:topic?/:type?",
  "radar": [
    {
      "source": [
        "dedao.cn/knowledge/topic/:topic",
        "dedao.cn/knowledge",
        "dedao.cn/"
      ]
    }
  ]
}
```
