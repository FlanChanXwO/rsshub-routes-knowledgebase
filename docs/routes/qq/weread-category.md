# 腾讯网 - 微信读书榜单

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/weread/:category`
- Route Name: `微信读书榜单`
- Example: `/qq/weread/newbook`
- URL: `qq.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `gogo-100`
- Source Location: `weread/category.ts`
- Source Module: `() => import('@/routes/qq/weread/category.ts')`

## Description
| 榜单                  | 榜单名     |
| ---------------------- | ---------- |
| Top50飙升榜           | rising     |
| Top50热搜榜           | hot_search |
| Top50新书榜           | newbook    |
| Top50小说榜           | general_novel_rising |
| Top200总榜            | all        |
| 神作榜                 | newrating_publish |
| 神作潜力榜            | newrating_potential_publish |
| 精品小说              | 100000     |
| 历史                  | 200000     |
| 文学                  | 300000     |
| 艺术                  | 400000     |
| 人物传记              | 500000     |
| 哲学宗教              | 600000     |
| 计算机                | 700000     |
| 心理                  | 800000     |
| 社会文化              | 900000     |
| 个人成长              | 1000000    |
| 经济理财              | 1100000    |
| 政治军事              | 1200000    |
| 童书                  | 1300000    |
| 教育学习              | 1400000    |
| 科学技术              | 1500000    |
| 生活百科              | 1600000    |
| 期刊杂志              | 1700000    |
| 原版书                | 1800000    |
| 男生小说              | 1900000    |
| 女生小说              | 2000000    |
| 医学健康              | 2100000    |

还可以分得更细 见 https://weread.qq.com/web/category/100000 的小标题栏

## Parameters
- `category`: 榜单名，见下表


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
    "new-media"
  ],
  "description": "| 榜单                  | 榜单名     |\n| ---------------------- | ---------- |\n| Top50飙升榜           | rising     |\n| Top50热搜榜           | hot_search |\n| Top50新书榜           | newbook    |\n| Top50小说榜           | general_novel_rising |\n| Top200总榜            | all        |\n| 神作榜                 | newrating_publish |\n| 神作潜力榜            | newrating_potential_publish |\n| 精品小说              | 100000     |\n| 历史                  | 200000     |\n| 文学                  | 300000     |\n| 艺术                  | 400000     |\n| 人物传记              | 500000     |\n| 哲学宗教              | 600000     |\n| 计算机                | 700000     |\n| 心理                  | 800000     |\n| 社会文化              | 900000     |\n| 个人成长              | 1000000    |\n| 经济理财              | 1100000    |\n| 政治军事              | 1200000    |\n| 童书                  | 1300000    |\n| 教育学习              | 1400000    |\n| 科学技术              | 1500000    |\n| 生活百科              | 1600000    |\n| 期刊杂志              | 1700000    |\n| 原版书                | 1800000    |\n| 男生小说              | 1900000    |\n| 女生小说              | 2000000    |\n| 医学健康              | 2100000    |\n\n还可以分得更细 见 https://weread.qq.com/web/category/100000 的小标题栏\n",
  "example": "/qq/weread/newbook",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "weread/category.ts",
  "maintainers": [
    "gogo-100"
  ],
  "module": "() => import('@/routes/qq/weread/category.ts')",
  "name": "微信读书榜单",
  "parameters": {
    "category": "榜单名，见下表"
  },
  "path": "/weread/:category"
}
```
