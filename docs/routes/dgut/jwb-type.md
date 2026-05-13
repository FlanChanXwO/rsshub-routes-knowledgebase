# 东莞理工学院 - 教务部通知公告

## Coverage
`index-only`

## Route
- Namespace: `dgut`
- Namespace Name: `东莞理工学院`
- Route Path: `/jwb/:type?`
- Route Name: `教务部通知公告`
- Example: `/dgut/jwb/jwtz`
- URL: `www.dgut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `1200522928`
- Source Location: `jwb.ts`
- Source Module: `() => import('@/routes/dgut/jwb.ts')`

## Description
| 教学动态 | 教务通知 | 教研通知 | 实践通知 | 产业学院 |  通识教育  |"杨振宁"班|招生信息 |采购公告 |
| ------- | -------  | ---------| --------| --------| ----------|---------|------- |--------|
| jxdt    | jwtz     | jytz     |   sjtz  |   cyxy  |   tsjy    | yznb    |  zsxx  | cggg   |

## Parameters
- `type`: 哪种通知，默认为教务通知


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `jwb.dgut.edu.cn/tzgg/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教学动态 | 教务通知 | 教研通知 | 实践通知 | 产业学院 |  通识教育  |\"杨振宁\"班|招生信息 |采购公告 |\n| ------- | -------  | ---------| --------| --------| ----------|---------|------- |--------|\n| jxdt    | jwtz     | jytz     |   sjtz  |   cyxy  |   tsjy    | yznb    |  zsxx  | cggg   |",
  "example": "/dgut/jwb/jwtz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwb.ts",
  "maintainers": [
    "1200522928"
  ],
  "module": "() => import('@/routes/dgut/jwb.ts')",
  "name": "教务部通知公告",
  "parameters": {
    "type": "哪种通知，默认为教务通知"
  },
  "path": "/jwb/:type?",
  "radar": [
    {
      "source": [
        "jwb.dgut.edu.cn/tzgg/"
      ],
      "target": ""
    }
  ]
}
```
