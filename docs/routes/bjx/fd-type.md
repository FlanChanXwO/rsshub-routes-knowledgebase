# 北极星电力网 - 风电

## Coverage
`index-only`

## Route
- Namespace: `bjx`
- Namespace Name: `北极星电力网`
- Route Path: `/fd/:type`
- Route Name: `风电`
- Example: `/bjx/fd/yw`
- URL: `www.bjx.com.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `hualiong`
- Source Location: `fd.ts`
- Source Module: `() => import('@/routes/bjx/fd.ts')`

## Description
`:type` 类型可选如下

| 要闻 | 政策 | 数据 | 市场 | 企业 | 招标 | 技术 | 报道 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| yw   | zc   | sj   | sc   | mq   | zb   | js   | bd   |

## Parameters
- `type`: 文章分类，详见下表


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
  "description": "`:type` 类型可选如下\n\n| 要闻 | 政策 | 数据 | 市场 | 企业 | 招标 | 技术 | 报道 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| yw   | zc   | sj   | sc   | mq   | zb   | js   | bd   |",
  "example": "/bjx/fd/yw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "fd.ts",
  "maintainers": [
    "hualiong"
  ],
  "module": "() => import('@/routes/bjx/fd.ts')",
  "name": "风电",
  "parameters": {
    "type": "文章分类，详见下表"
  },
  "path": "/fd/:type"
}
```
