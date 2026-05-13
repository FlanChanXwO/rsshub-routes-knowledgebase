# Free Computer Books - Book List

## Coverage
`index-only`

## Route
- Namespace: `freecomputerbooks`
- Namespace Name: `Free Computer Books`
- Route Path: `/:category?`
- Route Name: `Book List`
- Example: `/freecomputerbooks/compscAlgorithmBooks`
- URL: `freecomputerbooks.com`
- Language: `en`
- Categories: `reading`
- Maintainers: `cubroe`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/freecomputerbooks/index.tsx')`

## Description
_None_

## Parameters
- `category`: A category id., which should be the HTML file name (but **without** the `.html` suffix) in the URL path of a book list page.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `freecomputerbooks.com/`
  - `freecomputerbooks.com/index.html`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/freecomputerbooks/compscAlgorithmBooks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "cubroe"
  ],
  "module": "() => import('@/routes/freecomputerbooks/index.tsx')",
  "name": "Book List",
  "parameters": {
    "category": "A category id., which should be the HTML file name (but **without** the `.html` suffix) in the URL path of a book list page."
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "freecomputerbooks.com/",
        "freecomputerbooks.com/index.html"
      ],
      "target": ""
    }
  ],
  "url": "freecomputerbooks.com"
}
```
