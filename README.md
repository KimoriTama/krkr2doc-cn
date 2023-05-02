# 吉里吉里2 中文手册 krkr2doc-cn
本项目从2017年起缄默的U子未进行过任何更新，2023年3月起fork到本仓库下，进行更新与维护。

## 图像处理模式的相关术语对照

| 日语原文     | 英语术语                           | 中文翻译  |
| ------------ | ---------------------------------- | --------- |
| アルファ合成 | Alpha blending / Alpha compositing | alpha混合 |
| 加算アルファ合成 | Additive Alpha blending | 加法alpha混合 |
| 覆い焼き合成 | Dodge Blend Mode |颜色减淡混合|
| 焼き込み合成 | （Color）Burn Blending Mode |颜色加深混合|
| 乗算合成 | Multiply Blend Mode |乘法混合|
| 加算合成 | Additive Blend Mode |加法混合|
| 減算合成 | Subtractive  Blend Mode |减法混合|
| スクリーン合成 | Screen Blend Mode |屏幕混合（ps里叫滤色）|
| スクリーン乗算合成 | Screen Multiply Blend Mode |屏幕乘法混合|
| オーバーレイ合成 | Overlay Blend Mode |叠加混合|
| ソフトライト合成 | Soft Light Blend Mode |柔光混合|
| ハードライト合成 | Hard Light Blend Mode |硬光混合|
| 比較(明)合成 | Lighten Blend Mode |变亮混合|
| 比較(暗)合成 | Darken Blend Mode |变暗混合|
| 差の絶対値合成 | Difference Blend Mode |差异混合|
| 除外合成 | Exclusion Blend Mode |排除混合|

图像运算模式中文译法部分参照如下文章：

[Quartz 2D编程指南 （十四） —— 位图图像和图像蒙版（二） - 简书 ](https://www.jianshu.com/p/3e44d805a495)



## 如果对翻译有疑问

后续的翻译会把的日文原文留在注释中，方便有疑问时及时参照；较为确定没有疑问的原文可能会删除。如果对已删除的原文内容仍抱有疑惑，请使用git查看历史记录，即便如此仍没有原文的情况下是初代翻译人员未接入git的情况，需要您自行查找[日文原版](https://github.com/krkrz/krkr2doc)文档进行对比。

## 本文档可能存在的缺陷

1. **错误的翻译**。部分是设计音乐和图像等领域的专业术语了解不够，部分是因为复制后看漏了，没有进行校对。
2. **拼写错误**。校对遗漏。
3. **链接指向无效**。
4. **排版混乱**。可能会出现字没有对齐之类的情况。
5. **不一致的术语**。统一术语后未完全对之前不一致的翻译进行修改。

如发现以上问题，请提交issue或pull request。
