


Lidar
--------------

robosense-16
~~~~~~~~~~~~~~~~~~~~~~
在\ ``../ws_livox``\ 下打开终端，编译：

::
   
   $ catkin_make

网络配置:

::
   
   $ sudo ifconfig eno1 192.168.1.102 netmask 255.255.255.0
   $ sudo arp-scan -I wlp4s0 --localnet


tx2状态查看工具jetson-stats：
::

   $ sudo apt-get install python3-pip
   $ sudo -H pip3 install -U jetson-stats
   $ sudo jtop



Livox
~~~~~~~~~~~~~~~~~~~~~~
大疆产品

`Avia <https://www.livoxtech.com/cn/avia>`_







