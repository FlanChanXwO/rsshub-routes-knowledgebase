# BOOKWALKER電子書 - 搜尋

## Coverage
`index-only`

## Route
- Namespace: `bookwalker`
- Namespace Name: `BOOKWALKER電子書`
- Route Path: `/search/:filter?`
- Route Name: `搜尋`
- Example: `/bookwalker/search/order=sell_desc&s=34`
- URL: `www.bookwalker.com.tw`
- Language: `zh-TW`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `search.tsx`
- Source Module: `() => import('@/routes/bookwalker/search.tsx')`

## Description
::: tip
订阅 [依發售日新至舊排序的文學小說](https://www.bookwalker.com.tw/search?order=sell_desc&s=34)，其源网址为 `https://www.bookwalker.com.tw/search?order=sell_desc&s=34`，请参考该 URL 指定部分构成参数，此时路由为 [`/bookwalker/search/order=sell_desc&s=34`](https://rsshub.app/bookwalker/search/order=sell_desc&s=34)。
:::

## Parameters
- `filter`: {"description": "过滤器，默认为 `order=sell_desc`，即依發售日新至舊排序"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.bookwalker.com.tw/search`
- `target`: `/bookwalker/search`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "::: tip\n订阅 [依發售日新至舊排序的文學小說](https://www.bookwalker.com.tw/search?order=sell_desc&s=34)，其源网址为 `https://www.bookwalker.com.tw/search?order=sell_desc&s=34`，请参考该 URL 指定部分构成参数，此时路由为 [`/bookwalker/search/order=sell_desc&s=34`](https://rsshub.app/bookwalker/search/order=sell_desc&s=34)。\n:::",
  "example": "/bookwalker/search/order=sell_desc&s=34",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "search.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/bookwalker/search.tsx')",
  "name": "搜尋",
  "parameters": {
    "filter": {
      "description": "过滤器，默认为 `order=sell_desc`，即依發售日新至舊排序"
    }
  },
  "path": "/search/:filter?",
  "radar": [
    {
      "source": [
        "www.bookwalker.com.tw/search"
      ],
      "target": "/bookwalker/search"
    }
  ],
  "url": "www.bookwalker.com.tw",
  "view": 0
}
```
