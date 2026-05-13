# PornHub - Model

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/model/:username/:language?/:sort?/:img?`
- Route Name: `Model`
- Example: `/pornhub/model/stacy-starando`
- URL: `pornhub.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `model.ts`
- Source Module: `() => import('@/routes/pornhub/model.ts')`

## Description
_None_

## Parameters
- `language`: language, see below. defaults to www
- `username`: username, part of the url e.g. `pornhub.com/model/stacy-starando`
- `sort`: sorting method, see below. Defaults to mr (most recent)
- `img`: show images, set to `img=1` to enable


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.pornhub.com/model/:username`
  - `www.pornhub.com/model/:username/*`
- `target`: `/model/:username`
### Rule 2
- `source`:
  - `de.pornhub.com/model/:username`
  - `de.pornhub.com/model/:username/*`
- `target`: `/model/:username/de`
### Rule 3
- `source`:
  - `fr.pornhub.com/model/:username`
  - `fr.pornhub.com/model/:username/*`
- `target`: `/model/:username/fr`
### Rule 4
- `source`:
  - `es.pornhub.com/model/:username`
  - `es.pornhub.com/model/:username/*`
- `target`: `/model/:username/es`
### Rule 5
- `source`:
  - `it.pornhub.com/model/:username`
  - `it.pornhub.com/model/:username/*`
- `target`: `/model/:username/it`
### Rule 6
- `source`:
  - `pt.pornhub.com/model/:username`
  - `pt.pornhub.com/model/:username/*`
- `target`: `/model/:username/pt`
### Rule 7
- `source`:
  - `pl.pornhub.com/model/:username`
  - `pl.pornhub.com/model/:username/*`
- `target`: `/model/:username/pl`
### Rule 8
- `source`:
  - `rt.pornhub.com/model/:username`
  - `rt.pornhub.com/model/:username/*`
- `target`: `/model/:username/rt`
### Rule 9
- `source`:
  - `jp.pornhub.com/model/:username`
  - `jp.pornhub.com/model/:username/*`
- `target`: `/model/:username/jp`
### Rule 10
- `source`:
  - `nl.pornhub.com/model/:username`
  - `nl.pornhub.com/model/:username/*`
- `target`: `/model/:username/nl`
### Rule 11
- `source`:
  - `cz.pornhub.com/model/:username`
  - `cz.pornhub.com/model/:username/*`
- `target`: `/model/:username/cz`
### Rule 12
- `source`:
  - `cn.pornhub.com/model/:username`
  - `cn.pornhub.com/model/:username/*`
- `target`: `/model/:username/cn`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/pornhub/model/stacy-starando",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "model.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "module": "() => import('@/routes/pornhub/model.ts')",
  "name": "Model",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": "language, see below. defaults to www",
    "sort": "sorting method, see below. Defaults to mr (most recent)",
    "username": "username, part of the url e.g. `pornhub.com/model/stacy-starando`"
  },
  "path": "/model/:username/:language?/:sort?/:img?",
  "radar": [
    {
      "source": [
        "www.pornhub.com/model/:username",
        "www.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username"
    },
    {
      "source": [
        "de.pornhub.com/model/:username",
        "de.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/de"
    },
    {
      "source": [
        "fr.pornhub.com/model/:username",
        "fr.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/fr"
    },
    {
      "source": [
        "es.pornhub.com/model/:username",
        "es.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/es"
    },
    {
      "source": [
        "it.pornhub.com/model/:username",
        "it.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/it"
    },
    {
      "source": [
        "pt.pornhub.com/model/:username",
        "pt.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/pt"
    },
    {
      "source": [
        "pl.pornhub.com/model/:username",
        "pl.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/pl"
    },
    {
      "source": [
        "rt.pornhub.com/model/:username",
        "rt.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/rt"
    },
    {
      "source": [
        "jp.pornhub.com/model/:username",
        "jp.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/jp"
    },
    {
      "source": [
        "nl.pornhub.com/model/:username",
        "nl.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/nl"
    },
    {
      "source": [
        "cz.pornhub.com/model/:username",
        "cz.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/cz"
    },
    {
      "source": [
        "cn.pornhub.com/model/:username",
        "cn.pornhub.com/model/:username/*"
      ],
      "target": "/model/:username/cn"
    }
  ],
  "view": 3
}
```
