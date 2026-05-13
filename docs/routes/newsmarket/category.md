# 上下游 News&Market - 分類

## Coverage
`index-only`

## Route
- Namespace: `newsmarket`
- Namespace Name: `上下游 News&Market`
- Route Path: `/:category?`
- Route Name: `分類`
- Example: `/newsmarket`
- URL: `newsmarket.com.tw`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/newsmarket/index.ts')`

## Description
| 時事。政策  | 食安        | 新知      | 愛地方       | 種好田       | 好吃。好玩    |
| ----------- | ----------- | --------- | ------------ | ------------ | ------------- |
| news-policy | food-safety | knowledge | country-life | good-farming | good-food-fun |

| 食農教育       | 人物               | 漁業。畜牧           | 綠生活。國際        | 評論    |
| -------------- | ------------------ | -------------------- | ------------------- | ------- |
| food-education | people-and-history | raising-and-breeding | living-green-travel | opinion |

## Parameters
- `category`: 分类，见下表，默认为首页


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
  - `newsmarket.com.tw/blog/category/:category`
  - `newsmarket.com.tw/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 時事。政策  | 食安        | 新知      | 愛地方       | 種好田       | 好吃。好玩    |\n| ----------- | ----------- | --------- | ------------ | ------------ | ------------- |\n| news-policy | food-safety | knowledge | country-life | good-farming | good-food-fun |\n\n| 食農教育       | 人物               | 漁業。畜牧           | 綠生活。國際        | 評論    |\n| -------------- | ------------------ | -------------------- | ------------------- | ------- |\n| food-education | people-and-history | raising-and-breeding | living-green-travel | opinion |",
  "example": "/newsmarket",
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
  "module": "() => import('@/routes/newsmarket/index.ts')",
  "name": "分類",
  "parameters": {
    "category": "分类，见下表，默认为首页"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "newsmarket.com.tw/blog/category/:category",
        "newsmarket.com.tw/"
      ]
    }
  ]
}
```
