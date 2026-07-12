# National Cheng Kung University - Phys News

## Coverage
`index-only`

## Route
- Namespace: `ncku`
- Namespace Name: `National Cheng Kung University`
- Route Path: `/ncku/phys/:catagory?`
- Route Name: `Phys News`
- Example: `/ncku/phys/_all`
- URL: `www.ncku.edu.tw`
- Language: `_None_`
- Categories: `university`
- Maintainers: `simbafs`
- Source Location: `phys.ts`
- Source Module: `_None_`

## Description
| 分類               | catagory              |
| ------------------ | --------------------- |
| 物理系             | 24                    |
| 獎助學金           | scholarship           |
| 招生與錄取報到     | admission             |
| 助教公告           | course-announcement   |
| 大學部             | bachelor-announcement |
| 研究所             | master-announcement   |
| 畢業離校           | graduation            |
| 學生手冊與新生入學 | student-guide         |
| 榮譽榜             | honor                 |
| 求才公告           | career                |
| 其他               | others                |
| 所有訊息           | \_all                 |

## Parameters
- `catagory`: catagory, default is _all


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
  - `phys.ncku.edu.tw/news/`
- `target`: `/phys/_all`
### Rule 2
- `source`:
  - `phys.ncku.edu.tw/news/:catagory/`
- `target`: `/phys/:catagory`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分類               | catagory              |\n| ------------------ | --------------------- |\n| 物理系             | 24                    |\n| 獎助學金           | scholarship           |\n| 招生與錄取報到     | admission             |\n| 助教公告           | course-announcement   |\n| 大學部             | bachelor-announcement |\n| 研究所             | master-announcement   |\n| 畢業離校           | graduation            |\n| 學生手冊與新生入學 | student-guide         |\n| 榮譽榜             | honor                 |\n| 求才公告           | career                |\n| 其他               | others                |\n| 所有訊息           | \\_all                 |",
  "example": "/ncku/phys/_all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "phys.ts",
  "maintainers": [
    "simbafs"
  ],
  "name": "Phys News",
  "parameters": {
    "catagory": "catagory, default is _all"
  },
  "path": "/phys/:catagory?",
  "radar": [
    {
      "source": [
        "phys.ncku.edu.tw/news/"
      ],
      "target": "/phys/_all"
    },
    {
      "source": [
        "phys.ncku.edu.tw/news/:catagory/"
      ],
      "target": "/phys/:catagory"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "成大物理系公告 - 所有訊息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71366587573125120",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://phys.ncku.edu.tw/news/",
      "title": "成大物理系公告 - 所有訊息",
      "type": "feed",
      "url": "rsshub://ncku/phys/_all"
    }
  ]
}
```
