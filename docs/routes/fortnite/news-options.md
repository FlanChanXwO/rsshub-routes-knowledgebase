# Fortnite - News

## Coverage
`index-only`

## Route
- Namespace: `fortnite`
- Namespace Name: `Fortnite`
- Route Path: `/news/:options?`
- Route Name: `News`
- Example: `/fortnite/news`
- URL: `fortnite.com`
- Language: `en`
- Categories: `game`
- Maintainers: `lyqluis`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/fortnite/news.ts')`

## Description
-   `options.lang`, optional, language, eg. `/fortnite/news/lang=en-US`, common languages are listed below, more languages are available one the [official website](https://www.fortnite.com/news)

| English (default) | Spanish | Japanese | French | Korean | Polish |
| ----------------- | ------- | -------- | ------ | ------ | ------ |
| en-US             | es-ES   | ja       | fr     | ko     | pl     |

## Parameters
- `options`: Params


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "game"
  ],
  "description": "-   `options.lang`, optional, language, eg. `/fortnite/news/lang=en-US`, common languages are listed below, more languages are available one the [official website](https://www.fortnite.com/news)\n\n| English (default) | Spanish | Japanese | French | Korean | Polish |\n| ----------------- | ------- | -------- | ------ | ------ | ------ |\n| en-US             | es-ES   | ja       | fr     | ko     | pl     |",
  "example": "/fortnite/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "lyqluis"
  ],
  "module": "() => import('@/routes/fortnite/news.ts')",
  "name": "News",
  "parameters": {
    "options": "Params"
  },
  "path": "/news/:options?"
}
```
