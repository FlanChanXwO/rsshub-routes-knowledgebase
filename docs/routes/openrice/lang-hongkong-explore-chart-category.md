# Openrice開飯喇 - 香港餐廳排行榜

## Coverage
`index-only`

## Route
- Namespace: `openrice`
- Namespace Name: `Openrice開飯喇`
- Route Path: `/:lang/hongkong/explore/chart/:category`
- Route Name: `香港餐廳排行榜`
- Example: `/openrice/zh/hongkong/explore/chart/most-bookmarked`
- URL: `www.openrice.com`
- Language: `zh-HK`
- Categories: `shopping`
- Maintainers: `after9`
- Source Location: `chart.tsx`
- Source Module: `() => import('@/routes/openrice/chart.tsx')`

## Description
| 简体 | 繁體 | EN |
| ----- | ------ | ----- |
| zh-cn | zh | en |

| 最多收藏 | 每周最高评分 | 最高浏览 | 最佳甜品餐厅 |
| ----- | ------ | ----- | ----- |
| most-bookmarked | best-rating | most-popular | best-dessert |

## Parameters
- `lang`: 语言，缺省为 zh
- `category`: 类别，缺省为 most-bookmarked


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "\n| 简体 | 繁體 | EN |\n| ----- | ------ | ----- |\n| zh-cn | zh | en |\n\n| 最多收藏 | 每周最高评分 | 最高浏览 | 最佳甜品餐厅 |\n| ----- | ------ | ----- | ----- |\n| most-bookmarked | best-rating | most-popular | best-dessert |\n  ",
  "example": "/openrice/zh/hongkong/explore/chart/most-bookmarked",
  "location": "chart.tsx",
  "maintainers": [
    "after9"
  ],
  "module": "() => import('@/routes/openrice/chart.tsx')",
  "name": "香港餐廳排行榜",
  "parameters": {
    "category": "类别，缺省为 most-bookmarked",
    "lang": "语言，缺省为 zh"
  },
  "path": "/:lang/hongkong/explore/chart/:category"
}
```
