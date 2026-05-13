# Shopify - App reviews

## Coverage
`index-only`

## Route
- Namespace: `shopify`
- Namespace Name: `Shopify`
- Route Path: `/apps/:handle/reviews/:page?`
- Route Name: `App reviews`
- Example: `/shopify/apps/flow/reviews`
- URL: `shopify.com`
- Language: `en`
- Categories: `None`
- Maintainers: `PrintNow`
- Source Location: `apps/[handle].reviews.ts`
- Source Module: `() => import('@/routes/shopify/apps/[handle].reviews.ts')`

## Description
_None_

## Parameters
- `handle`: 例如一个 App 的链接 https://apps.shopify.com/flow，其中 flow 就是指的是 handle


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `apps.shopify.com/:handle`

## Raw JSON
```json
{
  "example": "/shopify/apps/flow/reviews",
  "location": "apps/[handle].reviews.ts",
  "maintainers": [
    "PrintNow"
  ],
  "module": "() => import('@/routes/shopify/apps/[handle].reviews.ts')",
  "name": "App reviews",
  "parameters": {
    "handle": "例如一个 App 的链接 https://apps.shopify.com/flow，其中 flow 就是指的是 handle"
  },
  "path": "/apps/:handle/reviews/:page?",
  "radar": [
    {
      "source": [
        "apps.shopify.com/:handle"
      ]
    }
  ]
}
```
