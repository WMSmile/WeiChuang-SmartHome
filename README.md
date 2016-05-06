# WeiChuang-SmartHome
这个是使用瑞芯微公司的RKPX2作为服务端的一个智能家具控制器软件。适用于其他项目。
使用AsyncSocket通信。
测试方法：可以手机端下载一个tcp通信软件（appstore上搜socket下载），设置其为服务器，然后电脑和手机端共用一个wifi。模拟器打开应用，点击右上角Setting设置ip和端口，连接服务器（ip和端口信息使用tcp通信软件设置为服务器的时候，会显示）。第一次使用的时候，点击登录界面下方的Register now完成一个简单的注册就可以进入。
自己项目要用类似功能时，只要修改一下发送的消息字符，即可。

发送(Sending)：
                     开(ON)          关(OFF)
客厅
        灯光         A               a
        窗帘         D               d
        空调         E               e
        监控         G               g
        电视         H               h
        空调＋       I
        空调－       J

卧室
        灯光         B               b
        窗帘         K               k
        空调         L               l
        监控         M               m
        电视         N               n
        空调＋       O
        空调－       P

浴室
        灯光         C               c
        窗帘         Q               q
        空调         R               r
     热水器          S               s
        电视         T               t
        空调＋       U 
        空调－       V

蜂鸣警报             F               f
阳台灯光             W               w 
走廊灯光             X               x
电饭锅               Y               y

所有灯               Z               z
