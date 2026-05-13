# China.com 中华网 - Finance News 财经 - 财经新闻

## Coverage
`index-only`

## Route
- Namespace: `china`
- Namespace Name: `China.com 中华网`
- Route Path: `/finance/:category?`
- Route Name: `Finance News 财经 - 财经新闻`
- Example: `/china/finance`
- URL: `finance.china.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `KingJem`
- Source Location: `finance/finance.ts`
- Source Module: `() => import('@/routes/china/finance/finance.ts')`

## Description
| 推荐    | TMT | 金融    | 地产   | 消费    | 医药  | 酒业 | IPO 观察 |
| ------- | --- | ------- | ------ | ------- | ----- | ---- | -------- |
| tuijian | TMT | jinrong | dichan | xiaofei | yiyao | wine | IPO      |

  > Note: The default news num is `30`.

  > 注意：默认新闻条数是 `30`。

## Parameters
- `category`: Category of news. See the form below for details, default is suggest news.


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
  - `finance.china.com/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 推荐    | TMT | 金融    | 地产   | 消费    | 医药  | 酒业 | IPO 观察 |\n| ------- | --- | ------- | ------ | ------- | ----- | ---- | -------- |\n| tuijian | TMT | jinrong | dichan | xiaofei | yiyao | wine | IPO      |\n\n  > Note: The default news num is `30`.\n\n  > 注意：默认新闻条数是 `30`。",
  "example": "/china/finance",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "finance/finance.ts",
  "maintainers": [
    "KingJem"
  ],
  "module": "() => import('@/routes/china/finance/finance.ts')",
  "name": "Finance News 财经 - 财经新闻",
  "parameters": {
    "category": "Category of news. See the form below for details, default is suggest news."
  },
  "path": "/finance/:category?",
  "radar": [
    {
      "source": [
        "finance.china.com/:category"
      ]
    }
  ]
}
```
