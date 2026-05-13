# DNA India - News

## Coverage
`index-only`

## Route
- Namespace: `dnaindia`
- Namespace Name: `DNA India`
- Route Path: `/:category`
- Route Name: `News`
- Example: `/dnaindia/headlines`
- URL: `www.dnaindia.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `Rjnishant530`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/dnaindia/news.ts')`

## Description
Categories:

| Headlines | Explainer | India | Entertainment | Sports | Viral | Lifestyle | Education | Business | World |
| --------- | --------- | ----- | ------------- | ------ | ----- | --------- | --------- | -------- | ----- |
| headlines | explainer | india | entertainment | sports | viral | lifestyle | education | business | world |

## Parameters
- `category`: Find it in the URL, or tables below


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dnaindia.com/:category`

## Raw JSON
```json
{
  "description": "Categories:\n\n| Headlines | Explainer | India | Entertainment | Sports | Viral | Lifestyle | Education | Business | World |\n| --------- | --------- | ----- | ------------- | ------ | ----- | --------- | --------- | -------- | ----- |\n| headlines | explainer | india | entertainment | sports | viral | lifestyle | education | business | world |",
  "example": "/dnaindia/headlines",
  "location": "news.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/dnaindia/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Find it in the URL, or tables below"
  },
  "path": [
    "/:category"
  ],
  "radar": [
    {
      "source": [
        "www.dnaindia.com/:category"
      ]
    }
  ],
  "url": "www.dnaindia.com"
}
```
