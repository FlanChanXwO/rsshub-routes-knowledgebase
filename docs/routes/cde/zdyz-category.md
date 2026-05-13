# 国家药品审评网站 - 指导原则专栏

## Coverage
`index-only`

## Route
- Namespace: `cde`
- Namespace Name: `国家药品审评网站`
- Route Path: `/zdyz/:category`
- Route Name: `指导原则专栏`
- Example: `/cde/zdyz/domesticGuide`
- URL: `www.cde.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `zdyz.ts`
- Source Module: `() => import('@/routes/cde/zdyz.ts')`

## Description
|    发布通告   |   征求意见  |
| :-----------: | :---------: |
| domesticGuide | opinionList |

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
  "description": "|    发布通告   |   征求意见  |\n| :-----------: | :---------: |\n| domesticGuide | opinionList |",
  "example": "/cde/zdyz/domesticGuide",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zdyz.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/cde/zdyz.ts')",
  "name": "指导原则专栏",
  "parameters": {
    "category": "类别，见下表"
  },
  "path": "/zdyz/:category"
}
```
