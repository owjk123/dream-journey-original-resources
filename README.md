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

## 重要发现
- 服务器保留了V116到V147的所有历史版本
- **HTTPS截断问题**: HTTPS服务器会截断文件，务必使用HTTP地址下载
- 地图文件之前爬取失败是因为HTTPS截断问题，使用HTTP后全部成功
- XML数据文件均不在静态资源目录，为服务端动态加载

## 资源清单
详见 RESOURCE_LIST.md
