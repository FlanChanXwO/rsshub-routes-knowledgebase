# 鹰角网络 - 明日方舟 - 游戏公告与新闻

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/hypergryph/arknights/news/:group?`
- Route Name: `明日方舟 - 游戏公告与新闻`
- Example: `/hypergryph/arknights/news`
- URL: `ak-conf.hypergryph.com/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `Astrian`
- Source Location: `arknights/news.ts`
- Source Module: `_None_`

## Description
| 全部 | 最新   | 公告         | 活动     | 新闻 |
| ---- | ------ | ------------ | -------- | ---- |
| ALL  | LATEST | ANNOUNCEMENT | ACTIVITY | NEWS |

## Parameters
- `group`: 分组，默认为 `ALL`


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `ak-conf.hypergryph.com/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 全部 | 最新   | 公告         | 活动     | 新闻 |\n| ---- | ------ | ------------ | -------- | ---- |\n| ALL  | LATEST | ANNOUNCEMENT | ACTIVITY | NEWS |",
  "example": "/hypergryph/arknights/news",
  "heat": 19,
  "location": "arknights/news.ts",
  "maintainers": [
    "Astrian"
  ],
  "name": "明日方舟 - 游戏公告与新闻",
  "parameters": {
    "group": "分组，默认为 `ALL`"
  },
  "path": "/arknights/news/:group?",
  "radar": [
    {
      "source": [
        "ak-conf.hypergryph.com/news"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "《明日方舟》游戏公告与新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56948849407992834",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ak.hypergryph.com/news",
      "title": "《明日方舟》游戏公告与新闻",
      "type": "feed",
      "url": "rsshub://hypergryph/arknights/news"
    },
    {
      "description": "《明日方舟》游戏公告与新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197299073968664578",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ak.hypergryph.com/news",
      "title": "《明日方舟》游戏公告与新闻",
      "type": "feed",
      "url": "rsshub://hypergryph/arknights/news/ACTIVITY"
    }
  ],
  "url": "ak-conf.hypergryph.com/news"
}
```
