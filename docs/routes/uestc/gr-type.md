# 电子科技大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/gr/:type?`
- Route Name: `研究生院`
- Example: `/uestc/gr/student`
- URL: `gr.uestc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `huyyi, mobyw`
- Source Location: `gr.ts`
- Source Module: `() => import('@/routes/uestc/gr.ts')`

## Description
| 重要公告  | 教学管理 | 学位管理 | 学生管理 | 就业实践 |
| --------- | -------- | -------- | -------- | -------- |
| important | teaching | degree   | student  | practice |

## Parameters
- `type`: 默认为 `important`


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
  - `gr.uestc.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 重要公告  | 教学管理 | 学位管理 | 学生管理 | 就业实践 |\n| --------- | -------- | -------- | -------- | -------- |\n| important | teaching | degree   | student  | practice |",
  "example": "/uestc/gr/student",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gr.ts",
  "maintainers": [
    "huyyi",
    "mobyw"
  ],
  "module": "() => import('@/routes/uestc/gr.ts')",
  "name": "研究生院",
  "parameters": {
    "type": "默认为 `important`"
  },
  "path": "/gr/:type?",
  "radar": [
    {
      "source": [
        "gr.uestc.edu.cn/"
      ]
    }
  ],
  "url": "gr.uestc.edu.cn/"
}
```
