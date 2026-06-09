# 明報 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `mingpao`
- Namespace Name: `明報`
- Route Path: `/mingpao/:type?/:category?`
- Route Name: `新聞`
- Example: `/mingpao/ins/all`
- URL: `mingpao.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `_None_`

## Description
| category | 即時新聞頻道 |
| -------- | ------------ |
| all      | 總目錄       |
| s00001   | 港聞         |
| s00002   | 經濟         |
| s00003   | 地產         |
| s00004   | 兩岸         |
| s00005   | 國際         |
| s00006   | 體育         |
| s00007   | 娛樂         |
| s00022   | 文摘         |
| s00024   | 熱點         |

| category | 每日明報頻道 |
| -------- | ------------ |
| s00001   | 要聞         |
| s00002   | 港聞         |
| s00003   | 社評         |
| s00004   | 經濟         |
| s00005   | 副刊         |
| s00011   | 教育         |
| s00012   | 觀點         |
| s00013   | 中國         |
| s00014   | 國際         |
| s00015   | 體育         |
| s00016   | 娛樂         |
| s00017   | English      |
| s00018   | 作家專欄     |

## Parameters
- `type`: {"default": "ins", "description": "新聞類型", "options": [{"label": "即時新聞", "value": "ins"}, {"label": "每日明報", "value": "pns"}]}
- `category`: 頻道，見下表


## Features
_None_

## Radar
### Rule 1
- `title`: `即時新聞`
- `source`:
  - `news.mingpao.com/ins/:categoryName/section/:date/:category`
- `target`: `/mingpao/ins/:category`
### Rule 2
- `title`: `每日明報`
- `source`:
  - `news.mingpao.com/pns/:categoryName/section/:date/:category`
- `target`: `/mingpao/pns/:category`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| category | 即時新聞頻道 |\n| -------- | ------------ |\n| all      | 總目錄       |\n| s00001   | 港聞         |\n| s00002   | 經濟         |\n| s00003   | 地產         |\n| s00004   | 兩岸         |\n| s00005   | 國際         |\n| s00006   | 體育         |\n| s00007   | 娛樂         |\n| s00022   | 文摘         |\n| s00024   | 熱點         |\n\n| category | 每日明報頻道 |\n| -------- | ------------ |\n| s00001   | 要聞         |\n| s00002   | 港聞         |\n| s00003   | 社評         |\n| s00004   | 經濟         |\n| s00005   | 副刊         |\n| s00011   | 教育         |\n| s00012   | 觀點         |\n| s00013   | 中國         |\n| s00014   | 國際         |\n| s00015   | 體育         |\n| s00016   | 娛樂         |\n| s00017   | English      |\n| s00018   | 作家專欄     |",
  "example": "/mingpao/ins/all",
  "heat": 27,
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "name": "新聞",
  "parameters": {
    "category": "頻道，見下表",
    "type": {
      "default": "ins",
      "description": "新聞類型",
      "options": [
        {
          "label": "即時新聞",
          "value": "ins"
        },
        {
          "label": "每日明報",
          "value": "pns"
        }
      ]
    }
  },
  "path": "/:type?/:category?",
  "radar": [
    {
      "source": [
        "news.mingpao.com/ins/:categoryName/section/:date/:category"
      ],
      "target": "/mingpao/ins/:category",
      "title": "即時新聞"
    },
    {
      "source": [
        "news.mingpao.com/pns/:categoryName/section/:date/:category"
      ],
      "target": "/mingpao/pns/:category",
      "title": "每日明報"
    }
  ],
  "topFeeds": [
    {
      "description": "明報新聞網-即時新聞 RSS - Powered by RSSHub",
      "errorAt": "2025-11-13T23:43:50.376Z",
      "errorMessage": "[GET] \"https://news.mingpao.com/ins/%e6%b8%af%e8%81%9e/article/20260607/s00001/1780825142879/%e8%8b%b1%e5%9f%ba%e5%ae%a3%e5%b8%83%e8%bd%84%e4%b8%8b%e5%b9%bc%e5%9c%92%e8%88%87%e4%b8%ad%e5%b0%8f%e5%ad%b8%e5%85%a8%e9%83%a8%e3%80%8c%e7%b5%90%e9%be%8d%e3%80%8d\": 403 \nFailed to fetch\n",
      "id": "67446046265380864",
      "image": "https://news.mingpao.com/image/mingpaonews_logo2.png",
      "ownerUserId": null,
      "siteUrl": "https://news.mingpao.com/",
      "title": "明報新聞網-即時新聞 RSS 總目錄",
      "type": "feed",
      "url": "rsshub://mingpao/ins/all"
    },
    {
      "description": "明報新聞網-每日明報 RSS - Powered by RSSHub",
      "errorAt": "2026-02-04T20:51:42.711Z",
      "errorMessage": "[GET] \"https://news.mingpao.com/pns/%e8%a6%81%e8%81%9e/article/20260607/s00001/1780768968400/%e6%b8%ac%e9%87%8f%e5%b8%ab%e5%ad%b8%e6%9c%83%e5%80%a1%e6%94%b9%e9%9d%a9%e5%bc%b7%e5%88%b6%e9%a9%97%e6%a8%93-%e8%a8%82%e5%8f%83%e8%80%83%e5%83%b9-%e5%8f%af%e6%8e%a2%e8%a8%8e%e7%b6%ad%e4%bf%ae%e5%88%86%e9%9a%8e%e6%ae%b5%e5%ae%9a%e6%99%82%e9%99%90-%e8%a8%ad%e7%8d%a8%e7%ab%8b%e6%a9%9f%e6%a7%8b%e4%bb%a3%e8%be%a6%e6%8b%9b%e6%a8%99\": 403 \n",
      "id": "79131389613658112",
      "image": "https://news.mingpao.com/image/mingpaonews_logo2.png",
      "ownerUserId": null,
      "siteUrl": "https://news.mingpao.com/",
      "title": "明報新聞網-每日明報 RSS 要聞",
      "type": "feed",
      "url": "rsshub://mingpao/pns"
    }
  ]
}
```
