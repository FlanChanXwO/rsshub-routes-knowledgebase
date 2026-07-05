# V2EX - 最热 / 最新主题

## Coverage
`index-only`

## Route
- Namespace: `v2ex`
- Namespace Name: `V2EX`
- Route Path: `/v2ex/topics/:type`
- Route Name: `最热 / 最新主题`
- Example: `/v2ex/topics/latest`
- URL: `v2ex.com`
- Language: `_None_`
- Categories: `bbs, popular`
- Maintainers: `WhiteWorld`
- Source Location: `topics.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: {"default": "hot", "description": "主题类型", "options": [{"label": "最热主题", "value": "hot"}, {"label": "最新主题", "value": "latest"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs",
    "popular"
  ],
  "example": "/v2ex/topics/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 23460,
  "location": "topics.ts",
  "maintainers": [
    "WhiteWorld"
  ],
  "name": "最热 / 最新主题",
  "parameters": {
    "type": {
      "default": "hot",
      "description": "主题类型",
      "options": [
        {
          "label": "最热主题",
          "value": "hot"
        },
        {
          "label": "最新主题",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/topics/:type",
  "topFeeds": [
    {
      "description": "V2EX-最热主题 - Powered by RSSHub",
      "errorAt": "2026-07-04T01:34:38.984Z",
      "errorMessage": "Failed query: insert into \"entries\" (\"feed_id\", \"id\", \"title\", \"url\", \"content\", \"description\", \"guid\", \"author\", \"author_url\", \"author_avatar\", \"inserted_at\", \"published_at\", \"media\", \"categories\", \"attachments\", \"extra\", \"language\", \"summary\", \"body_r2_key\", \"body_offloaded_at\") values ($1, $2, $3, $4, $5, $6, $7, $8, default, default, $9, $10, default, $11, default, default, default, default, default, default), ($12, $13, $14, $15, $16, $17, $18, $19, default, default, $20, $21, default, $22, default, default, default, default, default, default), ($23, $24, $25, $26, $27, $28, $29, $30, default, default, $31, $32, default, $33, default, default, default, default, default, default), ($34, $35, $36, $37, $38, $39, $40, $41, default, default, $42, $43, default, $44, default, default, default, default, default, default), ($45, $46, $47, $48, $49, $50, $51, $52, default, default, $53, $54, default, $55, default, default, default, default, default, default), ($56, $57, $58, $59, $60, $61, $62, $63, default, default, $64, $65, default, $66, default, default, default, default, default, default), ($67, $68, $69, $70, $71, $72, $73, $74, default, default, $75, $76, $77, $78, default, default, default, default, default, default), ($79, $80, $81, $82, $83, $84, $85, $86, default, default, $87, $88, $89, $90, default, default, default, default, default, default), ($91, $92, $93, $94, $95, $96, $97, $98, default, default, $99, $100, default, $101, default, default, default, default, default, default) on conflict (\"feed_id\",\"guid\") do update set \"title\" = excluded.\"title\", \"content\" = excluded.\"content\", \"description\" = excluded.\"description\", \"media\" = excluded.\"media\", \"attachments\" = excluded.\"attachments\", \"extra\" = COALESCE(\"entries\".\"extra\", '{}'::jsonb) || COALESCE(excluded.\"extra\", '{}'::jsonb) returning \"id\", \"published_at\", \"inserted_at\", \"feed_id\", \"title\", \"description\", \"content\", \"author\", \"url\", \"guid\", \"media\", \"attachments\"\nparams: 41147805268337669,1184272275713626112,咸粽子好吃还是甜粽子好吃？,https://www.v2ex.com/t/1224812,本人经常吃甜粽子，感觉甜粽子好吃，但是上一个端午节 朋友从南方寄过来几个咸粽子，有叉烧肉咸蛋黄的，有腊肉的还有一个是包的鲜肉粽。感觉都能接受呢？（把币扔给我🤣）,本人经常吃甜粽子，感觉甜粽子好吃，但是上一个端午节 朋友从南方寄过来几个咸粽子，有叉烧肉咸蛋黄的，有腊肉的还有一个是包的鲜肉粽。感觉都能接受呢？（把币扔给我🤣）,https://www.v2ex.com/t/1224812,11000111010,2026-07-04T03:11:05.257Z,2026-07-03T09:32:30.140Z,{\"美酒与美食\"},41147805268337669,1184272275713626113,我预判，第一波 AI 洪峰已过！,https://www.v2ex.com/t/1224778,<p>AI coding 趋势终于拐点了！</p>\n<p><strong>我预判，第一波 AI 洪峰已过。</strong></p>\n<p>据我观察<strong>4 个方面</strong>:</p>\n<p>1 、第三方价格数据(暴跌，需求减少)：</p>\n<p>GeminiPro 一年会员自动开通 CDK 包绑卡订阅 <strong>¥12</strong></p>\n<p>ChatGPT  [带 RT ]  [ Plus 成品号]  <strong>¥15</strong></p>\n<p>2 、v 站数据（话题占比下降）：</p>\n<p>据观察 V 站上月 AI 话题占比趋近 100%，当前占比也有下降趋势</p>\n<p>3 、个人数据：</p>\n<p>短期使用量，也明显下跌。不可能永远有新项目，只有初版稳定之后就不会再有暴力 token 需求。</p>\n<p>4 、小红书数据：</p>\n<p>前段时间->vibe coding 帖子热度极高。</p>\n<p>很多<strong>不懂代码的人</strong>。</p>\n<p>偶然有一个/多个想法->开通 ai 会员(短期)->生成 app （养猫\\遛狗\\逗娃..）</p>\n<p>后面在于推广维护，短期很难再有一个新想法。</p>\n<p><strong>看懂趋势比埋头苦干更有价值！</strong></p>\n<p>真的需要，<strong>说说大家的感觉</strong>，比如公司使用，个人观察，中转站数据？</p>\n,AI coding 趋势终于拐点了！ 我预判，第一波 AI 洪峰已过。\n\n据我观察4 个方面:\n\n1 、第三方价格数据(暴跌，需求减少)：\n\nGeminiPro 一年会员自动开通 CDK 包绑卡订阅 ¥12\n\nChatGPT [带 RT ] [ Plus 成品号] ¥15\n\n2 、v…,https://www.v2ex.com/t/1224778,123128xyz,2026-07-04T03:11:05.256Z,2026-07-03T07:54:25.231Z,{\"程序员\"},41147805268337669,1184272275713626114,家里孩子生了，请帮忙取个名字,https://www.v2ex.com/t/1224777,<p>姓先不跟你们说了。\n麻烦帮忙取下吧。</p>\n,姓先不跟你们说了。 麻烦帮忙取下吧。,https://www.v2ex.com/t/1224777,gotOwt,2026-07-04T03:11:05.255Z,2026-07-03T07:52:51.747Z,{\"问与答\"},41147805268337669,1184272275713626115,因存在植入后门风险，阿里内部全面禁用 Claude Code,https://www.v2ex.com/t/1224766,自 7 月 10 日起，阿里将全面禁止内部员工在办公环境下使用 Claude Code ，并推荐使用 Qoder 作为替代方案。<br>这是玩不起了吗,自 7 月 10 日起，阿里将全面禁止内部员工在办公环境下使用 Claude Code ，并推荐使用 Qoder 作为替代方案。 这是玩不起了吗,https://www.v2ex.com/t/1224766,syc001,2026-07-04T03:11:05.254Z,2026-07-03T07:16:44.583Z,{\"问与答\"},41147805268337669,1184272275713626116,看《感觉女友很爱去看演唱会，不想让她去怎么办》有感，人生真正的享受是什么,https://www.v2ex.com/t/1224760,<p>贴一下原文：<a href=\"https://www.v2ex.com/t/1224428#reply273\" target=\"_blank\">感觉女友很爱去看演唱会，不想让她去怎么办</a><br>\n作为我个人肯定觉得去看演唱会，费钱又费精力。不如自己呆在空调房里，打打游戏、睡睡觉、vibecoding 一下、看看电影。<br>\n但从他女朋友的角度，可能人家就是喜欢追星呢，就喜欢花大几千去看演唱会呢<br>\n各位觉得人生真正的享受是什么样的</p>\n,贴一下原文：感觉女友很爱去看演唱会，不想让她去怎么办 作为我个人肯定觉得去看演唱会，费钱又费精力。不如自己呆在空调房里，打打游戏、睡睡觉、vibecoding 一下、看看电影。\n 但从他女朋友的角度，可能人家就是喜欢追星呢，就喜欢花大几千去看演唱会呢\n 各位觉得人生真正的享受是什么样…,https://www.v2ex.com/t/1224760,rxswift,2026-07-04T03:11:05.253Z,2026-07-03T06:52:37.537Z,{\"生活\"},41147805268337669,1184272275713626117,赛格那件事有后续了，但是我有点理解不了舆论,https://www.v2ex.com/t/1224739,上下文帖子： <a href=\"https://www.v2ex.com/t/1224349\" target=\"_blank\">https://www.v2ex.com/t/1224349</a><br>赛格公告： <a href=\"https://mp.weixin.qq.com/s/iKLKHV7KaW3QlQg1Je-hNg\" target=\"_blank\">https://mp.weixin.qq.com/s/iKLKHV7KaW3QlQg1Je-hNg</a><br><br>昨天我就觉得疑点很多，顺手多搜了下：<br>   1. 出事的不是所谓的小人物，运动品牌地区代理，手握好多品牌，几百家门店，流水几十亿。<br>      -- 这种体量的人为什么被 1000w+ 的罚款搞死了，罚款是根因，还是压死骆驼的稻草。今天公告也说，提到他本身公司经营不善了。<br>   2. 为什么只罚他，并且金额这么巨大，他到底套现了多少，让商场这么罚款。<br>      -- 今天公告里说了相关的，但是没正面回复。合同说明了不能拆单去用，他们还用券帮外地经销商拿货，我觉得这个行为过分了，但是你经商，要赚黑钱，就要有心理去承受这罚款。<br><br>大部分网友们的反应是：<br>\t赛格未出公告前：资本逼死小人物。<br>\t赛格出公告后：你信赛格的公告还是信我是秦始皇，这都是资本的手段，资本可真厉害啊。<br>    <br>我不是给商场开脱，我也没全信商场的发言，况且我觉得商场也有好多信息没解释，比如有没有让强制退场等。<br>我只是觉得这件事疑点太多了，但是舆论关注点大部分都是资本搞死小人物的叙事上，什么都不去想，什么也听不进去。,上下文帖子： https://www.v2ex.com/t/1224349 赛格公告： https://mp.weixin.qq.com/s/iKLKHV7KaW3QlQg1Je-hNg\n\n昨天我就觉得疑点很多，顺手多搜了下：\n 1. 出事的不是所谓的小人物，运动品牌地区代理…,https://www.v2ex.com/t/1224739,catning,2026-07-04T03:11:05.252Z,2026-07-03T04:47:19.245Z,{\"问与答\"},41147805268337669,1184272275713626118,[OneDayAI] 先送后卖，新老用户留言即送一周套餐，每 20 楼抽 20 刀充值额度,https://www.v2ex.com/t/1224726,<p>距离上次推广已过去三个月，我们还在且一如既往保持 <strong>兼容+稳定+性价比+低试错</strong>。</p>\n<p>正值系统大升级完成节点，再来 V 站推广一波，带来了一些福利。</p>\n<p>🎉🎉🎉 还是老规矩了，本帖发布<strong>24 小时</strong>内留言就送。</p>\n<h2>网址</h2>\n<p><a href=\"https://api.autocode.space\" target=\"_blank\">https://api.autocode.space</a></p>\n<h2>福利</h2>\n<ol>\n<li><strong>新老用户在本帖留言即送一周套餐（ 24 小时 5 刀，7 天 10 刀）</strong>，可前往<a href=\"https://api.autocode.space/console/subscription-self\" target=\"_blank\"><strong>订阅管理</strong></a> 查询</li>\n<li>每 20 楼抽 20 刀充值额度</li>\n</ol>\n<h2>变化</h2>\n<ul>\n<li>之前被疯狂薅羊毛的签到重新开放</li>\n<li>系统支持更丰富的套餐设定，动态让利更简单</li>\n<li>任意分组均支持 Anthropic Claude 、OpenAI 、OpenAI-Responses 三协议互转</li>\n</ul>\n<blockquote>\n<p>只要是标准格式的客户端均支持调用：Codex 调用 Claude 、Claude Code 调用 Codex 、OpenCode 调用 Claude 、Codex ，想怎么用就怎么样</p>\n</blockquote>\n<ul>\n<li>支持在线申请开票</li>\n</ul>\n<h3>价格表</h3>\n<table>\n<thead>\n<tr>\n<th>线路</th>\n<th>价格</th>\n<th>备注</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td>Codex</td>\n<td>0.15 元/刀</td>\n<td>支持三协议调用</td>\n</tr>\n<tr>\n<td>Codex Pro</td>\n<td>0.4 元/刀</td>\n<td>支持三协议调用</td>\n</tr>\n<tr>\n<td>CCMAX 不限制客户端</td>\n<td>1.5 元/刀</td>\n<td>支持三协议调用</td>\n</tr>\n<tr>\n<td>CCMAX 限制客户端</td>\n<td>1 元/刀</td>\n<td>支持三协议调用</td>\n</tr>\n<tr>\n<td>kiro （ vip ）</td>\n<td>0.4 元/刀</td>\n<td>支持三协议调用</td>\n</tr>\n</tbody></table><p>一如既往保持 <strong>兼容性+稳定性+性价比+低试错</strong>。</p>\n<ul>\n<li><strong>兼容性</strong>：自研的泛化调用网关，支持三协议任意调用后准确转化成源站支持格式</li>\n<li><strong>稳定性</strong>：自研的网关支持多线路故障转移负载均衡</li>\n<li><strong>性价比</strong>：没有挤牙膏式的降价，C 端价格薄利多销</li>\n<li><strong>低试错</strong>：1 元起充，好用再充。</li>\n</ul>\n<h4>企业用户</h4>\n<ol>\n<li>独立的 B 端站点，服务器资源冗余，平滑支撑数千 RPM</li>\n<li>支持对公转账、企业开票</li>\n<li>法大大电子签合同签订</li>\n</ol>\n<h3>标准姿势</h3>\n<blockquote>\n<p>Github 注册 -> <a href=\"https://api.autocode.space/console/personal\" target=\"_blank\">获取用户 ID</a> -> V 站留言 -> 进群 push 群主加套餐</p>\n</blockquote>\n<h3>交流群</h3>\n<p>AI 技术交流群可进微信群，业务沟通进 TG 群，感谢理解。</p>\n<table>\n<thead>\n<tr>\n<th>AI 技术交流二群</th>\n<th>AI 技术交流三群</th>\n<th>业务沟通 TG 群</th>\n</tr>\n</thead>\n<tbody>\n<tr>\n<td><img alt=\"二群\" src=\"https://i.v2ex.co/4n9em0Nv.jpeg\"></td>\n<td><img alt=\"三群\" src=\"https://i.v2ex.co/x88l9cnJ.jpeg\"></td>\n<td><a href=\"https://t.me/+3U1DiC_up3w3NzFh\" target=\"_blank\">https://t.me/+3U1DiC_up3w3NzFh</a></td>\n</tr>\n</tbody></table>,距离上次推广已过去三个月，我们还在且一如既往保持 兼容+稳定+性价比+低试错。 正值系统大升级完成节点，再来 V 站推广一波，带来了一些福利。\n\n🎉🎉🎉 还是老规矩了，本帖发布24 小时内留言就送。\n\n网址\n\nhttps://api.autocode.space\n\n福利\n新老用户…,https://www.v2ex.com/t/1224726,dockerhub,2026-07-04T03:11:05.251Z,2026-07-03T04:00:58.069Z,[{\"url\":\"https://i.v2ex.co/4n9em0Nv.jpeg\",\"type\":\"photo\",\"width\":930,\"height\":1440},{\"url\":\"https://i.v2ex.co/x88l9cnJ.jpeg\",\"type\":\"photo\"}],{\"推广\"},41147805268337669,1184272275713626119,“有个东西，也是我今天才学到的，叫 CDN”,https://www.v2ex.com/t/1224709,<p><img alt=\"\" src=\"https://i.imgur.com/SMB70MK.png\"></p>\n<p><a href=\"https://mp.weixin.qq.com/s/L6R_SPWlOBv6dI0wWWHQrg\" target=\"_blank\">https://mp.weixin.qq.com/s/L6R_SPWlOBv6dI0wWWHQrg</a></p>\n<p>作者已编辑</p>\n,https://mp.weixin.qq.com/s/L6R_SPWlOBv6dI0wWWHQrg 作者已编辑,https://www.v2ex.com/t/1224709,tf2,2026-07-04T03:11:05.250Z,2026-07-03T03:18:56.858Z,[{\"url\":\"https://i.imgur.com/SMB70MK.png\",\"type\":\"photo\",\"width\":699,\"height\":461}],{\"分享发现\"},41147805268337669,1184272275713626120,现在备案域名的流程又臭又长,https://www.v2ex.com/t/1224707,最近申请了域名备案，发现不仅过管局，还要在公安联网备案。这公安联网备案的网站是真的垃圾，网页端注册一半让你去下个 app ，下完 app 用刚注册的账号登录还登录不进去，然后又重新注册一遍，看了 ios 商店里全是骂这勾八 app ，搞不懂都在工信部备案了为啥还要同样的信息再在公安在搞一遍，你要说多加一道流程捞经费我也认了，我 chovy 啊，你捞油水倒是把网站和 app 做好了啊,最近申请了域名备案，发现不仅过管局，还要在公安联网备案。这公安联网备案的网站是真的垃圾，网页端注册一半让你去下个 app ，下完 app 用刚注册的账号登录还登录不进去，然后又重新注册一遍，看了 ios 商店里全是骂这勾八 app…,https://www.v2ex.com/t/1224707,Teresa789,2026-07-04T03:11:05.249Z,2026-07-03T03:16:02.877Z,{\"程序员\"}",
      "id": "41147805268337669",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.v2ex.com/",
      "title": "V2EX-最热主题",
      "type": "feed",
      "url": "rsshub://v2ex/topics/hot"
    },
    {
      "description": "V2EX-最新主题 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41374278075966464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.v2ex.com/",
      "title": "V2EX-最新主题",
      "type": "feed",
      "url": "rsshub://v2ex/topics/latest"
    }
  ],
  "view": 0
}
```
