# NGA - 帖子

## Coverage
`index-only`

## Route
- Namespace: `nga`
- Namespace Name: `NGA`
- Route Path: `/nga/post/:tid/:authorId?`
- Route Name: `帖子`
- Example: `/nga/post/18449558`
- URL: `bbs.nga.cn`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `xyqfer, syrinka`
- Source Location: `post.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tid`: 帖子 id, 可在帖子 URL 找到
- `authorId`: 作者 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
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
    "bbs"
  ],
  "example": "/nga/post/18449558",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 29,
  "location": "post.ts",
  "maintainers": [
    "xyqfer",
    "syrinka"
  ],
  "name": "帖子",
  "parameters": {
    "authorId": "作者 id",
    "tid": "帖子 id, 可在帖子 URL 找到"
  },
  "path": "/post/:tid/:authorId?",
  "topFeeds": [
    {
      "description": "NGA 牛找到了 在 - 上班很无聊，弄个实盘聊聊天 - 中的回复 178 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154777115123643392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nga.178.com/read.php?tid=41073656&page=120&authorid=66025368&rand=993.9206114425884#",
      "title": "NGA 牛找到了 在 - 上班很无聊，弄个实盘聊聊天 - 中的回复 178",
      "type": "feed",
      "url": "rsshub://nga/post/41073656/66025368"
    },
    {
      "description": "NGA -阿狼- 在 - 我必不是蛇年红包 - 中的回复 178 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "179409436734540800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://nga.178.com/read.php?tid=43098323&page=292&authorid=150058&rand=846.4245608288869#",
      "title": "NGA -阿狼- 在 - 我必不是蛇年红包 - 中的回复 178",
      "type": "feed",
      "url": "rsshub://nga/post/43098323/150058"
    }
  ]
}
```
