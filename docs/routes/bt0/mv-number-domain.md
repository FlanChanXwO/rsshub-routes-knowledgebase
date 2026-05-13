# 不太灵影视 - 影视资源下载列表

## Coverage
`index-only`

## Route
- Namespace: `bt0`
- Namespace Name: `不太灵影视`
- Route Path: `/mv/:number/:domain?`
- Route Name: `影视资源下载列表`
- Example: `/bt0/mv/35575567/2`
- URL: `2bt0.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `miemieYaho`
- Source Location: `mv.ts`
- Source Module: `() => import('@/routes/bt0/mv.ts')`

## Description
_None_

## Parameters
- `number`: 影视详情id, 网页路径为`/mv/{id}.html`其中的id部分, 一般为8位纯数字
- `domain`: 数字1-9, 比如1表示请求域名为 1bt0.com, 默认为 2


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `2bt0.com/mv/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bt0/mv/35575567/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mv.ts",
  "maintainers": [
    "miemieYaho"
  ],
  "module": "() => import('@/routes/bt0/mv.ts')",
  "name": "影视资源下载列表",
  "parameters": {
    "domain": "数字1-9, 比如1表示请求域名为 1bt0.com, 默认为 2",
    "number": "影视详情id, 网页路径为`/mv/{id}.html`其中的id部分, 一般为8位纯数字"
  },
  "path": "/mv/:number/:domain?",
  "radar": [
    {
      "source": [
        "2bt0.com/mv/"
      ]
    }
  ]
}
```
