# 快手 - Profile

## Coverage
`index-only`

## Route
- Namespace: `kuaishou`
- Namespace Name: `快手`
- Route Path: `/profile/:principalId`
- Route Name: `Profile`
- Example: `/kuaishou/profile/3xk46q9cdnvgife`
- URL: `kuaishou.com/profile/:principalId`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `GuoChen-thlg`
- Source Location: `profile.ts`
- Source Module: `() => import('@/routes/kuaishou/profile.ts')`

## Description
::: tip
The profile page of the user, which contains the user's information, videos, and other information.
:::

## Parameters
- `principalId`: 用户 id, 可在主页中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `kuaishou.com/profile/:principalId`
- `target`: `/profile/:principalId`

## Raw JSON
```json
{
  "description": "::: tip\nThe profile page of the user, which contains the user's information, videos, and other information.\n:::",
  "example": "/kuaishou/profile/3xk46q9cdnvgife",
  "location": "profile.ts",
  "maintainers": [
    "GuoChen-thlg"
  ],
  "module": "() => import('@/routes/kuaishou/profile.ts')",
  "name": "Profile",
  "parameters": {
    "principalId": "用户 id, 可在主页中找到"
  },
  "path": "/profile/:principalId",
  "radar": [
    {
      "source": [
        "kuaishou.com/profile/:principalId"
      ],
      "target": "/profile/:principalId"
    }
  ],
  "url": "kuaishou.com/profile/:principalId"
}
```
