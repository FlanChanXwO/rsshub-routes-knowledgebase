# アイドルマスター THE IDOLM@STER - ニュース News

## Coverage
`index-only`

## Route
- Namespace: `idolmaster`
- Namespace Name: `アイドルマスター THE IDOLM@STER`
- Route Path: `/news/:routeParams?`
- Route Name: `ニュース News`
- Example: `/idolmaster/news/brand=MILLIONLIVE&brand=SHINYCOLORS&category=GAME&category=ANIME`
- URL: `idolmaster-official.jp/news`
- Language: `ja`
- Categories: `anime`
- Maintainers: `keocheung`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/idolmaster/news.ts')`

## Description
**Brand**
| THE IDOLM@STER | シンデレラガールズ | ミリオンライブ！ | SideM | シャイニーカラーズ | 学園アイドルマスター | その他 |
| -------------- | --------------- | ------------- | ----- | --------------- | ----------------- | ----- |
| IDOLMASTER | CINDERELLAGIRLS | MILLIONLIVE | SIDEM | SHINYCOLORS | GAKUEN | OTHER |

**Category**
| ゲーム | ライブ・イベント | アニメ | 配信番組 | ラジオ | グッズ | コラボ・キャンペーン | ミュージック | ブック・コミック | メディア | その他 |
| ----- | ------------- | ----- | ------- | ----- | ----- | ----------------- | --------- | -------------- | ------ | ----- |
| GAME | LIVE-EVENT | ANIME | LIVESTREAM | RADIO | GOODS | COLLABO-CAMP | CD | BOOK | MEDIA | OTHER |

## Parameters
- `routeParams`: The `brand` and `category` params in the path. The available values are as follows.


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
  - `idolmaster-official.jp/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "**Brand**\n| THE IDOLM@STER | シンデレラガールズ | ミリオンライブ！ | SideM | シャイニーカラーズ | 学園アイドルマスター | その他 |\n| -------------- | --------------- | ------------- | ----- | --------------- | ----------------- | ----- |\n| IDOLMASTER | CINDERELLAGIRLS | MILLIONLIVE | SIDEM | SHINYCOLORS | GAKUEN | OTHER |\n\n**Category**\n| ゲーム | ライブ・イベント | アニメ | 配信番組 | ラジオ | グッズ | コラボ・キャンペーン | ミュージック | ブック・コミック | メディア | その他 |\n| ----- | ------------- | ----- | ------- | ----- | ----- | ----------------- | --------- | -------------- | ------ | ----- |\n| GAME | LIVE-EVENT | ANIME | LIVESTREAM | RADIO | GOODS | COLLABO-CAMP | CD | BOOK | MEDIA | OTHER |\n    ",
  "example": "/idolmaster/news/brand=MILLIONLIVE&brand=SHINYCOLORS&category=GAME&category=ANIME",
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
    "keocheung"
  ],
  "module": "() => import('@/routes/idolmaster/news.ts')",
  "name": "ニュース News",
  "parameters": {
    "routeParams": "The `brand` and `category` params in the path. The available values are as follows."
  },
  "path": "/news/:routeParams?",
  "radar": [
    {
      "source": [
        "idolmaster-official.jp/news"
      ],
      "target": "/news"
    }
  ],
  "url": "idolmaster-official.jp/news"
}
```
