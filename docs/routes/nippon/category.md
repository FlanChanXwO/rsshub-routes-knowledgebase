# 走进日本 - 政治外交

## Coverage
`index-only`

## Route
- Namespace: `nippon`
- Namespace Name: `走进日本`
- Route Path: `/:category?`
- Route Name: `政治外交`
- Example: `/nippon/Politics`
- URL: `www.nippon.com`
- Language: `zh-CN`
- Categories: `travel`
- Maintainers: `laampui`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/nippon/index.ts')`

## Description
| 政治     | 经济    | 社会    | 展览预告 | 焦点专题           | 深度报道 | 话题         | 日本信息库 | 日本一蹩      | 人物访谈 | 编辑部通告    |
| -------- | ------- | ------- | -------- | ------------------ | -------- | ------------ | ---------- | ------------- | -------- | ------------- |
| Politics | Economy | Society | Culture  | Science,Technology | In-depth | japan-topics | japan-data | japan-glances | People   | Announcements |

## Parameters
- `category`: 默认政治，可选如下


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
  - `www.nippon.com/nippon/:category?`
  - `www.nippon.com/cn`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "description": "| 政治     | 经济    | 社会    | 展览预告 | 焦点专题           | 深度报道 | 话题         | 日本信息库 | 日本一蹩      | 人物访谈 | 编辑部通告    |\n| -------- | ------- | ------- | -------- | ------------------ | -------- | ------------ | ---------- | ------------- | -------- | ------------- |\n| Politics | Economy | Society | Culture  | Science,Technology | In-depth | japan-topics | japan-data | japan-glances | People   | Announcements |",
  "example": "/nippon/Politics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "laampui"
  ],
  "module": "() => import('@/routes/nippon/index.ts')",
  "name": "政治外交",
  "parameters": {
    "category": "默认政治，可选如下"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.nippon.com/nippon/:category?",
        "www.nippon.com/cn"
      ]
    }
  ]
}
```
