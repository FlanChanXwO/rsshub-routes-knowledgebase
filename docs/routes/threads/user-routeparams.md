# Threads - User timeline

## Coverage
`index-only`

## Route
- Namespace: `threads`
- Namespace Name: `Threads`
- Route Path: `/:user/:routeParams?`
- Route Name: `User timeline`
- Example: `/threads/zuck`
- URL: `threads.net`
- Language: `en`
- Categories: `social-media`
- Maintainers: `ninboy, pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/threads/index.ts')`

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
    "social-media"
  ],
  "example": "/threads/zuck",
  "location": "index.ts",
  "maintainers": [
    "ninboy",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/threads/index.ts')",
  "name": "User timeline",
  "parameters": {
    "routeParams": {
      "description": "Extra parameters, see the table below\nSpecify options (in the format of query string) in parameter `routeParams` to control some extra features for threads\n\n| Key                            | Description                                                                                                                  | Accepts                | Defaults to |\n| ------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | ---------------------- | ----------- |\n| `showAuthorInTitle`            | Show author name in title                                                                                                    | `0`/`1`/`true`/`false` | `true`      |\n| `showAuthorInDesc`             | Show author name in description (RSS body)                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedAuthorAvatarInDesc` | Show avatar of quoted author in description (RSS body) (Not recommended if your RSS reader extracts images from description) | `0`/`1`/`true`/`false` | `false`     |\n| `showAuthorAvatarInDesc`       | Show avatar of author in description (RSS body) (Not recommended if your RSS reader extracts images from description)        | `0`/`1`/`true`/`false` | `falseP`    |\n| `showEmojiForQuotesAndReply`   | Use \"🔁\" instead of \"QT\", \"↩️\" instead of \"Re\"                                                                               | `0`/`1`/`true`/`false` | `true`      |\n| `showQuotedInTitle`            | Show quoted tweet in title                                                                                                   | `0`/`1`/`true`/`false` | `true`      |\n| `replies`                      | Show replies                                                                                                                 | `0`/`1`/`true`/`false` | `true`      |"
    },
    "user": "Username"
  },
  "path": "/:user/:routeParams?",
  "view": 1
}
```
