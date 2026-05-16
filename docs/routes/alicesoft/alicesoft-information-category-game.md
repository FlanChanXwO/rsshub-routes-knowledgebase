# ALICESOFT - ニュース

## Coverage
`index-only`

## Route
- Namespace: `alicesoft`
- Namespace Name: `ALICESOFT`
- Route Path: `/alicesoft/information/:category?/:game?`
- Route Name: `ニュース`
- Example: `/alicesoft/information/game/cat377`
- URL: `www.alicesoft.com/information`
- Language: `_None_`
- Categories: `game`
- Maintainers: `keocheung`
- Source Location: `infomation.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: Category in the URL, which can be accessed under カテゴリ一覧 on the website.
- `game`: Game-specific subcategory in the URL, which can be accessed under カテゴリ一覧 on the website. In this case, the category value should be `game`.


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
  - `www.alicesoft.com/information`
  - `www.alicesoft.com/information/:category`
  - `www.alicesoft.com/information/:category/:game`
- `target`: `/information/:category/:game`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/alicesoft/information/game/cat377",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "infomation.ts",
  "maintainers": [
    "keocheung"
  ],
  "name": "ニュース",
  "parameters": {
    "category": "Category in the URL, which can be accessed under カテゴリ一覧 on the website.",
    "game": "Game-specific subcategory in the URL, which can be accessed under カテゴリ一覧 on the website. In this case, the category value should be `game`."
  },
  "path": "/information/:category?/:game?",
  "radar": [
    {
      "source": [
        "www.alicesoft.com/information",
        "www.alicesoft.com/information/:category",
        "www.alicesoft.com/information/:category/:game"
      ],
      "target": "/information/:category/:game"
    }
  ],
  "topFeeds": [
    {
      "description": "ALICESOFT 超昂大戦の記事一覧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74007369916644352",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.alicesoft.com/information/game/cat377",
      "title": "ALICESOFT 超昂大戦の記事一覧",
      "type": "feed",
      "url": "rsshub://alicesoft/information/game/cat377"
    },
    {
      "description": "ALICESOFT 記事一覧 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71404482934582272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.alicesoft.com/information",
      "title": "ALICESOFT 記事一覧",
      "type": "feed",
      "url": "rsshub://alicesoft/information"
    }
  ],
  "url": "www.alicesoft.com/information"
}
```
