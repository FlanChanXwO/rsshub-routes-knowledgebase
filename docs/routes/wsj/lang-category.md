# The Wall Street Journal (WSJ) 华尔街日报 - News

## Coverage
`index-only`

## Route
- Namespace: `wsj`
- Namespace Name: `The Wall Street Journal (WSJ) 华尔街日报`
- Route Path: `/:lang/:category?`
- Route Name: `News`
- Example: `/wsj/en-us/opinion`
- URL: `cn.wsj.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `oppilate`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/wsj/news.ts')`

## Description
en_us

| World | U.S. | Politics | Economy | Business | Tech       | Markets | Opinion | Books & Arts | Real Estate | Life & Work | Sytle               | Sports |
| ----- | ---- | -------- | ------- | -------- | ---------- | ------- | ------- | ------------ | ----------- | ----------- | ------------------- | ------ |
| world | us   | politics | economy | business | technology | markets | opinion | books-arts   | realestate  | life-work   | style-entertainment | sports |

  zh-cn / zh-tw

| 国际  | 中国  | 金融市场 | 经济    | 商业     | 科技       | 派        | 专栏与观点 |
| ----- | ----- | -------- | ------- | -------- | ---------- | --------- | ---------- |
| world | china | markets  | economy | business | technology | life-arts | opinion    |

  Provide full article RSS for WSJ topics.

## Parameters
- `lang`: Language, `en-us`, `zh-cn`, `zh-tw`
- `category`: Category. See below


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "en_us\n\n| World | U.S. | Politics | Economy | Business | Tech       | Markets | Opinion | Books & Arts | Real Estate | Life & Work | Sytle               | Sports |\n| ----- | ---- | -------- | ------- | -------- | ---------- | ------- | ------- | ------------ | ----------- | ----------- | ------------------- | ------ |\n| world | us   | politics | economy | business | technology | markets | opinion | books-arts   | realestate  | life-work   | style-entertainment | sports |\n\n  zh-cn / zh-tw\n\n| 国际  | 中国  | 金融市场 | 经济    | 商业     | 科技       | 派        | 专栏与观点 |\n| ----- | ----- | -------- | ------- | -------- | ---------- | --------- | ---------- |\n| world | china | markets  | economy | business | technology | life-arts | opinion    |\n\n  Provide full article RSS for WSJ topics.",
  "example": "/wsj/en-us/opinion",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "oppilate"
  ],
  "module": "() => import('@/routes/wsj/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Category. See below",
    "lang": "Language, `en-us`, `zh-cn`, `zh-tw`"
  },
  "path": "/:lang/:category?"
}
```
