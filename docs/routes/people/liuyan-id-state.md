# 人民网 - 领导留言板

## Coverage
`index-only`

## Route
- Namespace: `people`
- Namespace Name: `人民网`
- Route Path: `/liuyan/:id/:state?`
- Route Name: `领导留言板`
- Example: `/people/liuyan/539`
- URL: `liuyan.people.com.cn/`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `liuyan.ts`
- Source Module: `() => import('@/routes/people/liuyan.ts')`

## Description
| 全部 | 待回复 | 办理中 | 已办理 |
| ---- | ------ | ------ | ------ |
| 1    | 2      | 3      | 4      |

## Parameters
- `id`: 编号，可在对应人物页 URL 中找到
- `state`: 状态，见下表，默认为全部


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
  - `liuyan.people.com.cn/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 全部 | 待回复 | 办理中 | 已办理 |\n| ---- | ------ | ------ | ------ |\n| 1    | 2      | 3      | 4      |",
  "example": "/people/liuyan/539",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "liuyan.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/people/liuyan.ts')",
  "name": "领导留言板",
  "parameters": {
    "id": "编号，可在对应人物页 URL 中找到",
    "state": "状态，见下表，默认为全部"
  },
  "path": "/liuyan/:id/:state?",
  "radar": [
    {
      "source": [
        "liuyan.people.com.cn/"
      ]
    }
  ],
  "url": "liuyan.people.com.cn/"
}
```
