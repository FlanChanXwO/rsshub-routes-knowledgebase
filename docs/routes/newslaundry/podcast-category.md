# Newslaundry - Podcast

## Coverage
`index-only`

## Route
- Namespace: `newslaundry`
- Namespace Name: `Newslaundry`
- Route Path: `/podcast/:category?`
- Route Name: `Podcast`
- Example: `/newslaundry/podcast`
- URL: `newslaundry.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `Rjnishant530`
- Source Location: `podcast.ts`
- Source Module: `() => import('@/routes/newslaundry/podcast.ts')`

## Description
| Category | URL |
| -------- | --- |
| All Podcasts | [/podcast](https://rsshub.app/newslaundry/podcast) |
| NL Hafta | [/podcast/nl-hafta](https://rsshub.app/newslaundry/podcast/nl-hafta) |
| What's Your Ism? | [/podcast/whats-your-ism](https://rsshub.app/newslaundry/podcast/whats-your-ism) |

## Parameters
- `category`: Podcast category, see below for details


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `newslaundry.com/podcast`
- `target`: `/podcast`
### Rule 2
- `source`:
  - `newslaundry.com/collection/nl-hafta-podcast`
- `target`: `/podcast/nl-hafta`
### Rule 3
- `source`:
  - `newslaundry.com/podcast/whats-your-ism`
- `target`: `/podcast/whats-your-ism`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| Category | URL |\n| -------- | --- |\n| All Podcasts | [/podcast](https://rsshub.app/newslaundry/podcast) |\n| NL Hafta | [/podcast/nl-hafta](https://rsshub.app/newslaundry/podcast/nl-hafta) |\n| What's Your Ism? | [/podcast/whats-your-ism](https://rsshub.app/newslaundry/podcast/whats-your-ism) |",
  "example": "/newslaundry/podcast",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "podcast.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/newslaundry/podcast.ts')",
  "name": "Podcast",
  "parameters": {
    "category": "Podcast category, see below for details"
  },
  "path": "/podcast/:category?",
  "radar": [
    {
      "source": [
        "newslaundry.com/podcast"
      ],
      "target": "/podcast"
    },
    {
      "source": [
        "newslaundry.com/collection/nl-hafta-podcast"
      ],
      "target": "/podcast/nl-hafta"
    },
    {
      "source": [
        "newslaundry.com/podcast/whats-your-ism"
      ],
      "target": "/podcast/whats-your-ism"
    }
  ],
  "view": 0
}
```
