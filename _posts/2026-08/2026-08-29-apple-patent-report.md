---
layout: post
title: "Apple 专利小快报 2026-08-29"
date: 2026-08-29 23:25:04 +0800
categories: Apple
---

**New Patents**: 37  

---


<br/>

### 1. 二维背光操作系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR TWO-DIMENSIONAL BACKLIGHT OPERATION  
**Pub. No.**: US20260253561

**Applicant**: Apple Inc.  
**Inventor**: [Mahesh B. Chappalli](https://patents.google.com/?inventor=Mahesh+B.+Chappalli&assignee=Apple&country=US&num=100&sort=new), [Assaf Menachem](https://patents.google.com/?inventor=Assaf+Menachem&assignee=Apple&country=US&num=100&sort=new), [Daniel Yechiel Dar](https://patents.google.com/?inventor=Daniel+Yechiel+Dar&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种电子显示设备包括与发光二极管（LED）背光协同工作的面板。该设备根据LED的目标亮度值、当前亮度值以及LED的温度，对LED的亮度变化进行"斜坡化"或逐渐过渡。该设备还可以基于当前LED行估计的功耗和其他LED行的功耗来限制背光的功率。该设备还可以根据提供给LED的电流来确定减少的电压，以使LED工作。该设备还可以向背光发送中断，以在向面板像素写入图像内容时阻止对背光的更新。该设备还补偿了LED的老化和温度变化。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571350_1.jpg)

**Technical Field (技术领域)**:  
电子显示技术领域，具体涉及二维LED背光亮度调节和功耗管理。

**Background (发明背景)**:  
电子显示设备通常使用液晶显示（LCD）面板和背光系统来显示图像。传统背光可能因亮度变化剧烈而导致显示出现可见的伪影。此外，背光功耗会因显示内容而变化，过度功耗可能导致电压下降，影响显示性能。现有技术中，LED背光的老化和温度变化也会影响显示质量，尤其是在二维背光中。

**Summary (发明总览)**:  
本发明提出了一种改进的二维LED背光操作方法，通过对LED亮度变化进行斜坡化处理，避免亮度突变导致的显示伪影。同时，系统根据当前行和其他行的功耗动态调整背光功率，防止电压下降。此外，通过优化LED工作电压和同步更新背光与LCD面板刷新，本发明提高了显示质量并降低了功耗。系统还通过补偿LED的老化和温度变化，延长了显示器的使用寿命并减少了烧屏现象。

**Key Innovation (核心创新)**:  
1. 通过斜坡化处理LED亮度变化，根据当前亮度值、目标亮度值和LED温度进行亮度过渡，避免亮度突变导致的显示伪影。
2. 基于当前行LED的估计功耗和其他行LED的功耗，动态调整背光功率，防止因总功耗过高导致的电压下降。
3. 根据提供给LED的电流确定最小工作电压，节省功耗并确保LED正常工作。
4. 通过中断机制同步更新背光与LCD面板刷新，避免在写入图像内容时更新背光，减少显示闪烁和伪影。
5. 补偿LED的老化和温度变化，通过周期性调整补偿因子，延长LED寿命并减少烧屏现象。
6. 应用于高分辨率显示器和需要精确亮度控制的场景，如电视、电脑显示器和移动设备显示屏。
7. 独特价值在于提高显示质量、降低功耗并延长设备使用寿命，特别适用于对显示效果和能耗有高要求的应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571350)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253561)**
<br/><br/>

---


<br/>

### 2. 用于实时面部动画的在线建模方法

**Title (EN)**: Online Modeling for Real-Time Facial Animation  
**Pub. No.**: US20260253301

**Applicant**: Apple Inc.  
**Inventor**: [SOFIEN BOUAZIZ](https://patents.google.com/?inventor=SOFIEN+BOUAZIZ&assignee=Apple&country=US&num=100&sort=new), [MARK PAULY](https://patents.google.com/?inventor=MARK+PAULY&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明涉及一种用于实时面部动画的方法以及用于实时面部动画的处理设备。该方法包括提供动态表情模型、接收对应于用户面部表情的跟踪数据、根据动态表情模型和跟踪数据估计跟踪参数，以及基于跟踪数据和估计的跟踪参数对动态表情模型进行优化。该方法还可以包括基于跟踪参数生成对应于用户面部表情的图形表示。本发明涉及一个实时面部动画系统。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571062_1.jpg)

**Technical Field (技术领域)**:  
计算机图形学，实时动画技术，面部表情捕捉与建模

**Background (发明背景)**:  
实时面部动画技术在虚拟现实、游戏、社交网络等领域具有广泛应用前景。然而，现有技术依赖于复杂的硬件设置或需要大量用户校准，难以在消费级应用中推广。此外，基于视频的面部跟踪方法通常缺乏精细细节，且在复杂光照条件下性能下降。

**Summary (发明总览)**:  
本发明提出了一种无需用户特定训练或校准的实时面部动画方法，通过动态表情模型实现面部表情的在线建模与优化。该方法利用混合形状模型跟踪用户面部表情，并实时更新模型参数以匹配用户的面部特征，从而实现高质量的实时面部动画。

**Key Innovation (核心创新)**:  
1. 采用动态表情模型，包括多个混合形状（blendshapes），通过估计混合形状权重实现面部表情的精确跟踪。
2. 引入在线建模方法，实时接收跟踪数据并优化动态表情模型，无需预先训练或用户特定校准。
3. 通过固定数量的混合形状进行模型优化，避免扩展模型复杂度，优化内存消耗和计算性能。
4. 跟踪参数估计和模型优化分为两个阶段迭代进行，第一阶段估计刚性对齐和跟踪参数，第二阶段优化用户特定的动态表情模型。
5. 基于跟踪参数生成用户面部表情的图形表示，可用于渲染动画视觉表示，并可封装为编程接口或SDK供其他处理模块调用。
6. 该方法无需用户特定预处理或手动校准，适用于任何新用户，显著提升了系统的易用性和普适性。
7. 应用于消费级产品，如虚拟现实、游戏、社交网络等，提供高质量实时面部动画和虚拟交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571062)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253301)**
<br/><br/>

---


<br/>

### 3. 用于显示演示应用程序演示环境的设备、方法和图形用户界面

**Title (EN)**: DEVICES, METHODS, AND GRAPHICAL USER INTERFACES FOR DISPLAYING PRESENTATION ENVIRONMENTS FOR A PRESENTATION APPLICATION  
**Pub. No.**: US20260252170

**Applicant**: Apple Inc.  
**Inventor**: [Amy W. HUNG](https://patents.google.com/?inventor=Amy+W.+HUNG&assignee=Apple&country=US&num=100&sort=new), [Peter G. BERGER](https://patents.google.com/?inventor=Peter+G.+BERGER&assignee=Apple&country=US&num=100&sort=new), [Robert S. MOYER](https://patents.google.com/?inventor=Robert+S.+MOYER&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本披露描述的一些实施例涉及用于显示与演示应用程序相关联的虚拟环境的计算机系统。在一些实施例中，计算机系统显示用户选择的虚拟环境，该虚拟环境模拟了演示将要进行的真实世界场景。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569822_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及增强现实和虚拟现实技术，具体涉及用于提供扩展现实体验的计算机系统和用户界面。

**Background (发明背景)**:  
近年来，增强现实计算机系统的发展显著增加。现有增强现实环境通常包含一些虚拟元素，这些元素可以替换或增强物理世界。然而，现有的交互系统存在反馈反馈不足、操作复杂、效率低下等问题，导致用户认知负担重，影响虚拟/增强现实体验。此外，这些方法耗时较长，增加了计算机系统的能耗，尤其对电池供电设备不利。

**Summary (发明总览)**:  
本发明提供了一种改进的计算机系统和方法，用于提供扩展现实体验。通过在虚拟环境中显示演示内容，并允许用户在不同模式或环境之间切换，系统实现了更直观和高效的交互。系统能够根据用户输入动态调整虚拟环境中的音频模型，并支持在虚拟环境中展示三维虚拟对象的立体表示，从而提升用户对虚拟演示的沉浸感和操作效率。

**Key Innovation (核心创新)**:  
1. 支持在虚拟环境中显示演示内容，并允许用户在不同模式之间切换，例如从二维模式切换到三维模式，以提供更丰富的视觉体验。
2. 通过接收用户输入，动态调整虚拟环境中的音频模型，使音频效果与当前环境相匹配，从而增强沉浸感。
3. 在虚拟环境中展示三维虚拟对象的立体表示，用户可以通过输入设备将二维表示的虚拟对象转换为三维形式，并放置在环境中的不同位置。
4. 系统集成了多种输入方式，包括触摸、眼球追踪和手势识别，使用户能够以更自然的方式与虚拟环境交互。
5. 针对电池供电设备优化了能耗管理，通过减少不必要的计算和渲染操作，延长了设备的电池使用时间。
6. 提供了更直观的用户界面，使用户能够更轻松地理解输入与设备响应之间的关系，从而提高交互效率。
7. 本专利可应用于虚拟会议、在线教育和虚拟展览等场景，为用户提供更具沉浸感和互动性的演示体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569822)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252170)**
<br/><br/>

---


<br/>

### 4. 消息环境中的智能自动化助手

**Title (EN)**: INTELLIGENT AUTOMATED ASSISTANT IN A MESSAGING ENVIRONMENT  
**Pub. No.**: US20260252370

**Applicant**: Apple Inc.  
**Inventor**: [Petr KARASHCHUK](https://patents.google.com/?inventor=Petr+KARASHCHUK&assignee=Apple&country=US&num=100&sort=new), [Tomas A. VEGA GALVEZ](https://patents.google.com/?inventor=Tomas+A.+VEGA+GALVEZ&assignee=Apple&country=US&num=100&sort=new), [Thomas R. GRUBER](https://patents.google.com/?inventor=Thomas+R.+GRUBER&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明提供了在消息环境中运行智能自动化助手的方法和系统。在一个示例过程中，电子设备的显示屏上可以显示包含用户与数字助手之间多个消息的图形用户界面（GUI），这些消息以对话视图呈现。接收用户输入后，将其作为GUI中的第一条消息显示。存储与显示的用户输入相对应的电子设备上下文状态。根据从用户输入中推导出的用户意图执行相应操作，并将基于该操作生成的响应作为第二条消息显示在GUI中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570039_1.jpg)

**Technical Field (技术领域)**:  
智能自动化助手技术，具体涉及消息环境中的智能助手交互。

**Background (发明背景)**:  
智能自动化助手（数字助手）为人机交互提供了便捷的接口，但现有技术通常依赖专用的用户界面（如语音界面），限制了交互的多样性和便利性。传统方式难以适应多模式输入和复杂场景，阻碍了数字助手的广泛应用。

**Summary (发明总览)**:  
本发明将智能自动化助手集成到消息环境中，通过消息平台的多模式输入能力和对话式界面，提升数字助手的交互体验和功能范围。用户可以通过文本、语音、图像等多种方式与助手互动，助手能够理解复杂请求并执行相应任务。相较于传统语音或专用界面，本发明利用消息平台的异步特性，使用户能够更方便地回顾历史对话并执行更复杂的任务。

**Key Innovation (核心创新)**:  
1. 将智能助手集成到消息平台中，支持文本、语音、图像等多种输入模式，提升交互灵活性。
2. 通过对话视图展示用户与助手的交互历史，使用户能够方便地回顾和利用上下文信息。
3. 支持处理包含媒体对象（如图片）的用户输入，能够从媒体中提取文本并执行相关任务。
4. 实现了跨设备的消息交互，允许用户通过电子设备与远程设备上的用户进行协作式对话。
5. 利用消息平台的异步特性，使用户能够在不同时间点与助手进行交互，而无需实时响应。
6. 增强了数字助手在嘈杂环境或音频受限场景中的可用性，例如图书馆或公共场所。
7. 推测本专利可应用于智能家居、客户服务和团队协作等场景，为用户提供更自然和高效的交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570039)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252370)**
<br/><br/>

---


<br/>

### 5. 面向色觉障碍人群的色彩增强算法

**Title (EN)**: COLOR ENHANCEMENT ALGORITHM FOR COLOR-DEFICIENT PEOPLE  
**Pub. No.**: US20260253187

**Applicant**: Apple Inc.  
**Inventor**: [Honkai Tam](https://patents.google.com/?inventor=Honkai+Tam&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种电子设备包括显示器和处理电路，处理电路与显示器通信连接。处理电路被配置为接收指示源图像数据中像素颜色分量的源图像数据。颜色分量包括最大颜色分量、中间颜色分量和最小颜色分量。处理电路还被配置为基于颜色分量确定像素的分类，并基于分类修改一个或多个颜色分量以生成调整后的图像数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570935_1.jpg)

**Technical Field (技术领域)**:  
图像处理领域，具体涉及针对色觉障碍人群的色彩增强技术。

**Background (发明背景)**:  
电子设备通常使用显示器呈现视觉信息，但色觉障碍人群（如色盲）难以区分某些颜色。现有的图像处理技术未能充分解决这一问题，导致色觉障碍用户无法清晰感知显示内容。

**Summary (发明总览)**:  
本发明提出了一种针对色觉障碍用户的图像处理技术，通过修改图像数据的颜色分量来增强色彩区分度。用户可以自定义设置，处理电路根据这些设置调整图像数据，使得显示内容对色觉障碍用户更加清晰可辨。该方法通过调整中间和最小颜色分量来优化色彩对比度，从而实现更好的视觉体验。

**Key Innovation (核心创新)**:  
1. 通过分析源图像数据的RGB值，确定每个像素的最大、中间和最小颜色分量。
2. 基于颜色分量的分类结果，动态调整中间和最小颜色分量，以增强色彩对比度。
3. 提供用户自定义设置功能，允许用户根据个人色觉障碍情况调整色彩增强参数。
4. 采用像素级处理机制，确保图像细节的保留和色彩的自然过渡。
5. 通过调整中间和最小颜色分量，避免过度改变图像的整体色调，保持视觉一致性。
6. 该技术可应用于多种显示设备，包括智能手机、平板电脑和计算机显示器。
7. 特别适用于需要长时间观看屏幕或进行色彩敏感工作的场景，如地图导航、图像编辑和视频播放，为色觉障碍用户提供更友好的使用体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570935)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253187)**
<br/><br/>

---


<br/>

### 6. 降低头戴式设备图像捕捉延迟

**Title (EN)**: Reducing Image Capture Latency in a Head-Mounted Device  
**Pub. No.**: US20260255054

**Applicant**: Apple Inc.  
**Inventor**: [Shannon L Gardiner](https://patents.google.com/?inventor=Shannon+L+Gardiner&assignee=Apple&country=US&num=100&sort=new), [Chiraag Juvekar](https://patents.google.com/?inventor=Chiraag+Juvekar&assignee=Apple&country=US&num=100&sort=new), [Karan Sanghi](https://patents.google.com/?inventor=Karan+Sanghi&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明提供了一种电子设备，包括一个或多个图像传感器、用于运行操作系统的第一处理电路、用于控制图像传感器捕捉图像的第二处理电路，以及用于检测用户输入并在检测到用户输入时同时唤醒第一和第二处理电路的第三处理电路。图像传感器可将捕捉到的图像输出到图像信号处理（ISP）电路。ISP电路包括计算机视觉处理（CVP）电路，该电路接收捕捉到的图像并具有在第一电源域中运行的分系统，以及在第二电源域中运行的后端图像信号处理流水线。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485572997_1.jpg)

**Technical Field (技术领域)**:  
头戴式设备技术领域，具体涉及图像捕捉和低延迟处理。

**Background (发明背景)**:  
头戴式设备通常需要快速响应用户输入以捕捉周围环境的图像，但现有技术中处理电路的唤醒延迟会影响图像捕捉的及时性。
现有系统通常依赖单一处理单元处理用户输入和图像捕捉，导致整体响应速度较慢。
这种延迟在需要实时图像处理的应用场景中尤为明显，例如增强现实和虚拟现实。

**Summary (发明总览)**:  
本发明通过引入专门用于检测用户输入的第三处理电路，实现了对第一处理电路（操作系统）和第二处理电路（图像捕捉控制）的快速并行唤醒。
第二处理电路在唤醒后立即启动图像捕捉，从而显著降低延迟。
第一处理电路在唤醒后可以运行更多复杂应用，而第三处理电路保持低功耗运行以持续检测用户输入。
这种架构优化了系统功耗和响应速度，特别适用于需要实时图像捕捉的扩展现实（XR）应用。

**Key Innovation (核心创新)**:  
1. 引入独立的第三处理电路专门用于检测用户输入，实现对主处理电路和图像处理电路的快速并行唤醒。
2. 第二处理电路在唤醒后立即启动图像捕捉，利用其较短的唤醒时间减少整体延迟。
3. 设计了分层的电源域架构，CVP电路和后端图像处理流水线在不同电源域中运行，优化了功耗管理。
4. 第二处理电路包含相机驱动程序，可在主处理电路完全唤醒前开始图像捕捉，进一步缩短响应时间。
5. 第三处理电路持续保持低功耗运行，确保用户输入能被即时检测，同时不影响整体系统功耗。
6. 该架构特别适用于扩展现实（XR）设备，能够在低延迟条件下处理实时图像数据，提升用户体验。
7. 通过优化唤醒时间和电源管理，本发明在保持高效能的同时降低了功耗，适用于电池供电的头戴式设备。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485572997)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260255054)**
<br/><br/>

---


<br/>

### 7. 基于上下文的物体跟踪模式切换

**Title (EN)**: Context-Based Mode Transitions for Object Tracking  
**Pub. No.**: US20260253234

**Applicant**: Apple Inc.  
**Inventor**: [Ioana Negoita](https://patents.google.com/?inventor=Ioana+Negoita&assignee=Apple&country=US&num=100&sort=new), [Brian W. Temple](https://patents.google.com/?inventor=Brian+W.+Temple&assignee=Apple&country=US&num=100&sort=new), [Lee Sparks](https://patents.google.com/?inventor=Lee+Sparks&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
在某些实现中，一种方法包括：在按照第一模式运行时，获取与物理环境相关的音频数据和运动传感器数据；确定音频数据和运动传感器数据中的至少一个是否满足模式切换标准；如果确定音频数据和运动传感器数据中的至少一个满足模式切换标准，则将计算系统从第一模式切换到第二模式；在按照第二模式运行时：通过图像传感器基于图像帧摄取率获取物理环境的图像帧；对图像帧执行一组图像处理功能以确定已注册物体的当前位置；并更新已注册物体的记录以包括当前位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570988_1.jpg)

**Technical Field (技术领域)**:  
物体跟踪与监测领域，具体涉及基于上下文的模式切换技术。

**Background (发明背景)**:  
计算系统通常会注册并跟踪感兴趣的物理物体，例如通过场景相机持续捕捉物理环境的图像以跟踪其中的注册物体。然而，持续分析这些图像会消耗大量电力和计算资源。现有技术缺乏有效的节能机制，导致资源浪费。

**Summary (发明总览)**:  
本发明提出了一种基于上下文的物体跟踪模式切换方法，通过结合音频和运动传感器数据来智能切换工作模式。当检测到环境变化时，系统从低功耗模式切换到高功耗模式以进行精确跟踪。这种方法通过减少不必要的图像处理，降低了能耗并优化了资源利用。

**Key Innovation (核心创新)**:  
1. 结合音频和运动传感器数据作为模式切换的触发条件，实现对环境变化的智能感知。
2. 通过设置模式切换标准，系统能够在低功耗模式和高功耗模式之间动态切换，优化资源利用。
3. 在高功耗模式下，利用图像传感器获取图像帧，并通过图像处理功能精确定位已注册物体的位置。
4. 更新已注册物体的记录信息，确保跟踪数据的实时性和准确性。
5. 通过减少不必要的图像处理，降低了系统的整体能耗，延长了设备续航时间。
6. 该方法适用于智能家居、安防监控和物联网设备等场景，能够在保证跟踪精度的同时降低能耗。
7. 提供了一种高效且节能的物体跟踪解决方案，特别适用于对功耗敏感的移动和嵌入式设备。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570988)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253234)**
<br/><br/>

---


<br/>

### 8. 创意相机

**Title (EN)**: CREATIVE CAMERA  
**Pub. No.**: US20260255047

**Applicant**: Apple Inc.  
**Inventor**: [Marcel VAN OS](https://patents.google.com/?inventor=Marcel+VAN+OS&assignee=Apple&country=US&num=100&sort=new), [Lee BROUGHTON](https://patents.google.com/?inventor=Lee+BROUGHTON&assignee=Apple&country=US&num=100&sort=new), [Nicholas V. KING](https://patents.google.com/?inventor=Nicholas+V.+KING&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明主要涉及在图像数据中显示视觉效果的领域。在一些示例中，视觉效果包括在用户面部显示的虚拟形象。在一些示例中，视觉效果包括应用于图像数据的贴纸。在一些示例中，视觉效果包括屏幕效果。在一些示例中，视觉效果根据图像数据中的深度数据进行修改。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485572989_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及图像数据中的视觉效果显示，包括虚拟形象、贴纸和屏幕效果的应用。

**Background (发明背景)**:  
电子设备在捕捉和查看媒体时使用视觉效果来增强用户体验。现有技术通常采用复杂且耗时的用户界面，可能需要多次按键或操作，导致用户时间和设备能量浪费，这在电池供电设备中尤为重要。本发明旨在提供更快速、更高效的方法和界面来显示视觉效果。

**Summary (发明总览)**:  
本发明提出了一种改进的视觉效果显示方法，通过电子设备的相机和显示界面实现。用户可以通过简单的交互操作在图像数据中应用虚拟形象或贴纸等视觉效果。系统能够根据用户的操作实时调整视觉效果，例如在捕捉图像后自动切换发送按钮，并支持基于深度数据的视觉效果调整。相较于现有技术，本发明简化了用户操作流程，提高了交互效率，并优化了设备能耗管理。

**Key Innovation (核心创新)**:  
1. 提供了一种基于手势操作的相机界面，用户可以通过简单手势在拍摄过程中实时应用虚拟形象。
2. 实现了虚拟形象与用户姿态的动态同步，系统能够根据用户姿态变化实时调整虚拟形象的外观。
3. 在相机界面中集成了发送按钮功能，用户在拍摄完成后无需额外操作即可发送图像数据。
4. 支持根据图像数据中的深度信息调整视觉效果，例如在背景虚化时调整虚拟形象的位置和大小。
5. 通过优化用户界面交互流程，减少了操作步骤和按键次数，提升了用户体验和操作效率。
6. 适用于即时通讯应用场景，用户可以在聊天过程中快速捕捉并发送带有虚拟形象或贴纸的图像。
7. 优化了电池供电设备的能耗管理，通过减少不必要的界面刷新和操作步骤延长了设备续航时间。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485572989)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260255047)**
<br/><br/>

---


<br/>

### 9. 用于线程分配硬件资源的硬件资源分配系统

**Title (EN)**: Hardware Resource Allocation System for Allocating Resources to Threads  
**Pub. No.**: US20260252387

**Applicant**: Apple Inc.  
**Inventor**: [Mark D. Earl](https://patents.google.com/?inventor=Mark+D.+Earl&assignee=Apple&country=US&num=100&sort=new), [Dimitri Tan](https://patents.google.com/?inventor=Dimitri+Tan&assignee=Apple&country=US&num=100&sort=new), [Christopher L. Spencer](https://patents.google.com/?inventor=Christopher+L.+Spencer&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
在各种实施例中，资源分配管理电路可将多种不同类型的硬件资源（例如，不同类型的寄存器）分配给多个线程。不同类型的硬件资源对应多个硬件资源分配电路。资源分配管理电路使用线程的状态识别值跟踪硬件资源对线程的分配。当确定少于请求数量的某种或多种类型的硬件资源可用时，资源分配管理电路可识别一个或多个需要解除分配的线程。因此，与不使用状态识别值跟踪硬件资源对线程分配的硬件资源分配系统相比，本硬件资源分配系统可更高效地将硬件资源分配给线程。此外，由于与较少线程相关的硬件资源可能被解除分配，因此与传输线程状态信息相关的内存带宽也可能减少。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570059_1.jpg)

**Technical Field (技术领域)**:  
硬件资源管理领域，具体涉及多线程环境下的硬件资源分配技术。

**Background (发明背景)**:  
在计算设备（如图形处理单元GPU）中，提高硬件资源利用率的目标是尽可能长时间地充分利用设备。现有技术通过并行执行多个进程并动态分配硬件资源来提高利用率，但当进程请求的硬件资源总量超过可用资源时，管理这种分配变得困难。本发明旨在解决硬件资源分配效率低下以及资源解除分配后重复分配带来的内存带宽浪费问题。

**Summary (发明总览)**:  
本发明提出了一种硬件资源分配系统，通过资源分配管理电路管理多个线程对多种硬件资源的分配请求。该系统使用线程的状态识别值跟踪资源分配情况，并在资源不足时选择性地解除分配特定线程的资源。与传统方法相比，本发明通过减少不必要的资源解除分配和重新分配，降低了内存带宽消耗，提高了资源分配效率。

**Key Innovation (核心创新)**:  
1. 使用状态识别值跟踪每个线程的资源分配状态，实现对硬件资源的高效管理。
2. 在资源不足时，通过分析线程状态识别值，优先解除分配处于非活动执行状态的线程资源。
3. 减少资源解除分配后重新分配带来的内存带宽消耗，因为系统只针对特定线程进行资源调整。
4. 支持从多个指令流水线接收线程并独立处理资源请求，适应复杂的并行计算环境。
5. 通过硬件资源分配电路与资源管理电路的协同工作，实现对不同类型硬件资源的精细化分配。
6. 适用于多线程并行计算场景，如GPU计算，可提高资源利用率并降低系统能耗。
7. 在高负载情况下，通过智能资源分配策略，显著提升系统整体性能和稳定性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570059)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252387)**
<br/><br/>

---


<br/>

### 10. 用于改进室内人员检测的系统和技术

**Title (EN)**: SYSTEM AND TECHNIQUES FOR IMPROVING IN-ROOM PERSON DETECTION  
**Pub. No.**: US20260251790

**Applicant**: Apple Inc.  
**Inventor**: [Barak Baum](https://patents.google.com/?inventor=Barak+Baum&assignee=Apple&country=US&num=100&sort=new), [Yoav Feinmesser](https://patents.google.com/?inventor=Yoav+Feinmesser&assignee=Apple&country=US&num=100&sort=new), [Naftali Sommer](https://patents.google.com/?inventor=Naftali+Sommer&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种用于确定房间内人员存在性的技术可能包括电子设备发送第一传感器的电磁无线信号。该技术可能包括接收来自电磁无线信号的电磁回波信号。该技术可能包括基于电磁回波信号检测房间内的潜在目标。该技术可能包括使用第二传感器确定潜在目标在房间内。在确定潜在目标在房间内后，该技术可能包括保存电磁回波信号的训练特征以训练机器学习模型。该技术可以重复进行以获得对应于潜在目标在房间内的一组训练特征。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569407_1.jpg)

**Technical Field (技术领域)**:  
室内人员检测技术领域，具体涉及结合电磁信号和超声波雷达（声纳）进行目标检测。

**Background (发明背景)**:  
家庭自动化系统用于检测家庭中各个房间内人员的存在或缺失。然而，现有技术难以在不干扰住户的情况下提供高准确度的检测。现有系统通常依赖单一传感器，可能导致误报或漏报。

**Summary (发明总览)**:  
本发明提出了一种结合无线电磁信号和超声波雷达（声纳）来改进室内人员检测的方法。通过电磁信号检测潜在目标，并使用超声波雷达进行确认，以减少误报。电子设备可以保存电磁信号的回波特征，并利用这些特征训练机器学习模型，从而提高检测准确性。

**Key Innovation (核心创新)**:  
1. 结合使用无线电磁信号和超声波雷达（声纳），通过电磁信号检测目标并用超声波雷达进行确认，以减少误报。
2. 利用电子设备中的扬声器和麦克风作为声纳信号的发射和接收装置，实现对房间的广泛覆盖。
3. 通过记录电磁信号回波的训练特征，并使用这些特征训练机器学习模型，使系统能够学习并适应不同的室内环境。
4. 在训练过程中包含无目标和目标在房间外的案例，使机器学习模型能够学习正确的决策规则。
5. 使用第二传感器（如红外传感器或摄像头）来校准和训练房间模型，以识别特定目标并提高检测精度。
6. 当机器学习模型的预测率达到阈值时，可以停止使用声纳，从而减少对家庭宠物的干扰。
7. 通过分析来自其他电子设备（如智能手机、智能手表、无线耳机）的无线信号，进一步检测和分类房间内的目标，提供更全面的检测能力。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569407)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260251790)**
<br/><br/>

---


<br/>

### 11. 用于分享上下文相关媒体内容的用户界面

**Title (EN)**: USER INTERFACES FOR SHARING CONTEXTUALLY RELEVANT MEDIA CONTENT  
**Pub. No.**: US20260252211

**Applicant**: Apple Inc.  
**Inventor**: [Lynne DEVINE](https://patents.google.com/?inventor=Lynne+DEVINE&assignee=Apple&country=US&num=100&sort=new), [Michael BRANDT](https://patents.google.com/?inventor=Michael+BRANDT&assignee=Apple&country=US&num=100&sort=new), [Eric M.G. CIRCLAEYS](https://patents.google.com/?inventor=Eric+M.G.+CIRCLAEYS&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明主要涉及管理和分享上下文相关的媒体内容。在一些实施例中，设备接收输入后，会显示一个建议的媒体项集合供与收件人分享，该集合与和收件人的消息对话相关。在显示建议的媒体项集合后，设备会发送一条消息作为消息对话的一部分，提供对建议的媒体项集合中至少一部分的访问权限。在一些实施例中，设备接收来自外部设备的指示，表明第一个用户已与第二个用户分享了第一个媒体项集合。在接收到该指示后，设备会提示与第一个用户分享与第二个用户相关且基于上下文与第一个媒体项集合相关的一个或多个建议媒体项，这些建议媒体项不包括在第一个集合中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569868_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及媒体内容查看与分享的优化方法。

**Background (发明背景)**:  
随着用户媒体库规模的扩大和设备间媒体分享量的增加，现有技术在处理此类活动时显得繁琐且低效。例如，一些现有技术使用复杂且耗时的用户界面，需要多次按键或击键操作，导致用户时间和设备能耗的浪费，尤其在电池供电设备中更为突出。

**Summary (发明总览)**:  
本发明提供了一种更快速、更高效的用户界面方法，用于查看和分享相关媒体内容。设备通过接收用户输入，智能地推荐与当前对话相关的媒体项集合，用户可以选择部分或全部内容进行分享。相较于现有技术，本发明减少了用户操作步骤，优化了人机交互界面，提升了操作效率和用户体验，同时节省了设备能耗。

**Key Innovation (核心创新)**:  
1. 通过接收用户输入，智能推荐与当前消息对话相关的媒体项集合，简化用户选择过程。
2. 采用上下文感知技术，根据对话内容和用户历史数据生成精准的媒体推荐，提升推荐的关联性和实用性。
3. 提供快速分享机制，用户只需少量操作即可将推荐媒体项发送给收件人，简化分享流程。
4. 在接收到他人分享媒体项的指示后，设备能自动提示用户分享与该内容相关且基于上下文的额外媒体项，促进更丰富的互动。
5. 通过减少不必要的用户操作和优化界面设计，降低用户认知负担，提高人机交互效率。
6. 针对电池供电设备，优化了操作流程和界面显示方式，有效节省设备能耗，延长电池使用时间。
7. 本专利可应用于社交媒体平台、即时通讯工具和多媒体内容管理应用，为用户提供更智能、更高效的媒体分享体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569868)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252211)**
<br/><br/>

---


<br/>

### 12. 力检测输入结构

**Title (EN)**: FORCE-DETECTING INPUT STRUCTURE  
**Pub. No.**: US20260252033

**Applicant**: Apple Inc.  
**Inventor**: [Colin M. Ely](https://patents.google.com/?inventor=Colin+M.+Ely&assignee=Apple&country=US&num=100&sort=new), [Erik G. de Jong](https://patents.google.com/?inventor=Erik+G.+de+Jong&assignee=Apple&country=US&num=100&sort=new), [Fletcher R. Rothkopf](https://patents.google.com/?inventor=Fletcher+R.+Rothkopf&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种输入机构，例如表冠，能够检测施加的力的大小。在各种示例中，包括输入机构的组件具有外壳；与外壳耦合的轴杆，使得轴杆能够相对于外壳旋转、平移和横向移动；一个传感器，连接在轴杆与外壳之间，当轴杆相对于外壳移动时，力会传递到传感器上；以及与传感器耦合的处理单元。处理单元能够基于传感器的信号确定力的测量值。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569673_1.jpg)

**Technical Field (技术领域)**:  
电子设备输入技术领域，具体涉及可检测施加力大小的输入结构，例如表冠、按钮等。

**Background (发明背景)**:  
许多设备，特别是小型可穿戴设备，如智能手表等，通常使用有限的输入机制，例如表冠。现有技术中，表冠主要用于旋转或平移操作，但无法检测用户施加的力度。这限制了设备接收多样化输入的能力。

**Summary (发明总览)**:  
本发明提出了一种能够检测施加力大小的输入结构，例如表冠、按钮等。该输入结构通过内置的力传感器或电容传感器，感知用户操作时的力度变化，并将信号传递给处理单元进行处理。该设计使得输入结构能够识别不同类型的操作并接收多样化输入，从而提升设备的交互能力。

**Key Innovation (核心创新)**:  
1. 采用力传感器或电容传感器检测用户对输入结构施加的力度，实现非二值化的力检测。
2. 通过轴杆与外壳之间的传感器连接，感知轴杆的横向移动并测量相应的力大小。
3. 使用柔性材料作为电容传感器的介电层，确保传感器在轴杆移动时能够准确感知力的变化。
4. 在输入结构中集成可移动导体和导电元件，通过电容变化来检测力的施加情况。
5. 处理单元能够基于传感器信号确定力的具体数值，并识别轴杆移动的方向。
6. 传感器与处理单元之间可通过无线传输机制进行通信，提升设备的灵活性和可集成性。
7. 该输入结构可应用于智能手表等小型设备，为用户提供更精准的交互方式，例如通过力度控制实现不同的功能操作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569673)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252033)**
<br/><br/>

---


<br/>

### 13. 电子设备与远程电子设备之间的语音通信会话中的数字助手交互

**Title (EN)**: DIGITAL ASSISTANT INTERACTIONS IN A VOICE COMMUNICATION SESSION BETWEEN AN ELECTRONIC DEVICE AND A REMOTE ELECTRONIC DEVICE  
**Pub. No.**: US20260253588

**Applicant**: Apple Inc.  
**Inventor**: [Jonathan H. RUSSELL](https://patents.google.com/?inventor=Jonathan+H.+RUSSELL&assignee=Apple&country=US&num=100&sort=new), [Felicia W. EDWARDS](https://patents.google.com/?inventor=Felicia+W.+EDWARDS&assignee=Apple&country=US&num=100&sort=new), [Keith C. STRICKLING](https://patents.google.com/?inventor=Keith+C.+STRICKLING&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种示例方法包括：接收调用在电子设备上运行的数字助手的请求；如果确定在电子设备与至少一个远程设备进行语音通信会话期间接收到调用数字助手的请求，则根据第一组隐私设置操作数字助手；如果确定在电子设备未与至少一个远程设备进行语音通信会话期间接收到调用数字助手的请求，则根据第二组隐私设置操作数字助手，其中第二组隐私设置与第一组隐私设置不同。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571380_1.jpg)

**Technical Field (技术领域)**:  
智能数字助手技术，具体涉及在电子设备与远程设备之间的语音通信会话中调用数字助手。

**Background (发明背景)**:  
智能数字助手为用户与电子设备之间的交互提供了便捷接口，但现有技术中，在语音通信会话期间调用数字助手时，隐私保护机制不足，可能导致远程用户意外听到或干扰会话。此外，现有技术未充分考虑在语音通信会话期间数字助手对用户隐私的保护以及如何避免处理非预期输入。

**Summary (发明总览)**:  
本发明提出了一种在电子设备与远程设备进行语音通信会话期间调用数字助手的方法。该方法根据设备是否处于语音通信会话中，采用不同的隐私设置来操作数字助手。在会话期间，数字助手仅响应近端用户的请求，而不将响应发送给远程用户，从而保护隐私并避免干扰通信。本发明通过扩展数字助手的使用场景，同时确保通信安全和隐私保护，提升了用户交互效率和设备性能。

**Key Innovation (核心创新)**:  
1. 在语音通信会话期间调用数字助手时，采用专门的第一组隐私设置，确保数字助手仅响应近端用户的请求。
2. 通过区分语音通信会话期间和非会话期间调用数字助手的隐私设置，实现对远程用户隐私的保护，避免数字助手处理非预期输入。
3. 在语音通信会话期间，数字助手生成的响应仅提供给近端用户，而不发送给远程用户，从而避免对通信会话的干扰。
4. 数字助手在处理请求时，会根据是否处于语音通信会话中动态调整其行为模式，确保在不同场景下的隐私合规性。
5. 通过限制数字助手在语音通信会话期间的处理范围，防止其监听或处理远程用户的语音输入，从而增强用户隐私保护。
6. 本发明适用于智能手机、平板电脑等具备语音通信功能的设备，能够在保护隐私的同时提供数字助手服务。
7. 通过优化数字助手在语音通信会话期间的行为，提升用户交互效率，延长设备电池寿命，并确保通信安全和隐私合规。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571380)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253588)**
<br/><br/>

---


<br/>

### 14. 带嵌入式硅胶泡沫部分的耳塞

**Title (EN)**: EARTIPS WITH AN INSET SILICONE FOAM SECTION  
**Pub. No.**: US20260255095

**Applicant**: Apple Inc.  
**Inventor**: [Sarah B. Gysbers](https://patents.google.com/?inventor=Sarah+B.+Gysbers&assignee=Apple&country=US&num=100&sort=new), [Matthew J. Zaverl](https://patents.google.com/?inventor=Matthew+J.+Zaverl&assignee=Apple&country=US&num=100&sort=new), [Lee M. Panecki](https://patents.google.com/?inventor=Lee+M.+Panecki&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种可变形耳塞，包括：一体式硅橡胶耳塞主体，其包括一个界定通过可变形耳塞的声道的环形内体，以及一个与环形内体一体成型并围绕环形内体呈间隔关系的环形外法兰；一个在环形内体的外表面部分形成并完全围绕该部分延伸至外法兰的闭孔硅胶泡沫部分，从而填充环形内体和外法兰之间的空间；一个在外法兰和内壁之间形成的偏折区；以及一个与环形内体耦合并界定一个与通过环形内体形成的声道对齐的中央框架开口的环形刚性框架。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485573042_1.jpg)

**Technical Field (技术领域)**:  
耳机技术领域，具体涉及用于入耳式耳机的硅胶泡沫复合耳塞。

**Background (发明背景)**:  
入耳式耳机广泛应用于各种电子设备中，其耳塞需要提供良好的声学密封以提升音质并减少外界噪音。
传统耳塞在舒适性和降噪性能之间难以平衡，尤其在高频和中频噪音的被动衰减方面存在不足。
现有技术未能有效解决耳塞在高频噪音被动衰减与佩戴舒适性之间的矛盾。
本发明旨在提供一种兼具良好降噪性能、舒适性和声学密封能力的耳塞解决方案。

**Summary (发明总览)**:  
本发明提出了一种新型复合结构耳塞，通过在硅橡胶主体上嵌入硅胶泡沫层，显著提升了耳塞对中频和高频噪音的被动衰减能力。
该设计在不牺牲佩戴舒适性和声学密封性的前提下，利用泡沫层的声学特性阻挡外部噪音。
通过在耳塞主体和外法兰之间设置空气间隙（偏折区），确保耳塞能够适应不同耳道形状，提升佩戴稳定性。
该技术特别适用于配备主动降噪（ANC）功能的入耳式耳机，可增强ANC系统对中高频噪音的抑制效果。
整体方案通过优化材料组合和结构设计，实现了性能与用户体验的平衡。

**Key Innovation (核心创新)**:  
1. 采用闭孔硅胶泡沫层嵌入耳塞主体外表面，阻挡中频和高频噪音，提升被动降噪性能。
2. 通过在耳塞主体和外法兰之间设置空气间隙（偏折区），确保耳塞能够适应不同耳道形状，提升佩戴舒适性和稳定性。
3. 使用热塑性微球与液态硅橡胶混合并在特定位置加热膨胀，形成硅胶泡沫层，避免增加耳塞整体硬度，保证佩戴舒适性。
4. 采用三重注塑成型工艺，分别制造刚性框架、外法兰及耳塞主体，以及闭孔硅胶泡沫部分，确保各部分结构精确。
5. 刚性框架采用玻璃纤维增强尼龙材料，提升耳塞的耐用性和结构稳定性。
6. 该设计特别适用于配备ANC功能的耳机，通过增强中高频噪音的被动衰减，进一步提升ANC系统的整体降噪效果。
7. 应用于无线入耳式耳机时，可提供更优质的聆听体验，尤其在嘈杂环境中表现突出。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485573042)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260255095)**
<br/><br/>

---


<br/>

### 15. 具有展频驱动色层显示

**Title (EN)**: Display with Spread Spectrum Driven Tint Layer  
**Pub. No.**: US20260254938

**Applicant**: Apple Inc.  
**Inventor**: [Youngbae Son](https://patents.google.com/?inventor=Youngbae+Son&assignee=Apple&country=US&num=100&sort=new), [Shengchang Cai](https://patents.google.com/?inventor=Shengchang+Cai&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种显示设备包括用于传播图像光的波导。光学耦合器将图像光重定向至视窗。色层通过耦合器将环境光传输至视窗。驱动器向色层提供驱动信号，使色层处于稳态。驱动信号包括第一频率的二进制方波。驱动器在色层处于稳态时随时间变化第一频率。驱动器通过一组N个不同频率随机或按照预定计划变化第一频率。通过这种方式变化第一频率，可以减少环境光中由色层引起的闪烁现象，特别是在环境光包含强度调制的光时。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485572869_1.jpg)

**Technical Field (技术领域)**:  
电子设备技术领域，具体涉及头戴式显示设备中的光学显示技术。

**Background (发明背景)**:  
头戴式设备通常配备近眼显示系统，用于向用户呈现虚拟内容。
现有技术中，如何设计近眼显示系统以清晰呈现虚拟内容并避免环境光干扰是一个挑战。
如果设计不当，虚拟内容可能会被环境光冲淡，或者显示内容会出现令人不适的视觉伪影。
本发明旨在解决环境光干扰和视觉伪影问题。

**Summary (发明总览)**:  
本发明提出了一种改进型头戴式显示设备，通过波导传播图像光，并使用光学耦合器将图像光和环境光合并后传输至视窗。
色层在驱动信号控制下调节环境光的透过程度，驱动信号包含特定频率的方波。
通过在稳态下随机或按预定计划切换驱动信号的频率，可以消除环境光中的闪烁现象。
这种设计有效解决了现有技术中因频率干涉导致的视觉伪影问题。

**Key Innovation (核心创新)**:  
1. 采用展频技术，通过在稳态下随机或按预定计划切换驱动信号的频率，避免了环境光中的闪烁现象。
2. 使用二进制方波作为驱动信号，并通过一组N个不同频率的变化来减少环境光中的干涉效应。
3. 光学耦合器作为图像光和环境光的组合器，实现了虚拟内容与环境光的自然融合。
4. 色层在驱动信号控制下动态调节环境光的透过程度，提供更清晰的虚拟内容显示效果。
5. 通过消除环境光中的闪烁和干涉效应，提升了用户在虚拟现实或增强现实场景中的视觉舒适度。
6. 该技术特别适用于头戴式显示设备，在保证虚拟内容清晰度的同时，允许用户感知环境光。
7. 潜在应用场景包括虚拟现实、增强现实设备，以及需要与环境光自然交互的近眼显示系统。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485572869)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260254938)**
<br/><br/>

---


<br/>

### 16. 无线音频系统

**Title (EN)**: Un-Tethered Wireless Audio System  
**Pub. No.**: US20260255105

**Applicant**: Apple Inc.  
**Inventor**: [Clarke S. WATSON](https://patents.google.com/?inventor=Clarke+S.+WATSON&assignee=Apple&country=US&num=100&sort=new), [Benjamin W. COOK](https://patents.google.com/?inventor=Benjamin+W.+COOK&assignee=Apple&country=US&num=100&sort=new), [Axel D. BERNY](https://patents.google.com/?inventor=Axel+D.+BERNY&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种无线扬声器音频系统，用于接收音频源通过无线传输的音频信息。该系统包括第一和第二无线收发器。第一无线收发器与音频源建立双向次级无线链路，用于接收和确认音频信息的接收。第一和第二无线收发器通过主无线链路进行通信。无线音频系统包括音频源以及第一和第二无线收发器。第一和第二无线收发器通过主无线链路通信。音频源通过次级无线链路将音频信息传输给第一无线收发器，该次级无线链路根据标准无线协议配置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485573055_1.jpg)

**Technical Field (技术领域)**:  
无线音频技术领域，具体涉及无线扬声器系统及其通信链路。

**Background (发明背景)**:  
传统无线立体声音响通常采用单一射频收发器，通过有线连接向左右扬声器传输音频。现有技术中，使用专有无线协议的无线扬声器需要音频源额外配备适配器，而使用标准协议的无线扬声器则难以可靠地传输立体声音频到独立的左右接收器，导致扬声器之间需要有线连接，影响美观和使用便利性。

**Summary (发明总览)**:  
本发明提出了一种无线音频系统，通过在左右扬声器之间建立主无线链路，以及在音频源与其中一个扬声器之间建立次级无线链路，解决了现有技术中需要有线连接的问题。主无线链路可采用标准或专有协议，而次级无线链路采用标准协议以确保与音频源的兼容性。该系统消除了扬声器之间的有线连接，提升了使用便利性和美观性。

**Key Innovation (核心创新)**:  
1. 采用主次双无线链路设计，其中主链路连接左右扬声器，次级链路连接音频源与其中一个扬声器。
2. 主无线链路可选择标准协议或专有协议，以平衡兼容性和性能需求。
3. 次级无线链路采用标准协议，确保与市面上的主流音频源设备兼容。
4. 通过消除扬声器之间的有线连接，解决了传统无线扬声器系统中的线缆问题，提升了美观性和便携性。
5. 避免了使用专有协议带来的额外适配器需求问题，降低了系统复杂性和成本。
6. 适用于家庭音响、耳机等设备，尤其适合需要高便携性和美观性的应用场景。
7. 提供了更可靠和高效的立体声音频传输方案，解决了现有标准协议在无线立体声传输中的不足。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485573055)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260255105)**
<br/><br/>

---


<br/>

### 17. 搜索到应用用户界面的过渡

**Title (EN)**: SEARCH TO APPLICATION USER INTERFACE TRANSITIONS  
**Pub. No.**: US20260252219

**Applicant**: Apple Inc.  
**Inventor**: [Cameron BURGESS](https://patents.google.com/?inventor=Cameron+BURGESS&assignee=Apple&country=US&num=100&sort=new), [Ramon GILABERT LLOP](https://patents.google.com/?inventor=Ramon+GILABERT+LLOP&assignee=Apple&country=US&num=100&sort=new), [James N. JONES](https://patents.google.com/?inventor=James+N.+JONES&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明提供了一种系统和流程，用于实现搜索用户界面的显示和操作。当显示主屏幕时，通过检测特定手势输入来显示搜索用户界面；在搜索用户界面中检测到选择结果的输入后，显示与结果相关的应用用户界面；在应用用户界面显示期间，检测特定类型的输入，并根据输入的时间阈值或其他条件决定是返回搜索用户界面还是返回主屏幕。本发明旨在提高用户在不同界面间切换的效率，减少操作步骤，并优化设备资源使用。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569877_1.jpg)

**Technical Field (技术领域)**:  
用户界面技术领域，具体涉及搜索用户界面的连续性和应用切换机制。

**Background (发明背景)**:  
现有的电子设备中，从应用用户界面访问搜索用户界面通常较为繁琐。此外，许多搜索用户界面无法将用户输入或搜索结果数据有效地传递给其他应用或界面。这导致用户在不同界面间切换时效率低下，操作步骤繁琐。本发明旨在解决用户在不同界面间切换时的连续性问题，提高交互效率。

**Summary (发明总览)**:  
本发明提出了一种用户界面过渡机制，通过检测特定手势输入来快速切换到搜索界面，并在搜索结果中选择应用后进入相应的应用界面。在应用界面中，用户可以通过特定操作快速返回搜索界面或主屏幕。该机制通过减少用户操作步骤，优化了用户在不同界面间的切换体验，提高了交互效率，并降低了设备功耗。

**Key Innovation (核心创新)**:  
1. 通过检测特定手势输入，实现从主屏幕到搜索用户界面的快速切换，提升了用户访问搜索功能的便捷性。
2. 在搜索结果中选择应用后，系统会直接进入与结果相关的应用界面，并提供与搜索结果关联的用户界面对象，确保了搜索结果与应用的无缝衔接。
3. 在应用界面中，检测特定类型的输入（如返回手势），并根据输入的时间阈值决定是返回搜索界面还是主屏幕，实现了用户界面的智能过渡。
4. 当用户在应用界面中执行其他操作后，系统会检测到操作顺序并相应地返回主屏幕，避免了不必要的界面切换。
5. 本发明通过减少用户操作步骤和优化界面过渡逻辑，提高了用户与电子设备交互的整体效率。
6. 该机制降低了设备在界面切换过程中的资源消耗，延长了电池寿命。
7. 本发明适用于智能手机、平板电脑等电子设备，可应用于需要频繁进行搜索和应用切换的场景，如信息检索、任务管理和多任务处理。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569877)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252219)**
<br/><br/>

---


<br/>

### 18. 隐藏式浅深度连接器插座

**Title (EN)**: CONCEALED SHALLOW-DEPTH RECEPTACLE  
**Pub. No.**: US20260254156

**Applicant**: Apple Inc.  
**Inventor**: [Mahmoud R. Amini](https://patents.google.com/?inventor=Mahmoud+R.+Amini&assignee=Apple&country=US&num=100&sort=new), [James M. Jeon](https://patents.google.com/?inventor=James+M.+Jeon&assignee=Apple&country=US&num=100&sort=new), [Ayoub Yari Boroujeni](https://patents.google.com/?inventor=Ayoub+Yari+Boroujeni&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明涉及可隐藏和保护的低轮廓或浅深度连接器插座及其相关结构。示例提供了一种具有连接器插座的电子设备，该连接器插座可通过盖子隐藏。盖子可以隐藏连接器插座并防止碎屑进入。连接器插座还具有浅深度，适合用于小型设备。可以使用各种盖子机构，这些机构可以是双稳态的，即具有稳定的开启位置和关闭位置。当用户将盖子从开启位置移动到关闭位置以及从关闭位置移动到开启位置时，可以提供触觉反馈。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485572006_1.jpg)

**Technical Field (技术领域)**:  
电子设备连接器技术领域，具体涉及可隐藏式浅深度连接器插座及其保护盖设计。

**Background (发明背景)**:  
随着电子设备种类和数量的增加，对连接器插座的需求也在增长。然而，小型设备上的连接器插座开口影响美观，且容易受到灰尘和碎屑的污染，影响设备功能。此外，连接器插座通常需要一定的深度以符合标准，这给小型设备的设计带来了挑战。因此，需要能够隐藏和保护连接器插座并具有浅深度的解决方案。

**Summary (发明总览)**:  
本发明提供了一种可隐藏和保护的浅深度连接器插座设计方案。通过使用可滑动的盖子，连接器插座可以在不使用时隐藏并受到保护。盖子采用双稳态机制，提供明确的开启和关闭位置，并通过触觉反馈增强用户体验。连接器插座的浅深度设计使其适用于小型设备，同时保持与标准连接器的兼容性。

**Key Innovation (核心创新)**:  
1. 采用可滑动的盖子设计，实现连接器插座的隐藏和保护，防止灰尘和碎屑进入。
2. 盖子采用双稳态机制，提供明确的开启和关闭位置，并通过斜面设计提供触觉反馈。
3. 连接器插座采用浅深度设计，通过在舌片末端设置垂直框架，并在框架背面设置表面贴装接触部分，实现小型化。
4. 使用偏置弹簧或差动弹簧机构，实现盖子的稳定开启和关闭位置，并提供用户友好的操作体验。
5. 采用磁铁和铁磁材料组合的双稳态设计，通过磁力提供明确的开启和关闭位置，并增强触觉反馈。
6. 盖子与设备主体的相对运动通过精密设计的滑轨或导轨实现，确保操作的顺畅性和可靠性。
7. 本发明适用于便携式计算设备、手机、媒体播放器等小型电子设备，能够在不牺牲功能性的前提下提升设备的美观性和耐用性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485572006)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260254156)**
<br/><br/>

---


<br/>

### 19. 头戴式设备的态势感知

**Title (EN)**: Situational awareness for head mounted devices  
**Pub. No.**: US12718837

**Applicant**: Apple Inc.  
**Inventor**: [Neal D Evans](https://patents.google.com/?inventor=Neal+D+Evans&assignee=Apple&country=US&num=100&sort=new), [Robert D Silfvast](https://patents.google.com/?inventor=Robert+D+Silfvast&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明公开了用于为头戴式设备（HMD）用户提供态势感知的设备、系统和方法。一些实施例涉及向佩戴HMD的第一用户在物理环境中提供计算机生成现实（CGR）体验。在CGR体验期间，从物理环境中的传感器获取音频数据或图像数据，并基于该数据检测除第一用户之外的第二人的情绪状态或注意力方向。基于检测到的第二人的情绪状态或注意力方向，在CGR体验中提供通知或其他变化。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345982_1.jpg)

**Technical Field (技术领域)**:  
电子设备领域，具体涉及头戴式设备（HMD）的物理环境监测和用户反馈技术。

**Background (发明背景)**:  
用户在佩戴HMD进行CGR体验时，对周围物理环境的感知能力会降低或受限。例如，CGR内容可能会遮挡或削弱用户对物理环境的视听信息。此外，用户的行为可能会对周围人造成干扰，而用户可能并不知情。因此，有必要向用户提供基于周围人反应的信息，以帮助用户了解其行为对他人的影响。

**Summary (发明总览)**:  
本发明通过HMD设备监测用户周围物理环境中的其他人的情绪和注意力状态，为用户提供态势感知。当检测到周围人因用户行为产生负面情绪或受到干扰时，系统会向用户发出视觉或音频警告，以提醒用户调整行为。系统还能够根据不同环境上下文（如公共场所或私人空间）调整检测标准，从而提供更精准的反馈。

**Key Innovation (核心创新)**:  
1. 通过HMD上的外向摄像头和麦克风阵列捕捉周围人的图像和声音数据，实现对物理环境的实时监测。
2. 基于音频数据和图像数据，使用情绪识别算法检测周围人的情绪状态（如烦恼或不满）。
3. 通过分析图像数据中的面部朝向、注视方向、身体姿态和手势，识别周围人是否对用户产生注意力或被用户行为分散注意力。
4. 系统能够识别周围人情绪或注意力变化的原因，并将其与用户行为关联，从而提供精准的反馈。
5. 根据不同环境上下文（如图书馆或火车站），系统采用不同的情绪和注意力检测阈值，以适应不同场景需求。
6. 当检测到周围人产生负面情绪或受到干扰时，系统会向用户发出视觉或音频警告，如"您的行为可能会打扰他人"，以提醒用户调整行为。
7. 本发明可应用于增强现实（AR）、虚拟现实（VR）以及混合现实（MR）场景，为用户提供更智能、更安全的沉浸式体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345982)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12718837)**
<br/><br/>

---


<br/>

### 20. 用于传感器位移相机的独立悬挂动态电气互连

**Title (EN)**: Dynamic electrical interconnects with separate suspension for sensor shift cameras  
**Pub. No.**: US12720179

**Applicant**: Apple Inc.  
**Inventor**: [Scott W Miller](https://patents.google.com/?inventor=Scott+W+Miller&assignee=Apple&country=US&num=100&sort=new), [Douglas S Brodie](https://patents.google.com/?inventor=Douglas+S+Brodie&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明涉及一种用于传感器位移相机的电气互连结构，其与悬挂挠性件物理分离，用于传输电源和/或图像传感器产生的高速数据，从而降低悬挂结构的复杂性。相机包括一个静态部分（例如相机的基座或平台的不动部分），其连接在一组柔性电气互连的一侧。移动部分（例如支撑图像传感器的移动平台或镜头）连接在柔性电气互连的另一侧。柔性电气互连可以在相机的静态部分和移动部分之间传输电源、图像数据信号和/或控制信号。在一些实施例中，悬挂（例如基于挠性的悬挂）与柔性电气互连在物理上是分开的。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485347460_1.jpg)

**Technical Field (技术领域)**:  
相机技术领域，具体涉及用于移动部件的电气信号和/或电源布线与悬挂功能分离的结构设计。

**Background (发明背景)**:  
现代移动设备如智能手机、平板电脑等集成了多种功能，其中相机是重要组成部分。相机中的一些组件需要移动以实现光学图像稳定（OIS）和自动对焦（AF）等功能。然而，将移动部件与非移动部件之间的电气连接进行可靠设计存在挑战，例如如何为移动的图像传感器提供足够的信号传输能力，以及如何为图像传感器和音圈马达（VCM）线圈提供电源和接地。

**Summary (发明总览)**:  
本发明提出了一种用于传感器位移相机的动态电气互连方案，通过将电气连接与悬挂功能分离来简化相机结构。该方案使用柔性电气互连在相机的静态部分和移动部分之间传输电源、图像数据和控制信号。这种设计不仅降低了悬挂结构的复杂性，还提高了信号传输的可靠性和效率。相较于传统方法，本发明通过物理分离电气连接和悬挂功能，解决了现有技术中电气连接易受机械运动影响的问题。

**Key Innovation (核心创新)**:  
1. 采用独立的柔性电气互连结构，将电气连接与悬挂功能物理分离，避免了传统设计中电气连接受机械运动影响的问题。
2. 通过在柔性电气互连中集成电源、数据信号和控制信号传输线路，实现了相机移动部件与非移动部件之间的高效电气连接。
3. 设计了多种非限制性的环形结构、尺寸、材料和运动方式，以适应不同相机型号和功能需求，提高了设计的通用性和可扩展性。
4. 优化了电气互连的横截面设计，增强了其在相机移动过程中的稳定性和耐用性。
5. 通过减少悬挂结构的复杂性，降低了相机整体重量和制造成本，同时提高了图像稳定性和对焦精度。
6. 该设计特别适用于需要高精度图像处理和高可靠性的移动设备相机，如智能手机和数码相机。
7. 应用于光学图像稳定（OIS）和自动对焦（AF）系统时，能够显著提升相机在动态环境下的成像质量。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485347460)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12720179)**
<br/><br/>

---


<br/>

### 21. 基于凝视的光学系统校准图案

**Title (EN)**: Gaze-based calibration patterns for optical systems  
**Pub. No.**: US12717404

**Applicant**: Apple Inc.  
**Inventor**: [Lionel E Edwin](https://patents.google.com/?inventor=Lionel+E+Edwin&assignee=Apple&country=US&num=100&sort=new), [Malcolm J Northcott](https://patents.google.com/?inventor=Malcolm+J+Northcott&assignee=Apple&country=US&num=100&sort=new), [Tom Sengelaub](https://patents.google.com/?inventor=Tom+Sengelaub&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
一种电子设备可包括投影仪、波导和桥接传感器。投影仪可生成校准图案并将其包含在提供给波导的图像光中。传感器可基于校准图案生成传感器数据，用于检测和校正光学错位。凝视追踪传感器可利用传输和反射的红外光生成凝视信息。凝视信息可包括凝视方向、盲点位置、眨眼信息以及/或眼跳信息。投影仪可将校准图案放置在图像光的视场中与凝视方向分离的位置，可将校准图案放置在盲点位置，可将校准图案与眨眼同步，以及/或将校准图案与眼跳同步。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485344397_1.jpg)

**Technical Field (技术领域)**:  
光学系统技术领域，具体涉及头戴式设备的光学校准和凝视追踪技术。

**Background (发明背景)**:  
头戴式设备通常包含显示器和其他光学组件。在使用过程中，组件可能因跌落或其他高应力事件而发生错位，这会影响设备性能。现有的光学校准方法难以在不影响用户体验的情况下有效检测和校正光学错位。

**Summary (发明总览)**:  
本发明提出了一种基于凝视的光学校准方案，通过在头戴式设备中集成投影仪、波导和桥接传感器，利用凝视追踪技术来检测光学错位并调整图像光。校准图案的显示位置和时机经过优化，以避免干扰用户的视觉体验，例如通过将校准图案放置在用户的盲点或与眨眼同步显示。这种方法能够在不影响用户体验的情况下实现光学系统的精确校准。

**Key Innovation (核心创新)**:  
1. 利用桥接传感器连接两个波导，实时检测光学错位并生成传感器数据。
2. 通过凝视追踪传感器获取用户的凝视方向、盲点位置、眨眼和眼跳信息，用于优化校准图案的显示位置和时机。
3. 将校准图案放置在用户的盲点位置或与用户的凝视方向分离，以避免干扰视觉体验。
4. 将校准图案的显示与用户的眨眼或眼跳同步，进一步降低可见性。
5. 采用红外光进行凝视追踪，确保在各种光线条件下都能准确获取用户的凝视信息。
6. 通过调整图像光来校正检测到的光学错位，实现动态校准。
7. 该技术可应用于增强现实（AR）眼镜和虚拟现实（VR）头戴设备，提升光学系统的稳定性和用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485344397)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12717404)**
<br/><br/>

---


<br/>

### 22. 电子设备的辅助视图渲染

**Title (EN)**: Rendering auxiliary views for an electronic device  
**Pub. No.**: US12717403

**Applicant**: Apple Inc.  
**Inventor**: [Borna Ghavam](https://patents.google.com/?inventor=Borna+Ghavam&assignee=Apple&country=US&num=100&sort=new), [Jay Mayur Khandhar](https://patents.google.com/?inventor=Jay+Mayur+Khandhar&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
头戴式设备可与电子设备配对。在远程渲染方案中，头戴式设备的内容由配对的电子设备渲染，并通过无线传输到头戴式设备进行显示。远程渲染将头戴式设备上显示操作的某些处理负担（因此也是功耗）转移到配对的电子设备上。在预渲染方案中，可为给定显示帧渲染虚拟内容的辅助视图。预渲染可以减轻由延迟引起的伪影。然而，预渲染可能需要额外的网络带宽。因此，只有在无线连接的网络强度足够时才执行预渲染。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485344396_1.jpg)

**Technical Field (技术领域)**:  
头戴式显示设备，远程渲染技术，辅助视图渲染

**Background (发明背景)**:  
头戴式设备通常配备近眼显示器，用于向用户呈现三维内容。然而，延迟可能导致图像伪影或用户不适。现有的远程渲染方案虽然可以分担处理负担，但难以完全解决延迟问题。预渲染技术可以缓解延迟问题，但需要更高的网络带宽，这限制了其在无线连接条件下的应用。

**Summary (发明总览)**:  
本发明提出了一种结合远程渲染和预渲染的混合渲染方案，通过根据无线连接强度动态调整渲染策略来优化头戴式设备的显示效果。在网络条件良好时，系统会渲染多个视角的辅助视图以减少延迟带来的伪影；而在网络条件较差时，则仅渲染单个主视角视图以节省带宽。此外，系统还集成了头戴式设备的姿态信息采集功能，以实现基于用户头部动作的动态内容渲染。

**Key Innovation (核心创新)**:  
1. 提出了基于无线连接强度的动态渲染策略，在网络条件良好时渲染多个辅助视图以减少延迟伪影，在网络条件较差时仅渲染主视角视图以节省带宽。
2. 通过集成头戴式设备的姿态传感器，实时采集用户头部姿态信息，并将其用于渲染视角的动态调整。
3. 设计了辅助视图的预渲染机制，在给定显示帧中为不同视角预先渲染内容，从而降低延迟对用户体验的影响。
4. 实现了远程电子设备与头戴式设备之间的无线传输优化，确保多视图内容的高效传输。
5. 在头戴式设备端集成了多视图内容展示功能，根据接收到的多个渲染视图动态调整显示内容。
6. 该技术特别适用于需要高沉浸感和低延迟的虚拟现实和增强现实应用场景，例如游戏和虚拟培训环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485344396)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12717403)**
<br/><br/>

---


<br/>

### 23. 变焦镜头及成像装置

**Title (EN)**: Zoom Lens and Imaging Apparatus  
**Pub. No.**: US20260244001

**Applicant**: Apple Inc.  
**Inventor**: [Masaharu Hosoi](https://patents.google.com/?inventor=Masaharu+Hosoi&assignee=Apple&country=US&num=100&sort=new), [Yoshikazu Shinohara](https://patents.google.com/?inventor=Yoshikazu+Shinohara&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本镜头系统提供了一种在低高度相机（镜头系统高度小于或等于6毫米）中的变焦功能（可变放大倍率），适用于手机等设备。该镜头系统包括至少三个可沿公共光轴移动的镜头组，每个镜头组与相应的致动器耦合。根据焦距或放大倍率变化请求，控制器向每个致动器发送相应信号，驱动相应的镜头组按相应距离和方向移动。各个可移动镜头组可移动不同的距离和方向。镜头系统的f值小于f/3.0。图像传感器上的图像聚焦功能正在描述中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485205755_1.jpg)

**Technical Field (技术领域)**:  
相机系统领域，具体涉及小型相机和镜头系统的放大技术。

**Background (发明背景)**:  
随着智能手机和平板电脑等小型移动多功能设备的发展，市场对高分辨率、小型化、轻量化且能拍摄低F值高画质图像的相机需求日益增加。然而，传统的小型相机受限于技术，难以达到大型高质量相机的分辨率和图像质量。小型相机实现更高分辨率通常需要使用小像素尺寸的光电传感器和紧凑的高质量成像镜头系统。尽管光电传感器技术进步显著，但随着其更加紧凑和强大，对具有改进成像质量性能的紧凑型成像镜头系统的需求也在增加。此外，市场对小型相机配备更高像素数和/或更大像素尺寸图像传感器（两者可能都需要更大的图像传感器）以及可变图像放大功能的需求也在增加，同时还要保持足够紧凑的模块高度以适应便携式电子设备。因此，光学系统设计面临的主要挑战是提供一种能够在小型相机的物理限制下捕获高亮度、高分辨率图像并具有可变放大功能的成像镜头系统。

**Summary (发明总览)**:  
本发明提出了一种适用于小型设备的折叠式变焦镜头系统，通过至少三个可移动镜头组沿光轴移动实现连续变焦功能。该系统采用致动器驱动镜头组移动，响应用户输入调整焦距，从而实现从78毫米到130毫米等效焦距的连续变化。镜头系统始终作为长焦镜头工作，在保持紧凑尺寸的同时提供高亮度、高分辨率的成像能力。

**Key Innovation (核心创新)**:  
1. 采用至少三个可移动镜头组，通过沿光轴的独立移动实现连续变焦功能，解决了传统小型相机难以实现高倍率变焦的问题。
2. 使用致动器精确控制镜头组移动，响应用户输入实现等效焦距在78毫米到130毫米之间的连续变化。
3. 镜头系统始终作为长焦镜头工作，在紧凑的模块高度（小于或等于6毫米）下提供高倍率和高质量成像能力。
4. 通过精确控制镜头组移动路径和距离，优化了变焦过程中的图像稳定性，减少了传统变焦系统常见的图像失真。
5. 镜头系统设计支持f值小于f/3.0，在低光照条件下也能提供高质量成像。
6. 该设计可应用于智能手机等便携式设备，在不增加设备厚度的情况下提供专业级变焦功能。
7. 适用于需要高分辨率、高亮度成像且对设备尺寸有严格限制的移动成像场景，如手机摄影和专业移动影像采集。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485205755)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244001)**
<br/><br/>

---


<br/>

### 24. 在环境中呈现和共享内容的方法

**Title (EN)**: METHODS FOR PRESENTING AND SHARING CONTENT IN AN ENVIRONMENT  
**Pub. No.**: US20260244267

**Applicant**: Apple Inc.  
**Inventor**: [Wesley M. HOLDER](https://patents.google.com/?inventor=Wesley+M.+HOLDER&assignee=Apple&country=US&num=100&sort=new), [Christopher D. MCKENZIE](https://patents.google.com/?inventor=Christopher+D.+MCKENZIE&assignee=Apple&country=US&num=100&sort=new), [Israel PASTRANA VICENTE](https://patents.google.com/?inventor=Israel+PASTRANA+VICENTE&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
在一些实施例中，电子设备在环境中呈现和共享内容。在一些实施例中，电子设备选择性地降低呈现内容的立体环境的显著性。在一些实施例中，电子设备修改用户界面中内容的边界。在一些实施例中，电子设备与立体环境中的用户共享内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206047_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及增强现实（AR）、混合现实（MR）和虚拟现实（VR）技术领域，具体涉及在三维环境中呈现和操作内容的方法和用户界面。

**Background (发明背景)**:  
近年来，增强现实计算机系统的发展显著增加，但现有方法在交互效率和用户体验方面存在不足。例如，与虚拟对象交互的系统反馈不足，操作复杂且容易出错，增加了用户的认知负担。此外，这些方法耗时较长，导致能源浪费，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种改进的电子设备交互方法，通过优化用户界面和交互方式，提升在三维环境中的内容呈现和共享体验。电子设备能够根据用户视线调整三维环境的显著性，动态调整内容边界以适应播放和移动状态，并提供直观的内容共享机制。这些改进减少了用户操作步骤，提高了交互效率，同时优化了设备能耗。

**Key Innovation (核心创新)**:  
1. 通过检测用户视线方向，电子设备能够选择性地降低三维环境的显著性，例如通过模糊或变暗处理，从而减少用户观看内容时的干扰，并在用户视线离开内容时恢复环境可见性。
2. 电子设备根据内容的播放和移动状态动态调整其边界形状，例如在播放时使用完整边界以显示全部内容，在暂停或移动时调整边界形状以避免与其他对象冲突。
3. 电子设备实现了内容边界形状功能，通过将内容移动到特定用户的位置来授权访问，从而无需用户手动选择界面元素即可实现高效的内容共享。
4. 系统通过减少用户输入次数和复杂度，例如自动调整环境显著性或边界形状，降低了用户操作错误的可能性，提升了交互效率。
5. 该方法特别适用于电池供电设备，通过减少不必要的计算和显示更新，延长了设备续航时间。
6. 在三维环境中，电子设备能够区分私有内容和共享内容，并通过用户动作控制访问权限，从而增强隐私和安全保护。
7. 这些创新特别适用于增强现实、混合现实和虚拟现实应用场景，为用户提供了更自然、直观的交互方式，提升了整体体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206047)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244267)**
<br/><br/>

---


<br/>

### 25. 基于异相图像处理的立体显示

**Title (EN)**: STEREOSCOPIC DISPLAY BASED ON OUT OF PHASE IMAGE PROCESSING  
**Pub. No.**: US20260246905

**Applicant**: APPLE INC.  
**Inventor**: [David R. Pope](https://patents.google.com/?inventor=David+R.+Pope&assignee=Apple&country=US&num=100&sort=new), [D. Amnon Silverstein](https://patents.google.com/?inventor=D.+Amnon+Silverstein&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明公开了一种系统、方法和计算机程序产品实施例，用于通过例如利用单个图像信号处理器（ISP）来捕获和显示异相图像帧。具体而言，对第一只眼睛的第一图像帧和第二只眼睛的第二图像帧的处理和显示是异相进行的。每个图像传感器可以在不同时间读取其图像。当一个图像传感器读取第一图像帧的像素时，另一个图像传感器曝光第二图像帧。单个ISP可以在图像传感器读取图像帧的像素时处理这些像素。单个ISP可以接收来自图像传感器的像素，处理这些像素以供显示，并将像素提供给相应的显示器。显示器也以异相方式运行。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485208952_1.jpg)

**Technical Field (技术领域)**:  
虚拟现实（VR）和增强现实（AR）技术领域，具体涉及立体显示中的图像处理和显示技术。

**Background (发明背景)**:  
虚拟现实（VR）和混合现实（MR）系统通过显示立体场景为用户提供沉浸式体验。然而，这些系统存在光子到光子的延迟问题，可能导致用户产生眼睛疲劳、头痛和恶心。此外，VR系统需要处理和显示大量图像数据，这会影响系统性能并增加成本。现有的解决方案通常需要为每只眼睛配备独立的图像处理管道，这增加了计算资源的需求。

**Summary (发明总览)**:  
本发明提出了一种利用单个ISP处理和显示异相图像帧的立体显示技术。通过让两个图像传感器在不同时间读取图像帧，并在读取一个图像帧的同时曝光另一个图像帧，单个ISP可以高效地处理图像数据。这种方法减少了计算资源的需求，降低了功耗，并优化了内存使用。此外，由于图像帧不是同时显示的，显示器也以异相方式运行，从而进一步降低了延迟。

**Key Innovation (核心创新)**:  
1. 利用单个ISP处理左右眼图像帧，通过异相读取和曝光图像帧，实现图像处理的流水线操作。
2. 在一个缓冲区中存储图像帧的像素行，并在读取一个图像帧的同时曝光另一个图像帧，从而优化内存使用。
3. 通过让ISP和图像传感器以相同的频率运行，确保图像读取和处理速率一致，减少缓冲区大小。
4. 采用异相显示技术，使左右眼显示器在不同时间显示图像帧，进一步降低光子到光子的延迟。
5. 通过减少同时进行的处理任务，均衡功耗分布，降低整体电流消耗，从而减小电源需求。
6. 该技术可应用于VR、MR或AR头戴式设备，通过减少延迟和功耗，提升用户体验并延长设备续航时间。
7. 特别适用于便携式设备，如智能眼镜或VR头盔，在保证性能的同时实现更紧凑的设计和更长的电池寿命。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485208952)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260246905)**
<br/><br/>

---


<br/>

### 26. 利用多电子设备图像增强色彩校正

**Title (EN)**: Enhancing Color Correction Using Images from Multiple Electronic Devices  
**Pub. No.**: US20260245267

**Applicant**: Apple Inc.  
**Inventor**: [Sivalogeswaran Ratnasingam](https://patents.google.com/?inventor=Sivalogeswaran+Ratnasingam&assignee=Apple&country=US&num=100&sort=new), [Anshul K. Jain](https://patents.google.com/?inventor=Anshul+K.+Jain&assignee=Apple&country=US&num=100&sort=new), [Anselm Grundhoefer](https://patents.google.com/?inventor=Anselm+Grundhoefer&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种头戴式设备的操作方法，包括收集传感器数据，基于收集的数据预测头戴式设备的姿态，根据预测的姿态确定设备朝向第一方向时，指示外部第一设备捕获第一图像；以及当预测的姿态朝向第二方向时，指示外部第二设备捕获第二图像。该方法还包括基于第一或第二图像对增强现实（AR）内容进行色彩校正，并将校正后的AR内容呈现在头戴式设备的透明显示器上。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485207148_1.jpg)

**Technical Field (技术领域)**:  
头戴式设备技术领域，具体涉及利用多设备图像进行色彩校正的增强现实系统。

**Background (发明背景)**:  
现有电子设备常配备透明显示器，可将图像呈现于用户眼前并允许用户看到周围环境。然而，这些设备在色彩校正和图像采集方面存在不足，难以根据用户视角动态调整AR内容色彩。本发明旨在解决这一问题，通过利用外部设备采集多视角图像来优化AR内容的色彩表现。

**Summary (发明总览)**:  
本发明提出了一种利用外部设备采集多视角图像来增强AR内容色彩校正的方法。通过预测头戴式设备的姿态，系统可指示外部设备（如耳机或手表）从不同方向采集图像，并基于这些图像对AR内容进行色彩校正。校正后的内容通过头戴式设备的透明显示器呈现，为用户提供更准确的色彩表现。本发明通过多设备协作和动态图像采集，显著提升了AR内容的视觉体验。

**Key Innovation (核心创新)**:  
1. 利用外部设备（如耳机或手表）上的摄像头从不同方向采集图像，扩展了图像采集的范围和视角。
2. 通过预测头戴式设备的姿态，动态指示外部设备采集图像，确保采集的图像与用户视角高度相关。
3. 基于采集的图像对AR内容进行色彩校正，使用户看到的虚拟内容与真实环境色彩更加匹配。
4. 采用全景图像拼接或三维场景建模技术，进一步提升色彩校正的准确性和场景适应性。
5. 支持多用户协作，通过无线接收其他用户设备采集的图像，确定头戴式设备的位置并优化色彩校正。
6. 引入多光谱数据采集，通过超过三种颜色滤镜的摄像头创建物理环境的三维反射率地图，提升色彩校正的精细度。
7. 本发明可应用于增强现实眼镜等设备，为用户提供更真实、更准确的虚拟内容显示，尤其适用于需要高精度色彩表现的应用场景，如虚拟试穿或远程协作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485207148)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260245267)**
<br/><br/>

---


<br/>

### 27. 基于网络的网页内容显示方法

**Title (EN)**: DISPLAYING WEB-BASED CONTENT  
**Pub. No.**: US20260244461

**Applicant**: Apple Inc.  
**Inventor**: [Jonathan R. DASCOLA](https://patents.google.com/?inventor=Jonathan+R.+DASCOLA&assignee=Apple&country=US&num=100&sort=new), [Deena KHATTAB](https://patents.google.com/?inventor=Deena+KHATTAB&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明主要涉及对内容显示方式的改变。一些技术用于根据某些实施例按顺序显示内容片段。其他技术用于根据内容不同显示不同的内容控制选项。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206261_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及网页内容显示优化和用户交互界面改进。

**Background (发明背景)**:  
电子设备通常从多种来源接收内容，这些内容可能包含难以阅读的格式或无关信息，例如网页中的广告内容。现有的内容显示方法通常复杂且效率低下，导致用户时间和设备能耗的浪费，尤其对电池供电设备影响较大。因此，需要改进内容显示技术以解决这些问题。

**Summary (发明总览)**:  
本发明提供了一种更快速、更高效的内容显示方法，通过优化用户界面来减少用户认知负担并提升人机交互效率。该方法通过分步显示内容片段并提供相应的控制选项，使用户能够更灵活地浏览和管理内容，从而节省时间和设备能耗。

**Key Innovation (核心创新)**:  
1. 通过分步显示内容片段，用户可以逐步浏览网页内容，避免一次性加载过多信息，提升阅读效率。
2. 提供动态调整的用户界面元素，根据用户输入显示或隐藏特定内容，例如广告或附加信息，使用户界面更简洁。
3. 采用模块化用户界面设计，将不同类型的内容（如正文、广告、导航栏）分离，用户可以选择性地显示或隐藏这些模块。
4. 通过检测用户输入并实时更新显示内容，减少不必要的界面刷新和资源消耗，延长电池供电设备的续航时间。
5. 提供可定制的用户界面选项，允许用户根据个人偏好调整内容显示方式，例如字体大小、颜色主题等，提升用户体验。
6. 通过优化用户交互流程，减少用户操作步骤，例如将多步操作简化为单次点击，提高操作效率。
7. 本发明可应用于网页浏览器、电子书阅读器等设备，尤其适用于需要长时间阅读或浏览内容的场景，能有效提升用户舒适度和设备续航能力。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206261)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244461)**
<br/><br/>

---


<br/>

### 28. e-SIM传输操作的增强方法

**Title (EN)**: Enhancements to e-SIM Transfer Operations  
**Pub. No.**: US20260246637

**Applicant**: Apple Inc.  
**Inventor**: [Li LI](https://patents.google.com/?inventor=Li+LI&assignee=Apple&country=US&num=100&sort=new), [Aurelien P RABOISSON](https://patents.google.com/?inventor=Aurelien+P+RABOISSON&assignee=Apple&country=US&num=100&sort=new), [Hyewon LEE](https://patents.google.com/?inventor=Hyewon+LEE&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
一种装置，用于基于从用户设备（UE）接收的信号处理导出选定嵌入式用户身份模块（e-SIM）配置文件的请求，该请求包括与选定e-SIM配置文件对应的集成电路卡识别码（ICCID）和与ICCID对应的目标加密令牌，确定存储在装置上的e-SIM配置文件对应于ICCID且符合导出条件，生成与ICCID对应的交易识别码（TID）和源加密令牌，并为传输到UE生成包含ICCID、TID、源加密令牌和目标加密令牌的源加密签名。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485208657_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及嵌入式用户身份模块（e-SIM）技术，具体为e-SIM配置文件的导出和传输方法。

**Background (发明背景)**:  
随着e-SIM在用户设备中的普及，用户在更换设备时面临e-SIM迁移的挑战。传统物理SIM卡可以通过物理方式更换，而e-SIM则需要通过软件和信号传输实现迁移。现有的e-SIM传输方法用户体验有待提升。本发明旨在解决e-SIM在用户设备间传输时的操作复杂性和安全性问题。

**Summary (发明总览)**:  
本发明提供了一种改进的e-SIM传输方法，通过在用户设备间直接传输e-SIM配置文件来简化迁移过程。该方法包括生成交易识别码和加密令牌以确保传输安全，并使用加密签名机制验证传输请求的合法性。本发明无需网络介入即可实现e-SIM在用户设备间的安全传输，提供了更便捷的用户体验。

**Key Innovation (核心创新)**:  
1. 通过集成ICCID和加密令牌生成源加密签名，确保e-SIM传输请求的完整性和安全性。
2. 在用户设备间直接生成和传输绑定配置文件包（BPP），无需网络介入，简化了传输流程。
3. 使用交易识别码（TID）跟踪e-SIM传输过程，防止重复传输和篡改。
4. 在eUICC中实现e-SIM配置文件的导出功能，支持在用户设备间安全传输e-SIM。
5. 通过验证源加密签名和目标加密签名，确保传输过程中数据的真实性和完整性。
6. 支持在禁用状态下导出e-SIM配置文件，增强了传输过程的安全性。
7. 本发明可应用于5G NR网络及其他蜂窝网络，为用户设备升级和e-SIM迁移提供了一种高效、安全的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485208657)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260246637)**
<br/><br/>

---


<br/>

### 29. 多设备操作中的领导者选举

**Title (EN)**: LEADER ELECTION FOR MULTI-DEVICE OPERATIONS  
**Pub. No.**: US20260247130

**Applicant**: Apple Inc.  
**Inventor**: [Siva Ganesh Movva](https://patents.google.com/?inventor=Siva+Ganesh+Movva&assignee=Apple&country=US&num=100&sort=new), [Michael C. Laster](https://patents.google.com/?inventor=Michael+C.+Laster&assignee=Apple&country=US&num=100&sort=new), [Emmanuel Lalande](https://patents.google.com/?inventor=Emmanuel+Lalande&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本技术包括检测与第一电子设备相关联的一个或多个电子设备的标识符。此外，该技术包括访问一组电子设备的设备属性集合，该集合包括所述一个或多个电子设备。该技术还包括访问与所述一个或多个电子设备对应的设备属性子集。此外，该技术包括将设备属性子集与一个或多个群组标准进行比较，其中设备属性可包括设备类型、软件版本、功率容量、充电状态和活动状态中的至少一个。同时，该技术包括将第一电子设备指定为所述一个或多个电子设备的群组领导者设备或电子设备群组的非领导者设备。此外，该技术包括执行预定操作或延迟预定操作。该技术可以作为方法、计算机程序产品、非易失性计算机可读介质以及包含一个或多个存储器和一个或多个与存储器通信的处理器组成的计算设备来实现。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485209199_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及电子设备群组管理技术，具体涉及多设备协作中的领导者选举和任务分配。

**Background (发明背景)**:  
电子设备通常会执行诸如共享位置数据、报告标识符以帮助定位丢失设备以及共享照片等预定任务。这些任务可能存在冗余，例如群组中的设备可能会重复检测并报告所有其他群组成员的标识符。这种冗余意味着设备会浪费电力和计算资源在不必要的任务上。此外，服务器资源也被用于处理和存储重复的信息。因此，改进电子设备群组执行预定任务的方式是有必要的。

**Summary (发明总览)**:  
本发明提出了一种通过群组内电子设备协商和选举领导者来代表群组执行预定任务的方法。设备会检索其他设备的属性，如设备类型、功率容量、充电状态和活动状态，并基于这些属性选择群组领导者。例如，设备可能会选择正在充电的设备作为领导者以节省群组的电池容量。群组成员身份是动态的，设备可以根据群组组成或属性的变化选择不同的领导者。通过选举群组领导者，非领导者设备可以延迟或停止执行预定任务，从而节省电力和计算资源，同时减少服务器的处理负担。

**Key Innovation (核心创新)**:  
1. 通过检测设备标识符和访问设备属性集合，实现对群组内设备的识别和属性获取。
2. 基于设备属性（如设备类型、功率容量、充电状态和活动状态）进行群组领导者选举，确保领导者具备最佳条件。
3. 动态调整群组成员身份和领导者选举，适应群组组成或设备属性的变化。
4. 通过延迟或停止非领导者设备的预定任务，减少设备间的冗余操作，节省电力和计算资源。
5. 减少服务器处理和存储重复信息的负担，提高服务器资源利用效率。
6. 实施群组领导者选举机制后，服务器可以以更低的处理功率、内存和电力消耗执行预定任务。
7. 本发明适用于智能设备群组管理场景，例如家庭智能设备群组或可穿戴设备群组，可有效优化设备协作效率和资源利用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485209199)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260247130)**
<br/><br/>

---


<br/>

### 30. 在多用户通信会话中保持远程用户三维环境视觉表示的一致性

**Title (EN)**: MAINTAINING VISUAL CONSISTENCY OF VISUAL REPRESENTATIONS OF REMOTE USERS IN THREE-DIMENSIONAL ENVIRONMENTS WITHIN MULTI-USER COMMUNICATION SESSIONS  
**Pub. No.**: US20260245312

**Applicant**: Apple Inc.  
**Inventor**: [Gabrielle ECANOW](https://patents.google.com/?inventor=Gabrielle+ECANOW&assignee=Apple&country=US&num=100&sort=new), [Jiwoo JANG](https://patents.google.com/?inventor=Jiwoo+JANG&assignee=Apple&country=US&num=100&sort=new), [Tommy ROCHETTE](https://patents.google.com/?inventor=Tommy+ROCHETTE&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明涉及用于在包含一组共处一地用户的多用户通信会话中保持一个或多个远程用户在三维环境中的视觉表示一致性的系统和方法。本发明还涉及用于在多用户通信会话中将远程用户的视觉表示从虚拟平铺图转换为三维化身的系统和方法。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485207199_1.jpg)

**Technical Field (技术领域)**:  
本专利属于多用户通信技术领域，具体涉及三维环境中的用户视觉表示管理。

**Background (发明背景)**:  
现有计算机图形环境提供二维和/或三维虚拟环境，用户可以通过设备进行交互。在多用户通信会话中，非共处一地用户通常以虚拟化身形式显示在三维环境中。然而，现有技术难以在共处一地用户与远程用户共存的情况下，保持视觉表示的一致性和空间布局的合理性。

**Summary (发明总览)**:  
本发明提出了一种在多用户通信会话中管理远程用户三维视觉表示的方法。通过检测优先级数据的变化，系统能够动态调整远程用户虚拟表示的空间布局，确保视觉一致性。同时，系统支持将远程用户的虚拟表示从平铺图转换为三维化身，并基于其原有位置确定新三维表示的位置，从而实现更自然的交互体验。

**Key Innovation (核心创新)**:  
1. 通过检测优先级数据的变化，动态调整远程用户虚拟表示在三维环境中的空间布局，确保视觉一致性。
2. 在检测到优先级数据变化后，系统根据预设标准决定是否更新远程用户虚拟表示的空间布局，并同步更新其他共处一地设备的显示。
3. 支持将远程用户的虚拟表示从平铺图转换为三维化身，并基于其原有位置确定新三维表示的位置，实现更自然的交互体验。
4. 通过共处一地设备之间的数据传输，确保所有用户对远程用户视觉表示的更新保持同步。
5. 提供基于用户输入的触发机制，允许远程用户主动请求将自身表示转换为三维化身。
6. 系统能够根据用户优先级数据的变化，智能调整三维环境中虚拟表示的排列方式，优化空间利用率。
7. 本发明可应用于虚拟会议、协作平台等场景，为远程用户和共处一地用户提供更一致和沉浸式的三维交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485207199)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260245312)**
<br/><br/>

---


<br/>

### 31. 用于处理用户输入的手部参与状态技术

**Title (EN)**: Techniques for Utilizing a Hand Engagement State for Processing User Input  
**Pub. No.**: US20260244279

**Applicant**: Apple Inc.  
**Inventor**: [Ashwin Kumar Asoka Kumar Shenoi](https://patents.google.com/?inventor=Ashwin+Kumar+Asoka+Kumar+Shenoi&assignee=Apple&country=US&num=100&sort=new), [Julian K. Shutzberg](https://patents.google.com/?inventor=Julian+K.+Shutzberg&assignee=Apple&country=US&num=100&sort=new), [Leah M. Gum](https://patents.google.com/?inventor=Leah+M.+Gum&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明涉及管理参与区域的技术，包括系统跟踪用户的手部并确定用户手部的高度是否满足第一阈值高度。在确定用户手部的高度满足第一阈值高度后，系统启动用户界面参与状态，并在该状态下监控用户输入，通过检测手部跟踪期间的用户动作来确定用户输入。阈值高度与用户界面参与区域的边界相关联，并可根据用户活动进行调整。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206062_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及扩展现实(XR)环境中的手部跟踪和用户界面交互技术。

**Background (发明背景)**:  
现有扩展现实(XR)系统能够生成和呈现虚拟环境，用户可通过手势与虚拟对象交互。然而，现有技术在手部跟踪和交互区域管理方面存在不足，难以准确识别用户意图并优化交互体验。本发明旨在解决如何更智能地管理手部参与区域以提升用户交互效率的问题。

**Summary (发明总览)**:  
本发明提出了一种基于手部参与状态的用户界面交互管理方案，通过动态调整参与区域边界来优化用户输入体验。系统首先识别用户手部进入参与区域以表达交互意图，然后在交互状态下跟踪手部动作以识别用户输入，最后通过手部离开参与区域或进入休息姿态来结束交互。本发明通过动态调整参与区域边界，减少了用户从休息状态到交互状态所需的移动量，从而提升了用户与电子系统交互的便捷性。

**Key Innovation (核心创新)**:  
1. 引入参与区域概念，通过检测手部高度判断用户交互意图，实现更精准的交互状态识别。
2. 采用动态调整参与区域边界的技术，根据用户活动状态（如休息姿态）自适应修改边界，提升交互灵活性。
3. 在交互状态下，系统持续跟踪手部或眼部动作以识别用户输入，确保交互的准确性和实时性。
4. 通过检测手部休息姿态作为退出交互状态的触发条件，避免误判用户意图。
5. 参与区域边界可根据用户活动动态调整，例如在用户手部休息时降低边界高度，减少交互所需的移动量。
6. 本发明可应用于头戴式显示器、智能手机等设备，为XR环境中的用户交互提供更自然和高效的方式。
7. 通过减少用户从休息到交互的过渡时间，提升了整体用户体验，特别适用于需要频繁交互的XR应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206062)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244279)**
<br/><br/>

---


<br/>

### 32. 基于邻近性的第三方应用凭证操作

**Title (EN)**: PROXIMITY-BASED CREDENTIAL OPERATIONS FOR THIRD PARTY APPLICATION  
**Pub. No.**: US20260246633

**Applicant**: Apple Inc.  
**Inventor**: [Sunil Nair](https://patents.google.com/?inventor=Sunil+Nair&assignee=Apple&country=US&num=100&sort=new), [Alexander D. Pelletier](https://patents.google.com/?inventor=Alexander+D.+Pelletier&assignee=Apple&country=US&num=100&sort=new), [Rahul Narayan Singh](https://patents.google.com/?inventor=Rahul+Narayan+Singh&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本申请涉及用于向用户设备配置凭证的设备、组件、系统和方法。在某些实施例中，可检测到与凭证对应的物理对象位于用户设备的邻近范围内，以实现凭证的配置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485208653_1.jpg)

**Technical Field (技术领域)**:  
数据安全领域，具体涉及用户设备上存储的凭证相关机密信息的保护技术。

**Background (发明背景)**:  
随着用户设备的发展，设备上的应用程序能够处理更多任务，这些应用程序需要管理用户凭证并帮助用户执行任务。然而，管理多个应用程序的凭证存在挑战，尤其是需要满足高安全级别并避免违规处罚。此外，在每个应用程序中重复实现高安全级别的代码会占用宝贵的内存资源。

**Summary (发明总览)**:  
本发明提出了一种通过用户设备上的邻近性验证功能来配置凭证的解决方案。该方案通过一个专门的配置应用程序来管理第三方应用的凭证安全，避免第三方应用直接访问敏感信息。配置过程中，用户通过物理对象（如卡片）与设备进行交互，触发验证流程，从而实现凭证的安全配置。这种方法不仅提高了安全性，还减少了第三方应用对高安全级别代码的重复实现，节省了内存。

**Key Innovation (核心创新)**:  
1. 通过专门的配置应用程序管理第三方应用的凭证安全，防止第三方应用直接访问敏感信息。
2. 采用"点击验证"功能，用户通过物理对象与设备交互，触发凭证配置流程。
3. 配置应用程序在验证过程中接管屏幕显示，防止第三方应用在验证期间访问设备接收的数据。
4. 利用设备上的安全元件（如安全芯片）来验证物理对象的存在并检索相关信息，确保验证过程的安全性。
5. 通过集中管理高安全级别的代码，配置应用程序减少了第三方应用对重复代码的需求，节省了设备内存。
6. 该方案支持金融账户等高安全级别凭证的配置，确保符合监管要求和行业标准。
7. 应用于移动支付、身份验证等场景，为用户设备提供更安全、更便捷的凭证管理方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485208653)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260246633)**
<br/><br/>

---


<br/>

### 33. 基于运动的用户界面系统和方法

**Title (EN)**: SYSTEMS AND METHODS OF MOTION-BASED USER INTERFACES  
**Pub. No.**: US20260244307

**Applicant**: Apple Inc.  
**Inventor**: [Ioana NEGOITA](https://patents.google.com/?inventor=Ioana+NEGOITA&assignee=Apple&country=US&num=100&sort=new), [Ian PERRY](https://patents.google.com/?inventor=Ian+PERRY&assignee=Apple&country=US&num=100&sort=new), [Trent A. GREENE](https://patents.google.com/?inventor=Trent+A.+GREENE&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明的一些示例涉及根据电子设备的检测运动来移动三维环境中的虚拟物体的系统和方法。在一些示例中，电子设备检测针对用户界面元素的输入。在一些示例中，响应于检测到输入，电子设备根据用户界面元素执行操作。在一些示例中，响应于检测到输入，电子设备放弃执行根据用户界面元素的操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206092_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及三维环境中的用户界面显示技术，具体涉及调整三维环境中用户界面元素的运动。

**Background (发明背景)**:  
现有的计算机图形环境提供二维和/或三维环境，其中呈现给用户观看的对象是虚拟的并由计算机生成。一些对象是计算机物理环境中真实物体的表示。当检测到计算机移动时，电子设备会移动这些真实物体的表示，以模拟物理环境中的运动。然而，现有技术难以在用户移动设备时保持虚拟物体与用户的相对位置关系，导致虚拟物体在三维环境中的运动不够自然。

**Summary (发明总览)**:  
本发明提出了一种根据电子设备的运动模式调整三维环境中虚拟物体运动的方法。电子设备通过检测用户运动（如行走、慢跑、跑步等）来调整虚拟物体的位置，以模拟虚拟物体跟随用户的效果。同时，通过应用不同的校正因子来减少虚拟物体在设备移动时出现的弹跳现象，从而实现更自然的运动模拟。本发明还支持多种物体锁定方式，如世界锁定、身体锁定、倾斜锁定和头部锁定，以适应不同的用户需求和使用场景。

**Key Innovation (核心创新)**:  
1. 通过检测电子设备的运动模式（如行走、跑步等），动态调整三维环境中虚拟物体的位置和运动轨迹。
2. 应用校正因子来减少虚拟物体在设备移动时出现的弹跳现象，例如针对行走和跑步分别采用不同的校正策略。
3. 支持多种物体锁定方式，包括世界锁定、身体锁定、倾斜锁定和头部锁定，以适应不同的用户需求和使用场景。
4. 倾斜锁定模式下，虚拟物体根据用户头部倾斜角度在三维空间中以极坐标方式移动，保持与用户的相对距离不变。
5. 身体锁定模式下，虚拟物体与用户身体保持固定距离和方向偏移，不受用户头部或身体滚动方向变化的影响。
6. 头部锁定模式下，虚拟物体与用户头部保持固定距离和方向偏移，随着用户头部的移动而移动。
7. 本发明可应用于增强现实（AR）和虚拟现实（VR）设备，为用户提供更自然、更沉浸的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206092)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244307)**
<br/><br/>

---


<br/>

### 34. 用于色彩校正的自适应成像

**Title (EN)**: ADAPTIVE IMAGING FOR COLOR CORRECTION  
**Pub. No.**: US20260244021

**Applicant**: Apple Inc.  
**Inventor**: [Sivalogeswaran RATNASINGAM](https://patents.google.com/?inventor=Sivalogeswaran+RATNASINGAM&assignee=Apple&country=US&num=100&sort=new), [Anshul K. JAIN](https://patents.google.com/?inventor=Anshul+K.+JAIN&assignee=Apple&country=US&num=100&sort=new), [Ashirwad BAHUKHANDI](https://patents.google.com/?inventor=Ashirwad+BAHUKHANDI&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明涉及用于色彩校正的自适应成像技术，例如在混合现实和/或增强现实系统中高效提供虚拟内容的准确色彩表示。自适应成像包括基于要显示的虚拟内容信息以及虚拟内容将被显示的物理环境信息，调整传感器的一个或多个操作特性。该自适应成像可以利用人类视觉系统在周边区域对色彩的较低敏感性，更高效地执行色彩校正操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485205776_1.jpg)

**Technical Field (技术领域)**:  
本专利属于电子设备领域，具体涉及增强现实和混合现实系统中的自适应成像色彩校正技术。

**Background (发明背景)**:  
电子设备常用于在现实世界的视图上叠加虚拟内容，以创建混合现实或增强现实场景。然而，现有技术难以在虚拟内容与物理环境色彩交互时提供准确的色彩校正，尤其在透明或光学透视显示器上表现不足。本发明旨在解决这一问题，通过自适应调整物理环境图像的捕获方式，提高色彩校正的效率和准确性。

**Summary (发明总览)**:  
本发明提出了一种自适应成像方法，通过调整图像捕获方式以优化色彩校正效果。其核心思路是根据虚拟内容特性和物理环境特性，动态调整图像捕获参数，例如采用中央区域高分辨率和周边区域低分辨率的捕获方式，或在中央区域进行彩色捕获而在周边区域进行单色或减色捕获。这种方法利用了人眼对周边色彩敏感度较低的特性，提高了色彩校正的效率，同时减少计算资源消耗。与现有技术相比，本发明在增强现实和混合现实应用中提供了更高效、更精准的色彩校正方案。

**Key Innovation (核心创新)**:  
1. 采用自适应中央周边成像技术，通过在图像传感器中央区域进行高分辨率彩色捕获，而在周边区域进行低分辨率或单色捕获，优化色彩校正效率。
2. 实现自适应帧率控制，在中央区域使用高帧率捕获以捕捉快速变化，而在周边区域使用低帧率捕获以节省计算资源。
3. 通过传感器内部分区读取（in-sensor binning）技术，实现基于人眼中央凹视觉特性的自适应图像捕获。
4. 提供时间自适应图像捕获机制，交替捕获高保真和低保真帧，以及彩色和单色帧，以平衡色彩校正精度和系统性能。
5. 根据虚拟内容特性和物理环境特性动态调整捕获参数，例如根据虚拟对象色彩和物理背景色彩变化调整捕获策略。
6. 将自适应成像技术应用于增强现实和混合现实系统，通过更高效的色彩校正提升用户体验，特别是在透明显示器或光学透视显示器上。
7. 适用于头戴式设备、智能手机、平板电脑等设备，为虚拟内容与物理环境交互提供更精准的色彩表现。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485205776)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244021)**
<br/><br/>

---


<br/>

### 35. 用于相机的万向节和形状记忆合金致动器

**Title (EN)**: Gimbal and shape memory alloy actuator for camera  
**Pub. No.**: US12713130

**Applicant**: Apple Inc.  
**Inventor**: [Qiang Yang](https://patents.google.com/?inventor=Qiang+Yang&assignee=Apple&country=US&num=100&sort=new), [Yu-Min Lee](https://patents.google.com/?inventor=Yu-Min+Lee&assignee=Apple&country=US&num=100&sort=new), [Aurelien R Hubert](https://patents.google.com/?inventor=Aurelien+R+Hubert&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
本发明涉及一种相机系统，其包含一个致动器装置，用于实现自动对焦（AF）和/或光学图像稳定（OIS）运动。在各种实施例中，该致动器装置可包括一个或多个形状记忆合金（SMA）致动器。例如，相机系统可包括一个AF SMA致动器，该致动器由多个SMA导线组成，用于相对于相机系统的图像传感器沿光学轴方向移动相机系统的镜头组。在某些实施例中，相机系统可包括一个OIS致动器，用于使镜头组连同图像传感器一起绕垂直于光学轴的多个轴倾斜。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485066058_1.jpg)

**Technical Field (技术领域)**:  
相机技术领域，涉及自动对焦（AF）和光学图像稳定（OIS）技术，具体为使用形状记忆合金（SMA）致动器的相机系统。

**Background (发明背景)**:  
随着智能手机和平板电脑等小型移动多功能设备的普及，对高分辨率、小型化相机的需求日益增加。现有的小型相机可能采用光学图像稳定（OIS）机制，通过调整光学镜头在X轴和/或Y轴上的位置来感应并响应外部扰动，以补偿镜头的不必要运动。此外，一些小型相机采用自动对焦（AF）机制，通过沿相机光学轴移动光学镜头来调整物距，从而在图像传感器上清晰成像。然而，现有技术中AF和OIS的实现方式可能存在结构复杂、响应速度慢或能耗高等问题。

**Summary (发明总览)**:  
本发明提出了一种基于形状记忆合金（SMA）的相机致动系统，旨在实现更高效、更紧凑的自动对焦（AF）和光学图像稳定（OIS）功能。该系统利用SMA导线作为致动器，通过其形状记忆特性驱动镜头组进行精确运动。相较于传统机械致动器，SMA致动器具有结构简单、响应速度快和能耗低的特点。本发明通过优化SMA导线的配置和控制系统，实现了AF和OIS功能的集成，为小型相机提供了更优的解决方案。

**Key Innovation (核心创新)**:  
1. 采用形状记忆合金（SMA）导线作为致动器，通过其形状记忆特性实现镜头组的精确移动。
2. 设计了多根SMA导线协同工作的结构，以实现镜头组沿光学轴的自动对焦（AF）运动。
3. 开发了一种OIS致动器，通过倾斜镜头组和图像传感器来补偿外部扰动，从而实现多轴光学图像稳定。
4. SMA致动器的结构简单且紧凑，适用于小型化相机系统，有助于减小设备尺寸。
5. SMA致动器具有快速响应和低能耗的特点，提升了相机系统的整体性能。
6. 通过优化SMA导线的配置和控制算法，实现了AF和OIS功能的集成，提供了更优的用户体验。
7. 本发明特别适用于智能手机、平板电脑等便携式设备，能够在有限的空间内提供高质量的成像稳定性和对焦精度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485066058)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12713130)**
<br/><br/>

---


<br/>

### 36. 力输入处理和动态力阈值

**Title (EN)**: Force input processing and dynamic force thresholds  
**Pub. No.**: US12710323

**Applicant**: Apple Inc.  
**Inventor**: [David S. Graff](https://patents.google.com/?inventor=David+S.+Graff&assignee=Apple&country=US&num=100&sort=new), [Ananta Palani](https://patents.google.com/?inventor=Ananta+Palani&assignee=Apple&country=US&num=100&sort=new), [Amsal Jindani](https://patents.google.com/?inventor=Amsal+Jindani&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
一种电子设备包括与多个力传感器耦合的感测电路，用于感测一个或多个参数。处理电路与感测电路耦合，编程用于将多个电极感测到的参数组合成对应于施加在电子设备表面上的力的组合参数，并根据满足一个或多个第一标准来检测力输入，例如点击事件，其中第一标准包括当组合参数大于或等于第一阈值时满足的条件。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485062957_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及触摸和力敏感表面输入设备中的力输入检测和处理技术。

**Background (发明背景)**:  
现有的输入设备如按钮、鼠标、触摸传感器面板和触控笔等在计算系统中被广泛使用。触摸传感器面板因其操作简便和价格优势而特别受欢迎。然而，现有技术对力输入的检测精度和响应速度存在不足，难以适应复杂的使用场景和动态变化的需求。本发明旨在解决力输入检测的准确性和响应灵活性问题。

**Summary (发明总览)**:  
本发明提出了一种用于力输入检测的电子设备及其处理方法。设备通过多个力传感器感测施加的力，并结合处理电路将感测到的参数整合为反映施加力的组合参数。处理电路根据动态调整的阈值检测点击和未点击事件，并利用状态机管理操作状态之间的转换。设备还提供与状态变化相对应的触觉、听觉或视觉反馈，从而实现更准确和灵敏的力输入检测。

**Key Innovation (核心创新)**:  
1. 采用多个力传感器和电极阵列，精确感测施加在设备上的力分布，实现更全面的力输入检测。
2. 通过处理电路将多个电极感测到的参数整合为组合参数，简化力输入信号处理流程。
3. 引入动态阈值调整机制，根据环境条件和用户交互模式实时调整点击和未点击事件的判定阈值，提高检测的灵活性和适应性。
4. 利用力状态机管理操作状态转换，确保力输入事件处理的连续性和稳定性。
5. 提供与状态变化对应的触觉、听觉或视觉反馈，增强用户交互体验。
6. 该技术可应用于触控笔、触摸板等输入设备，尤其适用于需要高精度力输入检测的场景，如绘图、签名验证等。
7. 通过提高力输入检测的准确性和响应速度，本发明能够显著改善用户与电子设备之间的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485062957)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12710323)**
<br/><br/>

---


<br/>

### 37. 具有局部闪烁检测功能的头戴式电子设备

**Title (EN)**: Head-mounted electronic device with localized flicker detection  
**Pub. No.**: US12713140

**Applicant**: Apple Inc.  
**Inventor**: [Anselm Grundhoefer](https://patents.google.com/?inventor=Anselm+Grundhoefer&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
本发明提供了一种电子设备，包括用于获取场景图像的外部摄像头、用于显示所获取图像的显示器，以及控制电路。控制电路用于识别图像中的候选区域，该区域可能包含局部光源，确定候选区域是否表现出闪烁模式，并通过调整外部摄像头的曝光时间来减轻显示器上由局部光源引起的闪烁。该设备还可以包括用于感应一个或多个主要闪烁频率的闪烁传感器、用于从场景中获取深度信息的深度传感器、执行语义分割的场景理解子系统，以及用于输出与电子设备相关的运动和位置信息的运动和位置确定子系统。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485066069_1.jpg)

**Technical Field (技术领域)**:  
头戴式设备技术领域，具体涉及图像处理和闪烁检测技术。

**Background (发明背景)**:  
头戴式设备通常配备摄像头以获取外部环境的实时视频流，并通过显示器呈现给用户。外部环境中可能存在多个光源，每个光源具有不同的调制频率。当处理包含多个光源的场景时，显示内容可能会出现闪烁问题。现有的技术难以有效处理这种复杂的光源环境，容易导致显示内容出现图像伪影。

**Summary (发明总览)**:  
本发明提出了一种用于头戴式设备的操作方法，通过外部摄像头获取场景图像，识别可能包含光源的候选区域，并判断该区域是否表现出闪烁模式。通过调整摄像头的曝光时间，本发明能够减轻由局部光源引起的图像闪烁问题。此外，本发明还结合了深度信息、语义分割和运动位置信息，以更准确地识别和处理闪烁源。本发明相较于现有技术，能够更智能地识别和处理局部闪烁问题，提升用户体验。

**Key Innovation (核心创新)**:  
1. 通过外部摄像头获取图像并识别可能包含光源的候选区域，利用深度信息辅助定位光源位置。
2. 通过分析图像帧的曝光时间、帧率和行读取速度，计算候选区域中光源的闪烁频率。
3. 结合语义分割技术，识别图像中的电子显示屏或投影屏幕等特定区域，提高闪烁检测的准确性。
4. 利用闪烁传感器检测场景中的主要闪烁频率，并区分局部光源和主要光源的闪烁特性。
5. 基于运动和位置信息，对候选区域进行跟踪和确认，确保在连续帧中准确识别同一光源。
6. 通过调整摄像头的曝光时间，有效减轻由局部光源引起的图像闪烁问题，同时避免对非闪烁区域产生负面影响。
7. 本发明可应用于增强现实（AR）眼镜等头戴式设备，在复杂光源环境下提供更清晰、无闪烁的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485066069)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12713140)**
<br/><br/>

---



**Total Patents**: 37  
**Last Updated**: 20260829

---

The Patent Scoop Trio
