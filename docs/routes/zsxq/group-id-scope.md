# 知识星球 - 星球

## Coverage
`index-only`

## Route
- Namespace: `zsxq`
- Namespace Name: `知识星球`
- Route Path: `/group/:id/:scope?`
- Route Name: `星球`
- Example: `/zsxq/group/88855458825252`
- URL: `zsxq.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `group.ts`
- Source Module: `() => import('@/routes/zsxq/group.ts')`

## Description
| all  | digests | by_owner | questions | tasks |
| ---- | ------ | --------- | -------- | ------ |
| 最新 | 精华    | 只看星主    | 问答      | 作业   |

## Parameters
- `id`: 星球id，从网页端url中获取
- `scope`: 栏目分类，默认为"all"，见下表


## Features
- `requireConfig`: [{"description": "知识星球访问令牌,获取方式：\n1. 登录知识星球网页版\n2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://wx.zsxq.com\n4. 复制 Cookie 中的 zsxq_access_token 值", "name": "ZSXQ_ACCESS_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `wx.zsxq.com/dweb2/index/group/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| all  | digests | by_owner | questions | tasks |\n| ---- | ------ | --------- | -------- | ------ |\n| 最新 | 精华    | 只看星主    | 问答      | 作业   |",
  "example": "/zsxq/group/88855458825252",
  "features": {
    "requireConfig": [
      {
        "description": "知识星球访问令牌,获取方式：\n1. 登录知识星球网页版\n2. 打开浏览器开发者工具，切换到 Application 面板\n3. 点击侧边栏中的Storage -> Cookies -> https://wx.zsxq.com\n4. 复制 Cookie 中的 zsxq_access_token 值",
        "name": "ZSXQ_ACCESS_TOKEN"
      }
    ]
  },
  "location": "group.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/zsxq/group.ts')",
  "name": "星球",
  "parameters": {
    "id": "星球id，从网页端url中获取",
    "scope": "栏目分类，默认为\"all\"，见下表"
  },
  "path": "/group/:id/:scope?",
  "radar": [
    {
      "source": [
        "wx.zsxq.com/dweb2/index/group/:id"
      ]
    }
  ]
}
```
