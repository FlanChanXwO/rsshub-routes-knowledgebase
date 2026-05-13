# S&P Global - Ratings

## Coverage
`index-only`

## Route
- Namespace: `spglobal`
- Namespace Name: `S&P Global`
- Route Path: `/ratings/:language?`
- Route Name: `Ratings`
- Example: `/spglobal/ratings/en`
- URL: `www.spglobal.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `Cedaric`
- Source Location: `ratings.ts`
- Source Module: `() => import('@/routes/spglobal/ratings.ts')`

## Description
| language | Description |
| ---   | ---   |
| zh | 中文 |
| en | English |
| es | Español |
| pt | Português |
| jp | 日本語 |
| ru | Русский |
| ar | العربية |

## Parameters
- `language`: {"description": "语言", "options": [{"label": "中文", "value": "zh"}, {"label": "English", "value": "en"}, {"label": "Español", "value": "es"}, {"label": "Português", "value": "pt"}, {"label": "日本語", "value": "jp"}, {"label": "Русский", "value": "ru"}, {"label": "العربية", "value": "ar"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.spglobal.com/ratings/:language`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "\n| language | Description |\n| ---   | ---   |\n| zh | 中文 |\n| en | English |\n| es | Español |\n| pt | Português |\n| jp | 日本語 |\n| ru | Русский |\n| ar | العربية |\n    ",
  "example": "/spglobal/ratings/en",
  "location": "ratings.ts",
  "maintainers": [
    "Cedaric"
  ],
  "module": "() => import('@/routes/spglobal/ratings.ts')",
  "name": "Ratings",
  "parameters": {
    "language": {
      "description": "语言",
      "options": [
        {
          "label": "中文",
          "value": "zh"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Português",
          "value": "pt"
        },
        {
          "label": "日本語",
          "value": "jp"
        },
        {
          "label": "Русский",
          "value": "ru"
        },
        {
          "label": "العربية",
          "value": "ar"
        }
      ]
    }
  },
  "path": "/ratings/:language?",
  "radar": [
    {
      "source": [
        "www.spglobal.com/ratings/:language"
      ]
    }
  ],
  "view": 5
}
```
