# 电鸭社区 - 工作机会

## Coverage
`index-only`

## Route
- Namespace: `eleduck`
- Namespace Name: `电鸭社区`
- Route Path: `/jobs`
- Route Name: `工作机会`
- Example: `/eleduck/jobs`
- URL: `eleduck.com/categories/5`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `sfyumi`
- Source Location: `jobs.ts`
- Source Module: `() => import('@/routes/eleduck/jobs.ts')`

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
  - `eleduck.com/categories/5`
  - `eleduck.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/eleduck/jobs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jobs.ts",
  "maintainers": [
    "sfyumi"
  ],
  "module": "() => import('@/routes/eleduck/jobs.ts')",
  "name": "工作机会",
  "parameters": {},
  "path": "/jobs",
  "radar": [
    {
      "source": [
        "eleduck.com/categories/5",
        "eleduck.com/"
      ]
    }
  ],
  "url": "eleduck.com/categories/5"
}
```
