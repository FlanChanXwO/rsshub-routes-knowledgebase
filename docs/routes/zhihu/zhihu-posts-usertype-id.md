# 知乎 - 用户文章

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/posts/:usertype/:id`
- Route Name: `用户文章`
- Example: `/zhihu/posts/people/frederchen`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `whtsky, Colin-XKL`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
| 普通用户 | 机构用户 |
| -------- | -------- |
| people   | org      |

## Parameters
- `usertype`: 作者 id，可在用户主页 URL 中找到
- `id`: 用户类型usertype，参考用户主页的URL。目前有两种，见下表


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/:usertype/:id/posts`
  - `www.zhihu.com/:usertype/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "description": "| 普通用户 | 机构用户 |\n| -------- | -------- |\n| people   | org      |",
  "example": "/zhihu/posts/people/frederchen",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1358,
  "location": "posts.ts",
  "maintainers": [
    "whtsky",
    "Colin-XKL"
  ],
  "name": "用户文章",
  "parameters": {
    "id": "用户类型usertype，参考用户主页的URL。目前有两种，见下表",
    "usertype": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/posts/:usertype/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/:usertype/:id/posts",
        "www.zhihu.com/:usertype/:id"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "学校≠教育≠技能；文凭溢价=80%信号传递+20%人力资本 - Powered by RSSHub",
      "errorAt": "2025-04-22T11:31:51.374Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/members/L.M.Sherlock/articles?include=data%5B*%5D.comment_count%2Csuggest_edit%2Cis_normal%2Cthumbnail_extra_info%2Cthumbnail%2Ccan_comment%2Ccomment_permission%2Cadmin_closed_comment%2Ccontent%2Cvoteup_count%2Ccreated%2Cupdated%2Cupvoted_followees%2Cvoting%2Creview_info%2Creaction_instruction%2Cis_labeled%2Clabel_info%3Bdata%5B*%5D.vessay_info%3Bdata%5B*%5D.author.badge%5B%3F%28type%3Dbest_answerer%29%5D.topics%3Bdata%5B*%5D.author.vip_info%3B&offset=0&limit=20&sort_by=created\": 403 Forbidden\n[GET] \"https://www.zhihu.com/api/v4/members/L.M.Sherlock/articles?include=data%5B*%5D.comment_count%2Csuggest_edit%2Cis_normal%2Cthumbnail_extra_info%2Cthumbnail%2Ccan_comment%2Ccomment_permission%2Cadmin_closed_comment%2Ccontent%2Cvoteup_count%2Ccreated%2Cupdated%2Cupvoted_followees%2Cvoting%2Creview_info%2Creaction_instruction%2Cis_labeled%2Clabel_info%3Bdata%5B*%5D.vessay_info%3Bdata%5B*%5D.author.badge%5B%3F%28type%3Dbest_answerer%29%5D.topics%3Bdata%5B*%5D.author.vip_info%3B&offset=0&limit=20&sort_by=created\": 403 Forbidden\n",
      "id": "55435352270993409",
      "image": "https://pic1.zhimg.com/v2-c78eb026231e976049e9105170140ce3_l.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/L.M.Sherlock/posts",
      "title": "Thoughts Memo 的知乎文章",
      "type": "feed",
      "url": "rsshub://zhihu/posts/people/L.M.Sherlock"
    },
    {
      "description": "公众号：大猿搬砖简记 - Powered by RSSHub",
      "errorAt": "2025-04-22T11:33:42.477Z",
      "errorMessage": "[GET] \"https://www.zhihu.com/api/v4/members/lemonround/articles?include=data%5B*%5D.comment_count%2Csuggest_edit%2Cis_normal%2Cthumbnail_extra_info%2Cthumbnail%2Ccan_comment%2Ccomment_permission%2Cadmin_closed_comment%2Ccontent%2Cvoteup_count%2Ccreated%2Cupdated%2Cupvoted_followees%2Cvoting%2Creview_info%2Creaction_instruction%2Cis_labeled%2Clabel_info%3Bdata%5B*%5D.vessay_info%3Bdata%5B*%5D.author.badge%5B%3F%28type%3Dbest_answerer%29%5D.topics%3Bdata%5B*%5D.author.vip_info%3B&offset=0&limit=20&sort_by=created\": 403 Forbidden\n",
      "id": "66390660650222592",
      "image": "https://pic1.zhimg.com/v2-6304b8f8dd717ed99eeddd211d5714d1_l.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/people/lemonround/posts",
      "title": "猛猿 的知乎文章",
      "type": "feed",
      "url": "rsshub://zhihu/posts/people/lemonround"
    }
  ]
}
```
