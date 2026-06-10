# Threads - User timeline

## Coverage
`index-only`

## Route
- Namespace: `threads`
- Namespace Name: `Threads`
- Route Path: `/threads/:user/:routeParams?`
- Route Name: `User timeline`
- Example: `/threads/zuck`
- URL: `threads.net`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `ninboy, pseudoyu`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: Username
- `routeParams`: {"description": "Extra parameters, see the table below\nSpecify options (in the format of query string) in parameter `routeParams` to control some extra features for threads\n\n| Key                            | Description                                                                                                                  | Accepts                | Defaults to |\n| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------- |\n| `showAuthorInTitle`            | Show author name in title                                                                                                    | `0`/`1`/`true`/`false` | `true`      |\n| `showAuthorInDesc`             | Show author name in description (RSS body)                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedAuthorAvatarInDesc` | Show avatar of quoted author in description (RSS body) (Not recommended if your RSS reader extracts images from description) | `0`/`1`/`true`/`false` | `false`     |\n| `showAuthorAvatarInDesc`       | Show avatar of author in description (RSS body) (Not recommended if your RSS reader extracts images from description)        | `0`/`1`/`true`/`false` | `falseP`    |\n| `showEmojiForQuotesAndReply`   | Use \"🔁\" instead of \"QT\", \"↩️\" instead of \"Re\"                                                                               | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedInTitle`            | Show quoted tweet in title                                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `replies`                      | Show replies                                                                                                                 | `0`/`1`/`true`/`false` | `true`      |"}


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/threads/zuck",
  "heat": 34299,
  "location": "index.ts",
  "maintainers": [
    "ninboy",
    "pseudoyu"
  ],
  "name": "User timeline",
  "parameters": {
    "routeParams": {
      "description": "Extra parameters, see the table below\nSpecify options (in the format of query string) in parameter `routeParams` to control some extra features for threads\n\n| Key                            | Description                                                                                                                  | Accepts                | Defaults to |\n| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------- |\n| `showAuthorInTitle`            | Show author name in title                                                                                                    | `0`/`1`/`true`/`false` | `true`      |\n| `showAuthorInDesc`             | Show author name in description (RSS body)                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedAuthorAvatarInDesc` | Show avatar of quoted author in description (RSS body) (Not recommended if your RSS reader extracts images from description) | `0`/`1`/`true`/`false` | `false`     |\n| `showAuthorAvatarInDesc`       | Show avatar of author in description (RSS body) (Not recommended if your RSS reader extracts images from description)        | `0`/`1`/`true`/`false` | `falseP`    |\n| `showEmojiForQuotesAndReply`   | Use \"🔁\" instead of \"QT\", \"↩️\" instead of \"Re\"                                                                               | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedInTitle`            | Show quoted tweet in title                                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `replies`                      | Show replies                                                                                                                 | `0`/`1`/`true`/`false` | `true`      |"
    },
    "user": "Username"
  },
  "path": "/:user/:routeParams?",
  "topFeeds": [
    {
      "description": "zuck (@zuck) on Threads - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "45996937449535488",
      "image": "https://scontent-sin11-1.cdninstagram.com/v/t51.82787-19/550174606_17925811725103224_8363667901743352243_n.jpg?stp=dst-jpg_s150x150_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-sin11-1.cdninstagram.com&_nc_cat=1&_nc_oc=Q6cZ2gH9InF-QD39jTg7LrhbOWxRP_kHC_NuOLaYZ1gBlBx9FriOTZchfVIcjzIgbQHN1wEV0yEjxJUo_lh9NquuoxIc&_nc_ohc=11fxnRtMGhUQ7kNvwGNFTXC&_nc_gid=oUn6qmfjO0JCd8CBhL0gQA&edm=APs17CUBAAAA&ccb=7-5&oh=00_Af8nj_4TSco-SC8daFqeg8MQOb5pMoVKlB14GVLUWcadkA&oe=6A2D58FE&_nc_sid=10d13b",
      "ownerUserId": null,
      "siteUrl": "https://www.threads.com/@zuck",
      "title": "zuck (@zuck) on Threads",
      "type": "feed",
      "url": "rsshub://threads/zuck"
    },
    {
      "description": "hecaitou (@hecaitou) on Threads - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71435314045960192",
      "image": "https://scontent-lga3-2.cdninstagram.com/v/t51.2885-19/488156102_1160633875385251_3028278818063288032_n.jpg?stp=dst-jpg_s150x150_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby44NzkuYzIifQ&_nc_ht=scontent-lga3-2.cdninstagram.com&_nc_cat=107&_nc_oc=Q6cZ2gFEgpz0Z4p7xkryRyYNhO7Yo8BSOAAv8rAWMV9JkOEdIKxIBFQEKxIkgDCR-F4hhHQ&_nc_ohc=F5ruv_HaFxIQ7kNvwEkYs73&_nc_gid=rdsBshyyqoluT-tl_jHEXA&edm=APs17CUBAAAA&ccb=7-5&oh=00_Af-DrgJqKlZLEVG9_mD6poWYRIJcbgDMpFnTLYsTgcablg&oe=6A2D1484&_nc_sid=10d13b",
      "ownerUserId": null,
      "siteUrl": "https://www.threads.com/@hecaitou",
      "title": "hecaitou (@hecaitou) on Threads",
      "type": "feed",
      "url": "rsshub://threads/hecaitou"
    }
  ],
  "view": 1
}
```
