# MindMeister - Public Maps

## Coverage
`index-only`

## Route
- Namespace: `mindmeister`
- Namespace Name: `MindMeister`
- Route Path: `/:category?/:language?`
- Route Name: `Public Maps`
- Example: `/mindmeister/mind-map-examples`
- URL: `mindmeister.com`
- Language: `en`
- Categories: `study`
- Maintainers: `TonyRL`
- Source Location: `example.tsx`
- Source Module: `() => import('@/routes/mindmeister/example.tsx')`

## Description
| Categories    | parameter         |
| ------------- | ----------------- |
| Featured Map  | mind-map-examples |
| Business      | business          |
| Design        | design            |
| Education     | education         |
| Entertainment | entertainment     |
| Life          | life              |
| Marketing     | marketing         |
| Productivity  | productivity      |
| Summaries     | summaries         |
| Technology    | technology        |
| Other         | other             |

| Languages  | parameter |
| ---------- | --------- |
| English    | en        |
| Deutsch    | de        |
| Français   | fr        |
| Español    | es        |
| Português  | pt        |
| Nederlands | nl        |
| Dansk      | da        |
| Русский    | ru        |
| 日本語     | ja        |
| Italiano   | it        |
| 简体中文   | zh        |
| 한국어     | ko        |
| Other      | other     |

## Parameters
- `category`: Categories, see the table below, `mind-map-examples` by default
- `language`: Languages, see the table below, `en` by default


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
    "study"
  ],
  "description": "| Categories    | parameter         |\n| ------------- | ----------------- |\n| Featured Map  | mind-map-examples |\n| Business      | business          |\n| Design        | design            |\n| Education     | education         |\n| Entertainment | entertainment     |\n| Life          | life              |\n| Marketing     | marketing         |\n| Productivity  | productivity      |\n| Summaries     | summaries         |\n| Technology    | technology        |\n| Other         | other             |\n\n| Languages  | parameter |\n| ---------- | --------- |\n| English    | en        |\n| Deutsch    | de        |\n| Français   | fr        |\n| Español    | es        |\n| Português  | pt        |\n| Nederlands | nl        |\n| Dansk      | da        |\n| Русский    | ru        |\n| 日本語     | ja        |\n| Italiano   | it        |\n| 简体中文   | zh        |\n| 한국어     | ko        |\n| Other      | other     |",
  "example": "/mindmeister/mind-map-examples",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "example.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/mindmeister/example.tsx')",
  "name": "Public Maps",
  "parameters": {
    "category": "Categories, see the table below, `mind-map-examples` by default",
    "language": "Languages, see the table below, `en` by default"
  },
  "path": "/:category?/:language?"
}
```
