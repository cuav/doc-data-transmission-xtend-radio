# 硬件连接与使用

---

#### 不分接收端与发射端：

CUAV XTEND Radio模块不分接收端和发射端（不分飞机端和地面），模块上面内置了自动切换芯片

当USB插入电脑时，数据自动切换到USB端口

当USB不存在时，数据切换到6P GH1.25端口

#### 出厂已配对：

出厂默认为空速115K，接口速率为57600，点对点广播模式

如需修改配置，请看软件配置指南，一般只需要修改VID即可达到与其他模块隔离不能通讯的效果，如修改其他配置，请熟悉文档后再谨慎修改。

#### 与飞控连接：

PixHack：插入到飞控的radio接口

Pixhawk：插入到飞控的telem1或者telem2 接口

#### 地面站使用：

理论上PIX的地面站都兼容，连接时请选择57600波特率，注意驱动是否安装正确，端口号是否选对

如果使用手机OTG连接，可能距离比较短，因为OTG功率都不够的原因

### xtcu调试及相关配置教程：

[http://doc.cuav.net/tutorial/copter/optional-hardware/radio/usb xbee.html](http://doc.cuav.net/tutorial/copter/optional-hardware/radio/usb xbee.html)
