# 懂球帝 - 球队新闻

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/team_news/:team`
- Route Name: `球队新闻`
- Example: `/dongqiudi/team_news/50001755`
- URL: `m.dongqiudi.com`
- Language: `zh-CN`
- Categories: `sport`
- Maintainers: `HenryQW`
- Source Location: `team-news.ts`
- Source Module: `() => import('@/routes/dongqiudi/team-news.ts')`

## Description
_None_

## Parameters
- `team`: 球队 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dongqiudi.com/team/*team`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/dongqiudi/team_news/50001755",
  "location": "team-news.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/dongqiudi/team-news.ts')",
  "name": "球队新闻",
  "parameters": {
    "team": "球队 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中找到"
  },
  "path": "/team_news/:team",
  "radar": [
    {
      "source": [
        "www.dongqiudi.com/team/*team"
      ]
    }
  ]
}
```
