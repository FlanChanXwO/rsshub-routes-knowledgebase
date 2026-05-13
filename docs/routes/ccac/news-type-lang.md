# Macau Independent Commission Against Corruption 澳门廉政公署 - Latest News

## Coverage
`index-only`

## Route
- Namespace: `ccac`
- Namespace Name: `Macau Independent Commission Against Corruption 澳门廉政公署`
- Route Path: `/news/:type/:lang?`
- Route Name: `Latest News`
- Example: `/ccac/news/all`
- URL: `ccac.org.mo`
- Language: `zh-HK`
- Categories: `government`
- Maintainers: `linbuxiao`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/ccac/news.ts')`

## Description
Category

| All | Detected Cases | Investigation Reports or Recommendations | Annual Reports | CCAC's Updates |
| --- | -------------- | ---------------------------------------- | -------------- | -------------- |
| all | case           | Persuasion                               | AnnualReport   | PCANews        |

## Parameters
- `type`: Category
- `lang`: Language, default to `sc`. Supprot `en`(English), `sc`(Simplified Chinese), `tc`(Traditional Chinese) and `pt`(Portuguese)


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "Category\n\n| All | Detected Cases | Investigation Reports or Recommendations | Annual Reports | CCAC's Updates |\n| --- | -------------- | ---------------------------------------- | -------------- | -------------- |\n| all | case           | Persuasion                               | AnnualReport   | PCANews        |",
  "example": "/ccac/news/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "linbuxiao"
  ],
  "module": "() => import('@/routes/ccac/news.ts')",
  "name": "Latest News",
  "parameters": {
    "lang": "Language, default to `sc`. Supprot `en`(English), `sc`(Simplified Chinese), `tc`(Traditional Chinese) and `pt`(Portuguese)",
    "type": "Category"
  },
  "path": "/news/:type/:lang?"
}
```
