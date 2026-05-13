# 米哈游 - 米游社 - 同人榜

## Coverage
`index-only`

## Route
- Namespace: `mihoyo`
- Namespace Name: `米哈游`
- Route Path: `/bbs/img-ranking/:game/:routeParams?`
- Route Name: `米游社 - 同人榜`
- Example: `/mihoyo/bbs/img-ranking/ys/forumType=tongren&cateType=illustration&rankingType=daily`
- URL: `genshin.hoyoverse.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `CaoMeiYouRen`
- Source Location: `bbs/img-ranking.ts`
- Source Module: `() => import('@/routes/mihoyo/bbs/img-ranking.ts')`

## Description
| 键          | 含义                                  | 接受的值                                                             | 默认值       |
| ----------- | ------------------------------------- | -------------------------------------------------------------------- | ------------ |
| forumType   | 主榜类型（仅原神、大别野有 cos 主榜） | tongren/cos                                                          | tongren      |
| cateType    | 子榜类型（仅崩坏三、原神有子榜）      | 崩坏三：illustration/comic/cos；原神：illustration/comic/qute/manual | illustration |
| rankingType | 排行榜类型（崩坏二没有日榜）          | daily/weekly/monthly                                                 | daily        |
| lastId      | 当前页 id（用于分页）                 | 数字                                                                 | 1            |

  游戏缩写

| 崩坏三 | 原神 | 崩坏二 | 未定事件簿 | 星穹铁道 | 大别野 | 绝区零 |
| ------ | ---- | ------ | ---------- | -------- | ------ | ------ |
| bh3    | ys   | bh2    | wd         | sr       | dby    | zzz    |

  主榜类型

| 同人榜  | COS 榜 |
| ------- | ------ |
| tongren | cos    |

  子榜类型

  崩坏三 子榜

| 插画         | 漫画  | COS |
| ------------ | ----- | --- |
| illustration | comic | cos |

  原神 子榜

| 插画         | 漫画  | Q 版 | 手工   |
| ------------ | ----- | ---- | ------ |
| illustration | comic | qute | manual |

  排行榜类型

| 日榜  | 周榜   | 月榜    |
| ----- | ------ | ------- |
| daily | weekly | monthly |

## Parameters
- `game`: 游戏缩写
- `routeParams`: 额外参数；请参阅以下说明和表格


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
  - `miyoushe.com/:game/imgRanking/:forum_id/:ranking_id/:cate_id`
- `target`: `/bbs/img-ranking/:game`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "| 键          | 含义                                  | 接受的值                                                             | 默认值       |\n| ----------- | ------------------------------------- | -------------------------------------------------------------------- | ------------ |\n| forumType   | 主榜类型（仅原神、大别野有 cos 主榜） | tongren/cos                                                          | tongren      |\n| cateType    | 子榜类型（仅崩坏三、原神有子榜）      | 崩坏三：illustration/comic/cos；原神：illustration/comic/qute/manual | illustration |\n| rankingType | 排行榜类型（崩坏二没有日榜）          | daily/weekly/monthly                                                 | daily        |\n| lastId      | 当前页 id（用于分页）                 | 数字                                                                 | 1            |\n\n  游戏缩写\n\n| 崩坏三 | 原神 | 崩坏二 | 未定事件簿 | 星穹铁道 | 大别野 | 绝区零 |\n| ------ | ---- | ------ | ---------- | -------- | ------ | ------ |\n| bh3    | ys   | bh2    | wd         | sr       | dby    | zzz    |\n\n  主榜类型\n\n| 同人榜  | COS 榜 |\n| ------- | ------ |\n| tongren | cos    |\n\n  子榜类型\n\n  崩坏三 子榜\n\n| 插画         | 漫画  | COS |\n| ------------ | ----- | --- |\n| illustration | comic | cos |\n\n  原神 子榜\n\n| 插画         | 漫画  | Q 版 | 手工   |\n| ------------ | ----- | ---- | ------ |\n| illustration | comic | qute | manual |\n\n  排行榜类型\n\n| 日榜  | 周榜   | 月榜    |\n| ----- | ------ | ------- |\n| daily | weekly | monthly |",
  "example": "/mihoyo/bbs/img-ranking/ys/forumType=tongren&cateType=illustration&rankingType=daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bbs/img-ranking.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/mihoyo/bbs/img-ranking.ts')",
  "name": "米游社 - 同人榜",
  "parameters": {
    "game": "游戏缩写",
    "routeParams": "额外参数；请参阅以下说明和表格"
  },
  "path": "/bbs/img-ranking/:game/:routeParams?",
  "radar": [
    {
      "source": [
        "miyoushe.com/:game/imgRanking/:forum_id/:ranking_id/:cate_id"
      ],
      "target": "/bbs/img-ranking/:game"
    }
  ]
}
```
