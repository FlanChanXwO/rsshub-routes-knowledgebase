# 上海交通大学 - 电子信息与电气工程学院

## Coverage
`index-only`

## Route
- Namespace: `sjtu`
- Namespace Name: `上海交通大学`
- Route Path: `/seiee/:path/:catID?/:searchCatCode?`
- Route Name: `电子信息与电气工程学院`
- Example: `/sjtu/seiee/xzzx_notice_bks`
- URL: `www.sjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `dzx-dzx`
- Source Location: `seiee/index.ts`
- Source Module: `() => import('@/routes/sjtu/seiee/index.ts')`

## Description
_None_

## Parameters
- `path`: 不含'.html'的最后一部分路径
- `catID`: '本科生人才培养'与'研究生人才培养'的类别ID
- `searchCatCode`: '本科生人才培养'与'研究生人才培养'下类别名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.seiee.sjtu.edu.cn/:path.html`
- `target`: `/seiee/:path`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/sjtu/seiee/xzzx_notice_bks",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "seiee/index.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/sjtu/seiee/index.ts')",
  "name": "电子信息与电气工程学院",
  "parameters": {
    "catID": "'本科生人才培养'与'研究生人才培养'的类别ID",
    "path": "不含'.html'的最后一部分路径",
    "searchCatCode": "'本科生人才培养'与'研究生人才培养'下类别名"
  },
  "path": "/seiee/:path/:catID?/:searchCatCode?",
  "radar": [
    {
      "source": [
        "www.seiee.sjtu.edu.cn/:path.html"
      ],
      "target": "/seiee/:path"
    }
  ]
}
```
