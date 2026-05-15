# 开源中国 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `oschina`
- Namespace Name: `开源中国`
- Route Path: `/oschina/u/:uid`
- Route Name: `用户博客`
- Example: `/oschina/u/3920392`
- URL: `oschina.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `dxmpalb`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `uid`: 用户 id，可通过查看用户博客网址得到，以 u/数字结尾，数字即为 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `my.oschina.net/u/:uid`
  - `my.oschina.net/:uid`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/oschina/u/3920392",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "user.ts",
  "maintainers": [
    "dxmpalb"
  ],
  "name": "用户博客",
  "parameters": {
    "uid": "用户 id，可通过查看用户博客网址得到，以 u/数字结尾，数字即为 id"
  },
  "path": "/u/:uid",
  "radar": [
    {
      "source": [
        "my.oschina.net/u/:uid",
        "my.oschina.net/:uid"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "聚焦系统技术领域，分享前沿技术动态、技术创新与实践、行业技术热点分析。 - Powered by RSSHub",
      "errorAt": "2026-05-13T19:08:56.682Z",
      "errorMessage": "[GET] \"https://apiv1.oschina.net/oschinapi/blog/otherUser/web?userId=6150560&pageNum=1&pageSize=10\": 504 Gateway Time-out\n",
      "id": "56284523609749504",
      "image": "https://oscimg.oschina.net//oscnet/up-603af150a079285ac13aca510cba6c01.jpg",
      "ownerUserId": null,
      "siteUrl": "https://my.oschina.net/u/6150560",
      "title": "字节跳动SYS Tech的博客",
      "type": "feed",
      "url": "rsshub://oschina/u/6150560"
    }
  ]
}
```
