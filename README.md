# 手 K 动画源文件

本仓库收录“手 K 动画”作品对应的 3ds Max 工程和多机位动作视频，用于动作设计展示与源文件核验。

## 目录结构

```text
max/                  3ds Max 动作工程
video/
  blade-idle/         刃 · 待机
  hu-tao-run/         胡桃 · 跑步
  anby-strike/        安比 · 单击
  anby-combo/         安比 · 连击
  jiyan-combo/        忌炎 · 连击
```

每组视频包含 `front.mp4`、`side.mp4` 和 `dual.mp4`，分别对应正视图、侧视图和双视图。

## 文件对应

| 动作 | 角色 | MAX 源文件 | 正视图 | 侧视图 | 双视图 |
| --- | --- | --- | --- | --- | --- |
| 待机 | 刃 | [`max/blade-idle.max`](max/blade-idle.max) | [`front.mp4`](video/blade-idle/front.mp4) | [`side.mp4`](video/blade-idle/side.mp4) | [`dual.mp4`](video/blade-idle/dual.mp4) |
| 跑步 | 胡桃 | [`max/hu-tao-run.max`](max/hu-tao-run.max) | [`front.mp4`](video/hu-tao-run/front.mp4) | [`side.mp4`](video/hu-tao-run/side.mp4) | [`dual.mp4`](video/hu-tao-run/dual.mp4) |
| 单击 | 安比 | [`max/anby-strike.max`](max/anby-strike.max) | [`front.mp4`](video/anby-strike/front.mp4) | [`side.mp4`](video/anby-strike/side.mp4) | [`dual.mp4`](video/anby-strike/dual.mp4) |
| 连击 | 安比 | [`max/anby-combo.max`](max/anby-combo.max) | [`front.mp4`](video/anby-combo/front.mp4) | [`side.mp4`](video/anby-combo/side.mp4) | [`dual.mp4`](video/anby-combo/dual.mp4) |
| 连击 | 忌炎 | [`max/jiyan-combo.max`](max/jiyan-combo.max) | [`front.mp4`](video/jiyan-combo/front.mp4) | [`side.mp4`](video/jiyan-combo/side.mp4) | [`dual.mp4`](video/jiyan-combo/dual.mp4) |

## 说明

- MAX 文件是动作制作源工程。
- MP4 文件是多机位动作展示视频，便于不安装 3ds Max 时直接查看。
- 角色与游戏相关素材版权归原权利人所有，本仓库仅用于作品展示与交流。
