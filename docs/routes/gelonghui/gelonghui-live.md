# 格隆汇 - 实时快讯

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/gelonghui/live`
- Route Name: `实时快讯`
- Example: `/gelonghui/live`
- URL: `gelonghui.com/live`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `None`
- Source Location: `live.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `gelonghui.com/live`
  - `gelonghui.com/`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "example": "/gelonghui/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1379,
  "location": "live.tsx",
  "maintainers": [],
  "name": "实时快讯",
  "parameters": {},
  "path": "/live",
  "radar": [
    {
      "source": [
        "gelonghui.com/live",
        "gelonghui.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "格隆汇快讯栏目提供外汇投资实时行情,外汇投资交易,外汇投资炒股,证券等内容,实时更新,格隆汇未来将陆续开通台湾、日本、印度、欧洲等市场. - Powered by RSSHub",
      "errorAt": "2026-05-11T16:26:04.493Z",
      "errorMessage": "Failed query: insert into \"entries\" (\"feed_id\", \"id\", \"title\", \"url\", \"content\", \"description\", \"guid\", \"author\", \"author_url\", \"author_avatar\", \"inserted_at\", \"published_at\", \"media\", \"categories\", \"attachments\", \"extra\", \"language\", \"summary\", \"body_r2_key\", \"body_offloaded_at\") values ($1, $2, $3, $4, $5, $6, $7, default, default, default, $8, $9, default, $10, default, default, default, default, default, default), ($11, $12, $13, $14, $15, $16, $17, default, default, default, $18, $19, default, $20, default, default, default, default, default, default), ($21, $22, $23, $24, $25, $26, $27, default, default, default, $28, $29, $30, $31, default, default, default, default, default, default), ($32, $33, $34, $35, $36, $37, $38, default, default, default, $39, $40, default, $41, default, default, default, default, default, default), ($42, $43, $44, $45, $46, $47, $48, default, default, default, $49, $50, default, $51, default, default, default, default, default, default), ($52, $53, $54, $55, $56, $57, $58, default, default, default, $59, $60, default, $61, default, default, default, default, default, default), ($62, $63, $64, $65, $66, $67, $68, default, default, default, $69, $70, default, $71, default, default, default, default, default, default), ($72, $73, $74, $75, $76, $77, $78, default, default, default, $79, $80, default, $81, default, default, default, default, default, default), ($82, $83, $84, $85, $86, $87, $88, default, default, default, $89, $90, default, $91, default, default, default, default, default, default), ($92, $93, $94, $95, $96, $97, $98, default, default, default, $99, $100, default, $101, default, default, default, default, default, default), ($102, $103, $104, $105, $106, $107, $108, default, default, default, $109, $110, default, $111, default, default, default, default, default, default), ($112, $113, $114, $115, $116, $117, $118, default, default, default, $119, $120, default, $121, default, default, default, default, default, default), ($122, $123, $124, $125, $126, $127, $128, default, default, default, $129, $130, default, $131, default, default, default, default, default, default), ($132, $133, $134, $135, $136, $137, $138, default, default, default, $139, $140, default, $141, default, default, default, default, default, default), ($142, $143, $144, $145, $146, $147, $148, default, default, default, $149, $150, default, $151, default, default, default, default, default, default) on conflict (\"feed_id\",\"guid\") do update set \"title\" = excluded.\"title\", \"content\" = excluded.\"content\", \"description\" = excluded.\"description\", \"media\" = excluded.\"media\", \"attachments\" = excluded.\"attachments\", \"extra\" = COALESCE(\"entries\".\"extra\", '{}'::jsonb) || COALESCE(excluded.\"extra\", '{}'::jsonb) returning \"id\", \"published_at\", \"inserted_at\", \"feed_id\", \"title\", \"description\", \"content\", \"author\", \"url\", \"guid\", \"media\", \"attachments\"\nparams: 55611390687386624,1106795362456113152,格隆汇5月12日｜美国总统特朗普：我们等了伊朗四天，而他们的那份文件准备起来其实十分钟都用不了。,https://www.gelonghui.com/live/2443777,格隆汇5月12日｜美国总统特朗普：我们等了伊朗四天，而他们的那份文件准备起来其实十分钟都用不了。  <br>  ,格隆汇5月12日｜美国总统特朗普：我们等了伊朗四天，而他们的那份文件准备起来其实十分钟都用不了。,https://www.gelonghui.com/live/2443777,2026-05-11T16:25:51.146Z,2026-05-11T16:09:56.241Z,{},55611390687386624,1106795362456113153,德国与乌克兰将联合生产航程达1500公里无人机,https://www.gelonghui.com/live/2443776,格隆汇5月12日｜正在乌克兰首都基辅访问的德国国防部长鲍里斯·皮斯托里乌斯11日向媒体表示，德国与乌克兰将联合生产航程达1500公里的远程无人机。  <br>  ,格隆汇5月12日｜正在乌克兰首都基辅访问的德国国防部长鲍里斯·皮斯托里乌斯11日向媒体表示，德国与乌克兰将联合生产航程达1500公里的远程无人机。,https://www.gelonghui.com/live/2443776,2026-05-11T16:25:51.145Z,2026-05-11T16:09:32.831Z,{},55611390687386624,1106795362456113154,现货白银涨幅扩大至7%,https://www.gelonghui.com/live/2443769,格隆汇5月12日｜现货白银日内涨幅扩大至7%，报85.97美元/盎司。现货黄金价格涨0.35%，报4731.85美元/盎司。  <br>  <img src=\"https://img5.gelonghui.com/live/6f942-c7e8f65a-e027-4eb9-b2c4-b6715daf6e25.jpg?guru_height=668&#x26;guru_width=1311&#x26;guru_size=140152\">  ,格隆汇5月12日｜现货白银日内涨幅扩大至7%，报85.97美元/盎司。现货黄金价格涨0.35%，报4731.85美元/盎司。,https://www.gelonghui.com/live/2443769,2026-05-11T16:25:51.144Z,2026-05-11T16:01:40.462Z,[{\"url\":\"https://img5.gelonghui.com/live/6f942-c7e8f65a-e027-4eb9-b2c4-b6715daf6e25.jpg?guru_height=668&guru_width=1311&guru_size=140152\",\"type\":\"photo\",\"width\":1311,\"height\":668}],{},55611390687386624,1106795362456113155,特朗普：伊朗对美国所提方案的回应“愚蠢” “停火协议已岌岌可危”,https://www.gelonghui.com/live/2443763,格隆汇5月11日｜据CCTV国际时讯，美国总统特朗普5月11日在白宫对媒体表示，伊朗对美国所提方案的回应“愚蠢”，“停火协议已岌岌可危”。  <br>  ,格隆汇5月11日｜据CCTV国际时讯，美国总统特朗普5月11日在白宫对媒体表示，伊朗对美国所提方案的回应“愚蠢”，“停火协议已岌岌可危”。,https://www.gelonghui.com/live/2443763,2026-05-11T16:25:51.143Z,2026-05-11T16:00:14.205Z,{},55611390687386624,1106795362456113156,特朗普政府将暂时降低牛肉进口关税,https://www.gelonghui.com/live/2443760,格隆汇5月11日｜特朗普政府将允许更多外国生产的牛肉以更低的关税税率进口。特朗普的牛肉政策将影响所有牛肉出口国。特朗普政府还将放宽对狼的保护措施，并放宽美国养牛户的耳标规定。  <br>  ,格隆汇5月11日｜特朗普政府将允许更多外国生产的牛肉以更低的关税税率进口。特朗普的牛肉政策将影响所有牛肉出口国。特朗普政府还将放宽对狼的保护措施，并放宽美国养牛户的耳标规定。,https://www.gelonghui.com/live/2443760,2026-05-11T16:25:51.142Z,2026-05-11T15:53:35.992Z,{},55611390687386624,1106795362456113157,格隆汇5月11日｜特朗普谈伊朗： 他们以为我会对此感到厌倦、乏味，或是承受外界压力。但我毫无压力，完全没有任何压力。我们必将取得彻底胜利。,https://www.gelonghui.com/live/2443758,格隆汇5月11日｜特朗普谈伊朗： 他们以为我会对此感到厌倦、乏味，或是承受外界压力。但我毫无压力，完全没有任何压力。我们必将取得彻底胜利。  <br>  ,格隆汇5月11日｜特朗普谈伊朗： 他们以为我会对此感到厌倦、乏味，或是承受外界压力。但我毫无压力，完全没有任何压力。我们必将取得彻底胜利。,https://www.gelonghui.com/live/2443758,2026-05-11T16:25:51.141Z,2026-05-11T15:53:05.741Z,{},55611390687386624,1106795362456113158,利仁科技：控股股东拟协议转让10%公司股份,https://www.gelonghui.com/live/2443757,格隆汇5月11日｜利仁科技(001259.SZ)公告称，公司控股股东、实际控制人宋老亮拟通过协议转让方式，分别向上海蕴力科技合伙企业(有限合伙)和董湘琳各转让公司5%股份，合计转让10%股份。转让单价为32.77元/股，转让价款均为1.21亿元。本次转让不触及要约收购，不会导致公司控制权变更。  <br>  ,格隆汇5月11日｜利仁科技(001259.SZ)公告称，公司控股股东、实际控制人宋老亮拟通过协议转让方式，分别向上海蕴力科技合伙企业(有限合伙)和董湘琳各转让公司5%股份，合计转让10%股份。转让单价为32.77元/股，转让价款均为1.21亿元。本次转让不触及要约收购…,https://www.gelonghui.com/live/2443757,2026-05-11T16:25:51.140Z,2026-05-11T15:50:44.177Z,{},55611390687386624,1106795362456113159,格隆汇5月11日｜油价延续涨势，布伦特原油价格突破每桶104美元。,https://www.gelonghui.com/live/2443756,格隆汇5月11日｜油价延续涨势，布伦特原油价格突破每桶104美元。  <br>  ,格隆汇5月11日｜油价延续涨势，布伦特原油价格突破每桶104美元。,https://www.gelonghui.com/live/2443756,2026-05-11T16:25:51.139Z,2026-05-11T15:47:54.996Z,{},55611390687386624,1106795362456113160,泽连斯基与德国防长会晤 推进多项军事及能源合作,https://www.gelonghui.com/live/2443755,格隆汇5月11日｜据央视，乌克兰总统泽连斯基在基辅会见到访的德国国防部长皮斯托里乌斯，双方重点就联合武器生产、无人机合作等议题展开磋商并达成共识。泽连斯基称，德国对乌克兰军事援助累计已达286亿欧元，目前两国正推进六项联合武器生产项目，此举标志着双方军事技术合作实现重要起步。会晤期间，双方敲定为期十年的无人机合作协议。泽连斯基对德国上月签署的乌克兰防空系统支持协议表示感谢，但暂未透露协议具体细节。泽连斯基同时高度认可德国在乌克兰能源领域提供的援助支持，并透露皮斯托里乌斯在会晤前已实地参观乌克兰一处能源设施。此外，乌德两国国防部长当日签署合作意向书，正式启动“勇敢德国”联合计划，助力国防技术研发与创新初创企业发展。  <br>  ,格隆汇5月11日｜据央视，乌克兰总统泽连斯基在基辅会见到访的德国国防部长皮斯托里乌斯，双方重点就联合武器生产、无人机合作等议题展开磋商并达成共识。泽连斯基称，德国对乌克兰军事援助累计已达286亿欧元，目前两国正推进六项联合武器生产项目，此举标志着双方军事技术合作实现重要起步…,https://www.gelonghui.com/live/2443755,2026-05-11T16:25:51.138Z,2026-05-11T15:47:43.249Z,{},55611390687386624,1106795362456113161,美国在伊朗拒绝和平提议 于直布罗陀展示核潜艇存在,https://www.gelonghui.com/live/2443747,格隆汇5月11日｜就在美国总统特朗普拒绝伊朗最新提出的停火方案，称其“完全不可接受”后，五角大楼证实，一艘美国海军俄亥俄级核潜艇已停靠直布罗陀港，这是罕见地公开披露“轰炸机”级潜艇的部署。美国海军表示，此次访问凸显了美国的核能力和北约的承诺，并指出该潜艇是核三位一体中最具生存能力的打击力量之一。该潜艇的具体型号尚未公布。  <br>  ,格隆汇5月11日｜就在美国总统特朗普拒绝伊朗最新提出的停火方案，称其“完全不可接受”后，五角大楼证实，一艘美国海军俄亥俄级核潜艇已停靠直布罗陀港，这是罕见地公开披露“轰炸机”级潜艇的部署。美国海军表示，此次访问凸显了美国的核能力和北约的承诺…,https://www.gelonghui.com/live/2443747,2026-05-11T16:25:51.137Z,2026-05-11T15:39:40.057Z,{},55611390687386624,1106795362456113162,美国财政部拍卖三个月期国债,https://www.gelonghui.com/live/2443746,格隆汇5月11日｜美国财政部拍卖三个月期国债，得标利率3.610%，投标倍数2.86；拍卖六个月期国债，得标利率3.615%，投标倍数2.91。  <br>  ,格隆汇5月11日｜美国财政部拍卖三个月期国债，得标利率3.610%，投标倍数2.86；拍卖六个月期国债，得标利率3.615%，投标倍数2.91。,https://www.gelonghui.com/live/2443746,2026-05-11T16:25:51.136Z,2026-05-11T15:39:18.337Z,{},55611390687386624,1106795362456113163,格隆汇5月11日｜伊朗称浓缩铀问题不容谈判。,https://www.gelonghui.com/live/2443745,格隆汇5月11日｜伊朗称浓缩铀问题不容谈判。  <br>  ,格隆汇5月11日｜伊朗称浓缩铀问题不容谈判。,https://www.gelonghui.com/live/2443745,2026-05-11T16:25:51.135Z,2026-05-11T15:35:43.613Z,{},55611390687386624,1106795362456113164,格隆汇5月11日｜美国总统特朗普表示，不考虑救助美国航空公司。,https://www.gelonghui.com/live/2443743,格隆汇5月11日｜美国总统特朗普表示，不考虑救助美国航空公司。  <br>  ,格隆汇5月11日｜美国总统特朗普表示，不考虑救助美国航空公司。,https://www.gelonghui.com/live/2443743,2026-05-11T16:25:51.134Z,2026-05-11T15:34:49.810Z,{},55611390687386624,1106795362456113165,欧股收盘涨跌不一,https://www.gelonghui.com/live/2443742,格隆汇5月11日｜欧洲斯托克600指数上涨0.11%，英国富时100指数上涨0.36%；德国DAX指数上涨0.07%，法国CAC 40指数下跌0.76%，西班牙IBEX指数下跌0.17%。  <br>  ,格隆汇5月11日｜欧洲斯托克600指数上涨0.11%，英国富时100指数上涨0.36%；德国DAX指数上涨0.07%，法国CAC 40指数下跌0.76%，西班牙IBEX指数下跌0.17%。,https://www.gelonghui.com/live/2443742,2026-05-11T16:25:51.133Z,2026-05-11T15:34:36.025Z,{},55611390687386624,1106795362456113166,美国与以色列之间的战争冲击全球粮食生产,https://www.gelonghui.com/live/2443741,格隆汇5月11日｜美伊封锁霍尔木兹海峡——这条化肥、燃料和航运的关键通道——导致亚洲各地柴油和化肥价格飙升。泰国等主要粮食出口国的农民正在减少种植面积、降低化肥用量，甚至完全放弃耕种，因为成本高于潜在利润。泰国的稻米产业受到的冲击尤为严重。一些农民让田地空置，而另一些农民则只种植了往常面积的一部分。尿素短缺和创纪录的燃油价格使得农业生产在经济上难以为继。由于泰国是世界上最大的稻米出口国之一，产量下降可能会在2026年晚些时候推高全球稻米价格。这场危机正在东南亚和南亚蔓延，那里数百万人的收入和粮食安全依赖于农业。  <br>  ,格隆汇5月11日｜美伊封锁霍尔木兹海峡——这条化肥、燃料和航运的关键通道——导致亚洲各地柴油和化肥价格飙升。泰国等主要粮食出口国的农民正在减少种植面积、降低化肥用量，甚至完全放弃耕种，因为成本高于潜在利润。泰国的稻米产业受到的冲击尤为严重。一些农民让田地空置…,https://www.gelonghui.com/live/2443741,2026-05-11T16:25:51.132Z,2026-05-11T15:34:18.626Z,{}",
      "id": "55611390687386624",
      "image": "https://cdn.gelonghui.com/static/web/www.ico.la.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.gelonghui.com/live",
      "title": "格隆汇快讯-7x24小时市场快讯-财经市场热点",
      "type": "feed",
      "url": "rsshub://gelonghui/live"
    }
  ],
  "url": "gelonghui.com/live",
  "view": 0
}
```
