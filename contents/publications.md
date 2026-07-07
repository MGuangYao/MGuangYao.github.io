### Projects

- #### 2022.09–2024.03&emsp;&emsp;&emsp;&emsp;&emsp;基于姿态估计的乒乓球教学系统（嵌入式AI方向）&emsp;&emsp;&emsp;&emsp;&emsp;负责人 <br>

##### 工作描述：<br>
1. 基于 Raspberry Pi 4B 完成嵌入式 Linux 系统移植与优化，设计多线程数据采集模块，通过 UART 实现传感器数据实时采集，构建 MySQL 时序数据库实现运动数据毫秒级存储，系统响应延迟优化至 <15ms。<br>
2. 部署轻量化姿态识别算法：基于 OpenPose 框架进行模型剪枝与量化，采用 TensorRT 加速实现算法在嵌入式平台部署，通过多进程架构实现视频流处理（1080P@30fps）。<br>
3. 定期汇报项目进展，与团队指导老师保持紧密沟通，确保项目高质量、高效率推进。

- #### 2022.09-2023.05&emsp;&emsp;&emsp;&emsp;&emsp;建筑物安全监测预警系统（嵌入式IOT方向）&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;成员 <br>
##### 工作描述：<br>
1、基于CC2530 ZigBee模组组网，实现节点裂缝监测终端的自组织网络（传输距离≥80m），终端设备待机功耗优化至1.2μA。<br>
2、基于FreeRTOS实现多任务调度，创建图像采集（外接摄像头）、数据上报（MQTT协议）两级任务队列，系统响应延迟≤150ms。<br>
3、采用ESP32 Dev Module作主控板，由WIFI传输至上位机（QT开发）实现裂缝参数可视化（定位精度±2mm）。

### Published

- J. Luo, H. Long, S. Xie, Y. Zhang, H. Ma, and <strong>G. Meng</strong>. Improving Table Tennis Training and Technique Analysis: Accurate Classification of Actions with Informer Encoder.ICCVIT, page 27:1-27:4. ACM, (2023). [[Paper]](https://dl.acm.org/doi/10.1145/3627341.3630366)

