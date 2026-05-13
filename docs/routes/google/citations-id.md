# Google - Scholar Author Citations

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/citations/:id`
- Route Name: `Scholar Author Citations`
- Example: `/google/citations/mlmE4JMAAAAJ`
- URL: `www.google.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `KellyHwong, const7`
- Source Location: `citations.ts`
- Source Module: `() => import('@/routes/google/citations.ts')`

## Description
The parameter id in the route is the id in the URL of the user's Google Scholar reference page, for example `https://scholar.google.com/citations?user=mlmE4JMAAAAJ` to `mlmE4JMAAAAJ`.

  Query parameters are also supported here, for example `https://scholar.google.com/citations?user=mlmE4JMAAAAJ&sortby=pubdate` to `mlmE4JMAAAAJ&sortby=pubdate`. Please make sure that the user id (`mlmE4JMAAAAJ` in this case) should be the first parameter in the query string.

## Parameters
- `id`: N


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "The parameter id in the route is the id in the URL of the user's Google Scholar reference page, for example `https://scholar.google.com/citations?user=mlmE4JMAAAAJ` to `mlmE4JMAAAAJ`.\n\n  Query parameters are also supported here, for example `https://scholar.google.com/citations?user=mlmE4JMAAAAJ&sortby=pubdate` to `mlmE4JMAAAAJ&sortby=pubdate`. Please make sure that the user id (`mlmE4JMAAAAJ` in this case) should be the first parameter in the query string.",
  "example": "/google/citations/mlmE4JMAAAAJ",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "citations.ts",
  "maintainers": [
    "KellyHwong",
    "const7"
  ],
  "module": "() => import('@/routes/google/citations.ts')",
  "name": "Scholar Author Citations",
  "parameters": {
    "id": "N"
  },
  "path": "/citations/:id"
}
```
