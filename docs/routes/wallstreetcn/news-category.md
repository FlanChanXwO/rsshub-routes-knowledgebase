# 华尔街见闻 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `wallstreetcn`
- Namespace Name: `华尔街见闻`
- Route Path: `/news/:category?`
- Route Name: `资讯`
- Example: `/wallstreetcn/news`
- URL: `wallstreetcn.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/wallstreetcn/news.ts')`

## Description
| id           | 分类 |
| ------------ | ---- |
| global       | 最新 |
| shares       | 股市 |
| bonds        | 债市 |
| commodities  | 商品 |
| forex        | 外汇 |
| enterprise   | 公司 |
| asset-manage | 资管 |
| tmt          | 科技 |
| estate       | 地产 |
| car          | 汽车 |
| medicine     | 医药 |

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `wallstreetcn.com/news/:category`
  - `wallstreetcn.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| id           | 分类 |\n| ------------ | ---- |\n| global       | 最新 |\n| shares       | 股市 |\n| bonds        | 债市 |\n| commodities  | 商品 |\n| forex        | 外汇 |\n| enterprise   | 公司 |\n| asset-manage | 资管 |\n| tmt          | 科技 |\n| estate       | 地产 |\n| car          | 汽车 |\n| medicine     | 医药 |",
  "example": "/wallstreetcn/news",
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/wallstreetcn/news.ts')",
  "name": "资讯",
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "wallstreetcn.com/news/:category",
        "wallstreetcn.com/"
      ]
    }
  ]
}
```
