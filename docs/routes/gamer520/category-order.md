# 全球游戏交流中心 - 文章

## Coverage
`index-only`

## Route
- Namespace: `gamer520`
- Namespace Name: `全球游戏交流中心`
- Route Path: `/:category?/:order?`
- Route Name: `文章`
- Example: `/gamer520/switchyouxi`
- URL: `www.gamer520.com/`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `xzzpig`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/gamer520/index.ts')`

## Description
分类

| 所有 | Switch 游戏下载 | 金手指     | 3A 巨作 | switch 主题 | PC 游戏 |
| ---- | --------------- | ---------- | ------- | ----------- | ------- |
| all  | switchyouxi     | jinshouzhi | 3ajuzuo | zhuti       | pcgame  |

## Parameters
- `category`: 分类，见下表
- `order`: 排序，发布日期: date; 修改日期: modified


## Features
- `antiCrawler`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "分类\n\n| 所有 | Switch 游戏下载 | 金手指     | 3A 巨作 | switch 主题 | PC 游戏 |\n| ---- | --------------- | ---------- | ------- | ----------- | ------- |\n| all  | switchyouxi     | jinshouzhi | 3ajuzuo | zhuti       | pcgame  |",
  "example": "/gamer520/switchyouxi",
  "features": {
    "antiCrawler": true
  },
  "location": "index.ts",
  "maintainers": [
    "xzzpig"
  ],
  "module": "() => import('@/routes/gamer520/index.ts')",
  "name": "文章",
  "parameters": {
    "category": "分类，见下表",
    "order": "排序，发布日期: date; 修改日期: modified"
  },
  "path": "/:category?/:order?",
  "url": "www.gamer520.com/"
}
```
