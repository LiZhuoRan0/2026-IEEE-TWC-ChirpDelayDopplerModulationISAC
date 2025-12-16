# README

## 1. 工程简介

本工程为一套联合通信–雷达（或车载雷达场景）仿真与目标跟踪的 MATLAB 代码框架。  
主要功能包括：

- 构建系统与场景参数（载频、带宽、阵列结构、目标轨迹等）  
- 生成联合通信/雷达发射波形与回波时域数据  
- 基于二维 FFT 得到距离–多普勒图（RDM），并通过 CFAR 检测目标  
- 估计目标的距离、速度、角度及姿态（方向）  
- 利用卡尔曼滤波（KF）进行多目标跟踪与信息融合  
- 将仿真与跟踪结果保存为 `.mat` 文件，并通过 Plot 目录下脚本进行可视化与性能评估  

## 2. 目录结构概览

```text
.
├── Main_RadarTRx.m                % 雷达接收与跟踪主脚本
├── Main_CommTRx.m                 % 通信接收与跟踪主脚本
├── ParaClass.m                    % 系统与场景参数类
├── TDDataGen.m                    % 雷达/通信时域数据生成函数
├── Function/                      % 核心算法函数库
├── Data/                          % 仿真结果与中间数据
├── Fig/                           % 绘图结果
└── Plot/                          % 性能评估与可视化脚本
    ├── PerformanceEvaluation_Track_Radar.m
    └── PerformanceEvaluation_Track_Comm.m
```
