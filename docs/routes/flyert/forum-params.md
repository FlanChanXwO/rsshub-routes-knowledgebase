# 飞客茶馆 - 会员说

## Coverage
`index-only`

## Route
- Namespace: `flyert`
- Namespace Name: `飞客茶馆`
- Route Path: `/forum/:params{.+}?`
- Route Name: `会员说`
- Example: `/flyert/forum`
- URL: `www.flyert.com.cn`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `forum.ts`
- Source Module: `() => import('@/routes/flyert/forum.ts')`

## Description
::: tip
  若订阅 [酒店集团优惠](https://www.flyert.com.cn/forum.php?mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19)，网址为 `https://www.flyert.com.cn/forum.php?mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19`。截取 `https://www.flyert.com.cn/forum.php?` 到末尾的部分 `mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19` **进行 UrlEncode 编码** 后作为参数填入，此时路由为 [`/flyert/forum/mod%3Dforumdisplay%26sum%3Dall%26fid%3Dall%26catid%3D322%26filter%3Dsortid%26sortid%3D144%26searchsort%3D1%26youhui_type%3D226`](https://rsshub.app/flyert/forum/mod%3Dforumdisplay%26sum%3Dall%26fid%3Dall%26catid%3D322%26filter%3Dsortid%26sortid%3D144%26searchsort%3D1%26youhui_type%3D226)。
:::

## Parameters
- `params`: 参数，默认为空，可在对应分类页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.flyert.com.cn/forum.php`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n  若订阅 [酒店集团优惠](https://www.flyert.com.cn/forum.php?mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19)，网址为 `https://www.flyert.com.cn/forum.php?mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19`。截取 `https://www.flyert.com.cn/forum.php?` 到末尾的部分 `mod=forumdisplay&sum=all&fid=all&catid=322&filter=sortid&sortid=144&searchsort=1&youhui_type=19` **进行 UrlEncode 编码** 后作为参数填入，此时路由为 [`/flyert/forum/mod%3Dforumdisplay%26sum%3Dall%26fid%3Dall%26catid%3D322%26filter%3Dsortid%26sortid%3D144%26searchsort%3D1%26youhui_type%3D226`](https://rsshub.app/flyert/forum/mod%3Dforumdisplay%26sum%3Dall%26fid%3Dall%26catid%3D322%26filter%3Dsortid%26sortid%3D144%26searchsort%3D1%26youhui_type%3D226)。\n:::\n    ",
  "example": "/flyert/forum",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "forum.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/flyert/forum.ts')",
  "name": "会员说",
  "parameters": {
    "params": "参数，默认为空，可在对应分类页 URL 中找到"
  },
  "path": "/forum/:params{.+}?",
  "radar": [
    {
      "source": [
        "www.flyert.com.cn/forum.php"
      ]
    }
  ],
  "url": "www.flyert.com.cn"
}
```
