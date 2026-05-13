# 北京师范大学 - 党委学生工作部

## Coverage
`index-only`

## Route
- Namespace: `bnu`
- Namespace Name: `北京师范大学`
- Route Path: `/dwxgb/:category/:type`
- Route Name: `党委学生工作部`
- Example: `/bnu/dwxgb/xwzx/tzgg`
- URL: `bs.bnu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Fatpandac`
- Source Location: `dwxgb.ts`
- Source Module: `() => import('@/routes/bnu/dwxgb.ts')`

## Description
`https://dwxgb.bnu.edu.cn/xwzx/tzgg/index.html` 则对应为 `/bnu/dwxgb/xwzx/tzgg

## Parameters
- `category`: 大分类
- `type`: 子分类，例子如下


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
  - `dwxgb.bnu.edu.cn/:category/:type/index.html`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "`https://dwxgb.bnu.edu.cn/xwzx/tzgg/index.html` 则对应为 `/bnu/dwxgb/xwzx/tzgg",
  "example": "/bnu/dwxgb/xwzx/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dwxgb.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/bnu/dwxgb.ts')",
  "name": "党委学生工作部",
  "parameters": {
    "category": "大分类",
    "type": "子分类，例子如下"
  },
  "path": "/dwxgb/:category/:type",
  "radar": [
    {
      "source": [
        "dwxgb.bnu.edu.cn/:category/:type/index.html"
      ]
    }
  ]
}
```
