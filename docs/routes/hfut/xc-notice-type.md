# 合肥工业大学 - 宣城校区通知

## Coverage
`index-only`

## Route
- Namespace: `hfut`
- Namespace Name: `合肥工业大学`
- Route Path: `/xc/notice/:type?`
- Route Name: `宣城校区通知`
- Example: `/hfut/xc/notice/tzgg`
- URL: `hfut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `batemax`
- Source Location: `xc/notice.ts`
- Source Module: `() => import('@/routes/hfut/xc/notice.ts')`

## Description
| 通知公告(https://xc.hfut.edu.cn/1955/list.htm) | 院系动态-工作通知(https://xc.hfut.edu.cn/gztz/list.htm) |
| ------------ | -------------- |
| tzgg         | gztz           |

## Parameters
- `type`: 分类，见下表（默认为 `tzgg`)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportRadar`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xc.hfut.edu.cn`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告(https://xc.hfut.edu.cn/1955/list.htm) | 院系动态-工作通知(https://xc.hfut.edu.cn/gztz/list.htm) |\n| ------------ | -------------- |\n| tzgg         | gztz           |",
  "example": "/hfut/xc/notice/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "xc/notice.ts",
  "maintainers": [
    "batemax"
  ],
  "module": "() => import('@/routes/hfut/xc/notice.ts')",
  "name": "宣城校区通知",
  "parameters": {
    "type": "分类，见下表（默认为 `tzgg`)"
  },
  "path": "/xc/notice/:type?",
  "radar": [
    {
      "source": [
        "xc.hfut.edu.cn"
      ]
    }
  ]
}
```
