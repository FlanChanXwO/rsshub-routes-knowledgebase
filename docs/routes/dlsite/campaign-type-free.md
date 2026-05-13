# DLsite - Discounted Works

## Coverage
`index-only`

## Route
- Namespace: `dlsite`
- Namespace Name: `DLsite`
- Route Path: `/campaign/:type/:free?`
- Route Name: `Discounted Works`
- Example: `/dlsite/campaign/home`
- URL: `dlsite.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `cssxsh`
- Source Location: `campaign.ts`
- Source Module: `() => import('@/routes/dlsite/campaign.ts')`

## Description
_None_

## Parameters
- `type`: {"description": "类型", "options": [{"label": "「DLsite 同人」", "value": "home"}, {"label": "「DLsite コミック」", "value": "comic"}, {"label": "「DLsite PCソフト」", "value": "soft"}, {"label": "「DLsite 同人 - R18」", "value": "maniax"}, {"label": "「DLsite 成年コミック - R18」", "value": "books"}, {"label": "「DLsite 美少女ゲーム」", "value": "pro"}, {"label": "「DLsite 乙女」", "value": "girls"}, {"label": "「DLsite BL」", "value": "bl"}]}
- `free`: {"description": "免费", "options": [{"label": "是", "value": "1"}]}


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
  "example": "/dlsite/campaign/home",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "campaign.ts",
  "maintainers": [
    "cssxsh"
  ],
  "module": "() => import('@/routes/dlsite/campaign.ts')",
  "name": "Discounted Works",
  "parameters": {
    "free": {
      "description": "免费",
      "options": [
        {
          "label": "是",
          "value": "1"
        }
      ]
    },
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
  "path": "/campaign/:type/:free?"
}
```
