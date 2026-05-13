# Boss 设计 - 分类

## Coverage
`index-only`

## Route
- Namespace: `bossdesign`
- Namespace Name: `Boss 设计`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/bossdesign`
- URL: `bossdesign.cn`
- Language: `zh-CN`
- Categories: `design`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/bossdesign/index.ts')`

## Description
| Boss 笔记 | 电脑日志        | 素材资源         | 设计师神器      | 设计教程        | 设计资讯            |
| --------- | --------------- | ---------------- | --------------- | --------------- | ------------------- |
| note      | computer-skills | design-resources | design-software | design-tutorial | design_information |

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，留空为全部


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
    "design"
  ],
  "description": "| Boss 笔记 | 电脑日志        | 素材资源         | 设计师神器      | 设计教程        | 设计资讯            |\n| --------- | --------------- | ---------------- | --------------- | --------------- | ------------------- |\n| note      | computer-skills | design-resources | design-software | design-tutorial | design_information |",
  "example": "/bossdesign",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/bossdesign/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，留空为全部"
  },
  "path": "/:category?"
}
```
