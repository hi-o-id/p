---
layout: post
title: "Apple 专利小快报 2026-09-12"
date: 2026-09-12 13:39:58 +0800
categories: Apple
---

**New Patents**: 23  

---


<br/>

### 1. 头戴式设备中的图像捕捉预测

**Title (EN)**: Predicting Image Capture in a Head-Mounted Device  
**Pub. No.**: US20260270568

**Applicant**: Apple Inc.  
**Inventor**: [Shannon L. Gardiner](https://patents.google.com/?inventor=Shannon+L.+Gardiner&assignee=Apple&country=US&num=100&sort=new), [Chiraag Juvekar](https://patents.google.com/?inventor=Chiraag+Juvekar&assignee=Apple&country=US&num=100&sort=new), [Karan Sanghi](https://patents.google.com/?inventor=Karan+Sanghi&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明提供了一种头戴式设备，包括一个或多个图像传感器、用于运行头戴式设备操作系统的第一处理电路、用于控制一个或多个图像传感器捕捉图像的第二处理电路、用于预测用户图像捕捉输入的一个或多个组件，以及用于在预测到用户输入时唤醒第二处理电路的第三处理电路。图像传感器可以将捕捉到的图像输出到图像信号处理（ISP）电路。ISP电路包括计算机视觉处理（CVP）电路，该电路接收捕捉到的图像，并具有在第一电源域中运行的子系统和在第二电源域中运行的后端图像信号处理流水线。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619902_1.jpg)

**Technical Field (技术领域)**:  
头戴式设备技术领域，具体涉及图像捕捉预测和低功耗图像处理。

**Background (发明背景)**:  
头戴式设备通常配备摄像头用于捕捉周围环境的图像。然而，传统的设备在捕捉图像时需要持续运行处理电路，导致功耗较高。现有的解决方案未能有效平衡图像捕捉的及时性和设备功耗问题。本发明旨在解决这一问题，通过预测用户输入来优化图像捕捉流程，从而降低功耗并提高响应速度。

**Summary (发明总览)**:  
本发明提出了一种头戴式设备，通过预测用户图像捕捉输入来优化图像捕捉流程。设备包含多个处理电路，其中第三处理电路用于预测用户输入并唤醒第二处理电路以启动图像捕捉。第二处理电路在唤醒后控制图像传感器开始捕捉图像，而第三处理电路在捕捉过程中检测用户输入并唤醒第一处理电路以完成后续处理。该方法通过预测和分阶段唤醒处理电路，降低了设备功耗并提高了图像捕捉的响应速度。

**Key Innovation (核心创新)**:  
1. 通过惯性测量单元（IMU）检测用户按压设备的动作模式，实现对图像捕捉意图的预测。
2. 利用麦克风检测用户发出图像捕捉前的特定语音指令，进一步提高预测准确性。
3. 通过凝视传感器检测用户视线移动至虚拟按钮的位置，从而预测图像捕捉意图。
4. 采用上下文视觉子系统分析用户所处场景，智能判断是否可能进行图像捕捉。
5. 第三处理电路在预测到用户输入后，仅唤醒第二处理电路以启动图像捕捉，延迟唤醒第一处理电路以节省功耗。
6. 第二处理电路在唤醒后立即控制图像传感器开始捕捉图像，确保捕捉过程的及时性。
7. 本发明可应用于增强现实（AR）、虚拟现实（VR）以及日常拍摄场景中，提供低功耗、高响应的图像捕捉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619902)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270568)**
<br/><br/>

---


<br/>

### 2. 集成硬件按钮的用户界面

**Title (EN)**: USER INTERFACES INTEGRATING HARDWARE BUTTONS  
**Pub. No.**: US20260270547

**Applicant**: Apple Inc.  
**Inventor**: [Andre SOUZA DOS SANTOS](https://patents.google.com/?inventor=Andre+SOUZA+DOS+SANTOS&assignee=Apple&country=US&num=100&sort=new), [Marcos ALONSO](https://patents.google.com/?inventor=Marcos+ALONSO&assignee=Apple&country=US&num=100&sort=new), [Johnnie B. MANZARI](https://patents.google.com/?inventor=Johnnie+B.+MANZARI&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明描述了集成一个或多个硬件按钮的用户界面，包括相机用户界面，该界面能够根据不同按钮的按下或不同类型的按钮按压执行不同的媒体捕捉操作（例如，不同类型的捕捉、合成景深操作和/或相机用户界面的变化）、在相机应用内外对按钮按压提供不同的响应，以及根据不同类型的按钮按压提供不同的设置功能。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619880_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及集成硬件按钮的智能设备用户界面设计。

**Background (发明背景)**:  
电子设备（如智能手机、平板电脑和可穿戴设备）通过用户界面控制的功能范围、种类和复杂性不断增加。现有的用户界面依赖于显示软件控件或硬件按钮，但这些方法存在不足，例如过多的硬件按钮会增加设备尺寸、重量和成本，而过度依赖触摸控件或频繁切换软件控件和硬件按钮的系统则复杂、易出错、分散注意力且耗时，尤其对电池供电设备而言效率低下。

**Summary (发明总览)**:  
本发明提出了一种更高效的用户界面集成硬件按钮的方法，通过优化硬件按钮与软件界面的交互逻辑，减少用户认知负担并提升操作效率。该方法通过区分不同按钮或不同按压方式触发不同的功能操作，例如在相机应用中根据按压的硬件按钮或按压力度执行不同的媒体捕捉操作或界面调整，从而实现更直观和节能的用户体验。

**Key Innovation (核心创新)**:  
1. 通过区分不同硬件按钮的按压操作，实现多样化的媒体捕捉功能，例如在相机应用中根据按下的具体按钮执行不同的捕捉模式或效果处理。
2. 引入按压力度检测机制，根据按压力度区分执行媒体捕捉操作或界面调整功能，从而提供更丰富的交互方式。
3. 在相机应用内外对硬件按钮的按压提供不同的响应逻辑，例如在相机应用内执行捕捉操作，而在其他应用内执行其他功能。
4. 通过硬件按钮的组合按压或长按触发高级设置功能，例如调整相机参数或切换用户界面布局。
5. 采用合成景深效果作为媒体捕捉的附加功能，用户可通过特定按钮选择是否应用该效果，提升拍摄创意性。
6. 通过优化硬件按钮与软件界面的交互逻辑，减少用户操作步骤，提高操作效率并降低设备能耗。
7. 该技术特别适用于智能相机设备或具有相机功能的便携式设备，能够在复杂操作环境中提供更直观和可靠的用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619880)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270547)**
<br/><br/>

---


<br/>

### 3. 用于生成媒体内容集合的用户界面

**Title (EN)**: USER INTERFACES FOR GENERATING COLLECTIONS OF MEDIA CONTENT  
**Pub. No.**: US20260270530

**Applicant**: Apple Inc.  
**Inventor**: [Andrew J. LEUNG](https://patents.google.com/?inventor=Andrew+J.+LEUNG&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
在一些实施例中，电子设备根据本发明的某些实施例呈现媒体内容之间的过渡效果。在一些实施例中，电子设备根据某些实施例显示用于媒体内容的搜索用户界面。在一些实施例中，电子设备显示一个可选选项，该选项可选中以生成内容项的集合。在一些实施例中，电子设备使用机器学习和/或人工智能生成内容项的集合。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619861_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及电子设备呈现媒体播放器应用的用户界面，具体包括媒体内容过渡、搜索界面显示以及内容集合生成的技术。

**Background (发明背景)**:  
近年来，用户与电子设备的交互显著增加。这些设备包括计算机、平板电脑、电视、多媒体设备和移动设备等。用户通常希望高效地与媒体播放器应用交互，但现有技术中，用户在切换媒体内容、搜索内容以及生成内容集合时需要较多时间和操作步骤。本发明旨在提供更高效的用户界面交互方式，以减少用户操作时间和输入次数。

**Summary (发明总览)**:  
本发明通过优化用户界面显示、媒体内容过渡、搜索界面呈现以及内容集合生成的方式，提升用户与电子设备的交互效率。具体实现包括：
1. 提供更直观的用户界面视图显示方式，减少用户查看信息所需的时间和操作。
2. 优化媒体内容之间的过渡效果，使用户能够更快速地选择和切换内容。
3. 改进搜索用户界面的呈现方式，结合机器学习和人工智能技术，帮助用户更高效地搜索和生成内容集合。
4. 通过智能化的内容集合生成和浏览机制，帮助用户快速发现新内容。

**Key Innovation (核心创新)**:  
1. 通过优化用户界面视图的显示方式，减少用户查看媒体内容信息所需的时间和操作步骤，例如采用更直观的布局和导航设计。
2. 实现更流畅的媒体内容过渡效果，使用户能够快速选择和切换内容，可能采用手势识别或智能预测技术。
3. 改进搜索用户界面的呈现方式，结合机器学习和人工智能技术，提供更精准的搜索结果和内容推荐。
4. 利用人工智能算法自动生成内容集合，根据用户偏好、历史行为和内容特征进行个性化推荐。
5. 提供内容集合的智能浏览功能，使用户能够快速浏览和筛选集合中的内容，例如通过缩略图预览或快速滑动。
6. 集成多种输入方式，包括触摸、语音和手势，以适应不同用户的使用习惯和场景需求。
7. 本专利可应用于智能电视、移动设备或多媒体播放器等产品，为用户提供更智能、更便捷的媒体内容管理体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619861)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270530)**
<br/><br/>

---


<br/>

### 4. 对象建议的选择

**Title (EN)**: SELECTION OF OBJECTS FOR SUGGESTIONS  
**Pub. No.**: US20260267486

**Applicant**: Apple Inc.  
**Inventor**: [Guilherme KLINK](https://patents.google.com/?inventor=Guilherme+KLINK&assignee=Apple&country=US&num=100&sort=new), [Peter BURGNER](https://patents.google.com/?inventor=Peter+BURGNER&assignee=Apple&country=US&num=100&sort=new), [Paul EWERS](https://patents.google.com/?inventor=Paul+EWERS&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
一种示例方法包括：在与一个或多个传感器设备通信的计算机系统中：通过一个或多个传感器设备检测三维（3D）场景中的第一对象；并且响应于通过一个或多个传感器设备检测到3D场景中的第一对象：根据一组一个或多个标准是否满足来确定，其中当第一对象的属性位于与3D场景相关联的预定义区域内时，满足第一标准，提供基于第一对象确定的建议；如果一组一个或多个标准不满足，则不提供基于第一对象的建议。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616524_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及三维场景中对象建议的提供技术，具体涉及基于传感器检测和预定义区域属性判断来选择性地提供对象建议。

**Background (发明背景)**:  
近年来，用于交互和/或提供三维场景的计算机系统发展迅速。然而，现有系统在提供对象建议时往往缺乏精确性，可能导致用户界面混乱或用户被不相关的建议所干扰。本发明旨在解决这一问题，通过基于对象属性是否位于预定义区域内来选择性地提供建议，从而提高建议的准确性和用户界面的整洁度。

**Summary (发明总览)**:  
本发明提出了一种基于对象属性判断来选择性地提供建议的方法。当检测到三维场景中的对象时，系统会判断该对象的属性是否位于预定义区域内。如果满足条件，则提供基于该对象的建议；否则，不提供建议。该方法通过减少不必要建议的提供，使用户界面更加整洁，并提高用户选择对象的效率和准确性。

**Key Innovation (核心创新)**:  
1. 通过传感器设备检测三维场景中的对象，并基于对象的属性判断是否位于预定义区域内。
2. 根据预定义区域内的属性判断结果，选择性地提供对象建议，避免不相关建议的干扰。
3. 使用一组标准来评估对象属性，包括但不限于位置、尺寸、形状等属性，确保建议的准确性。
4. 通过减少不必要的建议提供，优化用户界面，提升用户体验并降低用户操作复杂度。
5. 适用于多种计算机系统，包括台式机、便携式设备、个人电子设备（如智能手表或头戴式设备）等。
6. 可与触控板、摄像头、显示生成组件（如头戴式显示器或触摸屏）等硬件结合使用，增强交互能力。
7. 该技术可应用于增强现实、虚拟现实以及日常用户界面中，为用户提供更智能、更精准的对象建议，提升整体交互效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616524)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267486)**
<br/><br/>

---


<br/>

### 5. 用于解锁计算机系统的设备、方法和图形用户界面

**Title (EN)**: DEVICES, METHODS, AND GRAPHICAL USER INTERFACES FOR UNLOCKING A COMPUTER SYSTEM  
**Pub. No.**: US20260267945

**Applicant**: Apple Inc.  
**Inventor**: [Walden J. DAVIS](https://patents.google.com/?inventor=Walden+J.+DAVIS&assignee=Apple&country=US&num=100&sort=new), [Evgenii KRIVORUCHKO](https://patents.google.com/?inventor=Evgenii+KRIVORUCHKO&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
当用户使用一个具有注意力感知功能的设备，并且当一个配套设备处于锁定状态时，检测到该配套设备上的输入。根据检测到的输入以及确定满足一组解锁条件，包括确定用户的注意力已指向配套设备（由注意力感知设备检测），则使配套设备解锁。如果未满足解锁条件，则注意力感知设备不会使配套设备解锁。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617019_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算机系统技术，具体涉及通过注意力感知设备实现设备解锁的方法。

**Background (发明背景)**:  
近年来，增强现实计算机系统发展迅速，但现有的解锁方法存在操作繁琐、效率低下的问题。例如，在使用虚拟现实或混合现实设备时，需要额外的解锁操作或复杂的身份验证方式（如面部识别），这增加了用户负担，降低了使用体验。此外，这些方法耗时较长，对电池供电设备来说能耗较高。

**Summary (发明总览)**:  
本发明提出了一种基于用户注意力感知的设备解锁方法。当用户使用主设备（如虚拟现实设备）时，如果检测到配套设备上的输入，系统会判断用户是否将注意力集中在配套设备上。只有在满足解锁条件（包括用户注意力指向配套设备）时，才会解锁配套设备。这种方法简化了解锁流程，减少了用户操作步骤，提升了人机交互效率，尤其适用于电池供电设备。

**Key Innovation (核心创新)**:  
1. 通过主设备的注意力感知功能检测用户是否将注意力集中在配套设备上，从而决定是否解锁。
2. 在用户使用主设备时，检测配套设备上的输入并实时判断解锁条件是否满足。
3. 利用主设备与配套设备之间的通信机制，实现基于用户注意力的智能解锁。
4. 减少解锁过程中的用户操作步骤，提升人机交互的流畅性和效率。
5. 特别适用于虚拟现实和混合现实设备等场景，避免了传统解锁方式对沉浸式体验的干扰。
6. 通过优化解锁流程，降低了电池供电设备的能耗，延长了设备使用时间。
7. 该方法可应用于智能手表、头戴式显示器等设备，为用户提供更自然、更高效的安全解锁体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617019)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267945)**
<br/><br/>

---


<br/>

### 6. 生物特征认证的实现方法

**Title (EN)**: IMPLEMENTATION OF BIOMETRIC AUTHENTICATION  
**Pub. No.**: US20260267952

**Applicant**: Apple Inc.  
**Inventor**: [Grant R. PAUL](https://patents.google.com/?inventor=Grant+R.+PAUL&assignee=Apple&country=US&num=100&sort=new), [Kyle C. BROGLE](https://patents.google.com/?inventor=Kyle+C.+BROGLE&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本公开涉及认证的方法和用户界面，包括根据某些实施例使用外部设备在计算机系统中提供和控制认证。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617027_1.jpg)

**Technical Field (技术领域)**:  
生物特征认证技术领域，具体涉及生物特征注册和认证失败时的替代认证方法。

**Background (发明背景)**:  
生物特征认证（如面部、虹膜或指纹）是一种便捷、高效且安全的方法，用于电子设备用户的身份验证。然而，当用户因生物特征部分被遮挡（如戴口罩）而无法通过认证时，现有技术通常要求用户使用其他繁琐的认证方式。这不仅浪费时间，还增加了设备能耗，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种更快速、更高效的生物特征认证方法，通过结合外部设备的状态（如解锁状态和与用户的物理关联）来增强认证过程。当生物特征认证失败时，系统会检查外部设备的状态，如果满足特定条件，则允许执行安全操作。这种方法不仅提高了认证的灵活性，还减少了用户操作负担，并延长了电池供电设备的使用时间。

**Key Innovation (核心创新)**:  
1. 结合外部设备状态（如解锁状态和与用户的物理关联）作为生物特征认证的补充条件。
2. 在生物特征数据不符合认证标准时，通过检测外部设备的状态来决定是否执行安全操作。
3. 外部设备的状态检测包括设备是否处于解锁状态以及是否与用户物理关联，确保认证的安全性。
4. 提供了一种在生物特征认证失败时无需用户重复输入或使用其他繁琐认证方式的方法。
5. 通过减少不必要的用户操作和设备能耗，提升了电池供电设备的续航能力和用户体验。
6. 该方法可应用于智能手机、智能手表等便携式设备，尤其在用户面部或指纹被遮挡时提供可靠的认证替代方案。
7. 通过提供更灵活的认证方式，降低了用户禁用生物特征认证的可能性，从而提高了设备整体安全性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617027)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267952)**
<br/><br/>

---


<br/>

### 7. 用于捕捉图像序列的虚拟指示器

**Title (EN)**: VIRTUAL INDICATOR FOR CAPTURING A SEQUENCE OF IMAGES  
**Pub. No.**: US20260268617

**Applicant**: Apple Inc.  
**Inventor**: [Bradley W. Peebler](https://patents.google.com/?inventor=Bradley+W.+Peebler&assignee=Apple&country=US&num=100&sort=new), [Zachary Z. Becker](https://patents.google.com/?inventor=Zachary+Z.+Becker&assignee=Apple&country=US&num=100&sort=new), [Qiujie Wu](https://patents.google.com/?inventor=Qiujie+Wu&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
一种第一设备包括显示器、输入设备、非易失性存储器以及与显示器、输入设备和非易失性存储器耦合的一个或多个处理器。在一些实施例中，方法包括通过输入设备检测对应于生成路径的请求的输入，以便在捕捉图像序列时由实体跟随。基于请求生成实体的路径。在一些实施例中，方法包括触发与实体相关联的第二设备，以在物理环境的透视视图上叠加指示路径的虚拟指示器。虚拟指示器在捕捉图像序列时引导实体沿着路径移动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617758_1.jpg)

**Technical Field (技术领域)**:  
增强现实技术领域，具体涉及通过虚拟指示器引导用户进行图像捕捉。

**Background (发明背景)**:  
现有设备通常配备摄像头用于捕捉图像，并提供图形用户界面来控制拍摄参数。然而，这些界面难以支持某些电影级拍摄效果，例如环绕拍摄。由于缺乏明确的路径引导，用户难以保持恒定的拍摄轨迹，导致拍摄结果不理想。本发明旨在解决这一问题，通过提供虚拟指示器来引导用户沿预定路径移动，从而实现更专业的拍摄效果。

**Summary (发明总览)**:  
本发明提出了一种通过虚拟指示器引导用户进行图像捕捉的方法。设备首先获取用户捕捉图像序列的请求，并确定所需路径的形状和尺寸。随后，设备在物理环境的透视视图上叠加虚拟指示器，以指示用户应沿其移动的路径。虚拟指示器不仅引导用户移动，还能根据用户偏离路径或移动速度不均的情况调整图像处理，以补偿这些偏差，从而确保最终图像序列的质量。

**Key Innovation (核心创新)**:  
1. 通过环境传感器捕捉用户行走路径数据，并生成虚拟指示器来引导用户沿预定轨迹移动。
2. 允许用户自定义路径形状和尺寸，例如圆形路径，并通过设备传感器记录用户定义的路径。
3. 在用户移动过程中，实时显示目标速度指示，例如通过屏幕文本或虚拟路径颜色变化来提示用户调整速度。
4. 采用图像扭曲技术补偿用户偏离路径或移动速度不均的情况，确保图像序列的连贯性和一致性。
5. 利用新颖视图合成技术，根据已捕捉的图像生成缺失视角的视图，以弥补用户未捕捉到某些路径段的问题。
6. 设备支持用户选择已捕捉的图像并重新定义路径，从而灵活调整拍摄结果。
7. 本发明可应用于360度视频拍摄、环绕物体拍摄等场景，为用户提供专业级的拍摄指导，提升最终作品质量。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617758)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268617)**
<br/><br/>

---


<br/>

### 8. 用于表示交互的用户界面和技术

**Title (EN)**: USER INTERFACES AND TECHNIQUES FOR REPRESENTING INTERACTIONS  
**Pub. No.**: US20260267400

**Applicant**: Apple Inc.  
**Inventor**: [Agatha Y. YU](https://patents.google.com/?inventor=Agatha+Y.+YU&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本公开涉及内容显示。一些技术用于根据某些实施例强调内容。其他技术用于根据某些实施例移除内容。其他技术用于根据某些实施例显示内容。还有一些技术用于根据某些实施例改变输出模式。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616431_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及用户界面显示和交互技术。

**Background (发明背景)**:  
电子设备通常需要管理内容，包括移除、添加和强调内容。现有的内容显示技术通常繁琐且效率低下，例如使用复杂的用户界面或需要多次按键操作，导致用户时间和设备能量浪费，这在电池供电设备中尤为重要。

**Summary (发明总览)**:  
本发明提供了一种更快速、更高效的内容显示方法和用户界面，通过优化用户交互流程，减少认知负担并提升人机交互效率。该方法通过检测软件代理的输入，动态调整用户界面的显示方式，包括强调和取消强调等操作，从而实现更流畅的用户体验并节省设备能耗。

**Key Innovation (核心创新)**:  
1. 通过检测软件代理的输入，动态调整用户界面的显示方式，包括强调和取消强调等操作，提升交互效率。
2. 采用多层次的用户界面元素强调机制，例如不同的强调样式和顺序，以增强用户对重要信息的感知。
3. 在不依赖额外用户输入的情况下，自动调整用户界面的显示状态，例如通过时间延迟或预设规则实现动态变化。
4. 结合输入设备和显示组件，实现用户界面的无缝过渡和响应，减少用户等待时间。
5. 通过优化用户界面的显示和隐藏方式，例如使用移动组件实现界面元素的物理移动，提升交互的自然性和直观性。
6. 适用于电池供电设备，通过减少不必要的用户界面操作和动态调整显示策略，延长设备续航时间。
7. 可应用于智能设备、便携式电子产品和车载系统等场景，提供更高效、更节能的用户交互解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616431)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267400)**
<br/><br/>

---


<br/>

### 9. 基于保存内容提供建议

**Title (EN)**: PROVIDING SUGGESTIONS BASED ON SAVED CONTENT  
**Pub. No.**: US20260267487

**Applicant**: Apple Inc.  
**Inventor**: [Paul EWERS](https://patents.google.com/?inventor=Paul+EWERS&assignee=Apple&country=US&num=100&sort=new), [Peter BURGNER](https://patents.google.com/?inventor=Peter+BURGNER&assignee=Apple&country=US&num=100&sort=new), [Christopher D. FU](https://patents.google.com/?inventor=Christopher+D.+FU&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明公开了基于内容（如三维场景的实时视图和保存视图）确定并呈现建议操作的技术。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616525_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及三维场景视图处理领域，具体涉及基于三维场景视图提供建议操作的技术。

**Background (发明背景)**:  
近年来，计算机系统与三维场景交互或提供三维场景的技术发展迅速。现有技术中，三维场景包括物理场景和扩展现实场景。然而，现有系统缺乏根据用户保存的内容和场景上下文自动提供相关操作建议的能力，导致用户操作效率低下。

**Summary (发明总览)**:  
本发明提出了一种基于三维场景视图提供建议操作的方法。当用户请求保存三维场景中的对象时，系统会捕获场景视图并通过图像识别和上下文信息分析确定相关建议操作。这些建议操作通过不同的应用程序呈现，用户可以通过选择图形元素触发相应操作。该方法通过减少用户输入和提供精准建议，提升了用户界面的效率和准确性，同时节省设备能耗并延长电池寿命。

**Key Innovation (核心创新)**:  
1. 通过图像传感器捕获用户保存的三维场景视图，并基于图像识别技术分析场景内容。
2. 结合场景视图之外的上下文信息（如用户历史行为、设备状态等）确定相关建议操作。
3. 在不同应用程序之间建立交互机制，使用户能够通过一个应用程序的界面触发另一个应用程序的操作。
4. 设计可选择的图形元素，使用户能够直观地选择和执行建议操作。
5. 适用于多种计算机系统，包括台式机、便携式设备和个人电子设备（如智能手表和头戴式设备）。
6. 通过减少用户输入和简化操作流程，提升用户交互效率和设备使用效率。
7. 该技术可应用于增强现实、虚拟现实和智能助手等领域，为用户提供个性化的操作建议和更智能的场景交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616525)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267487)**
<br/><br/>

---


<br/>

### 10. 电子设备的表盘

**Title (EN)**: CLOCK FACES FOR AN ELECTRONIC DEVICE  
**Pub. No.**: US20260267462

**Applicant**: Apple Inc.  
**Inventor**: [Kevin Will CHEN](https://patents.google.com/?inventor=Kevin+Will+CHEN&assignee=Apple&country=US&num=100&sort=new), [Alan C. DYE](https://patents.google.com/?inventor=Alan+C.+DYE&assignee=Apple&country=US&num=100&sort=new), [David A. SCHIMON](https://patents.google.com/?inventor=David+A.+SCHIMON&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明涉及一种设备接收显示表盘的请求，该表盘包含第一背景段和与第一背景段外观不同的第二背景段。设备在接收到请求后显示该表盘。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616498_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及电子设备的表盘显示与交互。

**Background (发明背景)**:  
便携式多功能设备被广泛用于包括计时在内的多种操作，用户希望设备不仅能显示当前时间，还能提供其他与情境相关的信息。然而，现有技术在呈现和交互表盘时通常繁琐且效率低下，例如需要多次按键或复杂的用户界面操作，这不仅浪费时间，还增加了设备的能耗，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种更快速、高效的电子设备表盘显示与交互方法及界面。通过优化表盘元素的显示逻辑，例如根据需要动态调整表盘元素的位置和大小，以及支持多语言显示和快速切换，提升了用户的使用体验并降低了认知负担，同时节省了设备能耗。

**Key Innovation (核心创新)**:  
1. 通过接收显示表盘的请求，设备能够动态调整表盘上模拟表盘元素的位置和大小，例如根据是否显示特定元素来改变其他元素的位置或尺寸。
2. 支持表盘元素的动态显示与隐藏，通过判断是否需要在特定位置显示某个元素来调整表盘布局，从而优化显示效果。
3. 实现了表盘的多语言支持，用户可以通过输入序列切换表盘上时间显示的语言，而不影响其他图形元素的语言设置。
4. 采用分区域显示技术，将时间指示和附加信息（如图形元素）分别以不同语言呈现，增强了国际化适用性。
5. 通过优化表盘显示逻辑，减少了用户操作步骤和设备资源消耗，尤其在电池供电设备上延长了续航时间。
6. 该技术可应用于智能手表、手机等便携设备，为用户提供更直观、高效的计时和信息显示方式。
7. 通过减少复杂界面操作和动态调整显示内容，提升了用户的使用体验，并使表盘设计更加灵活和个性化。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616498)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267462)**
<br/><br/>

---


<br/>

### 11. 上下文音量调整

**Title (EN)**: CONTEXTUAL VOLUME ADJUSTMENT  
**Pub. No.**: US20260267594

**Applicant**: Apple Inc.  
**Inventor**: [Jules K. FENNIS](https://patents.google.com/?inventor=Jules+K.+FENNIS&assignee=Apple&country=US&num=100&sort=new), [Brian T. GLEESON](https://patents.google.com/?inventor=Brian+T.+GLEESON&assignee=Apple&country=US&num=100&sort=new), [Miao HE](https://patents.google.com/?inventor=Miao+HE&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
计算机系统检测事件的发生，并在检测到事件发生时输出与该事件对应的音频输出。根据一组标准是否满足以及环境声音水平处于第一检测水平，计算机系统以第一输出水平输出第一音频输出。根据一组标准是否满足以及环境声音水平处于与第一检测水平不同的第二检测水平，计算机系统以与第一输出水平不同的第二输出水平输出第一音频输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616639_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面技术，具体涉及基于上下文调整音频输出水平的方法。

**Background (发明背景)**:  
智能手机和智能手表等电子设备在接收到电话或消息等事件时，会输出音频通知。现有的基于上下文调整音频输出水平的技术通常繁琐且效率低下，例如需要复杂的用户界面操作或多次按键。这些方法耗时且浪费用户时间和设备能量，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种基于上下文快速高效调整音频输出水平的方法和接口。通过检测事件发生并根据环境声音水平调整输出音量，本发明减少了用户认知负担，提高了人机交互效率，并节省了设备能耗。该方法可替代或补充现有的音量调整技术。

**Key Innovation (核心创新)**:  
1. 通过检测事件发生并根据环境声音水平动态调整音频输出水平，实现更智能的音量控制。
2. 采用多级检测机制，根据不同的环境声音水平自动选择合适的输出音量，确保在不同环境下音频通知的可听性。
3. 引入一组标准作为判断依据，确保音量调整的准确性和一致性，减少误操作。
4. 通过减少用户手动调整音量的需求，降低了用户操作复杂度，提升了使用体验。
5. 优化了电池供电设备的能耗管理，通过减少不必要的音量调整操作延长了电池续航时间。
6. 该技术可应用于智能手机、智能手表等便携式设备，尤其适用于嘈杂或安静环境下的音频通知场景。
7. 提供了更人性化的音频交互方式，使用户在不同环境下都能获得合适的听觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616639)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267594)**
<br/><br/>

---


<br/>

### 12. 公用电子设备上的隐私保护命令处理

**Title (EN)**: PRIVACY-PRESERVING COMMAND PROCESSING ON COMMUNAL ELECTRONIC DEVICES  
**Pub. No.**: US20260270248

**Applicant**: Apple Inc.  
**Inventor**: [Bob BRADLEY](https://patents.google.com/?inventor=Bob+BRADLEY&assignee=Apple&country=US&num=100&sort=new), [Marc J. KROCHMAL](https://patents.google.com/?inventor=Marc+J.+KROCHMAL&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明描述了在多个用户使用的公用电子设备上处理命令同时保护用户隐私的技术。通过自然语言处理分析接收到的命令，以确定是否需要访问特定用户的个人数据。当需要访问个人数据时，公用电子设备会识别与用户关联的个人电子设备。在某些实现中，公用电子设备会确定对个人数据的程序化访问是否受限，并向用户呈现授权请求。在某些实现中，个人电子设备处理命令的至少一部分并返回个人数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486619552_1.jpg)

**Technical Field (技术领域)**:  
智能家居设备领域，具体涉及公用设备与个人设备之间的隐私保护数据处理和通信机制。

**Background (发明背景)**:  
智能设备上的智能助手系统能够执行多种用户请求，但现有技术中，公用设备难以在保护用户隐私的同时提供个性化服务。公用设备通常避免存储个人数据，这限制了其在需要访问个人数据的功能上的应用。此外，现有技术缺乏有效机制来防止未经授权的用户查询其他用户的个人数据。

**Summary (发明总览)**:  
本发明提出了一种机制，使公用电子设备能够将涉及个人用户数据的虚拟助手请求转发或委托给个人用户设备进行处理。通过建立加密数据通道，公用设备与个人设备之间可以进行安全通信。公用设备在接收到需要访问个人数据的请求时，会通过安全的数据链路请求个人设备处理相关数据，从而在保护隐私的同时实现个性化功能。

**Key Innovation (核心创新)**:  
1. 通过自然语言处理分析命令，确定是否需要访问个人数据，从而实现智能命令处理的隐私保护。
2. 建立公用设备与个人设备之间的加密数据通道，确保数据传输的安全性，防止未经授权的访问。
3. 采用点对点数据连接和信任关系验证机制，确保公用设备与个人设备之间的通信安全可靠。
4. 引入伴侣设备概念，个人设备作为伴侣设备与公用设备配对，提供对个人数据的访问支持。
5. 实现伴侣链路服务，支持家庭网络内公用设备与个人设备之间的低延迟、持久性消息传输。
6. 允许公用设备将个人请求重定向到关联的个人设备，从而在保护隐私的同时实现虚拟助手的完整功能。
7. 应用于智能音箱等公用设备场景，能够在不存储个人数据的情况下提供个性化服务，提升用户隐私保护水平。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486619552)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260270248)**
<br/><br/>

---


<br/>

### 13. 用于监控访客的用户界面和技术

**Title (EN)**: USER INTERFACES AND TECHNIQUES FOR MONITORING GUESTS  
**Pub. No.**: US20260268677

**Applicant**: Apple Inc.  
**Inventor**: [Vincenzo O. GIULIANI](https://patents.google.com/?inventor=Vincenzo+O.+GIULIANI&assignee=Apple&country=US&num=100&sort=new), [Joshua D. DEITEL](https://patents.google.com/?inventor=Joshua+D.+DEITEL&assignee=Apple&country=US&num=100&sort=new), [Mischa K. MCLACHLAN](https://patents.google.com/?inventor=Mischa+K.+MCLACHLAN&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
一些技术用于根据某些实施例显示用于联系访客的用户界面元素。其他技术用于根据某些实施例显示访客活动。还有一些技术用于根据某些实施例显示与访客位置对应的摄像头画面。另一些技术用于根据某些实施例基于上下文显示媒体。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617824_1.jpg)

**Technical Field (技术领域)**:  
智能家居与监控系统领域，具体涉及访客监控和用户界面交互技术。

**Background (发明背景)**:  
电子设备通常能够捕捉图像并检测运动，但现有技术存在效率低下和功能单一的问题。
传统的访客监控系统通常只能提供基本的图像显示和运动通知，缺乏针对不同访客的个性化交互功能。
现有系统难以根据访客身份或活动提供定制化的操作界面，影响用户体验。

**Summary (发明总览)**:  
本发明提供了一种智能访客监控系统，通过识别不同访客并提供个性化的用户界面元素来增强交互体验。
系统能够根据访客身份显示不同的联系界面，并在检测到访客活动时提供相应的活动展示界面。
该系统还支持基于摄像头画面和上下文信息的媒体展示，提升了监控的智能化和用户友好性。
相较于传统方法，本发明实现了更高效、更智能的访客监控和交互。

**Key Innovation (核心创新)**:  
1. 通过识别不同访客身份，系统能够分别显示个性化的联系界面，例如针对家人、朋友或陌生人提供不同的交互选项。
2. 系统集成了活动监控功能，能够在检测到访客活动时，通过用户界面元素展示访客的具体活动内容，如运动轨迹或行为模式。
3. 实现了基于摄像头画面的实时画面显示功能，用户可以直观地查看访客当前位置和周边环境。
4. 支持基于上下文信息的媒体展示，例如根据时间、位置或访客历史记录自动调整显示内容，提高交互的智能性。
5. 采用模块化设计，用户可以通过输入设备与界面元素进行交互，例如点击查看访客活动详情，实现更灵活的交互方式。
6. 系统能够同时处理多个访客的检测和交互请求，并分别显示对应的用户界面元素，确保多任务处理的效率。
7. 本发明可应用于智能家居安防、办公场所访客管理等多种场景，为用户提供更安全、更便捷的访客监控体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617824)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268677)**
<br/><br/>

---


<br/>

### 14. 计算机机箱

**Title (EN)**: COMPUTER HOUSING  
**Pub. No.**: US20260267380

**Applicant**: Apple Inc.  
**Inventor**: [Eugene A. Whang](https://patents.google.com/?inventor=Eugene+A.+Whang&assignee=Apple&country=US&num=100&sort=new), [Christopher J. Stringer](https://patents.google.com/?inventor=Christopher+J.+Stringer&assignee=Apple&country=US&num=100&sort=new), [Brett W. Degner](https://patents.google.com/?inventor=Brett+W.+Degner&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明描述了一种台式计算系统，该系统至少包含一个中央核心，该核心被一个外壳包围，外壳的形状定义了中央核心所在的体积。外壳包括第一开口和第二开口，第一开口在轴向上与第二开口错开。第一开口的大小和形状根据用于冷却内部组件的空气流量而定，第二开口由一个唇边界定，该唇边以这样的方式与空气流的一部分相互作用，使得至少部分从内部组件传递到空气流的热量被传递到外壳。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486616408_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及紧凑型计算系统领域，具体涉及用于紧凑型计算系统的外壳结构设计及热管理技术。

**Background (发明背景)**:  
紧凑型计算系统的外观设计对用户体验至关重要，同时其组装耐用性也影响系统的使用寿命和价值。现有的紧凑型计算系统外壳设计面临轻量化与强度之间的矛盾：轻量外壳易弯曲变形，而坚固的外壳则较厚重。此外，外壳还需兼顾散热性能和美观性，这对材料选择和结构设计提出了挑战。

**Summary (发明总览)**:  
本发明提出了一种轻量化且耐用的紧凑型计算系统设计方案。通过采用圆柱形外壳结构，优化了内部空间利用率，并实现了高组件封装密度。系统采用轴向气流散热方案，通过调节风扇转速来适应不同的散热需求。外壳采用铝合金材质，并通过阳极氧化处理增强散热性能和电磁屏蔽效果。本发明相较于传统设计，在散热效率、空间利用率和耐用性方面均有显著提升。

**Key Innovation (核心创新)**:  
1. 采用圆柱形外壳设计，最大化内部体积与外壳体积比，实现高组件封装密度。
2. 外壳采用铝合金材质，并通过阳极氧化处理形成氧化铝层，既增强散热性能又提供电磁屏蔽。
3. 设计轴向气流散热系统，通过调节风扇转速（15-40 CFM）适应不同散热需求，在高负载时提供高效散热。
4. 组件布局采用轴向排列方式，增大与气流的接触面积，提升散热效率。
5. 外壳顶部设计有唇边，既用于引导气流，又便于用户搬运设备。
6. 系统可与其他紧凑型计算设备组合，形成多计算机系统，适用于服务器或网络计算场景。
7. 该设计特别适用于需要高计算密度和紧凑空间的应用场景，如数据中心或小型办公环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486616408)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260267380)**
<br/><br/>

---


<br/>

### 15. 具有动态天线切换功能的电子设备

**Title (EN)**: Electronic Devices with Dynamic Antenna Switching  
**Pub. No.**: US20260269468

**Applicant**: Apple Inc.  
**Inventor**: [Yuancheng Xu](https://patents.google.com/?inventor=Yuancheng+Xu&assignee=Apple&country=US&num=100&sort=new), [Thomas E. Biedka](https://patents.google.com/?inventor=Thomas+E.+Biedka&assignee=Apple&country=US&num=100&sort=new), [Jingni Zhong](https://patents.google.com/?inventor=Jingni+Zhong&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明提供了一种电子设备，其包含由第一路径供电的第一天线和由第二路径供电的第二天线。第一路径上设有第一耦合器，第二路径上设有第二耦合器，反馈路径将耦合器与接收器连接。第二路径上设有低通滤波器。第一天线用于传输低频段信号，部分信号可能耦合到第二天线。第二耦合器将耦合信号传递至接收器。控制电路生成表征第一天线信号耦合到第二天线的散射参数值，该参数值用于确定何时将第一天线切换出使用状态并将第二天线切换入使用状态。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486618694_1.jpg)

**Technical Field (技术领域)**:  
无线通信技术领域，具体涉及天线切换和信号耦合检测技术。

**Background (发明背景)**:  
随着无线通信设备的小型化趋势，天线设计面临空间限制和性能挑战。
现有技术难以在紧凑结构中实现多频段覆盖，同时避免天线间干扰。
此外，设备在不同工作条件下可能发生天线失谐，影响通信质量。
本发明旨在解决天线间信号耦合对通信性能的影响，并实现智能天线切换。

**Summary (发明总览)**:  
本发明提出了一种具有动态天线切换功能的电子设备，通过信号耦合检测机制来优化天线使用。
该设备包含两个天线，分别由不同的射频路径供电，并配备耦合器和反馈接收器来监测信号耦合情况。
通过分析散射参数值，设备可以智能地切换天线以适应不同的通信需求。
这种设计提高了设备在多频段工作时的稳定性和通信质量。

**Key Innovation (核心创新)**:  
1. 设计了双天线结构，并通过射频路径上的耦合器实时监测天线间信号耦合情况。
2. 在射频路径上集成了低通滤波器，有效减少高频干扰，提高信号检测精度。
3. 利用散射参数值（如复数传输系数）量化天线间耦合程度，为天线切换提供精确依据。
4. 通过处理器根据散射参数值动态调整天线使用状态，实现智能切换，提升通信稳定性。
5. 在射频路径上使用双刀双掷（DPDT）开关，实现天线与射频收发电路的灵活连接。
6. 该设计可应用于智能手机、平板电脑等便携式设备，在多频段通信场景下提供更可靠的天线性能。
7. 通过动态调整天线使用，该技术能够减少信号损耗和干扰，提升设备在复杂环境下的通信质量。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486618694)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260269468)**
<br/><br/>

---


<br/>

### 16. 具有扩展活动区域的电子设备显示屏

**Title (EN)**: Electronic Device Display With Extended Active Area  
**Pub. No.**: US20260268876

**Applicant**: Apple Inc.  
**Inventor**: [Mikael M. Silvanto](https://patents.google.com/?inventor=Mikael+M.+Silvanto&assignee=Apple&country=US&num=100&sort=new), [Dinesh C. Mathew](https://patents.google.com/?inventor=Dinesh+C.+Mathew&assignee=Apple&country=US&num=100&sort=new), [Victor H. Yin](https://patents.google.com/?inventor=Victor+H.+Yin&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本发明提供了一种电子设备，其配备有显示屏。该显示屏可由液晶显示像素、有机发光二极管像素或其他类型的像素构成。显示屏具有一个活动区域，该区域被至少一个边缘的非活动区域所围绕。活动区域包含像素并用于显示图像，而非活动区域不包含像素也不显示图像。非活动区域可涂覆一层黑色墨水或其他遮蔽材料，以遮挡内部组件。活动区域可具有一个开口，其中包含非活动区域的孤立部分，或者包含一个凹槽，非活动区域的一部分可突出于其中。诸如扬声器、摄像头、发光二极管、光传感器或其他电子设备等电气组件可安装在突出于凹槽或位于活动区域开口处的非活动区域部分。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486618042_1.jpg)

**Technical Field (技术领域)**:  
电子设备技术领域，具体涉及显示屏设计及组件布局。

**Background (发明背景)**:  
电子设备通常配备显示屏，例如手机、平板电脑和笔记本电脑。显示屏的活动区域包含用于显示图像的像素，而非活动区域则容纳显示驱动电路、按钮、摄像头等不发光组件。如果设计不当，显示屏边框可能会比预期更大，例如当摄像头或按钮位于显示屏边缘时，边框需要扩大以容纳这些组件，这会限制可用于向用户呈现视觉信息的显示区域。

**Summary (发明总览)**:  
本发明提出了一种改进的电子设备显示屏设计，通过在活动区域中设置开口或凹槽，将非活动区域的一部分嵌入其中，从而实现更紧凑的边框设计。该设计允许将电气组件如摄像头、传感器等集成到非活动区域中，同时保持显示屏的视觉连续性。通过这种布局，显示屏的边框尺寸得以减小，从而增加了活动显示区域的比例，提升了用户体验。

**Key Innovation (核心创新)**:  
1. 在显示屏活动区域中设置开口或凹槽，将非活动区域的一部分嵌入其中，实现更紧凑的边框设计。
2. 非活动区域采用黑色墨水或其他遮蔽材料涂覆，以遮挡内部组件，确保视觉上的统一性和美观性。
3. 将电气组件如摄像头、传感器、按钮等集成到非活动区域中，避免占用活动显示区域的空间。
4. 在非活动区域中设置延展区，例如细长的矩形区域，用于显示图标或其他信息，使显示屏外观更加连续和完整。
5. 通过在非活动区域中设置突出部分或岛形区域，为摄像头等组件提供独立的安装空间，同时减少对活动区域的影响。
6. 该设计适用于多种电子设备，包括手机、平板电脑和笔记本电脑，能够有效提升显示屏的视觉表现力和功能集成度。
7. 通过优化边框设计，本发明能够在不增加设备整体尺寸的情况下，扩大活动显示区域，为用户带来更好的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486618042)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268876)**
<br/><br/>

---


<br/>

### 17. 用于审查访客的用户界面和技术

**Title (EN)**: USER INTERFACES AND TECHNIQUES FOR REVIEWING GUESTS  
**Pub. No.**: US20260268757

**Applicant**: Apple Inc.  
**Inventor**: [Vincenzo O. GIULIANI](https://patents.google.com/?inventor=Vincenzo+O.+GIULIANI&assignee=Apple&country=US&num=100&sort=new), [Joshua D. DEITEL](https://patents.google.com/?inventor=Joshua+D.+DEITEL&assignee=Apple&country=US&num=100&sort=new), [Mischa K. MCLACHLAN](https://patents.google.com/?inventor=Mischa+K.+MCLACHLAN&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
本公开主要涉及显示主体指示的技术。一些技术用于根据认证显示访客的表示。另一些技术用于显示访问权限。还有一些技术用于在检测到主体时向设备发出警报。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617912_1.jpg)

**Technical Field (技术领域)**:  
智能家居安全领域，具体涉及访客审查和访问权限管理。

**Background (发明背景)**:  
随着智能家居设备的普及，家庭安全和管理变得更加复杂。现有的设备通常需要多个独立的应用程序来处理警报和配置安全权限，这带来了操作上的不便。因此，需要改进访客审查的技术。

**Summary (发明总览)**:  
本发明提供了一种更快速、高效和有效的访客审查方法。通过接收环境中的主体活动指示，系统在用户界面中显示主体的初始表示，并根据主体的认证状态动态更新显示内容。如果主体通过认证，则切换到不同的表示；如果未通过认证，则保持初始表示。此外，系统还支持显示访问权限并处理相关用户输入。

**Key Innovation (核心创新)**:  
1. 通过接收环境中的主体活动指示，系统能够实时检测并响应访客的出现。
2. 系统在用户界面中首先显示主体的初始表示，并根据主体的认证状态动态切换到不同的表示，从而提供直观的用户反馈。
3. 采用认证机制来确定访客身份，并根据认证结果调整显示内容，增强了系统的安全性和用户体验。
4. 支持在用户界面中显示访问权限，允许用户快速查看和管理访客的访问权限。
5. 通过与一个或多个输入设备和显示组件的交互，系统能够处理用户输入并实时更新显示内容。
6. 该技术可以集成到智能家居系统中，简化多设备管理流程，减少对多个独立应用程序的依赖。
7. 应用于家庭安全场景时，能够提供更高效、更安全的访客审查和访问权限管理，为用户提供更智能的家居体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617912)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268757)**
<br/><br/>

---


<br/>

### 18. 统一动画 API

**Title (EN)**: Unified Animation API  
**Pub. No.**: US20260268565

**Applicant**: Apple Inc.  
**Inventor**: [Naveen K. Vemuri](https://patents.google.com/?inventor=Naveen+K.+Vemuri&assignee=Apple&country=US&num=100&sort=new), [David A. Yen](https://patents.google.com/?inventor=David+A.+Yen&assignee=Apple&country=US&num=100&sort=new), [Joshua J. Taylor](https://patents.google.com/?inventor=Joshua+J.+Taylor&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
一种在包含显示屏、一个或多个处理器和非易失性存储器的设备上显示动画的方法。该方法包括执行二维动画系统进程、执行三维动画系统进程，以及执行包含定义动画的三维动画应用进程，该动画将实体二维层的目标属性从第一时间的第一个值改变为第二时间的第二个值。执行三维动画应用进程包括生成定义动画的二维动画定义，将二维动画定义提供给二维动画系统进程以生成二维显示数据，并将三维动画定义提供给三维动画系统进程以生成三维显示数据。该方法进一步包括基于二维显示数据和三维显示数据在显示屏上显示动画。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617698_1.jpg)

**Technical Field (技术领域)**:  
计算机图形学，动画技术，扩展现实（XR）系统

**Background (发明背景)**:  
现有的二维动画 API 主要用于组合、渲染和动画化二维层，例如图形用户界面（GUI）的用户界面元素。而三维动画 API 则用于模拟、渲染和动画化三维环境中的三维实体。然而，根据三维动画 API 动画化三维实体的二维层需要扩展三维动画 API 的功能，这增加了复杂性。本发明旨在解决在统一框架下同时处理二维和三维动画的问题。

**Summary (发明总览)**:  
本发明提出了一种统一动画 API，通过整合现有的二维动画 API 和三维动画 API，实现对二维层和三维实体的统一动画处理。该方法通过三维动画应用进程生成二维动画定义，并将其与三维动画定义结合，传递给相应的系统进程以生成显示数据。这种方法简化了动画开发流程，提高了系统效率，并支持在扩展现实（XR）环境中更灵活地处理二维和三维元素的动画效果。

**Key Innovation (核心创新)**:  
1. 提出了一个统一动画 API，将二维动画 API 和三维动画 API 整合在一起，实现了二维层和三维实体的统一动画处理。
2. 通过三维动画应用进程生成二维动画定义，并将其与三维动画定义结合，简化了动画开发流程。
3. 实现了对三维环境中二维层的动画支持，例如在虚拟环境中定义一个锁定的二维时钟或虚拟网页浏览器。
4. 提供了对二维层属性的验证机制，确保动画定义的目标属性类型正确，例如 float、color、vector 等。
5. 通过系统进程生成显示数据，并驱动显示屏显示动画，实现了高效的动画渲染。
6. 支持在扩展现实（XR）环境中灵活处理二维和三维元素的动画效果，例如在虚拟现实或增强现实场景中显示锁定的二维层。
7. 该技术可应用于头戴式设备、智能手机、平板电脑等设备，为用户提供更丰富的动画体验，特别是在 XR 环境中。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617698)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268565)**
<br/><br/>

---


<br/>

### 19. 认证图像

**Title (EN)**: Authenticated Images  
**Pub. No.**: US20260268025

**Applicant**: Apple Inc.  
**Inventor**: [Geoffrey Stahl](https://patents.google.com/?inventor=Geoffrey+Stahl&assignee=Apple&country=US&num=100&sort=new), [Michael J Rockwell](https://patents.google.com/?inventor=Michael+J+Rockwell&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 10.09.2026

**Abstract**:  
图像认证通过在操作系统（OS）层生成捕获图像的副本，该层对应用程序不可访问，并将副本通过操作系统层与安全存储库之间的安全通信通道转发至安全存储库。用户稍后可以在托管安全存储库的云网络中提供图像标识符，并获得捕获图像副本的可视化表示。如果提供的表示与共享的捕获图像版本匹配，则可以验证共享版本是原始捕获图像的真实表示。如果两者不同，则可以推断共享版本已被篡改或不是真实的。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486617106_1.jpg)

**Technical Field (技术领域)**:  
图像认证技术领域，具体涉及通过安全存储和通信机制防止图像被篡改或伪造。

**Background (发明背景)**:  
随着生成模型性能的提升，区分真实设备捕获的图像和人工智能生成的图像变得越来越困难。现有的认证方法依赖于附加的证书或元数据，但这些信息容易被伪造或篡改，导致认证的可靠性受到质疑。本发明旨在提供一种更安全的图像认证方法，防止图像被篡改或伪造。

**Summary (发明总览)**:  
本发明通过在操作系统层创建一个安全区域，将捕获的图像数据直接传输到该区域，并生成一个副本通过安全通信通道发送到远程安全存储库。存储库中的图像数据附有唯一标识符，用于后续认证。用户可以通过提供标识符和凭证来获取原始图像的表示，并与声称的图像进行比较，以验证其真实性。该方法通过将图像数据隔离存储并使用安全通信机制，防止图像被篡改或伪造。

**Key Innovation (核心创新)**:  
1. 在操作系统层实现一个安全区域（安全飞地），确保图像数据在传输到应用层之前被安全地复制和存储。
2. 通过安全通信通道将图像数据副本发送到远程安全存储库，防止数据在传输过程中被截获或篡改。
3. 在安全存储库中的图像数据附有唯一标识符，该标识符在图像数据被传输到应用层时也附加到副本上，确保数据的一致性和可追溯性。
4. 提供一种机制，允许用户通过提供标识符和凭证来获取原始图像的表示，并与声称的图像进行比较，以验证其真实性。
5. 通过将图像数据隔离存储在安全存储库中，防止图像被人工智能或图像编辑软件篡改或伪造。
6. 实施访问控制机制，确保只有授权用户才能访问和请求认证图像数据。
7. 本发明适用于需要高安全性的图像认证场景，如新闻报道、法医证据和关键事件的记录，能够有效防止图像被伪造或篡改。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486617106)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260268025)**
<br/><br/>

---


<br/>

### 20. 内容舒适显示

**Title (EN)**: Comfortable display of content  
**Pub. No.**: US12730508

**Applicant**: Apple Inc.  
**Inventor**: [Ioana Negoita](https://patents.google.com/?inventor=Ioana+Negoita&assignee=Apple&country=US&num=100&sort=new), [Allison W. Dryer](https://patents.google.com/?inventor=Allison+W.+Dryer&assignee=Apple&country=US&num=100&sort=new), [Trent A. Greene](https://patents.google.com/?inventor=Trent+A.+Greene&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
本发明涉及与显示器和输入设备通信电子设备中显示内容的方法和系统。该方法包括在计算机生成环境中相对于用户视点以第一表观深度显示内容。第一表观深度根据用户在第一时间段内的注视点深度测量值选择。该方法还包括在显示内容的同时，根据检测到的电子设备在物理环境中的运动来更新内容显示。更新内容显示包括在计算机生成环境中相对于用户视点以不同于第一表观深度的第二表观深度显示内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486364755_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及三维环境中的内容显示技术，具体涉及根据用户注视点和设备运动调整显示深度的技术。

**Background (发明背景)**:  
现有电子设备能够在用户视点相对位置显示具有表观深度的内容。然而，这些设备在处理用户运动或注视点变化时缺乏动态调整显示深度的能力。这可能导致视觉不适或内容显示与用户预期不一致的问题。本发明旨在解决这一问题，通过动态调整内容显示深度来提升用户体验。

**Summary (发明总览)**:  
本发明提出了一种在电子设备上动态显示内容的方法，通过检测用户注视点和设备运动来调整内容在三维环境中的显示深度。系统首先根据用户注视点的深度确定内容的初始显示深度。当检测到设备运动或用户注视点变化时，系统会相应地更新内容显示深度，以保持视觉舒适性和一致性。这种方法通过实时调整显示参数，提升了用户与三维内容交互的自然感和舒适度。

**Key Innovation (核心创新)**:  
1. 通过检测用户注视点的深度来确定内容的初始显示深度，从而提供更符合用户视觉习惯的显示效果。
2. 根据设备在物理环境中的运动来动态调整内容显示深度，以减少因设备移动导致的视觉不适。
3. 在检测到用户注视点位置变化时，实时更新内容显示深度，以保持内容与用户视觉焦点的对应关系。
4. 采用计算机生成环境中的深度调整机制，使得内容在不同深度层次间的过渡更加自然和流畅。
5. 通过满足特定运动和注视点变化条件来触发显示更新，确保调整过程的准确性和用户意图的匹配性。
6. 该技术可应用于虚拟现实、增强现实等场景，为用户提供更沉浸和舒适的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486364755)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12730508)**
<br/><br/>

---


<br/>

### 21. 具有色道间全内反射带的波导显示器

**Title (EN)**: Waveguide display with total internal reflection band between color channels  
**Pub. No.**: US12730266

**Applicant**: Apple Inc.  
**Inventor**: [Jong Young Hong](https://patents.google.com/?inventor=Jong+Young+Hong&assignee=Apple&country=US&num=100&sort=new), [Lai Wang](https://patents.google.com/?inventor=Lai+Wang&assignee=Apple&country=US&num=100&sort=new), [Byron R Cocilovo](https://patents.google.com/?inventor=Byron+R+Cocilovo&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
一种显示器包括一个波导，其具有夹在第一和第二基板之间的光栅介质。交叉耦合器可以将波导中的光引导至输出耦合器。输出耦合器可包括介质中的体全息图。输出耦合器可以将光从波导中耦合出来并引导至目镜盒。交叉耦合器可包括表面浮雕光栅（SRG）。SRG可以将入射到SRG上的不同色道的全部视场光在波导的全内反射（TIR）范围内衍射到波导TIR过渡角的对立两侧。这可以防止在目镜盒中一个或多个色道中形成难看的暗带。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486364493_1.jpg)

**Technical Field (技术领域)**:  
光学系统技术领域，具体涉及用于虚拟现实或增强现实显示器的波导光学系统。

**Background (发明背景)**:  
电子设备中的光学系统常用于向用户眼睛附近显示图像，例如虚拟现实或增强现实头戴式设备。
现有技术中，光学元件之间的边界可能导致图像出现难看的伪影，影响显示效果。
此外，笨重的光学组件也可能影响设备的整体性能和用户体验。
本发明旨在解决色道间因光衍射导致的暗带问题，同时优化光学性能。

**Summary (发明总览)**:  
本发明提出了一种改进的波导显示器，通过在波导结构中引入表面浮雕光栅（SRG），实现了对不同色道光的精确控制。
该设计利用SRG将不同色道的光衍射到波导全内反射（TIR）范围的不同区域，从而避免色道间形成暗带。
这种结构不仅提升了显示质量，还保持了波导的紧凑性。
相较于传统方案，本发明通过优化光路设计，减少了光学伪影，提升了整体显示效果。

**Key Innovation (核心创新)**:  
1. 采用表面浮雕光栅（SRG）作为交叉耦合器，通过精确控制光的衍射角度，将不同色道的光引导至波导TIR范围的对立两侧。
2. 在波导结构中引入第三基板，并在其中集成SRG，实现对第一和第二色道光的独立控制，避免色道间形成暗带。
3. 通过调整SRG的衍射特性，将第一色道的光衍射到TIR范围内的第一角度，将第二色道的光衍射到TIR范围外的第二角度，实现色道分离。
4. 利用体全息图作为输出耦合器，将光从波导中耦合出来并引导至目镜盒，确保光路的高效传输。
5. 该设计通过优化光路和光栅结构，减少了光学元件间的边界效应，提升了显示质量。
6. 该技术特别适用于虚拟现实和增强现实头戴式设备，能够提供更清晰、无伪影的图像显示。
7. 通过减少暗带和光学伪影，本发明提升了用户体验，并使设备更加紧凑和轻便。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486364493)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12730266)**
<br/><br/>

---


<br/>

### 22. 用于头戴式显示系统的镜头安装结构

**Title (EN)**: Lens mounting structures for head-mounted display systems  
**Pub. No.**: US12730324

**Applicant**: Apple Inc.  
**Inventor**: [Austin S Young](https://patents.google.com/?inventor=Austin+S+Young&assignee=Apple&country=US&num=100&sort=new), [Yinjuan He](https://patents.google.com/?inventor=Yinjuan+He&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
头戴式设备可具有提供显示图像的显示系统。显示图像可通过具有输出耦合器的波导提供给送到眼盒供用户观看。波导由头戴式支撑结构支撑，位于设备左侧的前后镜头之间以及右侧的前后镜头之间。前后镜头可使用前置和/或后置安装方式安装到头戴式支撑结构上。前置镜头从前部安装到头戴式支撑结构中，并可由头戴式支撑结构中的具有前表面（朝外表面）的对准架支撑。后置镜头从后部安装到头戴式支撑结构中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486364555_1.jpg)

**Technical Field (技术领域)**:  
电子设备技术领域，具体涉及头戴式显示设备的光学镜头安装结构。

**Background (发明背景)**:  
头戴式设备通常包含光学元件如镜头，这些镜头被安装在头戴式支撑结构中。
现有技术中，镜头安装方式可能影响设备的整体光学性能和用户体验。
传统安装方式可能限制镜头调节的灵活性，并影响显示图像与现实世界的叠加效果。
本发明旨在提供一种改进的镜头安装结构，以提高光学对准精度和调节灵活性。

**Summary (发明总览)**:  
本发明提供了一种用于头戴式显示系统的镜头安装结构，通过前置和后置安装方式实现镜头的高精度对准。
该结构利用对准架支撑镜头，前置镜头由朝外表面支撑，后置镜头由朝内表面支撑。
设备支持可调节光学组件，例如可电调节的光调制器，以增强显示效果。
这种设计优化了显示图像与现实世界的叠加效果，并提升了用户观看体验。

**Key Innovation (核心创新)**:  
1. 采用前置和后置安装方式，通过对准架分别支撑前置和后置镜头，实现高精度光学对准。
2. 前置镜头由具有前表面的对准架支撑，后置镜头由具有后表面的对准架支撑，确保镜头安装的稳定性和精确性。
3. 引入可电调节的光调制器等可调节光学组件，实现对显示图像的动态调节和优化。
4. 波导被设计为在左右两侧的前后镜头之间提供支撑，确保显示图像的均匀传输和清晰度。
5. 该结构允许用户同时观看显示图像和现实世界，并通过镜头优化叠加效果，提升混合现实体验。
6. 通过改进的安装结构，设备在光学性能和用户舒适度方面得到提升，适用于需要高精度光学对准的增强现实和虚拟现实应用。
7. 该技术可应用于头戴式显示设备，如增强现实眼镜和虚拟现实头盔，为用户提供更自然和沉浸的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486364555)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12730324)**
<br/><br/>

---


<br/>

### 23. 优化的混合拜耳色彩滤光片阵列

**Title (EN)**: Optimized hybrid Bayer color filter array  
**Pub. No.**: US12732711

**Applicant**: Apple Inc.  
**Inventor**: [Patrick C Carroll](https://patents.google.com/?inventor=Patrick+C+Carroll&assignee=Apple&country=US&num=100&sort=new), [Gilad Michael](https://patents.google.com/?inventor=Gilad+Michael&assignee=Apple&country=US&num=100&sort=new), [Paulom Shah](https://patents.google.com/?inventor=Paulom+Shah&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 08.09.2026

**Abstract**:  
在一些实施例中，图像传感器结构接收来自色彩滤光片阵列的光，该阵列包括多个区域。高分辨率区域包含用于传感器阵列中各个传感器的第一拜耳模式色彩滤光片，而低分辨率区域包含用于传感器阵列中传感器组的第二拜耳模式色彩滤光片。图像可以从图像传感器以多种分辨率读取，以最高分辨率模式读取的图像保留最大细节，而以较低分辨率模式读取的图像在某些实施例中可能需要较少的硬件和计算资源，并可能表现出更好的噪声性能。图像传感器结构的各个区域可能对应于不同的操作模式或不同的分辨率能力。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486367184_1.jpg)

**Technical Field (技术领域)**:  
图像传感器技术领域，具体涉及色彩滤光片阵列设计和多分辨率图像读取技术。

**Background (发明背景)**:  
随着智能手机和平板设备等小型移动多功能设备的发展，对高分辨率、小型化相机的需求日益增加。然而，增加相机传感器的分辨率对硬件资源和图像处理能力提出了更高的要求，同时光学性能受到限制。此外，不同的相机操作模式（如不同的视场角和静态摄影与动态摄影）对相机传感器的分辨率能力提出了不同的要求。因此，具有固定分辨率能力、硬件带宽和处理需求的固定相机传感器配置变得越来越具有挑战性。

**Summary (发明总览)**:  
本发明提出了一种优化的混合拜耳色彩滤光片阵列设计，通过在图像传感器结构中引入多个区域来适应不同的操作模式和分辨率需求。高分辨率区域使用传统的拜耳模式滤光片，而低分辨率区域则采用适用于传感器组的滤光片模式。这种设计允许图像以多种分辨率读取，在高分辨率模式下保留细节，在低分辨率模式下减少硬件和计算资源需求并提升噪声性能。

**Key Innovation (核心创新)**:  
1. 设计了混合拜耳色彩滤光片阵列，其中高分辨率区域采用传统拜耳模式，低分辨率区域采用适用于传感器组的滤光片模式。
2. 通过在图像传感器结构中划分不同区域，实现了对不同操作模式和分辨率需求的适应性。
3. 实现了多分辨率图像读取功能，允许用户根据需求选择高分辨率模式以保留细节或低分辨率模式以节省资源和提升噪声性能。
4. 低分辨率区域的传感器组滤光片设计减少了硬件和计算资源的需求，同时在低分辨率模式下提升了图像的噪声性能。
5. 该设计适用于需要兼顾高分辨率和低资源消耗的应用场景，如移动设备相机系统。
6. 通过优化色彩滤光片阵列布局，本发明能够在不显著增加硬件复杂性的情况下实现多分辨率图像读取。
7. 潜在应用场景包括智能手机相机、运动相机和监控设备等，能够在资源受限的环境中提供灵活的图像采集解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486367184)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12732711)**
<br/><br/>

---



**Total Patents**: 23  
**Last Updated**: 20260912

---

The Patent Scoop Trio
