# Ratkin Police｜鼠民警察

RimWorld 1.6 / Ratkin 警务装备 Mod。

## 定位
这是一个完全置于 Ratkin 世界观中的警务装备扩展。视觉上采用现代警务风格，但设定、组织与装备说明均以鼠民城镇的治安、巡逻、警务辅助和特勤体系为背景，不对应现实中的具体国家、机构或组织。

## 主 Mod 内容
- 民警：执勤服、秋冬服、警察背心、大檐帽、执勤帽
- 辅警：执勤服、秋冬服、反光衣、执勤帽
- 特警：执勤服、秋冬服、战术背心、贝雷帽
- 通用：甩棍执勤腰带、配枪执勤腰带、执法记录仪与肩灯

## 警衔子模块
警衔系统位于独立的 `Ranks/` 子模块中。
- 未启用 Rocket's Ranks：只加载主装备，不加载警衔。
- 启用 Rocket's Ranks：自动加载 8 级辅警 + 13 级警衔，共 21 级。
- 肩章逻辑、RankPack、RankDef 与 RankExtension 结构沿用 CPOLICE 的实现方式。
- 所有肩章贴图集中在一个文件夹中，不再为每一级警衔单独建立目录。

## 依赖
- Ratkin / NewRatkinPlus
- Humanoid Alien Races（按 Ratkin 版本需要）
- Rocket's Ranks（仅警衔子模块需要）
