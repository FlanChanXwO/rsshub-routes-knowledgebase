# 东方财富 - 研究报告

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/report/:category`
- Route Name: `研究报告`
- Example: `/eastmoney/report/strategyreport`
- URL: `data.eastmoney.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `syzq`
- Source Location: `report/index.tsx`
- Source Module: `() => import('@/routes/eastmoney/report/index.tsx')`

## Description
| 策略报告       | 宏观研究    | 券商晨报     | 行业研究 | 个股研报 |
| -------------- | ----------- | ------------ | -------- | -------- |
| strategyreport | macresearch | brokerreport | industry | stock    |

## Parameters
- `category`: {"description": "研报类型", "options": [{"label": "策略报告", "value": "strategyreport"}, {"label": "宏观研究", "value": "macresearch"}, {"label": "券商晨报", "value": "brokerreport"}, {"label": "行业研报", "value": "industry"}, {"label": "个股研报", "value": "stock"}]}


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
  - `data.eastmoney.com/report/:category`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 策略报告       | 宏观研究    | 券商晨报     | 行业研究 | 个股研报 |\n| -------------- | ----------- | ------------ | -------- | -------- |\n| strategyreport | macresearch | brokerreport | industry | stock    |",
  "example": "/eastmoney/report/strategyreport",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "report/index.tsx",
  "maintainers": [
    "syzq"
  ],
  "module": "() => import('@/routes/eastmoney/report/index.tsx')",
  "name": "研究报告",
  "parameters": {
    "category": {
      "description": "研报类型",
      "options": [
        {
          "label": "策略报告",
          "value": "strategyreport"
        },
        {
          "label": "宏观研究",
          "value": "macresearch"
        },
        {
          "label": "券商晨报",
          "value": "brokerreport"
        },
        {
          "label": "行业研报",
          "value": "industry"
        },
        {
          "label": "个股研报",
          "value": "stock"
        }
      ]
    }
  },
  "path": "/report/:category",
  "radar": [
    {
      "source": [
        "data.eastmoney.com/report/:category"
      ]
    }
  ],
  "view": 0
}
```
