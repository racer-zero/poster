# Poster Draft

## Task Overview

* 为一辆汽车部署了端到端的自动驾驶系统,从感知, 模型到控制系统.
* Our task is to deploy an end-to-end automatic driving system, including perception, model inference and control modules.

  

## Contribution

- 强化学习算法 Design a reinforcement learning algorithm with PPO
- 雷达感知融合算法 LIDAR perception data fusion algorithm
- 模型整合与接口部署 Model integration & interface deployment

## Approach

* 硬件设备 + Ray
  - 我們使用了8 台高性能服务器,各有2块2080Ti显卡
  - 高性能分布式强化学习训练平台
* Unity + LSTMPPO
  * imulator
* 三雷达融合(3D激光雷达数据融合和环境感知) 
  * data fusion and environmental perception based on 3 LIDAR
  * 雷达近处有盲区
* CAN接口

## Experiment Results



## Conclusion



## 图

* 车
* 雷达
* PPO
* LIDAR
* 模拟器