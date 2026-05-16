# 快手 - Profile

## Coverage
`index-only`

## Route
- Namespace: `kuaishou`
- Namespace Name: `快手`
- Route Path: `/kuaishou/profile/:principalId`
- Route Name: `Profile`
- Example: `/kuaishou/profile/3xk46q9cdnvgife`
- URL: `kuaishou.com/profile/:principalId`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `GuoChen-thlg`
- Source Location: `profile.ts`
- Source Module: `_None_`

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
  "categories": [
    "social-media"
  ],
  "description": "::: tip\nThe profile page of the user, which contains the user's information, videos, and other information.\n:::",
  "example": "/kuaishou/profile/3xk46q9cdnvgife",
  "heat": 6,
  "location": "profile.ts",
  "maintainers": [
    "GuoChen-thlg"
  ],
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
  "topFeeds": [
    {
      "description": "youbao5266的作品 - 快手 - Powered by RSSHub",
      "errorAt": "2026-05-15T02:17:36.166Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nFailed to fetch\n",
      "id": "147602391664470016",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "youbao5266的作品 - 快手",
      "type": "feed",
      "url": "rsshub://kuaishou/profile/youbao5266"
    },
    {
      "description": "3xe5h7ecz25ddn4的作品 - 快手 - Powered by RSSHub",
      "errorAt": "2025-04-04T18:17:54.132Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "90277166035281920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "3xe5h7ecz25ddn4的作品 - 快手",
      "type": "feed",
      "url": "rsshub://kuaishou/profile/3xe5h7ecz25ddn4"
    }
  ],
  "url": "kuaishou.com/profile/:principalId"
}
```
