# CrushNinja - 匿名投稿頁面

## Coverage
`index-only`

## Route
- Namespace: `crush`
- Namespace Name: `CrushNinja`
- Route Path: `/crush/pages/:id`
- Route Name: `匿名投稿頁面`
- Example: `/crush/pages/141719909033861`
- URL: `www.crush.ninja`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Tsuyumi25`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: {"description": "頁面 ID 或代稱，例如 `141719909033861` 或 `awkward87poland`"}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.crush.ninja/:locale/pages/:id`
- `target`: `/pages/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/crush/pages/141719909033861",
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "Tsuyumi25"
  ],
  "name": "匿名投稿頁面",
  "parameters": {
    "id": {
      "description": "頁面 ID 或代稱，例如 `141719909033861` 或 `awkward87poland`"
    }
  },
  "path": "/pages/:id",
  "radar": [
    {
      "source": [
        "www.crush.ninja/:locale/pages/:id"
      ],
      "target": "/pages/:id"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Anonymous submissions for the 匿名波蘭 Facebook page, powered by CrushNinja. 請仔細閱讀完粉專主頁的置頂文才投稿，請完全看清楚再來投稿。 我們這邊不是暈船勒戒所，暈船文請不要投稿 看完的可以繼續滑下去投稿了，請各位文章之中也不用感謝小編、送小編OO，… - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "192628418565219328",
      "image": "https://graph.facebook.com/298425701089585/picture?type=large",
      "ownerUserId": null,
      "siteUrl": "https://www.crush.ninja/en-us/pages/awkward87poland/",
      "title": "匿名波蘭",
      "type": "feed",
      "url": "rsshub://crush/pages/awkward87poland"
    }
  ],
  "url": "www.crush.ninja"
}
```
