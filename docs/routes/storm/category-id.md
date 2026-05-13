# 風傳媒 - 分类

## Coverage
`index-only`

## Route
- Namespace: `storm`
- Namespace Name: `風傳媒`
- Route Path: `/:category?/:id?`
- Route Name: `分类`
- Example: `/storm`
- URL: `storm.mg`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/storm/index.ts')`

## Description
| 新聞總覽 | 地方新聞      | 歷史頻道 | 評論總覽    |
| -------- | ------------- | -------- | ----------- |
| articles | localarticles | history  | all-comment |

::: tip
  支持形如 `https://www.storm.mg/category/118` 的路由，即 [`/storm/category/118`](https://rsshub.app/storm/category/118)

  支持形如 `https://www.storm.mg/localarticle-category/s149845` 的路由，即 [`/storm/localarticle-category/s149845`](https://rsshub.app/storm/localarticle-category/s149845)
:::

## Parameters
- `category`: 分类，见下表，默认为新聞總覽
- `id`: 子分类 ID，可在 URL 中找到


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
  - `storm.mg/:category/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 新聞總覽 | 地方新聞      | 歷史頻道 | 評論總覽    |\n| -------- | ------------- | -------- | ----------- |\n| articles | localarticles | history  | all-comment |\n\n::: tip\n  支持形如 `https://www.storm.mg/category/118` 的路由，即 [`/storm/category/118`](https://rsshub.app/storm/category/118)\n\n  支持形如 `https://www.storm.mg/localarticle-category/s149845` 的路由，即 [`/storm/localarticle-category/s149845`](https://rsshub.app/storm/localarticle-category/s149845)\n:::",
  "example": "/storm",
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
  "module": "() => import('@/routes/storm/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为新聞總覽",
    "id": "子分类 ID，可在 URL 中找到"
  },
  "path": "/:category?/:id?",
  "radar": [
    {
      "source": [
        "storm.mg/:category/:id"
      ]
    }
  ]
}
```
