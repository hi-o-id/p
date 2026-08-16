---
layout: post
title: "其他专利小快报 2026-08-16"
date: 2026-08-16 16:51:53 +0800
categories: 其他
---

**New Patents**: 40  

---


<br/>

### 1. 触发快速服务小区变更

**Title (EN)**: TRIGGERING A FAST SERVING CELL CHANGE  
**Pub. No.**: US20260239114

**Applicant**: GOOGLE LLC  
**Inventor**: [Chih-Hsiang Wu](https://patents.google.com/?inventor=Chih-Hsiang+Wu&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
分布式基站的中央单元（CU）向分布式单元（DU）发送与用户设备（UE）连接的低层触发移动性（LTM）相关的CU-DU消息，该消息包括候选小区的小区标识符（ID）。CU接收来自DU的响应消息，该消息包括（i）候选小区的LTM配置和（ii）小区ID。CU通过DU向UE发送LTM配置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484650486_1.jpg)

**Technical Field (技术领域)**:  
无线通信领域，具体涉及快速服务小区变更的触发机制。

**Background (发明背景)**:  
在电信系统中，PDCP子层提供用户平面数据传输、加密和完整性保护等服务。现有技术中，当UE在RAN内从一个小区移动到另一个小区时，需要进行完整的L2和L1重置，导致延迟增加、开销增大和中断时间延长。3GPP提出了低层触发移动性（LTM）以减少快速服务小区变更的延迟和开销，但具体触发机制尚不明确。

**Summary (发明总览)**:  
本发明提出了一种通过分布式基站中央单元（CU）和分布式单元（DU）协作触发快速服务小区变更的方法。CU向DU发送包含候选小区标识的请求消息，DU返回相应的LTM配置，CU再将该配置发送给UE。通过这种方式，UE可以在不进行完整L2重置的情况下快速切换服务小区，从而减少延迟和中断时间。

**Key Innovation (核心创新)**:  
1. 通过CU-DU消息传递机制实现LTM配置的请求和响应，CU发送包含候选小区ID的请求消息，DU返回对应的LTM配置。
2. DU在接收到CU的请求后，生成并发送包含候选小区LTM配置和ID的响应消息，确保配置信息的准确性和及时性。
3. CU将DU提供的LTM配置通过DU转发给UE，实现快速服务小区变更，避免了完整的L2重置过程。
4. 该方法利用分布式基站架构的优势，通过CU和DU的协同工作，提高服务小区变更的效率和可靠性。
5. 通过减少L2重置带来的延迟和开销，显著改善UE在移动过程中的通信连续性和用户体验。
6. 该技术特别适用于多无线电双连接（MR-DC）场景，支持UE在不同基站节点之间快速切换。
7. 本发明可应用于5G及未来通信网络中的快速服务小区变更场景，为高移动性用户和关键任务通信提供更稳定的服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484650486)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260239114)**
<br/><br/>

---


<br/>

### 2. 暴露式相机架构

**Title (EN)**: EXPOSED CAMERA ARCHITECTURES  
**Pub. No.**: US20260235936

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Lidu Huang](https://patents.google.com/?inventor=Lidu+Huang&country=US&num=100&sort=new), [Peng Chen](https://patents.google.com/?inventor=Peng+Chen&country=US&num=100&sort=new), [Likai Li](https://patents.google.com/?inventor=Likai+Li&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
相机模块包括镜头组件和图像传感器。镜头组件用于将图像光线聚焦到图像传感器上。保护套筒至少部分地围绕镜头组件设置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484646980_1.jpg)

**Technical Field (技术领域)**:  
光学领域，具体涉及相机技术。
涉及消费电子设备中相机的防护设计。
特别针对可穿戴设备中的相机模块。

**Background (发明背景)**:  
消费电子设备中的相机容易受到环境危害的影响，例如跌落可能导致镜头错位或内部机械损坏。
灰尘、沙子或液体等污染物可能渗入相机外壳，损坏光学元件或电子元件。
在可穿戴设备中，对相机模块的防护需求更加迫切。
传统相机依赖保护盖板来抵御机械应力，但这种设计限制了相机的小型化和外观优化。

**Summary (发明总览)**:  
本发明提出了一种暴露式相机架构，通过移除传统相机模块的保护盖板，实现相机的小型化和外观优化。
该设计通过多种技术手段保护相机免受环境因素影响，例如防尘、防水、防刮擦和抗跌落。
暴露式相机提供了更广的视野，减少了视觉障碍，并提升了设计灵活性。
该方案适用于增强现实（AR）和虚拟现实（VR）等应用场景。

**Key Innovation (核心创新)**:  
1. 采用固定镜头部分设计，使镜头相对于相机模块机械控制轮廓（MCO）保持固定，从而防止划痕、潮气侵入、腐蚀和机械冲击。
2. 开发了具有减震机制的固定MCO和光学图像稳定（OIS）相机，以提高相机在环境压力下的耐用性。
3. 引入表面可变形自动对焦镜头，内嵌镜头中并具备减震功能，以实现更精确的自动对焦和稳定性。
4. 设计了可移动的自动对焦镜头组（单个或多个透镜元件），内嵌镜头中并具备减震功能，以适应不同场景下的对焦需求。
5. 采用传感器位移光学图像稳定技术，并结合减震机制，以减少相机在运动中的图像模糊。
6. 结合传感器位移光学图像稳定和嵌入式自动对焦技术，并具备减震功能，以提供综合的图像稳定性和对焦精度。
7. 暴露式相机设计减少了视觉障碍，扩大了视野，特别适用于AR和VR应用，为用户带来更清晰的视觉体验，并提升了产品的设计自由度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484646980)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260235936)**
<br/><br/>

---


<br/>

### 3. 通过上下文数据增强语言模型输入

**Title (EN)**: ENRICHING LANGUAGE MODEL INPUT WITH CONTEXTUAL DATA  
**Pub. No.**: US20260236678

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Haim SOMECH](https://patents.google.com/?inventor=Haim+SOMECH&country=US&num=100&sort=new), [Adi L. MILLER](https://patents.google.com/?inventor=Adi+L.+MILLER&country=US&num=100&sort=new), [Assaf AVIHOO](https://patents.google.com/?inventor=Assaf+AVIHOO&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明旨在通过向模型（例如大语言模型，LLM）提供补充语料数据作为输入来改进现有技术。因此，模型能够更准确地生成预测的分数或数据，因为它能够更好地区分自然语言概念的通用理解与特定领域（例如组织）概念。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647799_1.jpg)

**Technical Field (技术领域)**:  
自然语言处理（NLP），大语言模型（LLM），机器学习

**Background (发明背景)**:  
自然语言处理（NLP）是一种基于计算机的技术，用于理解、学习和生成自然人类语言内容。现有的NLP技术依赖于复杂的机器学习模型，但这些模型在缺乏足够上下文数据的情况下进行预测时往往不准确。此外，这些模型需要消耗大量计算资源，例如内存和CPU，因为它们需要处理数百万个资源并调整数十亿个参数。

**Summary (发明总览)**:  
本发明通过向机器学习模型提供补充语料数据（例如元数据）来改进现有技术。具体来说，模型接收文本语料和补充语料数据作为输入，从而生成更准确的预测结果，例如用户问题的答案、情感分析、自动摘要、文本生成、机器翻译或文档分类等。本发明通过提供更丰富的上下文数据，使模型能够更准确地理解查询的意图，从而提高预测的准确性。此外，本发明减少了计算资源的消耗，因为模型无需进行大规模微调。

**Key Innovation (核心创新)**:  
1. 通过向机器学习模型提供补充语料数据（例如元数据），使模型能够更准确地理解输入文本的上下文，从而提高预测的准确性。
2. 补充语料数据可以嵌入文本中，例如在特定词汇旁添加标签，或者作为独立文档提供，例如附加的电子邮件或组织文档。
3. 在一个示例中，"Red Sea"被识别为公司项目名称而非水体，因为补充语料数据提供了上下文信息，使模型能够正确理解查询意图。
4. 本发明减少了计算资源的消耗，因为模型无需进行大规模微调，从而降低了训练和部署的时间和成本。
5. 通过减少对数十亿参数和超参数的需求，本发明使模型更加紧凑，降低了内存和计算需求。
6. 本发明适用于需要高准确性和低延迟的应用场景，例如企业项目管理、客户服务和内容生成。
7. 通过提供更丰富的上下文数据，本发明使模型能够更好地理解特定领域的概念，从而在专业领域中提供更精准的预测结果。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647799)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236678)**
<br/><br/>

---


<br/>

### 4. 用于现实世界机器人控制的视觉-语言神经网络训练方法

**Title (EN)**: TRAINING VISION-LANGUAGE NEURAL NETWORKS FOR REAL-WORLD ROBOT CONTROL  
**Pub. No.**: US20260233388

**Applicant**: Google LLC  
**Inventor**: [Yevgen Chebotar](https://patents.google.com/?inventor=Yevgen+Chebotar&country=US&num=100&sort=new), [Tianhe Yu](https://patents.google.com/?inventor=Tianhe+Yu&country=US&num=100&sort=new), [Quan Ho Vuong](https://patents.google.com/?inventor=Quan+Ho+Vuong&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明涉及控制与环境交互的智能体（agent）的方法、系统及装置，包括编码在计算机存储介质上的计算机程序。在一个方面，该方法包括：接收描述机器人要在环境中执行的任务的用户文本序列；将该用户文本序列转换为用于视觉语言理解任务的标准化格式的输入文本序列；获取表征环境状态的观察图像；使用策略神经网络处理（i）标准化格式的输入文本序列和（ii）观察图像，以生成定义智能体响应观察图像应执行动作的策略输出；选择智能体应执行的动作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484644162_1.jpg)

**Technical Field (技术领域)**:  
人工智能与机器人技术领域，具体涉及基于视觉-语言模型的机器人控制技术。

**Background (发明背景)**:  
神经网络是机器学习模型，通过多层非线性单元预测输入的输出。一些神经网络包含隐藏层，其输出作为下一层的输入。现有的机器人控制方法通常依赖于特定领域的训练数据，难以处理复杂指令或新环境。本发明旨在解决机器人控制中泛化能力不足、对复杂指令理解有限的问题。

**Summary (发明总览)**:  
本发明提出了一种基于视觉-语言模型的机器人控制方法，通过将机器人指令和观察图像输入到策略神经网络中，生成机器人应执行的动作。该方法利用大规模预训练模型的知识，提升机器人对多样化任务的适应能力。其核心创新在于将机器人动作表示为文本标记，并结合机器人训练数据和网络规模的视觉-语言训练数据进行训练，从而实现更广泛的泛化能力和新兴功能，如符号理解、多语言处理和基本推理。

**Key Innovation (核心创新)**:  
1. 将机器人指令转换为标准化文本格式，使其能够被预训练的视觉-语言模型直接处理，从而实现端到端的机器人控制。
2. 采用大规模预训练模型的知识，结合机器人训练数据和网络规模的视觉-语言数据集进行训练，提升模型的泛化能力。
3. 通过将机器人动作表示为文本标记，使策略神经网络能够处理复杂的指令，如对特定数字或图标的物体操作。
4. 实现了对未见过的物体、背景和环境的良好适应能力，增强了机器人在新任务和新环境中的表现。
5. 增强了机器人对自然语言指令的理解能力，能够执行如"拿起最大的物体"或"将物体放在某个图标上"等复杂指令。
6. 相较于传统方法，本发明在更少的数据和计算资源下实现了更广泛的任务覆盖和性能提升。
7. 该技术可应用于智能家居、工业自动化等领域，使机器人能够更自然地与人类交互并执行复杂任务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484644162)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260233388)**
<br/><br/>

---


<br/>

### 5. 增强现实系统、方法和设备上的智能内容渲染

**Title (EN)**: SMART CONTENT RENDERING ON AUGMENTED REALITY SYSTEMS, METHODS, AND DEVICES  
**Pub. No.**: US20260237166

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Shengzhi Wu](https://patents.google.com/?inventor=Shengzhi+Wu&country=US&num=100&sort=new), [Alexander Faaborg](https://patents.google.com/?inventor=Alexander+Faaborg&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明提供了一种基于上下文的内容显示系统和方法。该系统包括一个具有显示器的设备，该显示器在可视区域内提供内容。设备包括一个摄像头，用于跟踪摄像头视野中捕获的现实环境场景。设备可确定场景中的兴趣区域，并对摄像头跟踪的场景执行对象识别。设备可根据对象识别和兴趣区域确定环境交互，并根据环境交互自适应地调整显示器提供的内容位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484648340_1.jpg)

**Technical Field (技术领域)**:  
增强现实技术领域，具体涉及基于上下文分析和智能内容渲染的增强现实系统。

**Background (发明背景)**:  
增强现实技术通过视觉设备（如头戴式显示器）为用户提供调整后的现实体验。然而，虚拟内容与现实场景的叠加可能导致干扰，影响用户体验。例如，叠加的全息内容可能遮挡手机屏幕或可穿戴显示器，导致用户难以专注于感兴趣的内容。此外，虚拟内容可能分散用户对现实世界互动的注意力。本发明旨在解决增强现实设备在区分用户意图（物理互动或虚拟互动）方面的不足，并提供基于上下文的智能内容渲染方案。

**Summary (发明总览)**:  
本发明提出了一种增强现实设备智能内容渲染方法，通过摄像头跟踪现实场景并识别用户兴趣区域，结合对象识别技术确定环境交互情况。基于环境交互，系统自适应调整显示器上内容的位置。例如，当检测到用户关注现实物体时，系统会移动或最小化虚拟内容以减少干扰；当用户重新关注显示器时，内容则恢复或放大。本发明通过结合视线跟踪和场景识别技术，实现了增强现实内容与现实环境的智能融合，提升了用户体验。

**Key Innovation (核心创新)**:  
1. 通过摄像头跟踪用户视线并识别场景中的兴趣区域，结合对象识别技术确定用户意图。
2. 根据用户视线和场景交互情况，自适应调整显示器上虚拟内容的位置，例如移动、缩放或隐藏内容。
3. 实现视线从显示器到现实场景的过渡检测，在用户关注现实物体时自动调整虚拟内容以减少干扰。
4. 采用机器学习算法进行环境交互的智能判断，提升对用户意图识别的准确性和响应速度。
5. 支持连续、实时的对象识别和场景分析，确保系统能够及时响应用户行为变化。
6. 可应用于头戴式设备、智能眼镜等增强现实设备，以及智能手机和游戏设备等手持设备。
7. 通过智能内容渲染技术，使用户在增强现实环境中更自然地与现实世界互动，提升沉浸感和使用体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484648340)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260237166)**
<br/><br/>

---


<br/>

### 6. 代表用户自动拨打电话

**Title (EN)**: AUTOMATING TELEPHONE CALL(S) ON BEHALF OF USER(S)  
**Pub. No.**: US20260238723

**Applicant**: GOOGLE LLC  
**Inventor**: [Sasha Goldshtein](https://patents.google.com/?inventor=Sasha+Goldshtein&country=US&num=100&sort=new), [Yoav Tzur](https://patents.google.com/?inventor=Yoav+Tzur&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一些实施例接收用户输入以发起与实体的电话呼叫，并确定语音助手是否能够代表用户自动执行该电话呼叫。在确定语音助手能够自动执行与实体的电话呼叫后，这些实施例可以在电话呼叫发起之前，通过客户端设备渲染自动电话呼叫建议元素。在接收到用户选择自动电话呼叫建议元素后，这些实施例可以确定在电话呼叫期间代表用户执行的任务，并使语音助手发起并执行电话呼叫以代表用户完成任务。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484650053_1.jpg)

**Technical Field (技术领域)**:  
自动语音交互技术领域，具体涉及语音助手自动拨打电话并执行任务的技术。

**Background (发明背景)**:  
用户通常通过手动拨号或使用软件应用发起电话呼叫，但与实体沟通时可能面临长时间等待或需要与交互式语音应答系统（IVR）进行复杂交互的问题。这不仅增加了电话网络流量，还浪费了计算和网络资源。现有的语音助手虽然可以自动执行电话呼叫，但用户可能不知道这一功能的存在。

**Summary (发明总览)**:  
本发明提出了一种自动化电话呼叫系统，通过语音助手代表用户自动发起并执行电话呼叫。该系统首先判断语音助手是否能够自动化处理用户的电话呼叫请求，并在用户确认后自动执行相关任务。系统通过分析用户与实体的历史交互或实体类型来推荐任务，并通过语音合成与转录技术实现高效的自动化沟通，从而减少用户操作并优化资源利用。

**Key Innovation (核心创新)**:  
1. 通过语音助手自动识别并建议用户是否需要自动化处理电话呼叫任务，提升用户对自动化功能的认知。
2. 在电话呼叫发起前，通过客户端设备渲染任务选择界面，允许用户选择或描述需要执行的任务，提高任务执行的准确性。
3. 利用自然语言处理技术解析用户输入的任务描述，并基于用户与实体的历史交互数据生成任务建议，提升任务推荐的智能化水平。
4. 通过语音合成技术生成与实体沟通的语音内容，并使用语音转录技术记录通话内容，确保沟通过程的可追溯性和准确性。
5. 在电话呼叫过程中提供用户加入通话的选项，允许用户在必要时介入通话过程，增强用户对自动化过程的控制力。
6. 根据实体的营业时间智能调整呼叫发起时间，避免在非工作时间发起呼叫，提升资源利用效率。
7. 该技术可应用于客户服务、预约确认、物流查询等场景，通过自动化处理减少用户等待时间并降低网络负载。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484650053)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260238723)**
<br/><br/>

---


<br/>

### 7. 包含多个光源耦合器的显示系统

**Title (EN)**: DISPLAY SYSTEM INCLUDING MULTIPLE LIGHT SOURCE INCOUPLER  
**Pub. No.**: US20260235880

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jie Li](https://patents.google.com/?inventor=Jie+Li&country=US&num=100&sort=new), [Miaomiao Xu](https://patents.google.com/?inventor=Miaomiao+Xu&country=US&num=100&sort=new), [Yu Shi](https://patents.google.com/?inventor=Yu+Shi&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一种用于近眼应用的显示系统可包括多个光源和一个几何反射波导（GRWG）。该系统可包括用于组合多个光源光的二向色镜，用于引导和复制组合光的折叠光学元件，以及用于将复制的光引导至眼球盒区域的输出光学元件。还公开了各种其他显示系统、波导配置和方法。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484646919_1.jpg)

**Technical Field (技术领域)**:  
近眼显示技术领域，具体涉及光学波导和光源耦合技术。

**Background (发明背景)**:  
近眼显示设备需要紧凑、高效的光学系统来提供高质量的图像。现有技术通常使用单一光源和简单的光学结构，难以满足复杂的光学需求。
现有系统可能存在光效低、图像质量差和体积大的问题。
本发明旨在提供一种改进的光学系统，以实现更高效的光耦合和更高的图像质量。

**Summary (发明总览)**:  
本发明提出了一种包含多个光源和几何反射波导的近眼显示系统。
通过二向色镜将多个光源的光进行组合，并利用折叠光学元件引导和复制该组合光。
输出光学元件将复制后的光引导至眼球盒区域。
相较于传统单光源系统，本发明提高了光效并优化了图像质量。
该设计还实现了更紧凑的光学结构，适合近眼设备应用。

**Key Innovation (核心创新)**:  
1. 采用二向色镜实现多光源光的精确组合，提高了光的利用率和色彩准确性。
2. 使用几何反射波导（GRWG）作为核心光学元件，通过其几何结构实现光的有效传播和分配。
3. 折叠光学元件的设计使得组合光能够在波导内多次复制，扩大了光束的覆盖范围。
4. 输出光学元件的优化设计确保了光能够高效地进入眼球盒区域，提升了显示的均匀性和亮度。
5. 通过多光源的协同工作，系统能够提供更广的色域和更高的亮度，适应不同的显示需求。
6. 该设计实现了光学系统的紧凑化，适合集成到轻量化的近眼设备中。
7. 应用于增强现实（AR）和虚拟现实（VR）设备时，能够提供更清晰、更逼真的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484646919)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260235880)**
<br/><br/>

---


<br/>

### 8. 具有平面内照明的眼动追踪系统

**Title (EN)**: EYE TRACKING SYSTEM WITH IN-PLANE ILLUMINATION  
**Pub. No.**: US20260236094

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Qi Zhang](https://patents.google.com/?inventor=Qi+Zhang&country=US&num=100&sort=new), [Chad Lichtenhan](https://patents.google.com/?inventor=Chad+Lichtenhan&country=US&num=100&sort=new), [Morteza Karami](https://patents.google.com/?inventor=Morteza+Karami&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
描述了一种具有光学组件平面内照明的眼动追踪系统。使用与近眼显示设备光学组件平面对齐的侧发光发光二极管（LED）来照亮用户的眼睛并生成可被眼动追踪摄像头检测到的反射亮点。近眼显示设备的波导显示器将计算机生成的内容投射到眼睛上。在LED和波导显示器之间放置一面镜子，以反射来自LED的光束朝向波导显示器，从而减少可能引起重影信号的反射亮点。设备的处理器根据捕获的带有反射亮点的眼睛图像确定眼睛的位置和注视方向，并生成计算机生成的内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647156_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及近眼显示设备的眼动追踪技术，具体为在光学组件平面内配置发光二极管（LED）以实现眼动追踪功能。

**Background (发明背景)**:  
随着虚拟现实（VR）、增强现实（AR）和混合现实（MR）等交互式内容的发展，近眼显示设备的需求日益增加。现有技术中，眼动追踪系统通常需要复杂的算法和硬件配置来准确捕捉用户的注视方向和位置，这增加了系统的复杂性和功耗。此外，矫正光学镜片的存在可能影响照明光束的准确性。

**Summary (发明总览)**:  
本发明提出了一种改进的眼动追踪系统，通过在光学组件平面内使用侧发光LED来照亮用户的眼睛，并利用镜子反射光束以减少重影信号。该系统通过提高照明效率并适应矫正光学镜片，简化了系统结构并降低了功耗，同时提升了眼动追踪的准确性。

**Key Innovation (核心创新)**:  
1. 采用侧发光LED与光学组件平面对齐进行照明，通过优化光源布局提高照明效率。
2. 使用镜子反射LED光束至波导显示器，减少反射亮点引起的重影信号问题。
3. 通过在光学组件中集成矫正光学镜片并调整LED光束角度，解决镜片引起的照明失真问题。
4. 利用边缘折射元件或镜片形状调整，进一步优化光束方向，确保照明准确性。
5. 通过处理器分析带有反射亮点的眼睛图像，精确确定眼睛位置和注视方向。
6. 整体系统设计降低了复杂性和功耗，同时提升了眼动追踪的可靠性和精度。
7. 该技术可应用于VR、AR和MR设备中，提供更精准的交互体验，尤其适用于需要高精度眼动追踪的虚拟环境导航和内容交互场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647156)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236094)**
<br/><br/>

---


<br/>

### 9. 客户端实时视频配音质量评估与主动响应

**Title (EN)**: DUBBING QUALITY ASSESSMENTS AND PROACTIVE RESPONSES FOR REAL-TIME VIDEO DUBBING ON A CLIENT DEVICE  
**Pub. No.**: US20260237400

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Utkarsh CHAUHAN](https://patents.google.com/?inventor=Utkarsh+CHAUHAN&country=US&num=100&sort=new), [Rupeshkumar Rasiklal MEHTA](https://patents.google.com/?inventor=Rupeshkumar+Rasiklal+MEHTA&country=US&num=100&sort=new), [Suhrid Kiran PALSULE](https://patents.google.com/?inventor=Suhrid+Kiran+PALSULE&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明描述了一种用于分析视频中配音音频片段（将音频翻译转换为语音）的框架，其中配音音频片段是实时生成的，包括在客户端设备上本地生成。例如，本发明描述了一种视频配音系统，该系统利用各种轻量级机器学习模型来确定实时生成的配音片段的配音质量（例如，配音质量评分），并识别低质量配音片段的原因（例如，低质量评分的根本原因）。此外，视频配音系统向视频播放器提供主动指示，以在低质量配音片段播放之前或播放期间发出信号。此外，视频配音系统可以在配音音频片段开始播放之前或播放时提供低质量配音片段的原因。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484648598_1.jpg)

**Technical Field (技术领域)**:  
视频处理技术领域，具体涉及实时视频配音质量评估与优化。

**Background (发明背景)**:  
随着视频在全球范围内的传播，语言障碍成为一个重要问题。许多人需要翻译才能理解视频内容，但并非所有视频都提供多语言音频轨道。现有的视频播放系统在提供自动翻译时面临挑战，例如配音质量不稳定和实时评估困难。

**Summary (发明总览)**:  
本发明提出了一种视频配音系统，通过在客户端设备上使用轻量级机器学习模型，实时评估配音音频片段的质量并识别低质量原因。该系统能够在低质量配音片段播放前或播放时向用户发出警告，并提供改进建议或自动采取措施以提升用户体验。与现有技术相比，本发明在实时性、准确性和资源利用效率方面具有显著优势。

**Key Innovation (核心创新)**:  
1. 利用轻量级机器学习模型在客户端设备上实时生成配音质量评分，确保配音质量评估的及时性和准确性。
2. 通过配音质量估计模型识别低质量配音片段的根本原因，例如翻译不准确、语音匹配不当或语速不当。
3. 在低质量配音片段播放前或播放时向视频播放器提供主动警告，使用户能够提前了解并做出选择。
4. 使用配音质量推理模型提供低质量配音的具体原因，帮助用户理解问题所在并做出相应调整。
5. 通过实时检测低质量配音片段并采取主动措施（如调整配音参数或重新生成配音），提高客户端设备的处理效率。
6. 减少用户因低质量配音而重复回放视频的次数，从而降低计算资源的浪费并提升用户体验。
7. 本发明可应用于实时视频流媒体平台、在线教育工具和全球化视频内容分发，为用户提供高质量的实时配音服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484648598)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260237400)**
<br/><br/>

---


<br/>

### 10. 基于头部运动的凝视跟踪校准

**Title (EN)**: CALIBRATING GAZE TRACKING BASED ON HEAD MOVEMENT  
**Pub. No.**: US20260236092

**Applicant**: GOOGLE LLC  
**Inventor**: [Jason Todd Spencer](https://patents.google.com/?inventor=Jason+Todd+Spencer&country=US&num=100&sort=new), [Qinge Wu](https://patents.google.com/?inventor=Qinge+Wu&country=US&num=100&sort=new), [Jim Marggraff](https://patents.google.com/?inventor=Jim+Marggraff&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一种头戴式设备可以根据用户至少一只眼睛的第一凝视方向确定第一位置，该头戴式计算设备安装在用户的头部。头戴式设备可以根据用户头部的运动确定第二位置。头戴式设备可以接收用户与第二位置相关的选择。头戴式设备可以根据第一方向、第二位置和选择生成校准调整。头戴式设备可以根据用户至少一只眼睛的第二凝视方向和校准调整确定第三位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647154_1.jpg)

**Technical Field (技术领域)**:  
头戴式设备技术领域，具体涉及虚拟现实、增强现实中的凝视跟踪校准技术。

**Background (发明背景)**:  
头戴式设备通过显示可选择图标在虚拟现实环境中创建用户界面，用户可以通过眼睛移动控制光标，头戴式设备跟踪用户眼睛的凝视方向。然而，凝视方向的跟踪可能不准确，导致光标位置与用户预期不符，影响交互体验。本发明旨在解决由于设备佩戴位置、用户眼睛位置差异或三角测量误差导致的凝视跟踪不准确问题。

**Summary (发明总览)**:  
本发明提出了一种基于头部运动的凝视跟踪校准方法。当用户认为光标位置不准确时，可以通过移动头部来调整光标位置，并在目标位置进行选择。头戴式设备根据头部运动和用户选择生成校准调整，从而提高未来基于凝视方向的定位准确性。该方法通过用户主动参与校准过程，动态调整凝视跟踪参数，提升交互精度。

**Key Innovation (核心创新)**:  
1. 通过用户头部运动触发校准过程，用户在光标位置不准确时主动调整光标位置。
2. 设备接收用户对调整后光标位置的选择，并基于此生成校准调整参数。
3. 结合用户凝视方向和校准调整参数，动态修正凝视跟踪模型，提升定位精度。
4. 在用户固定凝视方向一段时间后，设备自动检测并确认初始位置的误差。
5. 通过用户头部移动和凝视方向数据，设备实时更新校准参数，适应不同用户佩戴状态。
6. 该方法适用于虚拟现实、增强现实等头戴式设备应用场景，能有效解决因设备佩戴或用户个体差异导致的跟踪误差。
7. 提升用户与头戴式设备交互的准确性和流畅度，尤其在需要精确选择的应用中提供更可靠的体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647154)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236092)**
<br/><br/>

---


<br/>

### 11. 通过用户与自动化助手的交互生成复杂内容

**Title (EN)**: COMPOSITION OF COMPLEX CONTENT VIA USER INTERACTION WITH AN AUTOMATED ASSISTANT  
**Pub. No.**: US20260238606

**Applicant**: GOOGLE LLC  
**Inventor**: [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new), [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明涉及一种自动化助手，用于根据用户输入生成复杂消息。每条消息根据用户指示自动化助手向收件人发送消息的输入选择相应的模板来创建。此外，模板的某些部分可以根据一个或多个用户向一个或多个收件人发送的先前消息指定特定内容。这样，当用户请求自动化助手发送消息时，自动化助手可以选择相关模板并相应地填充模板。在某些情况下，分配给选定模板的某些内容可以来自各种来源。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484649925_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及自动化助手生成复杂消息内容的技术。

**Background (发明背景)**:  
人机交互中，用户常通过语音或文本与自动化助手进行对话。然而，当用户需要发送复杂消息时，现有自动化助手难以处理额外的复杂性，用户不得不依赖键盘界面手动创建复杂消息。这不仅延长了消息创建时间，还消耗了额外的计算资源。

**Summary (发明总览)**:  
本发明提出了一种自动化助手，通过基于用户请求和上下文选择并填充内容模板来生成复杂消息。自动化助手根据用户的历史消息数据选择合适的模板，并动态填充模板中的动态部分，例如附加文件地址或特定内容。此外，自动化助手可以根据用户偏好和上下文调整消息的语气，例如在必要时添加紧急语气。

**Key Innovation (核心创新)**:  
1. 通过分析用户请求和上下文数据，自动化助手能够智能选择最合适的模板来生成消息内容。
2. 模板分为静态和动态部分，动态部分根据用户请求和上下文数据动态填充，例如附加文件地址或特定内容。
3. 利用机器学习模型处理用户语音输入，生成嵌入并与模板嵌入进行匹配，以选择最匹配的模板。
4. 根据用户的历史消息数据，自动化助手能够学习用户偏好的消息结构和内容，并自动应用到新消息中。
5. 自动化助手能够根据用户请求和上下文调整消息的语气，例如在必要时添加紧急语气，以满足用户对消息语气的期望。
6. 通过分析用户对先前消息的回复，自动化助手能够生成更符合用户期望的回复内容，例如在活动通知中请求确认。
7. 本发明可应用于邮件、消息应用等场景，帮助用户高效创建复杂消息，同时提升用户体验和消息质量。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484649925)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260238606)**
<br/><br/>

---


<br/>

### 12. 使用微调小型语言模型的内容增强

**Title (EN)**: CONTENT AUGMENTATION USING FINE-TUNED SMALL LANGUAGE MODELS  
**Pub. No.**: US20260237196

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Biyi FANG](https://patents.google.com/?inventor=Biyi+FANG&country=US&num=100&sort=new), [Yibo SUN](https://patents.google.com/?inventor=Yibo+SUN&country=US&num=100&sort=new), [Xiao TU](https://patents.google.com/?inventor=Xiao+TU&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一种增强服务接收来自客户端的请求，以针对请求中包含的图像文件编码的内容建议一组操作。该服务向内容生成服务发送第一个请求以获取该组操作，其中包括一个任务小型语言模型（SLM）基于图像文件内容生成该组操作的第一提示。增强服务向客户端回复至少部分操作集。增强服务从客户端接收对至少部分操作集中选定操作的指示，并向内容生成服务发送第二个请求以执行选定操作。第二个请求包括一个任务大型语言模型（LLM）执行选定操作全部或部分的第二提示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484648373_1.jpg)

**Technical Field (技术领域)**:  
计算机硬件和软件领域，具体涉及使用小型语言模型进行内容增强。

**Background (发明背景)**:  
内容增强是指通过添加相关信息、建议或操作来增强或丰富数字内容，以提高其价值和可用性。现有的内容增强服务通常依赖大型语言模型来提供基于用户提供内容的上下文相关操作建议。然而，当数据类型与其实际内容不匹配时，语言模型可能会推荐不相关的操作，例如在处理图像数据表时推荐图像编辑操作。这种不匹配会降低语言模型提供有意义和上下文相关操作建议的有效性。

**Summary (发明总览)**:  
本发明提出了一种结合小型和大型语言模型的内容增强方法。首先，使用小型语言模型快速生成基于图像文件内容的操作建议集，并将其呈现给用户供选择。然后，根据用户选择的操作，使用大型语言模型执行复杂任务。这种方法利用了小型语言模型的高效性和大型语言模型的强大处理能力，优化了系统的性能、可扩展性和成本效益。

**Key Innovation (核心创新)**:  
1. 采用小型语言模型（SLM）生成初始操作建议集，利用其快速响应和低资源消耗的特点，确保系统能够快速处理用户请求。
2. 通过对SLM进行微调，使用包含图像内容和已知操作标签的创新训练数据集，使SLM能够根据图像内容准确预测相关操作。
3. 在SLM的训练过程中，使用大型语言模型生成额外的操作，并通过反向传播调整SLM的权重，以提高预测准确性。
4. 使用大型语言模型（LLM）执行用户选择的复杂操作，利用其强大的处理能力确保任务执行的精确性和高质量。
5. 通过分离SLM和LLM的任务，系统能够在保持高效性的同时降低运营成本，特别是在大规模云部署或本地设备部署中。
6. 该方法适用于多种应用场景，例如文档分析、产品标签处理等，能够根据图像内容提供定制化的操作建议，如文本提取、翻译、价格比较等。
7. 整体上，本发明通过结合SLM和LLM的优势，提供了一种高效、可扩展且成本效益高的内容增强解决方案，适用于需要处理大量图像数据的应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484648373)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260237196)**
<br/><br/>

---


<br/>

### 13. 基于大语言模型生成的自然语言输出流式处理以减少渲染延迟

**Title (EN)**: STREAMING OF NATURAL LANGUAGE (NL) BASED OUTPUT GENERATED USING A LARGE LANGUAGE MODEL (LLM) TO REDUCE LATENCY IN RENDERING THEREOF  
**Pub. No.**: US20260236495

**Applicant**: GOOGLE LLC  
**Inventor**: [Martin Baeuml](https://patents.google.com/?inventor=Martin+Baeuml&country=US&num=100&sort=new), [Yanping Huang](https://patents.google.com/?inventor=Yanping+Huang&country=US&num=100&sort=new), [Wenhao Jia](https://patents.google.com/?inventor=Wenhao+Jia&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明涉及减少使用大语言模型（LLM）生成和/或渲染自然语言（NL）输出的延迟。系统的处理器可以：接收与客户端设备相关的NL输入，并利用LLM生成NL输出。NL输出可以是以流的形式存在，因为它包含多个片段，并且是按片段逐个生成的。在某些实现中，系统在生成第二个片段（及后续片段）时选择流式NL输出的第一个片段包含在流中，以减少在渲染之前评估整个NL输出的延迟。在这些实现的某些版本中，系统在生成第二个片段（及后续片段）时使客户端设备渲染第一个片段，以进一步减少渲染延迟。系统的处理器可以在客户端设备本地实现，也可以远程实现（例如，在与客户端设备通信连接的远程服务器上）。在某些实现中，生成NL输出流时，系统可以使用LLM处理NL输入以生成LLM输出流。LLM输出流可以包括例如对预测响应NL输入的单词或短语序列的概率分布。此外，LLM输出可以被视为LLM输出流，因为随着使用LLM处理NL输入的每个单词或短语，对预测响应NL输入的单词或短语序列的概率分布可以持续更新，并针对之前选择的NL输出流片段进行更新。此外，系统可以根据LLM输出流确定LLM输出流第一片段的多个候选片段，并基于一个或多个排名标准选择第一片段包含在NL输出流中。此外，系统可以根据选择包含在NL输出流中的第一片段来更新LLM的状态。在这些实现中，随着每个片段被选择包含在NL输出流中，片段可能不会在客户端设备上渲染，直到NL输出流完成。然而，随着每个片段被选择包含在NL输出流中，系统可以使客户端设备预取每个片段以供后续渲染（例如，通过API服务器）。通过在这些实现中更新LLM的状态，LLM可以利用第一片段作为前缀在进一步处理NL输入时，限制在确定基于LLM输出流的LLM输出流第二片段的多个候选片段时的概率分布搜索空间，并基于一个或多个排名标准选择第二片段包含在NL输出流中。此外，通过按片段逐个选择每个片段包含在NL输出流中，随着NL输入继续被LLM处理，系统无需在NL输入处理完成后选择整个NL输出，从而减少在客户端设备上渲染NL输出的延迟。如上所述，在这些实现中，NL输出流可能不会在客户端设备上渲染，直到NL输出流完成。例如，在各种实现中，最初生成的NL输出流可能由于保证原因、准确性原因、质量原因、连贯性原因和/或其他原因而不适合在客户端设备上渲染。因此，在这些实现的某些版本中，系统可以重新选择包含在NL输出流中的一个或多个替代片段，或者完全重新处理NL输入以生成替代的NL输出流（例如，通过修改LLM的参数，如温度参数）。尽管如此，在附加或替代实现中，每个片段可以在选择包含在NL输出流中时以流式方式在客户端设备上渲染。例如，在响应选择第一片段包含在NL输出流中时，不仅客户端设备预取第一片段，而且第一片段也在客户端设备上渲染。值得注意的是，当系统仍在处理NL输入并选择第二片段时，第一片段可以在客户端设备上渲染。通过在这些实现中以流式方式使每个片段渲染，系统使形成一个或多个（例如，全部）NL输出流片段在NL输入处理完成之前被渲染，从而进一步减少在客户端设备上渲染NL输出的延迟。在实现中，每个片段在选择包含在NL输出流中时在客户端设备上渲染，系统可以进一步使客户端设备渲染一个停止流式处理的可选择元素以及NL输出流。停止流式处理的可选择元素，当被选择时，可以使系统停止处理NL输入和/或停止渲染当前正在渲染的NL输出流片段（例如，停止渲染第一片段、第二片段或任何其他正在渲染的片段，当选择被接收时）。例如，如果用户意识到NL输入没有产生用户最初提供NL输入时想要的NL输出流，那么用户可以选择停止流式处理的可选择元素以停止任何进一步的处理和/或渲染。这使用户能够改进NL输入以产生用户想要的额外NL输出流。通过在这些实现中提供停止流式处理的可选择元素，系统可以使人机对话以更快速和高效的方式结束。尽管上述实现是关于LLM输出是LLM输出流（例如，对预测响应NL输入的单词或短语序列的概率分布是持续更新的），但应理解，这并不意味着限制。例如，在附加或替代实现中，任何之前选择的片段都可以作为上下文在重新处理NL输入时与上下文一起使用。在这些实现中，上下文可以有效地使任何后续片段相对于之前选择的片段被确定。然而，在这些实现中，对预测响应NL输入的单词或短语序列的概率分布可能不会持续更新。相反，在这些实现中，生成相应的额外概率分布对预测响应NL输入的单词或短语序列，并根据上述相同或类似的方式选择后续片段。上述描述提供了本公开的一些实现的概述。对这些实现和其他实现的进一步描述将在下面更详细地描述。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647598_1.jpg)

**Technical Field (技术领域)**:  
自然语言处理领域
大语言模型应用
流式输出技术

**Background (发明背景)**:  
大语言模型（LLM）是一类能够执行各种自然语言处理任务的机器学习模型，例如语言生成、机器翻译和问答。
LLM通常在大量多样化的数据上进行训练，包括网页、电子书、软件代码、电子新闻文章和机器翻译数据。
然而，使用LLM生成自然语言输出时会产生额外的延迟，这可能会延长用户与LLM的交互时间，影响用户体验。
因此，需要一种减少使用LLM时的延迟的方法。

**Summary (发明总览)**:  
本发明提出了一种通过流式处理大语言模型生成的自然语言输出以减少延迟的方法。
系统将自然语言输出分解为多个片段，并按顺序逐个生成和渲染。
在生成后续片段的同时，系统会提前选择并渲染当前片段，从而减少整体延迟。
这种方法允许用户在处理过程中逐步接收和查看输出内容。
相较于传统方法，本发明通过分段处理和提前渲染显著降低了延迟。

**Key Innovation (核心创新)**:  
1. 将自然语言输出分解为多个片段并按顺序生成，实现流式处理。
2. 在生成后续片段的同时，提前选择并渲染当前片段，减少延迟。
3. 通过客户端设备预取片段，进一步优化渲染速度。
4. 引入LLM状态更新机制，使后续片段的生成基于已渲染的片段内容。
5. 提供停止流式处理的可选择元素，允许用户在中途中断处理以调整输入。
6. 适用于需要实时交互的应用场景，如智能助手和实时翻译服务。
7. 通过分段处理和提前渲染，显著提升用户体验并减少用户等待时间。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647598)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236495)**
<br/><br/>

---


<br/>

### 14. 数字毛刺传感器

**Title (EN)**: Digital Glitch Sensor  
**Pub. No.**: US20260235672

**Applicant**: Google LLC  
**Inventor**: [Prathamesh Ramesh Save](https://patents.google.com/?inventor=Prathamesh+Ramesh+Save&country=US&num=100&sort=new), [Vinoth Kumar Deivasigamani](https://patents.google.com/?inventor=Vinoth+Kumar+Deivasigamani&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明涉及用于执行动态前端受害化过程的系统和方法，包括编码在计算机存储介质上的计算机程序。在一个方面中，系统包括一个数字毛刺检测器，该检测器包含一对由时钟信号驱动的移位反馈寄存器，以及配置为在移位反馈寄存器对的输出不同步时检测毛刺的控制逻辑。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484646688_1.jpg)

**Technical Field (技术领域)**:  
数字电路故障检测技术，具体涉及数字电路中的时钟频率和电压毛刺检测。

**Background (发明背景)**:  
数字电路在时钟信号异常时可能发生故障或性能下降，例如时钟频率过高或电压超出正常范围。传统毛刺检测方法复杂、昂贵且功耗高，难以适用于对功耗敏感的设备，如手机。此外，这些方法通常不适合低功耗技术，如动态电压和频率调节（DVFS）。

**Summary (发明总览)**:  
本发明提出了一种用于检测数字电路中各种类型毛刺的数字毛刺传感器。该传感器通过实现一对线性反馈移位寄存器（LFSR）来检测电路违规导致的寄存器不同步，从而实现毛刺检测。该方案具有结构简单、功耗低的特点，能够在不增加额外电路分析工作的情况下支持动态电压和频率调节（DVFS）。

**Key Innovation (核心创新)**:  
1. 采用线性反馈移位寄存器（LFSR）对作为核心检测单元，通过检测寄存器对不同步来识别电路毛刺。
2. 设计了一种低功耗电路结构，利用简单的移位反馈机制实现毛刺检测，降低了功耗和硬件复杂度。
3. 能够检测多种类型的毛刺，包括时钟频率毛刺、欠压毛刺和过压毛刺，提高了检测的全面性。
4. 通过简化电路结构，减少了传统毛刺检测方法中常见的复杂性和高功耗问题。
5. 支持动态电压和频率调节（DVFS），无需额外的电路特性分析工作，提升了系统的灵活性。
6. 适用于对功耗敏感的设备，如移动设备，通过低功耗设计延长设备续航时间。
7. 提高了数字电路的整体安全性和稳定性，通过及时检测毛刺防止设备执行意外或未授权的操作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484646688)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260235672)**
<br/><br/>

---


<br/>

### 15. 扩展现实系统中的等距输入

**Title (EN)**: ISOMETRIC INPUTS FOR EXTENDED-REALITY SYSTEMS  
**Pub. No.**: US20260236099

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Eric Trautmann](https://patents.google.com/?inventor=Eric+Trautmann&country=US&num=100&sort=new), [Diego Adrian Gutnisky](https://patents.google.com/?inventor=Diego+Adrian+Gutnisky&country=US&num=100&sort=new), [David Sussillo](https://patents.google.com/?inventor=David+Sussillo&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一种可穿戴设备包括神经肌肉传感器和处理器。神经肌肉传感器用于检测手部肌肉收缩的神经肌肉信号。处理器接收该信号并基于信号确定手部的一个或多个手指是否执行了等距收缩。处理器还确定这些等距收缩是否与扩展现实设备上的特定输入相关联，该设备被配置为响应特定输入执行特定操作。此外，处理器在确定等距收缩与特定输入相关联时，向扩展现实设备发送该特定输入的指示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647162_1.jpg)

**Technical Field (技术领域)**:  
扩展现实技术领域，具体涉及基于手部等距收缩的输入机制。

**Background (发明背景)**:  
现代扩展现实系统允许用户通过控制器或空中手势与虚拟内容交互，但这些输入机制可能笨重、不直观或不便。现有技术需要更创新的输入方式以提升用户体验。

**Summary (发明总览)**:  
本发明利用神经肌肉信号检测手部肌肉的等距收缩，并将其作为扩展现实系统的输入信号。通过将任何表面或物体转化为虚拟按钮或控制装置，用户无需依赖传统控制器即可进行交互。该方法通过分析肌肉信号识别用户意图，并将其转化为设备操作指令，从而实现更自然和直观的用户交互体验。

**Key Innovation (核心创新)**:  
1. 使用神经肌肉传感器检测手部肌肉的等距收缩信号，实现对用户意图的精确识别。
2. 将表面或物体转化为虚拟控制装置，用户可通过等距收缩进行交互，无需传统控制器。
3. 通过分析肌肉信号确定用户执行的特定操作，例如点击、滑动或旋转等。
4. 处理器将检测到的等距收缩与扩展现实设备上的特定输入关联，实现无缝交互。
5. 支持多种输入方式，包括空中手势和表面接触手势，提供灵活的用户交互选择。
6. 可穿戴设备与扩展现实头戴设备协同工作，通过无线通信传输输入指令。
7. 该技术可应用于虚拟现实、增强现实和混合现实场景，提供更自然和直观的用户交互方式，提升沉浸感和操作效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647162)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236099)**
<br/><br/>

---


<br/>

### 16. 虚拟和增强现实系统中的时序手势识别

**Title (EN)**: TEMPORAL GESTURE RECOGNITION FOR VIRTUAL AND AUGMENTED REALITY SYSTEMS  
**Pub. No.**: US20260237198

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Paul Anthony Crook](https://patents.google.com/?inventor=Paul+Anthony+Crook&country=US&num=100&sort=new), [Xiaohu Liu](https://patents.google.com/?inventor=Xiaohu+Liu&country=US&num=100&sort=new), [Francislav P. Penov](https://patents.google.com/?inventor=Francislav+P.+Penov&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一种用于虚拟和增强现实环境中的手势识别计算机实现方法包括接收与用户在不同时间点的手势输入相关联的第一和第二信号，这些信号基于VR头显或AR眼镜的传感器生成的数据。使用至少一个处理器，基于这些信号和时间信息识别用户意图，用户意图基于与手势输入相关联的手势标识符。基于用户意图生成第三信号，并根据第三信号在VR头显或AR眼镜上执行任务。手势输入可能包括眼睛运动、手部动作、手指动作（如捏合手势）或它们的组合，由摄像头检测。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484648375_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及虚拟现实和增强现实技术，具体为基于时序手势识别的智能交互系统。

**Background (发明背景)**:  
现有的智能助手系统主要依赖文本、语音或图像等用户输入来提供信息或服务。然而，在虚拟和增强现实环境中，用户更倾向于使用手势等自然交互方式。现有的手势识别技术通常依赖于通用模型，难以准确识别特定用户的个性化手势意图，尤其是在用户使用非标准手势或手势意图不明确的情况下。

**Summary (发明总览)**:  
本发明提出了一种基于时序信息的手势识别方法，通过分析用户在不同时间点的手势输入和语音输入，识别用户意图并执行相应任务。该方法利用个性化手势分类模型，结合用户的语音和手势输入进行训练，从而提高手势识别的准确性和用户交互的自然性。与传统方法相比，本发明能够更好地适应用户的个性化手势习惯，并支持更丰富的交互方式。

**Key Innovation (核心创新)**:  
1. 通过联合分析用户的手势输入和语音输入，识别用户意图，解决了传统方法中仅依赖手势识别准确率低的问题。
2. 利用时间信息构建手势输入的特征表示，将手势的时序特性和上下文信息纳入识别过程，提高了识别的准确性。
3. 训练个性化的手势分类模型，通过结合用户的语音和手势输入，生成用户特定的手势-意图关联模型，从而适应用户的个性化手势习惯。
4. 采用自然语言理解（NLU）模块解析用户的语音输入，并将其与手势输入关联，确保识别过程更加智能和上下文感知。
5. 通过对用户输入进行特征建模，将手势的组成部分和时序信息融入特征表示，增强了手势分类的可靠性和鲁棒性。
6. 该方法可应用于虚拟现实和增强现实设备，使用户能够通过手势与系统进行更自然和直观的交互。
7. 提升了用户在使用智能助手时的体验，使用户能够通过手势执行复杂任务，如控制虚拟对象或与虚拟环境互动。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484648375)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260237198)**
<br/><br/>

---


<br/>

### 17. 基于跨域行为数据的序列推荐方法

**Title (EN)**: SEQUENTIAL RECOMMENDATION BASED ON CROSS-DOMAIN BEHAVIOR DATA  
**Pub. No.**: US20260236765

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ning WU](https://patents.google.com/?inventor=Ning+WU&country=US&num=100&sort=new), [Ming GONG](https://patents.google.com/?inventor=Ming+GONG&country=US&num=100&sort=new), [Linjun SHOU](https://patents.google.com/?inventor=Linjun+SHOU&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明提出了一种基于跨域行为数据的序列推荐方法、装置和计算机可读介质。通过目标用户的过往内容项序列生成目标用户表示，从网络应用的日志中提取跨域行为序列集，并生成对应的跨域序列表示集。从跨域序列表示集中检索与目标用户表示相似的序列表示集，并基于目标用户表示和相似序列表示集预测目标用户与候选内容项集的交互概率集。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647895_1.jpg)

**Technical Field (技术领域)**:  
推荐系统技术领域，具体涉及跨域行为数据的序列推荐方法。

**Background (发明背景)**:  
随着网络技术的发展和信息的增长，推荐系统在许多在线服务中发挥着越来越重要的作用。现有推荐系统通常基于单一领域的行为数据预测用户兴趣，忽略了跨域行为数据中丰富的用户兴趣信息。由于不同应用的用户标识可能不同，现有方法难以有效利用跨域行为数据。

**Summary (发明总览)**:  
本发明提出了一种基于跨域行为数据的序列推荐方法，通过生成目标用户表示并结合跨域行为数据来增强推荐效果。具体实现路径包括从网络应用日志中提取跨域行为序列，生成跨域序列表示，并利用相似序列表示来推断目标用户兴趣，从而提升推荐准确性。该方法无需用户在不同应用中拥有统一标识，能够更全面地利用跨域行为数据。

**Key Innovation (核心创新)**:  
1. 通过跨域行为数据增强目标用户表示，利用跨域行为数据中的丰富信息提升推荐准确性。
2. 采用实体链接技术将跨域行为序列映射为跨域内容项序列，确保跨域数据的有效整合。
3. 设计基于注意力机制的筛选器，在内容项级别计算注意力权重，筛选与目标用户相关的表示，减少无关内容的影响。
4. 利用序列增强策略和动量对比学习机制训练推荐模型，提升模型的鲁棒性和编码能力。
5. 通过检索与目标用户表示相似的跨域序列表示集，动态更新用户兴趣模型，适应用户行为变化。
6. 该方法无需用户在不同应用中拥有统一标识，适用范围更广，可用于浏览器、视频应用、新闻应用等多种场景。
7. 预测目标用户与候选内容项集的交互概率集，为用户提供更精准的推荐内容，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647895)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236765)**
<br/><br/>

---


<br/>

### 18. 生产环境中加速容器启动的方法

**Title (EN)**: ACCELERATING CONTAINER INITIATION IN PRODUCTION ENVIRONMENTS  
**Pub. No.**: US20260236409

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Yi Jun LIU](https://patents.google.com/?inventor=Yi+Jun+LIU&country=US&num=100&sort=new), [Esteban REY LONDONO](https://patents.google.com/?inventor=Esteban+REY+LONDONO&country=US&num=100&sort=new), [Aviral TAKKAR](https://patents.google.com/?inventor=Aviral+TAKKAR&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明涉及用于加速生产环境中容器启动的方法、设备及产品，包括：基于在生产环境中发出的与容器相关的一个或多个输入/输出（I/O）操作，识别出足以使主机操作系统启动容器的数据范围；在接收到启动容器的请求时，提供该数据范围，使得主机操作系统能够基于提供的数据范围启动容器，而无需提供容器的完整数据集的其他部分。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647502_1.jpg)

**Technical Field (技术领域)**:  
本发明属于容器化软件部署技术领域，具体涉及容器启动加速技术。

**Background (发明背景)**:  
现代计算机系统广泛采用基于容器的架构，通过软件容器提供应用程序的隔离执行环境。然而，下载和初始化容器化应用程序通常需要大量系统资源、带宽和时间，导致性能下降和用户体验不佳。现有的容器启动方法，如下载多个压缩层并解压，可能导致网络瓶颈和数据碎片化问题。

**Summary (发明总览)**:  
本发明提出了一种通过选择性数据检索来加速容器启动的方法。其核心思路是识别启动容器所需的关键数据范围，并在启动请求时提供这些数据，而不是传输整个容器镜像。通过分析容器数据访问模式并利用本地缓存机制，本发明能够减少网络请求次数和带宽消耗，从而显著加快容器启动速度。相较于传统方法，本发明在保持透明性的同时提升了容器启动效率。

**Key Innovation (核心创新)**:  
1. 通过分析生产环境中容器启动时的I/O操作，识别启动容器所需的关键数据范围，从而避免传输整个容器镜像。
2. 利用容器数据访问模式的分析结果，生成使用配置文件，用于指导后续容器部署时的数据预取。
3. 实现本地缓存机制，存储频繁访问的数据，减少重复的网络请求，提高数据获取效率。
4. 采用实时分析技术，动态调整数据预取策略，以适应不同容器实例的启动需求。
5. 在不修改现有应用程序和部署流程的情况下，通过透明优化提升容器启动性能。
6. 通过减少网络请求数量和带宽消耗，降低网络瓶颈和数据碎片化问题，提升整体系统稳定性。
7. 本发明特别适用于云服务环境，能够帮助云服务提供商提升容器化应用部署效率，从而增强用户粘性和服务竞争力。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647502)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236409)**
<br/><br/>

---


<br/>

### 19. 可穿戴智能设备上的多模态搜索

**Title (EN)**: MULTIMODAL SEARCH ON WEARABLE SMART DEVICES  
**Pub. No.**: US20260236526

**Applicant**: GOOGLE LLC  
**Inventor**: [Bhanu Prakash Reddy Guda](https://patents.google.com/?inventor=Bhanu+Prakash+Reddy+Guda&country=US&num=100&sort=new), [Dia Kharrat](https://patents.google.com/?inventor=Dia+Kharrat&country=US&num=100&sort=new), [Anna Galusza](https://patents.google.com/?inventor=Anna+Galusza&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
根据至少一种实现方式，一种方法包括在可穿戴设备上获取查询并识别与查询相关的上下文信息，该上下文信息包括由可穿戴设备捕获的一组图像。该方法进一步包括基于查询和上下文生成至少一个搜索，并获取至少一个搜索结果。该方法还基于至少一个搜索结果生成对查询的响应，并将响应提供给可穿戴设备用户。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647632_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及可穿戴智能设备领域，具体涉及增强现实（AR）、虚拟现实（VR）和混合现实（MR）设备的多模态搜索技术。

**Background (发明背景)**:  
增强现实（XR）设备融合了物理和虚拟世界，包括虚拟现实（VR）、增强现实（AR）和混合现实（MR）技术。这些设备通过完全替换现实世界（VR）、在现实世界叠加数字内容（AR）或无缝融合数字和物理元素（MR）来提供沉浸式体验。然而，现有技术中存在难以准确理解用户查询意图并生成相关响应的技术问题。

**Summary (发明总览)**:  
本发明提出了一种在可穿戴智能设备上实现多模态搜索的方法，通过结合用户查询和设备捕获的上下文信息（如图像、传感器数据等），生成更精准的搜索请求并提供相关响应。该方法利用设备传感器、用户配置文件以及自然语言处理技术来理解用户意图，并通过网络搜索或设备内数据处理获取结果，最终生成并提供用户所需的响应。这种方法相较于传统搜索方式，能够更全面地利用设备感知能力，提升搜索结果的相关性和用户体验。

**Key Innovation (核心创新)**:  
1. 结合用户查询和设备捕获的图像及其他上下文信息（如传感器数据、用户位置、活动历史等），生成更全面的搜索请求。
2. 利用设备上的传感器数据（如加速度计、陀螺仪、深度传感器等）来捕捉用户环境和行为，提供更精准的上下文信息。
3. 采用名词短语提取和大型语言模型（LLM）技术，精准识别用户查询中的实体或兴趣点，从而提升搜索的准确性。
4. 通过反向图像搜索技术，利用设备捕获的图像进行视觉元素分析，以获取与图像相关的详细信息或识别对象。
5. 使用LLM对搜索结果进行处理和综合，生成连贯且信息丰富的响应，并通过设备显示、音频或其他输出方式提供给用户。
6. 在处理过程中，通过对候选响应的评分和排名机制（如相关性、准确性、连贯性等），选择最优的响应结果。
7. 本发明可应用于智能眼镜、耳机、手表等可穿戴设备，为用户提供更智能、个性化的搜索体验，尤其适用于需要实时信息获取的场景，如导航、购物和工业培训等。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647632)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236526)**
<br/><br/>

---


<br/>

### 20. 包含与视频中实体相关的描述性内容的实体卡片

**Title (EN)**: Entity Cards Including Descriptive Content Relating to Entities from a Video  
**Pub. No.**: US20260236531

**Applicant**: Google LLC  
**Inventor**: [Jonathan Matthew Malmaud](https://patents.google.com/?inventor=Jonathan+Matthew+Malmaud&country=US&num=100&sort=new), [Nicolas Paul-Stringall Higuera](https://patents.google.com/?inventor=Nicolas+Paul-Stringall+Higuera&country=US&num=100&sort=new), [Jeff Hsu](https://patents.google.com/?inventor=Jeff+Hsu&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一种计算机实现的方法包括：提供视频以在显示设备上呈现；当视频中出现第一个实体时，在视频播放期间提供包含与第一个实体相关的描述性内容的第一个实体卡片，该实体由一个或多个机器学习模型基于处理视频作为输入并预测最可能被搜索的实体作为输出而识别；第一个实体卡片基于一个或多个机器学习模型预测的实体生成。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647637_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及视频播放中的用户界面技术，具体为基于机器学习识别视频中实体并提供辅助理解的实体卡片。

**Background (发明背景)**:  
用户在观看视频时，尤其是涉及复杂或新话题的视频时，可能会遇到不熟悉的关键词或概念，这些内容对理解视频至关重要。例如，在关于埃及金字塔的视频中，"石棺"（sarcophagus）是一个重要概念，但用户可能因不熟悉该术语而难以理解视频内容。用户可能需要暂停视频并搜索该术语，这可能导致不便或因拼写错误而无法获得准确结果，甚至可能因内容难以理解而停止观看。

**Summary (发明总览)**:  
本发明提供了一种在视频播放过程中动态显示实体卡片的方法，通过机器学习模型识别视频中用户可能搜索的实体，并生成包含描述性内容的实体卡片。这些卡片在视频播放时自动显示，帮助用户理解视频内容。与现有技术相比，本发明无需用户手动搜索，通过智能识别和实时展示提升了用户体验。

**Key Innovation (核心创新)**:  
1. 利用机器学习模型分析视频内容，自动识别用户可能搜索的实体，解决了用户因不熟悉术语而难以理解视频内容的问题。
2. 在视频播放过程中实时生成并显示实体卡片，提供了与视频内容同步的辅助信息，无需用户手动搜索。
3. 通过知识图谱和视频转录文本的关联，筛选并排序候选实体，确保识别出的实体与视频主题高度相关。
4. 实体卡片包含描述性内容，如文本摘要和相关图像，为用户提供全面的实体信息。
5. 支持在视频播放时动态更新实体卡片，例如在多个实体出现时依次显示或替换卡片，保持信息展示的连贯性。
6. 提供用户交互功能，如点击通知元素展开实体卡片，或进行与视频主题相关的搜索，提升用户参与度。
7. 本技术可应用于教育、娱乐和知识分享等场景，为用户提供更智能、更便捷的视频观看体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647637)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236531)**
<br/><br/>

---


<br/>

### 21. 动态空间音频通信

**Title (EN)**: Dynamic Spatial Audio Communication  
**Pub. No.**: US20260238952

**Applicant**: Google LLC  
**Inventor**: [Sunil Kumar](https://patents.google.com/?inventor=Sunil+Kumar&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明描述了执行动态空间音频通信的各种方案。音频输出系统可基于其运动生成惯性测量单元（IMU）数据。音频输出系统可通过音频通信链路直接从音频源设备接收音频数据包。接收到音频数据包后，音频输出系统可通过音频通信链路向音频源设备传输IMU数据、确认信号，并可能包括上行音频数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484650306_1.jpg)

**Technical Field (技术领域)**:  
音频通信技术领域，具体涉及低延迟空间音频传输和IMU数据通信。

**Background (发明背景)**:  
空间音频输出需要将音频输出系统的IMU数据以低延迟传输至音频源设备，以便实时调整音频输出。然而，音频数据通常具有高带宽需求，IMU数据的传输进一步增加了带宽消耗。现有的异步连接导向逻辑传输（ACL）链路传输IMU数据时，为满足低延迟需求，链路间隔需大幅缩短，导致带宽利用率低下。

**Summary (发明总览)**:  
本发明提出了一种通过音频通信链路传输IMU数据的方案，以实现动态空间音频通信。音频输出系统生成IMU数据后，通过蓝牙低能耗（LE）协议中的连接同步流（CIS）链路将IMU数据和确认信号打包传输给音频源设备。相比传统方法，本发明通过CIS链路传输IMU数据，减少了对ACL链路的依赖，从而降低了整体带宽消耗并提高了传输效率。

**Key Innovation (核心创新)**:  
1. 利用CIS链路传输IMU数据，而非传统的ACL链路，从而降低对高带宽ACL链路的依赖。
2. 通过CIS链路传输IMU数据时，CIS链路间隔被设置为低于IMU数据传输的延迟要求，确保低延迟传输。
3. 采用时间复用技术，使单一无线电能够同时处理ACL链路和CIS链路的通信，进一步优化带宽使用。
4. 在CIS链路中打包传输IMU数据和确认信号，减少数据包数量，提高传输效率。
5. 音频输出系统可包括主副耳机结构，副耳机接收主耳机定向音频数据包后，向主耳机发送二次确认信号。
6. 音频输出系统可包括麦克风，传输给音频源设备的数据包中包含麦克风捕获的音频数据，支持双向音频通信。
7. 本发明特别适用于真无线耳机等音频输出设备，能够在视频会议、音频通话等场景中提供更精准的空间音频体验，同时降低整体带宽消耗。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484650306)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260238952)**
<br/><br/>

---


<br/>

### 22. 人工现实系统对现实环境中捕捉的文本片段的自动背景翻译

**Title (EN)**: Automatic Background Translation of Text Segments Captured in a Real-World Environment by an Artificial Reality System  
**Pub. No.**: US20260237161

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Chinmay HONRAO](https://patents.google.com/?inventor=Chinmay+HONRAO&country=US&num=100&sort=new), [Neeraj CHOUBEY](https://patents.google.com/?inventor=Neeraj+CHOUBEY&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明涉及人工现实（XR）系统（例如增强现实（AR）眼镜）对现实环境中捕捉的文本片段的自动背景翻译。AR眼镜使用外向摄像头持续主动扫描现实环境以检测文本。如果检测到的文本不是用户的母语，系统会在后台自动将其翻译成用户的母语。内向摄像头可以检测用户的注视点，并基于用户对文本的注视时长判断其阅读意图。如果系统确定用户有阅读意图，系统会在AR眼镜的增强显示上无缝显示翻译后的文本。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484648333_1.jpg)

**Technical Field (技术领域)**:  
人工现实（XR）技术领域，具体涉及增强现实（AR）眼镜的自动语言翻译技术。

**Background (发明背景)**:  
随着人工现实设备普及，其应用也日益复杂。现有的XR系统无法自动识别和翻译现实环境中的文本，用户需要手动操作才能获取翻译内容。这限制了用户在现实环境中获取信息的效率。本发明旨在解决这一问题，通过自动检测和翻译现实环境中的文本，提升用户体验。

**Summary (发明总览)**:  
本发明提出了一种人工现实系统对现实环境中文本的自动翻译方案。系统通过外向摄像头扫描环境并检测文本，内向摄像头识别用户注视点以判断其阅读意图。检测到文本后，系统自动识别源语言并翻译成用户母语，无需用户干预。检测到用户交互时，系统将翻译后的文本叠加显示在原文本位置。该方案通过自动翻译和选择性显示，缩短了翻译显示的延迟时间，并节省了系统资源。

**Key Innovation (核心创新)**:  
1. 通过外向摄像头持续扫描环境并检测文本，实现对现实环境中文本的实时检测。
2. 使用内向摄像头检测用户注视点，基于注视时长判断用户是否有意阅读文本。
3. 自动识别文本源语言并翻译成用户母语，无需用户手动请求翻译。
4. 采用低分辨率图像进行文本检测，高分辨率图像进行文本识别，优化系统资源利用。
5. 仅在检测到用户交互时显示翻译后的文本，并将其叠加在原文本位置，避免显示过多无关信息。
6. 通过选择性显示翻译文本，节省显示和电力资源，同时提升用户在现实环境中的安全性。
7. 该技术可应用于AR眼镜等设备，为用户提供无缝的跨语言信息获取体验，尤其适用于旅游、教育等场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484648333)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260237161)**
<br/><br/>

---


<br/>

### 23. 包括顶部第一电子元件和底部包覆成型第二电子元件的镜头支撑结构的头戴式设备

**Title (EN)**: Head-Wearable Device Including A Lens-Support Structure with a First Electronic Component Positioned on Top and an Over-Molded Second Electronic Component Positioned on Bottom  
**Pub. No.**: US20260237884

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Javier Rodriguez De Luis](https://patents.google.com/?inventor=Javier+Rodriguez+De+Luis&country=US&num=100&sort=new), [Liang Han](https://patents.google.com/?inventor=Liang+Han&country=US&num=100&sort=new), [Ce Zhang](https://patents.google.com/?inventor=Ce+Zhang&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明公开的系统包括一个支撑结构，该结构具有顶部部分和第一底部部分。系统还包括至少一个无线通信设备，该设备位于支撑结构的顶部部分。系统进一步包括至少一个天线，该天线位于支撑结构的第一底部部分。支撑结构第一底部部分的天线与位于支撑结构顶部部分的无线通信设备电连接。本发明还公开了各种其他可穿戴设备、装置及其制造方法。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484649131_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及可穿戴设备技术，具体为头戴式设备中的天线布局和电子元件集成技术。

**Background (发明背景)**:  
随着可穿戴设备的发展，对设备内部电子元件的集成度和功能性的要求不断提高。现有技术中，天线和无线通信设备通常采用分离式设计，导致设备内部空间利用率低且信号传输效率受限。此外，传统的包覆成型工艺难以满足复杂电子元件的集成需求。本发明旨在解决上述问题，通过创新的结构设计和制造方法提升设备性能。

**Summary (发明总览)**:  
本发明提出了一种新型头戴式设备结构，通过将无线通信设备布置在支撑结构顶部，同时在底部集成包覆成型的天线，实现设备内部空间的优化利用。该设计通过电连接确保天线与无线通信设备的高效通信，提升整体信号传输性能。本发明采用创新的制造工艺，将电子元件与支撑结构紧密结合，增强了设备的耐用性和可靠性。

**Key Innovation (核心创新)**:  
1. 采用顶部布置无线通信设备的设计，优化了设备内部空间利用率，同时便于信号传输。
2. 在底部集成包覆成型的天线，通过电连接与顶部无线通信设备连接，提升信号传输效率。
3. 使用创新的制造工艺，将电子元件与支撑结构紧密结合，增强设备的耐用性和可靠性。
4. 通过不同天线架构的设计，适应多种可穿戴设备的需求，提供灵活的集成方案。
5. 优化天线布局和布线方式，减少信号干扰，提高通信质量。
6. 适用于智能眼镜等头戴式设备，提供紧凑且高效的天线解决方案。
7. 独特的设计使得设备在复杂环境中仍能保持稳定的无线通信性能，拓展了应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484649131)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260237884)**
<br/><br/>

---


<br/>

### 24. 由智能助理系统驱动的智能相机

**Title (EN)**: Smart Cameras Enabled by Assistant Systems  
**Pub. No.**: US20260238876

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Lisa Xiaoyi Huang](https://patents.google.com/?inventor=Lisa+Xiaoyi+Huang&country=US&num=100&sort=new), [Eric Xiao](https://patents.google.com/?inventor=Eric+Xiao&country=US&num=100&sort=new), [Nicholas Michael Andrew Benson](https://patents.google.com/?inventor=Nicholas+Michael+Andrew+Benson&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
在一个实施例中，一种方法包括访问相机捕获的感官数据，基于感官数据的面部识别识别相机视野中的人，检测一个或多个人基于感官数据执行的动作，生成与至少一个人或至少一个确定动作的记录相关联的媒体文件，并向客户端系统发送用于呈现一个或多个媒体文件的指令。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484650220_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及网络环境中的数据库和文件管理技术，具体涉及智能助理系统的硬件和软件。

**Background (发明背景)**:  
智能助理系统能够根据用户输入、位置感知和访问多种在线信息源的能力代表用户执行任务或提供信息。现有的智能助理系统在处理多模态输入和提供个性化服务方面存在不足，尤其是在涉及相机功能时，难以准确识别用户兴趣点并生成有意义的媒体内容。

**Summary (发明总览)**:  
本发明提出了一种由智能助理系统驱动的智能相机解决方案，通过多模态用户输入和机器学习算法识别用户视野中的兴趣点，生成个性化的媒体文件并提供记忆回溯功能。该系统能够主动或被动地协助用户捕捉和管理重要时刻，同时确保用户隐私和计算资源的高效利用。

**Key Innovation (核心创新)**:  
1. 通过多模态用户输入（如语音、文本、图像、动作等）实现智能助理与用户的交互，提升用户体验。
2. 利用机器学习算法分析相机捕获的感官数据，精准识别用户视野中的兴趣点，确保捕捉到用户真正关心的内容。
3. 基于用户个人资料、偏好和历史输入生成个性化的媒体文件，使生成的内容更符合用户需求。
4. 通过记忆回溯功能，将当前捕捉到的时刻与用户过去的记忆相关联，增强用户对内容的理解和欣赏。
5. 采用客户端和服务器端混合架构处理用户输入，在保护用户隐私的同时优化计算资源的使用。
6. 提供对象/人物识别、兴趣点确定和注释生成等附加功能，进一步提升智能相机的智能化水平。
7. 应用于智能相机设备（如智能手机、AR/VR眼镜、智能显示屏），为用户提供便捷的实时捕捉、分享和记忆管理功能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484650220)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260238876)**
<br/><br/>

---


<br/>

### 25. 用于增加热预算的增强现实设备配件

**Title (EN)**: ARTIFICIAL REALITY DEVICE ACCESSORIES TO INCREASE THERMAL BUDGET  
**Pub. No.**: US20260239588

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Bardia Zandian](https://patents.google.com/?inventor=Bardia+Zandian&country=US&num=100&sort=new), [Alex Ockfen](https://patents.google.com/?inventor=Alex+Ockfen&country=US&num=100&sort=new), [Pankaj Raghuvanshi](https://patents.google.com/?inventor=Pankaj+Raghuvanshi&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一种增强现实设备包括一个用于向用户呈现增强现实程序视觉效果的组件，以及至少一个热源和一个接触点。该接触点专门配置用于容纳一个配件，该配件专门配置用于扩展增强现实设备的散热裕度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484651008_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算设备散热技术，具体为增强现实设备的热管理。

**Background (发明背景)**:  
增强现实设备在运行过程中会产生大量热量，环境因素如高温或阳光直射会加剧这一问题。过热可能导致设备性能下降或硬件损坏。现有的散热设计难以应对多种使用场景下的热管理需求。

**Summary (发明总览)**:  
本发明提出了一种通过外部配件扩展增强现实设备散热能力的系统。通过在设备上设置专用接触点，这些接触点能够将热量高效传递至配件，从而在不增加设备本身体积的情况下提升散热效率。配件可以是主动式或被动式，用户可根据需求和环境选择合适的散热方案。这种设计提高了设备在不同环境下的使用灵活性，并延长了持续使用时间。

**Key Innovation (核心创新)**:  
1. 通过在增强现实设备上设置专用接触点，实现热量从设备到外部配件的高效传递，从而避免热量积聚在设备内部。
2. 提供主动式和被动式两种配件方案：主动式配件使用风扇等组件主动散热，被动式配件通过增加表面积与空气或皮肤接触进行散热。
3. 设计了可切换的热路径控制系统，根据是否连接配件自动调整热量传递方向，确保在无配件时热量仍能通过设备表面自然散热。
4. 配件采用特殊设计的接触点，确保与设备之间的热传导效率最大化，同时保护用户免受高温接触点的伤害。
5. 允许用户根据使用场景和需求更换不同类型的散热配件，例如在户外使用时可选择带有遮阳功能的配件。
6. 通过扩展设备的热设计功率（TDP），使增强现实设备能够在更高负载或更严苛的环境下持续稳定运行。
7. 该技术可应用于头戴式显示器（HMD）和其他增强现实设备组件，为用户提供更长的使用时间和更舒适的使用体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484651008)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260239588)**
<br/><br/>

---


<br/>

### 26. 真无线耳塞的单声道音频传输

**Title (EN)**: Monophonic Audio for True Wireless Earbuds  
**Pub. No.**: US20260238974

**Applicant**: Google LLC  
**Inventor**: [Daniel BARROS](https://patents.google.com/?inventor=Daniel+BARROS&country=US&num=100&sort=new), [Sunil KUMAR](https://patents.google.com/?inventor=Sunil+KUMAR&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明提出了一种使用短距离无线通信链路的方法。通过在真无线耳塞对和音频源设备之间建立会话配置，建立单一连接等时流（CIS）以传输单声道音频流。在完成会话配置后，主耳塞接收在单一CIS上发送的音频数据包。尽管主耳塞成功接收音频数据包，但若确定音频数据包的数据尚未传输预定的次数，则向音频源设备发送否定确认（NAK）。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484650330_1.jpg)

**Technical Field (技术领域)**:  
无线通信技术领域，具体涉及真无线耳塞的单声道音频传输。

**Background (发明背景)**:  
传统无线音频传输协议（如蓝牙低功耗音频）通常需要分别向每只耳塞发送音频数据包，即使音频数据是单声道的。这种方法效率低下，浪费了宝贵的无线带宽资源。本发明旨在解决真无线耳塞传输单声道音频时带宽利用率低的问题。

**Summary (发明总览)**:  
本发明提出了一种通过单一连接等时流（CIS）向真无线耳塞对传输单声道音频的方法。主耳塞接收音频数据包后，通过内部传输将音频数据共享给副耳塞。副耳塞无需直接与音频源设备通信，而是通过主耳塞获取音频数据。本发明通过减少音频源设备与耳塞之间的通信次数，优化了无线带宽的使用。

**Key Innovation (核心创新)**:  
1. 通过单一CIS向真无线耳塞对传输单声道音频，避免了分别向每只耳塞发送音频数据包，从而节省了无线带宽。
2. 主耳塞在成功接收音频数据包后，根据预定的次数发送否定确认（NAK），以确保副耳塞也能成功接收音频数据。
3. 副耳塞通过主耳塞接收音频数据，无需直接与音频源设备通信，减少了通信复杂性和功耗。
4. 实现了根据耳塞间通信链路信号强度动态调整NAK发送次数的机制，以适应不同的通信环境。
5. 副耳塞通过主耳塞获取加密凭证和解密音频数据包，确保了数据传输的安全性。
6. 本发明适用于语音通话、音乐播放和游戏等单声道音频应用场景，能够在这些场景下显著提高无线带宽利用率。
7. 通过减少音频源设备与耳塞之间的通信次数，本发明在真无线耳塞应用中提供了更高效、更稳定的音频传输解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484650330)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260238974)**
<br/><br/>

---


<br/>

### 27. 用于可穿戴设备的密封聚合物结构电池

**Title (EN)**: HERMETICALLY SEALED POLYMERIZED STRUCTURAL BATTERIES FOR WEARABLE DEVICES  
**Pub. No.**: US20260237727

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Steven Eickhoff](https://patents.google.com/?inventor=Steven+Eickhoff&country=US&num=100&sort=new), [Mikael Wagner](https://patents.google.com/?inventor=Mikael+Wagner&country=US&num=100&sort=new), [Charles Dominic Consorte](https://patents.google.com/?inventor=Charles+Dominic+Consorte&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
一款智能眼镜包括一个镜腿，其中镜腿的一部分涂覆有密封涂层。该智能眼镜包括一个电池，电池位于镜腿内部，使得电池的电解质与镜腿的密封涂层接触。电解质被聚合，从而与镜腿的密封涂层结合。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484648956_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及可穿戴电子设备的电池技术，具体为具有柔性聚合物电解质和密封涂层的结构电池，用于智能眼镜的镜腿集成。

**Background (发明背景)**:  
可穿戴设备如智能眼镜等需要集成电池供电，但传统锂离子电池对湿气敏感，需要笨重的封装，增加了设备体积和重量。
传统电池形状固定，难以适应智能眼镜镜腿的曲面设计，导致空间利用率低。
此外，电池在反复弯曲时易受损，限制了其在可穿戴设备中的应用。

**Summary (发明总览)**:  
本发明提出了一种新型结构电池，通过聚合物电解质与设备内部密封涂层的结合，将电池直接集成到智能眼镜镜腿等可穿戴设备外壳中。
该电池采用阶梯式电极堆叠设计，能够适应曲面结构，提高空间利用率。
同时，电池具备柔性特性，能够在反复弯曲下保持性能稳定。
该设计消除了传统封装需求，简化了结构并提升了可靠性。

**Key Innovation (核心创新)**:  
1. 采用聚合物电解质与密封涂层直接结合的技术，省去了传统锂离子电池的铝塑膜或钢壳封装，简化了结构并减轻了重量。
2. 电池电极堆叠采用阶梯式设计，尺寸逐层变化，能够更好地适应智能眼镜镜腿的曲面结构，提高空间利用率。
3. 电池具备柔性特性，能够在反复弯曲（如智能眼镜的佩戴和取下）下保持性能稳定，解决了传统电池易受损的问题。
4. 密封涂层中包含柔性层和防护层，在保证密封性的同时，能够承受反复变形，确保电池的防潮性能。
5. 电解质具有可调节的弹性模量，可根据应用需求调整电池的机械性能，例如弯曲刚度。
6. 该电池设计支持镜腿的可拆卸结构，通过机械、热和电连接实现电池与设备的可靠集成。
7. 该技术可应用于智能眼镜等可穿戴设备，提升设备续航能力，同时保持轻便舒适的使用体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484648956)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260237727)**
<br/><br/>

---


<br/>

### 28. 冷却空气增强

**Title (EN)**: Cooling Air Augmentation  
**Pub. No.**: US20260239577

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Freddie BELL, JR.](https://patents.google.com/?inventor=Freddie+BELL%2C+JR.&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明涉及热管理和确保多个计算设备在彼此邻近运行时获得充分冷却的技术。通过获取包含多个计算设备的机架内的感知条件，该技术能够控制向机架内各个计算设备输送补充冷却空气，以增强来自集中式冷却系统的冷却空气，从而移除各个计算设备的散热负载。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484650995_1.jpg)

**Technical Field (技术领域)**:  
数据中心热管理技术，具体涉及机架内局部冷却增强。

**Background (发明背景)**:  
在数据中心等场景中，大量计算设备密集排列，产生大量热量需要移除以确保安全运行。
集中式冷却系统通常为整个数据中心提供冷却，但可能无法满足局部区域的高散热需求。
现有技术通过减少设备部署或降低设备性能来应对局部冷却不足的问题，导致空间利用率和计算性能下降。

**Summary (发明总览)**:  
本发明提出了一种通过局部冷却增强来改善数据中心热管理的技术方案。
通过在机架附近设置辅助空调单元和分配子组件，系统能够根据需要向机架内特定位置输送额外冷却空气。
这种方案解决了传统方法中因局部冷却不足而导致的设备性能受限或空间浪费问题。
该技术允许计算设备按照设计规格运行，同时避免局部过热问题。

**Key Innovation (核心创新)**:  
1. 引入辅助空调单元，在机架附近生成额外冷却空气，为集中式冷却系统提供补充。
2. 设计机架分配子组件，实现对补充冷却空气的精确控制，确保其被输送到机架内需要增强冷却的特定位置。
3. 通过传感器获取机架内实时温度和热负载数据，动态调整补充冷却空气的供应量，实现精准热管理。
4. 解决传统方法中因局部冷却不足而导致的设备性能受限问题，允许计算设备在高负载下正常运行。
5. 避免传统技术中因冷却不足而导致的机架闲置或设备降频问题，提高数据中心空间利用率。
6. 适用于高性能计算设备密集部署的场景，如数据中心服务器机架，能够有效应对局部过热问题。
7. 通过局部冷却增强技术，在不增加整体冷却系统规模的情况下，提升数据中心整体散热能力和设备运行稳定性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484650995)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260239577)**
<br/><br/>

---


<br/>

### 29. 在对话式推荐系统中使用大语言模型进行对话管理和推荐

**Title (EN)**: Using Large Language Models for Dialogue Management and Recommendations in a Conversational Recommender System  
**Pub. No.**: US20260236544

**Applicant**: Google LLC  
**Inventor**: [Zhenning Tan](https://patents.google.com/?inventor=Zhenning+Tan&country=US&num=100&sort=new), [Luke Beck Friedman](https://patents.google.com/?inventor=Luke+Beck+Friedman&country=US&num=100&sort=new), [Manoj Tiwari](https://patents.google.com/?inventor=Manoj+Tiwari&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明涉及使用大语言模型（LLM）的对话式推荐系统（CRS）。该系统通过一个或多个处理器接收用户通过客户端设备在交互式对话中输入的信息，并根据训练好的大语言模型预测对话状态。基于预测的对话状态，系统生成对用户输入的响应，并从候选语料库中识别出一组相关项目。系统还会生成一个包含一个或多个相关项目的推荐列表。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484647652_1.jpg)

**Technical Field (技术领域)**:  
对话式推荐系统；大语言模型；人机交互

**Background (发明背景)**:  
传统的推荐系统依赖用户隐式交互信号（如点击）来推断偏好，但存在点击诱饵、传播偏见和用户群体极化等问题。基于点击的界面限制了用户与系统的交互带宽，难以支持交互式探索。此外，大规模推荐系统在透明性和用户控制方面存在不足。现有的对话式推荐系统虽然提供实时沟通，但面临对话控制和推荐引擎集成的技术挑战。

**Summary (发明总览)**:  
本发明提出了一种基于大语言模型的对话式推荐系统，通过多轮对话实现用户兴趣的细化和控制。系统利用大语言模型进行对话状态预测、生成自然语言响应，并结合推荐引擎提供相关项目推荐。系统支持用户通过对话调整兴趣，提供推荐解释，并允许用户对推荐结果进行反馈，从而实现更透明和可控的推荐体验。

**Key Innovation (核心创新)**:  
1. 采用大语言模型作为对话管理器，实现自然语言对话处理和对话状态预测，提升对话流畅性和用户交互体验。
2. 通过对话状态预测和用户输入分析，生成个性化推荐列表，并提供基于上下文的推荐解释，增强推荐透明度和用户信任度。
3. 利用编码器模型处理对话上下文和目标响应，支持意图和情感分析，从而生成更符合用户需求的响应。
4. 引入澄清问题机制，在对话状态预测的基础上，主动向用户提出澄清问题，以获取更准确的兴趣信息。
5. 设计对话管理器中的策略护栏，限制对话轮次并引导对话回到主题，防止对话偏离推荐目标。
6. 结合摘要模型生成推荐解释，并将其整合到对话管理器中，为用户提供直观的推荐理由。
7. 本发明可应用于视频、音乐、电商等推荐场景，通过自然语言交互和推荐解释，提升用户满意度和系统实用性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484647652)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260236544)**
<br/><br/>

---


<br/>

### 30. 使用多设备进行用户交互和任务管理

**Title (EN)**: USER INTERACTION AND TASK MANAGEMENT USING MULTIPLE DEVICES  
**Pub. No.**: US20260238703

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Robert A. SIM](https://patents.google.com/?inventor=Robert+A.+SIM&country=US&num=100&sort=new), [Adam FOURNEY](https://patents.google.com/?inventor=Adam+FOURNEY&country=US&num=100&sort=new), [Russell Allen HERRING, JR.](https://patents.google.com/?inventor=Russell+Allen+HERRING%2C+JR.&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明提供了一种使用多设备进行用户交互和任务完成的系统和方法。一组设备可用于执行任务，不同设备可执行任务的不同步骤。设备管理服务可更新每台设备的状态信息，使用户能够通过任何计算设备与任务进行交互。例如，用户在一台设备上输入或更改的信息会提供给其他设备，使用户能够在任何其他设备上完成任务的各个方面。设备管理服务还可根据任务或步骤要求、设备特性、设备能力等因素，自动确定用户应使用哪台设备。因此，用户不必局限于使用同一台设备来完成不适合当前步骤或任务的设备，而是可以选择使用不同的设备，并在某些情况下自动切换到使用设备组中的不同设备。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484650031_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及多设备协同技术领域，具体涉及跨设备任务管理和用户交互技术。

**Background (发明背景)**:  
随着计算设备的种类和数量的增加，用户可能拥有多台设备来完成一项任务。然而，某些计算设备可能比其他设备更适合某些任务。此外，某些计算设备可能适合任务的某个步骤，但不适合另一个步骤。现有的单设备任务处理方式限制了用户在不同设备间灵活切换的能力，导致任务执行效率低下或用户体验不佳。本发明旨在解决这一问题，通过多设备协同管理提升任务执行效率和用户交互体验。

**Summary (发明总览)**:  
本发明提出了一种基于多设备的任务管理和用户交互方法，通过设备管理服务协调不同设备执行任务的不同步骤。用户可以在任何设备上输入或更改信息，这些信息会实时同步到其他设备。设备管理服务根据任务需求、设备特性和用户偏好等因素，自动选择最合适的设备进行交互。用户无需局限于使用同一台设备，而是可以在设备组中灵活切换，甚至在某些情况下自动切换设备以适应任务需求。这种方法提高了任务执行的灵活性和效率，改善了用户体验。

**Key Innovation (核心创新)**:  
1. 提出了多设备协同任务执行机制，通过设备管理服务协调不同设备执行任务的不同步骤，实现任务步骤的灵活分配。
2. 实现了跨设备状态信息同步，使用户在一台设备上的操作能够实时反映到其他设备上，确保任务执行的连续性和一致性。
3. 提供了基于任务需求、设备特性和用户偏好的智能设备选择算法，自动推荐或切换到最适合当前任务的设备。
4. 引入了任务会话的概念，通过设备标识符（如用户账号、IP 地址、MAC 地址等）将一组设备关联起来，形成一个动态的任务执行环境。
5. 支持预会话上下文信息的收集和处理，使设备管理服务能够根据用户之前的行为和任务相关数据，智能地选择和配置设备。
6. 允许使用多种设备组合来完成单个任务，例如将具备不同功能的设备组合在一起，以提供更全面的任务支持。
7. 本发明可应用于智能家居、办公协作、在线购物等多种场景，为用户提供无缝的多设备交互体验，提升任务执行效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484650031)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260238703)**
<br/><br/>

---


<br/>

### 31. 多应用增强现实环境中的对比度调整

**Title (EN)**: CONTRAST RATIO ADJUSTMENT IN MULTI-APPLICATION AUGMENTED REALITY ENVIRONMENT  
**Pub. No.**: US20260237327

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jasmine Soria Sears](https://patents.google.com/?inventor=Jasmine+Soria+Sears&country=US&num=100&sort=new), [Peter Lawrence Capak](https://patents.google.com/?inventor=Peter+Lawrence+Capak&country=US&num=100&sort=new), [Devan Lippman](https://patents.google.com/?inventor=Devan+Lippman&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本文描述了一种用于多应用增强现实（AR）环境中的对比度调整的装置、系统和方法。在一些方面中，方法包括接收要提供给头戴式显示器用户的第一个AR内容和第二个AR内容。基于第一个AR内容和第二个AR内容生成一个组合目标对比度。使用该组合目标对比度通过调整显示亮度或调整头戴式显示器的镜片的全局调光来调整头戴式显示器的对比度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484648518_1.jpg)

**Technical Field (技术领域)**:  
增强现实技术领域，具体涉及AR眼镜或头戴式显示器的内容显示。

**Background (发明背景)**:  
增强现实技术通过数字内容增强用户对物理世界的视觉体验，例如文本或图像。然而，不同因素如显示亮度或外部环境的光照条件会影响数字内容或AR内容的观看效果。现有的AR设备在处理多内容显示时存在不足，例如全局调光时整个玻璃镜片采用单一透光值，而不同内容可能需要不同的亮度或透光值。

**Summary (发明总览)**:  
本发明提出了一种在多应用增强现实环境中调整对比度的方法，通过接收来自不同应用的多种AR内容，生成一个组合目标对比度，并基于环境光照测量和目标对比度生成自动调光因子。该方法通过调整显示亮度和/或镜片的全局调光来优化AR头戴式显示器的对比度，从而在多内容显示时提供更合适的用户体验。

**Key Innovation (核心创新)**:  
1. 通过接收来自不同应用的多种AR内容，生成一个组合目标对比度，以适应多内容显示的需求。
2. 基于环境光照测量和目标对比度生成自动调光因子，实现动态调整显示亮度和镜片的全局调光。
3. 解决了现有技术中全局调光导致所有内容采用单一透光值的问题，通过动态调整提供更精细的对比度控制。
4. 允许不同内容根据其需求采用不同的亮度或透光值，从而提升多内容显示时的视觉体验。
5. 适用于AR处理环境中来自不同应用的内容，确保不同内容在显示时具有适当的亮度和对比度。
6. 通过优化显示亮度和透光值，在保证视觉清晰度的同时降低能耗，延长设备续航时间。
7. 本发明可应用于AR眼镜或头戴式显示器等设备，尤其适用于需要同时显示多种内容的场景，如导航、信息提示和虚拟协作等。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484648518)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260237327)**
<br/><br/>

---


<br/>

### 32. 基于光电容积描记图（PPG）数据推荐腕戴式设备生理测量位置的技巧及其应用系统

**Title (EN)**: TECHNIQUES FOR RECOMMENDING A WRIST-WEARABLE DEVICE POSITION FOR PHYSIOLOGICAL MEASUREMENTS BASED ON PHOTOPLETHYSMOGRAPHY (PPG) DATA AND SYSTEMS OF USE THEREOF  
**Pub. No.**: US20260232248

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Teodora Sandra Buda](https://patents.google.com/?inventor=Teodora+Sandra+Buda&country=US&num=100&sort=new), [Kevin Kai-feng Chiou](https://patents.google.com/?inventor=Kevin+Kai-feng+Chiou&country=US&num=100&sort=new), [Michael John Toksvig](https://patents.google.com/?inventor=Michael+John+Toksvig&country=US&num=100&sort=new)  
**Publication Date**: 13.08.2026

**Abstract**:  
本发明描述了一种基于光电容积描记图（PPG）数据推荐腕戴式设备生理测量位置的方法。该方法包括：在腕戴式设备处于第一和第二位置时：(i) 接收一个或多个PPG传感器捕获的第一和第二PPG数据，以及一个或多个校准PPG传感器捕获的第一和第二校准PPG数据；(ii) 基于第一和第二PPG数据生成第一和第二生理数据，并基于第一和第二校准PPG数据生成第一和第二校准生理数据；(iii) 通过比较第一和第二PPG数据与第一和第二校准PPG数据来确定第一和第二放置误差。根据第一放置误差小于第二放置误差的判断，向用户推荐将腕戴式设备佩戴在第一位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484646939_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及可穿戴设备领域，具体为基于PPG数据的腕戴式设备生理测量校准技术。

**Background (发明背景)**:  
智能手表、健身手环、智能戒指等腕戴式设备正变得越来越普及。这些设备配备了多种传感器，可用于监测心率、血压、血氧饱和度、心率变异性等生理指标。然而，腕戴式设备的佩戴位置和松紧度对准确测量这些生理指标至关重要。用户难以确定最佳佩戴位置，且舒适的佩戴方式可能导致测量结果不准确。本发明旨在解决上述问题。

**Summary (发明总览)**:  
本发明提出了一种通过比较PPG数据和校准PPG数据来推荐腕戴式设备最佳佩戴位置的方法。该方法通过在不同佩戴位置捕获PPG数据，并将其与校准设备的数据进行对比，从而确定最佳佩戴位置。本发明通过提供明确的佩戴建议，提升了生理测量的准确性，同时兼顾了用户的佩戴舒适度。与现有技术相比，本发明提供了一种更智能、更用户友好的设备佩戴优化方案。

**Key Innovation (核心创新)**:  
1. 通过在腕戴式设备的不同佩戴位置捕获PPG数据，并结合校准设备的数据进行分析，确定最佳佩戴位置。
2. 采用双传感器系统，包括PPG传感器和校准PPG传感器，确保数据对比的准确性和可靠性。
3. 通过比较不同佩戴位置的PPG数据和校准数据，计算放置误差，从而量化不同佩戴位置的测量质量。
4. 根据计算结果向用户推荐最佳佩戴位置，提供明确的佩戴指导，提升用户体验。
5. 该方法可应用于智能手表、健身手环等设备，适用于心率、血压、血氧等多项生理指标的测量。
6. 通过优化佩戴位置，不仅提高了测量准确性，还考虑了用户的佩戴舒适度。
7. 本发明可应用于扩展现实（XR）系统，如混合现实（MR）头显或增强现实（AR）眼镜，为用户提供更精准的生理数据监测。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484646939)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260232248)**
<br/><br/>

---


<br/>

### 33. 用于装载物品的可扩展容器的扩展装置

**Title (EN)**: Device for expanding container to be loaded with item(s)  
**Pub. No.**: US12703530

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Joshua Arleigh Burright](https://patents.google.com/?inventor=Joshua+Arleigh+Burright&country=US&num=100&sort=new), [Frank Van Yperzele](https://patents.google.com/?inventor=Frank+Van+Yperzele&country=US&num=100&sort=new), [Jente De Maeyer](https://patents.google.com/?inventor=Jente+De+Maeyer&country=US&num=100&sort=new)  
**Publication Date**: 11.08.2026

**Abstract**:  
一种装置包括一个用于接收多个容器的平台、一个风扇、一个管道和一个偏置元件。管道与风扇流体连接，并将空气引导至多个容器中的至少一个容器。引导空气进入容器使容器至少部分扩展，从而允许向容器内装载一个或多个物品。偏置元件使平台朝被引导进入容器的空气方向偏置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484462646_1.jpg)

**Technical Field (技术领域)**:  
物流包装技术领域，具体涉及用于自动扩展容器的装置。

**Background (发明背景)**:  
随着电子商务的兴起，订单履行、包装和运输的需求显著增加。零售商需要以更快的速度进行物品包装，但现有设备难以满足这种需求，导致效率低下和错误频发。

**Summary (发明总览)**:  
本发明提供了一种用于自动扩展容器的装置，通过向容器内注入空气使其膨胀，从而便于装载物品。平台设计用于承载多个容器，并通过偏置元件确保空气有效进入容器。该方案简化了包装流程，提高了包装效率，并减少了人工操作中的错误。

**Key Innovation (核心创新)**:  
1. 采用风扇和管道系统向容器内注入空气，使容器自动扩展，解决了人工扩展容器的低效问题。
2. 设计了偏置元件，使平台朝空气流动方向偏置，确保空气均匀进入容器并均匀扩展。
3. 平台可同时承载多个容器，通过批量处理提高包装效率，适应大规模物流需求。
4. 通过控制空气流量和压力，实现对容器扩展程度的精确调节，适应不同尺寸和材质的容器。
5. 该装置可与自动化包装系统集成，实现全流程自动化，减少人工干预和错误率。
6. 适用于电商、物流中心等场景，尤其适合处理大批量小型物品的包装需求。
7. 通过优化空气流动路径和容器扩展方式，降低了能耗并提高了设备使用寿命。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484462646)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12703530)**
<br/><br/>

---


<br/>

### 34. 基于场景感知的音乐可视化生成

**Title (EN)**: Scene-aware generation of music visualizations  
**Pub. No.**: US12707129

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Ian James Wallace](https://patents.google.com/?inventor=Ian+James+Wallace&country=US&num=100&sort=new), [Chong Huang](https://patents.google.com/?inventor=Chong+Huang&country=US&num=100&sort=new), [Kevin Thomas Merchant](https://patents.google.com/?inventor=Kevin+Thomas+Merchant&country=US&num=100&sort=new)  
**Publication Date**: 11.08.2026

**Abstract**:  
本发明描述了基于场景感知的音乐可视化生成技术。示例方法包括接收音乐样本和投影表面图像，并基于投影表面图像生成约束图像。该方法还包括对音乐样本进行情感分析，并使用音乐样本元数据和情感分析生成中间提示。然后，通过大型语言模型处理中间提示，并生成用于潜在扩散模型的后续关键帧提示集。该方法还包括使用潜在扩散模型生成关键帧集，并从关键帧生成插值图像。最后，该方法包括对齐...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484466618_1.jpg)

**Technical Field (技术领域)**:  
多媒体技术领域，具体涉及音乐可视化生成和人工智能辅助创作。

**Background (发明背景)**:  
音乐可视化通过为音频轨道提供视觉组件来增强多媒体体验。现有的音乐可视化技术通常尝试结合源音频轨道的不同方面，以提供互补的视觉效果。然而，现有技术往往缺乏对音乐情感和场景的深入理解，导致视觉效果与音乐内容脱节。本发明旨在解决这一问题，通过结合情感分析和场景感知来生成更协调、更具沉浸感的音乐可视化效果。

**Summary (发明总览)**:  
本发明提出了一种基于场景感知的音乐可视化生成方法。其核心思路是结合音乐的情感分析和场景信息，通过人工智能技术生成高质量的可视化效果。具体实现路径包括：接收音乐样本和投影表面图像，生成情感分析和场景约束，使用大型语言模型处理中间提示，并生成关键帧提示集。随后，利用潜在扩散模型生成关键帧，并通过插值技术生成最终的可视化图像。与现有技术相比，本发明通过引入情感分析和场景感知，显著提升了音乐可视化效果的协调性和沉浸感。

**Key Innovation (核心创新)**:  
1. 通过接收音乐样本和投影表面图像，生成基于场景的约束图像，确保可视化效果与实际场景高度契合。
2. 采用情感分析技术对音乐样本进行深度分析，提取情感特征，为后续生成提供情感指导。
3. 使用音乐样本元数据和情感分析生成中间提示，并通过大型语言模型进行优化处理，提升生成内容的语义连贯性。
4. 基于潜在扩散模型生成关键帧，并通过插值技术生成高质量的过渡图像，确保视觉效果流畅自然。
5. 结合场景感知和情感分析，生成与音乐内容高度协调的可视化效果，提升用户的沉浸式体验。
6. 该技术可应用于现场音乐会、虚拟现实场景和多媒体娱乐产品中，为用户提供个性化的音乐可视化体验。
7. 通过引入人工智能技术，本发明能够自动生成高度定制化的音乐可视化内容，显著降低人工创作成本。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484466618)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12707129)**
<br/><br/>

---


<br/>

### 35. 带视频和RFID的自动化结账系统

**Title (EN)**: Automated checkout system with video and RFID  
**Pub. No.**: US12705664

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Akash Modi](https://patents.google.com/?inventor=Akash+Modi&country=US&num=100&sort=new), [Kushagra Srivastava](https://patents.google.com/?inventor=Kushagra+Srivastava&country=US&num=100&sort=new), [Sandipan Saha](https://patents.google.com/?inventor=Sandipan+Saha&country=US&num=100&sort=new)  
**Publication Date**: 11.08.2026

**Abstract**:  
本发明描述了一种即走即付（JWO）设施的系统，用户可以进入设施，选取一个或多个商品，然后离开设施，无需进行手动结账即可租用、购买或以其他方式获取商品。在某些情况下，设施中的每个商品都附着一个标签，例如RFID标签，该标签包含一个出口系统，该系统包括RFID阅读器，用于检测标签何时离开设施。出口系统还可以包括一个或多个摄像头，用于帮助识别标签和商品通过多个结账通道中的哪一个离开，以确保商品与正确的用户账户关联，并/或对适当的支付工具进行扣款。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484465002_1.jpg)

**Technical Field (技术领域)**:  
零售自动化技术领域，具体涉及基于RFID和视频监控的无人结账系统。

**Background (发明背景)**:  
传统实体商店通常在顾客可接触的区域存放商品，顾客需将商品带到结账台进行购买或租赁。与此同时，一些零售环境使用传感器生成设施内事件的信息，使顾客可以在离开商店时自动支付商品，而无需进行手动支付流程。然而，现有系统可能存在商品识别不准确、结账效率低等问题。本发明旨在解决这些问题，提供一种更高效、更准确的自动化结账解决方案。

**Summary (发明总览)**:  
本发明提出了一种基于RFID和视频监控的自动化结账系统。用户进入商店后，可以自由选取商品并直接离开，系统会自动识别商品并完成支付。RFID标签用于追踪商品位置，视频监控用于确认商品与用户账户的关联性。该系统通过结合RFID和视频技术，提高了商品识别的准确性和结账效率，减少了人工干预。

**Key Innovation (核心创新)**:  
1. 采用RFID标签追踪商品位置，实现对商品出入的实时监控。
2. 结合视频监控技术，通过摄像头识别商品与用户账户的关联性，确保支付准确性。
3. 设计多通道出口系统，通过RFID阅读器和摄像头协同工作，区分不同结账通道的商品流动。
4. 通过RFID和视频数据的融合处理，提高商品识别和用户关联的准确性，减少误判。
5. 提供即走即付的购物体验，用户无需排队结账，提升购物便利性。
6. 系统可应用于超市、便利店等多种零售场景，尤其适合高人流量的场所。
7. 通过减少人工结账环节，降低运营成本，同时提高结账效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484465002)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12705664)**
<br/><br/>

---


<br/>

### 36. 基于运动物体感兴趣区域的视频压缩

**Title (EN)**: Video compression using region of interest of moving objects  
**Pub. No.**: US12707029

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Pramod Sreenivasa](https://patents.google.com/?inventor=Pramod+Sreenivasa&country=US&num=100&sort=new), [Raj Kumar Akella](https://patents.google.com/?inventor=Raj+Kumar+Akella&country=US&num=100&sort=new), [Ali Rahimi](https://patents.google.com/?inventor=Ali+Rahimi&country=US&num=100&sort=new)  
**Publication Date**: 11.08.2026

**Abstract**:  
本发明描述了基于检测图像数据中感兴趣区域（ROI）来压缩图像数据（如视频数据）的系统和过程。图像数据被分析以确定其中描绘的运动物体和静止物体（例如背景）。为了压缩图像数据，静止物体的刷新频率低于运动物体。在运动物体中识别出感兴趣区域，例如人的面部、手部以及/或由人移动的物体。这些ROI区域/像素被保持高质量，而非ROI区域/像素则降低质量以进一步压缩图像数据。面部质量被降低以模糊人的身份。可以同时定位并跟踪多个ROI区域。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484466507_1.jpg)

**Technical Field (技术领域)**:  
视频压缩技术；
图像处理；
感兴趣区域（ROI）检测

**Background (发明背景)**:  
在零售、批发等场景中，摄像头被广泛用于捕捉环境中的图像数据以跟踪操作。然而，这些摄像头生成的大量图像数据需要大量存储空间和带宽。
现有技术通过降低图像分辨率来减少数据量，但这会导致图像质量下降，丢失重要细节。
因此，需要一种既能减少数据量又能保留关键信息的图像压缩方法。

**Summary (发明总览)**:  
本发明提出了一种基于感兴趣区域（ROI）的视频压缩方法，通过区分运动物体和静止物体来优化压缩策略。
首先识别图像中的运动物体，并在其中检测出关键区域（如人脸、手部等）作为ROI。
然后，对静止物体和运动物体采用不同的刷新频率，同时对ROI区域保持高画质，对非ROI区域降低画质以实现压缩。
此外，本发明还引入了面部模糊技术以保护隐私。
这种方法在减少数据量的同时，保留了关键信息，提升了压缩效率。

**Key Innovation (核心创新)**:  
1. 通过检测运动物体和静止物体，动态调整刷新频率，实现差异化压缩。
2. 在运动物体中识别多个感兴趣区域（ROI），如人脸、手部等，并优先保持这些区域的高质量。
3. 采用非ROI区域降质技术，在保证关键信息清晰的同时，进一步减少数据量。
4. 引入面部模糊技术，在压缩过程中保护个人隐私。
5. 支持同时跟踪多个ROI区域，适应复杂场景下的压缩需求。
6. 该方法可应用于视频监控系统、直播平台等场景，在减少带宽和存储需求的同时，确保关键信息的完整性。
7. 通过差异化压缩策略，在压缩效率和数据质量之间取得平衡，提供更优的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484466507)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12707029)**
<br/><br/>

---


<br/>

### 37. 视频中的人物订阅

**Title (EN)**: Subscribe to people in videos  
**Pub. No.**: US12705276

**Applicant**: Google LLC  
**Inventor**: [Justin Lewis](https://patents.google.com/?inventor=Justin+Lewis&country=US&num=100&sort=new), [Kevin Greene](https://patents.google.com/?inventor=Kevin+Greene&country=US&num=100&sort=new)  
**Publication Date**: 11.08.2026

**Abstract**:  
本发明提供了一种计算机实现的方法，用于使用户能够订阅人物和其他标记实体。该方法包括维护订阅数据，指定多个用户订阅的多个实体，每个实体是与标签相关联的标记实体。该方法进一步包括识别与一个或多个标记实体相关联的媒体项，基于订阅数据确定订阅了媒体项中标记实体的用户，并将媒体项提供给该用户。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484464571_1.jpg)

**Technical Field (技术领域)**:  
内容分享平台技术领域，具体涉及根据用户偏好提供和推荐媒体项。

**Background (发明背景)**:  
互联网上的内容分享平台，如社交网络，允许用户相互连接和分享信息。然而，随着平台上内容量的增加，用户难以找到最感兴趣的内容。尽管已有一些推荐和内容组织方法，但这些方法的效果并不完全令人满意。

**Summary (发明总览)**:  
本发明提出了一种通过订阅机制来推荐媒体项的方法。用户可以订阅特定人物或标记实体，系统根据订阅数据识别用户感兴趣的媒体项并推送。这种方法通过个性化订阅机制提升了内容推荐的精准度，使用户能够更高效地获取感兴趣的内容。

**Key Innovation (核心创新)**:  
1. 引入基于标记实体的订阅机制，用户可以订阅特定人物或标签，从而实现更精准的内容推荐。
2. 系统维护订阅数据，记录用户订阅的多个实体，每个实体都与特定标签相关联。
3. 通过识别与标记实体相关联的媒体项，系统能够快速定位用户可能感兴趣的内容。
4. 基于订阅数据，系统能够确定哪些用户订阅了特定媒体项中的标记实体，从而实现个性化推送。
5. 该方法通过减少用户搜索时间并提高内容相关性，改善了用户体验。
6. 适用于社交网络、视频分享平台等场景，能够有效提升用户参与度和内容消费频率。
7. 创新性地结合了标记实体和订阅机制，为内容推荐提供了新的技术路径。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484464571)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12705276)**
<br/><br/>

---


<br/>

### 38. 提供批处理执行可视化和推荐

**Title (EN)**: Providing visibility and recommendations for batch processing  
**Pub. No.**: US12705106

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Nirmal Ganesh Nirmal Manoharan](https://patents.google.com/?inventor=Nirmal+Ganesh+Nirmal+Manoharan&country=US&num=100&sort=new), [Xu Yang](https://patents.google.com/?inventor=Xu+Yang&country=US&num=100&sort=new), [James Franz Riggleman](https://patents.google.com/?inventor=James+Franz+Riggleman&country=US&num=100&sort=new)  
**Publication Date**: 11.08.2026

**Abstract**:  
本发明由批处理服务实施，为用户提供其批处理作业的执行指标的可视化，并确定更优的调度策略和/或扩展算法以执行批处理作业。批处理服务收集批处理作业的遥测数据，并分析这些数据以生成执行指标。批处理服务使用这些执行指标生成各种可视化图表，向用户展示其批处理作业的性能。此外，批处理服务分析执行指标，并确定更优化的调度策略和/或扩展算法以运行批处理作业。通过这种方式，批处理服务能够提高批处理作业的执行效率。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484464383_1.jpg)

**Technical Field (技术领域)**:  
云计算技术领域，具体涉及批处理作业的调度和资源管理。

**Background (发明背景)**:  
云计算服务提供商为用户提供计算服务，用户无需自行建设和维护计算基础设施。服务提供商通常提供批处理服务，通过自动化调度和资源扩展来运行大规模批处理作业。然而，由于批处理作业消耗大量计算资源，调度和扩展效率低下会导致计算资源浪费和用户体验不佳。

**Summary (发明总览)**:  
本发明通过收集和分析批处理作业的遥测数据，为用户提供作业执行的可视化视图，帮助用户了解作业性能。同时，通过分析执行指标，系统能够优化批处理作业的调度策略和资源扩展算法，从而提高执行效率。本发明相较于现有技术的主要改进在于引入了数据驱动的优化机制，通过实时分析和调整来提升批处理作业的整体执行效率。

**Key Innovation (核心创新)**:  
1. 收集批处理作业的遥测数据，包括执行时间、资源使用情况等关键指标，为后续分析提供数据基础。
2. 通过分析执行指标，生成直观的可视化图表，帮助用户实时监控批处理作业的性能。
3. 基于历史执行数据，应用机器学习算法优化批处理作业的调度策略，例如调整作业优先级和资源分配。
4. 实现动态资源扩展算法，根据作业负载自动调整虚拟计算资源的使用，避免资源浪费或不足。
5. 提供推荐系统，根据历史数据和当前作业特征，为用户提供优化的调度和扩展建议。
6. 通过持续监控和分析，识别批处理作业中的瓶颈和低效环节，并提供改进建议。
7. 本发明可应用于云计算平台上的各种批处理场景，如数据分析、机器学习训练等，帮助用户提高作业执行效率并降低资源成本。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484464383)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12705106)**
<br/><br/>

---


<br/>

### 39. 直播流处理及其基于传感器的测量呈现

**Title (EN)**: Live stream processing and sensor-based measurement presentation therein  
**Pub. No.**: US12707127

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Shachar Flora Ben Dayan](https://patents.google.com/?inventor=Shachar+Flora+Ben+Dayan&country=US&num=100&sort=new), [Noah Lirone Sarfati](https://patents.google.com/?inventor=Noah+Lirone+Sarfati&country=US&num=100&sort=new), [Yotam Elor](https://patents.google.com/?inventor=Yotam+Elor&country=US&num=100&sort=new)  
**Publication Date**: 11.08.2026

**Abstract**:  
本发明描述了直播流处理及其基于传感器的测量呈现技术。在一个示例中，计算机系统在玩家处于空间内时，实时确定玩家的实时数据。这些实时数据是在空间内进行活动期间生成的。计算机系统在活动期间基于实时数据生成人工智能模型的输入，并确定人工智能模型的输出。该输出基于输入并指示对玩家在活动中将要执行的动作的预测。计算机系统基于该预测，在活动期间呈现用户界面元素，该用户界面元素指示该预测。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484466616_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及直播流处理技术，
结合人工智能模型和传感器数据，
用于实时动作预测和用户界面呈现。

**Background (发明背景)**:  
在线服务通常用于记录事件并向用户设备分发视频流。
现有技术中，摄像头从单一视角记录活动，
例如体育赛事中的动作，但无法提供个性化或预测性信息。
这导致观众只能被动观看，无法获得互动或预测性体验。
本发明旨在通过实时数据处理和人工智能模型，
提供对玩家动作的预测并以用户界面形式呈现。

**Summary (发明总览)**:  
本发明通过实时处理传感器数据并结合人工智能模型，
实现对玩家动作的预测。
具体来说，系统在活动期间收集实时数据，
生成人工智能模型的输入，
并基于模型输出预测玩家即将执行的动作。
系统随后在用户界面上呈现这些预测信息，
为观众提供互动性和预测性的观看体验。
相较于传统直播技术，本发明引入了实时数据分析和预测功能，
提升了用户对直播内容的参与度和理解。

**Key Innovation (核心创新)**:  
1. 通过传感器实时收集玩家在空间内的动作数据，
实现对活动细节的精确捕捉。
2. 基于实时数据生成人工智能模型的输入，
利用机器学习算法预测玩家即将执行的动作。
3. 将模型预测结果以用户界面元素的形式呈现，
为观众提供直观的预测信息。
4. 系统在活动进行期间持续更新数据和预测结果，
确保信息的实时性和准确性。
5. 通过结合传感器数据和人工智能模型，
提供超越传统直播的互动性和预测性功能。
6. 该技术可应用于体育赛事、虚拟现实游戏等场景，
为观众和参与者提供独特的互动体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484466616)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12707127)**
<br/><br/>

---


<br/>

### 40. 用于自主移动设备运动的低矮障碍物检测系统

**Title (EN)**: System for determining low-height obstacle for autonomous mobile device movement  
**Pub. No.**: US12703095

**Applicant**: AMAZON TECHNOLOGIES, INC.  
**Inventor**: [Mohammad Hadi Tabatabaee](https://patents.google.com/?inventor=Mohammad+Hadi+Tabatabaee&country=US&num=100&sort=new), [Shreekant Gayaka](https://patents.google.com/?inventor=Shreekant+Gayaka&country=US&num=100&sort=new)  
**Publication Date**: 11.08.2026

**Abstract**:  
一种自主移动设备（AMD）在可能包含可安全穿越的低矮障碍物（LHO）的物理空间中移动。传感器获取包括图像数据和距离数据的深度图像数据。深度图像数据被处理以确定分割数据，将图像中的像素分类为“地面”或“非地面”。分割数据被处理以确定由“地面”像素包围的“非地面”像素的聚类。每个聚类周围确定一个边界框。距离数据被处理以确定估计地面平面以上各点的高度。每个边界框内像素对应点的高度用于计算指标，例如接近地面的点与低于最大高度的所有点的比率。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484462165_1.jpg)

**Technical Field (技术领域)**:  
自主移动机器人技术，具体涉及低矮障碍物检测与识别。

**Background (发明背景)**:  
自主移动设备（AMD）在物理空间中移动时，需要获取环境信息以进行导航和任务执行。现有技术中，障碍物检测主要关注较高障碍物，而对低矮障碍物的处理能力不足。低矮障碍物可能影响设备移动的稳定性和安全性，但传统方法难以有效识别和分类这些障碍物。本发明旨在解决低矮障碍物检测和分类的难题，以提高自主移动设备的环境适应能力。

**Summary (发明总览)**:  
本发明提出了一种用于自主移动设备检测低矮障碍物的系统。通过传感器获取深度图像数据，系统将图像像素分类为地面和非地面，并识别非地面像素的聚类。系统计算每个聚类的高度信息，以确定障碍物的可穿越性。与传统方法相比，本发明能够更准确地识别低矮障碍物，并评估其对设备运动的影响，从而提高自主移动设备在复杂环境中的导航能力。

**Key Innovation (核心创新)**:  
1. 采用深度图像数据处理技术，将图像像素分类为“地面”和“非地面”，实现对低矮障碍物的初步识别。
2. 通过聚类分析识别由“地面”像素包围的“非地面”像素区域，精确定位低矮障碍物的位置和范围。
3. 利用距离数据计算每个障碍物的高度信息，并基于估计的地面平面确定障碍物的可穿越性。
4. 设计了一种基于边界框的评估方法，通过计算接近地面的点与总点数的比率，量化低矮障碍物的特征。
5. 该系统能够实时处理传感器数据，适应动态环境变化，提高自主移动设备在复杂地形中的导航能力。
6. 应用于室内外自主移动机器人，可有效识别如门槛、地毯边缘等低矮障碍物，提升设备移动的稳定性和安全性。
7. 通过精确的低矮障碍物检测和分类，本发明能够减少设备碰撞风险，优化运动路径规划。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484462165)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12703095)**
<br/><br/>

---



**Total Patents**: 40  
**Last Updated**: 20260816

---

The Patent Scoop Trio
