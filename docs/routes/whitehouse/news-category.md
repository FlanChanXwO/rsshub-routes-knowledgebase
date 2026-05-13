# The White House - News

## Coverage
`index-only`

## Route
- Namespace: `whitehouse`
- Namespace Name: `The White House`
- Route Path: `/news/:category?`
- Route Name: `News`
- Example: `/whitehouse/news`
- URL: `whitehouse.gov`
- Language: `en`
- Categories: `government`
- Maintainers: `nczitzk, hkamran80`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/whitehouse/news.ts')`

## Description
| All | Articles | Briefings and Statements | Presidential Actions | Remarks |
| --- | -------- | ------------------------ | -------------------- | ------- |
|     | articles | briefings-statements     | presidential-actions | remarks |

## Parameters
- `category`: Category, see below, all by default


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
  - `whitehouse.gov/:category`
  - `whitehouse.gov/`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| All | Articles | Briefings and Statements | Presidential Actions | Remarks |\n| --- | -------- | ------------------------ | -------------------- | ------- |\n|     | articles | briefings-statements     | presidential-actions | remarks |",
  "example": "/whitehouse/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "nczitzk",
    "hkamran80"
  ],
  "module": "() => import('@/routes/whitehouse/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Category, see below, all by default"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "whitehouse.gov/:category",
        "whitehouse.gov/"
      ],
      "target": "/news/:category"
    }
  ]
}
```
