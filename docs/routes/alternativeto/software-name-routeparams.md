# AlternativeTo - Software Alternatives

## Coverage
`index-only`

## Route
- Namespace: `alternativeto`
- Namespace Name: `AlternativeTo`
- Route Path: `/software/:name/:routeParams?`
- Route Name: `Software Alternatives`
- Example: `/alternativeto/software/cpp`
- URL: `www.alternativeto.net`
- Language: `en`
- Categories: `programming`
- Maintainers: `JimenezLi`
- Source Location: `software.ts`
- Source Module: `() => import('@/routes/alternativeto/software.ts')`

## Description
> routeParms can be copied from original site URL, example: `/alternativeto/software/cpp/license=opensource&platform=windows`

## Parameters
- `name`: Software name
- `routeParams`: Filters of software type


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.alternativeto.net/software/:name`
- `target`: `/software/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "> routeParms can be copied from original site URL, example: `/alternativeto/software/cpp/license=opensource&platform=windows`",
  "example": "/alternativeto/software/cpp",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "software.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/alternativeto/software.ts')",
  "name": "Software Alternatives",
  "parameters": {
    "name": "Software name",
    "routeParams": "Filters of software type"
  },
  "path": "/software/:name/:routeParams?",
  "radar": [
    {
      "source": [
        "www.alternativeto.net/software/:name"
      ],
      "target": "/software/:name"
    }
  ]
}
```
