# Access Briefing - Articles

## Coverage
`index-only`

## Route
- Namespace: `accessbriefing`
- Namespace Name: `Access Briefing`
- Route Path: `/:category{.+}?`
- Route Name: `Articles`
- Example: `/accessbriefing/latest/news`
- URL: `accessbriefing.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/accessbriefing/index.ts')`

## Description
::: tip
  If you subscribe to [Latest News](https://www.accessbriefing.com/latest/news)，where the URL is `https://www.accessbriefing.com/latest/news`, extract the part `https://www.accessbriefing.com/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/accessbriefing/latest/news`](https://rsshub.app/accessbriefing/latest/news).
:::

#### Latest

| Category                                                                               | ID                                                                                              |
| -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| [News](https://www.accessbriefing.com/latest/news)                                     | [latest/news](https://rsshub.app/target/site/latest/news)                                       |
| [Products & Technology](https://www.accessbriefing.com/latest/products-and-technology) | [latest/products-and-technology](https://rsshub.app/target/site/latest/products-and-technology) |
| [Rental News](https://www.accessbriefing.com/latest/rental-news)                       | [latest/rental-news](https://rsshub.app/target/site/latest/rental-news)                         |
| [People](https://www.accessbriefing.com/latest/people)                                 | [latest/people](https://rsshub.app/target/site/latest/people)                                   |
| [Regualtions & Safety](https://www.accessbriefing.com/latest/regualtions-safety)       | [latest/regualtions-safety](https://rsshub.app/target/site/latest/regualtions-safety)           |
| [Finance](https://www.accessbriefing.com/latest/finance)                               | [latest/finance](https://rsshub.app/target/site/latest/finance)                                 |
| [Sustainability](https://www.accessbriefing.com/latest/sustainability)                 | [latest/sustainability](https://rsshub.app/target/site/latest/sustainability)                   |

#### Insight

| Category                                                                          | ID                                                                                        |
| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| [Interviews](https://www.accessbriefing.com/insight/interviews)                   | [insight/interviews](https://rsshub.app/target/site/insight/interviews)                   |
| [Longer reads](https://www.accessbriefing.com/insight/longer-reads)               | [insight/longer-reads](https://rsshub.app/target/site/insight/longer-reads)               |
| [Videos and podcasts](https://www.accessbriefing.com/insight/videos-and-podcasts) | [insight/videos-and-podcasts](https://rsshub.app/target/site/insight/videos-and-podcasts) |

## Parameters
- `category`: Category, Latest News by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `accessbriefing.com/:category*`
- `target`: `/:category`
### Rule 2
- `title`: `Latest - News`
- `source`:
  - `accessbriefing.com/latest/news`
- `target`: `/latest/news`
### Rule 3
- `title`: `Latest - Products & Technology`
- `source`:
  - `accessbriefing.com/latest/products-and-technology`
- `target`: `/latest/products-and-technology`
### Rule 4
- `title`: `Latest - Rental News`
- `source`:
  - `accessbriefing.com/latest/rental-news`
- `target`: `/latest/rental-news`
### Rule 5
- `title`: `Latest - People`
- `source`:
  - `accessbriefing.com/latest/people`
- `target`: `/latest/people`
### Rule 6
- `title`: `Latest - Regualtions & Safety`
- `source`:
  - `accessbriefing.com/latest/regualtions-safety`
- `target`: `/latest/regualtions-safety`
### Rule 7
- `title`: `Latest - Finance`
- `source`:
  - `accessbriefing.com/latest/finance`
- `target`: `/latest/finance`
### Rule 8
- `title`: `Latest - Sustainability`
- `source`:
  - `accessbriefing.com/latest/sustainability`
- `target`: `/latest/sustainability`
### Rule 9
- `title`: `Insight - Interviews`
- `source`:
  - `accessbriefing.com/insight/interviews`
- `target`: `/insight/interviews`
### Rule 10
- `title`: `Insight - Longer reads`
- `source`:
  - `accessbriefing.com/insight/longer-reads`
- `target`: `/insight/longer-reads`
### Rule 11
- `title`: `Insight - Videos and podcasts`
- `source`:
  - `accessbriefing.com/insight/videos-and-podcasts`
- `target`: `/insight/videos-and-podcasts`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n  If you subscribe to [Latest News](https://www.accessbriefing.com/latest/news)，where the URL is `https://www.accessbriefing.com/latest/news`, extract the part `https://www.accessbriefing.com/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/accessbriefing/latest/news`](https://rsshub.app/accessbriefing/latest/news).\n:::\n\n#### Latest\n\n| Category                                                                               | ID                                                                                              |\n| -------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |\n| [News](https://www.accessbriefing.com/latest/news)                                     | [latest/news](https://rsshub.app/target/site/latest/news)                                       |\n| [Products & Technology](https://www.accessbriefing.com/latest/products-and-technology) | [latest/products-and-technology](https://rsshub.app/target/site/latest/products-and-technology) |\n| [Rental News](https://www.accessbriefing.com/latest/rental-news)                       | [latest/rental-news](https://rsshub.app/target/site/latest/rental-news)                         |\n| [People](https://www.accessbriefing.com/latest/people)                                 | [latest/people](https://rsshub.app/target/site/latest/people)                                   |\n| [Regualtions & Safety](https://www.accessbriefing.com/latest/regualtions-safety)       | [latest/regualtions-safety](https://rsshub.app/target/site/latest/regualtions-safety)           |\n| [Finance](https://www.accessbriefing.com/latest/finance)                               | [latest/finance](https://rsshub.app/target/site/latest/finance)                                 |\n| [Sustainability](https://www.accessbriefing.com/latest/sustainability)                 | [latest/sustainability](https://rsshub.app/target/site/latest/sustainability)                   |\n\n#### Insight\n\n| Category                                                                          | ID                                                                                        |\n| --------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |\n| [Interviews](https://www.accessbriefing.com/insight/interviews)                   | [insight/interviews](https://rsshub.app/target/site/insight/interviews)                   |\n| [Longer reads](https://www.accessbriefing.com/insight/longer-reads)               | [insight/longer-reads](https://rsshub.app/target/site/insight/longer-reads)               |\n| [Videos and podcasts](https://www.accessbriefing.com/insight/videos-and-podcasts) | [insight/videos-and-podcasts](https://rsshub.app/target/site/insight/videos-and-podcasts) |\n  ",
  "example": "/accessbriefing/latest/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/accessbriefing/index.ts')",
  "name": "Articles",
  "parameters": {
    "category": "Category, Latest News by default"
  },
  "path": "/:category{.+}?",
  "radar": [
    {
      "source": [
        "accessbriefing.com/:category*"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "accessbriefing.com/latest/news"
      ],
      "target": "/latest/news",
      "title": "Latest - News"
    },
    {
      "source": [
        "accessbriefing.com/latest/products-and-technology"
      ],
      "target": "/latest/products-and-technology",
      "title": "Latest - Products & Technology"
    },
    {
      "source": [
        "accessbriefing.com/latest/rental-news"
      ],
      "target": "/latest/rental-news",
      "title": "Latest - Rental News"
    },
    {
      "source": [
        "accessbriefing.com/latest/people"
      ],
      "target": "/latest/people",
      "title": "Latest - People"
    },
    {
      "source": [
        "accessbriefing.com/latest/regualtions-safety"
      ],
      "target": "/latest/regualtions-safety",
      "title": "Latest - Regualtions & Safety"
    },
    {
      "source": [
        "accessbriefing.com/latest/finance"
      ],
      "target": "/latest/finance",
      "title": "Latest - Finance"
    },
    {
      "source": [
        "accessbriefing.com/latest/sustainability"
      ],
      "target": "/latest/sustainability",
      "title": "Latest - Sustainability"
    },
    {
      "source": [
        "accessbriefing.com/insight/interviews"
      ],
      "target": "/insight/interviews",
      "title": "Insight - Interviews"
    },
    {
      "source": [
        "accessbriefing.com/insight/longer-reads"
      ],
      "target": "/insight/longer-reads",
      "title": "Insight - Longer reads"
    },
    {
      "source": [
        "accessbriefing.com/insight/videos-and-podcasts"
      ],
      "target": "/insight/videos-and-podcasts",
      "title": "Insight - Videos and podcasts"
    }
  ],
  "url": "accessbriefing.com"
}
```
