# 国家市场监督管理总局缺陷产品管理中心 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `samrdprc`
- Namespace Name: `国家市场监督管理总局缺陷产品管理中心`
- Route Path: `/:id{.+}?`
- Route Name: `栏目`
- Example: `/samrdprc/xwdt/gzdt`
- URL: `www.samrdprc.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/samrdprc/index.ts')`

## Description
::: tip
订阅 [网站公告](https://www.samrdprc.org.cn/wzgg/)，其源网址为 `https://www.samrdprc.org.cn/wzgg/`，请参考该 URL 指定部分构成参数，此时路由为 [`/samrdprc/wzgg`](https://rsshub.app/samrdprc/wzgg)。
:::

<details>
  <summary>更多分类</summary>

  #### 网站首页

  | [新闻动态](https://www.samrdprc.org.cn/xwdt/gzdt/) | [网站公告](https://www.samrdprc.org.cn/wzgg/) | [汽车召回](https://www.samrdprc.org.cn/qczh/) | [消费品召回](https://www.samrdprc.org.cn/xfpzh/) |
  | -------------------------------------------------- | --------------------------------------------- | --------------------------------------------- | ------------------------------------------------ |
  | [xwdt/gzdt](https://rsshub.app/samrdprc/xwdt/gzdt) | [wzgg](https://rsshub.app/samrdprc/wzgg)      | [qczh](https://rsshub.app/samrdprc/qczh)      | [xfpzh](https://rsshub.app/samrdprc/xfpzh)       |

  #### 科学研究

  | [技术报告](https://www.samrdprc.org.cn/yjgz/jsyj/) | [SAC/TC463](https://www.samrdprc.org.cn/yjgz/sactc/) | [研究动态](https://www.samrdprc.org.cn/yjgz/yjfx/) |
  | -------------------------------------------------- | ---------------------------------------------------- | -------------------------------------------------- |
  | [yjgz/jsyj](https://rsshub.app/samrdprc/yjgz/jsyj) | [yjgz/sactc](https://rsshub.app/samrdprc/yjgz/sactc) | [yjgz/yjfx](https://rsshub.app/samrdprc/yjgz/yjfx) |

  #### 安全教育

  | [安全教育](https://www.samrdprc.org.cn/aqjy/) |
  | --------------------------------------------- |
  | [aqjy](https://rsshub.app/samrdprc/aqjy)      |

  #### 法律法规

  | [国内法规](https://www.samrdprc.org.cn/flfg/gnfg/) |
  | -------------------------------------------------- |
  | [flfg/gnfg](https://rsshub.app/samrdprc/flfg/gnfg) |
</details>

## Parameters
- `id`: {"description": "栏目 id，默认为 `xwdt/gzdt`，即国内新闻，可在对应分类页 URL 中找到", "options": [{"label": "新闻动态", "value": "xwdt/gzdt"}, {"label": "网站公告", "value": "wzgg"}, {"label": "汽车召回", "value": "qczh"}, {"label": "消费品召回", "value": "xfpzh"}, {"label": "技术报告", "value": "yjgz/jsyj"}, {"label": "SAC/TC463", "value": "yjgz/sactc"}, {"label": "研究动态", "value": "yjgz/yjfx"}, {"label": "安全教育", "value": "aqjy"}, {"label": "国内法规", "value": "flfg/gnfg"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.samrdprc.org.cn/:id`
- `target`: `/:id`
### Rule 2
- `title`: `网站首页 - 新闻动态`
- `source`:
  - `www.samrdprc.org.cn/xwdt/gzdt/`
- `target`: `/xwdt/gzdt`
### Rule 3
- `title`: `网站首页 - 网站公告`
- `source`:
  - `www.samrdprc.org.cn/wzgg/`
- `target`: `/wzgg`
### Rule 4
- `title`: `网站首页 - 汽车召回`
- `source`:
  - `www.samrdprc.org.cn/qczh/`
- `target`: `/qczh`
### Rule 5
- `title`: `网站首页 - 消费品召回`
- `source`:
  - `www.samrdprc.org.cn/xfpzh/`
- `target`: `/xfpzh`
### Rule 6
- `title`: `科学研究 - 技术报告`
- `source`:
  - `www.samrdprc.org.cn/yjgz/jsyj/`
- `target`: `/yjgz/jsyj`
### Rule 7
- `title`: `科学研究 - SAC/TC463`
- `source`:
  - `www.samrdprc.org.cn/yjgz/sactc/`
- `target`: `/yjgz/sactc`
### Rule 8
- `title`: `科学研究 - 研究动态`
- `source`:
  - `www.samrdprc.org.cn/yjgz/yjfx/`
- `target`: `/yjgz/yjfx`
### Rule 9
- `title`: `安全教育 - 安全教育`
- `source`:
  - `www.samrdprc.org.cn/aqjy/`
- `target`: `/aqjy`
### Rule 10
- `title`: `法律法规 - 国内法规`
- `source`:
  - `www.samrdprc.org.cn/flfg/gnfg/`
- `target`: `/flfg/gnfg`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n订阅 [网站公告](https://www.samrdprc.org.cn/wzgg/)，其源网址为 `https://www.samrdprc.org.cn/wzgg/`，请参考该 URL 指定部分构成参数，此时路由为 [`/samrdprc/wzgg`](https://rsshub.app/samrdprc/wzgg)。\n:::\n\n<details>\n  <summary>更多分类</summary>\n\n  #### 网站首页\n\n  | [新闻动态](https://www.samrdprc.org.cn/xwdt/gzdt/) | [网站公告](https://www.samrdprc.org.cn/wzgg/) | [汽车召回](https://www.samrdprc.org.cn/qczh/) | [消费品召回](https://www.samrdprc.org.cn/xfpzh/) |\n  | -------------------------------------------------- | --------------------------------------------- | --------------------------------------------- | ------------------------------------------------ |\n  | [xwdt/gzdt](https://rsshub.app/samrdprc/xwdt/gzdt) | [wzgg](https://rsshub.app/samrdprc/wzgg)      | [qczh](https://rsshub.app/samrdprc/qczh)      | [xfpzh](https://rsshub.app/samrdprc/xfpzh)       |\n\n  #### 科学研究\n\n  | [技术报告](https://www.samrdprc.org.cn/yjgz/jsyj/) | [SAC/TC463](https://www.samrdprc.org.cn/yjgz/sactc/) | [研究动态](https://www.samrdprc.org.cn/yjgz/yjfx/) |\n  | -------------------------------------------------- | ---------------------------------------------------- | -------------------------------------------------- |\n  | [yjgz/jsyj](https://rsshub.app/samrdprc/yjgz/jsyj) | [yjgz/sactc](https://rsshub.app/samrdprc/yjgz/sactc) | [yjgz/yjfx](https://rsshub.app/samrdprc/yjgz/yjfx) |\n\n  #### 安全教育\n\n  | [安全教育](https://www.samrdprc.org.cn/aqjy/) |\n  | --------------------------------------------- |\n  | [aqjy](https://rsshub.app/samrdprc/aqjy)      |\n\n  #### 法律法规\n\n  | [国内法规](https://www.samrdprc.org.cn/flfg/gnfg/) |\n  | -------------------------------------------------- |\n  | [flfg/gnfg](https://rsshub.app/samrdprc/flfg/gnfg) |\n</details>\n",
  "example": "/samrdprc/xwdt/gzdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/samrdprc/index.ts')",
  "name": "栏目",
  "parameters": {
    "id": {
      "description": "栏目 id，默认为 `xwdt/gzdt`，即国内新闻，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "新闻动态",
          "value": "xwdt/gzdt"
        },
        {
          "label": "网站公告",
          "value": "wzgg"
        },
        {
          "label": "汽车召回",
          "value": "qczh"
        },
        {
          "label": "消费品召回",
          "value": "xfpzh"
        },
        {
          "label": "技术报告",
          "value": "yjgz/jsyj"
        },
        {
          "label": "SAC/TC463",
          "value": "yjgz/sactc"
        },
        {
          "label": "研究动态",
          "value": "yjgz/yjfx"
        },
        {
          "label": "安全教育",
          "value": "aqjy"
        },
        {
          "label": "国内法规",
          "value": "flfg/gnfg"
        }
      ]
    }
  },
  "path": "/:id{.+}?",
  "radar": [
    {
      "source": [
        "www.samrdprc.org.cn/:id"
      ],
      "target": "/:id"
    },
    {
      "source": [
        "www.samrdprc.org.cn/xwdt/gzdt/"
      ],
      "target": "/xwdt/gzdt",
      "title": "网站首页 - 新闻动态"
    },
    {
      "source": [
        "www.samrdprc.org.cn/wzgg/"
      ],
      "target": "/wzgg",
      "title": "网站首页 - 网站公告"
    },
    {
      "source": [
        "www.samrdprc.org.cn/qczh/"
      ],
      "target": "/qczh",
      "title": "网站首页 - 汽车召回"
    },
    {
      "source": [
        "www.samrdprc.org.cn/xfpzh/"
      ],
      "target": "/xfpzh",
      "title": "网站首页 - 消费品召回"
    },
    {
      "source": [
        "www.samrdprc.org.cn/yjgz/jsyj/"
      ],
      "target": "/yjgz/jsyj",
      "title": "科学研究 - 技术报告"
    },
    {
      "source": [
        "www.samrdprc.org.cn/yjgz/sactc/"
      ],
      "target": "/yjgz/sactc",
      "title": "科学研究 - SAC/TC463"
    },
    {
      "source": [
        "www.samrdprc.org.cn/yjgz/yjfx/"
      ],
      "target": "/yjgz/yjfx",
      "title": "科学研究 - 研究动态"
    },
    {
      "source": [
        "www.samrdprc.org.cn/aqjy/"
      ],
      "target": "/aqjy",
      "title": "安全教育 - 安全教育"
    },
    {
      "source": [
        "www.samrdprc.org.cn/flfg/gnfg/"
      ],
      "target": "/flfg/gnfg",
      "title": "法律法规 - 国内法规"
    }
  ],
  "url": "www.samrdprc.org.cn",
  "view": 0
}
```
