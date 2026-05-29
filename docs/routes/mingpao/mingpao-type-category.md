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
  "heat": 29,
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
      "errorMessage": "[GET] \"https://news.mingpao.com/ins/%e6%b8%af%e8%81%9e/article/20260526/s00001/1779801844888/%e3%80%90%e9%99%84%e5%90%8d%e5%96%ae%e3%80%918%e9%96%93%e3%80%8c%e6%b4%be0%e7%8f%ad%e3%80%8d%e5%b0%8f%e5%ad%b8%e7%8d%b2%e5%87%86%e5%90%88%e4%bd%b5%e5%90%84%e7%8d%b2100%e8%90%ac%e5%85%83-4%e6%a0%a1%e6%ad%a5%e5%90%91%e3%80%8c%e6%ae%ba%e6%a0%a1%e3%80%8d\": 403 Forbidden\nStatus code 406\n",
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
      "errorMessage": "[GET] \"https://news.mingpao.com/pns/%e8%a6%81%e8%81%9e/article/20260527/s00001/1779819275223/%e7%b6%b2%e7%b4%84%e8%bb%8a%e6%93%ac%e7%99%bc1%e8%90%ac%e7%89%8c-%e5%b9%b4%e8%b2%bb1560-%e6%94%bf%e5%ba%9c-%e4%ba%ba%e4%ba%ba%e6%97%a5%e9%a7%956%e5%b0%8f%e6%99%82%e3%80%8c%e8%83%bd%e7%ac%a6%e5%b8%82%e6%b0%91%e9%9c%80%e6%b1%82%e3%80%8d-%e6%98%8e%e5%b9%b48%e6%9c%88%e8%a6%8f%e7%ae%a1\": 403 Forbidden\n",
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
