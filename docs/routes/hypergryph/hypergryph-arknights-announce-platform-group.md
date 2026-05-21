# 鹰角网络 - 明日方舟 - 游戏内公告

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/hypergryph/arknights/announce/:platform?/:group?`
- Route Name: `明日方舟 - 游戏内公告`
- Example: `/hypergryph/arknights/announce`
- URL: `www.hypergryph.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `swwind`
- Source Location: `arknights/announce.ts`
- Source Module: `_None_`

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
  "description": "平台\n\n|  安卓服 | iOS 服 |   B 服   |\n| :-----: | :----: | :------: |\n| Android |   IOS  | Bilibili |\n\n分组\n\n| 全部 | 系统公告 | 活动公告 |\n| :--: | :------: | :------: |\n|  ALL |  SYSTEM  | ACTIVITY |",
  "example": "/hypergryph/arknights/announce",
  "heat": 37,
  "location": "arknights/announce.ts",
  "maintainers": [
    "swwind"
  ],
  "name": "明日方舟 - 游戏内公告",
  "parameters": {
    "group": "分组，默认为 ALL",
    "platform": "平台，默认为 Android"
  },
  "path": "/arknights/announce/:platform?/:group?",
  "topFeeds": [
    {
      "description": "《明日方舟》全部公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41374862675304448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ak.hypergryph.com/",
      "title": "《明日方舟》全部公告",
      "type": "feed",
      "url": "rsshub://hypergryph/arknights/announce"
    },
    {
      "description": "《明日方舟》全部公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "159622024157116416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ak.hypergryph.com/",
      "title": "《明日方舟》全部公告",
      "type": "feed",
      "url": "rsshub://hypergryph/arknights/announce/Android/ALL"
    }
  ]
}
```
