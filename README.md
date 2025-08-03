# Jellyfin-Player-Enhancements
这是一个为 Jellyfin 网页播放器设计的 Tampermonkey 脚本，为Jellyfin网页播放器添加一些额外功能。

## 功能：
- 弹幕支持: 基于 [jellyfin-plugin-danmu](https://github.com/cxfksword/jellyfin-plugin-danmu) 插件，为jellyfin网页播放器的视频添加弹幕功能。
  - UI 集成: 播放器控制栏右下角会新增弹幕开关和设置按钮。
  - 自定义设置: 支持调整弹幕速度、字体大小和颜色，并自动保存您的设置。
  - 智能提示: 当视频无弹幕时，会显示相应的提示信息。

- 倍速播放增强: 提供了键盘快捷键来快速控制播放速度，参考了[这个脚本](https://greasyfork.org/zh-CN/scripts/523429-%E8%A7%86%E9%A2%91%E5%80%8D%E9%80%9F%E6%92%AD%E6%94%BE)开发。
  - 长按 →: 快速切换到预设倍速播放（例如 2.0x）。松开按键后，自动恢复至长按前的播放速度。
  - 短按 →: 快速前进 5 秒。
  - [ 和 ]: 实时调整当前播放速度，以 0.5x 为步长。
  - \- 和 =: 调整长按 → 键的预设倍速。
  - P: 恢复到正常播放速度（1.0x）。

## 安装方式：
- 通过greasyfork安装(推荐)，点击[这里](https://update.greasyfork.org/scripts/544506/Jellyfin%20%E6%92%AD%E6%94%BE%E5%99%A8%E5%A2%9E%E5%BC%BA%E5%8A%9F%E8%83%BD%20%28%E5%BC%B9%E5%B9%95%2B%E5%80%8D%E9%80%9F%29.user.js)安装。
- 自己在油猴中新建脚本，把脚本内容粘贴进去并保存。
