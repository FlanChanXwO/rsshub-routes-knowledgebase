# 西南交通大学 - 计算机与人工智能学院

## Coverage
`index-only`

## Route
- Namespace: `swjtu`
- Namespace Name: `西南交通大学`
- Route Path: `/scai/:type`
- Route Name: `计算机与人工智能学院`
- Example: `/swjtu/scai/bks`
- URL: `www.swjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `AzureG03, SuperJeason`
- Source Location: `scai.ts`
- Source Module: `() => import('@/routes/swjtu/scai.ts')`

## Description
| 分区              | 参数         |
| ----------------- | ----------- |
| 本科生教育         | bks         |
| 研究生教育         | yjs         |
| 学生工作           | xsgz        |

## Parameters
- `type`: 通知类型


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `scai.swjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\n| 分区              | 参数         |\n| ----------------- | ----------- |\n| 本科生教育         | bks         |\n| 研究生教育         | yjs         |\n| 学生工作           | xsgz        |\n",
  "example": "/swjtu/scai/bks",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "scai.ts",
  "maintainers": [
    "AzureG03",
    "SuperJeason"
  ],
  "module": "() => import('@/routes/swjtu/scai.ts')",
  "name": "计算机与人工智能学院",
  "parameters": {
    "type": "通知类型"
  },
  "path": "/scai/:type",
  "radar": [
    {
      "source": [
        "scai.swjtu.edu.cn/"
      ]
    }
  ]
}
```
