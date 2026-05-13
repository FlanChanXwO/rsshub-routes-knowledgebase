# 广东省食品药品审评认证技术协会 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `gdsrx`
- Namespace Name: `广东省食品药品审评认证技术协会`
- Route Path: `/:id?`
- Route Name: `栏目`
- Example: `/gdsrx`
- URL: `gdsrx.org.cn`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `None`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/gdsrx/index.ts')`

## Description
| 栏目名称          | 栏目 id |
| ----------------- | ------- |
| 法规文库          | 10      |
| 法规资讯          | 12      |
| 专家供稿          | 13      |
| 协会动态 会员动态 | 20      |
| 协会动态          | 37      |
| 协会通知公告      | 38      |
| 会员动态          | 39      |

## Parameters
- `id`: 栏目 id，可在对应栏目页 URL 中找到，见下表，默认为法规文库


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
  "description": "| 栏目名称          | 栏目 id |\n| ----------------- | ------- |\n| 法规文库          | 10      |\n| 法规资讯          | 12      |\n| 专家供稿          | 13      |\n| 协会动态 会员动态 | 20      |\n| 协会动态          | 37      |\n| 协会通知公告      | 38      |\n| 会员动态          | 39      |",
  "example": "/gdsrx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [],
  "module": "() => import('@/routes/gdsrx/index.ts')",
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，可在对应栏目页 URL 中找到，见下表，默认为法规文库"
  },
  "path": "/:id?"
}
```
