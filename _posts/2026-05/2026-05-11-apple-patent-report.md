---
layout: post
title: "Apple 专利小快报 2026-05-11"
date: 2026-05-11 14:04:07 +0800
categories: Apple
---

**New Patents**: 13  

---


<br/>

### 1. 在头戴式设备中减轻闪烁并降低功耗的方法

**Title (EN)**: Mitigating Flicker and Reducing Power Consumption in a Head-Mounted Device  
**Pub. No.**: US20260129308

**Applicant**: Apple Inc.  
**Inventor**: [Daniel A Glynn](https://patents.google.com/?inventor=Daniel+A+Glynn&assignee=Apple&country=US&num=100&sort=new), [Simon Fortin-Deschenes](https://patents.google.com/?inventor=Simon+Fortin-Deschenes&assignee=Apple&country=US&num=100&sort=new), [Luke A Pillans](https://patents.google.com/?inventor=Luke+A+Pillans&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
本发明提供了一种用于操作电子设备（例如头戴式设备）以减轻闪烁相关问题的方法。该方法包括：以第一频率捕获物理环境的第一图像；确定光源的频率；基于光源的频率，将一个或多个图像传感器配置为以不同于第一频率的第二频率捕获物理环境的第二图像；并以不同于第二频率的显示频率输出失真图像。失真图像是通过基于头戴式设备在物理环境中的姿态，对在第二频率下捕获的第二图像的子集进行失真处理而生成的。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478565126_1.jpg)

**Technical Field (技术领域)**:  
电子设备技术领域，具体涉及头戴式设备中的图像处理与显示技术。

**Background (发明背景)**:  
头戴式设备通常配备摄像头以获取物理环境的实时视频流，并通过显示屏呈现给用户。环境中的光源可能以与摄像头和显示屏不同的频率调制，这可能导致视频流中出现明显的闪烁问题。现有的解决方案未能有效解决这种闪烁问题，影响用户体验。

**Summary (发明总览)**:  
本发明提出了一种通过调整图像捕获和显示频率来减轻头戴式设备中闪烁问题的方法。其核心思路是检测环境光源的频率，并相应地调整图像捕获频率，同时通过图像失真处理和选择性显示来优化显示效果。该方法不仅减轻了闪烁问题，还通过优化图像传感器设置提高了图像质量。

**Key Innovation (核心创新)**:  
1. 通过检测环境光源的频率并调整图像捕获频率，避免了光源调制引起的闪烁问题。
2. 采用图像失真处理技术，根据头戴式设备在物理环境中的姿态对图像进行动态调整，确保显示图像的准确性和稳定性。
3. 引入多组图像传感器设置，分别用于不同目的，例如曝光时间评估、图像传感器增益调整和高动态范围（HDR）恢复，以优化图像质量。
4. 通过选择性丢弃部分图像帧并对剩余图像进行失真处理，减少了处理负担，同时保持了显示的流畅性。
5. 在显示端采用与捕获端不同的显示频率，进一步减少闪烁现象。
6. 该方法不仅适用于增强现实（AR）、混合现实（MR）和虚拟现实（VR）场景，还能有效应用于各种需要实时视频显示的头戴式设备。
7. 通过优化图像处理和显示流程，本发明在减轻闪烁的同时降低了功耗，延长了设备的续航时间。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478565126)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260129308)**
<br/><br/>

---


<br/>

### 2. 跨设备交互

**Title (EN)**: CROSS DEVICE INTERACTIONS  
**Pub. No.**: US20260126942

**Applicant**: Apple Inc.  
**Inventor**: [Tianjia SUN](https://patents.google.com/?inventor=Tianjia+SUN&assignee=Apple&country=US&num=100&sort=new), [Chang ZHANG](https://patents.google.com/?inventor=Chang+ZHANG&assignee=Apple&country=US&num=100&sort=new), [Paul X. WANG](https://patents.google.com/?inventor=Paul+X.+WANG&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
本发明主要涉及跨设备交互的方法。当第一设备的第一显示屏上放置了具有第二显示屏的第二设备时，通过第一设备的输入设备检测到第一输入。根据检测到的第一输入以及判断输入发生时焦点是否在第二设备上，系统会在第二显示屏上显示对第一输入的响应。如果输入发生时焦点在第一设备上，则在第一显示屏上显示对第一输入的响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478562502_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及跨设备交互方法。

**Background (发明背景)**:  
用户常需使用多个设备访问存储在不同设备上的内容，但某些设备的显示屏不适合内容查看，用户也更习惯使用特定输入设备。现有的用户界面导航方法繁琐且效率低下，尤其在电池供电设备中，能量浪费问题突出。此外，不同用户界面之间的突然切换可能分散用户注意力，降低使用体验。

**Summary (发明总览)**:  
本发明提供了一种更快速、高效的跨设备交互方法，通过优化用户输入处理和界面响应逻辑，减少用户操作步骤和认知负担。该方法能够智能识别用户输入的焦点设备，并相应地在目标设备上显示响应内容，从而提升多设备内容交互的流畅性和效率，尤其适用于电池供电设备以节省电力。

**Key Innovation (核心创新)**:  
1. 通过检测用户输入的焦点设备，实现跨设备输入响应的智能分配，确保用户操作被正确识别并显示在目标设备上。
2. 在第一设备上放置第二设备时，系统能够识别设备间的空间关系，并根据输入焦点动态调整响应显示位置。
3. 提供内容创建用户界面，当第一设备从第二显示屏上移开后，自动在第一设备上显示内容创建界面，同时保留之前生成的内容，实现无缝过渡。
4. 通过减少用户输入次数和简化操作流程，降低用户认知负担，提升跨设备交互的效率和用户体验。
5. 优化电池供电设备的能耗管理，通过减少不必要的用户输入处理和界面渲染，延长设备续航时间。
6. 适用于多种设备类型，包括台式机、便携式设备和个人电子设备（如智能手表），具有广泛的适用性。
7. 可应用于文件管理、图像编辑、文档处理、视频播放、网页浏览等场景，为多设备协同工作提供创新解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478562502)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260126942)**
<br/><br/>

---


<br/>

### 3. 光学外壳

**Title (EN)**: OPTICAL ENCLOSURE  
**Pub. No.**: US20260126662

**Applicant**: Apple Inc.  
**Inventor**: [Ivan S. MARIC](https://patents.google.com/?inventor=Ivan+S.+MARIC&assignee=Apple&country=US&num=100&sort=new), [Cole SNIDER](https://patents.google.com/?inventor=Cole+SNIDER&assignee=Apple&country=US&num=100&sort=new), [Kalman S. SOBEL](https://patents.google.com/?inventor=Kalman+S.+SOBEL&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
一种可穿戴电子设备可以包括用于支撑显示器并促进其移动以实现与用户眼睛正确光学对准的一体式光学外壳。该光学外壳可以包括具有锥形直径的筒体，并在其上形成具有低反射率的涂层以提高显示器的相对对比度。光学外壳还可以包括一个或多个挂架，每个挂架定义一个用于接收导杆的通道。挂架可以各自提供具有低摩擦系数的涂层的内表面，以促进与导杆的滑动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478562193_1.jpg)

**Technical Field (技术领域)**:  
本专利属于头戴式设备领域，具体涉及用于光学对准的光学外壳技术。

**Background (发明背景)**:  
头戴式设备可由用户佩戴以在用户的视野内显示视觉信息，广泛应用于虚拟现实、增强现实和混合现实系统。现有的光学外壳通常由多个部件组成，这导致制造复杂且成本较高。此外，部件之间的连接可能导致性能不一致，且多部件设计会增加重量和装配难度。

**Summary (发明总览)**:  
本发明提出了一种用于头戴式设备的一体式光学外壳设计，通过采用锥形筒体和低反射率涂层来提高显示器的光学性能。光学外壳还包括带有低摩擦涂层挂架的导杆结构，以实现平稳移动。这种一体式设计简化了制造和装配过程，并提高了光学对准的精度和可靠性。

**Key Innovation (核心创新)**:  
1. 采用一体式光学外壳设计，替代传统多部件结构，减少了制造复杂性和成本。
2. 光学外壳筒体具有锥形直径，并涂覆低反射率涂层，有效提高显示器的对比度和视觉清晰度。
3. 挂架内表面涂覆低摩擦系数材料，确保与导杆的平稳滑动，实现精确的光学对准。
4. 一体式结构消除了部件间的连接问题，确保光学外壳各部分动作的一致性和可靠性。
5. 通过减少零件数量和简化装配过程，降低了整体重量和装配难度。
6. 该设计特别适用于需要高精度光学对准的虚拟现实、增强现实和混合现实头戴式设备。
7. 提升了用户视觉体验的舒适度和准确性，同时优化了设备的耐用性和长期性能稳定性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478562193)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260126662)**
<br/><br/>

---


<br/>

### 4. 动态确定呈现区域和过渡区域的方法和设备

**Title (EN)**: Method and Device for Dynamic Determination of Presentation and Transitional Regions  
**Pub. No.**: US20260127832

**Applicant**: Apple Inc.  
**Inventor**: [Benjamin H. Boesel](https://patents.google.com/?inventor=Benjamin+H.+Boesel&assignee=Apple&country=US&num=100&sort=new), [David H. Huang](https://patents.google.com/?inventor=David+H.+Huang&assignee=Apple&country=US&num=100&sort=new), [Jonathan Perron](https://patents.google.com/?inventor=Jonathan+Perron&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
本发明实施例公开了一种用于动态确定虚拟内容呈现视角距离的方法。该方法包括获取与物理环境相关联的第一维度；检测用于呈现虚拟内容的请求；在检测到请求后，获取与虚拟内容相关联的第二维度；基于第一维度和第二维度确定视角距离；并基于视角距离生成虚拟内容的呈现区域。最后，将虚拟内容呈现在所述呈现区域内。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478563491_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及内容呈现技术领域，具体为动态确定扩展现实内容呈现区域和过渡区域的方法。

**Background (发明背景)**:  
在狭小空间如飞机或汽车中呈现扩展现实（XR）内容时，由于视角距离不足，难以保持正确的比例。
简单地通过"门户"叠加XR内容以实现更大视角距离可能导致视觉不连续性，影响用户体验。
现有技术未能有效解决在有限物理空间内呈现虚拟内容时的比例和视觉连续性问题。

**Summary (发明总览)**:  
本发明提出了一种动态确定虚拟内容呈现区域和过渡区域的方法，通过分析物理环境和虚拟内容的特性来计算合适的视角距离。
该方法生成一个呈现区域用于显示虚拟内容，并围绕呈现区域生成一个过渡区域以减少视觉不连续性。
通过同时呈现虚拟内容和过渡区域，本发明能够在有限物理空间内提供更自然的虚拟内容呈现体验。
相较于现有技术，本发明通过综合考虑物理环境和虚拟内容特性，实现了更平滑的视觉过渡。

**Key Innovation (核心创新)**:  
1. 通过获取物理环境的第一维度和虚拟内容的第二维度，动态计算视角距离，从而确定虚拟内容的呈现区域。
2. 生成一个过渡区域，该区域围绕虚拟内容的呈现区域，用于减少虚拟内容与物理环境之间的视觉不连续性。
3. 利用显示设备同时呈现虚拟内容和过渡区域，确保用户在不同视角下获得更自然的视觉体验。
4. 通过综合考虑物理环境和虚拟内容的特性，实现对呈现区域和过渡区域的动态调整，适应不同场景需求。
5. 该方法可应用于头戴式设备、智能手机、平板电脑等多种电子设备，提升用户在狭小空间内使用XR内容的体验。
6. 通过光学波导、反射镜或全息介质等技术手段实现过渡区域的显示，进一步增强视觉连续性。
7. 本专利特别适用于在狭小物理空间内呈现虚拟内容，如飞机、汽车座舱等场景，为用户提供更沉浸的XR体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478563491)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260127832)**
<br/><br/>

---


<br/>

### 5. 基于视觉语言动作模型的端到端移动用户界面导航

**Title (EN)**: END-TO-END MOBILE USER INTERFACE NAVIGATION WITH VISION LANGUAGE ACTION MODELS  
**Pub. No.**: US20260127015

**Applicant**: Apple Inc.  
**Inventor**: [Di FENG](https://patents.google.com/?inventor=Di+FENG&assignee=Apple&country=US&num=100&sort=new), [Keen YOU](https://patents.google.com/?inventor=Keen+YOU&assignee=Apple&country=US&num=100&sort=new), [Zhen YANG](https://patents.google.com/?inventor=Zhen+YANG&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
本发明提供了一种基于视觉语言动作模型的端到端移动用户界面导航方法。装置接收来自电子设备用户界面的语言指令和视觉输入，并分别对语言指令和视觉输入进行分词处理。随后，装置使用多模态大语言模型处理分词后的语言指令和视觉输入，生成一个或多个动作输出。装置还将这些动作输出转换为可执行的命令，以使电子设备在用户界面上执行导航任务。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478562583_1.jpg)

**Technical Field (技术领域)**:  
人工智能与机器学习领域，具体涉及多模态大语言模型在移动用户界面导航中的应用。

**Background (发明背景)**:  
近年来，机器学习因训练数据的可用性和计算硬件的进步而迅速普及。大语言模型通常包含数亿到数十亿参数，需要大量计算能力和内存进行训练和推理。然而，在不同环境中部署大型机器学习模型存在性能挑战。现有的自主用户界面代理通常依赖复杂的模块化设计，并受限于在线评估和重新规划能力。此外，高质量的移动设备导航数据集匮乏，影响了模型的训练效果。

**Summary (发明总览)**:  
本发明提出了一种基于多模态大语言模型的自主用户界面代理，用于端到端的移动用户界面导航。该代理通过整合视觉、语言和动作处理，解释用户的自然语言指令和视觉输入，并生成自动化设备控制动作。其核心实现路径包括收集高质量导航数据、构建多模态大语言模型以及开发推理和重新规划机制。本发明相较于现有技术的主要改进在于简化了代理架构，提升了导航任务的执行效率和准确性。

**Key Innovation (核心创新)**:  
1. 采用多模态大语言模型，将视觉、语言和动作处理整合到一个端到端框架中，消除了对外部UI检测器的依赖。
2. 设计了包含2亿、8亿和130亿参数的不同规模模型，以适应不同设备的能力需求，提升了部署灵活性。
3. 通过收集和分析高质量操作系统导航数据，优化了模型在跨平台和跨应用场景下的性能。
4. 引入了用户意图预测组件，使代理能够总结和推断用户目标，从而增强交互的通用性。
5. 应用合成数据生成技术，通过模拟常见导航错误（如错误点击位置或重复操作）来增强模型的鲁棒性。
6. 开发了基于大语言模型的探索机制，用于自主数据收集，生成包含噪声和可变性的训练数据，提高模型在不可预测环境中的适应性。
7. 利用链式推理机制，通过推理轨迹支持多步骤逻辑思考，提升复杂导航场景中的决策准确性和可靠性，可应用于智能助手和自动化任务执行等领域。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478562583)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260127015)**
<br/><br/>

---


<br/>

### 6. 在具有触控显示的电子设备上主动识别并呈现相关内容的系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR PROACTIVELY IDENTIFYING AND SURFACING RELEVANT CONTENT ON AN ELECTRONIC DEVICE WITH A TOUCH-SENSITIVE DISPLAY  
**Pub. No.**: US20260129406

**Applicant**: Apple Inc.  
**Inventor**: [Daniel C. GROSS](https://patents.google.com/?inventor=Daniel+C.+GROSS&assignee=Apple&country=US&num=100&sort=new), [Jesper S. ANDERSEN](https://patents.google.com/?inventor=Jesper+S.+ANDERSEN&assignee=Apple&country=US&num=100&sort=new), [Hafid ARRAS](https://patents.google.com/?inventor=Hafid+ARRAS&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
本发明公开了在具有触控显示的电子设备上主动识别并呈现相关内容的系统和方法。在一个方面中，方法包括在第一应用中呈现内容，其中至少部分内容无需用户输入即可呈现。该方法进一步包括接收打开第二应用的请求。在响应接收该请求时，第二应用以包含输入接收字段的界面呈现。在接收任何用户输入之前，显示一个可选择的用户界面对象，指示在第一应用中已查看的内容部分，允许用户将该内容部分粘贴到输入接收字段中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478565233_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及具有触控显示的电子设备领域，具体为通过主动识别和呈现相关内容来提升用户交互效率的技术。

**Background (发明背景)**:  
触控显示的便携式电子设备已广泛普及，用户在设备上安装多个应用以提高日常活动效率。然而，用户需要花费大量时间解锁设备、查找应用及其功能。此外，应用中不断涌现的信息流使用户难以即时处理，导致用户希望稍后回顾特定信息时难以定位。本发明旨在提供一种直观易用的系统和方法，主动识别并呈现相关重要内容，以解决上述问题。

**Summary (发明总览)**:  
本发明提出了一种通过主动识别和呈现相关内容来提升用户交互效率的方案。其核心思路是在用户明确请求之前，智能预测用户需求并提供相关信息，例如联系人、地点、应用、文章等。实现路径包括在用户切换应用或执行特定操作时，自动检测并分析用户行为，识别潜在需求，然后以可选择的方式呈现相关内容。该方案减少了用户查找信息所需的输入次数，提升了设备操作效率，并延长了触控显示的使用寿命。

**Key Innovation (核心创新)**:  
1. 通过分析用户行为和上下文，主动识别用户可能需要的内容，例如联系人、位置、应用或信息片段。
2. 在用户切换应用或执行特定操作时，自动在界面上呈现相关内容，无需用户额外搜索或输入。
3. 采用可选择的用户界面对象，允许用户将识别到的重要内容快速粘贴到目标输入字段中。
4. 通过减少用户查找和输入操作，优化了人机交互流程，提升了设备操作效率。
5. 降低了触控显示的使用频率，从而延长了设备电池续航时间和触控显示寿命。
6. 该技术可应用于智能手机、平板电脑等便携设备，尤其适用于需要频繁切换应用和处理信息的场景。
7. 独特价值在于提供了一种更智能、更高效的内容呈现方式，使用户能够更快速地访问所需信息。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478565233)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260129406)**
<br/><br/>

---


<br/>

### 7. 用于内容变形的用户界面和技术

**Title (EN)**: USER INTERFACES AND TECHNIQUES FOR DEFORMING CONTENT  
**Pub. No.**: US20260126897

**Applicant**: Apple Inc.  
**Inventor**: [James M. GRAHAM](https://patents.google.com/?inventor=James+M.+GRAHAM&assignee=Apple&country=US&num=100&sort=new), [Stephane P. BERSOT](https://patents.google.com/?inventor=Stephane+P.+BERSOT&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
本公开内容主要涉及内容变形技术。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478562452_1.jpg)

**Technical Field (技术领域)**:  
本专利属于计算机用户界面领域，具体涉及通过空间变形指示输入位置的技术。

**Background (发明背景)**:  
电子设备通常需要指示输入位置，例如通过屏幕上的光标。然而，现有技术存在不足，例如使用鼠标光标覆盖内容区域，导致操作繁琐且效率低下。这些方法耗时较长，浪费用户时间和设备能量，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种更快速高效的用户界面技术，通过检测输入设备的位置并对用户界面背景进行空间变形来指示输入位置。该方法通过在用户界面背景的不同区域进行动态变形来响应输入位置的变化，从而减少用户认知负担，提高人机交互效率，并节省电池供电设备的能耗。

**Key Innovation (核心创新)**:  
1. 通过检测输入设备在用户界面外的空间位置，触发用户界面背景特定区域的空间变形，从而指示输入位置。
2. 采用动态变形技术，仅对当前输入位置对应的背景区域进行变形，而不影响其他区域，从而提高视觉清晰度。
3. 当输入位置变化时，动态更新变形区域，确保用户界面能够实时反映输入位置的变化。
4. 通过仅对相关背景区域进行变形，减少了对用户界面的视觉干扰，提升了用户体验。
5. 该方法适用于电池供电设备，通过减少不必要的显示更新，节省设备能耗并延长电池续航时间。
6. 该技术可应用于触摸屏设备、触控板设备等多种输入方式，提供一致且高效的交互体验。
7. 通过减少用户认知负担和提高交互效率，该技术特别适用于需要频繁输入操作的应用场景，如绘图软件、游戏和生产力工具。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478562452)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260126897)**
<br/><br/>

---


<br/>

### 8. 用于同时进行眼部特征跟踪和眼部模型更新的方法、系统和装置

**Title (EN)**: Methods, Systems, and Apparatuses For Simultaneous Eye Characteristic Tracking and Eye Model Updating  
**Pub. No.**: US20260127762

**Applicant**: Apple Inc.  
**Inventor**: [Hao Qin](https://patents.google.com/?inventor=Hao+Qin&assignee=Apple&country=US&num=100&sort=new), [Chia-Yin Tsai](https://patents.google.com/?inventor=Chia-Yin+Tsai&assignee=Apple&country=US&num=100&sort=new), [Tom Sengelaub](https://patents.google.com/?inventor=Tom+Sengelaub&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
本发明公开了通过同时或近乎同时的眼部特征跟踪和眼部模型更新实现用户设备上的隐蔽眼部注册的方法。所述实现方式将光线引导至用户的眼睛以产生反光亮点，并通过一个或多个传感器获取包含反光亮点描绘的图像帧。基于这些图像帧，在获取第一图像帧和第二图像帧之间的时间段内跟踪眼部特征并更新眼睛模型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478563413_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及眼部特征跟踪和三维眼部建模技术，具体为同时进行眼部特征跟踪和眼部模型更新的方法。

**Background (发明背景)**:  
现有技术中，眼部跟踪和眼部三维建模通常作为独立过程进行。传统的眼部注册过程通常需要用户执行一系列复杂的注视任务，这导致用户体验不佳，尤其是在需要快速进入扩展现实（XR）体验的场景中。本发明旨在解决用户注册过程繁琐的问题，通过在用户正常活动期间同时进行眼部特征跟踪和模型更新来简化注册流程。

**Summary (发明总览)**:  
本发明提出了一种在用户正常活动期间同时进行眼部特征跟踪和眼部模型更新的方法。通过使用红外光源在眼睛上产生反光亮点，并利用传感器捕捉包含这些亮点的图像帧，系统能够在捕捉到的新图像帧中实时确定眼部特征（如注视方向）并更新三维眼部模型。该方法无需用户执行复杂的注视任务，而是在后台自动完成注册过程，从而提供更便捷的用户体验。

**Key Innovation (核心创新)**:  
1. 通过同时进行眼部特征跟踪和模型更新，简化了用户注册流程，无需用户执行复杂的注视任务。
2. 利用红外光源在眼睛上产生反光亮点，并通过传感器捕捉包含这些亮点的图像帧，实现高精度的眼部特征捕捉。
3. 基于图像帧的实时处理，系统能够在捕捉到的新图像帧中同时确定眼部特征和更新三维眼部模型。
4. 通过比较图像帧中的眼部部分与覆盖图，选择关键帧进行模型更新，提高更新效率和精度。
5. 系统包括非易失性计算机可读存储介质、一个或多个处理器以及执行所述方法的程序指令，确保方法的可靠性和可扩展性。
6. 该方法特别适用于头戴式显示器（HMD），能够在用户进行其他任务时自动完成眼部注册，提升用户体验。
7. 本发明为扩展现实（XR）应用提供了一种高效的眼部注册解决方案，使用户能够快速进入沉浸式体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478563413)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260127762)**
<br/><br/>

---


<br/>

### 9. 眼动追踪数据过滤

**Title (EN)**: Eye Tracking Data Filtering  
**Pub. No.**: US20260126855

**Applicant**: Apple Inc.  
**Inventor**: [Jacob Wilson](https://patents.google.com/?inventor=Jacob+Wilson&assignee=Apple&country=US&num=100&sort=new), [Tobias Eble](https://patents.google.com/?inventor=Tobias+Eble&assignee=Apple&country=US&num=100&sort=new), [Sabine Webel](https://patents.google.com/?inventor=Sabine+Webel&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
眼动追踪通过确定用户相对于其前方镜片的初始瞳孔位置，检测瞳孔位置相对于镜片的移动变化至更新位置，并确定更新后的瞳孔位置是否超出与镜片相关的边界框来实现。如果更新后的瞳孔位置超出边界框，则选择边界框内的替代瞳孔位置，并利用更新后的瞳孔位置进行眼动追踪功能。眼动追踪还包括确定与注视方向相关的第一像素是否超出可见区域，识别可见区域内的替代像素，并基于替代像素的位置确定更新后的注视角度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478562405_1.jpg)

**Technical Field (技术领域)**:  
图像处理领域，具体涉及眼动追踪数据的生成和管理技术。

**Background (发明背景)**:  
眼动追踪广泛应用于注视检测、姿态估计、面部分析和识别等领域，其基础是电子定位和跟踪用户的注视点。然而，用于追踪眼睛的传感器常出现位移或抖动，导致眼动追踪数据不够精确或无效。现有的眼动追踪数据管理方法存在不足，需要改进以提高数据精度和稳定性。

**Summary (发明总览)**:  
本发明提出了一种改进的眼动追踪数据处理方法，通过将瞳孔位置限制在预定的校准区域内来提高数据精度。当检测到瞳孔位置超出校准区域时，系统会选择校准区域内的替代位置，并通过时间缓动函数平滑过渡以减少抖动。此外，本发明还优化了注视方向的计算，通过在可见区域内选择替代像素来修正注视角度，从而提高眼动追踪的可靠性和准确性。

**Key Innovation (核心创新)**:  
1. 通过将瞳孔位置限制在预定的校准区域内，确保眼动追踪数据的精确性和稳定性。
2. 当检测到瞳孔位置超出校准区域时，系统自动选择校准区域内的替代位置，避免数据无效。
3. 采用时间缓动函数平滑瞳孔位置的过渡，减少因传感器抖动引起的误差。
4. 优化注视方向的计算，通过在可见区域内选择替代像素来修正注视角度。
5. 提供了一种从视野中心到第一像素的向量选择方法，确保替代像素选择的合理性。
6. 通过上述技术改进，本发明能够有效减少眼动追踪数据中的噪声和误差。
7. 本发明可应用于虚拟现实、增强现实和用户界面交互等领域，提升用户体验和系统可靠性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478562405)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260126855)**
<br/><br/>

---


<br/>

### 10. 用于控制一个或多个电子设备的用户界面和技术

**Title (EN)**: TECHNIQUES AND USER INTERFACES FOR CONTROLLING ONE OR MORE ELECTRONIC DEVICES  
**Pub. No.**: US20260126900

**Applicant**: Apple Inc.  
**Inventor**: [Arian BEHZADI](https://patents.google.com/?inventor=Arian+BEHZADI&assignee=Apple&country=US&num=100&sort=new), [Christopher P. FOSS](https://patents.google.com/?inventor=Christopher+P.+FOSS&assignee=Apple&country=US&num=100&sort=new), [Andrew S. KIM](https://patents.google.com/?inventor=Andrew+S.+KIM&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 07.05.2026

**Abstract**:  
本公开涉及用于控制一个或多个电子设备以及根据某些示例显示一个或多个控制的用户界面和技术。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478562455_1.jpg)

**Technical Field (技术领域)**:  
本专利属于计算机用户界面领域，具体涉及电子设备控制技术。

**Background (发明背景)**:  
计算机系统通常与外部电子设备和/或外部计算机系统通信，以控制其操作。现有的控制方法通常繁琐且效率低下，例如需要复杂的用户界面和多次按键操作，这浪费了用户时间和设备能量，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种更快速、更高效的用户界面和控制方法，用于管理电子设备。通过检测用户指向设备的方向并显示相应控制指示，系统能够简化用户操作并减少认知负担。该方法通过方向检测和输入识别来切换控制目标，从而实现更高效的人机交互，尤其适用于电池供电设备以节省电力。

**Key Innovation (核心创新)**:  
1. 通过检测计算机系统指向设备的方向并持续一定时间，触发对该设备的控制指示显示。
2. 在显示控制指示的同时，检测用户是否改变指向方向，并在新方向上识别可控制设备。
3. 当检测到新的指向方向对应另一可控制设备且在原方向上有输入时，系统切换控制目标并更新显示指示。
4. 如果新指向方向无对应设备，系统保持原控制指示，避免误操作。
5. 通过方向检测和输入识别相结合，实现无需复杂界面的直观设备控制。
6. 该方法减少了用户操作步骤，提高了控制效率，尤其适用于电池供电设备以延长使用时间。
7. 可应用于智能家居、办公设备等场景，提供更便捷的设备管理和控制体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478562455)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260126900)**
<br/><br/>

---


<br/>

### 11. 用于锚定的深度信息补充方法

**Title (EN)**: Supplementing depth information for anchoring  
**Pub. No.**: US12620178

**Applicant**: Apple Inc.  
**Inventor**: [Rudy Poot](https://patents.google.com/?inventor=Rudy+Poot&assignee=Apple&country=US&num=100&sort=new), [Alvin Chung](https://patents.google.com/?inventor=Alvin+Chung&assignee=Apple&country=US&num=100&sort=new), [Tomas Alvarez Rodriguez](https://patents.google.com/?inventor=Tomas+Alvarez+Rodriguez&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 05.05.2026

**Abstract**:  
本发明涉及一种方法，包括获取指示电子设备在物理环境中的多个姿态的姿态数据，获取三维(3D)环境的表示。该3D环境表示包括多个平面，每个平面在xy空间中定义多个点，但不包括z空间(例如，深度)信息。该方法还包括基于姿态数据将3D环境表示锚定到物理环境中的物理锚定点，以及基于姿态数据将计算机生成的对象锚定到3D环境表示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478299207_1.jpg)

**Technical Field (技术领域)**:  
增强现实(AR)和虚拟现实(VR)技术领域，具体涉及3D环境锚定和深度信息补充技术。

**Background (发明背景)**:  
在增强现实和虚拟现实应用中，将虚拟环境锚定到物理环境是一个关键问题。现有的技术通常通过渲染环境来减少计算需求，但这种表示方式包含的图形信息较少，导致难以高效地将额外内容锚定到已锚定的环境表示上。

**Summary (发明总览)**:  
本发明提出了一种通过姿态数据将简化的3D环境表示锚定到物理环境的方法，并进一步将计算机生成的对象锚定到该环境表示上。该方法通过减少渲染的图形信息来降低计算需求，同时通过姿态数据确保锚定的准确性。相较于现有技术，本发明在保持较低计算成本的同时，提高了锚定附加内容的效率。

**Key Innovation (核心创新)**:  
1. 通过获取电子设备在物理环境中的姿态数据，实现对3D环境表示的精确锚定。
2. 使用包含多个xy平面但不包含深度信息的简化3D环境表示，降低渲染计算需求。
3. 基于姿态数据，将计算机生成的对象高效地锚定到简化的3D环境表示上。
4. 通过减少图形信息量，在保持锚定精度的同时，降低了计算资源的消耗。
5. 提供了一种在低计算成本下实现环境锚定的解决方案，适用于资源受限的设备。
6. 该方法可应用于增强现实应用场景，如虚拟物体放置和空间交互，提升用户体验。
7. 通过优化锚定过程，本发明能够支持更复杂的虚拟内容与物理环境的融合。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478299207)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12620178)**
<br/><br/>

---


<br/>

### 12. 使用组合变形函数对图像进行变形

**Title (EN)**: Warping an image with a combination of warping functions  
**Pub. No.**: US12620052

**Applicant**: Apple Inc.  
**Inventor**: [Seyedkoosha Mirhosseini](https://patents.google.com/?inventor=Seyedkoosha+Mirhosseini&assignee=Apple&country=US&num=100&sort=new), [Seyedpooya Mirhosseini](https://patents.google.com/?inventor=Seyedpooya+Mirhosseini&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 05.05.2026

**Abstract**:  
一种方法包括获取包含多个像素的图像。方法包括识别出用户当前关注的特定几何形状的像素子集。方法包括根据基于电子设备运动的第一个变形函数对该像素子集进行变形。方法还包括根据与第一个变形函数不同的第二个变形函数，对不同于第一像素子集的第二像素子集进行变形。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478299069_1.jpg)

**Technical Field (技术领域)**:  
图像处理领域，具体涉及基于设备运动对图像进行选择性变形的技术。

**Background (发明背景)**:  
带有集成摄像头和显示器的设备能够捕捉物理环境图像并在屏幕上显示。当设备移动时，设备可以对图像进行变形以合成并呈现新的视角视图。然而，图像变形通常是一个资源密集型操作。现有技术中，变形操作可能影响设备性能和用户体验。本发明旨在解决在设备运动时高效处理图像变形的问题。

**Summary (发明总览)**:  
本发明提出了一种基于设备运动对图像进行选择性变形的方案。通过识别用户关注的图像区域，并使用不同的变形函数分别处理关注区域和其他区域，实现了更高效的图像变形处理。该方法在保证变形效果的同时，降低了计算资源消耗，相较于传统整体变形方法具有更好的性能和适应性。

**Key Innovation (核心创新)**:  
1. 通过识别用户关注的图像区域，将图像分为关注区域和非关注区域，分别进行变形处理。
2. 使用基于设备运动的第一个变形函数对关注区域进行精细变形，以保持用户关注内容的视觉连贯性。
3. 对非关注区域应用不同的第二个变形函数，以简化计算并降低资源消耗。
4. 通过组合使用不同的变形函数，实现了对图像变形的动态调整，适应设备运动的变化。
5. 该方法在保证变形效果的同时，减少了计算资源的需求，提高了设备在变形处理上的效率。
6. 推测本专利可应用于增强现实（AR）和虚拟现实（VR）设备中，提供更流畅和自然的视角变换体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478299069)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12620052)**
<br/><br/>

---


<br/>

### 13. 基于检测物理环境中的关联上下文显示内容

**Title (EN)**: Displaying content based on detecting an associated context in a physical environment  
**Pub. No.**: US12619346

**Applicant**: Apple Inc.  
**Inventor**: [Thomas G. Salter](https://patents.google.com/?inventor=Thomas+G.+Salter&assignee=Apple&country=US&num=100&sort=new), [Jeffrey S. Norris](https://patents.google.com/?inventor=Jeffrey+S.+Norris&assignee=Apple&country=US&num=100&sort=new), [Christopher I. Word](https://patents.google.com/?inventor=Christopher+I.+Word&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 05.05.2026

**Abstract**:  
本发明涉及在电子设备上检测上下文（例如，检测物理对象以及可选地满足一个或多个条件）以在呈现的三维环境中显示用户界面元素时，自动显示应用程序的用户界面元素等内容的系统和方法。通过在满足特定条件（例如，三维环境的上下文适合显示用户界面元素）时自动显示用户界面元素，本发明旨在改善用户体验。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478298290_1.jpg)

**Technical Field (技术领域)**:  
本专利属于增强现实和用户界面技术领域，具体涉及基于物理环境上下文触发用户界面元素显示的技术。

**Background (发明背景)**:  
现有计算机图形环境提供二维和/或三维虚拟对象显示，但缺乏与现实物理环境有效融合的机制。传统系统难以根据用户所处物理环境自动调整显示内容，导致用户体验不够直观和便捷。本发明旨在解决这一问题，通过检测物理对象及其关联上下文，实现用户界面元素的智能显示。

**Summary (发明总览)**:  
本发明提出了一种基于物理环境上下文自动显示用户界面元素的方法。系统通过摄像头捕捉物理环境中的对象，并允许用户将特定对象与应用程序界面关联起来。当检测到关联对象及其满足的条件时，系统自动显示相应的用户界面元素。该方法通过预定义和用户自定义的关联方式，实现了更智能和个性化的内容显示，提升了用户与电子设备交互的便捷性和直观性。

**Key Innovation (核心创新)**:  
1. 通过摄像头捕捉物理环境并识别特定对象（如衣柜或窗户），实现对象与应用程序界面的关联。
2. 支持用户自定义关联规则，允许将通用物理对象（如透明或类窗户对象）与应用程序界面绑定。
3. 允许一个物理对象关联多个上下文条件，从而实现更灵活和多样化的用户界面触发机制。
4. 在检测到关联对象及其满足的条件时，系统自动在三维环境中显示相应的用户界面元素，提升交互的智能化和便捷性。
5. 提供预定义关联选项，用户可以选择接受或自定义现有关联规则，简化设置流程。
6. 通过多条件判断和对象识别技术，确保用户界面元素在适当的三维环境上下文中显示，避免误触发。
7. 该技术可应用于智能家居、导航系统和增强现实应用等领域，为用户提供更直观和个性化的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478298290)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12619346)**
<br/><br/>

---



**Total Patents**: 13  
**Last Updated**: 20260511

---

The Patent Scoop Trio
