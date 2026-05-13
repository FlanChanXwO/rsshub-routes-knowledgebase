# 中国光大银行 - 外汇牌价

## Coverage
`index-only`

## Route
- Namespace: `cebbank`
- Namespace Name: `中国光大银行`
- Route Path: `/quotation/history/:type`
- Route Name: `外汇牌价`
- Example: `/cebbank/quotation/history/usd`
- URL: `cebbank.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `linbuxiao`
- Source Location: `history.tsx`
- Source Module: `() => import('@/routes/cebbank/history.tsx')`

## Description
#### 总览 {#zhong-guo-guang-da-yin-hang-wai-hui-pai-jia-zong-lan}


#### 历史牌价 {#zhong-guo-guang-da-yin-hang-wai-hui-pai-jia-li-shi-pai-jia}

| 美元 | 英镑 | 港币 | 瑞士法郎 | 瑞典克郎 | 丹麦克郎 | 挪威克郎 | 日元 | 加拿大元 | 澳大利亚元 | 新加坡元 | 欧元 | 澳门元 | 泰国铢 | 新西兰元 | 韩圆 |
| ---- | ---- | ---- | -------- | -------- | -------- | -------- | ---- | -------- | ---------- | -------- | ---- | ------ | ------ | -------- | ---- |
| usd  | gbp  | hkd  | chf      | sek      | dkk      | nok      | jpy  | cad      | aud        | sgd      | eur  | mop    | thb    | nzd      | krw  |

## Parameters
- `type`: 货币的缩写，见下表


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
  "description": "#### 总览 {#zhong-guo-guang-da-yin-hang-wai-hui-pai-jia-zong-lan}\n\n\n#### 历史牌价 {#zhong-guo-guang-da-yin-hang-wai-hui-pai-jia-li-shi-pai-jia}\n\n| 美元 | 英镑 | 港币 | 瑞士法郎 | 瑞典克郎 | 丹麦克郎 | 挪威克郎 | 日元 | 加拿大元 | 澳大利亚元 | 新加坡元 | 欧元 | 澳门元 | 泰国铢 | 新西兰元 | 韩圆 |\n| ---- | ---- | ---- | -------- | -------- | -------- | -------- | ---- | -------- | ---------- | -------- | ---- | ------ | ------ | -------- | ---- |\n| usd  | gbp  | hkd  | chf      | sek      | dkk      | nok      | jpy  | cad      | aud        | sgd      | eur  | mop    | thb    | nzd      | krw  |",
  "example": "/cebbank/quotation/history/usd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "history.tsx",
  "maintainers": [
    "linbuxiao"
  ],
  "module": "() => import('@/routes/cebbank/history.tsx')",
  "name": "外汇牌价",
  "parameters": {
    "type": "货币的缩写，见下表"
  },
  "path": "/quotation/history/:type"
}
```
