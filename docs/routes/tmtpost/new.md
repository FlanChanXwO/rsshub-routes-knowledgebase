# 钛媒体 - 最新

## Coverage
`index-only`

## Route
- Namespace: `tmtpost`
- Namespace Name: `钛媒体`
- Route Path: `/new`
- Route Name: `最新`
- Example: `/tmtpost/new`
- URL: `www.tmtpost.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `new.ts`
- Source Module: `() => import('@/routes/tmtpost/new.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.tmtpost.com`
- `target`: `/new`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/tmtpost/new",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "new.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/tmtpost/new.ts')",
  "name": "最新",
  "path": "/new",
  "radar": [
    {
      "source": [
        "www.tmtpost.com"
      ],
      "target": "/new"
    }
  ],
  "url": "www.tmtpost.com",
  "view": 0
}
```
