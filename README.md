# moza_control_chassis
使用moza方向盘实现无线远程控制阿克曼线控底盘

实现功能：
- 远程控制底盘的前进、转向、加速、减速、方向灯、挡位切换
- 实时获取底盘的ROS信息，提供restful风格的API接口，可用于web界面展示
- 开机自启动和一键运行脚本
- 目前使用wifi进行通信、可使用5G模块实现超远程控制（目前使用的是socket通信）

环境要求：

硬件环境：可以使用树莓派或者工控机，需要安装python、cmake、g++、ROS，使用ubuntu系统（推荐18.04）

使用的方向盘如下所示：

![image](https://user-images.githubusercontent.com/48673646/201136286-e5328c64-603a-460c-8f4a-d935cdb8688a.png)


控制底盘如下所示：

![image](https://user-images.githubusercontent.com/48673646/201134747-63f5f8e5-80ff-4feb-87e4-65b99683e2ab.png)
