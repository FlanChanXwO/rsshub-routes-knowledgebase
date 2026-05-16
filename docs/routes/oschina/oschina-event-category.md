# 开源中国 - 活动

## Coverage
`index-only`

## Route
- Namespace: `oschina`
- Namespace Name: `开源中国`
- Route Path: `/oschina/event/:category?`
- Route Name: `活动`
- Example: `/oschina/event`
- URL: `www.oschina.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `event.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [强力推荐](https://www.oschina.net/event?tab=recommend)，网址为 `https://www.oschina.net/event?tab=recommend`，请截取 `https://www.oschina.net/event?tab=` 到末尾的部分 `recommend` 作为 `category` 参数填入，此时目标路由为 [`/oschina/event/recommend`](https://rsshub.app/oschina/event/recommend)。
:::

| 强力推荐  | 最新活动 |
| --------- | -------- |
| recommend | latest   |

## Parameters
- `category`: 分类，默认为 `latest`，即最新活动，可在对应分类页 URL 中找到


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
  - `www.oschina.net`
### Rule 2
- `title`: `强力推荐`
- `source`:
  - `www.oschina.net`
- `target`: `/event/recommend`
### Rule 3
- `title`: `最新活动`
- `source`:
  - `www.oschina.net`
- `target`: `/event/latest`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "::: tip\n若订阅 [强力推荐](https://www.oschina.net/event?tab=recommend)，网址为 `https://www.oschina.net/event?tab=recommend`，请截取 `https://www.oschina.net/event?tab=` 到末尾的部分 `recommend` 作为 `category` 参数填入，此时目标路由为 [`/oschina/event/recommend`](https://rsshub.app/oschina/event/recommend)。\n:::\n\n| 强力推荐  | 最新活动 |\n| --------- | -------- |\n| recommend | latest   |",
  "example": "/oschina/event",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 3,
  "location": "event.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "活动",
  "parameters": {
    "category": "分类，默认为 `latest`，即最新活动，可在对应分类页 URL 中找到"
  },
  "path": "/event/:category?",
  "radar": [
    {
      "source": [
        "www.oschina.net"
      ]
    },
    {
      "source": [
        "www.oschina.net"
      ],
      "target": "/event/recommend",
      "title": "强力推荐"
    },
    {
      "source": [
        "www.oschina.net"
      ],
      "target": "/event/latest",
      "title": "最新活动"
    }
  ],
  "topFeeds": [
    {
      "description": "活动专区, OSCHINA 社区 - Powered by RSSHub",
      "errorAt": "2025-04-03T10:57:18.137Z",
      "errorMessage": "[POST] \"https://www.oschina.net/action/ajax/get_more_event_list\": 404 Not Found\n",
      "id": "105058878886147072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.oschina.net/event?tab=latest",
      "title": "开源活动 - OSCHINA - 中文开源技术交流社区top",
      "type": "feed",
      "url": "rsshub://oschina/event"
    }
  ],
  "url": "www.oschina.net",
  "view": 0
}
```
