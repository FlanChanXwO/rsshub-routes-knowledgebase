# fanbox - Creator

## Coverage
`index-only`

## Route
- Namespace: `fanbox`
- Namespace Name: `fanbox`
- Route Path: `/fanbox/:creator`
- Route Name: `Creator`
- Example: `/fanbox/official`
- URL: `www.fanbox.cc`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `creator`: fanbox user name


## Features
- `requireConfig`: [{"description": "Required for private posts. Can be found in browser DevTools -> Application -> Cookies -> https://www.fanbox.cc -> FANBOXSESSID", "name": "FANBOX_SESSION_ID", "optional": true}]
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/fanbox/official",
  "features": {
    "nsfw": true,
    "requireConfig": [
      {
        "description": "Required for private posts. Can be found in browser DevTools -> Application -> Cookies -> https://www.fanbox.cc -> FANBOXSESSID",
        "name": "FANBOX_SESSION_ID",
        "optional": true
      }
    ]
  },
  "heat": 38,
  "location": "index.ts",
  "maintainers": [
    "KarasuShin",
    "pseudoyu"
  ],
  "name": "Creator",
  "parameters": {
    "creator": "fanbox user name"
  },
  "path": "/:creator",
  "topFeeds": [
    {
      "description": "特はない。 - Powered by RSSHub",
      "errorAt": "2025-11-26T09:51:52.390Z",
      "errorMessage": "[GET] \"https://api.fanbox.cc/post.info?postId=11011774\": 403 Forbidden\n",
      "id": "140056726308777984",
      "image": "https://pixiv.pximg.net/c/160x160_90_a2_g5/fanbox/public/images/user/3326223/icon/MueHg8Ixy6zLRTamiarKT8xC.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://kuromomo.fanbox.cc/",
      "title": "Fanbox - 黒猫桃園",
      "type": "feed",
      "url": "rsshub://fanbox/kuromomo"
    },
    {
      "description": "Fanbox - Feather - Powered by RSSHub",
      "errorAt": "2025-11-26T11:26:59.575Z",
      "errorMessage": "[GET] \"https://api.fanbox.cc/post.info?postId=11900940\": 403 Forbidden\n",
      "id": "82082879942475776",
      "image": "https://pixiv.pximg.net/c/160x160_90_a2_g5/fanbox/public/images/user/24059807/icon/aeWv4PxOsfgxu9I1n6OenEl5.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://feather.fanbox.cc/",
      "title": "Fanbox - Feather",
      "type": "feed",
      "url": "rsshub://fanbox/feather"
    }
  ]
}
```
