# Shopify - App store search

## Coverage
`index-only`

## Route
- Namespace: `shopify`
- Namespace Name: `Shopify`
- Route Path: `/apps/search/:q`
- Route Name: `App store search`
- Example: `/shopify/apps/search/flow`
- URL: `shopify.com`
- Language: `en`
- Categories: `None`
- Maintainers: `PrintNow`
- Source Location: `apps/search.ts`
- Source Module: `() => import('@/routes/shopify/apps/search.ts')`

## Description
_None_

## Parameters
- `q`: 需要搜索的 App


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `apps.shopify.com/search`

## Raw JSON
```json
{
  "example": "/shopify/apps/search/flow",
  "location": "apps/search.ts",
  "maintainers": [
    "PrintNow"
  ],
  "module": "() => import('@/routes/shopify/apps/search.ts')",
  "name": "App store search",
  "parameters": {
    "q": "需要搜索的 App"
  },
  "path": "/apps/search/:q",
  "radar": [
    {
      "source": [
        "apps.shopify.com/search"
      ]
    }
  ]
}
```
