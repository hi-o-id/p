---
layout: post
title: "其他专利小快报 2026-09-12"
date: 2026-09-12 18:49:12 +0800
categories: 其他
---

**New Patents**: 32  

---


<br/>

### 1. 基于生成对抗网络的设备端图像生成

**Title (EN)**: ON-DEVICE IMAGE GENERATION WITH GENERATIVE ADVERSARIAL NETWORKS  
**Pub. No.**: US20260268441

**Applicant**: Google LLC  
**Inventor**: [Haolin Jia](https://patents.google.com/?inventor=Haolin+Jia&country=US&num=100&sort=new), [Qifei Wang](https://patents.google.com/?inventor=Qifei+Wang&country=US&num=100&sort=new), [Omer Tov](https://patents.google.com/?inventor=Omer+Tov&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明涉及使用机器学习模型生成图像的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。例如，系统可以使用生成神经网络执行低延迟的设备端图像生成。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617561_1.jpg)

**Technical Field (技术领域)**:  
人工智能图像生成技术，具体涉及设备端生成对抗网络（GAN）架构设计及训练方法。

**Background (发明背景)**:  
机器学习模型，特别是神经网络，已被广泛用于图像生成任务。然而，现有技术中的神经网络通常需要大量计算资源，难以在边缘设备上实时运行。此外，复杂模型在资源受限设备上的部署会导致高延迟和高能耗。本发明旨在解决如何在保持高图像质量的同时，降低计算复杂度并实现设备端实时图像生成的问题。

**Summary (发明总览)**:  
本发明提出了一种基于生成对抗网络的图像生成系统，通过设计计算效率高的生成神经网络架构，实现设备端低延迟图像生成。该系统通过降低中间层特征图的分辨率并结合上采样操作，在保证图像质量的同时显著降低计算复杂度。此外，训练过程中引入辅助输出头生成低分辨率图像，以增强训练信号并提升生成效果。

**Key Innovation (核心创新)**:  
1. 设计了一种计算效率高的生成神经网络架构，通过降低中间层特征图的分辨率，减少了卷积块的计算复杂度。
2. 在神经网络输出头中引入上采样操作块，避免了卷积块对特征图进行上采样的需求，从而进一步降低计算量。
3. 在训练过程中，生成神经网络被增强有辅助输出头，这些输出头生成低分辨率图像并提供额外的训练信号，提升了训练效率和生成质量。
4. 通过在边缘设备上本地部署生成神经网络，减少了对计算和通信网络资源的消耗，相较于远程部署方式具有更低延迟和更高效率。
5. 该架构能够在保持高图像质量的同时，实现设备端实时图像生成，适用于如无条件或条件人脸图像生成等应用场景。
6. 通过降低对教师神经网络（teacher neural network）的依赖，减少了计算资源的消耗，同时保持了与复杂模型相近的生成质量。
7. 该技术可应用于资源受限的边缘设备，如移动设备或嵌入式系统，为实时图像生成提供高效解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617561)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268441)**
<br/><br/>

---


<br/>

### 2. 设备与系统的电源状态管理

**Title (EN)**: Management of Power States of Devices and Systems  
**Pub. No.**: US20260267398

**Applicant**: Google LLC  
**Inventor**: [Harsha Priya Narasapuram Venkatarama Gupta](https://patents.google.com/?inventor=Harsha+Priya+Narasapuram+Venkatarama+Gupta&country=US&num=100&sort=new), [Mukesh Agrawal](https://patents.google.com/?inventor=Mukesh+Agrawal&country=US&num=100&sort=new), [Jonathan Dillinger](https://patents.google.com/?inventor=Jonathan+Dillinger&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明技术通过管理电子设备的硬件电源状态来实现节能。通过优化这些电源状态，可以改善电子设备的功耗、功能性和/或唤醒延迟，相较于其他方法具有优势。技术要点包括优化寄生工作负载的管理以提高可穿戴设备的整体电源效率，从而提升设备性能。该技术还包括一个操作系统作为另一个操作系统的监督者。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616429_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及电子设备电源管理技术，具体包括硬件电源状态优化和操作系统间的协同管理。

**Background (发明背景)**:  
系统电源管理中的一个重要问题是支持各种系统组件（如具有一个或多个电源状态的硬件和/或软件）在不同电源状态之间的转换，同时管理这些电源状态之间的相互依赖关系。现有的系统挂起任务通常只关注处理器与硬件组件之间的简单依赖关系，而忽略了硬件组件之间的复杂依赖关系。此外，不同系统对电源和唤醒延迟的要求不同，传统的标准电源状态方案可能无法实现最佳节能效果。

**Summary (发明总览)**:  
本发明提出了一种精细化的电源管理方案，通过优化硬件组件的电源状态转换顺序和依赖关系管理，提升电子设备的电源效率。该技术通过操作系统间的协同工作，实现对硬件组件的智能电源控制，支持系统挂起和运行时电源管理等多种场景。相较于传统方法，本发明能够更准确地估算功耗并减少不必要的能耗，同时平衡电源与性能之间的权衡。

**Key Innovation (核心创新)**:  
1. 通过管理硬件组件之间的电源状态依赖关系，实现更精细化的电源控制，避免传统方法中可能出现的功耗估算偏差。
2. 引入操作系统间的协同管理机制，一个操作系统作为另一个操作系统的监督者，确保电源状态转换的可靠性和效率。
3. 支持系统挂起和运行时电源管理，能够在不影响系统性能的前提下，动态调整硬件组件的电源状态以优化整体功耗。
4. 提供操作序列支持，确保在电源状态转换过程中，硬件组件按正确顺序进行操作，例如USB设备在总线供电后才开启。
5. 实现电源状态转换的可追溯性，通过建立归因链，明确系统组件被唤醒的原因，从而更好地满足性能和功能需求。
6. 针对可穿戴设备等特定场景，优化寄生工作负载的管理，进一步提升设备的电源效率。
7. 该技术可应用于智能手机、可穿戴设备等电子设备，能够有效延长电池寿命并减少能耗，同时保持设备的功能性和响应速度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616429)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267398)**
<br/><br/>

---


<br/>

### 3. 浏览和搜索内容时呈现相关内容

**Title (EN)**: Presenting Related Content While Browsing and Searching Content  
**Pub. No.**: US20260267932

**Applicant**: Google LLC  
**Inventor**: [Srikanth Jalasutram](https://patents.google.com/?inventor=Srikanth+Jalasutram&country=US&num=100&sort=new), [Jia Sin Lua](https://patents.google.com/?inventor=Jia+Sin+Lua&country=US&num=100&sort=new), [Damon Chizuru Kawamoto](https://patents.google.com/?inventor=Damon+Chizuru+Kawamoto&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明涉及用于呈现附加内容建议界面的系统和方法，包括获取描述显示内容的显示数据，并确定与显示内容相关联的附加内容。然后可以提供一个界面，用于显示与显示内容和附加内容相关联的数据。该界面可以包括用于显示显示内容的一部分的第一显示窗口，以及用于显示与附加内容相关联的片段的第二显示窗口。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617005_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及内容推荐和用户界面设计。

**Background (发明背景)**:  
在浏览网页等数字内容时，用户通常只能看到与主题相关的一小部分信息，且这些信息可能过时或不够可靠。用户若想深入了解或与内容互动，往往需要手动进行额外搜索或收藏网页。现有技术无法有效提供上下文补充或便捷操作方式，导致用户需要花费额外时间进行信息查找。

**Summary (发明总览)**:  
本发明提出了一种基于当前显示内容提供附加内容的技术方案。通过分析显示内容，系统能够智能预测并推荐相关附加内容，并以直观界面呈现。该界面包含显示内容的主要部分和附加内容的预览片段，支持用户快速获取补充信息或执行相关操作。相较于传统方法，本发明通过机器学习模型和语义分析技术，提升了内容推荐的准确性和用户交互的便捷性。

**Key Innovation (核心创新)**:  
1. 利用机器学习模型对显示内容进行语义理解，生成机器学习输出，并基于此确定附加内容，从而实现智能内容推荐。
2. 提供包含显示内容预览和附加内容片段的界面，用户可通过该界面快速获取上下文信息或进行相关操作。
3. 通过统一资源定位符（URL）识别显示内容，并基于此确定相关联的附加网页或资源，生成相应的操作界面元素。
4. 支持增强现实体验，用户可通过界面中的可选择元素启动与显示内容相关的AR体验。
5. 界面包含滚动指示器和气泡界面元素，用户可通过气泡快速访问附加内容，提升交互效率。
6. 界面中的建议元素可根据附加内容的存在状态进行动态切换，提供更直观的用户反馈。
7. 本发明可应用于网页浏览、电子书阅读和移动应用等场景，为用户提供更丰富的上下文信息和便捷操作方式，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617005)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267932)**
<br/><br/>

---


<br/>

### 4. 视频会议沉浸式背景

**Title (EN)**: IMMERSIVE BACKGROUNDS FOR VIDEOCONFERENCING  
**Pub. No.**: US20260270370

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Andréa BRITTO MATTOS LIMA](https://patents.google.com/?inventor=Andr%C3%A9a+BRITTO+MATTOS+LIMA&country=US&num=100&sort=new), [Spencer G FOWERS](https://patents.google.com/?inventor=Spencer+G+FOWERS&country=US&num=100&sort=new), [Thiago VALLIN SPINA](https://patents.google.com/?inventor=Thiago+VALLIN+SPINA&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明通过将二维（2D）图像处理成多个具有深度并根据观察者视角变化而移动的图层来创建视频会议的沉浸式背景。通过跟踪观察者的视角方向，并根据视差效应移动图像的各个图层，从而产生深度感。当用于视频会议背景时，这会创造一种更加沉浸式的体验，因为视频会议参与者背后的背景看起来是三维的而非静态的。2D图像通过应用多种图像处理技术（包括图像分割、深度估计和图像补全）转换为沉浸式背景。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619687_1.jpg)

**Technical Field (技术领域)**:  
视频会议技术；
图像处理；
增强现实（AR）

**Background (发明背景)**:  
视频会议已成为远程工作环境中的重要通信工具，许多人使用背景图像来隐藏实际房间以保护隐私或呈现更专业的形象。然而，静态背景缺乏深度和互动性，可能导致视频会议体验显得不真实或生硬。尽管视频会议比仅音频通信更具互动性，但仍然无法完全实现面对面交流的连接感。

**Summary (发明总览)**:  
本发明提出了一种通过2D图像生成动态3D背景的技术，以提升视频会议体验。该系统允许用户选择2D图像作为背景，并利用图像分割、深度估计和图像补全技术将其处理成2.5D图像。在视频会议期间，系统通过AI眼动/头动追踪技术实时跟踪观察者的视角方向，并根据视角变化动态调整背景，模拟视差效应，创造3D背景的错觉。这种方法相比生成完整的3D模型，计算和数据需求更低，同时提供更自然和互动的视频会议体验。

**Key Innovation (核心创新)**:  
1. 通过图像分割技术将2D图像分解为多个具有深度信息的图层，实现背景图像的层次化处理。
2. 利用AI工具（如扩散模型）进行图像补全，包括图像修复和扩展，以生成完整的2.5D图像。
3. 采用AI眼动/头动追踪技术实时跟踪观察者的视角方向，实现背景的动态调整。
4. 根据视差效应移动图像图层，模拟3D效果，提升视频会议的沉浸感和真实感。
5. 相较于完整的3D背景模型，本发明采用2.5D图像处理方法，降低了计算资源消耗、存储需求和网络带宽占用。
6. 提供用户界面（UI）供用户选择和调整2D背景图像，增强用户体验的灵活性和个性化。
7. 应用于视频会议场景时，本发明能够提供更自然和互动的背景效果，提升远程沟通的沉浸感和专业性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619687)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270370)**
<br/><br/>

---


<br/>

### 5. 使用文本提示图像生成进行个性化头像调整

**Title (EN)**: PERSONALIZED AVATAR ADJUSTMENT USING TEXT PROMPTED IMAGE GENERATION  
**Pub. No.**: US20260268595

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Zohar Barzelay](https://patents.google.com/?inventor=Zohar+Barzelay&country=US&num=100&sort=new), [Rotem Bennet](https://patents.google.com/?inventor=Rotem+Bennet&country=US&num=100&sort=new), [Maxim Bluvshtein](https://patents.google.com/?inventor=Maxim+Bluvshtein&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
一种实施方式包括通过识别一组二维图像中的第一张二维图像中的第一个面部特征来生成第一分割掩码，第一分割掩码识别第一张二维图像的可更改部分和不可更改部分，不可更改部分包括第一个面部特征。一种实施方式包括使用图像修改模型，从第一张二维图像的第一数值表示、第一分割掩码、正向提示和负向提示出发，调整第一张二维图像，调整结果生成第二张二维图像，第二张二维图像替换一组二维图像中的第一张二维图像。一种实施方式包括

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617731_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及头像生成技术，具体为使用文本提示进行个性化头像调整的混合现实内容生成。

**Background (发明背景)**:  
社交媒体平台用户通常需要创建代表自己的头像，但现有技术难以在不扭曲用户身份的情况下进行有效调整。现有的头像调整方法依赖专业技能或有限的编辑工具，难以满足非专业人士的需求。此外，逐帧编辑视频输出的头像会导致结果不一致，影响用户体验。

**Summary (发明总览)**:  
本发明提供了一种使用文本提示进行个性化头像调整的方法。该方法首先识别二维图像中的面部特征并生成分割掩码，区分可更改和不可更改区域。然后，通过图像修改模型根据文本提示调整图像，生成新的二维图像。最后，利用三维建模模型从调整后的二维图像生成对应的三维模型。本发明通过文本驱动的图像生成技术，实现了更精准、更一致且保留用户身份特征的头像调整。

**Key Innovation (核心创新)**:  
1. 通过识别面部特征生成分割掩码，区分可更改和不可更改区域，确保关键特征不被过度修改。
2. 利用图像修改模型结合正向和负向文本提示进行图像调整，实现更精准的个性化调整效果。
3. 采用文本驱动的调整方式，用户只需输入自然语言指令即可完成头像修改，降低操作门槛。
4. 引入三维建模模型，将调整后的二维图像转换为三维模型，适应混合现实应用场景。
5. 通过一致性调整机制，确保视频输出中头像的帧间一致性，避免随机性带来的不自然效果。
6. 该技术可应用于社交媒体、虚拟现实和增强现实平台，为用户提供更自然、更具表现力的虚拟形象。
7. 独特价值在于结合文本提示和图像生成技术，在保留用户身份特征的同时实现高度个性化的头像调整。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617731)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268595)**
<br/><br/>

---


<br/>

### 6. 智能眼镜框架变形的在线校准

**Title (EN)**: ONLINE CALIBRATION OF SMARTGLASSES FRAME DEFORMATION  
**Pub. No.**: US20260267154

**Applicant**: GOOGLE, LLC  
**Inventor**: [Zhiheng Jia](https://patents.google.com/?inventor=Zhiheng+Jia&country=US&num=100&sort=new), [Joshua Anthony Hernandez](https://patents.google.com/?inventor=Joshua+Anthony+Hernandez&country=US&num=100&sort=new), [Chao Guo](https://patents.google.com/?inventor=Chao+Guo&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
用于增强现实智能眼镜的用户舒适度维护技术包括执行框架变形的在线校准，以校正镜头中的显示位置。这种校准涉及将世界朝向的摄像头与眼动追踪摄像头之间的框架部分建模为绕框架部分上的垂直轴旋转的铰链。即，框架部分由两个线段组成，它们在待确定的未知旋转（角度）处连接。在此处理中，将忽略任何引起的平移。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616161_1.jpg)

**Technical Field (技术领域)**:  
增强现实智能眼镜领域，具体涉及框架变形校准和显示位置校正技术。

**Background (发明背景)**:  
智能眼镜等可穿戴设备通常需要适应用户头部形状以确保舒适性和光学对准。然而，框架的柔性和可变形特性可能导致显示位置不稳定，特别是在双眼显示的情况下。这种变形会引发视觉不适，影响用户体验。本发明旨在解决智能眼镜框架变形导致的显示位置偏差问题，通过在线校准技术来维持显示与用户视线的对准。

**Summary (发明总览)**:  
本发明提出了一种智能眼镜框架变形在线校准方法，通过建模框架部分为铰链结构并利用陀螺仪数据计算铰链旋转角度，从而确定框架变形程度并校正显示位置。该方法通过实时监测框架变形并自动触发校准，确保显示与用户视线的对准，提升用户舒适度和视觉体验。

**Key Innovation (核心创新)**:  
1. 通过将世界朝向摄像头与眼动追踪摄像头之间的框架部分建模为铰链结构，简化了框架变形的计算模型。
2. 利用陀螺仪数据测量世界朝向摄像头和眼动追踪摄像头的旋转速度，并通过扩展卡尔曼滤波器处理数据以确定铰链旋转角度。
3. 考虑了陀螺仪数据的噪声和偏差，并引入了时间延迟参数以提高校准精度。
4. 在检测到显示位置超出校准阈值时，自动触发重新校准并通知用户，确保显示位置的准确性。
5. 通过实时在线校准技术，解决了框架变形导致的显示位置偏差问题，提升了智能眼镜的视觉体验。
6. 该方法不仅适用于刚性框架，也适用于具有一定柔性的框架，适应性强。
7. 应用于增强现实智能眼镜时，能够有效维持用户舒适度并确保眼动追踪和显示的准确性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616161)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267154)**
<br/><br/>

---


<br/>

### 7. 用于促进语音通信服务的设备自动重配置方法

**Title (EN)**: Automated Device Reconfiguration to Facilitate Voice Communication Service  
**Pub. No.**: US20260270304

**Applicant**: Google LLC  
**Inventor**: [Po-Ying Chuang](https://patents.google.com/?inventor=Po-Ying+Chuang&country=US&num=100&sort=new), [Kuan-Wei Chen](https://patents.google.com/?inventor=Kuan-Wei+Chen&country=US&num=100&sort=new), [Chien-Chun Huang Fu](https://patents.google.com/?inventor=Chien-Chun+Huang+Fu&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明提供了一种方法和系统，用于自动配置设备以支持语音通信服务。该方法包括：(i) 设备检测到尽管其具备支持语音呼叫服务的能力，但当前未配置允许语音呼叫服务；(ii) 作为响应，设备自动重新配置自身以允许语音呼叫服务。在一个实施例中，语音呼叫服务是基于IP多媒体子系统(IMS)的语音呼叫服务，用户设备(UE)存储接入点名称(APN)控制列表(ACL)，检测设备未配置允许语音呼叫服务涉及UE检测ACL未将IMS APN列为允许的APN，UE随后自动重新配置自身以允许语音呼叫服务。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619614_1.jpg)

**Technical Field (技术领域)**:  
无线通信技术领域，具体涉及支持语音通信服务的设备自动配置技术。

**Background (发明背景)**:  
现代无线通信系统通过接入节点为用户设备提供无线覆盖，但设备可能因配置问题无法使用IMS APN，从而无法进行语音通信。现有的配置方法可能导致设备无法自动调整以支持语音服务，影响用户体验。本发明旨在解决设备因配置不当而无法使用语音通信服务的问题。

**Summary (发明总览)**:  
本发明提出了一种设备自动重配置机制，使具备语音通信能力的设备能够检测自身配置是否允许语音呼叫服务，并在必要时自动调整配置以支持该服务。具体实现方式为设备通过检查APN控制列表(ACL)是否包含IMS APN，并在未包含时自动添加IMS APN，从而确保设备能够使用IMS进行语音通信。该方法相较于现有技术，能够自动解决设备配置问题，提升语音通信服务的可用性和用户体验。

**Key Innovation (核心创新)**:  
1. 设备具备自动检测自身配置是否允许IMS语音呼叫服务的能力，通过检查ACL列表实现。
2. 当检测到ACL未包含IMS APN时，设备能够自动将IMS APN添加到ACL中，无需用户手动干预。
3. 设备在添加IMS APN之前，会进行测试过程以确认IMS APN的可用性，例如尝试建立IMS APN连接。
4. 如果测试成功，设备确认IMS APN应被列入ACL；如果测试失败，则不添加IMS APN，确保配置的正确性。
5. 该机制适用于支持IMS的无线通信系统，能够自动调整设备配置以支持语音通信服务。
6. 该方法特别适用于语音优先的设备，确保设备在无法使用当前网络进行语音通信时，能够切换到支持语音通信的网络。
7. 通过自动配置，设备能够更可靠地提供语音通信服务，提升用户在不同网络环境下的使用体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619614)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270304)**
<br/><br/>

---


<br/>

### 8. 在语音机器人与人类的对应对话中解析唯一个人标识符

**Title (EN)**: RESOLVING UNIQUE PERSONAL IDENTIFIERS DURING CORRESPONDING CONVERSATIONS BETWEEN A VOICE BOT AND A HUMAN  
**Pub. No.**: US20260268905

**Applicant**: GOOGLE LLC  
**Inventor**: [Rafael Goldfarb](https://patents.google.com/?inventor=Rafael+Goldfarb&country=US&num=100&sort=new), [Or Guz](https://patents.google.com/?inventor=Or+Guz&country=US&num=100&sort=new), [Lior Alon](https://patents.google.com/?inventor=Lior+Alon&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明旨在使语音机器人利用多个机器学习层，在与人类进行对话时解析出唯一的个人标识符。这些唯一个人标识符可以包括对个人而言独特的字母数字序列。在一些实现中，对应于包含唯一个人标识符的口语表达式的自动语音识别（ASR）语音假设将被处理，以生成候选的唯一个人标识符。系统将选择候选唯一个人标识符中的字母数字字符，并通过向人类提出澄清请求来明确这些字符，直到预测其与实际提供的唯一个人标识符相符。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486618074_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术领域，具体涉及语音机器人与人类交互中的个人标识符解析。

**Background (发明背景)**:  
在人与计算机的对话中，自动化助手常需处理用户的语音输入。然而，传统的自动语音识别（ASR）系统在处理如电子邮件地址、物理地址等非标准词汇时容易出现识别错误。这会导致自动化助手执行错误操作或要求用户重复输入，从而延长对话时间并消耗更多计算资源。此外，错误的识别还可能引发隐私问题，例如将用户个人信息发送到错误的接收者。

**Summary (发明总览)**:  
本发明提出了一种通过语音机器人利用多层机器学习模型来解析用户唯一个人标识符的方法。在对话过程中，语音机器人会处理包含唯一个人标识符的语音输入，生成候选标识符，并通过机器学习模型分析预测的准确性。系统会向用户提出澄清请求，逐步优化候选标识符，直到确认其与用户实际输入相符。这种方法能够减少识别错误，提高对话效率和准确性，并降低隐私风险。

**Key Innovation (核心创新)**:  
1. 利用多层机器学习模型（如Transformer模型或RNN模型）处理ASR语音假设，生成唯一个人标识符的候选树。
2. 通过分析语音输入中的特定字符或符号（如"@"符号或数字字符串），预测语音中是否包含唯一个人标识符。
3. 根据机器学习模型生成的预测度量值，动态调整候选唯一个人标识符的优先级和准确性。
4. 在对话过程中，语音机器人会主动向用户提出澄清请求，例如确认特定字符或拼写，以逐步优化识别结果。
5. 结合语音机器人的对话意图（如请求用户提供标识符或验证标识符），利用机器学习模型更快速准确地解析个人标识符。
6. 通过逐步优化候选标识符并限制搜索范围（例如根据已确认的字符序列），提高识别效率和准确性。
7. 该技术可应用于客户服务场景，例如在电话中验证用户身份或查找关联服务，从而提升用户体验并减少隐私风险。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486618074)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268905)**
<br/><br/>

---


<br/>

### 9. 用于免触手势交互的头戴式设备

**Title (EN)**: HEAD-MOUNTED DEVICE CONFIGURED FOR TOUCHLESS HAND GESTURE INTERACTION  
**Pub. No.**: US20260267145

**Applicant**: GOOGLE LLC  
**Inventor**: [Dongeek Shin](https://patents.google.com/?inventor=Dongeek+Shin&country=US&num=100&sort=new), [Chung Chun Wan](https://patents.google.com/?inventor=Chung+Chun+Wan&country=US&num=100&sort=new), [Jonathan James Taylor](https://patents.google.com/?inventor=Jonathan+James+Taylor&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
免触交互对于头戴式设备可能需要超出实际需求的功率。本专利描述了一种稀疏关键点的手部建模技术，用于减少识别动态手势所需的计算和功率。通过仅在手部出现在头戴式设备的视野中时进行建模和识别，并使用带有辅助设备的分体式计算架构，可以进一步降低免触交互的功率需求。这些手部建模和跟踪技术还可以应用于其他场景，例如将增强现实环境中的渲染元素锁定到用户的手部。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616152_1.jpg)

**Technical Field (技术领域)**:  
增强现实（AR）技术领域，具体涉及头戴式设备的手势识别与交互技术。

**Background (发明背景)**:  
头戴式设备（如智能眼镜）通常配备抬头显示器（HUD），用于向用户显示用户界面（UI），并允许用户通过手势与现实世界中的物体进行虚拟交互。然而，现有技术中，免触手势识别需要较高的功率，这对手持设备有限的电池容量提出了挑战。此外，使用额外的外围设备（如智能手表）虽然可以降低功耗，但会增加系统的成本和复杂性。因此，需要一种在技术可行性和用户体验之间取得平衡的免触手势识别方案。

**Summary (发明总览)**:  
本发明提出了一种用于头戴式设备的免触手势识别技术，通过结合低功耗和高功耗处理流程，实现动态手势的检测、识别和响应。该方法通过仅在检测到手部时触发高分辨率图像捕获，并使用稀疏关键点建模来减少计算量，从而降低平均功耗并延长设备续航时间。此外，该技术还支持将渲染元素锁定到手部位置，以增强增强现实体验。

**Key Innovation (核心创新)**:  
1. 采用低分辨率图像持续监测视野中的手部，并在检测到手部时触发高分辨率图像捕获，从而降低整体功耗。
2. 使用稀疏关键点建模技术，仅提取手部关键位置信息，减少计算量和数据处理需求。
3. 结合分体式计算架构，将关键点数据传输到辅助设备进行处理，进一步分担计算负载并降低头戴式设备的功耗。
4. 通过跟踪关键点随时间的移动，识别动态手势（如点击或滚动），并基于识别结果生成相应的渲染元素。
5. 将渲染元素锁定到手部位置，实现增强现实环境中与用户手部的动态交互。
6. 该技术无需额外传感器或外围设备，降低了系统复杂性和成本。
7. 应用于智能眼镜等头戴式设备，可实现更自然、直观的免触交互方式，同时延长设备续航时间。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616152)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267145)**
<br/><br/>

---


<br/>

### 10. 预先初始化自动化助手例程和/或取消预定闹钟

**Title (EN)**: PRE-EMPTIVELY INITIALIZING AN AUTOMATED ASSISTANT ROUTINE AND/OR DISMISSING A SCHEDULED ALARM  
**Pub. No.**: US20260268910

**Applicant**: GOOGLE LLC  
**Inventor**: [Nevzat Topcu](https://patents.google.com/?inventor=Nevzat+Topcu&country=US&num=100&sort=new), [Michael Andrew Goodman](https://patents.google.com/?inventor=Michael+Andrew+Goodman&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明涉及根据满足一个或多个条件来预先初始化自动化助手例程和/或取消闹钟。用户可以在闹钟响起时确认闹钟，或者在预定时间之前取消闹钟。用户可以通过在预定时间之前与自动化助手交互和/或与自动化助手已知的设备交互来预先取消闹钟。通过识别导致闹钟被取消的操作，可以启动其他过程，例如自动化助手例程。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486618079_1.jpg)

**Technical Field (技术领域)**:  
智能助手技术领域，具体涉及基于条件触发的自动化操作和闹钟管理。

**Background (发明背景)**:  
在某些情况下，用户会设置闹钟以便在特定时间唤醒自己。然而，如果用户在闹钟响起之前已经醒来，闹钟仍会按计划触发，这会浪费计算和电力资源。此外，用户可能需要中断当前任务来停止闹钟。类似的问题也出现在自动化助手的操作中，用户可能无法舒适地提供触发短语，或者自动化助手需要持续监听音频数据，这会导致计算效率低下。

**Summary (发明总览)**:  
本发明提出了一种方法，通过识别用户行为或环境条件来预先取消闹钟或启动自动化助手例程。用户可以通过设备交互或满足特定情境条件来取消闹钟，而无需等待闹钟响起。这种方法可以减少不必要的计算资源消耗，并允许自动化助手在用户取消闹钟时自动执行预定义的任务集，从而提升用户体验并优化设备资源利用。

**Key Innovation (核心创新)**:  
1. 通过识别用户行为（如开关灯或激活特定应用）来满足情境条件，从而在闹钟响起之前预先取消闹钟。
2. 在用户与自动化助手交互或与已知设备交互时，识别并处理这些交互以取消闹钟，无需等待闹钟响起。
3. 在闹钟被取消时，自动触发预设的自动化助手例程，例如执行早晨任务集，无需用户额外输入语音指令。
4. 基于用户过去的行为模式生成情境条件参数，例如用户多次在闹钟响起后执行特定任务，系统可以学习并自动应用这些模式。
5. 允许用户配置自动化助手在闹钟响起或被取消时执行特定例程，例如打开咖啡机、播放音乐或调整家居设备。
6. 通过减少对语音指令的依赖，节省网络带宽和处理资源，因为无需将语音数据传输到服务器进行处理。
7. 应用于智能家居场景中，为用户提供更智能、更高效的早晨唤醒体验，同时优化设备资源利用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486618079)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268910)**
<br/><br/>

---


<br/>

### 11. 响应位置相关查询的特定位置三维模型

**Title (EN)**: Location-Specific Three-Dimensional Models Responsive to Location-Related Queries  
**Pub. No.**: US20260268615

**Applicant**: Google LLC  
**Inventor**: [Ignacio Garcia Dorado](https://patents.google.com/?inventor=Ignacio+Garcia+Dorado&country=US&num=100&sort=new), [Charles Goran](https://patents.google.com/?inventor=Charles+Goran&country=US&num=100&sort=new), [Jordi Serrano Berbel](https://patents.google.com/?inventor=Jordi+Serrano+Berbel&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
通过生成响应位置查询的特定位置三维模型，可以为用户提供对位置的更好理解，包括更好的交互性、更好的视角和更好的维度理解。模型的生成可以通过利用三维资产数据库和分割方法来实现。这些特定位置模型还可以通过进一步包含特定情境的模拟效果（如模拟天气或交通状况）来提供更多实用性。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617753_1.jpg)

**Technical Field (技术领域)**:  
三维建模技术领域，具体涉及基于位置查询生成特定位置三维模型的技术。

**Background (发明背景)**:  
现有搜索引擎在用户搜索位置时，通常返回超链接或包含文本片段、照片或地图的生成图形。这些结果无法准确呈现地标或纪念物的实际外观和规模。图像和视频虽然能提供位置的外观视角，但无法完全捕捉位置的维度信息。此外，搜索结果缺乏交互性，难以直观地探索位置的不同方面，例如不同视角的特写或位置的不同部分。

**Summary (发明总览)**:  
本发明提出了一种基于用户查询生成特定位置三维模型的方法。通过处理用户的位置查询，系统能够访问三维资产数据库并检索相关三维模型。随后，系统通过分割三维模型，生成特定位置的三维模型片段，并将其提供给用户设备。该方法不仅能提供更精确的地理位置信息，还能结合模拟效果（如天气或交通状况）增强用户体验。

**Key Innovation (核心创新)**:  
1. 通过三维模型分割技术，从通用三维模型中提取特定位置的三维模型片段，实现对单一位置的精确建模。
2. 利用图像分割和LiDAR数据等传感器数据，实现对复杂场景的高精度三维建模和分割，确保模型的准确性和细节表现。
3. 支持将特定位置的三维模型片段作为增强现实资产，提供沉浸式的位置展示体验，增强用户交互性。
4. 结合模拟效果（如天气或交通状况），为用户提供更全面的位置信息，帮助用户更好地理解和规划访问。
5. 通过服务器端渲染和传输，用户设备无需高性能计算资源即可实现高质量的三维模型展示。
6. 支持多种查询方式，包括文本搜索、图像识别和地图导航请求，扩展了应用场景和用户覆盖面。
7. 应用于旅游、导航和虚拟导览等领域，为用户提供更直观、更具互动性的位置信息获取方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617753)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268615)**
<br/><br/>

---


<br/>

### 12. 扩展现实显示中的双目尺寸差异匹配

**Title (EN)**: BINOCULAR SIZE DISPARITY MATCHING IN EXTENDED REALITY DISPLAYS  
**Pub. No.**: US20260268594

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Michaela PORUBANOVA](https://patents.google.com/?inventor=Michaela+PORUBANOVA&country=US&num=100&sort=new), [Gregory Michael LINK](https://patents.google.com/?inventor=Gregory+Michael+LINK&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明公开了用于在扩展现实(ER)系统中缩放图像以根据用户视力处方校准图像的技术。服务访问位于用户眼睛与ER系统显示之间镜片的屈光度信息，并访问用于在显示上显示的图像。服务基于屈光度信息生成或访问缩放因子。在图像显示在显示上之前，服务将缩放因子应用于图像，生成放大或缩小的图像版本。服务在显示中显示缩放后的图像。缩放因子旨在使通过镜片在显示上观看的缩放图像呈现预定尺寸。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617730_1.jpg)

**Technical Field (技术领域)**:  
扩展现实(ER)技术领域，具体涉及双目视觉校正和图像缩放技术。

**Background (发明背景)**:  
头戴式设备(HMD)等可穿戴设备正变得越来越流行，它们能够提供扩展现实(ER)体验。ER系统包括虚拟现实(VR)、混合现实(MR)和增强现实(AR)平台。然而，当用户佩戴不同屈光度的眼镜时，左右眼图像尺寸差异会导致深度感知不准确，甚至出现双目竞争现象，影响用户体验。

**Summary (发明总览)**:  
本发明提出了一种在ER系统中根据用户视力处方调整图像尺寸的方法。系统首先获取用户眼镜的屈光度信息，然后基于该信息生成缩放因子，对左右眼图像分别进行缩放处理。缩放后的图像通过用户眼镜观看时能够保持一致的尺寸，从而解决双目视觉差异问题，提高深度感知精度和用户舒适度。

**Key Innovation (核心创新)**:  
1. 通过获取用户眼镜的屈光度信息，精确计算图像缩放因子，实现对双目视觉差异的校正。
2. 分别对左右眼图像应用不同的缩放因子，确保通过用户眼镜观看时图像尺寸一致，解决双目竞争问题。
3. 在图像显示前进行实时缩放处理，避免因图像尺寸差异导致的深度感知失真。
4. 系统能够适应不同用户的视力处方，提供个性化的视觉校正方案。
5. 通过调整图像尺寸补偿眼镜的放大或缩小效应，确保ER场景中虚拟对象的真实尺寸感知。
6. 该技术可应用于VR、MR和AR等多种ER系统，提升用户在虚拟环境中的视觉体验。
7. 特别适用于需要高精度深度感知的应用场景，如虚拟手术、3D设计和远程协作等。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617730)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268594)**
<br/><br/>

---


<br/>

### 13. 用于可穿戴音频对话的智能眼镜系统

**Title (EN)**: SMART GLASSES SYSTEMS FOR HEARABLE CONVERSATIONS  
**Pub. No.**: US20260270630

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Sam Padinjaremannil Alex](https://patents.google.com/?inventor=Sam+Padinjaremannil+Alex&country=US&num=100&sort=new), [Thomas Ivan Harvey](https://patents.google.com/?inventor=Thomas+Ivan+Harvey&country=US&num=100&sort=new), [Kanji Mavji Kerai](https://patents.google.com/?inventor=Kanji+Mavji+Kerai&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明提供了一种方法，其中智能眼镜的第一用户所属的至少一个处理器与第二用户的可穿戴音频设备建立无线通信链路。智能眼镜使用至少一个麦克风检测第一用户的语音音频，并通过无线通信链路将该语音音频传输到可穿戴音频设备。本发明还公开了其他各种方面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619970_1.jpg)

**Technical Field (技术领域)**:  
智能眼镜与可穿戴音频设备领域，具体涉及语音增强和降噪技术。

**Background (发明背景)**:  
在嘈杂环境中理解语音存在困难，现有技术如助听器和智能眼镜虽配备了多麦克风阵列和基础信号处理技术，但在高噪声环境或低信噪比情况下效果有限。此外，这些设备可能无意中放大声音，对听力健康构成风险。因此，需要一种更强大和集成的方法来改善语音理解和保护听力健康。

**Summary (发明总览)**:  
本发明提出了一种智能眼镜与可穿戴音频设备协同工作的系统，通过智能眼镜上的定向麦克风阵列和先进信号处理算法捕捉并增强用户语音，然后通过低延迟蓝牙技术将处理后的音频传输到对话伙伴的可穿戴设备。该系统利用机器学习和数字信号处理技术进行降噪，并动态调整噪声消除和透明度水平，以优化语音清晰度和听力保护。本发明相较于传统设备，在高噪声环境下显著提升了语音清晰度和用户体验。

**Key Innovation (核心创新)**:  
1. 采用嘴部定向波束成形技术，通过智能眼镜上的空间分布麦克风阵列捕捉用户语音并抑制环境噪声，从而提高语音信噪比。
2. 结合深度神经网络（DNN）降噪和空间降噪技术，对捕捉到的语音进行进一步处理，以增强语音清晰度。
3. 通过低延迟蓝牙技术将处理后的音频实时传输到对话伙伴的可穿戴音频设备，如耳机、助听器或耳蜗植入物，确保高质量的音频播放。
4. 可穿戴音频设备支持主动和被动降噪机制，并根据环境噪声条件和信噪比动态调整噪声消除和透明度水平，以优化听力保护和语音可懂度。
5. 系统集成了AI助手，可智能管理设备配对、设置调整，并在群组对话中智能切换用户角色，如群组领导、团队成员或听众。
6. 通过在源设备（智能眼镜）进行近场音频捕捉和处理，而非依赖听者设备的远场音频处理，显著提升了嘈杂环境下的语音理解能力。
7. 该系统可应用于音乐会、酒吧、体育场等高噪声环境下的对话场景，为用户提供增强的听觉体验，同时保护听力健康。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619970)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270630)**
<br/><br/>

---


<br/>

### 14. 设备端人员识别及智能警报提供系统和方法

**Title (EN)**: Systems and Methods for On-Device Person Recognition and Provision of Intelligent Alerts  
**Pub. No.**: US20260268708

**Applicant**: Google LLC  
**Inventor**: [Mohammad Afshar](https://patents.google.com/?inventor=Mohammad+Afshar&country=US&num=100&sort=new), [Saajan Shridhar](https://patents.google.com/?inventor=Saajan+Shridhar&country=US&num=100&sort=new), [George Alban Heitz, III](https://patents.google.com/?inventor=George+Alban+Heitz%2C+III&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明描述了用于设备端人员识别和智能警报提供的系统和方法。该系统包括一个去中心化的多摄像头系统，用于设备端人脸识别。设备（例如安防摄像头、视频门铃）捕获人员的图像/视频，处理输入图像帧，检测人脸图像，过滤静态人脸，并将人脸旋转对齐至正面朝上。然后，设备过滤低质量人脸图像和/或人脸大部分被遮挡的图像。设备计算人脸嵌入，将其与本地存储的参考嵌入集进行比较，并将匹配结果发送到云服务。云服务根据匹配结果通知设备所有者观察到的对象是已知人员还是陌生人。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617858_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及视频监控和人脸识别技术，具体为设备端人脸识别和隐私保护技术。

**Background (发明背景)**:  
传统视频监控系统通常在云端进行人员识别，这需要将原始图像或视频流传输到云端，可能引发隐私问题。
许多设备缺乏本地加密能力，导致敏感数据以未加密形式传输。
此外，单摄像头系统可能因设备故障导致数据丢失，而多摄像头系统可能因设备性能差异无法统一运行人脸识别模型。
设备端人员识别虽然提高了隐私保护，但面临存储和计算能力有限、数据同步困难等问题。

**Summary (发明总览)**:  
本发明提出了一种去中心化的多摄像头系统，通过设备端人脸识别实现智能警报。
系统首先在设备端进行人脸检测、图像处理和特征提取，然后计算人脸嵌入并与本地存储的参考嵌入进行比对。
匹配结果用于判断观察对象是否为已知人员，并通过云服务通知设备所有者。
所有敏感信息（如人脸嵌入）均保留在设备端，避免了隐私泄露风险。
本发明通过设备端处理和本地存储解决了传统云端识别带来的隐私和效率问题，同时通过多设备协同机制提升了系统的鲁棒性和用户体验。

**Key Innovation (核心创新)**:  
1. 采用设备端人脸识别技术，所有人脸检测和特征提取计算均在本地设备完成，避免了将敏感数据传输到云端的风险。
2. 通过本地存储参考嵌入集并实现设备端比对，减少了对云端计算和存储资源的依赖，同时提升了识别效率。
3. 设计了多设备协同机制，通过对不同设备计算能力和存储容量的适配，确保多摄像头系统能够统一运行人脸识别模型。
4. 实现了对低质量人脸图像和遮挡图像的过滤机制，提高了识别的准确性和可靠性。
5. 提供了用户友好的管理界面，允许用户查看、编辑和管理本地人脸库，例如添加、删除或合并人员信息。
6. 通过设备端处理和本地存储机制，确保了用户隐私保护，同时支持与云端服务的必要交互，例如更新参考库或同步数据。
7. 本发明可应用于家庭安防、智能门铃等场景，为用户提供更安全、更高效的智能监控解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617858)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268708)**
<br/><br/>

---


<br/>

### 15. 使用扩散模型的数字图像恢复

**Title (EN)**: Digital Image Restoration Using Diffusion Models  
**Pub. No.**: US20260268453

**Applicant**: Google LLC  
**Inventor**: [Mauricio Delbracio](https://patents.google.com/?inventor=Mauricio+Delbracio&country=US&num=100&sort=new), [Peyman Milanfar](https://patents.google.com/?inventor=Peyman+Milanfar&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
提供了一种迭代图像恢复过程，该过程使用低质量图像与期望的高质量恢复图像作为训练数据，用于一个或多个图像恢复模型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617574_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及数字图像处理领域，具体为基于扩散模型的图像恢复技术。

**Background (发明背景)**:  
从低质量图像恢复高质量图像是计算机视觉和计算成像领域的一个基本问题。单图像恢复是一个高度不适定问题，多个合理的清晰图像可能对应相同的模糊和噪声观测结果。现有方法通常采用监督学习，通过训练模型来推断低质量图像的潜在高质量版本，但这些方法容易导致预测结果缺乏自然细节。

**Summary (发明总览)**:  
本发明提出了一种基于迭代过程的图像恢复方法，通过使用低质量图像与高质量图像的配对数据训练扩散模型。该方法通过逐步解决一系列较简单的逆问题，逐步恢复图像质量。模型在训练过程中学习从中间退化图像预测清晰图像的能力，从而实现高质量图像重建。与传统回归方法相比，该方法能够生成更接近原始样本的高保真恢复图像。

**Key Innovation (核心创新)**:  
1. 采用扩散模型进行图像恢复，通过迭代方式逐步恢复图像质量，避免了传统方法中单一回归预测导致的细节丢失问题。
2. 使用配对的低质量/高质量图像进行监督训练，模型能够学习从低质量图像生成高质量图像的映射关系。
3. 通过在每一步结合当前图像、预测结果和噪声样本，生成新的输出图像，从而实现逐步去噪和细节恢复。
4. 提出了一个迭代优化框架，每一步解决一个相对简单的逆问题，最终实现高质量图像重建。
5. 该方法不需要显式建模退化过程，而是通过学习配对数据中的模式来恢复图像。
6. 适用于处理各种类型的图像退化问题，如模糊、噪声和压缩伪影等。
7. 该技术可应用于图像修复、照片增强和医学影像处理等领域，能够显著提升图像质量和清晰度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617574)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268453)**
<br/><br/>

---


<br/>

### 16. 基于传感器数据的内存配置

**Title (EN)**: CONFIGURATION OF MEMORY BASED ON SENSOR DATA  
**Pub. No.**: US20260268992

**Applicant**: Google LLC  
**Inventor**: [Subrata Banik](https://patents.google.com/?inventor=Subrata+Banik&country=US&num=100&sort=new), [Jayvik Arun Desai](https://patents.google.com/?inventor=Jayvik+Arun+Desai&country=US&num=100&sort=new), [Minjia Xu](https://patents.google.com/?inventor=Minjia+Xu&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
根据至少一种实现方式，一种方法包括从计算设备上的至少一个传感器识别至少一个传感器数据。该方法进一步包括确定该至少一个传感器数据是否满足至少一个标准。在响应于该至少一个传感器数据满足该至少一个标准时，该方法进一步包括启动计算设备上的内存校准。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486618168_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算设备内存管理领域，具体涉及基于传感器数据触发内存校准的技术。

**Background (发明背景)**:  
现代计算设备依赖内存存储数据和指令，内存校准通过调整参数优化性能和可靠性。然而，现有技术难以确定何时进行校准以避免干扰用户操作并保持设备功能。本发明旨在解决这一问题，通过传感器数据的变化来智能触发内存校准。

**Summary (发明总览)**:  
本发明提出了一种基于传感器数据触发内存校准的技术方案。通过识别计算设备传感器数据的变化并判断其是否满足特定标准，系统能够在必要时自动或经用户批准后启动内存校准。该方法利用传感器数据（如温度、位置、湿度等）预测内存状态的变化，从而优化校准时机，减少不必要的校准次数，提高设备稳定性和数据处理效率。

**Key Innovation (核心创新)**:  
1. 通过传感器数据（如温度、位置、湿度等）实时监测设备环境变化，并将其与内存状态关联。
2. 应用机器学习模型分析传感器数据与内存状态之间的关系，预测潜在的内存问题并触发校准。
3. 预处理传感器数据，包括标准化、滤波和特征提取，以提高模型对环境变化的识别精度。
4. 根据传感器数据的变化趋势智能判断是否需要校准，避免因瞬时波动导致的不必要校准。
5. 支持多设备数据汇总训练模型，提升校准触发决策的准确性和普适性。
6. 在设备空闲时自动执行校准，或在用户批准后进行，减少对用户操作的干扰。
7. 通过预测性校准技术延长内存寿命，提升设备在复杂环境下的稳定性和可靠性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486618168)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268992)**
<br/><br/>

---


<br/>

### 17. 集成电路封装用散热器集成电压调节器组件

**Title (EN)**: HEATSINK INTEGRATED VOLTAGE REGULATOR ASSEMBLY FOR AN INTEGRATED CIRCUIT PACKAGE  
**Pub. No.**: US20260271706

**Applicant**: Google LLC  
**Inventor**: [Richard Stuart Roy](https://patents.google.com/?inventor=Richard+Stuart+Roy&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
一种用于集成电路封装的电压调节器组件，包括位于集成电路封装上表面的散热器。散热器在集成电路封装上方定义了一个腔体，电压调节器位于该腔体内。电压调节器与集成电路封装之间设置有弹簧针垫，用于将电压从电压调节器传输至集成电路封装。还提供了一种使用该电压调节器组件调节集成电路封装电压的方法。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486621141_1.jpg)

**Technical Field (技术领域)**:  
集成电路封装技术领域，具体涉及散热器与电压调节器的集成设计。

**Background (发明背景)**:  
随着半导体行业的发展，高性能集成电路的广泛应用对电压调节器的效率和稳定性提出了更高要求。传统电压调节器通常放置在印刷电路板上，与集成电路相邻，存在功率传输问题和瞬态支持不足的缺陷。本发明旨在解决高功率集成电路的电压调节效率、稳定性和散热问题。

**Summary (发明总览)**:  
本发明提出了一种将电压调节器集成到散热器中的设计方案，通过在集成电路封装上方设置带有腔体的散热器，将电压调节器置于腔体内，并通过弹簧针垫实现电压的直接传输。该设计缩短了电压传输路径，提升了功率传输效率和稳定性，同时利用散热器对电压调节器和集成电路封装进行有效散热。相较于传统方案，本发明简化了装配流程，提高了可维护性，并解决了集成电路和电压调节器的热膨胀和氧化问题。

**Key Innovation (核心创新)**:  
1. 将电压调节器集成到散热器内部，通过在散热器中定义腔体实现紧凑布局，缩短了电压传输路径。
2. 采用弹簧针垫连接电压调节器和集成电路封装，弹簧针垫可穿过散热器上的孔，实现高效可靠的电压传输。
3. 电压调节器分为两级，第一级将高压转换为中压，第二级将中压转换为低压，优化了电压转换效率。
4. 在散热器与集成电路封装之间使用导热界面材料，如导热垫、腻子或导热脂，确保高效散热。
5. 散热器可采用鳍片、冷板或液体冷却系统，甚至热虹吸散热器或热管散热器，适应不同散热需求。
6. 该设计允许集成电路封装灵活放置在印刷电路板上，并简化了电压调节器的更换流程，降低了维护成本。
7. 应用于高功率集成电路封装场景，如服务器、图形处理器等，可提供更稳定的电压供应和更高效的散热解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486621141)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260271706)**
<br/><br/>

---


<br/>

### 18. 具有元光栅输出耦合器的光学波导

**Title (EN)**: OPTICAL WAVEGUIDE WITH METAGRATING OUT-COUPLER  
**Pub. No.**: US20260267052

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Manisha SINGH](https://patents.google.com/?inventor=Manisha+SINGH&country=US&num=100&sort=new), [Mikhail ERDMANIS](https://patents.google.com/?inventor=Mikhail+ERDMANIS&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
一种光学装置，包括光学波导和用于从光学波导输出耦合光的出射光栅。光学波导具有表面并支持从该表面出射的显示光的全内反射。出射光栅包括分布在光学波导表面平行方向上的二维矩阵复制纳米级特征。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616051_1.jpg)

**Technical Field (技术领域)**:  
光学工程领域，具体涉及光学波导和元光栅技术，应用于近眼显示设备。

**Background (发明背景)**:  
近眼显示技术近年来发展迅速，成为新兴消费技术，尤其在虚拟现实(VR)和增强现实(AR)领域。然而，现有技术面临保持正常眼镜外观和透明度的挑战。传统线性衍射光栅在某些配置中可能无法理想工作，例如可能将大量光泄露到与期望输出方向相反的方向。此外，直接在光学波导上布置衍射光栅在需要垂直于光传播方向透明的情况下可能不是最佳选择。

**Summary (发明总览)**:  
本发明提出了一种新型光学波导，通过使用元光栅实现光的输出耦合。元光栅是一种二维复制纳米级特征的阵列，分布在光学波导表面平行方向上。该设计提高了输出耦合效率，同时减少了与期望输出方向相反方向的光泄露。在近眼显示应用中，元光栅减少了波导/耦合器组件的外部光晕。此外，通过在光学波导和元光栅之间布置一系列防反射层，整个组件对用户而言更加透明，从而改善了增强现实显示应用中的现实世界可见性。

**Key Innovation (核心创新)**:  
1. 采用元光栅作为光学波导的输出耦合器，通过二维复制纳米级特征阵列实现光的输出耦合。
2. 元光栅设计减少了与期望输出方向相反方向的光泄露，提高了输出耦合效率。
3. 在光学波导和元光栅之间布置防反射层，提升了组件的透明度，改善了现实世界可见性。
4. 该设计减少了波导/耦合器组件的外部光晕，适用于近眼显示设备。
5. 通过纳米级特征阵列的精确控制，实现了更均匀的光输出分布。
6. 该技术特别适用于增强现实(AR)应用，在透明性和显示效果之间取得了更好的平衡。
7. 预期应用于头戴式显示器，提供更清晰、更自然的混合现实视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616051)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267052)**
<br/><br/>

---


<br/>

### 19. 用于无缝多媒体跳过的生成式过渡

**Title (EN)**: GENERATIVE TRANSITIONING FOR SEAMLESS MULTIMEDIA SKIPPING  
**Pub. No.**: US20260270535

**Applicant**: GOOGLE LLC  
**Inventor**: [Brett Barros](https://patents.google.com/?inventor=Brett+Barros&country=US&num=100&sort=new), [Michael Ryan Dorsey](https://patents.google.com/?inventor=Michael+Ryan+Dorsey&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明描述了利用生成模型（GM）来总结被跳过的多媒体内容部分，并将这些被总结的部分作为多媒体内容跳过部分的过渡进行渲染。系统处理器可以：在多媒体内容播放期间，接收从当前部分跳转到不同部分的指示；使用GM处理多媒体内容中间部分对应的片段，生成中间部分的总结；并使中间部分的总结在恢复播放不同部分之前被渲染。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619868_1.jpg)

**Technical Field (技术领域)**:  
多媒体处理技术领域，具体涉及多媒体内容跳过时的生成式过渡生成。

**Background (发明背景)**:  
用户通过计算设备消费多媒体内容时，常常需要跳过不感兴趣的部分。然而，现有跳过方法会导致用户体验不连贯，且用户可能需要多次尝试才能找到目标内容。此外，现有方法如静态缩略图无法提供足够的上下文信息，导致计算和网络资源的浪费。

**Summary (发明总览)**:  
本发明提出利用生成模型在多媒体内容跳过时生成动态过渡总结，以提供上下文信息并实现更自然的过渡。具体实现包括：接收跳过指令后，使用生成模型处理被跳过部分的中间内容，生成总结，并在恢复播放前渲染该总结。相比现有技术，本发明通过动态生成适应用户跳过行为的总结，提供了更个性化和相关的内容过渡体验，同时优化了计算和网络资源的使用。

**Key Innovation (核心创新)**:  
1. 利用生成模型（GM）动态生成被跳过多媒体内容的总结，而不是依赖预定义的静态缩略图或标记。
2. GM输入不仅包括被跳过部分的中间内容，还可以结合前后内容片段，以生成更连贯的过渡总结。
3. 系统能够根据用户跳过行为（如跳过速度、跳过时长）以及内容相关性，智能调整生成的总结长度和细节。
4. 支持本地和远程生成模型的使用，以适应不同设备和网络条件下的处理需求。
5. 在多媒体内容播放前对特征进行预处理，以减少生成总结时的延迟，提高实时性。
6. 生成的总结可以是音频、文字或图像等多种形式，以适应不同类型的多媒体内容。
7. 该技术可应用于播客、有声书、视频等多种多媒体场景，为用户提供更流畅和个性化的跳过体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619868)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270535)**
<br/><br/>

---


<br/>

### 20. 连续昆虫传感系统与方法

**Title (EN)**: SYSTEMS AND METHODS FOR CONTINUOUS INSECT SENSING  
**Pub. No.**: US20260262616

**Applicant**: Google LLC  
**Inventor**: [Martin Sheridan](https://patents.google.com/?inventor=Martin+Sheridan&country=US&num=100&sort=new), [Jianyi Liu](https://patents.google.com/?inventor=Jianyi+Liu&country=US&num=100&sort=new), [Matthew Metlitz](https://patents.google.com/?inventor=Matthew+Metlitz&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
描述了用于连续昆虫传感的系统和方法。一个示例方法包括：在分离器接收包含一个或多个昆虫的流；将昆虫分离成单列流；使用传感器检测单列流中的昆虫；并根据检测到的每个昆虫递增计数器。一个示例系统包括：定义昆虫流动路径的通道；位于流动路径内并用于接收通道内昆虫流的分离器，分离器用于将昆虫分离成单列流；用于检测单列流中昆虫的传感器；以及与传感器通信处理器。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617532_1.jpg)

**Technical Field (技术领域)**:  
昆虫大规模饲养领域，具体涉及连续昆虫蛹传感技术。

**Background (发明背景)**:  
昆虫幼虫的大规模饲养通常需要大量人工操作。技术人员需要手动添加卵或幼虫到托盘中，并确定食物和水的添加量。定期观察幼虫生长情况，并在幼虫成熟为蛹后转移到其他环境。整个过程涉及大量人工操作，如搬运容器、清洗可重复使用的部件等。现有技术缺乏自动化解决方案，难以高效跟踪饲养效果和识别问题。

**Summary (发明总览)**:  
本发明提出了一种用于连续昆虫蛹传感的系统和方法。通过分离器将昆虫蛹流分离成单列流，并使用传感器进行检测和计数。该系统能够准确计数昆虫蛹，并可识别其大小、性别和物理异常等特征。相较于传统人工操作，本发明实现了从饲养环境到转移过程的自动化计数和跟踪，提升了效率并减少了人为错误。

**Key Innovation (核心创新)**:  
1. 采用机械分离器将昆虫蛹流分离成单列流，确保每个蛹都能被单独检测。
2. 使用摄像头作为传感器，通过连续拍摄单列流并应用光学流技术，实现对昆虫蛹的精确计数和跟踪。
3. 识别系统能够检测每个昆虫蛹的大小、性别以及是否存在物理异常（如畸形、死亡等），提供详细的个体信息。
4. 处理器与传感器通信，实时接收传感器信号并生成每个昆虫蛹的记录，包括图像和计数信息，实现从源头到目的地的全程跟踪。
5. 系统能够存储昆虫蛹的批次或容器编号，支持溯源和关联分析，便于快速识别饲养过程中的潜在问题。
6. 该技术可实现从饲养环境到转移过程的完全自动化计数和转移，减少人工操作，提高效率并降低劳动成本。
7. 应用于昆虫大规模饲养场景时，可帮助提高饲养计划的追踪精度，快速发现异常情况并采取相应措施。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617532)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260262616)**
<br/><br/>

---


<br/>

### 21. 基于嵌入摘要的内容推荐

**Title (EN)**: CONTENT RECOMMENDATION BASED ON EMBEDDING SUMMARIZATION  
**Pub. No.**: US20260267894

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Shaoguang YAN](https://patents.google.com/?inventor=Shaoguang+YAN&country=US&num=100&sort=new), [Yunqing Xia](https://patents.google.com/?inventor=Yunqing+Xia&country=US&num=100&sort=new), [Dong Wang](https://patents.google.com/?inventor=Dong+Wang&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明提出了一种基于嵌入摘要的内容推荐方法。获取包含基本输入和上下文输入的文本输入，其中基本输入包括候选内容项。生成与基本输入对应的嵌入序列以及与上下文输入对应的嵌入序列。通过对基本输入的嵌入序列执行池化操作生成池化嵌入。使用摘要操作对上下文输入的嵌入序列进行处理，以获得代表上下文输入的代表性嵌入序列。基于基本输入的嵌入序列和上下文输入的代表性嵌入序列生成文本输入的文本表示。基于文本输入表示预测候选内容项被点击的概率。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616963_1.jpg)

**Technical Field (技术领域)**:  
推荐系统；自然语言处理；嵌入技术

**Background (发明背景)**:  
随着网络技术的发展和信息的快速增长，推荐系统在许多在线服务中变得越来越重要。现有推荐系统通常基于用户兴趣进行个性化推荐，但处理长文本输入时，传统基于Transformer的模型存在计算复杂度高、预测延迟大的问题。

**Summary (发明总览)**:  
本发明提出了一种基于嵌入摘要的内容推荐方法，通过引入池化层和摘要层来优化推荐过程。首先生成基本输入和上下文输入的嵌入序列，然后通过池化操作提取基本输入的关键信息，并通过摘要操作从上下文输入中提取代表性嵌入。最后，将处理后的嵌入输入后续Transformer层进行进一步处理，以生成文本表示并预测点击概率。这种方法减少了需要处理的嵌入数量，从而降低了计算复杂度并缩短了预测延迟。

**Key Innovation (核心创新)**:  
1. 引入池化层对基本输入的嵌入序列进行池化操作，提取关键信息，生成池化嵌入。
2. 通过摘要操作处理上下文输入的嵌入序列，生成代表性嵌入序列，减少后续处理所需的嵌入数量。
3. 在点击概率预测模型中结合池化嵌入和代表性嵌入，生成文本输入表示，提高预测效率。
4. 采用多阶段训练方法，确保嵌入层生成高质量的嵌入序列，以便在摘要操作中有效选择关键嵌入。
5. 通过减少Transformer层的数量和自注意力计算量，降低预测延迟，适用于长文本输入场景。
6. 模型架构在嵌入层和底层Transformer层之间加入池化层和摘要层，优化了嵌入处理流程。
7. 该方法可应用于新闻、视频、产品等推荐系统，在处理大规模数据和长文本输入时提供更高效的推荐服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616963)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267894)**
<br/><br/>

---


<br/>

### 22. 基于验证的代理代码生成

**Title (EN)**: AGENTIC CODE GENERATION WITH VALIDATION  
**Pub. No.**: US20260267621

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Shikhar Mathur](https://patents.google.com/?inventor=Shikhar+Mathur&country=US&num=100&sort=new), [Derek Koh](https://patents.google.com/?inventor=Derek+Koh&country=US&num=100&sort=new), [Dharmen Mahendra Mehta](https://patents.google.com/?inventor=Dharmen+Mahendra+Mehta&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
响应于以自然语言接收的数字输入，本发明示例为生成式机器学习模型（GMLM）制定指令，该指令包括输入验证子指令和代码生成子指令。通过GMLM对数字输入和代码生成子指令的处理，示例生成并输出编程语言的代码，该代码对应于接收的自然语言输入。通过GMLM对输入验证子指令和代码的处理，示例检测数字输入中未经验证的部分。示例可以从GMLM生成的代码执行中排除数字输入的未经验证部分。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616669_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及代理系统，具体涉及生成式机器学习模型在代理系统中的应用。

**Background (发明背景)**:  
自动化代理能够执行用户级任务并以电子方式执行操作，减少或无需人工干预。现有的技术问题包括如何减少用户输入负担，如何确保用于减少用户输入的信息符合用户的非显性偏好，以及如何提高生成式机器学习模型生成内容的可靠性和安全性。

**Summary (发明总览)**:  
本发明提出了一种基于输入增强代理和多个输入增强子代理（分析代理）的解决方案，以生成符合用户非显性偏好的输入增强数据。输入增强代理与生成式机器学习模型（GMLM）交互，生成并验证代码，同时防止恶意语句注入。子代理通过数据分析和机器学习生成用户偏好表示，这些表示被用于指导任务代理执行任务，从而减少用户输入需求并提高任务执行的准确性。

**Key Innovation (核心创新)**:  
1. 通过输入增强代理与生成式机器学习模型（GMLM）交互，生成符合用户非显性偏好的输入增强数据。
2. 利用多个输入增强子代理（分析代理）并行处理不同类型的数据分析请求，生成多样化的用户偏好表示。
3. 在GMLM生成的代码中嵌入验证机制，防止恶意语句注入，确保代码的安全性和可靠性。
4. 通过机器学习算法将原始数据转换为易于处理的格式（如嵌入或向量），以捕捉用户的历史行为模式。
5. 将学习结果存储在低延迟数据存储中，以便在在线或实时环境中快速访问和使用。
6. 将用户偏好应用于任务执行，例如控制车辆导航、调整用户界面设置或改进推荐引擎。
7. 本专利可应用于智能助手、自动驾驶车辆和个性化推荐系统等领域，提供更智能、更安全的用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616669)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267621)**
<br/><br/>

---


<br/>

### 23. 电子设备的声学传输通道

**Title (EN)**: Acoustic Transmission Channel for an Electronic Device  
**Pub. No.**: US20260270611

**Applicant**: Google LLC  
**Inventor**: [Shengyin Ding](https://patents.google.com/?inventor=Shengyin+Ding&country=US&num=100&sort=new), [Chuan-Hsien Cheng](https://patents.google.com/?inventor=Chuan-Hsien+Cheng&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明提供了一种用于电子设备的声学结构，用于将内部音频驱动器的音频传输至外部环境。该声学结构包括一个声学通道，该通道将内部音频驱动器与位于外壳周边的声学出口流体耦合。声学通道的入口靠近音频驱动器，呈三角形，并沿倾斜角度延伸至声学出口，以绕过相邻的内部空间来引导声波。声学通道具有不对称的侧边界，包括一个基本平直的第一壁和一个间隔开的第二壁，第二壁具有曲线轮廓。曲线轮廓的特点是交替的正向和负向曲率。这种几何配置有助于流体动力学传输。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619949_1.jpg)

**Technical Field (技术领域)**:  
电子设备声学设计；声波传输通道；紧凑型设备音频优化

**Background (发明背景)**:  
随着电子设备（如智能手机和平板电脑）内部组件的集成度提高，音频驱动器和声学传输路径的空间布局受到限制。现有技术难以在紧凑空间内实现均匀且清晰的声场分布，尤其在设备被不同方式握持或放置时。

**Summary (发明总览)**:  
本发明提出了一种用于电子设备的声学传输通道设计，通过将音频驱动器与设备周边的声学出口通过一个倾斜的声学通道连接，解决了紧凑空间内的声波传输问题。该设计利用不对称的侧边界和曲线轮廓来优化声波传输路径，从而实现更均匀的声场分布和更少的声能损失。

**Key Innovation (核心创新)**:  
1. 采用三角形入口设计的声学通道，有效引导声波绕过内部组件（如摄像头），实现声波的定向传输。
2. 使用不对称的侧边界设计，包括一个平直的第一壁和一个具有交替正负曲率的第二壁，优化声波传输路径。
3. 通过曲线轮廓的声学通道壁面设计，平滑引导声波绕过内部空间，减少声波反射和能量损失。
4. 声学通道的横截面深度保持恒定，确保声波传输的稳定性并简化制造工艺。
5. 该设计允许在紧凑的设备内部实现更高效的声学传输，同时保持设备结构的紧凑性和完整性。
6. 通过优化声波传输路径，扩展了外部听音区域，使用户在不同设备位置下都能获得一致的音量和清晰度。
7. 该技术可应用于智能手机、平板电脑等便携式设备，提升音频输出质量并优化设备内部空间利用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619949)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270611)**
<br/><br/>

---


<br/>

### 24. 使用人工智能优化大规模代码迁移的提示

**Title (EN)**: OPTIMIZING PROMPTS FOR LARGE-SCALE CODE MIGRATION USING ARTIFICIAL INTELLIGENCE  
**Pub. No.**: US20260267636

**Applicant**: Google LLC  
**Inventor**: [Daniele Codecasa](https://patents.google.com/?inventor=Daniele+Codecasa&country=US&num=100&sort=new), [Valeriya Kharatyan](https://patents.google.com/?inventor=Valeriya+Kharatyan&country=US&num=100&sort=new), [Stoyan Nikolov](https://patents.google.com/?inventor=Stoyan+Nikolov&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本系统接收用户查询以执行源代码的至少一项代码迁移操作，并将与用户查询相关的提示作为输入提供给第一个训练用于生成提示的人工智能模型，该模型用于执行代码迁移操作。系统从第一个AI模型获取提示，从第二个AI模型获取每个提示对应的源代码迁移版本，以及基于提示的代码迁移操作预测的验证错误数量。系统通过确定迁移版本具有最低预测验证错误数来选择一个优化的迁移版本，并提供该优化的迁移版本。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616684_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及人工智能技术领域，具体为使用人工智能优化大规模代码迁移的提示生成。

**Background (发明背景)**:  
人工智能（如大语言模型）的开发和应用已经彻底改变了多个行业，通过提供高度复杂自然语言处理能力来提升用户体验。然而，AI模型对用户查询的理解程度和响应相关性直接影响其效果。在代码迁移场景中，用户查询或提示的模糊性可能导致AI模型忽略需要更新的代码部分。此外，全局更新指令可能引发不必要的重复操作，浪费计算资源并降低系统效率。

**Summary (发明总览)**:  
本发明通过引入一个专门生成优化提示的AI模型来改进大规模代码迁移过程。该模型基于用户查询生成优化的提示，供执行代码迁移的第二个AI模型使用。通过这种方式，系统能够减少用户需要提供的不同提示数量，降低AI模型被访问的频率，从而节省计算资源并避免重复的代码迁移操作。优化的提示确保只对需要更新的代码部分进行操作，从而提高整体效率。

**Key Innovation (核心创新)**:  
1. 引入双AI模型架构：一个AI模型专门用于生成优化的代码迁移提示，另一个AI模型根据提示执行实际的代码迁移操作。
2. 基于用户查询动态生成提示：第一个AI模型根据用户输入的初始查询生成多个提示选项，以适应不同的代码迁移需求。
3. 优化提示选择机制：通过评估每个提示对应的代码迁移版本中预测的验证错误数量，系统能够自动选择最优的提示。
4. 减少重复操作：优化的提示确保代码迁移操作只针对尚未更新的代码部分进行，避免不必要的重复更新。
5. 提高资源利用效率：通过减少AI模型被访问的次数和避免重复操作，系统显著降低了计算资源的消耗。
6. 提升迁移准确性：优化的提示设计使得代码迁移结果更符合用户预期，减少因提示不当导致的错误。
7. 应用于企业级代码库迁移：此技术特别适用于大型软件项目或企业级应用，能够在迁移过程中保持代码质量和一致性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616684)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267636)**
<br/><br/>

---


<br/>

### 25. 生成神经网络的测试时自增强扩展

**Title (EN)**: SELF-ENHANCED TEST-TIME SCALING OF GENERATIVE NEURAL NETWORKS  
**Pub. No.**: US20260268124

**Applicant**: Google LLC  
**Inventor**: [Jiefeng Chen](https://patents.google.com/?inventor=Jiefeng+Chen&country=US&num=100&sort=new), [Jie Ren](https://patents.google.com/?inventor=Jie+Ren&country=US&num=100&sort=new), [Sercan Omer Arik](https://patents.google.com/?inventor=Sercan+Omer+Arik&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明涉及用于响应请求生成输出序列的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。方法包括：接收输出序列的请求；并行生成多个候选输出序列；从多个候选输出序列中选择一个选定的候选输出序列；并根据请求提供选定的候选输出序列。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617215_1.jpg)

**Technical Field (技术领域)**:  
本发明属于人工智能领域，具体涉及生成神经网络及其推理系统。

**Background (发明背景)**:  
生成神经网络用于生成文本、音频或图像等输出序列。现有技术中，生成任务通常依赖重复采样或奖励模型评分等方法，但这些方法存在计算效率低和性能提升有限的问题。
本发明旨在解决生成神经网络在推理阶段计算扩展效率低下的问题，特别是在需要高质量输出序列的任务中。

**Summary (发明总览)**:  
本发明提出了一种基于生成神经网络的推理系统，通过自验证和自调整机制提升推理时的计算扩展效率。该系统能够在消耗更多计算资源时，生成更高质量的输出序列，例如更相关、更具信息量或更准确的结果。
与传统的重复采样或奖励模型评分方法相比，本发明在相同准确度下显著降低了计算资源消耗，同时在复杂规划和推理任务中表现出色。

**Key Innovation (核心创新)**:  
1. 采用自验证和自调整机制，使生成神经网络在推理阶段能够根据计算资源动态调整输出质量，从而提高计算扩展效率。
2. 通过并行生成多个候选输出序列，并从中选择最优结果，提升输出序列的整体质量。
3. 引入自回归Transformer架构，利用堆叠注意力层和输出子网络生成评分分布，从而实现更精准的输出选择。
4. 支持多模态输入输出，包括文本、图像和音频等，使得系统能够处理更广泛的生成任务。
5. 在推理阶段通过调整计算资源分配，实现与现有技术相比更高的输出质量提升，例如在NATURAL PLAN和LiveBench Reasoning基准测试中达到8.7%的准确度提升。
6. 应用于对话系统、机器翻译、自然语言处理和计算机辅助医疗诊断等领域，能够在复杂任务中提供更准确和有用的输出。
7. 通过减少计算资源消耗同时提升输出质量，为需要高效生成高质量内容的应用场景提供独特价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617215)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268124)**
<br/><br/>

---


<br/>

### 26. 基于动态约束和资源的AI部署配置方法

**Title (EN)**: DYNAMIC CONSTRAINT- AND RESOURCE-BASED ARTIFICIAL INTELLIGENCE (AI) DEPLOYMENT PROVISIONING  
**Pub. No.**: US20260268207

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Cedric Alexis Damien VIDAL](https://patents.google.com/?inventor=Cedric+Alexis+Damien+VIDAL&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明涉及用于基于动态约束和资源的AI部署配置的方法、设备及产品，包括：接收在云计算环境中创建AI部署的请求，其中请求包含用于选择要在AI部署中执行的模型的一个或多个约束；响应请求，确定云计算环境的资源可用性；基于资源可用性和AI部署的一个或多个优化目标生成部署规范，包括识别满足约束且基于资源可用性能够在云计算环境中执行的模型；并在云计算环境中基于部署规范生成AI部署。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617305_1.jpg)

**Technical Field (技术领域)**:  
云计算；人工智能；资源管理；部署优化

**Background (发明背景)**:  
云计算平台为用户提供计算资源以支持其AI部署。然而，用户在创建AI部署时通常需要指定具体的模型版本和配置，这可能导致部署失败，例如由于资源不足或区域限制。此外，用户在排查部署失败原因时可能面临困难，并需要花费大量时间修改部署规范。

**Summary (发明总览)**:  
本发明提出了一种基于动态约束和资源的AI部署配置方法，通过接收用户提供的模型约束和优化目标，结合部署时的资源可用性自动生成部署规范。该方法避免了用户手动指定所有配置细节，提升了部署成功率并优化了资源利用。与传统方法相比，本发明能够根据实时资源状况调整部署策略，减少因资源不足导致的部署失败。

**Key Innovation (核心创新)**:  
1. 通过接收用户定义的模型约束（如版本、性能指标等），系统能够根据约束条件筛选合适的AI模型。
2. 结合云计算环境的实时资源可用性数据，系统能够动态调整部署策略，确保部署在资源充足的情况下进行。
3. 基于用户设定的优化目标（如成本、延迟、吞吐量等），系统自动优化部署规范以实现最佳性能。
4. 采用自动化生成部署规范的方法，减少了用户手动配置的工作量，降低了因配置错误导致的部署失败风险。
5. 通过实时监控资源变化，系统能够及时调整部署策略，适应云计算环境中资源动态变化的特点。
6. 该方法适用于需要快速部署AI模型且对资源利用率有高要求的场景，如大规模机器学习任务或实时数据分析应用。
7. 通过简化用户操作流程并提高部署成功率，本发明提升了用户体验，增加了云计算平台的用户粘性和平台收入。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617305)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268207)**
<br/><br/>

---


<br/>

### 27. 机器人重新存放被转移库存的系统与方法

**Title (EN)**: Robotic re-stowing of relocated inventory  
**Pub. No.**: US12729064

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Yvetta Pols Sandhu](https://patents.google.com/?inventor=Yvetta+Pols+Sandhu&country=US&num=100&sort=new), [Julie Mitchell](https://patents.google.com/?inventor=Julie+Mitchell&country=US&num=100&sort=new), [Yashoda Dadkar](https://patents.google.com/?inventor=Yashoda+Dadkar&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
本发明描述了用于机器人重新存放被转移库存的系统与方法。在一些实施例中，可确定位于处理设施第一区域的第一托盘包含运往处理设施第二区域的第一物品。第一托盘由第一传送系统的第一扫描器扫描，以确定其运往第二区域。第一传送系统将第一托盘从第一区域运输到第二区域。第一托盘可被机器人存放在第二区域的第一存储舱中。装载第一存储舱的第一机器人驱动单元将其运输到第二区域的第一拣选站。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486363164_1.jpg)

**Technical Field (技术领域)**:  
机器人仓储技术领域，具体涉及自动化仓储系统中库存物品的重新存放与运输。

**Background (发明背景)**:  
在异构机器人处理设施中，机器人驱动系统用于在位置之间移动物品或物品容器。机器人手臂通过从一个位置取出物品并放置到目标位置来对物品进行分类。然而，现有系统可能缺乏对物品运输路径的智能规划，导致效率低下。此外，机器人与存储设备之间的协调可能存在不足，影响整体操作流畅性。本发明旨在解决这些问题，通过优化物品重新存放流程来提高处理效率。

**Summary (发明总览)**:  
本发明提出了一种机器人重新存放被转移库存的方案。其核心思路是使用机器人系统自动识别、运输和存放需要重新存放的物品。具体实现路径包括：通过扫描识别物品运输路径，利用传送系统将物品运输到目标区域，并由机器人将物品存放在存储舱中。随后，机器人驱动单元将存储舱运输到拣选站进行后续处理。本发明相较于现有技术的主要改进在于实现了物品运输和存放的自动化与智能化，提高了仓储操作的效率和准确性。

**Key Innovation (核心创新)**:  
1. 通过扫描系统智能识别物品运输路径，确保物品被准确运送到目标区域。
2. 利用机器人自动将物品存放在存储舱中，减少人工干预，提高存放效率。
3. 机器人驱动单元与存储舱的协同工作，实现物品在仓储设施内的自动化运输。
4. 在目标区域设置拣选站，优化物品重新存放后的处理流程。
5. 通过自动化流程减少人为错误，提高仓储操作的准确性和可靠性。
6. 该方案可应用于大型仓储设施或物流中心，尤其适用于需要频繁重新存放物品的场景。
7. 独特价值在于通过智能化和自动化手段提升仓储系统的整体效率和灵活性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486363164)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12729064)**
<br/><br/>

---


<br/>

### 28. 定制尺寸包装的自动化装载与打包系统

**Title (EN)**: Automated loading and packing for custom-sized packages  
**Pub. No.**: US12729028

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Wouter Van Der Steen](https://patents.google.com/?inventor=Wouter+Van+Der+Steen&country=US&num=100&sort=new), [Bert Heysse](https://patents.google.com/?inventor=Bert+Heysse&country=US&num=100&sort=new), [Bart De Smet](https://patents.google.com/?inventor=Bart+De+Smet&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
本发明公开了用于定制尺寸包装的自动化装载与打包的系统和方法。在一个实施例中，示例系统包括第一定制尺寸包装生成机，用于生成具有第一尺寸范围的包装；第二定制尺寸包装生成机，用于生成具有第二尺寸范围的包装；以及第一独立运输机器人，用于将物品运输至第一或第二定制尺寸包装生成机。第一和第二定制尺寸包装生成机与系统的物品导入部分解耦。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486363122_1.jpg)

**Technical Field (技术领域)**:  
物流自动化技术领域，具体涉及定制尺寸包装的自动化生成、运输和装载技术。

**Background (发明背景)**:  
随着在线购物的普及，订单履行过程变得日益复杂。例如，大型配送中心每天可能需要处理超过一百万个包裹，这对物流效率提出了更高要求。现有的订单履行操作，如拣选、分类和包装技术，存在效率低下的问题，需要大量人工操作。此外，不同形状和大小的物品需要定制尺寸的运输容器，这进一步增加了操作的复杂性。

**Summary (发明总览)**:  
本发明提出了一种用于定制尺寸包装的自动化系统，通过多个定制尺寸包装生成机与独立运输机器人协同工作，实现高效装载与打包。该系统通过解耦包装生成与物品导入部分，提升了操作的灵活性和效率。与传统方法相比，本发明能够根据物品尺寸自动选择或生成合适的包装容器，减少人工干预，提高物流处理速度。

**Key Innovation (核心创新)**:  
1. 采用多台定制尺寸包装生成机，分别处理不同尺寸范围的包装需求，实现包装尺寸的精确匹配。
2. 通过独立运输机器人将物品自动运输至相应的包装生成机，减少人工搬运环节，提高自动化程度。
3. 包装生成机与物品导入部分解耦设计，增强了系统的灵活性和可扩展性，适应不同规模和类型的物流中心。
4. 集成智能调度系统，根据物品尺寸、数量和目的地等信息，动态分配包装资源和运输路径，优化整体效率。
5. 采用模块化设计，便于维护和升级，降低运营成本。
6. 应用于大型配送中心和电商物流场景，能够处理高密度订单流，减少包装材料浪费，提高空间利用率。
7. 通过自动化和智能化手段，显著降低人工成本，提高物流处理速度，为大规模订单履行提供可靠解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486363122)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12729028)**
<br/><br/>

---


<br/>

### 29. 穿梭车轨道系统的自动化问题解决工作流程

**Title (EN)**: Automated problem solve workflows for shuttle rail systems  
**Pub. No.**: US12729071

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Diya Li](https://patents.google.com/?inventor=Diya+Li&country=US&num=100&sort=new), [Kenneth Edward Cecka](https://patents.google.com/?inventor=Kenneth+Edward+Cecka&country=US&num=100&sort=new), [Nadeem Hasan Syed](https://patents.google.com/?inventor=Nadeem+Hasan+Syed&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
本发明公开了用于穿梭车轨道系统和相关集装箱搬运设备的自动化问题解决工作流程的系统和方法。在一个实施例中，示例系统包括一个穿梭车和一个控制器。控制器被配置为确定穿梭车搭载有第一物品，穿梭车被配置为将第一物品运送到第一位置，确定第一物品未送达第一位置，并使穿梭车被引导至问题解决站。控制器还被配置为确定穿梭车在问题解决站卸载第一物品的集装箱，并使穿梭车在第一集装箱处卸载第一物品。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486363172_1.jpg)

**Technical Field (技术领域)**:  
物流自动化技术领域，具体涉及穿梭车轨道系统的自动化问题处理和货物搬运。

**Background (发明背景)**:  
随着在线购物的普及，订单履行和物流处理变得越来越复杂。例如，一个履行中心每天可能需要处理超过一百万个包裹。在这样的需求下，与订单和包裹处理相关的物流效率变得至关重要。现有的物流操作，如拣选、分类和包装技术，仍存在效率低下的问题，需要改进以减少人工干预。

**Summary (发明总览)**:  
本发明提出了一种用于穿梭车轨道系统的自动化问题解决方案。其核心思路是当穿梭车未能按计划送达物品时，系统自动识别问题并引导穿梭车至指定的问题解决站进行处理。通过这种方式，系统能够减少人工干预，提高物流处理效率。本发明相较于现有技术的主要改进在于引入了自动化的问题识别和解决机制，使得物流系统能够更智能地处理异常情况。

**Key Innovation (核心创新)**:  
1. 穿梭车搭载物品的自动检测与追踪技术，通过传感器和控制器实时监控物品位置和状态。
2. 问题识别算法，当穿梭车未能按计划送达物品时，系统自动触发问题解决流程。
3. 自动化引导机制，将穿梭车引导至指定的问题解决站，并确定卸载集装箱的位置。
4. 问题解决站的设计，包括智能分配卸载集装箱的算法，确保物品能够被正确处理。
5. 异常处理流程的优化，通过减少人工干预，提高物流处理效率和准确性。
6. 系统集成方案，将问题解决流程无缝集成到现有的物流管理系统中，确保整体操作的流畅性。
7. 本发明适用于大型物流中心和自动化仓库，能够显著提高货物处理效率，减少因异常情况导致的时间延误。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486363172)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12729071)**
<br/><br/>

---


<br/>

### 30. 通过将高复杂度编解码器降级为低复杂度编解码器处理媒体流以减少硬件资源占用

**Title (EN)**: Reducing utilization of a hardware resource by a media stream by downgrading from a high-complexity codec to a low-complexity codec to process the media stream  
**Pub. No.**: US12731596

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Madhusudan Kinthada Venkata](https://patents.google.com/?inventor=Madhusudan+Kinthada+Venkata&country=US&num=100&sort=new), [Siddharth Ray](https://patents.google.com/?inventor=Siddharth+Ray&country=US&num=100&sort=new), [Shivank Nayak](https://patents.google.com/?inventor=Shivank+Nayak&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
一种用于在资源受限设备上节省资源的方法，包括：(i) 识别资源受限设备上的媒体流，(ii) 检测到媒体流至少部分占用了资源受限设备上的硬件资源，且硬件资源占用量达到预定的硬件资源压力阈值，(iii) 在检测到占用量达到硬件资源压力阈值后，通过将资源受限设备用于处理媒体流的编解码器降级来减少媒体流对硬件资源的占用。还公开了其他各种方法、系统以及计算机可读介质。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486365956_1.jpg)

**Technical Field (技术领域)**:  
多媒体处理技术领域，具体涉及资源受限设备上的媒体编解码器资源优化。

**Background (发明背景)**:  
在资源受限的设备上处理媒体流时，高复杂度的编解码器会占用大量硬件资源，导致设备性能下降或能耗增加。
现有技术通常采用固定编解码器方案，无法根据实时资源占用情况动态调整。
这可能导致设备在处理高负载媒体流时出现卡顿或耗电过快的问题。
本发明旨在解决资源受限设备上媒体流处理时的硬件资源过度占用问题。

**Summary (发明总览)**:  
本发明提出了一种动态调整媒体流编解码器复杂度的技术方案。
当检测到硬件资源占用达到预设阈值时，系统会将当前使用的高复杂度编解码器降级为低复杂度编解码器。
这种动态调整机制能够有效减少媒体流对硬件资源的占用。
相较于传统固定编解码器方案，本发明能够更好地平衡媒体质量与硬件资源消耗。
该方法适用于各种资源受限设备，如智能手机、物联网设备和可穿戴设备。

**Key Innovation (核心创新)**:  
1. 引入硬件资源占用检测机制，实时监控媒体流对硬件资源的占用情况。
2. 设计了编解码器降级策略，当检测到资源占用超过阈值时，自动将高复杂度编解码器切换为低复杂度编解码器。
3. 通过预设的硬件资源压力阈值，实现对资源占用的精确控制，避免设备性能下降或能耗过高。
4. 提供了编解码器切换的平滑过渡机制，确保在降级过程中媒体流处理不出现中断或明显质量下降。
5. 适用于多种资源受限设备，包括智能手机、物联网设备和可穿戴设备，具有广泛的适用性。
6. 在保证基本媒体质量的前提下，显著降低媒体流对硬件资源的占用，延长设备续航时间。
7. 可应用于视频会议、直播和流媒体播放等场景，在资源受限环境下提供更稳定的媒体处理能力。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486365956)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12731596)**
<br/><br/>

---


<br/>

### 31. 无线数据传输中的干扰缓解

**Title (EN)**: Interference mitigation for wireless data transmission  
**Pub. No.**: US12732658

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Srikar Potta](https://patents.google.com/?inventor=Srikar+Potta&country=US&num=100&sort=new), [Santhosh Kumar Vojjala](https://patents.google.com/?inventor=Santhosh+Kumar+Vojjala&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
一种媒体播放系统可包含用于缓解干扰的功能。该系统可包括显示设备，例如智能电视，其可无线传输音频数据到一个或多个收听设备，例如耳塞、耳机等。该系统可使用遥控器的无线电来测量干扰，该测量位置远离智能电视，可能更接近收听设备。这种测量可能比仅在智能电视位置进行的干扰测量更能反映收听设备可靠接收数据包的能力。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486367125_1.jpg)

**Technical Field (技术领域)**:  
无线通信技术领域，具体涉及无线音频传输中的干扰检测与缓解技术。

**Background (发明背景)**:  
无线音频设备如耳塞、耳机等常用于接收来自智能电视等设备的音频数据。然而，无线传输过程中可能受到干扰，影响音频数据的可靠接收。现有的干扰检测方法通常仅在信号源位置进行测量，无法准确反映实际接收端的干扰情况。

**Summary (发明总览)**:  
本发明提出了一种通过遥控器无线电测量干扰的方法，以更准确地反映收听设备所处环境的干扰情况。该方法利用遥控器与智能电视共享的无线频段，在遥控器位置进行干扰测量，从而更好地评估收听设备的接收性能。本发明相较于传统方法，通过在更接近收听设备的位置进行干扰测量，提高了干扰检测的准确性。

**Key Innovation (核心创新)**:  
1. 利用遥控器的无线电模块作为干扰测量点，位置更接近实际收听设备，从而提供更准确的干扰数据。
2. 通过在智能电视和遥控器之间共享无线频段，实现对干扰环境的同步监测。
3. 采用遥控器作为分布式干扰传感器，扩展了干扰检测的范围和精度。
4. 通过分析遥控器测量的干扰数据，优化音频数据的传输参数，提高数据传输的可靠性。
5. 该方法可应用于家庭影院系统或无线耳机等场景，提升无线音频传输的稳定性和用户体验。
6. 通过在遥控器上集成干扰测量功能，无需额外硬件，降低了系统复杂度和成本。
7. 推测本专利可应用于智能家居和无线音频设备中，提供更可靠的无线音频传输解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486367125)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12732658)**
<br/><br/>

---


<br/>

### 32. 地理围栏引导导航

**Title (EN)**: Guided navigation into geofences  
**Pub. No.**: US12732777

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Raj Kumar Raj Joseph](https://patents.google.com/?inventor=Raj+Kumar+Raj+Joseph&country=US&num=100&sort=new), [Jagrati Shringi](https://patents.google.com/?inventor=Jagrati+Shringi&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
本发明描述了用于引导导航进入地理围栏的设备和相关技术。在各种示例中，运行在移动设备上的应用程序的图形用户界面（GUI）可显示围绕第一交付或取货位置的第一个地理围栏。移动设备的报告位置可在GUI上显示。确定第一导航方向指示行走进入第一个地理围栏的方向，并在GUI上显示指示第一导航方向的第一方向指示器。确定移动设备已进入第一个地理围栏。基于移动设备已进入第一地理围栏，移动设备可生成第一确认数据，指示已完成的交付至第一交付地址。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486367255_1.jpg)

**Technical Field (技术领域)**:  
物流配送技术领域，具体涉及地理围栏导航和交付确认。

**Background (发明背景)**:  
大规模配送平台通常采用不同的运输方法。在最后一公里配送中，配送人员需要将包裹配送到各种不同的位置。在某些情况下，配送人员需要向配送管理系统确认已正确送达指定地址或配送地点。现有的配送确认方法可能存在效率低下和准确性不足的问题。

**Summary (发明总览)**:  
本发明提供了一种基于地理围栏的导航和交付确认方法。通过在移动设备的用户界面上显示地理围栏和导航指示，指导配送人员进入指定区域，并在进入地理围栏后自动生成交付确认数据。该方法通过实时定位和导航技术，提高了配送过程的准确性和效率，减少了人工确认的误差。

**Key Innovation (核心创新)**:  
1. 通过移动设备的GUI显示地理围栏和当前位置，为配送人员提供直观的导航指引。
2. 利用实时定位技术，动态更新导航方向，确保配送人员准确进入目标地理围栏。
3. 在移动设备进入地理围栏时，自动生成交付确认数据，减少人工确认的误差和延迟。
4. 通过图形化界面展示导航方向和地理围栏边界，提升用户体验和操作便捷性。
5. 结合地理围栏技术，实现对配送过程的精细化管理和监控。
6. 该方法可应用于快递、外卖等配送场景，提高配送效率和准确性。
7. 通过自动化确认机制，降低配送错误率，提升整体配送服务质量。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486367255)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12732777)**
<br/><br/>

---



**Total Patents**: 32  
**Last Updated**: 20260912

---

The Patent Scoop Trio
