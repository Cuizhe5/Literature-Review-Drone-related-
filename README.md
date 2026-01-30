# Literature Review

## 相关概念:<br>
1:流量:单位时间内通过某一断面的车辆数,只关心：有没有车通过;通过了几辆。<br>
2:时间占用:在一个时间窗口内，传感器被车辆占据的时间比例。<br>
3.OD矩阵估计:在一个时间段内，有多少出行从起点区域O出发，到终点区域D结束<br>
(1)链路计数观测:在某一时间段内，有多少辆车通过这条链路<br>
(2)静态OD矩阵:在一个给定时间段内，OD不随时间变化<br>
(3)动态OD矩阵:OD随时间变化 <br>


## Y. Englezou, S. Timotheou and C.G. Panayiotou“Enhancing Traffic State Estimation Using UAV-Based Measurements”(2024,ICUAS)
  相较于传统传感器和CAF，通过将高斯过程（GP）模型与贝叶斯框架整合进处理，基于无人机的传感表现出更高的估计精度。覆盖了研究网络的高时空分辨率，且随着网络覆盖比例下降，估计误差不会显著变化<br>
描述TSE在交通监测的地位和作用->说明传统数据来源<br>
传统传感器的作用->缺陷<br>
FCD(浮动车数据)->缺陷(隐私问题)<br>
CAV(联网车)->缺陷(隐私问题)<br>
UAV(无人机)->包含的功能，说明交通管理有很多研究，但交通监测没有->无人机的用处好处<br>
本文贡献->提出方法->目标->与其它对比<br>

## Y. Englezou, S. Timotheou and C.G. Panayiotou“Estimating the Origin-Destination Matrix using link count observations from Unmanned Aerial Vehicles”(2021,ITSC)
利用飞行无人机获得的密度数据，估算在自由流动条件下预先规定时间内的静态外径矩阵。利用无人机收集的测量数据估算OD矩阵性能显著优于固定位置传感器的测量，即使无人机群的每时间步测量次数较少。
无人机飞到一个节点 → 悬停并观测tH秒 → 飞往下一个节点（耗时TU） → 再次悬停观测<br>
OD矩阵重要性->很少观测到->估计<br>
OD矩阵现有的研究用什么->静态矩阵和动态矩阵->研究具体做的是静态矩阵<br>
无人机可以用的地方->无人机作用<br>

