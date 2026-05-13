# Arcteryx - Outlet

## Coverage
`index-only`

## Route
- Namespace: `arcteryx`
- Namespace Name: `Arcteryx`
- Route Path: `/outlet/:country/:gender`
- Route Name: `Outlet`
- Example: `/arcteryx/outlet/us/mens`
- URL: `arcteryx.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `EthanWng97`
- Source Location: `outlet.ts`
- Source Module: `() => import('@/routes/arcteryx/outlet.ts')`

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
  "description": "Country\n\n| United States | Canada | United Kingdom |\n| ------------- | ------ | -------------- |\n| us            | ca     | gb             |\n\n  gender\n\n| male | female |\n| ---- | ------ |\n| mens | womens |\n\n::: tip\n  Parameter `country` can be found within the url of `Arcteryx` website.\n:::",
  "example": "/arcteryx/outlet/us/mens",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "outlet.ts",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/arcteryx/outlet.ts')",
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
  ]
}
```
