# Hangzhou People's Government - 司局通知

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/moe/s78/:column`
- Route Name: `司局通知`
- Example: `/gov/moe/s78/A13`
- URL: `hangzhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `TonyRL`
- Source Location: `moe/s78.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `column`: 司局 ID，可在 URL 找到


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
  - `moe.gov.cn/s78/:column/tongzhi`
  - `moe.gov.cn/s78/:column`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/moe/s78/A13",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "moe/s78.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "司局通知",
  "parameters": {
    "column": "司局 ID，可在 URL 找到"
  },
  "path": "/moe/s78/:column",
  "radar": [
    {
      "source": [
        "moe.gov.cn/s78/:column/tongzhi",
        "moe.gov.cn/s78/:column"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "高等教育司 - 司局通知 - 中华人民共和国教育部政府门户网站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92474699286284288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.moe.gov.cn/s78/A08/tongzhi/",
      "title": "高等教育司 - 司局通知 - 中华人民共和国教育部政府门户网站",
      "type": "feed",
      "url": "rsshub://gov/moe/s78/A08"
    },
    {
      "description": "社会科学司 - 司局通知 - 中华人民共和国教育部政府门户网站 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75853854808636416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.moe.gov.cn/s78/A13/tongzhi/",
      "title": "社会科学司 - 司局通知 - 中华人民共和国教育部政府门户网站",
      "type": "feed",
      "url": "rsshub://gov/moe/s78/A13"
    }
  ]
}
```
