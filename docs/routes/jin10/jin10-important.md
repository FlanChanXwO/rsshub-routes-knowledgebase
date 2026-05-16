# 金十数据 - 市场快讯

## Coverage
`index-only`

## Route
- Namespace: `jin10`
- Namespace Name: `金十数据`
- Route Path: `/jin10/:important?`
- Route Name: `市场快讯`
- Example: `/jin10`
- URL: `jin10.com/`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `laampui`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `important`: 只看重要，任意值开启，留空关闭


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
  - `jin10.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "example": "/jin10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2454,
  "location": "index.ts",
  "maintainers": [
    "laampui"
  ],
  "name": "市场快讯",
  "parameters": {
    "important": "只看重要，任意值开启，留空关闭"
  },
  "path": "/:important?",
  "radar": [
    {
      "source": [
        "jin10.com/"
      ],
      "target": ""
    }
  ],
  "topFeeds": [
    {
      "description": "金十数据 - Powered by RSSHub",
      "errorAt": "2026-05-15T02:58:57.228Z",
      "errorMessage": "Failed query: insert into \"entries\" (\"feed_id\", \"id\", \"title\", \"url\", \"content\", \"description\", \"guid\", \"author\", \"author_url\", \"author_avatar\", \"inserted_at\", \"published_at\", \"media\", \"categories\", \"attachments\", \"extra\", \"language\", \"summary\", \"body_r2_key\", \"body_offloaded_at\") values ($1, $2, $3, default, $4, $5, $6, default, default, default, $7, $8, default, default, default, default, default, default, default, default), ($9, $10, $11, default, $12, $13, $14, default, default, default, $15, $16, default, default, default, default, default, default, default, default), ($17, $18, $19, default, $20, $21, $22, default, default, default, $23, $24, default, default, default, default, default, default, default, default), ($25, $26, $27, default, $28, $29, $30, default, default, default, $31, $32, default, default, default, default, default, default, default, default), ($33, $34, $35, default, $36, $37, $38, default, default, default, $39, $40, default, default, default, default, default, default, default, default), ($41, $42, $43, default, $44, $45, $46, default, default, default, $47, $48, default, default, default, default, default, default, default, default), ($49, $50, $51, default, $52, $53, $54, default, default, default, $55, $56, default, default, default, default, default, default, default, default), ($57, $58, $59, default, $60, $61, $62, default, default, default, $63, $64, default, default, default, default, default, default, default, default), ($65, $66, $67, default, $68, $69, $70, default, default, default, $71, $72, default, default, default, default, default, default, default, default), ($73, $74, $75, default, $76, $77, $78, default, default, default, $79, $80, default, default, default, default, default, default, default, default), ($81, $82, $83, default, $84, $85, $86, default, default, default, $87, $88, default, default, default, default, default, default, default, default), ($89, $90, $91, default, $92, $93, $94, default, default, default, $95, $96, default, default, default, default, default, default, default, default), ($97, $98, $99, default, $100, $101, $102, default, default, default, $103, $104, default, default, default, default, default, default, default, default), ($105, $106, $107, default, $108, $109, $110, default, default, default, $111, $112, $113, default, default, default, default, default, default, default), ($114, $115, $116, $117, $118, $119, $120, default, default, default, $121, $122, $123, default, default, default, default, default, default, default), ($124, $125, $126, default, $127, $128, $129, default, default, default, $130, $131, default, default, default, default, default, default, default, default), ($132, $133, $134, default, $135, $136, $137, default, default, default, $138, $139, default, default, default, default, default, default, default, default), ($140, $141, $142, default, $143, $144, $145, default, default, default, $146, $147, default, default, default, default, default, default, default, default), ($148, $149, $150, default, $151, $152, $153, default, default, default, $154, $155, default, default, default, default, default, default, default, default), ($156, $157, $158, default, $159, $160, $161, default, default, default, $162, $163, default, default, default, default, default, default, default, default), ($164, $165, $166, default, $167, $168, $169, default, default, default, $170, $171, default, default, default, default, default, default, default, default) on conflict (\"feed_id\",\"guid\") do update set \"title\" = excluded.\"title\", \"content\" = excluded.\"content\", \"description\" = excluded.\"description\", \"media\" = excluded.\"media\", \"attachments\" = excluded.\"attachments\", \"extra\" = COALESCE(\"entries\".\"extra\", '{}'::jsonb) || COALESCE(excluded.\"extra\", '{}'::jsonb) returning \"id\", \"published_at\", \"inserted_at\", \"feed_id\", \"title\", \"description\", \"content\", \"author\", \"url\", \"guid\", \"media\", \"attachments\"\nparams: 44366244616936448,1111781045268557824,习近平同美国总统特朗普在中南海小范围会晤,金十数据5月15日讯，5月15日，国家主席习近平在中南海同美国总统特朗普举行小范围会晤。,金十数据5月15日讯，5月15日，国家主席习近平在中南海同美国总统特朗普举行小范围会晤。,jin10:index:20260515105632139800,2026-05-15T02:58:38.834Z,2026-05-15T02:56:32.398Z,44366244616936448,1111781045268557825,特朗普乘车抵达中南海,金十数据5月15日讯，5月15日，美国总统特朗普乘车抵达中南海。,金十数据5月15日讯，5月15日，美国总统特朗普乘车抵达中南海。,jin10:index:20260515105540362800,2026-05-15T02:58:38.833Z,2026-05-15T02:55:40.366Z,44366244616936448,1111781045268557826,外交部发言人就伊朗局势答记者问,金十数据5月15日讯，外交部发言人表示，近来，美伊实现停火，探索通过谈判解决问题，受到地区国家和国际社会欢迎。中方始终认为，对话谈判才是正道，武力解决没有出路。对话的大门既然打开，就不应再次关上。应稳住局势缓和势头，坚持政治解决大方向，通过对话协商，就伊核等问题达成兼顾各方关切的解决方案。应尽快重开航道，回应国际社会呼声，共同维护全球产供链稳定畅通。应尽快达成全面、持久停火，推动中东海湾局势早日恢复和平稳定，为构建一个可持续的地区安全架构奠定基础。,金十数据5月15日讯，外交部发言人表示，近来，美伊实现停火，探索通过谈判解决问题，受到地区国家和国际社会欢迎。中方始终认为，对话谈判才是正道，武力解决没有出路。对话的大门既然打开，就不应再次关上。应稳住局势缓和势头，坚持政治解决大方向，通过对话协商…,jin10:index:20260515105046941800,2026-05-15T02:58:38.832Z,2026-05-15T02:50:46.366Z,44366244616936448,1111781045268557827,<b>科创50指数翻红，此前一度跌超2%。</b>,<b>科创50指数翻红，此前一度跌超2%。</b>,科创50指数翻红，此前一度跌超2%。,jin10:index:20260515104958356800,2026-05-15T02:58:38.831Z,2026-05-15T02:49:58.635Z,44366244616936448,1111781045268557828,日本食品企业纷纷调整包装设计 农林水产大臣声称油墨供应充足,金十数据5月15日讯，据日本共同社，在15日的记者会上，日本农林水产大臣铃木宪和就食品行业因印刷油墨采购状况不稳定而出现的调整包装设计的趋势发表了看法。他表示：“虽然目前的包装使用‘尚无问题’，但业界正出于预防目的，着手探讨进行调整。”他同时强调，目前油墨供应量与平时相同，能够满足所需需求。石脑油是塑料的原材料，也是印刷油墨的原材料。铃木指出：“这些举措是基于各企业自身的商业判断而采取的，旨在为未来可能出现的供应中断风险做好准备。”他进一步澄清道：“我并不认为这是因中东局势而直接引发的食品供应方面的问题。”在食品行业中，包装设计调整的动向愈发明显。例如，卡乐比已将薯片产品包装改为黑白双色设计。,金十数据5月15日讯，据日本共同社，在15日的记者会上，日本农林水产大臣铃木宪和就食品行业因印刷油墨采购状况不稳定而出现的调整包装设计的趋势发表了看法。他表示：“虽然目前的包装使用‘尚无问题’，但业界正出于预防目的，着手探讨进行调整。”他同时强调，目前油墨供应量与平时相同…,jin10:index:20260515104927843800,2026-05-15T02:58:38.830Z,2026-05-15T02:49:27.028Z,44366244616936448,1111781045268557829,*ST美芝盘中涨停，上演“地天板”，成交额2.67亿元。,*ST美芝盘中涨停，上演“地天板”，成交额2.67亿元。,*ST美芝盘中涨停，上演“地天板”，成交额2.67亿元。,jin10:index:20260515104924019800,2026-05-15T02:58:38.829Z,2026-05-15T02:49:24.530Z,44366244616936448,1111781045268557830,摩根大通：即使海峡在6月重开，库存压力仍将支撑高油价,摩根大通：即使海峡在6月重开，库存压力仍将支撑高油价,摩根大通：即使海峡在6月重开，库存压力仍将支撑高油价,jin10:index:20260515104806319800,2026-05-15T02:58:38.828Z,2026-05-15T02:48:06.702Z,44366244616936448,1111781045268557831,SC原油主力合约日内涨幅达2.00%，现报643.50元/桶。,SC原油主力合约日内涨幅达2.00%，现报643.50元/桶。,SC原油主力合约日内涨幅达2.00%，现报643.50元/桶。,jin10:index:20260515104755103800,2026-05-15T02:58:38.827Z,2026-05-15T02:47:55.907Z,44366244616936448,1111781045268557832,外交部：中美元首达成一系列新共识,金十数据5月15日讯，外交部发言人表示，5月14日，习近平主席为特朗普总统举行欢迎仪式和欢迎宴会，同特朗普总统举行会谈，并共同参观天坛。两国元首就事关两国和世界的重大问题深入交换意见，达成一系列新共识。两国元首赞同将构建“中美建设性战略稳定关系”作为中美关系新定位，为未来3年乃至更长时间的中美关系提供战略指引，推动两国关系稳定、健康、可持续发展，为世界带来更多和平、繁荣、进步。两国元首还就妥善处理彼此关切达成重要共识，同意就国际地区问题加强沟通和协调。,金十数据5月15日讯，外交部发言人表示，5月14日，习近平主席为特朗普总统举行欢迎仪式和欢迎宴会，同特朗普总统举行会谈，并共同参观天坛。两国元首就事关两国和世界的重大问题深入交换意见，达成一系列新共识。两国元首赞同将构建“中美建设性战略稳定关系”作为中美关系新定位…,jin10:index:20260515104537417800,2026-05-15T02:58:38.826Z,2026-05-15T02:45:37.278Z,44366244616936448,1111781045268557833,期货热点追踪,低库存与基差修复支撑鸡蛋近月强势，后半段产能集中释放风险暗藏，鸡蛋市场趋势性行情还能持续多久？,低库存与基差修复支撑鸡蛋近月强势，后半段产能集中释放风险暗藏，鸡蛋市场趋势性行情还能持续多久？,jin10:index:20260515104339121800,2026-05-15T02:58:38.825Z,2026-05-15T02:43:39.770Z,44366244616936448,1111781045268557834,新加坡航空CEO：尽管存在中东冲突的影响，仍将继续扩展航空网络。,新加坡航空CEO：尽管存在中东冲突的影响，仍将继续扩展航空网络。,新加坡航空CEO：尽管存在中东冲突的影响，仍将继续扩展航空网络。,jin10:index:20260515104242914800,2026-05-15T02:58:38.824Z,2026-05-15T02:42:42.205Z,44366244616936448,1111781045268557835,也门冲突双方就释放被扣押人员达成协议 古特雷斯表示欢迎,金十数据5月15日讯，当地时间14日晚，联合国秘书长古特雷斯通过发言人发表声明，欢迎也门冲突双方当天达成协议，将释放1600余名与冲突相关的被扣押人员。古特雷斯呼吁各方与红十字国际委员会合作，迅速落实该协议。他还呼吁各方根据2018年《斯德哥尔摩协议》所承担的义务，继续推动进一步释放行动，实现“全部换全部”的冲突相关被扣押人员释放。。,金十数据5月15日讯，当地时间14日晚，联合国秘书长古特雷斯通过发言人发表声明，欢迎也门冲突双方当天达成协议，将释放1600余名与冲突相关的被扣押人员。古特雷斯呼吁各方与红十字国际委员会合作，迅速落实该协议。他还呼吁各方根据2018年《斯德哥尔摩协议》所承担的义务…,jin10:index:20260515104154147800,2026-05-15T02:58:38.823Z,2026-05-15T02:41:54.632Z,44366244616936448,1111781045268557836,机构：获利了结令韩国股市在短触高位后回落,金十数据5月15日讯，韩国股市周五一度突破8000点历史关口，但随后迅速转跌，跌幅超3%。美国总统特朗普针对伊朗的强硬表态，引发市场获利了结。尽管如此，韩国KOSPI指数本周累计仍上涨超过3%，有望实现连续第六周的上涨。未来资产证券分析师Seo Sang-young表示：“在特朗普表示对伊朗不会再保持耐心后，美国股指期货转跌，韩国市场也随之扩大跌幅。”特朗普在周四晚播出的采访中表示，他对伊朗的耐心已经接近极限，并敦促德黑兰尽快与华盛顿达成协议。,金十数据5月15日讯，韩国股市周五一度突破8000点历史关口，但随后迅速转跌，跌幅超3%。美国总统特朗普针对伊朗的强硬表态，引发市场获利了结。尽管如此，韩国KOSPI指数本周累计仍上涨超过3%，有望实现连续第六周的上涨。未来资产证券分析师Seo Sang-young表示…,jin10:index:20260515104038955800,2026-05-15T02:58:38.822Z,2026-05-15T02:40:38.297Z,44366244616936448,1111781045268557837,主力资金流向前十大个股,金十数据5月15日讯，截至2026年05月15日（周五）10:40，多氟多获主力资金净流入21.09亿元居首位，其次分别是维通利（11.37亿元）、领益智造（8.66亿元）、天孚通信（7.42亿元）、巨轮智能（6.63亿元）、紫光股份（6.07亿元）、三花智控（4.73亿元）、粤传媒（4.57亿元）、网宿科技（4.50亿元）、润泽科技（4.17亿元）；主力资金流出规模居首的个股是东山精密（-15.70亿元），其次是海光信息（-14.34亿元）、胜宏科技（-12.38亿元）、光迅科技（-10.20亿元）、中天科技（-10.12亿元）、寒武纪（-9.84亿元）、新易盛（-9.15亿元）、佰维存储（-8.98亿元）、澜起科技（-8.88亿元）、亨通光电（-8.15亿元）。<br><img src=\"https://flash-scdn.jin10.com/flash_dli/jin_fanti/img/53bef95c-2222-bef6-bbf9-1778812805740.jpg\">,金十数据5月15日讯，截至2026年05月15日（周五）10:40，多氟多获主力资金净流入21.09亿元居首位，其次分别是维通利（11.37亿元）、领益智造（8.66亿元）、天孚通信（7.42亿元）、巨轮智能（6.63亿元）、紫光股份（6.07亿元）、三花智控（4.73亿元…,jin10:index:20260515104032683800,2026-05-15T02:58:38.821Z,2026-05-15T02:40:32.031Z,[{\"url\":\"https://flash-scdn.jin10.com/flash_dli/jin_fanti/img/53bef95c-2222-bef6-bbf9-1778812805740.jpg\",\"type\":\"photo\",\"width\":960,\"height\":3736}],44366244616936448,1111781045268557838,瑞银预测今年白银供应缺口将从此前估计的3亿盎司收窄至6000-7000万盎司。光伏需求减弱、投资资金外流、矿产供应增加三重压制下，瑞银全线下调银价目标。点击查看,https://xnews.jin10.com/details/219276,瑞银预测今年白银供应缺口将从此前估计的3亿盎司收窄至6000-7000万盎司。光伏需求减弱、投资资金外流、矿产供应增加三重压制下，瑞银全线下调银价目标。点击查看<br><img src=\"https://gimg.jin10.com/gallary/26/02/iZAC6DudgGHlfKYXlmI0B.png/lite\">,瑞银预测今年白银供应缺口将从此前估计的3亿盎司收窄至6000-7000万盎司。光伏需求减弱、投资资金外流、矿产供应增加三重压制下，瑞银全线下调银价目标。点击查看,jin10:index:20260515104028070800,2026-05-15T02:58:38.820Z,2026-05-15T02:40:28.960Z,[{\"url\":\"https://gimg.jin10.com/gallary/26/02/iZAC6DudgGHlfKYXlmI0B.png/lite\",\"type\":\"photo\",\"width\":324,\"height\":243}],44366244616936448,1111781045268557839,恒生科技指数跌超2%，成份股中，哔哩哔哩(09626.HK)跌超7%，华虹半导体(01347.HK)跌超6%。,恒生科技指数跌超2%，成份股中，哔哩哔哩(09626.HK)跌超7%，华虹半导体(01347.HK)跌超6%。,恒生科技指数跌超2%，成份股中，哔哩哔哩(09626.HK)跌超7%，华虹半导体(01347.HK)跌超6%。,jin10:index:20260515103934660800,2026-05-15T02:58:38.819Z,2026-05-15T02:39:34.739Z,44366244616936448,1111781045268557840,A股人形机器人板块异动拉升，雷赛智能、巨轮智能等多股涨停，纽威数控涨超13%，凯龙高科、奇德新材涨超12%，五洲新春涨超9%。,A股人形机器人板块异动拉升，雷赛智能、巨轮智能等多股涨停，纽威数控涨超13%，凯龙高科、奇德新材涨超12%，五洲新春涨超9%。,A股人形机器人板块异动拉升，雷赛智能、巨轮智能等多股涨停，纽威数控涨超13%，凯龙高科、奇德新材涨超12%，五洲新春涨超9%。,jin10:index:20260515103804537800,2026-05-15T02:58:38.818Z,2026-05-15T02:38:04.813Z,44366244616936448,1111781045268557841,市场监管总局就《药品、医疗器械、保健食品、特殊医学用途配方食品广告审查管理办法（征求意见稿）》公开征求意见。,市场监管总局就《药品、医疗器械、保健食品、特殊医学用途配方食品广告审查管理办法（征求意见稿）》公开征求意见。,市场监管总局就《药品、医疗器械、保健食品、特殊医学用途配方食品广告审查管理办法（征求意见稿）》公开征求意见。,jin10:index:20260515103611828800,2026-05-15T02:58:38.817Z,2026-05-15T02:36:11.126Z,44366244616936448,1111781045268557842,金十期货5月15日讯，据Mysteel数据显示，今日MMLC电池级碳酸锂（早盘）价格较昨日下跌2750元/吨，中间价报192100元/吨。,金十期货5月15日讯，据Mysteel数据显示，今日MMLC电池级碳酸锂（早盘）价格较昨日下跌2750元/吨，中间价报192100元/吨。,金十期货5月15日讯，据Mysteel数据显示，今日MMLC电池级碳酸锂（早盘）价格较昨日下跌2750元/吨，中间价报192100元/吨。,jin10:index:20260515103511100800,2026-05-15T02:58:38.816Z,2026-05-15T02:35:11.187Z,44366244616936448,1111781045268557843,“再见，鲍威尔”回顾8年任期关键时刻！“你好，沃什”前瞻新官上任的新风向！,“再见，鲍威尔”回顾8年任期关键时刻！“你好，沃什”前瞻新官上任的新风向！,“再见，鲍威尔”回顾8年任期关键时刻！“你好，沃什”前瞻新官上任的新风向！,jin10:index:20260515103414507800,2026-05-15T02:58:38.815Z,2026-05-15T02:34:14.078Z,44366244616936448,1111781045268557844,A股黄金概念震荡走低，宁波中百跌超9%，高能环境跌超8%，兴业银锡跌超7%，白银有色、湖南白银、盛屯矿业、西部黄金跟跌。,A股黄金概念震荡走低，宁波中百跌超9%，高能环境跌超8%，兴业银锡跌超7%，白银有色、湖南白银、盛屯矿业、西部黄金跟跌。,A股黄金概念震荡走低，宁波中百跌超9%，高能环境跌超8%，兴业银锡跌超7%，白银有色、湖南白银、盛屯矿业、西部黄金跟跌。,jin10:index:20260515103356450800,2026-05-15T02:58:38.814Z,2026-05-15T02:33:56.500Z",
      "id": "44366244616936448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jin10.com/",
      "title": "金十数据",
      "type": "feed",
      "url": "rsshub://jin10"
    },
    {
      "description": "金十数据 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72573375336611840",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jin10.com/",
      "title": "金十数据",
      "type": "feed",
      "url": "rsshub://jin10/1"
    }
  ],
  "url": "jin10.com/",
  "view": 5
}
```
