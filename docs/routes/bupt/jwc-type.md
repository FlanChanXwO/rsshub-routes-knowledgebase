# 北京邮电大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `bupt`
- Namespace Name: `北京邮电大学`
- Route Path: `/jwc/:type`
- Route Name: `教务处`
- Example: `/bupt/jwc/tzgg`
- URL: `jwc.bupt.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Yoruet`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/bupt/jwc.ts')`

## Description
_None_

## Parameters
- `type`: {"description": "信息类型，可选值：tzgg（通知公告），xwzx（新闻资讯）", "optional": false, "type": "string"}


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
  - `jwc.bupt.edu.cn/tzgg1.htm`
- `target`: `/jwc/tzgg`
### Rule 2
- `source`:
  - `jwc.bupt.edu.cn/xwzx2.htm`
- `target`: `/jwc/xwzx`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/bupt/jwc/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "Yoruet"
  ],
  "module": "() => import('@/routes/bupt/jwc.ts')",
  "name": "教务处",
  "parameters": {
    "type": {
      "description": "信息类型，可选值：tzgg（通知公告），xwzx（新闻资讯）",
      "optional": false,
      "type": "string"
    }
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "jwc.bupt.edu.cn/tzgg1.htm"
      ],
      "target": "/jwc/tzgg"
    },
    {
      "source": [
        "jwc.bupt.edu.cn/xwzx2.htm"
      ],
      "target": "/jwc/xwzx"
    }
  ],
  "url": "jwc.bupt.edu.cn"
}
```
