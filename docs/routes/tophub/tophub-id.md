# 今日热榜 - 榜单

## Coverage
`index-only`

## Route
- Namespace: `tophub`
- Namespace Name: `今日热榜`
- Route Path: `/tophub/:id`
- Route Name: `榜单`
- Example: `/tophub/Om4ejxvxEN`
- URL: `tophub.today`
- Language: `_None_`
- Categories: `new-media, popular`
- Maintainers: `LogicJake`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 榜单id，可在 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "TOPHUB_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `tophub.today/n/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media",
    "popular"
  ],
  "example": "/tophub/Om4ejxvxEN",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "TOPHUB_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1675,
  "location": "index.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "榜单",
  "parameters": {
    "id": "榜单id，可在 URL 中找到"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "tophub.today/n/:id"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "订阅数：33万+ - Powered by RSSHub",
      "errorAt": "2026-05-14T03:02:38.883Z",
      "errorMessage": "Failed query: insert into \"entries\" (\"feed_id\", \"id\", \"title\", \"url\", \"content\", \"description\", \"guid\", \"author\", \"author_url\", \"author_avatar\", \"inserted_at\", \"published_at\", \"media\", \"categories\", \"attachments\", \"extra\", \"language\", \"summary\", \"body_r2_key\", \"body_offloaded_at\") values ($1, $2, $3, $4, $5, $6, $7, default, default, default, $8, $9, default, default, default, default, default, default, default, default), ($10, $11, $12, $13, $14, $15, $16, default, default, default, $17, $18, default, default, default, default, default, default, default, default), ($19, $20, $21, $22, $23, $24, $25, default, default, default, $26, $27, default, default, default, default, default, default, default, default), ($28, $29, $30, $31, $32, $33, $34, default, default, default, $35, $36, default, default, default, default, default, default, default, default), ($37, $38, $39, $40, $41, $42, $43, default, default, default, $44, $45, default, default, default, default, default, default, default, default), ($46, $47, $48, $49, $50, $51, $52, default, default, default, $53, $54, default, default, default, default, default, default, default, default), ($55, $56, $57, $58, $59, $60, $61, default, default, default, $62, $63, default, default, default, default, default, default, default, default), ($64, $65, $66, $67, $68, $69, $70, default, default, default, $71, $72, default, default, default, default, default, default, default, default), ($73, $74, $75, $76, $77, $78, $79, default, default, default, $80, $81, default, default, default, default, default, default, default, default), ($82, $83, $84, $85, $86, $87, $88, default, default, default, $89, $90, default, default, default, default, default, default, default, default), ($91, $92, $93, $94, $95, $96, $97, default, default, default, $98, $99, default, default, default, default, default, default, default, default), ($100, $101, $102, $103, $104, $105, $106, default, default, default, $107, $108, default, default, default, default, default, default, default, default), ($109, $110, $111, $112, $113, $114, $115, default, default, default, $116, $117, default, default, default, default, default, default, default, default), ($118, $119, $120, $121, $122, $123, $124, default, default, default, $125, $126, default, default, default, default, default, default, default, default), ($127, $128, $129, $130, $131, $132, $133, default, default, default, $134, $135, default, default, default, default, default, default, default, default), ($136, $137, $138, $139, $140, $141, $142, default, default, default, $143, $144, default, default, default, default, default, default, default, default), ($145, $146, $147, $148, $149, $150, $151, default, default, default, $152, $153, default, default, default, default, default, default, default, default), ($154, $155, $156, $157, $158, $159, $160, default, default, default, $161, $162, default, default, default, default, default, default, default, default), ($163, $164, $165, $166, $167, $168, $169, default, default, default, $170, $171, default, default, default, default, default, default, default, default), ($172, $173, $174, $175, $176, $177, $178, default, default, default, $179, $180, default, default, default, default, default, default, default, default), ($181, $182, $183, $184, $185, $186, $187, default, default, default, $188, $189, default, default, default, default, default, default, default, default), ($190, $191, $192, $193, $194, $195, $196, default, default, default, $197, $198, default, default, default, default, default, default, default, default), ($199, $200, $201, $202, $203, $204, $205, default, default, default, $206, $207, default, default, default, default, default, default, default, default), ($208, $209, $210, $211, $212, $213, $214, default, default, default, $215, $216, default, default, default, default, default, default, default, default), ($217, $218, $219, $220, $221, $222, $223, default, default, default, $224, $225, default, default, default, default, default, default, default, default), ($226, $227, $228, $229, $230, $231, $232, default, default, default, $233, $234, default, default, default, default, default, default, default, default), ($235, $236, $237, $238, $239, $240, $241, default, default, default, $242, $243, default, default, default, default, default, default, default, default), ($244, $245, $246, $247, $248, $249, $250, default, default, default, $251, $252, default, default, default, default, default, default, default, default), ($253, $254, $255, $256, $257, $258, $259, default, default, default, $260, $261, default, default, default, default, default, default, default, default), ($262, $263, $264, $265, $266, $267, $268, default, default, default, $269, $270, default, default, default, default, default, default, default, default) on conflict (\"feed_id\",\"guid\") do update set \"title\" = excluded.\"title\", \"content\" = excluded.\"content\", \"description\" = excluded.\"description\", \"media\" = excluded.\"media\", \"attachments\" = excluded.\"attachments\", \"extra\" = COALESCE(\"entries\".\"extra\", '{}'::jsonb) || COALESCE(excluded.\"extra\", '{}'::jsonb) returning \"id\", \"published_at\", \"inserted_at\", \"feed_id\", \"title\", \"description\", \"content\", \"author\", \"url\", \"guid\", \"media\", \"attachments\"\nparams: 63099316103761920,1110335223465168896,小石头跃上球台，龙队会对他说什么,https://mp.weixin.qq.com/s?__biz=MzU4MjQ1MTc5Mg==&mid=2247495942&idx=1&sn=70bae39fc5c14ce1d81358dc8e7da9da&chksm=209406#rd,10.0万,10.0万,https://mp.weixin.qq.com/s?__biz=MzU4MjQ1MTc5Mg==&mid=2247495942&idx=1&sn=70bae39fc5c14ce1d81358dc8e7da9da&chksm=209406#rd,2026-05-14T03:02:28.778Z,2026-05-14T03:02:28.735Z,63099316103761920,1110335223465168897,恒温循环大节奏稳稳的！午后局部有短时阵雨,https://mp.weixin.qq.com/s/5VDUUoM-HK2Z-173OzvgxA,10.0万,10.0万,https://mp.weixin.qq.com/s/5VDUUoM-HK2Z-173OzvgxA,2026-05-14T03:02:28.777Z,2026-05-14T03:02:28.734Z,63099316103761920,1110335223465168898,《给阿嬷的情书》为何让人“含泪推荐”,https://mp.weixin.qq.com/s/7QXb4S_UgZ4d0MCg3YisZQ,10.0万,10.0万,https://mp.weixin.qq.com/s/7QXb4S_UgZ4d0MCg3YisZQ,2026-05-14T03:02:28.776Z,2026-05-14T03:02:28.733Z,63099316103761920,1110335223465168899,我发现多看报纸真的很有益处,https://mp.weixin.qq.com/s/Ito3-HUezl9ymlBOYZvXOA,10.0万,10.0万,https://mp.weixin.qq.com/s/Ito3-HUezl9ymlBOYZvXOA,2026-05-14T03:02:28.775Z,2026-05-14T03:02:28.732Z,63099316103761920,1110335223465168900,特朗普称，他将会要求中国对美国的经贸团队访问提供便利，外交部：中方愿同美方一道秉持平等、尊重、互惠的精神，扩大合作，管控分歧,https://mp.weixin.qq.com/s/PICyLOY7nfF0e7UT2mSYpg,10.0万,10.0万,https://mp.weixin.qq.com/s/PICyLOY7nfF0e7UT2mSYpg,2026-05-14T03:02:28.774Z,2026-05-14T03:02:28.731Z,63099316103761920,1110335223465168901,特朗普称将要求中国对美国的经贸团队访问提供便利，外交部：中方愿同美方一道秉持平等、尊重、互惠的精神，扩大合作，管控分歧,https://mp.weixin.qq.com/s/iup8iOt7s6PbJst7oXENJw,10.0万,10.0万,https://mp.weixin.qq.com/s/iup8iOt7s6PbJst7oXENJw,2026-05-14T03:02:28.773Z,2026-05-14T03:02:28.730Z,63099316103761920,1110335223465168902,最高可达37℃以上！多地将现今年首个高温天,https://mp.weixin.qq.com/s/IRlPuRVJWwYjn_8w5mO5rQ,10.0万,10.0万,https://mp.weixin.qq.com/s/IRlPuRVJWwYjn_8w5mO5rQ,2026-05-14T03:02:28.772Z,2026-05-14T03:02:28.729Z,63099316103761920,1110335223465168903,和老婆一起洗澡，正帮她涂沐浴露 她问：“你以前和前女友也这样洗过澡吗？” 我一听，愣了下，决定装没听见 她又说：“哎呀你就说实话吧，我不会生气的” 我小心...,https://mp.weixin.qq.com/s/Dc1swURZWGgnD0vgUzineQ,10.0万,10.0万,https://mp.weixin.qq.com/s/Dc1swURZWGgnD0vgUzineQ,2026-05-14T03:02:28.771Z,2026-05-14T03:02:28.728Z,63099316103761920,1110335223465168904,演员李威被判刑,https://mp.weixin.qq.com/s/204vJJbD4rQQaEjd-qfN3w,10.0万,10.0万,https://mp.weixin.qq.com/s/204vJJbD4rQQaEjd-qfN3w,2026-05-14T03:02:28.770Z,2026-05-14T03:02:28.727Z,63099316103761920,1110335223465168905,美国财政部制裁了12个实体，指控其向中国运输伊朗石油，外交部：中方坚决反对非法单边制裁，将坚定维护本国企业正当合法权益,https://mp.weixin.qq.com/s/UvvDGjhQgrZyWgEPibY4fQ,10.0万,10.0万,https://mp.weixin.qq.com/s/UvvDGjhQgrZyWgEPibY4fQ,2026-05-14T03:02:28.769Z,2026-05-14T03:02:28.726Z,63099316103761920,1110335223465168906,“饭后百步走”，是饭后多久？医生提醒这7类人要慎重,https://mp.weixin.qq.com/s/4u793wkXv2C0I4PYiiYvIg,10.0万,10.0万,https://mp.weixin.qq.com/s/4u793wkXv2C0I4PYiiYvIg,2026-05-14T03:02:28.768Z,2026-05-14T03:02:28.725Z,63099316103761920,1110335223465168907,公职人员通过OA传涉密文件致泄密！重要提醒→,https://mp.weixin.qq.com/s/GNdo6MWz4Tq7RzvwUcR4gQ,10.0万,10.0万,https://mp.weixin.qq.com/s/GNdo6MWz4Tq7RzvwUcR4gQ,2026-05-14T03:02:28.767Z,2026-05-14T03:02:28.724Z,63099316103761920,1110335223465168908,特朗普，不急。 特朗普向来是出了名的急性子，行事风格干脆直接。 说到嘴里，就要拿到手里。作为大国总统，有时候，甚至会为了一件事情，连发几条社交媒体动态。...,https://mp.weixin.qq.com/s/JJYM7oj2RbI4Fl6xIjD17w,9.0万,9.0万,https://mp.weixin.qq.com/s/JJYM7oj2RbI4Fl6xIjD17w,2026-05-14T03:02:28.766Z,2026-05-14T03:02:28.723Z,63099316103761920,1110335223465168909,一季度结婚对数下降：年轻人是咋了？,https://mp.weixin.qq.com/s/1KKj7Qnf7I7rhQO5pSEVhg,8.6万,8.6万,https://mp.weixin.qq.com/s/1KKj7Qnf7I7rhQO5pSEVhg,2026-05-14T03:02:28.765Z,2026-05-14T03:02:28.722Z,63099316103761920,1110335223465168910,狼来啦。。。,https://mp.weixin.qq.com/s/sjpvcEiD26mk2kSRzHYqHw,8.5万,8.5万,https://mp.weixin.qq.com/s/sjpvcEiD26mk2kSRzHYqHw,2026-05-14T03:02:28.764Z,2026-05-14T03:02:28.721Z,63099316103761920,1110335223465168911,演员李威被判刑,https://mp.weixin.qq.com/s/r_vf_k6yeQvf5kvg1RMfTg,8.4万,8.4万,https://mp.weixin.qq.com/s/r_vf_k6yeQvf5kvg1RMfTg,2026-05-14T03:02:28.763Z,2026-05-14T03:02:28.720Z,63099316103761920,1110335223465168912,澎湃暗访后，九华山景区回应,https://mp.weixin.qq.com/s/mRgbwP3K8sFNYHw0lYrumQ,7.3万,7.3万,https://mp.weixin.qq.com/s/mRgbwP3K8sFNYHw0lYrumQ,2026-05-14T03:02:28.762Z,2026-05-14T03:02:28.719Z,63099316103761920,1110335223465168913,电力板块，掀涨停潮,https://mp.weixin.qq.com/s/439rB7h9rmq1dQoFvtyrvg,7.2万,7.2万,https://mp.weixin.qq.com/s/439rB7h9rmq1dQoFvtyrvg,2026-05-14T03:02:28.761Z,2026-05-14T03:02:28.718Z,63099316103761920,1110335223465168914,5月13日-早上好，美好的早晨，写上健康，填上快乐，加上好运，祝你每天快乐，幸福安康!,https://mp.weixin.qq.com/s/TGHeVBrIraDt0muDOkSkxQ,6.8万,6.8万,https://mp.weixin.qq.com/s/TGHeVBrIraDt0muDOkSkxQ,2026-05-14T03:02:28.760Z,2026-05-14T03:02:28.717Z,63099316103761920,1110335223465168915,惊悚！全国各地树上忽然集中出现大量诡异奇怪符号！真相是？,https://mp.weixin.qq.com/s/9bAmGoL0RrLXHO3DOSZdbw,3.6万,3.6万,https://mp.weixin.qq.com/s/9bAmGoL0RrLXHO3DOSZdbw,2026-05-14T03:02:28.759Z,2026-05-14T03:02:28.716Z,63099316103761920,1110335223465168916,安徽空地轨一体化超级枢纽通过验收，将由市域铁S1连通合肥西站,https://mp.weixin.qq.com/s/o6_rrDKu42PZsrMISl_0Lg,2.1万,2.1万,https://mp.weixin.qq.com/s/o6_rrDKu42PZsrMISl_0Lg,2026-05-14T03:02:28.758Z,2026-05-14T03:02:28.715Z,63099316103761920,1110335223465168917,南京市公安局致信,https://mp.weixin.qq.com/s/WPbeTIhV7V0niyPgJQldxQ,1.9万,1.9万,https://mp.weixin.qq.com/s/WPbeTIhV7V0niyPgJQldxQ,2026-05-14T03:02:28.757Z,2026-05-14T03:02:28.714Z,63099316103761920,1110335223465168918,最近微博热搜前两名，居然都跟豆包有关。第一条叫“豆包 收费”，第二条，一看差点没笑死我—— “豆包 笨还收费”。[偷笑] 不得不说，网友的嘴，有时候比AI毒多...,https://mp.weixin.qq.com/s/LsfKDpIpADuOqHcZmbqS0Q,1.8万,1.8万,https://mp.weixin.qq.com/s/LsfKDpIpADuOqHcZmbqS0Q,2026-05-14T03:02:28.756Z,2026-05-14T03:02:28.713Z,63099316103761920,1110335223465168919,痛心 | 天津90后新婚夫妻，双双确诊罕见病！孩子出生即夭折……,https://mp.weixin.qq.com/s/hDFzGwjFaJiKjMeZ0WcTkQ,1.8万,1.8万,https://mp.weixin.qq.com/s/hDFzGwjFaJiKjMeZ0WcTkQ,2026-05-14T03:02:28.755Z,2026-05-14T03:02:28.712Z,63099316103761920,1110335223465168920,B司取消销售指标,https://mp.weixin.qq.com/s/P9qdUOO-l6HBCfWn_mgO-w,1.8万,1.8万,https://mp.weixin.qq.com/s/P9qdUOO-l6HBCfWn_mgO-w,2026-05-14T03:02:28.754Z,2026-05-14T03:02:28.711Z,63099316103761920,1110335223465168921,母亲节大S女儿小玥儿开通账号，就因为关注徐家人不到24小时就遭网暴,https://mp.weixin.qq.com/s?__biz=MzIwMTExMzg5NQ==&mid=2649369580&idx=1&sn=d6f148b1669c60a8283216b2b0d0206a&chksm=793681#rd,1.1万,1.1万,https://mp.weixin.qq.com/s?__biz=MzIwMTExMzg5NQ==&mid=2649369580&idx=1&sn=d6f148b1669c60a8283216b2b0d0206a&chksm=793681#rd,2026-05-14T03:02:28.753Z,2026-05-14T03:02:28.710Z,63099316103761920,1110335223465168922,印度：我们要引领6G，中国行吗？韩国：人家专利遥遥领先，印度网友：恶意回答,https://mp.weixin.qq.com/s?__biz=MzU5MTA1MjM5MA==&mid=2247577514&idx=2&sn=c7fd3e0cd18e444b61fbba97dc89b3fe&chksm=753698#rd,9221,9221,https://mp.weixin.qq.com/s?__biz=MzU5MTA1MjM5MA==&mid=2247577514&idx=2&sn=c7fd3e0cd18e444b61fbba97dc89b3fe&chksm=753698#rd,2026-05-14T03:02:28.752Z,2026-05-14T03:02:28.709Z,63099316103761920,1110335223465168923,“珍品鲜虫草”价格暴跌！当地藏民小妹的话让人恍然大悟！,https://mp.weixin.qq.com/s/u79PwdDiVya5hBkuwT_Q8Q,8785,8785,https://mp.weixin.qq.com/s/u79PwdDiVya5hBkuwT_Q8Q,2026-05-14T03:02:28.751Z,2026-05-14T03:02:28.708Z,63099316103761920,1110335223465168924,当我开始“不要脸”养娃，孩子好带多了！,https://mp.weixin.qq.com/s/eX0IWbJCKqj3_IOemfDV6A,8209,8209,https://mp.weixin.qq.com/s/eX0IWbJCKqj3_IOemfDV6A,2026-05-14T03:02:28.750Z,2026-05-14T03:02:28.707Z,63099316103761920,1110335223465168925,以为增肥，实则减脂！这宝贝营养低GI，口口爽滑弹！,https://mp.weixin.qq.com/s/R6tAejTOrXYdtAAh7trCRg,7443,7443,https://mp.weixin.qq.com/s/R6tAejTOrXYdtAAh7trCRg,2026-05-14T03:02:28.749Z,2026-05-14T03:02:28.706Z",
      "id": "63099316103761920",
      "image": "https://file.ipadown.com/tophub/assets/images/media/mp.weixin.qq.com.png_160x160.png",
      "ownerUserId": null,
      "siteUrl": "https://tophub.today/n/WnBe01o371",
      "title": "微信 ‧ 24h热文榜",
      "type": "feed",
      "url": "rsshub://tophub/WnBe01o371"
    },
    {
      "description": "订阅数：19万+ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61088973762758656",
      "image": "https://file.ipadown.com/tophub/assets/images/media/tieba.baidu.com.png_160x160.png",
      "ownerUserId": null,
      "siteUrl": "https://tophub.today/n/Om4ejxvxEN",
      "title": "百度贴吧 ‧ 热议榜",
      "type": "feed",
      "url": "rsshub://tophub/Om4ejxvxEN"
    }
  ]
}
```
