# 幾米 JIMMY S.P.A. Official Website - Books

## Coverage
`index-only`

## Route
- Namespace: `jimmyspa`
- Namespace Name: `幾米 JIMMY S.P.A. Official Website`
- Route Path: `/books/:language`
- Route Name: `Books`
- Example: `/jimmyspa/books/tw`
- URL: `www.jimmyspa.com`
- Language: `zh-TW`
- Categories: `design`
- Maintainers: `Cedaric`
- Source Location: `books.ts`
- Source Module: `() => import('@/routes/jimmyspa/books.ts')`

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
  - `www.jimmyspa.com/:language/Books`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "\n| language | Description |\n| ---   | ---   |\n| tw | 臺灣正體 |\n| en | English |\n| jp | 日本語 |\n    ",
  "example": "/jimmyspa/books/tw",
  "location": "books.ts",
  "maintainers": [
    "Cedaric"
  ],
  "module": "() => import('@/routes/jimmyspa/books.ts')",
  "name": "Books",
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
  "path": "/books/:language",
  "radar": [
    {
      "source": [
        "www.jimmyspa.com/:language/Books"
      ]
    }
  ],
  "view": 0
}
```
