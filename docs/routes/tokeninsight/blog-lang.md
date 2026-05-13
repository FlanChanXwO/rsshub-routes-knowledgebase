# TokenInsight - Blogs

## Coverage
`index-only`

## Route
- Namespace: `tokeninsight`
- Namespace Name: `TokenInsight`
- Route Path: `/blog/:lang?`
- Route Name: `Blogs`
- Example: `/tokeninsight/blog/en`
- URL: `tokeninsight.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `fuergaosi233`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/tokeninsight/blog.ts')`

## Description
_None_

## Parameters
- `lang`: Language, see below, Chinese by default


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
  - `tokeninsight.com/:lang/blogs`
- `target`: `/blog/:lang`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/tokeninsight/blog/en",
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
    "fuergaosi233"
  ],
  "module": "() => import('@/routes/tokeninsight/blog.ts')",
  "name": "Blogs",
  "parameters": {
    "lang": "Language, see below, Chinese by default"
  },
  "path": "/blog/:lang?",
  "radar": [
    {
      "source": [
        "tokeninsight.com/:lang/blogs"
      ],
      "target": "/blog/:lang"
    }
  ]
}
```
