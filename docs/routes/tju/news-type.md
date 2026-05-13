# Tianjin University 天津大学 - News

## Coverage
`index-only`

## Route
- Namespace: `tju`
- Namespace Name: `Tianjin University 天津大学`
- Route Path: `/news/:type?`
- Route Name: `News`
- Example: `/tju/news/focus`
- URL: `cic.tju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `AlanZeng423, SuperPung`
- Source Location: `news/index.ts`
- Source Module: `() => import('@/routes/tju/news/index.ts')`

## Description
| Focus on TJU | General News | Internal News | Media Report | Pictures of TJU |
| :----------: | :----------: | :-----------: | :----------: | :-------------: |
|     focus    |    general   |    internal   |     media    |     picture     |

## Parameters
- `type`: default `focus`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
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
    "university"
  ],
  "description": "| Focus on TJU | General News | Internal News | Media Report | Pictures of TJU |\n| :----------: | :----------: | :-----------: | :----------: | :-------------: |\n|     focus    |    general   |    internal   |     media    |     picture     |",
  "example": "/tju/news/focus",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news/index.ts",
  "maintainers": [
    "AlanZeng423",
    "SuperPung"
  ],
  "module": "() => import('@/routes/tju/news/index.ts')",
  "name": "News",
  "parameters": {
    "type": "default `focus`"
  },
  "path": "/news/:type?"
}
```
