# Love Live! Official Website - News

## Coverage
`index-only`

## Route
- Namespace: `lovelive-anime`
- Namespace Name: `Love Live! Official Website`
- Route Path: `/lovelive-anime/news/:abbr?/:category?/:option?`
- Route Name: `News`
- Example: `/lovelive-anime/news`
- URL: `www.lovelive-anime.jp/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `axojhf, zhaoweizhong`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
| Sub-project Name | All Projects          | Lovelive! | Lovelive! Sunshine!! | Lovelive! Nijigasaki High School Idol Club | Lovelive! Superstar!! | 蓮ノ空女学院 | イキヅライブ！ | 幻日のヨハネ | ラブライブ！スクールアイドルミュージカル |
| ---------------- | --------------------- | --------- | -------------------- | ------------------------------------------ | --------------------- | ------------ | -------------- | ------------ | ---------------------------------------- |
| `abbr`parameter  | <u>*No parameter*</u> | lovelive  | sunshine             | nijigasaki                                 | superstar             | hasunosora   | ikizulive      | yohane       | musical                                  |

| Category Name       | 全てのニュース        | 音楽商品 | アニメ映像商品 | キャスト映像商品 | 劇場    | アニメ放送 / 配信 | キャスト配信 / ラジオ | ライブ / イベント | ブック | グッズ | ゲーム | メディア | ご当地情報 | キャンペーン | その他 |
| ------------------- | --------------------- | -------- | -------------- | ---------------- | ------- | ----------------- | --------------------- | ----------------- | ------ | ------ | ------ | -------- | ---------- | ------------ | ------ |
| `category`parameter | <u>*No parameter*</u> | music    | anime\_movie   | cast\_movie      | theater | onair             | radio                 | event             | books  | goods  | game   | media    | local      | campaign     | other  |

## Parameters
- `abbr`: The path to the Love Live series of sub-projects on the official website is detailed in the table below, `abbr` is `detail` when crawling the full text
- `category`: The official website lists the Topics category, `category` is `detail` when crawling the full text, other categories see the following table for details
- `option`: Crawl full text when `option` is `detail`.


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
  - `www.lovelive-anime.jp/`
  - `www.lovelive-anime.jp/news/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| Sub-project Name | All Projects          | Lovelive! | Lovelive! Sunshine!! | Lovelive! Nijigasaki High School Idol Club | Lovelive! Superstar!! | 蓮ノ空女学院 | イキヅライブ！ | 幻日のヨハネ | ラブライブ！スクールアイドルミュージカル |\n| ---------------- | --------------------- | --------- | -------------------- | ------------------------------------------ | --------------------- | ------------ | -------------- | ------------ | ---------------------------------------- |\n| `abbr`parameter  | <u>*No parameter*</u> | lovelive  | sunshine             | nijigasaki                                 | superstar             | hasunosora   | ikizulive      | yohane       | musical                                  |\n\n| Category Name       | 全てのニュース        | 音楽商品 | アニメ映像商品 | キャスト映像商品 | 劇場    | アニメ放送 / 配信 | キャスト配信 / ラジオ | ライブ / イベント | ブック | グッズ | ゲーム | メディア | ご当地情報 | キャンペーン | その他 |\n| ------------------- | --------------------- | -------- | -------------- | ---------------- | ------- | ----------------- | --------------------- | ----------------- | ------ | ------ | ------ | -------- | ---------- | ------------ | ------ |\n| `category`parameter | <u>*No parameter*</u> | music    | anime\\_movie   | cast\\_movie      | theater | onair             | radio                 | event             | books  | goods  | game   | media    | local      | campaign     | other  |",
  "example": "/lovelive-anime/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 10,
  "location": "news.tsx",
  "maintainers": [
    "axojhf",
    "zhaoweizhong"
  ],
  "name": "News",
  "parameters": {
    "abbr": "The path to the Love Live series of sub-projects on the official website is detailed in the table below, `abbr` is `detail` when crawling the full text",
    "category": "The official website lists the Topics category, `category` is `detail` when crawling the full text, other categories see the following table for details",
    "option": "Crawl full text when `option` is `detail`."
  },
  "path": "/news/:abbr?/:category?/:option?",
  "radar": [
    {
      "source": [
        "www.lovelive-anime.jp/",
        "www.lovelive-anime.jp/news/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "lovelive official website news - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63026938870732800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lovelive-anime.jp/news/",
      "title": "lovelive official website news",
      "type": "feed",
      "url": "rsshub://lovelive-anime/news"
    }
  ],
  "url": "www.lovelive-anime.jp/"
}
```
