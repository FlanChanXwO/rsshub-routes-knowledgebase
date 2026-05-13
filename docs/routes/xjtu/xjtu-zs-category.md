# 西安交通大学 - 本科招生网

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/zs/:category{.+}?`
- Route Name: `本科招生网`
- Example: `/xjtu/zs/zsxx1/zskx`
- URL: `zs.xjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `zs.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [招生快讯](https://zs.xjtu.edu.cn/zsxx1/zskx.htm)，网址为 `https://zs.xjtu.edu.cn/zsxx1/zskx.htm`，请截取 `https://zs.xjtu.edu.cn/` 到末尾 `.htm` 的部分 `zsxx1/zskx` 作为 `category` 参数填入，此时目标路由为 [`/xjtu/zs/zsxx1/zskx`](https://rsshub.app/xjtu/zs/zsxx1/zskx)。
:::

| [招生快讯](https://zs.xjtu.edu.cn/zsxx1/zskx.htm)   | [招生政策](https://zs.xjtu.edu.cn/zsxx1/zszc.htm)   | [招生计划](https://zs.xjtu.edu.cn/zsxx1/zsjh.htm)   | [阳光公告](https://zs.xjtu.edu.cn/zsxx1/yggg.htm)   | [历年录取](https://zs.xjtu.edu.cn/zsxx1/lnlq.htm)   |
| --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |
| [zsxx1/zskx](https://rsshub.app/xjtu/zs/zsxx1/zskx) | [zsxx1/zszc](https://rsshub.app/xjtu/zs/zsxx1/zszc) | [zsxx1/zsjh](https://rsshub.app/xjtu/zs/zsxx1/zsjh) | [zsxx1/yggg](https://rsshub.app/xjtu/zs/zsxx1/yggg) | [zsxx1/lnlq](https://rsshub.app/xjtu/zs/zsxx1/lnlq) |

## Parameters
- `category`: {"description": "分类，默认为 zsxx1/zskx，可在对应分类页 URL 中找到", "options": [{"label": "招生快讯", "value": "zsxx1/zskx"}, {"label": "招生政策", "value": "zsxx1/zszc"}, {"label": "招生计划", "value": "zsxx1/zsjh"}, {"label": "阳光公告", "value": "zsxx1/yggg"}, {"label": "历年录取", "value": "zsxx1/lnlq"}]}


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
  - `zs.xjtu.edu.cn/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: tip\n若订阅 [招生快讯](https://zs.xjtu.edu.cn/zsxx1/zskx.htm)，网址为 `https://zs.xjtu.edu.cn/zsxx1/zskx.htm`，请截取 `https://zs.xjtu.edu.cn/` 到末尾 `.htm` 的部分 `zsxx1/zskx` 作为 `category` 参数填入，此时目标路由为 [`/xjtu/zs/zsxx1/zskx`](https://rsshub.app/xjtu/zs/zsxx1/zskx)。\n:::\n\n| [招生快讯](https://zs.xjtu.edu.cn/zsxx1/zskx.htm)   | [招生政策](https://zs.xjtu.edu.cn/zsxx1/zszc.htm)   | [招生计划](https://zs.xjtu.edu.cn/zsxx1/zsjh.htm)   | [阳光公告](https://zs.xjtu.edu.cn/zsxx1/yggg.htm)   | [历年录取](https://zs.xjtu.edu.cn/zsxx1/lnlq.htm)   |\n| --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- | --------------------------------------------------- |\n| [zsxx1/zskx](https://rsshub.app/xjtu/zs/zsxx1/zskx) | [zsxx1/zszc](https://rsshub.app/xjtu/zs/zsxx1/zszc) | [zsxx1/zsjh](https://rsshub.app/xjtu/zs/zsxx1/zsjh) | [zsxx1/yggg](https://rsshub.app/xjtu/zs/zsxx1/yggg) | [zsxx1/lnlq](https://rsshub.app/xjtu/zs/zsxx1/lnlq) |",
  "example": "/xjtu/zs/zsxx1/zskx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "zs.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "本科招生网",
  "parameters": {
    "category": {
      "description": "分类，默认为 zsxx1/zskx，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "招生快讯",
          "value": "zsxx1/zskx"
        },
        {
          "label": "招生政策",
          "value": "zsxx1/zszc"
        },
        {
          "label": "招生计划",
          "value": "zsxx1/zsjh"
        },
        {
          "label": "阳光公告",
          "value": "zsxx1/yggg"
        },
        {
          "label": "历年录取",
          "value": "zsxx1/lnlq"
        }
      ]
    }
  },
  "path": "/zs/:category{.+}?",
  "radar": [
    {
      "source": [
        "zs.xjtu.edu.cn/:category"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "zs.xjtu.edu.cn",
  "view": 0
}
```
