# 钛媒体 - 最新

## Coverage
`index-only`

## Route
- Namespace: `tmtpost`
- Namespace Name: `钛媒体`
- Route Path: `/tmtpost/new`
- Route Name: `最新`
- Example: `/tmtpost/new`
- URL: `www.tmtpost.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `new.ts`
- Source Module: `_None_`

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
  "heat": 23,
  "location": "new.ts",
  "maintainers": [
    "nczitzk"
  ],
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
  "topFeeds": [
    {
      "description": "【最新资讯】及时的科股原创内容，有钛度的科股原创内容，帮助您及时获取互联网信息的信息，更多资讯内容，就在钛媒体官方网站。 - Powered by RSSHub",
      "errorAt": "2026-07-10T03:38:23.045Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 107943520642321408",
      "id": "107943520642321408",
      "image": "https://images.tmtpost.com/uploads/images/zhaopian/nuxtpic/change_logo3/og_image.png",
      "ownerUserId": null,
      "siteUrl": "https://www.tmtpost.com/new",
      "title": "最新资讯大全-钛媒体官方网站",
      "type": "feed",
      "url": "rsshub://tmtpost/new"
    }
  ],
  "url": "www.tmtpost.com",
  "view": 0
}
```
