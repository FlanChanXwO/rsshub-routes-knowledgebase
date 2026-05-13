# 新浪 - 新浪体育

## Coverage
`index-only`

## Route
- Namespace: `sina`
- Namespace Name: `新浪`
- Route Path: `/sina/sports/:type?`
- Route Name: `新浪体育`
- Example: `/sports`
- URL: `finance.sina.com.cn`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `nczitzk`
- Source Location: `sports.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 类别


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/sports",
  "heat": 1,
  "location": "sports.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "新浪体育",
  "parameters": {
    "type": "类别"
  },
  "path": "/sports/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 404 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "关注排坛大事 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "197554467454926851",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://sports.sina.com.cn/others/volley.shtml",
      "title": "排球 - 新浪体育",
      "type": "feed",
      "url": "rsshub://sina/sports/volley"
    }
  ]
}
```
