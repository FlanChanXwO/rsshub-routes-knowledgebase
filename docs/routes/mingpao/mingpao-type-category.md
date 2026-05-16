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
      "errorMessage": "[GET] \"https://news.mingpao.com/ins/%e5%85%a9%e5%b2%b8/article/20260513/s00004/1778682363599/%e4%b8%ad%e5%9c%8b%e6%b0%91%e8%88%aa%e5%b1%80%e6%88%90%e7%ab%8b%e4%bd%8e%e7%a9%ba%e5%ae%89%e5%85%a8%e5%8f%b8\": 403 Forbidden\nFailed to fetch\n",
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
      "errorMessage": "[GET] \"https://news.mingpao.com/pns/%e8%a6%81%e8%81%9e/article/20260515/s00001/1778780954784/%e4%b8%ad%e7%be%8e%e6%96%b0%e5%ae%9a%e4%bd%8d-%e5%bb%ba%e8%a8%ad%e6%80%a7%e6%88%b0%e7%95%a5%e7%a9%a9%e5%ae%9a%e9%97%9c%e4%bf%82-%e7%bf%92-%e5%90%88%e4%bd%9c%e7%82%ba%e4%b8%bb%e7%ab%b6%e7%88%ad%e6%9c%89%e5%ba%a6-%e7%89%b9%e6%9c%97%e6%99%ae%e9%82%809%e6%9c%88%e8%a8%aa%e7%be%8e\": 403 Forbidden\n",
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
