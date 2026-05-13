# 北极星电力网 - 光伏

## Coverage
`index-only`

## Route
- Namespace: `bjx`
- Namespace Name: `北极星电力网`
- Route Path: `/gf/:type`
- Route Name: `光伏`
- Example: `/bjx/gf/sc`
- URL: `www.bjx.com.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `Sxuet`
- Source Location: `types.ts`
- Source Module: `() => import('@/routes/bjx/types.ts')`

## Description
`:type` 类型可选如下

| 要闻 | 政策 | 市场行情 | 企业动态 | 独家观点 | 项目工程 | 招标采购 | 财经 | 国际行情 | 价格趋势 | 技术跟踪 |
| ---- | ---- | -------- | -------- | -------- | -------- | -------- | ---- | -------- | -------- | -------- |
| yw   | zc   | sc       | mq       | dj       | xm       | zb       | cj   | gj       | sj       | js       |

## Parameters
- `type`: 分类，北极星光伏最后的`type`字段


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
    "traditional-media"
  ],
  "description": "`:type` 类型可选如下\n\n| 要闻 | 政策 | 市场行情 | 企业动态 | 独家观点 | 项目工程 | 招标采购 | 财经 | 国际行情 | 价格趋势 | 技术跟踪 |\n| ---- | ---- | -------- | -------- | -------- | -------- | -------- | ---- | -------- | -------- | -------- |\n| yw   | zc   | sc       | mq       | dj       | xm       | zb       | cj   | gj       | sj       | js       |",
  "example": "/bjx/gf/sc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "types.ts",
  "maintainers": [
    "Sxuet"
  ],
  "module": "() => import('@/routes/bjx/types.ts')",
  "name": "光伏",
  "parameters": {
    "type": "分类，北极星光伏最后的`type`字段"
  },
  "path": "/gf/:type"
}
```
