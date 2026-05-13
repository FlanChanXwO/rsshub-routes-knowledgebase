# 中国银行 - 外汇牌价

## Coverage
`index-only`

## Route
- Namespace: `boc`
- Namespace Name: `中国银行`
- Route Path: `/whpj/:format?`
- Route Name: `外汇牌价`
- Example: `/boc/whpj/zs?filter_title=%E8%8B%B1%E9%95%91`
- URL: `boc.cn/sourcedb/whpj`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `LogicJake, HenryQW`
- Source Location: `whpj.ts`
- Source Module: `() => import('@/routes/boc/whpj.ts')`

## Description
| 短格式 | 中行折算价 | 现汇买卖 | 现钞买卖 | 现汇买入 | 现汇卖出 | 现钞买入 | 现钞卖出 |
| ------ | ---------- | -------- | -------- | -------- | -------- | -------- | -------- |
| short  | zs         | xh       | xc       | xhmr     | xhmc     | xcmr     | xcmc     |

## Parameters
- `format`: 输出的标题格式，默认为标题 + 所有价格。短格式仅包含货币名称。


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
  - `boc.cn/sourcedb/whpj`
  - `boc.cn/`
- `target`: `/whpj`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 短格式 | 中行折算价 | 现汇买卖 | 现钞买卖 | 现汇买入 | 现汇卖出 | 现钞买入 | 现钞卖出 |\n| ------ | ---------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| short  | zs         | xh       | xc       | xhmr     | xhmc     | xcmr     | xcmc     |",
  "example": "/boc/whpj/zs?filter_title=%E8%8B%B1%E9%95%91",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "whpj.ts",
  "maintainers": [
    "LogicJake",
    "HenryQW"
  ],
  "module": "() => import('@/routes/boc/whpj.ts')",
  "name": "外汇牌价",
  "parameters": {
    "format": "输出的标题格式，默认为标题 + 所有价格。短格式仅包含货币名称。"
  },
  "path": "/whpj/:format?",
  "radar": [
    {
      "source": [
        "boc.cn/sourcedb/whpj",
        "boc.cn/"
      ],
      "target": "/whpj"
    }
  ],
  "url": "boc.cn/sourcedb/whpj"
}
```
