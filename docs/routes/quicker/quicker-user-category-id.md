# Quicker - 用户更新

## Coverage
`index-only`

## Route
- Namespace: `quicker`
- Namespace Name: `Quicker`
- Route Path: `/quicker/user/:category/:id`
- Route Name: `用户更新`
- Example: `/quicker/user/Actions/3-CL`
- URL: `getquicker.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `Cesaryuan, nczitzk`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
| 动作    | 子程序      | 动作单      |
| ------- | ----------- | ----------- |
| Actions | SubPrograms | ActionLists |

## Parameters
- `category`: 分类，见下表
- `id`: 用户 id，可在对应用户页 URL 中找到


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
    "programming"
  ],
  "description": "| 动作    | 子程序      | 动作单      |\n| ------- | ----------- | ----------- |\n| Actions | SubPrograms | ActionLists |",
  "example": "/quicker/user/Actions/3-CL",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "user.ts",
  "maintainers": [
    "Cesaryuan",
    "nczitzk"
  ],
  "name": "用户更新",
  "parameters": {
    "category": "分类，见下表",
    "id": "用户 id，可在对应用户页 URL 中找到"
  },
  "path": "/user/:category/:id",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "CL分享的动作 - Quicker - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "142612564736696320",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://getquicker.net/User/Actions/3-CL",
      "title": "CL分享的动作 - Quicker",
      "type": "feed",
      "url": "rsshub://quicker/user/Actions/3-CL"
    }
  ]
}
```
