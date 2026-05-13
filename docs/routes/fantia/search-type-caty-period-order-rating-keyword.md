# Fantia - Search

## Coverage
`index-only`

## Route
- Namespace: `fantia`
- Namespace Name: `Fantia`
- Route Path: `/search/:type?/:caty?/:period?/:order?/:rating?/:keyword?`
- Route Name: `Search`
- Example: `/fantia/search/posts/all/daily`
- URL: `fantia.jp`
- Language: `ja`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/fantia/search.ts')`

## Description
Type

| クリエイター | 投稿  | 商品     | コミッション |
| ------------ | ----- | -------- | ------------ |
| fanclubs     | posts | products | commissions  |

  Category

| 分类                   | 分类名     |
| ---------------------- | ---------- |
| イラスト               | illust     |
| 漫画                   | comic      |
| コスプレ               | cosplay    |
| YouTuber・配信者       | youtuber   |
| Vtuber                 | vtuber     |
| 音声作品・ASMR         | voice      |
| 声優・歌い手           | voiceactor |
| アイドル               | idol       |
| アニメ・映像・写真     | anime      |
| 3D                     | 3d         |
| ゲーム制作             | game       |
| 音楽                   | music      |
| 小説                   | novel      |
| ドール                 | doll       |
| アート・デザイン       | art        |
| プログラム             | program    |
| 創作・ハンドメイド     | handmade   |
| 歴史・評論・情報       | history    |
| 鉄道・旅行・ミリタリー | railroad   |
| ショップ               | shop       |
| その他                 | other      |

  Ranking period

| デイリー | ウィークリー | マンスリー | 全期間 |
| -------- | ------------ | ---------- | ------ |
| daily    | weekly       | monthly    | all    |

  Sorting

| 更新の新しい順 | 更新の古い順 | 投稿の新しい順 | 投稿の古い順 | お気に入り数順 |
| -------------- | ------------ | -------------- | ------------ | -------------- |
| updater        | update_old  | newer          | create_old  | popular        |

  Rating

| すべて | 一般のみ | R18 のみ |
| ------ | -------- | -------- |
| all    | general  | adult    |

## Parameters
- `type`: {"default": "posts", "description": "Type, see the table below, `posts` by default", "options": [{"label": "クリエイター", "value": "fanclubs"}, {"label": "投稿", "value": "posts"}, {"label": "商品", "value": "products"}, {"label": "コミッション", "value": "commissions"}]}
- `caty`: {"default": "all", "description": "Category, see the table below, can also be found in search page URL, `すべてのクリエイター` by default", "options": [{"label": "すべてのクリエイター", "value": "all"}, {"label": "イラスト", "value": "illust"}, {"label": "漫画", "value": "comic"}, {"label": "コスプレ", "value": "cosplay"}, {"label": "YouTuber・配信者", "value": "youtuber"}, {"label": "Vtuber", "value": "vtuber"}, {"label": "音声作品・ASMR", "value": "voice"}, {"label": "声優・歌い手", "value": "voiceactor"}, {"label": "アイドル", "value": "idol"}, {"label": "アニメ・映像・写真", "value": "anime"}, {"label": "3D", "value": "3d"}, {"label": "ゲーム制作", "value": "game"}, {"label": "音楽", "value": "music"}, {"label": "小説", "value": "novel"}, {"label": "ドール", "value": "doll"}, {"label": "アート・デザイン", "value": "art"}, {"label": "プログラム", "value": "program"}, {"label": "創作・ハンドメイド", "value": "handmade"}, {"label": "歴史・評論・情報", "value": "history"}, {"label": "鉄道・旅行・ミリタリー", "value": "railroad"}, {"label": "ショップ", "value": "shop"}, {"label": "その他", "value": "other"}]}
- `period`: {"default": "", "description": "Ranking period, see the table below, empty by default", "options": [{"label": "デイリー", "value": "daily"}, {"label": "ウィークリー", "value": "weekly"}, {"label": "マンスリー", "value": "monthly"}, {"label": "全期間", "value": "all"}]}
- `order`: {"default": "updater", "description": "Sorting, see the table below, `更新の新しい順` by default", "options": [{"label": "更新の新しい順", "value": "updater"}, {"label": "更新の古い順", "value": "update_old"}, {"label": "投稿の新しい順", "value": "newer"}, {"label": "投稿の古い順", "value": "create_old"}, {"label": "お気に入り数順", "value": "popular"}]}
- `rating`: {"default": "all", "description": "Rating, see the table below, `すべて` by default", "options": [{"label": "すべて", "value": "all"}, {"label": "一般のみ", "value": "general"}, {"label": "R18 のみ", "value": "adult"}]}
- `keyword`: Keyword, empty by default


## Features
- `requireConfig`: [{"description": "The `cookie` after login can be obtained by viewing the request header in the console, If not filled in will cause some posts that require login to read to get exceptions", "name": "FANTIA_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "Type\n\n| クリエイター | 投稿  | 商品     | コミッション |\n| ------------ | ----- | -------- | ------------ |\n| fanclubs     | posts | products | commissions  |\n\n  Category\n\n| 分类                   | 分类名     |\n| ---------------------- | ---------- |\n| イラスト               | illust     |\n| 漫画                   | comic      |\n| コスプレ               | cosplay    |\n| YouTuber・配信者       | youtuber   |\n| Vtuber                 | vtuber     |\n| 音声作品・ASMR         | voice      |\n| 声優・歌い手           | voiceactor |\n| アイドル               | idol       |\n| アニメ・映像・写真     | anime      |\n| 3D                     | 3d         |\n| ゲーム制作             | game       |\n| 音楽                   | music      |\n| 小説                   | novel      |\n| ドール                 | doll       |\n| アート・デザイン       | art        |\n| プログラム             | program    |\n| 創作・ハンドメイド     | handmade   |\n| 歴史・評論・情報       | history    |\n| 鉄道・旅行・ミリタリー | railroad   |\n| ショップ               | shop       |\n| その他                 | other      |\n\n  Ranking period\n\n| デイリー | ウィークリー | マンスリー | 全期間 |\n| -------- | ------------ | ---------- | ------ |\n| daily    | weekly       | monthly    | all    |\n\n  Sorting\n\n| 更新の新しい順 | 更新の古い順 | 投稿の新しい順 | 投稿の古い順 | お気に入り数順 |\n| -------------- | ------------ | -------------- | ------------ | -------------- |\n| updater        | update_old  | newer          | create_old  | popular        |\n\n  Rating\n\n| すべて | 一般のみ | R18 のみ |\n| ------ | -------- | -------- |\n| all    | general  | adult    |",
  "example": "/fantia/search/posts/all/daily",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "The `cookie` after login can be obtained by viewing the request header in the console, If not filled in will cause some posts that require login to read to get exceptions",
        "name": "FANTIA_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/fantia/search.ts')",
  "name": "Search",
  "parameters": {
    "caty": {
      "default": "all",
      "description": "Category, see the table below, can also be found in search page URL, `すべてのクリエイター` by default",
      "options": [
        {
          "label": "すべてのクリエイター",
          "value": "all"
        },
        {
          "label": "イラスト",
          "value": "illust"
        },
        {
          "label": "漫画",
          "value": "comic"
        },
        {
          "label": "コスプレ",
          "value": "cosplay"
        },
        {
          "label": "YouTuber・配信者",
          "value": "youtuber"
        },
        {
          "label": "Vtuber",
          "value": "vtuber"
        },
        {
          "label": "音声作品・ASMR",
          "value": "voice"
        },
        {
          "label": "声優・歌い手",
          "value": "voiceactor"
        },
        {
          "label": "アイドル",
          "value": "idol"
        },
        {
          "label": "アニメ・映像・写真",
          "value": "anime"
        },
        {
          "label": "3D",
          "value": "3d"
        },
        {
          "label": "ゲーム制作",
          "value": "game"
        },
        {
          "label": "音楽",
          "value": "music"
        },
        {
          "label": "小説",
          "value": "novel"
        },
        {
          "label": "ドール",
          "value": "doll"
        },
        {
          "label": "アート・デザイン",
          "value": "art"
        },
        {
          "label": "プログラム",
          "value": "program"
        },
        {
          "label": "創作・ハンドメイド",
          "value": "handmade"
        },
        {
          "label": "歴史・評論・情報",
          "value": "history"
        },
        {
          "label": "鉄道・旅行・ミリタリー",
          "value": "railroad"
        },
        {
          "label": "ショップ",
          "value": "shop"
        },
        {
          "label": "その他",
          "value": "other"
        }
      ]
    },
    "keyword": "Keyword, empty by default",
    "order": {
      "default": "updater",
      "description": "Sorting, see the table below, `更新の新しい順` by default",
      "options": [
        {
          "label": "更新の新しい順",
          "value": "updater"
        },
        {
          "label": "更新の古い順",
          "value": "update_old"
        },
        {
          "label": "投稿の新しい順",
          "value": "newer"
        },
        {
          "label": "投稿の古い順",
          "value": "create_old"
        },
        {
          "label": "お気に入り数順",
          "value": "popular"
        }
      ]
    },
    "period": {
      "default": "",
      "description": "Ranking period, see the table below, empty by default",
      "options": [
        {
          "label": "デイリー",
          "value": "daily"
        },
        {
          "label": "ウィークリー",
          "value": "weekly"
        },
        {
          "label": "マンスリー",
          "value": "monthly"
        },
        {
          "label": "全期間",
          "value": "all"
        }
      ]
    },
    "rating": {
      "default": "all",
      "description": "Rating, see the table below, `すべて` by default",
      "options": [
        {
          "label": "すべて",
          "value": "all"
        },
        {
          "label": "一般のみ",
          "value": "general"
        },
        {
          "label": "R18 のみ",
          "value": "adult"
        }
      ]
    },
    "type": {
      "default": "posts",
      "description": "Type, see the table below, `posts` by default",
      "options": [
        {
          "label": "クリエイター",
          "value": "fanclubs"
        },
        {
          "label": "投稿",
          "value": "posts"
        },
        {
          "label": "商品",
          "value": "products"
        },
        {
          "label": "コミッション",
          "value": "commissions"
        }
      ]
    }
  },
  "path": "/search/:type?/:caty?/:period?/:order?/:rating?/:keyword?",
  "view": 2
}
```
