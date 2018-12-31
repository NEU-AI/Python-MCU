board与电脑的连接说明
================

首先，通过USB线将Typeboard与电脑连接，连接成功时板子上的绿灯会在0.5s内亮起，当其熄灭则表示开机启动程序已完成。

.. image:: https://github.com/tian0927/hello-world/raw/master/control.png

连接上后，window系统会将其视作移动磁盘，在本处其名称为PYBFLASH，可以看到仅有92KB的空间。

.. image:: https://github.com/tian0927/hello-world/raw/master/图片2.png


打开之后，其中包含有四个文件：


.. image:: https://github.com/tian0927/hello-world/raw/master/图片3.png


boot.py – 这个脚本执行时TPYBoard开发板启动。它设置了开发板的多个选项参数。 
main.py – 这是包含Python程序的主要脚本。在 boot.py 运行后被执行 
README.txt – 包含开启Python的必要基础信息。 
pybcdc.inf – 这是一个Windows驱动文件，配置串行USB装置
