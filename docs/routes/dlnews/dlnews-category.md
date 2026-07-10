# DL NEWS - Latest News

## Coverage
`index-only`

## Route
- Namespace: `dlnews`
- Namespace Name: `DL NEWS`
- Route Path: `/dlnews/:category?`
- Route Name: `Latest News`
- Example: `/dlnews/people-culture`
- URL: `dlnews.com/articles`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Rjnishant530`
- Source Location: `category.tsx`
- Source Module: `_None_`

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
  "categories": [
    "other"
  ],
  "example": "/dlnews/people-culture",
  "heat": 0,
  "location": "category.tsx",
  "maintainers": [
    "Rjnishant530"
  ],
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
  "topFeeds": [],
  "url": "dlnews.com/articles"
}
```
