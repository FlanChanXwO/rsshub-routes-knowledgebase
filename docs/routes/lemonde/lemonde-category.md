# Le Monde - News

## Coverage
`index-only`

## Route
- Namespace: `lemonde`
- Namespace Name: `Le Monde`
- Route Path: `/lemonde/:category?`
- Route Name: `News`
- Example: `/lemonde`
- URL: `lemonde.fr`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `mlkgrnt`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Category      | Description            |
| ------------- | ---------------------- |
| (empty)       | Homepage / Top stories |
| international | International          |
| politique     | Politics               |
| economie      | Economy                |
| societe       | Society                |
| culture       | Culture                |
| sport         | Sports                 |
| planete       | Environment            |
| pixels        | Tech / Digital         |
| sciences      | Sciences               |
| idees         | Opinions               |
| sante         | Health                 |
| em            | M le mag               |
| en-continu    | Live / Breaking        |
| decodeurs     | Fact-checking          |

## Parameters
- `category`: {"default": "", "description": "Category slug, see table below. Defaults to homepage."}


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
  - `lemonde.fr/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Category      | Description            |\n| ------------- | ---------------------- |\n| (empty)       | Homepage / Top stories |\n| international | International          |\n| politique     | Politics               |\n| economie      | Economy                |\n| societe       | Society                |\n| culture       | Culture                |\n| sport         | Sports                 |\n| planete       | Environment            |\n| pixels        | Tech / Digital         |\n| sciences      | Sciences               |\n| idees         | Opinions               |\n| sante         | Health                 |\n| em            | M le mag               |\n| en-continu    | Live / Breaking        |\n| decodeurs     | Fact-checking          |",
  "example": "/lemonde",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "mlkgrnt"
  ],
  "name": "News",
  "parameters": {
    "category": {
      "default": "",
      "description": "Category slug, see table below. Defaults to homepage."
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "lemonde.fr/:category"
      ],
      "target": "/:category"
    }
  ],
  "topFeeds": [],
  "view": 0
}
```
