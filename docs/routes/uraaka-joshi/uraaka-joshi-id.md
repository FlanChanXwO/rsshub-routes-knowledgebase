# 裏垢女子まとめ - User

## Coverage
`index-only`

## Route
- Namespace: `uraaka-joshi`
- Namespace Name: `裏垢女子まとめ`
- Route Path: `/uraaka-joshi/:id`
- Route Name: `User`
- Example: `/uraaka-joshi/_rrwq`
- URL: `uraaka-joshi.com/`
- Language: `_None_`
- Categories: `other`
- Maintainers: `SettingDust, Halcao`
- Source Location: `uraaka-joshi-user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: User ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `uraaka-joshi.com/:id`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/uraaka-joshi/_rrwq",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "uraaka-joshi-user.ts",
  "maintainers": [
    "SettingDust",
    "Halcao"
  ],
  "name": "User",
  "parameters": {
    "id": "User ID"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "uraaka-joshi.com/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "セルフグラビアの人。https://t.co/uaezeN1CR4 - Powered by RSSHub",
      "errorAt": "2025-05-15T09:52:55.580Z",
      "errorMessage": "Access denied (403)\n",
      "id": "75447921802487808",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.uraaka-joshi.com/user/na_na_m1218",
      "title": "奔放なナナさん (@na_na_m1218) / 裏垢女子まとめ",
      "type": "feed",
      "url": "rsshub://uraaka-joshi/na_na_m1218"
    },
    {
      "description": "🦭飢えてる上に肥えてるね(FEVER) - Powered by RSSHub",
      "errorAt": "2025-05-15T02:27:40.817Z",
      "errorMessage": "Access denied (403)\n",
      "id": "72930351635651584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.uraaka-joshi.com/user/_rrwq",
      "title": "あくめろさん (@_rrwq) / 裏垢女子まとめ",
      "type": "feed",
      "url": "rsshub://uraaka-joshi/_rrwq"
    }
  ],
  "url": "uraaka-joshi.com/"
}
```
