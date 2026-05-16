# Fortnite - News

## Coverage
`index-only`

## Route
- Namespace: `fortnite`
- Namespace Name: `Fortnite`
- Route Path: `/fortnite/news/:options?`
- Route Name: `News`
- Example: `/fortnite/news`
- URL: `fortnite.com`
- Language: `_None_`
- Categories: `game`
- Maintainers: `lyqluis`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
- `options.lang`, optional, language, eg. `/fortnite/news/lang=en-US`, common languages are listed below, more languages are available one the [official website](https://www.fortnite.com/news)

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
  "description": "- `options.lang`, optional, language, eg. `/fortnite/news/lang=en-US`, common languages are listed below, more languages are available one the [official website](https://www.fortnite.com/news)\n\n| English (default) | Spanish | Japanese | French | Korean | Polish |\n| ----------------- | ------- | -------- | ------ | ------ | ------ |\n| en-US             | es-ES   | ja       | fr     | ko     | pl     |",
  "example": "/fortnite/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "news.ts",
  "maintainers": [
    "lyqluis"
  ],
  "name": "News",
  "parameters": {
    "options": "Params"
  },
  "path": "/news/:options?",
  "topFeeds": [
    {
      "description": "Fortnite News - Powered by RSSHub",
      "errorAt": "2025-05-15T04:29:52.956Z",
      "errorMessage": "Fortnite API responded with 403 for https://www.fortnite.com/api/blog/getPosts?category=&postsPerPage=0&offset=0&locale=en-US&rootPageSlug=blog\n",
      "id": "68983907798491136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fortnite.com/news?lang=en-US",
      "title": "Fortnite News",
      "type": "feed",
      "url": "rsshub://fortnite/news"
    }
  ]
}
```
