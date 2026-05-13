# East China Normal University 华东师范大学 - ACM Online-Judge contests list

## Coverage
`index-only`

## Route
- Namespace: `ecnu`
- Namespace Name: `East China Normal University 华东师范大学`
- Route Path: `/acm/contest/:category?`
- Route Name: `ACM Online-Judge contests list`
- Example: `/ecnu/acm/contest/public`
- URL: `acm.ecnu.edu.cn/contest/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `a180285`
- Source Location: `contest.tsx`
- Source Module: `() => import('@/routes/ecnu/contest.tsx')`

## Description
_None_

## Parameters
- `category`: category is optional, default is all, use `public` for public only contests


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
  - `acm.ecnu.edu.cn/contest/`
  - `acm.ecnu.edu.cn/`
- `target`: `/acm/contest/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/ecnu/acm/contest/public",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "contest.tsx",
  "maintainers": [
    "a180285"
  ],
  "module": "() => import('@/routes/ecnu/contest.tsx')",
  "name": "ACM Online-Judge contests list",
  "parameters": {
    "category": "category is optional, default is all, use `public` for public only contests"
  },
  "path": "/acm/contest/:category?",
  "radar": [
    {
      "source": [
        "acm.ecnu.edu.cn/contest/",
        "acm.ecnu.edu.cn/"
      ],
      "target": "/acm/contest/"
    }
  ],
  "url": "acm.ecnu.edu.cn/contest/"
}
```
