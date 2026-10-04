## 插件目录

| 插件 | 当前版本 | 简介 | 下载 |
| --- | --- | --- | --- |
| [TimeUntil](#timeuntil) | 4.9 | 活动时间助手 | [⬇️ 下载](https://github.com/Yunxei/jingxia/releases/download/timeuntil-v4.9/TimeUntil-4.9.zip) |
| Panoptes | — | 屏幕提示与辅助 | 尚未发布 |
| packratio | — | 贸易货物辅助 | 尚未发布 |
| speedometer | — | 载具速度显示 | 尚未发布 |
| ReloadButton | — | 快速重载插件 | 尚未发布 |
| Nyxaria | — | 背包整理辅助 | 尚未发布 |
| combatcloset | — | 装备套装辅助 | 尚未发布 |

点击插件名称查看详细说明。

<a id="timeuntil"></a>

<details>
<summary>⏱️ TimeUntil 4.9 ｜ 活动时间助手</summary>

**插件说明**

用于查看地区状态、活动时间以及相关倒计时。

**主要功能**

- 地区和平 / 纷争 / 战争时间显示
- 游戏活动时间与倒计时
- 自定义显示内容
- 活动显示数量设置
- 主界面显示 / 隐藏
- 配置与界面状态保存

**下载**

[⬇️ 下载 TimeUntil 4.9](https://github.com/Yunxei/jingxia/releases/download/timeuntil-v4.9/TimeUntil-4.9.zip)

需要共享依赖：globals

第一次安装需要同时安装 globals；已经安装过则无需重复安装。

**安装方法**

解压到游戏 `Addon` 目录，最终结构：

```text
Addon/
└─ TimeUntil/
   ├─ toc.g
   └─ timeuntil.lua
```

**更新记录**

`4.9`

当前正式发布版本。

</details>

<details>
<summary>🧩 globals ｜ 共享依赖</summary>

- globals 是部分插件运行所需的共享依赖
- 当前已确认 TimeUntil、Panoptes、speedometer 使用 globals
- globals 无正式版本号
- 多个插件共用同一个 globals，只需安装一份

**下载**

[⬇️ 下载 globals](https://github.com/Yunxei/jingxia/releases/download/globals/globals.zip)

**安装方法**

解压到游戏 `Addon` 目录，最终结构：

```text
Addon/
└─ globals/
   ├─ apitypes.lua
   ├─ barmaker.lua
   ├─ button.lua
   ├─ buttoncommon.lua
   ├─ classmappings.lua
   ├─ utils.lua
   ├─ window.lua
   └─ windowcommon.lua
```

</details>
