# TV Tropes - Featured

## Coverage
`index-only`

## Route
- Namespace: `tvtropes`
- Namespace Name: `TV Tropes`
- Route Path: `/tvtropes/featured/:category?`
- Route Name: `Featured`
- Example: `/tvtropes/featured/today`
- URL: `tvtropes.org`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `featured.tsx`
- Source Module: `_None_`

## Description
| Today's Featured Trope | Newest Trope |
| ---------------------- | ------------ |
| today                  | newest       |

## Parameters
- `category`: Category, see below, Today's Featured Trope by default


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
  "description": "| Today's Featured Trope | Newest Trope |\n| ---------------------- | ------------ |\n| today                  | newest       |",
  "example": "/tvtropes/featured/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "featured.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Featured",
  "parameters": {
    "category": "Category, see below, Today's Featured Trope by default"
  },
  "path": "/featured/:category?",
  "topFeeds": []
}
```
