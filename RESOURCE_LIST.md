# 造梦江湖原版资源备份

**备份日期**: 2026-05-10
**资源来源**: http://sbai.4399.com/4399swf/upload_swf/ftp10/honghao/20130321/9/assets/

## 下载统计

| 目录 | 文件数 | 总大小 |
|------|--------|--------|
| main-swf | 1 | 3.1M |
| assets-swf | 271 | 153M |
| assets-map/maps | 37 | 18M |
| assets-audio | 11 | 6.2M |
| assets-other | 1 | 364K |

## 资源类型分布

### 核心功能SWF (assets-swf/ - 271个)
Public 25个 | Player 6个 | Role 17个 | RoleBig 9个 | fight 11个
icon 19个 | load 30个 | World 5个 | dialog 12个 | db 28个
FightEffect 4个 | EventEffect 2个 | LevelEvent 2个 | Weather 3个 | Shop 7个
Activity 11个 | Vip 1个 | Union 1个 | Upgrade 5个 | Instruction 6个
PlayerFight 1个 | EndlessBattle 4个 | Guide 8个 | OtherEffect 6个 | PluginGame 8个
MoveGame 2个 | FlipGame 3个 | LinkGame 2个 | MatchGame 2个 | RunGame 2个
另有EquipStrengthen, Daily, DailyWork, Strength, Achievement, WorldBoss等

### 地图SWF (assets-map/maps/ - 37个)
#### 主版本 (22个)
第1章: 1p1V132, 1p2V122, 1p3V142, 1p4V122
第2章: 2p1V122, 2p2V122, 2p3V122, 2p4V122
第3章: 3p1V122, 3p2V122, 3p3V126, 3p4V138
第4章: 4p1V122, 4p2V122, 4p3V126, 4p4V138
第5章: 5p1V126, 5p2V127, 5p3V136, 5p4V136
第6章: 6p1V142, 6p2V147

#### 历史版本 (15个)
1p1V122, 1p3V122, 1p3V125, 2p3V116, 2p4V117, 3p3V122, 3p4V117, 3p4V122,
4p3V119, 4p3V122, 4p4V119, 4p4V122, 5p1V123, 5p1V125, 5p3V130

### 场景音效 (assets-audio/scene/ - 7个)
scene_1V122.mp3 (520KB) | scene_2V122.mp3 (582KB) | scene_3V122.mp3 (488KB)
scene_4V122.mp3 (573KB) | scene_5V122.mp3 (573KB) | scene_6V142.mp3 (573KB)
hideV122.mp3 (376KB)

### 其他音频 (assets-audio/ - 4个)
fight.mp3, fightV122.mp3, start.mp3, startV122.mp3

### 其他资源 (assets-other/ - 1个)
ctrlmov4V122.swf (365KB) - 壳SWF中引用的控制模块

### XML数据文件 (0个 - 全部404)
Player.xml, PlayerData.xml, World.xml 等48个 - 均为服务端动态加载，不在静态资源目录

## 更新日志

### 2026-05-10 v2 - 补充地图和音效
- 补充下载22个主版本地图SWF（第1-6章完整地图）+ 15个历史版本，共37个地图文件
- 补充下载7个场景音效MP3（scene_1~6, hide）
- 发现ctrlmov4V122.swf（控制模块，365KB）
- 发现HTTP服务器可返回完整文件（之前HTTPS被截断）
- 48个XML数据文件均不在静态资源目录（404）
- 发现所有地图SWF确实存在，之前下载失败是因为HTTPS截断问题
