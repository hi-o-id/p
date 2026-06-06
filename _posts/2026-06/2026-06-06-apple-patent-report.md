---
layout: post
title: "Apple 专利小快报 2026-06-06"
date: 2026-06-06 13:23:09 +0800
categories: Apple
---

**New Patents**: 3  

---


<br/>

### 1. 自校准音频

**Title (EN)**: Self-calibrating audio  
**Pub. No.**: US12647744

**Applicant**: Apple Inc.  
**Inventor**: [Soenke Pelzer](https://patents.google.com/?inventor=Soenke+Pelzer&assignee=Apple&country=US&num=100&sort=new), [David E. Romblom](https://patents.google.com/?inventor=David+E.+Romblom&assignee=Apple&country=US&num=100&sort=new), [Dirk Schroeder](https://patents.google.com/?inventor=Dirk+Schroeder&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 02.06.2026

**Abstract**:  
通过用户环境的模型执行光线追踪模拟。基于捕获用户环境中声音的一个或多个麦克风信号测量环境的衰减率。从光线追踪模拟生成环境的房间脉冲响应。基于环境的衰减率和房间脉冲响应修改环境的模型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480491502_1.jpg)

**Technical Field (技术领域)**:  
音频处理领域，具体涉及空间音频的模拟与校准技术。

**Background (发明背景)**:  
在声学空间中，声音会因反射和吸收而逐渐衰减，这种现象被称为混响。混响在空间音频中起重要作用，但现有技术难以准确模拟用户实际物理空间的声学特性，导致空间音频体验不够真实。

**Summary (发明总览)**:  
本发明通过光线追踪模拟和麦克风信号分析，动态校准音频以匹配用户环境的声学特性。通过测量环境衰减率和生成房间脉冲响应，迭代优化环境模型，从而实现更逼真的空间音频渲染。

**Key Innovation (核心创新)**:  
1. 通过光线追踪模拟生成房间脉冲响应，并结合麦克风信号测量的环境衰减率，实现对用户环境的声学特性建模。
2. 采用迭代优化方法，根据麦克风信号反馈不断调整环境模型的表面吸收系数，以提升模拟精度。
3. 利用视觉和音频信息共同校准环境模型，通过摄像头捕捉用户环境的图像并结合混响感知进行精细调整。
4. 通过调整衰减率和能量，使模拟的房间脉冲响应与用户实际环境相匹配，从而提供更准确的声源距离感知。
5. 实现自动校准功能，无需用户手动干预即可完成音频空间化渲染的优化。
6. 将该技术应用于增强现实或混合现实场景中，可提供更逼真的沉浸式音频体验。
7. 通过准确模拟用户房间的混响特性，解决了现有空间音频渲染中声学特性失真的问题。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480491502)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12647744)**
<br/><br/>

---


<br/>

### 2. 表面纹理检测与仿真

**Title (EN)**: Surface texture detection and emulation  
**Pub. No.**: US12644701

**Applicant**: Apple Inc.  
**Inventor**: [Nicholas C Soldner](https://patents.google.com/?inventor=Nicholas+C+Soldner&assignee=Apple&country=US&num=100&sort=new), [Arthur Y Zhang](https://patents.google.com/?inventor=Arthur+Y+Zhang&assignee=Apple&country=US&num=100&sort=new), [Simon Fortin-Deschenes](https://patents.google.com/?inventor=Simon+Fortin-Deschenes&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 02.06.2026

**Abstract**:  
一种手持设备，包含传感器组件，用于检测和测量表面特征，如粗糙度或纹理。该设备还可以捕获运动数据（例如速度和轨迹）。手持设备还可以包括用于仿真表面特征的组件。该设备可以重建、消除或改变虚拟或真实表面上的曲线或粗糙度。手持设备可以包括传感器组件、仿真组件或两者。例如，该设备可用作扩展现实（XR）系统的配件，或作为独立设备使用。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480488155_1.jpg)

**Technical Field (技术领域)**:  
扩展现实（XR）技术领域，具体涉及表面纹理检测与仿真技术。

**Background (发明背景)**:  
扩展现实（XR）系统结合了计算机生成的信息与现实世界图像或视图，以增强用户的视觉体验。现有技术中已有设备可以收集和传输表面粗糙度或纹理的信息，但通常依赖于昂贵的光学或触觉传感器系统，且难以小型化。此外，虽然通过机器学习辅助的计算机视觉可以估计表面粗糙度，但在局部尺度上可能不够准确。

**Summary (发明总览)**:  
本发明提出了一种手持设备，能够检测和测量表面特征如粗糙度或纹理，并可仿真表面特征。该设备结合了传感器组件和仿真组件，可用于XR系统或作为独立设备使用。其核心思路是通过光学或振动传感器直接测量表面特性，并通过固态触觉组件或线性执行器进行表面特征的重建或调整，从而实现更精确的表面特征感知和再现。

**Key Innovation (核心创新)**:  
1. 采用光学或振动传感器（如力传感器、加速度计、干涉仪、深度传感器和摄像头）实现对表面粗糙度和纹理的精确检测。
2. 通过固态触觉组件和线性执行器组件，能够重建、改变或消除真实表面的粗糙度或曲线。
3. 利用设备运动数据（如轨迹和速度），结合表面特征信息，通过高带宽触觉引擎再现任何表面的触感。
4. 使用高动态线性执行器调整握持位置与表面之间的距离，以模拟平面上的曲线或消除曲线，创造平坦的触感。
5. 结合触觉引擎和高动态线性执行器，实现超出单一触觉引擎范围的表面振幅再现。
6. 集成陀螺仪，实现设备绕长轴旋转的精确控制，用于形状笔刷工具的精细操作，并可根据设备滚动角度改变表面触感。
7. 应用于XR系统时，可提升用户沉浸感，通过更精确的表面特征捕捉和再现增强虚拟与现实交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480488155)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12644701)**
<br/><br/>

---


<br/>

### 3. 可拉伸织物制品

**Title (EN)**: Stretchable fabric items  
**Pub. No.**: US12644209

**Applicant**: Apple Inc.  
**Inventor**: [Camille I Henrot](https://patents.google.com/?inventor=Camille+I+Henrot&assignee=Apple&country=US&num=100&sort=new), [Kristen L Cretella](https://patents.google.com/?inventor=Kristen+L+Cretella&assignee=Apple&country=US&num=100&sort=new), [Jessica J Lu](https://patents.google.com/?inventor=Jessica+J+Lu&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 02.06.2026

**Abstract**:  
腕带等物品可包括针织织物管或其他织物外层，该外层具有形成腕带外表面的第一和第二针织织物部分。针织织物外层可围绕一个内部空腔，该空腔具有一个或多个通道。弹性材料丝可位于这些通道中。弹性材料丝可各自保持在单一通道内，或可在多个通道之间来回编织，同时穿过相邻的弹性材料丝以产生摩擦点。一些弹性材料丝可穿过针织织物管内腔与腕带外表面之间的多个开口来回穿梭。约束点和摩擦点可用于控制腕带的拉伸性，同时减少随时间的延长。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480487614_1.jpg)

**Technical Field (技术领域)**:  
电子设备用织物制品领域，具体涉及可拉伸且具有弹性控制的织物腕带技术。

**Background (发明背景)**:  
传统腕带材料如金属、塑料和织物在佩戴初期舒适，但织物腕带容易随时间延长而拉伸。这种拉伸会导致腕带佩戴不当，影响传感器测量精度并引起用户不适。现有的织物腕带缺乏有效的弹性控制机制。

**Summary (发明总览)**:  
本发明提供了一种具有弹性控制的织物腕带结构，通过在针织织物管内部设置弹性材料丝，并利用约束点和摩擦点来控制拉伸性，从而减少腕带的延长现象。弹性材料丝可以分布在不同通道中，并通过针织织物管上的开口在内外表面间穿梭，以实现更均匀的弹性分布和更稳定的结构。

**Key Innovation (核心创新)**:  
1. 采用针织织物管结构，内部设置多个通道，用于容纳弹性材料丝，实现更灵活的弹性控制。
2. 弹性材料丝可在不同通道间来回编织，并在相邻丝之间产生摩擦点，从而增强弹性控制效果。
3. 通过针织织物管上的开口，弹性材料丝可在内外表面间穿梭，优化弹性分布并提高结构稳定性。
4. 设置约束点，将弹性材料丝固定在针织织物外层，以控制拉伸性并减少随时间的延长。
5. 利用摩擦点控制弹性材料丝的移动，进一步增强对腕带拉伸性的控制。
6. 该设计可应用于电子设备腕带，如智能手表带，提供更持久、舒适的佩戴体验。
7. 通过优化弹性控制机制，本发明可有效减少传感器测量误差，提升设备整体性能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480487614)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12644209)**
<br/><br/>

---



**Total Patents**: 3  
**Last Updated**: 20260606

---

The Patent Scoop Trio
