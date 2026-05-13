# 西安电子科技大学 - 研究生院/卓越工程师学院

## Coverage
`index-only`

## Route
- Namespace: `xidian`
- Namespace Name: `西安电子科技大学`
- Route Path: `/gr/:category?`
- Route Name: `研究生院/卓越工程师学院`
- Example: `/xidian/gr/home_tzgg1`
- URL: `gr.xidian.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ZiHao256`
- Source Location: `gr.ts`
- Source Module: `() => import('@/routes/xidian/gr.ts')`

## Description
| 文章来源          | 参数           |
| ------------- | ------------ |
| ✅主页-最新动态      | home_zxdt    |
| ✅主页-通知公告      | home_tzgg1   |
| ✅主页-讲座报告      | home_jzbg    |
| ✅研院介绍-基本情况    | yyjs_jbqk    |
| ✅研院介绍-机构设置    | yyjs_jbqk1   |
| ✅研院介绍-部门领导    | yyjs_jbqk2   |
| ✅研院介绍-服务指南    | yyjs_jbqk3   |
| ✅研院介绍-学院联系方式  | yyjs_jbqk4   |
| ✅招生信息         | yjsy         |
| ✅招生信息-硕士研究生招生 | yjsy_yjszs   |
| ✅招生信息-博士研究生招生 | yjsy_bsyjszs |
| ✅招生信息-其他类型招生  | yjsy_qtlxzs  |
| ✅培养管理         | pygl         |
| ✅培养管理-学术学位    | pygl_xsxw    |
| ✅培养管理-专业学位    | pygl_zyxw    |
| ✅培养管理-教学管理    | pygl_jxgl    |
| ✅培养管理-课程建设    | pygl_jxgl1   |
| ✅培养管理-管理规定    | pygl_jxgl2   |
| ✅培养管理-国际交流    | pygl_jxgl3   |
| ✅培养管理-办事流程    | pygl_bslc    |
| ✅学位授予         | xwsy         |
| ✅学位授予-通知公告    | xwsy_tzgg    |
| ✅学位授予-规章制度    | xwsy_gzzd    |
| ✅学位授予-授位名单    | xwsy_swmd    |
| ✅学位授予-资料下载    | xwsy_zlxz    |

## Parameters
- `category`: 通知类别，默认为主页-通知公告


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
  - `gr.xidian.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 文章来源          | 参数           |\n| ------------- | ------------ |\n| ✅主页-最新动态      | home_zxdt    |\n| ✅主页-通知公告      | home_tzgg1   |\n| ✅主页-讲座报告      | home_jzbg    |\n| ✅研院介绍-基本情况    | yyjs_jbqk    |\n| ✅研院介绍-机构设置    | yyjs_jbqk1   |\n| ✅研院介绍-部门领导    | yyjs_jbqk2   |\n| ✅研院介绍-服务指南    | yyjs_jbqk3   |\n| ✅研院介绍-学院联系方式  | yyjs_jbqk4   |\n| ✅招生信息         | yjsy         |\n| ✅招生信息-硕士研究生招生 | yjsy_yjszs   |\n| ✅招生信息-博士研究生招生 | yjsy_bsyjszs |\n| ✅招生信息-其他类型招生  | yjsy_qtlxzs  |\n| ✅培养管理         | pygl         |\n| ✅培养管理-学术学位    | pygl_xsxw    |\n| ✅培养管理-专业学位    | pygl_zyxw    |\n| ✅培养管理-教学管理    | pygl_jxgl    |\n| ✅培养管理-课程建设    | pygl_jxgl1   |\n| ✅培养管理-管理规定    | pygl_jxgl2   |\n| ✅培养管理-国际交流    | pygl_jxgl3   |\n| ✅培养管理-办事流程    | pygl_bslc    |\n| ✅学位授予         | xwsy         |\n| ✅学位授予-通知公告    | xwsy_tzgg    |\n| ✅学位授予-规章制度    | xwsy_gzzd    |\n| ✅学位授予-授位名单    | xwsy_swmd    |\n| ✅学位授予-资料下载    | xwsy_zlxz    |",
  "example": "/xidian/gr/home_tzgg1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gr.ts",
  "maintainers": [
    "ZiHao256"
  ],
  "module": "() => import('@/routes/xidian/gr.ts')",
  "name": "研究生院/卓越工程师学院",
  "parameters": {
    "category": "通知类别，默认为主页-通知公告"
  },
  "path": "/gr/:category?",
  "radar": [
    {
      "source": [
        "gr.xidian.edu.cn/"
      ]
    }
  ],
  "url": "gr.xidian.edu.cn"
}
```
