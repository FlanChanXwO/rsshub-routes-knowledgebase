# 国家能源局 - 信息稿件

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/zhengce/govall/:advance?`
- Route Name: `信息稿件`
- Example: `/gov/zhengce/govall/orpro=555&notpro=2&search_field=title`
- URL: `www.gov.cn/`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `ciaranchen`
- Source Location: `zhengce/govall.ts`
- Source Module: `() => import('@/routes/gov/zhengce/govall.ts')`

## Description
|               选项              |                       意义                       |              备注              |
| :-----------------------------: | :----------------------------------------------: | :----------------------------: |
|              orpro              |             包含以下任意一个关键词。             |          用空格分隔。          |
|              allpro             |                包含以下全部关键词                |                                |
|              notpro             |                 不包含以下关键词                 |                                |
|              inpro              |                完整不拆分的关键词                |                                |
|           searchfield           | title: 搜索词在标题中；content: 搜索词在正文中。 |  默认为空，即网页的任意位置。  |
| pubmintimeYear, pubmintimeMonth |                    从某年某月                    | 单独使用月份参数无法只筛选月份 |
| pubmaxtimeYear, pubmaxtimeMonth |                    到某年某月                    | 单独使用月份参数无法只筛选月份 |
|              colid              |                       栏目                       |      比较复杂，不建议使用      |

## Parameters
- `advance`: 高级搜索选项，将作为请求参数直接添加到url后。目前已知的选项及其意义如下。


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
  - `www.gov.cn/`
- `target`: `/zhengce/govall`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "|               选项              |                       意义                       |              备注              |\n| :-----------------------------: | :----------------------------------------------: | :----------------------------: |\n|              orpro              |             包含以下任意一个关键词。             |          用空格分隔。          |\n|              allpro             |                包含以下全部关键词                |                                |\n|              notpro             |                 不包含以下关键词                 |                                |\n|              inpro              |                完整不拆分的关键词                |                                |\n|           searchfield           | title: 搜索词在标题中；content: 搜索词在正文中。 |  默认为空，即网页的任意位置。  |\n| pubmintimeYear, pubmintimeMonth |                    从某年某月                    | 单独使用月份参数无法只筛选月份 |\n| pubmaxtimeYear, pubmaxtimeMonth |                    到某年某月                    | 单独使用月份参数无法只筛选月份 |\n|              colid              |                       栏目                       |      比较复杂，不建议使用      |",
  "example": "/gov/zhengce/govall/orpro=555&notpro=2&search_field=title",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zhengce/govall.ts",
  "maintainers": [
    "ciaranchen"
  ],
  "module": "() => import('@/routes/gov/zhengce/govall.ts')",
  "name": "信息稿件",
  "parameters": {
    "advance": "高级搜索选项，将作为请求参数直接添加到url后。目前已知的选项及其意义如下。"
  },
  "path": "/zhengce/govall/:advance?",
  "radar": [
    {
      "source": [
        "www.gov.cn/"
      ],
      "target": "/zhengce/govall"
    }
  ],
  "url": "www.gov.cn/"
}
```
