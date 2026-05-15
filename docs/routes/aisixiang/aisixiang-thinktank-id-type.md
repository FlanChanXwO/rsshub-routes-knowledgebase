# 爱思想 - 思想库（专栏）

## Coverage
`index-only`

## Route
- Namespace: `aisixiang`
- Namespace Name: `爱思想`
- Route Path: `/aisixiang/thinktank/:id/:type?`
- Route Name: `思想库（专栏）`
- Example: `/aisixiang/thinktank/WuQine/论文`
- URL: `aisixiang.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `hoilc, nczitzk`
- Source Location: `thinktank.ts`
- Source Module: `_None_`

## Description
| 论文 | 时评 | 随笔 | 演讲 | 访谈 | 著作 | 读书 | 史论 | 译作 | 诗歌 | 书信 | 科学 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `id`: 专栏 ID，一般为作者拼音，可在URL中找到
- `type`: 栏目类型，参考下表，默认为全部


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
    "reading"
  ],
  "description": "| 论文 | 时评 | 随笔 | 演讲 | 访谈 | 著作 | 读书 | 史论 | 译作 | 诗歌 | 书信 | 科学 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/aisixiang/thinktank/WuQine/论文",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 86,
  "location": "thinktank.ts",
  "maintainers": [
    "hoilc",
    "nczitzk"
  ],
  "name": "思想库（专栏）",
  "parameters": {
    "id": "专栏 ID，一般为作者拼音，可在URL中找到",
    "type": "栏目类型，参考下表，默认为全部"
  },
  "path": "/thinktank/:id/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "陈嘉映，1952年出生于上海。宾夕法尼亚州立大学博士。曾任教于北京大学、华东师范大学，现为首都师范大学哲学系特聘教授，外国哲学学科专业负责人。主要研究领域为分析哲学、现象学和科学哲学。著有《海德格尔哲学概论》、《语言哲学》、《思远道》、《泠风集》、《哲学 科学 常识》等。（<a href=\"http://www.aisixiang.com/data/detail.php?id=22792\" target=\"_blank\"><font color=#990033><u>陈嘉映简介</u></font></a>） - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "98011535417850905",
      "image": "https://oss.aisixiang.com/images/logo_thinktank.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.aisixiang.com/thinktank/chenjiaying.html",
      "title": "爱思想 - 陈嘉映",
      "type": "feed",
      "url": "rsshub://aisixiang/thinktank/chenjiaying"
    },
    {
      "description": "张维迎，北京大学校长助理，光华管理学院前院长，网络经济研究中心主任，教授，兼任国务院学位委员会应用经济学学科评议组成员，中国企业家论坛首席经济学家，牛津大学现代中国研究中心研究员。1959年生于陕西省吴堡县，1982年西北大学经济学本科毕业，1994年获牛津大学经济学博士学位。1984-1990年曾在国家体改委工作，1994年起任教于北京大学。主要研究领域为产业组织与企业理论。主要著作有：《企业的企业家-契约理论》，《博弈论与信息经济学》，《企业理论与中国企业改革》，《产权、政府与信誉》，《信息、信任与法律》,《大学的逻辑》，《论企业家》（合著），《产权、激励与公司治理》，《竞争力与企业成长》，《价格、市场与企业家》，《中国改革30年》(主编), 《市场的逻辑》等。另有数十篇中英文学术论文在国内外权威期刊发表。 - Powered by RSSHub",
      "errorAt": "2026-05-13T12:07:57.382Z",
      "errorMessage": "Failed to fetch\n",
      "id": "82048909265511424",
      "image": "https://oss.aisixiang.com/images/logo_thinktank.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.aisixiang.com/thinktank/zhangweiying.html",
      "title": "爱思想 - 张维迎",
      "type": "feed",
      "url": "rsshub://aisixiang/thinktank/zhangweiying"
    }
  ]
}
```
