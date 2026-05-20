# 得到 - 知识城邦

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/dedao/knowledge/:topic?/:type?`
- Route Name: `知识城邦`
- Example: `/dedao/knowledge`
- URL: `dedao.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `knowledge.tsx`
- Source Module: `_None_`

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
  "heat": 88,
  "location": "knowledge.tsx",
  "maintainers": [
    "nczitzk"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "得到 - 知识城邦 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "102156742857121792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dedao.cn/knowledge",
      "title": "得到 - 知识城邦",
      "type": "feed",
      "url": "rsshub://dedao/knowledge"
    },
    {
      "description": "来分享你和万维钢一起学习的收获吧！课程、书籍都可以。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85673494190769152",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.dedao.cn/knowledge/topic/gZdLwQEoAnOQbAmJQJyQY1PGmVDY2K",
      "title": "得到 - 知识城邦 - 跟万维钢和全球精英大脑同步",
      "type": "feed",
      "url": "rsshub://dedao/knowledge/gZdLwQEoAnOQbAmJQJyQY1PGmVDY2K/false"
    }
  ]
}
```
