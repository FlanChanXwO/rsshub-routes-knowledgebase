# CosplayTele - Tag

## Coverage
`index-only`

## Route
- Namespace: `cosplaytele`
- Namespace Name: `CosplayTele`
- Route Path: `/cosplaytele/tag/:tag`
- Route Name: `Tag`
- Example: `/cosplaytele/tag/aqua`
- URL: `cosplaytele.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Tag


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
  - `cosplaytele.com/tag/:tag`
- `target`: `/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/cosplaytele/tag/aqua",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 86,
  "location": "tag.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Tag",
  "parameters": {
    "tag": "Tag"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "cosplaytele.com/tag/:tag"
      ],
      "target": "/tag/:tag"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "CosplayTele - Tag: aqua - Powered by RSSHub",
      "errorAt": "2026-07-15T05:16:59.547Z",
      "errorMessage": "Failed to fetch\nFailed to fetch\n",
      "id": "115641530793657344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cosplaytele.com/tag/aqua/",
      "title": "CosplayTele - Tag: aqua",
      "type": "feed",
      "url": "rsshub://cosplaytele/tag/aqua"
    },
    {
      "description": "CosplayTele - Tag: sono-bisque-doll - Powered by RSSHub",
      "errorAt": "2026-07-15T05:31:00.622Z",
      "errorMessage": "[GET] \"https://cosplaytele.com/tag/sono-bisque-doll/\": <no response> Number of requests reached it's maximum 4800\nFailed to fetch\n",
      "id": "121742107387352145",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cosplaytele.com/tag/sono-bisque-doll/",
      "title": "CosplayTele - Tag: sono-bisque-doll",
      "type": "feed",
      "url": "rsshub://cosplaytele/tag/sono-bisque-doll"
    }
  ],
  "url": "cosplaytele.com/"
}
```
