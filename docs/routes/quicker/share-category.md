# Quicker - 动作分享

## Coverage
`index-only`

## Route
- Namespace: `quicker`
- Namespace Name: `Quicker`
- Route Path: `/share/:category?`
- Route Name: `动作分享`
- Example: `/quicker/share/Recent`
- URL: `getquicker.net`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `share.ts`
- Source Module: `() => import('@/routes/quicker/share.ts')`

## Description
| 动作库最新更新 | 动作库最多赞 | 动作库新动作 | 动作库最近赞 |
| -------------- | ------------ | ------------ | ------------ |
| Recent         | Recommended  | NewActions   | RecentLiked  |

| 子程序      | 扩展热键  | 文本指令     |
| ----------- | --------- | ------------ |
| SubPrograms | PowerKeys | TextCommands |

## Parameters
- `category`: 分类，见下表，默认为动作库最新更新


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
  - `getquicker.net/Share/:category`
  - `getquicker.net/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 动作库最新更新 | 动作库最多赞 | 动作库新动作 | 动作库最近赞 |\n| -------------- | ------------ | ------------ | ------------ |\n| Recent         | Recommended  | NewActions   | RecentLiked  |\n\n| 子程序      | 扩展热键  | 文本指令     |\n| ----------- | --------- | ------------ |\n| SubPrograms | PowerKeys | TextCommands |",
  "example": "/quicker/share/Recent",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "share.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/quicker/share.ts')",
  "name": "动作分享",
  "parameters": {
    "category": "分类，见下表，默认为动作库最新更新"
  },
  "path": "/share/:category?",
  "radar": [
    {
      "source": [
        "getquicker.net/Share/:category",
        "getquicker.net/"
      ]
    }
  ]
}
```
