# Hedwig - Posts

## Coverage
`index-only`

## Route
- Namespace: `hedwig`
- Namespace Name: `Hedwig`
- Route Path: `/hedwig/posts/:site`
- Route Name: `Posts`
- Example: `/posts/walnut`
- URL: `hedwig.pub`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `zwithz, GetToSet`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `site`: 站点名，原则上只要是 `{site}.hedwig.pub` 都可以匹配


## Features
- `supportRadar`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/posts/walnut",
  "features": {
    "supportRadar": false
  },
  "heat": 17,
  "location": "posts.ts",
  "maintainers": [
    "zwithz",
    "GetToSet"
  ],
  "name": "Posts",
  "parameters": {
    "site": "站点名，原则上只要是 `{site}.hedwig.pub` 都可以匹配"
  },
  "path": "/posts/:site",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 404 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "关注互联网、效率工具与生活方式，一起脱离重力束缚 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "151609591425263616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://walnut.hedwig.pub/",
      "title": "地心引力",
      "type": "feed",
      "url": "rsshub://hedwig/posts/walnut"
    },
    {
      "description": "分享个体见闻，探索内心宇宙 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "151650896037741568",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://cbyd.hedwig.pub/",
      "title": "🏰城堡阅读📚",
      "type": "feed",
      "url": "rsshub://hedwig/posts/cbyd"
    }
  ],
  "url": "hedwig.pub",
  "view": 0
}
```
