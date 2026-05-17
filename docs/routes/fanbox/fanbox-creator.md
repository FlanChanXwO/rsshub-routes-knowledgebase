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
      "description": "这里是鬼针草！每个月我都会更新一幅白丝、黑丝题材的插图的，尺度在r15，谢谢大家的支持！ - Powered by RSSHub",
      "errorAt": "2025-11-26T15:22:23.460Z",
      "errorMessage": "[GET] \"https://api.fanbox.cc/post.info?postId=11755600\": 403 Forbidden\n[GET] \"https://api.fanbox.cc/post.info?postId=11594889\": 403 Forbidden\n",
      "id": "140054677210474496",
      "image": "https://pixiv.pximg.net/c/160x160_90_a2_g5/fanbox/public/images/user/6049901/icon/FQky4DosFQb4M2L1WKK42DQ6.jpeg",
      "ownerUserId": null,
      "siteUrl": "https://szcb911.fanbox.cc/",
      "title": "Fanbox - 鬼針草",
      "type": "feed",
      "url": "rsshub://fanbox/szcb911"
    }
  ]
}
```
