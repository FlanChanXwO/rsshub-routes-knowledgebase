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
  "heat": 19241,
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
      "description": "李雅英 LeeAYoung 📩 business@yyyoungggggg.com ⚾️ @fubon_guardians_official 🏀 @fubon_braves_official 🌊 浪Live_2929 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67858616875452416",
      "image": "https://media.picnob.info/get?url=https://scontent-cph2-1.cdninstagram.com/v/t51.82787-19/657853704_18533228257068477_1620498928579652346_n.jpg?stp=dst-jpg_s320x320_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby44MjguYzIifQ&_nc_ht=scontent-cph2-1.cdninstagram.com&_nc_cat=109&_nc_oc=Q6cZ2gF0LeE9FRyDMn2LCLbUcG0iHIeNbPqi-uGIGdxR0D3Jwvedy01tOEeBjVGaUwC-3KA&_nc_ohc=RqkRNhZElvwQ7kNvwFPfTmg&_nc_gid=4D26HXkR5YHl0TIo2HuOBg&edm=AOQ1c0wBAAAA&ccb=7-5&ig_cache_key=GAgNNie9xc1239dBAPoq5JQwK30WbmNDAQAB3203200j-ccb7-5&oh=00_Af52e-cn7SPJfHqGx-6bjqocMED0guC1f7oPFszezCLDDg&oe=69FC6411&_nc_sid=8b3546",
      "ownerUserId": null,
      "siteUrl": "https://www.instagram.com/yyyoungggggg/",
      "title": "이아영 (@yyyoungggggg) public posts - Picnob",
      "type": "feed",
      "url": "rsshub://picnob.info/user/yyyoungggggg"
    }
  ],
  "url": "picnob.info",
  "view": 2
}
```
