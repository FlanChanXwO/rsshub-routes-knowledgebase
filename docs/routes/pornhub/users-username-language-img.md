# PornHub - Users

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/users/:username/:language?/:img?`
- Route Name: `Users`
- Example: `/pornhub/users/pornhubmodels`
- URL: `pornhub.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `users.ts`
- Source Module: `() => import('@/routes/pornhub/users.ts')`

## Description
_None_

## Parameters
- `language`: language, see below. defaults to `www` (English)
- `username`: username, part of the url e.g. `pornhub.com/users/pornhubmodels`
- `img`: show images, set to `img=1` to enable


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.pornhub.com/users/:username`
  - `www.pornhub.com/users/:username/*`
- `target`: `/users/:username`
### Rule 2
- `source`:
  - `de.pornhub.com/users/:username`
  - `de.pornhub.com/users/:username/*`
- `target`: `/users/:username/de`
### Rule 3
- `source`:
  - `fr.pornhub.com/users/:username`
  - `fr.pornhub.com/users/:username/*`
- `target`: `/users/:username/fr`
### Rule 4
- `source`:
  - `es.pornhub.com/users/:username`
  - `es.pornhub.com/users/:username/*`
- `target`: `/users/:username/es`
### Rule 5
- `source`:
  - `it.pornhub.com/users/:username`
  - `it.pornhub.com/users/:username/*`
- `target`: `/users/:username/it`
### Rule 6
- `source`:
  - `pt.pornhub.com/users/:username`
  - `pt.pornhub.com/users/:username/*`
- `target`: `/users/:username/pt`
### Rule 7
- `source`:
  - `pl.pornhub.com/users/:username`
  - `pl.pornhub.com/users/:username/*`
- `target`: `/users/:username/pl`
### Rule 8
- `source`:
  - `rt.pornhub.com/users/:username`
  - `rt.pornhub.com/users/:username/*`
- `target`: `/users/:username/rt`
### Rule 9
- `source`:
  - `jp.pornhub.com/users/:username`
  - `jp.pornhub.com/users/:username/*`
- `target`: `/users/:username/jp`
### Rule 10
- `source`:
  - `nl.pornhub.com/users/:username`
  - `nl.pornhub.com/users/:username/*`
- `target`: `/users/:username/nl`
### Rule 11
- `source`:
  - `cz.pornhub.com/users/:username`
  - `cz.pornhub.com/users/:username/*`
- `target`: `/users/:username/cz`
### Rule 12
- `source`:
  - `cn.pornhub.com/users/:username`
  - `cn.pornhub.com/users/:username/*`
- `target`: `/users/:username/cn`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/pornhub/users/pornhubmodels",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "users.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "module": "() => import('@/routes/pornhub/users.ts')",
  "name": "Users",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": "language, see below. defaults to `www` (English)",
    "username": "username, part of the url e.g. `pornhub.com/users/pornhubmodels`"
  },
  "path": "/users/:username/:language?/:img?",
  "radar": [
    {
      "source": [
        "www.pornhub.com/users/:username",
        "www.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username"
    },
    {
      "source": [
        "de.pornhub.com/users/:username",
        "de.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/de"
    },
    {
      "source": [
        "fr.pornhub.com/users/:username",
        "fr.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/fr"
    },
    {
      "source": [
        "es.pornhub.com/users/:username",
        "es.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/es"
    },
    {
      "source": [
        "it.pornhub.com/users/:username",
        "it.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/it"
    },
    {
      "source": [
        "pt.pornhub.com/users/:username",
        "pt.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/pt"
    },
    {
      "source": [
        "pl.pornhub.com/users/:username",
        "pl.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/pl"
    },
    {
      "source": [
        "rt.pornhub.com/users/:username",
        "rt.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/rt"
    },
    {
      "source": [
        "jp.pornhub.com/users/:username",
        "jp.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/jp"
    },
    {
      "source": [
        "nl.pornhub.com/users/:username",
        "nl.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/nl"
    },
    {
      "source": [
        "cz.pornhub.com/users/:username",
        "cz.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/cz"
    },
    {
      "source": [
        "cn.pornhub.com/users/:username",
        "cn.pornhub.com/users/:username/*"
      ],
      "target": "/users/:username/cn"
    }
  ]
}
```
