# 人人影视 - 影视资讯

## Coverage
`index-only`

## Route
- Namespace: `yyets`
- Namespace Name: `人人影视`
- Route Path: `/article/:type?`
- Route Name: `影视资讯`
- Example: `/yyets/article`
- URL: `yysub.net`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `wb121017405`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/yyets/article.ts')`

## Description
| 全部 | 影视资讯 | 收视快报 | 人人影评  | 人人剧评  | 新剧评测    | 片单推荐 |
| ---- | -------- | -------- | --------- | --------- | ----------- | -------- |
|      | news     | report   | m_review | t_review | new_review | recom    |

## Parameters
- `type`: {"default": "all", "description": "类型", "options": [{"label": "全部", "value": "all"}, {"label": "影视资讯", "value": "news"}, {"label": "收视快报", "value": "report"}, {"label": "人人影评", "value": "m_review"}, {"label": "人人剧评", "value": "t_review"}, {"label": "新剧评测", "value": "new_review"}, {"label": "片单推荐", "value": "recom"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| 全部 | 影视资讯 | 收视快报 | 人人影评  | 人人剧评  | 新剧评测    | 片单推荐 |\n| ---- | -------- | -------- | --------- | --------- | ----------- | -------- |\n|      | news     | report   | m_review | t_review | new_review | recom    |",
  "example": "/yyets/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "wb121017405"
  ],
  "module": "() => import('@/routes/yyets/article.ts')",
  "name": "影视资讯",
  "parameters": {
    "type": {
      "default": "all",
      "description": "类型",
      "options": [
        {
          "label": "全部",
          "value": "all"
        },
        {
          "label": "影视资讯",
          "value": "news"
        },
        {
          "label": "收视快报",
          "value": "report"
        },
        {
          "label": "人人影评",
          "value": "m_review"
        },
        {
          "label": "人人剧评",
          "value": "t_review"
        },
        {
          "label": "新剧评测",
          "value": "new_review"
        },
        {
          "label": "片单推荐",
          "value": "recom"
        }
      ]
    }
  },
  "path": "/article/:type?",
  "view": 0
}
```
