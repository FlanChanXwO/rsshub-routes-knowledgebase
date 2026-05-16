# 牛客网 - 面经

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/nowcoder/experience/:tagId`
- Route Name: `面经`
- Example: `/nowcoder/experience/639?order=3&companyId=665&phaseId=0`
- URL: `nowcoder.com/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `huyyi`
- Source Location: `experience.ts`
- Source Module: `_None_`

## Description
可选参数：

- companyId：公司 id，[🔗查询链接](https://www.nowcoder.com/discuss/tag/exp), 复制打开
- order：3 - 最新；1 - 最热
- phaseId：0 - 所有；1 - 校招；2 - 实习；3 - 社招

## Parameters
- `tagId`: 职位id [🔗查询链接](https://www.nowcoder.com/profile/all-jobs)复制打开


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
  - `nowcoder.com/`
- `target`: `/experience`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "可选参数：\n\n- companyId：公司 id，[🔗查询链接](https://www.nowcoder.com/discuss/tag/exp), 复制打开\n- order：3 - 最新；1 - 最热\n- phaseId：0 - 所有；1 - 校招；2 - 实习；3 - 社招",
  "example": "/nowcoder/experience/639?order=3&companyId=665&phaseId=0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "experience.ts",
  "maintainers": [
    "huyyi"
  ],
  "name": "面经",
  "parameters": {
    "tagId": "职位id [🔗查询链接](https://www.nowcoder.com/profile/all-jobs)复制打开"
  },
  "path": "/experience/:tagId",
  "radar": [
    {
      "source": [
        "nowcoder.com/"
      ],
      "target": "/experience"
    }
  ],
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-03T00:36:33.091Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "152521497877571584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://nowcoder/experience/639"
    }
  ],
  "url": "nowcoder.com/"
}
```
