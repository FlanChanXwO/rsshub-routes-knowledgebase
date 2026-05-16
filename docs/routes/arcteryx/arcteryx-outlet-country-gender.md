# Arcteryx - Outlet

## Coverage
`index-only`

## Route
- Namespace: `arcteryx`
- Namespace Name: `Arcteryx`
- Route Path: `/arcteryx/outlet/:country/:gender`
- Route Name: `Outlet`
- Example: `/arcteryx/outlet/us/mens`
- URL: `arcteryx.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `EthanWng97`
- Source Location: `outlet.ts`
- Source Module: `_None_`

## Description
Country

| United States | Canada | United Kingdom |
| ------------- | ------ | -------------- |
| us            | ca     | gb             |

gender

| male | female |
| ---- | ------ |
| mens | womens |

::: tip
Parameter `country` can be found within the url of `Arcteryx` website.
:::

## Parameters
- `country`: country
- `gender`: gender


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `outlet.arcteryx.com/:country/en/c/:gender`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Country\n\n| United States | Canada | United Kingdom |\n| ------------- | ------ | -------------- |\n| us            | ca     | gb             |\n\ngender\n\n| male | female |\n| ---- | ------ |\n| mens | womens |\n\n::: tip\nParameter `country` can be found within the url of `Arcteryx` website.\n:::",
  "example": "/arcteryx/outlet/us/mens",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "outlet.ts",
  "maintainers": [
    "EthanWng97"
  ],
  "name": "Outlet",
  "parameters": {
    "country": "country",
    "gender": "gender"
  },
  "path": "/outlet/:country/:gender",
  "radar": [
    {
      "source": [
        "outlet.arcteryx.com/:country/en/c/:gender"
      ]
    }
  ],
  "topFeeds": []
}
```
