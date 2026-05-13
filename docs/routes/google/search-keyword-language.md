# Google - Search

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/search/:keyword/:language?`
- Route Name: `Search`
- Example: `/google/search/rss/zh-CN,zh`
- URL: `www.google.com`
- Language: `en`
- Categories: `other`
- Maintainers: `CaoMeiYouRen`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/google/search.ts')`

## Description
_None_

## Parameters
- `keyword`: Keyword
- `language`: Accept-Language. Example: `zh-CN,zh;q=0.9,en;q=0.8,ja;q=0.7`


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
  "example": "/google/search/rss/zh-CN,zh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/google/search.ts')",
  "name": "Search",
  "parameters": {
    "keyword": "Keyword",
    "language": "Accept-Language. Example: `zh-CN,zh;q=0.9,en;q=0.8,ja;q=0.7`"
  },
  "path": "/search/:keyword/:language?"
}
```
