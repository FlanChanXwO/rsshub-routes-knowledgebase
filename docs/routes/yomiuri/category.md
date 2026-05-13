# Yomiuri Shimbun 読売新聞 - News

## Coverage
`index-only`

## Route
- Namespace: `yomiuri`
- Namespace Name: `Yomiuri Shimbun 読売新聞`
- Route Path: `/:category?`
- Route Name: `News`
- Example: `/yomiuri/news`
- URL: `www.yomiuri.co.jp`
- Language: `ja`
- Categories: `traditional-media`
- Maintainers: `Arracc`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/yomiuri/news.ts')`

## Description
Free articles only.

| Category       | Parameter |
| -------------- | --------- |
| 新着・速報     | news      |
| 社会           | national  |
| 政治           | politics  |
| 経済           | economy   |
| スポーツ       | sports    |
| 国際           | world     |
| 地域           | local     |
| 科学・ＩＴ     | science   |
| エンタメ・文化 | culture   |
| ライフ         | life      |
| 医療・健康     | medical   |
| 教育・就活     | kyoiku    |
| 選挙・世論調査 | election  |
| 囲碁・将棋     | igoshougi |
| 社説           | editorial |
| 皇室           | koushitsu |

## Parameters
- `category`: Category, `news` by default


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
  - `www.yomiuri.co.jp/:category?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Free articles only.\n\n| Category       | Parameter |\n| -------------- | --------- |\n| 新着・速報     | news      |\n| 社会           | national  |\n| 政治           | politics  |\n| 経済           | economy   |\n| スポーツ       | sports    |\n| 国際           | world     |\n| 地域           | local     |\n| 科学・ＩＴ     | science   |\n| エンタメ・文化 | culture   |\n| ライフ         | life      |\n| 医療・健康     | medical   |\n| 教育・就活     | kyoiku    |\n| 選挙・世論調査 | election  |\n| 囲碁・将棋     | igoshougi |\n| 社説           | editorial |\n| 皇室           | koushitsu |",
  "example": "/yomiuri/news",
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
    "Arracc"
  ],
  "module": "() => import('@/routes/yomiuri/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Category, `news` by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.yomiuri.co.jp/:category?"
      ]
    }
  ]
}
```
