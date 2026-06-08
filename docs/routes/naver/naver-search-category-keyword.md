# 네이버 - 검색

## Coverage
`index-only`

## Route
- Namespace: `naver`
- Namespace Name: `네이버`
- Route Path: `/naver/search/:category/:keyword`
- Route Name: `검색`
- Example: `/naver/search/all/송소희`
- URL: `naver.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `slowmande`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: {"default": "all", "description": "검색 카테고리. 기본값: all (통합검색)", "options": [{"label": "통합검색", "value": "all"}, {"label": "블로그", "value": "blog"}, {"label": "카페", "value": "cafe"}, {"label": "뉴스", "value": "news"}, {"label": "동영상", "value": "video"}]}
- `keyword`: 검색 키워드


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
  - `m.search.naver.com/search.naver`
- `target`: `/search/:category/:keyword`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/naver/search/all/송소희",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "slowmande"
  ],
  "name": "검색",
  "parameters": {
    "category": {
      "default": "all",
      "description": "검색 카테고리. 기본값: all (통합검색)",
      "options": [
        {
          "label": "통합검색",
          "value": "all"
        },
        {
          "label": "블로그",
          "value": "blog"
        },
        {
          "label": "카페",
          "value": "cafe"
        },
        {
          "label": "뉴스",
          "value": "news"
        },
        {
          "label": "동영상",
          "value": "video"
        }
      ]
    },
    "keyword": "검색 키워드"
  },
  "path": "/search/:category/:keyword",
  "radar": [
    {
      "source": [
        "m.search.naver.com/search.naver"
      ],
      "target": "/search/:category/:keyword"
    }
  ],
  "topFeeds": []
}
```
