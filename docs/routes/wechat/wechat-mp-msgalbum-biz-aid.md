# 微信小程序 - 公众号文章话题 Tag

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/wechat/mp/msgalbum/:biz/:aid`
- Route Name: `公众号文章话题 Tag`
- Example: `/wechat/mp/msgalbum/MzA3MDM3NjE5NQ==/1375870284640911361`
- URL: `posts.careerengine.us`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `MisteryMonster`
- Source Location: `msgalbum.ts`
- Source Module: `_None_`

## Description
一些公众号（如看理想）会在微信文章里添加 Tag ，点入 Tag 的链接如 `https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzA3MDM3NjE5NQ==&action=getalbum&album_id=1375870284640911361`，其中`biz` 为 `MzA3MDM3NjE5NQ==`，`aid` 为 `1375870284640911361`。

## Parameters
- `biz`: 公众号id
- `aid`: Tag id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "一些公众号（如看理想）会在微信文章里添加 Tag ，点入 Tag 的链接如 `https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzA3MDM3NjE5NQ==&action=getalbum&album_id=1375870284640911361`，其中`biz` 为 `MzA3MDM3NjE5NQ==`，`aid` 为 `1375870284640911361`。",
  "example": "/wechat/mp/msgalbum/MzA3MDM3NjE5NQ==/1375870284640911361",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 865,
  "location": "msgalbum.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "name": "公众号文章话题 Tag",
  "parameters": {
    "aid": "Tag id",
    "biz": "公众号id"
  },
  "path": "/mp/msgalbum/:biz/:aid",
  "topFeeds": [
    {
      "description": "PaperAgent|LLM热点Paper - Powered by RSSHub",
      "errorAt": "2025-07-23T12:13:10.406Z",
      "errorMessage": "wechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HJy4DWqj_Z45pH3coCluZBUELphxL_6qrMIOygrn&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzk0MTYzMzMxMA%3D%3D%26mid%3D2247507399%26idx%3D1%26sn%3D0498f7ea08368ae16048fdb9b3a6f20d\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HJ64DWqjL_TfK60xLAIWZPp5X4Tj5mtB0ZRP89zs&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzk0MTYzMzMxMA%3D%3D%26mid%3D2247507484%26idx%3D2%26sn%3Dccd1459e08fb75531b73908ef0d683ae\nFailed to fetch\n",
      "id": "55818057211386897",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mp.weixin.qq.com/mp/appmsgalbum?__biz=Mzk0MTYzMzMxMA&action=getalbum&album_id=3256352785986404355",
      "title": "PaperAgent|LLM热点Paper",
      "type": "feed",
      "url": "rsshub://wechat/mp/msgalbum/Mzk0MTYzMzMxMA/3256352785986404355"
    },
    {
      "description": "Ots安全|威胁分析 - Powered by RSSHub",
      "errorAt": "2025-07-23T05:08:30.331Z",
      "errorMessage": "wechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HDu6D2qjVzQAs2dqPKJ2H1ByHCQaraSRBLRK8O5i&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzAxMjYyMzkwOA%3D%3D%26mid%3D2247534948%26idx%3D2%26sn%3D98f8b22608d05e9c87cc7cc810e30af4\nwechat-mp: request blocked by WAF: : ， . Video Mini Program ...: https://mp.weixin.qq.com/mp/wappoc_appmsgcaptcha?poc_token=HGm6D2qjNx5pR6_t7N14o2cwd3vdmRXb4gs2TP4M&target_url=https%3A%2F%2Fmp.weixin.qq.com%2Fs%3F__biz%3DMzAxMjYyMzkwOA%3D%3D%26mid%3D2247534948%26idx%3D2%26sn%3D98f8b22608d05e9c87cc7cc810e30af4\n",
      "id": "57679399689810944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzAxMjYyMzkwOA==&action=getalbum&album_id=2839958662130647042",
      "title": "Ots安全|威胁分析",
      "type": "feed",
      "url": "rsshub://wechat/mp/msgalbum/MzAxMjYyMzkwOA==/2839958662130647042"
    }
  ]
}
```
