# 巴哈姆特電玩資訊站 - GNN 新聞

## Coverage
`index-only`

## Route
- Namespace: `gamer`
- Namespace Name: `巴哈姆特電玩資訊站`
- Route Path: `/gnn/:category?`
- Route Name: `GNN 新聞`
- Example: `/gamer/gnn/1`
- URL: `acg.gamer.com.tw`
- Language: `zh-TW`
- Categories: `anime`
- Maintainers: `Arracc, ladeng07, pseudoyu`
- Source Location: `gnn-index.ts`
- Source Module: `() => import('@/routes/gamer/gnn-index.ts')`

## Description
缺省為首頁

## Parameters
- `category`: {"description": "版塊", "options": [{"label": "PC", "value": "1"}, {"label": "TV 掌機", "value": "3"}, {"label": "手機遊戲", "value": "4"}, {"label": "動漫畫", "value": "5"}, {"label": "主題報導", "value": "9"}, {"label": "活動展覽", "value": "11"}, {"label": "電競", "value": "13"}, {"label": "Switch", "value": "ns"}, {"label": "PS5", "value": "ps5"}, {"label": "PS4", "value": "ps4"}, {"label": "XboxOne", "value": "xbone"}, {"label": "XboxSX", "value": "xbsx"}, {"label": "PC 單機", "value": "pc"}, {"label": "PC 線上", "value": "olg"}, {"label": "iOS", "value": "ios"}, {"label": "Android", "value": "android"}, {"label": "Web", "value": "web"}, {"label": "漫畫", "value": "comic"}, {"label": "動畫", "value": "anime"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "缺省為首頁",
  "example": "/gamer/gnn/1",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gnn-index.ts",
  "maintainers": [
    "Arracc",
    "ladeng07",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/gamer/gnn-index.ts')",
  "name": "GNN 新聞",
  "parameters": {
    "category": {
      "description": "版塊",
      "options": [
        {
          "label": "PC",
          "value": "1"
        },
        {
          "label": "TV 掌機",
          "value": "3"
        },
        {
          "label": "手機遊戲",
          "value": "4"
        },
        {
          "label": "動漫畫",
          "value": "5"
        },
        {
          "label": "主題報導",
          "value": "9"
        },
        {
          "label": "活動展覽",
          "value": "11"
        },
        {
          "label": "電競",
          "value": "13"
        },
        {
          "label": "Switch",
          "value": "ns"
        },
        {
          "label": "PS5",
          "value": "ps5"
        },
        {
          "label": "PS4",
          "value": "ps4"
        },
        {
          "label": "XboxOne",
          "value": "xbone"
        },
        {
          "label": "XboxSX",
          "value": "xbsx"
        },
        {
          "label": "PC 單機",
          "value": "pc"
        },
        {
          "label": "PC 線上",
          "value": "olg"
        },
        {
          "label": "iOS",
          "value": "ios"
        },
        {
          "label": "Android",
          "value": "android"
        },
        {
          "label": "Web",
          "value": "web"
        },
        {
          "label": "漫畫",
          "value": "comic"
        },
        {
          "label": "動畫",
          "value": "anime"
        }
      ]
    }
  },
  "path": "/gnn/:category?",
  "view": 0
}
```
