# 中证网 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cs`
- Namespace Name: `中证网`
- Route Path: `/:category{.+}?`
- Route Name: `栏目`
- Example: `_None_`
- URL: `cs.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cs/index.ts')`

## Description
| 要闻 | 公司 | 市场 | 基金 |
| ---- | ---- | ---- | ---- |
| xwzx | ssgs | gppd | tzjj |

| 科创 | 产经   | 期货     | 海外   |
| ---- | ------ | -------- | ------ |
| 5g   | cj2020 | zzqh2020 | hw2020 |

<details>
<summary>更多栏目</summary>

#### 要闻

| 财经要闻 | 观点评论 | 民生消费  |
| -------- | -------- | --------- |
| xwzx/hg  | xwzx/jr  | xwzx/msxf |

#### 公司

| 公司要闻  | 公司深度  | 公司巡礼  |
| --------- | --------- | --------- |
| ssgs/gsxw | ssgs/gssd | ssgs/gsxl |

#### 市场

| A 股市场  | 港股资讯  | 债市研究  | 海外报道  | 期货报道  |
| --------- | --------- | --------- | --------- | --------- |
| gppd/gsyj | gppd/ggzx | gppd/zqxw | gppd/hwbd | gppd/qhbd |

#### 基金

| 基金动态  | 基金视点  | 基金持仓  | 私募基金  | 基民学苑  |
| --------- | --------- | --------- | --------- | --------- |
| tzjj/jjdt | tzjj/jjks | tzjj/jjcs | tzjj/smjj | tzjj/tjdh |

#### 机构

| 券商 | 银行 | 保险 |
| ---- | ---- | ---- |
| qs   | yh   | bx   |

#### 其他

| 中证快讯 7x24 | IPO 鉴真 | 公司能见度 |
| ------------- | -------- | ---------- |
| sylm/jsbd     | yc/ipojz | yc/gsnjd   |
</details>

## Parameters
- `category`: 分类，见下表，默认为首页


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "description": "| 要闻 | 公司 | 市场 | 基金 |\n| ---- | ---- | ---- | ---- |\n| xwzx | ssgs | gppd | tzjj |\n\n| 科创 | 产经   | 期货     | 海外   |\n| ---- | ------ | -------- | ------ |\n| 5g   | cj2020 | zzqh2020 | hw2020 |\n\n<details>\n<summary>更多栏目</summary>\n\n#### 要闻\n\n| 财经要闻 | 观点评论 | 民生消费  |\n| -------- | -------- | --------- |\n| xwzx/hg  | xwzx/jr  | xwzx/msxf |\n\n#### 公司\n\n| 公司要闻  | 公司深度  | 公司巡礼  |\n| --------- | --------- | --------- |\n| ssgs/gsxw | ssgs/gssd | ssgs/gsxl |\n\n#### 市场\n\n| A 股市场  | 港股资讯  | 债市研究  | 海外报道  | 期货报道  |\n| --------- | --------- | --------- | --------- | --------- |\n| gppd/gsyj | gppd/ggzx | gppd/zqxw | gppd/hwbd | gppd/qhbd |\n\n#### 基金\n\n| 基金动态  | 基金视点  | 基金持仓  | 私募基金  | 基民学苑  |\n| --------- | --------- | --------- | --------- | --------- |\n| tzjj/jjdt | tzjj/jjks | tzjj/jjcs | tzjj/smjj | tzjj/tjdh |\n\n#### 机构\n\n| 券商 | 银行 | 保险 |\n| ---- | ---- | ---- |\n| qs   | yh   | bx   |\n\n#### 其他\n\n| 中证快讯 7x24 | IPO 鉴真 | 公司能见度 |\n| ------------- | -------- | ---------- |\n| sylm/jsbd     | yc/ipojz | yc/gsnjd   |\n</details>",
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cs/index.ts')",
  "name": "栏目",
  "parameters": {
    "category": "分类，见下表，默认为首页"
  },
  "path": "/:category{.+}?"
}
```
