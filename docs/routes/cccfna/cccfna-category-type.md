# 中国食品土畜进出口商会 - 资讯信息

## Coverage
`index-only`

## Route
- Namespace: `cccfna`
- Namespace Name: `中国食品土畜进出口商会`
- Route Path: `/cccfna/:category/:type?`
- Route Name: `资讯信息`
- Example: `/cccfna/meirigengxin`
- URL: `www.cccfna.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `hualiong`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
存在**二级分类**的**一级分类**不能单独当作参数，如：`/cccfna/hangyezixun`
:::

文章的目录分级如下:

- shanghuidongtai（商会通知）
- meirigengxin（每日更新）
- tongzhigonggao（通知公告）
- hangyezixun（行业资讯）
  - zhengcedaohang（政策导航）
  - yujinxinxi（预警信息）
  - shichangdongtai（市场动态）
  - gongxuxinxi（供需信息）
- maoyitongji（贸易统计）
  - tongjikuaibao（统计快报）
  - hangyetongji（行业统计）
  - guobiemaoyi（国别贸易）
  - maoyizhinan（贸易指南）
- nongchanpinbaogao（农产品报告）
  - nongchanpinyuebao（农产品月报）
  - zhongdianchanpinyuebao（重点产品月报）
  - zhongdianchanpinzoushi（重点产品走势）

## Parameters
- `category`: 文章种类，即一级分类，详情见下表
- `type`: 文章类型，即二级分类，详情见下表


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.cccfna.org.cn/:category/:type?`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n存在**二级分类**的**一级分类**不能单独当作参数，如：`/cccfna/hangyezixun`\n:::\n\n文章的目录分级如下:\n\n- shanghuidongtai（商会通知）\n- meirigengxin（每日更新）\n- tongzhigonggao（通知公告）\n- hangyezixun（行业资讯）\n  - zhengcedaohang（政策导航）\n  - yujinxinxi（预警信息）\n  - shichangdongtai（市场动态）\n  - gongxuxinxi（供需信息）\n- maoyitongji（贸易统计）\n  - tongjikuaibao（统计快报）\n  - hangyetongji（行业统计）\n  - guobiemaoyi（国别贸易）\n  - maoyizhinan（贸易指南）\n- nongchanpinbaogao（农产品报告）\n  - nongchanpinyuebao（农产品月报）\n  - zhongdianchanpinyuebao（重点产品月报）\n  - zhongdianchanpinzoushi（重点产品走势）",
  "example": "/cccfna/meirigengxin",
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "hualiong"
  ],
  "name": "资讯信息",
  "parameters": {
    "category": "文章种类，即一级分类，详情见下表",
    "type": "文章类型，即二级分类，详情见下表"
  },
  "path": "/:category/:type?",
  "radar": [
    {
      "source": [
        "www.cccfna.org.cn/:category/:type?"
      ]
    }
  ],
  "topFeeds": []
}
```
