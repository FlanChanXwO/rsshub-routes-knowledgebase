# 鹰角网络 - 明日方舟 - 游戏内公告

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/arknights/announce/:platform?/:group?`
- Route Name: `明日方舟 - 游戏内公告`
- Example: `/hypergryph/arknights/announce`
- URL: `www.hypergryph.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `swwind`
- Source Location: `arknights/announce.ts`
- Source Module: `() => import('@/routes/hypergryph/arknights/announce.ts')`

## Description
平台

|  安卓服 | iOS 服 |   B 服   |
| :-----: | :----: | :------: |
| Android |   IOS  | Bilibili |

  分组

| 全部 | 系统公告 | 活动公告 |
| :--: | :------: | :------: |
|  ALL |  SYSTEM  | ACTIVITY |

## Parameters
- `platform`: 平台，默认为 Android
- `group`: 分组，默认为 ALL


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "平台\n\n|  安卓服 | iOS 服 |   B 服   |\n| :-----: | :----: | :------: |\n| Android |   IOS  | Bilibili |\n\n  分组\n\n| 全部 | 系统公告 | 活动公告 |\n| :--: | :------: | :------: |\n|  ALL |  SYSTEM  | ACTIVITY |",
  "example": "/hypergryph/arknights/announce",
  "location": "arknights/announce.ts",
  "maintainers": [
    "swwind"
  ],
  "module": "() => import('@/routes/hypergryph/arknights/announce.ts')",
  "name": "明日方舟 - 游戏内公告",
  "parameters": {
    "group": "分组，默认为 ALL",
    "platform": "平台，默认为 Android"
  },
  "path": "/arknights/announce/:platform?/:group?"
}
```
