---
layout: post
title: "Apple 专利小快报 2026-09-27"
date: 2026-09-27 13:43:05 +0800
categories: Apple
---

**New Patents**: 31  

---


<br/>

### 1. 电子设备的通信距离扩展

**Title (EN)**: RANGE EXTENSION FOR ELECTRONIC DEVICES  
**Pub. No.**: US20260292528

**Applicant**: Apple Inc.  
**Inventor**: [Arun Vijayakumari MAHASENAN](https://patents.google.com/?inventor=Arun+Vijayakumari+MAHASENAN&assignee=Apple&country=US&num=100&sort=new), [Sudhir K. BAGHEL](https://patents.google.com/?inventor=Sudhir+K.+BAGHEL&assignee=Apple&country=US&num=100&sort=new), [Venkateswara Rao MANEPALLI](https://patents.google.com/?inventor=Venkateswara+Rao+MANEPALLI&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种无需修改无线硬件即可扩展设备无线通信距离的技术。距离扩展操作可以通过软件在发送设备或接收设备上执行。在发送设备上，距离扩展操作包括在信号调制前通过修改数据本身来减少数据表示的符号空间。在接收设备上，距离扩展操作包括累积包含错误的帧，并通过累积的帧估计原始帧。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487358503_1.jpg)

**Technical Field (技术领域)**:  
无线通信技术领域，具体涉及电子设备的通信距离扩展技术。

**Background (发明背景)**:  
电子设备通常配备无线电组件用于传输无线信号，但无线电组件的物理硬件限制了通信距离。现有的无线电技术如Thread和Zigbee在便携设备中应用广泛，但这些设备的位置变化和信号环境的变化可能导致通信距离不足的问题。

**Summary (发明总览)**:  
本发明提出了一种通过软件实现无线通信距离扩展的方法，主要通过在发送端减少数据表示的符号空间和在接收端累积包含错误的帧来估计原始数据。该方法无需修改现有无线电硬件，能够在低速率无线个人区域网络（LR-WPAN）通信中应用，如Thread或Zigbee通信。本发明特别适用于紧急模式、低信号强度和高误码率等场景。

**Key Innovation (核心创新)**:  
1. 通过软件在发送设备上减少数据表示的符号空间，具体方法是在信号调制前修改数据本身，从而降低对硬件的依赖。
2. 在接收设备上，通过累积包含错误的帧并从中估计原始帧，提升在低信号强度和高误码率条件下的数据恢复能力。
3. 无需对现有无线电硬件进行任何修改，仅通过软件实现通信距离的扩展，降低了实施成本和技术门槛。
4. 特别适用于紧急模式（如SOS模式），在设备发送求助信号时提高信号被附近设备检测到的概率。
5. 适用于多种无线电技术，包括但不限于Thread和Zigbee通信标准，扩展了应用场景。
6. 在便携设备（如智能手机）和固定设备（如智能音箱、机顶盒和物联网设备）中均能有效应用，适应性强。
7. 在低信号强度和高误码率条件下提供可靠的通信距离扩展功能，提升了无线通信的可靠性和覆盖范围。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358503)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292528)**
<br/><br/>

---


<br/>

### 2. 用于定向泄漏或调节应用的稳定电磁阀

**Title (EN)**: Stable Electro-Magnetic Valve for Intentional Leak or Tuning Applications  
**Pub. No.**: US20260292389

**Applicant**: Apple Inc.  
**Inventor**: [Onur I. Ilkorur](https://patents.google.com/?inventor=Onur+I.+Ilkorur&assignee=Apple&country=US&num=100&sort=new), [Christopher Wilk](https://patents.google.com/?inventor=Christopher+Wilk&assignee=Apple&country=US&num=100&sort=new), [Scott C. Grinker](https://patents.google.com/?inventor=Scott+C.+Grinker&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种便携式电子设备，包括：具有形成包围换能器的内部腔室和从内部腔室延伸的开口的外壳壁的壳体；以及耦合到开口的电磁阀，该电磁阀包括一个在施加电压时被激励的固定部分，用于驱动可动部分在第一状态和第二状态之间移动，以关闭或打开开口。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487358349_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及电子设备中的电磁阀技术，具体为用于调节声学和热学性能的稳定电磁阀。

**Background (发明背景)**:  
电子设备（如台式电脑、扬声器、智能手机、耳机等）通常包含用于转换电声信号的换能器。由于这些设备的外形较为紧凑，换能器的性能可能受到影响，例如难以维持最佳音质。此外，耳机与耳道紧密密封可能导致不适或声学问题。

**Summary (发明总览)**:  
本发明提出了一种用于电子设备的稳定电磁阀，通过在两个空气腔之间建立可控的声学连接来调节系统性能或满足用户的声学和热舒适需求。该电磁阀可以调节换能器前腔与周围环境之间的通信，以减少耳道中的湿度和热量积聚，或通过调节耳道与耳机之间的声学和热学连接来提升舒适度。

**Key Innovation (核心创新)**:  
1. 采用电磁阀技术，通过电压激励固定部分驱动可动部分，实现对开口的精确控制。
2. 设计了双稳态电磁阀结构，可稳定保持在打开或关闭状态，适应不同的声学需求。
3. 可动部分采用滑动式设计，通过在开口处滑动来关闭或打开，实现对声学阻抗的调节。
4. 固定部分包含一对磁铁和线圈，通过磁力驱动钢制可动部分在第一状态和第二状态之间移动。
5. 在钢制可动部分的两端和磁铁之间设置阻尼元件，以优化运动平稳性和响应速度。
6. 开口设计为多个小孔，可动部分带有多个突起，通过覆盖不同数量的小孔来调节开度。
7. 该电磁阀可应用于耳机等便携设备，通过调节耳道与环境的连通性，提升佩戴舒适度和声学性能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358349)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292389)**
<br/><br/>

---


<br/>

### 3. 基于设备位置调整图像显示

**Title (EN)**: Adjusting Display of an Image based on Device Position  
**Pub. No.**: US20260289800

**Applicant**: Apple Inc.  
**Inventor**: [Pavel V. Dudrenov](https://patents.google.com/?inventor=Pavel+V.+Dudrenov&assignee=Apple&country=US&num=100&sort=new), [Felipe Bacim De Araujo E Silva](https://patents.google.com/?inventor=Felipe+Bacim+De+Araujo+E+Silva&assignee=Apple&country=US&num=100&sort=new), [Karol E. Czaradzki](https://patents.google.com/?inventor=Karol+E.+Czaradzki&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明公开了基于用户身体部位相对于设备显示位置来生成显示图像的设备、系统和方法。在一些实现中，设备包括图像传感器、显示器、非易失性存储器和处理器。方法包括通过图像传感器捕获用户身体部位的第一图像，基于第一图像确定身体部位相对于显示器的位置，并生成用于在显示器上呈现的第二图像。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487355490_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及增强现实和可穿戴设备领域，具体为基于用户身体部位位置调整显示图像的技术。

**Background (发明背景)**:  
现有设备通常配备图像传感器和显示器，用于捕捉和显示图像。然而，当用户的身体部位被设备遮挡时，直接观察变得困难。现有技术未能有效解决图像显示与实际身体部位位置不一致的问题，导致用户体验不佳。本发明旨在解决这一问题，通过调整图像显示位置来匹配用户身体部位的实际位置。

**Summary (发明总览)**:  
本发明提出了一种基于用户身体部位位置调整图像显示的方法。设备通过图像传感器捕捉用户身体部位的位置信息，并根据该位置信息调整图像显示，以确保图像与实际身体部位对齐。该方法通过动态调整图像位置，提升了用户在使用设备时的视觉体验，并解决了设备遮挡带来的视觉偏差问题。

**Key Innovation (核心创新)**:  
1. 通过图像传感器实时捕捉用户身体部位的位置信息，例如手部位置。
2. 基于捕捉到的位置信息，计算身体部位相对于设备显示器的相对位置。
3. 根据计算结果动态调整显示图像的位置，例如将手部图像向左或向右移动以匹配实际位置。
4. 采用非易失性存储器存储调整算法和用户偏好设置，确保快速响应和个性化体验。
5. 通过处理器执行图像处理和位置校准算法，实现实时图像调整。
6. 该技术可应用于增强现实（AR）设备、可穿戴设备以及智能手机等，提供更自然的视觉交互体验。
7. 特别适用于需要精确视觉对齐的场景，如远程协作、虚拟试穿等，提升用户的使用便利性和沉浸感。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355490)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289800)**
<br/><br/>

---


<br/>

### 4. 图案投影仪

**Title (EN)**: Pattern projector  
**Pub. No.**: US20260287835

**Applicant**: APPLE INC.  
**Inventor**: [Refael Della Pergola](https://patents.google.com/?inventor=Refael+Della+Pergola&assignee=Apple&country=US&num=100&sort=new), [Roei Remez](https://patents.google.com/?inventor=Roei+Remez&assignee=Apple&country=US&num=100&sort=new), [Assaf Avraham](https://patents.google.com/?inventor=Assaf+Avraham&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种光电子装置包括半导体基底和多个发射器阵列，这些发射器阵列配置为发射光学辐射束。光学基底安装在半导体基底上方。光学基底上的光学超表面包括多个光学孔径。每个孔径配置为接收、准直并分裂由相应发射器阵列发射的束，形成一组准直的子束，从而将这些准直子束以不同的角度导向目标，在目标上形成光斑图案。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
光电子技术；光学超表面；图案投影

**Background (发明背景)**:  
传统光学投影设备通常依赖复杂的光学系统来实现光束的准直和定向，这导致设备体积大且成本高。现有的微光学技术虽然能够实现小型化，但在光束控制和图案生成方面仍存在精度不足的问题。本发明旨在提供一种更紧凑且高效的光学图案投影方案。

**Summary (发明总览)**:  
本发明提出了一种基于光学超表面的图案投影装置，通过在半导体基底上集成多个发射器阵列，并在光学基底上布置光学超表面，实现对发射光束的精确控制。该装置利用光学孔径对光束进行准直和分裂，从而在目标上形成预定的光斑图案。与传统光学系统相比，本发明具有更小的体积和更高的光束控制精度。

**Key Innovation (核心创新)**:  
1. 采用光学超表面技术，通过微结构光学孔径实现对发射光束的精确准直和分裂。
2. 在半导体基底上集成多个发射器阵列，每个阵列对应一个光学孔径，实现多光束并行处理。
3. 通过设计光学超表面的微结构参数，控制每个子束的出射角度，从而在目标上形成预定的光斑图案。
4. 利用光学超表面的平面结构特性，显著减小了装置的体积和重量。
5. 实现了高精度的光束控制，能够在目标上生成复杂且精细的光学图案。
6. 该技术可应用于激光投影显示、3D 扫描和光学传感等领域，提供更高效的光学图案生成方案。
7. 通过优化光学孔径的设计，本发明能够在不同工作距离下保持图案的稳定性和清晰度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353327)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260287835)**
<br/><br/>

---


<br/>

### 5. 用于界面中空间对象相对表示和解歧的系统与方法

**Title (EN)**: System and Methods for Relative Representation of Spatial Objects and Disambiguation in an Interface  
**Pub. No.**: US20260287888

**Applicant**: Apple Inc.  
**Inventor**: [Patrick S. Piemonte](https://patents.google.com/?inventor=Patrick+S.+Piemonte&assignee=Apple&country=US&num=100&sort=new), [Wolf Kienzle](https://patents.google.com/?inventor=Wolf+Kienzle&assignee=Apple&country=US&num=100&sort=new), [Douglas Bowman](https://patents.google.com/?inventor=Douglas+Bowman&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本文描述并主张的实施例提供了一种用户与机器交互的系统和方法。在一个实施例中，系统接收来自移动机器用户输入，该输入指示或描述了世界中的某个对象。例如，用户可以通过手势指向对象，由视觉传感器检测；或者用户可以通过语音描述对象，由音频传感器检测。接收输入的系统随后确定用户指示的附近位置的对象。这种确定可能包括利用用户或自主/移动机器附近地理位置的已知对象。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及空间对象识别与解歧技术。

**Background (发明背景)**:  
在现有的用户与机器交互系统中，用户通常需要通过特定方式指示对象，例如手势或语音描述。然而，现有技术难以在复杂环境中准确识别用户所指对象，尤其当多个相似对象共存时。此外，现有系统在处理用户输入时，对环境上下文信息的利用不足，导致识别准确率较低。本发明旨在解决这些问题，通过结合用户输入和环境上下文信息，提高对象识别的准确性和效率。

**Summary (发明总览)**:  
本发明提供了一种用于用户与机器交互的系统和方法，通过接收用户对空间对象的指示输入，并结合环境上下文信息，确定用户所指的具体对象。系统利用视觉传感器或音频传感器捕捉用户输入，并结合用户位置附近的已知对象信息进行判断。与现有技术相比，本发明通过整合多源信息，提高了对象识别的准确性和鲁棒性。

**Key Innovation (核心创新)**:  
1. 利用视觉传感器捕捉用户手势输入，通过图像识别技术确定用户指向的对象。
2. 通过音频传感器接收用户语音描述，结合自然语言处理技术解析用户意图。
3. 结合用户地理位置信息，调用地理信息系统（GIS）数据库中的已知对象数据，提高识别准确性。
4. 采用多源信息融合算法，整合视觉、语音和地理信息，进行综合判断和对象解歧。
5. 系统能够动态更新环境上下文信息，适应动态变化的环境条件。
6. 通过机器学习模型不断优化识别算法，提高对复杂场景的适应能力。
7. 本发明可应用于增强现实（AR）、智能导航和机器人交互等领域，为用户提供更智能、更精准的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353387)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260287888)**
<br/><br/>

---


<br/>

### 6. 液体与连接检测

**Title (EN)**: LIQUID AND CONNECTION DETECTION  
**Pub. No.**: US20260291151

**Applicant**: Apple Inc.  
**Inventor**: [Eric B. Wankoff](https://patents.google.com/?inventor=Eric+B.+Wankoff&assignee=Apple&country=US&num=100&sort=new), [Peter J. Cameron](https://patents.google.com/?inventor=Peter+J.+Cameron&assignee=Apple&country=US&num=100&sort=new), [Mahmoud R. Amini](https://patents.google.com/?inventor=Mahmoud+R.+Amini&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及能够检测与对应连接器插入件的连接的连接器插座和连接器插座接口，能够检测连接器插座中的液体，并能够限制液体对连接器插座造成的损害。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
本专利属于连接器技术领域，具体涉及液体检测和连接检测技术。

**Background (发明背景)**:  
在电子设备中，连接器插座容易受到液体侵入，导致设备损坏或故障。
现有技术难以有效检测连接器插座中的液体并防止液体造成的损害。
本发明旨在提供一种能够检测液体并限制液体损害的连接器插座解决方案。

**Summary (发明总览)**:  
本发明提出了一种具有液体检测和连接检测功能的连接器插座设计。
通过在连接器插座中集成传感器和防护机制，实现对液体的检测和防护。
该设计能够在液体侵入时及时响应并限制损害，从而提高连接器的可靠性和耐用性。
相较于现有技术，本发明提供了更全面的液体防护和连接检测功能。

**Key Innovation (核心创新)**:  
1. 在连接器插座中集成液体传感器，能够实时检测液体侵入情况。
2. 设计了多层防护结构，包括防水密封和液体导流通道，以限制液体对内部电路的损害。
3. 通过电学信号变化检测连接器插入件与插座之间的连接状态，实现可靠的连接检测。
4. 集成了智能控制电路，能够在检测到液体时自动触发保护机制，如断开电路或发出警报。
5. 采用模块化设计，便于在现有连接器插座中集成液体检测和防护功能。
6. 该技术可应用于消费电子、汽车电子和工业设备等领域，提供可靠的液体防护和连接检测功能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356986)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260291151)**
<br/><br/>

---


<br/>

### 7. 用于头戴式显示系统的镜头安装结构

**Title (EN)**: Lens Mounting Structures for Head-Mounted Display Systems  
**Pub. No.**: US20260287908

**Applicant**: Apple Inc.  
**Inventor**: [Austin S Young](https://patents.google.com/?inventor=Austin+S+Young&assignee=Apple&country=US&num=100&sort=new), [Yinjuan He](https://patents.google.com/?inventor=Yinjuan+He&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
头戴式设备可具有提供显示图像的显示系统。这些显示图像通过波导传输到视窗供用户观看，波导具有输出耦合器。波导由头戴式支撑结构支撑，位于设备左侧的前后镜头之间以及右侧的前后镜头之间。前后镜头通过前置和/或后置安装方式安装到头戴式支撑结构上。前置镜头从前端安装到头戴式支撑结构中，并可由头戴式支撑结构中的具有前表面的对准架支撑。后置镜头则从后端安装到头戴式支撑结构中。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
头戴式显示技术领域，具体涉及镜头安装结构及波导支撑设计。

**Background (发明背景)**:  
头戴式显示设备需要精确的镜头定位以确保图像质量。现有技术中，镜头安装方式可能影响设备整体结构稳定性和装配效率。此外，波导的支撑方式对光学性能和用户体验有重要影响。本发明旨在提供一种更可靠、高效的镜头安装和波导支撑方案。

**Summary (发明总览)**:  
本发明提出了一种改进的头戴式显示系统镜头安装结构，通过前置和后置安装方式优化镜头定位精度。波导由专门的头戴式支撑结构固定，确保光学组件的稳定性和一致性。该设计简化了装配流程，提高了光学系统的整体性能。相较于传统方法，本发明在结构稳定性和装配效率方面有显著提升。

**Key Innovation (核心创新)**:  
1. 采用前置镜头安装方式，通过从前端安装镜头并使用对准架支撑，确保镜头定位精度和稳定性。
2. 设计了具有前表面的对准架，为前置镜头提供精确的定位基准，提升光学对准质量。
3. 引入后置镜头安装方式，从后端安装镜头，简化装配流程并减少对光学组件的潜在干扰。
4. 波导由专门的头戴式支撑结构固定，确保光学组件在设备中的稳定性和一致性。
5. 前后镜头的安装方式结合波导支撑设计，形成完整的光学系统集成方案，提升整体光学性能。
6. 该设计简化了装配流程，提高了生产效率，同时保证了光学系统的可靠性和稳定性。
7. 应用于增强现实（AR）和虚拟现实（VR）头戴式设备，可提供更清晰、更稳定的图像显示，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353409)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260287908)**
<br/><br/>

---


<br/>

### 8. 用于检测和识别AR/VR场景中特征的方法和设备

**Title (EN)**: Methods and Devices for Detecting and Identifying Features in an AR/VR Scene  
**Pub. No.**: US20260289814

**Applicant**: Apple Inc.  
**Inventor**: [Jeffrey S. Norris](https://patents.google.com/?inventor=Jeffrey+S.+Norris&assignee=Apple&country=US&num=100&sort=new), [Alexandre Da Veiga](https://patents.google.com/?inventor=Alexandre+Da+Veiga&assignee=Apple&country=US&num=100&sort=new), [Bruno M. Sommer](https://patents.google.com/?inventor=Bruno+M.+Sommer&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种方法包括获取由第一姿态表征的第一透视图像数据。该方法包括获取第一透视图像数据中像素的像素表征向量。该方法包括根据特征像素表征向量满足特征置信度阈值，识别第一透视图像数据中对象的特征。该方法包括在显示装置上显示第一透视图像数据以及与该特征对应的增强现实（AR）显示标记。该方法包括获取由第二姿态表征的第二透视图像数据。该方法包括将AR显示标记变换到与第二姿态相关的位置，以跟踪该特征。该方法包括在显示装置上显示第二透视图像数据，并根据变换保持显示与对象特征对应的AR显示标记。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487355506_1.jpg)

**Technical Field (技术领域)**:  
增强现实场景理解技术，具体涉及AR/VR场景中现实世界特征的检测与跟踪。

**Background (发明背景)**:  
在增强现实/虚拟现实（AR/VR）场景中检测和识别特征在技术和用户体验方面都存在挑战。例如，使用深度信息检测、识别和跟踪AR/VR场景中的现实世界特征存在困难。依赖深度信息不仅资源消耗大，而且由于现有方法无法很好地应对姿态信息的变化，导致无法提供准确可靠的AR/VR场景信息。这降低了设备向用户展示的场景特征数量和质量，如对象和特征识别信息及其测量信息，从而影响用户体验和与其他应用的集成。

**Summary (发明总览)**:  
本发明提出了一种基于透视图像数据检测和跟踪AR/VR场景中对象特征的方法。该方法通过分析像素表征向量识别场景中的特征，并使用AR显示标记进行标记和跟踪。通过获取不同姿态下的透视图像数据，动态调整AR显示标记的位置以保持对特征的持续跟踪。该方法无需依赖深度信息，通过像素表征向量和置信度阈值实现更准确和高效的AR/VR场景理解。

**Key Innovation (核心创新)**:  
1. 通过分析像素表征向量识别AR/VR场景中的对象特征，无需依赖深度信息，降低计算资源消耗。
2. 采用特征置信度阈值判断像素表征向量是否满足特征识别条件，提高识别的准确性和可靠性。
3. 通过动态调整AR显示标记的位置，实现对场景中对象特征的持续跟踪，适应不同姿态变化。
4. 利用平面拟合技术，将像素分组并拟合平面，进一步提高对场景中平面对象的识别精度。
5. 基于三维点云生成体素区域，生成空间的三维表示，并合成对应的二维平面图，提供更丰富的场景信息。
6. 该方法可应用于AR/VR设备中，实现更精准的虚拟内容与现实场景的对齐，提升用户体验。
7. 特别适用于需要精确定位和跟踪现实世界对象的应用场景，如AR导航、虚拟装配和远程协作等。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355506)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289814)**
<br/><br/>

---


<br/>

### 9. 基于触摸检测的像素刷新率调整

**Title (EN)**: Pixel Refresh Rate Adjustment Based on Touch Detection  
**Pub. No.**: US20260288282

**Applicant**: Apple Inc.  
**Inventor**: [Saman Saeedi](https://patents.google.com/?inventor=Saman+Saeedi&assignee=Apple&country=US&num=100&sort=new), [Amit Nayyar](https://patents.google.com/?inventor=Amit+Nayyar&assignee=Apple&country=US&num=100&sort=new), [Sagar R Vaze](https://patents.google.com/?inventor=Sagar+R+Vaze&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明主要涉及电子设备显示面板表面上的触摸检测与定位。电子设备可在检测到触摸存在时，通过限制显示面板像素的刷新率来响应，而无需重新编程显示面板的驱动电路。通过这种方式，电子设备可在不重新编程驱动电路的情况下，通过限制显示刷新率来确定检测到的触摸位置。电子设备通过在多个刷新周期内生成图像数据帧来限制刷新率，同时在限制刷新率时基本保持像素的行时间。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353819_1.jpg)

**Technical Field (技术领域)**:  
电子显示技术领域，具体涉及基于触摸检测的动态刷新率调整技术。

**Background (发明背景)**:  
现代电子设备通常配备触摸屏以实现用户交互。传统方法在检测到触摸时需要重新编程显示驱动电路，这增加了系统复杂性和功耗。此外，现有技术在处理触摸检测和定位时可能影响显示刷新率，导致图像质量下降或响应延迟。本发明旨在解决这些问题，通过一种无需重新编程驱动电路的方法来动态调整刷新率。

**Summary (发明总览)**:  
本发明提出了一种基于触摸检测的动态刷新率调整方法。当检测到触摸时，电子设备通过限制显示刷新率来降低功耗，同时保持触摸检测的准确性。具体实现方式是在检测到触摸后，将刷新周期减半，并在扩展的垂直消隐期间处理触摸信号。当没有触摸时，设备以更高的刷新率运行以提供更好的显示质量。本发明通过单刷新周期内调整刷新率，避免了图像显示中的伪影问题，并确保触摸检测和定位的实时性。

**Key Innovation (核心创新)**:  
1. 通过限制刷新率来响应触摸检测，无需重新编程显示驱动电路，降低了系统复杂性和功耗。
2. 在检测到触摸时，将刷新周期减半，并在扩展的垂直消隐期间处理触摸信号，确保触摸检测的实时性。
3. 在单刷新周期内调整刷新率，保持像素的行时间不变，避免了图像显示中的伪影问题。
4. 在没有触摸时，以更高的刷新率运行显示面板，提升显示质量。
5. 通过优化触摸信号处理时间，实现触摸检测快于触摸定位，提高系统响应速度。
6. 适用于多种电子设备，包括手机、平板电脑、可穿戴设备和虚拟现实设备等。
7. 在保持触摸检测精度的同时，提供了更流畅的显示体验和更低的功耗。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353819)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288282)**
<br/><br/>

---


<br/>

### 10. 用于校准显示器的用户界面

**Title (EN)**: USER INTERFACES FOR CALIBRATING A DISPLAY  
**Pub. No.**: US20260290279

**Applicant**: Apple Inc.  
**Inventor**: [Robert L. RIDENOUR](https://patents.google.com/?inventor=Robert+L.+RIDENOUR&assignee=Apple&country=US&num=100&sort=new), [Muralidhar M. SHENOY](https://patents.google.com/?inventor=Muralidhar+M.+SHENOY&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明主要涉及用于校准显示器的方法和用户界面，包括基于医疗成像显示标准校准显示器配置文件的方法和用户界面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487356021_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及显示器校准技术。

**Background (发明背景)**:  
电子设备通常配备显示器，用于多种用途。现有技术中，显示器校准方法通常较为繁琐且效率低下，例如需要复杂的用户界面或多次按键操作。此外，一些方法需要昂贵的专用设备，耗时较长，尤其对电池供电设备而言能耗较高。

**Summary (发明总览)**:  
本发明提供了一种更快速、更高效的显示器校准方法及用户界面。该方法通过与显示器、输入设备和测量仪器通信的计算机系统实现，基于医疗成像显示标准校准显示器配置文件。系统通过用户界面引导用户操作，自动识别测量仪器类型并执行校准过程，最终根据校准结果调整显示特性，确保符合医疗成像显示标准。

**Key Innovation (核心创新)**:  
1. 通过用户界面引导用户启动校准过程，简化操作步骤，减少用户认知负担。
2. 自动识别不同类型的测量仪器，并根据仪器类型显示相应的校准信息，提升校准过程的适配性和准确性。
3. 在校准过程中，通过显示特定视觉图案并接收测量仪器反馈的数据，实现对显示器视觉特性的精确测量和校准。
4. 基于校准结果自动调整显示器的视觉显示特性，确保校准后的显示器配置文件符合医疗成像显示标准。
5. 提供校准结果的实时反馈，使用户能够直观了解校准状态。
6. 减少对专用设备的依赖，降低校准成本，同时适用于电池供电设备，节省能耗。
7. 适用于医疗成像显示器的校准场景，确保图像显示的准确性和一致性，提升医疗诊断的可靠性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356021)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260290279)**
<br/><br/>

---


<br/>

### 11. 眼动追踪组件

**Title (EN)**: EYE-TRACKING ASSEMBLY  
**Pub. No.**: US20260288239

**Applicant**: Apple Inc.  
**Inventor**: [Ivan S. Maric](https://patents.google.com/?inventor=Ivan+S.+Maric&assignee=Apple&country=US&num=100&sort=new), [Eric Shyr](https://patents.google.com/?inventor=Eric+Shyr&assignee=Apple&country=US&num=100&sort=new), [James W. Sallay](https://patents.google.com/?inventor=James+W.+Sallay&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种头戴式电子设备包括光学模块框架、连接到光学模块框架并延伸在显示平面上的显示器，以及眼动追踪组件。眼动追踪组件包括连接到光学模块框架并围绕显示器周边布置的扁平电缆，例如柔性印刷电路板（FPC），以及电连接到扁平电缆并配置为将光线从显示器方向射出的发光二极管（LED）。扁平电缆定义了一个主要平面，该平面通常与显示器正交。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353772_1.jpg)

**Technical Field (技术领域)**:  
头戴式电子设备技术领域，具体涉及光学模块和眼动追踪组件。

**Background (发明背景)**:  
随着便携式计算技术的进步，头戴式设备能够为用户提供增强现实和虚拟现实（AR/VR）体验。这些设备通常包括显示器、镜框、镜头、光学组件、电池、马达、扬声器、传感器、摄像头等组件。然而，眼动追踪组件如果放置在用户的视野范围内，可能会造成视觉干扰。此外，制造此类光学模块可能复杂且成本高昂，需要在洁净室中组装以防止灰尘和其他污染物，导致组装复杂且成本高。因此，需要更简单、更经济的方法来制造光学模块和头戴式设备，同时在用户体验中不造成视觉干扰。

**Summary (发明总览)**:  
本发明提出了一种新型头戴式电子设备及其眼动追踪组件设计，通过将扁平电缆（例如柔性印刷电路板）布置在显示器周边，并使电缆的主要平面与显示器正交，从而减少眼动追踪组件的视觉干扰。同时，采用侧射型LED进一步减小光学模块的厚度和重量，提升整体美观性和便携性。制造过程中，部分组件可以在洁净室外组装，提高了生产效率并降低了成本。

**Key Innovation (核心创新)**:  
1. 采用扁平电缆（如柔性印刷电路板）围绕显示器周边布置，其主要平面与显示器正交，减少眼动追踪组件的视觉干扰。
2. 使用侧射型LED代替传统的正面发射LED，减小光学模块的厚度和重量，同时使LED相对隐藏于边框内。
3. 扁平电缆通过黑色焊料与LED连接，进一步降低视觉可见性，提升整体美观性。
4. 光学模块框架和边框之间形成腔体，扁平电缆布置在腔体内，优化空间利用率并保护内部组件。
5. 边框上设置红外线窗口，LED通过该窗口发射光线，实现更精确的眼动追踪。
6. 通过在边框上集成柔性印刷电路板并与显示器集成，简化了组装流程，部分组件可在洁净室外组装，降低制造成本。
7. 该设计适用于AR/VR头戴式设备，能够在不牺牲性能的前提下，提供更轻薄、更具沉浸感的用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353772)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288239)**
<br/><br/>

---


<br/>

### 12. 用于管理三维环境中内容共享的用户界面

**Title (EN)**: USER INTERFACES FOR MANAGING SHARING OF CONTENT IN THREE-DIMENSIONAL ENVIRONMENTS  
**Pub. No.**: US20260288297

**Applicant**: Apple Inc.  
**Inventor**: [Stephen O. LEMAY](https://patents.google.com/?inventor=Stephen+O.+LEMAY&assignee=Apple&country=US&num=100&sort=new), [Christopher D. MCKENZIE](https://patents.google.com/?inventor=Christopher+D.+MCKENZIE&assignee=Apple&country=US&num=100&sort=new), [Matan STAUBER](https://patents.google.com/?inventor=Matan+STAUBER&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种计算机系统可选地显示一个用户界面对象，该对象根据内容是私有的还是共享的来显示内容。计算机系统可选地显示一个包含共享内容的用户界面对象，该对象基于参与者是否有权访问内容。计算机系统可选地显示一个共享指示器，以指示相应的内容已与一个或多个其他参与者共享。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353836_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及增强现实和虚拟现实技术，具体为三维环境中的内容共享管理。

**Background (发明背景)**:  
近年来，增强现实计算机系统的发展显著增加。现有技术中的一些系统在执行与虚拟对象相关的操作时提供不足的反馈，需要一系列输入才能在增强现实环境中实现预期结果，且虚拟对象的操作复杂、繁琐且容易出错。这些问题增加了用户的认知负担，降低了虚拟/增强现实环境的体验。此外，这些方法耗时较长，导致计算机系统能量浪费，这在电池供电设备中尤为重要。

**Summary (发明总览)**:  
本发明提供了一种改进的用户界面，用于在三维环境中更高效、更直观地管理内容共享。该方法通过减少用户输入的数量、范围和性质，帮助用户理解输入与设备响应之间的联系，从而创建更高效的人机界面。系统能够根据内容是私有的还是共享的来显示相应的用户界面对象，并提供适当的视觉反馈以指示共享状态。

**Key Innovation (核心创新)**:  
1. 通过用户界面对象显示内容，并根据内容是私有的还是共享的来调整显示方式，从而保护隐私并促进共享。
2. 在三维环境中显示参与者代表，并根据实时通信会话中的事件动态生成新的虚拟对象，以保持共享空间的一致性。
3. 当检测到用户输入时，系统先以较低视觉显著性显示控制界面，然后在用户进一步交互时以更高视觉显著性显示，以减少对用户的干扰。
4. 通过空间关系的一致性设计，确保不同参与者视角下的内容显示位置和共享状态保持一致，提升协作体验。
5. 针对私有内容，系统仅显示其空间位置而不泄露具体内容；针对共享内容，则同时显示位置和内容。
6. 该方法适用于便携式设备、可穿戴设备以及头戴式设备等不同类型的计算机系统，具有广泛的适用性。
7. 通过减少用户输入和提高交互效率，本发明不仅提升了用户体验，还为电池供电设备节省了能量，延长了使用时间。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353836)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288297)**
<br/><br/>

---


<br/>

### 13. 自动认证方法和设备

**Title (EN)**: Method and Device for Automatic Authentication  
**Pub. No.**: US20260288925

**Applicant**: Apple Inc.  
**Inventor**: [Thomas G. Salter](https://patents.google.com/?inventor=Thomas+G.+Salter&assignee=Apple&country=US&num=100&sort=new), [Rahul Nair](https://patents.google.com/?inventor=Rahul+Nair&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
在一个实现方案中，一种用户认证方法由包括摄像头、眼动追踪器、一个或多个处理器和非易失性存储器的第一设备执行。该方法包括通过摄像头获取物理环境的图像，检测图像中的第二设备，使用眼动追踪器确定用户的注视方向，确定用户的注视方向指向第二设备，并在确定用户的注视方向指向第二设备后，向第二设备传输认证凭证。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354526_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及用户自动认证技术，具体涉及通过眼动追踪和设备间通信实现认证。

**Background (发明背景)**:  
用户在使用多个电子设备或账户时，需要分别进行登录或认证，这通常耗时且繁琐。此外，用户可能难以记住复杂的密码，或者使用弱密码以确保记忆，这带来了安全隐患。

**Summary (发明总览)**:  
本发明提出了一种通过眼动追踪实现自动认证的方法。第一设备通过摄像头捕捉环境图像，检测目标设备，并利用眼动追踪确定用户的注视方向。当用户注视目标设备时，第一设备自动向目标设备传输认证凭证，从而实现快速、安全的认证。这种方法减少了用户手动输入认证信息的需要，提高了认证效率。

**Key Innovation (核心创新)**:  
1. 通过摄像头捕捉物理环境图像，识别目标设备，为自动认证提供环境感知能力。
2. 利用眼动追踪技术确定用户的注视方向，确保认证请求由用户的主动行为触发。
3. 在检测到用户注视目标设备时，自动向目标设备传输认证凭证，简化了认证流程。
4. 结合眼动追踪和设备间通信技术，实现了无需用户手动输入密码的认证方式。
5. 通过非易失性存储器存储认证信息，确保数据安全性和隐私保护。
6. 该方法可应用于多种电子设备，如智能手机、平板电脑、头戴式设备等，具有广泛的适用性。
7. 特别适用于增强现实（AR）、虚拟现实（VR）等扩展现实（XR）环境，提供更自然的用户交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354526)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288925)**
<br/><br/>

---


<br/>

### 14. 用于管理媒体库的的用户界面

**Title (EN)**: USER INTERFACES FOR MANAGING MEDIA LIBRARIES  
**Pub. No.**: US20260288308

**Applicant**: Apple Inc.  
**Inventor**: [Nicole R. RYAN](https://patents.google.com/?inventor=Nicole+R.+RYAN&assignee=Apple&country=US&num=100&sort=new), [Aaron MORING](https://patents.google.com/?inventor=Aaron+MORING&assignee=Apple&country=US&num=100&sort=new), [Johnnie B. MANZARI](https://patents.google.com/?inventor=Johnnie+B.+MANZARI&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本公开内容涉及用于管理媒体库的方法和用户界面，包括用于管理一个或多个媒体库的方法和用户界面，用于通知参与者关于一个或多个媒体库变化的方法和用户界面，用于管理捕获媒体的方法和用户界面，用于推荐媒体项的方法和用户界面，以及用于管理重复媒体的方法和用户界面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353848_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及媒体库管理。

**Background (发明背景)**:  
现有媒体库管理方法通常较为繁琐且效率低下，例如使用复杂的用户界面，需要多次按键或击键操作，导致用户时间和设备能量浪费。在电池供电设备中，这一问题尤为突出。本发明旨在提供更快速、高效的媒体库管理方法和用户界面，以减少用户认知负担并提升人机交互效率，同时节省设备电量。

**Summary (发明总览)**:  
本发明提出了一种基于用户界面的媒体库管理方案，通过检测用户分享媒体项的请求并根据特定条件推荐相关媒体内容。系统会分析用户参与事件与媒体项的关联性，自动推荐符合条件的多组媒体内容，从而简化用户操作并提高媒体管理效率。该方法适用于个人和共享媒体库场景，并针对电池供电设备优化了能耗表现。

**Key Innovation (核心创新)**:  
1. 通过检测用户分享请求并结合用户参与事件，自动推荐相关媒体内容，提升推荐精准度。
2. 采用多时段事件关联分析技术，将不同时间点的用户参与事件与媒体内容进行匹配。
3. 提供分组的媒体推荐方案，将推荐内容按事件和时间段进行组织，方便用户选择。
4. 引入通知触发机制，只有在满足特定条件时才会向用户显示媒体库变更通知，减少干扰。
5. 针对电池供电设备优化了算法效率，降低了系统能耗，延长设备续航时间。
6. 该技术可应用于照片、视频等媒体库管理场景，尤其适合多人协作或活动记录等场景。
7. 通过简化用户操作流程和优化推荐逻辑，提升了用户体验并减少了设备资源消耗。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353848)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288308)**
<br/><br/>

---


<br/>

### 15. 具有改进轻载效率的反激式转换器

**Title (EN)**: FLYBACK CONVERTER WITH IMPROVED LIGHT LOAD EFFICIENCY  
**Pub. No.**: US20260291394

**Applicant**: Apple Inc.  
**Inventor**: [Prudhvi Mohan Maddineni](https://patents.google.com/?inventor=Prudhvi+Mohan+Maddineni&assignee=Apple&country=US&num=100&sort=new), [Vijay G. Phadke](https://patents.google.com/?inventor=Vijay+G.+Phadke&assignee=Apple&country=US&num=100&sort=new), [Liang Zhou](https://patents.google.com/?inventor=Liang+Zhou&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
通过反激式转换器的控制电路操作多个开关器件，包括以固定频率操作主开关以在主开关导通时在反激式变压器中存储能量，并在主开关关断时将能量从反激式变压器传递到输出；互补地操作电压钳位开关与主开关，以在反激式转换器向输出传递能量时钳制反激式变压器初级绕组的电压；以及操作反向电流开关以通过在电压钳位开关导通且反激式变压器中存储的能量传递后导通反向电流开关来回收反激式转换器中的漏电能量。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
电力电子技术领域，具体涉及反激式转换器的轻载效率优化技术。

**Background (发明背景)**:  
反激式转换器广泛应用于电源管理领域，但在轻载条件下效率较低。
现有技术通常采用固定频率操作，导致在轻载时开关损耗较大。
此外，漏电能量未得到有效回收，进一步降低了整体效率。
本发明旨在解决轻载条件下反激式转换器效率低下的问题。

**Summary (发明总览)**:  
本发明提出了一种改进的反激式转换器，通过互补操作主开关和电压钳位开关来优化能量传递过程。
同时，通过引入反向电流开关来回收漏电能量，从而提高轻载条件下的效率。
该方案通过协调控制多个开关器件的工作时序，实现了能量利用的最大化。
相较于传统方法，本发明在轻载条件下显著降低了开关损耗并提高了整体效率。

**Key Innovation (核心创新)**:  
1. 采用互补操作的主开关和电压钳位开关，通过协调控制时序来优化能量传递过程，减少开关损耗。
2. 引入反向电流开关，在电压钳位开关导通期间回收漏电能量，提高能量利用效率。
3. 通过固定频率操作主开关，确保在轻载条件下仍能维持稳定的输出电压。
4. 电压钳位开关的设计有效限制了反激式变压器初级绕组的电压尖峰，提高了系统可靠性。
5. 该方案特别适用于需要频繁切换轻载和重载的应用场景，如便携式电子设备电源管理。
6. 通过减少轻载条件下的开关损耗，延长了电源系统的使用寿命并降低了发热量。
7. 适用于消费电子、工业电源等需要高效轻载性能的应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487357253)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260291394)**
<br/><br/>

---


<br/>

### 16. 用于直播内容项播放的用户界面

**Title (EN)**: USER INTERFACES FOR PLAYBACK OF LIVE CONTENT ITEMS  
**Pub. No.**: US20260292305

**Applicant**: Apple Inc.  
**Inventor**: [Christopher J. ELLINGFORD](https://patents.google.com/?inventor=Christopher+J.+ELLINGFORD&assignee=Apple&country=US&num=100&sort=new), [Lucio MORENO RUFO](https://patents.google.com/?inventor=Lucio+MORENO+RUFO&assignee=Apple&country=US&num=100&sort=new), [Fredric R. VINNA](https://patents.google.com/?inventor=Fredric+R.+VINNA&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本披露描述的一些实施例涉及用于控制显示在播放用户界面中的直播内容项播放的一个或多个电子设备。一些实施例涉及用于在关键内容用户界面中显示与直播内容项对应的关键内容的一个或多个电子设备。一些实施例涉及用于在多视图用户界面中同时显示多个内容项的一个或多个电子设备。一些实施例涉及用于在播放用户界面中显示与内容项对应的见解的一个或多个电子设备。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487358256_1.jpg)

**Technical Field (技术领域)**:  
用户界面技术领域，具体涉及直播内容播放控制、关键内容展示和多视图内容展示。

**Background (发明背景)**:  
近年来，用户与电子设备的交互显著增加，这些设备包括计算机、平板电脑、电视、多媒体设备和移动设备等。在某些情况下，设备会展示直播内容项，并提供特定的用户界面来显示相关信息。用户希望能够高效地控制直播内容项的播放，特别是在使用电池供电的输入设备时，改善交互体验和减少用户操作时间非常重要。

**Summary (发明总览)**:  
本发明提供了一系列用于优化直播内容播放体验的用户界面解决方案。通过在播放界面中集成播放控制工具，用户可以更直观地操作直播内容。同时，系统支持关键内容展示和多视图播放功能，使用户能够快速浏览重要片段或同时观看多个直播内容。此外，系统还提供与内容相关的见解展示，帮助用户深入理解内容。这些技术通过减少用户认知负担和优化设备资源使用，提升了整体用户体验。

**Key Innovation (核心创新)**:  
1. 在播放用户界面中集成播放控制工具，通过接收用户输入来显示播放控制条和视觉指示器，使用户能够直观地控制直播内容的播放进度。
2. 支持关键内容展示，用户可以通过输入请求查看与直播内容项对应的关键内容片段，系统会按顺序展示这些片段，并允许用户快速导航。
3. 实现多视图用户界面，用户可以同时观看多个直播内容项，系统会根据用户输入调整每个内容项的显示尺寸，并在一定时间后自动调整布局以优化观看体验。
4. 提供与直播内容相关的见解展示，用户可以选择查看详细信息，系统会将直播内容最小化并更新显示与内容相关的见解。
5. 通过减少用户输入的冗余操作，降低设备处理和电池消耗，提高整体系统效率。
6. 适用于移动设备（如智能手机、平板电脑）和具有触摸界面的桌面设备，提供一致的用户体验。
7. 这些技术特别适用于直播体育赛事、新闻报道和在线教育等场景，帮助用户更高效地获取和理解关键信息。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358256)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292305)**
<br/><br/>

---


<br/>

### 17. 提供、修改和/或与用户界面交互的系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR PROVIDING, MODIFYING, AND/OR INTERACTING WITH USER INTERFACES  
**Pub. No.**: US20260288080

**Applicant**: Apple Inc.  
**Inventor**: [Andrew P. CLYMER](https://patents.google.com/?inventor=Andrew+P.+CLYMER&assignee=Apple&country=US&num=100&sort=new), [Yeobeen CHUNG](https://patents.google.com/?inventor=Yeobeen+CHUNG&assignee=Apple&country=US&num=100&sort=new), [Louis R. MIKOLAY](https://patents.google.com/?inventor=Louis+R.+MIKOLAY&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本公开涉及提供、修改和/或与用户界面交互的技术。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353594_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面领域，具体涉及用户界面的提供、修改和交互技术。

**Background (发明背景)**:  
现有计算机系统通过输入设备检测用户输入，并根据输入执行操作并提供反馈反馈等反馈。然而，一些现有技术使用复杂且耗时的用户界面，可能需要多次按键或击键，导致操作效率低下，尤其对电池供电设备而言能耗较高。

**Summary (发明总览)**:  
本发明提供了一种更快速、更高效的用户界面交互方法，通过优化用户界面的显示和操作方式，减少用户认知负担并提高人机交互效率。该方法通过动态显示时间界面和根据上下文调整唤醒屏幕内容等方式，简化用户操作流程，节省设备能耗。

**Key Innovation (核心创新)**:  
1. 设计了一种动态时间用户界面，通过第一表盘指示当前时间，并随着时间变化，表盘在界面中从第一位置移动到第二位置，提供直观的视觉反馈。
2. 实现了基于上下文感知的唤醒屏幕显示，系统根据不同上下文状态展示不同的视觉媒体内容，例如在特定场景下优先显示相关应用或信息。
3. 通过优化用户输入检测和处理流程，减少了用户操作步骤，例如将复杂的多次按键操作简化为一次触摸或手势操作。
4. 采用高效的用户界面渲染技术，在保证视觉效果的同时降低设备能耗，延长电池供电设备的续航时间。
5. 提供了一种可编程的用户界面交互框架，开发者可以根据具体需求定制界面元素和交互逻辑，增强系统的灵活性和可扩展性。
6. 该技术可应用于智能手表、手机等移动设备，以及智能家居控制面板等场景，为用户提供更便捷、更智能的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353594)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288080)**
<br/><br/>

---


<br/>

### 18. 用于音频流传输的统一通信接口建立方法与系统

**Title (EN)**: Method and System for Establishing a Unified Communication Interface for Audio Streaming  
**Pub. No.**: US20260292385

**Applicant**: Apple Inc.  
**Inventor**: [Natalia A. Fornshell](https://patents.google.com/?inventor=Natalia+A.+Fornshell&assignee=Apple&country=US&num=100&sort=new), [Suraj Sumangala](https://patents.google.com/?inventor=Suraj+Sumangala&assignee=Apple&country=US&num=100&sort=new), [Aarti Kumar](https://patents.google.com/?inventor=Aarti+Kumar&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种方法，包括确定用户头戴式耳机与电子设备之间建立了有线连接；建立耳机与电子设备之间的无线连接；通过有线连接传输第一音频信号至耳机以进行音频播放；通过无线连接从耳机接收由耳机传感器捕获的头部跟踪数据，其中头部跟踪数据指示用户头部的移动；基于头部跟踪数据修改第一音频信号以产生第二音频信号；并通过有线连接传输第二音频信号至耳机以进行音频播放，以补偿用户头部的移动。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
音频处理技术领域，具体涉及音频流传输和头部跟踪数据的处理。

**Background (发明背景)**:  
随着音频设备的发展，用户对沉浸式音频体验的需求日益增加。传统的有线耳机在音频传输中缺乏灵活性，而无线耳机在音频质量和实时性方面存在不足。现有的解决方案未能有效结合有线和无线传输的优势，导致音频体验受限。本发明旨在解决音频传输中实时性和灵活性不足的问题。

**Summary (发明总览)**:  
本发明提出了一种结合有线和无线传输的音频处理方法，通过有线连接传输音频信号，同时利用无线连接传输头部跟踪数据。基于头部跟踪数据，系统动态调整音频信号以补偿用户的头部运动，从而提供更自然的音频体验。该方法结合了有线传输的低延迟和无线传输的灵活性，提升了音频播放的沉浸感。

**Key Innovation (核心创新)**:  
1. 通过有线连接传输音频信号，确保低延迟和高保真度的音频播放。
2. 利用无线连接传输头部跟踪数据，实现用户头部运动的实时捕捉。
3. 基于捕捉到的头部跟踪数据，动态调整音频信号以补偿用户的头部运动。
4. 结合有线和无线传输的优势，既保证了音频质量，又提升了传输的灵活性。
5. 通过耳机传感器精确捕捉用户头部的运动数据，确保音频调整的准确性。
6. 该方法可应用于虚拟现实（VR）和增强现实（AR）设备，提供更沉浸式的音频体验。
7. 特别适用于需要高精度头部跟踪和实时音频调整的场景，如3D音频游戏和沉浸式音频体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358345)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292385)**
<br/><br/>

---


<br/>

### 19. 图像处理管线的延迟降低方法与设备

**Title (EN)**: METHOD AND DEVICE FOR LATENCY REDUCTION OF AN IMAGE PROCESSING PIPELINE  
**Pub. No.**: US20260289719

**Applicant**: Apple Inc.  
**Inventor**: [Bertrand Nepveu](https://patents.google.com/?inventor=Bertrand+Nepveu&assignee=Apple&country=US&num=100&sort=new), [Marc-Andre Chenier](https://patents.google.com/?inventor=Marc-Andre+Chenier&assignee=Apple&country=US&num=100&sort=new), [Yan Cote](https://patents.google.com/?inventor=Yan+Cote&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
在一些实现中，系统级芯片（SoC）包括图像处理电路，用于获取对应于物理环境的第一图像数据。图像处理电路将第一图像数据的第一切片读入一个或多个输入缓冲区，并对第一切片执行一个或多个图像处理操作以获得第二图像数据的第一部分。图像处理电路将第一图像数据的第二切片读入一个或多个输入缓冲区，并对第二切片执行图像处理操作以获得第二图像数据的第二部分。通过对第一图像数据按切片进行处理，SoC能够在减少缓冲区存储需求的同时生成第二图像数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487355402_1.jpg)

**Technical Field (技术领域)**:  
图像处理管线技术，具体涉及降低图像读取和显示扫描延迟的系统与方法。

**Background (发明背景)**:  
在扩展现实（XR）内容中，因运动引起的晕动症是推广的一大障碍。提高帧率至至少60帧每秒（fps）是减少晕动症的一种方法，这意味着端到端（E2E）图像处理管线的处理时间应少于20毫秒。然而，图像传感器读取图像帧的操作可能消耗约6毫秒，成为E2E管线的瓶颈。此外，显示扫描也是另一个主要瓶颈。

**Summary (发明总览)**:  
本发明提出了一种通过切片处理图像数据来降低图像处理管线延迟的方法。该方法将图像数据分割成多个切片，依次处理每个切片，从而减少缓冲需求并提高处理效率。同时，本发明还提供了一种优化显示扫描延迟的方法，通过评估图像数据的复杂度和虚拟内容的合成时间，动态调整渲染策略以确保实时性。

**Key Innovation (核心创新)**:  
1. 采用切片处理技术，将图像数据分割成多个切片，依次处理每个切片，从而减少缓冲需求并提高处理效率。
2. 通过动态调整图像处理顺序和缓冲区使用策略，优化图像数据的读取和写入过程，降低整体延迟。
3. 提出一种基于图像复杂度评估的虚拟内容渲染方法，根据图像复杂度动态调整渲染策略，确保在复杂场景下仍能保持实时性。
4. 在虚拟内容渲染时间超出阈值时，采用复用之前渲染结果的方式，避免因渲染延迟导致的画面卡顿。
5. 结合设备姿态信息，实时调整虚拟内容的渲染视角，确保虚拟内容与物理环境的视觉一致性。
6. 本发明可应用于增强现实（AR）、虚拟现实（VR）等XR设备中，通过降低图像处理和显示延迟，提升用户体验并减少晕动症的发生。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355402)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289719)**
<br/><br/>

---


<br/>

### 20. 用于提供实时社交智能的数字助手

**Title (EN)**: DIGITAL ASSISTANT FOR PROVIDING REAL-TIME SOCIAL INTELLIGENCE  
**Pub. No.**: US20260290341

**Applicant**: Apple Inc.  
**Inventor**: [Eddy Zexin LIANG](https://patents.google.com/?inventor=Eddy+Zexin+LIANG&assignee=Apple&country=US&num=100&sort=new), [William CARUSO](https://patents.google.com/?inventor=William+CARUSO&assignee=Apple&country=US&num=100&sort=new), [Madhu CHINTHAKUNTA](https://patents.google.com/?inventor=Madhu+CHINTHAKUNTA&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及智能自动化助手，具体而言是提供实时社交智能。示例方法包括：在向电子设备用户提供一个或多个输出的同时，通过检测用户近场场景中的人、确定用户正在注视该人，并在用户注视该人时检测到来自用户或该人的语音输入，来确定用户是否处于参与状态。在确定用户处于参与状态后，暂停向用户提供输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487356090_1.jpg)

**Technical Field (技术领域)**:  
智能数字助手技术领域，具体涉及实时社交智能和用户交互管理。

**Background (发明背景)**:  
智能自动化助手为用户与电子设备之间的交互提供了便捷接口，但现有技术难以智能识别用户何时处于社交互动中。用户在需要与他人互动时，必须手动暂停与数字助手的交互，这既不方便又浪费时间。此外，用户在社交互动后可能忘记重新启用助手，导致错过重要通知。

**Summary (发明总览)**:  
本发明提出了一种智能数字助手系统，通过检测用户近场场景中的人、用户的注视行为以及语音输入来判断用户是否处于社交互动状态。在确定用户处于社交互动时，助手会自动暂停向用户发送输出，避免干扰用户的社交活动。该方法简化了用户与数字助手交互的管理过程，提升了用户体验，同时节省了设备能耗。

**Key Innovation (核心创新)**:  
1. 通过检测用户近场场景中的人、用户的注视行为以及语音输入，智能判断用户是否处于社交互动状态。
2. 在确定用户处于社交互动状态时，自动暂停向用户发送输出，避免干扰用户的社交活动。
3. 实现了无需用户手动干预即可智能管理数字助手与用户交互的机制，提升了交互的自然性和便捷性。
4. 通过减少用户频繁开启和关闭数字助手的需求，降低了设备能耗并延长了电池续航时间。
5. 防止数字助手在用户社交互动过程中发出干扰性通知或提示，确保用户能够专注于当前社交活动。
6. 适用于智能眼镜等扩展现实设备，为用户提供无缝的混合交互体验。
7. 提升了数字助手在复杂社交场景中的智能化水平，使其能够更好地适应用户的日常社交需求。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356090)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260290341)**
<br/><br/>

---


<br/>

### 21. 显示上下文化的小组件

**Title (EN)**: Displaying a Contextualized Widget  
**Pub. No.**: US20260288301

**Applicant**: Apple Inc.  
**Inventor**: [Thomas G. Salter](https://patents.google.com/?inventor=Thomas+G.+Salter&assignee=Apple&country=US&num=100&sort=new), [Anshu K. Chimalamarri](https://patents.google.com/?inventor=Anshu+K.+Chimalamarri&assignee=Apple&country=US&num=100&sort=new), [Bryce L. Schmidtchen](https://patents.google.com/?inventor=Bryce+L.+Schmidtchen&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及一种在电子设备上执行的方法，该设备具有一个或多个处理器、非易失性存储器以及显示屏。该设备还可以包括图像传感器和输入设备。方法包括基于图像数据获取与物理对象相关联的语义值，图像数据与第一输入模态相关。在一些实现中，方法包括基于语义值获取小组件，并根据对象接近性标准（例如，显示屏锁定、身体锁定或世界锁定）相对于物理对象显示小组件。在一些实现中，方法包括从输入设备获取用户数据，用户数据与第二输入模态相关。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353840_1.jpg)

**Technical Field (技术领域)**:  
本专利属于人机交互技术领域，具体涉及基于语义识别和输入模态融合的智能小组件显示技术。

**Background (发明背景)**:  
现有技术中，电子设备通常根据用户输入启动应用程序并显示相关内容，而不考虑设备当前所处的物理环境。这导致设备无法显示与物理环境上下文相关的内容，从而降低了用户体验。本发明旨在解决这一问题，通过识别物理对象并显示与之上下文相关的小组件来增强用户交互体验。

**Summary (发明总览)**:  
本发明提出了一种基于语义识别和用户输入融合的智能小组件显示方法。电子设备通过图像传感器获取物理环境的图像数据，并基于语义分割等技术识别物理对象的语义值。基于语义值和用户输入数据，设备选择并显示与物理对象上下文相关的小组件。小组件的显示方式根据对象接近性标准进行动态调整，例如显示屏锁定、身体锁定或世界锁定，从而提供更贴合用户环境的交互体验。

**Key Innovation (核心创新)**:  
1. 通过计算机视觉技术（如语义分割）识别物理对象的语义值，实现对物理环境的智能感知。
2. 基于语义值和用户输入数据动态选择和显示小组件，实现内容与物理环境的上下文关联。
3. 小组件的显示方式包括显示屏锁定、身体锁定和世界锁定，适应不同场景下的用户交互需求。
4. 小组件可包含状态指示器，例如显示设备可见范围内物理对象的状态信息（如烤箱温度）。
5. 小组件可包含控制功能，例如通过选择小组件中的手电筒图标来控制设备的手电筒功能。
6. 通过身体锁定技术，小组件可以相对于用户身体位置保持固定位置和角度，适应用户的移动。
7. 本发明可应用于智能家居、AR/VR设备等场景，为用户提供更智能、更直观的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353840)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288301)**
<br/><br/>

---


<br/>

### 22. 降质图像缓冲回退

**Title (EN)**: Degraded Quality Image Buffer Fallback  
**Pub. No.**: US20260289720

**Applicant**: Apple Inc.  
**Inventor**: [Peter A. Lisherness](https://patents.google.com/?inventor=Peter+A.+Lisherness&assignee=Apple&country=US&num=100&sort=new), [Nathaniel C. Begeman](https://patents.google.com/?inventor=Nathaniel+C.+Begeman&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种用于减少电子显示设备上图像数据显示延迟的系统、方法和设备。该方法包括指示图像处理电路从第一帧缓冲器读取图像数据的第一个图块，并在读取第一个图块后确定第一帧缓冲器或第二帧缓冲器是否具有更高质量的第二个图块。基于第一帧缓冲器或第二帧缓冲器中哪一个具有更高质量的第二个图块，指示图像处理电路从具有更高质量第二个图块的第一帧缓冲器或第二帧缓冲器中读取第二个图块。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487355403_1.jpg)

**Technical Field (技术领域)**:  
图形渲染技术领域，具体涉及基于图块质量进行图像数据选择显示的电子显示系统。

**Background (发明背景)**:  
在增强现实（AR）和虚拟现实（VR）系统中，以及游戏应用中，快速显示渲染图像内容对于减少用户感知延迟至关重要。现有技术如"VSYNC关闭"通过尽快切换到新内容来缩短延迟，但可能导致切换边界处的图像错位问题。此外，现有技术假设扫描输出从旧图像开始，并在新图像完全渲染后切换，这限制了延迟的进一步降低。

**Summary (发明总览)**:  
本发明提出了一种基于图块粒度的图像渲染和显示方法，通过在帧缓冲器中选择性地读取已完成渲染的图块来减少延迟。显示控制器根据图块的质量水平逐图块或逐图块行决定从哪个帧缓冲器读取数据。这种方法允许在最高质量图像帧完全渲染之前开始显示已完成的图块，从而实现比传统全帧VSYNC关闭更低的延迟。

**Key Innovation (核心创新)**:  
1. 采用图块粒度渲染，将图像帧分割成多个图块并按任意顺序完成渲染，从而实现更灵活的图像数据选择。
2. 通过比较不同帧缓冲器中图块的质量水平，动态选择更高质量的图块进行显示，优化图像质量与延迟的平衡。
3. 在多通道渲染管线中，允许用较低质量的早期渲染结果替换部分图像内容，以减少延迟，同时保持整体视觉体验。
4. 支持对特定区域（如用户注视点区域）优先生成和读取高质量图像数据，提升关键区域的视觉表现。
5. 在扫描输出过程中，动态替换为更高质量的图像数据，以减少视觉瑕疵并提供更流畅的视觉体验。
6. 适用于AR/VR应用场景，在保证低延迟的同时，容忍轻微的图像质量下降，避免前后帧混合带来的时空失真问题。
7. 通过优先处理用户视觉敏感区域的高质量数据，在保证低延迟的同时，提升用户对图像质量的感知体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355403)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289720)**
<br/><br/>

---


<br/>

### 23. 直通式管道

**Title (EN)**: PASSTHROUGH PIPELINE  
**Pub. No.**: US20260289904

**Applicant**: Apple Inc.  
**Inventor**: [Christian I. Moore](https://patents.google.com/?inventor=Christian+I.+Moore&assignee=Apple&country=US&num=100&sort=new), [Moinul H. Khan](https://patents.google.com/?inventor=Moinul+H.+Khan&assignee=Apple&country=US&num=100&sort=new), [Seyedkoosha Mirhosseini](https://patents.google.com/?inventor=Seyedkoosha+Mirhosseini&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
在一个实现中，一种用于将图像与虚拟内容进行流水线混合的方法由包括图像传感器、显示器、一个或多个处理器和非易失性存储器的设备执行。该方法包括使用图像传感器捕获物理环境的图像的第一部分；将物理环境的图像的第一部分进行变形处理以生成变形后的第一部分；将变形后的第一部分与虚拟内容的第一部分混合以生成混合后的第一部分；在显示器上显示混合后的第一部分；使用图像传感器捕获物理环境的图像的第二部分；将物理环境的图像的第二部分进行变形处理。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487355604_1.jpg)

**Technical Field (技术领域)**:  
扩展现实(XR)技术领域，具体涉及低延迟图像与虚拟内容融合显示技术。

**Background (发明背景)**:  
现有头戴式设备(HMD)通过场景摄像头捕捉用户所在物理环境的图像，并在显示器上呈现给用户。部分图像或图像的某些部分可与虚拟对象结合，为用户提供XR体验。然而，图像处理过程会引入延迟，导致用户不适或迷失方向。

**Summary (发明总览)**:  
本发明提出了一种低延迟图像与虚拟内容融合显示方法，通过流水线处理方式减少延迟。
主要实现步骤包括：
1. 捕捉物理环境图像并进行畸变校正；
2. 将校正后的图像与虚拟内容混合；
3. 采用流水线方式处理图像的不同部分，实现实时显示。
相较于传统方法，本发明通过并行处理图像的不同部分，显著降低了延迟，提升了用户体验。

**Key Innovation (核心创新)**:  
1. 采用流水线处理方式，将图像捕捉、变形校正和虚拟内容混合过程并行化，显著减少延迟。
2. 通过分阶段处理图像的不同部分，实现图像与虚拟内容的实时融合显示。
3. 引入色差校正机制，通过对第二颜色通道进行变形处理，补偿镜头引起的色差问题。
4. 在图像混合过程中，通过填充孔洞技术处理变形图像中的缺失区域，确保显示图像的完整性。
5. 优化了图像处理流程，通过接收基于图像子集的参数进行动态调整，提高处理效率。
6. 该技术可应用于头戴式设备，提供低延迟的直通式图像显示功能，减少用户不适感。
7. 适用于需要实时图像与虚拟内容融合的场景，如增强现实、虚拟现实等，为用户提供更自然的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355604)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289904)**
<br/><br/>

---


<br/>

### 24. 头戴式显示设备

**Title (EN)**: HEAD MOUNTABLE DISPLAY  
**Pub. No.**: US20260287909

**Applicant**: Apple Inc.  
**Inventor**: [Jeremy C Franklin](https://patents.google.com/?inventor=Jeremy+C+Franklin&assignee=Apple&country=US&num=100&sort=new), [Jason C Sauers](https://patents.google.com/?inventor=Jason+C+Sauers&assignee=Apple&country=US&num=100&sort=new), [Trevor J Ness](https://patents.google.com/?inventor=Trevor+J+Ness&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种头戴式显示设备包括一个界定前开口和后开口的外壳，一个设置在前开口的显示屏幕，以及一个设置在后开口的显示组件。一个包括第一电子组件的第一固定带和一个第二固定带可与外壳耦合。第二固定带可包括第二电子组件，且一个固定带可延伸并耦合于第一固定带和第二固定带之间。头戴式显示设备还可包括一个前部曲面透明盖板。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
头戴式显示设备技术领域，具体涉及可穿戴显示设备及其固定结构。

**Background (发明背景)**:  
头戴式显示设备在虚拟现实和增强现实应用中越来越普及。
现有技术中，设备通常需要复杂的固定结构以确保佩戴舒适性和稳定性。
传统设计在电子组件的集成和用户佩戴体验方面存在不足。
本发明旨在提供一种改进的头戴式显示设备，以解决这些问题。

**Summary (发明总览)**:  
本发明提出了一种新型头戴式显示设备，通过优化固定带结构来提升佩戴舒适性和稳定性。
设备采用双固定带设计，其中每个固定带都集成了电子组件。
固定带之间通过延伸的固定带连接，确保整体结构的稳固性。
此外，设备配备前部曲面透明盖板，以提供更好的视觉效果和防护。
相较于现有技术，本发明在结构集成和用户体验方面实现了显著改进。

**Key Innovation (核心创新)**:  
1. 采用双固定带设计，其中第一固定带和第二固定带分别集成电子组件，实现设备功能模块的分布式布局。
2. 通过延伸的固定带连接双固定带，确保设备佩戴时的稳固性和均匀受力，提升用户佩戴舒适度。
3. 前部曲面透明盖板设计，提供更广阔的视野和更好的光学性能，同时增强设备的防护能力。
4. 电子组件集成在固定带中，而非集中在主机部分，有助于减轻主机重量并优化重心分布。
5. 该设计适用于虚拟现实、增强现实等应用场景，能够为用户提供更沉浸式的视觉体验。
6. 通过模块化设计，设备易于维护和升级，用户可根据需求更换或添加功能模块。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353410)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260287909)**
<br/><br/>

---


<br/>

### 25. 多设备模型增强

**Title (EN)**: MULTIPLE DEVICE MODEL AUGMENTATION  
**Pub. No.**: US20260289929

**Applicant**: Apple Inc.  
**Inventor**: [Daniel Kurz](https://patents.google.com/?inventor=Daniel+Kurz&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明公开了使用外部设备数据来改进可穿戴设备上用户数据的设备、系统和方法。例如，一个示例过程可包括接收来自可穿戴电子设备传感器的第一传感器数据，该数据描绘了佩戴可穿戴电子设备的用户的第一面部区域。该过程还可包括接收来自与可穿戴电子设备分离的第二设备的第二传感器数据，该数据描绘了用户的第二面部区域，该第二面部区域在第一传感器数据中缺失。该过程可进一步确定第一传感器数据和第二传感器数据对应于同一用户，并基于第一传感器数据和第二传感器数据生成用户模型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487355633_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及增强现实与可穿戴设备领域，具体涉及利用外部设备传感器数据补充和增强可穿戴设备生成的用户模型的技术。

**Background (发明背景)**:  
在用户使用设备（如头戴式显示器）时，生成或修改用户表示（例如3D用户模型）是有价值的。然而，现有系统通常无法利用外部来源的潜在可用数据来生成或修改此类表示。这导致用户模型可能不完整或不准确。

**Summary (发明总览)**:  
本发明通过整合外部设备传感器数据来增强可穿戴设备生成的用户模型。外部设备（如独立摄像头）提供用户身体不同部位或特征的视觉数据，这些数据可补充可穿戴设备传感器（如头戴式设备摄像头）的有限视角数据。通过数据匹配和融合技术，生成更完整、准确的用户模型。此外，外部数据可用于更新用户模型的预测模型或支持联邦学习，从而提升模型性能和适应性。

**Key Innovation (核心创新)**:  
1. 利用外部设备（如独立摄像头）提供用户身体不同部位或特征的视觉数据，补充可穿戴设备传感器的有限视角数据。
2. 通过数据匹配技术，将外部设备数据和可穿戴设备数据进行身份识别和关联，确保数据融合的准确性。
3. 采用多种匹配标准，包括特征点匹配、衣物识别、面部相似性识别和身体部位相似性识别，以提高数据匹配的可靠性。
4. 将外部设备数据用于更新用户模型的预测模型（如神经网络），通过额外训练数据或输入数据提升模型性能。
5. 支持联邦学习，通过共享外部数据或梯度来增强模型的训练效果，同时保护用户隐私。
6. 实现了用户模型的动态更新，包括点云模型、参数化表示模型和骨骼模型（如骨长度）的更新。
7. 本发明可应用于增强现实、虚拟现实和个性化用户建模等领域，为用户提供更准确、完整的虚拟形象和交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355633)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289929)**
<br/><br/>

---


<br/>

### 26. 带有倾斜致动器的折叠光学相机

**Title (EN)**: Folded Optics Camera with Tilt Actuator  
**Pub. No.**: US20260287917

**Applicant**: Apple Inc.  
**Inventor**: [Jian Ouyang](https://patents.google.com/?inventor=Jian+Ouyang&assignee=Apple&country=US&num=100&sort=new), [Nicholas D. Smyth](https://patents.google.com/?inventor=Nicholas+D.+Smyth&assignee=Apple&country=US&num=100&sort=new), [Scott W. Miller](https://patents.google.com/?inventor=Scott+W.+Miller&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及一种具有折叠光学系统和倾斜致动器的相机。在一些实施例中，相机包括折叠光学组件，该组件包含棱镜和镜头组。在一些实施例中，相机致动器组件包括一个或多个用于多轴倾斜棱镜的致动器。此外，致动器组件还包括一个或多个用于沿轴向平移镜头组的致动器。在一些实施例中，相机还包括轴承悬挂组件，该组件允许根据致动器组件所启用的运动对棱镜和/或镜头组进行受控移动。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
光学成像技术领域，具体涉及折叠光学设计和多轴运动控制技术。

**Background (发明背景)**:  
传统相机设计中，光学组件通常采用固定结构，难以实现灵活的光路调整。折叠光学系统虽然能减小设备尺寸，但光学组件的移动控制较为复杂。现有的光学调整方案通常只支持单轴运动，无法满足多方向调节的需求。本发明旨在提供一种能够多轴调节光学组件的折叠光学相机，以提升光学调整的灵活性和精度。

**Summary (发明总览)**:  
本发明提出了一种新型折叠光学相机设计，通过引入多轴倾斜致动器和镜头组平移机构，实现光学组件的灵活调整。该设计采用棱镜和镜头组的组合，并通过轴承悬挂系统确保运动控制的精确性。与传统折叠光学相机相比，本发明提供了更全面的光学调整能力，能够适应多种拍摄场景和需求。

**Key Innovation (核心创新)**:  
1. 采用多轴倾斜致动器设计，使棱镜能够在多个方向上精确调整角度，从而实现灵活的光路控制。
2. 引入镜头组平移致动器，通过沿轴向移动镜头组来补偿光学误差，提高成像质量。
3. 使用轴承悬挂组件，为棱镜和镜头组提供受控运动支持，确保运动精度和稳定性。
4. 结合折叠光学系统与多轴运动控制技术，在减小设备尺寸的同时提升光学调整能力。
5. 通过精确控制光学组件的运动，实现对焦、变焦和图像稳定等功能的集成。
6. 该设计可应用于小型化、高性能相机产品，如智能手机相机、运动相机或无人机相机。
7. 独特价值在于提供更灵活的光学调整能力，在复杂拍摄环境下也能保证高质量成像。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353419)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260287917)**
<br/><br/>

---


<br/>

### 27. 音频的空间混合

**Title (EN)**: Spatial Blending of Audio  
**Pub. No.**: US20260292430

**Applicant**: Apple Inc.  
**Inventor**: [Shai Messingher Lang](https://patents.google.com/?inventor=Shai+Messingher+Lang&assignee=Apple&country=US&num=100&sort=new), [Joshua D. Atkins](https://patents.google.com/?inventor=Joshua+D.+Atkins&assignee=Apple&country=US&num=100&sort=new), [Scott A. Wardle](https://patents.google.com/?inventor=Scott+A.+Wardle&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
音频处理系统可获取要显示的视觉对象的大小，并至少基于视觉对象的大小确定多个虚拟扬声器的虚拟位置。每个虚拟扬声器通过双耳音频在每个虚拟位置进行空间渲染，通过头戴式扬声器进行播放。其他方面也进行了描述和主张。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487358394_1.jpg)

**Technical Field (技术领域)**:  
音频处理技术领域，具体涉及根据视觉对象呈现的空间音频技术。

**Background (发明背景)**:  
声音通过介质传播并被麦克风捕捉，生成音频信号。音频作品可以与视觉对象相关联，并通过扬声器输出。现有的沉浸式体验中，用户对视觉对象的呈现有更多控制，但音频呈现方式未能充分与视觉对象的状态相协调。此外，不同音频格式的存在也要求一种能够动态适应沉浸式音频格式的转换方法。

**Summary (发明总览)**:  
本发明提出了一种根据视觉对象特性动态调整空间音频呈现的方法。通过获取视觉对象的大小等特征，系统确定多个虚拟扬声器的位置，并使用双耳音频技术进行空间渲染。系统能够根据视觉对象的大小调整虚拟扬声器的分布，并在用户头部移动时保持音频方向与视觉对象一致。此外，系统支持多种音频格式向沉浸式音频格式的动态转换。

**Key Innovation (核心创新)**:  
1. 通过视觉对象的大小动态调整虚拟扬声器的分布，例如当视觉对象尺寸变小时，虚拟扬声器间距减小，反之则增大。
2. 在第一模式下，虚拟扬声器的虚拟中心通道根据视觉对象在显示屏幕上的位置进行定向，并限制在用户位置的球体范围内。
3. 在第二模式下，所有虚拟扬声器直接放置在视觉对象位置，不受用户位置球体范围的限制，适用于视觉对象尺寸较小或用户选择移动视觉对象的情况。
4. 系统支持从第一模式到第二模式的平滑过渡动画，以及反向过渡，同时保持整体声能不变。
5. 采用基于向量的幅度平移（VBAP）技术，将多声道音频格式（如5.1、7.1）映射到虚拟扬声器，并支持球体上的插值处理。
6. 在用户头部移动时，虚拟扬声器在球体上旋转，以保持音频方向与视觉对象一致，并基于用户位置更新收听位置。
7. 该技术可应用于增强现实、虚拟现实或多媒体应用中，通过动态调整空间音频呈现方式，提升用户对视觉对象和音频的沉浸式体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358394)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292430)**
<br/><br/>

---


<br/>

### 28. 基于凝视导航的设备、方法和图形用户界面

**Title (EN)**: DEVICES, METHODS, AND GRAPHICAL USER INTERFACES FOR GAZE-BASED NAVIGATION  
**Pub. No.**: US20260288293

**Applicant**: Apple Inc.  
**Inventor**: [Pol PLA I CONESA](https://patents.google.com/?inventor=Pol+PLA+I+CONESA&assignee=Apple&country=US&num=100&sort=new), [Bas ORDING](https://patents.google.com/?inventor=Bas+ORDING&assignee=Apple&country=US&num=100&sort=new), [Stephen O. LEMAY](https://patents.google.com/?inventor=Stephen+O.+LEMAY&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
在一些实施例中，电子设备根据检测到用户的凝视来展开内容项。在一些实施例中，电子设备根据确定用户正在阅读内容项来滚动内容项的文本。在一些实施例中，电子设备根据检测到用户的头部移动和用户的凝视来在用户界面之间导航。在一些实施例中，电子设备根据检测到用户的头部移动和用户的凝视来显示与内容部分相关的增强内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353832_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算机系统领域，具体为基于用户凝视和头部运动的导航技术。

**Background (发明背景)**:  
近年来，增强现实计算机系统的发展显著增加，但现有技术在与包含虚拟元素的界面交互时存在诸多不足，例如反馈不足、操作繁琐、效率低下等。这些问题增加了用户的认知负担，降低了用户体验，并导致不必要的能量消耗，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种基于用户凝视和头部运动的导航方法，通过眼动追踪设备检测用户的凝视和头部动作，实现内容展开、文本滚动、界面导航以及增强内容显示等功能。该方法无需传统输入设备，仅通过眼睛和头部动作即可实现自然高效的交互，降低了用户操作复杂度，尤其适用于运动控制能力受限的用户。

**Key Innovation (核心创新)**:  
1. 通过眼动追踪设备检测用户凝视，识别用户正在阅读的内容项并自动展开，提升阅读体验。
2. 根据用户凝视位置判断阅读进度，自动滚动文本内容，使用户无需手动操作即可连续阅读。
3. 利用摄像头检测用户头部运动和凝视方向，实现用户界面间的自然导航，简化交互流程。
4. 结合用户头部前倾动作和凝视方向，识别用户对特定内容区域的关注，并显示相关增强内容（如定义、扩展图片、网站预览等）。
5. 通过凝视和头部动作控制设备，提供了无需物理接触的交互方式，降低了用户操作难度。
6. 该技术特别适用于运动控制能力受限的用户，提高了设备的可访问性。
7. 应用于增强现实、虚拟现实等场景中，可提供更沉浸式的用户体验，并减少用户疲劳。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353832)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288293)**
<br/><br/>

---


<br/>

### 29. 阀门端口

**Title (EN)**: Valved Port  
**Pub. No.**: US20260292394

**Applicant**: Apple Inc.  
**Inventor**: [Lucas Vindrola](https://patents.google.com/?inventor=Lucas+Vindrola&assignee=Apple&country=US&num=100&sort=new), [Andrew M. Hulva](https://patents.google.com/?inventor=Andrew+M.+Hulva&assignee=Apple&country=US&num=100&sort=new), [Onur I. Ilkorur](https://patents.google.com/?inventor=Onur+I.+Ilkorur&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种电子设备，包括：外壳，其外壳壁围绕换能器形成背腔室，并且声管将背腔室与外壳壁周围的环境耦合；以及连接到声管的阀门，能够响应换能器的声压级自动调节声管。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487358355_1.jpg)

**Technical Field (技术领域)**:  
音频设备领域，具体涉及可动态调节的换能器背腔室技术。

**Background (发明背景)**:  
电子设备中的换能器（如扬声器）需要将电信号转换为声波，但受限于设备体积，难以保持最佳音质。
现有技术中，换能器背腔室的设计对低频响应有显著影响，但缺乏根据音量动态调节的机制。
在高声压级下，换能器的振膜行程受限，影响低频输出。

**Summary (发明总览)**:  
本发明提出了一种可动态调节的换能器背腔室设计，通过声管和阀门系统，根据换能器的声压级自动调节背腔室的空气体积。
在高音量时，阀门打开声管以增加低频输出；在低音量时，阀门关闭声管以优化低频表现。
该设计通过调节声管的几何形状、表面积和体积，实现对共振频率的动态调整。
相较于传统固定背腔室设计，本发明在高低音量下均能提供更优的低频表现。

**Key Innovation (核心创新)**:  
1. 采用可调节声管设计，通过改变声管的几何形状、表面积和体积来动态调节共振频率。
2. 使用主动阀门（如电磁阀、滑动闸阀或微机电阀门）根据声压级自动调节声管的开闭状态。
3. 在高声压级下，阀门打开声管以最大化空气体积，从而提升低频输出能力。
4. 在低声压级下，阀门关闭声管以最小化空气体积，优化低频表现。
5. 声管系统可包含多个声管和阀门，通过协同工作实现更精细的空气体积调节。
6. 滑动部件设计可沿垂直于声管轴线的方向移动，根据不同声压级调节总空气体积。
7. 该技术可应用于耳机、扬声器等音频设备，在紧凑型设备中提供更优的低频音质表现。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358355)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292394)**
<br/><br/>

---


<br/>

### 30. 内容消费反馈

**Title (EN)**: Content consumption feedback  
**Pub. No.**: US12744833

**Applicant**: Apple Inc.  
**Inventor**: [Bradley W. Peebler](https://patents.google.com/?inventor=Bradley+W.+Peebler&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
本发明提供了一种在设备上提供内容消费反馈的方法，该设备包括显示屏、一个或多个处理器和非易失性存储器。该方法包括接收用户输入以定义第一内容消费偏好，该偏好指定了用户偏好的第一类型内容的数量；向第一内容提供商传输指示第一内容消费偏好的数据；确定用户从第一内容提供商处消费的第一类型内容的数量；并向用户提供关于用户消费的第一类型内容数量的反馈。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487049361_1.jpg)

**Technical Field (技术领域)**:  
用户界面技术领域，具体涉及内容消费反馈。

**Background (发明背景)**:  
现有应用通常基于推荐引擎向用户展示内容，该引擎根据用户与之前展示内容的互动来选择内容。然而，随着时间推移，推荐引擎倾向于选择用户潜意识偏好的内容，而非用户有意识偏好的内容。这可能导致用户消费的内容与实际偏好不符。

**Summary (发明总览)**:  
本发明旨在通过用户主动定义内容消费偏好来改进内容推荐系统。用户可以指定对特定类型内容的偏好量，系统将根据这些偏好向内容提供商传输数据，并跟踪用户实际消费情况。通过提供反馈，用户可以更好地控制内容消费并调整偏好设置，从而实现更符合用户意识偏好的内容推荐。

**Key Innovation (核心创新)**:  
1. 用户可以主动定义对特定类型内容的消费偏好，例如数量或频率，从而提供更精确的个性化设置。
2. 系统将用户定义的偏好数据传输给内容提供商，确保内容选择更符合用户的明确需求。
3. 通过跟踪用户实际消费的第一类型内容的数量，系统能够提供详细的反馈，帮助用户了解其消费习惯。
4. 该方法允许用户根据反馈调整偏好设置，实现对内容消费的动态控制。
5. 通过将用户意识偏好与实际消费行为结合，本发明解决了现有推荐引擎过度依赖潜意识偏好的问题。
6. 该技术可应用于流媒体、新闻资讯和社交媒体等多种内容平台，为用户提供更符合其明确需求的内容推荐。
7. 通过提供更精准的内容消费反馈，本发明提升了用户体验，并帮助用户更好地管理其内容消费行为。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487049361)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12744833)**
<br/><br/>

---


<br/>

### 31. 用于稳定球轴承接触的预紧力优化

**Title (EN)**: Preload force optimization for stable ball bearing contact  
**Pub. No.**: US12744434

**Applicant**: Apple Inc.  
**Inventor**: [Scott W Miller](https://patents.google.com/?inventor=Scott+W+Miller&assignee=Apple&country=US&num=100&sort=new), [Hao Zheng](https://patents.google.com/?inventor=Hao+Zheng&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
本发明涉及一种设备（例如相机或其他类型的设备），用于优化球轴承音圈电机（VCM）致动器的预紧力，以实现稳定的球轴承接触。通过放置和/或调整板的位置和形状，使预紧力的中心位于能够实现稳定球轴承接触的位置（例如，防止运动过程中框架/载体的动态倾斜/摇摆）。在某些实施例中，该设备包括一个柔性电路，用于向球轴承VCM致动器提供驱动电流。在一些实施例中，球轴承VCM致动器用于相机设备中，以移动载体的图像传感器相对于镜头的位置，从而实现对焦和/或自动对焦（AF）功能。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487048920_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及光学设备中的精密运动控制技术，具体为球轴承音圈电机（VCM）致动器的预紧力优化。

**Background (发明背景)**:  
球轴承VCM致动器广泛应用于各种设备中，用于实现组件的精确往复运动。例如，智能手机和平板设备中的小型高分辨率相机使用球轴承VCM致动器来移动图像传感器或镜头，以实现自动对焦功能。然而，现有技术中，预紧力的控制不当可能导致球轴承接触不稳定，进而影响运动精度和设备性能。

**Summary (发明总览)**:  
本发明提出了一种通过优化预紧力来提高球轴承VCM致动器稳定性的技术方案。其核心思路是通过调整预紧力作用点的位置和分布，确保球轴承在运动过程中保持稳定接触。实现路径包括设计特定形状的预紧力施加板，以及使用柔性电路提供精确的驱动电流。本发明相较于现有技术，能够有效减少运动过程中的动态倾斜和摇摆现象，提高设备的对焦精度和稳定性。

**Key Innovation (核心创新)**:  
1. 通过设计特定形状的预紧力施加板，将预紧力中心调整到最佳位置，从而实现稳定的球轴承接触。
2. 利用柔性电路提供精确的驱动电流，确保球轴承VCM致动器在不同工作条件下保持稳定性能。
3. 通过优化预紧力分布，减少运动过程中框架或载体的动态倾斜和摇摆现象，提高运动精度。
4. 适用于相机设备中，可精确控制图像传感器相对于镜头的位置，实现更可靠的对焦和自动对焦功能。
5. 创新性地结合机械结构和电路设计，提供了一种综合性的预紧力优化方案。
6. 该技术可应用于需要高精度运动控制的光学设备中，如智能手机相机、医疗成像设备等。
7. 通过提高球轴承接触稳定性，本发明能够显著提升设备的对焦速度和精度，为用户提供更优质的拍摄体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487048920)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12744434)**
<br/><br/>

---



**Total Patents**: 31  
**Last Updated**: 20260927

---

The Patent Scoop Trio
