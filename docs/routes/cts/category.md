# 華視 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `cts`
- Namespace Name: `華視`
- Route Path: `/:category`
- Route Name: `新聞`
- Example: `/cts/real`
- URL: `news.cts.com.tw`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `miles170`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/cts/news.ts')`

## Description
| 即時 | 氣象    | 政治     | 國際          | 社會    | 運動   | 生活 | 財經  | 台語      | 地方  | 產業 | 綜合    | 藝文 | 娛樂      |
| ---- | ------- | -------- | ------------- | ------- | ------ | ---- | ----- | --------- | ----- | ---- | ------- | ---- | --------- |
| real | weather | politics | international | society | sports | life | money | taiwanese | local | pr   | general | arts | entertain |

## Parameters
- `category`: 类别


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `news.cts.com.tw/:category/index.html`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 即時 | 氣象    | 政治     | 國際          | 社會    | 運動   | 生活 | 財經  | 台語      | 地方  | 產業 | 綜合    | 藝文 | 娛樂      |\n| ---- | ------- | -------- | ------------- | ------- | ------ | ---- | ----- | --------- | ----- | ---- | ------- | ---- | --------- |\n| real | weather | politics | international | society | sports | life | money | taiwanese | local | pr   | general | arts | entertain |",
  "example": "/cts/real",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "miles170"
  ],
  "module": "() => import('@/routes/cts/news.ts')",
  "name": "新聞",
  "parameters": {
    "category": "类别"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "news.cts.com.tw/:category/index.html"
      ]
    }
  ]
}
```
