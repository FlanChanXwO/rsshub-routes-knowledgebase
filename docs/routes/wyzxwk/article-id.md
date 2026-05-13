# 乌有之乡 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `wyzxwk`
- Namespace Name: `乌有之乡`
- Route Path: `/article/:id?`
- Route Name: `栏目`
- Example: `/wyzxwk/article/shushe`
- URL: `wyzxwk.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/wyzxwk/article.ts')`

## Description
时政

| 时代观察 | 舆论战争 |
| -------- | -------- |
| shidai   | yulun    |

  经济

| 经济视点 | 社会民生 | 三农关注 | 产业研究 |
| -------- | -------- | -------- | -------- |
| jingji   | shehui   | sannong  | chanye   |

  国际

| 国际纵横 | 国防外交 |
| -------- | -------- |
| guoji    | guofang  |

  思潮

| 理想之旅 | 思潮碰撞 | 文艺新生 | 读书交流 |
| -------- | -------- | -------- | -------- |
| lixiang  | sichao   | wenyi    | shushe   |

  历史

| 历史视野 | 中华文化 | 中华医药 | 共产党人 |
| -------- | -------- | -------- | -------- |
| lishi    | zhonghua | zhongyi  | cpers    |

  争鸣

| 风华正茂 | 工农之声 | 网友杂谈 | 网友时评 |
| -------- | -------- | -------- | -------- |
| qingnian | gongnong | zatan    | shiping  |

  活动

| 乌有公告 | 红色旅游 | 乌有讲堂  | 书画欣赏 |
| -------- | -------- | --------- | -------- |
| gonggao  | lvyou    | jiangtang | shuhua   |

## Parameters
- `id`: 栏目 id，可在栏目页 URL 中找到，默认为时代观察


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
  - `wyzxwk.com/Article/:id`
  - `wyzxwk.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "时政\n\n| 时代观察 | 舆论战争 |\n| -------- | -------- |\n| shidai   | yulun    |\n\n  经济\n\n| 经济视点 | 社会民生 | 三农关注 | 产业研究 |\n| -------- | -------- | -------- | -------- |\n| jingji   | shehui   | sannong  | chanye   |\n\n  国际\n\n| 国际纵横 | 国防外交 |\n| -------- | -------- |\n| guoji    | guofang  |\n\n  思潮\n\n| 理想之旅 | 思潮碰撞 | 文艺新生 | 读书交流 |\n| -------- | -------- | -------- | -------- |\n| lixiang  | sichao   | wenyi    | shushe   |\n\n  历史\n\n| 历史视野 | 中华文化 | 中华医药 | 共产党人 |\n| -------- | -------- | -------- | -------- |\n| lishi    | zhonghua | zhongyi  | cpers    |\n\n  争鸣\n\n| 风华正茂 | 工农之声 | 网友杂谈 | 网友时评 |\n| -------- | -------- | -------- | -------- |\n| qingnian | gongnong | zatan    | shiping  |\n\n  活动\n\n| 乌有公告 | 红色旅游 | 乌有讲堂  | 书画欣赏 |\n| -------- | -------- | --------- | -------- |\n| gonggao  | lvyou    | jiangtang | shuhua   |",
  "example": "/wyzxwk/article/shushe",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/wyzxwk/article.ts')",
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，可在栏目页 URL 中找到，默认为时代观察"
  },
  "path": "/article/:id?",
  "radar": [
    {
      "source": [
        "wyzxwk.com/Article/:id",
        "wyzxwk.com/"
      ]
    }
  ]
}
```
