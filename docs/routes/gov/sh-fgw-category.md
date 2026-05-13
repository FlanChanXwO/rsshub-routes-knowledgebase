# 国家能源局 - 上海市发展和改革委员会

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/sh/fgw/:category{.+}?`
- Route Name: `上海市发展和改革委员会`
- Example: `/gov/sh/fgw/fgw_zxxxgk`
- URL: `fgw.sh.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `sh/fgw/index.tsx`
- Source Module: `() => import('@/routes/gov/sh/fgw/index.tsx')`

## Description
::: tip
  若订阅 [最新信息公开](https://fgw.sh.gov.cn/fgw_zxxxgk/index.html)，网址为 `https://fgw.sh.gov.cn/fgw_zxxxgk/index.html`。截取 `https://fgw.sh.gov.cn/` 到末尾 `/index.html` 的部分 `fgw_zxxxgk` 作为参数填入，此时路由为 [`/gov/sh/fgw/fgw_zxxxgk`](https://rsshub.app/gov/sh/fgw/fgw_zxxxgk)。
:::

| 最新信息公开 | 要闻动态   |
| ------------ | ---------- |
| fgw_zxxxgk   | fgw_fzggdt |

## Parameters
- `category`: 分类，默认为 `fgw_zxxxgk`，即最新信息公开，可在对应分类页 URL 中找到


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
  - `fgw.sh.gov.cn/:category`
### Rule 2
- `title`: `最新信息公开`
- `source`:
  - `fgw.sh.gov.cn/fgw_zxxxgk/index.html`
- `target`: `/sh/fgw/fgw_zxxxgk`
### Rule 3
- `title`: `要闻动态`
- `source`:
  - `fgw.sh.gov.cn/fgw_fzggdt/index.html`
- `target`: `/sh/fgw/fgw_fzggdt`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n  若订阅 [最新信息公开](https://fgw.sh.gov.cn/fgw_zxxxgk/index.html)，网址为 `https://fgw.sh.gov.cn/fgw_zxxxgk/index.html`。截取 `https://fgw.sh.gov.cn/` 到末尾 `/index.html` 的部分 `fgw_zxxxgk` 作为参数填入，此时路由为 [`/gov/sh/fgw/fgw_zxxxgk`](https://rsshub.app/gov/sh/fgw/fgw_zxxxgk)。\n:::\n\n| 最新信息公开 | 要闻动态   |\n| ------------ | ---------- |\n| fgw_zxxxgk   | fgw_fzggdt |\n  ",
  "example": "/gov/sh/fgw/fgw_zxxxgk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "sh/fgw/index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/sh/fgw/index.tsx')",
  "name": "上海市发展和改革委员会",
  "parameters": {
    "category": "分类，默认为 `fgw_zxxxgk`，即最新信息公开，可在对应分类页 URL 中找到"
  },
  "path": [
    "/sh/fgw/:category{.+}?",
    "/shanghai/fgw/:category{.+}?"
  ],
  "radar": [
    {
      "source": [
        "fgw.sh.gov.cn/:category"
      ]
    },
    {
      "source": [
        "fgw.sh.gov.cn/fgw_zxxxgk/index.html"
      ],
      "target": "/sh/fgw/fgw_zxxxgk",
      "title": "最新信息公开"
    },
    {
      "source": [
        "fgw.sh.gov.cn/fgw_fzggdt/index.html"
      ],
      "target": "/sh/fgw/fgw_fzggdt",
      "title": "要闻动态"
    }
  ],
  "url": "fgw.sh.gov.cn"
}
```
