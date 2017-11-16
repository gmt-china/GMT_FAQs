## 尚未整理

gsview可以查看中文，ps2raster报错
最后一行多了-K

---

gsview 可以查看中文，ps2raster 不报错，不显示中文
ps2raster 或者说 psconvert 本质上是调用了 ghostscript 来实现图片格式转换，-C 的作用是将额外的参数传递给 ghostscript，-sFONTPATH=xxx这个实际上是 ghostscript 的参数。但是我们为了中文支持如果已经写了一个环境变量 `GS_FONTPATH` 为C:\Windows\Fonts了，是不是应该全局生效，这个传参就不需要了？

---

特殊符号，如角标，百分号等的表示

---

经纬度表示为度°分′秒″或表示为ddd.x°/在GMT绘图时，如何在经纬度轴上添加上N,E的标注

---

如何地图色填图
分段数据前 > -G<color>

---

请问GMT可以在画站点的同时把站点名也标注上吗？

---

surface插值后的黑色区域如何处理？

---

makecpt的-D强制把超过范围的值设为最大，最小值

---

如何控制边框的线条的粗细

---
grdimage出现密集格网
xyz2grd的格网间距选错了

---

如何在JX投影下表示地理坐标

---

如何去掉某一方向上的刻度线，只保留边框？
两遍psbasemap

---

关于缺少数据的问答栏。比如国界、省界、海岸线、国内城市坐标这一类。

---

GMT的输入数据有什么格式要求/画线首尾相连了
分段数据用>隔开

---

如何提取自己数据的某一列/某一行/计算行数

awk

---

如何提取多边形内/缓冲区内的数据
gmtselect

---

从Linux到windows的txt脚本文件中文乱码
改文件编码格式为ANSI/GB2312

---

awk里怎么能把数据按照科学计数法的格式输出，而不是按纯数值。
AWK printf


32位XP系统下GMT的安装

---
GMT Fatal Error: No SI/US keyword in GMT configuration file <COLOR_BACKGROUND = black>

---

Option -M is deprecated

---

Z-slice with dz=0

---

grdimage: Intensity file has improper dimensions! /重采样时格网个数差1行1列

---

ps2raster -A -P earth.ps
earth.ps: GMT PS format detected but file is not finalized. Maybe a -K in excess? No output created."

---

mismatch between actual (2) and expected (3) fields near line 3811
