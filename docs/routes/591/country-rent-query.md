# 591 Rental house - Rental house

## Coverage
`index-only`

## Route
- Namespace: `591`
- Namespace Name: `591 Rental house`
- Route Path: `/:country/rent/:query?`
- Route Name: `Rental house`
- Example: `/591/tw/rent/order=posttime&orderType=desc`
- URL: `rent.591.com.tw`
- Language: `zh-TW`
- Categories: `other`
- Maintainers: `Yukaii`
- Source Location: `list.tsx`
- Source Module: `() => import('@/routes/591/list.tsx')`

## Description
::: tip
  Copy the URL of the 591 filter housing page and remove the front part `https://rent.591.com.tw/?`, you will get the query parameters.
:::

## Parameters
- `country`: Country code. Only tw is supported now
- `query`: Query Parameters


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
    "other"
  ],
  "description": "::: tip\n  Copy the URL of the 591 filter housing page and remove the front part `https://rent.591.com.tw/?`, you will get the query parameters.\n:::",
  "example": "/591/tw/rent/order=posttime&orderType=desc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "list.tsx",
  "maintainers": [
    "Yukaii"
  ],
  "module": "() => import('@/routes/591/list.tsx')",
  "name": "Rental house",
  "parameters": {
    "country": "Country code. Only tw is supported now",
    "query": "Query Parameters"
  },
  "path": "/:country/rent/:query?"
}
```
