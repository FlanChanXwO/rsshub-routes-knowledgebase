# FT 中文网 - FT 中文网

## Coverage
`index-only`

## Route
- Namespace: `ftchinese`
- Namespace Name: `FT 中文网`
- Route Path: `/:language/:channel?`
- Route Name: `FT 中文网`
- Example: `/ftchinese/simplified/hotstoryby7day`
- URL: `ftchinese.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `HenryQW, xyqfer`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/ftchinese/channel.ts')`

## Description
::: tip
  -   不支持付费文章。
:::

  通过提取文章全文，以提供比官方源更佳的阅读体验。

  支持所有频道，频道名称见 [官方频道 RSS](http://www.ftchinese.com/channel/rss.html).

  -   频道为单一路径，如 `http://www.ftchinese.com/rss/news` 则为 `/ftchinese/simplified/news`.
  -   频道包含多重路径，如 `http://www.ftchinese.com/rss/column/007000002` 则替换 `/` 为 `-` `/ftchinese/simplified/column-007000002`.

## Parameters
- `language`: 语言，简体 `simplified`，繁体 `traditional`
- `channel`: 频道，缺省为每日更新


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
  "description": "::: tip\n  -   不支持付费文章。\n:::\n\n  通过提取文章全文，以提供比官方源更佳的阅读体验。\n\n  支持所有频道，频道名称见 [官方频道 RSS](http://www.ftchinese.com/channel/rss.html).\n\n  -   频道为单一路径，如 `http://www.ftchinese.com/rss/news` 则为 `/ftchinese/simplified/news`.\n  -   频道包含多重路径，如 `http://www.ftchinese.com/rss/column/007000002` 则替换 `/` 为 `-` `/ftchinese/simplified/column-007000002`.",
  "example": "/ftchinese/simplified/hotstoryby7day",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel.ts",
  "maintainers": [
    "HenryQW",
    "xyqfer"
  ],
  "module": "() => import('@/routes/ftchinese/channel.ts')",
  "name": "FT 中文网",
  "parameters": {
    "channel": "频道，缺省为每日更新",
    "language": "语言，简体 `simplified`，繁体 `traditional`"
  },
  "path": "/:language/:channel?"
}
```
