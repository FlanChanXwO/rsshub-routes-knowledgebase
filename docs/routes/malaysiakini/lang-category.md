# Malaysiakini - News

## Coverage
`index-only`

## Route
- Namespace: `malaysiakini`
- Namespace Name: `Malaysiakini`
- Route Path: `/:lang/:category?`
- Route Name: `News`
- Example: `/malaysiakini/en`
- URL: `malaysiakini.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/malaysiakini/index.ts')`

## Description
| Language | English | Bahasa Malaysia | 华文     |
| -------- | ------ | ------- | ------ | 
| `:lang`  | `en`    | `my`   | `zh`    |

| Category               | `:category` |
| ---------------------- | ------------- |
| News                   | `news`      |
| Columns                | `columns`   |
| From Our Readers       | `letters`   |

## Parameters
- `lang`: Language, see below
- `category`: Category, see below, news by default


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: [{"description": "Malaysiakini Email or Username", "name": "MALAYSIAKINI_EMAIL", "optional": true}, {"description": "Malaysiakini Password", "name": "MALAYSIAKINI_PASSWORD", "optional": true}, {"description": "To obtain the refresh token, log into Malaysiakini and look for the cookie `nl____refreshToken` within document.cookie in the browser console. The token is the value of the cookie.", "name": "MALAYSIAKINI_REFRESHTOKEN", "optional": true}]

## Radar
### Rule 1
- `source`:
  - `malaysiakini.com/`
- `target`: `/en`
### Rule 2
- `source`:
  - `malaysiakini.com/:lang`
- `target`: `/:lang`
### Rule 3
- `source`:
  - `www.malaysiakini.com/:lang/latest/:category`
- `target`: `/:lang/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "\n| Language | English | Bahasa Malaysia | 华文     |\n| -------- | ------ | ------- | ------ | \n| `:lang`  | `en`    | `my`   | `zh`    |\n\n| Category               | `:category` |\n| ---------------------- | ------------- |\n| News                   | `news`      |\n| Columns                | `columns`   |\n| From Our Readers       | `letters`   |",
  "example": "/malaysiakini/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Malaysiakini Email or Username",
        "name": "MALAYSIAKINI_EMAIL",
        "optional": true
      },
      {
        "description": "Malaysiakini Password",
        "name": "MALAYSIAKINI_PASSWORD",
        "optional": true
      },
      {
        "description": "To obtain the refresh token, log into Malaysiakini and look for the cookie `nl____refreshToken` within document.cookie in the browser console. The token is the value of the cookie.",
        "name": "MALAYSIAKINI_REFRESHTOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/malaysiakini/index.ts')",
  "name": "News",
  "parameters": {
    "category": "Category, see below, news by default",
    "lang": "Language, see below"
  },
  "path": "/:lang/:category?",
  "radar": [
    {
      "source": [
        "malaysiakini.com/"
      ],
      "target": "/en"
    },
    {
      "source": [
        "malaysiakini.com/:lang"
      ],
      "target": "/:lang"
    },
    {
      "source": [
        "www.malaysiakini.com/:lang/latest/:category"
      ],
      "target": "/:lang/:category"
    }
  ]
}
```
