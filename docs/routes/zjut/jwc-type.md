# 浙江工业大学 - 浙江工业大学教务处

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/jwc/:type`
- Route Name: `浙江工业大学教务处`
- Example: `/zjut/jwc/1839`
- URL: `www.jwc.zjut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `zhullyb`
- Source Location: `jwc/index.ts`
- Source Module: `() => import('@/routes/zjut/jwc/index.ts')`

## Description
| 板块 | 参数 |
| ------- | ------- |
| 新闻动态 | 1838 |
| 课程思政 | 1842 |
| 校内动态 | 2613 |
| 学习思考 | 2614 |
| 成果展示 | 2615 |
| 媒体聚焦 | 2616 |
| 制度文件 | 2617 |
| 教学运行 | 1849 |
| 实践竞赛 | 1850 |
| 留学生Notice | 1851 |
| 项目申报 | 1852 |
| 学籍管理 | 1853 |
| 办事指南 | 1839 |

## Parameters
- `type`: 分类，见下表


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
  - `www.jwc.zjut.edu.cn/:type/list.htm`
- `target`: `/jwc/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 板块 | 参数 |\n| ------- | ------- |\n| 新闻动态 | 1838 |\n| 课程思政 | 1842 |\n| 校内动态 | 2613 |\n| 学习思考 | 2614 |\n| 成果展示 | 2615 |\n| 媒体聚焦 | 2616 |\n| 制度文件 | 2617 |\n| 教学运行 | 1849 |\n| 实践竞赛 | 1850 |\n| 留学生Notice | 1851 |\n| 项目申报 | 1852 |\n| 学籍管理 | 1853 |\n| 办事指南 | 1839 |",
  "example": "/zjut/jwc/1839",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc/index.ts",
  "maintainers": [
    "zhullyb"
  ],
  "module": "() => import('@/routes/zjut/jwc/index.ts')",
  "name": "浙江工业大学教务处",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/jwc/:type",
  "radar": [
    {
      "source": [
        "www.jwc.zjut.edu.cn/:type/list.htm"
      ],
      "target": "/jwc/:type"
    }
  ],
  "url": "www.jwc.zjut.edu.cn"
}
```
