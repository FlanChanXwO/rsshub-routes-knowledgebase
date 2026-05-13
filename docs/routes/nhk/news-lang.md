# NHK - WORLD-JAPAN - Top Stories

## Coverage
`index-only`

## Route
- Namespace: `nhk`
- Namespace Name: `NHK`
- Route Path: `/news/:lang?`
- Route Name: `WORLD-JAPAN - Top Stories`
- Example: `/nhk/news/en`
- URL: `www3.nhk.or.jp`
- Language: `ja`
- Categories: `traditional-media`
- Maintainers: `TonyRL, pseudoyu, cscnk52`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/nhk/news.tsx')`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "Language, see below", "options": [{"label": "العربية", "value": "ar"}, {"label": "বাংলা", "value": "bn"}, {"label": "မြန်မာဘာသာစကား", "value": "my"}, {"label": "中文（简体）", "value": "zh"}, {"label": "中文（繁體）", "value": "zt"}, {"label": "English", "value": "en"}, {"label": "Français", "value": "fr"}, {"label": "हिन्दी", "value": "hi"}, {"label": "Bahasa Indonesia", "value": "id"}, {"label": "코리언", "value": "ko"}, {"label": "فارسی", "value": "fa"}, {"label": "Português", "value": "pt"}, {"label": "Русский", "value": "ru"}, {"label": "Español", "value": "es"}, {"label": "Kiswahili", "value": "sw"}, {"label": "ภาษาไทย", "value": "th"}, {"label": "Türkçe", "value": "tr"}, {"label": "Українська", "value": "uk"}, {"label": "اردو", "value": "ur"}, {"label": "Tiếng Việt", "value": "vi"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www3.nhk.or.jp/nhkworld/:lang/news/list/`
  - `www3.nhk.or.jp/nhkworld/:lang/news/`
- `target`: `/news/:lang`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/nhk/news/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.tsx",
  "maintainers": [
    "TonyRL",
    "pseudoyu",
    "cscnk52"
  ],
  "module": "() => import('@/routes/nhk/news.tsx')",
  "name": "WORLD-JAPAN - Top Stories",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "Language, see below",
      "options": [
        {
          "label": "العربية",
          "value": "ar"
        },
        {
          "label": "বাংলা",
          "value": "bn"
        },
        {
          "label": "မြန်မာဘာသာစကား",
          "value": "my"
        },
        {
          "label": "中文（简体）",
          "value": "zh"
        },
        {
          "label": "中文（繁體）",
          "value": "zt"
        },
        {
          "label": "English",
          "value": "en"
        },
        {
          "label": "Français",
          "value": "fr"
        },
        {
          "label": "हिन्दी",
          "value": "hi"
        },
        {
          "label": "Bahasa Indonesia",
          "value": "id"
        },
        {
          "label": "코리언",
          "value": "ko"
        },
        {
          "label": "فارسی",
          "value": "fa"
        },
        {
          "label": "Português",
          "value": "pt"
        },
        {
          "label": "Русский",
          "value": "ru"
        },
        {
          "label": "Español",
          "value": "es"
        },
        {
          "label": "Kiswahili",
          "value": "sw"
        },
        {
          "label": "ภาษาไทย",
          "value": "th"
        },
        {
          "label": "Türkçe",
          "value": "tr"
        },
        {
          "label": "Українська",
          "value": "uk"
        },
        {
          "label": "اردو",
          "value": "ur"
        },
        {
          "label": "Tiếng Việt",
          "value": "vi"
        }
      ]
    }
  },
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "www3.nhk.or.jp/nhkworld/:lang/news/list/",
        "www3.nhk.or.jp/nhkworld/:lang/news/"
      ],
      "target": "/news/:lang"
    }
  ],
  "view": 0
}
```
