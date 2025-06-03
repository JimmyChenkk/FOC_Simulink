# 三相异步电机的转子磁链定向控制（FOC）仿真（Simulink）  
# Flux Orientation Control (FOC) for Three-Phase Induction Asynchronous Motor (Simulink)

---

## 项目简介 | Project Description

在 Simulink 中实现了 **三相异步电机的转子磁链定向控制（FOC）** 的仿真，使用 **空间矢量脉宽调制（SVPWM）** 控制DC-AC三相逆变桥。  
This project implements the simulation of **Rotor Flux-Oriented Control (FOC)** for a **three-phase induction motor** in Simulink, using **Space Vector Pulse Width Modulation (SVPWM)** to control a DC-AC three-phase inverter bridge.

本项目基于开源仓库 [opsniian/simulink-_IM_FOC](https://github.com/opsniian/simulink-_IM_FOC) 进行修改，特此感谢原作者的贡献。  
This project is modified based on the open-source repository [opsniian/simulink-_IM_FOC](https://github.com/opsniian/simulink-_IM_FOC), with sincere thanks to the original author.

此外，本仓库还包含了对该项目的详细**报告文档**（见仓库内 PDF 文件：FOC.pdf），以帮助更好地理解模型设计与控制策略。  
Additionally, a detailed **project report** is included in this repository (see the PDF file: `FOC.pdf`) to help better understand the model design and control strategy.

内容仅供参考，如有错误欢迎批评指正，谢谢。
For reference only. If there are any errors, constructive criticism is welcome. Thank you.

> **关键词**：FOC、三相异步电机、SVPWM、Simulink、矢量控制、转子磁链定向  
> **Keywords**: FOC, three-phase induction motor, SVPWM, Simulink, vector control, rotor flux orientation

## 软件要求 | Requirements

MATLAB-R2025a
