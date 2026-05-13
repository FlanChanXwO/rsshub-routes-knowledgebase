# Followin - Tag

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/tag/:tagId/:lang?`
- Route Name: `Tag`
- Example: `/followin/tag/177008`
- URL: `followin.io`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/followin/tag.ts')`

## Description
_None_

## Parameters
- `tagId`: Tag ID, can be found in URL
- `lang`: Language, see table above, `en` by default


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
  - `followin.io/:lang/tag/:tagId`
  - `followin.io/tag/:tagId`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/followin/tag/177008",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/followin/tag.ts')",
  "name": "Tag",
  "parameters": {
    "lang": "Language, see table above, `en` by default",
    "tagId": "Tag ID, can be found in URL"
  },
  "path": "/tag/:tagId/:lang?",
  "radar": [
    {
      "source": [
        "followin.io/:lang/tag/:tagId",
        "followin.io/tag/:tagId"
      ]
    }
  ]
}
```
