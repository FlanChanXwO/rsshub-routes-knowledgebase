# 掘金 - AI 编程

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/aicoding/:tag?/:sort?`
- Route Name: `AI 编程`
- Example: `/juejin/aicoding`
- URL: `aicoding.juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `aicoding.ts`
- Source Module: `() => import('@/routes/juejin/aicoding.ts')`

## Description
_None_

## Parameters
- `tag`: {"description": "标签，留空为全部", "options": [{"label": "AI编程", "value": "AI编程"}, {"label": "Claude", "value": "Claude"}, {"label": "Trae", "value": "Trae"}, {"label": "MCP", "value": "MCP"}, {"label": "Cursor", "value": "Cursor"}, {"label": "Cline", "value": "Cline"}, {"label": "Github Copilot", "value": "Github Copilot"}, {"label": "bolt", "value": "bolt"}, {"label": "V0", "value": "V0"}, {"label": "replit", "value": "replit"}, {"label": "Warp", "value": "Warp"}, {"label": "Visual Studio IntelliCode", "value": "Visual Studio IntelliCode"}, {"label": "WindSurf", "value": "WindSurf"}, {"label": "豆包MarsCode", "value": "豆包MarsCode"}, {"label": "通义灵码", "value": "通义灵码"}, {"label": "Devin", "value": "Devin"}, {"label": "文心快码", "value": "文心快码"}, {"label": "imgcook", "value": "imgcook"}, {"label": "CodeWhisperer", "value": "CodeWhisperer"}, {"label": "Lovable", "value": "Lovable"}, {"label": "FittenCode", "value": "FittenCode"}, {"label": "Solo", "value": "Solo"}, {"label": "CodeFuse", "value": "CodeFuse"}, {"label": "Tabnine", "value": "Tabnine"}]}
- `sort`: {"default": "hot", "description": "排序方式，默认为最新发布", "options": [{"label": "热门", "value": "hot"}, {"label": "最新", "value": "latest"}]}


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
  - `juejin.cn/books`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/aicoding",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "aicoding.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/juejin/aicoding.ts')",
  "name": "AI 编程",
  "parameters": {
    "sort": {
      "default": "hot",
      "description": "排序方式，默认为最新发布",
      "options": [
        {
          "label": "热门",
          "value": "hot"
        },
        {
          "label": "最新",
          "value": "latest"
        }
      ]
    },
    "tag": {
      "description": "标签，留空为全部",
      "options": [
        {
          "label": "AI编程",
          "value": "AI编程"
        },
        {
          "label": "Claude",
          "value": "Claude"
        },
        {
          "label": "Trae",
          "value": "Trae"
        },
        {
          "label": "MCP",
          "value": "MCP"
        },
        {
          "label": "Cursor",
          "value": "Cursor"
        },
        {
          "label": "Cline",
          "value": "Cline"
        },
        {
          "label": "Github Copilot",
          "value": "Github Copilot"
        },
        {
          "label": "bolt",
          "value": "bolt"
        },
        {
          "label": "V0",
          "value": "V0"
        },
        {
          "label": "replit",
          "value": "replit"
        },
        {
          "label": "Warp",
          "value": "Warp"
        },
        {
          "label": "Visual Studio IntelliCode",
          "value": "Visual Studio IntelliCode"
        },
        {
          "label": "WindSurf",
          "value": "WindSurf"
        },
        {
          "label": "豆包MarsCode",
          "value": "豆包MarsCode"
        },
        {
          "label": "通义灵码",
          "value": "通义灵码"
        },
        {
          "label": "Devin",
          "value": "Devin"
        },
        {
          "label": "文心快码",
          "value": "文心快码"
        },
        {
          "label": "imgcook",
          "value": "imgcook"
        },
        {
          "label": "CodeWhisperer",
          "value": "CodeWhisperer"
        },
        {
          "label": "Lovable",
          "value": "Lovable"
        },
        {
          "label": "FittenCode",
          "value": "FittenCode"
        },
        {
          "label": "Solo",
          "value": "Solo"
        },
        {
          "label": "CodeFuse",
          "value": "CodeFuse"
        },
        {
          "label": "Tabnine",
          "value": "Tabnine"
        }
      ]
    }
  },
  "path": "/aicoding/:tag?/:sort?",
  "radar": [
    {
      "source": [
        "juejin.cn/books"
      ]
    }
  ],
  "url": "aicoding.juejin.cn"
}
```
