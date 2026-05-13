# Rodong Sinmun 劳动新闻 - News

## Coverage
`index-only`

## Route
- Namespace: `rodong`
- Namespace Name: `Rodong Sinmun 劳动新闻`
- Route Path: `/news/:language?`
- Route Name: `News`
- Example: `/rodong/news`
- URL: `rodong.rep.kp/cn/index.php`
- Language: `ko`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/rodong/news.ts')`

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
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/rodong/news.ts')",
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
  "url": "rodong.rep.kp/cn/index.php"
}
```
