---
layout: post
title: "其他专利小快报 2026-04-04"
date: 2026-04-04 18:22:17 +0800
categories: 其他
---

**New Patents**: 29  

---


<br/>

### 1. 电子设备中用于检测手写笔的节能数字转换器激活方法

**Title (EN)**: POWER-EFFICIENT DIGITIZER ACTIVATION FOR STYLUS PEN DETECTION IN ELECTRONIC DEVICES  
**Pub. No.**: US20260093355

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Roei Shlomo MENASHOF](https://patents.google.com/?inventor=Roei+Shlomo+MENASHOF&country=US&num=100&sort=new), [Oren ISTRIN](https://patents.google.com/?inventor=Oren+ISTRIN&country=US&num=100&sort=new), [Nadav LINENBERG](https://patents.google.com/?inventor=Nadav+LINENBERG&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
计算设备可通过一个或多个静电天线执行节能搜索周期以检测电子手写笔设备。基于检测到触发事件，计算设备可停止执行节能搜索周期，并执行耗能更高的搜索周期以检测电子手写笔设备，其中耗能更高的搜索周期的能耗高于节能搜索周期的能耗。计算设备可在耗能更高的搜索周期中检测到电子手写笔设备后，与电子手写笔设备进行同步。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834855_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及电子设备中的数字转换器技术，具体为通过节能搜索周期和耗能搜索周期检测电子手写笔的方案。

**Background (发明背景)**:  
传统电子设备的数字转换器通常持续搜索活动手写笔设备以确保快速响应。然而，这种持续搜索方式会消耗大量电能，尤其对于不常使用手写笔的用户来说，会显著缩短设备电池寿命。现有技术无法有效平衡搜索响应速度和能耗问题。

**Summary (发明总览)**:  
本发明提出了一种基于触发事件切换搜索模式的手写笔检测方法。

1. 通过静电天线执行节能搜索周期以检测手写笔设备。
2. 当检测到触发事件时，停止节能搜索周期并切换到耗能更高的搜索周期。
3. 在耗能搜索周期中检测到手写笔后，与手写笔设备进行同步。

相较于传统持续耗能搜索方式，本发明通过触发事件驱动的搜索模式切换，显著降低了设备能耗，同时确保了手写笔检测的及时性。

**Key Innovation (核心创新)**:  
1. 引入节能搜索周期和耗能搜索周期两种模式，通过触发事件驱动模式切换，实现能耗优化。
   技术详解：节能搜索周期采用较长的搜索间隔和较少的搜索窗口，而耗能搜索周期则采用更密集的搜索模式。
   实现方式：基于检测到的触发事件动态调整搜索模式。
   功能：降低非活跃状态下的能耗，同时保证手写笔检测的及时性。
2. 触发事件包括手写笔静电信号检测、无线通信信道检测以及特定应用请求等。
   技术详解：例如，通过蓝牙或Wi-Fi检测到手写笔的标识符，或检测到手写笔的特定姿态或压力数据。
   实现方式：利用现有无线通信协议和传感器技术。
   功能：准确判断用户使用手写笔的意图，避免不必要的耗能搜索。
3. 节能搜索周期采用较长的搜索间隔和较少的搜索窗口。
   技术详解：例如，节能搜索周期中搜索窗口的数量和时间长度均少于耗能搜索周期。
   实现方式：通过调整搜索窗口的频率和持续时间优化能耗。
   功能：在不影响检测速度的前提下，最大限度降低非活跃状态下的能耗。
4. 耗能搜索周期采用更密集的搜索模式以快速检测手写笔。
   技术详解：例如，增加搜索窗口的数量和频率。
   实现方式：基于触发事件快速切换到高密度搜索模式。
   功能：确保在用户使用手写笔时能够及时检测到设备。
5. 触发事件可由用户行为或设备状态变化触发。
   技术详解：例如，用户打开特定应用或手写笔进入特定姿态。
   实现方式：通过传感器和软件逻辑判断用户意图。
   功能：提高搜索模式的响应速度和准确性。
6. 本发明适用于支持手写笔输入的电子设备，如平板电脑、智能手机等。
   功能：延长电池寿命，同时保证手写笔输入的流畅性和响应速度。
   独特价值：在不影响用户体验的前提下，显著降低设备能耗。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834855)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093355)**
<br/><br/>

---


<br/>

### 2. 通过用户与本地环境的交互来估算用户听力损失

**Title (EN)**: ESTIMATION OF HEARING LOSS OF A USER FROM INTERACTIONS WITH A LOCAL ENVIRONMENT BY THE USER IDENTIFIED FROM CAPTURED AUDIO AND INFORMATION DESCRIBING THE LOCAL AREA  
**Pub. No.**: US20260095710

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Christi Miller](https://patents.google.com/?inventor=Christi+Miller&country=US&num=100&sort=new), [Sara Ng](https://patents.google.com/?inventor=Sara+Ng&country=US&num=100&sort=new), [Calvin Murdock](https://patents.google.com/?inventor=Calvin+Murdock&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
音频系统包括一个或多个声学传感器，用于捕捉音频系统周围本地区域的音频，以及一个或多个附加传感器，用于捕捉描述本地区域的数据。音频系统中的音频控制器根据捕捉到的音频和描述本地区域的数据识别用户的交互。音频控制器确定与每个交互相关的属性，例如描述用户说话情况的指标、描述用户请求澄清的指标，以及基于从用户捕捉到的音频中确定的主题的指标。基于交互及其相关属性，音频控制器为用户估算一个声音配置文件，该配置文件识别用户听力损失的频率范围。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476837467_1.jpg)

**Technical Field (技术领域)**:  
听力损失补偿技术领域，具体涉及通过用户与环境的交互自动估算听力损失并提供补偿。

**Background (发明背景)**:  
目前，轻度至中度听力损失影响了许多人，但传统的听力损失诊断需要患者前往临床机构进行听力测试和问卷调查。这种方法耗时且数据有限，难以全面评估用户的实际听力功能，从而限制了听力损失的准确估算和补偿效果。

**Summary (发明总览)**:  
本发明提出了一种通过分析用户与本地环境的交互来估算用户听力损失的方法。系统通过声学传感器和附加传感器捕捉音频和本地环境数据，识别用户的交互行为并分析相关属性。基于这些数据，系统应用训练模型估算用户的听力损失情况，并生成个性化的声音配置文件。进一步地，系统可利用该配置文件调整音频输出，补偿用户的听力损失，从而提高用户的听觉体验。

**Key Innovation (核心创新)**:  
1. 通过声学传感器捕捉本地音频并结合附加传感器数据（如视频、位置信息），实现对用户交互行为的全面识别，例如用户的动作、语音和反应。
2. 利用多模态数据（音频、视频、用户生物特征等）分析用户与环境的交互，提取与听力相关的关键属性，如语音请求频率、靠近声源的动作等。
3. 应用机器学习模型处理交互数据和环境属性，生成个性化的用户声音配置文件，精确识别不同频率范围的听力损失情况。
4. 创新性地将眼动追踪和面部表情信息纳入分析，通过用户对声音的反应（如转头、注视）进一步优化听力损失估算的准确性。
5. 基于估算的声音配置文件，系统动态调整音频输出，通过频率补偿和音量调节生成增强音频，提升用户对音频内容的理解能力。
6. 耳机集成化设计，将传感器、音频处理和补偿功能集成到单一设备中，实现实时听力损失补偿和个性化音频体验。
7. 本发明可应用于智能耳机、虚拟现实和增强现实设备，为用户提供个性化的听力补偿方案，尤其适用于需要频繁与环境交互的场景，如会议、导航和娱乐。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476837467)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260095710)**
<br/><br/>

---


<br/>

### 3. 人工智能系统中用户状态的检测

**Title (EN)**: DETECTION OF USER STATE IN ARTIFICIAL INTELLIGENCE SYSTEMS  
**Pub. No.**: US20260093371

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Edwin James GALE](https://patents.google.com/?inventor=Edwin+James+GALE&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
人工智能（AI）模型的响应基于用户的情感状态生成。在接收到用户输入后，对用户输入的内容进行分析并确定用户的情感状态。使用双重模型比较分析情感状态，并根据确定的情感状态生成响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834872_1.jpg)

**Technical Field (技术领域)**:  
人工智能技术领域，具体涉及情感识别与用户状态检测。

**Background (发明背景)**:  
现有的计算系统提供交互和协作环境以促进用户之间的通信。许多应用根据用户的情感状态提供个性化功能，但情感状态检测不准确会降低应用的有效性和准确性。现有的情感模型在提供特定情境的情感标签和捕捉情感体验的细微差别方面存在不足，这阻碍了情感智能AI系统的发展。

**Summary (发明总览)**:  
本发明提出了一种基于双重模型比较的情感状态检测方法，通过结合情感的四因素（效价、强度、控制和情境）生成具体的情感标签。该方法简化了情感维度以提高计算效率，并利用结构化的双重模型框架更准确地捕捉情感背后的认知评估过程。本发明相较于现有技术的主要改进在于提供了更精确的情感理解和更高效的计算实现路径。

**Key Innovation (核心创新)**:  
1. 采用双重模型比较框架，通过对比过去与现在、自我与他人、期望与现实等维度，更准确地捕捉情感背后的认知评估过程。
实现方式：通过将情感映射到这些对比维度上，结合情感的四因素（效价、强度、控制和情境）进行分析。
功能或解决的问题：解决了现有情感模型无法准确描述情感细微差别的不足，提高了情感识别的准确性。
2. 结合四因素（效价、强度、控制和情境）对情感进行分类和描述。
实现方式：将情感的四因素简化为二元或三点量表，降低计算资源需求。
功能或解决的问题：提高了情感分类的计算效率，同时保持了情感描述的准确性。
3. 引入了子维度和内外表达因素，进一步细化情感状态的描述。
实现方式：通过子维度捕捉情感的细微差别，并通过内外表达因素区分内部感受和外部表达。
功能或解决的问题：使AI系统能够更细致地理解用户的情感状态，从而提供更人性化的交互体验。
4. 将情感标签生成与自然语言处理（NLP）技术结合，应用于AI系统。
实现方式：利用NLP算法（如情感分析、文本分类等）分析用户输入，并生成相应的情感标签。
功能或解决的问题：使AI系统能够根据用户的情感状态生成更合适的响应，提高用户交互的质量。
5. 采用多模态生成模型，结合文本、图像、音频等多种输入模式进行情感分析。
实现方式：利用多模态模型处理不同类型的输入数据，并生成综合的情感分析结果。
功能或解决的问题：提高了情感识别的全面性和准确性，适用于更复杂的应用场景。
6. 应用于虚拟助手等AI系统，提供更精准的情感识别和响应。
实现方式：通过集成情感检测模块，使虚拟助手能够根据用户的情感状态调整交互方式。
功能或解决的问题：提高了虚拟助手的人性化程度，增强了用户的信任感和满意度。
7. 降低情感识别的计算资源消耗，提高情感分类的效率。
实现方式：通过简化情感维度和采用高效的计算方法，减少情感分类所需的计算资源。
功能或解决的问题：使情感识别技术能够更广泛地应用于资源受限的设备，如移动设备和物联网设备。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834872)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093371)**
<br/><br/>

---


<br/>

### 4. 用于控制联网设备的复合图形助手界面的方法、系统和装置

**Title (EN)**: METHODS, SYSTEMS, AND APPARATUS FOR PROVIDING COMPOSITE GRAPHICAL ASSISTANT INTERFACES FOR CONTROLLING CONNECTED DEVICES  
**Pub. No.**: US20260093450

**Applicant**: GOOGLE LLC  
**Inventor**: [David Roy Schairer](https://patents.google.com/?inventor=David+Roy+Schairer&country=US&num=100&sort=new), [Triona Butler](https://patents.google.com/?inventor=Triona+Butler&country=US&num=100&sort=new), [Cindy Tran](https://patents.google.com/?inventor=Cindy+Tran&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明提供了一种用于定制复合图形助手界面的方法、装置、系统及计算机可读介质，以实现与多个不同联网设备的交互。当用户请求自动化助手执行联网设备的特定功能时，自动化助手会生成复合图形助手界面。该界面通过识别联网设备的其他功能，并将这些功能映射到各种图形控制元素上，为用户提供一个综合界面来控制设备。每个图形控制元素根据功能特点进行排列。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834960_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及物联网设备控制与图形用户界面设计。

**Background (发明背景)**:  
随着物联网设备的普及，用户需要安装多个第三方应用程序来控制不同设备，这导致设备内存和网络带宽的浪费。此外，通过语音命令控制设备时，环境噪声可能影响语音识别准确性，导致资源浪费。本发明旨在解决用户需要管理多个应用以及语音控制效率低下的问题。

**Summary (发明总览)**:  
本发明提出了一种通过自动化助手生成复合图形界面来控制联网设备的方法。用户通过语音命令请求控制设备后，自动化助手会生成一个综合界面，整合设备的多种控制功能。该界面通过选择合适的图形控制元素（如开关、颜色选择器和旋钮）来匹配设备的功能，从而提供直观的操作方式。这种方法减少了用户对多个应用程序的依赖，并提高了网络和计算资源的利用效率。

**Key Innovation (核心创新)**:  
1. 通过自动化助手生成复合图形界面，整合多个联网设备的控制功能，实现用户对设备的统一管理。
实现方式：识别用户语音命令中的设备类型和功能，映射到相应的图形控制元素上。
功能或解决的问题：减少用户对多个应用程序的依赖，提高设备控制效率。
2. 根据设备功能选择合适的图形控制元素，如开关、颜色选择器和旋钮，以提供直观的操作界面。
实现方式：根据设备的功能参数（如开关状态、颜色值和亮度值）选择对应的图形元素。
功能或解决的问题：提供用户友好的界面，降低学习成本。
3. 在用户发出语音命令后，自动化助手会更新图形界面以反映设备的当前状态。
实现方式：接收语音命令后，从设备获取状态信息并更新界面上的图形元素。
功能或解决的问题：使用户能够实时了解设备状态，提高交互效率。
4. 通过减少对远程服务器的依赖，节省网络带宽。
实现方式：在本地处理语音命令并生成图形界面，只有必要时才与设备通信。
功能或解决的问题：降低网络资源消耗，提高响应速度。
5. 提供更高效的设备功能调整方式，例如通过图形界面进行精细控制。
实现方式：对于需要精确调整的功能（如亮度或温度），使用滑块或旋钮等图形元素。
功能或解决的问题：提高用户对设备功能的控制精度，减少误操作。
6. 增强用户对设备功能的发现性，通过图形界面展示更多控制选项。
实现方式：在界面上展示设备的多种功能选项，并根据用户交互动态调整显示内容。
功能或解决的问题：使用户能够更全面地了解和控制设备功能。
7. 推测应用场景：智能家居环境中的多设备控制，例如智能灯光、温控器和家用电器。
独特价值：提供统一的控制界面，简化用户操作流程，提升智能家居的整体用户体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834960)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093450)**
<br/><br/>

---


<br/>

### 5. 系统深度空闲期间功率和温度波动的协同优化系统与方法

**Title (EN)**: System And Method For Co-Optimizing Power And Temperature Fluctuation During System Deep Idle  
**Pub. No.**: US20260093531

**Applicant**: Google LLC  
**Inventor**: [Houle Gan](https://patents.google.com/?inventor=Houle+Gan&country=US&num=100&sort=new), [Parthasarathy Ranganathan](https://patents.google.com/?inventor=Parthasarathy+Ranganathan&country=US&num=100&sort=new), [Rammohan Padmanabhan](https://patents.google.com/?inventor=Rammohan+Padmanabhan&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明公开了一种通过控制服务器机器的功耗水平、xPU温度变化以及作业启动延迟来缓解由频繁芯片温度波动引起的硬件退化的方法。根据一些实施例，功率和温度优化系统可以监控由xPU深度空闲状态引起的作业间波动导致的xPU温度波动。xPU的深度空闲状态是指当分配给xPU的作业或工作单元停止时，xPU关闭或降低其组件电压以节省功率的状态。xPU的深度空闲状态将持续到下一个作业或工作单元开始。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476835049_1.jpg)

**Technical Field (技术领域)**:  
服务器系统优化；
人工智能/机器学习硬件管理；
温度与功耗协同控制技术

**Background (发明背景)**:  
随着人工智能和机器学习应用的增加，数据中心服务器面临频繁的工作负载波动，这导致芯片温度频繁变化。
这种温度波动会加速热界面材料（TIM）的退化，影响电子组件的可靠性和寿命。
现有技术主要通过增加额外功率或简单调节冷却设备来缓解温度波动，但这些方法效率低下且能耗较高。
本发明旨在提供一种更高效的解决方案，通过协同控制功耗、温度和作业延迟来减少硬件退化。

**Summary (发明总览)**:  
本发明提出了一种通过动态协同控制服务器系统的功耗、温度和作业延迟来优化服务器硬件稳定性的方法。
其核心思路是在作业切换期间，通过减少功率供应、调整冷却速率和延迟作业启动时间来实现温度的平稳过渡。
该方法利用动态电压和频率缩放（DVFS）技术以及智能调度机制来优化功耗和温度管理。
相较于传统方法，本发明通过减少不必要的功率消耗和避免温度剧烈波动，延长了硬件寿命并提高了系统可靠性。

**Key Innovation (核心创新)**:  
1. 通过检测作业结束信号并采用分阶段动态电压和频率缩放（DVFS）技术，逐步减少服务器系统的功率供应，从而避免温度急剧下降。
实现方式：利用DVFS技术动态调整处理器的工作电压和频率。
功能：减少功耗波动对温度的影响。
2. 通过控制冷却设备（如风扇或流体阀门）的冷却速率，在功率需求下降时防止xPU温度快速下降。
实现方式：使用智能阀门控制和风扇速度调节机制。
功能：维持温度稳定，减少TIM材料因温度波动造成的退化。
3. 采用机器学习模型优化功耗、温度和作业延迟的协同控制策略。
实现方式：使用度量函数表示功耗减少量、延迟变化和冷却速率，并利用机器学习模型进行优化。
功能：实现更精准的温度和功耗平衡。
4. 通过延迟当前作业或下一个计划作业的启动时间，进一步控制温度波动。
实现方式：使用智能调度器延迟作业加载时间。
功能：避免作业启动时的温度骤变。
5. 在作业间主动增加功率消耗（"填充功率"），以维持xPU温度的相对恒定。
实现方式：通过启动非真实作业、解锁xPU时钟树或插入指令到xPU流水线中。
功能：减少温度波动对硬件的影响。
6. 系统包含执行器，用于控制冷却阀门和调整作业延迟时间。
实现方式：集成执行器与控制算法协同工作。
功能：实现对硬件设备的精确控制。
7. 本发明可应用于数据中心和高性能计算环境，通过减少硬件退化提高系统可靠性和寿命。
独特价值：在人工智能和机器学习工作负载频繁波动的场景下，提供了一种高效且节能的硬件保护方案。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476835049)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093531)**
<br/><br/>

---


<br/>

### 6. 机器学习模型的稀疏激活感知权重加载与推理

**Title (EN)**: SPARSE ACTIVATION-AWARE WEIGHT LOADING AND INFERENCE FOR MACHINE LEARNING MODELS  
**Pub. No.**: US20260093965

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Mahdi Heydari](https://patents.google.com/?inventor=Mahdi+Heydari&country=US&num=100&sort=new), [Sankalp Dayal](https://patents.google.com/?inventor=Sankalp+Dayal&country=US&num=100&sort=new), [Abhishek Sahadev Sutar](https://patents.google.com/?inventor=Abhishek+Sahadev+Sutar&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明描述了用于机器学习模型的稀疏激活感知权重加载和推理的设备和相关技术。在一些示例中，首先为输入数据生成第一激活张量，并为其生成第一稀疏性映射图，该映射图指示第一激活张量中零值和非零值的位置。随后识别与第一稀疏性映射图中非零值对应的权重张量的第一组通道，并将该组通道加载到内存中。机器学习模型基于第一组通道和第一激活张量生成输出数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476835528_1.jpg)

**Technical Field (技术领域)**:  
机器学习模型优化；稀疏张量计算；硬件加速技术

**Background (发明背景)**:  
机器学习技术被广泛应用于预测、问题解决和图像数据中的对象识别等领域。然而，现有技术中，机器学习模型的计算和内存需求较高，尤其在处理包含大量参数的大型模型时存在瓶颈。尽管已有一些技术利用权重张量的静态稀疏性来优化计算，但激活张量的动态稀疏性尚未得到充分利用。本发明旨在解决这一问题，通过利用激活张量的动态稀疏性来减少计算操作、降低延迟、减少功耗并提高吞吐量。

**Summary (发明总览)**:  
本发明提出了一种利用激活张量动态稀疏性的技术，通过生成稀疏性映射图来识别激活张量中的非零值位置，并仅加载与这些非零值相关的权重张量通道，从而减少内存占用和计算量。该方法通过减少不必要的计算操作和内存访问来提高机器学习模型的推理效率，尤其适用于具有动态稀疏性的大型模型，如大语言模型（LLMs）。本发明通过硬件和软件协同优化，实现了更高效的模型推理。

**Key Innovation (核心创新)**:  
1. 稀疏性映射图生成技术：
通过为激活张量生成稀疏性映射图，精确识别张量中的零值和非零值位置，从而为后续的权重加载提供依据。
2. 动态权重加载机制：
仅加载与激活张量中非零值对应的权重张量通道，减少内存占用和计算量，实现对动态稀疏性的有效利用。
3. 硬件加速优化：
结合硬件加速器（如GPU、NPU）实现稀疏性感知计算，通过并行处理和内存优化进一步提升计算效率。
4. 减少计算操作：
由于零值与任何数相乘结果为零，本发明通过跳过这些无效计算操作，显著减少了需要执行的计算量。
5. 内存访问优化：
通过减少需要加载的权重数据量，降低内存带宽需求，缓解内存瓶颈问题，尤其适用于内存受限的设备。
6. 适用于大型模型：
本发明特别适用于参数规模庞大的机器学习模型（如LLMs），通过减少计算和内存需求，提升模型推理的可行性和效率。
7. 应用场景与价值：
本发明可应用于需要高效推理的领域，如实时图像识别、自然语言处理等，为资源受限环境下的机器学习应用提供支持。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476835528)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093965)**
<br/><br/>

---


<br/>

### 7. 不可听见的正交信号通信

**Title (EN)**: INAUDIBLE ORTHOGONAL SIGNAL COMMUNICATION  
**Pub. No.**: US20260095258

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Syed Abdullah Nauroze](https://patents.google.com/?inventor=Syed+Abdullah+Nauroze&country=US&num=100&sort=new), [Eugene Ren](https://patents.google.com/?inventor=Eugene+Ren&country=US&num=100&sort=new), [Guangji Shi](https://patents.google.com/?inventor=Guangji+Shi&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明涉及不可听见的正交信号通信方法。该方法包括基于输入消息确定一系列符号，每个符号代表一个数值，且每个符号对应一个与其他符号正交的带限白噪声音调。该方法还包括生成包含这些符号的子令牌，其中每个符号在时间上与其他至少一个符号重叠。通过使用扩频技术对载波波进行调制以产生信号音频波形，并提供该信号音频。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476836963_1.jpg)

**Technical Field (技术领域)**:  
本发明属于音频信号处理领域，具体涉及不可听见的正交信号通信技术。

**Background (发明背景)**:  
声音波可以通过各种调制技术传输信息，例如过去的声学调制解调器将数字数据转换为可听声音通过电话线传输，并在接收端解调回数字数据。然而，现有技术面临诸多挑战，例如人耳对特定频率范围的高灵敏度、设备的频率响应差异以及信号传输中的多路径效应等。

**Summary (发明总览)**:  
本发明提出了一种不可听见的正交信号通信方法，通过在可听频率范围内使用带限白噪声音调进行信号传输。这些音调彼此正交，并采用扩频技术进行调制，以实现信号的不可听性和抗干扰性。该方法能够在不影响用户体验的前提下，实现高效且可靠的信号传输，适用于多种设备，包括电视等消费电子产品。

**Key Innovation (核心创新)**:  
1. 采用带限白噪声音调作为信号载体，通过正交特性确保每个音调之间互不干扰，从而实现信号的不可听性和抗干扰性。
2. 使用扩频技术对载波波进行调制，使得信号在频域上分散，降低人耳对信号的感知，同时提高信号的鲁棒性。
3. 设计了一种时间重叠的子令牌结构，使得多个符号在时间上共享传输时段，从而提高信号传输效率。
4. 通过优化信号幅度和频率范围，确保信号在可听频率范围内保持不可听性，同时适应不同设备的频率响应特性。
5. 引入多路径效应补偿机制，通过信号处理算法减少环境对信号传输的影响，提高信号接收的可靠性。
6. 针对不同设备（如电视）的频率响应特性进行优化，确保信号在主流消费电子产品上具有广泛的适用性和可检测性。
7. 本发明可应用于广告、互动电视等领域，通过不可听见的信号传输实现用户与设备之间的互动，同时不影响用户的听觉体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476836963)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260095258)**
<br/><br/>

---


<br/>

### 8. 可变形冷板

**Title (EN)**: Conformable Cold Plates  
**Pub. No.**: US20260096057

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Oscar Farias MOGUEL](https://patents.google.com/?inventor=Oscar+Farias+MOGUEL&country=US&num=100&sort=new), [Dennis TRIEU](https://patents.google.com/?inventor=Dennis+TRIEU&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明涉及用于冷却计算机芯片的冷板组件。一个示例包括一个歧管和一个可变形冷板，可变形冷板与歧管相接以形成流体通道。当暴露于流体通道中的流体压力时，可变形冷板能够根据与其接触的计算机芯片的形状进行变形。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476837850_1.jpg)

**Technical Field (技术领域)**:  
本专利属于计算机芯片冷却技术领域，具体涉及液体冷却中的可变形冷板技术。

**Background (发明背景)**:  
随着计算性能的提升，计算机芯片（如CPU、GPU等）产生的热量显著增加，传统的气冷方式已无法满足散热需求。
液体冷却通过冷板组件实现，但传统冷板刚性较强，难以适应芯片在运行过程中因温度变化导致的形状变化。
这种不匹配会导致散热效率降低，可能损坏芯片或迫使芯片降频运行以避免过热。

**Summary (发明总览)**:  
本发明提出了一种可变形冷板技术，通过设计一种能够根据芯片形状变化的柔性冷板来提高散热效率。
该冷板在流体压力作用下能够与芯片表面紧密贴合，从而在芯片运行过程中保持稳定的热传导性能。
相较于传统刚性冷板，本发明解决了因芯片形变导致的散热效率下降问题，提升了芯片性能和系统可靠性。

**Key Innovation (核心创新)**:  
1. 采用可变形冷板设计，通过柔性材料制造冷板，使其能够根据芯片的形状变化进行自适应调整。
   实现方式：利用流体压力使冷板发生形变，从而与芯片表面紧密贴合。
   功能：解决了传统刚性冷板与芯片形变不匹配的问题，提高了热传导效率。
2. 在冷板与歧管之间形成流体通道，通过流体循环带走芯片产生的热量。
   实现方式：冷板与歧管密封连接，形成封闭的流体通道。
   功能：确保冷却液能够有效循环，带走芯片产生的热量。
3. 冷板设计考虑了不同尺寸芯片的形变特性，通过调整冷板的柔性和厚度来适应不同芯片。
   实现方式：根据芯片尺寸和形变特性优化冷板的材料选择和结构设计。
   功能：确保冷板在不同尺寸芯片上均能保持良好的热传导性能。
4. 通过流体压力控制冷板的变形程度，实现对冷板与芯片接触压力的精确调节。
   实现方式：调整流体的流速和压力来控制冷板的变形程度。
   功能：确保冷板与芯片表面接触良好，同时避免因压力过大导致芯片损坏。
5. 冷板材料选择具有高导热性和耐腐蚀性的合金，以提高散热效率和延长使用寿命。
   实现方式：选用导热系数高且耐腐蚀的合金材料制造冷板。
   功能：确保冷板在长期使用过程中保持良好的散热性能和机械强度。
6. 冷板设计适用于多种计算机芯片，包括CPU、GPU和内存等。
   实现方式：采用模块化设计，使冷板能够适应不同类型的芯片。
   功能：扩展了冷板的应用范围，使其能够满足多种计算组件的散热需求。
7. 本发明可应用于高性能计算服务器和数据中心等场景，提供高效的芯片散热解决方案。
   功能：解决了高性能计算环境中芯片散热难题，提高了系统的稳定性和可靠性。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476837850)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260096057)**
<br/><br/>

---


<br/>

### 9. 激光投影设备及相关方法

**Title (EN)**: LASER PROJECTION DEVICES AND RELATED METHODS  
**Pub. No.**: US20260093126

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Zhuoliang Ni](https://patents.google.com/?inventor=Zhuoliang+Ni&country=US&num=100&sort=new), [Wai Sze Tiffany Lam](https://patents.google.com/?inventor=Wai+Sze+Tiffany+Lam&country=US&num=100&sort=new), [Wanli Chi](https://patents.google.com/?inventor=Wanli+Chi&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
一种显示系统包括具有带宽（Δλ）的窄带光源、与光源光学耦合的照明模块、用于被照明模块照明的空间光调制器，以及配置为大致准直从空间光调制器接收的光的投影系统，其中照明模块包括二维扩散元件阵列，光源的相干长度（λ2/Δλ）小于光源到第一扩散元件的光程与光源到第二扩散元件的光程之差。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834601_1.jpg)

**Technical Field (技术领域)**:  
激光投影技术领域，具体涉及光学系统设计和光源照明技术。

**Background (发明背景)**:  
传统激光投影系统常面临光源相干性引起的散斑问题，影响显示质量。
现有技术通常采用机械振动或复杂光学元件来减少散斑，但增加了系统复杂性和成本。
本发明旨在提供一种更简单且有效的解决方案，以减少散斑并提高图像质量。

**Summary (发明总览)**:  
本发明提出了一种基于非相干光源照明和二维扩散元件阵列的激光投影系统。
通过控制光源的相干长度，使其小于不同扩散元件之间的光程差，从而减少散斑。
该系统利用光学路径差来破坏光源的相干性，实现更均匀的照明效果。
相较于传统方法，本发明简化了系统结构并降低了成本，同时保持了高图像质量。

**Key Innovation (核心创新)**:  
1. 采用二维扩散元件阵列，通过控制光源的相干长度（λ2/Δλ）小于不同扩散元件之间的光程差，实现光源的非相干化。
技术细节：利用光学路径差破坏光源的相干性，减少散斑现象。
功能：提供更均匀的照明效果，提升图像质量。
2. 设计了一种光学系统，使光源的相干长度与扩散元件之间的光程差精确匹配。
实现方式：通过精确计算和调整光学路径长度，确保光源的非相干性。
功能：优化照明均匀性，减少系统复杂性。
3. 照明模块中集成了多个扩散元件，形成二维阵列结构。
技术细节：通过阵列化设计，增加光线的多样性，进一步降低散斑。
功能：增强照明均匀性，提高显示系统的整体性能。
4. 投影系统配置为大致准直从空间光调制器接收的光。
实现方式：使用光学准直元件对调制后的光进行准直处理。
功能：确保投影图像的清晰度和一致性。
5. 系统结构简化，减少了对机械振动或复杂光学元件的依赖。
技术细节：通过非相干光源和扩散元件阵列的组合，替代传统散斑消除方法。
功能：降低系统成本和复杂性，同时保持高质量显示效果。
6. 适用于高分辨率激光投影系统，可应用于家庭影院、会议室投影等场景。
应用场景：提供高清晰度、低散斑的投影解决方案。
独特价值：在保证图像质量的同时，提升用户体验并降低维护成本。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834601)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093126)**
<br/><br/>

---


<br/>

### 10. 检测电子设备充电接口的软短路

**Title (EN)**: Detecting a Soft Short Circuit at a Charging Interface of an Electronic Device  
**Pub. No.**: US20260093306

**Applicant**: Google LLC  
**Inventor**: [Ajmal Godil](https://patents.google.com/?inventor=Ajmal+Godil&country=US&num=100&sort=new), [Conrad Smith](https://patents.google.com/?inventor=Conrad+Smith&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
提供了一种用于检测电子设备充电接口软短路的方法。该方法包括获取与电子设备充电接口电连接的电压参考的初始电压测量值，获取电压参考的多个额外电压测量值，基于初始电压测量值和最接近当前时间的电压测量值检测充电接口的软短路，并在检测到软短路时使电子设备执行一个或多个控制动作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834801_1.jpg)

**Technical Field (技术领域)**:  
电子设备充电管理技术领域，具体涉及充电接口软短路检测。

**Background (发明背景)**:  
电子设备通常配备可充电电池，通过充电接口连接外部电源进行充电。
充电接口可能因进水或内部元件故障等原因形成软短路，导致设备异常发热或损坏。
现有技术缺乏有效检测软短路的方法，无法及时发现潜在安全隐患。
本发明旨在提供一种检测充电接口软短路的方法，以提升设备安全性。

**Summary (发明总览)**:  
本发明提出了一种通过电压测量检测电子设备充电接口软短路的方法。
核心思路是定期监测充电接口电压参考值的变化，通过比较初始电压和后续测量值判断是否存在软短路。
当检测到电压下降超过设定阈值时，判定为软短路并触发相应控制措施，如自动关机或提示用户进行维护。
相较于现有技术，本发明提供了一种主动检测机制，能够在软短路导致严重问题前预警并采取保护措施。

**Key Innovation (核心创新)**:  
1. 通过电压参考值的变化检测软短路：
   技术详解：利用初始电压测量值作为基准，定期获取额外电压测量值，通过比较两者差异判断是否存在软短路。
   实现方式：处理器获取电压参考值并与预设阈值比较。
   功能或解决的问题：能够及时发现软短路，避免设备异常发热或损坏。
2. 设置电压下降阈值以提高检测准确性：
   技术详解：设定电压下降的最小阈值（如至少0.5伏），只有当电压下降超过该值时才判定为软短路。
   实现方式：处理器根据预设阈值进行判断。
   功能或解决的问题：减少误报，提高检测准确性。
3. 在非充电状态下进行电压测量：
   技术详解：在设备未通过外部电源充电时获取电压测量值，避免充电电流对测量结果的影响。
   实现方式：处理器在设备未连接外部电源时进行电压测量。
   功能或解决的问题：确保测量结果的准确性，提高检测可靠性。
4. 存储电压测量值以实现持续监测：
   技术详解：将初始电压测量值和额外电压测量值存储在内存中，以便进行持续监测和历史数据比较。
   实现方式：处理器将电压测量值写入内存的不同位置或覆盖旧数据。
   功能或解决的问题：实现对软短路的持续监测和趋势分析。
5. 自动关机作为保护措施：
   技术详解：当检测到软短路时，自动关闭设备以防止进一步损坏。
   实现方式：处理器触发关机指令。
   功能或解决的问题：保护设备免受软短路引起的潜在损害。
6. 提示用户进行维护：
   技术详解：当检测到软短路时，通过显示屏提示用户进行维护操作，如手动关机。
   实现方式：处理器控制显示屏显示通知信息。
   功能或解决的问题：提醒用户采取必要措施，提高设备安全性。
7. 应用于可穿戴设备等小型电子设备：
   技术详解：将软短路检测方法应用于可穿戴设备等小型电子设备，利用其充电接口进行电压测量。
   实现方式：在小型电子设备的充电接口处集成电压参考和检测电路。
   功能或解决的问题：提升小型电子设备的安全性，延长设备使用寿命。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834801)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093306)**
<br/><br/>

---


<br/>

### 11. 移动车辆中设备的运动跟踪

**Title (EN)**: MOTION TRACKING FOR DEVICES ON MOVING VEHICLES  
**Pub. No.**: US20260093115

**Applicant**: Google LLC  
**Inventor**: [Chao Guo](https://patents.google.com/?inventor=Chao+Guo&country=US&num=100&sort=new), [Qiyue Zhang](https://patents.google.com/?inventor=Qiyue+Zhang&country=US&num=100&sort=new), [Jiunn-Kai Huang](https://patents.google.com/?inventor=Jiunn-Kai+Huang&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明描述了一种技术，通过接收来自与扩展现实设备相连的第一传感器信号，以及来自与扩展现实设备通信且位于同一移动参考系中的图像传感器的第二传感器信号，来确定扩展现实设备相对于移动参考系的运动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834589_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及扩展现实设备运动跟踪技术，具体为在移动参考系（如车辆）中的运动跟踪。

**Background (发明背景)**:  
现有的运动跟踪技术，如使用惯性测量单元（IMU）或视觉惯性里程计（VIO），在移动参考系中容易受到外部运动干扰，导致跟踪不准确。例如，在行驶的车辆中使用XR设备时，设备传感器会同时检测到用户头部运动和车辆运动，导致跟踪结果失真。此外，车辆运动还会加剧VR环境中的晕动症问题。本发明旨在解决在移动参考系中实现精确运动跟踪的技术难题。

**Summary (发明总览)**:  
本发明提出了一种在移动参考系中实现精确运动跟踪的方法，通过结合使用位于同一移动参考系中的两个设备来分离目标运动与外部运动。具体实现方式包括使用一个固定在移动参考系中的设备（如车辆上的摄像头）来捕捉外部环境数据，并与被跟踪设备（如XR设备）的传感器数据结合，以消除外部运动对跟踪结果的影响。该方法能够提供更准确的运动跟踪，并减少因车辆运动引起的晕动症问题。

**Key Innovation (核心创新)**:  
1. 通过结合使用固定在移动参考系中的第二设备（如车辆上的摄像头）和被跟踪设备（如XR设备）的传感器数据，实现对外部运动（如车辆运动）的分离，从而提高运动跟踪的准确性。
2. 利用第二设备的图像传感器捕捉外部环境图像数据，并将其与被跟踪设备的运动传感器数据结合，以消除移动参考系对跟踪结果的干扰。
3. 在第二设备中集成一个指向移动参考系外部（如车窗外）的图像传感器，通过捕捉外部环境的图像数据，提供一个稳定的参考系，用于校正被跟踪设备的运动数据。
4. 通过在被跟踪设备和第二设备之间建立共同的地标或地图（如车辆内部地图），实现对共同运动信号的提取和分离，从而获得被跟踪设备相对于移动参考系的精确运动数据。
5. 在一些实施例中，第二设备可以是另一个XR设备，通过无线通信与被跟踪设备共享图像数据，共同构建一个虚拟的静止参考系，用于精确跟踪被跟踪设备的运动。
6. 通过将被跟踪设备的IMU数据与第二设备的IMU数据结合，并考虑传感器偏差和噪声的影响，动态估计并去除车辆运动对跟踪结果的影响。
7. 本发明可应用于车辆中的XR设备（如HMD），通过提供精确的运动跟踪和减少晕动症，提升用户在移动环境中的XR体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834589)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093115)**
<br/><br/>

---


<br/>

### 12. 通用追踪模块

**Title (EN)**: Universal Tracking Module  
**Pub. No.**: US20260094284

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jason Andrew HIGGINS](https://patents.google.com/?inventor=Jason+Andrew+HIGGINS&country=US&num=100&sort=new), [Lorenz Henric JENTZ](https://patents.google.com/?inventor=Lorenz+Henric+JENTZ&country=US&num=100&sort=new), [Nicholas Friele EVERIST](https://patents.google.com/?inventor=Nicholas+Friele+EVERIST&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明涉及一种能够进行六自由度追踪的通用追踪模块（UTM）。在人工现实环境中，六自由度追踪指的是追踪物体在三维空间中沿三个移动轴和三个旋转轴自由移动和旋转的能力。六自由度追踪提供了在3D空间中追踪移动和旋转的高精度，使得虚拟和增强现实环境中的物体和交互能够更准确和真实地呈现，从而提供更逼真和沉浸式的体验。在一些示例中，UTM包括多个发光二极管（LED），通过捕捉UTM的图像可以确定其位置和方向。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476835882_1.jpg)

**Technical Field (技术领域)**:  
本专利属于人工现实技术领域，具体涉及六自由度追踪技术。

**Background (发明背景)**:  
六自由度追踪是一种用于准确测量物体在三维空间中移动和旋转的方法。现有技术中，追踪系统通常需要大量计算资源，且难以在计算资源受限的设备中实现。此外，现有系统通常只能追踪特定设备或物体，无法为任意物体提供六自由度追踪功能。本发明旨在提供一种通用追踪模块，以解决上述问题。

**Summary (发明总览)**:  
本发明提出了一种通用追踪模块（UTM），能够为任意物体提供六自由度追踪功能。UTM通过内置的LED和IMU传感器，结合头戴式显示器（HMD）中的图像处理和机器学习算法，实现对物体位置、方向和位置的精确追踪。该模块采用Inside-Out追踪技术，利用内部成像设备和计算机视觉算法确定自身在三维空间中的位置和方向。相较于现有技术，本发明无需依赖外部摄像头或传感器，且适用于计算资源受限的设备。

**Key Innovation (核心创新)**:  
1. 采用通用设计，UTM可附着于任意物体，通过内置LED和IMU传感器提供六自由度追踪功能，解决了现有系统无法为任意物体提供追踪的问题。
2. 利用Inside-Out追踪技术，UTM通过内部成像设备和计算机视觉算法确定自身位置和方向，无需依赖外部摄像头或传感器，降低了对外部设备的依赖。
3. 结合HMD的图像处理和机器学习算法，UTM能够精确识别LED位置并匹配UTM的LED模式，从而实现高精度的位置和方向追踪。
4. 通过IMU数据辅助，UTM能够在复杂环境中减少计算复杂度，同时保持追踪精度和性能，解决了现有系统在高动态场景下性能下降的问题。
5. UTM支持部分LED模式匹配，即使在部分LED被遮挡或无法识别的情况下，仍能通过子模式匹配提供可靠的追踪结果，提高了系统的鲁棒性。
6. 本发明可应用于虚拟现实（VR）和增强现实（AR）系统，通过提供更准确的物体追踪，实现更自然和沉浸式的用户交互体验。
7. UTM可应用于多种场景，如游戏、教育、医疗等，为不具备内置追踪功能的设备提供六自由度追踪能力，扩展了人工现实技术的应用范围。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476835882)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260094284)**
<br/><br/>

---


<br/>

### 13. 基于可穿戴设备检测负载分布的天线性能调整装置、系统和方法

**Title (EN)**: APPARATUSES, SYSTEMS, AND METHODS FOR ANTENNA PERFORMANCE ADJUSTMENT BASED ON WEARABLE DEVICE DETECTED LOAD DISTRIBUTION  
**Pub. No.**: US20260095201

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Md Rashidul ISLAM](https://patents.google.com/?inventor=Md+Rashidul+ISLAM&country=US&num=100&sort=new), [Joung Sub SHIN](https://patents.google.com/?inventor=Joung+Sub+SHIN&country=US&num=100&sort=new), [Chia-Wei LIU](https://patents.google.com/?inventor=Chia-Wei+LIU&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本技术方案涉及一种系统和方法，其中与设备主体相连的带体包含一个与主体可操作连接的天线，以及由主体和/或带体支撑的一组传感器。该组传感器可以生成指示用户身体部分与主体和/或带体之间相互作用的测量值。与传感器组相连的控制器可以根据测量值识别由用户身体部分引起的负载分布，并根据负载分布确定与用户身体部分相关的天线的回波损耗特性，并依据回波损耗特性调整天线的频率响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476836901_1.jpg)

**Technical Field (技术领域)**:  
本发明属于可穿戴设备技术领域，具体涉及天线性能自适应调整技术。

**Background (发明背景)**:  
可穿戴设备通常需要支持多频段无线通信，但人体佩戴状态的变化会影响天线性能。现有技术中，天线设计通常基于标准测试模型，难以适应实际使用中人体条件的变化，导致天线频率偏移和性能下降。本发明旨在解决人体佩戴状态变化对天线性能的影响问题。

**Summary (发明总览)**:  
本发明通过在可穿戴设备主体和带体上分布传感器，实时检测用户佩戴状态引起的负载分布变化。控制器根据传感器数据识别佩戴状态，并调整天线性能以优化频率响应。系统采用可调阻抗匹配网络，根据负载分布选择最佳配置，确保天线在不同佩戴条件下保持最佳性能。本发明通过动态调整天线参数，解决了传统天线设计无法适应人体动态变化的问题。

**Key Innovation (核心创新)**:  
1. 通过在可穿戴设备主体和带体上集成力传感器、应变传感器和张力传感器，实时检测用户佩戴状态引起的负载分布变化，实现对佩戴条件的精确感知。
2. 利用控制器对传感器数据进行分类，将测量值映射到不同的负载分布模式，如紧贴佩戴、松散佩戴或部分负载，从而识别具体的佩戴状态。
3. 基于检测到的负载分布模式，计算天线回波损耗特性，并从预存储的配置库中选择最佳的天线调谐配置，确保天线性能与目标频率响应匹配。
4. 采用可调阻抗匹配网络，包含电容器、电感器和电阻器等组件，通过调整这些组件的参数来优化天线的频率响应，使其与负载分布引起的回波损耗特性相适应。
5. 设计了多天线切换机制，当一个天线受到高吸收影响时，控制器可以激活另一个天线，确保在设备位置变化时通信频段性能始终保持最佳。
6. 系统能够根据实时测量数据更新存储的传感器数据与天线回波损耗特性的关联模型，实现对佩戴状态变化的持续学习和自适应调整。
7. 本发明可应用于智能手表、健身追踪器等可穿戴设备，通过动态调整天线性能，提升无线通信的稳定性和可靠性，尤其适用于复杂的人体佩戴环境。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476836901)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260095201)**
<br/><br/>

---


<br/>

### 14. 基于雷达的远距离手势识别技术

**Title (EN)**: Radar-Based Gesture Determination at Long Ranges  
**Pub. No.**: US20260093333

**Applicant**: Google LLC  
**Inventor**: [Eiji Hayashi](https://patents.google.com/?inventor=Eiji+Hayashi&country=US&num=100&sort=new), [Zhuo Wang](https://patents.google.com/?inventor=Zhuo+Wang&country=US&num=100&sort=new), [Andrew C. Felch](https://patents.google.com/?inventor=Andrew+C.+Felch&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本文描述了基于雷达的远距离手势识别技术和设备。该技术使计算设备能够在最远八米的范围内检测并识别手势。用户无需在特定位置、特定方向、依赖唤醒触发或特定时间执行手势命令，从而可以随时随地自由提供命令。这种持续的手势识别功能通过机器学习模型、增强数据生成以及负数据的引入得以实现。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834830_1.jpg)

**Technical Field (技术领域)**:  
本专利属于人机交互技术领域，具体涉及基于雷达的远距离手势识别技术。

**Background (发明背景)**:  
环境计算技术在自动驾驶车辆和智能家居设备中的应用日益普及。这些技术允许用户同时处理多项任务，而环境计算设备则代表用户执行操作。然而，许多环境计算设备在识别用户命令方面存在局限性，例如需要用户在特定位置或特定方式下执行命令，或在执行命令前提供唤醒触发。这些限制使用户难以无缝地将设备融入日常生活。

**Summary (发明总览)**:  
本发明提出了一种基于雷达的远距离手势识别方法，旨在解决现有技术中用户需在特定位置或特定方式下执行命令的问题。该方法通过雷达系统持续检测并识别最远八米范围内的手势，无需用户依赖唤醒触发或特定时间执行命令。实现方式包括使用机器学习模型处理雷达信号数据，结合增强数据生成和负数据来提高识别精度。本发明相较于现有技术的主要改进在于提供了更自由、更便捷的手势识别方式，同时避免了隐私问题。

**Key Innovation (核心创新)**:  
1. 远距离雷达识别技术：
通过雷达系统在八米范围内持续检测手势，无需用户依赖特定位置或方向，实现更自由的手势识别。
2. 无需唤醒触发：
持续识别手势，无需用户执行唤醒触发（如语音提示或视觉提示），减少用户操作负担。
3. 机器学习模型的应用：
利用机器学习模型处理雷达信号数据，通过增强数据（如雷达信号特征的插值或外推）提高识别精度。
4. 负数据引入：
引入负数据（即与已知手势不相关的用户动作）来优化识别模型，减少误识别并提高识别质量。
5. 雷达数据隐私保护：
主要依赖雷达数据而非摄像头或麦克风数据，避免收集用户敏感信息，保护用户隐私。
6. 多传感器融合（推测）：
可能结合其他传感器数据（如红外传感器）以增强识别能力，特别是在复杂环境条件下。
7. 应用场景与价值：
适用于智能家居和自动驾驶等领域，提供更自然、更便捷的人机交互方式，提升用户体验并保护用户隐私。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834830)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093333)**
<br/><br/>

---


<br/>

### 15. 虚拟会议中与摄像头的增强集成方法

**Title (EN)**: ENHANCED INTEGRATION WITH CAMERAS FOR VIRTUAL MEETINGS  
**Pub. No.**: US20260095549

**Applicant**: Google LLC  
**Inventor**: [Daniel Enrique Ferrara](https://patents.google.com/?inventor=Daniel+Enrique+Ferrara&country=US&num=100&sort=new), [Jonathan Deokule](https://patents.google.com/?inventor=Jonathan+Deokule&country=US&num=100&sort=new), [Adam Mitchell Merber](https://patents.google.com/?inventor=Adam+Mitchell+Merber&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
一种用于虚拟会议中与摄像头增强集成的方法包括：在第一客户端设备上呈现虚拟会议用户界面（UI），该UI在与会者之间进行虚拟会议期间显示多个区域，每个区域对应一个由相应客户端设备提供的视频流。该方法包括通过第一数据通道在第一客户端设备上的客户端应用程序获取第一视频流，并通过第二数据通道获取元数据。然后根据通过第二数据通道获取的元数据，在虚拟会议期间对第一视频流的视觉表示进行修改。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476837288_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及虚拟会议技术，具体为虚拟会议中与摄像头的增强集成。

**Background (发明背景)**:  
虚拟会议通过虚拟会议平台连接多个参与者，实现音频和视频流的共享。现有的虚拟会议平台通常通过单一数据通道连接摄像头与客户端设备，仅传输视频流而不传输实时元数据。这导致无法实现基于实时元数据的视频增强功能，影响了虚拟会议的用户体验。

**Summary (发明总览)**:  
本发明提出了一种通过建立第二数据通道来增强虚拟会议中摄像头集成的技术方案。该方法通过第二数据通道实时传输视频流的元数据，使客户端应用程序能够根据这些元数据动态调整视频流的显示效果，从而提升虚拟会议的用户体验。相比现有技术，本发明通过引入实时元数据支持，实现了更丰富的视频交互功能和更精准的视频内容呈现。

**Key Innovation (核心创新)**:  
1. 通过第二数据通道传输实时元数据：
技术详解：建立符合HID规范的第二数据通道，使摄像头能够将视频流的实时元数据（如场景、对象和背景信息）传输到客户端应用程序。
实现方式：摄像头与客户端应用程序之间建立专用数据通道，传输实时元数据。
功能或解决的问题：解决了现有技术中无法传输实时元数据的问题，为视频增强功能提供支持。
2. 动态调整视频流显示效果：
技术详解：根据实时元数据，客户端应用程序动态调整视频流的视觉表示，例如调整对象突出显示、背景虚化等。
实现方式：客户端应用程序解析元数据并应用相应的视频处理算法。
功能或解决的问题：提升了视频内容的呈现效果，使用户更容易关注重要信息。
3. 支持多设备实时数据同步：
技术详解：虚拟会议平台支持多个客户端设备同时通过第二数据通道传输元数据，并进行实时数据同步。
实现方式：平台管理多个数据通道的连接和通信，确保元数据的一致性和实时性。
功能或解决的问题：确保在多设备参与的虚拟会议中，所有参与者都能获得相同的增强体验。
4. 增强对象交互功能：
技术详解：利用元数据识别视频流中的对象，并在用户界面中提供交互选项，例如点击对象获取更多信息。
实现方式：客户端应用程序结合元数据识别对象并生成交互元素。
功能或解决的问题：增加了视频内容的互动性，提升了用户参与度。
5. 优化视频流传输效率：
技术详解：通过第二数据通道传输元数据，避免在主视频流数据通道中增加额外负担，从而优化传输效率。
实现方式：分离视频流和元数据的数据通道，确保各自独立传输。
功能或解决的问题：防止视频流延迟或卡顿，提升整体传输性能。
6. 兼容现有虚拟会议平台：
技术详解：第二数据通道的设计符合现有虚拟会议平台的接口规范，确保兼容性。
实现方式：采用标准化的数据通道协议，与现有平台无缝集成。
功能或解决的问题：使本发明能够快速部署到现有的虚拟会议环境中，无需大规模改造。
7. 应用场景与价值：
推测应用场景：适用于企业会议、在线教育、远程医疗等需要高质量视频交互的场景。
独特价值：提供更智能、更互动的虚拟会议体验，提升远程协作的效率和效果。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476837288)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260095549)**
<br/><br/>

---


<br/>

### 16. 用于高功率热稳定小型热管的方法和系统

**Title (EN)**: METHODS AND SYSTEMS FOR HIGH POWER THERMALLY STABLE SMALL HEAT PIPES  
**Pub. No.**: US20260096061

**Applicant**: Meta Platforms, Inc.  
**Inventor**: [Michael Nikkhoo](https://patents.google.com/?inventor=Michael+Nikkhoo&country=US&num=100&sort=new), [Shankhadeep Das](https://patents.google.com/?inventor=Shankhadeep+Das&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明涉及一种用于混合现实设备的热管理系统和设备。该系统包括一个管状部件，具有近端和远端，管状部件包含外壳并定义了一个蒸汽腔，管状部件在近端和远端处密封。热管理系统包括一个位于蒸汽腔内的外加热引擎，外加热引擎靠近管状部件的内表面壁。热管理系统还包括一个位于外加热引擎内部的内加热引擎，内加热引擎的外表面定义了一个由管状部件内壁和内加热引擎外表面限定的辅助腔。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476837855_1.jpg)

**Technical Field (技术领域)**:  
混合现实设备的热管理技术，具体涉及小型热管设计。

**Background (发明背景)**:  
混合现实头戴设备需要摆脱外部电源线的束缚，实现自主移动，这对设备的散热性能提出了更高要求。
现有技术中，设备过热会导致用户体验下降，甚至可能损坏设备。
因此，需要一种高效的热管理系统来维持设备的稳定运行温度。

**Summary (发明总览)**:  
本发明提出了一种用于混合现实设备的新型热管设计，通过内外双层加热引擎结构实现高效散热。
该设计采用同心圆排列的金属丝束结构，形成内外两层加热引擎，并通过蒸汽腔和辅助腔的协同作用增强散热效果。
与现有技术相比，本发明通过优化金属丝束的排列方式和直径，提升了散热效率，同时减小了设备体积。
该设计可集成于眼镜的镜腿中，适用于小型化混合现实设备。

**Key Innovation (核心创新)**:  
1. 采用内外双层加热引擎结构，通过蒸汽腔和辅助腔的协同作用提升散热效率。
技术细节：外加热引擎由金属丝束编织成外层圆壳，内加热引擎则编织成内层圆壳并封装蒸汽腔。
实现方式：内外引擎的金属丝束采用交错编织方式，形成多孔结构。
功能：增强热传导效率并提供更大的散热表面积。
2. 优化金属丝束的排列方式和直径，提升散热性能。
技术细节：内加热引擎的金属丝束数量多于外加热引擎，但外加热引擎的金属丝直径更大。
实现方式：通过调整金属丝束的密度和直径，实现不同区域的散热强度控制。
功能：确保热量均匀分布并有效传递至外部。
3. 设计同心圆排列结构，减小设备体积并提高空间利用率。
技术细节：内外加热引擎与管状部件采用同心圆排列方式。
实现方式：利用管状部件的内壁作为支撑结构，形成紧凑的散热模块。
功能：适用于小型化混合现实设备，如眼镜式头戴设备。
4. 采用铜或铜合金材料，提升导热性能。
技术细节：管状部件和金属丝束可由铜或铜合金制成。
实现方式：利用铜的高导热系数，快速传导热量。
功能：提高整体散热效率并减少热积累。
5. 设计可密封加压的蒸汽腔，增强热传导效率。
技术细节：管状部件在近端和远端密封并加压，内部封装传输流体。
实现方式：通过控制蒸汽腔内的压力，优化热传导过程。
功能：提高热传导速度并维持稳定的散热性能。
6. 适用于眼镜式混合现实设备，可集成于镜腿中。
技术细节：管状部件可设计为适合眼镜镜腿的尺寸。
实现方式：将热管嵌入镜腿结构中，不影响设备外观和使用舒适度。
功能：为小型化混合现实设备提供高效散热解决方案。
7. 推测应用场景：可应用于虚拟现实、增强现实等混合现实设备中。
独特价值：提供了一种小型化、高效的热管理方案，解决了设备过热问题，提升了用户体验和设备可靠性。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476837855)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260096061)**
<br/><br/>

---


<br/>

### 17. 基于屏幕内容的隐式校准用于视线追踪

**Title (EN)**: Implicit Calibration from Screen Content for Gaze Tracking  
**Pub. No.**: US20260093324

**Applicant**: Google LLC  
**Inventor**: [Dmitry Lagun](https://patents.google.com/?inventor=Dmitry+Lagun&country=US&num=100&sort=new), [Gautam Prasad](https://patents.google.com/?inventor=Gautam+Prasad&country=US&num=100&sort=new), [Pezhman Firoozfam](https://patents.google.com/?inventor=Pezhman+Firoozfam&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明涉及用于视线追踪的隐式校准方法和系统。该方法包括由神经网络模块接收与显示屏幕上的呈现内容相关联的显示内容。神经网络模块还接收未校准的视线信息，其中未校准的视线信息包括与显示屏幕上的显示内容相关的观众视线未校准视线轨迹。神经网络模块对未校准的视线信息和显示内容应用选定的函数，以生成用户特定的视线函数。用户特定的视线函数具有一个或多个个性化参数。然后，神经网络模块可以将用户特定的视线函数应用于未校准的视线信息，以生成与显示屏幕上的显示内容相关联的校准视线信息。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834821_1.jpg)

**Technical Field (技术领域)**:  
本发明属于人机交互技术领域，具体涉及视线追踪的隐式校准技术。

**Background (发明背景)**:  
视线追踪技术用于确定用户当前在设备显示屏幕上查看的内容，但未校准的系统可能无法准确识别用户实际注视的位置。传统的视线预测系统通常采用显式校准方法，这需要针对特定个体进行耗时且资源密集的训练，且对设备和用户条件有较高要求。

**Summary (发明总览)**:  
本发明提出了一种基于屏幕内容和未校准视线信息的隐式校准方法，通过神经网络模块处理显示内容和未校准视线信息，生成用户特定的视线函数。该方法无需显式校准步骤，利用时空信息生成个性化参数，从而实现更快速、更高效的视线校准。该方法相较于传统显式校准方法，显著降低了资源消耗，并可在多种设备上实时应用。

**Key Innovation (核心创新)**:  
1. 采用神经网络模块处理显示内容和未校准视线信息，通过端到端模型生成用户特定的视线函数。
技术详解：利用神经网络编码显示内容的时空信息和未校准视线信息，生成上下文向量，并在解码器中应用该向量生成校准后的视线信息。
实现方式：通过自注意力机制处理时间维度和空间维度信息，并使用全连接层优化输出。
功能或解决的问题：无需显式校准步骤，实现快速准确的视线追踪。
2. 利用显著性图（热图）识别屏幕上的兴趣点，并将其与未校准视线信息结合进行校准。
技术详解：生成屏幕内容的显著性图，并将其与未校准视线轨迹进行匹配。
实现方式：通过神经网络分析屏幕内容像素和视线测量序列，生成个性化校准函数。
功能或解决的问题：提高视线追踪的准确性，特别是在复杂屏幕内容环境下。
3. 支持使用真实网页或合成内容进行训练和测试。
技术详解：提供多种数据来源，包括真实网页截图和合成的文本或图形信息。
实现方式：使用合成数据集模拟不同用户界面的视线轨迹，并生成训练和测试页面。
功能或解决的问题：增强模型的泛化能力，适应不同应用场景。
4. 引入时间信息编码机制，捕捉用户视线轨迹的动态变化。
技术详解：在神经网络中编码时间间隔内的视线测量和屏幕内容像素序列。
实现方式：通过时间窗口分析视线轨迹的变化趋势，并生成时间上下文信息。
功能或解决的问题：提高对用户视线动态变化的适应能力，实现更精准的校准。
5. 提供基于变换的校准模型训练方法，通过扰动生成多样化的训练数据。
技术详解：使用Φ(γ)变换，其中γ代表用户级参数，Φ代表操作这些参数的功能形式。
实现方式：通过变换生成扰动后的训练和测试页面，以增强模型的鲁棒性。
功能或解决的问题：提高模型对不同用户和场景的适应能力。
6. 适用于多种设备和应用场景，包括VR、医疗设备、驾驶监控等。
技术详解：隐式校准方法可应用于VR环境、医疗设备（如脑震荡诊断）、驾驶监控等。
实现方式：利用通用性强的神经网络模型，适应不同设备和应用的需求。
功能或解决的问题：扩展视线追踪技术的应用范围，提升用户体验。
7. 实时处理能力，支持多模态交互。
技术详解：实时处理未校准视线信息，并结合语音、触摸和手势等多模态输入。
实现方式：优化神经网络模型的计算效率，实现低延迟的视线校准。
功能或解决的问题：提升人机交互的自然性和流畅度。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834821)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093324)**
<br/><br/>

---


<br/>

### 18. 稀疏深度成像中插值深度值的方法

**Title (EN)**: SPARSE DEPTH IMAGING WITH INTERPOLATED DEPTH VALUES  
**Pub. No.**: US20260094288

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ling ZHU](https://patents.google.com/?inventor=Ling+ZHU&country=US&num=100&sort=new), [John Peter GODBAZ](https://patents.google.com/?inventor=John+Peter+GODBAZ&country=US&num=100&sort=new), [Vishali MOGALLAPU](https://patents.google.com/?inventor=Vishali+MOGALLAPU&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明提出了一种稀疏深度成像系统的操作方法。该方法包括接收环境的深度图，深度图包含位于光学传感器坐标系中的多个像素点。接收光学源坐标系中的照明点图案，每个照明点在光学源坐标系的定义平面中具有固定位置。将深度图投影到光学传感器坐标系中的三维点云中，并将三维点云中的每个点分配到定义平面中的二维位置。基于三维点云中点的变换深度，对每个照明点的深度值进行插值，并将每个照明点分配到光学传感器坐标系中的三维位置。最后，在光学传感器坐标系中输出每个照明点的深度值。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476835887_1.jpg)

**Technical Field (技术领域)**:  
本专利属于深度成像技术领域，具体涉及稀疏深度成像和深度值插值技术。

**Background (发明背景)**:  
深度成像系统在消费电子产品中越来越普遍，例如智能手机、笔记本电脑和虚拟现实设备。然而，现有技术中，深度成像的可靠性依赖于深度图的准确性。在稀疏深度成像中，由于光学源和光学传感器之间的横向偏移，照明点的位置在深度图像中未知，这给照明点定位和深度计算带来了挑战。

**Summary (发明总览)**:  
本发明提出了一种通过插值方法提高稀疏深度成像精度的技术方案。其核心思路是将接收到的深度图投影到三维点云中，并基于点云数据对照明点的深度值进行插值，从而获得更准确的深度信息。具体实现路径包括：将深度图转换为三维点云，分配照明点的二维位置，计算插值深度值，并最终输出照明点的三维位置和深度值。本发明相较于现有技术，能够更准确地定位照明点并计算其深度值，从而提高稀疏深度成像的可靠性和精度。

**Key Innovation (核心创新)**:  
1. 通过将深度图投影到三维点云中，实现对照明点位置的精确定位。
技术详解：利用光学传感器坐标系中的深度图数据，将其转换为三维点云，并分配每个点云点的二维位置。
功能：解决了照明点位置在深度图像中未知的问题。
2. 基于三维点云中点的变换深度，对照明点的深度值进行插值。
技术详解：利用点云中邻近点的深度信息，通过插值算法计算照明点的深度值。
功能：提高了深度计算的准确性，特别是在照明点稀疏的情况下。
3. 将照明点分配到光学传感器坐标系中的三维位置。
技术详解：通过插值得到的深度值和预定义的二维位置，计算照明点的三维坐标。
功能：提供了照明点的精确三维信息，便于后续的机器视觉和识别任务。
4. 适用于高环境光和深色物体等复杂场景。
技术详解：稀疏点投影和插值方法在复杂光照条件下表现更稳定。
功能：扩展了深度成像系统的应用场景，提高了在户外和复杂环境中的可靠性。
5. 减少了对硬件校准的依赖。
技术详解：通过软件算法补偿光学源和传感器之间的偏移。
功能：降低了系统校准的复杂度，提高了设备的易用性。
6. 提高了深度成像系统的整体精度和可靠性。
技术详解：结合插值算法和点云数据处理技术。
功能：为手势识别、面部识别等应用提供更准确的基础数据。
7. 应用于虚拟现实、增强现实和智能设备中。
技术详解：提供更精确的深度信息以支持机器视觉和三维重建。
功能：增强用户体验，例如更自然的交互和更真实的环境感知。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476835887)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260094288)**
<br/><br/>

---


<br/>

### 19. 头戴式显示器中可变散光校正的系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR VARIABLE ASTIGMATIC CORRECTION IN HEAD MOUNTED DISPLAYS  
**Pub. No.**: US20260093118

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Brandon Michael Hellman Friedman](https://patents.google.com/?inventor=Brandon+Michael+Hellman+Friedman&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
一种装置可包括一个观看光学系统。该观看光学系统可包括第一可旋转相位板、第二可旋转相位板和一个可调焦装置。该观看光学系统被配置用于对来自显示器的光线进行成像，所成像的光线具有球面功率、柱面功率和柱面轴。通过调整可调焦装置、旋转第一可旋转相位板和旋转第二可旋转相位板，可以控制成像光线的球面功率、柱面功率和柱面轴。还公开了其他设备、装置、系统以及制造方法。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834592_1.jpg)

**Technical Field (技术领域)**:  
头戴式显示器光学系统；
可调节光学校正技术；
散光校正与焦距调节。

**Background (发明背景)**:  
头戴式显示器（HMD）需要精确的光学校正以提供清晰的图像，但现有技术难以同时处理球面和散光误差。
传统光学系统通常采用固定光学元件，无法适应不同用户的视力差异。
这导致图像失真或模糊，影响用户体验。
本发明旨在提供一种可动态调节球面和散光校正的光学系统，以解决上述问题。

**Summary (发明总览)**:  
本发明提出了一种可调节光学系统，通过旋转相位板和调整焦距来动态控制球面和散光校正。
该系统利用两个可旋转相位板和一个可调焦装置来改变成像光线的光学特性。
相较于传统固定光学系统，本发明能够适应不同用户的视力需求，提供更清晰的图像。
通过独立控制球面功率、柱面功率和柱面轴，本发明实现了更灵活的光学校正。
这种设计提高了光学系统的适应性和用户体验。

**Key Innovation (核心创新)**:  
1. 采用双可旋转相位板设计，通过独立旋转两个相位板来控制柱面功率和柱面轴向，实现对散光的精确校正。
技术实现方式：相位板采用液晶或微机械结构，通过电控旋转实现动态调节。
功能：提供灵活的散光校正，适应不同用户的视力需求。
2. 结合可调焦装置，实现对球面功率的动态调节。
技术实现方式：可调焦装置采用液体透镜或机械调焦结构，通过改变透镜形状或位置来调整焦距。
功能：提供精确的球面校正，适应不同观看距离和用户视力。
3. 光学系统采用模块化设计，将散光校正和球面校正功能分离。
技术实现方式：两个相位板分别负责散光校正的不同方面，可调焦装置独立控制球面校正。
功能：提高光学系统的可调节性和适应性。
4. 通过电控系统实现对相位板和可调焦装置的精确控制。
技术实现方式：采用微处理器和传感器反馈系统，根据用户输入或自动检测结果调整光学参数。
功能：提供自动化和智能化的光学校正，提升用户体验。
5. 光学系统设计紧凑，适用于头戴式显示器的小型化需求。
技术实现方式：采用微型化光学元件和集成化设计，减少系统体积和重量。
功能：确保光学系统在不增加头戴设备体积的情况下提供高质量图像。
6. 光学系统能够实时适应环境光变化和用户视力变化。
技术实现方式：通过传感器检测环境光强度和用户视力参数，自动调整光学参数。
功能：提供动态的光学校正，适应不同使用场景和用户需求。
7. 本发明可应用于虚拟现实（VR）、增强现实（AR）等头戴式显示器产品。
独特价值：提供更清晰、更舒适的视觉体验，减少视觉疲劳，提升用户沉浸感。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834592)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093118)**
<br/><br/>

---


<br/>

### 20. 多电池到单电池调节期间降低静态电流的负载依赖方法

**Title (EN)**: LOAD DEPENDENT METHOD TO REDUCE QUIESCENT CURRENT DURING MULTI-CELL TO SINGLE-CELL BATTERY REGULATION  
**Pub. No.**: US20260095059

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Julian Arlo BINDER](https://patents.google.com/?inventor=Julian+Arlo+BINDER&country=US&num=100&sort=new), [Mike VOONG](https://patents.google.com/?inventor=Mike+VOONG&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
一种电源控制设备能够在电池供电系统中实现高效的电源传输，同时在低功耗条件下减少静态电流。该设备包括一个控制逻辑电路，用于检测系统的电源状态并生成控制信号。一个理想二极管电路根据控制信号选择性地将电源从第一电源输入或第二电源输入耦合到系统电源输出。一个线性稳压器电路提供具有低静态电流的第一稳压电源信号，以在待机或负载降低操作期间维持系统的最小功能。一个开关模式电源电路在激活时选择性地提供具有较高静态电流的第二稳压电源信号以支持更高的负载条件。通过根据系统状态在这些电源电路之间切换，该设备提高了能源效率，延长了电池寿命，并支持需要低功耗待机和全性能模式的紧凑型电池供电系统。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476836743_1.jpg)

**Technical Field (技术领域)**:  
电池供电系统电源管理技术领域，具体涉及多电池到单电池调节期间的静态电流优化。

**Background (发明背景)**:  
电子设备通常使用多种电池拓扑结构作为电源解决方案。传统的电池组配置包括串联、并联或串并联组合的电池单元，这些配置决定了电池组的总电压和容量。然而，现有技术中，电源管理电路在低负载或待机模式下往往消耗过多静态电流，导致电池寿命缩短。此外，传统的电源管理方案在实现高效能电源切换时通常需要复杂的电路设计，增加了成本和故障风险。

**Summary (发明总览)**:  
本发明提出了一种新型电源控制方案，通过多模式电源管理实现高效的电池供电系统电源传输。该方案采用负载依赖的电源切换机制，在不同负载条件下选择性地使用线性稳压器或开关模式电源电路，以优化静态电流和系统性能。通过理想二极管电路实现电源的无缝切换，本发明在降低电路复杂度的同时提高了可靠性，并显著延长了电池供电设备的待机时间。

**Key Innovation (核心创新)**:  
1. 采用负载依赖的多模式电源管理机制，通过状态机或模式拓扑结构检测系统状态并选择合适的电源电路，实现高效电源切换。
2. 设计了理想二极管电路，根据控制信号选择性地将电源从第一电源输入或第二电源输入耦合到系统电源输出，确保电源切换的平滑性和高效性。
3. 集成线性稳压器电路，在低负载或待机模式下提供具有低静态电流的稳压电源信号，以减少功耗并维持系统基本功能。
4. 集成开关模式电源电路，在高负载条件下提供具有较高静态电流的稳压电源信号，以支持更高的负载需求，同时在不需要时关闭以节省能量。
5. 通过状态机控制电源电路的启用和禁用，实现对系统电源状态的实时监控和动态调整，优化电源分配并延长电池寿命。
6. 实现了电路复杂度的降低，相比传统方案减少了元件数量和制造成本，同时提高了系统的可靠性和稳定性。
7. 本发明适用于需要长时间待机和高负载性能切换的电池供电设备，如便携式电子设备、物联网设备和可穿戴设备，能够显著延长设备的使用时间和电池寿命。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476836743)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260095059)**
<br/><br/>

---


<br/>

### 21. 内容插入用户界面

**Title (EN)**: CONTENT INSERT USER INTERFACE  
**Pub. No.**: US20260093386

**Applicant**: GOOGLE LLC  
**Inventor**: [Donny Chen Reynolds](https://patents.google.com/?inventor=Donny+Chen+Reynolds&country=US&num=100&sort=new), [Yuncheng Shen](https://patents.google.com/?inventor=Yuncheng+Shen&country=US&num=100&sort=new), [Matthieu Trudeau](https://patents.google.com/?inventor=Matthieu+Trudeau&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
一种方法可以在应用程序的输入区域获得焦点时检测到预定的输入手势，并响应于检测到该手势而显示一个用户界面。该用户界面包括：第一个可选项，用于在选择时将文件相关的内容插入输入区域；第二个可选项，用于在选择时执行预定的输入手势的默认操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834889_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及内容插入和用户界面设计。

**Background (发明背景)**:  
目前，用户通常使用剪切、复制和粘贴操作将内容插入应用程序，这需要使用剪贴板临时存储内容。这种方法需要用户在不同应用之间切换并手动定位内容，导致操作繁琐，尤其对操作能力受限的用户不友好。此外，这种方式会占用额外的系统资源和显示空间，并可能分散用户注意力。

**Summary (发明总览)**:  
本发明提出了一种通过预定的输入手势触发显示用户界面的方法，用户界面提供多种内容插入选项，无需离开当前应用或使用额外应用即可选择并插入内容。该方法通过检测输入手势和应用输入区域的焦点状态，动态显示包含文件相关内容和默认操作选项的用户界面，从而简化内容插入流程，提高操作效率。

**Key Innovation (核心创新)**:  
1. 预定义输入手势触发机制：通过检测预定义的输入手势（如键盘按键），在应用输入区域获得焦点时触发用户界面显示，实现快速内容插入。
2. 多源内容选择界面：用户界面提供多种内容来源选项，包括最近访问的文件、生成的内容以及特定应用输出，用户无需切换应用即可选择插入内容。
3. 动态内容生成与插入：用户界面包含查询字段，用户可搜索文件或生成内容，并通过选择相应选项将内容插入当前应用的输入区域。
4. 双功能输入手势设计：预定义输入手势具有双重功能，当输入区域有焦点时触发用户界面显示，否则执行默认操作（如切换键盘功能）。
5. 减少用户操作步骤：通过在单一界面内提供多种内容选择和插入选项，减少了用户在不同应用间切换和手动复制粘贴的需求。
6. 提升操作效率：减少处理器资源占用和用户与设备的交互次数，尤其对操作能力受限的用户更为友好。
7. 应用场景与价值：该技术可应用于文字处理、社交媒体、图像编辑、电子邮件等需要频繁插入内容的应用场景，为用户提供更高效、更便捷的内容插入体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834889)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093386)**
<br/><br/>

---


<br/>

### 22. 状态转换前后数据通信的管理方法

**Title (EN)**: MANAGING DATA COMMUNICATION BEFORE AND AFTER A STATE TRANSITION  
**Pub. No.**: US20260095937

**Applicant**: GOOGLE LLC  
**Inventor**: [Chih-Hsiang Wu](https://patents.google.com/?inventor=Chih-Hsiang+Wu&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
为了在用户设备（UE）状态转换期间管理通信，基站的核心单元（CU）通过处理硬件在UE处于非活动状态时执行早期数据传输程序，包括向UE传输至少一个数据包序列中的数据包。CU确定将UE从非活动状态转换到连接状态。在响应将UE转换到连接状态时，CU通过处理硬件向UE传输序列中的下一个数据包，或者在确定至少一个数据包未被接收时，通过处理硬件重新向UE传输该数据包。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476837718_1.jpg)

**Technical Field (技术领域)**:  
无线通信领域，具体涉及用户设备（UE）与无线接入网（RAN）在非活动状态和连接状态之间的数据通信管理。

**Background (发明背景)**:  
在蜂窝无线接入网络中，基站与用户设备（UE）通过无线电接入技术和协议栈的多层进行通信。RRC子层定义了UE的RRC_IDLE、RRC_CONNECTED和RRC_INACTIVE状态。现有的方法中，UE在非活动状态时传输少量数据时可能需要切换到连接状态，这可能导致通信效率低下和延迟增加。

**Summary (发明总览)**:  
本发明提出了一种在UE状态转换期间管理数据通信的方法，主要通过在UE处于非活动状态时执行早期数据传输程序，并在状态转换后继续或重新传输数据包。该方法通过核心单元（CU）和分布式单元（DU）协调处理，确保数据包在状态转换过程中不丢失或重复传输。与现有技术相比，本发明在保持通信效率的同时，减少了状态转换带来的延迟和资源浪费。

**Key Innovation (核心创新)**:  
1. 在UE处于非活动状态时，通过CU执行早期数据传输程序，包括向UE传输数据包序列中的至少一个数据包，从而在状态转换前预先传输数据。
2. CU确定将UE从非活动状态转换到连接状态，并在转换后继续传输数据包序列中的下一个数据包，确保数据传输的连续性。
3. 如果CU确定之前传输的数据包未被UE接收，则通过处理硬件重新传输该数据包，防止数据丢失并提高通信可靠性。
4. 在DU中实现类似的功能，通过DU与UE进行数据包通信，并在UE状态转换后继续或重新传输数据包，确保数据传输的协调性。
5. UE在状态转换过程中，通过处理硬件与CU和DU协调通信，确保数据包在状态转换期间正确传输和接收。
6. 本发明通过在状态转换前预先传输数据，并在转换后继续或重新传输数据包，避免了传统方法中因状态转换带来的通信延迟和资源浪费。
7. 该方法适用于需要高效数据传输的场景，如物联网设备通信和低延迟应用，能够在保持通信效率的同时，减少状态转换带来的不利影响。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476837718)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260095937)**
<br/><br/>

---


<br/>

### 23. 动态配置带有助手命令的热词按钮

**Title (EN)**: DYNAMICALLY CONFIGURING A WARM WORD BUTTON WITH ASSISTANT COMMANDS  
**Pub. No.**: US20260094610

**Applicant**: GOOGLE LLC  
**Inventor**: [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new), [Antonio Gaetani](https://patents.google.com/?inventor=Antonio+Gaetani&country=US&num=100&sort=new), [Bastiaan Van Eeckhoudt](https://patents.google.com/?inventor=Bastiaan+Van+Eeckhoudt&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本文描述了与客户端设备相关联的热词按钮的动态配置方法，该方法基于检测到的热词激活事件，为热词按钮配置特定的助手命令。在检测到客户端设备的热词激活事件后，本方法可确定是否需要对激活热词按钮的用户进行用户验证。如果需要用户验证，则执行用户验证。在确定激活热词按钮的用户已通过验证后，本方法可指示自动化助手执行特定操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476836246_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及智能助手与客户端设备的热词按钮动态配置。

**Background (发明背景)**:  
人机对话通常通过自动化助手进行，用户通过语音或文本输入命令，助手通过用户界面输出或控制智能设备进行响应。
现有技术中，客户端设备的热词按钮通常只能执行预定义的有限命令，且在某些情况下出于数据安全考虑无法执行某些操作。
这导致用户需要通过其他方式与设备交互，增加了用户输入次数并浪费了计算资源。

**Summary (发明总览)**:  
本发明提出了一种动态配置热词按钮的方法，根据客户端设备环境中的热词激活事件，为热词按钮配置上下文相关的助手命令。
该方法不仅支持硬件按钮和软件按钮，还支持用户验证机制，根据激活事件类型和命令意图决定是否需要验证以及验证方式。
相较于现有技术，本发明通过动态配置和灵活的验证机制，提升了热词按钮的灵活性和安全性，减少了用户交互步骤并优化了资源利用。

**Key Innovation (核心创新)**:  
1. 动态配置热词按钮：根据检测到的热词激活事件类型（如来电、短信、闹钟等），为热词按钮动态分配相应的助手命令，实现命令的上下文相关性和灵活性。
2. 用户验证机制：针对不同类型的热词激活事件和命令意图，智能决定是否需要用户验证以及采用何种验证方式（如语音识别、面部识别、指纹识别等），确保安全性。
3. 基于事件持续时间调整命令：热词按钮的助手命令配置时间根据事件类型动态调整，例如来电时按钮在电话铃响期间有效，短信事件则在初始接收后的预设时间内有效。
4. 默认与用户自定义命令结合：支持自动化助手为热词按钮配置默认命令，同时允许用户通过设置界面自定义特定事件的命令，满足个性化需求。
5. 多种验证方式灵活应用：对于需要高安全性的命令（如回复短信、接听电话），采用基于语音的验证方式；对于低风险操作（如暂停音乐），则可选择非语音验证或无需验证。
6. 跨设备控制支持：热词按钮不仅可控制本地设备，还可通过通信协议控制环境中的其他设备，实现更广泛的应用场景。
7. 应用于智能家居和移动设备：此技术可应用于智能音箱、手机等设备，在来电处理、消息回复、媒体控制等场景中提供更便捷和安全的人机交互方式。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476836246)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260094610)**
<br/><br/>

---


<br/>

### 24. 虚拟会议自动浮动窗口

**Title (EN)**: AUTOMATIC FLOATING WINDOW FOR VIRTUAL MEETINGS  
**Pub. No.**: US20260093370

**Applicant**: Google LLC  
**Inventor**: [Bo Wang](https://patents.google.com/?inventor=Bo+Wang&country=US&num=100&sort=new), [Denys Miasoutov](https://patents.google.com/?inventor=Denys+Miasoutov&country=US&num=100&sort=new), [Lixia Liu](https://patents.google.com/?inventor=Lixia+Liu&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
一种方法包括浏览器应用程序接收第一用户交互以在浏览器应用程序的第一个标签页中启动虚拟会议。该方法进一步包括在虚拟会议期间接收第二用户交互以将浏览器应用程序的焦点切换到第二个标签页。该方法进一步包括，在浏览器应用程序的焦点切换到第二个标签页时，显示一个浮动窗口，同时显示第二个标签页的内容。浮动窗口包括与虚拟会议相关的一个或多个元素。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834871_1.jpg)

**Technical Field (技术领域)**:  
虚拟会议技术领域，具体涉及在浏览器应用中自动显示虚拟会议元素的浮动窗口技术。

**Background (发明背景)**:  
虚拟会议系统允许用户通过数字手段进行远程或本地通信。然而，当用户切换浏览器标签页时，虚拟会议界面可能会被隐藏，导致用户无法继续参与会议。这不仅增加了用户的时间成本，还可能因错过会议内容而需要额外的资源进行后续跟进。

**Summary (发明总览)**:  
本发明提出了一种在浏览器应用中自动显示虚拟会议元素的浮动窗口方案。当用户将浏览器焦点切换到非会议标签页时，系统会生成一个浮动窗口，显示会议相关元素，使用户能够继续参与会议。该方案通过减少用户切换标签页的时间消耗和资源浪费，提升了会议参与效率。相较于现有技术，本发明允许用户同时进行会议和任务处理，无需额外操作即可保持会议参与度。

**Key Innovation (核心创新)**:  
1. 浮动窗口自动生成与显示技术：
当用户将浏览器焦点从虚拟会议标签页切换到其他标签页时，系统自动生成一个浮动窗口，并在其中显示会议相关元素，如参与者列表和会议控制按钮。
实现方式：通过监听浏览器焦点变化事件，触发浮动窗口的生成和内容渲染。
功能：使用户无需切换回会议标签页即可继续参与会议。
2. 浮动窗口内容动态调整机制：
浮动窗口的大小变化会触发会议元素的动态显示或隐藏。例如，窗口放大时显示更多参与者信息，窗口缩小时隐藏部分元素以节省空间。
实现方式：通过监听窗口大小变化事件，动态调整显示内容。
功能：提供灵活的用户界面，适应不同用户的操作习惯和需求。
3. 子窗口交互功能：
浮动窗口内可显示子窗口，如会议通知或消息提醒，用户点击子窗口后，浏览器焦点自动切换回会议标签页。
实现方式：通过事件监听和焦点控制机制实现子窗口与主标签页的交互。
功能：使用户能够快速响应会议中的重要信息或通知。
4. 多客户端兼容设计：
不同虚拟会议客户端（如浏览器应用、移动应用、虚拟会议室）均可支持浮动窗口功能，确保用户在不同设备上获得一致的会议体验。
实现方式：通过标准化会议元素接口和跨平台通信协议实现。
功能：提供无缝的多设备会议体验，提升用户参与度。
5. 资源优化：
用户可以在不中断会议的情况下同时进行其他任务，减少了因频繁切换标签页而消耗的额外计算资源。
实现方式：通过浮动窗口的独立渲染和资源管理机制实现。
功能：提高系统效率，节省用户时间。
6. 用户界面一致性：
无论用户是在标签页内还是在浮动窗口中参与会议，会议界面的布局和功能保持一致，确保用户操作的连续性。
实现方式：通过统一的UI组件库和样式规范实现。
功能：降低用户学习成本，提升使用体验。
7. 应用场景与价值：
本发明适用于需要同时进行会议和任务处理的场景，如远程办公、在线教育等。它不仅提升了会议参与的便捷性，还通过减少资源消耗和操作步骤，为用户带来更高效、更流畅的会议体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834871)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093370)**
<br/><br/>

---


<br/>

### 25. 铰链装置

**Title (EN)**: Hinged Device  
**Pub. No.**: US20260093290

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Tung Yuen LAU](https://patents.google.com/?inventor=Tung+Yuen+LAU&country=US&num=100&sort=new), [Denys V. YAREMENKO](https://patents.google.com/?inventor=Denys+V.+YAREMENKO&country=US&num=100&sort=new), [Jingjiang ZHANG](https://patents.google.com/?inventor=Jingjiang+ZHANG&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明涉及铰链装置，例如铰链式计算设备。一个示例包括固定在第一铰链臂上的第一部分，该铰链臂可绕第一铰链轴旋转，以及固定在第二铰链臂上的第二部分，该铰链臂可绕第二铰链轴旋转。一个定时滑块可定位在位于第一铰链轴和第二铰链轴之间的中央轴上，用于根据第一和第二铰链臂的取向控制它们所受的摩擦扭矩，并同步第一和第二铰链臂绕第一和第二铰链轴的旋转。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476834782_1.jpg)

**Technical Field (技术领域)**:  
铰链技术领域，具体涉及可折叠计算设备的铰链同步与扭矩控制技术。

**Background (发明背景)**:  
许多计算机设备形态，如智能手机、平板电脑和笔记本电脑，通过折叠以便于存储和展开以便于使用来提供增强功能。然而，现有铰链装置在同步旋转和扭矩控制方面存在不足，导致设备展开或折叠时不够顺畅或稳定。本发明旨在解决铰链装置在旋转同步性和扭矩控制方面的技术问题。

**Summary (发明总览)**:  
本发明提出了一种新型铰链装置，通过在中央轴上设置定时滑块来控制两个铰链臂的旋转同步性和摩擦扭矩。该装置能够根据铰链臂的取向调整摩擦力，并存储弹出能量以实现自动展开功能。与传统铰链相比，本发明提供了更精确的旋转控制和更流畅的展开体验。

**Key Innovation (核心创新)**:  
1. 定时滑块设计：通过在中央轴上设置定时滑块，实现对第一和第二铰链臂旋转的精确控制，确保两个部分同步旋转。
2. 摩擦扭矩调节：定时滑块根据铰链臂的取向调整摩擦扭矩，在不同角度提供适当的阻力，保证设备展开和折叠的稳定性。
3. 弹出能量存储：在特定取向时，铰链装置能够存储弹出能量，当用户需要时自动释放，实现设备的自动展开功能。
4. 中央控制器集成：中央控制器位于中央轴上，负责协调摩擦扭矩和旋转同步，提供统一控制机制。
5. 适应多种设备形态：该铰链装置可应用于多种可折叠计算设备形态，包括笔记本电脑、平板电脑等，提供一致的用户体验。
6. 机械结构优化：通过优化铰链臂和中央轴的机械结构，减少摩擦损耗，提高装置的耐用性和可靠性。
7. 应用场景与价值：该铰链装置特别适用于需要频繁展开和折叠的便携式计算设备，能够提升设备的便携性和使用便利性，同时延长设备的使用寿命。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476834782)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260093290)**
<br/><br/>

---


<br/>

### 26. 在虚拟会议中向额外设备提供数据的方法

**Title (EN)**: PROVIDING DATA TO ADDITIONAL DEVICES IN A VIRTUAL MEETING  
**Pub. No.**: US20260095548

**Applicant**: Google LLC  
**Inventor**: [Kathleen Alexandra Bryan](https://patents.google.com/?inventor=Kathleen+Alexandra+Bryan&country=US&num=100&sort=new), [Shiblee Imtiaz Hasan](https://patents.google.com/?inventor=Shiblee+Imtiaz+Hasan&country=US&num=100&sort=new)  
**Publication Date**: 02.04.2026

**Abstract**:  
本发明提供了一种在虚拟会议中向额外设备提供数据的方法。该方法包括在虚拟会议期间呈现一个虚拟会议用户界面（UI），该界面包含一个或多个区域，每个区域对应由客户端设备生成的媒体流。该方法还包括获取一个指示，表明与第一参与者的第一客户端设备相关联的第一个额外设备在第一参与者的位置处可用。该方法还包括修改虚拟会议UI，以在对应于由第一客户端设备生成的第一媒体流的第一区域中呈现第一个额外设备的视觉指示。该方法还包括使第二客户端设备指示的第一数据被发送到第一个额外设备，以使第一个额外设备执行第一预定操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476837286_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及虚拟会议技术，具体为在虚拟会议中向额外设备提供数据的方法和系统。

**Background (发明背景)**:  
虚拟会议平台允许多个参与者通过网络连接并共享音频和视频流进行高效通信。现有的虚拟会议平台通常提供一个用户界面，显示每个参与者的视频流。然而，当参与者希望使用额外设备（如打印机）时，通常需要通过电子邮件或聊天界面发送数据，这会导致操作繁琐且分散会议注意力。

**Summary (发明总览)**:  
本发明提出了一种在虚拟会议中向额外设备提供数据的方法，通过在虚拟会议用户界面中直接显示可用额外设备的视觉指示，并允许参与者选择将数据直接发送到这些设备。该方法无需参与者使用其他系统或应用，也无需下载内容，从而简化了数据共享流程，提高了操作效率。本发明通过自动化和简化数据共享过程，增强了虚拟会议的用户体验。

**Key Innovation (核心创新)**:  
1. 在虚拟会议用户界面中集成额外设备指示功能，通过在对应于参与者视频流的区域中显示额外设备的视觉指示（如打印机图标），使其他参与者能够直观识别可用设备。
2. 实现用户界面交互功能，允许参与者通过点击视觉指示来选择对额外设备执行的操作，例如打印文件，从而无需使用其他应用或系统。
3. 提供数据直接传输机制，使选定的数据能够从发送者的客户端设备直接发送到接收者的额外设备，无需中间步骤或额外下载。
4. 通过虚拟会议系统自动识别和注册额外设备的位置和状态信息，确保数据发送的准确性和设备可用性。
5. 优化用户交互流程，通过在用户界面中提供操作选项，减少参与者之间的沟通成本，提高会议效率。
6. 支持多种额外设备类型，包括打印机、移动设备和虚拟现实（VR）设备，扩展了虚拟会议的应用场景。
7. 本发明适用于需要高效数据共享和设备操作的虚拟会议场景，如远程办公、在线教育和虚拟协作，能够显著提升用户体验和会议效率。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476837286)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260095548)**
<br/><br/>

---


<br/>

### 27. 基于TCP/IP架构的多处理器通信框架

**Title (EN)**: Multi-processor communication framework using TCP/IP architecture  
**Pub. No.**: US12591538

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Praveen Chebolu](https://patents.google.com/?inventor=Praveen+Chebolu&country=US&num=100&sort=new), [Venkateshwar Junnuthulla](https://patents.google.com/?inventor=Venkateshwar+Junnuthulla&country=US&num=100&sort=new), [Kranthi Thimmapuram](https://patents.google.com/?inventor=Kranthi+Thimmapuram&country=US&num=100&sort=new)  
**Publication Date**: 31.03.2026

**Abstract**:  
定义了一种基于传输控制协议/互联网协议（TCP/IP）架构的多处理器通信框架（MCF），用于异构处理节点之间的处理器间通信。该框架包括应用层、传输层、网络层和每个处理节点的处理器间通信（IPC）层。IPC层可通过电子设备内的物理通道或共享内存促进两个处理节点之间的数据传输。该框架支持多播、广播、单播和零拷贝功能，类似于TCP/IP协议栈。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476617925_1.jpg)

**Technical Field (技术领域)**:  
处理器间通信技术；
TCP/IP架构；
异构计算系统

**Background (发明背景)**:  
现代计算设备需要高性能和高能效以处理不同领域的应用，如音频处理、图像处理和通信标准。为此，计算设备通常包含多个处理节点，如应用处理器、微控制器单元、数字信号处理器、硬件加速器或图形处理单元等。然而，由于这些设备支持广泛的使用场景，处理节点之间的通信成为一项具有挑战性的任务。

**Summary (发明总览)**:  
本发明提出了一种基于TCP/IP架构的多处理器通信框架，通过分层设计实现异构处理节点间的通信。该框架利用IPC层在物理通道或共享内存中传输数据，并支持多播、广播、单播和零拷贝功能。其核心思路是通过TCP/IP协议栈的成熟机制优化处理器间通信效率，同时适应异构计算环境的需求。相较于传统方法，本发明在通信可靠性和数据传输效率方面提供了改进。

**Key Innovation (核心创新)**:  
1. 采用分层TCP/IP架构设计处理器处理器间通信，通过应用层、传输层、网络层和IPC层的协同工作，实现高效数据传输。
2. IPC层支持通过物理通道或共享内存进行数据传输，提供灵活的通信方式选择，适应不同硬件架构的需求。
3. 支持多播、广播和单播功能，扩展了通信框架的应用场景，使其能够处理复杂的通信需求。
4. 实现零拷贝功能，通过减少数据拷贝次数降低延迟并提高传输效率，适用于对实时性要求高的应用场景。
5. 通过TCP/IP协议栈的成熟机制提供可靠的通信保障，包括错误检测和纠正机制，确保数据传输的完整性和可靠性。
6. 框架设计考虑了异构处理节点之间的兼容性问题，通过标准化接口实现不同类型处理节点的无缝集成。
7. 该框架可应用于高性能计算设备，如多核处理器系统、异构计算平台和实时嵌入式系统，为复杂应用场景提供高效通信解决方案。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476617925)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12591538)**
<br/><br/>

---


<br/>

### 28. 使用递归实现非二的快速傅里叶变换（FFT）硬件算法的自动化硬件设计

**Title (EN)**: Automate hardware design using recursion in non-power of two fast fourier transform (FFT) hardware algorithms  
**Pub. No.**: US12591632

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Ryan Pinto](https://patents.google.com/?inventor=Ryan+Pinto&country=US&num=100&sort=new), [Ali M. Ficici](https://patents.google.com/?inventor=Ali+M.+Ficici&country=US&num=100&sort=new), [Jinkyu Choi](https://patents.google.com/?inventor=Jinkyu+Choi&country=US&num=100&sort=new)  
**Publication Date**: 31.03.2026

**Abstract**:  
本专利描述了实现非二的快速傅里叶变换（FFT）算法的编译器技术。该非二的FFT算法使用递归函数生成定点数字信号处理器（DSP）的计算模块硬件设计，并在计算模块之间路由数据。编译器接收指定索引序列和定点DSP位宽的输入，并执行一个过程。该过程通过递归循环分割序列，确定硬件设计中的乘法次数，并生成非二的FFT算法的跟踪图。该过程通过递归函数进入，并在递归循环递减到对应于基-3或基-2的指定值时退出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476618029_1.jpg)

**Technical Field (技术领域)**:  
数字信号处理领域，具体涉及非二的快速傅里叶变换（FFT）算法的硬件实现和自动化设计。

**Background (发明背景)**:  
随着数字媒体消费的增长，用户对高效信号处理的需求的需求日益增加。传统的FFT算法通常基于二的幂次方，这在处理非二的信号长度时效率较低。现有的非二的FFT算法在硬件实现上复杂且资源消耗大，难以满足现代电子设备对性能和功耗的要求。

**Summary (发明总览)**:  
本发明提出了一种基于递归的非二的FFT硬件设计自动化方法，通过递归函数生成计算模块和路由数据，从而实现高效的硬件设计。该方法通过递归分割输入序列，优化乘法操作数量，并生成跟踪图以指导硬件实现。与传统方法相比，本发明在处理非二的信号长度时具有更高的灵活性和效率，能够显著降低硬件资源消耗。

**Key Innovation (核心创新)**:  
1. 使用递归函数生成非二的FFT硬件设计，通过递归分割输入序列，实现对任意长度信号的高效处理。
2. 在硬件设计中确定乘法操作数量，通过优化乘法次数，降低硬件资源消耗和计算复杂度。
3. 生成非二的FFT算法的跟踪图，指导硬件实现，确保数据在计算模块之间的高效路由。
4. 采用递归循环机制，在递归过程中动态调整计算模块和路由路径，适应不同信号长度的需求。
5. 通过基-3和基-2的递归终止条件，确保算法在处理非二的信号长度时的稳定性和准确性。
6. 该方法能够自动生成硬件设计，减少人工设计的工作量，提高设计效率和准确性。
7. 本发明适用于需要处理非二的信号长度的应用场景，如无线通信、音频处理和图像处理等领域，能够提供更高效、更灵活的信号处理解决方案。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476618029)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12591632)**
<br/><br/>

---


<br/>

### 29. 曲面层压

**Title (EN)**: Curved surface lamination  
**Pub. No.**: US12591147

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Prithu Sharma](https://patents.google.com/?inventor=Prithu+Sharma&country=US&num=100&sort=new), [Alan Kleiman Shwarsctein](https://patents.google.com/?inventor=Alan+Kleiman+Shwarsctein&country=US&num=100&sort=new), [Adar Magen](https://patents.google.com/?inventor=Adar+Magen&country=US&num=100&sort=new)  
**Publication Date**: 31.03.2026

**Abstract**:  
本发明提供了一种方法，通过使用至少一个可变形元件对透镜组件的曲面施加力，使其与功能层叠结构粘合，形成层压组合体。该方法可用于制造增强现实或虚拟现实设备等装置，其中曲面可根据用户的眼科处方进行定制。本发明涉及基于处方光学元件的头戴式设备的制造方法及相关装置。此外，还公开了其他设备、方法、系统及计算机可读介质。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-04/US476617493_1.jpg)

**Technical Field (技术领域)**:  
光学制造技术领域，具体涉及曲面光学元件的层压工艺及头戴式显示设备制造。

**Background (发明背景)**:  
在光学设备制造中，尤其是头戴式显示设备，需要将光学元件与功能层叠结构精确结合。现有技术中，曲面光学元件的层压工艺存在精度不足、贴合不均匀等问题，难以满足定制化光学需求。本发明旨在解决曲面光学元件与功能层叠结构之间的高精度粘合问题，特别是针对基于用户处方光学需求的定制化光学设备。

**Summary (发明总览)**:  
本发明提出了一种通过可变形元件对曲面光学元件施加压力的层压方法，以实现光学组件与功能层叠结构的精确粘合。该方法利用定制化曲面光学元件的特性，适用于制造基于用户处方光学需求的头戴式显示设备。与现有技术相比，本发明提高了层压精度和贴合均匀性，能够更好地满足定制化光学设备的需求。

**Key Innovation (核心创新)**:  
1. 使用可变形元件对曲面光学元件施加压力：通过设计特定的可变形元件结构，实现对曲面光学元件的均匀施压，确保层压过程中光学表面不受损伤。
2. 定制化曲面光学元件：根据用户的眼科处方定制曲面光学元件的曲率，使其能够提供精确的光学矫正功能。
3. 高精度层压工艺：通过控制可变形元件的变形量和施力方式，实现光学元件与功能层叠结构的高精度贴合，确保光学性能的一致性。
4. 适用于头戴式显示设备：利用该层压方法制造的曲面光学元件可以集成到头戴式显示设备中，提供基于处方光学需求的增强现实或虚拟现实体验。
5. 提高贴合均匀性：通过可变形元件的弹性变形补偿曲面光学元件与功能层叠结构之间的不规则间隙，确保层压后的光学组件具有均匀的贴合效果。
6. 简化制造流程：相比传统层压工艺，本发明减少了复杂的对准和固定步骤，降低了制造成本和周期。
7. 应用于定制化光学设备：该技术特别适用于需要根据用户处方进行光学矫正的设备，如近视或远视矫正的头戴式显示设备，为用户提供更精准的光学体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476617493)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12591147)**
<br/><br/>

---



**Total Patents**: 29  
**Last Updated**: 20260404

---

The Patent Scoop Trio
