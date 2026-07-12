# Kleinanzeigen - Search

## Coverage
`index-only`

## Route
- Namespace: `kleinanzeigen`
- Namespace Name: `Kleinanzeigen`
- Route Path: `/kleinanzeigen/search/:routeParams`
- Route Name: `Search`
- Example: `/kleinanzeigen/search/category=PCs&location=Berlin&radius=20`
- URL: `www.kleinanzeigen.de`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `LunyaaDev`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
::: tip
Parameter

| Name            | Description                                                               | Default       |
| --------------- | ------------------------------------------------------------------------- | ------------- |
| query           | Search Query                                                              | undefined     |
| category        | Category (as named on Kleinanzeigen)                                      | undefined     |
| categoryId      | Category ID (advanced)                                                    | undefined     |
| location        | Location (as named on Kleinanzeigen)                                      | undefined     |
| locationId      | Location ID (advanced)                                                    | undefined     |
| radius          | Radius in KM around the Location                                          | 0             |
| sortingField    | Order of the Products (SORTING\_DATE, PRICE\_AMOUNT, PRICE\_AMOUNT\_DESC) | SORTING\_DATE |
| minPrice        | minimal Price                                                             | undefined     |
| maxPrice        | maximal Price                                                             | undefined     |
| shippingCarrier | Shipping Carrier (e.g. DHL, HERMES)                                       | undefined     |

:::

## Parameters
- `routeParams`: Extra parameters, see the table below


## Features
- `requireConfig`: false
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
    "shopping"
  ],
  "description": "::: tip\nParameter\n\n| Name            | Description                                                               | Default       |\n| --------------- | ------------------------------------------------------------------------- | ------------- |\n| query           | Search Query                                                              | undefined     |\n| category        | Category (as named on Kleinanzeigen)                                      | undefined     |\n| categoryId      | Category ID (advanced)                                                    | undefined     |\n| location        | Location (as named on Kleinanzeigen)                                      | undefined     |\n| locationId      | Location ID (advanced)                                                    | undefined     |\n| radius          | Radius in KM around the Location                                          | 0             |\n| sortingField    | Order of the Products (SORTING\\_DATE, PRICE\\_AMOUNT, PRICE\\_AMOUNT\\_DESC) | SORTING\\_DATE |\n| minPrice        | minimal Price                                                             | undefined     |\n| maxPrice        | maximal Price                                                             | undefined     |\n| shippingCarrier | Shipping Carrier (e.g. DHL, HERMES)                                       | undefined     |\n\n:::",
  "example": "/kleinanzeigen/search/category=PCs&location=Berlin&radius=20",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "LunyaaDev"
  ],
  "name": "Search",
  "parameters": {
    "routeParams": "Extra parameters, see the table below"
  },
  "path": "/search/:routeParams",
  "radar": [],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
