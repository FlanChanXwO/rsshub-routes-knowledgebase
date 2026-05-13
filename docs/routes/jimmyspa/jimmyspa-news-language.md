# 幾米 JIMMY S.P.A. Official Website - News

## Coverage
`index-only`

## Route
- Namespace: `jimmyspa`
- Namespace Name: `幾米 JIMMY S.P.A. Official Website`
- Route Path: `/jimmyspa/news/:language`
- Route Name: `News`
- Example: `/jimmyspa/news/tw`
- URL: `www.jimmyspa.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `Cedaric`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| language | Description |
| -------- | ----------- |
| tw       | 臺灣正體    |
| en       | English     |
| jp       | 日本語      |

## Parameters
- `language`: {"description": "语言", "options": [{"label": "臺灣正體", "value": "tw"}, {"label": "English", "value": "en"}, {"label": "日本語", "value": "jp"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.jimmyspa.com/:language/News`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "| language | Description |\n| -------- | ----------- |\n| tw       | 臺灣正體    |\n| en       | English     |\n| jp       | 日本語      |",
  "example": "/jimmyspa/news/tw",
  "heat": 9,
  "location": "news.ts",
  "maintainers": [
    "Cedaric"
  ],
  "name": "News",
  "parameters": {
    "language": {
      "description": "语言",
      "options": [
        {
          "label": "臺灣正體",
          "value": "tw"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "日本語",
          "value": "jp"
        }
      ]
    }
  },
  "path": "/news/:language",
  "radar": [
    {
      "source": [
        "www.jimmyspa.com/:language/News"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "幾米 - 最新消息(tw) - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "93099761740480512",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jimmyspa.com/tw/News",
      "title": "幾米 - 最新消息(tw)",
      "type": "feed",
      "url": "rsshub://jimmyspa/news/tw"
    }
  ],
  "view": 2
}
```
