# GitHub - Search Result

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/search/:query/:sort?/:order?`
- Route Name: `Search Result`
- Example: `/github/search/RSSHub/bestmatch/desc`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `LogicJake`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/github/search.ts')`

## Description
| Sort options     | sort      |
| ---------------- | --------- |
| Best match       | bestmatch |
| Most stars       | stars     |
| Most forks       | forks     |
| Recently updated | updated   |

## Parameters
- `query`: search keyword
- `sort`: Sort options (default to bestmatch)
- `order`: Sort order, desc and asc (desc descending by default)


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
    "programming"
  ],
  "description": "| Sort options     | sort      |\n| ---------------- | --------- |\n| Best match       | bestmatch |\n| Most stars       | stars     |\n| Most forks       | forks     |\n| Recently updated | updated   |",
  "example": "/github/search/RSSHub/bestmatch/desc",
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
    "LogicJake"
  ],
  "module": "() => import('@/routes/github/search.ts')",
  "name": "Search Result",
  "parameters": {
    "order": "Sort order, desc and asc (desc descending by default)",
    "query": "search keyword",
    "sort": "Sort options (default to bestmatch)"
  },
  "path": "/search/:query/:sort?/:order?"
}
```
