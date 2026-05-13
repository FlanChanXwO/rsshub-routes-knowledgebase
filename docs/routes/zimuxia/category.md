# FIX 字幕侠 - 分类

## Coverage
`index-only`

## Route
- Namespace: `zimuxia`
- Namespace Name: `FIX 字幕侠`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/zimuxia`
- URL: `zimuxia.cn`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/zimuxia/index.ts')`

## Description
| ALL | FIX 德语社 | 欧美剧集 | 欧美电影 | 综艺 & 纪录 | FIX 日语社 | FIX 韩语社 | FIX 法语社 |
| --- | ---------- | -------- | -------- | ----------- | ---------- | ---------- | ---------- |
|     | 昆仑德语社 | 欧美剧集 | 欧美电影 | 综艺纪录    | fix 日语社 | fix 韩语社 | fix 法语社 |

## Parameters
- `category`: 分类，见下表，默认为 ALL


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
    "multimedia"
  ],
  "description": "| ALL | FIX 德语社 | 欧美剧集 | 欧美电影 | 综艺 & 纪录 | FIX 日语社 | FIX 韩语社 | FIX 法语社 |\n| --- | ---------- | -------- | -------- | ----------- | ---------- | ---------- | ---------- |\n|     | 昆仑德语社 | 欧美剧集 | 欧美电影 | 综艺纪录    | fix 日语社 | fix 韩语社 | fix 法语社 |",
  "example": "/zimuxia",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/zimuxia/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为 ALL"
  },
  "path": "/:category?"
}
```
