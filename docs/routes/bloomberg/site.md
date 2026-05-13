# Bloomberg - Bloomberg Site

## Coverage
`index-only`

## Route
- Namespace: `bloomberg`
- Namespace Name: `Bloomberg`
- Route Path: `/:site?`
- Route Name: `Bloomberg Site`
- Example: `/bloomberg/bbiz`
- URL: `www.bloomberg.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `bigfei`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/bloomberg/index.ts')`

## Description
| Site ID      | Title        |
| ------------ | ------------ |
| /            | News         |
| bpol         | Politics     |
| bbiz         | Business     |
| markets      | Markets      |
| technology   | Technology   |
| green        | Green        |
| wealth       | Wealth       |
| pursuits     | Pursuits     |
| bview        | Opinion      |
| equality     | Equality     |
| businessweek | Businessweek |
| citylab      | CityLab      |

## Parameters
- `site`: {"description": "Site ID, can be found below", "options": [{"label": "News", "value": "/"}, {"label": "Politics", "value": "bpol"}, {"label": "Business", "value": "bbiz"}, {"label": "Markets", "value": "markets"}, {"label": "Technology", "value": "technology"}, {"label": "Green", "value": "green"}, {"label": "Wealth", "value": "wealth"}, {"label": "Pursuits", "value": "pursuits"}, {"label": "Opinion", "value": "bview"}, {"label": "Equality", "value": "equality"}, {"label": "Businessweek", "value": "businessweek"}, {"label": "CityLab", "value": "citylab"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "\n| Site ID      | Title        |\n| ------------ | ------------ |\n| /            | News         |\n| bpol         | Politics     |\n| bbiz         | Business     |\n| markets      | Markets      |\n| technology   | Technology   |\n| green        | Green        |\n| wealth       | Wealth       |\n| pursuits     | Pursuits     |\n| bview        | Opinion      |\n| equality     | Equality     |\n| businessweek | Businessweek |\n| citylab      | CityLab      |\n  ",
  "example": "/bloomberg/bbiz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "bigfei"
  ],
  "module": "() => import('@/routes/bloomberg/index.ts')",
  "name": "Bloomberg Site",
  "parameters": {
    "site": {
      "description": "Site ID, can be found below",
      "options": [
        {
          "label": "News",
          "value": "/"
        },
        {
          "label": "Politics",
          "value": "bpol"
        },
        {
          "label": "Business",
          "value": "bbiz"
        },
        {
          "label": "Markets",
          "value": "markets"
        },
        {
          "label": "Technology",
          "value": "technology"
        },
        {
          "label": "Green",
          "value": "green"
        },
        {
          "label": "Wealth",
          "value": "wealth"
        },
        {
          "label": "Pursuits",
          "value": "pursuits"
        },
        {
          "label": "Opinion",
          "value": "bview"
        },
        {
          "label": "Equality",
          "value": "equality"
        },
        {
          "label": "Businessweek",
          "value": "businessweek"
        },
        {
          "label": "CityLab",
          "value": "citylab"
        }
      ]
    }
  },
  "path": "/:site?",
  "view": 0
}
```
