---
layout: post
title: "其他专利小快报 2026-08-08"
date: 2026-08-08 19:02:16 +0800
categories: 其他
---

**New Patents**: 35  

---


<br/>

### 1. 设备状态感知的动态自动语音识别优化

**Title (EN)**: Device State Aware Dynamic Automatic Speech Recognition Optimization  
**Pub. No.**: US20260229216

**Applicant**: Google LLC  
**Inventor**: [Pu-sen Chao](https://patents.google.com/?inventor=Pu-sen+Chao&country=US&num=100&sort=new), [Petar Stanisa Aleksic](https://patents.google.com/?inventor=Petar+Stanisa+Aleksic&country=US&num=100&sort=new), [Meysam Bastani](https://patents.google.com/?inventor=Meysam+Bastani&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明提供了一种方法，包括接收指示用户设备的第一段文本转语音（TTS）音频播放结束的事件（TTS结束事件）。基于接收到的TTS结束事件，该方法还指示自动语音识别（ASR）系统使用第一级别的ASR处理来进行语音识别。当用户提出自然语言查询以请求大语言模型（LLM）驱动的助手生成第二段响应时，该方法包括由ASR系统使用第一级别的ASR处理对音频数据进行语音识别，以生成语音识别结果，并由LLM驱动的助手处理该语音识别结果以生成第二段响应。基于接收到的指示第二段TTS音频即将从用户设备播放的事件（TTS开始事件），该方法进一步指示ASR系统使用第二级别的ASR处理来对用户设备播放第二段TTS音频期间由麦克风捕获的任何用户语音进行语音识别，其中第二级别的ASR处理与第一级别不同。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426932_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术领域，具体涉及设备状态感知的动态自动语音识别优化。

**Background (发明背景)**:  
自动语音识别（ASR）系统是当前广泛使用的技术。现代ASR系统不仅追求高质量（如低词错误率），还追求低延迟（如用户说话与转录或响应出现之间的短延迟）。然而，现有ASR系统在会话期间通常采用静态优化策略，无法根据设备状态动态调整处理级别。这可能导致在TTS播放期间错误地截断用户语音或对噪声过于敏感，影响识别准确性。

**Summary (发明总览)**:  
本发明提出了一种动态调整ASR处理级别的方案，通过感知设备状态来优化语音识别性能。在TTS播放结束后，系统采用高敏感度的ASR处理以捕捉用户语音，而在TTS播放期间则切换到低敏感度的ASR处理以减少干扰。该方法通过分析对话历史和上下文来调整识别策略，并针对预期用户查询进行优化，从而在保证识别准确性的同时提高系统效率。

**Key Innovation (核心创新)**:  
1. 通过接收TTS结束事件和开始事件，动态调整ASR处理级别，在TTS播放结束后采用高敏感度处理，在TTS播放期间采用低敏感度处理。
2. 利用LLM驱动的助手生成的对话历史和上下文，指导ASR系统偏向于与当前上下文相关的特定词汇，提高识别准确性。
3. 在预期用户将提出简短后续查询的情况下，优化ASR系统以优先识别这些查询，提升用户体验。
4. 通过端点检测模型分析音频数据中的静音时长，确保在满足结束话语（EOU）时长阈值后，才开始处理语音识别结果，避免过早截断用户语音。
5. 在接收到后续音频数据时，延长EOU时长阈值，以适应更长的用户话语，提高识别的完整性和准确性。
6. 该方法可应用于智能助手、语音搜索和长篇语音转录等场景，通过动态调整ASR处理级别，在不同设备状态下提供更精准的语音识别服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426932)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229216)**
<br/><br/>

---


<br/>

### 2. 用于显示设备的动态色彩吸收控制技术

**Title (EN)**: TECHNIQUES FOR DYNAMIC CONTROL OF COLOR ABSORPTION FOR DISPLAY DEVICES  
**Pub. No.**: US20260229157

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Phillip NELSEN](https://patents.google.com/?inventor=Phillip+NELSEN&country=US&num=100&sort=new), [Poon Yarn Chee](https://patents.google.com/?inventor=Poon+Yarn+Chee&country=US&num=100&sort=new), [Seungwoo Lee](https://patents.google.com/?inventor=Seungwoo+Lee&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明描述了用于控制显示设备的色适应膜的示例。通过接收色适应膜需要吸收的一种或多种颜色的指示，可以修改色适应膜中多个色彩吸收层中一个或多个层的透光率。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426868_1.jpg)

**Technical Field (技术领域)**:  
显示技术领域，具体涉及色适应膜的色彩吸收控制。

**Background (发明背景)**:  
混合现实设备需要平衡环境光透射和图像显示效果，但现有技术存在功耗问题。
传统单层光透射控制方法难以实现低透光率控制，影响显示效果。
在强光环境下，增加亮度或背光会显著增加功耗，影响设备续航。

**Summary (发明总览)**:  
本发明提出了一种基于多层色适应膜的色彩吸收动态控制方案。
通过独立控制多个色彩吸收层，实现对不同颜色光线的选择性吸收。
该方案能够降低显示设备的光透射率，提升图像对比度并减少功耗。
相较于传统单层方案，本发明在色彩控制和光管理方面具有显著优势。

**Key Innovation (核心创新)**:  
1. 采用多层独立控制的色适应膜结构，每层针对特定颜色（如红、绿、蓝）进行选择性吸收。
2. 通过向各层发送功率控制信号，实现对色彩吸收量的精确调控，每层使用介电液晶材料配合吸光染料。
3. 能够根据显示内容、环境光条件或预设参数，动态调整色彩吸收水平，优化显示效果。
4. 通过独立控制各颜色光线的透射率，实现更低的光透射率，提升图像对比度。
5. 在不增加显示设备亮度的情况下，通过吸收特定环境光来改善图像可见性和对比度，从而降低功耗。
6. 减少显示设备在显示高亮度图像时的色彩透射泄漏现象。
7. 可应用于头戴式显示设备（如HUD）的可拆卸遮阳板，通过调整进入视野的光线颜色来增强物体对比度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426868)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229157)**
<br/><br/>

---


<br/>

### 3. 用于泄漏缓解的吸收垫

**Title (EN)**: ABSORBENT PAD FOR LEAK MITIGATION  
**Pub. No.**: US20260225000

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Rick Chun Kit CHEUNG](https://patents.google.com/?inventor=Rick+Chun+Kit+CHEUNG&country=US&num=100&sort=new), [Luke Thomas GREGORY](https://patents.google.com/?inventor=Luke+Thomas+GREGORY&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种用于液体冷却计算设备的泄漏缓解系统包括一个连接有吸收材料的流体传感器。吸收垫放置在与液体冷却计算设备相关的位置，以收集来自冷却系统的液体。传感器检测吸收材料吸收的液体的存在，泄漏缓解系统实施泄漏缓解协议以防止或减少对计算设备的损坏。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484422279_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及液体冷却计算系统的泄漏检测与缓解技术，具体为一种带有流体传感器的吸收垫。

**Background (发明背景)**:  
随着计算设备处理能力提升和尺寸减小，其热生成元件的热密度增加。现代计算系统采用液体冷却系统来散热，但液体冷却系统可能发生泄漏，损坏处理器和其他组件。现有的冷却系统缺乏有效的泄漏检测和缓解机制。

**Summary (发明总览)**:  
本发明提出了一种带有流体传感器的吸收垫，用于液体冷却计算系统的泄漏检测与缓解。该吸收垫通过吸收泄漏液体并利用传感器检测液体存在来识别泄漏。系统根据检测结果实施缓解措施，如关闭冷却系统阀门或发出警报，从而减少对计算设备的损害。相较于现有技术，本发明提供了更早的泄漏检测和更有效的泄漏吸收能力。

**Key Innovation (核心创新)**:  
1. 采用带有流体传感器的吸收垫设计，实时检测冷却系统泄漏并吸收泄漏液体。
2. 传感器可测量泄漏的位置、数量、速率、液体类型等参数，为缓解措施提供精确数据支持。
3. 系统能够区分冷凝水和冷却液，并针对不同情况实施不同的缓解协议，提高检测准确性。
4. 具备持续监测功能，可定期或按需请求传感器数据，实现对数据中心泄漏的持续监控。
5. 在检测到泄漏后，系统可自动关闭冷却泵或阀门，切断泄漏源，防止进一步损坏。
6. 该技术可应用于服务器、机架或数据中心等场景，为液体冷却系统提供可靠的泄漏防护。
7. 通过早期检测和快速响应，降低因冷却液泄漏导致的设备损坏风险，提高数据中心运行安全性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484422279)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260225000)**
<br/><br/>

---


<br/>

### 4. 基于机器学习的音频编辑模型

**Title (EN)**: Machine-Learned Audio Editing Model  
**Pub. No.**: US20260229255

**Applicant**: Google LLC  
**Inventor**: [Ron Weiss](https://patents.google.com/?inventor=Ron+Weiss&country=US&num=100&sort=new), [Eduardo David Fonseca Montero](https://patents.google.com/?inventor=Eduardo+David+Fonseca+Montero&country=US&num=100&sort=new), [Dan Ellis](https://patents.google.com/?inventor=Dan+Ellis&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明提供了一种利用机器学习进行音频编辑的系统和方法，以提高编辑的精确性和灵活性。一些示例系统使用基于向量的音频编辑表示来调节和控制机器学习的音频编辑模型。这种方法通过将编辑操作进行数值编码并使用训练好的模型进行处理，从而实现对音频编辑的详细和精确控制。该系统能够处理多种编辑操作，包括音频生成、删除、转换、时间偏移和/或增强，从而为音频处理提供了一套全面的工具。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426975_1.jpg)

**Technical Field (技术领域)**:  
人工智能，机器学习，音频处理技术
基于向量的音频编辑表示
音频编辑自动化

**Background (发明背景)**:  
传统的音频编辑工具通常需要手动操作来完成插入新声音、去除噪声、转换音频属性或时间偏移等任务。这种手动过程耗时、易出错，并且需要高水平的专业知识来确保精确性。此外，现有系统通常无法处理复杂的音频编辑任务，例如将音频与视觉元素同步或在不破坏整体音频完整性的情况下动态调整密集混音中的特定音频元素。现有的音频编辑系统也常常不支持基于高级建模技术的实时反馈或迭代改进，限制了编辑人员高效试验不同编辑的能力。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的音频编辑方法，通过使用基于向量的音频编辑表示来精确控制音频编辑操作。该方法将编辑操作编码为数值向量，并使用训练好的机器学习模型进行处理，从而实现对音频生成、删除、转换、时间偏移和增强等操作的自动化处理。与传统方法相比，本发明通过交互式事件滚动可视化界面和自由文本输入等方式，提供了更直观和精确的编辑控制方式。

**Key Innovation (核心创新)**:  
1. 采用基于向量的音频编辑表示，将编辑操作编码为数值向量，实现对音频编辑的精确控制。
2. 使用交互式事件滚动可视化界面，用户可以直接在图形界面上插入、删除或修改音频事件，简化编辑操作。
3. 支持自由形式的文本输入，将文本描述转换为文本嵌入并整合到向量表示中，提供丰富的语义信息。
4. 通过机器学习模型处理输入音频数据和向量编辑表示，实现音频生成、删除、转换、时间偏移和增强等多种编辑操作。
5. 引入差分事件滚动机制，仅记录用户编辑前后的差异，进一步提高处理效率和精度。
6. 该技术可应用于音频制作、语音编辑和多媒体内容创作等领域，为复杂音频处理任务提供高效解决方案。
7. 通过实时反馈和迭代改进机制，编辑人员可以更高效地试验不同编辑效果，提升创作体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426975)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229255)**
<br/><br/>

---


<br/>

### 5. 计算设备组件电池充电

**Title (EN)**: COMPUTING DEVICE COMPONENT BATTERY CHARGING  
**Pub. No.**: US20260229911

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Gregory Allen NIELSEN](https://patents.google.com/?inventor=Gregory+Allen+NIELSEN&country=US&num=100&sort=new), [Donghwi KIM](https://patents.google.com/?inventor=Donghwi+KIM&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种移动计算设备被配置为对组件电池进行充电。该移动计算设备包括电源单元、计算设备电池、处理器以及存储有可由处理器执行的指令的存储器，用于控制从电源单元或计算设备电池对组件电池的充电速率，该控制至少部分基于提供给处理器的节流功率的大小。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484427699_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及移动计算设备领域，具体涉及对可拆卸组件或辅助电池的智能充电控制技术。

**Background (发明背景)**:  
现代电子设备如笔记本电脑和平板电脑常与可充电外部组件（如手写笔或键盘）一起使用。此外，一些设备除了主电池外还包含辅助电池。现有的充电方法可能会影响计算设备的性能。本发明旨在解决在充电过程中如何平衡组件电池充电与计算设备性能的问题。

**Summary (发明总览)**:  
本发明提出了一种智能充电控制方案，通过监测提供给处理器的节流功率大小来调节组件电池的充电速率。该方案确保在充电过程中不影响计算设备的性能。此外，本发明还利用组件电池的电量状态，在电量达到一定阈值时切换到可再生能源进行充电，从而优化计算设备资源分配并维持组件的正常工作。

**Key Innovation (核心创新)**:  
1. 通过监测处理器节流功率大小来动态调整组件电池的充电速率，确保充电过程不会对处理器性能产生负面影响。
2. 利用组件电池的电量状态，在电量高于预设阈值时自动切换到可再生能源进行充电，从而减少对计算设备主电源的依赖。
3. 实现了对可拆卸组件（如电子笔或键盘）和辅助电池的智能充电管理，优化了充电效率并提升了用户体验。
4. 通过智能切换充电源（主电源、计算设备电池或可再生能源），在保证组件正常工作的同时，最大限度地释放计算设备的性能潜力。
5. 提供了基于电量状态和处理器节流状态的综合充电控制策略，实现了充电效率与设备性能的平衡。
6. 该技术可应用于配备可拆卸组件或辅助电池的移动计算设备，如笔记本电脑、平板电脑等，提升了设备的整体续航能力和使用灵活性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484427699)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229911)**
<br/><br/>

---


<br/>

### 6. 使用循环神经网络实现机器人末端执行器的视角不变视觉伺服的方案

**Title (EN)**: VIEWPOINT INVARIANT VISUAL SERVOING OF ROBOT END EFFECTOR USING RECURRENT NEURAL NETWORK  
**Pub. No.**: US20260225237

**Applicant**: GOOGLE LLC  
**Inventor**: [Alexander Toshev](https://patents.google.com/?inventor=Alexander+Toshev&country=US&num=100&sort=new), [Fereshteh Sadeghi](https://patents.google.com/?inventor=Fereshteh+Sadeghi&country=US&num=100&sort=new), [Sergey Levine](https://patents.google.com/?inventor=Sergey+Levine&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明涉及训练和使用循环神经网络模型以实现机器人末端执行器的视觉伺服的方案。在视觉伺服的场景中，该模型可用于在多个时间步骤中生成动作预测，以预测末端执行器应如何移动以朝向目标物体。该模型具有视角不变性，可用于具有不同视角的多种机器人视觉组件，或在机器人视觉组件视角发生剧烈变化时仍能使用。此外，该模型可基于大量模拟数据训练，这些数据基于模拟器执行模拟情节并根据模型生成。通过模拟器生成的数据可以提高模型对不同视角和场景的适应性和准确性。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484422540_1.jpg)

**Technical Field (技术领域)**:  
机器人技术领域，具体涉及机器人视觉伺服的循环神经网络应用

**Background (发明背景)**:  
机器人通常使用末端执行器执行抓取等操作任务。现有的基于机器学习的视觉伺服从输入图像生成预测，但当视角变化较大时表现不佳。此外，现有方法主要依赖真实机器人数据训练模型，这需要大量机器人操作时间和资源，并可能导致设备磨损和需要人工干预。

**Summary (发明总览)**:  
本发明提出了一种基于循环神经网络的机器人视觉伺服的训练和使用方法。该方法利用循环神经网络在多个时间步骤中生成动作预测，以指导末端执行器朝向目标物体移动。通过使用模拟数据训练模型，并结合强化学习技术，模型能够适应不同的视角和场景。此外，模型还可通过真实数据进一步微调，以提高在实际机器人上的性能。

**Key Innovation (核心创新)**:  
1. 采用循环神经网络架构，通过记忆单元（如LSTM或GRU）实现对历史动作和场景图像的记忆，从而在多时间步骤中持续调整动作预测。
2. 使用模拟数据训练模型，通过模拟器生成多视角和多场景的训练数据，提高模型对不同视角和场景的适应性和准确性。
3. 在训练过程中引入强化学习，通过比较动作预测方向与目标物体的真实方向来计算奖励，从而优化模型性能。
4. 利用模拟器生成的动作演示数据加速策略学习，通过扰动最优方向来增强模型的鲁棒性。
5. 通过真实数据对模型的可视部分进行微调，使用手动标注的真实场景图像作为训练输入，以提高模型在实际应用中的准确性。
6. 模型的可视部分可独立于动作部分和政策部分进行更新，从而在不影响整体策略的情况下提高视觉处理的性能。
7. 该技术可应用于工业机器人抓取、物流分拣等场景，通过提高视觉伺服的视角适应性和准确性，显著提升机器人操作的可靠性和效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484422540)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260225237)**
<br/><br/>

---


<br/>

### 7. 可变速度致动器

**Title (EN)**: VARIABLE SPEED ACTUATORS  
**Pub. No.**: US20260227636

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Kenneth Alexander Diest](https://patents.google.com/?inventor=Kenneth+Alexander+Diest&country=US&num=100&sort=new), [Shaomin Xiong](https://patents.google.com/?inventor=Shaomin+Xiong&country=US&num=100&sort=new), [Lidu Huang](https://patents.google.com/?inventor=Lidu+Huang&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种镜头组件包括显示器、镜头、致动块和处理逻辑。显示器用于生成包含图像的显示光。镜头用于聚焦显示光。致动块用于调整镜头与显示器之间的间距。致动块包括形状记忆合金（SMA）致动器。处理逻辑用于操作SMA致动器以控制其致动速度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484425189_1.jpg)

**Technical Field (技术领域)**:  
光学领域，具体涉及可变速度致动器技术。

**Background (发明背景)**:  
形状记忆合金（SMA）致动器因其可逆相变能力，近年来在航空航天、汽车和生物医学设备等领域得到广泛应用。然而，现有技术主要关注提高SMA致动器的致动速度，而忽略了某些应用场景中需要控制或降低致动速度的需求。

**Summary (发明总览)**:  
本发明提出了一种基于形状记忆合金（SMA）的可变速度致动器技术，通过控制SMA致动器的致动速度，实现对显示元件与镜头系统之间距离的精确调节。该技术通过电信号调制、机械阻尼、磁场控制等多种手段实现对致动速度的灵活控制，尤其适用于虚拟现实（VR）、增强现实（AR）等近眼显示设备，以避免因快速致动导致的视觉不适。

**Key Innovation (核心创新)**:  
1. 通过电信号调制（如脉冲宽度调制、脉冲幅度调制）控制SMA致动器的加热电流，从而调节其致动速度。
2. 采用机械阻尼装置（如固定摩擦或可变摩擦制动器）限制SMA致动器的运动速度。
3. 利用磁场与SMA材料的相互作用，改变其对加热的响应特性，从而控制致动速度。
4. 通过多步电流加载方式，逐步增加电流以延长致动过程时间，实现更缓慢的致动。
5. 结合多个SMA致动器形成组合致动器，通过选择不同物理特性的致动器来控制整体致动速度。
6. 在近眼显示设备中应用该技术，通过精确控制显示元件与镜头系统之间的距离调节速度，避免快速致动带来的视觉不适。
7. 该技术可应用于虚拟现实、增强现实等场景，提供更自然和舒适的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484425189)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260227636)**
<br/><br/>

---


<br/>

### 8. 中压模块化机架系统

**Title (EN)**: MEDIUM VOLTAGE MODULAR RACK SYSTEM  
**Pub. No.**: US20260231350

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ehsan NASR AZADANI](https://patents.google.com/?inventor=Ehsan+NASR+AZADANI&country=US&num=100&sort=new), [Scot Edward HEATH](https://patents.google.com/?inventor=Scot+Edward+HEATH&country=US&num=100&sort=new), [Jayson Michael JOCHIM](https://patents.google.com/?inventor=Jayson+Michael+JOCHIM&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种中压模块化机架系统包括：用于容纳多个计算资源的IT机架；包含多个电源连接器并用于将计算资源与低压直流电源源操作耦合的电源面板机架；包含一个或多个储能设备且每个储能设备均配置为从低压直流电源源存储能量并向其提供能量的储能机架；包含用于将中压电源源转换为低压直流电源源的电能转换设备的电源转换机架；以及用于接收中压交流电源源和中压直流电源源的中压机架。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484429289_1.jpg)

**Technical Field (技术领域)**:  
数据中心供电技术领域，具体涉及中压供电的模块化机架系统。

**Background (发明背景)**:  
数据中心对计算、存储和网络设备的需求随着人工智能和云计算等应用的增长而迅速增加，导致数据中心密度和电力需求上升。传统数据中心采用低电压、高电流的配电方式，需要大量昂贵的铜线且效率较低。随着数据中心电力需求的增加，现有配电方式面临成本和物理空间方面的挑战。

**Summary (发明总览)**:  
本发明提出了一种中压模块化机架系统，通过将中压电源直接引入机架，减少数据中心对铜线的需求。系统采用模块化设计，包括IT机架、电源面板机架、储能机架、电源转换机架和中压机架，各机架可独立配置和升级。该设计通过降低电流需求，提高了电力传输效率并减少了物理空间占用。

**Key Innovation (核心创新)**:  
1. 采用中压供电设计，将中压电源直接引入机架，减少数据中心对低电压、高电流配电的依赖。
2. 通过模块化设计，将系统分解为IT机架、电源面板机架、储能机架、电源转换机架和中压机架，各机架可独立配置和升级。
3. 包含一个或多个储能设备，能够从低压直流电源源存储能量并向其提供能量，支持电力需求的动态调节。
4. 电源转换机架配置有电能转换设备，能够高效地将中压电源转换为低压直流电源。
5. 通过减少铜线使用量，降低了数据中心建设和运营成本，同时提高了电力传输效率。
6. 支持现有数据中心逐步升级为中压模块化系统，用户可根据需求分阶段替换传统机架。
7. 适用于高密度、高电力需求的数据中心应用场景，如人工智能和云计算，能够提供更高效、灵活的电力解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484429289)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260231350)**
<br/><br/>

---


<br/>

### 9. 具有原位电流测量电路的微型LED系统

**Title (EN)**: MICRO-LED SYSTEMS HAVING IN SITU CURRENT MEASUREMENT CIRCUITS  
**Pub. No.**: US20260229156

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Lawrence A. PRATHER](https://patents.google.com/?inventor=Lawrence+A.+PRATHER&country=US&num=100&sort=new), [Kenneth Colin DYER](https://patents.google.com/?inventor=Kenneth+Colin+DYER&country=US&num=100&sort=new), [Barry THOMPSON](https://patents.google.com/?inventor=Barry+THOMPSON&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明描述了具有原位电流测量电路的微型发光二极管（micro-LEDs）系统。示例性micro-LED系统包括在显示基底上形成的多个micro-LED和在背板基底上形成的多个像素驱动电路，这些电路与显示基底耦合，其中每个像素驱动电路在micro-LEDs的第一工作模式下向相应的micro-LED提供电流。该micro-LED系统还包括在背板基底上形成的电流测量电路，该电路包含一个用于驱动源极跟随器晶体管的运算放大器。该系统还包括一组传输晶体管，用于在第二工作模式下按每个像素驱动电路为基础，有选择地将电流从一个或多个像素驱动电路重定向到电流测量电路，从而允许在背板基底内进行原位电流测量。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426867_1.jpg)

**Technical Field (技术领域)**:  
显示技术领域，具体涉及micro-LED显示系统的电流测量电路。

**Background (发明背景)**:  
micro-LED通常在不同于背板基底的显示基底上形成，背板基底包含用于驱动micro-LED的像素驱动电路。背板基底还包括其他电路，包括控制电路。micro-LED阵列的显示基底采用与背板基底不同的工艺技术制造。此外，micro-LED需要不同的电压，包括负电压才能工作。例如，在阴极连接的micro-LED阵列中，micro-LED的公共阴极相对于阳极端子保持在负电压。公共阴极端子的负电压可低至负5伏或更低。这些高电压可能会损坏在背板基底上形成的低压电压晶体管。此外，micro-LED需要不同的模拟电压才能工作，这些电压通常也与背板基底上形成的低压电压晶体管不兼容。此外，micro-LED侧的电压摆幅高于背板基底上形成的电路的电压摆幅。这意味着很难测量与micro-LED相关的电流和电压。先前的解决方案不足以解决这些问题。因此，需要改进用于micro-LED的电流测量电路。

**Summary (发明总览)**:  
本发明提出了一种新型micro-LED系统，通过在背板基底中集成电流测量电路，实现对micro-LED电流的原位测量。该系统采用一组传输晶体管，在测试模式下按像素驱动电路为基础，将电流重定向到电流测量电路。电流测量电路包含一个运算放大器，用于驱动源极跟随器晶体管，从而实现精确测量。本发明解决了现有技术中难以在背板基底上准确测量micro-LED电流的问题，提供了一种更可靠和高效的测量方法。

**Key Innovation (核心创新)**:  
1. 在背板基底中集成了电流测量电路，通过运算放大器驱动源极跟随器晶体管，实现对micro-LED电流的原位测量。
2. 采用一组传输晶体管，在测试模式下按像素驱动电路为基础，将电流从像素驱动电路重定向到电流测量电路。
3. 电流测量电路包含一个电平转换和缩放电路，用于调整电压水平以适配模数转换器（ADC），确保测量精度。
4. 通过在背板基底内进行电流测量，避免了高电压对低压晶体管的损害，提高了系统的可靠性和稳定性。
5. 该设计解决了micro-LED与背板电路之间电压不兼容的问题，使得电流测量更加准确和高效。
6. 本发明可应用于高分辨率micro-LED显示器中，用于实时监测和校准每个像素的电流，提升显示质量和寿命。
7. 通过原位测量技术，本专利为micro-LED显示系统提供了独特的电流监测能力，适用于需要高精度和高可靠性的应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426867)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229156)**
<br/><br/>

---


<br/>

### 10. 用于低反射波导且具有高显示性能的光栅

**Title (EN)**: GRATING FOR LOW REFLECTION WAVEGUIDE WITH HIGH DISPLAY PERFORMANCE  
**Pub. No.**: US20260227561

**Applicant**: GOOGLE LLC  
**Inventor**: [Qinglan Huang](https://patents.google.com/?inventor=Qinglan+Huang&country=US&num=100&sort=new), [Thomas Hoekman](https://patents.google.com/?inventor=Thomas+Hoekman&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种波导包括至少一个一维（1D）光栅，该光栅设置在波导上或波导内。1D光栅包括沿单一轴线定义的周期性结构，该周期性结构包含交替的不同折射率区域。1D光栅还在每个周期内包含多个高折射率区域。在另一种配置中，波导包括至少一个二维（2D）光栅，该光栅设置在波导上。2D光栅包括沿第一轴和垂直于第一轴的第二轴定义的晶格结构，该晶格结构包含交替的不同折射率区域。2D光栅还在每个晶格单元内包含多个高折射率区域。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484425105_1.jpg)

**Technical Field (技术领域)**:  
光学显示技术领域，具体涉及用于增强现实（AR）和虚拟现实（VR）显示的波导光栅技术。

**Background (发明背景)**:  
波导是光学系统中的关键组件，广泛应用于增强现实和虚拟现实显示中，用于引导光源发出的光线至用户眼睛，同时保持对外界环境的透明度。衍射光栅在这些系统中用于高效耦合和操控光线。然而，高折射率材料制成的光栅存在表面反射问题，这会影响光学性能和视觉体验，特别是在需要高透明度和低杂散光的应用中。

**Summary (发明总览)**:  
本发明提出了一种用于低反射波导的光栅技术，通过在一维和二维光栅中引入特定结构来减少表面反射并提高光学性能。一维光栅通过在每个周期内设置双重光栅线来降低反射率并增强红光波长效率。二维光栅通过优化晶格形状和折射率分布，实现单方向光衍射并减少反射。本发明相较于现有技术，在减少表面反射的同时保持了高衍射效率，并提升了显示亮度和均匀性。

**Key Innovation (核心创新)**:  
1. 采用一维光栅结构，在每个周期内设置双重光栅线，通过共振模式降低反射率至2%以下，同时增强红光波长效率。
2. 设计二维光栅晶格结构，使其主要在单一方向上衍射光线，通过优化矩形或椭圆形单元结构实现精确的衍射控制。
3. 在二维光栅的每个晶格单元内引入折射率过渡区域，通过调节填充因子实现1.7%的平均轴向反射率。
4. 利用亚波长特征实现对光的精确操控，包括衍射、反射和透射，以实现定制化的光学功能。
5. 通过优化光栅结构，在减少表面反射的同时保持高衍射效率，解决了高折射率材料带来的反射问题。
6. 这些光栅配置可应用于头戴式显示设备（HWD），显著提升显示亮度和均匀性，同时减少杂散光和眩光。
7. 本发明特别适用于增强现实和虚拟现实显示设备，能够在复杂光学环境下提供更清晰、更逼真的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484425105)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260227561)**
<br/><br/>

---


<br/>

### 11. 基于机器学习的提示驱动图像编辑

**Title (EN)**: PROMPT-DRIVEN IMAGE EDITING USING MACHINE LEARNING  
**Pub. No.**: US20260228944

**Applicant**: Google LLC  
**Inventor**: [Yael Pritch KNAAN](https://patents.google.com/?inventor=Yael+Pritch+KNAAN&country=US&num=100&sort=new), [Noam PETRANK](https://patents.google.com/?inventor=Noam+PETRANK&country=US&num=100&sort=new), [Navin SARMA](https://patents.google.com/?inventor=Navin+SARMA&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种媒体应用接收初始图像和用于更改初始图像的文本请求，初始图像包含具有面部的对象。媒体应用从初始图像生成对应于对象面部的保留掩码。媒体应用将文本请求、初始图像和保留掩码作为输入提供给扩散模型。扩散模型基于初始图像输出去噪后的初始图像；通过文本调节和前向扩散生成满足文本请求的噪声翻译图像；并基于噪声翻译图像、提取的特征和自注意力图输出去噪后的翻译图像。媒体应用将去噪后的初始图像、保留掩码和去噪后的翻译图像混合形成输出图像，其中保留掩码防止对初始图像中面部的修改。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426631_1.jpg)

**Technical Field (技术领域)**:  
人工智能图像生成领域，具体涉及基于扩散模型的图像编辑技术。

**Background (发明背景)**:  
生成式人工智能可用于从文本提示生成图像，但当图像包含人物时，结果往往存在问题，因为细节特征如手指、眼睛和嘴巴的表示可能不准确。现有的生成式AI在捕捉这些复杂特征方面仍处于发展中。

**Summary (发明总览)**:  
本发明提出了一种基于扩散模型的图像编辑方法，通过保留初始图像中面部的特征并结合文本请求进行图像修改。该方法首先生成一个保留面部特征的掩码，然后利用扩散模型对图像进行去噪处理和文本调节，生成满足文本请求的修改后图像。最终通过混合初始图像、保留掩码和修改后的图像，生成最终的输出图像。该方法通过保留关键特征和利用自注意力机制，实现了更精准的图像编辑。

**Key Innovation (核心创新)**:  
1. 通过生成保留掩码，精确保护初始图像中面部的特征，防止在编辑过程中被修改。
2. 利用扩散模型进行前向扩散和文本调节，生成满足文本请求的噪声翻译图像，确保图像修改符合用户需求。
3. 结合提取的特征和自注意力图，在去噪过程中保持初始图像的结构和细节，实现更精准的图像编辑。
4. 提供多种用户交互方式，包括从预制提示库中选择或直接输入文本请求，提升用户体验。
5. 能够识别并建议替换或修改背景中的特定区域或对象，增强图像编辑的智能化和自动化。
6. 采用DDIM反演方法进行逆扩散处理，提高图像去噪和重建的效率。
7. 该技术可应用于图像编辑软件、社交媒体内容生成等场景，为用户提供更自然和精准的图像修改功能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426631)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260228944)**
<br/><br/>

---


<br/>

### 12. 用于自主钓鱼识别检测的钓鱼检测引擎

**Title (EN)**: PHISHING DETECTION ENGINE(S) FOR AUTONOMOUS PHISHING IDENTIFICATION  
**Pub. No.**: US20260230504

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Gilad KIRSHENBOIM](https://patents.google.com/?inventor=Gilad+KIRSHENBOIM&country=US&num=100&sort=new), [David Natan KAPLAN](https://patents.google.com/?inventor=David+Natan+KAPLAN&country=US&num=100&sort=new), [Aviel LAVIE](https://patents.google.com/?inventor=Aviel+LAVIE&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明提供了一种钓鱼检测引擎及其相关功能。在一个方面，钓鱼检测引擎捕获客户端设备用户界面上显示的焦点内容。从焦点内容中，钓鱼检测引擎提取特征，这些特征包括文本元素和视觉元素。利用这些特征，并在某些情况下结合与客户端设备相关的历史用户交互，钓鱼检测引擎判断这些特征是否表明存在潜在的钓鱼活动。如果检测到潜在钓鱼活动，钓鱼检测引擎执行一个或多个安全操作以限制潜在钓鱼活动的损害，例如阻止钓鱼活动的激活步骤的执行。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484428356_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算机软件应用与服务领域，具体为用于自主检测和识别潜在钓鱼活动的钓鱼检测引擎。

**Background (发明背景)**:  
在当今数字互联时代，钓鱼活动已成为一种普遍且日益增长的威胁。钓鱼是一种网络攻击形式，恶意行为者冒充合法组织或个人，诱骗用户泄露敏感信息，如密码、信用卡号码或个人数据。钓鱼通常通过欺诈性电子邮件、短信或虚假网站进行，利用人类信任，可能导致身份盗用、财务损失和数据泄露。随着对数字平台的依赖增加，钓鱼手段变得越来越复杂，更难以检测，这增加了个人和企业面临的风险。

**Summary (发明总览)**:  
本发明提出了一种用于自主钓鱼识别的钓鱼检测引擎，通过监控用户与客户端设备用户界面的交互内容来检测潜在钓鱼活动。该引擎通过提取焦点内容的文本和视觉特征，并利用机器学习模型处理这些特征来判断是否存在钓鱼行为。如果检测到潜在钓鱼活动，引擎会执行相应的安全操作，例如阻止恶意链接的执行或生成钓鱼活动报告以供进一步处理。本发明通过实时监控和智能分析，弥补了传统钓鱼检测方法在应对复杂钓鱼手段时的不足。

**Key Innovation (核心创新)**:  
1. 通过监控用户界面的焦点内容，实时提取文本和视觉特征，实现对钓鱼活动的动态检测。
2. 利用机器学习模型处理提取的特征，模型经过历史数据集训练，能够识别与正常内容交互不同的钓鱼特征。
3. 针对不同客户端设备或用户，模型可进行个性化调整，以更准确地识别与特定用户或设备相关的正常内容交互。
4. 在无法明确分类的情况下，引擎会持续监控后续内容交互，提取新特征以进一步确认是否存在钓鱼活动。
5. 当检测到高风险钓鱼活动时，引擎会执行安全操作，如阻止恶意URL或访问网页，以防止钓鱼攻击的进一步执行。
6. 在钓鱼活动成功的情况下，引擎会生成详细的钓鱼活动报告，包括截图、识别理由和相关信息，供安全系统分析。
7. 本发明可应用于电子邮件、消息应用和网页等多种场景，为用户提供全面的钓鱼防护，提升数字通信的安全性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484428356)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260230504)**
<br/><br/>

---


<br/>

### 13. 基于用户偏好的生成式人工智能自适应音频技术

**Title (EN)**: ADAPTIVE AUDIO BASED ON USER PREFERENCES THROUGH LEVERAGING GENERATIVE ARTIFICIAL INTELLIGENCE  
**Pub. No.**: US20260224990

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Tero Juhani PATANA](https://patents.google.com/?inventor=Tero+Juhani+PATANA&country=US&num=100&sort=new), [Erik Roberto GARCIA](https://patents.google.com/?inventor=Erik+Roberto+GARCIA&country=US&num=100&sort=new), [Shuoqi Scott WANG](https://patents.google.com/?inventor=Shuoqi+Scott+WANG&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明公开了一种用于根据用户偏好调整动态音频流以修改特定声音类别的技术。该技术适用于包括游戏系统在内的多种系统。用户可通过图形用户界面选择声音类别和变换类型。系统使用预训练的生成式人工智能（AI）模型处理动态音频流（例如游戏实例），以用户指定的变换类型对声音类别实例进行转换。生成式AI模型的输出流可作为音频输出使用。该技术允许在无需针对特定应用或游戏进行编程的情况下，处理和转换系统上的所有动态音频流。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484422268_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及计算软件和硬件领域，具体为自适应音频技术。

**Background (发明背景)**:  
听觉触发因素会影响人类情绪和用户体验，例如ASMR内容可引发愉悦感，而某些重复声音可能引发不耐受甚至心理压力。在游戏等场景中，常见声音如枪声、爆炸声等可能对部分用户造成负面影响。目前，尚无简便方法帮助受这些声音困扰的用户避免不适。

**Summary (发明总览)**:  
本发明提出了一种基于生成式人工智能的自适应音频处理方案。用户可选择特定声音类别和变换类型，系统通过预训练模型识别并处理音频内容，实现对目标音频的调整，如去除、增强或替换等。该方案无需针对特定应用进行编程，可广泛应用于不同系统和场景。其核心创新在于利用AI模型对音频内容进行智能识别和动态调整，以满足用户个性化需求。

**Key Innovation (核心创新)**:  
1. 通过预训练的生成式AI模型实现对动态音频流中特定声音类别的智能识别和分类。
2. 提供多种变换类型，包括去除、替换、增强、隔离等，用户可自定义音频处理方式。
3. 支持用户上传样本以训练个性化AI模型，实现对特定声音类别的精准处理。
4. 允许用户在不同设备间同步AI模型和用户偏好设置，确保跨平台一致性。
5. 采用分段处理机制，用户可调整处理粒度以平衡处理精度和延迟。
6. 可堆叠多个AI模型以同时处理多个声音类别，实现复杂音频场景的全面覆盖。
7. 该技术可应用于游戏、音频编辑、辅助功能等领域，为有听觉障碍或特殊需求的用户提供定制化音频体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484422268)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260224990)**
<br/><br/>

---


<br/>

### 14. 具有气压压力传感器和光学传感器的指套组件用于测量血压

**Title (EN)**: Finger Cuff Assembly Having Barometric Pressure Sensors and Optical Sensors for Measuring Blood Pressure  
**Pub. No.**: US20260224120

**Applicant**: Google LLC  
**Inventor**: [Ravi Narasimhan](https://patents.google.com/?inventor=Ravi+Narasimhan&country=US&num=100&sort=new), [Samuel Wei Sheng](https://patents.google.com/?inventor=Samuel+Wei+Sheng&country=US&num=100&sort=new), [Paul Joseph Silberschatz](https://patents.google.com/?inventor=Paul+Joseph+Silberschatz&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种指套组件包括一个具有内表面的指套腔体，以及排列在内表面上的气压压力传感器阵列。该气压压力传感器阵列用于映射手指中动脉附近的压力表面，以提供多个数据通道来测量血压。指套组件还包括一个或多个光学传感器，排列在气压压力传感器阵列旁边的指套腔体内表面上，以及一个与气压压力传感器阵列配合的充气囊，充气时气囊会增加气压压力传感器对手指的压力。指套组件还包括一个控制模块，具有用于接收多个数据通道数据的电路，并使用这些数据来估算血压。随着气压压力传感器上的压力增加，动脉的脉搏在多个数据通道上被检测到，并被控制模块用于估算血压。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484424899_1.jpg)

**Technical Field (技术领域)**:  
医疗设备技术领域，具体涉及无创血压测量技术，特别是基于气压压力传感器和光学传感器的指套式血压测量装置。

**Background (发明背景)**:  
传统的无创血压测量通常使用外部袖带对患者动脉施加压力，通过观察动脉反应来确定血压。无袖带血压测量技术虽然减少了患者负担，但大多依赖光学信号（如光电容积描记图PPG）和生理信号（如心电图ECG或心冲击图BCG），其测量准确性不足。现有的基于PPG波形形状的脉搏波分析方法也存在类似问题，无法满足临床精准血压监测的需求。

**Summary (发明总览)**:  
本发明提出了一种新型指套式血压测量方案，通过在指套内集成气压压力传感器阵列和光学传感器，实现对患者血压的精准测量。该方案利用气压压力传感器阵列对动脉周围压力分布进行空间映射，并通过充气囊调节压力，结合光学传感器检测动脉脉搏信号，最终实现多通道、多模态的血压测量。与传统袖带和无袖带方法相比，本发明提供了更便捷且精准的血压测量方式。

**Key Innovation (核心创新)**:  
1. 采用气压压力传感器阵列封装在弹性材料中，实现对动脉周围压力分布的精确空间映射，解决了传统单点测量无法适应不同动脉位置的问题。
2. 通过充气囊调节气压压力传感器对手指的压力，并在压力变化过程中捕捉动脉脉搏的幅度和形态特征，为血压估算提供多维度数据支持。
3. 集成光学传感器（如脉搏血氧仪）用于检测动脉闭塞状态，与气压压力传感器数据结合，提高血压测量的准确性和可靠性。
4. 内置微型泵控制气囊充气，实现对测量过程的精确控制，并可根据患者手指尺寸自动调节压力。
5. 设备采用模块化设计，指套与控制模块可分离，便于佩戴和操作，同时确保测量数据的稳定传输。
6. 相较于传统袖带式设备，本发明提供更便捷的佩戴体验；相较于无袖带设备，本发明通过多通道数据采集提高了测量精度。
7. 该技术可应用于家庭医疗场景或可穿戴设备中，为需要频繁监测血压的患者提供了一种高效且精准的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484424899)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260224120)**
<br/><br/>

---


<br/>

### 15. 头戴式设备在显示模式和无显示模式之间切换的技术、设备及其使用方法

**Title (EN)**: TECHNIQUES FOR SWITCHING BETWEEN A DISPLAY MODE AND A DISPLAYLESS MODE AT A HEAD-WEARABLE DEVICE, AND DEVICES AND METHODS OF USE THEREOF  
**Pub. No.**: US20260229154

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Yfat Eyal](https://patents.google.com/?inventor=Yfat+Eyal&country=US&num=100&sort=new), [Vanessa Michelle Garcia](https://patents.google.com/?inventor=Vanessa+Michelle+Garcia&country=US&num=100&sort=new), [Anurag Awasthi](https://patents.google.com/?inventor=Anurag+Awasthi&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明描述了一种方法，用于根据检测到的显示抑制条件自动将头戴式设备从显示状态切换到无显示状态。该方法包括：在头戴式设备处于显示状态时：(i) 获取第一指令，(ii) 根据第一指令在头戴式设备的显示屏上呈现第一响应，以及(iii) 根据检测到的显示抑制条件，使头戴式设备进入无显示状态。该方法进一步包括：在头戴式设备处于无显示状态时：(i) 获取第二指令，(ii) 根据第二指令在头戴式设备的扬声器上呈现第二响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426864_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及扩展现实(XR)设备领域，具体为在显示模式和无显示模式之间切换的技术。

**Background (发明背景)**:  
扩展现实(XR)设备通过在用户视野中呈现信息来提供即时信息。然而，XR设备在日常环境和公共场所使用时，可能会因显示不必要的或阻碍性的XR元素而干扰用户的视野。此外，在某些情况下，如驾驶时，显示任何XR元素可能会带来安全隐患。同时，持续在显示屏上呈现信息会消耗更多电量，影响设备续航。因此，需要一种解决方案，在视觉呈现不是必要时减少显示屏的使用。

**Summary (发明总览)**:  
本发明提出了一种智能切换头戴式设备显示模式的方法，旨在解决XR设备在不需要视觉信息时过度使用显示屏的问题。该方法通过检测特定条件（如用户需求、安全性或注意力需求）自动将设备从显示状态切换到无显示状态。当需要用户输入或特定任务时，设备会重新激活显示屏并提供相关用户界面。本发明通过动态调整显示状态，在保证用户体验的同时，延长设备续航并提高安全性。

**Key Innovation (核心创新)**:  
1. 通过检测显示抑制条件（如安全需求、注意力需求或用户自定义条件）自动将设备从显示状态切换到无显示状态，优化设备在不同场景下的使用。
2. 在无显示状态下，通过语音、手势或凝视等非视觉指令执行任务，减少对显示屏的依赖，提升设备在不便于视觉操作环境中的可用性。
3. 设备在需要用户确认或澄清时，会智能地重新激活显示屏并显示相关用户界面，确保用户操作的准确性和便捷性。
4. 通过在无显示状态下使用音频反馈，设备能够在减少视觉信息呈现的同时，保持与用户的有效交互，提升用户体验。
5. 设备能够根据用户行为和环境变化动态调整显示状态，例如在驾驶时自动关闭显示屏以提高安全性。
6. 通过减少显示屏的使用频率，本发明有效降低了设备能耗，延长了电池续航时间。
7. 本发明可应用于AR眼镜、MR头盔等XR设备，适用于驾驶、户外运动等场景，为用户提供更安全、更高效的交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426864)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229154)**
<br/><br/>

---


<br/>

### 16. 会议管理系统中的中断语音管理引擎

**Title (EN)**: DISRUPTED-SPEECH MANAGEMENT ENGINE FOR A MEETING MANAGEMENT SYSTEM  
**Pub. No.**: US20260230560

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Mrinal Kumar SHARMA](https://patents.google.com/?inventor=Mrinal+Kumar+SHARMA&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明涉及提供与会议管理系统的中断语音管理引擎相关的中断语音辅助服务的方法、系统及计算机存储介质。该中断语音辅助服务是一种辅助功能服务，支持中断语音管理引擎的可访问性操作，以在会议管理系统中提供中断语音辅助功能。在操作中，访问包含音频数据的会议数据。分析音频数据以确定其包含达到中断语音阈值水平的中断语音。基于包含达到中断语音阈值水平的中断语音的音频数据，可以执行一个或多个针对会议的中断语音辅助操作。这些操作包括识别中断语音词汇；确定中断语音词汇的替代词汇。基于一个或多个中断语音辅助操作生成中断语音辅助界面，该界面包含中断语音词汇的替代词汇。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484428417_1.jpg)

**Technical Field (技术领域)**:  
会议管理系统；语音处理技术；辅助功能服务

**Background (发明背景)**:  
现有的会议管理系统主要支持远程会议和虚拟会议，但缺乏处理用户语音中断（如口吃或其他言语障碍）的计算基础设施和逻辑。这些系统无法有效解决用户言语障碍问题，限制了用户之间的有效沟通。此外，现有系统缺乏针对言语障碍用户的辅助功能服务，导致言语障碍用户难以通过会议管理系统进行有效交流。

**Summary (发明总览)**:  
本发明提出了一种改进的会议管理系统，通过集成中断语音管理引擎来提供针对言语障碍用户的辅助功能。该系统能够识别会议中的中断语音，生成包含替代词汇的辅助界面，并提供实时反馈和用户鼓励等功能。通过这些技术手段，系统能够显著提升言语障碍用户与其他参会者之间的沟通效率，为会议管理系统提供更全面的辅助功能支持。

**Key Innovation (核心创新)**:  
1. 引入中断语音管理引擎，通过分析音频数据识别会议中的中断语音，并确定替代词汇。
2. 提供个性化的中断语音辅助服务，根据用户的言语障碍档案数据生成定制化的替代词汇。
3. 生成中断语音辅助界面，包含中断语音词汇及其替代词汇，并在会议中实时显示。
4. 支持数字助理功能，用于生成中断语音辅助界面并与用户交互。
5. 提供用户鼓励功能，通过音频数据分析和替代词汇的使用情况给予用户反馈和奖励。
6. 扫描会议幻灯片以识别中断语音词汇，并提供相应的辅助功能。
7. 该技术可应用于远程会议、远程教育等场景，为言语障碍用户提供更便捷的沟通方式，提升会议效率和用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484428417)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260230560)**
<br/><br/>

---


<br/>

### 17. 考虑智能眼镜框架变形的视觉内容输出

**Title (EN)**: OUTPUTTING VISUAL CONTENT CONSIDERING SMARTGLASSES FRAME DEFORMATION  
**Pub. No.**: US20260228916

**Applicant**: GOOGLE LLC  
**Inventor**: [Joshua Anthony Hernandez](https://patents.google.com/?inventor=Joshua+Anthony+Hernandez&country=US&num=100&sort=new), [Zhiheng Jia](https://patents.google.com/?inventor=Zhiheng+Jia&country=US&num=100&sort=new), [Ryan Christopher DuToit](https://patents.google.com/?inventor=Ryan+Christopher+DuToit&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明涉及在增强现实智能眼镜使用过程中保持用户舒适度的技术，包括对框架变形进行在线校准以校正镜片中的显示位置。该校准通过将世界朝向摄像头与眼动追踪摄像头之间的框架部分建模为绕框架部分法线轴旋转的铰链来实现，即框架部分由两个线段组成，它们在待确定的未知旋转角度处连接。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426601_1.jpg)

**Technical Field (技术领域)**:  
增强现实智能眼镜领域，具体涉及框架变形校准和显示位置校正技术。

**Background (发明背景)**:  
智能眼镜等可穿戴设备通常需要适应用户的头部形状，这导致框架材料具有一定的柔性和可变形性。然而，这种柔性可能引起显示组件的错位，特别是在眼动追踪摄像头和显示输出之间产生偏差，影响用户体验。本发明旨在解决框架变形导致的显示错位问题，通过实时校准来维持视觉内容的正确显示。

**Summary (发明总览)**:  
本发明提出了一种智能眼镜框架变形在线校准方法，通过将世界朝向摄像头与眼动追踪摄像头之间的框架部分建模为铰链结构，计算铰链角度以反映框架变形程度。基于该角度，智能眼镜的显示内容位置被动态调整，以确保视觉内容与用户视线对齐，从而提升佩戴舒适度。该方法通过实时处理摄像头投影数据实现，无需复杂的硬件改造。

**Key Innovation (核心创新)**:  
1. 将智能眼镜框架变形建模为铰链结构，通过计算铰链角度来量化框架变形程度。
2. 利用世界朝向摄像头和眼动追踪摄像头对同一物体点的投影数据，提取特征并计算铰链角度。
3. 通过实时处理摄像头数据，实现智能眼镜显示位置的动态校正，确保视觉内容与用户视线一致。
4. 采用基于铰链模型的三角方程计算方法，简化了变形校正的计算复杂度。
5. 该方法能够适应温度变化、框架老化以及意外冲击等不同场景下的变形情况。
6. 通过在线校准机制，智能眼镜可以在用户佩戴过程中持续校正显示位置，提升视觉体验。
7. 该技术可应用于增强现实导航、虚拟现实显示等场景，提供更精准的视觉内容呈现。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426601)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260228916)**
<br/><br/>

---


<br/>

### 18. 非预期触摸输入的聚合可能性

**Title (EN)**: AGGREGATED LIKELIHOOD OF UNINTENTIONAL TOUCH INPUT  
**Pub. No.**: US20260227875

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Gilad PUNDAK](https://patents.google.com/?inventor=Gilad+PUNDAK&country=US&num=100&sort=new), [Hanan GRINBERG](https://patents.google.com/?inventor=Hanan+GRINBERG&country=US&num=100&sort=new), [Eran ARBEL](https://patents.google.com/?inventor=Eran+ARBEL&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明提供了一种在触摸感应显示设备上处理输入的方法。首先识别触摸感应显示设备的触摸输入。基于从识别的触摸输入中提取的第一组特征，确定该触摸输入为非预期的第一可能性，并将其与第一置信阈值进行比较。如果第一可能性低于第一置信阈值，则基于从附加传感器输出中提取的第二组特征确定该触摸输入为非预期的第二可能性。然后基于至少第一可能性、第一组特征和第二可能性确定该触摸输入为非预期的聚合可能性。如果聚合可能性高于第二置信阈值，则阻止该触摸输入。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484425451_1.jpg)

**Technical Field (技术领域)**:  
触摸感应显示技术领域，具体涉及非预期触摸输入的检测与处理。

**Background (发明背景)**:  
触摸感应显示设备在日常生活中非常普遍，但其输入可能来自用户有意或无意的操作。无意的触摸输入可能导致设备误操作，如上传信息、删除文件或进行购买等。现有的触摸感应技术主要依赖触摸传感器数据，难以在复杂场景中准确区分有意和无意输入。

**Summary (发明总览)**:  
本发明提出了一种两阶段方法，用于区分触摸输入是否有意。首先，通过触摸传感器数据评估触摸输入为非预期的可能性。如果可能性较低，则进一步分析来自其他传感器的数据，如加速度计、陀螺仪和设备摄像头等，以确定输入的意图。最终基于综合分析结果决定是否阻止该触摸输入。这种方法在保证高准确率的同时，减少了误判并提升了用户体验。

**Key Innovation (核心创新)**:  
1. 采用两阶段处理方法，先通过触摸传感器数据初步判断触摸输入的意图性，再结合其他传感器数据进行综合分析。
2. 利用触摸传感器生成的热点图（heatmap）提取特征，精确识别触摸输入的物理特征和位置信息。
3. 通过加速度计、陀螺仪等传感器数据判断输入设备的运动状态，从而区分用户有意操作和无意的触碰。
4. 引入设备摄像头图像处理技术，分析用户和设备在触摸输入前的相对位置、方向和运动轨迹。
5. 将第二阶段的分析过程移出设备固件，通过软件层面的补丁实现升级，降低了实现和集成成本。
6. 通过缓存和离线分析已有传感器数据，显著减少对设备功耗的影响。
7. 该技术可应用于智能手机、平板电脑等触摸设备，有效减少误操作，提高用户操作的准确性和可靠性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484425451)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260227875)**
<br/><br/>

---


<br/>

### 19. 消除重影图像

**Title (EN)**: GHOST IMAGE MITIGATION  
**Pub. No.**: US20260228991

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Dmitry Sizov](https://patents.google.com/?inventor=Dmitry+Sizov&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种增强现实（AR）显示系统包括一个具有表面和显示视场（FOV）的波导，布置在波导表面上的第一和第二输入光学元件，以及分别配置为向第一和第二输入光学元件发射第一和第二显示光并将第一和第二显示光耦合到波导中的第一和第二投影仪，其中第一投影仪相对于波导表面以第一倾斜角度定向，第二投影仪相对于波导表面以第二倾斜角度定向，第一倾斜角度至少是第一投影仪视场的一半，第二倾斜角度至少是第二投影仪视场的一半。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426683_1.jpg)

**Technical Field (技术领域)**:  
增强现实显示技术；光学波导系统；投影仪光学设计

**Background (发明背景)**:  
增强现实（AR）显示系统通常使用波导将图像投射到用户视野中。然而，现有技术中投影仪与波导的排列方式容易导致重影图像的产生，影响显示质量。
现有系统难以有效消除重影图像，同时保持紧凑的设备尺寸和合理的成本。
本发明旨在通过优化投影仪的倾斜角度来减少重影图像的产生。

**Summary (发明总览)**:  
本发明提出了一种通过调整投影仪倾斜角度来减少AR显示系统中重影图像的技术方案。
通过将投影仪以至少半个视场角度倾斜，可以有效减少重影图像的产生。
该方法在保持光学系统紧凑性的同时，提升了显示质量。
相较于传统方法，本发明提供了一种更简单且成本效益更高的解决方案。

**Key Innovation (核心创新)**:  
1. 通过设置投影仪相对于波导表面的倾斜角度来减少重影图像的产生，其中倾斜角度至少是投影仪视场的一半。
2. 采用双投影仪设计，分别以不同的倾斜角度将显示光耦合到波导中，进一步降低重影图像的干扰。
3. 通过优化投影仪的倾斜角度，在不增加系统复杂性的前提下，实现更清晰的图像显示。
4. 该设计保持了光学系统的紧凑性，适用于便携式AR设备。
5. 通过调整倾斜角度，可以灵活适应不同视场需求的AR应用场景。
6. 该技术特别适用于需要高对比度和低重影干扰的增强现实显示场景，如导航和工业培训。
7. 提供了更优的图像质量和用户体验，同时降低了生产成本和复杂性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426683)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260228991)**
<br/><br/>

---


<br/>

### 20. 显示设备动态调光控制技术

**Title (EN)**: TECHNIQUES FOR DYNAMIC CONTROL OF DIMMING FOR DISPLAY DEVICES  
**Pub. No.**: US20260229155

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Chang Joon PARK](https://patents.google.com/?inventor=Chang+Joon+PARK&country=US&num=100&sort=new), [Brock M. Roland](https://patents.google.com/?inventor=Brock+M.+Roland&country=US&num=100&sort=new), [Glen Patrick Gordon](https://patents.google.com/?inventor=Glen+Patrick+Gordon&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明描述了用于控制显示设备调光面板的示例。通过接收环境光量的测量指示和眼睛注视位置的指示，可以向调光面板的对应区域发送功率控制信号，以激活该区域的调光功能。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426865_1.jpg)

**Technical Field (技术领域)**:  
显示技术领域，具体涉及混合现实设备中的动态调光控制。

**Background (发明背景)**:  
混合现实设备需要平衡环境光透射与显示图像的对比度，但现有技术中增加亮度或背光会显著增加功耗，影响设备续航能力。
小型化设计的可穿戴设备对功耗尤为敏感，现有调光方案难以兼顾显示效果与能耗控制。
本发明旨在解决调光过程中不必要的功耗问题，同时保持良好的图像显示效果。

**Summary (发明总览)**:  
本发明提出了一种针对显示设备调光面板的动态控制方法，通过对调光面板进行分区控制，根据环境光强度和用户注视位置，智能调节特定区域的透光率。
该方法利用眼动追踪传感器和光传感器数据，动态调整调光区域，从而在保证显示效果的同时降低整体功耗。
相较于传统整体调光方案，本发明通过选择性调光实现了更精细的能耗控制。

**Key Innovation (核心创新)**:  
1. 采用分区调光设计，将调光面板划分为多个独立可控区域，实现对显示设备局部区域的精确调光。
2. 结合眼动追踪技术，实时监测用户注视位置，并仅对注视区域对应的调光面板区域进行调光处理。
3. 通过环境光传感器输入数据，根据环境光强度动态调整调光程度，在保证显示效果的同时优化功耗。
4. 调光面板通过电极接收功率信号，实现对特定区域的调光激活或关闭，提供更精细的透光率控制。
5. 针对混合现实设备中的全息图像显示，智能调节对应区域的调光强度，提升图像对比度和可视性。
6. 通过选择性调光，在高环境光条件下也能有效降低功耗，同时保持良好的用户体验。
7. 该技术可应用于可穿戴显示设备，如混合现实眼镜等，为用户提供更节能且优质的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426865)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229155)**
<br/><br/>

---


<br/>

### 21. 基于生成式人工智能的用户自定义声音类别转换自适应音频技术

**Title (EN)**: ADAPTIVE AUDIO LEVERAGING GENERATIVE ARTIFICIAL INTELLIGENCE FOR USER-DEFINED SOUND CLASS TRANSFORMATION  
**Pub. No.**: US20260224991

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Tero Juhani PATANA](https://patents.google.com/?inventor=Tero+Juhani+PATANA&country=US&num=100&sort=new), [Erik Roberto GARCIA](https://patents.google.com/?inventor=Erik+Roberto+GARCIA&country=US&num=100&sort=new), [Shuoqi Scott WANG](https://patents.google.com/?inventor=Shuoqi+Scott+WANG&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明公开了一种用于调整动态音频流以根据用户偏好修改特定声音类别的技术，适用于包括游戏系统在内的系统。用户可以通过图形用户界面提供至少一个声音类别的样本实例和转换类型。系统使用这些声音类别的实例来训练生成式人工智能（AI）模型，以识别动态音频流（例如，来自游戏实例的音频）中的声音类别实例，并根据转换类型对其实施转换。生成式AI模型的输出流可用作音频输出。当用户在输出音频流中听到其他声音类别实例时，可以提供反馈以进一步调整模型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484422269_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算软件和硬件领域，具体为自适应音频技术。

**Background (发明背景)**:  
听觉触发因素会影响人类情绪，进而影响某些产品和服务的技术用户体验。例如，ASMR内容能引发愉悦的生理反应，而对某些重复声音（如咀嚼、咳嗽、吸食）的不耐受则会导致听觉过敏症（misophonia）。对于患有声音恐惧症（phonophobia）或创伤后应激障碍（PTSD）的人来说，某些声音触发因素甚至会造成严重的心理困扰。在游戏场景中，常见游戏音效如枪声、爆炸声和意外声音（如恐怖游戏中的音效）可能引发不良反应。此外，一些环境声音如瀑布、风、雨、昆虫和动物的声音也可能对某些人造成困扰。目前，尚无简单方法帮助受这些声音影响的人避免这些问题，因此需要改进。

**Summary (发明总览)**:  
本发明提出了一种利用生成式人工智能模型识别声音类别并根据用户偏好选择性操控音频内容的技术，以实现用户的理想体验。用户可定义或选择声音类别并提供样本实例来训练模型。生成式AI模型经过训练后，能够理解并区分不同类型的背景噪音、动作序列、对话、环境音效等。用户可以指示该模型识别目标音频内容，并在听到之前对其进行衰减、增强、移除、更改或完全替换。用户在使用过程中可提供反馈以微调模型，从而实现更精准的音频处理。

**Key Innovation (核心创新)**:  
1. 通过用户提供的样本实例和转换类型训练生成式AI模型，实现对特定声音类别的精准识别和操控。
2. 支持多种转换类型，包括替换、增强、隔离和移除，以满足不同用户的个性化需求。
3. 允许用户在使用过程中提供反馈，系统据此对生成式AI模型进行微调，提高音频处理的准确性和用户满意度。
4. 支持在多个设备间同步用户账户和生成式AI模型设置，确保用户在不同设备上获得一致的音频体验。
5. 采用堆叠模型架构，可同时处理多个声音类别，实现更复杂的音频操控。
6. 数字化音频流并分割成片段进行处理，用户可选择片段的细致程度以平衡处理效率和效果。
7. 应用于游戏场景时，可帮助用户自定义游戏音效，避免不愉快的听觉体验，提升游戏沉浸感和舒适度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484422269)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260224991)**
<br/><br/>

---


<br/>

### 22. 面向盲人的照片和图像屏幕阅读器

**Title (EN)**: PHOTO AND IMAGE SCREEN READER FOR THE BLIND  
**Pub. No.**: US20260227951

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Gregory Ward RATAJIK](https://patents.google.com/?inventor=Gregory+Ward+RATAJIK&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明公开了帮助视障人士处理图像的技术。服务访问包含场景中物体的图像，图像由像素组成。服务对物体像素和场景进行分类。服务接收用户对图像的输入，包括：鼠标悬停在物体像素上、选择物体像素或鼠标在物体像素上的移动。响应用户输入，服务触发播放包含描述物体分类的音频细节的音频输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484425534_1.jpg)

**Technical Field (技术领域)**:  
图像处理与辅助技术领域，具体涉及视障用户交互式图像导航和音频描述技术。

**Background (发明背景)**:  
现有的视障用户屏幕内容辅助技术包括屏幕阅读器、图像替代文本和AI生成摘要等，但这些方法存在不足。
屏幕阅读器主要朗读控件文本，替代文本仅提供宏观描述，而AI生成摘要则缺乏交互性和细节。
因此，需要一种能够提供实时、交互式和详细图像内容描述的新方法。

**Summary (发明总览)**:  
本发明提供了一种交互式图像导航系统，通过机器学习对图像中的物体和场景进行分类。
用户可以通过鼠标或语音命令与图像进行交互，系统根据用户操作实时提供详细的音频描述。
该系统不仅能识别物体，还能理解物体间的空间关系，为用户提供像素级导航体验。
此外，系统支持图像编辑功能，如裁剪、复制等，并通过音频反馈辅助用户完成任务。
该技术还适用于机器学习应用，如视频流中的边界线定义和活动检测。

**Key Innovation (核心创新)**:  
1. 通过机器学习引擎对图像中的物体像素进行分类，并生成包含分类信息的第一元数据，实现对图像内容的精准识别。
2. 允许用户通过鼠标悬停、选择或移动操作与图像进行交互，系统根据指针位置实时提供详细的音频描述。
3. 提供像素级导航功能，用户可以精确定位图像中的物体并了解其空间关系，例如物体之间的相对位置。
4. 支持基于语音的用户指令，用户可以通过语音命令进行图像编辑操作，如裁剪指定区域的图像。
5. 集成机器学习相机参数功能，用户可以通过音频反馈精确定位并绘制边界线，用于视频流中的活动检测。
6. 音频描述不仅包含物体分类信息，还包括物体在图像中的位置和与其他物体的关系，提供更丰富的上下文信息。
7. 该技术可应用于图像编辑、辅助教学、机器学习训练等多种场景，为视障用户提供更便捷的图像处理工具。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484425534)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260227951)**
<br/><br/>

---


<br/>

### 23. 用于画廊视图中的图像堆叠技术

**Title (EN)**: TECHNIQUES FOR STACKING IMAGES IN A GALLERY VIEW  
**Pub. No.**: US20260228021

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Srinivasa Chaitanya Kumar Reddy GOPIREDDY](https://patents.google.com/?inventor=Srinivasa+Chaitanya+Kumar+Reddy+GOPIREDDY&country=US&num=100&sort=new), [John Robert Selbie](https://patents.google.com/?inventor=John+Robert+Selbie&country=US&num=100&sort=new), [Nuh Mohamed Mohamud](https://patents.google.com/?inventor=Nuh+Mohamed+Mohamud&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明描述了用于生成图像查看应用中画廊视图的图像堆叠示例。通过基于与多张图像相关联的时间戳，可以识别多张图像的多个切片。在给定切片内，可以为每张图像生成嵌入。基于比较切片内部分图像的相应嵌入，可以将切片内部分图像分组到图像堆叠中。在画廊视图中，可以显示代表图像堆叠的单一顶层图像。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484425610_1.jpg)

**Technical Field (技术领域)**:  
图像处理技术领域，具体涉及图像堆叠和智能分组技术。

**Background (发明背景)**:  
现代用户设备普遍配备摄像头，用户可以拍摄大量图像。此外，云存储服务允许用户在不同设备间备份和访问图像。然而，当用户查看存储的图像时，重复或相似的图像会导致界面杂乱，降低浏览效率。现有的图像查看应用难以有效管理和展示大量相似图像。

**Summary (发明总览)**:  
本发明提出了一种基于时间戳切片和图像嵌入相似度比较的图像堆叠方法。通过将图像按时间切片分组，并在切片内比较图像嵌入的相似度，将相似图像分组堆叠。在画廊视图中，仅显示堆叠的单一顶层图像代表整组图像，从而减少显示的图像数量，降低界面杂乱度。本发明通过智能分组和堆叠技术，提升了图像查看体验。

**Key Innovation (核心创新)**:  
1. 基于时间戳对图像进行切片，减少需要比较的图像数量，提高分组效率。
2. 在每个时间切片内，通过生成图像嵌入并比较相似度，实现图像的智能分组。
3. 采用阈值相似度检测机制，确保分组图像具有足够的视觉相似性。
4. 在画廊视图中，仅显示堆叠的单一顶层图像，代替显示所有相似图像，减少界面杂乱。
5. 提供用户手动选择顶层图像的选项，允许用户自定义堆叠图像的代表图像。
6. 在设备本地执行图像堆叠处理，避免依赖云端计算，提高处理效率和隐私保护。
7. 通过加权平均处理前景和背景嵌入，提高图像分组准确性，适用于照片管理和相册应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484425610)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260228021)**
<br/><br/>

---


<br/>

### 24. 用于加速增强现实感知的语义数据表面元素重投影技术

**Title (EN)**: SURFEL REPROJECTION OF SEMANTIC DATA FOR ACCELERATED AUGMENTED REALITY PERCEPTION  
**Pub. No.**: US20260229029

**Applicant**: GOOGLE LLC  
**Inventor**: [Eric Lee Turner](https://patents.google.com/?inventor=Eric+Lee+Turner&country=US&num=100&sort=new), [Pratibha Tripathi](https://patents.google.com/?inventor=Pratibha+Tripathi&country=US&num=100&sort=new), [Keisuke Tateno](https://patents.google.com/?inventor=Keisuke+Tateno&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明涉及在数据结构的存储中保存语义信息，这些数据结构的更新频率低于标称帧率。例如，将语义模型应用于一系列图像帧中的第一帧，以生成每像素的语义数据。同时，从第一帧图像中提取第一边缘图像以定义语义标签的边界。然后从语义数据和第一边缘图像生成第一语义图像，并将语义数据存储在数据结构中。对于序列中的第二帧图像，提取第二边缘图像，但语义数据从数据结构导出到第二边缘图像，以生成第二语义图像，而无需生成新的语义数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426726_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及视频或图像帧序列的语义图像分割技术，具体用于增强现实应用。

**Background (发明背景)**:  
在增强现实应用中，语义图像分割用于识别场景中的区域，以便放置虚拟对象。传统方法使用机器学习模型对每个像素进行语义分类，但这种方法在处理多帧图像时存在延迟问题。例如，单帧图像的语义标签生成可能需要超过100毫秒，导致实时性不足。本发明旨在解决这一问题，通过减少语义数据处理频率来提高处理效率。

**Summary (发明总览)**:  
本发明提出了一种基于表面元素（surfels）的语义数据存储和重投影方法。首先，对图像帧序列中的第一帧生成语义图像，并将其语义信息存储在数据结构中。随后，对序列中的后续帧，通过导出存储的语义信息并结合新的边缘图像生成语义图像，而无需对每个新帧重新生成语义数据。该方法通过减少语义数据处理频率，提高了处理效率，同时保持了语义图像的准确性和时间稳定性。

**Key Innovation (核心创新)**:  
1. 使用表面元素（surfels）作为语义信息的存储结构，每个surfels包含位置和表面方向信息，并在世界坐标系中保持位置数据。
2. 将第一帧图像生成的语义数据转移到surfels中，而不是逐帧更新语义信息，从而减少处理频率。
3. 通过导出surfels中的语义数据并结合新的边缘图像，生成后续帧的语义图像，避免了重复的语义数据生成。
4. 采用稀疏语义图像生成和稠密化操作，在保持高帧率的同时，确保语义图像的准确性。
5. 该方法相较于传统方法，显著降低了延迟，提高了语义图像生成的时间稳定性和精度。
6. 提供了模型输出图像分辨率的灵活性，适应不同应用场景的需求。
7. 该技术特别适用于增强现实应用，例如在导航应用中精确定位虚拟对象（如箭头）到正确的场景区域（如道路）。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426726)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229029)**
<br/><br/>

---


<br/>

### 25. 包含单轴或双轴有机固体材料的高折射率透镜

**Title (EN)**: HIGH INDEX LENS INCLUDING UNIAXIAL OR BIAXIAL ORGANIC SOLID MATERIAL  
**Pub. No.**: US20260227549

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Tingling Rao](https://patents.google.com/?inventor=Tingling+Rao&country=US&num=100&sort=new), [Xingzhou Tu](https://patents.google.com/?inventor=Xingzhou+Tu&country=US&num=100&sort=new), [Lafe Joseph Purvis, II](https://patents.google.com/?inventor=Lafe+Joseph+Purvis%2C+II&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
一种设备包括显示器和光学配置，光学配置用于接收来自显示器的显示光并将其引导至远程观看位置，其中光学配置包括一个透镜，该透镜包含光学各向异性有机固体，且有机固体包含排列的有机分子晶体。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
光学显示技术；
高折射率光学材料；
有机晶体光学器件

**Background (发明背景)**:  
光学显示系统通常需要高质量的透镜来引导和聚焦显示光。
传统透镜材料在折射率和光学性能方面存在局限性。
现有技术难以同时实现高折射率和光学各向异性。
这限制了光学系统的性能，特别是在需要精确光控制的应用中。
本发明旨在提供一种具有高折射率和光学各向异性的透镜材料。

**Summary (发明总览)**:  
本发明提出了一种包含有机分子晶体的光学透镜设计。
通过在透镜中使用单轴或双轴有机固体材料，实现了高折射率和光学各向异性。
该透镜能够更有效地控制光的传播路径和偏振状态。
相较于传统材料，本发明提供了更高的光学性能和设计灵活性。
这种透镜特别适用于需要精确光控制的光学显示系统。

**Key Innovation (核心创新)**:  
1. 采用单轴或双轴有机固体材料作为透镜核心材料，通过分子晶体排列实现高折射率。
2. 通过控制有机分子晶体的排列方向，实现对光的偏振状态和传播路径的精确控制。
3. 透镜设计结合了高折射率和光学各向异性特性，提升了光学系统的性能。
4. 使用有机材料代替传统无机材料，提供了更好的可加工性和设计灵活性。
5. 该透镜能够有效减少光学畸变，提高显示图像的清晰度和对比度。
6. 适用于增强现实（AR）、虚拟现实（VR）以及高精度光学显示设备，提供更优质的光学体验。
7. 有机材料的使用还带来了更轻的重量和更好的环境适应性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484425092)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260227549)**
<br/><br/>

---


<br/>

### 26. 飞行器的对接系统和方法

**Title (EN)**: DOCKING SYSTEMS AND METHODS FOR AERIAL VEHICLES  
**Pub. No.**: US20260227798

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Hsiao-Chieh Yen](https://patents.google.com/?inventor=Hsiao-Chieh+Yen&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
对接系统和方法包括飞行器和对接站。飞行器在对接过程中实施控制策略，以保持在与对接站相关的安全包络内，并保持对接站上表面着陆垫的可见性。此外，控制策略在飞行器保持在安全包络内且可见着陆垫的情况下，优先考虑下降速度而非水平定位。此外，接地垫可包括多组反光体和标记，以促进对接过程的执行。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484425368_1.jpg)

**Technical Field (技术领域)**:  
飞行器技术领域，具体涉及室内飞行器的对接和着陆系统。

**Background (发明背景)**:  
飞行器通常在户外空间运行，依靠GPS和IMU等传感器进行定位和导航。然而，在室内空间运行飞行器面临独特挑战，例如空间狭窄且操作区域有限，需要精确执行起飞、着陆或对接操作。此外，室内飞行器需要适应空间尺寸的服务系统，这对现有技术提出了新的要求。

**Summary (发明总览)**:  
本发明提出了一种针对室内飞行器的对接系统和方法，通过在对接站上设置带有标记的着陆垫，并采用分阶段控制策略来优化对接过程。飞行器在对接过程中需保持在安全包络内，同时保持对着陆垫的可见性。系统通过多组不同类型的标记和传感器，分阶段引导飞行器进行精确定位和对接。该方法简化了飞行器的高层控制逻辑，专注于垂直定位，同时允许底层控制器处理水平定位。

**Key Innovation (核心创新)**:  
1. 采用多组反光体和标记（如反光体、AprilTags®、QR码等）设计着陆垫，通过不同阶段的标记组合实现飞行器精确定位。
2. 设计了分阶段控制策略，在不同高度阶段使用不同类型的标记进行定位，确保飞行器在下降过程中始终保持对着陆垫的可见性。
3. 在对接站上设置可透光的保护盖，既保护着陆垫标记免受损坏，又允许特定波长的光穿透以供传感器检测。
4. 控制策略优先考虑飞行器在安全包络内的垂直运动，当接近边界时暂停或调整高度，从而提高对接过程的安全性。
5. 通过简化高层控制逻辑，将重点放在垂直定位上，同时利用底层控制器处理水平定位，简化了飞行器的控制流程。
6. 该系统特别适用于室内环境，通过适配空间尺寸的服务系统，解决了室内飞行器对接的独特挑战。
7. 该技术可应用于物流无人机、监控无人机等场景，提供安全高效的对接解决方案，提升用户体验和操作可靠性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484425368)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260227798)**
<br/><br/>

---


<br/>

### 27. 基于大语言模型预测的对话系统响应偏差技术

**Title (EN)**: LARGE LANGUAGE MODEL-PREDICTED RESPONSE BIASING FOR CONVERSATIONAL SYSTEMS  
**Pub. No.**: US20260229227

**Applicant**: Google LLC  
**Inventor**: [Petar Stanisa Aleksic](https://patents.google.com/?inventor=Petar+Stanisa+Aleksic&country=US&num=100&sort=new), [Lillian Qiaohui Zhou](https://patents.google.com/?inventor=Lillian+Qiaohui+Zhou&country=US&num=100&sort=new)  
**Publication Date**: 06.08.2026

**Abstract**:  
本发明提供了一种方法，包括在用户与助手大语言模型（LLM）的对话中接收由助手LLM生成的面向用户的响应，基于该响应预测用户后续查询中可能使用的词语，并使自动语音识别（ASR）模型偏向于识别这些预测的词语。随后接收表征用户后续查询的音频数据，并使用偏向于识别预测词语的ASR模型处理音频数据以生成后续查询的转录文本。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484426945_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及大语言模型预测的对话系统响应偏差技术，具体涉及语音对话中的自动语音识别（ASR）模型优化。

**Background (发明背景)**:  
现有的对话系统通常采用级联架构，其中自动语音识别（ASR）模型负责将用户语音转录为文本，然后LLM处理文本以生成响应。然而，ASR模型缺乏对话上下文，难以生成最准确的转录文本。尽管LLM对用户可能的语音形式有清晰预测，但ASR模型对此信息并不知情。

**Summary (发明总览)**:  
本发明通过在对话系统中引入LLM预测机制，使ASR模型能够根据LLM对用户可能输入的预测进行偏向性识别，从而提高语音识别的准确性。具体实现包括：LLM预测用户后续查询中的可能词语，ASR模型根据这些预测进行偏向性识别，并生成转录文本。本发明相较于现有技术的主要改进在于将LLM的预测能力与ASR模型结合，提升了语音识别的准确性和效率。

**Key Innovation (核心创新)**:  
1. 通过LLM预测用户后续查询中的可能词语，为ASR模型提供预测信息，从而实现对ASR模型的偏向性识别。
2. 在LLM生成响应后，系统会分析响应内容以确定用户可能的后续输入，例如识别问题中的可能答案或特定选项。
3. ASR模型的偏向性识别不仅基于LLM的预测，还结合了对话历史中的相关术语，以进一步提高识别的准确性。
4. 系统能够处理用户以“是”或“否”形式回答的二元问题，并将其作为预测词语提供给ASR模型。
5. 在转录用户后续查询后，LLM会处理转录文本以生成新的响应，从而实现对话的连续性。
6. 通过文本转语音（TTS）系统将LLM生成的响应转换为合成语音，供用户设备播放，实现完整的语音交互体验。
7. 本发明可应用于智能助手、语音控制应用等场景，提升语音交互的流畅度和准确性，尤其在复杂对话环境中表现突出。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484426945)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260229227)**
<br/><br/>

---


<br/>

### 28. 用于后置滤波器回声抑制的逐帧输入估计

**Title (EN)**: Per frame input estimation for post filter echo suppression  
**Pub. No.**: US12700418

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Karim Helwani](https://patents.google.com/?inventor=Karim+Helwani&country=US&num=100&sort=new), [Michael Mark Goodwin](https://patents.google.com/?inventor=Michael+Mark+Goodwin&country=US&num=100&sort=new), [Erfan Soltanmohammadi](https://patents.google.com/?inventor=Erfan+Soltanmohammadi&country=US&num=100&sort=new)  
**Publication Date**: 04.08.2026

**Abstract**:  
本发明确定用于后置滤波器回声抑制的逐帧输入。通过扬声器播放的远端信号的双向通信捕获音频数据可被处理为各个帧的不同子带。可以应用经过训练以接受帧的不同子带及其对应的远端音频数据帧的子带作为输入的机器学习模型，以生成可作为帧的后置滤波器输入的输出。从机器学习模型输出的后置滤波器输入可包括衰减参数、近端估计和回声估计。使用后置滤波器输入对帧的不同子带应用后置滤波器，以去除由远端音频数据引起的回声数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484410997_1.jpg)

**Technical Field (技术领域)**:  
音频处理技术领域，具体涉及回声抑制和机器学习在音频增强中的应用。

**Background (发明背景)**:  
音频增强技术已被用于改善音频通信的性能，例如提高捕获的人声的清晰度。
现有的音频增强技术通常依赖于固定的滤波器或简单的信号处理方法。
这些方法在处理复杂场景下的回声抑制时效果有限。
本发明旨在通过机器学习模型提供更精确的回声估计和抑制。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的回声抑制方法，通过逐帧处理音频数据来提高回声消除效果。
该方法将音频帧分解为多个子带，并利用机器学习模型分析这些子带以生成后置滤波器所需的参数。
通过这种方式，可以更准确地估计近端信号和回声信号，从而实现更有效的回声抑制。
相较于传统方法，本发明利用机器学习模型提高了回声估计的准确性和音频增强的效果。

**Key Innovation (核心创新)**:  
1. 采用机器学习模型对音频帧的子带进行分析，生成用于后置滤波器的参数，包括衰减参数、近端估计和回声估计。
2. 将音频数据分解为多个子带进行处理，以提高回声抑制的精度和效果。
3. 通过训练机器学习模型，使其能够接受远端音频数据和捕获音频数据的对应子带作为输入，从而实现更精确的回声估计。
4. 提供了一种动态调整后置滤波器参数的方法，以适应不同场景下的回声抑制需求。
5. 该方法能够有效去除由远端音频数据引起的回声，同时保留近端信号的质量。
6. 应用于实时通信场景，如视频会议和语音通话，可显著提升音频质量和用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484410997)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12700418)**
<br/><br/>

---


<br/>

### 29. 具有高长宽比致动器的音频换能器

**Title (EN)**: Audio transducer with high aspect ratio actuator  
**Pub. No.**: US12701365

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Alexander Victor Salvatti](https://patents.google.com/?inventor=Alexander+Victor+Salvatti&country=US&num=100&sort=new), [Wei Yang](https://patents.google.com/?inventor=Wei+Yang&country=US&num=100&sort=new), [Douglas K. Hogue](https://patents.google.com/?inventor=Douglas+K.+Hogue&country=US&num=100&sort=new)  
**Publication Date**: 04.08.2026

**Abstract**:  
本发明涉及一种设备，包括扬声器及其至少部分容纳扬声器的外壳。扬声器包括锥形振膜、围绕锥形振膜的悬边，以及具有第一表面和第二表面的音圈架，音圈架上设有平面线圈。扬声器还包括致动器，其具有靠近第一表面的第一磁体组件和靠近第二表面的第二磁体组件。第一磁体组件包括第一磁体和第二磁体，第二磁体组件包括第三磁体和第四磁体。第一柱和第二柱与音圈架连接，第一金属弹性件与第一柱连接，第二金属弹性件与第二柱连接。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484412040_1.jpg)

**Technical Field (技术领域)**:  
音频设备技术领域，具体涉及紧凑型扬声器设计。

**Background (发明背景)**:  
随着电子设备向小型化发展，设备内部空间变得有限，这对扬声器等组件的性能提出了挑战。传统扬声器由于需要移动空气来产生声音，通常体积较大，难以适应紧凑型应用。尤其是在低频声音的输出方面，当产品尺寸受限且需要达到所需音量时，问题更加突出。

**Summary (发明总览)**:  
本发明提出了一种新型扬声器设计，通过在音圈架两侧设置磁体组件，并结合金属弹性件与连接柱的配合，实现了紧凑空间内的高效声音输出。该设计通过优化磁体布局和机械结构，在有限空间内提升了扬声器的低频响应能力和整体音质表现。相较于传统扬声器，本发明在保持性能的同时显著减小了体积，更适合现代电子设备的紧凑型设计需求。

**Key Innovation (核心创新)**:  
1. 采用双面磁体布局设计，在音圈架两侧分别设置第一磁体组件和第二磁体组件，通过对称磁场分布提升扬声器的驱动效率和稳定性。
2. 使用高长宽比的磁体组件设计，在有限空间内最大化磁场强度，从而增强扬声器的低频响应能力。
3. 通过第一柱和第二柱与音圈架的连接，以及金属弹性件的配合，实现精确的机械运动控制，减少振动失真。
4. 金属弹性件的设计增强了扬声器的耐用性，同时提供了更好的振动阻尼效果，提升音质表现。
5. 该设计允许在紧凑型设备中实现高性能音频输出，特别适用于智能家居设备、便携式音响等对空间要求严格的场景。
6. 通过优化磁体布局和机械结构，在减小扬声器体积的同时，保持甚至提升了音质表现，解决了传统紧凑型扬声器性能不足的问题。
7. 本发明可应用于需要高品质音频输出且空间受限的电子设备，如智能音箱、电视机和便携式音频设备，为产品设计提供更多可能性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484412040)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12701365)**
<br/><br/>

---


<br/>

### 30. 个性化事件精彩片段音乐视频生成器

**Title (EN)**: Personalized event highlight music video generator  
**Pub. No.**: US12701306

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Avi Avraham Ben-Cohen](https://patents.google.com/?inventor=Avi+Avraham+Ben-Cohen&country=US&num=100&sort=new), [Gilad Cohen](https://patents.google.com/?inventor=Gilad+Cohen&country=US&num=100&sort=new), [Amit Adam](https://patents.google.com/?inventor=Amit+Adam&country=US&num=100&sort=new)  
**Publication Date**: 04.08.2026

**Abstract**:  
该系统从精彩片段集锦中识别出精彩片段。利用关联和个性化元数据，对精彩片段进行处理和分析，以确定其是否满足用户偏好。然后，可以将精彩片段与专门为该片段选择的音频结合，生成音乐视频并提供给用户。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484411973_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及多媒体内容处理领域，具体为基于用户偏好的个性化精彩片段生成和音乐视频合成技术。

**Background (发明背景)**:  
随着网络技术的发展，数字媒体内容变得广泛可用，用户可以通过多种设备实时观看或回放事件内容。
现有技术通常将事件分割成可识别的片段，以提供简洁的事件摘要。
然而，现有技术生成的摘要往往缺乏个性化，无法根据用户偏好进行定制。
本发明旨在解决这一问题，通过个性化处理精彩片段并生成定制化的音乐视频来提升用户体验。

**Summary (发明总览)**:  
本发明提出了一种个性化事件精彩片段音乐视频生成系统。
首先，系统从事件集锦中识别出精彩片段。
然后，利用关联数据和用户个性化数据对片段进行分析，以确定其是否符合用户偏好。
接着，系统选择合适的音频并将其与精彩片段结合，生成音乐视频。
相较于现有技术，本发明通过个性化处理和音乐视频合成，为用户提供更符合个人兴趣的观看体验。

**Key Innovation (核心创新)**:  
1. 通过分析用户偏好数据，识别符合用户兴趣的精彩片段，实现个性化内容筛选。
2. 利用关联数据对精彩片段进行深度处理，确保生成的音乐视频内容与片段主题高度匹配。
3. 将音频选择与精彩片段进行智能匹配，通过音频增强片段的情感表达和观赏性。
4. 采用自动化处理流程，减少人工干预，提高音乐视频生成效率。
5. 提供用户反馈机制，允许用户对生成的音乐视频进行评分和调整，进一步优化个性化体验。
6. 应用于体育赛事、演唱会等场景中，为用户提供定制化的精彩回顾视频，提升用户参与感和满意度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484411973)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12701306)**
<br/><br/>

---


<br/>

### 31. 图像生成中的妆容融合

**Title (EN)**: Makeup blending in image generation  
**Pub. No.**: US12700198

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Hui Pang](https://patents.google.com/?inventor=Hui+Pang&country=US&num=100&sort=new), [Sunil Sharadchandra Hadap](https://patents.google.com/?inventor=Sunil+Sharadchandra+Hadap&country=US&num=100&sort=new), [Rahul Suresh](https://patents.google.com/?inventor=Rahul+Suresh&country=US&num=100&sort=new)  
**Publication Date**: 04.08.2026

**Abstract**:  
本发明提供了一种系统和方法，用于根据输入的人脸图像生成该人脸虚拟佩戴选定妆容的图像。系统会对人脸图像进行处理，分解出人脸的阴影、高光、边界和颜色等要素。为了估算佩戴妆容后的人脸颜色，系统会估计人脸图像中皮肤和选定妆容的反射率。然后，通过结合皮肤和妆容颜色的反射率来估算佩戴妆容后的人脸颜色。最终，通过将估算出的颜色与分解出的人脸要素（如阴影和高光）结合，在人脸边界内重建出最终图像。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484410752_1.jpg)

**Technical Field (技术领域)**:  
计算机视觉，虚拟试穿技术，图像处理

**Background (发明背景)**:  
现有的虚拟试穿技术包括服装、妆容等产品应用，主要依赖于机器学习模型或基于物理的方法。机器学习模型如神经网络和生成式人工智能技术需要大量训练数据，而基于物理的方法则依赖物理规则构建虚拟试穿功能。这些方法在处理妆容融合时，可能无法准确模拟妆容与皮肤之间的光学交互，导致结果不够真实。

**Summary (发明总览)**:  
本发明提出了一种基于光学反射率分析的妆容融合技术，通过分解人脸图像的要素并估算皮肤和妆容的反射率，生成更逼真的虚拟妆容效果。该方法首先对人脸图像进行分解，提取阴影、高光、边界和颜色等要素，然后结合皮肤和妆容的反射率计算最终颜色，最后将颜色与分解的要素结合重建图像。与现有技术相比，本发明在模拟妆容与皮肤的光学交互方面更加准确，生成的虚拟妆容效果更加自然。

**Key Innovation (核心创新)**:  
1. 通过分解人脸图像的阴影、高光、边界和颜色等要素，实现对图像的精细化处理，为后续的妆容融合提供基础。
2. 采用皮肤和妆容反射率模型，精确估算佩戴妆容后的人脸颜色，解决了现有方法中光学交互模拟不准确的问题。
3. 结合分解的人脸要素和估算的颜色，通过重建技术生成最终图像，确保妆容效果的自然过渡和融合。
4. 利用反射率模型，不仅考虑了妆容的颜色，还考虑了其在不同光照条件下的表现，提高了虚拟妆容的真实感。
5. 该方法可应用于虚拟试妆应用，通过提供更逼真的妆容效果，提升用户体验，并帮助用户更准确地选择适合自己的产品。
6. 通过优化反射率计算和图像重建算法，本发明在保证效果的同时，也提高了处理速度，适用于实时应用场景。
7. 推测该技术可扩展应用于其他虚拟试穿领域，如配饰、染发等，进一步拓展其应用场景和市场价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484410752)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12700198)**
<br/><br/>

---


<br/>

### 32. 使用行为指标优化内容布局的系统和方法

**Title (EN)**: Systems and methods for optimizing content layout using behavior metrics  
**Pub. No.**: USRE050980

**Applicant**: Google LLC  
**Inventor**: [Guannan Zhang](https://patents.google.com/?inventor=Guannan+Zhang&country=US&num=100&sort=new), [Zhenguo Ou](https://patents.google.com/?inventor=Zhenguo+Ou&country=US&num=100&sort=new)  
**Publication Date**: 04.08.2026

**Abstract**:  
提供了使用行为指标优化内容布局的系统和方法。收集在客户端设备上呈现的内容项的行为数据。行为数据指示用户行为（例如点击）发生的内容项显示区域内的各个位置。行为数据用于为内容项布局方案的各个组件分配权重。在与布局方案的特定组件相关联的内容项区域内发生的用户行为会增加相应组件的权重。与布局方案的每个组件相关联的权重用于优化内容项的布局。分配了更大权重的组件被突出显示或强调。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484407031_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及互联网广告技术，具体为基于用户行为数据优化内容布局的方法。

**Background (发明背景)**:  
互联网提供了丰富多样的内容。网页和其他类型的第一方内容发布商通常通过允许赞助的第三方内容（例如广告）无缝集成来将其内容变现。程序化互联网广告系统可用于自动化选择和整合第三方内容与第一方内容。然而，第三方内容提供商会发现创建有效且吸引人的内容项具有挑战性。现有的内容布局方法难以根据用户行为动态调整布局以提高用户参与度。

**Summary (发明总览)**:  
本发明提出了一种基于用户行为数据优化内容布局的方法。通过收集用户与内容项交互的行为数据，分析用户行为发生的位置，并据此为布局方案的各个组件分配权重。系统会识别权重最大的组件并调整其显示尺寸，以突出显示用户更感兴趣的内容部分。同时，系统还会根据权重比例调整其他组件的尺寸，确保整体布局的协调性和可用空间的充分利用。

**Key Innovation (核心创新)**:  
1. 通过收集用户行为数据（如点击位置和悬停位置），实现对用户兴趣点的精准定位。
2. 基于行为数据为内容项布局方案的各个组件分配权重，量化用户对不同内容的关注度。
3. 识别权重最大的组件并动态调整其显示尺寸，确保用户感兴趣的内容获得更多展示空间。
4. 计算权重比例并相应调整次重要组件的尺寸，以保持布局的协调性和视觉平衡。
5. 在调整过程中，先将所有组件缩小至最小尺寸，再逐步增加重要组件的尺寸，避免布局混乱。
6. 针对图像和文本组件分别设定不同的最小显示尺寸（如阈值显示区域和最小字体大小），确保内容可读性。
7. 本发明可应用于互联网广告和内容展示平台，通过优化布局提高用户参与度和广告效果。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484407031)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/USRE050980)**
<br/><br/>

---


<br/>

### 33. 内容投射系统和方法

**Title (EN)**: System and method for casting content  
**Pub. No.**: US12699538

**Applicant**: GOOGLE LLC  
**Inventor**: [Shengzhi Wu](https://patents.google.com/?inventor=Shengzhi+Wu&country=US&num=100&sort=new), [Alexander James Faaborg](https://patents.google.com/?inventor=Alexander+James+Faaborg&country=US&num=100&sort=new)  
**Publication Date**: 04.08.2026

**Abstract**:  
本发明提供了一种系统和方法，用于将用户设备的内容输出传输到外部设备，并由外部设备进行输出。外部设备可通过多种方式在物理空间中检测和识别，例如基于与用户设备的先前连接、共享网络或连接设备系统、用户设备捕获的图像信息以及预先存储的用于识别外部设备的锚定信息等。外部设备的选择基于与设备相关的预先存储的配置信息，包括其输出能力等。被识别的外部设备将输出传输的内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484410020_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及内容投射技术领域，具体涉及通过用户设备与外部设备之间的智能交互实现内容投射。

**Background (发明背景)**:  
随着智能设备的普及，用户希望在不同设备间无缝共享和投射内容。然而，现有技术通常依赖复杂的用户操作来扫描、检测兼容设备并启动内容共享，这导致用户体验繁琐且效率低下。本发明旨在简化这一过程，通过智能检测和自动选择外部设备来优化内容投射体验。

**Summary (发明总览)**:  
本发明提出了一种智能内容投射方法，通过用户设备自动检测范围内的外部设备，并根据外部设备的输出能力和内容特性选择合适的设备进行投射。实现路径包括设备检测、识别和内容执行转移。相较于现有技术，本发明通过减少用户干预和智能匹配设备能力，提供了更便捷的内容投射体验。

**Key Innovation (核心创新)**:  
1. 通过用户设备的传感器（如摄像头）自动检测范围内的外部设备，无需用户手动扫描或选择。
2. 基于图像信息中的物理特征识别用户设备位置，并结合数据库中的预存信息精确定位外部设备。
3. 根据外部设备的输出能力（如分辨率、音频性能）和内容特性（如视频、音频）智能匹配最佳投射目标。
4. 在内容投射前，通过视觉或听觉方式向用户请求验证，确保操作的安全性。
5. 支持多种设备检测方式，包括先前连接设备、电磁信号检测、共享网络检测等，提高检测的可靠性和灵活性。
6. 适用于手持设备和头戴显示设备等多种用户终端，并能在网络环境下协同工作。
7. 应用于家庭娱乐、办公协作等场景，提供无缝的内容投射体验，提升用户与设备间的交互效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484410020)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12699538)**
<br/><br/>

---


<br/>

### 34. 分区自适应照明的功率预算管理

**Title (EN)**: Power budgeting for zonal adaptive illumination  
**Pub. No.**: US12701641

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Sergey Kalita](https://patents.google.com/?inventor=Sergey+Kalita&country=US&num=100&sort=new), [Danylo Dorofieiev](https://patents.google.com/?inventor=Danylo+Dorofieiev&country=US&num=100&sort=new), [Andrii Shekera](https://patents.google.com/?inventor=Andrii+Shekera&country=US&num=100&sort=new)  
**Publication Date**: 04.08.2026

**Abstract**:  
本发明提供了一种用于管理相机设备在图像捕获过程中照明的系统和方法，通过在区域的一个或多个子区域上逐帧调整照明。相机设备可与可控照明设备相关联，该设备能够基于与区域至少两个子区域相关联的独立照明属性来调整区域的照明。调整可以随着区域的变化逐帧动态进行。照明设备可以包括独立可控的照明单元，例如发光二极管（LED）阵列，其中LED阵列中的各个LED可以独立控制。当照明发生变化时，对各个LED的功率分配可以动态更新。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484412341_1.jpg)

**Technical Field (技术领域)**:  
图像捕获技术；照明控制；动态功率分配

**Background (发明背景)**:  
图像捕获设备，如视频或静态相机，常用于各种应用场景中，如安防摄像头和视频门铃。在某些情况下，这些设备依赖自然光源进行图像捕获，但自然光源可能不稳定或具有时间性变化。现有技术中，图像捕获设备通常需要与照明组件配合使用，以提供稳定的照明。然而，补充照明可能导致图像数据曝光不足或过度曝光。现有技术通常通过在不同曝光水平下捕获多张图像并将其组合来扩展动态范围，但这需要图像区域在捕获间隔内没有显著变化。

**Summary (发明总览)**:  
本发明提出了一种基于逐帧调整的分区自适应照明管理方案，通过对区域内的不同子区域独立控制照明，实现动态照明调整。系统利用可独立控制的照明单元（如LED阵列），根据图像捕获需求动态分配功率，以优化照明效果。与传统多帧曝光技术相比，本发明通过实时调整照明避免了时间延迟问题，并能在动态场景中提供更优的图像质量。

**Key Innovation (核心创新)**:  
1. 采用分区照明控制技术，将照明区域划分为多个子区域并独立控制照明强度，实现更精细的照明管理。
2. 使用可独立控制的LED阵列作为照明单元，通过动态调整各个LED的功率分配来适应场景变化。
3. 引入逐帧动态调整机制，根据每帧图像的实时需求调整照明参数，避免了传统多帧曝光技术的时间延迟问题。
4. 通过实时监测场景变化和照明需求，动态更新功率分配，确保在动态场景中保持最佳照明效果。
5. 结合图像捕获设备的曝光设置和照明调整，实现更精确的曝光控制，减少曝光不足或过度曝光的情况。
6. 适用于安防摄像头、视频门铃等需要实时图像捕获的场景，提供更稳定和高质量的图像输出。
7. 在动态场景中提供更高效的照明管理方案，延长设备使用寿命并降低能耗。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484412341)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12701641)**
<br/><br/>

---


<br/>

### 35. 用于眼动追踪系统的非远心全息光学元件

**Title (EN)**: Non-telecentric holographic optical element in an eye tracking system  
**Pub. No.**: US12699268

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jianbo Zhao](https://patents.google.com/?inventor=Jianbo+Zhao&country=US&num=100&sort=new), [Yang Yang](https://patents.google.com/?inventor=Yang+Yang&country=US&num=100&sort=new), [Peter Johnsen](https://patents.google.com/?inventor=Peter+Johnsen&country=US&num=100&sort=new)  
**Publication Date**: 04.08.2026

**Abstract**:  
一种装置、系统和方法用于支持头戴式显示器（HMD）中的眼动追踪。波导系统可定位在用户的视场范围内以及HMD的透镜组件内，以捕获从眼睛反射的光。波导系统包括配置为将光耦合入波导并引导光至出耦合光栅的全息光学元件（HOE）。HOE可配置为将多个入射光线映射到相应数量的全内反射（TIR）角度。入射光线可包括至少一些非垂直于HOE入射面的倾斜光线。HOE可具有一个视场（FOV），该视场覆盖的眼球区域至少部分位于周边区域之外。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484409720_1.jpg)

**Technical Field (技术领域)**:  
光学技术领域，具体涉及眼动追踪技术。

**Background (发明背景)**:  
眼动追踪技术使头戴式显示器能够根据用户的眼球运动或眼球方向与用户进行交互。然而，现有眼动追踪系统容易受到自然障碍的限制，例如睫毛和眼睑会遮挡眼睛的图像，从而降低眼动追踪操作的质量。

**Summary (发明总览)**:  
本发明提出了一种用于眼动追踪系统的波导系统，通过在HMD中集成非远心全息光学元件（HOE），实现对眼睛反射光的有效捕获和引导。HOE能够处理非垂直入射的光线，并通过全内反射（TIR）机制将光线引导至出耦合光栅，从而提高眼动追踪的精度和可靠性。该设计解决了现有技术中因自然障碍导致的追踪精度下降问题。

**Key Innovation (核心创新)**:  
1. 采用非远心全息光学元件（HOE），能够处理非垂直入射的光线，从而扩大了系统的视场范围。
2. HOE将入射光线映射到多个全内反射（TIR）角度，确保光线在波导内的有效传播。
3. 通过优化HOE的设计，使其能够有效捕获来自眼睛的反射光，减少睫毛和眼睑等自然障碍的影响。
4. 出耦合光栅的设计确保了光线的准确定向输出，提高了眼动追踪的精度。
5. 该系统集成在HMD的透镜组件中，实现了紧凑且高效的眼动追踪解决方案。
6. 应用于头戴式显示器中，能够提供更准确和可靠的眼动追踪功能，改善用户体验。
7. 特别适用于需要高精度眼动追踪的虚拟现实（VR）和增强现实（AR）应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484409720)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12699268)**
<br/><br/>

---



**Total Patents**: 35  
**Last Updated**: 20260808

---

The Patent Scoop Trio
