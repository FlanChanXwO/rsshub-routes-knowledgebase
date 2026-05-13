# 语雀 - 知识库

## Coverage
`index-only`

## Route
- Namespace: `yuque`
- Namespace Name: `语雀`
- Route Path: `/:name/:book`
- Route Name: `知识库`
- Example: `/yuque/ruanyf/weekly`
- URL: `yuque.com`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `aha2mao, ltaoo`
- Source Location: `book.ts`
- Source Module: `() => import('@/routes/yuque/book.ts')`

## Description
| Node.js 专栏                                             | 阮一峰每周分享                                                 | 语雀使用手册                                             |
| -------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------- |
| [/yuque/egg/nodejs](https://rsshub.app/yuque/egg/nodejs) | [/yuque/ruanyf/weekly](https://rsshub.app/yuque/ruanyf/weekly) | [/yuque/yuque/help](https://rsshub.app/yuque/yuque/help) |

## Parameters
- `name`: 用戶名
- `book`: 知识库 ID


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
  - `yuque.com/:name/:book`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| Node.js 专栏                                             | 阮一峰每周分享                                                 | 语雀使用手册                                             |\n| -------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------- |\n| [/yuque/egg/nodejs](https://rsshub.app/yuque/egg/nodejs) | [/yuque/ruanyf/weekly](https://rsshub.app/yuque/ruanyf/weekly) | [/yuque/yuque/help](https://rsshub.app/yuque/yuque/help) |",
  "example": "/yuque/ruanyf/weekly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "book.ts",
  "maintainers": [
    "aha2mao",
    "ltaoo"
  ],
  "module": "() => import('@/routes/yuque/book.ts')",
  "name": "知识库",
  "parameters": {
    "book": "知识库 ID",
    "name": "用戶名"
  },
  "path": "/:name/:book",
  "radar": [
    {
      "source": [
        "yuque.com/:name/:book"
      ]
    }
  ]
}
```
