# ExptFont-MagiskModule<br>实验字库（Magisk模块）

![实机演示：桌面、微信公众号文章、知乎app首页](Presentation_1.0.png) 实机演示：桌面、微信公众号文章、知乎app首页

## 模块简介
本模块修改自[LXGW的作品](https://github.com/lxgw/advanced-cjk-font-magisk-module-template)，旨在手机上实现[天珩全字库（TH-Tshyn）](http://cheonhyeong.com/Simplified/download.html)的开箱即用，同时也尽力平衡移动端文本阅读的美观性与功能性。

---

## 字库组合方案
| 类型、字重 | 选用 | 备注 | 文件位置
|-------------------|-----------------------------------|-----------------------------------|-----------------------------------|
| 中文正体-常规 | [思源宋体（SemiBold字重）](https://github.com/notofonts/noto-cjk)v2.003 | **中文字形主体风格**，SemiBold起手，看起来超爽。 | `ExptFont/system/fonts/fontchw4.otf` |
| **中文正体-粗** | [思源宋体（Black字重）](https://github.com/notofonts/noto-cjk)v2.003 | 比[小标宋](https://www.foundertype.com/index.php/FontInfo/index/id/164)还粗。It's so BIG! | `ExptFont/system/fonts/fontchw5.otf` |
| <span style="font-weight: 300;">中文正体-细</span> | 宋一体 | [相关历史文化](http://printinginst.com/newsinfo/2222180.html)。 | `ExptFont/system/fonts/fontchw3.otf` |
| _中文斜体-常规_ | [霞鹜文楷-屏幕阅读版](https://github.com/lxgw/LxgwWenKai-Screen)v1.510  | 所谓“斜体”（italic）脱胎于西文手写体，对中文而言，使用楷体再合适不过。 | `ExptFont/system/fonts/fontciw4.ttf` |
| _**中文斜体-粗**_ | [阿里妈妈东方大楷](https://www.maoken.com/freefonts/17643.html) | 喜不喜欢妈妈？ | `ExptFont/system/fonts/fontciw5.ttf` |
| <span style="font-weight: 300;">_中文斜体-细_</span> | [霞鹜文楷（Light字重）](https://github.com/lxgw/LxgwWenKai)v1.511 | 选用light字重以增大差异度。 | `ExptFont/system/fonts/fontciw3.ttf` |
| Latin-Normal-Regular | [天珩泰晤士报体（TH-Times）](http://cheonhyeong.com/Tools/Times.html)v8.01 | **西文字形主体风格**，同时保证各类复杂文种正常显示。字体信息详见[说明文档](http://cheonhyeong.com/Tools/Times.html)。 | `ExptFont/system/fonts/fontenw4.ttc` |
| **Latin-Normal-Bold**;<br>_-Italic-Regular; **Bold**_ | 泰晤士报新罗马体（_Times_ **New** Roman） | 久经 | `ExptFont/system/fonts/fontenw5.ttf`; `fonteiw4.ttf`; `fonteiw5.ttf` |
| <span style="font-weight: 300;">Latin-Normal-Light;<br>_-Italic-Light_<span style="font-weight: 300;"> | [计算机现代体-统一码版（Computer Modern-Unicode）](https://ctan.org/pkg/cm-unicode)v0.7.0 | 考验 | `ExptFont/system/fonts/fontenw3.ttf`; `fonteiw3.ttf` |
| 扩展字符支持 | [天珩全字库（TH-Tshyn）](http://cheonhyeong.com/Simplified/download.html)v4.1.0 | **用于fallback**，覆盖[Unicode®16.0](https://www.unicode.org/versions/Unicode16.0.0/)全部字符（包括所有扩展汉字）。 | `ExptFont/system/fonts/TH-Tshyn-P0.ttf`; `TH-Tshyn-P1.ttf`; `TH-Tshyn-P2.ttf`; `TH-Tshyn-P16.ttf` |

---

## 安装说明
0. 确定爱机装有“救砖模块”，且已做好数据备份。
1. 在[Releases](https://github.com/Fisher4124/ExptFont-MagiskModule/releases)页面下载`ExptFont.zip` (或自行打包)，[百度网盘 (提取码lmqr)](https://pan.baidu.com/s/1YUE_1eQbMNQOK9kM16Fyog)。
2. Magisk，启动！ → 右下角【模块】 → 上部【从本地安装】。
3. 刷入后重启设备。

---

应许之作。