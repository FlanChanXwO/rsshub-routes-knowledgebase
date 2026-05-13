# 每经网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `nbd`
- Namespace Name: `每经网`
- Route Path: `/:id?`
- Route Name: `分类`
- Example: `/nbd`
- URL: `nbd.com.cn/`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/nbd/index.ts')`

## Description
| 头条 | 要闻 | 图片新闻 | 推荐 |
| ---- | ---- | -------- | ---- |
| 2    | 3    | 4        | 5    |

## Parameters
- `id`: 分类 id，见下表，默认为要闻


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
  - `nbd.com.cn/`
  - `nbd.com.cn/columns/:id?`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 头条 | 要闻 | 图片新闻 | 推荐 |\n| ---- | ---- | -------- | ---- |\n| 2    | 3    | 4        | 5    |",
  "example": "/nbd",
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
  "module": "() => import('@/routes/nbd/index.ts')",
  "name": "分类",
  "parameters": {
    "id": "分类 id，见下表，默认为要闻"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "nbd.com.cn/",
        "nbd.com.cn/columns/:id?"
      ]
    }
  ],
  "url": "nbd.com.cn/"
}
```
