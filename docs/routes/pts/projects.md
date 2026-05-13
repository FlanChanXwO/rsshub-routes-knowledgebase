# 公視新聞網 - 數位敘事

## Coverage
`index-only`

## Route
- Namespace: `pts`
- Namespace Name: `公視新聞網`
- Route Path: `/projects`
- Route Name: `數位敘事`
- Example: `/pts/projects`
- URL: `news.pts.org.tw/projects`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `projects.ts`
- Source Module: `() => import('@/routes/pts/projects.ts')`

## Description
_None_

## Parameters
_None_


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
  - `news.pts.org.tw/projects`
  - `news.pts.org.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/pts/projects",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "projects.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/pts/projects.ts')",
  "name": "數位敘事",
  "parameters": {},
  "path": "/projects",
  "radar": [
    {
      "source": [
        "news.pts.org.tw/projects",
        "news.pts.org.tw/"
      ]
    }
  ],
  "url": "news.pts.org.tw/projects"
}
```
