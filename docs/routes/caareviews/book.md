# caa.reviews - Book Reviews

## Coverage
`index-only`

## Route
- Namespace: `caareviews`
- Namespace Name: `caa.reviews`
- Route Path: `/book`
- Route Name: `Book Reviews`
- Example: `/caareviews/book`
- URL: `caareviews.org/reviews/book`
- Language: `en`
- Categories: `journal`
- Maintainers: `Fatpandac`
- Source Location: `book.ts`
- Source Module: `() => import('@/routes/caareviews/book.ts')`

## Description
_None_

## Parameters
_None_


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
  - `caareviews.org/reviews/book`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/caareviews/book",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "book.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/caareviews/book.ts')",
  "name": "Book Reviews",
  "parameters": {},
  "path": "/book",
  "radar": [
    {
      "source": [
        "caareviews.org/reviews/book"
      ]
    }
  ],
  "url": "caareviews.org/reviews/book"
}
```
