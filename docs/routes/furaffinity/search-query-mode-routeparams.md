# Furaffinity - Search

## Coverage
`index-only`

## Route
- Namespace: `furaffinity`
- Namespace Name: `Furaffinity`
- Route Path: `/search/:query/:mode?/:routeParams?`
- Route Name: `Search`
- Example: `/furaffinity/search/protogen/nsfw`
- URL: `furaffinity.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TigerCubDen, SkyNetX007`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/furaffinity/search.ts')`

## Description
Additional search parameters
| Parameter       | Description          | Default   | Options                                                        |
|-----------------|----------------------|-----------|----------------------------------------------------------------|
| order_by        | Sort by              | relevancy | relevancy, date, popularity                                    |
| order_direction | Sort order           | desc      | desc, asc                                                      |
| range           | Date range           | all       | all, 1day, 3days, 7days, 30days, 90days, 1year, 3years, 5years |
| pattern         | Query match pattern  | extended  | all, any, extended                                             |
| type            | Category of artworks | all       | art, flash, photo, music, story, poetry                        |

## Parameters
- `query`: Query value
- `mode`: R18 content toggle, default value is sfw, options are sfw, nsfw
- `routeParams`: Additional search parameters


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `furaffinity.net`
- `target`: `/search`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "Additional search parameters\n| Parameter       | Description          | Default   | Options                                                        |\n|-----------------|----------------------|-----------|----------------------------------------------------------------|\n| order_by        | Sort by              | relevancy | relevancy, date, popularity                                    |\n| order_direction | Sort order           | desc      | desc, asc                                                      |\n| range           | Date range           | all       | all, 1day, 3days, 7days, 30days, 90days, 1year, 3years, 5years |\n| pattern         | Query match pattern  | extended  | all, any, extended                                             |\n| type            | Category of artworks | all       | art, flash, photo, music, story, poetry                        |\n",
  "example": "/furaffinity/search/protogen/nsfw",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "TigerCubDen",
    "SkyNetX007"
  ],
  "module": "() => import('@/routes/furaffinity/search.ts')",
  "name": "Search",
  "parameters": {
    "mode": "R18 content toggle, default value is sfw, options are sfw, nsfw",
    "query": "Query value",
    "routeParams": "Additional search parameters"
  },
  "path": "/search/:query/:mode?/:routeParams?",
  "radar": [
    {
      "source": [
        "furaffinity.net"
      ],
      "target": "/search"
    }
  ],
  "url": "furaffinity.net"
}
```
