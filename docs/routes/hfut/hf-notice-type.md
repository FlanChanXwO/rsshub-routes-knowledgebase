# 合肥工业大学 - 合肥校区通知

## Coverage
`index-only`

## Route
- Namespace: `hfut`
- Namespace Name: `合肥工业大学`
- Route Path: `/hf/notice/:type?`
- Route Name: `合肥校区通知`
- Example: `/hfut/hf/notice/tzgg`
- URL: `hfut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `batemax`
- Source Location: `hf/notice.ts`
- Source Module: `() => import('@/routes/hfut/hf/notice.ts')`

## Description
| 通知公告(https://news.hfut.edu.cn/tzgg2.htm) | 教学科研(https://news.hfut.edu.cn/tzgg2/jxky.htm) | 其他通知(https://news.hfut.edu.cn/tzgg2/qttz.htm) |
| ------------ | -------------- | ------------------ |
| tzgg         | jxky            | qttz              |

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
  - `news.hfut.edu.cn`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告(https://news.hfut.edu.cn/tzgg2.htm) | 教学科研(https://news.hfut.edu.cn/tzgg2/jxky.htm) | 其他通知(https://news.hfut.edu.cn/tzgg2/qttz.htm) |\n| ------------ | -------------- | ------------------ |\n| tzgg         | jxky            | qttz              |",
  "example": "/hfut/hf/notice/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "hf/notice.ts",
  "maintainers": [
    "batemax"
  ],
  "module": "() => import('@/routes/hfut/hf/notice.ts')",
  "name": "合肥校区通知",
  "parameters": {
    "type": "分类，见下表（默认为 `tzgg`)"
  },
  "path": "/hf/notice/:type?",
  "radar": [
    {
      "source": [
        "news.hfut.edu.cn"
      ]
    }
  ]
}
```
