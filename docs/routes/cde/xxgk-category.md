# 国家药品审评网站 - 信息公开

## Coverage
`index-only`

## Route
- Namespace: `cde`
- Namespace Name: `国家药品审评网站`
- Route Path: `/xxgk/:category`
- Route Name: `信息公开`
- Example: `/cde/xxgk/priorityApproval`
- URL: `www.cde.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `xxgk.tsx`
- Source Module: `() => import('@/routes/cde/xxgk.tsx')`

## Description
|   优先审评公示   |  突破性治疗公示  | 临床试验默示许可 |
| :--------------: | :--------------: | :--------------: |
| priorityApproval | breakthroughCure |     cliniCal     |

## Parameters
- `category`: 类别，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "|   优先审评公示   |  突破性治疗公示  | 临床试验默示许可 |\n| :--------------: | :--------------: | :--------------: |\n| priorityApproval | breakthroughCure |     cliniCal     |",
  "example": "/cde/xxgk/priorityApproval",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xxgk.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/cde/xxgk.tsx')",
  "name": "信息公开",
  "parameters": {
    "category": "类别，见下表"
  },
  "path": "/xxgk/:category"
}
```
