# Microsoft - Product tags in mcr.microsoft.com

## Coverage
`index-only`

## Route
- Namespace: `microsoft`
- Namespace Name: `Microsoft`
- Route Path: `/microsoft/mcr/product/*`
- Route Name: `Product tags in mcr.microsoft.com`
- Example: `/microsoft/mcr/product/dotnet/framework/runtime`
- URL: `microsoft.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `margani`
- Source Location: `mcr.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `product`: repository path in mcr.microsoft.com


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
  - `https://mcr.microsoft.com/en-us/product/:product/tags`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/microsoft/mcr/product/dotnet/framework/runtime",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "mcr.ts",
  "maintainers": [
    "margani"
  ],
  "name": "Product tags in mcr.microsoft.com",
  "parameters": {
    "product": "repository path in mcr.microsoft.com"
  },
  "path": "/mcr/product/*",
  "radar": [
    {
      "source": [
        "https://mcr.microsoft.com/en-us/product/:product/tags"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
