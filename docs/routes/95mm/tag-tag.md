# MM 范 - 标签

## Coverage
`index-only`

## Route
- Namespace: `95mm`
- Namespace Name: `MM 范`
- Route Path: `/tag/:tag`
- Route Name: `标签`
- Example: `/95mm/tag/黑丝`
- URL: `95mm.org/`
- Language: `zh-CN`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/95mm/tag.ts')`

## Description
_None_

## Parameters
- `tag`: 标签，可在对应标签页中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `95mm.org/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/95mm/tag/黑丝",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/95mm/tag.ts')",
  "name": "标签",
  "parameters": {
    "tag": "标签，可在对应标签页中找到"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "95mm.org/"
      ]
    }
  ],
  "url": "95mm.org/"
}
```
