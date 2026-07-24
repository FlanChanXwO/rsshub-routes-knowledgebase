# Capital Museum - News

## Coverage
`index-only`

## Route
- Namespace: `capitalmuseum`
- Namespace Name: `Capital Museum`
- Route Path: `/capitalmuseum/news/:type?`
- Route Name: `News`
- Example: `/capitalmuseum/news/notice`
- URL: `www.capitalmuseum.org.cn/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: News type, supported values: news（新闻资讯）, notice（通知公告）. Default: All news.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.capitalmuseum.org.cn/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/capitalmuseum/news/notice",
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "magazian"
  ],
  "name": "News",
  "parameters": {
    "type": "News type, supported values: news（新闻资讯）, notice（通知公告）. Default: All news."
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "www.capitalmuseum.org.cn/news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
