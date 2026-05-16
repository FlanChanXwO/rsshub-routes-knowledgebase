# FIX 字幕侠 - 剧集

## Coverage
`index-only`

## Route
- Namespace: `zimuxia`
- Namespace Name: `FIX 字幕侠`
- Route Path: `/zimuxia/portfolio/:id`
- Route Name: `剧集`
- Example: `/zimuxia/portfolio/我们这一天`
- URL: `zimuxia.cn`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `portfolio.ts`
- Source Module: `_None_`

## Description
::: tip
本路由以 `magnet` 为默认 linktype，可以通过在路由后方加上 `?linktype=链接类型` 指定导出的链接类型。比如路由为 [`/zimuxia/portfolio/我们这一天?linktype=baidu`](https://rsshub.app/zimuxia/portfolio/我们这一天?linktype=baidu) 来导出百度盘链接。目前，你可以选择的 `链接类型` 包括: `magnet`(默认), `all`(所有), `ed2k`(电驴), `baidu`(百度盘), `quark`(夸克盘), `115`(115 盘), `subhd`(字幕).
:::

## Parameters
- `id`: 剧集名，可在剧集页 URL 中找到


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
  - `zimuxia.cn/portfolio/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n本路由以 `magnet` 为默认 linktype，可以通过在路由后方加上 `?linktype=链接类型` 指定导出的链接类型。比如路由为 [`/zimuxia/portfolio/我们这一天?linktype=baidu`](https://rsshub.app/zimuxia/portfolio/我们这一天?linktype=baidu) 来导出百度盘链接。目前，你可以选择的 `链接类型` 包括: `magnet`(默认), `all`(所有), `ed2k`(电驴), `baidu`(百度盘), `quark`(夸克盘), `115`(115 盘), `subhd`(字幕).\n:::",
  "example": "/zimuxia/portfolio/我们这一天",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "portfolio.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "剧集",
  "parameters": {
    "id": "剧集名，可在剧集页 URL 中找到"
  },
  "path": "/portfolio/:id",
  "radar": [
    {
      "source": [
        "zimuxia.cn/portfolio/:id"
      ]
    }
  ],
  "topFeeds": []
}
```
