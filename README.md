# ExptFont-MagiskModule<br>实验字库（Magisk模块）

![实机演示：桌面、微信公众号文章、知乎app首页](Presentation_1.0.png) 实机演示：桌面、微信公众号文章、知乎app首页

## 模块简介
本模块修改自[LXGW的作品](https://github.com/lxgw/advanced-cjk-font-magisk-module-template)，目的在于平衡移动端文本阅读美观性与功能性，同时保证扩展字符的全覆盖。

---

## 字库组合方案
| 类型 | 调用 | 备注 |
|-------------------|-----------------------------------|-----------------------------------|
| 中文正体-常规 | [思源宋体（SemiBold字重）](https://github.com/notofonts/noto-cjk)v2.003 | **字形主体风格**。 |
| **中/西文正体-加粗** | [思源黑体（Bold字重）](https://github.com/notofonts/noto-cjk)v2.004 | 宋体加粗为黑体的“传统”设计，使视觉上与常规文本差异更明显。 |
| _中文斜体-常规_ | [霞鹜文楷（屏幕阅读版）](https://github.com/lxgw/LxgwWenKai-Screen)  | 所谓“斜体”（italic）脱胎于西文手写体，对中文而言，使用楷体再合适不过。 |
| _**中文斜体-加粗**_ | [阿里妈妈东方大楷](https://www.maoken.com/freefonts/17643.html) | 喜不喜欢妈妈？ |
| 西文正体-常规 | [天珩泰晤士报体（TH-Times）](http://cheonhyeong.com/Tools/Times.html)v8.01 | 保证各类复杂文种正常显示，故调用优先级高。详见[沈天珩的说明文档](http://cheonhyeong.com/Tools/Times.html)。 |
| _西文斜体-常规、**加粗**_ | 泰晤士报新罗马体（Times New Roman） | 增补了中文标点符号。 |
| 扩展字符支持 | [天珩全字库（TH-Tshyn）](http://cheonhyeong.com/Simplified/download.html)v4.1.0 | **用于fallback**，覆盖[Unicode®16.0](https://www.unicode.org/versions/Unicode16.0.0/)全部字符（包括所有扩展汉字）。 |

---

## 安装说明
0. 确定爱机装有“救砖模块”，且已做好数据备份。
1. 在[Releases](https://github.com/Fisher4124/ExptFont-MagiskModule/releases)页面下载`ExptFont.zip`，或自行打包。
2. Magisk，启动！ → 右下角【模块】 → 上部【从本地安装】。
3. 刷入后重启设备。

---

应许之作。