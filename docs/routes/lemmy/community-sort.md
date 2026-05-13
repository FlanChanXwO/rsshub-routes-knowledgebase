# Lemmy - Community

## Coverage
`index-only`

## Route
- Namespace: `lemmy`
- Namespace Name: `Lemmy`
- Route Path: `/:community/:sort?`
- Route Name: `Community`
- Example: `/lemmy/technology@lemmy.world/Hot`
- URL: `join-lemmy.org`
- Language: `en`
- Categories: `social-media`
- Maintainers: `wb14123, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/lemmy/index.ts')`

## Description
_None_

## Parameters
- `community`: Lemmmy community, for example technology@lemmy.world
- `sort`: {"default": "Active", "description": "Sort by", "options": [{"label": "Active", "value": "Active"}, {"label": "Hot", "value": "Hot"}, {"label": "New", "value": "New"}, {"label": "Old", "value": "Old"}, {"label": "TopDay", "value": "TopDay"}, {"label": "TopWeek", "value": "TopWeek"}, {"label": "TopMonth", "value": "TopMonth"}, {"label": "TopYear", "value": "TopYear"}, {"label": "TopAll", "value": "TopAll"}, {"label": "MostComments", "value": "MostComments"}, {"label": "NewComments", "value": "NewComments"}, {"label": "TopHour", "value": "TopHour"}, {"label": "TopSixHour", "value": "TopSixHour"}, {"label": "TopTwelveHour", "value": "TopTwelveHour"}, {"label": "TopThreeMonths", "value": "TopThreeMonths"}, {"label": "TopSixMonths", "value": "TopSixMonths"}, {"label": "TopNineMonths", "value": "TopNineMonths"}, {"label": "Controversial", "value": "Controversial"}, {"label": "Scaled", "value": "Scaled"}]}


## Features
- `requireConfig`: [{"description": "", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"}]
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
    "social-media"
  ],
  "example": "/lemmy/technology@lemmy.world/Hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "wb14123",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/lemmy/index.ts')",
  "name": "Community",
  "parameters": {
    "community": "Lemmmy community, for example technology@lemmy.world",
    "sort": {
      "default": "Active",
      "description": "Sort by",
      "options": [
        {
          "label": "Active",
          "value": "Active"
        },
        {
          "label": "Hot",
          "value": "Hot"
        },
        {
          "label": "New",
          "value": "New"
        },
        {
          "label": "Old",
          "value": "Old"
        },
        {
          "label": "TopDay",
          "value": "TopDay"
        },
        {
          "label": "TopWeek",
          "value": "TopWeek"
        },
        {
          "label": "TopMonth",
          "value": "TopMonth"
        },
        {
          "label": "TopYear",
          "value": "TopYear"
        },
        {
          "label": "TopAll",
          "value": "TopAll"
        },
        {
          "label": "MostComments",
          "value": "MostComments"
        },
        {
          "label": "NewComments",
          "value": "NewComments"
        },
        {
          "label": "TopHour",
          "value": "TopHour"
        },
        {
          "label": "TopSixHour",
          "value": "TopSixHour"
        },
        {
          "label": "TopTwelveHour",
          "value": "TopTwelveHour"
        },
        {
          "label": "TopThreeMonths",
          "value": "TopThreeMonths"
        },
        {
          "label": "TopSixMonths",
          "value": "TopSixMonths"
        },
        {
          "label": "TopNineMonths",
          "value": "TopNineMonths"
        },
        {
          "label": "Controversial",
          "value": "Controversial"
        },
        {
          "label": "Scaled",
          "value": "Scaled"
        }
      ]
    }
  },
  "path": "/:community/:sort?"
}
```
