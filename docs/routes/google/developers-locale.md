# Google - Developers Blog

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/developers/:locale?`
- Route Name: `Developers Blog`
- Example: `/google/developers/en`
- URL: `developers.googleblog.com`
- Language: `en`
- Categories: `blog`
- Maintainers: `Loongphy`
- Source Location: `developers.ts`
- Source Module: `() => import('@/routes/google/developers.ts')`

## Description
Google Developers Blog

## Parameters
- `locale`: {"default": "en", "description": "language", "options": [{"label": "English", "value": "en"}, {"label": "Español (Latam)", "value": "es"}, {"label": "Bahasa Indonesia", "value": "id"}, {"label": "日本語", "value": "ja"}, {"label": "한국어", "value": "ko"}, {"label": "Português (Brasil)", "value": "pt-br"}, {"label": "简体中文", "value": "zh-hans"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `developers.googleblog.com`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "Google Developers Blog",
  "example": "/google/developers/en",
  "location": "developers.ts",
  "maintainers": [
    "Loongphy"
  ],
  "module": "() => import('@/routes/google/developers.ts')",
  "name": "Developers Blog",
  "parameters": {
    "locale": {
      "default": "en",
      "description": "language",
      "options": [
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Español (Latam)",
          "value": "es"
        },
        {
          "label": "Bahasa Indonesia",
          "value": "id"
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
          "label": "Português (Brasil)",
          "value": "pt-br"
        },
        {
          "label": "简体中文",
          "value": "zh-hans"
        }
      ]
    }
  },
  "path": "/developers/:locale?",
  "radar": [
    {
      "source": [
        "developers.googleblog.com"
      ]
    }
  ],
  "url": "developers.googleblog.com"
}
```
