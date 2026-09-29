# SKALD: Against the Black Priory 简体中文汉化

《SKALD: Against the Black Priory》完整简体中文汉化：剧情叙述、对话与选项、物品与法术、任务日志、书籍、教程、界面、战斗播报与状态提示，约 20 万字。中文字体按原版字号重绘，界面布局与原版一致。

A complete Simplified Chinese fan translation for [SKALD: Against the Black Priory](https://store.steampowered.com/app/1069160/) (v1.0.7e, Windows).

## 下载 / Download

- **[Releases](../../releases/latest)**：下载 `SKALD_SimplifiedChinese_v0.9.0.zip`
- mod.io（游戏官方模组平台，国内需要加速）：<https://mod.io/g/skald-against-the-bl/m/simplified-chinese-translation>

两处是同一个文件，SHA256 见发布说明。

## 安装

1. 关闭游戏。
2. Steam 里右键游戏 → 管理 → 浏览本地文件，打开游戏目录。
3. 把压缩包里的全部内容解压到游戏目录（`winhttp.dll` 要和 `SKALD Against the Black Priory.exe` 在同一层）。
4. 启动游戏即为中文。

包内附带 BepInEx 5.4.23.5。已经装过 BepInEx 5 的，只复制 `BepInEx\plugins\SkaldCN` 即可；装着 BepInEx 6 的请不要直接覆盖。

**卸载**：删除 `BepInEx\plugins\SkaldCN`。要连加载器一起删，再删除 `winhttp.dll`、`doorstop_config.ini`、`.doorstop_version` 和 `BepInEx` 文件夹。

**存档**：建议新开游戏。英文旧存档可以读取，但存档里已经记下的日志条目和部分名称可能仍是英文。

## 测试范围

AI 辅助翻译，之后做了术语统一、格式校验和两轮质量检查。实机游玩验证到第 2 章；之后的章节做了自动化检查（文本覆盖、字形覆盖、补丁加载、剧情分支条件逐条排查），还没有完整实机测过。

已知问题：右侧面板底框的「MAIN MENU」是画在贴图上的字，未汉化；只在 Windows 上测试过。

## 反馈

后面章节遇到漏译、文字溢出或读着别扭的句子，欢迎[提 Issue](../../issues)，附截图最好。遇到报错请附上 `BepInEx\LogOutput.log` 和 `Player.log`（路径见压缩包内 `README_SKALD_CN.txt`）。

## 关于本仓库 / About this repository

本仓库只发布打包好的汉化，不含翻译源文件。
This repository hosts release packages only; translation sources are not published here.

## 授权 / Licensing

- 汉化为玩家自制，与 High North Studios 和 Raw Fury 无关。汉化在运行时加载，不修改任何游戏文件。
  Unofficial fan translation, not affiliated with High North Studios or Raw Fury.
- 中文字体：[Fusion Pixel Font](https://github.com/TakWolf/fusion-pixel-font) © TakWolf（SIL OFL 1.1）、[Cubic 11](https://github.com/ACh-K/Cubic-11)。
- 加载器：[BepInEx](https://github.com/BepInEx/BepInEx)（LGPL-2.1）。
- 各许可证全文在压缩包的 `BepInEx\plugins\SkaldCN\LICENSES\` 里。
