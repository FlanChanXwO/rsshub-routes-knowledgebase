# 微信小程序 - 公众号栏目 (非推送 & 历史消息)

## Coverage
`index-only`

## Route
- Namespace: `wechat`
- Namespace Name: `微信小程序`
- Route Path: `/mp/homepage/:biz/:hid/:cid?`
- Route Name: `公众号栏目 (非推送 & 历史消息)`
- Example: `/wechat/mp/homepage/MzA3MDM3NjE5NQ==/16`
- URL: `posts.careerengine.us`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `MisteryMonster`
- Source Location: `mp.ts`
- Source Module: `() => import('@/routes/wechat/mp.ts')`

## Description
只适用拥有首页模板 (分享链接带有 homepage) 的公众号。例如从公众号分享出来的链接为 `https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==&hid=4`，`biz` 为 `MzA3MDM3NjE5NQ==`，`hid` 为 `4`。

  有些页面里会有分栏， `cid` 可以通过元素选择器选中栏目查看`data-index`。如[链接](https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==&hid=4)里的 `京都职人` 栏目的 `cid` 为 `0`，`文艺时光` 栏目的 `cid` 为 `2`。如果不清楚的话最左边的栏目为`0`，其右方栏目依次递增 `1`。

## Parameters
- `biz`: 公众号id
- `hid`: 分页id
- `cid`: 页内栏目


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
  "description": "只适用拥有首页模板 (分享链接带有 homepage) 的公众号。例如从公众号分享出来的链接为 `https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==&hid=4`，`biz` 为 `MzA3MDM3NjE5NQ==`，`hid` 为 `4`。\n\n  有些页面里会有分栏， `cid` 可以通过元素选择器选中栏目查看`data-index`。如[链接](https://mp.weixin.qq.com/mp/homepage?__biz=MzA3MDM3NjE5NQ==&hid=4)里的 `京都职人` 栏目的 `cid` 为 `0`，`文艺时光` 栏目的 `cid` 为 `2`。如果不清楚的话最左边的栏目为`0`，其右方栏目依次递增 `1`。",
  "example": "/wechat/mp/homepage/MzA3MDM3NjE5NQ==/16",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mp.ts",
  "maintainers": [
    "MisteryMonster"
  ],
  "module": "() => import('@/routes/wechat/mp.ts')",
  "name": "公众号栏目 (非推送 & 历史消息)",
  "parameters": {
    "biz": "公众号id",
    "cid": "页内栏目",
    "hid": "分页id"
  },
  "path": "/mp/homepage/:biz/:hid/:cid?"
}
```
