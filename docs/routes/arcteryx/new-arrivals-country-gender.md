# Arcteryx - New Arrivals

## Coverage
`index-only`

## Route
- Namespace: `arcteryx`
- Namespace Name: `Arcteryx`
- Route Path: `/new-arrivals/:country/:gender`
- Route Name: `New Arrivals`
- Example: `/arcteryx/new-arrivals/us/mens`
- URL: `arcteryx.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `EthanWng97`
- Source Location: `new-arrivals.ts`
- Source Module: `() => import('@/routes/arcteryx/new-arrivals.ts')`

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
  - `arcteryx.com/:country/en/c/:gender/new-arrivals`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "Country\n\n| United States | Canada | United Kingdom |\n| ------------- | ------ | -------------- |\n| us            | ca     | gb             |\n\n  gender\n\n| male | female |\n| ---- | ------ |\n| mens | womens |\n\n::: tip\n  Parameter `country` can be found within the url of `Arcteryx` website.\n:::",
  "example": "/arcteryx/new-arrivals/us/mens",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "new-arrivals.ts",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/arcteryx/new-arrivals.ts')",
  "name": "New Arrivals",
  "parameters": {
    "country": "country",
    "gender": "gender"
  },
  "path": "/new-arrivals/:country/:gender",
  "radar": [
    {
      "source": [
        "arcteryx.com/:country/en/c/:gender/new-arrivals"
      ]
    }
  ]
}
```
