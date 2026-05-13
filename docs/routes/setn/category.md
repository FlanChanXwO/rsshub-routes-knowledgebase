# 三立新聞網 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `setn`
- Namespace Name: `三立新聞網`
- Route Path: `/:category?`
- Route Name: `新聞`
- Example: `/setn`
- URL: `setn.com/ViewAll.aspx`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/setn/index.ts')`

## Description
| 即時 | 熱門 | 娛樂 | 政治 | 社會 |
| ---- | ---- | ---- | ---- | ---- |

| 國際 | 兩岸 | 生活 | 健康 | 旅遊 |
| ---- | ---- | ---- | ---- | ---- |

| 運動 | 地方 | 財經 | 富房網 | 名家 |
| ---- | ---- | ---- | ------ | ---- |

| 新奇 | 科技 | 汽車 | 寵物 | 女孩 | HOT 焦點 |
| ---- | ---- | ---- | ---- | ---- | -------- |

## Parameters
- `category`: 分类，见下表，默认为即時


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
  - `setn.com/ViewAll.aspx`
  - `setn.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 即時 | 熱門 | 娛樂 | 政治 | 社會 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 國際 | 兩岸 | 生活 | 健康 | 旅遊 |\n| ---- | ---- | ---- | ---- | ---- |\n\n| 運動 | 地方 | 財經 | 富房網 | 名家 |\n| ---- | ---- | ---- | ------ | ---- |\n\n| 新奇 | 科技 | 汽車 | 寵物 | 女孩 | HOT 焦點 |\n| ---- | ---- | ---- | ---- | ---- | -------- |",
  "example": "/setn",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/setn/index.ts')",
  "name": "新聞",
  "parameters": {
    "category": "分类，见下表，默认为即時"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "setn.com/ViewAll.aspx",
        "setn.com/"
      ],
      "target": ""
    }
  ],
  "url": "setn.com/ViewAll.aspx"
}
```
