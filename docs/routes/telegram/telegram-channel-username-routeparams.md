# Telegram - Channel

## Coverage
`index-only`

## Route
- Namespace: `telegram`
- Namespace Name: `Telegram`
- Route Path: `/telegram/channel/:username/:routeParams?`
- Route Name: `Channel`
- Example: `/telegram/channel/awesomeRSSHub`
- URL: `t.me`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `DIYgod, Rongronggg9, synchrone, pseudoyu`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
::: tip
Due to Telegram restrictions, some channels involving pornography, copyright, and politics cannot be subscribed. You can confirm by visiting `https://t.me/s/:username`, it's recommended to deploy your own instance with telegram api configs (create your telegram application via `https://core.telegram.org/api/obtaining_api_id`, run this command `node ./lib/routes/telegram/scripts/get-telegram-session.mjs` to get `TELEGRAM_SESSION` and set it as Environment Variable).
:::

## Parameters
- `username`: channel username
- `routeParams`: extra parameters, see the table below
| Key                    | Description                                                           | Accepts                                            | Defaults to  |
| :--------------------: | :-------------------------------------------------------------------: | :------------------------------------------------: | :----------: |
| showLinkPreview        | Show the link preview from Telegram                                   | 0/1/true/false                                     | true         |
| showViaBot             | For messages sent via bot, show the bot                               | 0/1/true/false                                     | true         |
| showReplyTo            | For reply messages, show the target of the reply                      | 0/1/true/false                                     | true         |
| showFwdFrom            | For forwarded messages, show the forwarding source                    | 0/1/true/false                                     | true         |
| showFwdFromAuthor      | For forwarded messages, show the author of the forwarding source      | 0/1/true/false                                     | true         |
| showInlineButtons      | Show inline buttons                                                   | 0/1/true/false                                     | false        |
| showMediaTagInTitle    | Show media tags in the title                                          | 0/1/true/false                                     | true         |
| showMediaTagAsEmoji    | Show media tags as emoji                                              | 0/1/true/false                                     | true         |
| showHashtagAsHyperlink | Show hashtags as hyperlinks (`https://t.me/s/channel?q=%23hashtag`) | 0/1/true/false                                     | true         |
| includeFwd             | Include forwarded messages                                            | 0/1/true/false                                     | true         |
| includeReply           | Include reply messages                                                | 0/1/true/false                                     | true         |
| includeServiceMsg      | Include service messages (e.g. message pinned, channel photo updated) | 0/1/true/false                                     | true         |
| includeUnsupportedMsg  | Include messages unsupported by t.me                                  | 0/1/true/false                                     | false        |
| searchQuery            | search query                                                          | keywords; replace `#hashtag` with `%23hashtag` | (no keyword) |

Specify different option values than default values can meet different needs, URL

```
https://rsshub.app/telegram/channel/NewlearnerChannel/showLinkPreview=0&showViaBot=0&showReplyTo=0&showFwdFrom=0&showFwdFromAuthor=0&showInlineButtons=0&showMediaTagInTitle=1&showMediaTagAsEmoji=1&includeFwd=0&includeReply=1&includeServiceMsg=0&includeUnsupportedMsg=0
```

generates an RSS without any link previews and annoying metadata, with emoji media tags in the title, without forwarded messages (but with reply messages), and without messages you don't care about (service messages and unsupported messages), for people who prefer pure subscriptions.

For backward compatibility reasons, invalid `routeParams` will be treated as `searchQuery` .


## Features
- `requireConfig`: [{"description": "Telegram API Authentication", "name": "TELEGRAM_SESSION", "optional": true}, {"description": "Telegram API ID", "name": "TELEGRAM_API_ID", "optional": true}, {"description": "Telegram API Hash", "name": "TELEGRAM_API_HASH", "optional": true}, {"description": "Telegram Max Concurrent Downloads", "name": "TELEGRAM_MAX_CONCURRENT_DOWNLOADS", "optional": true}, {"description": "Telegram Proxy Host", "name": "TELEGRAM_PROXY_HOST", "optional": true}, {"description": "Telegram Proxy Port", "name": "TELEGRAM_PROXY_PORT", "optional": true}, {"description": "Telegram Proxy Secret", "name": "TELEGRAM_PROXY_SECRET", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `t.me/s/:username`
- `target`: `/channel/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "description": "::: tip\nDue to Telegram restrictions, some channels involving pornography, copyright, and politics cannot be subscribed. You can confirm by visiting `https://t.me/s/:username`, it's recommended to deploy your own instance with telegram api configs (create your telegram application via `https://core.telegram.org/api/obtaining_api_id`, run this command `node ./lib/routes/telegram/scripts/get-telegram-session.mjs` to get `TELEGRAM_SESSION` and set it as Environment Variable).\n:::",
  "example": "/telegram/channel/awesomeRSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Telegram API Authentication",
        "name": "TELEGRAM_SESSION",
        "optional": true
      },
      {
        "description": "Telegram API ID",
        "name": "TELEGRAM_API_ID",
        "optional": true
      },
      {
        "description": "Telegram API Hash",
        "name": "TELEGRAM_API_HASH",
        "optional": true
      },
      {
        "description": "Telegram Max Concurrent Downloads",
        "name": "TELEGRAM_MAX_CONCURRENT_DOWNLOADS",
        "optional": true
      },
      {
        "description": "Telegram Proxy Host",
        "name": "TELEGRAM_PROXY_HOST",
        "optional": true
      },
      {
        "description": "Telegram Proxy Port",
        "name": "TELEGRAM_PROXY_PORT",
        "optional": true
      },
      {
        "description": "Telegram Proxy Secret",
        "name": "TELEGRAM_PROXY_SECRET",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 293836,
  "location": "channel.ts",
  "maintainers": [
    "DIYgod",
    "Rongronggg9",
    "synchrone",
    "pseudoyu"
  ],
  "name": "Channel",
  "parameters": {
    "routeParams": "extra parameters, see the table below\n| Key                    | Description                                                           | Accepts                                            | Defaults to  |\n| :--------------------: | :-------------------------------------------------------------------: | :------------------------------------------------: | :----------: |\n| showLinkPreview        | Show the link preview from Telegram                                   | 0/1/true/false                                     | true         |\n| showViaBot             | For messages sent via bot, show the bot                               | 0/1/true/false                                     | true         |\n| showReplyTo            | For reply messages, show the target of the reply                      | 0/1/true/false                                     | true         |\n| showFwdFrom            | For forwarded messages, show the forwarding source                    | 0/1/true/false                                     | true         |\n| showFwdFromAuthor      | For forwarded messages, show the author of the forwarding source      | 0/1/true/false                                     | true         |\n| showInlineButtons      | Show inline buttons                                                   | 0/1/true/false                                     | false        |\n| showMediaTagInTitle    | Show media tags in the title                                          | 0/1/true/false                                     | true         |\n| showMediaTagAsEmoji    | Show media tags as emoji                                              | 0/1/true/false                                     | true         |\n| showHashtagAsHyperlink | Show hashtags as hyperlinks (`https://t.me/s/channel?q=%23hashtag`) | 0/1/true/false                                     | true         |\n| includeFwd             | Include forwarded messages                                            | 0/1/true/false                                     | true         |\n| includeReply           | Include reply messages                                                | 0/1/true/false                                     | true         |\n| includeServiceMsg      | Include service messages (e.g. message pinned, channel photo updated) | 0/1/true/false                                     | true         |\n| includeUnsupportedMsg  | Include messages unsupported by t.me                                  | 0/1/true/false                                     | false        |\n| searchQuery            | search query                                                          | keywords; replace `#hashtag` with `%23hashtag` | (no keyword) |\n\nSpecify different option values than default values can meet different needs, URL\n\n```\nhttps://rsshub.app/telegram/channel/NewlearnerChannel/showLinkPreview=0&showViaBot=0&showReplyTo=0&showFwdFrom=0&showFwdFromAuthor=0&showInlineButtons=0&showMediaTagInTitle=1&showMediaTagAsEmoji=1&includeFwd=0&includeReply=1&includeServiceMsg=0&includeUnsupportedMsg=0\n```\n\ngenerates an RSS without any link previews and annoying metadata, with emoji media tags in the title, without forwarded messages (but with reply messages), and without messages you don't care about (service messages and unsupported messages), for people who prefer pure subscriptions.\n\nFor backward compatibility reasons, invalid `routeParams` will be treated as `searchQuery` .\n",
    "username": "channel username"
  },
  "path": "/channel/:username/:routeParams?",
  "radar": [
    {
      "source": [
        "t.me/s/:username"
      ],
      "target": "/channel/:username"
    }
  ],
  "topFeeds": [
    {
      "description": "Founder of Telegram. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55779617166007296",
      "image": "https://cdn4.telesco.pe/file/kpi_9Aid-ILvfQdoa16ZH9HLtwpPf9II7F8MmRbhxIn6Ip7iwvxDn6zLtCHUpnp_aDUUMK1PTsaBtOPSNax6bPsXSj6z0cNEe21kBDtafh_bWFgmVW_8D4O52XY02bu8C-kfRRgBIiQSSHHrHAuXMmLKZHhCi6oMRuJQ31aTF2-FIpFugyi5nXTEhJ6NohSy5uHbE4d9AO60tEg42XIfjOQk6gc2Fs6hVmlTOR_1es_G9QHbpv1AznvRCZReFOM4JnvGwZ31d98LZX0_y1bcAaUpIpXEFbHEN6klKLSAuKJnlbyDOyRx-JYcgQBhK_Pyvzi1-R0mRIS2NOS8TZTnDw.jpg",
      "ownerUserId": null,
      "siteUrl": "https://t.me/s/durov",
      "title": "Pavel Durov - Telegram Channel",
      "type": "feed",
      "url": "rsshub://telegram/channel/durov"
    },
    {
      "description": "本群组主要分享白嫖机场、白嫖资源、白嫖线报、以及存放一些信息，嫖友聚居地哦频道的灌水群https://t.me/anranbpbbs需要真实邮箱怎么办对于需要真实邮箱验证的，大家可以下载手机版的网易邮箱大师，可以不限量注册163的邮箱各种超低价会员：Anran杂货铺， 优酷月仅需3元，百度网盘svip 1元起，52bp.icu阿里网盘资源搜索：公众号：彳亍说，发送 阿里 资源名称 即可百度网盘、迅雷、优酷会员分享：小程序：彳亍说小屋测试 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65367894677815296",
      "image": "https://cdn5.telesco.pe/file/up2bJvqefqjPOKvdHLwAoxskACi8VN3XQx3FXh-1zzIeUfQTL7ce1rBiaa1BNyw9WJIwY0C8co55gL428apwbxBRbv7Z_IACkM-mWJ9zQUvrVeFWN20UgPI_Bjwz8MEQdjXMghqkK4TEKd0IYM6mdCokL336p2S00ZbxHINU1XsG42Gx94OjtPOSXVTsFEqtll9moB2fFtsEs3znHLotGXsZOoqflf_h5wq_ZUVZuHxRaDt3gESdh7Of9Nt7KMV08RuhLEx4asfexKLGYFpZ31hrWE_7HabZzHSgN2F7JmvbZdSPpcGG9NGv-bu_r-IQaY5sCY02rXCnPouX6-7KwQ.jpg",
      "ownerUserId": null,
      "siteUrl": "https://t.me/s/anranbp",
      "title": "我爱白嫖 - Telegram Channel",
      "type": "feed",
      "url": "rsshub://telegram/channel/anranbp"
    }
  ],
  "view": 1
}
```
