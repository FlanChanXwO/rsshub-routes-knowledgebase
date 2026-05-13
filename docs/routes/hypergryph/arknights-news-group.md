# 鹰角网络 - 明日方舟 - 游戏公告与新闻

## Coverage
`index-only`

## Route
- Namespace: `hypergryph`
- Namespace Name: `鹰角网络`
- Route Path: `/arknights/news/:group?`
- Route Name: `明日方舟 - 游戏公告与新闻`
- Example: `/hypergryph/arknights/news`
- URL: `ak-conf.hypergryph.com/news`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `Astrian`
- Source Location: `arknights/news.ts`
- Source Module: `() => import('@/routes/hypergryph/arknights/news.ts')`

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
  "description": "\n| 全部 | 最新   | 公告         | 活动     | 新闻 |\n| ---- | ------ | ------------ | -------- | ---- |\n| ALL  | LATEST | ANNOUNCEMENT | ACTIVITY | NEWS |",
  "example": "/hypergryph/arknights/news",
  "location": "arknights/news.ts",
  "maintainers": [
    "Astrian"
  ],
  "module": "() => import('@/routes/hypergryph/arknights/news.ts')",
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
  "url": "ak-conf.hypergryph.com/news"
}
```
