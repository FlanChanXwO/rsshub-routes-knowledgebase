# PornHub - Pornstar

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/pornstar/:username/:language?/:sort?/:img?`
- Route Name: `Pornstar`
- Example: `/pornhub/pornstar/june-liu/www/mr`
- URL: `pornhub.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `I2IMk, queensferryme`
- Source Location: `pornstar.ts`
- Source Module: `() => import('@/routes/pornhub/pornstar.ts')`

## Description
_None_

## Parameters
- `username`: {"description": "username, part of the url e.g. `pornhub.com/pornstar/june-liu`"}
- `language`: {"default": "www", "description": "language, defaults to `www` (English)", "options": [{"label": "English", "value": "www"}, {"label": "Deutsch", "value": "de"}, {"label": "Español", "value": "es"}, {"label": "Français", "value": "fr"}, {"label": "Italiano", "value": "it"}, {"label": "日本語", "value": "ja"}, {"label": "Português", "value": "pt"}, {"label": "Polski", "value": "pl"}, {"label": "Русский", "value": "rt"}, {"label": "Dutch", "value": "nl"}, {"label": "Czech", "value": "cs"}, {"label": "中文（简体）", "value": "cn"}]}
- `sort`: {"description": "sorting method, defaults to `mr` (Most Recent)", "options": [{"label": "Most Recent", "value": "mr"}, {"label": "Most Viewed", "value": "mv"}, {"label": "Top Rated", "value": "tr"}, {"label": "Longest", "value": "lg"}]}
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
  - `www.pornhub.com/pornstar/:username`
  - `www.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username`
### Rule 2
- `source`:
  - `de.pornhub.com/pornstar/:username`
  - `de.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/de`
### Rule 3
- `source`:
  - `fr.pornhub.com/pornstar/:username`
  - `fr.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/fr`
### Rule 4
- `source`:
  - `es.pornhub.com/pornstar/:username`
  - `es.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/es`
### Rule 5
- `source`:
  - `it.pornhub.com/pornstar/:username`
  - `it.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/it`
### Rule 6
- `source`:
  - `pt.pornhub.com/pornstar/:username`
  - `pt.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/pt`
### Rule 7
- `source`:
  - `pl.pornhub.com/pornstar/:username`
  - `pl.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/pl`
### Rule 8
- `source`:
  - `rt.pornhub.com/pornstar/:username`
  - `rt.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/rt`
### Rule 9
- `source`:
  - `jp.pornhub.com/pornstar/:username`
  - `jp.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/jp`
### Rule 10
- `source`:
  - `nl.pornhub.com/pornstar/:username`
  - `nl.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/nl`
### Rule 11
- `source`:
  - `cz.pornhub.com/pornstar/:username`
  - `cz.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/cz`
### Rule 12
- `source`:
  - `cn.pornhub.com/pornstar/:username`
  - `cn.pornhub.com/pornstar/:username/*`
- `target`: `/pornstar/:username/cn`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/pornhub/pornstar/june-liu/www/mr",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pornstar.ts",
  "maintainers": [
    "I2IMk",
    "queensferryme"
  ],
  "module": "() => import('@/routes/pornhub/pornstar.ts')",
  "name": "Pornstar",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "language": {
      "default": "www",
      "description": "language, defaults to `www` (English)",
      "options": [
        {
          "label": "English",
          "value": "www"
        },
        {
          "label": "Deutsch",
          "value": "de"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Français",
          "value": "fr"
        },
        {
          "label": "Italiano",
          "value": "it"
        },
        {
          "label": "日本語",
          "value": "ja"
        },
        {
          "label": "Português",
          "value": "pt"
        },
        {
          "label": "Polski",
          "value": "pl"
        },
        {
          "label": "Русский",
          "value": "rt"
        },
        {
          "label": "Dutch",
          "value": "nl"
        },
        {
          "label": "Czech",
          "value": "cs"
        },
        {
          "label": "中文（简体）",
          "value": "cn"
        }
      ]
    },
    "sort": {
      "description": "sorting method, defaults to `mr` (Most Recent)",
      "options": [
        {
          "label": "Most Recent",
          "value": "mr"
        },
        {
          "label": "Most Viewed",
          "value": "mv"
        },
        {
          "label": "Top Rated",
          "value": "tr"
        },
        {
          "label": "Longest",
          "value": "lg"
        }
      ]
    },
    "username": {
      "description": "username, part of the url e.g. `pornhub.com/pornstar/june-liu`"
    }
  },
  "path": "/pornstar/:username/:language?/:sort?/:img?",
  "radar": [
    {
      "source": [
        "www.pornhub.com/pornstar/:username",
        "www.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username"
    },
    {
      "source": [
        "de.pornhub.com/pornstar/:username",
        "de.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/de"
    },
    {
      "source": [
        "fr.pornhub.com/pornstar/:username",
        "fr.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/fr"
    },
    {
      "source": [
        "es.pornhub.com/pornstar/:username",
        "es.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/es"
    },
    {
      "source": [
        "it.pornhub.com/pornstar/:username",
        "it.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/it"
    },
    {
      "source": [
        "pt.pornhub.com/pornstar/:username",
        "pt.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/pt"
    },
    {
      "source": [
        "pl.pornhub.com/pornstar/:username",
        "pl.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/pl"
    },
    {
      "source": [
        "rt.pornhub.com/pornstar/:username",
        "rt.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/rt"
    },
    {
      "source": [
        "jp.pornhub.com/pornstar/:username",
        "jp.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/jp"
    },
    {
      "source": [
        "nl.pornhub.com/pornstar/:username",
        "nl.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/nl"
    },
    {
      "source": [
        "cz.pornhub.com/pornstar/:username",
        "cz.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/cz"
    },
    {
      "source": [
        "cn.pornhub.com/pornstar/:username",
        "cn.pornhub.com/pornstar/:username/*"
      ],
      "target": "/pornstar/:username/cn"
    }
  ],
  "view": 3
}
```
