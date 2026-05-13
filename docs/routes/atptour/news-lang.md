# ATP Tour - News

## Coverage
`index-only`

## Route
- Namespace: `atptour`
- Namespace Name: `ATP Tour`
- Route Path: `/news/:lang?`
- Route Name: `News`
- Example: `/atptour/news/en`
- URL: `www.atptour.com`
- Language: `en`
- Categories: `sport`
- Maintainers: `LM1207`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/atptour/news.ts')`

## Description
_None_

## Parameters
- `lang`: en or es.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `atptour.com`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/atptour/news/en",
  "location": "news.ts",
  "maintainers": [
    "LM1207"
  ],
  "module": "() => import('@/routes/atptour/news.ts')",
  "name": "News",
  "parameters": {
    "lang": "en or es."
  },
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "atptour.com"
      ]
    }
  ]
}
```
