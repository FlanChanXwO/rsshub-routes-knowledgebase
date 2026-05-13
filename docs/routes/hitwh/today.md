# 哈尔滨工业大学（威海） - 今日工大 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `hitwh`
- Namespace Name: `哈尔滨工业大学（威海）`
- Route Path: `/today`
- Route Name: `今日工大 - 通知公告`
- Example: `/hitwh/today`
- URL: `hitwh.edu.cn/1024/list.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `raptazure`
- Source Location: `today.ts`
- Source Module: `() => import('@/routes/hitwh/today.ts')`

## Description
_None_

## Parameters
_None_


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
  - `hitwh.edu.cn/1024/list.htm`
  - `hitwh.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/hitwh/today",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "today.ts",
  "maintainers": [
    "raptazure"
  ],
  "module": "() => import('@/routes/hitwh/today.ts')",
  "name": "今日工大 - 通知公告",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "hitwh.edu.cn/1024/list.htm",
        "hitwh.edu.cn/"
      ]
    }
  ],
  "url": "hitwh.edu.cn/1024/list.htm"
}
```
