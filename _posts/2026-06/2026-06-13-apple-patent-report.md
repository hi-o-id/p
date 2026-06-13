---
layout: post
title: "Apple 专利小快报 2026-06-13"
date: 2026-06-13 13:29:40 +0800
categories: Apple
---

**New Patents**: 13  

---


<br/>

### 1. 温度检测

**Title (EN)**: Temperature Detection  
**Pub. No.**: US20260151037

**Applicant**: Apple Inc.  
**Inventor**: [Grant H Mulliken](https://patents.google.com/?inventor=Grant+H+Mulliken&assignee=Apple&country=US&num=100&sort=new), [Cameron A Harder](https://patents.google.com/?inventor=Cameron+A+Harder&assignee=Apple&country=US&num=100&sort=new), [Fletcher R Rothkopf](https://patents.google.com/?inventor=Fletcher+R+Rothkopf&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
用于头戴式设备（HMD）中的生物特征数据测量方法与装置，包括温度测量。热传感器可集成到HMD中，用于收集用户面部表面的热数据。这些热数据可用于例如确定用户的核心体温，或用于生成用户呼吸的估计值。从传感器信号中得到的温度数据和/或呼吸率及其变化可用于生成并向用户呈现生物特征数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480741981_1.jpg)

**Technical Field (技术领域)**:  
头戴式设备技术领域，具体涉及生物特征数据测量，包括温度检测和呼吸检测。

**Background (发明背景)**:  
虚拟现实（VR）和混合现实（MR）系统为用户提供沉浸式体验，但现有技术中呼吸检测主要依赖穿戴式设备或面罩式流量计，这些方法不适合长期使用且难以集成到HMD中。传统接触式传感器如热敏电阻和热电偶，以及昂贵的热成像摄像头，存在集成难度大、成本高或需要持续接触皮肤等问题。

**Summary (发明总览)**:  
本发明提出了一种在头戴式设备中集成温度检测的方法，通过接触式和非接触式热传感器测量用户体温，并可进一步分析呼吸率变化。传感器可安装在HMD的鼻托、光密封组件或其他位置，结合摄像头和加速度计数据，实现对用户生物特征数据的全面监测。该方法无需外部设备，提升了长期使用的舒适性和便捷性。

**Key Innovation (核心创新)**:  
1. 集成接触式和非接触式热传感器（如热敏电阻、热电偶和被动红外传感器）到HMD中，实现体温的精确测量。
2. 在HMD的鼻托、光密封组件等位置安装传感器，确保与用户面部的良好接触和数据采集的稳定性。
3. 利用HMD内置的红外摄像头和可见光摄像头，通过图像分析技术监测用户面部温度变化，辅助呼吸率检测。
4. 结合高带宽加速度计数据，通过运动传感器分析用户鼻部表面的细微运动，进一步提高呼吸率检测的准确性。
5. 支持多传感器数据融合处理，可同时监测体温、呼吸率及其他生物特征数据，提供全面的用户健康反馈。
6. 传感器设计紧凑，易于集成到小型化HMD中，不影响设备的外观和佩戴舒适度。
7. 该技术可应用于VR/MR系统、健康监测设备等场景，为用户提供实时生物特征数据监测和反馈，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480741981)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260151037)**
<br/><br/>

---


<br/>

### 2. 立体浮动窗口元数据

**Title (EN)**: Stereoscopic Floating Window Metadata  
**Pub. No.**: US20260156239

**Applicant**: Apple Inc.  
**Inventor**: [Christopher L. Flick](https://patents.google.com/?inventor=Christopher+L.+Flick&assignee=Apple&country=US&num=100&sort=new), [Timothy K. Dashwood](https://patents.google.com/?inventor=Timothy+K.+Dashwood&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
本发明公开了用于解决立体多媒体内容中"立体窗口违规"问题的技术。立体窗口违规会导致立体效果对观众而言变得"破碎"，例如，当立体内容中的左眼和右眼视图不匹配时可能会发生这种情况。立体不匹配通常出现在左右眼视频图像帧的边缘（例如，一个物体在左眼视图中被截断，但在对应的右眼视图中却没有）。根据本发明公开的技术，不是通过永久性遮罩或其他方式编辑立体视频内容来应对窗口违规，而是为立体视频生成伴随的立体窗口违规元数据信息。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480745085_1.jpg)

**Technical Field (技术领域)**:  
图像处理技术领域，具体涉及立体视频内容中的窗口违规问题及元数据处理技术。

**Background (发明背景)**:  
立体视频内容中的窗口违规问题会导致立体效果受损，例如左右眼视图边缘的物体显示不一致。这种不匹配通常出现在图像帧边缘，可能导致观众产生不适感。现有的解决方案，如"浮动窗口"技术，通过裁剪或遮罩图像边缘来匹配左右视图，但这些方法会永久改变图像源，无法在后期制作或播放时进行调整。

**Summary (发明总览)**:  
本发明提出了一种非破坏性的立体窗口违规解决方案，通过生成立体窗口违规元数据信息来替代对视频内容的永久性编辑。该元数据定义了每个左右眼图像帧对的几何形状，用于消除或减轻窗口违规的影响。在播放时，播放设备可以利用这些元数据实时裁剪或修改视频图像帧，从而在不影响原始视频源的情况下改善立体效果。该技术特别适用于扩展现实（XR）环境中的立体视频内容渲染。

**Key Innovation (核心创新)**:  
1. 提出了一种基于元数据的立体窗口违规解决方案，通过生成包含窗口违规信息的元数据轨道来替代对视频内容的永久性编辑。
2. 定义了立体图像对中每个边缘的偏移值，包括左边缘、右边缘以及四个角边缘的偏移，以消除窗口违规的影响。
3. 提供了分辨率自适应的偏移值处理机制，将标准化偏移值转换为与显示屏幕分辨率相关的具体偏移值，确保在不同设备上的兼容性。
4. 采用关键帧编码和差分编码方案对偏移值信息进行编码，以减少数据量并提高处理效率。
5. 允许播放设备在播放时根据需要选择性地应用或忽略窗口违规元数据，例如在2D播放模式下可以忽略这些信息。
6. 特别适用于XR环境，通过实时裁剪或修改视频图像帧的像素透明度或颜色值来动态处理窗口违规问题。
7. 该技术可应用于VR、AR等XR场景下的立体视频内容渲染，为用户提供更自然、更舒适的立体视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480745085)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260156239)**
<br/><br/>

---


<br/>

### 3. 低带宽和紧急通信用户界面

**Title (EN)**: LOW-BANDWIDTH AND EMERGENCY COMMUNICATION USER INTERFACES  
**Pub. No.**: US20260156444

**Applicant**: Apple Inc.  
**Inventor**: [Guillaume R. ARDAUD](https://patents.google.com/?inventor=Guillaume+R.+ARDAUD&assignee=Apple&country=US&num=100&sort=new), [Julian K. MISSIG](https://patents.google.com/?inventor=Julian+K.+MISSIG&assignee=Apple&country=US&num=100&sort=new), [Matan STAUBER](https://patents.google.com/?inventor=Matan+STAUBER&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
本发明主要涉及低带宽和紧急通信的用户界面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480745311_1.jpg)

**Technical Field (技术领域)**:  
本发明属于计算机用户界面领域，具体涉及低带宽通信和紧急通信技术。

**Background (发明背景)**:  
现有计算机系统虽然能够显示各种通信界面，但低带宽和紧急通信的用户界面通常较为繁琐且效率低下。例如，一些现有技术需要复杂的按键操作或多次按键，导致用户时间和设备能量浪费，这在电池供电设备中尤为重要。本发明旨在提供更快速、高效的低带宽和紧急通信方法及界面。

**Summary (发明总览)**:  
本发明提供了一种改进的低带宽和紧急通信用户界面设计方案。通过检测可用网络类型，系统能够动态调整用户界面的显示方式。当检测到地面无线网络可用时，界面以标准模式显示；当检测到地面无线网络不可用时，界面切换为备用模式，显示，并提示用户可通过其他通信网络发起通信。此外，在紧急通信模式下，系统提供了一种简化的用户界面，允许用户快速发送紧急信息至附近设备，而无需手动选择接收者，从而提高通信效率和用户体验。

**Key Innovation (核心创新)**:  
1. 通过检测地面无线网络的可用性，动态调整用户界面的显示模式，确保用户在不同网络环境下都能快速发起通信。
2. 在地面无线网络不可用时，界面以不同外观显示，并明确提示用户可使用其他通信网络进行通信，提升了用户操作的直观性。
3. 提供了一种简化的紧急通信用户界面，用户无需手动选择接收者，系统根据接收设备的接近程度自动选择目标，提升了紧急情况下的通信效率。
4. 通过减少用户操作步骤和界面复杂度，降低了用户的认知负担，使通信过程更加高效。
5. 针对电池供电设备，优化了界面显示逻辑，减少了不必要的能量消耗，延长了设备的使用时间。
6. 该技术可应用于智能手机、平板电脑等便携式设备，尤其适用于紧急救援、户外探险等场景，为用户提供可靠的通信保障。
7. 通过简化用户界面和优化通信流程，本发明在低带宽和紧急情况下提供了更快速、更可靠的通信解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480745311)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260156444)**
<br/><br/>

---


<br/>

### 4. 使用不同视场摄像头的立体捕捉

**Title (EN)**: Stereoscopic Capture Using Cameras with Different Fields of View  
**Pub. No.**: US20260156236

**Applicant**: Apple Inc.  
**Inventor**: [Guy Rapaport](https://patents.google.com/?inventor=Guy+Rapaport&assignee=Apple&country=US&num=100&sort=new), [Zejing Wang](https://patents.google.com/?inventor=Zejing+Wang&assignee=Apple&country=US&num=100&sort=new), [Vicky Kogan](https://patents.google.com/?inventor=Vicky+Kogan&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
本发明提供了一种电子设备，包括配置有第一视场的第一摄像头用于捕捉第一图像，配置有第二视场的第二摄像头用于捕捉第二图像，以及控制电路，用于基于第一和第二图像输出立体内容。控制电路可包括图像信号处理器，用于处理第一和第二图像；附加处理器，用于对第一和第二图像执行立体校正和图像稳定；以及压缩模块，用于组合附加处理器输出的图像。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480745082_1.jpg)

**Technical Field (技术领域)**:  
电子设备技术领域，具体涉及多摄像头立体成像技术。

**Background (发明背景)**:  
电子设备通常配备一个或多个摄像头用于捕捉场景的图像或视频流。现有的电子设备可能包括广角摄像头、超广角摄像头和长焦摄像头，但这些设备在生成立体内容时存在图像校正、稳定性同步以及视场融合方面的不足。本发明旨在解决这些问题，通过结合不同视场的图像生成高质量的立体内容。

**Summary (发明总览)**:  
本发明提出了一种利用不同视场摄像头生成立体内容的方法和设备。通过广角和超广角摄像头捕捉图像，并结合图像处理、立体校正和图像稳定技术，生成高质量的立体图像或视频流。该方法还包括同步图像稳定信息、计算姿态校正矩阵以及应用多视角视频编码方案，从而实现更精准的立体内容输出。

**Key Innovation (核心创新)**:  
1. 采用广角和超广角摄像头组合捕捉图像，通过不同视场的图像融合生成立体内容，提升立体成像的深度感和广度。
2. 引入图像信号处理器对捕捉的图像进行初步处理，确保图像质量符合立体成像要求。
3. 通过附加处理器执行立体校正和图像稳定操作，解决由于设备移动或抖动导致的图像失真问题。
4. 应用多视角视频编码方案对校正和稳定的图像进行压缩，生成高效的立体视频流。
5. 同步第一和第二摄像头的图像稳定信息，通过旋转矩阵和运动数据计算校正姿态，并使用时间滤波器稳定校正后的姿态。
6. 提供用户通知机制，当设备处于错误捕捉方向、摄像头被遮挡、光线不足或存在外部物体干扰时，及时提醒用户调整设备状态。
7. 本发明可应用于智能手机、虚拟现实设备或增强现实设备，为用户提供更真实、更稳定的立体视觉体验，尤其适用于需要高精度立体成像的场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480745082)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260156236)**
<br/><br/>

---


<br/>

### 5. 用于与三维环境交互的设备、方法和图形用户界面

**Title (EN)**: Devices, Methods, and Graphical User Interfaces for Interacting with Three-Dimensional Environments  
**Pub. No.**: US20260153922

**Applicant**: Apple Inc.  
**Inventor**: [Jonathan R. Dascola](https://patents.google.com/?inventor=Jonathan+R.+Dascola&assignee=Apple&country=US&num=100&sort=new), [Stephen O. Lemay](https://patents.google.com/?inventor=Stephen+O.+Lemay&assignee=Apple&country=US&num=100&sort=new), [Israel Pastrana Vicente](https://patents.google.com/?inventor=Israel+Pastrana+Vicente&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
计算机系统显示三维环境的第一视图。在显示第一视图时，计算机系统检测到指向三维环境中对应于用户手部在物理环境中的位置的第一位置的凝视输入，同时检测到用户手部在物理环境中的移动，该移动满足预设标准。作为响应，计算机系统在三维环境中显示多个用户界面对象，这些对象位于远离对应于用户手部在物理环境中的位置的第一位置的第二位置。当激活时，相应的用户界面对象会在三维环境中启动显示相应的计算机生成体验的过程。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480742516_1.jpg)

**Technical Field (技术领域)**:  
虚拟现实、增强现实和扩展现实技术领域，具体涉及与三维环境交互的计算机系统和用户界面。

**Background (发明背景)**:  
近年来，虚拟现实、增强现实和扩展现实计算机系统的发展显著增加。这些系统通常依赖于输入设备，如摄像头、控制器和触摸屏，以与虚拟元素交互。然而，现有方法在交互效率和用户体验方面存在不足，例如操作复杂、反馈不足以及需要多次输入才能实现目标。这些问题增加了用户的认知负担，并降低了整体体验质量。

**Summary (发明总览)**:  
本发明提供了一种改进的计算机系统和方法，用于与包含虚拟元素的三维环境进行交互。通过检测用户的凝视输入和手部动作，系统能够在三维环境中动态显示和操作用户界面对象。该方法通过减少用户输入的复杂性和数量，并提供直观的反馈机制，简化了与虚拟元素的交互过程，从而提升了用户体验和操作效率。

**Key Innovation (核心创新)**:  
1. 通过检测用户的凝视输入和手部动作，实现对三维环境中用户界面对象的动态显示和操作。
2. 当用户手部动作满足预设手势标准时，系统在三维环境中显示多个用户界面对象，这些对象的位置与用户手部位置相关联。
3. 用户可以通过凝视输入选择三维环境中的用户界面对象，并通过手部动作触发相应的计算机生成体验。
4. 系统支持多组可选择用户界面对象的切换，通过移动和调整视觉显著性来优化用户交互体验。
5. 在三维环境中，用户界面对象和背景内容具有不同的视觉属性，系统根据用户输入动态调整这些属性以突出显示重要内容。
6. 通过减少用户输入的复杂性和数量，并提供直观的反馈机制，简化了与虚拟元素的交互过程。
7. 本发明可应用于虚拟现实、增强现实和扩展现实设备，为用户提供更高效、更直观的交互方式，尤其适用于需要快速操作和反馈响应的场景，如游戏、导航和生产力工具。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480742516)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260153922)**
<br/><br/>

---


<br/>

### 6. 具有可调节特性的触控笔

**Title (EN)**: STYLUS WITH ADJUSTABLE FEATURES  
**Pub. No.**: US20260153946

**Applicant**: Apple Inc.  
**Inventor**: [Jean Hsiang-Chun LU](https://patents.google.com/?inventor=Jean+Hsiang-Chun+LU&assignee=Apple&country=US&num=100&sort=new), [Jacob L. MATLICK](https://patents.google.com/?inventor=Jacob+L.+MATLICK&assignee=Apple&country=US&num=100&sort=new), [Wesley W. ZUBER](https://patents.google.com/?inventor=Wesley+W.+ZUBER&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
一种输入设备，例如触控笔，可以包括调节功能，用于改变触控笔的某一部分（例如笔尖）的尺寸、形状、刚度或其他特性。通过改变触控笔笔尖的尺寸、形状、刚度或其他特性，可以模拟特定书写或绘图工具的特性。例如，可以通过改变触控笔的特性来模拟笔尖的刚度、重量分布和/或特定工具的转动惯量。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480742542_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及可调节特性的触控笔及其触觉反馈技术。

**Background (发明背景)**:  
现有的触控输入设备，如触控笔，通常用于在电子设备的触摸面板上提供输入。然而，这些设备通常无法根据用户需求动态调整其物理特性，例如笔尖的形状、刚度或摩擦力。这导致用户在使用不同工具时无法获得与真实书写或绘图工具相似的体验。本发明旨在解决这一问题，通过提供一种可调节特性的触控笔来模拟不同工具的使用体验。

**Summary (发明总览)**:  
本发明提出了一种具有可调节特性的触控笔，其主要通过改变笔尖的物理特性来模拟不同书写或绘图工具的使用体验。实现方式包括动态调整笔尖的尺寸、形状、刚度、摩擦力等特性，以适应用户在不同场景下的需求。该触控笔能够模拟多种工具的特性，例如钢笔、铅笔、粉笔、马克笔或画笔，从而提供更自然和熟悉的用户体验。相较于传统触控笔，本发明提供了更高的灵活性和适应性，使用户能够根据具体任务调整设备特性。

**Key Innovation (核心创新)**:  
1. 通过可调节的笔尖设计，使用户能够动态改变触控笔的尺寸、形状和刚度，以模拟不同书写或绘图工具的特性。
2. 实现了对笔尖摩擦力的调节，使用户能够根据需要调整书写或绘图时的触感体验。
3. 提供了对触控笔重心和转动惯量的调节功能，以模拟不同工具的物理特性，例如画笔的平衡感。
4. 采用模块化设计，允许用户更换或调整笔尖组件，以适应不同的使用场景和工具模拟需求。
5. 通过电子控制机制，实现对笔尖特性的精确调节，并可与电子设备进行交互以提供更智能的触觉反馈。
6. 应用于电子绘画、书写、选择界面元素等场景，为用户带来更接近真实工具的体验，尤其适合专业设计师和艺术家。
7. 独特价值在于提供了一种高度个性化的输入方式，使用户能够根据个人偏好和任务需求定制触控笔的特性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480742542)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260153946)**
<br/><br/>

---


<br/>

### 7. 基于检测手势触发的输入动作技术

**Title (EN)**: Techniques for Triggering Input Actions from Detected Gestures  
**Pub. No.**: US20260153939

**Applicant**: Apple Inc.  
**Inventor**: [Julian K. Shutzberg](https://patents.google.com/?inventor=Julian+K.+Shutzberg&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
处理手势输入包括基于手部追踪数据检测手势的第一实例，确定第一实例手势未满足输入动作触发条件，并基于附加手部追踪数据检测手势的第二实例。根据确定第二实例手势在第一实例手势的阈值时间内被检测到，基于手势的第二组启发式规则确定第二实例手势是否满足输入动作触发条件。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480742534_1.jpg)

**Technical Field (技术领域)**:  
扩展现实（XR）技术领域，具体涉及手势识别和输入动作触发技术。

**Background (发明背景)**:  
扩展现实（XR）系统允许用户通过手势与虚拟对象或环境交互。然而，现有技术在手势追踪和识别过程中容易因误判导致用户输入被意外拒绝，例如在间接选择操作中可能因视线或手势的细微偏差导致失败。这影响了用户体验和交互效率。

**Summary (发明总览)**:  
本发明提出了一种改进的手势识别技术，通过对手势的重复尝试进行优化处理来减少误拒绝。具体方法包括在检测到用户重复手势时，放宽触发条件，例如扩大目标区域或调整手势检测参数，以提高识别成功率。该方法适用于XR环境中的用户界面交互场景。

**Key Innovation (核心创新)**:  
1. 通过检测手势的重复实例并应用不同的启发式规则来优化手势识别过程。
2. 在检测到重复手势时，放宽触发条件，例如扩大目标区域或调整检测参数，以提高识别成功率。
3. 结合手部追踪数据和其他上下文信息（如视线方向、用户界面元素位置）来增强手势识别的准确性。
4. 在用户首次尝试失败后，系统自动调整后续手势识别的判定标准，以减少误拒绝。
5. 通过调整间接选择操作中的视线和手势组合判定逻辑，提升复杂交互场景下的操作可靠性。
6. 该技术可应用于XR系统中的用户界面交互，例如虚拟对象选择、菜单导航等场景。
7. 通过减少误拒绝次数，提升用户在XR环境中的交互体验和操作效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480742534)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260153939)**
<br/><br/>

---


<br/>

### 8. 用于提供环境跟踪内容的设备、方法和图形用户界面

**Title (EN)**: DEVICES, METHODS, AND GRAPHICAL USER INTERFACES FOR PROVIDING ENVIRONMENT TRACKING CONTENT  
**Pub. No.**: US20260154168

**Applicant**: Apple Inc.  
**Inventor**: [Karen EL ASMAR](https://patents.google.com/?inventor=Karen+EL+ASMAR&assignee=Apple&country=US&num=100&sort=new), [Christopher D. MCKENZIE](https://patents.google.com/?inventor=Christopher+D.+MCKENZIE&assignee=Apple&country=US&num=100&sort=new), [Kaely COON](https://patents.google.com/?inventor=Kaely+COON&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
本公开涉及用于提供利用环境跟踪（例如，物理环境的环境跟踪）的内容的设备、方法和图形用户界面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480742788_1.jpg)

**Technical Field (技术领域)**:  
计算机系统技术领域，具体涉及增强现实和混合现实体验中的环境跟踪内容显示。

**Background (发明背景)**:  
近年来，增强现实计算机系统的发展显著增加。现有增强现实环境通常包含一些虚拟元素，用于替代或增强现实世界。然而，现有系统在与虚拟对象交互时提供的反馈不足，需要多次输入才能实现目标，且虚拟对象操作复杂、繁琐且易出错。这些问题增加了用户的认知负担，降低了虚拟/增强现实体验的质量。此外，这些方法耗时较长，导致计算机系统能量浪费，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种改进的计算机系统方法及界面，用于提供利用三维环境跟踪的内容。通过优化用户输入与设备响应之间的连接，本发明减少了用户输入的数量、范围和复杂性，从而创建了更高效的人机交互界面。该方法通过在检测到用户输入时逐步增强控制界面的视觉显著性来提供反馈，使用户能够更轻松准确地与系统交互，同时减少对用户注意力的干扰。

**Key Innovation (核心创新)**:  
1. 通过检测用户视线和手势来触发媒体播放控制界面的显示，并逐步增强其视觉显著性，以减少对用户注意力的干扰。
2. 在检测到与计算机系统运动相关的环境跟踪错误时，提供一个可选择的选项，允许用户在错误持续的情况下重新显示内容。
3. 通过减少用户输入的次数和复杂性，优化了人机交互效率，例如通过初始显示低显著性控制界面，随后根据用户进一步操作增强其显著性。
4. 实现了在环境跟踪错误条件下动态调整显示内容的功能，确保用户在错误持续时仍能选择性地访问内容。
5. 提供了更直观的用户界面反馈机制，使用户能够更清晰地理解输入与系统响应之间的关系。
6. 适用于便携式和可穿戴设备，通过优化环境跟踪错误处理机制，延长了电池供电设备的使用时间。
7. 可应用于增强现实、混合现实和虚拟现实场景，为用户提供更流畅、更可靠的内容交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480742788)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260154168)**
<br/><br/>

---


<br/>

### 9. 输入设备

**Title (EN)**: INPUT DEVICE  
**Pub. No.**: US20260153944

**Applicant**: Apple Inc.  
**Inventor**: [Megan M. Sapp](https://patents.google.com/?inventor=Megan+M.+Sapp&assignee=Apple&country=US&num=100&sort=new), [Brian T. Gleeson](https://patents.google.com/?inventor=Brian+T.+Gleeson&assignee=Apple&country=US&num=100&sort=new), [Steven J. Taylor](https://patents.google.com/?inventor=Steven+J.+Taylor&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
一种计算机系统包括一个输入设备，该输入设备具有一个界定内部空间的壳体。壳体包括握持部分和界定一个孔口的基座部分。计算机系统还包括位于内部空间的倾斜传感器、位于孔口的位置传感器以及处理器。处理器与位置传感器、倾斜传感器以及存储电子指令的存储组件电连接。当处理器执行这些指令时，会接收来自倾斜传感器的第一输入，接收来自位置传感器的第二输入，并根据第一和第二输入确定基座是否与支撑表面接触以及基座相对于支撑表面的角度。如果基座与支撑表面接触，处理器还会基于角度输出信号。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480742540_1.jpg)

**Technical Field (技术领域)**:  
计算机输入系统，具体涉及具有倾斜和位置传感功能的输入设备。

**Background (发明背景)**:  
传统计算机输入设备如鼠标和触控板主要依赖机械按钮和二维运动跟踪来与用户交互。这些设备在输入手势种类和数量上存在限制，难以满足日益复杂的软件应用需求，例如在视频编辑或三维设计中的高效操作。现有输入设备难以提供直观且多样化的输入方式，影响了用户对复杂功能的控制效率。

**Summary (发明总览)**:  
本发明提出了一种新型输入设备，通过集成倾斜传感器和位置传感器，扩展了用户输入选项。该设备能够检测其在支撑表面上的倾斜角度和接触状态，并根据这些信息向计算机发送独特的命令信号。用户可以通过倾斜或旋转设备来执行各种功能，如菜单滚动、图像缩放和三维对象控制等。这种设计提供了更直观和多样化的输入方式，提升了用户对复杂软件应用的控制效率。

**Key Innovation (核心创新)**:  
1. 集成了倾斜传感器（如惯性测量单元）和位置传感器（如光学传感器），实现了对设备倾斜角度和位置的同时检测。
2. 通过基座上的孔口设计，光学传感器能够有效发送和接收光线，从而实现精确的位置跟踪。
3. 倾斜表面设计引导用户实现预设的倾斜角度，对应特定的计算功能，增强了用户输入的准确性和直观性。
4. 处理器根据倾斜和位置输入确定设备是否与支撑表面接触，并基于倾斜角度输出相应的控制信号。
5. 设备支持检测完全离开支撑表面的状态，并相应输出不同的信号，以实现更丰富的交互方式。
6. 握持部分设计为曲线形状，基座和握持部分可一体成型，提升了设备的握持舒适性和结构稳定性。
7. 该输入设备可应用于三维设计软件、视频编辑软件等复杂应用场景，为用户提供更高效和直观的控制方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480742540)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260153944)**
<br/><br/>

---


<br/>

### 10. 增强型模拟视觉

**Title (EN)**: ENHANCED SIMULATED VISION  
**Pub. No.**: US20260154024

**Applicant**: Apple Inc.  
**Inventor**: [Thomas G. SALTER](https://patents.google.com/?inventor=Thomas+G.+SALTER&assignee=Apple&country=US&num=100&sort=new), [Christopher I. WORD](https://patents.google.com/?inventor=Christopher+I.+WORD&assignee=Apple&country=US&num=100&sort=new), [Jeffrey S. NORRIS](https://patents.google.com/?inventor=Jeffrey+S.+NORRIS&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
本发明涉及用于选择性地显示电子设备的物理环境部分图像并增强其可见性的系统和方法。在一些示例中，图像被叠加显示在物理环境的视图部分上。在一些示例中，电子设备在满足一个或多个第一条件时显示图像，在条件不满足时则不显示图像。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480742629_1.jpg)

**Technical Field (技术领域)**:  
扩展现实技术领域，具体涉及增强现实环境中的物理环境图像显示技术。

**Background (发明背景)**:  
现有的计算机图形环境提供二维或三维虚拟对象显示，但这些对象通常由计算机生成。部分系统基于物理环境的图像构建虚拟环境，但在低光照条件下，用户难以清晰观察物理环境。现有技术缺乏在低光照条件下增强物理环境可视性的有效解决方案。

**Summary (发明总览)**:  
本发明提出了一种在扩展现实环境中增强物理环境可视性的方法。电子设备在检测到特定条件（如低光照、用户输入或环境上下文数据）时，会以增强亮度的方式显示物理环境的图像或视频。这使得用户能够在低光照条件下更清晰地观察周围环境。该方法结合了虚拟显示和光学透视技术，通过动态调整显示参数来适应不同的使用场景。

**Key Innovation (核心创新)**:  
1. 通过检测环境亮度低于预设阈值，触发增强显示模式，使用户在低光照条件下能够更清晰地观察物理环境。
2. 结合虚拟或视频透视技术，电子设备利用显示屏呈现物理环境的增强图像或视频。
3. 支持用户输入触发增强显示，提供更灵活的交互方式。
4. 基于环境上下文数据（如时间、地点）自动调整显示参数，优化显示效果。
5. 在三维环境中，虚拟对象可采用世界锁定、头部锁定、身体锁定或倾斜锁定等多种定位方式，适应不同使用场景。
6. 倾斜锁定对象根据用户头部运动在三维空间中动态调整位置，保持与用户的相对距离和三维环境中的固定方向。
7. 本技术可应用于增强现实眼镜、头盔显示器等设备，在低光照环境中提供更清晰的视觉体验，尤其适用于户外、夜间或暗光条件下的导航和操作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480742629)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260154024)**
<br/><br/>

---


<br/>

### 11. 在环境中呈现与产品相关的虚拟元素

**Title (EN)**: PRESENTING VIRTUAL ELEMENTS ASSOCIATED WITH A PRODUCT IN AN ENVIRONMENT  
**Pub. No.**: US20260154919

**Applicant**: Apple Inc.  
**Inventor**: [Thomas G. SALTER](https://patents.google.com/?inventor=Thomas+G.+SALTER&assignee=Apple&country=US&num=100&sort=new), [Jeffrey S. NORRIS](https://patents.google.com/?inventor=Jeffrey+S.+NORRIS&assignee=Apple&country=US&num=100&sort=new), [Christopher I. WORD](https://patents.google.com/?inventor=Christopher+I.+WORD&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
本发明涉及用于在检测到物理环境中的产品时执行一个或多个操作的系统和方法的实施例。例如，执行一个或多个操作包括在环境中呈现一个或多个虚拟元素。此外，执行一个或多个操作还包括存储与产品相关的信息。在某些实施例中，一个或多个操作在满足一个或多个条件时执行。例如，当检测到用户对产品的兴趣的一个或多个指示时，满足一个条件。在某些实施例中，在环境中呈现一个或多个虚拟元素以指示产品在物理环境中的位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480743621_1.jpg)

**Technical Field (技术领域)**:  
增强现实技术领域，具体涉及通过虚拟元素与物理环境中的产品进行交互。

**Background (发明背景)**:  
现有的计算机图形环境提供二维和/或三维环境，其中用户看到的一些对象是虚拟的并由计算机生成。然而，现有技术通常无法有效地将虚拟元素与物理环境中的产品关联起来，导致用户难以获取与产品相关的实时信息或进行交互。本发明旨在解决这一问题，通过在检测到用户对产品的兴趣时，动态呈现与产品相关的虚拟元素。

**Summary (发明总览)**:  
本发明提出了一种在物理环境中检测产品并执行相关操作的方法。核心思路是当电子设备检测到用户对产品的兴趣时，通过一个或多个虚拟元素呈现与产品相关的信息，例如产品的购买地点或添加到购物清单的功能。实现路径包括通过输入设备检测用户对产品的兴趣信号，如注意力、手势或交互行为，并基于这些信号触发虚拟元素的呈现。本发明相较于现有技术的主要改进在于将虚拟元素与物理环境中的产品动态关联，提升了用户获取产品信息的便捷性和交互体验。

**Key Innovation (核心创新)**:  
1. 通过输入设备检测用户对物理环境中产品的兴趣信号，包括用户的注意力、手势或交互行为，从而触发虚拟元素的呈现。
2. 在环境中呈现与产品相关的虚拟元素，例如显示产品可购买的位置或区域，为用户提供直观的购买指引。
3. 将与产品相关的信息添加到应用程序的信息库中，例如将产品添加到购物清单中，实现便捷的产品管理。
4. 电子设备能够检测自身在物理环境中的位置，并根据位置判断是否在特定区域内呈现与产品相关的虚拟元素，例如在商店内显示产品的具体位置。
5. 支持多种虚拟元素呈现方式，包括基于用户意图的动态更新，例如当用户对产品表现出兴趣时，实时更新虚拟元素的内容。
6. 虚拟元素可以以不同的锁定方式呈现，例如世界锁定、头部锁定或身体锁定，以适应用户的移动和视角变化。
7. 本发明可应用于增强现实购物应用，通过虚拟元素引导用户购买产品，提升购物体验并简化购买流程。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480743621)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260154919)**
<br/><br/>

---


<br/>

### 12. 电子设备的跨平台显示内容共享

**Title (EN)**: CROSS-PLATFORM SHARING OF DISPLAYED CONTENT FOR ELECTRONIC DEVICES  
**Pub. No.**: US20260154030

**Applicant**: Apple Inc.  
**Inventor**: [Olivier PINON](https://patents.google.com/?inventor=Olivier+PINON&assignee=Apple&country=US&num=100&sort=new), [Afshin TAGHAVI NASRABADI](https://patents.google.com/?inventor=Afshin+TAGHAVI+NASRABADI&assignee=Apple&country=US&num=100&sort=new), [Maneli NOORKAMI](https://patents.google.com/?inventor=Maneli+NOORKAMI&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
本发明提供了一种跨平台显示内容共享的方法。在一个或多个实现中，跨平台显示内容共享包括：在第一设备的第一个显示器上显示显示内容的第一渲染，并在接收到捕获和/或共享显示内容的请求时，生成显示内容的第二渲染，第二渲染与第一渲染不同。第二渲染的生成方式使得，当第二渲染在具有不同外形尺寸和/或显示技术的第二设备的第二个显示器上显示时，所显示的第二渲染能够准确代表第一设备用户对第一渲染的感知视图。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480742635_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及电子设备领域，具体为跨平台显示内容共享技术。

**Background (发明背景)**:  
电子设备通常使用显示像素阵列来显示内容。一些设备能够记录特定时间或时间段内的显示像素值，这些记录值可以存储或作为屏幕截图或屏幕共享图像/视频共享。然而，现有技术中记录的像素值只能在具有相同外形尺寸和显示技术的设备上准确再现。如果在其他设备上显示，可能会出现失真或难以理解的情况。本发明旨在解决在不同外形尺寸和显示技术的设备之间准确共享显示内容的问题。

**Summary (发明总览)**:  
本发明提出了一种跨平台显示内容共享方法，通过在显示第一渲染的同时生成第二渲染来实现内容共享。第二渲染经过特殊处理，使其能够在具有不同外形尺寸和显示技术的设备上准确再现用户的第一视角体验。该方法适用于从三维扩展现实（XR）环境到二维显示设备的跨平台内容共享，解决了现有技术中在不同设备上显示内容失真的问题。

**Key Innovation (核心创新)**:  
1. 在显示第一渲染的同时生成第二渲染，第二渲染经过特殊处理以适应不同外形尺寸和显示技术的设备。
2. 通过调整显示内容的渲染方式，例如变形、色彩映射、视角校正等，确保在不同设备上显示时能够准确再现原始视角。
3. 支持从三维XR环境到二维显示设备的跨平台内容共享，例如从XR头戴设备到智能手机或电视的共享。
4. 利用图像处理算法和显示技术优化，确保在不同设备上显示的内容具有可读性和视觉一致性。
5. 提供用户友好的界面，允许用户选择共享的内容范围和目标设备类型。
6. 适用于多种电子设备，包括智能手机、平板电脑、笔记本电脑、XR头戴设备等。
7. 独特价值在于实现跨平台的无缝内容共享，提升用户体验，特别是在需要从高端XR设备向普通显示设备共享内容时。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480742635)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260154030)**
<br/><br/>

---


<br/>

### 13. 基于手势激活可操作项

**Title (EN)**: Hand-Gesture Activation of Actionable Items  
**Pub. No.**: US20260153937

**Applicant**: Apple Inc.  
**Inventor**: [Brett D. Miller](https://patents.google.com/?inventor=Brett+D.+Miller&assignee=Apple&country=US&num=100&sort=new), [Daniel K. Boothe](https://patents.google.com/?inventor=Daniel+K.+Boothe&assignee=Apple&country=US&num=100&sort=new), [Martin E. Johnson](https://patents.google.com/?inventor=Martin+E.+Johnson&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 04.06.2026

**Abstract**:  
本发明描述了一种在包含图像传感器、处理器和非易失性存储器的设备上执行操作的方法。该方法包括接收来自图像传感器的物理环境图像，检测图像中的选择手势以选择特定的可操作项，该可操作项与某个操作相关联，并在检测到选择手势后执行与该可操作项相关的操作，而无需显示包含可选择控制元素的用户界面元素。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-06/US480742532_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及基于手势识别执行操作。

**Background (发明背景)**:  
现有技术中，设备通常通过显示与可操作项关联的提示（如光点）来执行操作，用户需与提示交互才能触发操作。然而，对于没有显示器的设备，这种方法不可行。现有技术无法有效支持无显示设备直接通过手势与可操作项交互。

**Summary (发明总览)**:  
本发明提出了一种无需显示提示即可通过手势直接与物理环境中的可操作项交互的方法。设备通过图像传感器捕捉环境图像，识别可操作项和用户手势。当检测到特定手势时，设备直接执行与目标可操作项相关的操作，无需显示任何用户界面元素。这种方法扩展了无显示设备的交互能力，并提升了操作的直观性和便捷性。

**Key Innovation (核心创新)**:  
1. 通过图像传感器捕捉物理环境图像，识别环境中的可操作项及其关联操作。
2. 采用手势识别技术检测用户选择特定可操作项的手势，无需依赖显示提示。
3. 在检测到手势后，直接执行与目标可操作项相关的操作，无需显示任何用户界面元素。
4. 结合手势和语音命令，进一步增强交互的灵活性和准确性。
5. 适用于无显示设备，使这些设备能够通过自然手势与物理环境中的对象进行交互。
6. 通过减少对显示界面的依赖，降低设备成本和复杂性，同时提升用户体验。
7. 可应用于智能家居、虚拟现实和增强现实等领域，提供更直观和自然的交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US480742532)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260153937)**
<br/><br/>

---



**Total Patents**: 13  
**Last Updated**: 20260613

---

The Patent Scoop Trio
