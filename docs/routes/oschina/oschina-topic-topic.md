# 开源中国 - 问答主题

## Coverage
`index-only`

## Route
- Namespace: `oschina`
- Namespace Name: `开源中国`
- Route Path: `/oschina/topic/:topic`
- Route Name: `问答主题`
- Example: `/oschina/topic/weekly-news`
- URL: `oschina.net`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `loveely7`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: 主题名，可从 [全部主题](https://www.oschina.net/question/topics) 进入主题页，在 URL 中找到


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
  - `oschina.net/question/topic/:topic`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/oschina/topic/weekly-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "topic.ts",
  "maintainers": [
    "loveely7"
  ],
  "name": "问答主题",
  "parameters": {
    "topic": "主题名，可从 [全部主题](https://www.oschina.net/question/topics) 进入主题页，在 URL 中找到"
  },
  "path": "/topic/:topic",
  "radar": [
    {
      "source": [
        "oschina.net/question/topic/:topic"
      ]
    }
  ],
  "topFeeds": []
}
```
