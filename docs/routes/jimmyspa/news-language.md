# 幾米 JIMMY S.P.A. Official Website - News

## Coverage
`index-only`

## Route
- Namespace: `jimmyspa`
- Namespace Name: `幾米 JIMMY S.P.A. Official Website`
- Route Path: `/news/:language`
- Route Name: `News`
- Example: `/jimmyspa/news/tw`
- URL: `www.jimmyspa.com`
- Language: `zh-TW`
- Categories: `design`
- Maintainers: `Cedaric`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/jimmyspa/news.ts')`

## Description
| language | Description |
| ---   | ---   |
| tw | 臺灣正體 |
| en | English |
| jp | 日本語 |

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
  "description": "\n| language | Description |\n| ---   | ---   |\n| tw | 臺灣正體 |\n| en | English |\n| jp | 日本語 |\n    ",
  "example": "/jimmyspa/news/tw",
  "location": "news.ts",
  "maintainers": [
    "Cedaric"
  ],
  "module": "() => import('@/routes/jimmyspa/news.ts')",
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
  "view": 2
}
```
