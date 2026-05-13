# 客家電視台 - 新聞首頁

## Coverage
`index-only`

## Route
- Namespace: `hakkatv`
- Namespace Name: `客家電視台`
- Route Path: `/news/:type?`
- Route Name: `新聞首頁`
- Example: `/hakkatv/news`
- URL: `hakkatv.org.tw/news`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `type.ts`
- Source Module: `() => import('@/routes/hakkatv/type.ts')`

## Description
| 客家焦點 | 政經要聞  | 民生醫療 | 地方風采 | 國際萬象      |
| -------- | --------- | -------- | -------- | ------------- |
| hakka    | political | medical  | local    | international |

## Parameters
- `type`: 新聞，見下表，留空為全部


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
  - `hakkatv.org.tw/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 客家焦點 | 政經要聞  | 民生醫療 | 地方風采 | 國際萬象      |\n| -------- | --------- | -------- | -------- | ------------- |\n| hakka    | political | medical  | local    | international |",
  "example": "/hakkatv/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "type.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/hakkatv/type.ts')",
  "name": "新聞首頁",
  "parameters": {
    "type": "新聞，見下表，留空為全部"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "hakkatv.org.tw/news"
      ],
      "target": "/news"
    }
  ],
  "url": "hakkatv.org.tw/news"
}
```
