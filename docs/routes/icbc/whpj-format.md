# 中国工商银行 - 外汇牌价

## Coverage
`index-only`

## Route
- Namespace: `icbc`
- Namespace Name: `中国工商银行`
- Route Path: `/whpj/:format?`
- Route Name: `外汇牌价`
- Example: `/icbc/whpj/zs?filter_title=%E8%8B%B1%E9%95%91`
- URL: `icbc.com.cn/column/1438058341489590354.html`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `leoleoasd`
- Source Location: `whpj.ts`
- Source Module: `() => import('@/routes/icbc/whpj.ts')`

## Description
| 短格式 | 参考价 | 现汇买卖 | 现钞买卖 | 现汇买入 | 现汇卖出 | 现钞买入 | 现钞卖出 |
| ------ | ------ | -------- | -------- | -------- | -------- | -------- | -------- |
| short  | zs     | xh       | xc       | xhmr     | xhmc     | xcmr     | xcmc     |

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
  - `icbc.com.cn/column/1438058341489590354.html`
- `target`: `/whpj`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| 短格式 | 参考价 | 现汇买卖 | 现钞买卖 | 现汇买入 | 现汇卖出 | 现钞买入 | 现钞卖出 |\n| ------ | ------ | -------- | -------- | -------- | -------- | -------- | -------- |\n| short  | zs     | xh       | xc       | xhmr     | xhmc     | xcmr     | xcmc     |",
  "example": "/icbc/whpj/zs?filter_title=%E8%8B%B1%E9%95%91",
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
    "leoleoasd"
  ],
  "module": "() => import('@/routes/icbc/whpj.ts')",
  "name": "外汇牌价",
  "parameters": {
    "format": "输出的标题格式，默认为标题 + 所有价格。短格式仅包含货币名称。"
  },
  "path": "/whpj/:format?",
  "radar": [
    {
      "source": [
        "icbc.com.cn/column/1438058341489590354.html"
      ],
      "target": "/whpj"
    }
  ],
  "url": "icbc.com.cn/column/1438058341489590354.html"
}
```
