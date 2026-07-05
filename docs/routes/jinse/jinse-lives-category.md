# 金色财经 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `jinse`
- Namespace Name: `金色财经`
- Route Path: `/jinse/lives/:category?`
- Route Name: `快讯`
- Example: `/jinse/lives`
- URL: `jinse.com.cn`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `lives.ts`
- Source Module: `_None_`

## Description
| 全部 | 精选 | 政策 | 数据 | NFT | 项目 |
| ---- | ---- | ---- | ---- | --- | ---- |
| 0    | 1    | 2    | 3    | 4   | 5    |

## Parameters
- `category`: {"default": "0", "description": "分类", "options": [{"label": "全部", "value": "0"}, {"label": "精选", "value": "1"}, {"label": "政策", "value": "2"}, {"label": "数据", "value": "3"}, {"label": "NFT", "value": "4"}, {"label": "项目", "value": "5"}]}


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
    "finance"
  ],
  "description": "| 全部 | 精选 | 政策 | 数据 | NFT | 项目 |\n| ---- | ---- | ---- | ---- | --- | ---- |\n| 0    | 1    | 2    | 3    | 4   | 5    |",
  "example": "/jinse/lives",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1055,
  "location": "lives.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "快讯",
  "parameters": {
    "category": {
      "default": "0",
      "description": "分类",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "精选",
          "value": "1"
        },
        {
          "label": "政策",
          "value": "2"
        },
        {
          "label": "数据",
          "value": "3"
        },
        {
          "label": "NFT",
          "value": "4"
        },
        {
          "label": "项目",
          "value": "5"
        }
      ]
    }
  },
  "path": "/lives/:category?",
  "topFeeds": [
    {
      "description": "区块链新闻频道为您24小时提供最新区块链新闻信息，汇集全球各个区域最新消息，并为您提供最及时全面的区块链资讯 - Powered by RSSHub",
      "errorAt": "2026-07-04T03:11:40.404Z",
      "errorMessage": "Failed query: insert into \"entries\" (\"feed_id\", \"id\", \"title\", \"url\", \"content\", \"description\", \"guid\", \"author\", \"author_url\", \"author_avatar\", \"inserted_at\", \"published_at\", \"media\", \"categories\", \"attachments\", \"extra\", \"language\", \"summary\", \"body_r2_key\", \"body_offloaded_at\") values ($1, $2, $3, $4, $5, $6, $7, $8, default, default, $9, $10, default, default, default, default, default, default, default, default), ($11, $12, $13, $14, $15, $16, $17, $18, default, default, $19, $20, default, default, default, default, default, default, default, default), ($21, $22, $23, $24, $25, $26, $27, $28, default, default, $29, $30, default, default, default, default, default, default, default, default), ($31, $32, $33, $34, $35, $36, $37, $38, default, default, $39, $40, default, default, default, default, default, default, default, default), ($41, $42, $43, $44, $45, $46, $47, $48, default, default, $49, $50, default, default, default, default, default, default, default, default), ($51, $52, $53, $54, $55, $56, $57, $58, default, default, $59, $60, default, default, default, default, default, default, default, default), ($61, $62, $63, $64, $65, $66, $67, $68, default, default, $69, $70, default, default, default, default, default, default, default, default), ($71, $72, $73, $74, $75, $76, $77, $78, default, default, $79, $80, default, default, default, default, default, default, default, default), ($81, $82, $83, $84, $85, $86, $87, $88, default, default, $89, $90, default, default, default, default, default, default, default, default), ($91, $92, $93, $94, $95, $96, $97, $98, default, default, $99, $100, default, default, default, default, default, default, default, default), ($101, $102, $103, $104, $105, $106, $107, $108, default, default, $109, $110, default, default, default, default, default, default, default, default), ($111, $112, $113, $114, $115, $116, $117, $118, default, default, $119, $120, default, default, default, default, default, default, default, default), ($121, $122, $123, $124, $125, $126, $127, $128, default, default, $129, $130, default, default, default, default, default, default, default, default), ($131, $132, $133, $134, $135, $136, $137, $138, default, default, $139, $140, default, default, default, default, default, default, default, default), ($141, $142, $143, $144, $145, $146, $147, $148, default, default, $149, $150, default, default, default, default, default, default, default, default), ($151, $152, $153, $154, $155, $156, $157, $158, default, default, $159, $160, default, default, default, default, default, default, default, default), ($161, $162, $163, $164, $165, $166, $167, $168, default, default, $169, $170, default, default, default, default, default, default, default, default), ($171, $172, $173, $174, $175, $176, $177, $178, default, default, $179, $180, default, default, default, default, default, default, default, default), ($181, $182, $183, $184, $185, $186, $187, $188, default, default, $189, $190, default, default, default, default, default, default, default, default), ($191, $192, $193, $194, $195, $196, $197, $198, default, default, $199, $200, default, default, default, default, default, default, default, default) on conflict (\"feed_id\",\"guid\") do update set \"title\" = excluded.\"title\", \"content\" = excluded.\"content\", \"description\" = excluded.\"description\", \"media\" = excluded.\"media\", \"attachments\" = excluded.\"attachments\", \"extra\" = COALESCE(\"entries\".\"extra\", '{}'::jsonb) || COALESCE(excluded.\"extra\", '{}'::jsonb) returning \"id\", \"published_at\", \"inserted_at\", \"feed_id\", \"title\", \"description\", \"content\", \"author\", \"url\", \"guid\", \"media\", \"attachments\"\nparams: 56701589104355328,1184271401201217536,千问：拟人化互动类智能体及用户自建智能体功能将于7月10日正式下线,https://jinse.com.cn/lives/521344.html,【千问：拟人化互动类智能体及用户自建智能体功能将于7月10日正式下线】金色财经报道，7月4日，据千问平台消息，因功能升级与维护，拟人化互动类智能体及用户自建智能体功能将于2026年7月10日正式下线。届时，用户将无法继续访问相关智能体的配置信息及历史对话记录。(金十),【千问：拟人化互动类智能体及用户自建智能体功能将于7月10日正式下线】金色财经报道，7月4日，据千问平台消息，因功能升级与维护，拟人化互动类智能体及用户自建智能体功能将于2026年7月10日正式下线。届时，用户将无法继续访问相关智能体的配置信息及历史对话记录。(金十),jinse-lives-521344,,2026-07-04T03:11:30.441Z,2026-07-04T02:48:16.699Z,56701589104355328,1184271401201217537,豆包：智能体功能将于7月15日下线,https://jinse.com.cn/lives/521343.html,【豆包：智能体功能将于7月15日下线】金色财经报道，7月4日，豆包发布《豆包智能体功能下线通知》称，智能体功能将于2026年7月15日下线，届时用户将无法新建智能体，已创建保存的智能体也会同步无法调用、运行。在7月15日之后，豆包将对智能体相关数据进行处理，后续将无法在豆包内查看或恢复。(金十),【豆包：智能体功能将于7月15日下线】金色财经报道，7月4日，豆包发布《豆包智能体功能下线通知》称，智能体功能将于2026年7月15日下线，届时用户将无法新建智能体，已创建保存的智能体也会同步无法调用、运行。在7月15日之后，豆包将对智能体相关数据进行处理…,jinse-lives-521343,,2026-07-04T03:11:30.440Z,2026-07-04T02:19:46.373Z,56701589104355328,1184271401201217538,SemiAnalysis：AI数据中心内存支出占比2027年或突破40%,https://jinse.com.cn/lives/521342.html,【SemiAnalysis：AI数据中心内存支出占比2027年或突破40%】金色财经报道，7月4日，专注于半导体与AI基础设施的顶级研究机构SemiAnalysis发文称，内存占超大规模数据中心资本支出的比例引发了大量讨论，尤其是在上周美光科技财报发布后。一些市场参与者对明年这一比例可能有多高感到震惊。该机构称，二月底发布初步观点后，许多客户对其30%的数字提出质疑：“内存占服务器BOM的比例只有十几个百分点。整体资本支出怎么可能那么高？”五月份，在价格上涨速度甚至超出预期之后，SemiAnalysis直接回应称：将DRAM、NAND和HBM结合起来，在英伟达系统中的内存支出占比到2026年底将超过30%，并将在2027年超过40%。该机构预计，未来几个月市场将更充分地理解这一趋势。(金十),【SemiAnalysis：AI数据中心内存支出占比2027年或突破40%】金色财经报道，7月4日，专注于半导体与AI基础设施的顶级研究机构SemiAnalysis发文称，内存占超大规模数据中心资本支出的比例引发了大量讨论，尤其是在上周美光科技财报发布后…,jinse-lives-521342,,2026-07-04T03:11:30.439Z,2026-07-04T02:07:14.772Z,56701589104355328,1184271401201217539,三星第三季DRAM拟提价20%，厂家称已接口头通知,https://jinse.com.cn/lives/521341.html,【三星第三季DRAM拟提价20%，厂家称已接口头通知】金色财经报道，7月3日，有消息称三星电子拟将今年第三季度DRAM（动态随机存取存储器）的平均售价，环比上一季度提高20%。“这是真的”，一家消费电子终端厂商负责人表示，今年6月三星已与他们洽谈，现已收到三星关于DRAM提价的口头通知。“上游部品大幅涨价会传导至整机终端售价上，这会遏制一定的市场需求，但毕竟现在消费电子产品整体价格不高，即使涨价预计也不太会影响用户选购。”上述消费电子终端厂商负责人说。另一位业内资深人士也表示，三星拟三季度DRAM提价20%的消息属实，三星已经通过口头报价通知了部分客户。（一财）,【三星第三季DRAM拟提价20%，厂家称已接口头通知】金色财经报道，7月3日，有消息称三星电子拟将今年第三季度DRAM（动态随机存取存储器）的平均售价，环比上一季度提高20%。“这是真的”，一家消费电子终端厂商负责人表示，今年6月三星已与他们洽谈…,jinse-lives-521341,,2026-07-04T03:11:30.438Z,2026-07-04T01:28:58.731Z,56701589104355328,1184271401201217540,某巨鲸于4小时前再度从Binance提出100枚WBTC，价值624万美元,https://jinse.com.cn/lives/521340.html,【某巨鲸于4小时前再度从Binance提出100枚WBTC，价值624万美元】金色财经报道，7月4日，据链上分析师余烬监测，这个从1号开始不断从Binance提出ETH的鲸鱼，他的ETH已经浮盈330万美元了。而今天在4小时前他又从Binance提出了100枚WBTC(624万美元)。 \n他抄底就开始反弹：3天时间他一共囤积了19,752枚ETH(3143万美元)+100枚WBTC(624万美元)，ETH价格1,591美元、BTC价格62,390美元。也正好是这几天里，ETH反弹了200美元、BTC反弹了4000美元。<p>原文链接: <a href=\"https://x.com/EmberCN/status/2073206319163826423\" target=\"_blank\">https://x.com/EmberCN/status/2073206319163826423</a></p>,【某巨鲸于4小时前再度从Binance提出100枚WBTC，价值624万美元】金色财经报道，7月4日，据链上分析师余烬监测，这个从1号开始不断从Binance提出ETH的鲸鱼，他的ETH已经浮盈330万美元了。而今天在4小时前他又从Binance提出了100枚WBTC…,jinse-lives-521340,,2026-07-04T03:11:30.437Z,2026-07-04T00:50:52.175Z,56701589104355328,1184271401201217541,某巨鲸已平仓以太坊空单，亏损938.6万美元,https://jinse.com.cn/lives/521339.html,【某巨鲸已平仓以太坊空单，亏损938.6万美元】金色财经报道，7月4日，据Onchain Lens监测，巨鲸地址“0x50b”已平仓以太坊空头仓位，这笔交易亏损938.6万美元。该巨鲸账户总收益由盈利660万美元转为亏损230万美元。目前其仍持有228.7枚20倍杠杆比特币多头仓位。<p>原文链接: <a href=\"https://x.com/OnchainLens/status/2073203619219087453\" target=\"_blank\">https://x.com/OnchainLens/status/2073203619219087453</a></p>,【某巨鲸已平仓以太坊空单，亏损938.6万美元】金色财经报道，7月4日，据Onchain Lens监测，巨鲸地址“0x50b”已平仓以太坊空头仓位，这笔交易亏损938.6万美元。该巨鲸账户总收益由盈利660万美元转为亏损230万美元。目前其仍持有228…,jinse-lives-521339,,2026-07-04T03:11:30.436Z,2026-07-04T00:39:29.812Z,56701589104355328,1184271401201217542,特朗普：财政部接受股票捐赠 以资助“特朗普账户”,https://jinse.com.cn/lives/521338.html,【特朗普：财政部接受股票捐赠 以资助“特朗普账户”】金色财经报道，7月4日，美国总统特朗普：美国财政部现在将接受以流动性良好的上市公司股票形式进行的慈善捐赠，用于为符合资格的美国儿童提供 TRUMP ACCOUNTS（特朗普账户） 的资金支持。TRUMP ACCOUNTS 项目反响极其热烈——在项目正式启动之前，已经有超过600万个账户提出申请。(金十),【特朗普：财政部接受股票捐赠 以资助“特朗普账户”】金色财经报道，7月4日，美国总统特朗普：美国财政部现在将接受以流动性良好的上市公司股票形式进行的慈善捐赠，用于为符合资格的美国儿童提供 TRUMP ACCOUNTS（特朗普账户） 的资金支持。TRUMP ACCOUNTS…,jinse-lives-521338,,2026-07-04T03:11:30.435Z,2026-07-04T00:23:12.141Z,56701589104355328,1184271401201217543,F2Pool创始人王纯再次向Binance存入9,876枚ETH，价值约1,702万美元,https://jinse.com.cn/lives/521337.html,【F2Pool创始人王纯再次向Binance存入9,876枚ETH，价值约1,702万美元】金色财经报道，7月4日，据Onchain Lens监测，F2Pool创始人王纯再次向Binance存入9,876枚ETH，价值约1,702万美元。<p>原文链接: <a href=\"https://x.com/OnchainLens/status/2073193563257716934\" target=\"_blank\">https://x.com/OnchainLens/status/2073193563257716934</a></p>,【F2Pool创始人王纯再次向Binance存入9,876枚ETH，价值约1,702万美元】金色财经报道，7月4日，据Onchain Lens监测，F2Pool创始人王纯再次向Binance存入9,876枚ETH，价值约1,702万美元。 原文链接: https://x.com…,jinse-lives-521337,,2026-07-04T03:11:30.434Z,2026-07-04T00:05:24.663Z,56701589104355328,1184271401201217544,金色晨讯 | 7月4日隔夜重要动态一览,https://jinse.com.cn/lives/521336.html,【金色晨讯 | 7月4日隔夜重要动态一览】21:00-7:00关键词：OUSD、Strategy、Hyperliquid、委内瑞拉 \n1.委内瑞拉最大炼油厂恢复运行； \n2.美国参议员Gillibrand呼吁禁止特朗普及官员发行Meme币； \n3.Solana本季度在代币化股票赛道 现货交易量达到48.4亿美元； \n4.Upbit：公司不会参与OUSD的发行，未来可能考虑参与生态系统扩展； \n5.Galaxy研究主管：Strategy资本策略赢得时间，但结构性压力仍未消除； \n6.“美联储传声筒”：特朗普定调、白宫高官喊话 美联储迎来“前瞻指引”新时代； \n7.Jeff：直接利用Hyperliquid链上流动性将重新定义下一代金融应用构建方式。,【金色晨讯 | 7月4日隔夜重要动态一览】21:00-7:00关键词：OUSD、Strategy、Hyperliquid、委内瑞拉 1.委内瑞拉最大炼油厂恢复运行； 2.美国参议员Gillibrand呼吁禁止特朗普及官员发行Meme币； 3…,jinse-lives-521336,,2026-07-04T03:11:30.433Z,2026-07-03T23:32:26.875Z,56701589104355328,1184271401201217545,CryptoQuant：BTC与山寨币交易所充值激增，或预示市场波动上升,https://jinse.com.cn/lives/521335.html,【CryptoQuant：BTC与山寨币交易所充值激增，或预示市场波动上升】金色财经报道，7月4日，CryptoQuant 表示，比特币、以太坊及山寨币流入交易所的规模近期明显上升，这一模式历史上往往预示加密市场即将进入更高波动阶段。 \nCryptoQuant 研究主管 Julio Moreno 指出，6 月 30 日比特币流入交易所数量接近 49,000 枚 BTC，属于罕见极端水平。今年此前仅出现过四次类似接近 50,000 枚 BTC 的单日充值峰值，而这些峰值通常随后伴随价格波动显著放大和明确方向性走势。 \n报告认为，在当前流入规模下，市场正在吸收大量被转移至交易所的比特币。由于转入交易所通常意味着潜在卖压、仓位调整或衍生品保证金需求上升，因此可能引发更剧烈的价格波动。 \nCryptoQuant 还指出，以太坊和山寨币流入交易所的数量也在上升，说明压力并不局限于比特币，而是扩散至更广泛的加密资产市场。总体来看，交易所充值激增可能意味着短期市场方向即将发生更大幅度变化。<p>原文链接: <a href=\"https://www.theblock.co/post/407160/cryptoquant-bitcoin-ether-altcoin-exchange-deposits-volatility\" target=\"_blank\">https://www.theblock.co/post/407160/cryptoquant-bitcoin-ether-altcoin-exchange-deposits-volatility</a></p>,【CryptoQuant：BTC与山寨币交易所充值激增，或预示市场波动上升】金色财经报道，7月4日，CryptoQuant 表示，比特币、以太坊及山寨币流入交易所的规模近期明显上升，这一模式历史上往往预示加密市场即将进入更高波动阶段。 CryptoQuant 研究主管…,jinse-lives-521335,,2026-07-04T03:11:30.432Z,2026-07-03T23:14:33.440Z,56701589104355328,1184271401201217546,Michael Saylor：约1亿人通过MSTR普通股获得比特币敞口,https://jinse.com.cn/lives/521334.html,【Michael Saylor：约1亿人通过MSTR普通股获得比特币敞口】金色财经报道，7月4日，BitcoinTreasuries.NET在X平台发文表示，Strategy的Michael Saylor称，目前约1亿人通过MSTR普通股获得比特币敞口，Strategy已成为美国最大的股票发行方。<p>原文链接: <a href=\"https://x.com/BTCtreasuries/status/2073112035257196720\" target=\"_blank\">https://x.com/BTCtreasuries/status/2073112035257196720</a></p>,【Michael Saylor：约1亿人通过MSTR普通股获得比特币敞口】金色财经报道，7月4日，BitcoinTreasuries.NET在X平台发文表示，Strategy的Michael Saylor称，目前约1亿人通过MSTR普通股获得比特币敞口…,jinse-lives-521334,,2026-07-04T03:11:30.431Z,2026-07-03T23:13:27.408Z,56701589104355328,1184271401201217547,美国参议员Gillibrand呼吁禁止特朗普及官员发行Meme币,https://jinse.com.cn/lives/521333.html,【美国参议员Gillibrand呼吁禁止特朗普及官员发行Meme币】金色财经报道，7月4日，美国参议员Kirsten Gillibrand呼吁国会立法，禁止包括总统及其配偶在内的所有民选官员发行或赞助数字资产（包括Meme币）。这一呼吁源于最新财务披露：特朗普2025年约6.36亿美元收入来自Meme币发行，其配偶亦发行Meme币，并通过NFT及数字收藏品获得约600万美元收入。 \nGillibrand表示，这种行为属于“自我交易”，破坏金融监管与消费者保护，并呼吁立即推进伦理改革，禁止公职人员及其配偶利用职务牟利。<p>原文链接: <a href=\"https://decrypt.co/372749/senator-gillibrand-ban-trump-elected-officials-launching-meme-coins\" target=\"_blank\">https://decrypt.co/372749/senator-gillibrand-ban-trump-elected-officials-launching-meme-coins</a></p>,【美国参议员Gillibrand呼吁禁止特朗普及官员发行Meme币】金色财经报道，7月4日，美国参议员Kirsten Gillibrand呼吁国会立法，禁止包括总统及其配偶在内的所有民选官员发行或赞助数字资产（包括Meme币）。这一呼吁源于最新财务披露：特朗普2025年约6…,jinse-lives-521333,,2026-07-04T03:11:30.430Z,2026-07-03T22:55:57.205Z,56701589104355328,1184271401201217548,Strategy持有比特币数量为全球政府合计持有量1.3倍,https://jinse.com.cn/lives/521332.html,【Strategy持有比特币数量为全球政府合计持有量1.3倍】金色财经报道，7月4日，Bitcoin Treasuries 在 X 平台发文表示，Strategy MSTR 目前持有的比特币数量为全球所有政府合计持有量的 1.3 倍。<p>原文链接: <a href=\"https://x.com/BTCtreasuries/status/2073157333505782191\" target=\"_blank\">https://x.com/BTCtreasuries/status/2073157333505782191</a></p>,【Strategy持有比特币数量为全球政府合计持有量1.3倍】金色财经报道，7月4日，Bitcoin Treasuries 在 X 平台发文表示，Strategy MSTR 目前持有的比特币数量为全球所有政府合计持有量的 1.3 倍。 原文链接: https://x.com…,jinse-lives-521332,,2026-07-04T03:11:30.429Z,2026-07-03T22:23:08.424Z,56701589104355328,1184271401201217549,Sharplink联席CEO Joseph Chalom：以太坊验证者超90万，Solana不足800,https://jinse.com.cn/lives/521331.html,【Sharplink联席CEO Joseph Chalom：以太坊验证者超90万，Solana不足800】金色财经报道，7月4日，Sharplink 联席 CEO、Blackrock 前高管 Joseph Chalom 表示，以太坊拥有超 90 万名验证者和超 100 万名开发者，具备 Solana 无法匹配的去中心化优势。Electric Capital 数据显示，已有 1,012,824 名开发者在以太坊上贡献代码，过去 12 个月约 23.2 万人保持活跃。 \nChalom 称，Solana 验证者不足 800 名，且 92% 运行在同一客户端。数据显示，Sharplink 截至 6 月下旬持有 88.6725 万枚 ETH。<p>原文链接: <a href=\"https://news.bitcoin.com/chalom-defends-ethereum-over-solana/?utm_source=chatgpt.com\" target=\"_blank\">https://news.bitcoin.com/chalom-defends-ethereum-over-solana/?utm_source=chatgpt.com</a></p>,【Sharplink联席CEO Joseph Chalom：以太坊验证者超90万，Solana不足800】金色财经报道，7月4日，Sharplink 联席 CEO、Blackrock 前高管 Joseph Chalom 表示，以太坊拥有超 90 万名验证者和超 100 万名开发者…,jinse-lives-521331,,2026-07-04T03:11:30.428Z,2026-07-03T22:05:30.616Z,56701589104355328,1184271401201217550,受AI热潮与美联储乐观预期提振，新兴市场资产全线反弹,https://jinse.com.cn/lives/521330.html,【受AI热潮与美联储乐观预期提振，新兴市场资产全线反弹】金色财经报道，7月4日，随着韩国科技蓝筹股反弹，新兴市场股市创下自6月中旬以来的最大单日涨幅；同时，受美国劳动力市场数据弱于预期的影响，新兴市场货币连续第二日走强。周五，MSCI新兴市场股票指数上涨2.2%，创6月15日以来最大单日涨幅。韩国芯片制造商SK海力士和三星电子的强劲表现，抵消了台积电股价下跌带来的拖累。韩国综合股价指数（Kospi）大涨5.8%，部分收复了此前两个交易日近10%的跌幅。<p>原文链接: <a href=\"https://wap.cj.sina.cn/pc/7x24/4970135\" target=\"_blank\">https://wap.cj.sina.cn/pc/7x24/4970135</a></p>,【受AI热潮与美联储乐观预期提振，新兴市场资产全线反弹】金色财经报道，7月4日，随着韩国科技蓝筹股反弹，新兴市场股市创下自6月中旬以来的最大单日涨幅；同时，受美国劳动力市场数据弱于预期的影响，新兴市场货币连续第二日走强。周五，MSCI新兴市场股票指数上涨2.2…,jinse-lives-521330,,2026-07-04T03:11:30.427Z,2026-07-03T21:45:48.361Z,56701589104355328,1184271401201217551,美元指数3日下跌0.02%,https://jinse.com.cn/lives/521329.html,【美元指数3日下跌0.02%】金色财经报道，美元指数3日下跌0.02%，在汇市尾市收于100.845。,【美元指数3日下跌0.02%】金色财经报道，美元指数3日下跌0.02%，在汇市尾市收于100.845。,jinse-lives-521329,,2026-07-04T03:11:30.426Z,2026-07-03T20:59:56.840Z,56701589104355328,1184271401201217552,俄总统新闻秘书：普京宣布俄军“完全解放”卢甘斯克,https://jinse.com.cn/lives/521328.html,【俄总统新闻秘书：普京宣布俄军“完全解放”卢甘斯克】金色财经报道，7月4日，俄罗斯总统新闻秘书佩斯科夫当地时间3日晚在临时召开的新闻发布会上介绍，俄总统普京宣布俄军已“完全解放”卢甘斯克并在顿涅茨克取得重大进展。佩斯科夫当晚还宣布，俄军已完全占领康斯坦丁诺夫卡市。<p>原文链接: <a href=\"https://www.cls.cn/detail/2417009\" target=\"_blank\">https://www.cls.cn/detail/2417009</a></p>,【俄总统新闻秘书：普京宣布俄军“完全解放”卢甘斯克】金色财经报道，7月4日，俄罗斯总统新闻秘书佩斯科夫当地时间3日晚在临时召开的新闻发布会上介绍，俄总统普京宣布俄军已“完全解放”卢甘斯克并在顿涅茨克取得重大进展。佩斯科夫当晚还宣布，俄军已完全占领康斯坦丁诺夫卡市。 原文链接: ht…,jinse-lives-521328,,2026-07-04T03:11:30.425Z,2026-07-03T20:59:31.934Z,56701589104355328,1184271401201217553,伊朗议会议长卡利巴夫：美国应接受地区现实，呼吁推动解除制裁,https://jinse.com.cn/lives/521327.html,【伊朗议会议长卡利巴夫：美国应接受地区现实，呼吁推动解除制裁】金色财经报道，7月4日，伊朗议会议长卡利巴夫在会见乌兹别克斯坦议会代表时表示，美国必须接受在与以色列及美国对伊朗冲突后形成的“现实变化”，承认地区局势已经不同以往。他称，当前局势较过去有所改善，美国已被迫接受新的地区格局。在此背景下，各方经贸关系有望进一步拓展，并希望为未来解除制裁创造条件。卡利巴夫还表示，在伊朗与阿曼对波斯湾及霍尔木兹海峡的“联合管理”框架下，美国在地区的“干扰”将减少，从而为区域过境与交通合作创造更有利条件。<p>原文链接: <a href=\"https://flash.jin10.com/detail/20260704031009595800\" target=\"_blank\">https://flash.jin10.com/detail/20260704031009595800</a></p>,【伊朗议会议长卡利巴夫：美国应接受地区现实，呼吁推动解除制裁】金色财经报道，7月4日，伊朗议会议长卡利巴夫在会见乌兹别克斯坦议会代表时表示，美国必须接受在与以色列及美国对伊朗冲突后形成的“现实变化”，承认地区局势已经不同以往。他称，当前局势较过去有所改善…,jinse-lives-521327,,2026-07-04T03:11:30.424Z,2026-07-03T20:10:38.249Z,56701589104355328,1184271401201217554,惠誉：中东局势仍对全球企业构成风险,https://jinse.com.cn/lives/521326.html,【惠誉：中东局势仍对全球企业构成风险】金色财经报道，7月4日，惠誉评级发布报告称，尽管6月17日美伊签署临时谅解备忘录，但双方仍持续进行报复性军事打击，协议也较为脆弱，且以色列未参与，使中东局势仍对全球企业构成风险。惠誉在更新的“负面情景”分析中指出，即便当前设定的极端情景（如股市下跌10%、企业债利差扩大100–200个基点、货币政策收紧、全球经济明显放缓）未必完全发生，但仍可作为冲突升级时的参考。在该情景下，美国、欧元区经济增速将显著下降。惠誉共评估了全球6个地区的72个行业子领域，其中大多数风险判断维持不变，少数被上调或下调。总体来看，惠誉认为中东冲突的“尾部风险”仍在，若局势重新升级，将继续对全球企业信用环境和金融市场造成压力。<p>原文链接: <a href=\"https://flash.jin10.com/detail/20260704005624444800\" target=\"_blank\">https://flash.jin10.com/detail/20260704005624444800</a></p>,【惠誉：中东局势仍对全球企业构成风险】金色财经报道，7月4日，惠誉评级发布报告称，尽管6月17日美伊签署临时谅解备忘录，但双方仍持续进行报复性军事打击，协议也较为脆弱，且以色列未参与，使中东局势仍对全球企业构成风险。惠誉在更新的“负面情景”分析中指出，即便当前设定的极端情景…,jinse-lives-521326,,2026-07-04T03:11:30.423Z,2026-07-03T20:09:51.294Z,56701589104355328,1184271401201217555,特朗普与内塔尼亚胡通话，双方同意近期在美国会晤,https://jinse.com.cn/lives/521325.html,【特朗普与内塔尼亚胡通话，双方同意近期在美国会晤】金色财经报道，7月4日，据 AXIOS 网站，美国总统特朗普今天与以色列总理内塔尼亚胡通了电话。以色列总理办公室表示，双方同意近期在美国举行会晤。<p>原文链接: <a href=\"https://flash.jin10.com/detail/20260704003454888800\" target=\"_blank\">https://flash.jin10.com/detail/20260704003454888800</a></p>,【特朗普与内塔尼亚胡通话，双方同意近期在美国会晤】金色财经报道，7月4日，据 AXIOS 网站，美国总统特朗普今天与以色列总理内塔尼亚胡通了电话。以色列总理办公室表示，双方同意近期在美国举行会晤。 原文链接: https://flash.jin10.com/detail…,jinse-lives-521325,,2026-07-04T03:11:30.422Z,2026-07-03T20:08:24.655Z",
      "id": "56701589104355328",
      "image": "https://staticn.jinse.com.cn/w/img/b6900fe.png",
      "ownerUserId": null,
      "siteUrl": "https://jinse.com.cn/lives",
      "title": "金色财经 - 全部",
      "type": "feed",
      "url": "rsshub://jinse/lives/0"
    },
    {
      "description": "区块链新闻频道为您24小时提供最新区块链新闻信息，汇集全球各个区域最新消息，并为您提供最及时全面的区块链资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72606914246960128",
      "image": "https://staticn.jinse.com.cn/w/img/b6900fe.png",
      "ownerUserId": null,
      "siteUrl": "https://jinse.com.cn/lives",
      "title": "金色财经 - 精选",
      "type": "feed",
      "url": "rsshub://jinse/lives/1"
    }
  ],
  "view": 5
}
```
