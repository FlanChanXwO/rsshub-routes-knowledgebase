# Node.js - News

## Coverage
`index-only`

## Route
- Namespace: `nodejs`
- Namespace Name: `Node.js`
- Route Path: `/blog/:language?`
- Route Name: `News`
- Example: `/nodejs/blog`
- URL: `nodejs.org`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/nodejs/blog.ts')`

## Description
Official RSS Source: https://nodejs.org/en/feed/blog.xml

| العربية | Catalan | Deutsch | Español | زبان فارسی |
| ------- | ------- | ------- | ------- | ---------- |
| ar      | ca      | de      | es      | fa         |

| Français | Galego | Italiano | 日本語 | 한국어 |
| -------- | ------ | -------- | ------ | ------ |
| fr       | gl     | it       | ja     | ko     |

| Português do Brasil | limba română | Русский | Türkçe | Українська |
| ------------------- | ------------ | ------- | ------ | ---------- |
| pt-br               | ro           | ru      | tr     | uk         |

| 简体中文 | 繁體中文 |
| -------- | -------- |
| zh-cn    | zh-tw    |

## Parameters
- `language`: Language, see below, en by default


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
  - `nodejs.org/:language/blog`
  - `nodejs.org/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Official RSS Source: https://nodejs.org/en/feed/blog.xml\n\n| العربية | Catalan | Deutsch | Español | زبان فارسی |\n| ------- | ------- | ------- | ------- | ---------- |\n| ar      | ca      | de      | es      | fa         |\n\n| Français | Galego | Italiano | 日本語 | 한국어 |\n| -------- | ------ | -------- | ------ | ------ |\n| fr       | gl     | it       | ja     | ko     |\n\n| Português do Brasil | limba română | Русский | Türkçe | Українська |\n| ------------------- | ------------ | ------- | ------ | ---------- |\n| pt-br               | ro           | ru      | tr     | uk         |\n\n| 简体中文 | 繁體中文 |\n| -------- | -------- |\n| zh-cn    | zh-tw    |",
  "example": "/nodejs/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/nodejs/blog.ts')",
  "name": "News",
  "parameters": {
    "language": "Language, see below, en by default"
  },
  "path": "/blog/:language?",
  "radar": [
    {
      "source": [
        "nodejs.org/:language/blog",
        "nodejs.org/"
      ]
    }
  ]
}
```
