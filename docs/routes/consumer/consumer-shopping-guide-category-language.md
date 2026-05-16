# 消费者委员会 - 消費全攻略

## Coverage
`index-only`

## Route
- Namespace: `consumer`
- Namespace Name: `消费者委员会`
- Route Path: `/consumer/shopping-guide/:category?/:language?`
- Route Name: `消費全攻略`
- Example: `/consumer/shopping-guide`
- URL: `consumer.org.hk`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `shopping-guide.ts`
- Source Module: `_None_`

## Description
| 冷知識 | 懶人包 | 特集     | 銀髮一族           | 飲食煮意         | 科技達人   | 健康美容          | 規劃人生                    | 消閒娛樂                  | 家品家電        | 親子時光        | 綠色生活     |
| ------ | ------ | -------- | ------------------ | ---------------- | ---------- | ----------------- | --------------------------- | ------------------------- | --------------- | --------------- | ------------ |
| trivia | tips   | features | silver-hair-market | food-and-cooking | tech-savvy | health-and-beauty | life-and-financial-planning | leisure-and-entertainment | home-appliances | family-and-kids | green-living |

## Parameters
- `category`: 分类，见下表，默认为 `trivia`
- `language`: 语言，见上表，默认为 `tc`


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
    "new-media"
  ],
  "description": "| 冷知識 | 懶人包 | 特集     | 銀髮一族           | 飲食煮意         | 科技達人   | 健康美容          | 規劃人生                    | 消閒娛樂                  | 家品家電        | 親子時光        | 綠色生活     |\n| ------ | ------ | -------- | ------------------ | ---------------- | ---------- | ----------------- | --------------------------- | ------------------------- | --------------- | --------------- | ------------ |\n| trivia | tips   | features | silver-hair-market | food-and-cooking | tech-savvy | health-and-beauty | life-and-financial-planning | leisure-and-entertainment | home-appliances | family-and-kids | green-living |",
  "example": "/consumer/shopping-guide",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "shopping-guide.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "消費全攻略",
  "parameters": {
    "category": "分类，见下表，默认为 `trivia`",
    "language": "语言，见上表，默认为 `tc`"
  },
  "path": "/shopping-guide/:category?/:language?",
  "topFeeds": []
}
```
