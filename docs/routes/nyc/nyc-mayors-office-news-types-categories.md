# New York City Government - Mayor's Office News

## Coverage
`index-only`

## Route
- Namespace: `nyc`
- Namespace Name: `New York City Government`
- Route Path: `/nyc/mayors-office-news/:types?/:categories?`
- Route Name: `Mayor's Office News`
- Example: `/nyc/mayors-office-news/executive-orders/civic-services`
- URL: `nyc.gov`
- Language: `_None_`
- Categories: `government`
- Maintainers: `hkamran80`
- Source Location: `mayors-office-news.ts`
- Source Module: `_None_`

## Description
Types

| Type                | Slug                |
| ------------------- | ------------------- |
| Press releases      | press-releases      |
| Executive orders    | executive-orders    |
| Public schedule     | public-schedule     |
| Audio               | audio               |
| Statements          | statements          |
| Designation letters | designation-letters |
| Images              | images              |
| Video               | video               |
| All                 | all                 |

Categories

| Category                | Slug                |
| ----------------------- | ------------------- |
| Business                | business            |
| Culture and recreation  | culture-recreation  |
| Environment             | environment         |
| Housing and development | housing-development |
| Social services         | social-services     |
| Civic services          | civic-services      |
| Education               | education           |
| Health                  | health              |
| Public safety           | public-safety       |
| Transportation          | transportation      |
| All                     | all                 |

## Parameters
- `types`: {"default": "all", "description": "a comma-separated list of news types. Options: see table."}
- `categories`: {"default": "all", "description": "a comma-separated list of categories. Options: see table."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `nyc.gov`
  - `nyc.gov/mayors-office`
  - `nyc.gov/mayors-office/news/`
  - `nyc.gov/mayors-office/news/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Types\n\n| Type                | Slug                |\n| ------------------- | ------------------- |\n| Press releases      | press-releases      |\n| Executive orders    | executive-orders    |\n| Public schedule     | public-schedule     |\n| Audio               | audio               |\n| Statements          | statements          |\n| Designation letters | designation-letters |\n| Images              | images              |\n| Video               | video               |\n| All                 | all                 |\n\nCategories\n\n| Category                | Slug                |\n| ----------------------- | ------------------- |\n| Business                | business            |\n| Culture and recreation  | culture-recreation  |\n| Environment             | environment         |\n| Housing and development | housing-development |\n| Social services         | social-services     |\n| Civic services          | civic-services      |\n| Education               | education           |\n| Health                  | health              |\n| Public safety           | public-safety       |\n| Transportation          | transportation      |\n| All                     | all                 |",
  "example": "/nyc/mayors-office-news/executive-orders/civic-services",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "mayors-office-news.ts",
  "maintainers": [
    "hkamran80"
  ],
  "name": "Mayor's Office News",
  "parameters": {
    "categories": {
      "default": "all",
      "description": "a comma-separated list of categories. Options: see table."
    },
    "types": {
      "default": "all",
      "description": "a comma-separated list of news types. Options: see table."
    }
  },
  "path": "/mayors-office-news/:types?/:categories?",
  "radar": [
    {
      "source": [
        "nyc.gov",
        "nyc.gov/mayors-office",
        "nyc.gov/mayors-office/news/",
        "nyc.gov/mayors-office/news/*"
      ]
    }
  ],
  "topFeeds": []
}
```
