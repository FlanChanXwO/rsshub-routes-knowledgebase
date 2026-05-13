# Tumblr - Tagged Posts

## Coverage
`index-only`

## Route
- Namespace: `tumblr`
- Namespace Name: `Tumblr`
- Route Path: `/tagged/:tag`
- Route Name: `Tagged Posts`
- Example: `/tumblr/tagged/nature`
- URL: `tumblr.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `PolarisStarnor`
- Source Location: `tagged.ts`
- Source Module: `() => import('@/routes/tumblr/tagged.ts')`

## Description
_None_

## Parameters
- `tag`: Tag name (see `https://www.tumblr.com/docs/en/api/v2#tagged--get-posts-with-tag`)


## Features
- `requireConfig`: [{"description": "Please see above for details.", "name": "TUMBLR_CLIENT_ID"}, {"description": "Please see above for details.", "name": "TUMBLR_CLIENT_SECRET"}, {"description": "Please see above for details.", "name": "TUMBLR_REFRESH_TOKEN"}]
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
    "social-media"
  ],
  "example": "/tumblr/tagged/nature",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_CLIENT_ID"
      },
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_CLIENT_SECRET"
      },
      {
        "description": "Please see above for details.",
        "name": "TUMBLR_REFRESH_TOKEN"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tagged.ts",
  "maintainers": [
    "PolarisStarnor"
  ],
  "module": "() => import('@/routes/tumblr/tagged.ts')",
  "name": "Tagged Posts",
  "parameters": {
    "tag": "Tag name (see `https://www.tumblr.com/docs/en/api/v2#tagged--get-posts-with-tag`)"
  },
  "path": "/tagged/:tag",
  "radar": []
}
```
