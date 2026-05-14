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

## bili-articles 目录说明

转载自B站UP主"子恒兄"的游戏详细介绍图文，包含完整的游戏系统截图和说明。

- `bili-articles/article1.md` - [总集篇①](https://b23.tv/w96YXEU)：VIP系统、称号图鉴、队伍界面（传功/队伍/觉醒/练功）、技能图鉴（87张图片）
- `bili-articles/article2.md` - [总集篇②](https://b23.tv/Oh2sUVA)：角色图鉴、商城系统、竞技场及活动日常任务系统（78张图片）
- `bili-articles/article1_images/` - 总集篇①配图（87张）
- `bili-articles/article2_images/` - 总集篇②配图（78张）

> 图文版权归原作者"子恒兄"所有，仅作资料备份用途。

## 重要发现
- 服务器保留了V116到V147的所有历史版本
- **HTTPS截断问题**: HTTPS服务器会截断文件，务必使用HTTP地址下载
- 地图文件之前爬取失败是因为HTTPS截断问题，使用HTTP后全部成功
- XML数据文件均不在静态资源目录，为服务端动态加载

## 资源清单
详见 RESOURCE_LIST.md
