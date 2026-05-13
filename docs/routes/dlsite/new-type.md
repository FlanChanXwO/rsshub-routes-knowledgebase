# DLsite - Current Release

## Coverage
`index-only`

## Route
- Namespace: `dlsite`
- Namespace Name: `DLsite`
- Route Path: `/new/:type`
- Route Name: `Current Release`
- Example: `/dlsite/new/home`
- URL: `dlsite.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `cssxsh`
- Source Location: `new.ts`
- Source Module: `() => import('@/routes/dlsite/new.ts')`

## Description
| Doujin | Comics | PC Games | Doujin (R18) | Adult Comics | H Games | Otome | BL |
| ------ | ------ | -------- | ------------ | ------------ | ------- | ----- | -- |
| home   | comic  | soft     | maniax       | books        | pro     | girls | bl |

## Parameters
- `type`: {"description": "类型", "options": [{"label": "「DLsite 同人」", "value": "home"}, {"label": "「DLsite コミック」", "value": "comic"}, {"label": "「DLsite PCソフト」", "value": "soft"}, {"label": "「DLsite 同人 - R18」", "value": "maniax"}, {"label": "「DLsite 成年コミック - R18」", "value": "books"}, {"label": "「DLsite 美少女ゲーム」", "value": "pro"}, {"label": "「DLsite 乙女」", "value": "girls"}, {"label": "「DLsite BL」", "value": "bl"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| Doujin | Comics | PC Games | Doujin (R18) | Adult Comics | H Games | Otome | BL |\n| ------ | ------ | -------- | ------------ | ------------ | ------- | ----- | -- |\n| home   | comic  | soft     | maniax       | books        | pro     | girls | bl |",
  "example": "/dlsite/new/home",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "new.ts",
  "maintainers": [
    "cssxsh"
  ],
  "module": "() => import('@/routes/dlsite/new.ts')",
  "name": "Current Release",
  "parameters": {
    "type": {
      "description": "类型",
      "options": [
        {
          "label": "「DLsite 同人」",
          "value": "home"
        },
        {
          "label": "「DLsite コミック」",
          "value": "comic"
        },
        {
          "label": "「DLsite PCソフト」",
          "value": "soft"
        },
        {
          "label": "「DLsite 同人 - R18」",
          "value": "maniax"
        },
        {
          "label": "「DLsite 成年コミック - R18」",
          "value": "books"
        },
        {
          "label": "「DLsite 美少女ゲーム」",
          "value": "pro"
        },
        {
          "label": "「DLsite 乙女」",
          "value": "girls"
        },
        {
          "label": "「DLsite BL」",
          "value": "bl"
        }
      ]
    }
  },
  "path": "/new/:type",
  "view": 0
}
```
