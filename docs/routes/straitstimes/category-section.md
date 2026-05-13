# The Strait Times - News

## Coverage
`index-only`

## Route
- Namespace: `straitstimes`
- Namespace Name: `The Strait Times`
- Route Path: `/:category?/:section?`
- Route Name: `News`
- Example: `/straitstimes/singapore`
- URL: `straitstimes.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/straitstimes/index.tsx')`

## Description
| Category               | `:category`               |
| ---------------------- | --------------------------- |
| Singapore              | `singapore`               |
| Asia                   | `asia`                    |
| World                  | `world`                   |
| Opinion                | `opinion`                 |
| Life                   | `life`                    |
| Business               | `business`                |
| Jobs                   | `jobs`                    |
| Parenting & Education  | `parenting-and-education` |
| Food                   | `food`                    |
| Tech                   | `tech`                    |
| Sport                  | `sport`                   |
| Podcasts               | `podcasts`                |,

| Section                | `:section`                |
| ---------------------- | --------------------------- |
| Top Stories            | `top-stories`             |
| Latest                 | `latest`                  |

## Parameters
- `category`: Category, see below for more information
- `section`: Section, see below for more information


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
### Rule 1
- `source`:
  - `www.straitstimes.com/:category`
- `target`: `/:category`
### Rule 2
- `source`:
  - `www.straitstimes.com`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "\n| Category               | `:category`               |\n| ---------------------- | --------------------------- |\n| Singapore              | `singapore`               |\n| Asia                   | `asia`                    |\n| World                  | `world`                   |\n| Opinion                | `opinion`                 |\n| Life                   | `life`                    |\n| Business               | `business`                |\n| Jobs                   | `jobs`                    |\n| Parenting & Education  | `parenting-and-education` |\n| Food                   | `food`                    |\n| Tech                   | `tech`                    |\n| Sport                  | `sport`                   |\n| Podcasts               | `podcasts`                |,\n\n| Section                | `:section`                |\n| ---------------------- | --------------------------- |\n| Top Stories            | `top-stories`             |\n| Latest                 | `latest`                  |",
  "example": "/straitstimes/singapore",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/straitstimes/index.tsx')",
  "name": "News",
  "parameters": {
    "category": "Category, see below for more information",
    "section": "Section, see below for more information"
  },
  "path": "/:category?/:section?",
  "radar": [
    {
      "source": [
        "www.straitstimes.com/:category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.straitstimes.com"
      ],
      "target": "/"
    }
  ]
}
```
