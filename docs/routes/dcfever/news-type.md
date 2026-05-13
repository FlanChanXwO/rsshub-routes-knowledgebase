# DCFever - 新聞中心

## Coverage
`index-only`

## Route
- Namespace: `dcfever`
- Namespace Name: `DCFever`
- Route Path: `/news/:type?`
- Route Name: `新聞中心`
- Example: `/dcfever/news`
- URL: `dcfever.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/dcfever/news.ts')`

## Description
| 所有新聞 | 攝影器材 | 手機通訊 | 汽車熱話 | 攝影文化    | 影片攝錄    | 測試報告 | 生活科技 | 攝影技巧  |
| -------- | -------- | -------- | -------- | ----------- | ----------- | -------- | -------- | --------- |
|          | camera   | mobile   | auto     | photography | videography | reviews  | gadget   | technique |

## Parameters
- `type`: 分類，預設為所有新聞


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `dcfever.com/news/index.php`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 所有新聞 | 攝影器材 | 手機通訊 | 汽車熱話 | 攝影文化    | 影片攝錄    | 測試報告 | 生活科技 | 攝影技巧  |\n| -------- | -------- | -------- | -------- | ----------- | ----------- | -------- | -------- | --------- |\n|          | camera   | mobile   | auto     | photography | videography | reviews  | gadget   | technique |",
  "example": "/dcfever/news",
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/dcfever/news.ts')",
  "name": "新聞中心",
  "parameters": {
    "type": "分類，預設為所有新聞"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "dcfever.com/news/index.php"
      ],
      "target": "/news"
    }
  ]
}
```
