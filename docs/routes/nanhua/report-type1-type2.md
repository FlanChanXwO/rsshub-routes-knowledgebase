# 南华期货 - 研报

## Coverage
`index-only`

## Route
- Namespace: `nanhua`
- Namespace Name: `南华期货`
- Route Path: `/report/:type1/:type2`
- Route Name: `研报`
- Example: `/nanhua/report/WEEK/WEEK_black`
- URL: `mall.nanhua.net/mall/r/w/reportNew/report-list.html`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `report.ts`
- Source Module: `() => import('@/routes/nanhua/report.ts')`

## Description
_None_

## Parameters
- `type1`: 一级分类代码，如 `WEEK`（周度报告）、`SEASON`（季年报告）、`HOT`（热点报告）等，需要使用 `encodeURIComponent` 编码
- `type2`: 二级分类代码，如 `WEEK_black`（黑色）、`WEEK_enchem`（能化）等，需要使用 `encodeURIComponent` 编码


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mall.nanhua.net/mall/r/w/reportNew/report-list.html`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/nanhua/report/WEEK/WEEK_black",
  "location": "report.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/nanhua/report.ts')",
  "name": "研报",
  "parameters": {
    "type1": "一级分类代码，如 `WEEK`（周度报告）、`SEASON`（季年报告）、`HOT`（热点报告）等，需要使用 `encodeURIComponent` 编码",
    "type2": "二级分类代码，如 `WEEK_black`（黑色）、`WEEK_enchem`（能化）等，需要使用 `encodeURIComponent` 编码"
  },
  "path": "/report/:type1/:type2",
  "radar": [
    {
      "source": [
        "mall.nanhua.net/mall/r/w/reportNew/report-list.html"
      ]
    }
  ],
  "url": "mall.nanhua.net/mall/r/w/reportNew/report-list.html"
}
```
