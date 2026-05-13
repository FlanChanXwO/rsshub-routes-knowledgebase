# 30 Seconds of code - Category and Subcategory

## Coverage
`index-only`

## Route
- Namespace: `30secondsofcode`
- Namespace Name: `30 Seconds of code`
- Route Path: `/category/:category?/:subCategory?`
- Route Name: `Category and Subcategory`
- Example: `/category/css/interactivity`
- URL: `www.30secondsofcode.org`
- Language: `en`
- Categories: `programming`
- Maintainers: `Rjnishant530`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/30secondsofcode/category.ts')`

## Description
_None_

## Parameters
- `category`: {"description": "Main Category. For Complete list visit site \"https://www.30secondsofcode.org/collections/p/1/\"", "options": [{"label": "Javascript", "value": "js"}, {"label": "CSS", "value": "css"}, {"label": "JavaScript Algorithms", "value": "algorithm"}, {"label": "React", "value": "react"}]}
- `subCategory`: {"description": "Filter within Category. Visit Individual Category site for subCategories"}


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
  - `30secondsofcode.org/:category/:subCategory/`
  - `30secondsofcode.org/:category/`
- `target`: `/category/:category/:subCategory`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/category/css/interactivity",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/30secondsofcode/category.ts')",
  "name": "Category and Subcategory",
  "parameters": {
    "category": {
      "description": "Main Category. For Complete list visit site \"https://www.30secondsofcode.org/collections/p/1/\"",
      "options": [
        {
          "label": "Javascript",
          "value": "js"
        },
        {
          "label": "CSS",
          "value": "css"
        },
        {
          "label": "JavaScript Algorithms",
          "value": "algorithm"
        },
        {
          "label": "React",
          "value": "react"
        }
      ]
    },
    "subCategory": {
      "description": "Filter within Category. Visit Individual Category site for subCategories"
    }
  },
  "path": "/category/:category?/:subCategory?",
  "radar": [
    {
      "source": [
        "30secondsofcode.org/:category/:subCategory/",
        "30secondsofcode.org/:category/"
      ],
      "target": "/category/:category/:subCategory"
    }
  ]
}
```
