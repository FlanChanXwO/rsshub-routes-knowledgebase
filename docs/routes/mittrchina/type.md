# 麻省理工科技评论 - 首页

## Coverage
`index-only`

## Route
- Namespace: `mittrchina`
- Namespace Name: `麻省理工科技评论`
- Route Path: `/:type?`
- Route Name: `首页`
- Example: `/mittrchina/index`
- URL: `mittrchina.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `EsuRt, queensferryme`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/mittrchina/index.tsx')`

## Description
| 快讯     | 本周热文 | 首页资讯 | 视频  |
| -------- | -------- | -------- | ----- |
| breaking | hot      | index    | video |

## Parameters
- `type`: 类型，见下表，默认为首页资讯


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
    "new-media"
  ],
  "description": "| 快讯     | 本周热文 | 首页资讯 | 视频  |\n| -------- | -------- | -------- | ----- |\n| breaking | hot      | index    | video |",
  "example": "/mittrchina/index",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "EsuRt",
    "queensferryme"
  ],
  "module": "() => import('@/routes/mittrchina/index.tsx')",
  "name": "首页",
  "parameters": {
    "type": "类型，见下表，默认为首页资讯"
  },
  "path": "/:type?"
}
```
