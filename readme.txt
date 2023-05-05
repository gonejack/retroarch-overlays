来自：https://github.com/gnatydnac/Overlays-For-Retroarch-vita

0:将Data目录复制到Vita根目录。
0:First of all, you need to copy "Data" folder to Vita.
--------------------------------------------------------------

1:GB、GBC、GBA通用视频设定：
1:Global Settings for GB, GBC & GBA:

设置 (Settings)
-视频 (Video)
--硬件双线性过滤 (Bilinear Filtering) > 关 (off)
--缩放 (Scaling)
----放大整数倍 (Integer Scale) > 开 (On)
----宽高比选项 (Aspect Ratio) > Core Provided
--------------------------------------------------------------

2:Gambatte相关设定(GB、GBC)
2:settings for Gambatte
主菜单 (Main Menu)
-快捷菜单 (Quick Menu)
--核心选项 (Options)
----GB上色方式 (GB Colorization) > 内置 (Internal)
----内置色板 (Internal Palette) > 选择与"覆层名"对应的选项 (choose the corresponding one)
----色彩校正 (Color Correction) > 
若覆层名后带有"ColorCorrection"，选"Always"。硬件模式为GBC时选"Always"，配合前光位置设定可以得到较为还原的GBC色彩。
(choose "always" if"ColorCorrection" exist in filename. When Hardware Mode sets to GBC, it provides a color range like real console)
----色彩校正模式 (Color Correction Mode) > 精确 (Accurate)
----硬件模拟 (Emulated Hardware) > 
使用Pal目录下的覆层选GB，其他选GBC或GBA均可
 (choose GB if you use an overlay below the path "Pal")

*PS:使用Pal目录下的覆层，配合对应设定可以达到较为乐观的仿真效果，只是需要花点时间去设置。
*PS:When using an overlay in "Pal", it will take you time to set or change, but provides the best effect on Vita.
------------------------------------------------------------------

3:FCeumm相关设定 (FC)
3:settings for FCeumm
设置 (Settings)
-视频 (Video)
--硬件双线性过滤 (Bilinear Filtering) > 关(off)
--缩放 (Scaling)
----放大整数倍 (Integer Scale) > Off (对应 FullScreen) / On (对应 CoreProvide)
----宽高比选项 (Aspect Ratio) > Core Provided

主菜单 (Main Menu)
-快捷菜单 (Quick Menu)
--核心选项 (Options)
----宽高比选项 (Aspect Ratio) > 4:3
------------------------------------------------------------------

4:通用和其他覆层：自行研究
4:Universal&Other overlays: try it yourself
------------------------------------------------------------------

5:设定完记得在核心选项中保存一下核心配置。
5:Save core override after you have done everything.
------------------------------------------------------------------
Now Enjoy It!
