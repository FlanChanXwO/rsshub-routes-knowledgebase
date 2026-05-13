# 游戏星辰 - 游戏星辰

## Coverage
`index-only`

## Route
- Namespace: `2023game`
- Namespace Name: `游戏星辰`
- Route Path: `/:category?/:tab?`
- Route Name: `游戏星辰`
- Example: `/2023game/sgame/topicList`
- URL: `www.2023game.com/`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `xzzpig`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/2023game/index.ts')`

## Description
分类

| PS4游戏 | switch游戏 | 3DS游戏 | PSV游戏 | Xbox360 | PS3游戏 | 世嘉MD/SS | PSP游戏 | PC周边 | 怀旧掌机 | 怀旧主机 | PS4教程 | PS4金手指 | switch金手指 | switch教程 | switch补丁 | switch主题 | switch存档 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| ps4 | sgame | 3ds | psv | jiaocheng | ps3yx | zhuji.md | zhangji.psp | pcgame | zhangji | zhuji | ps4.psjc | ps41.ps4pkg | nsaita.cundang | nsaita.pojie | nsaita.buding | nsaita.zhutie | nsaita.zhuti |

## Parameters
- `category`: 分类，见下表
- `tab`: 标签, 所有:all;最新:topicList;热门:jhcpb


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
    "game"
  ],
  "description": "分类\n\n| PS4游戏 | switch游戏 | 3DS游戏 | PSV游戏 | Xbox360 | PS3游戏 | 世嘉MD/SS | PSP游戏 | PC周边 | 怀旧掌机 | 怀旧主机 | PS4教程 | PS4金手指 | switch金手指 | switch教程 | switch补丁 | switch主题 | switch存档 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| ps4 | sgame | 3ds | psv | jiaocheng | ps3yx | zhuji.md | zhangji.psp | pcgame | zhangji | zhuji | ps4.psjc | ps41.ps4pkg | nsaita.cundang | nsaita.pojie | nsaita.buding | nsaita.zhutie | nsaita.zhuti |",
  "example": "/2023game/sgame/topicList",
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
    "xzzpig"
  ],
  "module": "() => import('@/routes/2023game/index.ts')",
  "name": "游戏星辰",
  "parameters": {
    "category": "分类，见下表",
    "tab": "标签, 所有:all;最新:topicList;热门:jhcpb"
  },
  "path": "/:category?/:tab?",
  "url": "www.2023game.com/"
}
```
