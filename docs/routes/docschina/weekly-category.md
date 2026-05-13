# 印记中文 - 周刊 - JavaScript

## Coverage
`index-only`

## Route
- Namespace: `docschina`
- Namespace Name: `印记中文`
- Route Path: `/weekly/:category?`
- Route Name: `周刊 - JavaScript`
- Example: `/docschina/weekly`
- URL: `docschina.org`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `daijinru, hestudy`
- Source Location: `weekly.ts`
- Source Module: `() => import('@/routes/docschina/weekly.ts')`

## Description
| javascript | node | react |
| ---------- | ---- | ----- |
| js         | node | react |

## Parameters
- `category`: 周刊分类，见下表，默认为js


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `docschina.org/news/weekly/js/*`
  - `docschina.org/news/weekly/js`
  - `docschina.org/`
- `target`: `/jsweekly`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| javascript | node | react |\n| ---------- | ---- | ----- |\n| js         | node | react |",
  "example": "/docschina/weekly",
  "location": "weekly.ts",
  "maintainers": [
    "daijinru",
    "hestudy"
  ],
  "module": "() => import('@/routes/docschina/weekly.ts')",
  "name": "周刊 - JavaScript",
  "parameters": {
    "category": "周刊分类，见下表，默认为js"
  },
  "path": "/weekly/:category?",
  "radar": [
    {
      "source": [
        "docschina.org/news/weekly/js/*",
        "docschina.org/news/weekly/js",
        "docschina.org/"
      ],
      "target": "/jsweekly"
    }
  ]
}
```
