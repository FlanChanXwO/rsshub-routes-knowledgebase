# 円谷ステーション - ニュース

## Coverage
`index-only`

## Route
- Namespace: `m-78`
- Namespace Name: `円谷ステーション`
- Route Path: `/news/:category?`
- Route Name: `ニュース`
- Example: `/m-78/news`
- URL: `m-78.jp`
- Language: `ja`
- Categories: `anime`
- Maintainers: `KarasuShin`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/m-78/news.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "news", "description": "news category", "options": [{"label": "ニュース", "value": "news"}, {"label": "動画配信", "value": "streaming"}, {"label": "イベント", "value": "event"}, {"label": "放送", "value": "onair"}, {"label": "放送/配信", "value": "broadcast"}, {"label": "グッズ", "value": "goods"}, {"label": "ウルトラマン カードゲーム", "value": "ultraman-cardgame"}, {"label": "ショップ", "value": "shop"}, {"label": "Blu-ray・DVD", "value": "blu-ray_dvd"}, {"label": "デジタル", "value": "digital"}]}


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `m-78.jp/news`
- `target`: `/news`
### Rule 2
- `source`:
  - `m-78.jp/news/category/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/m-78/news",
  "features": {
    "supportRadar": true
  },
  "location": "news.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/m-78/news.ts')",
  "name": "ニュース",
  "parameters": {
    "category": {
      "default": "news",
      "description": "news category",
      "options": [
        {
          "label": "ニュース",
          "value": "news"
        },
        {
          "label": "動画配信",
          "value": "streaming"
        },
        {
          "label": "イベント",
          "value": "event"
        },
        {
          "label": "放送",
          "value": "onair"
        },
        {
          "label": "放送/配信",
          "value": "broadcast"
        },
        {
          "label": "グッズ",
          "value": "goods"
        },
        {
          "label": "ウルトラマン カードゲーム",
          "value": "ultraman-cardgame"
        },
        {
          "label": "ショップ",
          "value": "shop"
        },
        {
          "label": "Blu-ray・DVD",
          "value": "blu-ray_dvd"
        },
        {
          "label": "デジタル",
          "value": "digital"
        }
      ]
    }
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "m-78.jp/news"
      ],
      "target": "/news"
    },
    {
      "source": [
        "m-78.jp/news/category/:category"
      ],
      "target": "/news/:category"
    }
  ],
  "view": 0
}
```
