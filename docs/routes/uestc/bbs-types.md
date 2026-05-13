# 电子科技大学 - 清水河畔

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/bbs/:types?`
- Route Name: `清水河畔`
- Example: `/uestc/bbs/newthread`
- URL: `bbs.uestc.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `huyyi`
- Source Location: `bbs.ts`
- Source Module: `() => import('@/routes/uestc/bbs.ts')`

## Description
::: tip
仅支持自建，您需要设置以下配置才能正常使用：
-   河畔cookie: `UESTC_BBS_COOKIE`
-   Header中的授权字段: `UESTC_BBS_AUTH_KEY`
:::

## Parameters
- `types`: 选择内容类型(多选`,`分割），可选值：[newreply,newthread,digest,life,hotlist]。默认为所有。


## Features
- `requireConfig`: [{"description": "河畔的cookie", "name": "UESTC_BBS_COOKIE", "optional": false}, {"description": "河畔Header中的authorization字段", "name": "UESTC_BBS_AUTH_KEY", "optional": false}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `bbs.uestc.edu.cn/*`
- `target`: `/bbs/newthread`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\n::: tip\n仅支持自建，您需要设置以下配置才能正常使用：\n-   河畔cookie: `UESTC_BBS_COOKIE`\n-   Header中的授权字段: `UESTC_BBS_AUTH_KEY`\n:::\n",
  "example": "/uestc/bbs/newthread",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "河畔的cookie",
        "name": "UESTC_BBS_COOKIE",
        "optional": false
      },
      {
        "description": "河畔Header中的authorization字段",
        "name": "UESTC_BBS_AUTH_KEY",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bbs.ts",
  "maintainers": [
    "huyyi"
  ],
  "module": "() => import('@/routes/uestc/bbs.ts')",
  "name": "清水河畔",
  "parameters": {
    "types": "选择内容类型(多选`,`分割），可选值：[newreply,newthread,digest,life,hotlist]。默认为所有。"
  },
  "path": "/bbs/:types?",
  "radar": [
    {
      "source": [
        "bbs.uestc.edu.cn/*"
      ],
      "target": "/bbs/newthread"
    }
  ],
  "url": "bbs.uestc.edu.cn"
}
```
