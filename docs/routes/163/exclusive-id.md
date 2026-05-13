# 网易公开课 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/exclusive/:id?`
- Route Name: `栏目`
- Example: `/163/exclusive/qsyk`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `exclusive.ts`
- Source Module: `() => import('@/routes/163/exclusive.ts')`

## Description
| 分类     | 编号 |
| -------- | ---- |
| 首页     |      |
| 轻松一刻 | qsyk |
| 槽值     | cz   |
| 人间     | rj   |
| 大国小民 | dgxm |
| 三三有梗 | ssyg |
| 数读     | sd   |
| 看客     | kk   |
| 下划线   | xhx  |
| 谈心社   | txs  |
| 哒哒     | dd   |
| 胖编怪聊 | pbgl |
| 曲一刀   | qyd  |
| 今日之声 | jrzs |
| 浪潮     | lc   |
| 沸点     | fd   |

## Parameters
- `id`: 栏目, 默认为首页


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
  - `3g.163.com/touch/exclusive/sub/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 分类     | 编号 |\n| -------- | ---- |\n| 首页     |      |\n| 轻松一刻 | qsyk |\n| 槽值     | cz   |\n| 人间     | rj   |\n| 大国小民 | dgxm |\n| 三三有梗 | ssyg |\n| 数读     | sd   |\n| 看客     | kk   |\n| 下划线   | xhx  |\n| 谈心社   | txs  |\n| 哒哒     | dd   |\n| 胖编怪聊 | pbgl |\n| 曲一刀   | qyd  |\n| 今日之声 | jrzs |\n| 浪潮     | lc   |\n| 沸点     | fd   |",
  "example": "/163/exclusive/qsyk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "exclusive.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/163/exclusive.ts')",
  "name": "栏目",
  "parameters": {
    "id": "栏目, 默认为首页"
  },
  "path": "/exclusive/:id?",
  "radar": [
    {
      "source": [
        "3g.163.com/touch/exclusive/sub/:id"
      ]
    }
  ]
}
```
