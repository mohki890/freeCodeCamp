---
title: Color and Usability
localeTitle: 颜色和可用性
---
## 颜色和可用性

就像[通过视觉显示表现颜色](/visual-design/color-theory/index.md)的差异一样，人眼和大脑以各种方式解释颜色。

大约有二十分之一的人有色盲。\[2\] 这几乎是十亿人！ 色盲是指将一系列不同颜色解释为一种颜色的色调。 有时一个人不知道他们会遇到色盲，因为这些颜色“看起来很正常”。 这对于字母与其背景之间的对比色以及警报有着严重的影响，例如，色彩在其中传达了重要的背景。 甚至像传递'停止'和'去'这样简单的事情也是有问题的，因为最常见的色盲形式是红色和绿色看起来相同。

超过百分之一的人口有[其他类型的重大视力丧失（Wikipedia.org）](https://en.wikipedia.org/wiki/Visual_impairment) 。 损失可能包括对视觉清晰度（近视或远视）范围内的对比度，失真和限制的过敏或过小的敏感度。

计算机屏幕能够显示对比度，这是纸张上可用对比度的两倍。

以下是帮助应对设计挑战的指南，以适应这些差异，同时不会对他人的体验产生负面影响。 这些指南还有助于[自适应技术（Wikipedia.org）](https://en.wikipedia.org/wiki/Assistive_technology#Visual_impairments)更有效地工作。

### 定义

**亮度**要确定指南的亮度，请将RGB颜色值相加。如果字体具有RGB颜色（255,0,0），则表示它具有100％红色，0％绿色和蓝色光。它的亮度是255 + 0 + 0 = 255。 最大亮度为白色，255 + 255 + 255 = 765。

**对比度**要确定指南的对比度，请减去两种颜色之间的_亮度_ 。

### 方针

1.  避免在文本中超出纸张级别的对比。文本和文本背景之间的亮度差异至少为300（如果不是400） - 对于小字体来说稍微多一点，对于较大字体则要少一些。 如果字体颜色为红色，则RGB值可能为（255,0,0），亮度为765中的255。 如果背景为黄色，则RGB值可能为（255,255,0）= 510。 510和255之间的差异是255。 此示例对比度太低，并将我们带到下一个指南。
    
2.  为了检查对比度和调整色盲，假设红色和绿色原色是相同的颜色。 最常见的色盲形式类似于红色和绿色。 这意味着对于重要通信的有效性，可以考虑红色RGB（255,0,0），绿色RGB（0,255,0）和“Olive”\[1\] RGB（127,127,0）的颜色基本上是相同颜色的相同颜色对比。 为了计算对比度，黄色RGB（255,255,0）的亮度是任何一种原色的两倍。 两种基色仍然产生两倍的亮度。
    

### 概要

好消息是，在选择适合读者的有效颜色托盘方面仍有很多灵活性。

[这种快速风格指南有助于确保您的拉取请求被接受](https://github.com/freecodecamp/guides/blob/master/README.md) 。

#### 更多信息：

1.  [网页颜色（Wikipedia.org）](https://en.wikipedia.org/wiki/Web_colors#Web-safe_colors)
    
2.  [色盲（Wikipedia.org）](https://en.wikipedia.org/wiki/Color_blindness)