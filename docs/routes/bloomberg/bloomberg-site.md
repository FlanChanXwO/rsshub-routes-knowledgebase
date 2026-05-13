# Bloomberg - Bloomberg Site

## Coverage
`index-only`

## Route
- Namespace: `bloomberg`
- Namespace Name: `Bloomberg`
- Route Path: `/bloomberg/:site?`
- Route Name: `Bloomberg Site`
- Example: `/bloomberg/bbiz`
- URL: `www.bloomberg.com`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `bigfei`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| Site ID      | Title        |
| ------------ | ------------ |
| /            | News         |
| bpol         | Politics     |
| bbiz         | Business     |
| markets      | Markets      |
| technology   | Technology   |
| green        | Green        |
| wealth       | Wealth       |
| pursuits     | Pursuits     |
| bview        | Opinion      |
| equality     | Equality     |
| businessweek | Businessweek |
| citylab      | CityLab      |

## Parameters
- `site`: {"description": "Site ID, can be found below", "options": [{"label": "News", "value": "/"}, {"label": "Politics", "value": "bpol"}, {"label": "Business", "value": "bbiz"}, {"label": "Markets", "value": "markets"}, {"label": "Technology", "value": "technology"}, {"label": "Green", "value": "green"}, {"label": "Wealth", "value": "wealth"}, {"label": "Pursuits", "value": "pursuits"}, {"label": "Opinion", "value": "bview"}, {"label": "Equality", "value": "equality"}, {"label": "Businessweek", "value": "businessweek"}, {"label": "CityLab", "value": "citylab"}]}


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
    "finance",
    "popular"
  ],
  "description": "| Site ID      | Title        |\n| ------------ | ------------ |\n| /            | News         |\n| bpol         | Politics     |\n| bbiz         | Business     |\n| markets      | Markets      |\n| technology   | Technology   |\n| green        | Green        |\n| wealth       | Wealth       |\n| pursuits     | Pursuits     |\n| bview        | Opinion      |\n| equality     | Equality     |\n| businessweek | Businessweek |\n| citylab      | CityLab      |",
  "example": "/bloomberg/bbiz",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5412,
  "location": "index.ts",
  "maintainers": [
    "bigfei"
  ],
  "name": "Bloomberg Site",
  "parameters": {
    "site": {
      "description": "Site ID, can be found below",
      "options": [
        {
          "label": "News",
          "value": "/"
        },
        {
          "label": "Politics",
          "value": "bpol"
        },
        {
          "label": "Business",
          "value": "bbiz"
        },
        {
          "label": "Markets",
          "value": "markets"
        },
        {
          "label": "Technology",
          "value": "technology"
        },
        {
          "label": "Green",
          "value": "green"
        },
        {
          "label": "Wealth",
          "value": "wealth"
        },
        {
          "label": "Pursuits",
          "value": "pursuits"
        },
        {
          "label": "Opinion",
          "value": "bview"
        },
        {
          "label": "Equality",
          "value": "equality"
        },
        {
          "label": "Businessweek",
          "value": "businessweek"
        },
        {
          "label": "CityLab",
          "value": "citylab"
        }
      ]
    }
  },
  "path": "/:site?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Bloomberg - News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72541421314282496",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bloomberg.com/feeds///sitemap_news.xml",
      "title": "Bloomberg - News",
      "type": "feed",
      "url": "rsshub://bloomberg/%2F"
    },
    {
      "description": "Bloomberg - News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64731996464440320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.bloomberg.com/feeds/sitemap_news.xml",
      "title": "Bloomberg - News",
      "type": "feed",
      "url": "rsshub://bloomberg"
    }
  ],
  "view": 0
}
```
