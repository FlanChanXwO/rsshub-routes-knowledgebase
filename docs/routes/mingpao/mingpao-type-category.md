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
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "明報新聞網-即時新聞 RSS - Powered by RSSHub",
      "errorAt": "2025-11-13T23:43:50.376Z",
      "errorMessage": "[GET] \"https://news.mingpao.com/ins/%e6%b8%af%e8%81%9e/article/20260717/s00001/1784304979738/%e7%be%8e%e5%9c%8b%e7%a2%ba%e8%aa%8d%e3%80%8c%e8%a1%8c%e6%94%bf%e5%91%bd%e4%bb%a4%e3%80%8d%e7%b5%82%e6%ad%a2-%e6%9e%97%e5%ae%9a%e5%9c%8b%e7%ad%899%e4%ba%ba%e7%8d%b2%e6%92%a4%e5%88%b6%e8%a3%81-39%e4%b8%ad%e6%b8%af%e5%ae%98%e5%93%a1%e7%ba%8c%e8%a2%ab%e5%88%b6%e8%a3%81\": 403 Forbidden\nFailed to fetch\n",
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
      "errorMessage": "[GET] \"https://news.mingpao.com/pns/%e8%a6%81%e8%81%9e/article/20260717/s00001/1784223565844/%e6%94%bf%e5%ba%9c%e8%aa%8d%e7%9b%a3%e7%ae%a1%e5%bc%b1%e9%bb%9e-%e7%a8%b1%e4%b8%8d%e5%90%8c%e7%9b%b4%e6%8e%a5%e8%b2%ac%e4%bb%bb-%e9%99%b3%e8%be%ad%e7%b8%bd%e7%b5%90%e5%a4%a7%e7%81%ab6%e6%88%90%e5%9b%a0-%e6%b6%89%e4%ba%8b%e6%89%bf%e8%be%a6%e5%95%86%e5%b0%88%e6%a5%ad%e4%ba%ba%e5%a3%ab%e3%80%8c%e8%ad%89%e6%93%9a%e7%a2%ba%e7%ab%8b%e3%80%8d\": 403 Forbidden\n",
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
