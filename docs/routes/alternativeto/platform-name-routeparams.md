# AlternativeTo - Platform Software

## Coverage
`index-only`

## Route
- Namespace: `alternativeto`
- Namespace Name: `AlternativeTo`
- Route Path: `/platform/:name/:routeParams?`
- Route Name: `Platform Software`
- Example: `/alternativeto/platform/firefox`
- URL: `www.alternativeto.net`
- Language: `en`
- Categories: `programming`
- Maintainers: `JimenezLi`
- Source Location: `platform.ts`
- Source Module: `() => import('@/routes/alternativeto/platform.ts')`

## Description
> routeParms can be copied from original site URL, example: `/alternativeto/platform/firefox/license=free`

## Parameters
- `name`: Platform name
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
  - `www.alternativeto.net/platform/:name`
- `target`: `/platform/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "> routeParms can be copied from original site URL, example: `/alternativeto/platform/firefox/license=free`",
  "example": "/alternativeto/platform/firefox",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "platform.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/alternativeto/platform.ts')",
  "name": "Platform Software",
  "parameters": {
    "name": "Platform name",
    "routeParams": "Filters of software type"
  },
  "path": "/platform/:name/:routeParams?",
  "radar": [
    {
      "source": [
        "www.alternativeto.net/platform/:name"
      ],
      "target": "/platform/:name"
    }
  ]
}
```
