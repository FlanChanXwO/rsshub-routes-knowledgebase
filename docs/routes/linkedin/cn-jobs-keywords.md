# LinkedIn - Jobs

## Coverage
`index-only`

## Route
- Namespace: `linkedin`
- Namespace Name: `LinkedIn`
- Route Path: `/cn/jobs/:keywords?`
- Route Name: `Jobs`
- Example: `/linkedin/cn/jobs/Software`
- URL: `linkedin.com`
- Language: `en`
- Categories: `other`
- Maintainers: `bigfei`
- Source Location: `cn/index.ts`
- Source Module: `() => import('@/routes/linkedin/cn/index.ts')`

## Description
另外，可以通过添加额外的以下 query 参数来输出满足特定要求的工作职位：

| 参数       | 描述                                              | 举例                                                    | 默认值  |
| ---------- | ------------------------------------------------- | ------------------------------------------------------- | ------- |
| `geo`      | geo 编码                                          | 102890883（中国）、102772228（上海）、103873152（北京） | 空      |
| `remote`   | 是否只显示远程工作                                | `true/false`                                            | `false` |
| `location` | 工作地点                                          | `china/shanghai/beijing`                                | 空      |
| `relevant` | 排序方式 (true: 按相关性排序，false： 按日期排序) | `true/false`                                            | `false` |
| `period`   | 发布时间                                          | `1/7/30`                                                | 空      |

  例如：
  [`/linkedin/cn/jobs/Software?location=shanghai&period=1`](https://rsshub.app/linkedin/cn/jobs/Software?location=shanghai&period=1): 查找所有在上海的今日发布的所有 Software 工作

  **为了方便起见，建议您在 [LinkedIn.cn](https://www.linkedin.cn/incareer/jobs/search) 上进行搜索，并使用 [RSSHub Radar](https://github.com/DIYgod/RSSHub-Radar) 加载特定的 feed。**

## Parameters
- `keywords`: 搜索关键字


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
    "other"
  ],
  "description": "另外，可以通过添加额外的以下 query 参数来输出满足特定要求的工作职位：\n\n| 参数       | 描述                                              | 举例                                                    | 默认值  |\n| ---------- | ------------------------------------------------- | ------------------------------------------------------- | ------- |\n| `geo`      | geo 编码                                          | 102890883（中国）、102772228（上海）、103873152（北京） | 空      |\n| `remote`   | 是否只显示远程工作                                | `true/false`                                            | `false` |\n| `location` | 工作地点                                          | `china/shanghai/beijing`                                | 空      |\n| `relevant` | 排序方式 (true: 按相关性排序，false： 按日期排序) | `true/false`                                            | `false` |\n| `period`   | 发布时间                                          | `1/7/30`                                                | 空      |\n\n  例如：\n  [`/linkedin/cn/jobs/Software?location=shanghai&period=1`](https://rsshub.app/linkedin/cn/jobs/Software?location=shanghai&period=1): 查找所有在上海的今日发布的所有 Software 工作\n\n  **为了方便起见，建议您在 [LinkedIn.cn](https://www.linkedin.cn/incareer/jobs/search) 上进行搜索，并使用 [RSSHub Radar](https://github.com/DIYgod/RSSHub-Radar) 加载特定的 feed。**",
  "example": "/linkedin/cn/jobs/Software",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cn/index.ts",
  "maintainers": [
    "bigfei"
  ],
  "module": "() => import('@/routes/linkedin/cn/index.ts')",
  "name": "Jobs",
  "parameters": {
    "keywords": "搜索关键字"
  },
  "path": "/cn/jobs/:keywords?"
}
```
