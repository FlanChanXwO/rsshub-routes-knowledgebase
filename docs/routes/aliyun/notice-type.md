# 阿里云 - 公告

## Coverage
`index-only`

## Route
- Namespace: `aliyun`
- Namespace Name: `阿里云`
- Route Path: `/notice/:type?`
- Route Name: `公告`
- Example: `/aliyun/notice`
- URL: `developer.aliyun.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `muzea`
- Source Location: `notice.ts`
- Source Module: `() => import('@/routes/aliyun/notice.ts')`

## Description
| 类型     | type |
| -------- | ---- |
| 全部     |      |
| 升级公告 | 1    |
| 安全公告 | 2    |
| 备案公告 | 3    |
| 其他     | 4    |

## Parameters
- `type`: N


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 类型     | type |\n| -------- | ---- |\n| 全部     |      |\n| 升级公告 | 1    |\n| 安全公告 | 2    |\n| 备案公告 | 3    |\n| 其他     | 4    |",
  "example": "/aliyun/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "notice.ts",
  "maintainers": [
    "muzea"
  ],
  "module": "() => import('@/routes/aliyun/notice.ts')",
  "name": "公告",
  "parameters": {
    "type": "N"
  },
  "path": "/notice/:type?"
}
```
