# 掘金 - 沸点

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/pins/:type?`
- Route Name: `沸点`
- Example: `/juejin/pins/6824710202487472141`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `xyqfer, laampui`
- Source Location: `pins.ts`
- Source Module: `() => import('@/routes/juejin/pins.ts')`

## Description
| 推荐      | 热门 | 上班摸鱼            | 内推招聘            | 一图胜千言          | 今天学到了          | 每天一道算法题      | 开发工具推荐        | 树洞一下            |
| --------- | ---- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- |
| recommend | hot  | 6824710203301167112 | 6819970850532360206 | 6824710202487472141 | 6824710202562969614 | 6824710202378436621 | 6824710202000932877 | 6824710203112423437 |

## Parameters
- `type`: 默认为 recommend，见下表


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
    "programming"
  ],
  "description": "| 推荐      | 热门 | 上班摸鱼            | 内推招聘            | 一图胜千言          | 今天学到了          | 每天一道算法题      | 开发工具推荐        | 树洞一下            |\n| --------- | ---- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- | ------------------- |\n| recommend | hot  | 6824710203301167112 | 6819970850532360206 | 6824710202487472141 | 6824710202562969614 | 6824710202378436621 | 6824710202000932877 | 6824710203112423437 |",
  "example": "/juejin/pins/6824710202487472141",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pins.ts",
  "maintainers": [
    "xyqfer",
    "laampui"
  ],
  "module": "() => import('@/routes/juejin/pins.ts')",
  "name": "沸点",
  "parameters": {
    "type": "默认为 recommend，见下表"
  },
  "path": "/pins/:type?"
}
```
