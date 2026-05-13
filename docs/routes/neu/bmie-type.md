# 东北大学 - 医学与生物信息工程学院

## Coverage
`index-only`

## Route
- Namespace: `neu`
- Namespace Name: `东北大学`
- Route Path: `/bmie/:type`
- Route Name: `医学与生物信息工程学院`
- Example: `/neu/bmie/news`
- URL: `neunews.neu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `tennousuathena`
- Source Location: `bmie.ts`
- Source Module: `() => import('@/routes/neu/bmie.ts')`

## Description
| Id                      | 名称       |
| ----------------------- | ---------- |
| news                    | 学院新闻   |
| academic                | 学术科研   |
| talent_development     | 人才培养   |
| international_exchange | 国际交流   |
| announcement            | 通知公告   |
| undergraduate_dev      | 本科生培养 |
| postgraduate_dev       | 研究生培养 |
| undergraduate_recruit  | 本科生招募 |
| postgraduate_recruit   | 研究生招募 |
| CPC_build              | 党的建设   |
| CPC_work               | 党委工作   |
| union_work             | 工会工作   |
| CYL_work               | 共青团工作 |
| security_management    | 安全管理   |
| alumni_style           | 校友风采   |

## Parameters
- `type`: 分类 id 见下表


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
    "university"
  ],
  "description": "| Id                      | 名称       |\n| ----------------------- | ---------- |\n| news                    | 学院新闻   |\n| academic                | 学术科研   |\n| talent_development     | 人才培养   |\n| international_exchange | 国际交流   |\n| announcement            | 通知公告   |\n| undergraduate_dev      | 本科生培养 |\n| postgraduate_dev       | 研究生培养 |\n| undergraduate_recruit  | 本科生招募 |\n| postgraduate_recruit   | 研究生招募 |\n| CPC_build              | 党的建设   |\n| CPC_work               | 党委工作   |\n| union_work             | 工会工作   |\n| CYL_work               | 共青团工作 |\n| security_management    | 安全管理   |\n| alumni_style           | 校友风采   |",
  "example": "/neu/bmie/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bmie.ts",
  "maintainers": [
    "tennousuathena"
  ],
  "module": "() => import('@/routes/neu/bmie.ts')",
  "name": "医学与生物信息工程学院",
  "parameters": {
    "type": "分类 id 见下表"
  },
  "path": "/bmie/:type"
}
```
