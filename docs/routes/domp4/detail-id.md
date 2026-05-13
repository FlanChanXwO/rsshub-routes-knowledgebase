# DoMP4 影视 - 剧集订阅

## Coverage
`index-only`

## Route
- Namespace: `domp4`
- Namespace Name: `DoMP4 影视`
- Route Path: `/detail/:id`
- Route Name: `剧集订阅`
- Example: `/domp4/detail/LBTANI22222I`
- URL: `www.xlmp4.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `savokiss, pseudoyu`
- Source Location: `detail.ts`
- Source Module: `() => import('@/routes/domp4/detail.ts')`

## Description
::: tip
由于大部分详情页是 `/html/xxx.html`，还有部分是 `/detail/123.html`，所以此处做了兼容，id 取 `xxx` 或者 `123` 都可以。

新增 `second` 参数，用于选择下载地址二（地址二不可用或者不填都默认地址一），用法: `/domp4/detail/LBTANI22222I?second=1`。

域名频繁更换，目前使用 www.xlmp4.com
:::

## Parameters
- `id`: 从剧集详情页 URL 处获取，如：`https://www.xlmp4.com/html/LBTANI22222I.html`，取 `.html` 前面部分


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
  - `www.xlmp4.com/detail/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n由于大部分详情页是 `/html/xxx.html`，还有部分是 `/detail/123.html`，所以此处做了兼容，id 取 `xxx` 或者 `123` 都可以。\n\n新增 `second` 参数，用于选择下载地址二（地址二不可用或者不填都默认地址一），用法: `/domp4/detail/LBTANI22222I?second=1`。\n\n域名频繁更换，目前使用 www.xlmp4.com\n:::",
  "example": "/domp4/detail/LBTANI22222I",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "detail.ts",
  "maintainers": [
    "savokiss",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/domp4/detail.ts')",
  "name": "剧集订阅",
  "parameters": {
    "id": "从剧集详情页 URL 处获取，如：`https://www.xlmp4.com/html/LBTANI22222I.html`，取 `.html` 前面部分"
  },
  "path": "/detail/:id",
  "radar": [
    {
      "source": [
        "www.xlmp4.com/detail/:id"
      ]
    }
  ]
}
```
