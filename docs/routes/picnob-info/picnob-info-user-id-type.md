# Instagram - User Profile - Picnob.info

## Coverage
`index-only`

## Route
- Namespace: `picnob.info`
- Namespace Name: `Instagram`
- Route Path: `/picnob.info/user/:id/:type?`
- Route Name: `User Profile - Picnob.info`
- Example: `/picnob.info/user/xlisa_olivex`
- URL: `picnob.info`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Instagram id
- `type`: {"default": "posts", "description": "Type of profile page", "options": [{"label": "Posts", "value": "posts"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "social-media",
    "popular"
  ],
  "example": "/picnob.info/user/xlisa_olivex",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 16969,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Profile - Picnob.info",
  "parameters": {
    "id": "Instagram id",
    "type": {
      "default": "posts",
      "description": "Type of profile page",
      "options": [
        {
          "label": "Posts",
          "value": "posts"
        }
      ]
    }
  },
  "path": "/user/:id/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 301 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "谢谢你的关注 - Powered by RSSHub",
      "errorAt": "2024-12-12T00:24:16.873Z",
      "errorMessage": "503 Service Unavailable\n",
      "id": "60491404833914880",
      "image": "https://sp1.piokok.com/a/a_44102649694_28441710182871616169_e322c99cf726f66957cffc3fbc34e99c.jpg?v/t51.2885-19/123266262_3067125136865188_9063518416041685664_n.jpg?stp=dst-jpg_e0_s150x150_tt6&_nc_ht=scontent-mad2-1.cdninstagram.com&_nc_cat=104&_nc_ohc=ls01UnhNlAsQ7kNvgHGhRik&_nc_gid=ac3e89eb9bcf441d8fa35e01494a1dcc&edm=AOQ1c0wBAAAA&ccb=7-5&oh=00_AYC-P4Uvy4czlrklmfyZy5avLFEvV_EIc64uwpwcRTlGrQ&oe=674C0FB5&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.piokok.com/profile/azhu_a1997/",
      "title": "阿朱啊 (@azhu_a1997) - Picnob",
      "type": "feed",
      "url": "rsshub://picnob/user/azhu_a1997"
    },
    {
      "description": "身長高そうって言われるけど153cmです ファンマーク👸💜🐶 リンクはファンクラブと出演作品一覧‪‪❤︎‬ - Powered by RSSHub",
      "errorAt": "2026-05-02T22:32:03.996Z",
      "errorMessage": "Failed to fetch\n",
      "id": "68847339940895744",
      "image": "https://media.picnob.info/get?url=https://scontent-cph2-1.cdninstagram.com/v/t51.82787-19/581178426_18544063333011928_7335411493667389019_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby42MzAuYzIifQ&_nc_ht=scontent-cph2-1.cdninstagram.com&_nc_cat=104&_nc_oc=Q6cZ2gEyEQAMQBbvcbI59o1KH-9DzJWHnR54ftOw9dd25BS4L0bHwEWSsiNVGt0FH0MK8r4&_nc_ohc=QrBuoPzTKqkQ7kNvwHR6av6&_nc_gid=-6_75qdWylpQ7JDykJi3OQ&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GDoUpCLYEagzuuFBAFu_XInjncxlbmNDAQAB3203200j-ccb7-5&oh=00_Af2BI932CbuJxyL3w8QyQ6qDf5SVwKklQs5ZIDavTHj0bg&oe=69F11A85&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/riri_nanatsumori/",
      "title": "七ツ森りり (@riri_nanatsumori) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/riri_nanatsumori"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
