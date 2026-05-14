# 造梦江湖原版Flash服务端资源备份

从4399服务器备份的造梦江湖（小宝传奇）原版Flash游戏资源。

## 资源来源
- 4399游戏平台 (https://www.4399.com/)
- 资源基址(HTTP): http://sbai.4399.com/4399swf/upload_swf/ftp10/honghao/20130321/9/assets/
- 资源基址(HTTPS): https://sda.4399.com/4399swf/upload_swf/ftp10/honghao/20130321/9/assets/
- **注意**: HTTPS服务器会截断文件（返回23KB），请使用HTTP地址下载完整文件

## 目录结构
- `main-swf/` - 主SWF文件 (xbcqv147.swf, 3.1M)
- `assets-swf/` - 功能SWF资源（271个，含历史版本V116-V147）
- `assets-map/maps/` - 地图SWF（37个，第1-6章含历史版本）
- `assets-audio/` - 音频文件（11个，含场景音效和战斗/开始音效）
- `assets-other/` - 其他发现的文件（ctrlmov4V122.swf）
- `bili-articles/` - B站游戏详细介绍图文（子恒兄整理，含图片）
- `docs/` - 游戏分析文档
- `video-screenshots/` - B站视频截图

## bili-articles 目录说明

转载自B站UP主"子恒兄"的游戏详细介绍图文，包含完整的游戏系统截图和说明。

- `bili-articles/article1.md` - [总集篇①](https://b23.tv/w96YXEU)：VIP系统、称号图鉴、队伍界面（传功/队伍/觉醒/练功）、技能图鉴（87张图片）
- `bili-articles/article2.md` - [总集篇②](https://b23.tv/Oh2sUVA)：角色图鉴、商城系统、竞技场及活动日常任务系统（78张图片）
- `bili-articles/article1_images/` - 总集篇①配图（87张）
- `bili-articles/article2_images/` - 总集篇②配图（78张）

> 图文版权归原作者"子恒兄"所有，仅作资料备份用途。

## video-screenshots 目录说明

基于B站视频截图收集的游戏素材，用于游戏复刻项目参考。

### lichunyuan/ - 丽春院副本截图
- 来源: [造梦江湖1之小宝传奇 丽春院1-3隐藏副本全流程](https://b23.tv/9H41qF6)
- 内容: 丽春院关卡选择、大富翁走格玩法、回合制战斗、隐藏副本剧情、洞穴探索等截图（56张）
- 相关文档: `docs/lichunyuan-dungeon-analysis.md`

### lichunyuan-dungeon-analysis.md

丽春院1-3隐藏副本详细分析文档，包含：

- **关卡选择界面**: 1-1、1-2、1-3三个关卡，简易/困难两种难度
- **核心玩法**: 大富翁式走格系统，如意骰子道具（上限399个）
- **战斗系统**: 回合制卡牌对战，己方角色（双儿、韦小宝、洪教主）
- **敌方怪物**: 妖魔、恶犬、乌鸦、护院、醉汉、罗刹祭司等
- **隐藏副本**: 剧情触发进入洞穴探索，收集装备奖励
- **奖励系统**: 惊喜卡牌、金币/装备获得、战斗胜利结算
- **UI元素**: 角色信息栏、资源显示、功能按钮、道具系统

## docs 目录说明

- `lichunyuan-dungeon-analysis.md` - 丽春院隐藏副本详细分析（基于视频截图）

## 重要发现
- 服务器保留了V116到V147的所有历史版本
- **HTTPS截断问题**: HTTPS服务器会截断文件，务必使用HTTP地址下载
- 地图文件之前爬取失败是因为HTTPS截断问题，使用HTTP后全部成功
- XML数据文件均不在静态资源目录，为服务端动态加载

## 资源清单
详见 RESOURCE_LIST.md

