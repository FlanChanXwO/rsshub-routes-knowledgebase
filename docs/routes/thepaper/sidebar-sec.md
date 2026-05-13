# 澎湃新闻 - 侧边栏

## Coverage
`index-only`

## Route
- Namespace: `thepaper`
- Namespace Name: `澎湃新闻`
- Route Path: `/sidebar/:sec?`
- Route Name: `侧边栏`
- Example: `/thepaper/sidebar`
- URL: `thepaper.cn/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `bigfei`
- Source Location: `sidebar.ts`
- Source Module: `() => import('@/routes/thepaper/sidebar.ts')`

## Description
_None_

## Parameters
- `sec`: {"description": "侧边栏 id", "options": [{"label": "澎湃热榜", "value": "hotNews"}, {"label": "澎湃快讯", "value": "financialInformationNews"}, {"label": "早晚报", "value": "morningEveningNews"}, {"label": "要闻精选", "value": "editorHandpicked"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `thepaper.cn/`
- `target`: `/sidebar`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/thepaper/sidebar",
  "location": "sidebar.ts",
  "maintainers": [
    "bigfei"
  ],
  "module": "() => import('@/routes/thepaper/sidebar.ts')",
  "name": "侧边栏",
  "parameters": {
    "sec": {
      "description": "侧边栏 id",
      "options": [
        {
          "label": "澎湃热榜",
          "value": "hotNews"
        },
        {
          "label": "澎湃快讯",
          "value": "financialInformationNews"
        },
        {
          "label": "早晚报",
          "value": "morningEveningNews"
        },
        {
          "label": "要闻精选",
          "value": "editorHandpicked"
        }
      ]
    }
  },
  "path": "/sidebar/:sec?",
  "radar": [
    {
      "source": [
        "thepaper.cn/"
      ],
      "target": "/sidebar"
    }
  ],
  "url": "thepaper.cn/"
}
```
