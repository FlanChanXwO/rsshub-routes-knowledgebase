# DL NEWS - Latest News

## Coverage
`index-only`

## Route
- Namespace: `dlnews`
- Namespace Name: `DL NEWS`
- Route Path: `/:category?`
- Route Name: `Latest News`
- Example: `/dlnews/people-culture`
- URL: `dlnews.com/articles`
- Language: `en`
- Categories: `None`
- Maintainers: `Rjnishant530`
- Source Location: `category.tsx`
- Source Module: `() => import('@/routes/dlnews/category.tsx')`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `dlnews.com/articles/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "example": "/dlnews/people-culture",
  "location": "category.tsx",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/dlnews/category.tsx')",
  "name": "Latest News",
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "dlnews.com/articles/:category"
      ],
      "target": "/:category"
    }
  ],
  "url": "dlnews.com/articles"
}
```
