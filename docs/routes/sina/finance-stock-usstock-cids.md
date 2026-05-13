# 新浪 - 美股

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/finance/stock/usstock/:cids?`
- Route Name: `美股`
- Example: `/sina/finance/stock/usstock`
- URL: `finance.sina.com.cn/stock/usstock`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `finance/stock/usstock.ts`
- Source Module: `() => import('@/routes/sina/finance/stock/usstock.ts')`

## Description
| 最新报道 | 中概股 | 国际财经 | 互联网 |
| -------- | ------ | -------- | ------ |
| 57045    | 57046  | 56409    | 40811  |

## Parameters
- `cids`: 分区 id，见下表，默认为 `57045`


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
  - `finance.sina.com.cn/stock/usstock`
  - `finance.sina.com.cn/`
- `target`: `/finance/stock/usstock`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 最新报道 | 中概股 | 国际财经 | 互联网 |\n| -------- | ------ | -------- | ------ |\n| 57045    | 57046  | 56409    | 40811  |",
  "example": "/sina/finance/stock/usstock",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "finance/stock/usstock.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/sina/finance/stock/usstock.ts')",
  "name": "美股",
  "parameters": {
    "cids": "分区 id，见下表，默认为 `57045`"
  },
  "path": "/finance/stock/usstock/:cids?",
  "radar": [
    {
      "source": [
        "finance.sina.com.cn/stock/usstock",
        "finance.sina.com.cn/"
      ],
      "target": "/finance/stock/usstock"
    }
  ],
  "url": "finance.sina.com.cn/stock/usstock"
}
```
