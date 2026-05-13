# 得物 - 平台公告

## Coverage
`index-only`

## Route
- Namespace: `dewu`
- Namespace Name: `得物`
- Route Path: `/declaration/:categoryId?`
- Route Name: `平台公告`
- Example: `/dewu/declaration/1010580020`
- URL: `dewu.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `blade0910`
- Source Location: `declaration.ts`
- Source Module: `() => import('@/routes/dewu/declaration.ts')`

## Description
| 类型             | type       |
| ---------------- | ---------- |
| 技术变更         | 1010580020 |
| 服务市场规则中心 | 1014821004 |
| 规则变更         | 1011202692 |
| 维护公告         | 1010568195 |

## Parameters
- `categoryId`: 公告分类, 可在页面URL获取 默认为1010580020


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
  "description": "| 类型             | type       |\n| ---------------- | ---------- |\n| 技术变更         | 1010580020 |\n| 服务市场规则中心 | 1014821004 |\n| 规则变更         | 1011202692 |\n| 维护公告         | 1010568195 |",
  "example": "/dewu/declaration/1010580020",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "declaration.ts",
  "maintainers": [
    "blade0910"
  ],
  "module": "() => import('@/routes/dewu/declaration.ts')",
  "name": "平台公告",
  "parameters": {
    "categoryId": "公告分类, 可在页面URL获取 默认为1010580020"
  },
  "path": "/declaration/:categoryId?"
}
```
