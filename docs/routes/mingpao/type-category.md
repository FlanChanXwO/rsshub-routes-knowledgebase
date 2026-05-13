# 明報 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `mingpao`
- Namespace Name: `明報`
- Route Path: `/:type?/:category?`
- Route Name: `新聞`
- Example: `/mingpao/ins/all`
- URL: `mingpao.com`
- Language: `zh-TW`
- Categories: `None`
- Maintainers: `TonyRL`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/mingpao/index.tsx')`

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
  "description": "| category | 即時新聞頻道 |\n| -------- | ------------ |\n| all      | 總目錄       |\n| s00001   | 港聞         |\n| s00002   | 經濟         |\n| s00003   | 地產         |\n| s00004   | 兩岸         |\n| s00005   | 國際         |\n| s00006   | 體育         |\n| s00007   | 娛樂         |\n| s00022   | 文摘         |\n| s00024   | 熱點         |\n\n| category | 每日明報頻道 |\n| -------- | ------------ |\n| s00001   | 要聞         |\n| s00002   | 港聞         |\n| s00003   | 社評         |\n| s00004   | 經濟         |\n| s00005   | 副刊         |\n| s00011   | 教育         |\n| s00012   | 觀點         |\n| s00013   | 中國         |\n| s00014   | 國際         |\n| s00015   | 體育         |\n| s00016   | 娛樂         |\n| s00017   | English      |\n| s00018   | 作家專欄     |",
  "example": "/mingpao/ins/all",
  "location": "index.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/mingpao/index.tsx')",
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
  ]
}
```
