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
  "heat": 34131,
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
      "image": "https://scontent-sin11-1.cdninstagram.com/v/t51.82787-19/550174606_17925811725103224_8363667901743352243_n.jpg?stp=dst-jpg_s150x150_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby4xMDgwLmMyIn0&_nc_ht=scontent-sin11-1.cdninstagram.com&_nc_cat=1&_nc_oc=Q6cZ2gHRkENYp0jsOKfm5UdJWYlOkga7pQGPCnV5dz0ODJNAbiCF5rK0O3-L60VwFhLk37-KcS30qR-2gXznAhUDu2i4&_nc_ohc=YLNRubrUt5oQ7kNvwH07zLP&_nc_gid=BSglshTD__zuQR39K1SptA&edm=APs17CUBAAAA&ccb=7-5&oh=00_Af9R3R8IPKOdtNCfxkMisMDmKPJXT-t5PjdiuuGx0XlA5g&oe=6A37E4FE&_nc_sid=10d13b",
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
      "image": "https://scontent-lhr8-1.cdninstagram.com/v/t51.2885-19/488156102_1160633875385251_3028278818063288032_n.jpg?stp=dst-jpg_s150x150_tt6&efg=eyJ2ZW5jb2RlX3RhZyI6InByb2ZpbGVfcGljLmRqYW5nby44NzkuYzIifQ&_nc_ht=scontent-lhr8-1.cdninstagram.com&_nc_cat=107&_nc_oc=Q6cZ2gHVnydXiz_C4NSe-y_qBoOyofrfcMxDAUekPL7CObKb16xDC6H_fE1SvK5xN8gWCHU&_nc_ohc=sIHj-Txpx-cQ7kNvwFFc88U&_nc_gid=ig1820wa0r8sJIog9lvzOQ&edm=APs17CUBAAAA&ccb=7-5&oh=00_Af9Hz-U9su_ZgPmljUIcdzaoNj1VkfiC1Q5FEgdE6J8GZw&oe=6A37D8C4&_nc_sid=10d13b",
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
