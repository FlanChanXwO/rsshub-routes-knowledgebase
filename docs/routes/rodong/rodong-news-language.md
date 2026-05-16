# Rodong Sinmun 劳动新闻 - News

## Coverage
`index-only`

## Route
- Namespace: `rodong`
- Namespace Name: `Rodong Sinmun 劳动新闻`
- Route Path: `/rodong/news/:language?`
- Route Name: `News`
- Example: `/rodong/news`
- URL: `rodong.rep.kp/cn/index.php`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 조선어 | English | 中文 |
| ------ | ------- | ---- |
| ko     | en      | cn   |

## Parameters
- `language`: Language, see below, `ko` by default


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
  - `rodong.rep.kp/cn/index.php`
  - `rodong.rep.kp/en/index.php`
  - `rodong.rep.kp/ko/index.php`
  - `rodong.rep.kp/cn`
  - `rodong.rep.kp/en`
  - `rodong.rep.kp/ko`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 조선어 | English | 中文 |\n| ------ | ------- | ---- |\n| ko     | en      | cn   |",
  "example": "/rodong/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "News",
  "parameters": {
    "language": "Language, see below, `ko` by default"
  },
  "path": "/news/:language?",
  "radar": [
    {
      "source": [
        "rodong.rep.kp/cn/index.php",
        "rodong.rep.kp/en/index.php",
        "rodong.rep.kp/ko/index.php",
        "rodong.rep.kp/cn",
        "rodong.rep.kp/en",
        "rodong.rep.kp/ko"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": [],
  "url": "rodong.rep.kp/cn/index.php"
}
```
