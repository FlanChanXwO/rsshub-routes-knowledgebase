# 哈尔滨理工大学 - 图书馆

## Coverage
`index-only`

## Route
- Namespace: `hrbust`
- Namespace Name: `哈尔滨理工大学`
- Route Path: `/lib/:category?`
- Route Name: `图书馆`
- Example: `/hrbust/lib`
- URL: `lib.hrbust.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `cscnk52`
- Source Location: `lib.ts`
- Source Module: `() => import('@/routes/hrbust/lib.ts')`

## Description
| 公告消息 | 资源动态 | 参考中心 | 常用工具 | 外借服务 | 报告厅及研讨间服务 | 外文引进数据库 | 外文电子图书 | 外文试用数据库 | 中文引进数据库 | 中文电子图书 | 中文试用数据库 |
|----------|----------|----------|----------|----------|--------------------|----------------|--------------|----------------|----------------|--------------|----------------|
| 3421     | 3422     | ckzx     | cygj     | wjfw     | ytjfw              | yw             | yw_3392      | yw_3395        | zw             | zw_3391      | zw_3394        |

## Parameters
- `category`: 栏目标识，默认为 3421（公告消息）


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `lib.hrbust.edu.cn/:category/list.htm`
- `target`: `/lib/:category`
### Rule 2
- `source`:
  - `lib.hrbust.edu.cn`
- `target`: `/lib`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公告消息 | 资源动态 | 参考中心 | 常用工具 | 外借服务 | 报告厅及研讨间服务 | 外文引进数据库 | 外文电子图书 | 外文试用数据库 | 中文引进数据库 | 中文电子图书 | 中文试用数据库 |\n|----------|----------|----------|----------|----------|--------------------|----------------|--------------|----------------|----------------|--------------|----------------|\n| 3421     | 3422     | ckzx     | cygj     | wjfw     | ytjfw              | yw             | yw_3392      | yw_3395        | zw             | zw_3391      | zw_3394        |",
  "example": "/hrbust/lib",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "lib.ts",
  "maintainers": [
    "cscnk52"
  ],
  "module": "() => import('@/routes/hrbust/lib.ts')",
  "name": "图书馆",
  "parameters": {
    "category": "栏目标识，默认为 3421（公告消息）"
  },
  "path": "/lib/:category?",
  "radar": [
    {
      "source": [
        "lib.hrbust.edu.cn/:category/list.htm"
      ],
      "target": "/lib/:category"
    },
    {
      "source": [
        "lib.hrbust.edu.cn"
      ],
      "target": "/lib"
    }
  ],
  "url": "lib.hrbust.edu.cn",
  "view": 5
}
```
