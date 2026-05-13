# zyw - 今日热榜

## Coverage
`index-only`

## Route
- Namespace: `zyw`
- Namespace Name: `zyw`
- Route Path: `/hot/:site?`
- Route Name: `今日热榜`
- Example: `/zyw/hot`
- URL: `hot.zyw.asia`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `hot.ts`
- Source Module: `() => import('@/routes/zyw/hot.ts')`

## Description
::: tip
  全部站点请见 [此处](https://hot.zyw.asia/#/list)
:::

| 哔哩哔哩 | 微博 | 知乎 | 36 氪 | 百度 | 少数派 | IT 之家 | 澎湃新闻 | 今日头条 | 百度贴吧 | 稀土掘金 | 腾讯新闻 |
| -------- | ---- | ---- | ----- | ---- | ------ | ------- | -------- | -------- | -------- | -------- | -------- |

## Parameters
- `site`: 站点，见下表，默认为空，即全部


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
    "new-media"
  ],
  "description": "::: tip\n  全部站点请见 [此处](https://hot.zyw.asia/#/list)\n:::\n\n| 哔哩哔哩 | 微博 | 知乎 | 36 氪 | 百度 | 少数派 | IT 之家 | 澎湃新闻 | 今日头条 | 百度贴吧 | 稀土掘金 | 腾讯新闻 |\n| -------- | ---- | ---- | ----- | ---- | ------ | ------- | -------- | -------- | -------- | -------- | -------- |",
  "example": "/zyw/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/zyw/hot.ts')",
  "name": "今日热榜",
  "parameters": {
    "site": "站点，见下表，默认为空，即全部"
  },
  "path": "/hot/:site?"
}
```
