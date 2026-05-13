# 懂球帝 - 足球赛果

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/result/:team`
- Route Name: `足球赛果`
- Example: `/dongqiudi/result/50001755`
- URL: `m.dongqiudi.com`
- Language: `zh-CN`
- Categories: `sport`
- Maintainers: `HenryQW`
- Source Location: `result.ts`
- Source Module: `() => import('@/routes/dongqiudi/result.ts')`

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
  "example": "/dongqiudi/result/50001755",
  "location": "result.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/dongqiudi/result.ts')",
  "name": "足球赛果",
  "parameters": {
    "team": "球队 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中找到"
  },
  "path": "/result/:team",
  "radar": [
    {
      "source": [
        "www.dongqiudi.com/team/*team"
      ]
    }
  ]
}
```
