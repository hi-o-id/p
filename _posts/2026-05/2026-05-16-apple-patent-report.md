---
layout: post
title: "Apple 专利小快报 2026-05-16"
date: 2026-05-16 15:20:56 +0800
categories: Apple
---

**New Patents**: 13  

---


<br/>

### 1. 多用户通信会话中的替代对象表示

**Title (EN)**: Alternative Object Representations in Multi-User Communication Sessions  
**Pub. No.**: US20260134620

**Applicant**: Apple Inc.  
**Inventor**: [Leanid Vouk](https://patents.google.com/?inventor=Leanid+Vouk&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
本发明涉及在多用户通信会话中共享二维视频流数据和额外数据（例如，三维数据），并使接收（观看）设备能够根据情况选择性地使用这些信息。例如，如果接收设备具有立体视觉能力（例如头戴式设备），则设备可决定使用额外数据来呈现接收的二维视频流，以增加用户表示或其他对象的深度。相反，如果接收设备（例如传统平板电脑、移动设备或笔记本电脑）不具备立体视觉能力，则设备可决定仅以二维方式显示二维视频流，而不一定使用额外数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478868127_1.jpg)

**Technical Field (技术领域)**:  
多用户通信技术领域，具体涉及基于设备能力选择性呈现二维和三维对象表示的技术。

**Background (发明背景)**:  
在多用户通信会话中，现有技术主要通过共享二维视频流和音频流来支持用户之间的视觉和听觉互动。然而，这些技术未能充分利用三维信息来增强用户体验，也未充分考虑或根据接收设备的立体视觉能力等可变因素进行定制化处理。

**Summary (发明总览)**:  
本发明提出了一种在多用户通信会话中共享二维视频流和三维数据的方法，使接收设备能够根据自身能力（如是否支持立体视觉）选择性地呈现对象表示。发送设备发送包含二维视频流和可选三维数据的组合数据，接收设备根据设备类型、立体视觉能力以及三维数据质量等因素决定是否使用三维数据来增强对象表示的深度效果。这种方法既支持立体视觉设备呈现具有深度感的对象，也允许不具备立体视觉能力的设备以传统二维方式显示内容。

**Key Innovation (核心创新)**:  
1. 实现了二维视频流与三维数据的联合传输，使接收设备能够根据自身能力选择性地呈现对象表示。
2. 通过分析接收设备的立体视觉能力（如是否支持头戴式设备或普通平板设备），动态决定是否使用三维数据来增强对象表示的深度效果。
3. 支持在二维视频流中针对特定对象或时间片段嵌入三维数据，例如每第10帧嵌入深度信息，以优化数据处理效率。
4. 提供了多种呈现模式，包括仅二维显示、使用三维数据增强深度感，以及在二维背景上叠加具有立体感的对象表示。
5. 发送设备能够根据接收设备的能力和需求，灵活调整发送的数据类型和格式，例如仅发送二维视频流或同时发送附加的三维数据。
6. 在头戴式设备等支持立体视觉的设备上，可呈现具有深度感的对象，而在普通平板或笔记本电脑上则保持传统二维显示。
7. 本发明可应用于视频会议、虚拟现实和增强现实场景，为不同设备提供一致且优化的用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478868127)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260134620)**
<br/><br/>

---


<br/>

### 2. 具有视力矫正功能的头戴式显示设备

**Title (EN)**: Head-Mounted Display Device With Vision Correction  
**Pub. No.**: US20260133437

**Applicant**: Apple Inc.  
**Inventor**: [Victoria C. Chan](https://patents.google.com/?inventor=Victoria+C.+Chan&assignee=Apple&country=US&num=100&sort=new), [Christina G. Gambacorta](https://patents.google.com/?inventor=Christina+G.+Gambacorta&assignee=Apple&country=US&num=100&sort=new), [Graham B. Myhre](https://patents.google.com/?inventor=Graham+B.+Myhre&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
一种头戴式显示设备包括显示系统和光学系统，均集成在壳体中。显示系统包含用于生成图像的显示器，位置调节器用于相对于用户眼睛位置移动显示器。可调节光学系统包括可调谐透镜，例如可调谐圆柱形液晶透镜。当用户眼睛位于眼位时，可通过透镜观看显示器。头戴式显示设备集成了传感器，用于测量用户眼睛的屈光误差。传感器包括波导和体全息图，以及用于收集从用户视网膜反射的光线的摄像头。通过调整显示器相对于眼位的显示位置和/或基于显示内容或测量的眼睛屈光误差调整透镜设置，可以提高观看舒适度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478866818_1.jpg)

**Technical Field (技术领域)**:  
头戴式显示设备技术领域，具体涉及光学系统和视力矫正技术。

**Background (发明背景)**:  
头戴式设备如虚拟现实眼镜和增强现实眼镜使用显示器生成图像，并通过透镜将图像呈现给用户眼睛。现有技术中，这类设备的光学系统可能体积庞大、重量大且调节能力不足，长时间使用可能导致佩戴不适。本发明旨在解决光学系统不够灵活、难以适应不同用户视力差异的问题。

**Summary (发明总览)**:  
本发明提出了一种具有视力矫正功能的智能头戴式显示设备，通过集成可调谐光学系统和传感器，实现对用户眼睛屈光误差的测量和补偿。设备通过调整显示器位置和透镜设置来优化观看体验，适应不同用户的瞳距、面部解剖结构和视力状况。其核心改进在于提供了一种动态调节的光学系统，既能矫正视力问题，又能提升佩戴舒适度。

**Key Innovation (核心创新)**:  
1. 采用可调谐圆柱形液晶透镜，通过动态调节光学参数，实现对用户近视、远视和散光等屈光误差的矫正。
2. 集成波导和体全息图作为传感器组件，结合摄像头收集视网膜反射光线，精确测量眼睛的屈光误差。
3. 使用位置调节器调整显示器相对于用户眼睛的水平和垂直位置，以适应不同用户的瞳距和面部解剖结构。
4. 通过调整显示器与眼睛的间距，实现对焦距的精细控制，进一步提升图像清晰度和观看舒适度。
5. 结合固定球面透镜和可调谐透镜的组合光学系统，在保证光学性能的同时简化设备结构。
6. 设备能够根据显示内容或测量的眼睛屈光误差自动调整光学设置，实现个性化的视觉体验。
7. 该技术可应用于虚拟现实和增强现实系统，为用户提供更舒适、更清晰的视觉体验，尤其适合需要长时间佩戴的用户。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478866818)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260133437)**
<br/><br/>

---


<br/>

### 3. 在三维环境中促进内容项多视图显示的方法

**Title (EN)**: METHODS OF FACILITATING MULTIVIEW DISPLAY OF CONTENT ITEMS IN A THREE-DIMENSIONAL ENVIRONMENT  
**Pub. No.**: US20260133667

**Applicant**: Apple Inc.  
**Inventor**: [Matan STAUBER](https://patents.google.com/?inventor=Matan+STAUBER&assignee=Apple&country=US&num=100&sort=new), [Marinos BERNITSAS](https://patents.google.com/?inventor=Marinos+BERNITSAS&assignee=Apple&country=US&num=100&sort=new), [Danvin RUANGCHAN](https://patents.google.com/?inventor=Danvin+RUANGCHAN&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
在一些实施例中，计算机系统促进在三维环境中以多视图观看模式显示的一个或多个内容项表示的更新显示方向。在一些实施例中，计算机系统促进与在三维环境中以多视图观看模式显示的一个或多个内容项的交互。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478867073_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算机生成体验领域，具体为增强现实和混合现实体验的显示技术。

**Background (发明背景)**:  
近年来，增强现实计算机系统的发展显著增加。现有增强现实环境通常包含一些虚拟元素，用于替代或增强现实世界。然而，现有系统存在反馈反馈不足、交互步骤繁琐、虚拟对象操作复杂等问题，这增加了用户认知负担，影响了虚拟/增强现实体验。此外，这些方法耗时较长，导致计算机系统能耗增加，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种改进的计算机系统用户界面，用于在三维环境中提供扩展现实体验。通过优化内容项的显示方向和多视图交互方式，本发明简化了用户操作步骤，减少了输入数量，提高了交互效率。本发明还通过改进的反馈和直观的交互方式，降低了用户认知负担，提升了整体体验。

**Key Innovation (核心创新)**:  
1. 通过检测用户输入，实时更新三维环境中内容项的显示方向，实现多视图内容项的动态调整。
2. 在检测到特定输入时，动态显示多个内容项的表示，并调整其相对于用户视角的方位，以提供更丰富的视觉体验。
3. 提供内容选择用户界面，允许用户通过直观的手势或语音输入选择多视图模式下的内容项。
4. 在多视图模式下，支持同时显示多个内容项的播放状态，并通过调整其相对位置和方向来优化用户观看体验。
5. 通过优化用户输入与设备响应的连接，减少用户输入次数和复杂度，提升人机交互效率。
6. 适用于便携式设备（如头戴式显示器）和电池供电设备，通过减少计算量和优化显示机制来节省能耗。
7. 应用于虚拟现实、增强现实和混合现实场景，为用户提供更自然、直观的交互方式，提升沉浸式体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478867073)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260133667)**
<br/><br/>

---


<br/>

### 4. 用于光线追踪着色器的链式技术

**Title (EN)**: Chaining Techniques for Ray Tracing Shaders  
**Pub. No.**: US20260134616

**Applicant**: Apple Inc.  
**Inventor**: [Ali Rabbani Rankouhi](https://patents.google.com/?inventor=Ali+Rabbani+Rankouhi&assignee=Apple&country=US&num=100&sort=new), [Luca O. Iuliano](https://patents.google.com/?inventor=Luca+O.+Iuliano&assignee=Apple&country=US&num=100&sort=new), [Richard J. Forster](https://patents.google.com/?inventor=Richard+J.+Forster&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
本发明涉及图形处理器中用于光线追踪的叶着色器技术。在一些实施例中，图形处理器包括着色器处理电路和光线加速电路，用于执行与图形场景的加速数据结构相对应的遍历操作。加速电路在检测到第一根光线到达加速数据结构中的节点时，会启动第一着色器程序来处理该节点。处理器在执行第一着色器程序中的指令时，会启动并执行第二着色器程序以进一步处理该节点。本发明还公开了用于确定是生成单个着色器还是多个链式着色器的技术。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478868123_1.jpg)

**Technical Field (技术领域)**:  
图形处理器技术领域，具体涉及光线追踪的着色器控制技术。

**Background (发明背景)**:  
光线追踪是一种通过模拟光线与虚拟物体交互来生成图像的渲染技术，能够提供高度真实感的场景和照明效果，但其计算成本较高。传统光线追踪系统通常采用反向光线追踪方法，从相机出发追踪光线路径。尽管硬件加速技术可以提升遍历加速数据结构的效率，但在处理复杂节点（如叶节点）时，着色器程序内的线程发散问题会导致效率低下。本发明旨在解决这一问题，通过改进着色器执行方式提高光线追踪的性能和效率。

**Summary (发明总览)**:  
本发明提出了一种基于链式着色器的光线追踪处理方法，通过将节点处理过程拆分为多个顺序执行的着色器程序来优化性能。具体来说，初始着色器执行初步测试（如定向包围盒测试），然后通过链式指令启动后续着色器处理通过测试的光线。这种方法能够有效减少线程发散，提高SIMT组内执行效率，同时允许未通过测试的光线独立继续遍历。

**Key Innovation (核心创新)**:  
1. 将叶节点处理拆分为多个链式着色器程序，例如将定向包围盒（OBB）测试和曲线测试分离到不同的着色器中。
2. 通过在初始着色器中执行初步测试（如OBB测试），并使用链式指令启动后续着色器处理通过测试的光线，从而实现更高效的资源利用。
3. 允许未通过初步测试的光线独立继续遍历，避免了不必要的等待时间，提高了整体处理效率。
4. 硬件加速器支持动态启动后续着色器，并能够重新分组光线以适应链式着色器的执行需求。
5. 通过分离不同测试阶段的处理，减少了SIMT组内线程发散问题，提高了着色器执行的并行度。
6. 这种方法适用于复杂场景中的光线追踪处理，能够在保持高真实感的同时提升性能并降低功耗。
7. 本发明特别适用于需要高效光线追踪的图形应用场景，如游戏、虚拟现实和电影渲染，能够提供更流畅的体验和更逼真的视觉效果。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478868123)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260134616)**
<br/><br/>

---


<br/>

### 5. 用于显示用户界面和用户界面叠加元素的设备、方法和图形用户界面

**Title (EN)**: DEVICE, METHOD, AND GRAPHICAL USER INTERFACE FOR DISPLAYING USER INTERFACES AND USER INTERFACE OVERLAY ELEMENTS  
**Pub. No.**: US20260133691

**Applicant**: Apple Inc.  
**Inventor**: [Mani Amini](https://patents.google.com/?inventor=Mani+Amini&assignee=Apple&country=US&num=100&sort=new), [Wan Si Wan](https://patents.google.com/?inventor=Wan+Si+Wan&assignee=Apple&country=US&num=100&sort=new), [Eric Lance Wilson](https://patents.google.com/?inventor=Eric+Lance+Wilson&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
一种方法包括：以全屏视图显示包括以第一组显示属性显示的第一类型组件的第一显示区域；检测用于显示第二显示区域的第一用户输入；并且，在检测到第一用户输入的情况下：根据确定第一用户输入对应于请求以全屏视图显示第二显示区域，以全屏视图显示包括以第一组显示属性显示的第一类型组件的第二显示区域；以及根据确定第一用户输入对应于请求以分屏视图显示第二显示区域，以分屏视图显示第二显示区域，其中第二显示区域中的第一类型组件以不同于第一组显示属性的第二组显示属性显示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478867100_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及用户界面显示技术，具体涉及基于用户输入动态调整显示区域布局和显示属性的方法。

**Background (发明背景)**:  
电子设备通常使用外围输入（如触摸屏、鼠标、键盘）来操控用户界面，但这些输入方式往往控制有限且效率低下。复杂的操作需要重复或繁琐的输入，增加了用户负担并降低了设备效率。本发明旨在提供更快速、高效的导航和操控用户界面的方法，以减少认知负担并优化人机交互体验。

**Summary (发明总览)**:  
本发明提出了一种基于用户输入动态调整显示区域布局和显示属性的方法。通过检测用户输入并判断其意图，系统能够以全屏或分屏视图显示不同的显示区域，并根据显示区域所在层级应用不同的显示属性。此外，本发明还提供了一种根据背景内容动态调整用户界面叠加元素外观的方法，以增强用户对界面元素的辨识度。本发明通过减少用户交互次数和优化显示效果，提升了设备的使用效率和电池续航能力。

**Key Innovation (核心创新)**:  
1. 通过检测用户输入并判断其意图，系统能够以全屏或分屏视图显示不同的显示区域，从而实现更灵活的界面布局。
2. 在显示区域切换时，根据显示区域所在层级应用不同的显示属性，例如在深色模式下为不同层级的组件分配不同的显示属性，以增强用户对层级结构的辨识度。
3. 提供了一种根据背景内容动态调整用户界面叠加元素外观的方法，通过分析背景内容的视觉属性值，确保叠加元素与背景之间保持足够的视觉对比度。
4. 在检测到显示设备亮度或环境光变化时，系统会调整用户界面元素的显示属性，以优化在各种光照条件下的可读性和视觉舒适度。
5. 通过压缩调整前景和背景用户界面元素之间的对比度范围，本发明解决了低亮度环境下OLED屏幕的“果冻效应”问题。
6. 本发明通过减少用户交互次数和优化显示效果，降低了设备的磨损和功耗，延长了电池续航时间。
7. 该技术可应用于智能手机、平板电脑、笔记本电脑等便携式设备，为用户提供更高效、更舒适的界面交互体验，特别是在深色模式和低光照环境下具有独特优势。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478867100)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260133691)**
<br/><br/>

---


<br/>

### 6. 配置基于上下文的计算设备使用限制

**Title (EN)**: Configuring Context-Based Restrictions For A Computing Device  
**Pub. No.**: US20260134153

**Applicant**: Apple Inc.  
**Inventor**: [Paul W. Salzman](https://patents.google.com/?inventor=Paul+W.+Salzman&assignee=Apple&country=US&num=100&sort=new), [Christopher G. Skogen](https://patents.google.com/?inventor=Christopher+G.+Skogen&assignee=Apple&country=US&num=100&sort=new), [David S. Clark](https://patents.google.com/?inventor=David+S.+Clark&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
在一些实现中，计算设备可以限制另一计算设备在特定上下文中的使用。例如，父母可能希望使用其计算设备来限制其子女在上学期间使用其计算设备的行为，而此时子女应参与其他活动。例如，父母的控制设备可以远程配置和控制卫星设备的使用，而无需物理接触卫星设备。父母可以实施限制、权限或不同的策略，以管理卫星设备与其他设备通信、执行各种应用程序功能、运行任何特定软件以及管理其自身设置的能力。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478867610_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算设备操作领域，具体为远程限制设备在特定上下文中的使用。

**Background (发明背景)**:  
现代移动设备在用户应专注于生产性活动（如工作、学习或其他生产性活动）时常常成为干扰。现有的设备管理方法通常需要物理接触设备，这给设备管理者（如父母或雇主）带来了不便和负担。

**Summary (发明总览)**:  
本发明提出了一种远程配置基于上下文的设备使用限制的方法。通过控制设备，用户可以远程设置和管理另一设备的功能限制，例如限制通信、执行应用程序或运行特定软件的能力。这种方法无需物理接触设备即可实现多设备管理，并提供了一种机制来监控和报告设备的使用情况，从而提高管理的有效性和可靠性。

**Key Innovation (核心创新)**:  
1. 实现了远程配置和管理设备使用限制的功能，用户无需物理接触设备即可进行管理。
2. 提供了基于上下文的限制机制，例如在特定时间或地点自动应用限制策略。
3. 支持多设备管理，用户可以同时为多个设备配置相同的限制配置，减少重复操作。
4. 引入了明显的模式退出过程机制，例如当设备用户尝试退出限制模式时，系统会向控制设备发送通知，从而提高管理的透明度和可靠性。
5. 在限制模式下，设备仍能执行特定功能，如紧急通信或联系父母，确保设备在紧急情况下的可用性。
6. 通过限制设备功能，减少了电池消耗、带宽使用和处理器的占用，从而延长设备续航时间和提高设备性能。
7. 适用于家长控制和企业设备管理场景，提供了一种高效、可靠且用户友好的设备管理解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478867610)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260134153)**
<br/><br/>

---


<br/>

### 7. 具有侧壁显示屏的电子设备

**Title (EN)**: Electronic Devices With Sidewall Displays  
**Pub. No.**: US20260133663

**Applicant**: Apple Inc.  
**Inventor**: [Scott A. Myers](https://patents.google.com/?inventor=Scott+A.+Myers&assignee=Apple&country=US&num=100&sort=new), [Stephen Brian Lynch](https://patents.google.com/?inventor=Stephen+Brian+Lynch&assignee=Apple&country=US&num=100&sort=new), [Anthony S. Montevirgen](https://patents.google.com/?inventor=Anthony+S.+Montevirgen&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
本发明涉及包含柔性显示屏的电子设备，该柔性显示屏被弯曲以在设备多个表面形成显示屏。弯曲的柔性显示屏可形成正面显示屏和边缘显示屏。边缘显示屏可通过图案化的外壳部件、打印或涂覆的遮罩层，或通过选择性地激活和停用与柔性显示屏相关的显示像素，与正面显示屏或其他边缘显示屏分隔。边缘显示屏可作为虚拟按钮、虚拟开关或补充正面显示屏的信息显示屏交替使用。虚拟按钮可包括透明按钮部件、透镜、触觉反馈组件、音频反馈组件或其他用于在用户操作虚拟按钮时提供反馈的组件。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478867069_1.jpg)

**Technical Field (技术领域)**:  
柔性显示技术领域，具体涉及具有弯曲边缘显示屏的电子设备及其用户界面设计。

**Background (发明背景)**:  
传统电子设备通常使用刚性显示屏，如液晶显示屏（LCD），并通过设备边缘的物理按钮和开关进行用户输入操作。这种设计限制了设备外观的创新性和交互方式的多样性。柔性显示技术虽然提供了新的可能性，但如何有效利用柔性显示屏的弯曲特性来增强用户交互体验仍是一个挑战。

**Summary (发明总览)**:  
本发明提出了一种具有弯曲边缘显示屏的电子设备设计方案，通过将柔性显示屏弯曲以覆盖设备的侧壁表面，实现了正面和侧壁显示的集成。侧壁显示屏可作为虚拟用户界面控件，如按钮和开关，并根据用户操作进行动态重新配置。这种设计不仅取代了传统的物理按钮和开关，还提供了更灵活的用户交互方式，提升了设备的功能性和美观性。

**Key Innovation (核心创新)**:  
1. 通过弯曲柔性显示屏，在电子设备的侧壁表面创建显示区域，实现多表面显示一体化。
2. 使用不透明遮罩层将柔性显示屏的主动显示区域与不活动区域分离，并通过开孔控制显示内容的可见性。
3. 在侧壁显示屏上创建虚拟用户界面控件，如按钮和开关，并通过触摸输入进行操作。
4. 虚拟按钮可根据用户操作动态重新配置，例如从音量控制切换为相机快门按钮或设备功能控制器。
5. 通过在柔性显示屏的触摸敏感层上预设输入动作（如轻触、滑动手势）来改变设备的操作模式。
6. 侧壁显示屏可显示信息或虚拟按钮，提供与传统物理按钮相同或更丰富的用户交互功能。
7. 该设计可应用于智能手机、平板电脑等便携式设备，为用户提供更直观、更具沉浸感的交互体验，同时增强设备的美学设计。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478867069)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260133663)**
<br/><br/>

---


<br/>

### 8. 基于上下文的虚拟形象质量

**Title (EN)**: CONTEXT-BASED AVATAR QUALITY  
**Pub. No.**: US20260134649

**Applicant**: Apple Inc.  
**Inventor**: [Hayden James Barsotti](https://patents.google.com/?inventor=Hayden+James+Barsotti&assignee=Apple&country=US&num=100&sort=new), [Connor A. Smith](https://patents.google.com/?inventor=Connor+A.+Smith&assignee=Apple&country=US&num=100&sort=new), [Alexandre Da Veiga](https://patents.google.com/?inventor=Alexandre+Da+Veiga&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
本发明公开了多种实现方案，包括设备、系统和方法，用于提供通信会话，其中第一设备接收并使用流式传输的虚拟形象数据来渲染包含时变虚拟形象的画面，例如在通信会话期间由另一用户的设备发送的该用户的部分或全部视频内容。为了有效利用资源（例如电力、带宽等），一些实现方案根据用户上下文调整虚拟形象的提供过程（例如视频帧率、图像分辨率等），例如判断观看者是否正在注视虚拟形象、虚拟形象是否位于观看者的中央凹区域或视野范围内。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478868160_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及虚拟形象技术领域，具体为在多用户通信会话中用于优化虚拟形象呈现质量的技术。

**Background (发明背景)**:  
现有的通信会话技术允许用户共享音频、图像和其他内容，但难以在资源受限的情况下提供既准确反映用户外观又高效利用系统资源的虚拟形象。此外，现有系统无法根据用户的注视行为或环境上下文动态调整虚拟形象的质量。

**Summary (发明总览)**:  
本发明提供了一种通信会话方法，通过第一设备接收并渲染包含时变虚拟形象的画面，例如另一用户的视频内容。该方法根据用户上下文（例如用户的注视行为、虚拟形象在视野中的位置等）动态调整虚拟形象的提供过程，例如调整视频帧率或图像分辨率，从而优化资源利用。实现方式包括识别用户的未来注意力状态，并根据该状态选择不同质量的虚拟形象数据或渲染优化策略。

**Key Innovation (核心创新)**:  
1. 通过识别用户的未来注意力状态（如注视行为、虚拟形象在视野中的位置等），动态调整虚拟形象的提供过程，例如调整视频帧率或图像分辨率。
2. 将虚拟形象数据分割成多个部分（如宏块），每部分具有多种质量等级，接收设备根据用户的注意力状态选择适当的质量等级进行渲染。
3. 采用多种渲染优化策略，包括网格分辨率选择、动画分辨率选择和着色器细节/复杂度选择，以根据用户注意力状态优化虚拟形象呈现效果。
4. 在通信会话中，第一设备能够从远程设备或中间服务器获取不同质量的虚拟形象数据，并根据用户上下文选择合适的质量版本进行渲染。
5. 通过分析用户的动作（如静止、移动、转头等）和虚拟形象的动作（如说话、开始动手等），进一步优化虚拟形象的呈现质量。
6. 该技术可应用于扩展现实（XR）环境，通过在3D环境中定位3D虚拟形象，并根据用户注视行为调整其呈现质量。
7. 本发明能够提升通信会话中虚拟形象的视觉质量和资源利用效率，尤其适用于需要高沉浸感和高效资源管理的应用场景，如虚拟会议和远程协作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478868160)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260134649)**
<br/><br/>

---


<br/>

### 9. 推送通知分发系统

**Title (EN)**: PUSH NOTIFICATION DISTRIBUTION SYSTEM  
**Pub. No.**: US20260135927

**Applicant**: Apple Inc.  
**Inventor**: [Huan HE](https://patents.google.com/?inventor=Huan+HE&assignee=Apple&country=US&num=100&sort=new), [Jonathon SODOS](https://patents.google.com/?inventor=Jonathon+SODOS&assignee=Apple&country=US&num=100&sort=new), [Nicholas J. CIRCOSTA](https://patents.google.com/?inventor=Nicholas+J.+CIRCOSTA&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
推送通知分发系统集中管理并向在电子设备上运行的应用程序分发推送通知。注册请求以聚合注册请求的形式发送，用于注册应用程序接收推送通知。推送通知的传递优先级可根据指定偏好进行管理。当接收到针对电子设备的推送通知时，如果发现与推送通知关联的应用程序标识符在具有指定传递优先级的应用程序标识符列表中，则可以更改推送通知的传递优先级。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478869570_1.jpg)

**Technical Field (技术领域)**:  
网络通信领域，具体涉及推送通知管理。

**Background (发明背景)**:  
推送通知用于通知应用程序有关其更新的信息。在接收推送通知之前，运行应用程序的电子设备需要注册以接收与该应用程序相关的推送通知。随着电子设备上运行的应用程序数量增加，维护这些应用程序的推送通知注册负担也增加。此外，推送通知的高频率传递可能对电子设备的性能产生不利影响。

**Summary (发明总览)**:  
本发明提出了一种集中化的推送通知分发系统，通过在电子设备上运行的推送分发客户端聚合来自多个应用程序的注册请求，并将其作为一个整体发送给推送分发服务器。服务器维护一个包含应用程序标识符、用户标识符和设备标识符的集中化注册表，从而简化推送通知的分发流程。这种方法减少了网络通信量，提高了注册可靠性，并降低了开发者和应用服务器的管理开销。

**Key Innovation (核心创新)**:  
1. 通过在电子设备上运行的推送分发客户端聚合多个应用程序的注册请求，减少了网络通信量。
2. 推送分发服务器维护一个集中化的注册表，包含应用程序标识符、用户标识符和设备标识符，简化了推送通知的分发流程。
3. 根据指定条件（如用户登录状态或时间间隔）决定是否生成聚合注册请求，从而优化注册请求的发送频率。
4. 支持不同优先级的推送通知传递，例如立即传递高优先级通知，或在电子设备处于活跃状态时传递低优先级通知。
5. 通过集中化注册表，开发者只需跟踪用户账户而非所有关联设备，降低了管理复杂性。
6. 推送通知分发系统能够跨多个设备分发通知，利用集中化注册表识别与特定用户账户关联的电子设备。
7. 该系统适用于需要高效推送通知管理的应用场景，如社交媒体和消息应用，能够提升用户体验并优化设备性能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478869570)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260135927)**
<br/><br/>

---


<br/>

### 10. 物理环境物体的3D表示

**Title (EN)**: 3D Representation of Physical Environment Objects  
**Pub. No.**: US20260134621

**Applicant**: Apple Inc.  
**Inventor**: [Boyuan Sun](https://patents.google.com/?inventor=Boyuan+Sun&assignee=Apple&country=US&num=100&sort=new), [Bin Liu](https://patents.google.com/?inventor=Bin+Liu&assignee=Apple&country=US&num=100&sort=new), [Feng Tang](https://patents.google.com/?inventor=Feng+Tang&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
本发明提供物体的3D表示。这些表示基于3D点云和/或2D图像输入，这些输入是通过传感器数据（例如，图像、深度数据、运动数据等）获得的。3D点云输入可用于部件分割和/或确定物体部件的位置和/或方向，例如生成表示物体部件大小、位置和方向的3D边界框。2D图像输入可用于部件属性识别，例如确定椅子腿部部件是否具有特定类型，如星形、直立、交叉形等。部件属性可用于生成相对简单且相对准确的各部件在其相应区域（例如，在使用3D点云输入确定的边界框内）的形状表示。因此，物体的输出3D表示可以相对高效地生成（例如，无需计算成本高的3D网格算法）。输出3D表示可以提供关于物体大小、位置、方向和部件形状的合理准确度的3D表示。输出3D表示可以包括更平滑、更干净或更令人满意的视觉外观，基于已知几何形状而不是直接（或仅）基于可能嘈杂的传感器数据来表示物体部件。3D表示可用于各种目的，包括但不限于生成可用于实时和实时通信会话中的物体表示、在扩展现实（XR）中放置虚拟物体（例如，准确地将虚拟角色的手臂放置在沙发背上），和/或增强搜索（例如，搜索与他人沙发相似的沙发）。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478868128_1.jpg)

**Technical Field (技术领域)**:  
本专利属于计算机视觉与增强现实领域，具体涉及利用传感器数据生成物体3D表示的技术。

**Background (发明背景)**:  
在物理环境中生成物体的3D表示是计算机视觉和增强现实中的重要技术。现有的方法主要依赖于3D点云或3D网格，但这些方法在捕捉和使用物体的3D表示方面存在不足，例如难以高效地生成精确的3D表示，或者在处理复杂场景时计算成本过高。本发明旨在解决这些问题，通过结合3D点云和2D图像输入，提供一种更高效、更准确的3D表示生成方法。

**Summary (发明总览)**:  
本发明提出了一种结合3D点云和2D图像输入来生成物体3D表示的方法。首先，基于3D点云生成物体的粗略3D表示，该表示包括物体各部件的3D位置和大小。然后，通过2D图像识别各部件的属性，例如类型、颜色和材料等。最后，基于粗略表示和识别出的属性生成更精细的3D表示，该表示更准确地反映了物体的形状和结构。本发明相较于现有技术的主要改进在于，通过结合点云和图像数据，实现了更高效、更准确的3D表示生成。

**Key Innovation (核心创新)**:  
1. 结合3D点云和2D图像输入，通过互补数据源提高3D表示的准确性和效率。
2. 利用3D点云进行部件分割和位置/方向确定，生成包含各部件3D边界框的粗略表示。
3. 通过2D图像识别部件属性，例如类型、颜色和材料等，为精细化3D表示提供依据。
4. 基于识别出的属性和粗略表示，生成更精细的3D表示，例如用特定形状的部件替换边界框。
5. 采用几何形状而非直接依赖传感器数据生成3D表示，提升视觉外观的平滑性和准确性。
6. 该方法无需复杂的3D网格算法，计算成本较低，适用于实时应用场景。
7. 本发明可应用于增强现实中的虚拟物体放置、实时通信会话中的物体表示生成以及物体相似性搜索等领域，提供更准确和高效的3D表示。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478868128)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260134621)**
<br/><br/>

---


<br/>

### 11. 平面区域估计

**Title (EN)**: PLANE ESTIMATION  
**Pub. No.**: US20260134702

**Applicant**: Apple Inc.  
**Inventor**: [Seongdo Kim](https://patents.google.com/?inventor=Seongdo+Kim&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 14.05.2026

**Abstract**:  
一种系统或方法通过将平面区域与基于语义分割和法线方向信息识别的表面片段进行匹配来扩展平面区域。语义分割和法线方向信息可以通过对场景的一个或多个图像进行机器学习来确定。语义分割和法线方向信息被结合或以其他方式使用，以确定表面片段，例如，具有相似语义标签（例如地板、桌子、墙壁等）和相似法线方向的片段。然后将这些表面片段与初始平面区域进行匹配（例如，在3D空间中）。基于这种匹配，确定表面片段的部分或全部属于同一平面区域，从而可以用于扩展平面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478868218_1.jpg)

**Technical Field (技术领域)**:  
本专利属于计算机视觉领域，具体涉及基于场景理解的平面区域估计技术。

**Background (发明背景)**:  
现有技术使用基于图像的计算机视觉方法识别物理场景中的平面区域，例如SLAM技术通过匹配图像中的纹理或其他特征来提供3D点位置，并预测地板、桌面、墙壁和天花板等平面区域的位置。然而，由于SLAM预测的3D点位置较为稀疏，尤其是对于远离图像采集设备的平面区域部分，预测的平面区域通常不够完整或准确。现有的方法往往无法识别足够大的平面区域或其边界，或者需要从多个位置和角度获取图像。

**Summary (发明总览)**:  
本发明提出了一种扩展平面区域的方法，通过结合语义分割和法线方向信息来识别表面片段，并将其与SLAM等技术检测到的初始平面区域进行匹配，从而扩展平面区域。该方法还通过判断平面区域和表面片段的匹配情况，例如对齐、重叠或法线方向一致，来确定扩展的稳定性。此外，本发明还提出了一种基于垂直片段和水平平面边界构建垂直平面的方法。

**Key Innovation (核心创新)**:  
1. 通过结合语义分割和法线方向信息，识别具有一致语义标签和法线方向的表面片段，从而实现更准确的平面区域扩展。
2. 采用机器学习技术对图像进行语义分割和法线方向预测，提高了对复杂场景中平面区域的识别能力。
3. 通过将SLAM检测到的初始平面区域与表面片段进行3D空间匹配，解决了现有方法中平面区域不完整的问题。
4. 引入了稳定性判断机制，只有在确认扩展区域稳定后，才将其添加到平面区域中，提高了平面区域估计的可靠性。
5. 提出了一种基于垂直片段和水平平面边界构建垂直平面的方法，能够识别和构建新的垂直平面，例如墙壁。
6. 该技术可应用于增强现实、室内导航和场景重建等领域，通过提供更准确的平面区域信息，提升用户体验和应用效果。
7. 通过对多个图像进行综合分析，本发明能够处理动态场景中的平面区域变化，适应更复杂的实际应用环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478868218)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260134702)**
<br/><br/>

---


<br/>

### 12. 电子设备的视角不变边缘滤波

**Title (EN)**: View-invariant edge filtering for electronic devices  
**Pub. No.**: US12626457

**Applicant**: Apple Inc.  
**Inventor**: [James A. McCombe](https://patents.google.com/?inventor=James+A.+McCombe&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 12.05.2026

**Abstract**:  
本发明提供了一种视角不变边缘滤波技术。在一个或多个实现中，该技术可实现抗锯齿效果，有效减少或消除在不同显示配置下可见的锯齿现象，包括注视点渲染配置以及显示内容可在三维虚拟空间中移动和旋转的配置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478614565_1.jpg)

**Technical Field (技术领域)**:  
电子设备显示技术领域，具体涉及视角不变边缘滤波技术。

**Background (发明背景)**:  
电子设备通常使用显示像素阵列来呈现内容。当显示内容中的边界通过像素显示时，可能会出现视觉伪影，即锯齿现象，导致本应平滑的边界呈现为锯齿状或阶梯状。如果边界在显示时移动，这种锯齿现象还可能使用户感知到不期望的“爬行”伪影，因为边界移动时像素会随着开启或关闭。

**Summary (发明总览)**:  
本发明提出了一种视角不变边缘滤波技术，旨在解决显示内容边界锯齿和移动伪影问题。其核心思路是通过一种抗锯齿方法，在各种显示配置下保持边缘平滑。该技术特别适用于注视点渲染和三维虚拟空间中的动态显示内容。

**Key Innovation (核心创新)**:  
1. 采用视角不变滤波算法，在不同视角下保持边缘平滑，有效减少锯齿现象。
2. 通过动态调整滤波参数，适应注视点渲染配置，确保在注视点区域和非注视点区域均实现高质量边缘显示。
3. 实现三维虚拟空间中显示内容的实时边缘滤波，支持内容在三维空间中的移动和旋转。
4. 利用像素级边缘检测技术，精确识别需要滤波的边界区域，提高滤波效率。
5. 通过自适应滤波强度调节机制，根据显示内容运动速度动态调整滤波强度，减少运动伪影。
6. 该技术可应用于虚拟现实、增强现实设备以及高动态范围显示器，提升用户视觉体验。
7. 独特价值在于在复杂显示配置下提供一致且高质量的边缘显示效果，尤其适合需要高保真视觉效果的场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478614565)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12626457)**
<br/><br/>

---


<br/>

### 13. 使用填充掩码和合成表示的点云增强

**Title (EN)**: Point cloud enhancement using an infill mask and synthesized representation  
**Pub. No.**: US12626450

**Applicant**: Apple Inc.  
**Inventor**: [Magnus H Johnson](https://patents.google.com/?inventor=Magnus+H+Johnson&assignee=Apple&country=US&num=100&sort=new), [Eric Geusz](https://patents.google.com/?inventor=Eric+Geusz&assignee=Apple&country=US&num=100&sort=new), [Jeremy R Bernstein](https://patents.google.com/?inventor=Jeremy+R+Bernstein&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 12.05.2026

**Abstract**:  
本发明通过创建填充掩码和合成表示来对包含遮挡区域的点云进行填充，其中合成表示包含遮挡区域点的生成信息。填充掩码和合成表示均通过将3D点云光栅化生成2D版本，并分别使用第一和第二机器学习技术来生成。识别出的遮挡区域点将与合成表示中生成的信息匹配，并填充回点云中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-05/US478614557_1.jpg)

**Technical Field (技术领域)**:  
本专利属于三维点云处理领域，具体涉及点云增强和遮挡区域填充技术。

**Background (发明背景)**:  
三维传感器如LiDAR、3D相机和3D扫描仪可捕获空间点位置及其属性信息。然而，在某些情况下，传感器可能因遮挡而无法捕获某些区域的数据，导致点云数据不完整。现有的点云处理方法通常无法有效处理这些缺失数据，可能导致后续应用中的精度下降。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的点云增强方法，通过生成填充掩码和合成表示来填补点云中的遮挡区域。该方法首先将3D点云转换为2D表示，然后利用两种不同的机器学习算法分别生成填充掩码和合成表示。填充掩码用于识别遮挡区域，而合成表示则提供填充所需的信息，从而实现对点云的智能增强。

**Key Innovation (核心创新)**:  
1. 采用机器学习算法生成填充掩码，精准识别点云中的遮挡区域。
2. 利用第二机器学习算法生成合成表示，为遮挡区域提供可靠的生成信息。
3. 通过将3D点云转换为2D表示，降低计算复杂度并提高处理效率。
4. 填充过程基于合成表示中的信息，避免了随机填充带来的数据不准确问题。
5. 填充掩码和合成表示的结合使用，确保了填充点的位置和属性与原始点云的一致性。
6. 该方法可应用于编码器和解码器端，分别在编码前和重建时对点云进行增强。
7. 本发明可应用于自动驾驶、虚拟现实和3D重建等领域，提升点云数据的完整性和应用价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US478614557)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12626450)**
<br/><br/>

---



**Total Patents**: 13  
**Last Updated**: 20260516

---

The Patent Scoop Trio
