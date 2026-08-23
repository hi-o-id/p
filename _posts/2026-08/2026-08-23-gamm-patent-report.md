---
layout: post
title: "其他专利小快报 2026-08-23"
date: 2026-08-23 13:43:44 +0800
categories: 其他
---

**New Patents**: 32  

---


<br/>

### 1. 基于群体偏好对齐的定制化大语言模型响应

**Title (EN)**: CUSTOMIZED LLM RESPONSES BY GROUP PREFERENCE ALIGNMENT  
**Pub. No.**: US20260244671

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Jennifer Lynay NEVILLE](https://patents.google.com/?inventor=Jennifer+Lynay+NEVILLE&country=US&num=100&sort=new), [Sujay Kumar Jauhar](https://patents.google.com/?inventor=Sujay+Kumar+Jauhar&country=US&num=100&sort=new), [Jack Wilson Stokes, III](https://patents.google.com/?inventor=Jack+Wilson+Stokes%2C+III&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种基于群体意图感知的大语言模型（LLM）定制方法。该方法包括使用第一生成模型从现实世界对话日志中的用户响应中提取并关联隐式判断，这些隐式判断指示了与对话日志相关的对话的偏好或非偏好。随后，使用第一或第二生成模型将第一生成模型的隐式判断总结为通用偏好方面，从而生成特定于群体的评估标准，这些评估标准显示了群体之间在通用偏好方面的显著差异。基于生成模型的群体特定评估标准，本发明进一步包括：（i）增强对第三生成模型的提示，形成增强提示并将其提供给第三生成模型；或者（ii）对第三生成模型进行微调，使其成为与群体特定评估标准对齐的生成模型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206492_1.jpg)

**Technical Field (技术领域)**:  
本专利属于自然语言处理领域，具体涉及大语言模型的个性化定制技术。

**Background (发明背景)**:  
生成模型通常采用一刀切的训练范式，难以满足不同用户群体的特定需求。这种方法忽略了不同群体在对话偏好上的差异，导致生成模型在处理特定任务时表现不佳。例如，专家和非专家用户对术语和解释的需求不同，文化背景也会影响偏好。本发明旨在解决生成模型在个性化定制方面的不足，通过识别群体间的偏好差异并调整模型输出以更好地满足这些需求。

**Summary (发明总览)**:  
本发明提出了一种基于群体偏好对齐的生成模型定制方法，通过两步实现：首先，从现实世界对话日志中提取并总结群体间的显著偏好差异，形成特定于群体的评估标准；其次，利用这些评估标准，通过动态调整提示或微调模型参数来生成符合群体特定偏好的响应。该方法相较于现有技术，能够更准确地捕捉用户群体的隐式偏好，并在不牺牲模型核心能力的前提下，显著提升生成模型对用户偏好的对齐度。

**Key Innovation (核心创新)**:  
1. 提出了一种群体感知偏好提取方法，通过分析现实世界对话日志，提取并总结群体间的显著偏好差异，形成可解释的评估标准。
2. 开发了两种基于评估标准的个性化响应生成方法：一种是通过上下文相关的提示动态调整响应，另一种是通过生成对比性合成数据对模型进行微调。
3. 实现了基于GPT4作为评判者的自动化评估，验证了该方法在提升生成模型对用户偏好对齐度方面的有效性，同时保持了模型在标准基准测试中的稳健性能。
4. 创新性地结合了群体偏好和意图感知技术，通过分析用户对对话的满意度和原因，识别不同群体间的偏好差异。
5. 提出了使用对比性合成数据训练模型的方法，通过生成与偏好和非偏好相关的对话示例，提升模型对特定群体偏好的适应性。
6. 该方法可应用于多种场景，如教育、医疗和编程等领域，通过定制化响应更好地满足不同用户群体的需求。
7. 推测该技术可应用于智能客服系统、个性化推荐和内容生成等领域，为用户提供更精准、更符合其偏好的服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206492)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244671)**
<br/><br/>

---


<br/>

### 2. 浏览器内设备端人工智能处理

**Title (EN)**: On-Device Artificial Intelligence Processing In-Browser  
**Pub. No.**: US20260244697

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ori ZIV](https://patents.google.com/?inventor=Ori+ZIV&country=US&num=100&sort=new), [Barak KINARTI](https://patents.google.com/?inventor=Barak+KINARTI&country=US&num=100&sort=new), [Ben BAKHAR](https://patents.google.com/?inventor=Ben+BAKHAR&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本公开示例描述了用于设备端、浏览器内人工智能处理的系统和方法。在示例中，接收人工智能管道的选择，并接收与该人工智能管道相关联的内容。内容被分割成多个数据段，并为数据段生成一组数据特征。加载与人工智能管道相关联的人工智能模块以创建人工智能管道。将数据特征集提供给人工智能管道。执行人工智能管道以生成数据特征集的洞察。然后将洞察提供给用户。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206522_1.jpg)

**Technical Field (技术领域)**:  
人工智能处理技术，具体涉及浏览器内设备端人工智能管道执行。

**Background (发明背景)**:  
人工智能模型的运行通常依赖于服务器或云端计算环境，这带来了高昂的计算成本。随着人工智能复杂性和使用量的增加，这些成本也在上升。尽管客户端设备的硬件能力有所提升，但在设备端执行人工智能仍面临兼容性问题、性能下降以及数据安全挑战。本发明旨在解决这些问题，通过在设备端浏览器内实现人工智能处理，降低成本并提高数据隐私。

**Summary (发明总览)**:  
本发明提出了一种在设备端浏览器内执行人工智能处理的方法。用户通过客户端浏览器界面选择或创建人工智能管道，管道由多个AI模块组成。内容被分割并生成特征后，传递给管道进行处理，最终生成洞察并展示给用户。该方法通过在客户端执行AI处理，降低了云端计算成本，同时增强了数据隐私保护。

**Key Innovation (核心创新)**:  
1. 实现了客户端浏览器内的人工智能处理框架，通过在设备端执行AI任务，降低了对云端计算资源的依赖。
2. 提供了用户界面，允许用户通过可视化方式创建、编辑和调整AI管道，包括修改AI模块及其排列顺序。
3. 支持对多种数据类型（如视频、音频、图像和文本）进行分割和特征提取，以适应不同AI处理需求。
4. 通过加载和排列AI模块来动态构建AI管道，实现了灵活的任务处理流程。
5. 提供了AI管道的可视化机制，使用户能够直观地查看管道结构（如依赖图）并进行修改。
6. 增强了数据隐私，因为AI处理在设备端进行，减少了数据在传输过程中的暴露风险。
7. 适用于需要实时AI处理和隐私保护的应用场景，如个人设备上的内容分析工具或企业内部的AI辅助系统。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206522)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244697)**
<br/><br/>

---


<br/>

### 3. 使用虚拟光源照亮混合现实场景

**Title (EN)**: LIGHTING A MIXED-REALITY SCENE USING A VIRTUAL LIGHT SOURCE  
**Pub. No.**: US20260245297

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jun Miao](https://patents.google.com/?inventor=Jun+Miao&country=US&num=100&sort=new), [Chuong Nguyen](https://patents.google.com/?inventor=Chuong+Nguyen&country=US&num=100&sort=new), [Alex Dongseok Shin](https://patents.google.com/?inventor=Alex+Dongseok+Shin&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
一种实施方式包括使用训练数据集训练场景重光照模型，以将虚拟光源对混合现实场景的影响纳入其中，训练结果得到一个训练好的场景重光照模型。
一种实施方式包括从混合现实场景的第一帧的第一颜色数据和第一深度数据以及第一虚拟光源的数据中，使用训练好的场景重光照模型生成对应于第一帧的第二帧，第二帧纳入了第一虚拟光源对混合现实场景的影响。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485207182_1.jpg)

**Technical Field (技术领域)**:  
混合现实技术领域，具体涉及使用虚拟光源照亮混合现实场景。

**Background (发明背景)**:  
混合现实（MR）结合了虚拟现实（VR）和增强现实（AR），通过计算系统呈现虚拟内容与现实世界的融合。
现有技术中，虚拟对象通常仅由现实世界的环境光照明，缺乏虚拟光源对现实世界部分场景的逼真影响。
例如，虚拟台灯应能照亮现实中的桌子，但现有技术无法实现这种效果。
这导致虚拟光源与现实场景的交互显得不真实，尤其在较暗的场景中更为明显。

**Summary (发明总览)**:  
本发明提出了一种使用虚拟光源照亮混合现实场景的方法。
通过训练数据集和机器学习技术，训练场景重光照模型以模拟特定虚拟光源对混合现实场景的影响。
利用训练好的模型，从混合现实场景的帧数据中生成包含虚拟光源效果的新帧。
该方法不仅能处理虚拟对象，还能让虚拟光源对现实场景产生真实的光照效果。
相较于现有技术，本发明实现了虚拟光源与现实场景的动态交互，提升了混合现实场景的真实感。

**Key Innovation (核心创新)**:  
1. 通过训练数据集和机器学习技术，训练场景重光照模型以模拟虚拟光源对混合现实场景的影响。
2. 使用人工神经网络实现场景重光照模型，并采用现有的神经网络训练技术进行训练。
3. 构建虚拟光源库，每个虚拟光源对应一个训练好的场景重光照模型，便于快速调用和渲染。
4. 引入基于用户注视点的注视点渲染技术，根据用户注视位置调整渲染细节，提高渲染效率。
5. 通过混合现实头显传感器数据（如惯性测量单元、眼球追踪等）计算用户注视点，实现动态渲染。
6. 考虑帧间连续性，避免对每一帧都进行重光照处理，减少视觉不一致性。
7. 该技术可应用于混合现实装饰应用、虚拟游戏等场景，为用户提供更逼真的虚拟光源与现实场景交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485207182)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260245297)**
<br/><br/>

---


<br/>

### 4. 通过可变运动学特征的滑动手势导航用户界面元素

**Title (EN)**: NAVIGATING THROUGH USER INTERFACE ELEMENTS WITH A VARIABLE KINEMATIC PROFILE SWIPE GESTURE  
**Pub. No.**: US20260244275

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Pablo Tostado Marcos](https://patents.google.com/?inventor=Pablo+Tostado+Marcos&country=US&num=100&sort=new), [Anoushka Tiwari](https://patents.google.com/?inventor=Anoushka+Tiwari&country=US&num=100&sort=new), [Francisco Jose Luongo](https://patents.google.com/?inventor=Francisco+Jose+Luongo&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明描述了一种用于导航一个或多个用户界面元素的方法。该方法包括显示多个用户界面元素，获取拇指在食指上执行第一次滑动手势期间生成的数据，该第一次滑动手势具有第一运动学特征，并根据第一运动学特征，以第一速率使焦点选择器在第一组用户界面元素中移动。该方法还包括获取拇指在食指上执行第二次滑动手势期间生成的额外数据，该第二次滑动手势具有与第一次滑动手势不同的第二运动学特征，并根据第二运动学特征，使焦点选择器移动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206056_1.jpg)

**Technical Field (技术领域)**:  
本专利属于可穿戴设备输入系统领域，具体涉及基于可变运动学特征的滑动手势检测与解释技术，用于用户界面导航。

**Background (发明背景)**:  
可穿戴设备作为与电子设备和用户界面交互的输入机制日益普及。这些设备通过检测用户的手势来实现界面导航、元素选择等交互。然而，不同用户的手势执行方式存在强度、速度、力度和位移的差异，导致现有通用手势识别模型难以满足个性化需求。

**Summary (发明总览)**:  
本发明提出了一种基于个性化手势识别的用户界面导航方法。通过检测用户滑动手势的运动学特征，系统能够区分普通滑动手势和强力滑动手势，并据此调整界面元素的滚动速率和数量。该方法通过神经肌肉信号传感器收集数据，并应用双峰分布模型确定区分不同手势的阈值，从而提供更精准和符合用户习惯的交互体验。

**Key Innovation (核心创新)**:  
1. 通过神经肌肉信号传感器实时捕捉用户滑动手势的细微运动学特征，实现高精度手势识别。
2. 应用双峰分布模型分析手势数据，区分普通滑动手势和强力滑动手势，并设定相应阈值。
3. 根据手势的运动学特征动态调整用户界面元素的滚动速率和数量，提供个性化交互体验。
4. 支持在多种可穿戴设备上实现，包括AR眼镜、智能手表和智能服装等，扩展应用场景。
5. 通过个性化手势识别技术，提升用户在扩展现实（XR）环境中的交互效率和操作准确性。
6. 特别适用于需要精准控制和高响应速度的应用场景，如混合现实（MR）中的虚拟对象操作。
7. 为用户提供更自然、直观的交互方式，减少学习成本，同时适应不同用户的手势习惯。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206056)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244275)**
<br/><br/>

---


<br/>

### 5. 基于物理约束的AI生成视觉内容检测方法

**Title (EN)**: DETECTION OF INAUTHENTIC VISUAL CONTENT USING PHYSICS BASED CONSTRAINTS  
**Pub. No.**: US20260245390

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Amit MANCHANDA](https://patents.google.com/?inventor=Amit+MANCHANDA&country=US&num=100&sort=new), [Shubhojit Mallick](https://patents.google.com/?inventor=Shubhojit+Mallick&country=US&num=100&sort=new), [Nithya Ragupathy](https://patents.google.com/?inventor=Nithya+Ragupathy&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本技术涉及一种机器学习检测模型，用于检测AI操纵的媒体内容，例如视频和图像。该技术使用机器学习算法分析视频和图像以生成真实性评分。检测模型经过训练以理解基于物理的约束。由于难以完全按照物理规则修改或生成图像，因此检测模型能够识别图像和视频中可能的物理规则偏差，并利用这些差异生成真实性指标。基于物理的约束可能包括光学感知、重力感知、材料属性感知、能量守恒和物理交互感知。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485207286_1.jpg)

**Technical Field (技术领域)**:  
人工智能安全领域，具体涉及AI生成内容检测技术。

**Background (发明背景)**:  
随着生成式AI模型（如LLM、扩散模型、GAN等）的快速发展，其在视频和图像生成方面的应用日益广泛。然而，这也带来了安全隐患，例如生成深度伪造内容用于传播虚假信息或进行网络骚扰。现有的AI生成内容难以被人类有效识别，这凸显了检测AI生成内容的重要性。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的AI生成内容检测技术，通过分析媒体内容生成真实性评分。该技术利用物理约束来识别AI生成或篡改的媒体内容。检测模型通过理解光学、重力、材料属性、能量守恒和物理交互等物理约束，能够识别不符合物理规律的内容，从而区分真实与虚假媒体。本发明通过结合VAE和cGAN模型，利用物理约束生成逼真图像，并与输入图像进行比较，以检测潜在的篡改行为。

**Key Innovation (核心创新)**:  
1. 采用基于物理约束的VAE编码器，通过在潜在空间中强制执行物理约束，确保生成图像符合物理规律。
2. 使用物理约束的cGAN生成器，通过输入由VAE生成的物理约束潜在空间，生成符合物理规律的新图像。
3. 通过比较输入图像与物理约束生成图像的差异，生成真实性评分，并标记显著差异区域。
4. 在VAE编码器中引入多层物理约束层，每层可针对特定物理规则进行训练，例如光学、重力和材料属性。
5. 采用多目标训练框架，同时优化VAE和cGAN模型参数，通过加权损失函数平衡多个训练目标。
6. 该技术可应用于检测深度伪造视频和图像，通过识别不符合物理规律的内容来防止虚假信息的传播。
7. 独特价值在于提供了一种可靠的媒体真实性验证工具，可用于身份验证、欺诈检测等安全领域。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485207286)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260245390)**
<br/><br/>

---


<br/>

### 6. 量子计算按需协同处理资源

**Title (EN)**: ON-DEMAND CO-PROCESSING RESOURCES FOR QUANTUM COMPUTING  
**Pub. No.**: US20260244498

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Milan Krneta](https://patents.google.com/?inventor=Milan+Krneta&country=US&num=100&sort=new), [Eric M. Kessler](https://patents.google.com/?inventor=Eric+M.+Kessler&country=US&num=100&sort=new), [Christian Bruun Madsen](https://patents.google.com/?inventor=Christian+Bruun+Madsen&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
提供商网络的算法执行管理系统可接收用户请求，使用不同类型的计算资源（包括经典计算资源和量子计算资源）来执行算法。该请求可指示包含算法代码及其执行依赖项（如库）的容器。算法执行管理系统首先确定量子计算资源可用于执行算法，然后配置经典计算资源。系统可使用用户指示的容器在经典计算资源上执行算法的一部分，并在量子计算资源上执行算法的另一部分。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206302_1.jpg)

**Technical Field (技术领域)**:  
量子计算与经典计算协同处理技术领域，具体涉及算法执行管理和资源调度。

**Background (发明背景)**:  
云计算服务允许用户通过网络访问远程资源，而基于云的量子计算服务则提供对不同量子硬件提供商的量子计算机的访问。量子计算机利用量子物理定律处理信息，与经典计算机相比具有叠加和纠缠等特性。然而，用户在使用不同计算资源时自行设置和管理计算环境较为困难，且执行效率难以保证。本发明旨在解决这一问题，通过自动化管理算法执行流程来提高效率。

**Summary (发明总览)**:  
本发明提出了一种算法执行管理系统，能够协调经典计算资源和量子计算资源来执行用户算法。系统通过容器化技术封装算法代码及其依赖项，并根据资源可用性动态配置经典计算资源作为量子计算的协同处理器。执行完成后，系统将结果存储并通知用户，同时释放计算资源供其他任务使用。该方案简化了用户操作流程，提高了资源利用率，并优化了算法执行性能。

**Key Innovation (核心创新)**:  
1. 通过容器化技术封装算法代码及其依赖项，为用户提供标准化的计算环境，简化了跨不同计算资源的算法部署流程。
2. 动态检测量子计算资源的可用性，并在资源就绪后按需配置经典计算资源作为协同处理器，优化了资源调度效率。
3. 在算法执行期间，为量子计算任务分配优先级，确保算法在量子资源上的执行优先级高于其他任务，从而缩短执行时间并提高执行的可预测性。
4. 采用容器化计算环境运行算法代码，确保执行过程的可重复性和隔离性，同时支持用户自定义计算环境以满足特定需求。
5. 在算法执行完成后，系统自动释放经典和量子计算资源，提高资源利用率并降低用户成本，尤其适用于按需付费模式。
6. 提供用户友好的接口，允许用户选择量子计算资源类型并提交算法执行请求，降低了量子计算的使用门槛。
7. 该系统可应用于需要高性能计算和复杂问题求解的领域，如材料科学、药物研发和金融建模，为用户提供更高效、更经济的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206302)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244498)**
<br/><br/>

---


<br/>

### 7. 协调集外围设备的配对和连接管理

**Title (EN)**: COORDINATED SET PERIPHERAL DEVICE PAIRING AND CONNECTION MANAGEMENT  
**Pub. No.**: US20260244580

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Sharib SHAMIM](https://patents.google.com/?inventor=Sharib+SHAMIM&country=US&num=100&sort=new), [Raamish MALIK](https://patents.google.com/?inventor=Raamish+MALIK&country=US&num=100&sort=new), [Sidhi LOHIA](https://patents.google.com/?inventor=Sidhi+LOHIA&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种协调集外围设备的配对和连接管理系统与方法。通常，在将外围设备与主机设备配对时，会向用户呈现一个选项以同意将发现的设备连接到主机设备。在实施例中，在呈现连接选项之前，配对服务会获取有关发现的设备的产品特定详细信息，并确定该设备是否属于协调集的一部分。这些详细信息从主机设备和/或外围设备的原始设备制造商处收集并存储在本地和/或云目录中。当确定发现的设备为协调集设备时，会向用户呈现包括多成员连接选项在内的各种用户界面元素。用户选择多成员连接选项后，可以通过单一用户交互同意连接协调集外围设备的所有或部分成员。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206392_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及无线外围设备配对技术，具体为协调集设备的多设备配对和连接管理。

**Background (发明背景)**:  
当前，外围设备通常需要与主机设备配对才能使用无线连接。现有的配对方案通常会向用户展示范围内的外围设备，用户需选择特定设备进行配对。然而，当外围设备是协调集设备（例如一对耳机或一组传感器节点）时，用户可能需要多次交互才能配对所有设备，这容易导致混淆。本发明旨在解决多设备协调集配对过程中用户体验不佳的问题。

**Summary (发明总览)**:  
本发明提出了一种协调集外围设备的配对和连接管理方法。通过主机设备上的配对服务与云端目录通信，获取外围设备的产品特定信息，从而在配对前确定设备是否属于协调集。当检测到设备为协调集设备时，系统会向用户呈现多成员连接选项，允许用户通过单一交互同意连接协调集的所有或部分设备。这种方法简化了配对流程，减少了用户交互次数，并提高了连接的安全性和准确性。

**Key Innovation (核心创新)**:  
1. 通过云端目录收集和存储外围设备的产品特定信息（如型号和制造商），使主机设备能够在配对前识别协调集设备。
2. 在检测到协调集设备时，系统会向用户呈现多成员连接选项，允许用户通过单一用户交互同意连接所有或部分设备。
3. 存储的外围设备详细信息包括协调集设备的特定图像或图标，这些信息作为用户界面的提示，减少了用户选择错误设备的可能性。
4. 系统提供与外围设备相关的配套应用程序或服务的链接，用户可以通过该链接下载或打开应用程序以访问设备的附加功能。
5. 通过减少用户交互步骤和提供明确的设备信息，本发明简化了协调集设备的配对流程，提高了用户体验。
6. 该方法适用于多种协调集设备场景，如耳机组、扬声器组和传感器网络等，能够有效支持复杂的多设备连接需求。
7. 通过提供更直观的配对界面和更安全的连接方式，本发明提升了用户对协调集设备的使用信心和满意度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206392)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244580)**
<br/><br/>

---


<br/>

### 8. 服务器机柜门百叶窗及控制系统

**Title (EN)**: SERVER RACK DOOR LOUVER AND CONTROL SYSTEMS  
**Pub. No.**: US20260247559

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Freddie BELL, JR.](https://patents.google.com/?inventor=Freddie+BELL%2C+JR.&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
一种服务器机柜门组件包括：(i) 一个包含通风区域的门板，用于允许气流穿过门板；(ii) 一个或多个压力传感器，用于收集指示门板压力降的压力数据；(iii) 一个与门板连接的百叶窗系统，包括：(1) 多个叶片；(2) 一个或多个与多个叶片机械连接的致动器，用于调整多个叶片的倾斜角度；(3) 一个或多个控制器，用于生成或接收基于门板压力降指示的压力数据确定的多个叶片的倾斜角度，并控制一个或多个致动器以调整叶片的倾斜角度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485209675_1.jpg)

**Technical Field (技术领域)**:  
服务器机柜冷却技术领域，具体涉及机柜门百叶窗及气流控制系统。

**Background (发明背景)**:  
服务器是用于通过网络向其他计算机提供数据、资源和服务的强大计算机，通常部署在数据中心以确保可靠性和性能。数据中心的关键考虑因素包括温度控制、湿度调节和高效电源管理。服务器通常放置在机柜中以便于空间利用、维护和通风。现有的热通道封闭技术虽然能提高冷却效率，但存在气流湍流和热空气渗入服务器机柜的问题，影响冷却效果并增加设备过热风险。

**Summary (发明总览)**:  
本发明提出了一种服务器机柜门组件，通过在门板上集成通风区域和百叶窗系统，利用压力传感器收集压力数据，并根据数据动态调整百叶窗叶片的倾斜角度，以优化机柜内部和热通道的气流方向，减少湍流并防止热空气渗入服务器机柜。该系统能够根据服务器内部温度、气流特性和热通道气流状况等条件进行实时调整，从而提升冷却效率并保障服务器稳定运行。

**Key Innovation (核心创新)**:  
1. 集成通风区域的门板设计，通过内部气流引导实现机柜内外空气交换。
2. 压力传感器实时监测门板压力降，为百叶窗系统提供动态调整依据。
3. 百叶窗系统采用可调节叶片倾斜角度设计，通过致动器实现对气流方向的精确控制。
4. 控制器根据压力数据和其他环境参数（如温度、气流速度）动态调整叶片角度，优化气流分布并减少湍流。
5. 通过减少热空气渗入和气流湍流，提升服务器机柜的冷却效率并降低设备过热风险。
6. 该系统不仅适用于热通道封闭技术（HAC），也可扩展应用于冷通道封闭技术（CAC）等多种场景。
7. 通过优化气流管理，本发明可提高数据中心能源效率并延长服务器使用寿命，适用于高密度服务器部署环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485209675)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260247559)**
<br/><br/>

---


<br/>

### 9. 基于演示的任务辅助的机器学习方法

**Title (EN)**: DEMONSTRATION-BASED TASK ASSISTANCE USING MACHINE LEARNING  
**Pub. No.**: US20260244470

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Andrew D. WILSON](https://patents.google.com/?inventor=Andrew+D.+WILSON&country=US&num=100&sort=new), [Vibhav VINEET](https://patents.google.com/?inventor=Vibhav+VINEET&country=US&num=100&sort=new), [Balasaravanan Thoravi KUMARAVEL](https://patents.google.com/?inventor=Balasaravanan+Thoravi+KUMARAVEL&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明涉及使用机器学习模型来帮助用户完成现实世界中的任务。公开的实施方式可以获取第一用户执行现实世界任务的演示视频。然后，可以处理该演示视频以获得增强数据，这些数据可以在稍后用于帮助另一用户执行该任务。例如，增强数据可以包括演示视频中的关键帧或为关键帧生成的字幕。当另一用户尝试执行该任务时，可以检索选定的增强数据，并用于提示生成模型回答与任务相关的用户查询。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206270_1.jpg)

**Technical Field (技术领域)**:  
人工智能，机器学习，任务辅助系统

**Background (发明背景)**:  
近年来，生成式机器学习模型在生成内容方面展示了巨大的能力，例如生成文本总结现有文档或生成图像。然而，这些模型在理解人类如何与物理世界互动方面存在局限，难以有效辅助涉及物理交互的现实世界任务。

**Summary (发明总览)**:  
本发明提出了一种利用生成式机器学习模型辅助用户完成现实世界任务的方法。通过获取第一用户的任务演示视频并结合上下文信号进行分割，系统生成与视频片段相关的增强数据并存储在数据库中。当第二用户尝试执行同一任务时，系统基于输入图像检索相关增强数据，并使用生成式模型生成对用户查询的解答，从而提供任务指导。这种方法使生成式模型能够利用上下文数据更有效地辅助用户完成任务。

**Key Innovation (核心创新)**:  
1. 通过获取第一用户的任务演示视频并结合上下文信号（如语音、注视方向、手势等）进行视频分割，实现对任务流程的精细化分析。
2. 利用多模态生成模型为视频片段生成增强数据，包括关键帧和字幕，从而为后续任务辅助提供丰富的信息资源。
3. 构建一个数据库存储增强数据，支持基于用户输入图像的快速检索和匹配，确保在用户需要时提供精准的指导信息。
4. 采用生成式模型结合检索到的增强数据生成对用户查询的解答，使模型能够利用上下文信息提供更准确的指导。
5. 该方法不要求对特定任务进行专门训练或微调，通用性强，可应用于多种现实世界任务。
6. 通过提供关键帧和字幕作为辅助信息，帮助用户更直观地理解任务步骤，提升学习效率和执行准确性。
7. 该技术可应用于智能助手、远程指导系统或机器人任务学习等领域，为复杂任务的执行提供创新解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206270)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244470)**
<br/><br/>

---


<br/>

### 10. 安全硬件强制传感器隐私系统及其执行方法

**Title (EN)**: Secure Hardware-Enforced Sensor Privacy Systems And Methods for Performing Thereon  
**Pub. No.**: US20260244794

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Sudhir Satpathy](https://patents.google.com/?inventor=Sudhir+Satpathy&country=US&num=100&sort=new), [Wojciech Stefan Powiertowski](https://patents.google.com/?inventor=Wojciech+Stefan+Powiertowski&country=US&num=100&sort=new), [Marcus Eugene Hodges](https://patents.google.com/?inventor=Marcus+Eugene+Hodges&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种系统，包括一个静音电路，该电路存储一个只能通过硬件操作修改的静音状态。电路接收来自硬件源的静音触发信号。在接收到静音触发信号时，静音电路将强制静音状态原子性地应用于一个或多个传感器。当不再接收到静音触发信号时，静音电路原子性地清除一个或多个传感器上的强制静音状态。本文中描述的电路、系统和方法的实施使得在消费设备（如增强现实设备）中实现硬件强制传感器隐私成为可能。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206629_1.jpg)

**Technical Field (技术领域)**:  
硬件安全架构，传感器隐私控制，硬件强制隐私机制

**Background (发明背景)**:  
传统系统中的传感器隐私机制通常依赖于软件控制，容易受到软件漏洞的篡改或操纵。基于软件的隐私状态转换缺乏原子性，可能导致隐私保护不完整或不一致。此外，具有固定隐私配置的系统难以适应不断变化的隐私政策或动态系统需求。此外，传统的传感器处理架构通常将所有传感器数据通过主操作系统控制下的公共处理路径传输，这可能将敏感传感器数据暴露于操作系统的潜在安全漏洞中。

**Summary (发明总览)**:  
本发明通过硬件强制机制解决现有软件隐私控制的安全漏洞问题。其核心思路是实现硬件级别的静音操作，确保传感器隐私状态的切换是原子性的且不可被软件篡改。通过硬件锁定的静音掩码和可配置的触发机制，系统能够提供防篡改的隐私控制。此外，本发明通过隔离的安全和非安全处理路径以及可信执行环境，保护传感器数据免受操作系统和应用的安全威胁，同时提供准确的隐私状态指示。

**Key Innovation (核心创新)**:  
1. 采用硬件强制静音机制，通过硬件操作控制传感器静音状态，确保静音操作的原子性和不可篡改性，防止软件攻击。
2. 使用硬件锁定的静音掩码寄存器，仅支持写1置位操作，防止软件从静音状态中移除传感器，增强隐私保护。
3. 实现跨多个处理单元的协调静音操作，通过定时器和多微控制器单元同步状态转换，防止部分传感器未被静音的情况。
4. 采用隔离的安全和非安全处理路径，传感器数据通过专用硬件处理，不暴露于主操作系统，保护敏感数据。
5. 通过可信执行环境控制传感器数据路由和隐私指示器管理，确保用户获得准确的隐私状态信息。
6. 静音操作的状态变化由硬件触发信号控制，例如物理开关或硬件生成的请求，完全绕过软件层，增强安全性。
7. 本发明适用于增强现实设备、智能可穿戴设备等消费电子产品，能够在动态隐私需求下提供可靠且安全的传感器隐私保护。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206629)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244794)**
<br/><br/>

---


<br/>

### 11. 使用外部传感器进行手势检测

**Title (EN)**: GESTURE DETECTION USING EXTERNAL SENSORS  
**Pub. No.**: US20260244277

**Applicant**: Google LLC  
**Inventor**: [Katherine Blair Huffman](https://patents.google.com/?inventor=Katherine+Blair+Huffman&country=US&num=100&sort=new), [Gregory Granito](https://patents.google.com/?inventor=Gregory+Granito&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本技术提供了一种用于确定用户所提供的手势的系统。系统的一个或多个处理器可接收来自一个或多个视觉传感器捕获用户动作的图像数据，并接收用户佩戴的一个或多个可穿戴计算设备提供的运动数据。处理器可根据图像数据识别用户身体对应于执行命令的手势部分。处理器还可确定图像数据与接收的运动数据之间的一或多个相关性。基于识别出的用户身体部分以及图像数据与接收的运动数据之间的一或多个相关性，处理器可检测手势。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206058_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及结合视觉传感器与可穿戴设备传感器数据的手势识别技术。

**Background (发明背景)**:  
传统计算设备通常依赖键盘、鼠标等接口进行用户交互，但这些方式在处理三维对象或复杂操作时不够直观便捷。对于智能手表和头戴设备等可穿戴设备，传统接口可能因设备形态限制而无法使用或使用不便。可穿戴设备虽然配备了麦克风和惯性测量单元（IMU）等传感器，但现有技术难以实现精准高效的手势识别。

**Summary (发明总览)**:  
本发明提出了一种结合视觉传感器与可穿戴设备传感器数据的手势检测方法。系统通过视觉传感器捕捉用户动作图像数据，同时接收可穿戴设备提供的运动数据。处理器通过分析图像数据识别用户执行手势的身体部位，并确定图像数据与运动数据之间的相关性，从而实现手势检测。该方法通过多源数据融合提高了手势识别的准确性和可靠性。

**Key Innovation (核心创新)**:  
1. 通过融合来自视觉传感器和可穿戴设备的图像数据和运动数据，实现多源数据协同处理，提升手势识别的准确性。
2. 采用时间戳同步技术，将图像数据与可穿戴设备的惯性测量数据对齐，确保数据的时间一致性。
3. 通过坐标系统转换，将可穿戴设备的惯性测量数据从设备坐标系转换到与图像数据一致的坐标系，解决数据异构问题。
4. 基于识别出的用户身体部位（如手部位置和手指位置）以及运动数据，生成时间序列的运动数据，包括位置、速度和加速度等参数。
5. 利用可穿戴设备的信号强度测量值确定设备与视觉传感器之间的距离，并将其作为手势检测的辅助信息。
6. 通过雷达传感器获取环境中的运动数据，并将其与图像数据相关联，以增强手势检测的鲁棒性。
7. 本发明可应用于智能手表、头戴设备等可穿戴设备，为用户提供更自然直观的人机交互方式，尤其适用于虚拟现实和增强现实场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206058)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244277)**
<br/><br/>

---


<br/>

### 12. 安全生物识别认证架构

**Title (EN)**: Secure Biometric Authentication Architecture  
**Pub. No.**: US20260244726

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jason Haensly](https://patents.google.com/?inventor=Jason+Haensly&country=US&num=100&sort=new), [Hsuhua Yu](https://patents.google.com/?inventor=Hsuhua+Yu&country=US&num=100&sort=new), [Bo-Huei Lin](https://patents.google.com/?inventor=Bo-Huei+Lin&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种使用配套系统级芯片（SoC）的安全生物识别认证系统和方法。该配套SoC相较于主SoC具有更小的面积和更低的功耗，包含用于生物识别处理的机器学习（ML）加速器和一个与主SoC通用处理隔离的子系统，通过片上网络（NoC）互连，并配有访问控制防火墙，仅允许ML加速器访问生物传感器数据和子系统访问存储的生物识别模板。ML加速器通过将生物传感器数据应用于ML模型来生成验证后的传感器数据，并从验证后的传感器数据中生成生物识别签名。子系统用于存储加密的生物识别模板。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206553_1.jpg)

**Technical Field (技术领域)**:  
安全硬件架构，具体涉及使用配套SoC实现安全生物识别认证的技术。

**Background (发明背景)**:  
随着现代电子设备特别是可穿戴设备的发展，安全生物识别认证变得越来越重要。传统方法依赖主SoC进行认证处理，但存在安全风险，如操作系统或应用漏洞可能导致生物数据泄露。此外，主SoC通常不具备硬件级隔离机制，容易受到侧信道攻击，且功耗较高，不适合电池受限的可穿戴设备。

**Summary (发明总览)**:  
本发明提出了一种基于配套SoC的安全生物识别认证架构，通过专用硬件加速器和隔离子系统实现生物数据的处理和存储。该架构通过片上网络（NoC）连接各组件，并采用防火墙机制限制对生物传感器数据和存储模板的访问，从而提高安全性。与传统主SoC实现相比，本发明在保持系统效率的同时，显著降低了功耗并增强了安全性。

**Key Innovation (核心创新)**:  
1. 采用低功耗深度学习加速器处理生物数据，通过帧质量验证和签名生成提高处理效率。
2. 设计了与主SoC通用处理隔离的信任根子系统，用于管理加密生物识别模板和机器学习模型。
3. 通过片上网络（NoC）实现组件互连，并集成防火墙机制，仅允许特定组件访问生物传感器数据和存储模板。
4. 信任根子系统对机器学习模型进行真实性验证，确保模型未被篡改。
5. 在认证过程中实施速率限制机制，防止暴力破解攻击。
6. 在主SoC断电期间，配套SoC可维持认证状态，实现始终在线的认证功能。
7. 适用于可穿戴设备，如智能手表和增强现实（AR）眼镜，提供低功耗、高安全性的生物识别认证解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206553)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244726)**
<br/><br/>

---


<br/>

### 13. 混合文本转语音系统

**Title (EN)**: HYBRID TEXT TO SPEECH  
**Pub. No.**: US20260245543

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Jinzhu LI](https://patents.google.com/?inventor=Jinzhu+LI&country=US&num=100&sort=new), [Guangyu WU](https://patents.google.com/?inventor=Guangyu+WU&country=US&num=100&sort=new), [Yulin LI](https://patents.google.com/?inventor=Yulin+LI&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
一种混合文本转语音（TTS）系统和方法，该系统接收来自用户应用的文本数据；确定接收的文本数据在缓存中缺失；将接收的文本数据同时发送到远程TTS引擎和设备中的TTS引擎；接收来自远程TTS引擎和设备中TTS引擎的语音数据；并基于选择策略选择或组合来自远程TTS引擎或设备中TTS引擎的语音数据。语音数据被传输到用户应用。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485207453_1.jpg)

**Technical Field (技术领域)**:  
文本转语音（TTS）技术领域，具体涉及混合TTS系统架构。

**Background (发明背景)**:  
文本转语音（TTS）技术在现代车辆和物联网设备中应用广泛。现有技术包括在线TTS系统和离线TTS系统，各有优缺点。在线TTS系统质量高、易更新，但依赖网络连接；离线TTS系统无需网络，但质量较低且更新困难。混合TTS系统结合两者，但面临用户体验不连贯、资源管理效率低以及开发复杂性高等挑战。

**Summary (发明总览)**:  
本发明提出了一种混合文本转语音（TTS）架构，通过并行使用在线TTS和本地设备TTS来提供无缝的用户体验。该系统通过统一的TTS接口与远程TTS系统和本地TTS系统通信，减少了计算资源复杂性并提高了系统鲁棒性。统一接口接收文本数据后，将请求同时发送给远程和本地TTS系统，并根据选择策略返回更准确的语音结果。

**Key Innovation (核心创新)**:  
1. 引入统一的TTS接口，简化了用户应用与远程及本地TTS系统的交互，降低了应用层的处理负担。
2. 通过并行请求远程和本地TTS系统，并基于选择策略动态选择结果，提升了语音生成的速度和准确性。
3. 实现了远程和本地TTS系统之间的无缝切换，通过共享语音数据和模型结构，减少了切换时的音质和语调差异。
4. 在网络不稳定或不可用的情况下，系统能够自动切换到本地TTS系统，确保语音生成服务的连续性。
5. 通过减少应用层的复杂逻辑和资源管理需求，降低了开发和维护成本，同时提高了系统整体鲁棒性。
6. 该系统特别适用于非静态平台，如车辆等经常面临网络连接不稳定或缺失的场景。
7. 通过提供更一致的用户体验和更高效的语音生成服务，本发明能够广泛应用于智能设备、车载系统等场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485207453)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260245543)**
<br/><br/>

---


<br/>

### 14. 基于运动触发的快速快门和读取技术

**Title (EN)**: Motion-Triggered Fast Shutter and Readout  
**Pub. No.**: US20260247014

**Applicant**: Google LLC  
**Inventor**: [Vickie Youmin Wu](https://patents.google.com/?inventor=Vickie+Youmin+Wu&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本文档描述了基于运动触发的快速快门和读取技术。这些技术减少了捕捉快速移动物体时产生的运动差异和卷帘快门效应。此外，这些技术实现了一个自适应系统，根据需要提供快速快门速度，最小化后期校正处理，并减少对静止场景区域的功耗。在实施中，相机系统包括一对同步的图像传感器（例如，主传感器和辅助传感器）。辅助传感器以比主传感器更高的帧率和更低的分辨率运行，用于检测运动并向主图像传感器提供运动信息（例如，运动区域和移动物体的速度）。主图像传感器使用专用的模数转换器（ADC）电路来提高运动区域内的像素快门速度和读取速度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485209070_1.jpg)

**Technical Field (技术领域)**:  
图像处理技术领域，具体涉及相机系统中基于运动触发的快速快门和读取技术。

**Background (发明背景)**:  
随着智能手机的普及，相机性能成为关键挑战之一。快速移动的目标会导致运动差异，尤其在使用卷帘快门传感器时，会出现图像失真，如抖动、运动模糊和卷帘快门效应，影响图像质量和用户体验。现有技术如小分辨率全局快门传感器或慢动作模式无法同时满足高分辨率和快速捕捉的需求。

**Summary (发明总览)**:  
本发明提出了一种基于运动触发的快速快门和读取技术，通过使用辅助传感器检测运动并提供运动信息，主传感器针对运动区域提高快门速度和读取速度，从而减少运动差异和卷帘快门效应。该技术无需依赖后期处理校正，节省了功耗并提升了图像质量。与传统方法相比，本发明在捕捉快速移动物体时提供了更高效的解决方案。

**Key Innovation (核心创新)**:  
1. 采用辅助传感器检测运动并提供运动信息，包括运动区域和物体速度，从而实现对快速移动目标的精准捕捉。
2. 主传感器针对运动区域使用专用的模数转换器（ADC）电路，提高快门速度和读取速度，减少卷帘快门效应。
3. 通过分离运动区域和其他区域的处理，主传感器能够针对不同区域采用不同的采样率，优化图像质量和功耗。
4. 辅助传感器以更高的帧率和更低的分辨率运行，能够快速检测运动并忽略颜色信息，提升处理效率。
5. 该技术无需依赖后期处理校正，减少了计算资源消耗并提升了实时性能。
6. 适用于智能手机、运动相机等设备，能够在体育赛事、动物拍摄等场景中提供更清晰的快速移动物体图像。
7. 通过减少对静止场景区域的功耗，提升了整体系统的能效，延长了设备续航时间。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485209070)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260247014)**
<br/><br/>

---


<br/>

### 15. 重格式化内容的生成

**Title (EN)**: Generation of Reformatted Content  
**Pub. No.**: US20260246985

**Applicant**: Google LLC  
**Inventor**: [Jonathan Brunsman](https://patents.google.com/?inventor=Jonathan+Brunsman&country=US&num=100&sort=new), [Yi Yang](https://patents.google.com/?inventor=Yi+Yang&country=US&num=100&sort=new), [Patrick Lacz](https://patents.google.com/?inventor=Patrick+Lacz&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种用于生成重格式化内容的方法、系统、设备和非易失性计算机可读介质。该技术包括获取与音视频内容相关的内容数据段，通过将内容数据输入机器学习分类模型，确定与内容段相关的类别。基于将内容段输入特定于内容的机器学习模型，生成包含基于内容段特征生成的文本或图像的重格式化内容数据。每个内容段被输入到配置为生成重格式化内容段的特定于内容的机器学习模型中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485209039_1.jpg)

**Technical Field (技术领域)**:  
音视频内容处理，机器学习模型应用，文本和图像生成

**Background (发明背景)**:  
随着互联网的发展，用户可以访问多种类型的内容，包括视频内容。然而，某些用户可能更倾向于消费文本或静态图像内容，而不是视频内容。这主要是因为文本和图像的浏览速度通常比视频更快。现有的音视频内容处理方法无法有效满足用户对快速获取信息的需求。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习模型处理音视频内容并生成重格式化内容的方法。该方法首先对音视频内容进行分类，然后利用特定于类别的机器学习模型生成包含文本和图像的重格式化内容。相较于传统方法，本发明能够根据用户需求定制内容格式，并从音视频内容中提取关键信息以生成更易于消费的形式。

**Key Innovation (核心创新)**:  
1. 通过机器学习分类模型对音视频内容进行多维度分类，包括视觉特征、音频特征和文本特征（如字幕数据）。
2. 利用特定于类别的机器学习模型对内容段进行重格式化处理，生成包含文本和图像的组合内容。
3. 重格式化内容的设计风格根据内容类型进行定制，例如餐厅评论和操作指南采用不同的布局和配色方案。
4. 支持基于用户查询生成重格式化内容，能够根据当前或历史搜索查询提取相关内容片段。
5. 采用生成式机器学习模型（如Transformer和扩散模型）进行内容生成，确保生成内容的准确性和多样性。
6. 能够从音视频内容中提取关键信息并生成摘要式文本和图像，提升用户获取信息的效率。
7. 应用于音视频内容平台或搜索引擎，能够为用户提供更快速、更具吸引力的内容消费体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485209039)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260246985)**
<br/><br/>

---


<br/>

### 16. 利用投影仪阵列的近眼显示系统

**Title (EN)**: NEAR-EYE DISPLAY SYSTEMS UTILIZING AN ARRAY OF PROJECTORS  
**Pub. No.**: US20260244027

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Joel Steven KOLLIN](https://patents.google.com/?inventor=Joel+Steven+KOLLIN&country=US&num=100&sort=new), [Andreas GEORGIOU](https://patents.google.com/?inventor=Andreas+GEORGIOU&country=US&num=100&sort=new), [Ishan CHATTERJEE](https://patents.google.com/?inventor=Ishan+CHATTERJEE&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明描述了包括投影仪阵列和一维出瞳扩展器的近眼显示系统。投影仪阵列沿第一维度排列，并输出图像光至波导内的输入耦合器，波导提供一维出瞳扩展。在一些实现中，使用了排列成错列的单色投影仪阵列。输入耦合器将投影仪阵列的图像光耦合到波导内的全内反射路径中。输入耦合器可采用包括衍射光学元件和反射光学元件在内的不同光学元件。图像光在波导内传播，直到与输出耦合器相互作用。图像光与输出耦合器相互作用后，在与第一维度垂直的第二维度上扩展，并从波导中耦合出来。输出耦合器可采用包括衍射光学元件和反射光学元件在内的不同光学元件。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485205783_1.jpg)

**Technical Field (技术领域)**:  
近眼显示技术领域，具体涉及利用投影仪阵列和波导光学元件的显示系统。

**Background (发明背景)**:  
近眼显示技术用于在用户视野中创建虚拟图像，广泛应用于增强现实、虚拟现实和混合现实设备。现有技术中，波导光学元件被用于将光从投影仪传输到用户眼睛，但实现大出瞳扩展时面临尺寸、重量和效率问题。传统方法如使用多个投影仪或复杂光学元件会导致系统体积大、成本高且效率低下。

**Summary (发明总览)**:  
本发明提出了一种利用投影仪阵列和一维出瞳扩展器的近眼显示系统，通过波导光学元件实现图像光的扩展。投影仪阵列沿第一维度排列，图像光被输入耦合器耦合到波导内，并在波导内传播。输出耦合器在第二维度上扩展图像光并将其耦合出波导。该方案通过减少光学元件数量和复杂度，实现了更紧凑、高效的近眼显示系统。

**Key Innovation (核心创新)**:  
1. 采用投影仪阵列设计，通过多个投影仪协同工作，在保证高分辨率和宽视场的同时减少单个投影仪的负担。
2. 使用一维出瞳扩展器，通过波导内的衍射和反射光学元件实现图像光在单一方向上的扩展，降低系统复杂度。
3. 投影仪阵列采用错列排列方式，优化图像光耦合到波导的效率，减少光损失。
4. 输入耦合器采用多种光学元件组合，包括衍射光学元件和反射光学元件，以实现更高效的光耦合。
5. 输出耦合器通过波导内的光学元件实现图像光在第二维度上的扩展，形成更大的出瞳，提升用户体验。
6. 该设计减少了光学元件数量和系统体积，使近眼显示设备更轻薄、更适合日常佩戴。
7. 应用于增强现实和虚拟现实设备时，能够提供更高质量的图像显示和更舒适的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485205783)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244027)**
<br/><br/>

---


<br/>

### 17. 集成天线的显示装置

**Title (EN)**: Antenna Integrated Display  
**Pub. No.**: US20260244243

**Applicant**: Google LLC  
**Inventor**: [Choongho Lee](https://patents.google.com/?inventor=Choongho+Lee&country=US&num=100&sort=new), [Chih-Chun Chang](https://patents.google.com/?inventor=Chih-Chun+Chang&country=US&num=100&sort=new), [Sangmoo Choi](https://patents.google.com/?inventor=Sangmoo+Choi&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种显示组件，包括一个界定内部空间的显示盖板，该内部空间具有中心区域和周边区域。显示组件包括位于中心区域的第一显示区域，具有第一组像素；位于周边区域至少部分区域内的第二显示区域，具有第二组像素，第二显示区域围绕第一显示区域的周边延伸；以及位于第一和第二显示区域之间并围绕第一显示区域周边的非像素化区域。显示组件还包括一个天线区域，其中至少一个天线布置在非像素化区域内，以及涂覆在显示盖板内表面上的不透明涂层，用于覆盖布置在非像素化区域内的天线。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206022_1.jpg)

**Technical Field (技术领域)**:  
可穿戴计算设备技术领域，具体涉及集成天线的显示组件设计。

**Background (发明背景)**:  
可穿戴计算设备（如智能手表）通常需要显示信息和收集用户数据，并依赖无线通信与外部设备交互。然而，将天线有效集成到设备中一直存在挑战，特别是在有限的空间内实现功能与设计的平衡。现有技术难以在不牺牲显示区域或增加设备体积的情况下集成天线。

**Summary (发明总览)**:  
本发明提出了一种创新的显示组件设计方案，通过在显示盖板内部设置非像素化区域，将天线集成到该区域中，并使用不透明涂层进行遮蔽。这种设计在不增加设备体积的情况下，充分利用了显示区域周边的闲置空间，实现了紧凑的天线集成方案。制造方法包括在显示盖板内表面打印导电油墨形成天线和遮蔽涂层。本发明提供了一种更紧凑、高效的天线集成方式，适用于智能手表等可穿戴设备。

**Key Innovation (核心创新)**:  
1. 在显示盖板内部设置非像素化区域，将天线集成到该区域中，充分利用了显示区域周边的闲置空间。
2. 使用导电油墨在显示盖板内表面打印天线，这种方法简化了天线制造工艺并降低了成本。
3. 通过不透明涂层遮蔽天线区域，既保证了天线的功能性，又维持了显示组件的美观性。
4. 天线设计为弯曲形状，贴合显示盖板的曲面结构，进一步优化了空间利用率。
5. 导电油墨可以是金属基或聚合物基材料，具有良好的导电性和遮蔽性能。
6. 该设计特别适用于智能手表等可穿戴设备，在有限空间内实现了天线与显示组件的集成。
7. 创新性地将天线与显示组件结合，在不影响显示效果的前提下，为可穿戴设备提供了更可靠的无线通信能力。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206022)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244243)**
<br/><br/>

---


<br/>

### 18. 基于主动声学传感的相互依赖人类行为检测和/或分类

**Title (EN)**: Interdependent Human Behavior Detection and/or Classification using Active Acoustic Sensing  
**Pub. No.**: US20260240489

**Applicant**: Google LLC  
**Inventor**: [Jason Daniel Guss](https://patents.google.com/?inventor=Jason+Daniel+Guss&country=US&num=100&sort=new), [Xiaoran Fan](https://patents.google.com/?inventor=Xiaoran+Fan&country=US&num=100&sort=new), [Trausti Thormundsson](https://patents.google.com/?inventor=Trausti+Thormundsson&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本专利描述了利用主动声学传感技术进行相互依赖人类行为检测和/或分类的技术和方法。通过主动声学传感，可以在给定时间段内检测和/或分类多种人类行为。相互依赖人类行为检测和/或分类是指利用对第一种人类行为的检测和/或分类来辅助对第二种人类行为的检测和/或分类。与其他单一行为检测技术相比，该方法提高了人类行为检测和/或分类的准确性和/或可靠性。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206127_1.jpg)

**Technical Field (技术领域)**:  
本专利属于健康监测技术领域，具体涉及利用主动声学传感进行人体行为检测和分类。

**Background (发明背景)**:  
随着医疗和健康技术的进步，人们越来越关注个人健康监测。然而，现有的一些健康监测设备可能存在侵入性强、不舒适或成本高等问题，影响了用户的接受度。例如，用于检测磨牙症的超声波传感器可能因使用不便而被用户放弃。此外，一些设备在检测不同类型的行为时能力有限，无法提供全面的健康反馈。

**Summary (发明总览)**:  
本发明提出了一种基于主动声学传感的耳戴设备（如耳机），能够进行相互依赖的人类行为检测和分类。该设备通过在用户耳道内传输和接收声学信号，识别声学回路的变化，从而检测和分类多种行为，如咀嚼、磨牙和睡眠等。通过第一种行为的检测结果辅助第二种行为的检测，本发明提高了检测的准确性和可靠性，并可使用单一传感器实现多种行为检测，降低了设备复杂度和成本。

**Key Innovation (核心创新)**:  
1. 利用主动声学传感技术，通过在用户耳道内传输和接收声学信号，识别声学回路的变化，实现对多种人类行为的检测和分类。
2. 采用相互依赖的行为检测方法，即利用对第一种行为的检测结果辅助对第二种行为的检测，从而提高检测的准确性和可靠性。
3. 通过单一类型的传感模式（如主动声学传感）和单一传感器实现多种行为检测，简化了设备结构，降低了成本和功耗。
4. 耳戴设备通过形成声学回路（如在耳道内形成密封），有效感知用户行为变化，无需依赖其他辅助传感器（如光学或电传感器）。
5. 该技术可应用于健康监测设备，如耳机，通过检测用户行为（如磨牙、睡眠质量）来提供个性化的健康反馈或设备控制功能。
6. 相比传统监测设备，本发明无需额外硬件支持，减少了设备体积、重量和成本，提升了用户体验。
7. 该技术可应用于日常健康监测场景，如监测磨牙症、睡眠质量等，为用户提供便捷、无干扰的健康数据收集方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206127)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260240489)**
<br/><br/>

---


<br/>

### 19. 通过级联大语言模型提供主动协助

**Title (EN)**: PROACTIVE ASSISTANCE VIA A CASCADE OF LLMS  
**Pub. No.**: US20260244856

**Applicant**: Google LLC  
**Inventor**: [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new), [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
一种提供主动协助的方法包括：数字助理获取与用户设备用户相关的上下文事件；使用在用户设备上执行的本地大语言模型（LLM）确定远程LLM提示置信度；确定远程LLM提示置信度满足阈值；基于此生成针对远程LLM的提示；将远程LLM提示传输至远程LLM；接收来自远程LLM的响应内容，该内容提供与上下文事件相关的主动协助；以及基于从远程LLM接收的响应内容，向用户设备输出展示内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485206696_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及人工智能领域，具体为通过级联大语言模型（LLM）实现智能助理的主动协助技术。

**Background (发明背景)**:  
大语言模型（LLM）越来越多地被用于提供用户与数字助理之间的对话体验。然而，现有技术中，数字助理的主动功能通常需要持续监控和响应事件，这对计算资源和隐私保护提出了挑战。传统方法依赖云端LLM处理所有事件，导致高昂的推理成本和潜在的隐私泄露风险。

**Summary (发明总览)**:  
本发明提出了一种通过本地和远程LLM级联协作实现智能助理主动协助的方法。系统首先利用本地LLM分析用户设备上的上下文事件，评估是否需要调用远程LLM进行进一步处理。只有在满足特定置信度阈值时，才会生成并发送远程LLM提示，从而减少不必要的远程调用，降低推理成本。同时，通过本地LLM对敏感信息进行预处理，增强用户隐私保护。本发明在保证主动协助效果的同时，显著降低了计算开销并提高了隐私安全性。

**Key Innovation (核心创新)**:  
1. 采用本地LLM进行初步事件分析，降低对远程LLM的调用频率，从而减少推理成本。
2. 通过本地LLM生成远程LLM提示，并基于置信度阈值决定是否触发远程LLM，实现智能调用。
3. 在生成远程LLM提示时，利用本地LLM对上下文事件进行总结或去标识化处理，保护用户隐私。
4. 支持对非文本数据进行文本转换处理，使LLM能够处理更广泛的上下文事件。
5. 允许对多个上下文事件进行批量处理，进一步优化远程LLM的调用效率。
6. 通过用户交互反馈（如用户同意）调整远程LLM提示的生成逻辑，提升用户体验。
7. 本专利可应用于智能助理、消息应用和物联网设备等场景，提供高效且隐私安全的主动协助功能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485206696)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244856)**
<br/><br/>

---


<br/>

### 20. 通过电子眼镜设备进行人体通信

**Title (EN)**: HUMAN BODY COMMUNICATION VIA ELECTRONIC EYEWEAR DEVICES  
**Pub. No.**: US20260244025

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Benjamin Cook](https://patents.google.com/?inventor=Benjamin+Cook&country=US&num=100&sort=new), [Jiang Zhu](https://patents.google.com/?inventor=Jiang+Zhu&country=US&num=100&sort=new), [Yasuo Morimoto](https://patents.google.com/?inventor=Yasuo+Morimoto&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明涉及一种设备，包括人体通信（HBC）控制器和与HBC控制器电连接的第一电极，该电极在用户佩戴设备时与用户的皮肤接触。设备还包括与HBC控制器电连接的第二电极。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485205780_1.jpg)

**Technical Field (技术领域)**:  
人体通信技术领域，具体涉及通过电子眼镜设备进行人体通信。

**Background (发明背景)**:  
人体通信（HBC）利用人体导电特性传输信号，实现数据交换。与蓝牙或Wi-Fi等传统无线通信方法不同，HBC以人体作为传输介质，提供安全、低功耗和短距离的连接。然而，HBC面临信号衰减、人体成分变化和环境因素影响传输质量等挑战。

**Summary (发明总览)**:  
本发明提出了一种通过电子眼镜设备进行人体通信的技术方案。通过在智能眼镜或增强现实眼镜的镜片中使用透明金属结构（如氧化铟锡或金属网格）作为人体通信的浮动地线，提升了通信链路预算。该技术利用镜片中的金属结构作为人体通信的浮动地线，优化了能量效率，并支持与手表或腕带等设备的两部分系统通信。

**Key Innovation (核心创新)**:  
1. 在智能眼镜或增强现实眼镜的镜片中使用透明金属结构（如氧化铟锡或金属网格）作为人体通信的浮动地线。
2. 利用镜片中的金属结构作为人体通信的浮动地线，提升通信链路预算并减少信号衰减。
3. 通过优化透明金属结构的设计，使其在玻璃前表面的金属表面积最大，从而增强人体通信效果。
4. 透明金属结构不仅用于人体通信，还可用于天线功能，实现多功能集成。
5. 该技术支持与手表或腕带等设备的两部分系统通信，提升了人体通信系统的整体效能。
6. 通过改进电极设计和信号处理技术，解决了人体成分变化对通信质量的影响。
7. 该技术可应用于医疗监测、生物识别和个人局域网等领域，提供更安全、高效的人体通信解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485205780)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260244025)**
<br/><br/>

---


<br/>

### 21. 从单张图像中提取多个概念

**Title (EN)**: Extracting Multiple Concepts from a Single Image  
**Pub. No.**: US20260245263

**Applicant**: Google LLC  
**Inventor**: [Omri Avrahami](https://patents.google.com/?inventor=Omri+Avrahami&country=US&num=100&sort=new), [Kfir Aberman](https://patents.google.com/?inventor=Kfir+Aberman&country=US&num=100&sort=new), [Daniel Cohen-Or](https://patents.google.com/?inventor=Daniel+Cohen-Or&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种系统和一种方法，用于执行文本场景分解任务：给定包含多个概念的单张场景图像，该技术能够为每个概念提取不同的文本标记，从而实现对生成场景的细粒度控制。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485207144_1.jpg)

**Technical Field (技术领域)**:  
机器学习领域，具体涉及文本场景分解和基于文本提示生成新图像的技术。

**Background (发明背景)**:  
人类能够轻松地将复杂场景分解为其组成部分，并在不同情境中重新想象这些部分。然而，现有的生成模型在执行此类分解和情境化任务时面临挑战。尽管已有一些尝试通过个性化大规模文本到图像模型来优化特定概念的生成，但这些方法主要依赖于多张图像来学习单一概念，难以适应不同场景。

**Summary (发明总览)**:  
本发明提出了一种从单张图像中提取多个视觉概念的方法。其核心思路是通过引入掩码来标识图像中的多个目标概念，并使用两阶段定制化过程优化文本嵌入和模型权重，以实现对概念的准确捕捉并避免过拟合。此外，本发明引入了联合采样策略，以提升生成图像中多概念组合的能力。

**Key Innovation (核心创新)**:  
1. 通过引入掩码技术，标识单张图像中多个目标概念的位置，从而实现对每个概念的独立提取。
2. 采用两阶段定制化过程，第一阶段优化文本嵌入（"句柄"），第二阶段微调模型权重，以在准确捕捉概念和避免过拟之间取得平衡。
3. 使用掩码扩散损失，使句柄能够生成其指定的概念，并通过交叉注意力图的损失防止概念之间的纠缠。
4. 引入联合采样训练策略，提升生成图像中多个概念组合的准确性和自然度。
5. 实现了从单张图像中提取多个文本标记的功能，使得用户可以通过文本提示生成包含单个或多个概念的新图像。
6. 该方法能够处理不同类型的概念，并支持用户自定义或自动生成掩码，适应性强。
7. 潜在应用场景包括图像编辑、虚拟场景生成和创意设计等领域，为用户提供更精细的图像生成控制。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485207144)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260245263)**
<br/><br/>

---


<br/>

### 22. 生成式语言模型

**Title (EN)**: GENERATIVE LANGUAGE MODELS  
**Pub. No.**: US20260245549

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Rahul Gupta](https://patents.google.com/?inventor=Rahul+Gupta&country=US&num=100&sort=new), [Charith Peris](https://patents.google.com/?inventor=Charith+Peris&country=US&num=100&sort=new), [Palash Goyal](https://patents.google.com/?inventor=Palash+Goyal&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本文描述了用于调节生成式语言模型响应的系统和相关技术。用户输入到生成式语言模型中可能包含偏见、错误信息以及其他需要调节的内容。为了防止生成式语言模型生成促进这些调节内容形式的响应，本技术确定与用户输入的调节内容类别相对应的策略。该策略可能对应于指导生成式语言模型如何响应此类调节内容的指令模板。生成式语言模型的输出在呈现给用户之前也可能被调节。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485207459_1.jpg)

**Technical Field (技术领域)**:  
人工智能，生成式语言模型，文本生成，偏见和错误信息过滤

**Background (发明背景)**:  
随着语音识别技术的发展，用户可以通过语音与计算设备进行交互。然而，生成式语言模型可能会生成包含偏见、错误信息或有害内容的响应。这些问题可能导致对特定群体的歧视或传播有害信息。现有的解决方案通常依赖于额外的模型训练或后处理，但这些方法可能无法实时有效地防止不当输出。

**Summary (发明总览)**:  
本发明提出了一种无需额外训练即可在推理时调节生成式语言模型输出的方法。通过识别用户输入中的调节内容并对其进行增强，系统可以生成更安全、中立和符合道德的响应。该方法利用机器学习模型检测用户输入中的潜在问题，并调整输入以引导语言模型生成更合适的输出。此外，系统还可以在输出中检测到调节内容时提供替代响应或警告。

**Key Innovation (核心创新)**:  
1. 通过检测用户输入中的调节内容（如偏见、错误信息或有害内容），系统能够识别需要调节的输入。
2. 利用增强技术修改用户输入，例如添加约束条件，以引导生成式语言模型生成更安全和中立的响应。
3. 系统集成了机器学习分类器，用于实时识别用户输入和模型输出中的调节内容。
4. 在检测到调节内容时，系统可以选择不展示原始输出，而是提供替代响应或错误提示。
5. 该方法无需对生成式语言模型进行额外训练即可实现调节功能，提高了系统的灵活性和实时性。
6. 系统可以配置用户权限，确保只有在用户授权的情况下才执行调节操作，符合隐私和数据保护法规。
7. 本发明可应用于虚拟助手、聊天机器人和内容审核系统等场景，有效减少偏见和错误信息的传播。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485207459)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260245549)**
<br/><br/>

---


<br/>

### 23. 用于光学组件相机校准的光学基准点

**Title (EN)**: LIGHT-BASED FIDUCIALS FOR CAMERA CALIBRATION WITH RESPECT TO AN OPTICAL COMPONENT  
**Pub. No.**: US20260246912

**Applicant**: GOOGLE LLC  
**Inventor**: [Zhiheng Jia](https://patents.google.com/?inventor=Zhiheng+Jia&country=US&num=100&sort=new), [Yi Qin](https://patents.google.com/?inventor=Yi+Qin&country=US&num=100&sort=new), [Scott Fullam](https://patents.google.com/?inventor=Scott+Fullam&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本文描述了用于光学组件相机校准的光学基准点。在一个实现中，成像系统包括用于对主体成像的图像传感器；位于图像传感器与主体之间的光学组件；在与图像传感器的视场相关联的区域内与光学组件集成的基准点集；以及处理器。基准点可在光学组件的折射平面中实现不连续性。处理器执行的过程包括接收来自图像传感器的图像；使用图像并基于通过不连续性的异常光传播，检测基准点集的配置；并基于该配置，执行校准操作以考虑光学组件对光的影响。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485208959_1.jpg)

**Technical Field (技术领域)**:  
光学成像技术领域，具体涉及光学组件与相机校准结合的技术。

**Background (发明背景)**:  
相机通过光学系统捕捉三维环境的光线并生成二维图像，但光学组件会影响光线路径，导致图像失真或偏差。
现有技术中，相机校准通常需要考虑光学组件的影响，但被动光学组件（如保护玻璃）难以精确校准。
这种校准不足可能导致成像质量下降或数据误差，特别是在动态环境中。

**Summary (发明总览)**:  
本发明提出了一种利用光学基准点进行相机校准的技术，通过在光学组件的折射平面中集成微小不连续性作为基准点。
这些基准点对人类视觉几乎不可见，但可通过相机捕捉并用于校准。
该技术通过分析图像帧并过滤动态内容，识别静态不连续性，从而实现对光学组件影响的精确补偿。
相较于传统方法，本发明无需额外硬件即可实现高精度校准，尤其适用于头戴式显示设备等复杂光学系统。

**Key Innovation (核心创新)**:  
1. 通过在光学组件的折射平面中集成微小不连续性作为基准点，实现对光学组件的精确校准。
2. 利用异常光传播特性，使基准点对人类视觉几乎不可见，同时保持对相机的可检测性。
3. 通过分析图像帧并过滤动态内容，识别静态不连续性，从而实现对光学组件影响的精确补偿。
4. 该技术无需额外硬件即可实现高精度校准，降低了校准成本和复杂性。
5. 特别适用于头戴式显示设备等复杂光学系统，能够有效补偿光学组件随时间变化的影响。
6. 基准点可放置在光学组件的任何位置，包括视场范围内，不会影响用户体验或图像质量。
7. 该技术可应用于增强现实、虚拟现实等扩展现实系统，提升成像精度和用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485208959)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260246912)**
<br/><br/>

---


<br/>

### 24. 具有降低串扰的印刷电路板硬件接口

**Title (EN)**: PRINTED CIRCUIT BOARD HARDWARE INTERFACE WITH REDUCED CROSSTALK  
**Pub. No.**: US20260247522

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Gong OUYANG](https://patents.google.com/?inventor=Gong+OUYANG&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
一种硬件接口包括印刷电路板（PCB），其包含多个PCB狗骨结构，用于电连接多个PCB过孔与对应的多个插座引脚。每个PCB狗骨结构包括相应的PCB、中介迹线和与相应插座引脚电连接的插座接口焊盘。多个PCB狗骨结构包括第一和第二PCB狗骨结构，分别包括第一和第二PCB过孔及插座接口焊盘。第一插座接口焊盘与第二插座接口焊盘相邻，第一PCB过孔与第二PCB过孔相邻。第一插座接口焊盘和第二插座接口焊盘沿第一方向排列，第一PCB过孔和第二PCB过孔沿与第一方向不同的第二方向排列。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485209634_1.jpg)

**Technical Field (技术领域)**:  
电子设备硬件接口技术，具体涉及印刷电路板（PCB）信号传输中的电磁串扰抑制技术。

**Background (发明背景)**:  
电子设备通常使用硬件接口将印刷电路板（PCB）与外部硬件芯片（如中央处理器CPU）连接，通过一系列电连接实现通信。然而，这些接口组件之间的电磁串扰会干扰信号传输，例如相邻插座引脚或PCB过孔之间的电磁干扰会累积并影响整体信号质量。现有技术未能有效解决这一问题，导致信号传输质量下降。

**Summary (发明总览)**:  
本发明提出了一种改进的硬件接口设计，通过优化PCB狗骨结构的排列来降低电磁串扰对信号传输的影响。具体来说，接口中的第一和第二PCB狗骨结构分别沿不同方向排列，使得相邻插座引脚之间的串扰与相邻PCB过孔之间的串扰极性相反，从而部分抵消串扰效应。此外，PCB过孔被分为信号过孔列和接地过孔列，接地过孔列提供电磁屏蔽以减少信号过孔列之间的干扰。这种设计提高了信号传输的信噪比（SNR）并降低了误码率（BER）。

**Key Innovation (核心创新)**:  
1. 采用PCB狗骨结构设计，通过中介迹线连接插座接口焊盘和PCB过孔，实现信号传输路径的优化。
2. 将第一和第二PCB狗骨结构的插座接口焊盘沿第一方向排列，其对应的PCB过孔沿第二方向排列，形成极性相反的串扰源，从而部分抵消电磁串扰。
3. 将PCB过孔分为信号过孔列和接地过孔列，接地过孔列提供电磁屏蔽，减少信号过孔列之间的干扰。
4. 通过在相邻接地过孔列之间的空间布线，减少导电迹线与信号过孔之间的串扰，提高信号传输质量。
5. 这种设计提高了信号传输的信噪比（SNR）和数据通信的可靠性，降低了误码率（BER）。
6. 适用于需要高密度信号传输的电子设备，如CPU与PCB之间的连接，能够有效提升通信稳定性。
7. 通过减少电磁串扰，该设计可应用于对信号完整性要求较高的场景，如高速数据传输和精密计算设备。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485209634)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260247522)**
<br/><br/>

---


<br/>

### 25. 基于距离的机器学习模型声音分离方法

**Title (EN)**: Distance based Sound Separation using Machine Learning Models  
**Pub. No.**: US20260245575

**Applicant**: Google LLC  
**Inventor**: [John Randall Hershey](https://patents.google.com/?inventor=John+Randall+Hershey&country=US&num=100&sort=new), [Scott Thomas Wisdom](https://patents.google.com/?inventor=Scott+Thomas+Wisdom&country=US&num=100&sort=new), [Hakan Erdogan](https://patents.google.com/?inventor=Hakan+Erdogan&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
本发明提供了一种基于距离的声音分离方法，包括接收由合成训练数据组成的音频混合信号。每个音频混合信号包含接近麦克风的第一个声音和不接近麦克风的第二个声音，训练数据由声学模拟器生成，以捕捉基于与麦克风距离变化的声学特性。该方法基于训练数据训练神经网络，以预测特定音频混合信号中接近麦克风的近声和不接近麦克风的远声。近声对应于接近特定麦克风的声音源，远声对应于不接近特定麦克风的声音源。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485207488_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及声音信号处理领域，具体为基于距离的声音分离技术。

**Background (发明背景)**:  
声音分离是从混合声音中提取特定声音子集的技术。在信号处理领域，如何在干扰下提取清晰语音是一个长期存在的问题。现有技术在使用神经网络进行声音分离时面临计算能力和内存限制的问题，且不同用户对增强或抑制的声音偏好不同。此外，基于方向的声音分离技术受限于麦克风阵列的物理尺寸，难以准确估计远距离声音源。

**Summary (发明总览)**:  
本发明提出了一种基于距离的声音分离方法，通过训练神经网络区分音频信号中的近声和远声。该方法利用声学模拟器生成的合成训练数据，捕捉声学特性随距离变化的规律。神经网络根据音频混合信号中的特定声学特性预测近声和远声，从而实现声音分离。与传统基于方向的声音分离技术相比，本发明不受麦克风阵列物理尺寸的限制，能够更准确地分离远距离声音源。

**Key Innovation (核心创新)**:  
1. 利用声学模拟器生成包含距离信息的合成训练数据，捕捉声学特性随距离变化的规律。
2. 训练神经网络以预测音频混合信号中的近声和远声，实现基于距离的声音分离。
3. 通过预测特定音频混合信号中的近声和远声，避免了传统方法对麦克风阵列物理尺寸的限制。
4. 神经网络能够根据音频信号中的特定声学特性进行预测，无需显式估计房间特性或混响参数。
5. 该方法可应用于单麦克风或多麦克风系统，提供更灵活的声音分离解决方案。
6. 适用于助听设备等应用场景，能够根据用户偏好选择性地增强或抑制特定声音源。
7. 通过预测物理和可解释的声学特性（如DRR），提供更准确的声音源距离估计和声音质量评估。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485207488)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260245575)**
<br/><br/>

---


<br/>

### 26. 电视显示的环境感知色调映射

**Title (EN)**: ENVIRONMENTALLY AWARE TONE MAPPING FOR A TELEVISION DISPLAY  
**Pub. No.**: US20260246898

**Applicant**: GOOGLE LLC  
**Inventor**: [Dongeek Shin](https://patents.google.com/?inventor=Dongeek+Shin&country=US&num=100&sort=new)  
**Publication Date**: 20.08.2026

**Abstract**:  
一种方法包括显示设备接收来自环境光测量设备的环境光测量数据，计算指示环境光测量设备之间测量距离的距离测量值，基于环境光测量数据和距离测量值生成光测量图，基于光测量图生成原始色调映射函数（使用空间感知图神经网络），将原始色调映射函数应用于媒体内容以生成媒体内容的色彩校正版本，并在显示设备的显示屏上显示色彩校正后的媒体内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485208943_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及电视显示技术，具体为基于环境光感知的智能色调映射技术。

**Background (发明背景)**:  
用户在不同的环境条件下观看电视时，观看体验会受到环境光的影响。在明亮或昏暗的房间中，相同的显示内容可能无法提供相同的观看体验。现有的电视显示技术难以根据环境光条件自动调整显示色调映射，导致用户观看体验不佳。

**Summary (发明总览)**:  
本发明提出了一种基于环境光感知的电视显示色调映射方法，通过接收环境光传感器数据并结合设备间的距离信息生成光测量图，利用空间感知图神经网络生成色调映射函数，并将其应用于媒体内容以实现色彩校正。该方法能够根据环境光条件自动调整电视显示效果，提升用户的沉浸式观看体验。

**Key Innovation (核心创新)**:  
1. 通过环境光传感器（如智能手机、智能手表等）收集环境光数据，并结合设备间的距离测量值生成光测量图，实现对环境光的精准感知。
2. 利用空间感知图神经网络处理光测量数据，生成原始色调映射函数，该网络能够根据空间位置关系对环境光数据进行智能推断。
3. 通过过滤不在同一房间内的环境光数据，确保色调映射函数仅基于用户所在房间的实际环境光条件进行计算。
4. 将生成的色调映射函数转换为缩放向量，提供给显示设备的渲染引擎，实现对媒体内容的实时色彩校正。
5. 采用超宽带室内定位或高精度距离测量技术计算设备间距离，提高环境光数据采集的准确性。
6. 该方法可应用于联网显示设备（如智能电视），并支持与移动计算设备（如智能手机）协同工作，实现更灵活的应用场景。
7. 通过自动调整显示色调映射，本发明能够根据环境光条件优化用户观看体验，特别适用于昏暗环境下的电影观看或明亮环境下的日常使用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485208943)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260246898)**
<br/><br/>

---


<br/>

### 27. 用于消除手写笔输入延迟的系统

**Title (EN)**: System for stylus input latency compensation  
**Pub. No.**: US12710845

**Applicant**: AMAZON TECHNOLOGIES, INC.  
**Inventor**: [Shuang Gao](https://patents.google.com/?inventor=Shuang+Gao&country=US&num=100&sort=new), [Jim Oommen Thomas](https://patents.google.com/?inventor=Jim+Oommen+Thomas&country=US&num=100&sort=new), [Jingyi Zhang](https://patents.google.com/?inventor=Jingyi+Zhang&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
一种手写笔通过触摸屏提供输入，触摸屏包括触摸传感器和显示器。通过确定手写笔尖在书写过程中的预测路径，减少或消除手写笔尖放置与显示器上呈现视觉指示之间的延迟。基于预测路径在显示器上呈现视觉指示。触摸传感器的输入可能包括手写笔尖未接触触摸屏时的悬停事件和手写笔尖接触触摸屏时的触摸事件。可以训练机器学习网络以确定预测路径。网络的一部分可以训练为接受动态长度的事件序列并生成固定长度的序列，从而降低后续网络的复杂性。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485063535_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及触摸屏输入延迟补偿技术。

**Background (发明背景)**:  
触摸屏设备在用户通过触摸传感器输入和显示器呈现之间存在延迟问题。这种延迟会影响用户体验，特别是在需要高精度输入的场景中，如手写笔绘图或书写。现有的解决方案难以有效减少延迟，且难以适应不同用户的输入习惯和速度。本发明旨在解决手写笔输入延迟问题，提高输入响应速度和准确性。

**Summary (发明总览)**:  
本发明通过预测手写笔尖的运动路径来减少触摸屏输入延迟。系统利用触摸传感器提供的手写笔位置数据，结合机器学习算法预测笔尖的未来位置，并基于预测结果提前在显示器上呈现视觉指示。该方法通过动态处理输入事件序列并生成固定长度的输出序列，简化了后续处理流程。与传统方法相比，本发明能够更快速、准确地响应用户输入，提升了人机交互的流畅性。

**Key Innovation (核心创新)**:  
1. 通过预测手写笔尖的运动路径，提前在显示器上呈现视觉指示，从而减少输入延迟。
2. 利用机器学习网络训练预测模型，动态处理不同长度的事件序列，提高预测精度。
3. 将输入事件序列转换为固定长度的输出序列，简化后续处理流程，降低系统复杂性。
4. 结合触摸传感器提供的悬停和接触事件数据，实现更全面的输入检测和预测。
5. 通过训练网络适应不同用户的输入习惯和速度，提供个性化的延迟补偿方案。
6. 该技术可应用于高精度要求的触摸屏设备，如绘图板、签名终端等，提升用户体验。
7. 预测路径的实时性和准确性使得手写笔输入更加流畅自然，接近真实书写体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485063535)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12710845)**
<br/><br/>

---


<br/>

### 28. 用于轨道穿梭车的电磁开关

**Title (EN)**: Electromagnet switch for shuttles on a track  
**Pub. No.**: US12709476

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Michael D Assadi](https://patents.google.com/?inventor=Michael+D+Assadi&country=US&num=100&sort=new), [Zechariah Ives](https://patents.google.com/?inventor=Zechariah+Ives&country=US&num=100&sort=new), [Sudhakar Teegavarapu](https://patents.google.com/?inventor=Sudhakar+Teegavarapu&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
本发明公开了一种用于在履行中心内将带有货物的穿梭车从一个位置运输到另一个位置的轨道系统。该轨道系统可包括线性同步电机（LSM）以推动穿梭车沿预定路径行进。轨道系统可包括多条轨道路径、磁组件和用于将穿梭车转向替代路径的电磁铁。为了使穿梭车从一个轨道路径移动到另一个轨道路径，可在路径的交叉处设置电磁铁和磁组件。当电磁铁通电时，其磁场可吸引穿梭车至所需路径（例如，弯曲路径），而磁组件可使穿梭车沿所需路径行进。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485062019_1.jpg)

**Technical Field (技术领域)**:  
物流自动化技术领域，具体涉及用于履行中心的穿梭车轨道运输与转向系统。

**Background (发明背景)**:  
随着在线购物的普及，履行中心的订单处理和包裹运输需求显著增加。现有固定路径的运输和分拣系统难以快速改变路径，导致操作效率低下和瓶颈问题。因此，需要改进订单履行中的运输和分拣技术，以提高物流效率。

**Summary (发明总览)**:  
本发明提出了一种基于电磁控制的轨道穿梭车转向系统，通过在轨道交叉点设置电磁铁和磁组件，实现穿梭车的灵活转向。该系统利用线性同步电机驱动穿梭车，并结合电磁转向机制，使穿梭车能够快速切换路径，从而提高履行中心的物流效率。本发明相较于传统固定路径系统，提供了更高的灵活性和适应性。

**Key Innovation (核心创新)**:  
1. 采用线性同步电机（LSM）作为穿梭车的主要驱动装置，确保高效、精确的直线运动控制。
2. 在轨道交叉点设置电磁铁和磁组件，通过电磁力引导穿梭车转向，实现灵活路径切换。
3. 电磁铁的通电控制与穿梭车的运动状态同步，确保转向过程的平稳性和可靠性。
4. 磁组件设计用于在电磁铁吸引穿梭车后，维持其沿新路径的稳定行进，避免偏离。
5. 该系统可应用于高密度、多路径的履行中心环境，通过快速路径切换提高物流处理效率。
6. 相比传统固定路径系统，本发明显著减少了因路径变更导致的操作延迟和瓶颈问题。
7. 适用于大规模、高吞吐量的物流场景，如电商履行中心，可提升整体运营效率和货物处理能力。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485062019)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12709476)**
<br/><br/>

---


<br/>

### 29. 多应用上的选择性呼叫通知

**Title (EN)**: Selective call notifications on multiple applications  
**Pub. No.**: US12712965

**Applicant**: Meta Platforms, Inc.  
**Inventor**: [Jennifer Marie Shott](https://patents.google.com/?inventor=Jennifer+Marie+Shott&country=US&num=100&sort=new), [Pradeep George Mathias](https://patents.google.com/?inventor=Pradeep+George+Mathias&country=US&num=100&sort=new), [Qi Chen](https://patents.google.com/?inventor=Qi+Chen&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
本发明涉及一种系统、方法和非易失性计算机可读介质，用于接收传入呼叫，选择用户计算设备上安装的具有呼叫功能的多个应用之一来提供传入呼叫或未接呼叫的通知，并使所选应用提供相应的通知。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485065878_1.jpg)

**Technical Field (技术领域)**:  
数字通信领域，具体涉及多应用呼叫通知的选择性提供技术。

**Background (发明背景)**:  
随着计算设备的多样化，用户通过不同应用进行通信的需求日益增加。然而，现有技术无法智能地选择合适的应用来通知用户呼叫或未接呼叫，导致用户体验不佳。本发明旨在解决这一问题，通过智能选择应用来提供呼叫通知。

**Summary (发明总览)**:  
本发明提出了一种智能选择应用来提供呼叫通知的方法。通过分析用户偏好、活跃应用、应用权限等因素，系统能够选择最合适的应用来通知用户传入呼叫或未接呼叫。这种方法不仅提高了通知的准确性和及时性，还优化了用户的通信体验。

**Key Innovation (核心创新)**:  
1. 通过分析用户是否指定了首选应用，选择相应的应用来提供呼叫通知。
2. 在用户仅安装了一个或两个具有呼叫功能的应用时，自动选择已安装的应用进行通知。
3. 检测用户当前活跃的应用，并优先在该应用上提供呼叫通知。
4. 如果用户未指定首选应用且未在特定应用中活跃，系统会选择通过呼叫发起方的应用来提供通知。
5. 根据应用对摄像头或麦克风的权限，以及应用的近期使用频率，选择合适的应用进行通知。
6. 确保所选应用与呼叫发起方的应用使用场景一致，以提供更符合用户习惯的通知方式。
7. 本发明可应用于即时通讯、社交网络等多种通信场景，提升多应用环境下呼叫通知的智能化和用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485065878)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12712965)**
<br/><br/>

---


<br/>

### 30. 多智能助手的人工智能通知管理

**Title (EN)**: Notification management for multi-assistant artificial intelligence  
**Pub. No.**: US12711941

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Mayank Mahajan](https://patents.google.com/?inventor=Mayank+Mahajan&country=US&num=100&sort=new), [Daniel Yim](https://patents.google.com/?inventor=Daniel+Yim&country=US&num=100&sort=new), [Anurag Kartikeya Akkiraju](https://patents.google.com/?inventor=Anurag+Kartikeya+Akkiraju&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
一种语音处理系统可以通过用户设备访问多个虚拟助手。用户可以通过说出唤醒词来调用特定的虚拟助手。虚拟助手可以通过用户设备向用户发送通知，用户设备会显示可用通知的指示。用户可以使用例如语音用户界面请求通知的传递。在传递来自多个虚拟助手的通知时，系统可以使用不同的声音和/或视觉特征来指示通知的来源。例如，在传递与第一个虚拟助手对应的第一个通知后，第一个虚拟助手可以提供传递第二个通知的选项。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485064743_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术；多智能助手系统；人机交互

**Background (发明背景)**:  
语音识别技术已经发展到人类可以通过语音与计算设备进行交互的程度。现有的语音处理系统能够识别用户的语音命令并执行相应任务。然而，当多个虚拟助手共存时，如何有效管理和区分来自不同助手的通知成为一个问题。现有的系统缺乏对多助手通知来源的清晰标识，可能导致用户混淆。

**Summary (发明总览)**:  
本发明提出了一种多智能助手通知管理系统，通过语音和视觉特征区分不同助手的通知来源。用户可以通过语音命令请求通知的传递，系统会使用不同的声音或视觉提示来标识通知的来源。这种方法不仅提高了用户对通知来源的识别效率，还增强了多助手系统的人机交互体验。

**Key Innovation (核心创新)**:  
1. 通过语音和视觉特征区分不同虚拟助手的通知来源，使用户能够快速识别通知的来源。
2. 系统在传递通知时采用不同的声音特征，例如不同的语音语调或声音风格，以标识不同的虚拟助手。
3. 使用视觉提示，例如不同的颜色、图标或界面布局，来进一步区分来自不同助手的通知。
4. 用户可以通过语音命令请求通知的传递，系统会根据用户的指令选择合适的虚拟助手进行响应。
5. 在多助手交互过程中，系统会记录用户的操作历史，并根据历史记录优化通知的传递顺序和方式。
6. 该系统可以应用于智能家居、智能手机和车载系统等多种场景，提供更智能和个性化的通知管理服务。
7. 通过区分通知来源，本发明解决了多助手系统中的通知混淆问题，提升了用户的交互体验和操作效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485064743)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12711941)**
<br/><br/>

---


<br/>

### 31. 热感触摸界面

**Title (EN)**: Heat-sensing touch interface  
**Pub. No.**: US12710847

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Anatoly Tsvetov](https://patents.google.com/?inventor=Anatoly+Tsvetov&country=US&num=100&sort=new), [Roei Shlomo Menashof](https://patents.google.com/?inventor=Roei+Shlomo+Menashof&country=US&num=100&sort=new), [Oren Istrin](https://patents.google.com/?inventor=Oren+Istrin&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
本发明公开了一种热感触摸界面，通过对触摸数据的温度特征进行剖析以识别用户输入。温度特征分析提高了触摸精度，使用户与触摸设备的交互更加自然。当与手掌触摸点相关的热数据超出手指触摸的温度范围时，可将手掌触摸分类为非用户输入；当与水分触摸点相关的热数据低于手指触摸的温度范围时，可将水分触摸分类为非用户输入。用户输入的温度范围可以动态调整。通过基于触摸数据的检测来激活或采样热传感器阵列，从而节省能源。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485063537_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及热感触摸界面和触摸输入识别技术。

**Background (发明背景)**:  
触摸输入设备（如触摸屏和触摸板）在计算设备中广泛使用，但现有技术难以区分用户输入和非用户输入，例如手掌或水分造成的误触。这导致触摸识别的准确性和用户体验受到限制。现有系统缺乏对温度特征的利用，无法有效过滤非用户输入。

**Summary (发明总览)**:  
本发明提出了一种基于温度特征分析的热感触摸界面，通过对触摸数据进行温度剖析来区分用户输入和非用户输入。该系统允许用户自定义触摸和温度配置文件，并可根据触摸输入和检测到的屏幕及环境温度动态调整温度范围阈值。通过热数据过滤触摸数据，系统能够有效排除非用户输入，从而提高触摸精度并实现更自然的用户交互。

**Key Innovation (核心创新)**:  
1. 利用热传感器阵列采集触摸点的温度数据，通过温度特征分析提高触摸输入识别的准确性。
2. 实现了用户自定义的触摸和温度配置文件，支持根据用户需求和应用场景（如文字处理、游戏）进行个性化设置。
3. 动态调整温度范围阈值，根据实时触摸输入和检测到的屏幕及环境温度进行自适应优化。
4. 通过热数据过滤非用户输入，例如区分手掌触摸和手指触摸，以及识别水分造成的误触。
5. 采用基于触摸数据检测的传感器激活机制，仅在必要时激活热传感器阵列，从而降低能耗。
6. 该技术可应用于触摸屏和触摸板等设备，提升用户交互的自然性和设备的智能化水平。
7. 特别适用于需要高精度触摸识别的场景，如无键盘输入设备或对误触敏感的应用环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485063537)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12710847)**
<br/><br/>

---


<br/>

### 32. 使用计算机视觉和地理定位数据强制执行成像设备的虚拟限制使用区域的技术

**Title (EN)**: Techniques for using computer vision and geolocation data to enforce virtual restricted-use zones for imaging devices  
**Pub. No.**: US12711711

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jared Zimmerman](https://patents.google.com/?inventor=Jared+Zimmerman&country=US&num=100&sort=new), [Tae Wan An](https://patents.google.com/?inventor=Tae+Wan+An&country=US&num=100&sort=new)  
**Publication Date**: 18.08.2026

**Abstract**:  
本发明提供了一种用于强制执行与头戴式设备通信耦合的成像设备的虚拟限制使用区域的方法和系统。该方法包括基于物理区域中存在的一个或多个限制使用区域标记来识别虚拟限制使用区域，并利用该虚拟限制使用区域来强制执行对物理区域内成像设备使用的限制。成像设备与头戴式设备通信耦合。该方法进一步包括，在确定成像设备位于虚拟限制使用区域内时，自动且无需人工干预地禁用与头戴式设备通信耦合的成像设备。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485064491_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及头戴式设备技术领域，具体涉及通过计算机视觉和地理定位数据强制执行成像设备虚拟限制使用区域的技术。

**Background (发明背景)**:  
随着人工智能现实系统（如头戴式设备）的普及，用户信任成为关键问题。这些设备通常配备成像设备（如摄像头）和/或麦克风，能够在敏感和私人场所捕获图像和/或音频数据。缺乏对数据捕获的限制可能导致用户不信任，而过多的限制则可能影响用户体验。因此，需要一种既能保护他人隐私，又能让用户自由使用成像设备的方法。

**Summary (发明总览)**:  
本发明通过头戴式设备、手腕佩戴设备或与这些设备通信耦合的中介设备来检测一个或多个虚拟限制使用区域的存在。这些区域包括警告区和执行区。在警告区内，系统会通知用户即将进入执行区；在执行区内，系统会自动禁用成像设备以防止捕获图像数据。该方法通过自动禁用成像设备来保护用户及周围人员的隐私，防止对受保护财产、特殊事件或受保护地点的捕获，从而在虚拟限制使用区域内提供改进的隐私保护技术。

**Key Innovation (核心创新)**:  
1. 通过检测物理区域中的限制使用区域标记来识别虚拟限制使用区域，实现对成像设备使用的精确控制。
2. 引入警告区和执行区的概念，在用户接近限制区域时提供通知，并在进入执行区时自动禁用成像设备。
3. 利用头戴式设备、手腕佩戴设备或中介设备的位置定位功能，实时确定成像设备是否位于虚拟限制使用区域内。
4. 通过自动禁用成像设备，无需人工干预即可有效防止在限制区域内捕获图像数据。
5. 除了成像设备，本发明还支持禁用与头戴式设备通信耦合的其他设备（如麦克风），进一步增强隐私保护。
6. 该技术适用于博物馆、电影院、私人财产等场景，能够防止对受保护财产的未经授权的捕获。
7. 通过平衡用户自由和隐私保护，本发明为头戴式设备用户提供了更安全、更可靠的使用体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485064491)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12711711)**
<br/><br/>

---



**Total Patents**: 32  
**Last Updated**: 20260823

---

The Patent Scoop Trio
