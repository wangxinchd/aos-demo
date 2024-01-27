# aos-demo
该仓库用于仿真器对外呈现的damo记录。aos地址: https://github.com/wangxinchd/aos

# openDrive 可视化工具效果
下面测试地图中，左侧是采用 odrViewer64.1.9.1【官方的openDrive可视化工具】解析的效果，右侧是aos内部算法解析的效果
## 地图1：crest-curve.xodr
![image](https://github.com/wangxinchd/aos-demo/assets/49182176/4dd79be5-61d5-4de8-a4aa-c41ccdf05bac)
## 地图2：curves_elevation.xodr
![image](https://github.com/wangxinchd/aos-demo/assets/49182176/39c0fd35-ac76-4140-a384-d82f7ae2d551)


# 案例说明
下述案例采用的是aos仿真工具进行模拟的，其中绿色的车统一可以认为是主车，黑色的车为障碍物车。
## 案例1: cut-in 场景
案例文件：demo001-cut-in交互视频.mp4
案例说明：在双向单车道，后方有高速来车[黑色]接逆向车道 cut-in 主车[绿色].

[![cut-in_demo]()](https://github.com/wangxinchd/aos-demo/assets/49182176/94830406-2209-4586-a222-1b329c384c8d)

# openScenario 编辑器案例说明
下述案例采用的是 我自己开发的openScenario 编辑器，构建的xosc场景，目前只简单的完成了对于主车的添加，产生的场景，可以采用aos仿真工具进行解析，确定主车的行为。
## 案例1: openScenario 编辑器编辑主车
案例说明：在双向单车道，添加了主车，初始化位置为(10, -1.5), 车速为10。位置采用的是绝对位置，速度采用的是绝对速度
[![ego forward]()](https://github.com/wangxinchd/aos-demo/assets/49182176/6da15611-94ed-49ab-b510-0a90b922050c）




