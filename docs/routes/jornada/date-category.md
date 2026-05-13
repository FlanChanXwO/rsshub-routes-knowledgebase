# La Jornada - News

## Coverage
`index-only`

## Route
- Namespace: `jornada`
- Namespace Name: `La Jornada`
- Route Path: `/:date?/:category?`
- Route Name: `News`
- Example: `/jornada/2022-10-12/capital`
- URL: `jornada.com.mx`
- Language: `es`
- Categories: `traditional-media`
- Maintainers: `Thealf154`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/jornada/index.ts')`

## Description
Provides a way to get an specific rss feed by date and category over the official one.

| Category             | `:category` |
| -------------------- | ----------- |
| Capital              | capital     |
| Cartones             | cartones    |
| Ciencia y Tecnología | ciencia     |
| Cultura              | cultura     |
| Deportes             | deportes    |
| Economía             | economia    |
| Estados              | estados     |
| Mundo                | mundo       |
| Opinión              | opinion     |
| Política             | politica    |
| Sociedad             | sociedad    |

## Parameters
- `date`: Date string, must be in format of `YYYY-MM-DD`. You can get today's news using `today`
- `category`: Category, refer to the table below


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
    "traditional-media"
  ],
  "description": "Provides a way to get an specific rss feed by date and category over the official one.\n\n| Category             | `:category` |\n| -------------------- | ----------- |\n| Capital              | capital     |\n| Cartones             | cartones    |\n| Ciencia y Tecnología | ciencia     |\n| Cultura              | cultura     |\n| Deportes             | deportes    |\n| Economía             | economia    |\n| Estados              | estados     |\n| Mundo                | mundo       |\n| Opinión              | opinion     |\n| Política             | politica    |\n| Sociedad             | sociedad    |",
  "example": "/jornada/2022-10-12/capital",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Thealf154"
  ],
  "module": "() => import('@/routes/jornada/index.ts')",
  "name": "News",
  "parameters": {
    "category": "Category, refer to the table below",
    "date": "Date string, must be in format of `YYYY-MM-DD`. You can get today's news using `today`"
  },
  "path": "/:date?/:category?"
}
```
