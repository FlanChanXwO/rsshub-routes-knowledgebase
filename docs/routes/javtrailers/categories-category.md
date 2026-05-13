# JavTrailers - Categories

## Coverage
`index-only`

## Route
- Namespace: `javtrailers`
- Namespace Name: `JavTrailers`
- Route Path: `/categories/:category`
- Route Name: `Categories`
- Example: `/javtrailers/categories/50001755`
- URL: `javtrailers.com/categories`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `categories.ts`
- Source Module: `() => import('@/routes/javtrailers/categories.ts')`

## Description
_None_

## Parameters
- `category`: Category name, can be found in the URL of the category page


## Features
- `nsfw`: true
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `javtrailers.com/categories/:category`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javtrailers/categories/50001755",
  "features": {
    "nsfw": true,
    "requirePuppeteer": true
  },
  "location": "categories.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/javtrailers/categories.ts')",
  "name": "Categories",
  "parameters": {
    "category": "Category name, can be found in the URL of the category page"
  },
  "path": "/categories/:category",
  "radar": [
    {
      "source": [
        "javtrailers.com/categories/:category"
      ]
    }
  ],
  "url": "javtrailers.com/categories"
}
```
