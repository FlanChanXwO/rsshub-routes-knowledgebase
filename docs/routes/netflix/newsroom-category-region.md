# Netflix - Newsroom

## Coverage
`index-only`

## Route
- Namespace: `netflix`
- Namespace Name: `Netflix`
- Route Path: `/newsroom/:category?/:region?`
- Route Name: `Newsroom`
- Example: `/netflix/newsroom`
- URL: `about.netflix.com/`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `newsroom.ts`
- Source Module: `() => import('@/routes/netflix/newsroom.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "all", "description": "Category", "options": [{"label": "All News", "value": "all"}, {"label": "Business", "value": "business"}, {"label": "Entertainment", "value": "entertainment"}, {"label": "Product", "value": "product"}, {"label": "Social Impact", "value": "impact"}]}
- `region`: {"default": "en", "description": "Region, can be found in the region URL", "options": [{"label": "اللغة العربية", "value": "ar"}, {"label": "Deutsch", "value": "de"}, {"label": "Ελληνικά", "value": "el"}, {"label": "English", "value": "en"}, {"label": "Español (LatAm)", "value": "es"}, {"label": "Español (España)", "value": "es-es"}, {"label": "Français", "value": "fr"}, {"label": "Bahasa Indonesia", "value": "id"}, {"label": "Italiano", "value": "it"}, {"label": "日本語", "value": "ja"}, {"label": "한국어", "value": "ko"}, {"label": "Polski", "value": "pl"}, {"label": "Português (Brasil)", "value": "pt-br"}, {"label": "Português (Portugal)", "value": "pt-pt"}, {"label": "Română", "value": "ro"}, {"label": "русский", "value": "ru"}, {"label": "ไทย", "value": "th"}, {"label": "Türkçe", "value": "tr"}, {"label": "Tiếng Việt", "value": "vi"}, {"label": "简体中文", "value": "zh-hans"}, {"label": "繁體中文", "value": "zh-hant"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `about.netflix.com/:region/newsroom`
### Rule 2
- `source`:
  - `netflix.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/netflix/newsroom",
  "location": "newsroom.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/netflix/newsroom.ts')",
  "name": "Newsroom",
  "parameters": {
    "category": {
      "default": "all",
      "description": "Category",
      "options": [
        {
          "label": "All News",
          "value": "all"
        },
        {
          "label": "Business",
          "value": "business"
        },
        {
          "label": "Entertainment",
          "value": "entertainment"
        },
        {
          "label": "Product",
          "value": "product"
        },
        {
          "label": "Social Impact",
          "value": "impact"
        }
      ]
    },
    "region": {
      "default": "en",
      "description": "Region, can be found in the region URL",
      "options": [
        {
          "label": "اللغة العربية",
          "value": "ar"
        },
        {
          "label": "Deutsch",
          "value": "de"
        },
        {
          "label": "Ελληνικά",
          "value": "el"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Español (LatAm)",
          "value": "es"
        },
        {
          "label": "Español (España)",
          "value": "es-es"
        },
        {
          "label": "Français",
          "value": "fr"
        },
        {
          "label": "Bahasa Indonesia",
          "value": "id"
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
          "label": "한국어",
          "value": "ko"
        },
        {
          "label": "Polski",
          "value": "pl"
        },
        {
          "label": "Português (Brasil)",
          "value": "pt-br"
        },
        {
          "label": "Português (Portugal)",
          "value": "pt-pt"
        },
        {
          "label": "Română",
          "value": "ro"
        },
        {
          "label": "русский",
          "value": "ru"
        },
        {
          "label": "ไทย",
          "value": "th"
        },
        {
          "label": "Türkçe",
          "value": "tr"
        },
        {
          "label": "Tiếng Việt",
          "value": "vi"
        },
        {
          "label": "简体中文",
          "value": "zh-hans"
        },
        {
          "label": "繁體中文",
          "value": "zh-hant"
        }
      ]
    }
  },
  "path": "/newsroom/:category?/:region?",
  "radar": [
    {
      "source": [
        "about.netflix.com/:region/newsroom"
      ]
    },
    {
      "source": [
        "netflix.com"
      ]
    }
  ],
  "url": "about.netflix.com/"
}
```
