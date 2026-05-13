# 簡訊設計 - 志祺七七

## Coverage
`index-only`

## Route
- Namespace: `simpleinfo`
- Namespace Name: `簡訊設計`
- Route Path: `/:category?`
- Route Name: `志祺七七`
- Example: `/simpleinfo`
- URL: `blog.simpleinfo.cc`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `haukeng`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/simpleinfo/index.tsx')`

## Description
| 夥伴聊聊 | 專案設計 |
| -------- | -------- |
| work     | talk     |

| 國內外新聞 | 政治百分百 | 社會觀察家 | 心理與哲學            |
| ---------- | ---------- | ---------- | --------------------- |
| news       | politics   | society    | psychology-philosophy |

| 科學大探索 | 環境與健康         | ACG 快樂聊 | 好書籍分享   | 其它主題     |
| ---------- | ------------------ | ---------- | ------------ | ------------ |
| science    | environment-health | acg        | book-sharing | other-topics |

## Parameters
- `category`: 分类名


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
  - `blog.simpleinfo.cc/blog/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 夥伴聊聊 | 專案設計 |\n| -------- | -------- |\n| work     | talk     |\n\n| 國內外新聞 | 政治百分百 | 社會觀察家 | 心理與哲學            |\n| ---------- | ---------- | ---------- | --------------------- |\n| news       | politics   | society    | psychology-philosophy |\n\n| 科學大探索 | 環境與健康         | ACG 快樂聊 | 好書籍分享   | 其它主題     |\n| ---------- | ------------------ | ---------- | ------------ | ------------ |\n| science    | environment-health | acg        | book-sharing | other-topics |",
  "example": "/simpleinfo",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "haukeng"
  ],
  "module": "() => import('@/routes/simpleinfo/index.tsx')",
  "name": "志祺七七",
  "parameters": {
    "category": "分类名"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "blog.simpleinfo.cc/blog/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
