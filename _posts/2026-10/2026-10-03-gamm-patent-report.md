---
layout: post
title: "其他专利小快报 2026-10-03"
date: 2026-10-03 15:06:59 +0800
categories: 其他
---

**New Patents**: 83  

---


<br/>

### 1. 基于机器学习的运动转录和字幕生成交互支持系统

**Title (EN)**: INTERACTIVE SUPPORT SYSTEM USING MACHINE LEARNING-BASED MOTION TRANSCRIPTION AND CAPTIONING  
**Pub. No.**: US20260301321

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Andréa BRITTO MATTOS LIMA](https://patents.google.com/?inventor=Andr%C3%A9a+BRITTO+MATTOS+LIMA&country=US&num=100&sort=new), [Spencer G. FOWERS](https://patents.google.com/?inventor=Spencer+G.+FOWERS&country=US&num=100&sort=new), [Thiago VALLIN SPINA](https://patents.google.com/?inventor=Thiago+VALLIN+SPINA&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明公开了用于转录参与3D视频会议的主体动作的技术。在某些配置中，描述主体动作的字幕会叠加显示在主体的3D表示附近。此外，还可以实时计算并显示主体的物理指标，例如运动速度和运动流畅度。在一些配置中，通过分析主体的4D网格来逐帧确定主体的姿势。从姿势中获取关节坐标，并将其转换为基于文本的表示。然后，将逐帧的关节坐标文本表示与提示上下文一起提供给机器学习模型，以推断出主体动作的描述和/或物理指标。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686142_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及3D视频会议、运动捕捉和机器学习领域，具体涉及基于运动转录和字幕生成的技术。

**Background (发明背景)**:  
传统的远程医疗系统依赖于2D视频会议，但这些系统在复杂医疗场景中缺乏空间深度和沉浸感。实时体积捕捉技术，如微软的Holoportation™，虽然提供了动态的3D患者动作表示，但高分辨率的3D表示可能仍不足以提供足够的诊断信息。本发明旨在解决现有技术中信息不足的问题，通过提供更丰富的运动描述和物理指标来增强远程观察效果。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的交互支持系统，通过分析参与3D视频会议的主体的动作来生成详细的运动描述和物理指标。该系统通过逐帧分析主体的4D网格来确定姿势，并将其转换为文本表示。随后，这些文本表示与提示上下文一起输入机器学习模型，以推断出动作描述和物理指标。相较于现有技术，本发明提供了更丰富的运动信息和实时反馈的物理指标，增强了远程观察的准确性和实用性。

**Key Innovation (核心创新)**:  
1. 通过4D网格逐帧分析主体的姿势，并提取关节坐标，实现精确的运动捕捉。
2. 将关节坐标转换为基于文本的表示，为机器学习模型提供结构化的输入数据。
3. 利用机器学习模型结合提示上下文，生成对主体动作的描述，提升信息表达的语义丰富度。
4. 实时计算并显示主体的物理指标，如运动速度和流畅度，为远程观察者提供即时反馈。
5. 在3D视频会议中叠加显示动作描述字幕，增强远程观察的直观性和信息量。
6. 该技术可应用于医疗诊断、运动康复评估和运动员技能评估等多个领域，提供更全面的评估依据。
7. 通过提供详细的运动描述和物理指标，本发明能够显著提升远程医疗和运动评估的准确性和效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686142)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301321)**
<br/><br/>

---


<br/>

### 2. 从智能家居事件数据生成可操作洞察

**Title (EN)**: Generating Actionable Insights from Smart Home Event Data  
**Pub. No.**: US20260303401

**Applicant**: Google LLC  
**Inventor**: [Ignacio Robles Paiz](https://patents.google.com/?inventor=Ignacio+Robles+Paiz&country=US&num=100&sort=new), [Raymond Stepkans Strods](https://patents.google.com/?inventor=Raymond+Stepkans+Strods&country=US&num=100&sort=new), [Erin Rebecca Griffiths](https://patents.google.com/?inventor=Erin+Rebecca+Griffiths&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明描述了用于从智能家居事件数据生成可操作洞察的系统和技术。示例方法包括通过一个或多个家庭监控传感器生成家庭数据；通过机器学习模型接收家庭数据并基于家庭数据生成一个或多个相关性；基于这些相关性生成家庭操作，并通过一个或多个处理器配置家庭操作以输出给用户。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488688419_1.jpg)

**Technical Field (技术领域)**:  
智能家居技术领域，具体涉及基于人工智能的智能家居数据分析与决策系统。

**Background (发明背景)**:  
智能家居设备如门铃摄像头和智能恒温器等会产生大量数据，但并非所有数据都对用户有用。现有的智能家居系统缺乏对数据的智能分析和筛选能力，导致用户难以从海量数据中提取有价值的信息。本发明旨在解决这一问题，通过生成可操作的洞察来帮助用户更好地理解和管理家庭环境。

**Summary (发明总览)**:  
本发明通过机器学习模型对智能家居事件数据进行分析，生成用户可操作的洞察。这些洞察基于数据中的相关性，例如识别异常行为、预测潜在问题或优化家庭设备的使用。相较于传统方法，本发明利用生成式人工智能技术，使系统能够动态理解家庭场景并提供智能化的建议和操作。

**Key Innovation (核心创新)**:  
1. 利用机器学习模型对智能家居事件数据进行相关性分析，识别用户可能感兴趣的模式和行为。
2. 通过生成式人工智能技术（如大语言模型）生成可操作的洞察，例如建议用户调整设备设置或提醒潜在风险。
3. 系统能够理解智能家居设备的各种功能，并基于这些功能动态生成多样化的操作建议。
4. 允许用户通过自然语言界面与系统交互，例如通过文本或语音请求特定类型的分析或建议。
5. 系统能够处理未预先定义的情况，通过结合互联网知识理解家庭场景与设备能力之间的关系。
6. 支持自动或按需向用户展示洞察，例如通过移动设备或智能汽车界面提供实时建议。
7. 本专利可应用于智能家居管理场景，如能源优化、安全监控和设备维护，为用户提供个性化的智能家居体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488688419)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260303401)**
<br/><br/>

---


<br/>

### 3. 多媒体内容上下文搜索

**Title (EN)**: CONTEXTUAL SEARCH ON MULTIMEDIA CONTENT  
**Pub. No.**: US20260300303

**Applicant**: GOOGLE LLC  
**Inventor**: [Gökhan Hasan Bakir](https://patents.google.com/?inventor=G%C3%B6khan+Hasan+Bakir&country=US&num=100&sort=new), [Károly CSALOGÁNY](https://patents.google.com/?inventor=K%C3%A1roly+CSALOG%C3%81NY&country=US&num=100&sort=new), [Behshad Behzadi](https://patents.google.com/?inventor=Behshad+Behzadi&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明提供了一种针对多媒体内容的上下文搜索技术。方法包括提取与多媒体内容相关的实体，这些实体包括多媒体内容中一个或多个对象的特征值；基于提取的实体和与多媒体内容相关的查询中的术语生成一个或多个查询重写候选；将这些查询重写候选提供给搜索引擎；根据提供的结果集特征对查询重写候选进行评分；根据评分对查询重写候选进行排名；基于排名靠前的查询重写候选重写与多媒体内容相关的查询；并根据重写后的查询提供搜索结果集以供显示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685022_1.jpg)

**Technical Field (技术领域)**:  
多媒体内容搜索；上下文感知搜索；实时搜索优化

**Background (发明背景)**:  
随着网络多媒体内容（如流媒体视频）的普及，用户在观看内容时经常需要查询相关信息。然而，现有技术要求用户手动输入视频标题和上下文信息进行搜索，并需要进一步筛选搜索结果以找到答案。这种方式耗时且分散用户对内容的注意力，降低了用户体验。本发明旨在解决这一问题，通过自动将上下文信息整合到用户查询中并实时提供相关结果。

**Summary (发明总览)**:  
本发明提出了一种改进的多媒体内容上下文搜索方法。通过提取多媒体内容中的实体信息，并结合用户查询中的关键词，生成多个查询重写候选。这些候选通过搜索引擎进行评分和排名，最终选择最优的重写查询来获取结果集。该方法在用户消费多媒体内容时实时提供搜索结果，无需用户中断观看过程，从而提升了用户体验。

**Key Innovation (核心创新)**:  
1. 提取多媒体内容中的实体信息，包括视频中出现的对象（如人物、物品等）的特征值，为上下文搜索提供基础数据支持。
2. 基于用户查询和提取的实体信息生成多个查询重写候选，确保搜索意图与多媒体内容高度匹配。
3. 通过分析搜索引擎返回的结果集特征对查询重写候选进行评分和排名，筛选出最优查询重写方案。
4. 在用户观看多媒体内容时，实时提供基于重写查询的搜索结果，无需用户中断观看过程。
5. 提供用户隐私保护机制，允许用户选择是否存储查询信息，并控制信息收集和共享行为。
6. 该技术可应用于流媒体平台、在线教育视频和互动式多媒体内容中，提升用户获取信息的效率和准确性。
7. 通过减少用户手动搜索和筛选结果的时间，优化了观看体验，尤其适用于需要快速获取信息的场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685022)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300303)**
<br/><br/>

---


<br/>

### 4. 参数化风格化虚拟形象

**Title (EN)**: Parameterizing Stylized Avatars  
**Pub. No.**: US20260301291

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Xiaobo AN](https://patents.google.com/?inventor=Xiaobo+AN&country=US&num=100&sort=new), [Gabriele PELLEGRINI](https://patents.google.com/?inventor=Gabriele+PELLEGRINI&country=US&num=100&sort=new), [John KAHWATY](https://patents.google.com/?inventor=John+KAHWATY&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及根据特定设计语言对风格化虚拟形象进行参数化处理。通过定义适用于计算平台（如视频游戏、社交媒体或扩展现实平台）的虚拟形象的风格框架（例如设计语言），生成一组随机测试虚拟形象，并确定每个测试虚拟形象解剖特征（如眼睛、耳朵、鼻子、嘴唇）的测量值。然后，从随机组中选择符合风格框架的虚拟形象子集。基于符合风格框架的测量值，确定一组约束条件（如长度、角度、比例或范围），用于生成与计算平台相关的虚拟形象。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686110_1.jpg)

**Technical Field (技术领域)**:  
本专利属于数字虚拟形象设计领域，具体涉及基于设计语言的虚拟形象参数化生成技术。

**Background (发明背景)**:  
虚拟形象作为用户的虚拟代表，在扩展现实空间中用于表达自我或与他人互动。然而，现有虚拟形象创建工具和平台缺乏统一性和一致性，导致生成的虚拟形象可能不符合平台的视觉风格或设计语言。传统方法依赖高度详细的手动定制或缺乏美学一致性的自动化系统，难以在设计一致性上保持标准，尤其在需要生成大量虚拟形象时问题更为突出。

**Summary (发明总览)**:  
本发明提出了一种基于设计语言的虚拟形象参数化生成方法，通过定义风格框架并生成随机测试虚拟形象，测量其解剖特征并筛选符合风格框架的虚拟形象，从而确定生成虚拟形象所需的约束条件。该方法将主观艺术原则转化为可编程的数学约束，实现大规模生成视觉风格一致的虚拟形象，提升了计算机作为内容生成平台的功能效率，并解决了动态数字环境中统一设计语言的技术难题。

**Key Innovation (核心创新)**:  
1. 定义适用于特定计算平台的虚拟形象风格框架，将艺术设计语言转化为可量化的设计规范。
2. 通过生成随机测试虚拟形象并测量其解剖特征（如眼睛、耳朵、鼻子、嘴唇），构建虚拟形象特征数据库。
3. 基于风格框架筛选符合设计规范的虚拟形象子集，并提取关键测量数据作为生成约束条件。
4. 将艺术设计原则转化为可编程的数学约束，实现虚拟形象的自动化生成，确保视觉风格的一致性。
5. 提供可调整的参数范围，允许用户在不同个性化水平下生成虚拟形象，同时保持与设计语言的统一性。
6. 应用于视频游戏、社交媒体、扩展现实等场景，能够高效生成大量符合统一设计语言的虚拟形象。
7. 通过计算机技术解决大规模虚拟形象生成中的设计一致性问题，提升了内容生成平台的效率和用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686110)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301291)**
<br/><br/>

---


<br/>

### 5. 位置感知助手

**Title (EN)**: LOCATION-AWARE ASSISTANT  
**Pub. No.**: US20260304067

**Applicant**: GOOGLE LLC  
**Inventor**: [Dongeek Shin](https://patents.google.com/?inventor=Dongeek+Shin&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及用于自动化助手的空间化音频反馈的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。在一个方面，该方法包括以下操作：确定用户输入已在客户端设备上被接收，基于传感器数据识别客户端设备所在环境中的一个或多个兴趣点以及用户相对于这些兴趣点的朝向，基于处理用户输入和传感器数据识别提供与特定兴趣点相关信息的自然语言响应，根据用户相对于特定兴趣点的朝向确定用于提供自然语言响应的一个或多个空间音频参数。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488677556_1.jpg)

**Technical Field (技术领域)**:  
本发明属于智能助手技术领域，具体涉及基于空间音频和用户位置感知的智能交互技术。

**Background (发明背景)**:  
用户通过各种设备执行不同任务，这些设备包括智能手机、智能手表等，并具备助手功能。助手功能通常遵循查询和响应协议，但现有助手音频输出缺乏根据用户姿态调整环境适应性的特点，导致缺乏本地上下文和兴趣点识别。此外，现有助手音频响应缺乏空间音频参数，无法让用户感知声音来自特定方向，影响沉浸感。

**Summary (发明总览)**:  
本发明提出了一种基于位置感知的智能助手系统，通过识别用户姿态和环境中的兴趣点，并结合空间音频技术，提供更符合用户环境和姿态的音频反馈。系统利用传感器数据确定用户位置和朝向，识别兴趣点并生成相关自然语言响应，再根据用户朝向调整音频的空间参数，使用户感知到声音来自兴趣点的方向，从而提升沉浸感和交互体验。

**Key Innovation (核心创新)**:  
1. 通过传感器数据识别用户姿态和环境中的兴趣点，例如使用地理定位传感器、陀螺仪和加速度计来确定用户位置和朝向。
2. 结合电子地图（E-maps）和动态信息（如商品信息、可访问性信息）来识别与用户姿态相关的兴趣点。
3. 基于用户姿态和兴趣点生成自然语言响应，并使用空间音频参数（如双耳定向音频）进行渲染，使用户感知声音来自兴趣点的方向。
4. 通过用户姿态与兴趣点距离的动态调整音频参数，例如根据用户与兴趣点的距离调整音量、回声和混响效果。
5. 提供用户自定义设置，允许用户调整空间音频特征的预配置选项，以适应个人偏好。
6. 通过用户姿态和兴趣点信息过滤不相关的助手输出，例如抑制来自非兴趣点的信息或数字信息推送。
7. 本发明可应用于智能零售、博物馆导览和智能城市等场景，为用户提供更沉浸和个性化的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488677556)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260304067)**
<br/><br/>

---


<br/>

### 6. 用于头戴式设备的眼部和环境感知组合系统

**Title (EN)**: COMBINED EYE AND ENVIRONMENT SENSING FOR A HEAD-MOUNTED DEVICE  
**Pub. No.**: US20260299306

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Yatong An](https://patents.google.com/?inventor=Yatong+An&country=US&num=100&sort=new), [Youmin Wang](https://patents.google.com/?inventor=Youmin+Wang&country=US&num=100&sort=new), [Zhaoyu Nie](https://patents.google.com/?inventor=Zhaoyu+Nie&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种用于头戴式设备的眼部和环境感知系统使用共享光源来追踪眼球方向并确定环境中物体的距离。该头戴式设备包括一个框架、一个配置为向眼球盒区域发射光束的光源、一个配置为接收眼球盒区域反射光的第一光电探测器，以及一个配置为接收经过眼球盒区域反射后的环境反射光的第二光电探测器。连接至光电探测器的处理逻辑接收光束检测数据，并基于检测数据确定眼球盒区域中眼球部分的第一距离以及环境中一个或多个物体的第二距离。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488683927_1.jpg)

**Technical Field (技术领域)**:  
光学领域，具体涉及眼球追踪技术和环境感知技术。

**Background (发明背景)**:  
眼球追踪技术使头戴式显示器能够根据用户的眼球运动或方向与用户交互，而环境感知技术则进一步增强了用户的人工现实体验。然而，在头戴式设备中独立运行眼球追踪系统和环境感知系统会消耗更多电量、体积更大且更重。本发明旨在解决这些问题，通过整合两种感知功能来提高效率。

**Summary (发明总览)**:  
本发明提出了一种整合眼球追踪和环境感知的系统，通过共享光源和扫描机制来同时实现眼球方向追踪和环境物体距离测量。该系统利用一个光源、一个微机电系统（MEMS）镜、一个面向眼球的探测器和另一个面向场景的探测器来捕捉数据。处理逻辑接收来自探测器的数据，执行眼球的三维重建和环境物体的距离测量，从而减少功耗、减小设备体积和重量。

**Key Innovation (核心创新)**:  
1. 采用共享光源和MEMS镜扫描机制，同时实现眼球追踪和环境感知功能，简化了系统结构。
2. 通过眼向光电探测器接收眼球盒区域的反射光，实现眼球的三维重建和方向追踪。
3. 利用场景向光电探测器接收环境反射光，实现对环境中一个或多个物体的距离测量。
4. 使用两个独立的快门窗口来过滤不需要的光线，分别控制眼球和环境感知的检测时间，减少环境光干扰。
5. 整合系统减少了电池消耗、尺寸和重量，提升了头戴式设备的便携性和续航能力。
6. 该技术特别适用于虚拟现实（VR）和增强现实（AR）应用，通过精确的眼球追踪和环境感知增强用户体验。
7. 推测该系统可应用于需要高精度眼球追踪和环境感知的设备，如智能眼镜、AR/VR头戴设备等，提供更自然的人机交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488683927)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299306)**
<br/><br/>

---


<br/>

### 7. 集成向量数据库的网页浏览器

**Title (EN)**: Web Browser with Integrated Vector Database  
**Pub. No.**: US20260300422

**Applicant**: Google LLC  
**Inventor**: [Zebedee Pedersen](https://patents.google.com/?inventor=Zebedee+Pedersen&country=US&num=100&sort=new), [Yasmine Rubinovitz](https://patents.google.com/?inventor=Yasmine+Rubinovitz&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
网页浏览应用程序可以实现向量数据库以存储会话数据。该应用程序可以自动将加载的网页内容嵌入到维护多个网页会话会话数据的嵌入式数据存储中。用户可以使用简单指令查询网页浏览器。网页浏览器可以解释指令并使用嵌入式数据存储快速搜索嵌入数据的多种模式，以检索相关结果。网页浏览器可以使用机器学习模型通过在访问的网页数据内容上执行基于向量的查询来回答查询或执行其他任务。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685154_1.jpg)

**Technical Field (技术领域)**:  
机器学习；网页浏览器；向量数据库；会话数据处理

**Background (发明背景)**:  
传统的网页浏览器主要依赖本地存储和服务器交互来管理用户会话数据。这种方法在处理复杂查询和跨会话数据检索时效率较低。现有技术缺乏对会话数据的智能管理和快速检索能力，导致用户体验不佳。

**Summary (发明总览)**:  
本发明提出了一种集成向量数据库的网页浏览器，通过机器学习模型将网页内容嵌入向量空间并存储在数据库中。用户可以通过自然语言指令查询浏览器，浏览器利用向量数据库快速检索相关内容并生成响应。该方法通过预处理和后处理任务优化了机器学习模型的输入，从而提高了实时查询的效率和准确性。

**Key Innovation (核心创新)**:  
1. 实现了网页浏览器与向量数据库的集成，通过机器学习模型将网页内容嵌入向量空间，实现高效的数据存储和检索。
2. 提供了基于向量相似性搜索的查询机制，允许用户使用简单指令进行跨会话数据的快速检索。
3. 通过将会话数据预处理为嵌入表示，显著提高了数据检索的速度和准确性，支持复杂查询的实时处理。
4. 引入了轻量级工具管理器模型，用于智能地选择和调用特定任务模型，优化了任务执行的流程和效率。
5. 采用并行预处理操作，将复杂的推理任务分解为多个可并行执行的子任务，缩短了整体处理时间。
6. 通过在潜在嵌入空间中直接执行复杂操作，减少了对主机器学习模型的依赖，降低了计算资源消耗。
7. 该技术可应用于智能网页浏览助手、跨设备会话同步和个性化内容推荐等场景，提供更智能和高效的用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685154)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300422)**
<br/><br/>

---


<br/>

### 8. 用于多任务AI助手的代理元协调器

**Title (EN)**: AGENTIC META-ORCHESTRATOR FOR MULTI-TASK AI ASSISTANTS  
**Pub. No.**: US20260300782

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Xiaofeng Zhu](https://patents.google.com/?inventor=Xiaofeng+Zhu&country=US&num=100&sort=new), [Hemant Kumar](https://patents.google.com/?inventor=Hemant+Kumar&country=US&num=100&sort=new), [Yunshen Zhou](https://patents.google.com/?inventor=Yunshen+Zhou&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
示例方法、设备和计算机可读介质提供了一种利用多个代理来回答查询的人工智能（AI）助手。主机应用程序从客户端接收查询，并将查询应用于协调器以选择回答查询的代理子集。协调器对查询和包含每个代理描述以及分隔符类描述的代理描述集应用相关性排序算法。协调器可以根据与多个AI代理领域之外的上下文描述相关的分隔符类的排名，动态选择子集中代理的数量。主机应用程序将查询提供给每个选定的代理，聚合来自每个选定代理的响应，并将聚合后的响应输出给客户端。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685549_1.jpg)

**Technical Field (技术领域)**:  
人工智能领域，具体涉及多代理协作和查询处理技术。

**Background (发明背景)**:  
生成式人工智能（AI）快速发展，在人机交互方面展现出潜力，例如聊天机器人。然而，现有技术存在一些局限性，如大型语言模型（LLM）受限于训练语料库，难以提供需要最新信息的答案，可能产生幻觉或无法访问私有领域。此外，训练LLM的成本高昂，难以针对特定领域进行频繁更新。因此，需要在不增加不切实际的训练成本的情况下改进生成式AI，以解决当前信息和领域特定问题。

**Summary (发明总览)**:  
本发明提出了一种基于多代理的AI助手系统，通过协调器选择相关代理来回答用户查询。协调器使用相关性排序算法，根据代理描述和领域外上下文描述来选择代理子集。系统将查询分发给选定的代理，聚合其响应并返回给用户。该方法允许动态添加新代理，无需重新训练基础模型，并通过用户反馈不断优化响应质量。

**Key Innovation (核心创新)**:  
1. 引入协调器机制，通过相关性排序算法选择最相关的代理子集进行查询处理，避免了为每个新代理重新训练基础模型的需求。
2. 采用领域外上下文描述的分隔符类，使协调器能够识别并排除与当前查询不相关的代理，从而提高响应准确性。
3. 实现了基于元学习决策树模型的代理排序和用户反馈量化机制，持续优化AI助手的响应质量。
4. 允许在不影响基础模型的情况下动态添加新代理，降低了系统更新和维护的成本。
5. 通过多代理协作处理软件代码合规性问题，能够识别不合规代码，提高代码质量和测试效率。
6. 聚合来自多个代理的响应，利用不同代理的优势提供更全面和准确的答案。
7. 应用于AI助手产品中，能够处理复杂查询，提供最新信息和领域特定知识，同时保持高效的资源利用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685549)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300782)**
<br/><br/>

---


<br/>

### 9. 高效多模态搜索优化系统与方法

**Title (EN)**: Systems and Methods for Efficient Multimodal Search Refinement  
**Pub. No.**: US20260300380

**Applicant**: Google LLC  
**Inventor**: [Balint Miklos](https://patents.google.com/?inventor=Balint+Miklos&country=US&num=100&sort=new), [Rajan Sharad Patel](https://patents.google.com/?inventor=Rajan+Sharad+Patel&country=US&num=100&sort=new), [Severin Heiniger](https://patents.google.com/?inventor=Severin+Heiniger&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及一种用于多模态搜索优化的计算机实现方法。该方法包括从用户处获取包含一个或多个查询图像的视觉搜索查询。提供包含一个或多个响应查询图像的结果图像以及指示用户对视觉搜索查询进行优化的界面元素的搜索界面供用户显示。从用户处获取包含对视觉搜索查询优化的文本数据。通过计算系统将文本数据附加到视觉搜索查询中以获得多模态搜索查询。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685108_1.jpg)

**Technical Field (技术领域)**:  
本专利属于用户搜索优化领域，具体涉及通过文本内容优化视觉搜索以形成多模态搜索查询的技术。

**Background (发明背景)**:  
近年来，虚拟助手等应用开始为用户提供视觉搜索功能，用户可以通过提供图像作为搜索查询来获取结果。然而，仅依赖视觉搜索的应用难以准确理解用户意图，尤其是当用户意图与图像内容不完全对应时。例如，用户可能想搜索某图案而非某类服装，但现有技术难以识别这种意图。因此，需要一种允许用户优化视觉搜索查询的系统和方法。

**Summary (发明总览)**:  
本发明提出了一种通过文本优化视觉搜索的多模态搜索方法。用户提交包含一个或多个图像的视觉搜索查询后，系统会展示相关结果图像并提示用户进行优化。用户可以通过输入文本数据对搜索进行细化，系统将文本数据与视觉搜索查询结合，形成多模态搜索查询，从而提高搜索准确性和用户体验。

**Key Innovation (核心创新)**:  
1. 通过提供包含结果图像和优化提示的搜索界面，允许用户直观地理解当前搜索结果并快速进行优化。
2. 允许用户输入文本数据对视觉搜索进行细化，例如添加颜色、材质等属性，从而更准确地表达搜索意图。
3. 将文本数据与视觉搜索查询结合，形成多模态搜索查询，使搜索结果更符合用户需求。
4. 通过减少用户重新拍摄图像的需求，降低了资源消耗（如电力、计算资源、存储空间等），提升了搜索效率。
5. 适用于多种应用场景，如电子商务平台、虚拟助手等，帮助用户更高效地找到目标产品或信息。
6. 特别适用于用户对视觉搜索结果有进一步细化需求时，例如在搜索服装时指定颜色或品牌。
7. 通过多模态搜索优化，提升了搜索结果的精准度，为用户提供了更个性化的搜索体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685108)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300380)**
<br/><br/>

---


<br/>

### 10. 通过3D远程会议交互注释增强理解

**Title (EN)**: AUGMENTED UNDERSTANDING THROUGH ANNOTATION OF 3D TELECONFERENCE INTERACTIONS  
**Pub. No.**: US20260301936

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Andréa BRITTO MATTOS LIMA](https://patents.google.com/?inventor=Andr%C3%A9a+BRITTO+MATTOS+LIMA&country=US&num=100&sort=new), [Spencer G FOWERS](https://patents.google.com/?inventor=Spencer+G+FOWERS&country=US&num=100&sort=new), [Thiago VALLIN SPINA](https://patents.google.com/?inventor=Thiago+VALLIN+SPINA&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明公开了在3D远程会议期间实时高亮显示受试者身体部位的技术。在某些配置中，实时捕捉受试者的图像并生成受试者的输入网格表示。该输入网格可在远程会议期间显示给受试者。当医疗从业者讲话时，系统会识别对受试者身体部位的引用，并在输入网格的显示中高亮显示这些被识别的部位，从而清晰展示医疗从业者所指的内容。例如，如果从业者说“我需要进一步检查左脚和右肩”，则输入网格的显示将高亮显示受试者的左脚和右肩。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686821_1.jpg)

**Technical Field (技术领域)**:  
3D远程医疗技术；实时人体部位高亮显示；医疗交互增强

**Background (发明背景)**:  
传统的远程医疗系统依赖于2D视频会议，但这些系统在复杂医疗场景中缺乏空间深度和沉浸感。这种局限性在整形外科和重建手术中尤为显著，患者通常难以理解复杂的手术程序，如肿瘤切除和皮瓣重建。这些手术涉及从身体供体部位移植皮肤、血管和其他组织。如果患者无法全面理解手术过程，可能会导致困惑、焦虑和遗憾。

**Summary (发明总览)**:  
本发明提出了一种在3D远程会议中实时高亮显示受试者身体部位的技术。通过实时捕捉受试者的图像并生成其3D网格表示，系统能够在医疗从业者提及特定身体部位时，自动高亮显示这些部位。这种方法增强了医患之间的沟通效果，特别是在需要精确指示身体部位的复杂医疗场景中。本发明相较于传统2D视频会议系统，提供了更直观、更具空间感的交互方式。

**Key Innovation (核心创新)**:  
1. 通过实时捕捉受试者图像生成3D网格表示，实现对受试者身体部位的精确建模。
2. 利用自然语言处理技术识别医疗从业者对话中提到的身体部位，并将其与3D网格模型进行匹配。
3. 在3D网格显示中高亮显示被提及的身体部位，使患者能够直观理解医疗从业者的指示。
4. 系统支持实时交互，确保高亮显示与医疗从业者的讲话内容同步，提升沟通效率。
5. 采用先进的3D渲染技术，确保高亮显示效果清晰且不干扰整体视觉效果。
6. 该技术特别适用于整形外科和重建手术等复杂医疗场景，帮助患者更好地理解手术过程。
7. 通过增强医患沟通，本发明可减少患者的困惑和焦虑，提高医疗服务的满意度和效果。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686821)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301936)**
<br/><br/>

---


<br/>

### 11. 具有触觉振动调谐功能的计算设备

**Title (EN)**: COMPUTING DEVICE WITH HAPTIC VIBRATION TUNING  
**Pub. No.**: US20260299692

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Amnon Dan FREIDLIN](https://patents.google.com/?inventor=Amnon+Dan+FREIDLIN&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种具有触觉调谐功能的计算设备包括配置为发出触觉振动的触觉马达、存储指令的存储器以及配置为执行指令以执行各种功能的处理器。该计算设备执行配置为控制触觉马达并调整要发出的触觉振动的触觉引擎，接收包括触觉振动声音音调在内的触觉参数，将音调转换为振动频率值，并控制触觉马达以该振动频率值发出触觉振动，从而使触觉振动的音调与音调匹配。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684352_1.jpg)

**Technical Field (技术领域)**:  
触觉反馈技术领域，具体涉及触觉振动与声音音调同步调谐。

**Background (发明背景)**:  
许多计算设备，特别是可穿戴或手持设备，如智能手机，都配备了触觉单元以产生触觉振动。这些振动用于提供通知、反馈或沉浸式体验。然而，现有技术中，触觉振动的频率会产生不同的可听嗡嗡声，这些声音可能与设备播放的音频提示不协调。此外，在用户已经处于繁忙和混乱的环境中时，额外的噪音可能使用户对传达的信息不敏感。

**Summary (发明总览)**:  
本发明提供了一种具有触觉调谐功能的计算设备，通过触觉引擎控制触觉马达并调整触觉振动。其核心思路是将触觉振动的音调与目标音调匹配，通过接收触觉参数并将其转换为振动频率值来实现。这种方法解决了现有技术中触觉振动产生的噪音与设备音频提示不协调的问题，从而提供更和谐的用户体验。

**Key Innovation (核心创新)**:  
1. 通过触觉引擎接收触觉振动的音调参数，并将其转换为振动频率值，实现触觉振动与音调的精确匹配。
2. 处理器执行指令以控制触觉马达按照转换的振动频率值发出触觉振动，确保触觉反馈与音频提示的协调性。
3. 解决了现有技术中触觉振动产生的可听噪音与设备音频提示不协调的问题，提升了用户体验。
4. 通过调整触觉振动的频率值，使用户能够更清晰地感知触觉反馈，避免在嘈杂环境中信息传达的干扰。
5. 该技术可应用于智能手机、可穿戴设备等便携式计算设备，提供更精准和舒适的触觉反馈。
6. 通过触觉与音频的同步调谐，增强了用户对设备通知和反馈的感知能力，特别是在多任务处理或嘈杂环境中。
7. 推测该技术可应用于虚拟现实和增强现实设备，提供更沉浸式的触觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684352)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299692)**
<br/><br/>

---


<br/>

### 12. USB-C 连接器

**Title (EN)**: USB-C Connector  
**Pub. No.**: US20260302687

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Cameron Delaney LOCHER](https://patents.google.com/?inventor=Cameron+Delaney+LOCHER&country=US&num=100&sort=new), [Jazmine HOYLE](https://patents.google.com/?inventor=Jazmine+HOYLE&country=US&num=100&sort=new), [Thomas Joseph LONGO](https://patents.google.com/?inventor=Thomas+Joseph+LONGO&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明主要涉及设备与线缆之间的USB-C连接。示例设备包括一个包含多个表面并共同定义一个体积的外壳。设备还包括一个位于该体积内并凹入单个表面后方的USB-C插座。该凹入的USB-C插座包含符合USB-C标准的引脚排列。示例还包括一个穿过单个表面延伸至凹入USB-C插座的漏斗结构。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488687634_1.jpg)

**Technical Field (技术领域)**:  
本发明属于USB-C连接器技术领域，具体涉及带有磁性功能的USB-C连接器及其线缆设计。

**Background (发明背景)**:  
USB-C连接器因其通用性和数据传输能力被广泛使用，但现有技术中，USB-C连接器依赖于机械固定，容易因意外拉扯而损坏设备或连接器。
同时，市场上存在一些专有的磁性连接方案，虽然提供了便捷的连接和断开功能，但这些方案需要专用充电器，限制了通用性。
本发明旨在解决上述问题，在保持USB-C通用性的同时，提供磁性连接功能。

**Summary (发明总览)**:  
本发明提出了一种结合磁性连接功能的USB-C连接方案，通过在USB-C端口上集成磁性吸引机制，并设计相应的磁性USB-C插头，实现便捷的连接和断开功能。
该方案通过在USB-C线缆端集成磁性插头，并在设备端设计兼容标准USB-C的磁性漏斗端口，实现了即插即用和意外情况下的快速断开。
该方案无需额外配件或转换器即可实现磁性连接，同时保留了标准USB-C连接的所有功能。

**Key Innovation (核心创新)**:  
1. 在USB-C端口上集成磁性漏斗结构，使其能够吸引磁性USB-C插头，实现便捷的磁性连接和断开功能。
2. 设计了带有锥形结构的磁性USB-C插头，确保插头与端口的精确对齐，并提供更好的用户体验。
3. 磁性漏斗端口完全兼容标准USB-C连接器，用户可以选择使用传统USB-C插头或磁性插头。
4. 通过在USB-C线缆端集成磁性插头，将磁性功能从设备端转移到线缆端，避免了对设备内部空间的额外占用。
5. 磁性断开机制在意外拉扯情况下可快速断开连接，保护设备免受损坏。
6. 该方案可应用于笔记本电脑、电源适配器等多种设备，为用户提供更安全、更便捷的连接体验。
7. 实现了在保持USB-C通用性的同时，提供磁性连接功能，解决了传统USB-C连接器易损坏的问题。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488687634)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260302687)**
<br/><br/>

---


<br/>

### 13. 对话中个性化声音定位的系统和方法

**Title (EN)**: Systems and Methods for Personalized Sound Localization in a Conversation  
**Pub. No.**: US20260301745

**Applicant**: Google LLC  
**Inventor**: [Dimitri Kanevsky](https://patents.google.com/?inventor=Dimitri+Kanevsky&country=US&num=100&sort=new), [Artem Dementyev](https://patents.google.com/?inventor=Artem+Dementyev&country=US&num=100&sort=new), [Sagar Savla](https://patents.google.com/?inventor=Sagar+Savla&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种示例方法包括从第一和第二音频输入设备接收第一和第二音频信号。第一和第二音频信号对应于两个参与者之间的对话语音输入。该方法包括基于第一和第二音频信号估计语音输入到达第一和第二音频输入设备的时间延迟。该方法包括基于到达时间的估计时间延迟估计两个音频源的方向。该方法包括基于两个音频源估计的方向，将对话的语音转文本记录的相应部分与相应参与者关联。该方法包括基于关联显示修改后的对话语音转文本记录，该记录标记了与相应参与者相关联的语音转文本记录的相应部分。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686609_1.jpg)

**Technical Field (技术领域)**:  
音频处理技术领域，具体涉及多麦克风阵列的声音定位和语音分离技术。

**Background (发明背景)**:  
现代计算设备通常具备语音识别能力，但现有技术难以区分多个中的多个说话者，且在嘈杂环境中性能不佳。现有语音转文本方法无法有效识别不同说话者，导致转录内容混乱。此外，实时语音识别对计算资源要求高，难以在移动设备上实现高效处理。

**Summary (发明总览)**:  
本发明提出了一种基于多麦克风阵列的声音定位和个性化语音识别方法。通过估计声音到达不同麦克风的时间差来确定声源方向，并结合个性化声学模型进行说话者分离和语音转文本。相较于传统方法，本发明能够在低计算资源条件下实现实时、准确的说话者区分，并提供视觉化的对话转录展示，提升了语音识别在移动设备上的实用性和准确性。

**Key Innovation (核心创新)**:  
1. 利用TDOA（到达时间差）技术，通过双麦克风实现180度范围内的声源定位，无需额外硬件。
2. 结合声音定位和个性化声学模型（如d-vector或说话者嵌入），实现对不同说话者的准确分离和识别。
3. 采用低延迟的波束成形算法，在移动设备上实现实时音频处理，提升嘈杂环境下的语音识别准确率。
4. 通过麦克风阵列信号处理技术，将不同说话者的语音在转录文本中视觉化区分，并显示其空间位置。
5. 提供用户选择特定声源的功能，实现选择性语音增强和背景噪声抑制。
6. 在不依赖网络连接的情况下，通过本地化处理保障用户隐私，同时实现高准确度的语音转文本。
7. 应用于实时语音转文本应用，为听力障碍者、语言学习者或会议记录提供更清晰、易于理解的对话转录。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686609)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301745)**
<br/><br/>

---


<br/>

### 14. 基于多模态嵌入和生成式人工智能模型的基于位置响应的生成

**Title (EN)**: GENERATING LOCATION-BASED RESPONSES BASED ON MULTIMODAL EMBEDDINGS AND GENERATIVE ARTIFICIAL INTELLIGENCE (AI) MODELS  
**Pub. No.**: US20260300300

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ming TAN](https://patents.google.com/?inventor=Ming+TAN&country=US&num=100&sort=new), [Hamideh REZAEE](https://patents.google.com/?inventor=Hamideh+REZAEE&country=US&num=100&sort=new), [Pak Kiu CHUNG](https://patents.google.com/?inventor=Pak+Kiu+CHUNG&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明描述了一种基于位置的响应系统，该系统利用多模态嵌入和生成式人工智能（AI）模型来生成针对用户查询的基于位置的响应。例如，该系统接收来自客户端设备的实时图像、实时位置数据和用户查询，并基于实时图像和实时位置数据在多模态向量嵌入空间中确定多模态嵌入。然后，将多模态嵌入与从客户端设备接收的数据一起提供给生成式AI模型，并指示其生成用户查询响应。接收到生成式AI模型的响应后，系统可将其提供给客户端设备。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685019_1.jpg)

**Technical Field (技术领域)**:  
人工智能；多模态数据处理；基于位置的智能服务

**Background (发明背景)**:  
基于位置的服务已成为现代技术的重要组成部分，利用地理空间数据为用户提供广泛的服务和信息。然而，现有系统在提供基于位置的响应时仍面临挑战，例如无法充分理解位置数据的细微差别，导致响应不准确或需要额外查询。此外，缺乏来自多个来源的丰富位置上下文信息也会影响导航辅助的准确性。

**Summary (发明总览)**:  
本发明提出了一种基于位置的响应系统，通过结合多模态嵌入和生成式AI模型来生成更准确、更具视觉引导性的位置响应。该系统接收实时用户输入（如查询、位置数据和图像），并利用这些数据生成多模态嵌入。随后，系统将这些信息提供给生成式AI模型，以生成受视觉信息影响的位置响应。与现有技术相比，本发明通过提供更丰富的上下文信息，提高了生成响应的效率和准确性，特别是在导航和位置识别方面。

**Key Innovation (核心创新)**:  
1. 利用多模态嵌入技术，将实时图像、位置数据和用户查询融合为一个综合向量表示，从而捕捉更丰富的上下文信息。
2. 通过生成式AI模型处理多模态嵌入，生成基于位置的响应，使系统能够提供更准确、更具视觉引导性的导航建议。
3. 在导航过程中，系统使用实时图像与多模态嵌入进行对比，以确认用户是否沿正确方向行进，并在必要时提供视觉校正。
4. 系统能够识别用户当前位置并提取相应的多模态嵌入，从而避免生成式AI模型在识别地理位置时消耗大量计算资源。
5. 通过提供多模态嵌入，生成式AI模型可以更高效地生成响应，因为它可以直接利用嵌入中的上下文信息，而无需额外查询外部数据源。
6. 在本地导航场景中，系统提供基于视觉的导航指令，使用户更容易理解方向，尤其是在不熟悉的环境中。
7. 该系统可应用于智能导航、虚拟助手和增强现实等领域，为用户提供更直观、更精准的位置信息服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685019)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300300)**
<br/><br/>

---


<br/>

### 15. 使用框架执行操作对话

**Title (EN)**: USING FRAMES FOR ACTION DIALOGS  
**Pub. No.**: US20260300421

**Applicant**: GOOGLE LLC  
**Inventor**: [David P. Whipp](https://patents.google.com/?inventor=David+P.+Whipp&country=US&num=100&sort=new), [David Kliger Elson](https://patents.google.com/?inventor=David+Kliger+Elson&country=US&num=100&sort=new), [Shir Judith Yehoshua](https://patents.google.com/?inventor=Shir+Judith+Yehoshua&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及使用框架执行任务的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。方法包括：接收执行任务的第一请求，该请求包含用户语音以识别任务；生成与任务相关联的框架，其中框架包含执行任务所需的一个或多个类型的值，每个类型的值可由相应的值满足；接收提供与问题相关信息的第二请求，该请求包含用户语音以识别问题；向搜索引擎提供识别问题的信息，并接收识别一个或多个术语的响应；确定至少一个术语可以满足执行任务所需的值的类型；并将至少一个术语存储在框架中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685153_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及语音驱动的任务执行和对话管理。

**Background (发明背景)**:  
传统移动设备通常配备语音识别软件，用于响应用户指令，如拨打电话、发送短信或搜索信息。然而，现有技术难以理解用户对话中的上下文关联性，尤其在多轮对话中难以有效关联问题和答案以完成任务。本发明旨在解决这一问题，通过引入框架机制来更好地理解用户意图并执行相关任务。

**Summary (发明总览)**:  
本发明提出了一种基于框架的任务执行方法，通过对话管理实现任务相关信息的收集和整合。用户提出任务请求后，系统生成一个任务框架，并在后续对话中收集所需信息。系统能够理解用户提出的问题与任务之间的关系，并利用搜索结果或用户数据来回答问题，从而完成任务的执行。这种方法提高了系统对用户意图的理解能力，并优化了多轮对话中的信息处理流程。

**Key Innovation (核心创新)**:  
1. 通过生成任务框架来组织和管理任务执行所需的信息，框架包含任务执行所需的各种类型的值。
2. 在用户提出与任务相关的问题时，系统能够识别问题并将其与任务关联，从而理解问题的上下文。
3. 利用搜索引擎或用户数据来回答用户问题，并将答案中的关键术语与任务框架中的值类型进行匹配。
4. 通过概率过滤机制评估关键术语与任务值的匹配度，并根据阈值进行筛选，以提高匹配的准确性。
5. 在多轮对话中，系统能够处理用户提出的具有不同含义的术语，并通过消歧问题引导用户选择正确的含义。
6. 系统能够根据用户确认更新任务框架，并最终执行任务，例如创建日历事件或发送信息。
7. 本专利可应用于智能助手、语音交互设备等场景，提供更智能、更精准的任务执行能力，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685153)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300421)**
<br/><br/>

---


<br/>

### 16. 生成模型处理的对话上下文

**Title (EN)**: DIALOG CONTEXT FOR GENERATIVE MODEL PROCESSING  
**Pub. No.**: US20260301737

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Ravi Kumar Herunde Prakash](https://patents.google.com/?inventor=Ravi+Kumar+Herunde+Prakash&country=US&num=100&sort=new), [Austin Jia-Enn Liou](https://patents.google.com/?inventor=Austin+Jia-Enn+Liou&country=US&num=100&sort=new), [Genna Michelle Krecicki Moderhack](https://patents.google.com/?inventor=Genna+Michelle+Krecicki+Moderhack&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明描述了一种技术，使用户无需明确请求即可恢复用户与系统的对话。系统通过确定接收到的用户输入与涉及该用户的用户-系统对话的语义相似性来决定处理方式。如果系统确定用户输入与任何存储的对话在语义上不相似，则系统将不使用对话作为上下文来处理用户输入。相反，如果系统确定用户输入与存储的对话在语义上相似，则系统将在处理用户输入时使用该语义相似的对话作为上下文。如果系统确定用户输入与多个存储的对话在语义上相似，则系统将请求用户选择其中一个语义相似的对话以用作上下文。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686600_1.jpg)

**Technical Field (技术领域)**:  
自然语言处理，生成模型，对话系统

**Background (发明背景)**:  
自然语言处理系统已经发展到人类可以通过语音和自然语言文本与计算设备进行交互。然而，现有系统在处理多轮对话时，难以有效识别和利用对话历史信息，导致用户体验不佳。此外，用户在不同设备上恢复对话时，现有系统通常无法提供连贯的上下文支持。

**Summary (发明总览)**:  
本发明提出了一种基于语义相似性的对话恢复机制，使用户能够自然地恢复与系统的对话。系统通过比较用户输入与存储对话的语义表示，确定是否需要使用对话上下文进行处理。如果存在多个相似对话，系统会请求用户选择具体恢复哪一个对话。通过这种方式，系统能够在多轮对话中保持上下文连贯性，并支持跨设备恢复对话。

**Key Innovation (核心创新)**:  
1. 通过计算用户输入与存储对话的语义相似性，确定是否需要使用对话上下文进行处理。
2. 使用对话嵌入（dialog embeddings）来表示对话的语义信息，从而实现高效的相似性比较。
3. 在用户输入与多个对话语义相似时，系统会请求用户选择具体恢复哪一个对话，以避免歧义。
4. 支持跨设备恢复对话，用户可以使用不同的设备继续之前的对话，而无需重新启动。
5. 通过生成对话摘要嵌入（dialog summary embeddings），系统能够快速定位相关对话并更新对话摘要。
6. 将对话摘要嵌入与用户标识关联，确保用户在不同设备上都能访问到相同的对话上下文。
7. 本发明可应用于智能助手、客服系统等场景，提供更自然和连贯的用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686600)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301737)**
<br/><br/>

---


<br/>

### 17. 优化整体编辑向量以实现目标表情照片编辑效果

**Title (EN)**: OPTIMIZATION OF OVERALL EDITING VECTOR TO ACHIEVE TARGET EXPRESSION PHOTO EDITING EFFECT  
**Pub. No.**: US20260301464

**Applicant**: Google LLC  
**Inventor**: [Maciej Pesko](https://patents.google.com/?inventor=Maciej+Pesko&country=US&num=100&sort=new), [Yunyingying Xu](https://patents.google.com/?inventor=Yunyingying+Xu&country=US&num=100&sort=new), [Ronald Thomas Votel](https://patents.google.com/?inventor=Ronald+Thomas+Votel&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及使用机器学习模型处理数据的方法、系统及设备，包括编码在计算机存储介质上的计算机程序，用于自动生成特定目标表情照片效果的数据集。在一个方面，系统接收多个图像对，每个图像对包含一个原始人脸图像和一个代表目标表情照片编辑效果的表达人脸图像，生成一个初始整体编辑向量，其中生成初始整体编辑向量包括使用样式空间编码器模型处理每个图像对，以在嵌入空间中生成原始人脸图像和表达人脸图像的嵌入，然后根据一个或多个优化标准优化初始整体编辑向量，生成优化后的整体编辑向量。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686301_1.jpg)

**Technical Field (技术领域)**:  
本专利属于人工智能和计算机视觉领域，具体涉及基于机器学习生成目标表情照片编辑效果的技术。

**Background (发明背景)**:  
传统上，生成目标表情照片数据集需要依赖人工编辑大量原始图像，这既耗时又费力。现有的生成对抗网络（如StyleClip和DragGAN）虽然可以生成表情变化，但需要用户进一步编辑或交互，难以实现自动化和规模化处理。本发明旨在解决这一问题，通过自动生成优化后的整体编辑向量，实现目标表情照片效果的自动化生成。

**Summary (发明总览)**:  
本发明提出了一种自动化生成目标表情照片数据集的方法。该方法通过接收包含原始人脸图像和表达人脸图像的图像对，使用样式空间编码器生成嵌入，并优化整体编辑向量，最终生成具有目标表情的照片。相较于传统方法，本发明无需人工干预即可生成高质量的目标表情数据集，并可应用于多种原始图像，实现规模化处理。

**Key Innovation (核心创新)**:  
1. 通过样式空间编码器模型处理图像对，生成原始图像和表达图像的嵌入，实现对目标表情的精确捕捉。
2. 基于优化标准（如图像清晰度、伪影存在和预期面部过渡）优化整体编辑向量，确保生成的照片质量。
3. 采用可调损失模型，允许用户通过直接反馈控制优化过程，实现更灵活的目标表情生成。
4. 利用超参数搜索自动调整损失权重参数，提高优化过程的自动化程度和效率。
5. 生成的整体编辑向量具有通用性，可应用于大量原始图像，显著减少人工编辑工作量。
6. 适用于边缘设备上的资源受限模型，通过高质量训练数据集实现实时、高保真度的目标表情生成。
7. 实现了目标表情数据集生成的规模化处理，可并行部署多个管道，显著提高处理效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686301)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301464)**
<br/><br/>

---


<br/>

### 18. 屏幕视觉内容的自动化上下文洞察

**Title (EN)**: AUTOMATED CONTEXTUAL INSIGHTS FOR ON-SCREEN VISUAL CONTENT  
**Pub. No.**: US20260299972

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Medhaj Suresh ATHILKAR](https://patents.google.com/?inventor=Medhaj+Suresh+ATHILKAR&country=US&num=100&sort=new), [Yan YAN](https://patents.google.com/?inventor=Yan+YAN&country=US&num=100&sort=new), [Benjamin Bear STOLOVITZ](https://patents.google.com/?inventor=Benjamin+Bear+STOLOVITZ&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本文所述技术提供了一种系统，用于主动输出与屏幕视觉内容（如文本和图像）的上下文相关的信息。人工智能系统的最新发展使得各种用户生产力工具得以实现，这些工具简化了计算设备（如笔记本电脑、智能手机、平板电脑）的用户体验。然而，由于用户可能觉得技术负担过大，即使这些工具非常有用，一些用户也可能不会利用人工智能生产力工具。因此，本系统通过内容捕获主动提取屏幕内容以供计算模型（例如生成语言模型）分析，以响应用户活动触发器。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684660_1.jpg)

**Technical Field (技术领域)**:  
人工智能，用户界面技术，自动化内容分析

**Background (发明背景)**:  
现代生活中，用户通过计算设备完成工作、学习、计划旅行或在线购物等任务，使用各种软件应用处理不同任务。然而，用户可能难以追踪特定时刻的活动及其上下文。现有的软件功能，如浏览历史或最近文件列表，缺乏记录上下文和理解用户意图的能力，导致用户需要手动搜索和回忆信息，这既耗时又容易出错。

**Summary (发明总览)**:  
本发明提出了一种系统，通过分析屏幕内容，主动为用户提供与其当前上下文相关的洞察。系统通过内容捕获提取屏幕上的视觉内容，并使用计算模型（如多模态生成AI模型、大型语言模型或小型语言模型）进行处理，以识别语义内容。系统根据用户活动触发器自动调用计算模型，并提供相关的后续输入和输出建议，从而在用户界面上直观呈现信息，提升用户体验。

**Key Innovation (核心创新)**:  
1. 通过内容捕获技术主动提取屏幕上的视觉内容，包括文本、图像、音频和多媒体内容，确保对用户活动进行准确记录。
2. 利用计算模型（如多模态生成AI模型）分析内容捕获的语义内容，识别屏幕上的具体信息及其关联概念。
3. 根据用户活动触发器（如打开特定应用或暂停打字）自动调用计算模型，减少用户的技术负担，无需用户手动操作。
4. 生成与屏幕内容语义相关的后续输入和输出，例如针对特定问题的建议或答案，并将其与内容捕获一起呈现在用户界面上。
5. 提供基于共享属性的内容捕获组织方式，例如按主题或应用分类，使用户能够轻松浏览和搜索历史活动。
6. 针对不熟悉AI工具的用户设计系统，降低技术门槛，使技术倾向较低的用户也能享受AI带来的便利。
7. 应用于用户活动回顾、邮件撰写辅助、在线购物等场景，帮助用户快速获取所需信息并提高任务完成的效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684660)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299972)**
<br/><br/>

---


<br/>

### 19. 联合声学回声消除（AEC）和个性化噪声抑制（PNS）

**Title (EN)**: Joint Acoustic Echo Cancellation (AEC) and Personalized Noise Suppression (PNS)  
**Pub. No.**: US20260301758

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Sefik Emre ESKIMEZ](https://patents.google.com/?inventor=Sefik+Emre+ESKIMEZ&country=US&num=100&sort=new), [Takuya YOSHIOKA](https://patents.google.com/?inventor=Takuya+YOSHIOKA&country=US&num=100&sort=new), [Huaming WANG](https://patents.google.com/?inventor=Huaming+WANG&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种数据处理系统实现了接收与参与在线通信会议的第一计算设备相关联的远端信号，以及接收与参与在线通信会议的第二计算设备相关联的近端信号。近端信号包括目标说话人的语音、第一干扰说话人的语音以及回声信号。该系统进一步实现了将远端信号、近端信号和目标说话人的指示作为输入提供给机器学习模型。该机器学习模型经过训练以分析远端信号和近端信号，执行个性化噪声抑制（PNS）以去除一个或多个干扰说话人的语音，并执行声学回声消除（AEC）以去除回声。模型输出包含目标说话人语音的音频信号。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686624_1.jpg)

**Technical Field (技术领域)**:  
通信技术领域，具体涉及在线音频/视频会议中的声学回声消除和个性化噪声抑制技术。

**Background (发明背景)**:  
在线音频和视频会议平台已成为重要的通信工具，但声学回声和背景噪声会降低音频质量。声学回声是由于远端用户的语音被近端用户的设备捕获并回放，导致远端用户听到自己语音的回声。背景噪声包括其他人的语音，通信平台的语音处理模型难以区分目标用户和背景中其他人的语音。现有的无条件语音增强模型无法有效区分通信参与者和背景中的其他说话人，可能导致隐私问题。

**Summary (发明总览)**:  
本发明提出了一种联合声学回声消除（AEC）和个性化噪声抑制（PNS）的技术方案，通过机器学习模型同时处理回声和背景噪声。该模型利用用户注册数据提取说话人嵌入向量，从音频信号中过滤掉其他音频源。其主要创新点在于模型能够同时执行AEC和PNS，且无需为每个用户单独训练。模型通过少量用户音频数据进行个性化，适应性强，适用于实时全双工通信。

**Key Innovation (核心创新)**:  
1. 提出了一个联合AEC和PNS的机器学习模型架构，通过单一模型同时处理回声和背景噪声，简化了传统需要多个独立模型的处理流程。
2. 利用用户注册数据提取说话人嵌入向量，实现对目标说话人的精准语音分离和回声消除。
3. 模型训练过程中使用包含多说话人的数据集，使其能够对未在训练数据中的说话人同样表现良好，提升了泛化能力。
4. 通过少量用户音频数据（称为注册数据）进行个性化适配，无需为每个用户重新训练模型，节省了计算资源。
5. 模型体积小，计算和内存需求低，支持实时音频信号处理，适用于全双工通信场景。
6. 有效解决了传统无条件语音增强模型无法区分目标用户和背景说话人的问题，避免了隐私泄露风险。
7. 应用于远程办公和在线会议场景，能够显著提升音频质量，提供更清晰、更专注的通信体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686624)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301758)**
<br/><br/>

---


<br/>

### 20. 具有跨确认功能的联合连接等时流通信

**Title (EN)**: Joint Connected Isochronous Stream Communication with Cross Acknowledgement  
**Pub. No.**: US20260303302

**Applicant**: Google LLC  
**Inventor**: [Daniel Barros](https://patents.google.com/?inventor=Daniel+Barros&country=US&num=100&sort=new), [Sunil Kumar](https://patents.google.com/?inventor=Sunil+Kumar&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及短距离无线通信的各种配置。一对真无线耳塞中的一个耳塞可以接收发往另一耳塞的音频数据包。在真无线耳塞与传输音频数据包的音频源之间可能存在一个连接等时组（CIG）内的单一连接等时流（CIS）。该耳塞可以向另一耳塞发送跨确认信号以指示接收到音频数据包。该耳塞还可以在发送跨确认信号后向另一耳塞传输音频数据包中的音频数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488688312_1.jpg)

**Technical Field (技术领域)**:  
短距离无线通信技术领域，具体涉及真无线耳塞间的音频数据传输与确认机制。

**Background (发明背景)**:  
短距离无线通信技术（如蓝牙）日益普及，用户对高质量音频体验的需求不断提高。现有技术面临的主要挑战包括通信带宽有限和包丢失问题，这可能导致音频中断，影响用户体验。现有方案中，单个耳塞若未成功接收音频包，需直接向音频源请求重传，但可能因信号衰减或干扰导致重传失败，增加功耗并降低电池寿命。

**Summary (发明总览)**:  
本发明提出了一种新型真无线耳塞通信方案，通过在两个耳塞之间建立联合连接等时流（CIS），实现音频数据的协同传输与确认。当一个耳塞未成功接收音频包时，另一耳塞可作为中继，将音频数据直接转发给该耳塞，从而避免对音频源的重复请求重传。这种方法不仅提高了通信可靠性，还优化了功耗管理。

**Key Innovation (核心创新)**:  
1. 通过单一CIS在CIG内传输包含双耳音频数据的音频包，实现音频源与单个耳塞（主耳塞）通信。
2. 另一耳塞（隐藏耳塞）通过监听主耳塞接收的音频包，提取对应自身音频通道的数据。
3. 当主耳塞未成功接收音频包时，隐藏耳塞可向主耳塞直接转发相关音频数据，避免音频源重传失败。
4. 主耳塞基于隐藏耳塞的跨确认信号向音频源发送确认，即使自身未成功接收音频包也能完成确认流程。
5. 隐藏耳塞存储主耳塞的加密凭证，用于解密仅发往主耳塞的音频包。
6. 隐藏耳塞可基于解密后的音频数据驱动自身扬声器输出音频，实现双耳音频同步。
7. 该方案适用于真无线耳塞通信场景，在弱信号环境下提供更可靠的音频传输，并有效降低功耗。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488688312)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260303302)**
<br/><br/>

---


<br/>

### 21. 基于表情符号驱动的会议智能AI摘要生成

**Title (EN)**: EMOJI-DRIVEN INTELLIGENT AI SUMMARIES FOR MEETINGS  
**Pub. No.**: US20260303393

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Mrinal Kumar SHARMA](https://patents.google.com/?inventor=Mrinal+Kumar+SHARMA&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明利用会议中的表情符号反应动态生成AI增强的会议摘要，这些摘要能够捕捉讨论的内容和情感。该方法优先考虑关键要点，突出需要澄清或采取行动的领域，并根据角色特定的反馈定制见解。通过将情感分析整合到会议摘要中，本发明确保了团队更好的协调性和可操作的结果。本发明重新定义了会议中表情符号的使用方式，通过将表情符号解释为情感和参与度的实时指标，系统能够动态突出关键讨论点、未解决的问题以及需要后续跟进的事项。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488688410_1.jpg)

**Technical Field (技术领域)**:  
人工智能，会议管理，情感分析

**Background (发明背景)**:  
在采用敏捷方法的工作环境中，会议如冲刺计划对于团队协调和项目成功至关重要。然而，现有会议工具主要依赖文本转录或通用自动摘要，无法完全捕捉参与者的情感或优先事项。表情符号作为数字通信中普遍的表达形式，尚未被有效利用以提升会议效果。

**Summary (发明总览)**:  
本发明通过在会议中实时捕捉表情符号反馈，结合AI技术生成智能化的会议摘要。其核心思路是分析表情符号所反映的情感和参与度，动态识别关键讨论点、未解决问题以及需要后续跟进的事项。该方法不仅能生成更贴合团队需求和优先级的摘要，还能通过情感分析提升团队协调性，确保会议成果的可操作性。与现有技术相比，本发明能够更全面地整合情感和内容信息，提供更精准的会议总结。

**Key Innovation (核心创新)**:  
1. 利用表情符号作为情感和参与度的实时指标，通过分析如"竖起大拇指"表示同意、"皱眉"表示困惑或好奇、"拇指向下"表示不满等表情符号，动态捕捉会议中的情感变化。
2. 结合AI技术，将表情符号的情感分析与会议内容整合，生成兼顾情感和内容的智能摘要，确保会议重点的准确性和全面性。
3. 通过识别表情符号的集中出现，标记需要澄清或后续跟进的讨论点，例如多个"皱眉"表情符号出现时，系统会标记该讨论点以提示进一步澄清。
4. 根据不同角色的反馈定制会议摘要，例如针对项目经理、技术负责人等不同角色提供个性化的见解和建议。
5. 改进会议工具的实用性，通过生成具有准确角色和权限的任务和后续会议，提升系统的安全性和协作效率。
6. 在会议结束后自动生成带有优先级的行动项列表，帮助团队快速识别需要立即关注的事项，例如通过多个"心形"表情符号标记的讨论点表示高优先级。
7. 本发明可应用于敏捷开发会议、项目评审等场景，通过提供更精准和可操作的会议摘要，帮助团队提高效率并减少因信息不对称导致的问题。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488688410)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260303393)**
<br/><br/>

---


<br/>

### 22. 改进中心视场检测范围的散热相机镜头设计

**Title (EN)**: THERMAL CAMERA LENS DESIGNWITH IMPROVED CENTER-FIELD DETECTION RANGE  
**Pub. No.**: US20260303933

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Kevin James MATHERSON](https://patents.google.com/?inventor=Kevin+James+MATHERSON&country=US&num=100&sort=new), [Zachary David DEROCHER](https://patents.google.com/?inventor=Zachary+David+DEROCHER&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种用于头戴式显示设备等应用的紧凑型热成像相机系统，采用了一种具有特定桶形畸变特性的镜头设计。该设计在保持整体视场（FOV）的同时，提高了镜头的角分辨率。桶形畸变特性使得相机中心区域的像素角分辨率（即每角度视场的像素数）相较于具有理想零畸变特性的传统直线镜头有所增加。这种角分辨率的提升增强了物体和/或人的热特征的远距离中心视场检测能力，而光学畸变使得镜头能够满足相机的整体角视场要求。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488677410_1.jpg)

**Technical Field (技术领域)**:  
热成像技术领域，具体涉及用于头戴式显示设备的热成像相机镜头设计。

**Background (发明背景)**:  
热成像相机系统正越来越多地集成到头戴式显示设备中，以提高情境感知能力并在各种使用环境中提供关键信息，如消费、医疗和紧急服务。然而，现有紧凑型热成像传感器在像素尺寸和分辨率方面存在限制，影响了远距离检测能力。此外，增加镜头焦距以提高检测范围通常会缩小整体视场，不利于某些应用场景。

**Summary (发明总览)**:  
本发明提出了一种热成像相机镜头设计，通过采用特定的桶形畸变特性来提高中心视场的角分辨率，从而增强热特征的检测范围。该设计在不改变整体视场的情况下，通过数学描述的高阶多项式项实现镜头中心区域的角分辨率提升。畸变校正通过图像处理算法完成，确保热成像数据的可用性。这种设计特别适用于需要宽视场和远距离检测的应用场景，如混合现实头戴式显示设备。

**Key Innovation (核心创新)**:  
1. 采用桶形畸变镜头设计，通过高阶多项式项（如三次和/或四次项）实现镜头中心区域的角分辨率提升。
2. 在保持整体视场不变的情况下，通过提升中心区域的像素角分辨率来增强热特征的检测范围。
3. 使用f-theta畸变特性或四次畸变特性，进一步优化中心视场相对于边缘视场的角分辨率。
4. 通过图像处理算法校正镜头畸变，确保热成像数据的准确性和可用性。
5. 在混合现实头戴式显示设备中应用该设计，利用宽视场提高空间感知能力并减少隧道视觉和眩晕感。
6. 适用于消防、急救和工业检测等场景，提供更远距离的热成像检测能力，提高操作安全性。
7. 在固定热成像监控系统中应用，可减少所需设备数量，同时保持大面积覆盖和远距离检测能力。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488677410)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260303933)**
<br/><br/>

---


<br/>

### 23. 使用头戴式设备多传感器数据进行的健康与健身追踪及其使用方法

**Title (EN)**: HEALTH AND FITNESS TRACKING USING MULTI-SENSOR DATA FROM A HEAD-WEARABLE DEVICE, AND SYSTEMS AND METHODS OF USE THEREOF  
**Pub. No.**: US20260295365

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Venkataraman Chandrasekaran](https://patents.google.com/?inventor=Venkataraman+Chandrasekaran&country=US&num=100&sort=new), [Sneha Kadetotad](https://patents.google.com/?inventor=Sneha+Kadetotad&country=US&num=100&sort=new), [Vamshi Kandala](https://patents.google.com/?inventor=Vamshi+Kandala&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明描述了一种用户佩戴具有多个传感器的头戴式设备进行锻炼的方法。该方法包括：从位于头戴式设备框架上的传感器接收数据，该传感器用于收集与用户头部属性相关的数据；基于与用户头部属性相关的数据确定与用户身体属性相关的指标；确定该指标与预期的用户身体属性指标之间的差异是否满足预定阈值；如果确定差异满足预定阈值，则触发与用户身体属性相关的指示呈现。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488679582_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及可穿戴设备领域，具体为利用头戴式设备传感器进行健康与健身数据追踪的技术。

**Background (发明背景)**:  
现有可穿戴设备的健康与健身数据通常仅限于活动后的整体反馈和分析。此外，实时通知可能会分散用户注意力，例如需要低头查看显示屏或对用户输入做出反应，这降低了通知的有效性。因此，需要一种更高效且不分散注意力的健康与健身追踪方法。

**Summary (发明总览)**:  
本发明提供了一种基于头戴式设备传感器数据的健康与健身追踪系统和方法。该系统能够在用户锻炼时，通过分析头部传感器数据来推断身体状态指标，并在必要时提供非侵入性的反馈或指示。其核心在于利用多传感器数据融合技术，实现对用户健康和健身状态的实时监测，同时减少对用户活动的干扰。

**Key Innovation (核心创新)**:  
1. 通过头戴式设备上的传感器收集用户头部数据，例如心率、瞳孔扩张、呼吸模式等，实现非侵入性健康监测。
2. 基于头部传感器数据推断用户身体状态指标，例如心率变异性、呼吸效率、运动强度等。
3. 采用多传感器数据融合技术，结合心率、呼吸、运动轨迹等多维度数据，提高健康监测的准确性和可靠性。
4. 在虚拟现实（VR）训练环境中，根据实时生物识别数据动态调整训练计划，例如根据心率调整运动强度。
5. 提供实时反馈机制，例如通过VR场景变化或虚拟教练建议，帮助用户保持正确的运动强度和姿势。
6. 持续监测用户生物识别数据以确保安全，并在检测到潜在健康风险时发出警报，例如心率过高或呼吸异常。
7. 本发明可应用于VR健身、AR运动辅助等领域，为用户提供个性化、安全且高效的健身体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488679582)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260295365)**
<br/><br/>

---


<br/>

### 24. 使用可穿戴设备预测房颤发生的方法

**Title (EN)**: Methods for Predicting Atrial Fibrillation (AFIB) Occurrences Using a Wearable Device  
**Pub. No.**: US20260294263

**Applicant**: Google LLC  
**Inventor**: [Zeinab Esmaeilpour](https://patents.google.com/?inventor=Zeinab+Esmaeilpour&country=US&num=100&sort=new), [Anthony Zahi Faranesh](https://patents.google.com/?inventor=Anthony+Zahi+Faranesh&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明提供了一种预测心脏心律失常事件的方法。该方法包括基于从可穿戴计算设备的一个或多个生物传感器获得的生物特征数据，确定用户是否经历了初始心脏心律失常事件。在确定用户经历了初始心脏心律失常事件后，该方法包括获取指示用户心脏节律的生物特征数据，用于观察期。该方法包括确定用户在观察期内心脏心律失常事件的一个或多个时间模式。该方法包括基于用户在观察期内心脏心律失常事件的一个或多个时间模式，生成至少一个未来心脏心律失常事件的预测。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488683107_1.jpg)

**Technical Field (技术领域)**:  
可穿戴设备技术，心脏健康监测，房颤预测

**Background (发明背景)**:  
可穿戴设备如智能手表等可以监测用户的心率数据，但现有技术难以有效预测心脏心律失常事件，尤其是房颤。
由于房颤具有阵发性和无症状的特点，短时间的心电图监测往往无法捕捉到异常。
现有方法缺乏对历史心律数据的分析，难以实现对房颤的提前预警。

**Summary (发明总览)**:  
本发明提出了一种基于可穿戴设备的心律失常预测方法，通过分析用户的历史心律数据来预测未来的房颤事件。
该方法首先识别用户的初始房颤事件，然后收集观察期内的心律数据并建立概率模型。
通过时间模式分析和预测模型，生成未来房颤事件的预测信号。
该方法能够提前预警房颤事件，并建议用户进行进一步的心电图监测。

**Key Innovation (核心创新)**:  
1. 通过可穿戴设备（如智能手表）上的生物传感器（如PPG传感器）收集用户的心律数据，实现对房颤事件的持续监测。
2. 建立基于时间模式的心脏状态转移概率模型，使用转移矩阵表示用户在不同心脏状态之间的转换概率。
3. 转移矩阵包含四个概率值，分别表示用户保持在正常心律、转为房颤、从房颤恢复为正常心律以及保持在房颤状态的可能性。
4. 将概率模型与分类器结合，构建预测模型，用于预测未来房颤事件的发生。
5. 根据初始房颤事件调整观察期长度，提高预测模型的准确性和针对性。
6. 在预测到未来房颤事件时，向用户发送佩戴心电图监测设备的建议，并提供预测信号作为预警。
7. 该方法可应用于智能健康监测设备，为用户提供个性化的心脏健康预警服务，帮助医生进行更有效的诊断和治疗。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488683107)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260294263)**
<br/><br/>

---


<br/>

### 25. 计算设备的端口

**Title (EN)**: PORT FOR A COMPUTING DEVICE  
**Pub. No.**: US20260299870

**Applicant**: GOOGLE LLC  
**Inventor**: [Joshua Moore](https://patents.google.com/?inventor=Joshua+Moore&country=US&num=100&sort=new), [Craig Eric Ranta](https://patents.google.com/?inventor=Craig+Eric+Ranta&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明提供了一种位于计算设备外壳内的端口。该端口利用外壳内的共用安装空间，在单一组合端口中实现了第一组件和第二组件的功能。该端口在第一模式下作为音频输出端口工作，在第二模式下作为充电和/或数据通信端口工作。音频输出设备的前部空间延伸至端口的插座和音频驱动器之间，以在第一模式下通过插座输出音频内容。在第二模式下，可在端口插座壁部所定义的空腔内设置接口设备，以方便与可选择插入插座进行充电和/或有线数据通信的充电插头连接。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684547_1.jpg)

**Technical Field (技术领域)**:  
计算设备连接端口技术，具体涉及多功能组合端口设计。

**Background (发明背景)**:  
计算设备通常包含多种接口设备，用于用户输入输出信息、与外部设备通信以及充电等功能。然而，由于设备外形尺寸、安装空间限制以及美观性等因素，某些计算设备在容纳电子元件、接口端口和接口设备等方面面临空间受限的问题。现有技术难以在有限空间内实现多功能集成。

**Summary (发明总览)**:  
本发明提出了一种多功能组合端口设计，通过在计算设备外壳内集成音频输出和充电/数据通信功能，显著提高了空间利用率。该设计通过共用安装空间，在单一端口中实现了多种功能模块的集成，特别适用于外形尺寸受限的计算设备，如头戴式显示器或智能眼镜。

**Key Innovation (核心创新)**:  
1. 设计了一种组合端口，将音频输出功能和充电/数据通信功能集成在单一端口中，通过共用安装空间实现多功能集成。
2. 在第一模式下，端口作为音频输出端口工作，通过音频驱动器与插座之间的空间输出音频内容。
3. 在第二模式下，端口作为充电和数据通信端口工作，通过外部电缆的插头实现设备充电和数据交换。
4. 端口设计包含一个接口设备，位于插座壁部所定义的空腔内，便于与充电插头连接并支持有线数据通信。
5. 该设计特别适用于外形尺寸受限的计算设备，如头戴式显示器或智能眼镜，解决了传统设计中空间不足的问题。
6. 通过组合端口设计，减少了设备所需接口数量，优化了内部空间布局，提升了设备的紧凑性和便携性。
7. 该技术可应用于智能眼镜、VR/AR头戴设备等场景，提供更高效的空间利用方案，同时满足音频输出和充电/数据通信需求。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684547)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299870)**
<br/><br/>

---


<br/>

### 26. 基于设备的防盗与恢复系统

**Title (EN)**: DEVICE-BASED ANTI-THEFT AND RECOVERY SYSTEM  
**Pub. No.**: US20260300561

**Applicant**: Google LLC  
**Inventor**: [Sudeep Chauhan](https://patents.google.com/?inventor=Sudeep+Chauhan&country=US&num=100&sort=new), [Ehsan Nourbakhsh](https://patents.google.com/?inventor=Ehsan+Nourbakhsh&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明公开了用于计算设备的基于设备的防盗与恢复技术。示例系统包括一个或多个处理器，用于执行指令以接收来自意图将计算设备转移给受让人的转让人的一组信号参数，如果满足这些参数，则允许计算设备停用受保护的操作模式；在正常操作模式下激活受保护模式，其中计算设备在受保护模式激活期间禁用正常操作模式下启用的一个或多个功能；在受保护模式下接收潜在受让人对应的用户输入，该输入对应计算设备的唤醒功能；并响应于接收用户输入，基于与计算设备相关的一个或多个信号与信号参数的比较，确定计算设备是否在受让人手中；如果确定计算设备在受让人手中，则停用受保护操作模式；如果确定计算设备不在受让人手中，则保持受保护操作模式。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685305_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及计算设备安全技术，具体为防盗与设备转移控制领域。

**Background (发明背景)**:  
移动设备和其他计算设备经常成为盗窃的目标。为了防止盗窃，原始设备制造商（OEM）或软件生态系统提供商通常提供远程禁用被盗设备的服务。然而，现有技术主要依赖远程操作，可能无法有效防止设备在转移过程中被盗或被滥用。本发明旨在提供一种基于设备的防盗与恢复系统，以在设备转移过程中保护设备安全。

**Summary (发明总览)**:  
本发明提出了一种基于设备的防盗与恢复系统，通过在设备转移过程中激活受保护模式来防止未经授权的使用。系统通过接收转让人提供的信号参数来验证设备是否在受让人手中，并在验证通过后停用受保护模式，允许受让人正常使用设备。该方法通过设备自身机制实现，无需依赖远程操作，增强了设备在转移过程中的安全性。

**Key Innovation (核心创新)**:  
1. 通过设备自身机制实现防盗保护，无需依赖远程操作，提升了防盗的可靠性和实时性。
2. 在设备转移过程中激活受保护模式，禁用正常功能，防止设备在运输或交付过程中被滥用。
3. 通过接收转让人提供的信号参数，验证设备是否在受让人手中，确保只有合法受让人能够激活设备。
4. 在受保护模式下，设备会响应潜在受让人的用户输入，并基于信号参数进行比对，以确定设备是否在受让人手中。
5. 如果验证失败，设备将保持受保护模式，防止未经授权的使用；如果验证成功，则停用受保护模式，允许受让人正常使用设备。
6. 该系统可应用于智能手机、平板电脑等计算设备，为设备转移过程提供安全保护。
7. 通过设备自身的安全机制，本发明为设备转移提供了更高效、更安全的解决方案，尤其适用于高价值设备。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685305)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300561)**
<br/><br/>

---


<br/>

### 27. 在自动化助手交互中选择性提供增强型澄清提示

**Title (EN)**: SELECTIVELY PROVIDING ENHANCED CLARIFICATION PROMPTS IN AUTOMATED ASSISTANT INTERACTIONS  
**Pub. No.**: US20260301740

**Applicant**: GOOGLE LLC  
**Inventor**: [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new), [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明描述的实现方案接收捕获语音的音频数据，基于对音频数据的处理生成对应的识别结果，并基于对识别结果的处理确定语音是否具有歧义（即，既可被解释为请求执行第一特定操作，也可被解释为请求执行第二特定操作）。在确定语音具有歧义的情况下，本发明决定提供增强型澄清提示，该提示除了自然语言外还输出额外内容。增强型澄清提示用于请求进一步的用户界面输入，以区分第一特定操作和第二特定操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686603_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及语音识别和自然语言处理中的歧义处理。

**Background (发明背景)**:  
人机对话中，用户通过语音或文本输入命令或请求，自动化助手根据这些输入执行相应操作。然而，当用户的语音或文本输入存在歧义时，自动化助手可能无法准确判断用户的意图，从而导致操作错误或需要进一步澄清。现有技术通常使用纯自然语言提示来澄清用户意图，但这种方法可能效率低下，甚至导致用户放弃其目标。

**Summary (发明总览)**:  
本发明提出了一种在自动化助手交互中根据特定条件选择性提供增强型澄清提示的方法。当检测到用户输入的语音具有歧义时，系统会决定是否提供增强型澄清提示，而不是仅使用纯自然语言提示。增强型提示通过音频或视觉内容（如音乐片段、图片或视频）来帮助用户更高效地澄清其意图，从而减少交互时间并提高准确性。

**Key Innovation (核心创新)**:  
1. 通过分析用户语音输入的歧义性，智能判断是否需要提供增强型澄清提示，而非仅依赖纯自然语言提示。
2. 利用音频和视觉内容（如音乐片段、图片或视频）作为增强型澄清提示的一部分，帮助用户更直观地理解并区分候选操作。
3. 基于历史自动化助手交互数据，预先确定在特定情况下使用增强型提示的必要性，以提高用户澄清输入的准确性和效率。
4. 通过比较描述候选操作的术语之间的文本和语义相似度，动态决定是否需要提供增强型提示，以应对高度相似的操作选项。
5. 采用逆文档频率（IDF）和其他指标评估描述候选操作的术语的稀有性，并根据评估结果选择合适的澄清提示方式。
6. 通过综合考虑多种条件（如用户历史行为、术语相似度和稀有性），实现对增强型提示的智能选择，从而优化人机交互体验。
7. 本发明可应用于智能音箱、虚拟助手等语音交互产品中，帮助用户在面对歧义输入时更高效地获得准确反馈，提升用户满意度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686603)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301740)**
<br/><br/>

---


<br/>

### 28. 用户跌倒风险评估

**Title (EN)**: Fall Risk Assessment for a User  
**Pub. No.**: US20260294278

**Applicant**: Google LLC  
**Inventor**: [Boyan Bonev](https://patents.google.com/?inventor=Boyan+Bonev&country=US&num=100&sort=new), [Jung Ook Hong](https://patents.google.com/?inventor=Jung+Ook+Hong&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明提供了一种用于评估用户跌倒风险的计算机实现方法。该方法包括获取指示用户参与跌倒风险活动的数据，并根据该数据调整用户佩戴的可穿戴计算设备的跌倒检测阈值。该方法还包括提供指示用户因参与跌倒风险活动而有跌倒风险的警报。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488683273_1.jpg)

**Technical Field (技术领域)**:  
可穿戴计算设备领域，具体涉及跌倒风险评估和预防技术。

**Background (发明背景)**:  
可穿戴计算设备通常佩戴在用户手腕等部位，内置传感器可检测用户运动数据并识别跌倒事件。然而，现有设备在跌倒检测的灵敏度上存在不足，尤其在用户进行高风险活动时可能无法及时调整检测参数，导致误报或漏报。本发明旨在解决这一问题，通过动态调整跌倒检测阈值来提高检测准确性。

**Summary (发明总览)**:  
本发明提出了一种基于可穿戴设备的跌倒风险评估方法，通过分析用户行为数据动态调整跌倒检测阈值。当检测到用户进行高风险活动时，设备会降低检测阈值以提高灵敏度，并及时向用户发出跌倒风险警报。该方法结合了用户活动数据和设备传感器数据，通过机器学习模型优化检测参数，从而实现更精准的跌倒风险预测。

**Key Innovation (核心创新)**:  
1. 通过传感器数据识别用户是否正在进行跌倒风险活动，如行走、搬运物体或刚睡醒后的步态不稳。
2. 利用机器学习模型处理传感器数据，动态调整跌倒检测阈值，以适应不同活动场景下的风险变化。
3. 针对不同类型的跌倒风险活动设置不同的检测阈值，例如搬运物体时降低检测灵敏度以避免误报。
4. 结合睡眠数据（如睡眠时长和深度）调整跌倒检测参数，特别是在用户刚睡醒时的步态监测中提高检测准确性。
5. 通过可穿戴设备或关联的移动设备向用户发出跌倒风险警报，并提供触觉或听觉提示以确保用户及时响应。
6. 支持多传感器数据融合，例如同时使用加速度计和陀螺仪数据，以提高跌倒检测的可靠性和准确性。
7. 该技术可应用于日常健康监测、老年人护理和运动康复等领域，帮助用户预防跌倒风险并提高安全性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488683273)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260294278)**
<br/><br/>

---


<br/>

### 29. 电容式触摸界面的触摸类型分析和分类

**Title (EN)**: TOUCH TYPE PROFILING AND CLASSIFICATION FOR A CAPACITIVE TOUCH INTERFACE  
**Pub. No.**: US20260299724

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Anatoly TSVETOV](https://patents.google.com/?inventor=Anatoly+TSVETOV&country=US&num=100&sort=new), [Roei Shlomo MENASHOF](https://patents.google.com/?inventor=Roei+Shlomo+MENASHOF&country=US&num=100&sort=new), [Oren ISTRIN](https://patents.google.com/?inventor=Oren+ISTRIN&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种具有触摸类型分析和分类功能的电容式触摸界面提高了触摸事件分类的准确性，使用户能够更自然地与触摸设备（例如触摸屏和触摸板）进行交互。通过避免对非输入触摸事件进行报告、处理、操作和撤销，节省了资源。从触摸事件数据集中提取触摸特征，例如触摸位置、大小、形状、持续时间、一致性、电容强度、动态变化（例如形状变化、移动模式）、聚类、手掌指示等。基于触摸特征指示的触摸类型，对触摸事件进行分类（例如，触摸输入、工具输入、手掌触摸、水分）。例如，水分触摸特征可能包括不规则的触摸形状、弱或不稳定的电容测量值。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684385_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及电容式触摸界面的触摸事件分类和识别技术。

**Background (发明背景)**:  
触摸输入设备（如触摸屏和触摸板）广泛应用于计算设备中，但现有技术难以区分用户输入和非用户输入。非用户输入（如手掌触摸和水分）常被误判为用户输入，导致设备行为异常和用户体验下降。此外，高湿度或液体环境下的电容式触摸设备容易产生误触，影响设备正常运行。

**Summary (发明总览)**:  
本发明提出了一种基于触摸特征分析和分类的电容式触摸界面解决方案。通过提取触摸事件数据中的多种特征（如位置、大小、形状、持续时间等），对触摸事件进行分类，区分用户输入和非用户输入（如手掌触摸和水分）。该方案通过动态调整触摸分析和灵敏度，适应不同的使用环境和用户需求，从而提高触摸识别的准确性，减少误触并优化用户体验。

**Key Innovation (核心创新)**:  
1. 通过提取触摸事件数据中的多种特征（如位置、大小、形状、持续时间、电容强度、动态变化等），实现对触摸事件的全面分析。
2. 基于触摸特征构建触摸类型分类模型，能够准确区分用户输入（如手指触摸、工具触摸）和非用户输入（如手掌触摸、水分）。
3. 针对水分触摸和手掌触摸等非用户输入，设计了专门的触摸特征识别算法，例如识别不规则触摸形状、弱或不稳定的电容测量值。
4. 提供用户自定义触摸类型配置文件和灵敏度设置的功能，允许用户根据个人需求调整触摸识别参数。
5. 在触摸输入过程中进行动态适应，根据触摸类型分类结果和检测到的屏幕及环境条件调整触摸分析和灵敏度。
6. 通过向用户和操作系统提供不同类型的反馈反馈（如水分指示），帮助用户及时采取纠正措施。
7. 该技术可应用于智能手机、平板电脑等电容式触摸设备，能够在复杂环境下提高触摸识别的准确性，提升用户体验并减少误操作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684385)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299724)**
<br/><br/>

---


<br/>

### 30. 协调与异构机器学习代理的交互

**Title (EN)**: COORDINATING INTERACTIONS WITH HETEROGENOUS MACHINE LEARNING AGENTS  
**Pub. No.**: US20260300001

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Lindsay Gray GREENE](https://patents.google.com/?inventor=Lindsay+Gray+GREENE&country=US&num=100&sort=new), [Cong CHEN](https://patents.google.com/?inventor=Cong+CHEN&country=US&num=100&sort=new), [Sheikh Sadid AL HASAN](https://patents.google.com/?inventor=Sheikh+Sadid+AL+HASAN&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及促进用户与多个代理之间的交互，这些代理提供不同的生成式机器学习能力。在某些实施方式中，接收用户输入并选择两个或多个代理来执行特定任务。然后，根据所选代理的代理定义代表用户协调与这些代理的交互。接收特定任务的结果并将其提供给用户。例如，用户输入可以通过聊天界面接收，允许用户进行涉及多个代理执行特定任务的单一聊天会话，从而使用户感觉像是在与单个代理交互。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684692_1.jpg)

**Technical Field (技术领域)**:  
人工智能，生成式机器学习，代理协调技术

**Background (发明背景)**:  
近年来，生成式机器学习模型在生成内容方面展示了巨大能力，例如生成文本总结现有文档或进行对话，以及生成或修改图像。然而，用户直接使用这些模型可能需要大量努力，并且许多用户缺乏有效利用这些模型的专业知识。现有的代理方法虽然可以简化用户与模型的交互，但不同代理的能力和技术限制各异，且代理之间直接交互的能力有限。

**Summary (发明总览)**:  
本发明提出了一种协调用户与多个机器学习代理交互的技术方案。通过提供代理注册表，记录各代理的特性，系统能够根据用户任务选择合适的代理组合，并代表用户协调它们之间的交互。系统采用统一接口接收用户输入，并通过代理协作完成任务，最终将结果返回给用户。这种方法使用户无需直接管理多个代理的交互，同时享受不同代理组合带来的优势。

**Key Innovation (核心创新)**:  
1. 提供一个代理注册表，用于存储多个代理的特性、能力和限制信息，为代理选择提供依据。
2. 根据用户输入的任务描述和代理注册表中的信息，动态选择最适合的代理组合来完成任务。
3. 采用协调机制，在多个代理之间共享上下文信息，确保代理间的交互流畅且高效。
4. 提供统一的用户界面，使用户能够通过单一入口与多个代理进行交互，无需切换应用或窗口。
5. 通过抽象底层代理交互细节，为用户提供无缝体验，使用户感觉像是在与单个代理互动。
6. 实现了对代理能力的动态管理和任务分配，适应不同代理组合的变化和任务需求。
7. 该技术可应用于复杂任务场景，如多步骤分析、对话生成和图像处理，为用户提供更智能和高效的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684692)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300001)**
<br/><br/>

---


<br/>

### 31. 减少立体显示中深度冲突的方法

**Title (EN)**: METHOD FOR REDUCING DEPTH CONFLICTS IN STEREOSCOPIC DISPLAYS  
**Pub. No.**: US20260303770

**Applicant**: GOOGLE LLC  
**Inventor**: [Philip George Nichols Lamoureux](https://patents.google.com/?inventor=Philip+George+Nichols+Lamoureux&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
在立体显示中，当背景对象的渲染深度小于叠加在其上的前景对象的深度时，会产生深度冲突。本发明通过在前景对象叠加在背景对象上时增加背景对象的深度来解决此冲突。在重叠条件结束后，背景对象的深度可以恢复到原始值。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488688823_1.jpg)

**Technical Field (技术领域)**:  
立体显示技术，具体涉及虚拟现实系统中显示内容的深度调整方法。

**Background (发明背景)**:  
虚拟现实系统通过头戴式设备显示三维场景，并利用传感器检测用户头部运动以调整显示内容，使用户获得沉浸式体验。深度感知基于向用户左右眼传输立体图像而产生的视差效应。然而，当多个应用同时在头戴式设备上显示内容时，不同的视差效应可能导致深度冲突问题。

**Summary (发明总览)**:  
本发明提出了一种在立体显示中防止深度冲突的方法，通过调整图像的视差参数来改变渲染深度。具体而言，将重叠图像对中底部图像的立体深度推远，以确保即使顶部图像的精确立体深度未知，也能解决深度冲突问题。该方法通过调整瞳距值来改变渲染深度，并允许在重叠条件结束后恢复原始深度设置。

**Key Innovation (核心创新)**:  
1. 通过调整瞳距值生成调整后的瞳距值，并基于此渲染具有不同立体深度的图像对，以防止深度冲突。
2. 实现了动态调整立体深度，其中前景图像的深度逐渐增加，而背景图像的深度保持相对固定，从而避免深度冲突。
3. 提供了将瞳距值设为零的选项，使得调整后的立体深度为无限大，进一步减少深度冲突的可能性。
4. 引入了一种渐进式调整机制，通过在一定时间内逐渐减少瞳距值，使立体深度平滑过渡，避免视觉不连续性。
5. 实现了基于用户头部平移的调整，确保在用户移动时，渲染的立体图像具有准确的运动视差，同时保持深度一致性。
6. 将调整后的参数应用于第一应用，而原始参数应用于第二应用，使得重叠窗口的深度关系更加明确。
7. 本发明可应用于虚拟现实头戴式设备，通过优化立体深度渲染，提升用户视觉体验并减少视觉疲劳，尤其适用于多应用同时运行的环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488688823)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260303770)**
<br/><br/>

---


<br/>

### 32. 多分离视场增强现实波导系统

**Title (EN)**: MULTIPLE SEPARATED FIELD OF VIEW AUGMENTED REALITY WAVEGUIDE SYSTEM  
**Pub. No.**: US20260299299

**Applicant**: GOOGLE LLC  
**Inventor**: [Thomas Hoekman](https://patents.google.com/?inventor=Thomas+Hoekman&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种眼镜显示设备的波导系统将来自主显示器的显示光引导至主视场（FOV），并将来自辅助显示器的显示光引导至与主视场分离的辅助视场。在某些实施例中，与主显示光以不同角度耦合到波导系统的给定颜色的附加显示光，从波导系统以相对于主视场偏移的对应角度输出，从而形成在空间上与主视场分离的辅助视场。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488683920_1.jpg)

**Technical Field (技术领域)**:  
增强现实显示技术，具体涉及多视场波导光学系统。

**Background (发明背景)**:  
增强现实（AR）显示系统通常使用光学组合器将现实世界的光与显示器的光结合，以向用户的眼睛输出。现有技术中，光学组合器如波导存在视场（FOV）较小和光学组合器较厚的问题。此外，不同波长的光通过全内反射（TIR）在波导中以不同角度传播，导致单一波导难以支持大视场。现有AR系统通常采用单一视场显示所有内容和用户界面（UI）元素，导致用户体验不够沉浸。

**Summary (发明总览)**:  
本发明提出一种近眼显示系统，通过波导系统将来自两个显示器的不同颜色显示光分别引导至分离的主视场和辅助视场。系统利用多个输入耦合器和输出耦合器实现光的分离和输出，从而在单一波导系统中实现多视场显示。这种设计允许在主视场之外添加辅助内容，提升用户体验的沉浸感。

**Key Innovation (核心创新)**:  
1. 采用双显示器设计，一个主显示器和一个辅助显示器，分别提供不同颜色的显示光，并通过波导系统引导至分离的主视场和辅助视场。
2. 使用多个输入耦合器（incouplers），分别将主显示器和辅助显示器的显示光耦合到波导系统中，实现光的分离输入。
3. 通过设计波导系统中的光路，使得不同波长的光在k空间中形成闭合回路，确保输出光的角度与入射光的角度保持一致。
4. 利用二维光栅作为输出耦合器（outcoupler），扩展来自不同输入耦合器的显示光，并将其耦合出波导系统。
5. 在波导系统中引入单色显示光（如红色、绿色或蓝色），在主视场之外创建辅助视场，用于显示特定内容，如导航箭头或字幕。
6. 通过合理设计波导结构和光栅参数，实现多视场显示，同时保持波导的轻薄和光学效率。
7. 本发明可应用于增强现实眼镜等可穿戴设备，通过多视场显示提升用户沉浸感，例如在视野边缘显示导航信息或录制指示器。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488683920)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299299)**
<br/><br/>

---


<br/>

### 33. 用于多模态自由形式对象识别的系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR MULTIMODAL FREEFORM OBJECT IDENTIFICATION  
**Pub. No.**: US20260299683

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jacqueline Fashimpaur](https://patents.google.com/?inventor=Jacqueline+Fashimpaur&country=US&num=100&sort=new), [Ting Zhang](https://patents.google.com/?inventor=Ting+Zhang&country=US&num=100&sort=new), [Tanya Renee Jonker](https://patents.google.com/?inventor=Tanya+Renee+Jonker&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
描述了一种执行对象选择过程的方法。该方法包括：在用户执行选择输入时，响应于用户执行选择输入：接收来自用户佩戴的头戴式设备的一个或多个摄像头所捕获的包含一个或多个对象的视野图像数据；接收来自头戴式设备的包含用户对上述一个或多个对象中至少一个的注视数据的注视数据；接收来自用户佩戴的手腕佩戴式设备的手势数据，该手势数据指示用户执行选择手势，选择手势具有手势大小和手势形状；基于注视数据、图像数据、手势大小和手势形状，确定上述一个或多个对象中至少一部分；并向用户呈现所选对象部分的指示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684343_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及对象识别领域，具体是通过头戴式设备与手腕佩戴式设备的多模态输入（注视和手势）进行对象识别。

**Background (发明背景)**:  
可穿戴设备在识别用户对对象的详细和准确选择方面能力有限，影响用户体验。仅依赖手势识别容易产生用户操作摩擦，例如用手圈出对象的一部分可能被误识别为选择整个对象及其周围对象。本发明旨在解决上述问题，通过结合注视和手势输入提高对象选择的准确性和用户体验。

**Summary (发明总览)**:  
本发明提供了一种结合注视和手势输入的多模态对象识别方法，通过头戴式设备捕捉用户视野图像数据和注视数据，同时通过手腕佩戴式设备捕捉用户的手势数据。该方法通过分析这些数据，精准识别用户选择的对象部分并提供反馈。本发明相较于现有技术的主要改进在于结合多种输入模式，提高了对象选择的准确性和用户操作的直观性。

**Key Innovation (核心创新)**:  
1. 结合注视数据和手势数据，通过分析用户注视位置和手势大小、形状，实现对对象部分的精准识别。
2. 利用头戴式设备的摄像头捕捉用户视野图像数据，并结合手腕佩戴式设备的手势传感器数据，实现多模态输入融合。
3. 通过分析手势的尺寸和形状特征，区分用户选择手势与其他手势，避免误识别。
4. 提供实时反馈机制，向用户展示所选对象部分，增强交互的直观性和准确性。
5. 兼容多种可穿戴设备，包括AR眼镜、MR头显和智能手表等，适应不同用户场景。
6. 应用于增强现实（AR）和混合现实（MR）环境，支持用户与虚拟或现实对象进行高效交互。
7. 独特价值在于提升用户与虚拟或现实对象交互的效率和准确性，尤其适用于需要精确选择的应用场景，如虚拟装配、远程协作和智能导航。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684343)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299683)**
<br/><br/>

---


<br/>

### 34. 用于引导用户执行与特定运动单元相关的可检测生物电位手势的系统和方法，以及相关的可操作反馈

**Title (EN)**: SYSTEMS AND METHODS FOR GUIDING USERS TO PERFORM DETECTABLE BIOPOTENTIAL-BASED GESTURES TIED TO SPECIFIC MOTOR UNITS, AND ACTIONABLE FEEDBACK ASSOCIATED THEREWITH  
**Pub. No.**: US20260299703

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Diego Adrian Gutnisky](https://patents.google.com/?inventor=Diego+Adrian+Gutnisky&country=US&num=100&sort=new), [Najja Marshall](https://patents.google.com/?inventor=Najja+Marshall&country=US&num=100&sort=new), [Emanuele Formento](https://patents.google.com/?inventor=Emanuele+Formento&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明公开了一种引导用户激活生物运动单元(MUs)的方法和系统。该方法包括呈现执行与MUs激活相关的运动的指令，以及与MUs激活相关的图形元素。在检测到MUs激活后，根据在执行运动期间捕获的生物电位传感器数据，确定用户需要执行的额外运动和图形元素的变化。该方法还包括呈现执行额外运动的额外指令，以及图形元素的变化。在检测到MUs的额外激活后，根据确定在执行额外运动期间捕获的第二生物电位传感器数据满足手势映射阈值，将第二生物电位传感器数据与一个或多个基于生物电位的手势相关联，并呈现图形元素的第二变化。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684364_1.jpg)

**Technical Field (技术领域)**:  
生物电位传感器技术；
人机交互；
微动作训练与优化

**Background (发明背景)**:  
随着电子设备（如手机、平板电脑、笔记本电脑等）的普及，用户需要频繁与设备交互，这通常会打断现实世界的活动。现有的交互方式效率低下、分散注意力，且在某些场合下不够得体。因此，需要一种解决方案，使用户能够快速高效地与电子设备交互，同时保持对现实世界的参与，并确保在各种场合下的社交接受度。

**Summary (发明总览)**:  
本发明提供了一种通过训练用户执行微动作来与电子设备进行交互的方法。这些微动作与特定生物运动单元的激活相关联，并通过生物电位传感器进行检测。系统会引导用户识别和隔离这些生物运动单元，并优化其激活方式，使得用户的动作对旁观者来说几乎不可察觉。这种方法不仅使用户能够在不脱离现实世界的情况下与设备交互，还能在各种场合下以更得体的方式使用电子设备。此外，通过减少用户的身体动作（如拇指或手指的移动），可以降低用户疲劳。

**Key Innovation (核心创新)**:  
1. 通过生物电位传感器实时捕捉用户微动作的生物电位信号，实现对特定运动单元激活的精确检测。
2. 提供分步指导，通过增强现实界面逐步引导用户执行与特定运动单元激活相关的动作，并提供即时视觉反馈。
3. 基于生物电位传感器数据动态调整用户动作建议，优化运动单元的激活效果，确保手势识别的准确性。
4. 采用图形元素的变化（如颜色、形状或动画）直观地指示用户动作的完成度和运动单元的激活状态。
5. 通过机器学习算法分析生物电位数据，识别用户独特的生物运动单元特征，并生成个性化的动作指导方案。
6. 将检测到的手势与特定功能或命令关联，使用户能够通过微动作控制电子设备，实现高效的人机交互。
7. 该技术可应用于智能手表、头戴式设备等可穿戴设备，为用户提供在社交场合中更隐蔽、更便捷的设备控制方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684364)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299703)**
<br/><br/>

---


<br/>

### 35. 用于定制微同轴电缆的系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR CUSTOMIZING MICRO-COAXIAL CABLES  
**Pub. No.**: US20260301990

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Kristy Alana Jost](https://patents.google.com/?inventor=Kristy+Alana+Jost&country=US&num=100&sort=new), [Daniel Myers](https://patents.google.com/?inventor=Daniel+Myers&country=US&num=100&sort=new), [Brendon Allen Beardsley](https://patents.google.com/?inventor=Brendon+Allen+Beardsley&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明提供了一种通过挤出工艺将导电芯连接到微同轴电缆表面以制造定制化微同轴电缆的方法，并在不使用烧蚀工艺的情况下提供表面连接。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686881_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及微同轴电缆领域，具体为微同轴电缆的定制化制造技术。

**Background (发明背景)**:  
微同轴电缆广泛应用于电子设备中，用于数据传输和信号传输。然而，传统微同轴电缆在尺寸缩小时容易出现连接不可靠的问题，尤其是在可穿戴设备和智能纺织品等应用中。此外，传统电缆缺乏电磁干扰保护和信号损失保护，且需要通过烧蚀工艺进行定制化连接，这既耗时又昂贵。

**Summary (发明总览)**:  
本发明提出了一种通过挤出工艺制造定制化微同轴电缆的方法。该方法通过在微同轴电缆的表面以可定制的间隔连接导电芯，并提供表面连接，从而避免了使用烧蚀工艺。定制化微同轴电缆包括多个层中的绝缘和导电材料段，并通过挤出工艺制造。本发明简化了与其他电子组件的互连过程，并提高了电缆的灵活性和结构完整性。

**Key Innovation (核心创新)**:  
1. 通过挤出工艺将导电芯连接到微同轴电缆表面，实现表面连接，避免了传统烧蚀工艺的复杂性和成本。
2. 在微同轴电缆的所有层中定制化设置绝缘和导电材料段，通过连接多个层的导电段，实现导电芯与电缆外壳的连接。
3. 在电缆外壳上创建表面导电轨迹，从而实现与其他电子组件的更可靠连接，例如通过导电焊盘与表面轨迹连接。
4. 使用弹性材料（如金属填充聚合物或液态金属）作为导电层，使电缆保持柔韧性，适用于可穿戴设备等反复弯曲的应用场景。
5. 通过挤出工艺一次性制造电缆长度，并使用不同导电和绝缘材料定制各层结构，简化制造流程。
6. 改善微同轴电缆与其他电子组件的连接便捷性，通过增加表面连接节点和提高电缆的结构完整性和柔韧性。
7. 本发明特别适用于可穿戴技术和智能纺织品领域，能够实现与柔性材料的集成，并扩展连接轨迹的放置选项。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686881)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301990)**
<br/><br/>

---


<br/>

### 36. 利用人工智能代理缓解安全事件

**Title (EN)**: MITIGATION OF SECURITY EVENTS UTILIZING ARTIFICIAL INTELLIGENCE AGENTS  
**Pub. No.**: US20260303618

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Maor NISSAN](https://patents.google.com/?inventor=Maor+NISSAN&country=US&num=100&sort=new), [Roee OZ](https://patents.google.com/?inventor=Roee+OZ&country=US&num=100&sort=new), [Tamer SALMAN](https://patents.google.com/?inventor=Tamer+SALMAN&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本文描述了用于缓解和修复安全事件的系统、方法和设备以及计算机可读存储介质。在一个方面，第一个人工智能（AI）代理基于与检测到的计算网络安全事件相关的事件信息和识别计算网络候选者的候选数据选择用于修复安全事件的候选者。第二个人工智能代理生成用于修复安全事件的修复任务，并将修复任务分配给选定的候选者。第三个人工智能代理监控修复任务的执行情况，并在选定的候选者未能修复安全事件时进行检测。在另一个方面，第一个人工智能代理基于安全事件与候选者之间的相似性选择候选者。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488688656_1.jpg)

**Technical Field (技术领域)**:  
网络安全领域，利用人工智能代理实现安全事件自动分配和修复。

**Background (发明背景)**:  
现有计算网络系统依赖人工团队成员处理安全漏洞或暴露问题。人工选择和分配任务耗时且易出错，可能导致任务分配给不合适的团队成员。手动监控任务执行也存在人为错误风险。

**Summary (发明总览)**:  
本发明利用人工智能代理实现安全事件修复的自动化流程。通过AI代理选择合适的修复人员或组件，生成修复任务并分配任务，同时监控任务执行情况并处理失败情况。该方法减少了人工干预，提高了任务分配和执行的准确性和效率，从而缩短了安全事件修复时间，降低了安全风险。

**Key Innovation (核心创新)**:  
1. 采用多代理协同工作模式，包括候选选择代理、任务生成代理和监控代理，实现安全事件修复的端到端自动化。
2. 利用AI算法分析事件信息和候选数据，智能选择最适合修复安全事件的候选者，提高任务分配的准确性。
3. 通过AI代理实时监控修复任务的执行情况，及时发现并处理修复失败情况，减少安全事件影响范围。
4. 引入AI驱动的任务生成机制，根据事件类型和候选者能力自动生成定制化的修复任务，提升修复效率。
5. 减少人工干预，降低人为错误风险，同时减轻安全团队的工作负担。
6. 适用于企业网络和云环境等复杂计算网络系统，能够处理多种类型的安全事件，如数据泄露、应用程序后门、资源受损等。
7. 通过缩短安全事件修复时间，降低网络系统受攻击的风险，为组织提供更可靠的安全保障。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488688656)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260303618)**
<br/><br/>

---


<br/>

### 37. 通过手持设备访问人工现实内容

**Title (EN)**: ACCESSING ARTIFICIAL REALITY CONTENT THROUGH A HANDHELD DEVICE  
**Pub. No.**: US20260295410

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jan Herling](https://patents.google.com/?inventor=Jan+Herling&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
在一个实施例中，计算系统可基于与手持设备相关联的一个或多个传感器确定手持设备在现实空间中的设备姿态。系统可基于手持设备的面部跟踪数据确定与手持设备相关联的第一用户的头部姿态，该头部姿态是相对于现实空间中的手持设备而言的。系统可基于现实空间中的第一用户的头部姿态在虚拟空间中渲染与第一用户相关联的第一虚拟形象。系统可基于现实空间中的第一用户的头部姿态向第一用户渲染一个或多个虚拟对象。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488679633_1.jpg)

**Technical Field (技术领域)**:  
人工现实技术领域，具体涉及通过手持设备访问人工现实内容。

**Background (发明背景)**:  
人工现实技术包括虚拟现实、增强现实、混合现实等，通过调整现实呈现给用户。传统上，用户需要通过AR/VR头戴设备访问人工现实内容，但部分用户可能没有此类设备。本发明旨在解决用户使用手持设备（如智能手机或人工现实终端）访问人工现实内容时，无法准确获取用户头部姿态的问题。

**Summary (发明总览)**:  
本发明提出了一种通过手持设备访问人工现实内容的方法。系统首先利用SLAM技术和/或外部跟踪技术确定手持设备的姿态，然后通过面部跟踪技术确定用户的头部姿态。系统结合设备姿态和用户头部姿态，在虚拟空间中准确放置用户的虚拟形象，并基于用户的视角渲染人工现实内容。系统还支持在现实世界与虚拟世界之间进行部分对齐，例如对齐地板表面，以增强沉浸感。此外，系统通过渲染虚拟物品或漫画风格虚拟形象等方式增强用户体验。

**Key Innovation (核心创新)**:  
1. 利用SLAM技术和/或外部跟踪技术确定手持设备的精确姿态，包括设备的高度、前后摄像头方向和姿态等。
2. 通过手持设备的实时面部和/或身体跟踪功能，确定用户的头部姿态，从而实现用户虚拟形象的准确放置。
3. 在现实世界与虚拟世界之间进行部分对齐，例如对齐地板表面，以增强用户在虚拟空间中的定位感和沉浸感。
4. 使用手持设备的摄像头和传感器（如深度传感器）跟踪用户的双手、手臂和其他身体动作，实现与虚拟对象或其他用户的互动。
5. 渲染与用户实际动作相对应的虚拟形象，但进行适当调整以改善用户体验，例如避免虚拟形象完全镜像手持设备的单手姿态。
6. 为用户提供虚拟物品（如武器、王冠、面具等），并将其叠加到用户的真实形象上，以增强虚拟形象的表现力。
7. 通过渲染虚拟对象的阴影，为手持设备用户提供深度提示，帮助其识别虚拟对象的位置、距离、大小和形状，从而提升在虚拟空间中的感知能力。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488679633)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260295410)**
<br/><br/>

---


<br/>

### 38. 触摸输入设备

**Title (EN)**: TOUCH INPUT DEVICE  
**Pub. No.**: US20260299715

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Thomas Joseph LONGO](https://patents.google.com/?inventor=Thomas+Joseph+LONGO&country=US&num=100&sort=new), [Tianyu ZHAO](https://patents.google.com/?inventor=Tianyu+ZHAO&country=US&num=100&sort=new), [Nayeem Sardarsab DESAI](https://patents.google.com/?inventor=Nayeem+Sardarsab+DESAI&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种输入设备包括触摸表面和包含开关的印刷电路板。安装支架包括与开关对齐的凸台，多个平面弹簧各自具有固定在安装支架上的支架端和与印刷电路板耦合的相对端。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684377_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及触摸输入设备及其机械结构设计。

**Background (发明背景)**:  
现有触摸输入设备通常依赖多个触摸或压力传感器来检测用户输入，这增加了成本并占用更多空间。
一些设备采用旋转式触摸板，但靠近铰链的触摸输入难以触发开关，而中间区域的输入则可能导致开关触发不一致。
本发明旨在解决上述问题，提供一种能够均匀传递触摸输入负载并可靠触发开关的触摸输入设备。

**Summary (发明总览)**:  
本发明提出了一种新型触摸输入设备，通过在触摸表面下方设置安装支架和多个平面弹簧，实现触摸输入的均匀负载传递。
该设计确保无论触摸输入发生在触摸表面的哪个位置，都能可靠触发开关。
同时，该结构具有低剖面特性，简化了制造工艺并降低了成本。
相较于传统多传感器方案，本发明减少了组件数量并优化了空间利用率。

**Key Innovation (核心创新)**:  
1. 采用安装支架与凸台配合的设计，确保触摸输入的负载能够均匀传递到开关上。
2. 使用多个平面弹簧连接安装支架和印刷电路板，提供稳定的机械支撑并增强触觉反馈。
3. 通过优化弹簧的布置和弹性特性，实现触摸输入的精确触发，提升设备可靠性。
4. 设计具有低剖面特性，减少了设备厚度并简化了整体结构。
5. 相比传统多传感器方案，本设计减少了传感器数量和电路复杂度，降低了制造成本。
6. 该结构适用于各种尺寸和形状的触摸输入设备，包括触摸板和小型触控面板。
7. 应用于笔记本电脑、平板电脑等便携式设备时，能够提供更可靠的用户输入体验并节省内部空间。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684377)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299715)**
<br/><br/>

---


<br/>

### 39. 游戏开发系统中基于人工智能的叙事决策引擎

**Title (EN)**: AI-DRIVEN NARRATIVE DECISION-MAKING ENGINE IN A GAME DEVELOPMENT SYSTEM  
**Pub. No.**: US20260295428

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Lucas Fernán SALVADOR](https://patents.google.com/?inventor=Lucas+Fern%C3%A1n+SALVADOR&country=US&num=100&sort=new), [Kailin ZHENG](https://patents.google.com/?inventor=Kailin+ZHENG&country=US&num=100&sort=new), [Kevin Jusef BASTIAN](https://patents.google.com/?inventor=Kevin+Jusef+BASTIAN&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明描述了用于提供基于人工智能的叙事决策管理的方法、系统及计算机存储介质。该人工智能驱动的叙事决策引擎旨在促进游戏环境中动态的、情境感知的决策制定。其作为受控决策引擎运行，与游戏开发框架集成，通过从预定义的开发者策划的动作中进行选择来增强角色互动（例如，非玩家角色-NPC）。该引擎处理结构化文本输入，评估游戏状态变量，并基于过去的互动、角色记忆和游戏世界情境确定最合适的动作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488679653_1.jpg)

**Technical Field (技术领域)**:  
本专利属于人工智能与游戏开发交叉领域，具体涉及基于人工智能的叙事决策管理技术。

**Background (发明背景)**:  
传统游戏开发依赖手动脚本定义非玩家角色（NPC）行为、对话树和事件触发器，这需要复杂的逻辑系统和基于规则的决策制定。这种方法劳动强度大且耗时，导致NPC互动缺乏灵活性且难以扩展。随着游戏世界的扩大，手动定义游戏行为逻辑的复杂性进一步增加，限制了互动体验的动态性和一致性。

**Summary (发明总览)**:  
本发明提出了一种基于人工智能的叙事决策引擎，通过结构化选择系统实现游戏角色（如NPC）的动态、情境感知行为。开发者提供游戏世界的叙事描述和预定义动作列表，引擎利用大型语言模型（LLM）在受控框架内选择最符合叙事逻辑的动作。该引擎通过跟踪世界状态和角色记忆，支持动态叙事生成，同时确保开发者对所有输出的控制，从而实现一致性、安全性和高质量的决策。

**Key Innovation (核心创新)**:  
1. 采用受控的LLM架构，通过索引选择预定义动作而非生成自由内容，确保决策的安全性和一致性。
2. 提供开发者定义的叙事描述和动作列表，使LLM在自然语言环境下进行情境感知决策。
3. 通过结构化文本描述管理世界状态和角色记忆，支持动态叙事生成并减少手动脚本需求。
4. 引入角色特定记忆和情境感知机制，使NPC行为更具个性化和反应性。
5. 提供开发者对LLM决策的透明审查和调试功能，通过生成叙事理由支持行为优化。
6. 采用即插即用的SDK设计，便于与现有游戏引擎集成并触发动画、对话或环境变化。
7. 应用于大型开放世界游戏时，可显著提升NPC互动复杂性和动态性，同时降低开发成本和复杂性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488679653)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260295428)**
<br/><br/>

---


<br/>

### 40. 语义图像相似性

**Title (EN)**: SEMANTIC IMAGE SIMILARITY  
**Pub. No.**: US20260300384

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Manish GUPTA](https://patents.google.com/?inventor=Manish+GUPTA&country=US&num=100&sort=new), [Niraj Nrisinvha BHILEGAONKAR](https://patents.google.com/?inventor=Niraj+Nrisinvha+BHILEGAONKAR&country=US&num=100&sort=new), [Avishek MAZUMDER](https://patents.google.com/?inventor=Avishek+MAZUMDER&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及基于查询图像执行图像搜索，结果包括与查询图像语义信息匹配的图片。例如，使用图像编码器从存储在索引中的图像中提取信息。当接收到查询时，搜索索引以确定潜在匹配项，并在查询图像与潜在匹配项之间进行比较，以确定具有与查询图像匹配语义信息的图像。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685112_1.jpg)

**Technical Field (技术领域)**:  
人工智能；图像搜索；语义信息提取

**Background (发明背景)**:  
现有的图像搜索工具通常基于图像的视觉特征（如颜色、形状等）进行匹配，但这些特征往往与用户查询的语义无关，导致搜索结果不够精准。例如，搜索几何图形或建筑图纸时，常出现与查询图像视觉相似但语义不相关的无关结果。本发明旨在解决这一问题，通过提取图像的语义信息来提供更相关的搜索结果。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的图像搜索系统，通过提取图像的语义信息来识别具有相同或相似含义的图像。该系统使用如Siamese网络、三元组网络或图像编码器等模型来训练并生成图像的语义表示。搜索时，系统将查询图像输入模型并搜索预生成的索引，以找到语义匹配的图像。这种方法相较于传统方法，能够提供更符合用户意图的搜索结果，例如提供几何问题的解决方案或对用户生成的图表进行反馈。

**Key Innovation (核心创新)**:  
1. 采用机器学习模型（如Siamese网络或三元组网络）训练以确定图像之间的语义相似性，从而实现对几何问题、建筑图纸等高语义信息图像的精准匹配。
2. 使用图像编码器解析图像内容，例如通过神经图表解析器将几何图表解析为几何标记数据，用于生成表示几何元素、关系和谓词的标记。
3. 构建基于机器学习模型生成的图像语义表示的索引，该索引包含图像的嵌入向量和几何标记，支持快速语义搜索。
4. 提供用户查询图像的语义匹配结果，例如返回解决几何问题的步骤或提供对用户生成图表的反馈，提升搜索结果的相关性和实用性。
5. 通过比较用户生成的图表与正确表示，提供针对学生和教师的反馈功能，帮助学生学习和教师批改作业。
6. 将该技术应用于建筑图纸和计算机辅助设计图纸的对比，提升工程和设计领域的图像搜索精度。
7. 本发明能够广泛应用于教育、工程设计等领域，为需要处理高语义信息图像的用户提供精准的搜索和反馈工具。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685112)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300384)**
<br/><br/>

---


<br/>

### 41. 基于图像显著性的智能取景方法，考虑点击位置和连续调整

**Title (EN)**: Image Saliency Based Smart Framing with Consideration of Tapping Position and Continuous Adjustment  
**Pub. No.**: US20260303951

**Applicant**: Google LLC  
**Inventor**: [Ruijin Cang](https://patents.google.com/?inventor=Ruijin+Cang&country=US&num=100&sort=new), [Wei Hong](https://patents.google.com/?inventor=Wei+Hong&country=US&num=100&sort=new), [Steven David Hickson](https://patents.google.com/?inventor=Steven+David+Hickson&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种方法包括接收与显示图像相关联的第一用户指示区域。基于第一用户指示区域和显示图像确定第一显著性区域。基于第一显著性区域显示第一放大图像。接收与第一放大图像相关联的第二用户指示区域。基于第二用户指示区域和第一放大图像确定第二显著性区域。基于第二显著性区域显示第二放大图像，其中第二放大图像比第一放大图像进一步放大。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488677430_1.jpg)

**Technical Field (技术领域)**:  
图像处理领域，具体涉及智能取景和图像缩放技术。

**Background (发明背景)**:  
现代计算设备通常配备图像捕捉功能，但固定变焦比限制了用户捕捉特定细节的能力。
手动调整变焦需要用户反复操作，耗时且不够便捷。
现有技术难以自动识别图像中的兴趣区域并智能调整缩放比例。
本发明旨在解决自动识别兴趣区域并实现智能连续缩放的问题。

**Summary (发明总览)**:  
本发明提出了一种基于图像显著性的智能取景方法，通过用户指示区域和图像显著性分析实现自动缩放。
首先，系统根据用户指示区域确定图像中的显著性区域并显示放大图像。
然后，系统根据新的用户指示区域和放大后的图像进一步细化显著性区域并调整缩放比例。
该过程可以重复进行，直到图像聚焦于用户感兴趣的具体目标。
系统还支持自动回退到默认缩放比例或原始视野，以防止过度缩放。
相较于传统手动调整，本发明实现了更智能、更精准的图像取景体验。

**Key Innovation (核心创新)**:  
1. 通过用户指示区域与图像显著性分析结合，智能识别用户感兴趣的目标区域。
2. 采用多级缩放机制，根据用户输入和图像内容逐步调整缩放比例，实现更精准的取景。
3. 系统能够动态更新显著性区域，在放大图像后重新分析以提高识别精度。
4. 支持自动回退机制，在过度缩放或用户输入不明确时恢复到默认缩放比例或原始视野。
5. 通过非接触式用户输入（如点击位置）实现交互式缩放，提升操作便捷性。
6. 该方法可应用于智能手机、相机等设备，为用户提供更智能的图像捕捉体验。
7. 特别适用于复杂场景的拍摄，例如多人合影或包含多个兴趣点的场景，帮助用户快速聚焦目标。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488677430)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260303951)**
<br/><br/>

---


<br/>

### 42. 利用学习目标改进搜索结果

**Title (EN)**: USING LEARNING OBJECTIVES TO IMPROVE SEARCH RESULTS  
**Pub. No.**: US20260300351

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Vyzantinos Repantis](https://patents.google.com/?inventor=Vyzantinos+Repantis&country=US&num=100&sort=new), [Patrick Graves](https://patents.google.com/?inventor=Patrick+Graves&country=US&num=100&sort=new), [Michael W. Thot](https://patents.google.com/?inventor=Michael+W.+Thot&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明提供了一种搜索方法，包括接收知识消费者发出的查询，通过处理器处理查询，生成查询的嵌入，基于生成的嵌入检索与查询相关的多个学习目标（LO），并检索与这些学习目标相关的内容，最后将相关内容提供给知识消费者进行展示。知识消费者可以是人类用户、计算机程序或机器。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685076_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及搜索技术领域，具体为利用学习目标改进搜索结果的技术。

**Background (发明背景)**:  
现有文档索引和检索技术主要依赖近似最近邻（ANN）搜索方法，这些方法在基于相似性度量识别和检索文档方面有效，但无法有效索引和检索与特定用户查询在知识层面上直接相关的分块文档。现有的方法难以处理作者意图与词或标记相似性之间的差异，导致用户难以找到最相关的信息，搜索结果不够准确。

**Summary (发明总览)**:  
本发明提出了一种基于学习目标的搜索解决方案，通过将学习目标与不同格式的文档（如文本、视频片段、代码片段和图像）关联，并使用知识依赖图表示学习目标之间的关系，从而动态地为知识消费者提供更好的搜索和学习体验。该方法通过压缩搜索空间、映射多模态内容到作者意图，并考虑用户专业知识水平，提供个性化的搜索结果。

**Key Innovation (核心创新)**:  
1. 通过学习目标（LO）定义内容作者的意图，并使用元标签将学习目标映射到实际内容，实现搜索空间的压缩。
2. 构建学习目标连接图，并利用知识依赖图表示学习目标之间的关系，以预测用户下一步的学习需求或前提知识。
3. 采用多模态内容检索机制，通过统一的搜索空间格式，实现从文本、视频片段、代码片段等多种格式中检索结果。
4. 基于用户的历史搜索数据或已消费内容，动态调整搜索结果，提供符合用户专业水平和理解能力的个性化学习路径。
5. 通过学习目标而非单纯的内容匹配，确保返回的结果更符合作者的真实意图，即使内容质量本身不是最优。
6. 该方法可应用于教育平台、技术文档检索系统或企业培训系统，为用户提供精准且符合学习需求的搜索结果。
7. 通过学习目标引导的搜索机制，能够提升用户的学习效率，并提供更符合用户需求的个性化内容推荐。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685076)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300351)**
<br/><br/>

---


<br/>

### 43. 多智能体助手的动态流式决策层级

**Title (EN)**: DYNAMIC STREAMING DECISION HIERARCHY FOR MULTIPLE AGENT ASSISTANTS  
**Pub. No.**: US20260303390

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Pritesh Rajesh KANANI](https://patents.google.com/?inventor=Pritesh+Rajesh+KANANI&country=US&num=100&sort=new), [Madhu SUDAN](https://patents.google.com/?inventor=Madhu+SUDAN&country=US&num=100&sort=new), [Naveen SHRIVASTAVA](https://patents.google.com/?inventor=Naveen+SHRIVASTAVA&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本文披露的技术提供了一种用于会议系统的多智能体助手的动态流式决策层级。系统根据会议参与者的不同角色动态分配不同的专用AI智能体，每个智能体执行与其角色相匹配的专用功能集。在某些实施例中，系统根据各种来源确定要完成的任务，确定完成任务所需角色，并将角色分配给会议参与者。随后，依赖角色的AI智能体被用来指导并辅导每个会议参与者执行与其确定角色相对应的功能。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488688406_1.jpg)

**Technical Field (技术领域)**:  
人工智能，会议管理系统，智能体协作

**Background (发明背景)**:  
现有的协作系统允许用户通过视频流、音频流、共享文件、聊天消息等方式进行沟通。一些系统管理通信会议，但这些系统通常依赖静态配置、预定义规则或用户驱动的流程来分配角色、管理议程和解决冲突。这些系统缺乏实时适应会议动态变化的能力，导致任务分配和执行出现偏差。

**Summary (发明总览)**:  
本发明提出了一种动态分配AI智能体的方法，通过实时分析会议内容和参与者信息，为不同角色分配专用智能体。系统首先确定会议任务，然后确定所需角色并分配给选定的参与者。智能体根据角色指导参与者执行相应功能。本发明通过整合博弈论模型（如纳什均衡）和帕累托优化，实现了实时数据驱动的决策优化，显著提升了资源利用效率和任务执行效果。

**Key Innovation (核心创新)**:  
1. 通过实时分析会议议程、讨论内容和组织数据，动态确定会议任务和所需角色。
2. 基于角色分配专用AI智能体，而非为每个参与者提供通用智能体，提升智能体功能的专业性和效率。
3. 整合博弈论模型（如纳什均衡）和帕累托优化，实现实时数据驱动的角色分配和任务协调。
4. 通过持续监控会议活动，动态部署和移除角色依赖的智能体，优化计算资源利用。
5. 为共享角色的参与者提供智能体交互跟踪，避免重复指导和功能推荐，提升协作效率。
6. 通过基于角色的访问控制提升系统安全性，根据实时会议内容分析进行细粒度权限管理。
7. 应用于虚拟会议和协作场景，能够在复杂会议环境中提供精准指导和高效任务协调。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488688406)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260303390)**
<br/><br/>

---


<br/>

### 44. 对象检测的动态定制

**Title (EN)**: DYNAMIC CUSTOMIZATION FOR OBJECT DETECTION  
**Pub. No.**: US20260301369

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Mordechai KADOSH](https://patents.google.com/?inventor=Mordechai+KADOSH&country=US&num=100&sort=new), [Tom HIRSHBERG](https://patents.google.com/?inventor=Tom+HIRSHBERG&country=US&num=100&sort=new), [Zvi FIGOV](https://patents.google.com/?inventor=Zvi+FIGOV&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明涉及用于对象检测的动态定制系统和方法。对象检测器使用对象检测模型（例如开放词汇模型）来检测和分类对象。该对象检测器支持无需重新训练模型即可定制分类。通过使用嵌入来区分检测的多种状态，提高了检测过程的准确性和相关性。在示例中，对象检测器通过创建分类器来处理逻辑条件，该分类器经过训练以区分对象的各种组合。本发明支持使用图像进行定制，允许用户提供示例供对象检测器学习。在进一步的示例中，对象检测器的功能扩展到处理实时视频流，例如，用户可以实时标记示例。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686195_1.jpg)

**Technical Field (技术领域)**:  
本发明属于计算机视觉领域，具体涉及对象检测和分类的动态定制技术。

**Background (发明背景)**:  
开放词汇模型是经过训练以识别和分类图像中对象的机器学习模型。现有技术中，训练特定开放词汇模型的方法是针对特定类别训练模型。如果需要对模型进行更改（例如，添加新的对象类别），则需要重新训练模型。这种方法效率低下且耗时。此外，现有技术无法在检测过程中实时更新模型，导致处理复杂条件时灵活性不足。本发明旨在解决这些问题，实现无需重新训练即可动态定制对象检测。

**Summary (发明总览)**:  
本发明提出了一种用于对象检测的动态定制方法，通过在检测过程中实时更新模型，无需重新训练或重新处理图像。该方法利用文本和图像嵌入来区分检测到的对象的不同状态，从而提高检测的准确性和相关性。对象检测器能够处理逻辑条件，例如通过创建分类器来区分对象的不同组合。此外，本发明支持使用图像进行定制，允许用户实时提供示例供系统学习，从而增强系统的适应性和灵活性。

**Key Innovation (核心创新)**:  
1. 实现了无需重新训练即可动态定制对象检测模型，通过在检测过程中实时更新模型参数，避免了重新处理图像或视频的繁琐过程。
2. 使用文本和图像嵌入来区分检测到的对象的不同状态，例如区分"干净的桌子"和"脏的桌子"，从而提高检测的准确性和相关性。
3. 通过创建分类器处理逻辑条件，例如区分对象的不同组合（如"脏的桌子且有瓶子"），使系统能够处理更复杂的检测任务。
4. 支持用户通过提供示例图像来定制对象检测器，使系统能够从用户输入中学习并适应特定的应用场景。
5. 能够处理实时视频流，允许用户实时标记对象作为示例，从而实现动态学习和即时更新。
6. 利用生成模型提供状态对比，使系统能够适应更复杂的条件，例如处理多状态对象或复杂场景。
7. 本发明可应用于智能监控、自动驾驶和机器人视觉等领域，为这些场景提供更高效、更灵活的对象检测解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686195)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301369)**
<br/><br/>

---


<br/>

### 45. 语音认证的实时停止决策

**Title (EN)**: REAL-TIME STOPPING DECISIONS FOR VOICE AUTHENTICATION  
**Pub. No.**: US20260301746

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC.  
**Inventor**: [HAYDAR TALIB](https://patents.google.com/?inventor=HAYDAR+TALIB&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
说话人识别系统的决策阈值是基于冒充者语音样本和真实语音样本的试验分数预先计算得出的，并在实时应用中用于系统在早期检查点做出接受或拒绝语音输入的决策，同时保持最小的准确性损失。该系统被建模为马尔可夫决策过程（MDP），并使用来自多个检查点的试验分数生成最优策略。通过强化学习确定MDP的最优策略，并将其应用于试验分数以推断每个检查点的决策阈值。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488686610_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术领域，具体涉及基于语音生物特征的说话人识别系统。

**Background (发明背景)**:  
说话人识别系统通常用于电话远程认证，广泛应用于门禁控制、敏感信息访问、资金转账、信用卡授权和语音银行等领域。现有系统通过分析语音特征并与预录语音模板比较来生成相似度分数，但面临实时性能与准确性之间的权衡问题，特别是在资源受限的设备上。

**Summary (发明总览)**:  
本发明通过将说话人识别系统建模为马尔可夫决策过程（MDP），并使用强化学习生成最优策略，从而实现决策阈值的预计算。该方法在保证最小准确性损失的前提下，优化了系统在不同检查点的决策时机，提升了实时性能并降低了资源消耗。相较于传统方法，本发明在决策效率和准确性之间实现了更好的平衡。

**Key Innovation (核心创新)**:  
1. 将说话人识别系统建模为马尔可夫决策过程（MDP），通过状态、动作、转移概率、奖励和折扣因子来描述系统行为。
2. 使用强化学习算法生成最优策略，以最大化累积奖励，从而确定在不同检查点的最优决策阈值。
3. 通过定义基于特定误接受率（FAR）和误拒绝率（FRR）的转移概率，实现对早期决策与等待决策之间权衡的优化。
4. 在多个检查点生成试验分数，并利用这些分数训练MDP模型，以实现对系统性能的动态调整。
5. 通过预计算决策阈值，系统能够在保证最小准确性损失的前提下，在早期检查点做出决策，从而减少资源消耗和功耗。
6. 该方法适用于移动设备等资源受限的环境，能够有效降低设备运行成本并提升用户体验。
7. 应用于远程认证、门禁控制和金融交易等场景，能够在保证安全性的同时提高操作效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488686610)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260301746)**
<br/><br/>

---


<br/>

### 46. 基于AI模型和用户配置文件异常检测的安全操作

**Title (EN)**: SECURITY ACTION BASED ON ANOMALY DETECTION USING AI MODEL PROFILES AND USER PROFILES  
**Pub. No.**: US20260300473

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Aviv SHITRIT](https://patents.google.com/?inventor=Aviv+SHITRIT&country=US&num=100&sort=new), [Roee OZ](https://patents.google.com/?inventor=Roee+OZ&country=US&num=100&sort=new), [Idan HEN](https://patents.google.com/?inventor=Idan+HEN&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本文描述了基于AI模型配置文件和用户配置文件进行异常检测并执行安全操作的技术。通过生成与AI模型相关的AI模型配置文件（例如模型会话配置文件、模型响应配置文件等）和与AI模型用户相关的用户配置文件（例如用户会话配置文件、用户提示配置文件等），当传入的AI提示与一个或多个AI模型配置文件和/或用户配置文件的差异大于或等于差异阈值时，将对传入的AI提示执行安全操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488685211_1.jpg)

**Technical Field (技术领域)**:  
人工智能安全领域，具体涉及AI模型和用户行为异常检测及安全防护技术。

**Background (发明背景)**:  
人工智能模型面临网络安全威胁，如恶意软件感染和未授权访问。攻击者可能通过注入不良信息使AI模型生成不良输出。现有异常检测技术主要针对已知恶意行为，覆盖范围有限，难以应对新型安全威胁，且需要频繁重建AI模型。

**Summary (发明总览)**:  
本发明提出了一种基于AI模型配置文件和用户配置文件进行异常检测并执行安全操作的方法。通过生成AI模型和用户的多种配置文件，并比较传入AI提示与这些配置文件的差异，当差异超过设定阈值时触发安全操作。这种方法能够更全面地理解AI模型和用户行为模式，从而检测出未知恶意行为并提高异常检测的覆盖范围，无需重建AI模型。

**Key Innovation (核心创新)**:  
1. 通过生成AI模型配置文件（如模型会话配置文件和模型响应配置文件），捕捉AI模型在不同会话和响应中的语义特征。
2. 生成用户配置文件（如用户会话配置文件和用户提示配置文件），分析用户与AI模型交互的行为模式。
3. 利用嵌入技术生成特征向量（如模型会话特征向量、模型响应特征向量、用户会话特征向量和用户提示特征向量），实现对AI模型和用户行为的深度语义表示。
4. 通过比较传入AI提示与AI模型配置文件和用户配置文件的差异，触发安全操作，实现对异常行为的实时检测。
5. 采用差异阈值机制，灵活调整异常检测的敏感度，适应不同场景的安全需求。
6. 该方法能够检测未知恶意行为，提高异常检测的覆盖范围，无需重建AI模型，降低了安全防护的成本和复杂性。
7. 适用于AI助手、聊天机器人等AI应用场景，提供更强大的安全防护能力，防止恶意攻击和数据泄露。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488685211)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260300473)**
<br/><br/>

---


<br/>

### 47. 用户计算设备的电路连接系统

**Title (EN)**: Circuitry Connection System for User Computing Device  
**Pub. No.**: US20260302662

**Applicant**: Google LLC  
**Inventor**: [Chih Yeh Wang](https://patents.google.com/?inventor=Chih+Yeh+Wang&country=US&num=100&sort=new), [Joe Chen](https://patents.google.com/?inventor=Joe+Chen&country=US&num=100&sort=new), [Shih-Hsien Yang](https://patents.google.com/?inventor=Shih-Hsien+Yang&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种用户计算设备包括一个界定空腔的外壳，以及至少部分位于该空腔内的电路连接系统。该电路连接系统包括包含电路的电路板。电路连接系统还包括一个与电气组件连接并相对于电路板固定的静态引脚，该静态引脚具有平坦的顶面。此外，电路连接系统包括一个电气连接器，其包括与电路板连接的基部、与基部间隔的弯曲部分，以及从基部延伸至弯曲部分的延伸部分。延伸部分被配置为使弯曲部分偏压以接触静态引脚的平坦顶面，从而电连接电气组件与电路板上的电路。弯曲部分被配置为最小化静态引脚与电路板上的电路之间的直流电阻。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488687607_1.jpg)

**Technical Field (技术领域)**:  
用户计算设备领域，具体涉及电路连接系统及电气连接技术。

**Background (发明背景)**:  
用户计算设备通常使用电气连接器将电气组件连接到电路板上的电路。例如，充电设备通过电气连接器与设备电路板连接以对电池充电。现有的电气连接器可能使用引脚偏压接触接触板，但引脚在偏压过程中可能发生位移，导致性能不稳定和可靠性问题，如接触面积变化引起的直流电阻增加或连接中断。

**Summary (发明总览)**:  
本发明提出了一种改进的电路连接系统，通过设计一种电气连接器来提供稳定的电气连接。该连接器包括与电路板连接的基部、与基部间隔的弯曲部分，以及连接两者的延伸部分。延伸部分使弯曲部分偏压接触静态引脚的平坦顶面，从而实现电气组件与电路板电路的稳定连接。弯曲部分的设计旨在最小化直流电阻，提高连接可靠性和充电效率。

**Key Innovation (核心创新)**:  
1. 采用静态引脚设计，其平坦顶面提供稳定的接触表面，避免了传统引脚偏压时的位移问题。
2. 电气连接器的弯曲部分被配置为与静态引脚的平坦顶面接触，通过精确的接触设计最小化直流电阻。
3. 延伸部分的设计确保弯曲部分对静态引片施加适当的偏压力，从而实现可靠且一致的电气连接。
4. 该系统特别适用于充电设备与电路板的连接，通过稳定的电气连接提高了充电效率和可靠性。
5. 通过减少接触面积变化和直流电阻波动，本发明提升了用户计算设备在电气连接方面的整体性能和稳定性。
6. 该技术可应用于智能手表、智能手机、耳机等便携式设备，为其提供更高效的充电和数据传输解决方案。
7. 相比于传统设计，本发明在保证连接稳定性的同时，简化了结构并减少了因位移导致的故障风险。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488687607)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260302662)**
<br/><br/>

---


<br/>

### 48. 片上系统的主动热控制

**Title (EN)**: Proactive Thermal Control for a System-on-Chip  
**Pub. No.**: US20260299523

**Applicant**: Google LLC  
**Inventor**: [Mohsen Heidarinejad](https://patents.google.com/?inventor=Mohsen+Heidarinejad&country=US&num=100&sort=new), [Arpit Mittal](https://patents.google.com/?inventor=Arpit+Mittal&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明描述了用于实现片上系统（SoC）主动热控制的技术和方法。在示例方面，热控制系统利用预测模型，根据SoC的当前运行点和当前温度预测SoC的未来演变。该预测用于主动更新热控制策略，以调整SoC的一个或多个子系统的运行状态。在某些方面，还考虑了用户对设备外壳热限值的感知（例如，用户触摸外壳表面的温度），以确定设备计算出的功率/热指标与用户对外壳热限值感知之间的权衡和矛盾目标。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684167_1.jpg)

**Technical Field (技术领域)**:  
本专利属于片上系统热管理领域，具体涉及基于预测模型的主动热控制技术。

**Background (发明背景)**:  
电子设备通常采用片上系统（SoC）实现其多种功能。SoC包含多个子系统，如CPU、GPU等，这些子系统的运行会产生热量。如果热量积累不受控制，可能导致SoC温度过高，损坏SoC和其他组件，并降低设备可靠性。现有的热节流过程式通常是被动的，存在响应延迟问题，可能导致性能下降和用户体验不佳。

**Summary (发明总览)**:  
本发明提出了一种基于预测模型的主动热控制方案，通过预测SoC子系统的未来温度变化，主动调整热控制策略以优化性能与热管理的平衡。该方案利用实时计算的功率/热指标和加权阈值，动态调整子系统的运行状态。与传统基于固定阈值的方法不同，本发明能够适应不同的工作负载和使用场景，提供更智能的热管理。

**Key Innovation (核心创新)**:  
1. 采用预测模型，根据当前运行状态和温度预测SoC子系统的未来温度变化，实现提前热管理。
2. 通过实时计算的功率/热指标和加权阈值，动态调整热控制策略，避免传统方法的过度节流问题。
3. 结合用户对设备外壳热限值的感知，优化热控制策略，在性能和用户舒适度之间找到平衡。
4. 提供一种自适应的热控制方法，能够根据不同的工作负载和使用场景调整策略，提升系统整体效率。
5. 采用无功耗的被动冷却系统设计，减少对机械冷却组件的依赖，降低系统复杂度和能耗。
6. 通过预测和动态调整，实现更平滑的性能过渡，避免传统方法中常见的性能波动和用户体验下降。
7. 本专利可应用于智能手机、笔记本电脑等高性能计算设备，提供更智能、更高效的热管理方案，提升设备可靠性和用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684167)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299523)**
<br/><br/>

---


<br/>

### 49. 通过用户参与和移动在人工现实环境中进行虚拟组件定位

**Title (EN)**: Virtual Component Positioning in Artificial Reality Via User Engagement and Movement  
**Pub. No.**: US20260299699

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Michael HARRIS](https://patents.google.com/?inventor=Michael+HARRIS&country=US&num=100&sort=new), [Jesse GUERRERO](https://patents.google.com/?inventor=Jesse+GUERRERO&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
本发明通过应用对用户相对于虚拟组件的位置进行的变换，实现人工现实环境中虚拟组件的重新定位。例如，通过用户重新定位动作（如包含参与部分和移动部分的姿势）来应用变换。变换基于用户在重新定位动作期间的动作，对用户的相对位置进行位置变化。从用户的角度来看，用户相对于虚拟组件的相对位置变化会被感知为人工现实环境中虚拟组件显示位置的变化。由于人工现实环境对用户的显示始终从用户的视角出发，因此用户会将相对位置的变化视为虚拟组件显示位置的变化。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488684359_1.jpg)

**Technical Field (技术领域)**:  
人工现实技术领域，具体涉及虚拟组件在人工现实会话中的重新定位。

**Background (发明背景)**:  
人工现实系统（如增强现实和虚拟现实）越来越受欢迎，但现有技术中共享人工现实环境的虚拟组件重新定位机制存在不足。当涉及共享环境中的复杂场景（如不同版本的环境包含共享虚拟组件和不同现实组件）时，现有机制容易失效。本发明旨在解决在共享人工现实环境中高效且实用地重新定位用户相对于虚拟组件位置的问题。

**Summary (发明总览)**:  
本发明提出了一种通过用户参与和移动来重新定位人工现实环境中虚拟组件的方法。用户通过特定动作（如抓取或捏取）参与虚拟组件，并通过移动来调整其相对位置。变换机制根据用户的动作调整其相对于虚拟组件的位置，从而改变虚拟组件的显示位置。该方法不仅提高了重新定位的效率和实用性，还能在共享人工现实环境中避免对其他用户显示的干扰。

**Key Innovation (核心创新)**:  
1. 通过用户特定动作（如抓取或捏取）参与虚拟组件，实现对虚拟组件的精确定位和调整。
2. 基于用户移动的变换机制，动态调整用户相对于虚拟组件的位置，从而改变虚拟组件的显示位置。
3. 在共享人工现实环境中，不同用户视角下的虚拟组件显示位置可以独立调整，避免相互干扰。
4. 实现了对共享虚拟对象和用户化虚拟对象（如用户化身）的差异化处理，确保共享体验的协调性。
5. 通过用户动作和位置变换的结合，提供了一种直观且高效的用户交互方式，提升了用户体验。
6. 适用于增强现实和混合现实环境，能够在现实世界和虚拟世界之间实现无缝融合。
7. 本发明可应用于多人协作场景，如虚拟会议或远程协作，提供更自然和直观的交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488684359)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260299699)**
<br/><br/>

---


<br/>

### 50. 多箔片极耳电池的紧凑设计

**Title (EN)**: COMPACT DESIGN FOR MULTIPLE FOIL TAB BATTERY  
**Pub. No.**: US20260302557

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Wei LI](https://patents.google.com/?inventor=Wei+LI&country=US&num=100&sort=new)  
**Publication Date**: 01.10.2026

**Abstract**:  
一种多箔片极耳电池包括由第一端和第二端之间卷绕多层堆叠形成的卷绕结构。该多层堆叠包括阳极层和从阳极层延伸的第一组箔片极耳，这些箔片极耳在第一连接点处电连接。多层堆叠还包括阴极层和从阴极层延伸的第二组箔片极耳，这些箔片极耳在第二连接点处电连接。引出极耳作为电池的端子，并通过物理上与第一连接点和第二连接点分离的位置与卷绕结构连接。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US488687491_1.jpg)

**Technical Field (技术领域)**:  
电池技术领域，具体涉及多箔片极耳电池的紧凑化设计。

**Background (发明背景)**:  
电池能量密度通常随电极尺寸增大而提高，但现代电池中除电极外的其他组件也占据物理空间。随着电子设备不断小型化，对更紧凑且高能量密度的电池需求日益增加。现有技术中，多箔片极耳电池的箔片连接方式限制了电池的最小厚度，并消耗了电池封装内的长度空间，从而限制了固定尺寸电池的能量密度。

**Summary (发明总览)**:  
本发明提出了一种多箔片极耳电池的紧凑设计，通过将电池的引出极耳与电极上远离箔片极耳焊接点的位置连接，从而实现更高的能量密度。该方法通过电连接第一组箔片极耳和第二组箔片极耳，并分别在不同位置连接引出极耳，避免了传统设计中因箔片连接造成的空间浪费。相较于现有技术，本发明在不增加电池整体尺寸的情况下，提高了能量密度。

**Key Innovation (核心创新)**:  
1. 通过将引出极耳连接在远离箔片极耳焊接点的电极位置，减少了箔片连接对电池厚度的限制。
2. 采用物理分离的连接方式，避免了传统设计中箔片连接占据电池封装内长度的缺陷。
3. 通过优化箔片极耳和引出极耳的连接位置，实现了在不增加电池整体尺寸的情况下提高能量密度。
4. 保持了多箔片极耳电池的层间连接优势，同时减少了因连接点造成的空间浪费。
5. 该设计适用于需要高能量密度和紧凑尺寸的电池应用场景，如便携式电子设备和小型化设备。
6. 通过改进连接方式，降低了电池内部阻抗，提升了电池的整体性能。
7. 该设计可应用于锂离子电池等多种类型的电池，为小型化高能量密度电池提供了一种可行的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US488687491)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260302557)**
<br/><br/>

---


<br/>

### 51. 使用非自回归解码生成音频

**Title (EN)**: GENERATING AUDIO USING NON-AUTOREGRESSIVE DECODING  
**Pub. No.**: US20260290306

**Applicant**: Google LLC  
**Inventor**: [Zalán Borsos](https://patents.google.com/?inventor=Zal%C3%A1n+Borsos&country=US&num=100&sort=new), [Marco Tagliasacchi](https://patents.google.com/?inventor=Marco+Tagliasacchi&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及用于生成输出音频信号的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。在一些实现中，输出音频信号可以通过使用生成神经网络在独立于输出音频信号长度的迭代次数中生成。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487356050_1.jpg)

**Technical Field (技术领域)**:  
人工智能领域，具体涉及神经网络音频生成技术。

**Background (发明背景)**:  
神经网络是一种使用非线性单元预测输入输出的机器学习模型。现有音频生成系统通常依赖自回归解码方法，这导致生成长音频时计算成本高且效率低下。此外，现有系统难以生成语义丰富且多样化的音频内容，如音乐、环境音和复杂声音事件。本发明旨在解决这些问题，通过改进神经网络架构和优化解码过程来提高音频生成效率和质量。

**Summary (发明总览)**:  
本发明提出了一种基于生成神经网络的音频生成系统，能够在独立于音频长度的迭代次数中生成音频。该系统采用非自回归解码方法，通过并行处理多个音频特征来提高生成效率。系统利用局部自注意力机制和卷积增强的注意力模块来优化音频特征处理，同时支持多种音频表示形式，包括声学标记和语义标记。

**Key Innovation (核心创新)**:  
1. 采用非自回归解码方法，通过并行处理多个音频特征实现高效音频生成，避免了传统自回归方法逐个生成音频标记的低效问题。
2. 使用局部自注意力机制，将计算复杂度从自注意力的二次方降低到线性，降低了模型复杂度和推理成本。
3. 引入卷积增强的注意力模块，通过结合卷积层和自注意力层，提升对音频特征的空间和时间建模能力。
4. 支持多种音频表示形式，包括由神经音频编解码器生成的声学标记和辅助音频处理神经网络生成的语义标记，增强了系统的灵活性和适用性。
5. 通过残差向量量化层对音频信号进行分层处理，允许系统在不同量化层级上并行生成多个音频标记，进一步优化计算资源利用。
6. 提供了一种基于置信度的掩码选择机制，系统能够根据神经网络对音频标记的预测置信度选择性地解掩码，从而提高生成音频的质量。
7. 本系统可应用于生成高质量且语义连贯的音频内容，如音乐、语音和环境音，适用于虚拟现实、音频编辑和智能助手等场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356050)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260290306)**
<br/><br/>

---


<br/>

### 52. 用于个性化即时查询建议的媒体消费上下文

**Title (EN)**: MEDIA CONSUMPTION CONTEXT FOR PERSONALIZED INSTANT QUERY SUGGEST  
**Pub. No.**: US20260288857

**Applicant**: GOOGLE LLC  
**Inventor**: [Dhruv Bakshi](https://patents.google.com/?inventor=Dhruv+Bakshi&country=US&num=100&sort=new), [Jakob Nicolaus Foerster](https://patents.google.com/?inventor=Jakob+Nicolaus+Foerster&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及生成搜索查询建议的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。一种方法包括在搜索会话期间接收请求以获取建议的搜索查询；响应于接收建议搜索查询的请求，识别与媒体内容项相关联的实体；基于识别的实体生成建议的搜索查询；并提供数据以在用户界面中呈现生成的建议搜索查询。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354450_1.jpg)

**Technical Field (技术领域)**:  
本专利属于搜索引擎技术领域，具体涉及利用用户媒体消费历史生成个性化搜索建议的技术。

**Background (发明背景)**:  
用户通常通过输入查询来请求搜索引擎提供信息。现有技术中，搜索引擎处理查询并返回相应的信息。然而，现有技术未能充分利用用户的媒体消费历史来生成更相关的搜索建议。这导致搜索建议可能与用户的兴趣或当前情境关联性较低。

**Summary (发明总览)**:  
本发明提出了一种系统，通过分析用户的媒体消费历史来生成个性化的即时搜索建议。该系统识别用户消费过的媒体内容及其相关实体，如演员、导演或制作公司等。在用户请求搜索建议时，系统基于这些实体生成个性化的搜索建议，从而提供更符合用户兴趣的搜索结果。这种方法利用了用户的媒体消费行为来增强搜索建议的相关性和个性化程度。

**Key Innovation (核心创新)**:  
1. 通过识别用户媒体消费历史中的实体（如演员、导演、制作公司等），生成与用户兴趣高度相关的搜索建议。
2. 在搜索会话期间，实时分析用户输入的查询片段或背景音频数据，以识别当前情境下的相关实体。
3. 利用媒体消费数据库，追踪用户已消费的内容，并在生成搜索建议时优先考虑这些内容相关的实体。
4. 引入触发词机制，在特定时间窗口内识别与用户当前消费内容相关的实体，从而提供更精准的搜索建议。
5. 支持处理用户输入的部分查询或背景音频数据，即使在没有明确输入字符的情况下也能生成建议。
6. 通过将用户媒体消费历史与搜索建议生成过程结合，提升搜索建议的个性化和精准度。
7. 该技术可应用于音乐、视频等流媒体平台，为用户提供更智能的搜索体验，例如根据用户当前收听的内容推荐相关艺人或作品。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354450)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288857)**
<br/><br/>

---


<br/>

### 53. 内容过渡方法

**Title (EN)**: Transitioning Of Content  
**Pub. No.**: US20260292298

**Applicant**: Google LLC  
**Inventor**: [Robert Benea](https://patents.google.com/?inventor=Robert+Benea&country=US&num=100&sort=new), [Andrej Cedilnik](https://patents.google.com/?inventor=Andrej+Cedilnik&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种内容过渡的安排方案。通过接收与媒体播放设备相关联的第一信号，其中包含第一用户识别信息，可以识别出第一用户。基于第一用户的识别，可以在媒体播放设备上呈现媒体内容。接收与媒体播放设备相关联的第二信号后，可以确定第一用户已离开媒体播放设备。在确定第一用户已离开后，媒体播放设备将停止呈现媒体内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487358248_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及内容呈现技术领域，具体为基于面部识别的自动内容过渡技术。

**Background (发明背景)**:  
随着内容呈现设备和渠道的增加，用户在不同设备间切换内容时面临诸多不便，例如需要手动登录、查找内容位置等操作。现有的内容切换方式繁琐且耗时，用户体验较差。本发明旨在解决用户在不同设备间无缝过渡内容的问题。

**Summary (发明总览)**:  
本发明提出了一种基于面部识别的内容过渡系统和方法。通过摄像头捕捉图像并识别用户面部，系统可以自动选择并呈现用户偏好的内容。当检测到用户从一个设备转移到另一个设备时，系统无需用户操作即可无缝过渡内容。本发明利用面部识别和计算机视觉算法，实现用户在不同设备间的连续内容体验。

**Key Innovation (核心创新)**:  
1. 通过摄像头捕捉图像并使用面部识别技术识别用户身份，实现基于用户身份的个性化内容推荐。
2. 利用计算机视觉算法（如Eigenfaces、主成分分析、Fisherfaces等）进行人脸检测和识别，确保识别的准确性和效率。
3. 系统记录会话标识符、用户标识符等数据，并与面部识别数据关联，实现跨设备的内容同步和过渡。
4. 通过检测和识别多个观看者并关联当前播放节目的相关信息，系统能够在多人场景下提供无缝的内容过渡体验。
5. 系统能够自动识别用户从一个设备转移到另一个设备，并在新设备上自动开始播放用户之前观看的节目，无需用户手动操作。
6. 通过分析用户面部信息和设备状态，系统可以处理多用户场景下的内容过渡，避免内容冲突。
7. 本发明可应用于智能家居、媒体播放设备等场景，为用户提供连续、无缝的内容消费体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358248)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292298)**
<br/><br/>

---


<br/>

### 54. 具有自动说话人轮换检测的流式语音到语音模型

**Title (EN)**: STREAMING SPEECH-TO-SPEECH MODEL WITH AUTOMATIC SPEAKER TURN DETECTION  
**Pub. No.**: US20260290315

**Applicant**: Google LLC  
**Inventor**: [Fadi Biadsy](https://patents.google.com/?inventor=Fadi+Biadsy&country=US&num=100&sort=new), [Oleg Rybakov](https://patents.google.com/?inventor=Oleg+Rybakov&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种用于语音到语音模型中的轮换检测方法包括接收作为语音到语音（S2S）模型输入的对应于用户语音的声学帧序列。在多个输出步骤中的每个步骤中，通过S2S模型的音频编码器生成对应声学帧的高级特征表示，并通过S2S模型的轮换检测器基于音频编码器在相应输出步骤生成的高级特征表示，确定用户语音在该输出步骤是否处于断点。当轮换检测器确定用户语音处于断点时，该方法包括将由S2S模型的语音解码器合成的输出音频帧序列合成为代表用户语音的时域音频波形合成交替语音。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487356061_1.jpg)

**Technical Field (技术领域)**:  
语音处理技术领域，具体涉及流式语音到语音转换及说话人轮换检测技术。

**Background (发明背景)**:  
现有的语音到语音（S2S）模型通常需要用户手动指示语音的开始和结束，这限制了其在实时应用中的便利性。此外，现有技术难以处理非典型语音或跨语言转换场景中的流畅性需求。本发明旨在解决这些问题，通过自动检测说话人轮换，实现更自然和高效的语音转换。

**Summary (发明总览)**:  
本发明提出了一种基于流式音频输入的语音到语音转换方法，通过实时处理用户语音并自动检测说话人轮换，实现无缝的语音转换。系统使用音频编码器生成高级特征表示，并通过轮换检测器判断当前是否处于说话轮换点。当检测到轮换点时，语音解码器合成对应的输出音频帧并生成合成交替语音。本发明无需用户手动控制，能够实时处理并转换语音，适用于非典型语音和跨语言转换场景。

**Key Innovation (核心创新)**:  
1. 通过音频编码器实时生成声学帧的高级特征表示，为轮换检测提供基础。
2. 引入深度神经网络作为轮换检测器，基于高级特征表示判断说话人轮换点，实现自动检测。
3. 在检测到轮换点时，语音解码器合成输出音频帧并生成时域音频波形，确保合成交替语音的流畅性。
4. 支持非典型语音处理，通过训练模型适应不同类型的用户语音，提高转换质量。
5. 实现跨语言转换功能，将用户语音转换为另一种语言的合成交替语音。
6. 通过训练模型使用标注数据，优化轮换检测和语音转换性能，提升整体准确性和自然度。
7. 适用于实时语音转换应用，如语音助手和翻译设备，提供更自然和高效的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356061)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260290315)**
<br/><br/>

---


<br/>

### 55. 用于微流体热管理的系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR MICROFLUIDIC THERMAL MANAGEMENT  
**Pub. No.**: US20260293048

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ruslan NAGIMOV](https://patents.google.com/?inventor=Ruslan+NAGIMOV&country=US&num=100&sort=new), [Bharath RAMAKRISHNAN](https://patents.google.com/?inventor=Bharath+RAMAKRISHNAN&country=US&num=100&sort=new), [Husam Atallah ALISSA](https://patents.google.com/?inventor=Husam+Atallah+ALISSA&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种热管理设备包括具有第一周边侧和第二周边侧的微流体体积，并包含至少一个热元件；一个通往微流体体积的第一端口；一个从微流体体积的第二端口；位于第一端口的入口阀；位于第二端口的出口阀；以及与入口阀和/或出口阀的部分机械连接的阀压电元件，用于移动至少一个阀的部分并选择性地允许流体通过微流体体积流动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487359076_1.jpg)

**Technical Field (技术领域)**:  
电子设备的热管理技术，具体涉及微流体冷却系统。

**Background (发明背景)**:  
传统热管理技术通过热扩散器将处理器等发热元件的热量传导至散热器，但需要较大的体积和质量。微流体冷却技术虽然可以直接将工作流体应用于芯片表面，但其温度控制能力受限于工作流体的热容量和流动控制能力。本发明旨在解决现有技术中热管理效率不足的问题，特别是在应对快速变化的散热需求时。

**Summary (发明总览)**:  
本发明提出了一种基于微流体的热管理方案，通过在微流体体积中集成压电驱动的阀门和泵膜，实现对工作流体流动的精确控制。该方案能够根据发热元件的散热需求动态调整流体的流动路径、流量和方向，从而更高效地管理热点温度。与传统热扩散器相比，本发明具有更快的响应速度和更高的热管理效率。

**Key Innovation (核心创新)**:  
1. 采用压电驱动阀门，通过施加电压或电流控制阀门的开闭，实现对微流体体积中流体流动的精确控制。
2. 设计了双向流体歧管结构，允许流体在微流体体积中双向流动，从而优化冷却路径并提高散热效率。
3. 集成了压电泵膜，通过电压或电流驱动改变微流体体积的体积，推动工作流体流动并增强冷却效果。
4. 通过温度、功率消耗或工作负载的实时监测数据，动态调整流体流动参数，实现智能化的热管理。
5. 相较于传统热扩散器，本发明具有更小的体积和更快的响应速度，特别适用于对空间和散热效率要求较高的电子设备。
6. 该技术可应用于处理器、存储器、ASIC等各类发热元件的热管理，提供更灵活和高效的冷却解决方案。
7. 通过对微流体流动的精细控制，本发明能够有效应对突发性热负荷变化，为高性能计算场景提供可靠的热管理支持。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487359076)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260293048)**
<br/><br/>

---


<br/>

### 56. 利用机器学习模型和大型生成模型生成改进的技术报告

**Title (EN)**: GENERATING IMPROVED TECHNICAL REPORTS USING MACHINE-LEARNING MODELS ANDLARGE GENERATIVE MODELS  
**Pub. No.**: US20260288779

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Urszula Stefania CHAJEWSKA](https://patents.google.com/?inventor=Urszula+Stefania+CHAJEWSKA&country=US&num=100&sort=new), [Harsh SHRIVASTAVA](https://patents.google.com/?inventor=Harsh+SHRIVASTAVA&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及使用领域洞察系统，通过机器学习模型和大型生成模型为复杂数据和/或数据稀疏领域提供通俗易懂的描述和洞察。例如，该系统将机器学习模型生成的多种输出格式的数据转换为清晰、准确、易于理解且直截了当的结果。领域洞察系统通过使用基于数据输出类型和报告描述符定制的动态提示来实现这一点，从而提高了大型生成模型的准确性和效率。特别是，该系统使用精心选择参数的专业提示，并在某些情况下使用系统级元提示，以生成准确的领域报告和解释。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354364_1.jpg)

**Technical Field (技术领域)**:  
人工智能，机器学习，大型生成模型，数据处理与分析

**Background (发明背景)**:  
近年来，计算设备在硬件和软件方面取得了显著进步，特别是在处理和分析数据集方面。这些进步催生了能够处理大规模复杂数据集的系统，这些系统通常被数据科学家用于计算密集型任务。然而，这些系统生成的输出虽然技术上正确，但由于其复杂性，用户难以有效解读。此外，某些情况下模型生成的输出存在错误，但由于输出复杂性，难以识别错误或诊断模型或数据集的潜在问题。

**Summary (发明总览)**:  
本发明提出了一种领域洞察系统，通过结合机器学习模型和大型生成模型，从复杂数据集中生成基于领域的报告。该系统利用动态提示，根据数据输出类型和报告描述符指导大型生成模型，从而提高报告的准确性和效率。与现有系统相比，本发明能够更准确地理解数据集的上下文信息，并生成易于理解的通俗语言结果。

**Key Innovation (核心创新)**:  
1. 通过动态提示机制，根据数据输出类型和报告描述符定制大型生成模型的输入，从而提高生成结果的准确性和效率。
2. 使用精心选择参数的专业提示和系统级元提示，确保大型生成模型理解输入数据的上下文、语法和基础信息，避免生成错误结果。
3. 针对样本与特征比例不匹配的数据集（例如样本少、特征多），提供准确的洞察，这是现有系统难以有效分析的领域。
4. 动态提示能够灵活适应多个机器学习模型生成的多格式数据输出，并指导大型生成模型将不同数据输出整合成单一结果。
5. 在必要时使用专用模型对机器学习模型的数据输出进行细化处理，确保在大型生成模型无法高效或准确处理数据时仍能生成高质量的报告。
6. 系统级提示提供领域数据的元信息、报告受众级别等重要上下文信息，使大型生成模型能够更高效地专注于特定领域。
7. 本发明可应用于科学数据分析、实验结果解释等领域，为科学家、学生等用户提供易于理解的通俗语言报告，显著提升数据解读效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354364)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288779)**
<br/><br/>

---


<br/>

### 57. 人工智能驱动的头脑风暴会议引导与模板化

**Title (EN)**: ARTIFICIAL INTELLIGENCE DRIVEN LEADING AND TEMPLATIZING OF IDEATION SESSION  
**Pub. No.**: US20260291766

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Sarah Ragab Ismail SALEH](https://patents.google.com/?inventor=Sarah+Ragab+Ismail+SALEH&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种数据处理系统实现了在与会者关联的多个客户端设备之间的在线会议期间检测触发条件发生的情况，该触发条件的发生表明应启动用于收集参与者想法的头脑风暴会议；基于与在线会议相关的会议信息选择头脑风暴会议模板，每个头脑风暴会议模板包括一个自然语言提示模板，该模板包含向语言模型发出的指令，以生成特定类型的头脑风暴会议议程并根据该议程进行头脑风暴会议；基于头脑风暴会议模板的自然语言提示模板构建提示；并提供该提示。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
人工智能，会议管理，协作工具

**Background (发明背景)**:  
在线会议和协作工具在现代工作环境中越来越普遍，但传统的头脑风暴会议往往缺乏结构化流程，导致效率低下和参与度不足。现有的会议管理系统通常无法根据会议的具体需求自动生成合适的议程或引导流程。

**Summary (发明总览)**:  
本发明提出了一种基于人工智能的会议引导系统，通过检测会议中的触发条件自动启动头脑风暴会议，并利用预定义的模板生成个性化的会议议程。该系统通过自然语言处理技术，根据会议类型和目标自动构建引导流程，从而提高会议效率和参与度。

**Key Innovation (核心创新)**:  
1. 通过检测会议中的触发条件（如关键词、参与者行为等）自动启动头脑风暴会议，确保会议流程的及时性和准确性。
2. 基于会议信息（如主题、参与人数、目标等）选择合适的头脑风暴会议模板，提供个性化的会议引导方案。
3. 利用自然语言提示模板生成详细的会议议程，指导语言模型根据特定类型的头脑风暴会议需求进行流程引导。
4. 通过构建动态提示，将会议模板与实时会议数据结合，实现对会议进程的动态调整和优化。
5. 提供结构化的会议引导流程，帮助参与者更好地聚焦于讨论主题，提高会议效率和产出质量。
6. 该系统可应用于企业会议、创意工作坊、团队协作等多种场景，帮助组织者更高效地管理会议流程。
7. 通过人工智能技术实现会议引导的自动化和智能化，显著减少人工干预，提升会议管理的效率和一致性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487357663)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260291766)**
<br/><br/>

---


<br/>

### 58. 扩展现实表面输入系统、设备和方法

**Title (EN)**: SYSTEMS, DEVICES, AND METHODS FOR EXTENDED-REALITY SURFACE TYPING  
**Pub. No.**: US20260288249

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Karol Constantine Hatzilias](https://patents.google.com/?inventor=Karol+Constantine+Hatzilias&country=US&num=100&sort=new), [Jingming Dong](https://patents.google.com/?inventor=Jingming+Dong&country=US&num=100&sort=new), [Guangxun Liao](https://patents.google.com/?inventor=Guangxun+Liao&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种增强现实头戴式系统，包括用于提供物体追踪的第一图像数据的第一外向摄像头，以及用于深度感测的第二图像数据的第二外向摄像头，其中第二外向摄像头的分辨率高于第一外向摄像头。第一和第二外向摄像头配置为提供图像数据，供人工智能助手在第一时间点进行上下文AI处理，以回答用户查询。此外，第一和第二外向摄像头配置为捕捉与增强现实头戴式设备的第一视野相关的图像数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487353782_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及增强现实和混合现实技术，具体为扩展现实头戴式设备中的表面输入技术。

**Background (发明背景)**:  
混合现实设备需要提供无缝且沉浸式的扩展现实环境，用户可通过手势识别、眼动追踪和/或身体追踪技术与设备交互。然而，现有技术在平衡外形尺寸、重量、功耗、效率、成本、速度以及组件视觉隐蔽性和用户界面无缝性等方面仍存在挑战。

**Summary (发明总览)**:  
本发明提供了一种改进的扩展现实头戴式系统，通过优化摄像头位置减少视觉遮挡，同时降低光学或机械组件的视觉显著性，从而实现更自然和沉浸式的用户交互体验。系统利用外向摄像头进行物体追踪和深度感测，并结合人工智能助手提供上下文感知交互功能。

**Key Innovation (核心创新)**:  
1. 采用双摄像头设计，其中一个摄像头用于高分辨率深度感测，另一个用于物体追踪，通过优化摄像头位置减少视觉遮挡。
2. 结合人工智能助手进行上下文感知处理，能够实时回答用户查询并提供智能交互支持。
3. 提供虚拟扩展现实键盘界面，可投射到物理表面或以三维全息形式显示在用户视野中，支持通过手势或触控设备进行交互。
4. 系统支持多种输入方式，包括空中手势、接触式手势以及通过触控笔或触觉反馈手套进行输入，适应不同用户场景。
5. 设备可与智能手表、中间处理设备等外部设备协同工作，形成一个完整的扩展现实交互系统。
6. 通过优化组件集成和简化设计，在保持功能性的同时降低了系统重量和成本。
7. 本发明可应用于增强现实眼镜和混合现实头戴设备，适用于办公、游戏、教育等多种场景，提供更自然和高效的交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353782)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288249)**
<br/><br/>

---


<br/>

### 59. 基于用户特定文本记录的格式预测

**Title (EN)**: USER-SPECIFIC TEXT RECORD-BASED FORMAT PREDICTION  
**Pub. No.**: US20260289314

**Applicant**: Google LLC  
**Inventor**: [Abraham ITTYCHERIAH](https://patents.google.com/?inventor=Abraham+ITTYCHERIAH&country=US&num=100&sort=new), [Adam TISHOK](https://patents.google.com/?inventor=Adam+TISHOK&country=US&num=100&sort=new), [Max KESSLER](https://patents.google.com/?inventor=Max+KESSLER&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种方法包括识别电子文档中的候选文本部分的输入，从存储的文本记录中识别与候选文本部分对应的存储文本条目。将候选文本部分和存储文本条目的至少一部分作为输入提供给训练好的机器学习模型。从训练好的机器学习模型获得输出，该输出识别(i)候选文本部分的格式类型，以及(ii)格式类型适用于候选文本部分的置信度水平。根据格式类型生成向电子文档用户提供的格式建议通知。根据输出更新存储的文本记录，包括候选文本部分和格式类型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354956_1.jpg)

**Technical Field (技术领域)**:  
电子文档处理领域，具体涉及基于文本匹配的格式预测和自动格式建议技术。

**Background (发明背景)**:  
电子文档处理应用允许用户创建和编辑文档，但手动更改格式既耗时又消耗大量计算资源。现有的格式规则创建方法繁琐且不够全面，而基于模型的格式预测方法往往准确度不足，导致资源浪费。

**Summary (发明总览)**:  
本发明通过分析电子文档中的文本区域，识别候选文本部分并与预定义模式匹配，利用存储的文本记录确认适当的格式类型。通过机器学习模型和文本记录相结合的方式，向用户提供格式建议。该方法减少了手动格式调整的工作量，提高了格式预测的准确性和效率。

**Key Innovation (核心创新)**:  
1. 通过比较文本区域与预定义模式，识别候选文本部分作为格式建议的候选对象。
2. 利用存储的文本记录，包含之前用户接受的格式建议或机器学习模型推荐的格式类型，确保格式建议的准确性。
3. 通过对候选文本部分与存储文本记录中的单词进行逐词匹配，确认格式类型的适用性。
4. 结合机器学习模型和存储文本记录，通过对候选文本部分进行注释生成输入，提高格式预测的准确性。
5. 在用户编辑文档时自动应用格式建议，减少手动调整格式的时间和资源消耗。
6. 适用于协作文档环境，支持多用户同时访问和编辑文档时的格式一致性。
7. 应用于办公软件、云端文档管理平台等场景，提升用户编辑效率并优化资源利用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354956)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289314)**
<br/><br/>

---


<br/>

### 60. 使用机器学习估计物体的3D形状

**Title (EN)**: USING MACHINE LEARNING TO ESTIMATE A 3D SHAPE OF OBJECTS  
**Pub. No.**: US20260284891

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Hakan Boyraz](https://patents.google.com/?inventor=Hakan+Boyraz&country=US&num=100&sort=new), [Charles Swan](https://patents.google.com/?inventor=Charles+Swan&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明公开了用于机器人放置物体的3D形状估计的系统和方法。系统可以从不同视角捕捉物体的图像并生成特征。系统使用机器学习模型（例如神经网络）将体素集内的体素投影到图像中的不同位置。系统基于对应于这些不同位置的初始特征，使用机器学习模型生成体素的第二特征。系统基于第二特征确定体素是否指示物体。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
机器人技术；计算机视觉；3D重建

**Background (发明背景)**:  
在机器人操作中，准确估计物体的3D形状对于物体抓取和放置至关重要。
现有技术通常依赖于单视角图像或简单的几何模型，难以处理复杂形状和遮挡问题。
传统方法在处理多视角数据时计算复杂度高且精度不足。
本发明旨在提供一种更高效、更准确的3D形状估计方法。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的3D形状估计方法，通过多视角图像生成特征并利用神经网络进行体素级别的推理。
系统首先从不同视角捕捉物体图像并提取特征，然后将这些特征与体素关联。
通过神经网络，系统能够推断每个体素是否属于目标物体，从而构建物体的3D形状模型。
相较于传统方法，本发明在处理复杂形状和遮挡时具有更高的准确性和鲁棒性。

**Key Innovation (核心创新)**:  
1. 采用多视角图像特征提取技术，通过不同视角的图像捕捉物体的完整信息。
2. 使用神经网络将体素投影到图像中的不同位置，实现体素与图像特征的精确匹配。
3. 基于多层级特征融合技术，将初始图像特征与体素特征结合，提高形状估计的准确性。
4. 通过体素级别的推理机制，识别每个体素是否属于目标物体，从而构建精确的3D形状模型。
5. 引入自适应权重分配机制，根据不同视角图像的可靠性动态调整特征权重。
6. 该方法可应用于机器人抓取和放置任务中，提高物体操作的精度和效率。
7. 特别适用于处理复杂形状和遮挡情况下的3D重建，为自动化生产线提供更可靠的物体建模方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487350075)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260284891)**
<br/><br/>

---


<br/>

### 61. 集成镜头与框架的头戴式设备

**Title (EN)**: HEAD-MOUNTED DEVICE HAVING LENS INTEGRATED WITH FRAME  
**Pub. No.**: US20260287906

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Sarat Babu](https://patents.google.com/?inventor=Sarat+Babu&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种头戴式显示器（HMD）包括结构框架、波导、目镜侧镜头和外界侧镜头。波导用于将显示光引导至眼球盒区域。目镜侧镜头或外界侧镜头作为一体成型的连续折射材料集成到结构框架中。目镜侧镜头具有第一光学功率，用于将显示光聚焦到眼球盒区域。外界侧镜头具有第二光学功率，第一光学功率和第二光学功率的组合将场景光聚焦到眼球盒区域。波导位于目镜侧镜头和外界侧镜头之间。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
光学显示技术；
头戴式显示设备；
集成光学系统

**Background (发明背景)**:  
头戴式显示器（HMD）通常需要多个光学元件来实现显示和成像功能。
现有技术中，这些光学元件通常是独立组件，导致设备复杂且体积较大。
此外，独立光学元件的组装精度要求高，增加了制造成本。
本发明旨在通过集成光学元件来简化设备结构并降低成本。

**Summary (发明总览)**:  
本发明提出了一种新型头戴式显示器，通过将光学镜头与设备框架集成来简化结构。
具体实现方式是将目镜侧镜头或外界侧镜头作为一体成型的连续折射材料嵌入结构框架中。
波导被放置在目镜侧镜头和外界侧镜头之间，以引导显示光。
这种设计不仅减少了光学元件的数量，还提高了光学系统的集成度和稳定性。
相较于传统HMD，本发明在保证光学性能的同时，显著降低了设备复杂度和制造成本。

**Key Innovation (核心创新)**:  
1. 将目镜侧镜头或外界侧镜头作为一体成型的连续折射材料集成到结构框架中，简化了设备结构。
2. 通过波导将显示光引导至眼球盒区域，并利用目镜侧镜头的第一光学功率进行聚焦。
3. 结合外界侧镜头的第二光学功率，实现场景光的高效聚焦，提升显示效果。
4. 波导被精确放置在目镜侧镜头和外界侧镜头之间，确保光路设计的合理性。
5. 这种集成设计减少了光学元件数量，降低了设备复杂度和制造成本。
6. 适用于需要轻量化、高集成度的头戴式显示设备，如虚拟现实（VR）和增强现实（AR）设备。
7. 提供了更紧凑的光学系统解决方案，特别适合对设备尺寸和重量有严格要求的应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353406)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260287906)**
<br/><br/>

---


<br/>

### 62. 基于手持设备运动生成合成坐标数据的方法和系统

**Title (EN)**: SYSTEMS AND METHODS FOR GENERATING SYNTHESIZED COORDINATE DATA BASED ON HANDHELD DEVICE MOTION  
**Pub. No.**: US20260288266

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Sheng Shen](https://patents.google.com/?inventor=Sheng+Shen&country=US&num=100&sort=new), [Paul Austin Buckley](https://patents.google.com/?inventor=Paul+Austin+Buckley&country=US&num=100&sort=new), [Qingyi Dong](https://patents.google.com/?inventor=Qingyi+Dong&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种生成合成坐标数据的方法。该方法包括从手持设备的输入执行器接收第一运动数据，第一运动数据代表输入执行器的运动并对应于第一数据格式，确定输入执行器是否满足操作模式切换条件，基于满足操作模式切换条件，至少部分地激活手持设备在第二模式下的操作，从手持设备的传感器接收第二运动数据，第二运动数据代表手持设备的运动并对应于第二数据格式，当手持设备在第二模式下操作时，生成合成坐标数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487353801_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及人机交互技术，具体为基于运动传感器的数据处理和坐标生成技术。

**Background (发明背景)**:  
传统的手持设备通常依赖单一的运动传感器或输入执行器来捕捉用户动作，这限制了设备的交互能力和精度。现有的技术方案在处理不同类型的运动数据时存在兼容性问题，且无法有效融合多种数据源。此外，现有系统在模式切换时可能导致数据丢失或延迟，影响用户体验。本发明旨在解决这些问题，通过优化数据处理和模式切换机制，提升设备交互的准确性和响应速度。

**Summary (发明总览)**:  
本发明提出了一种新的数据处理方法，通过结合输入执行器和传感器的运动数据，生成更精确的合成坐标数据。系统首先接收来自输入执行器的运动数据，并判断是否需要切换操作模式。一旦满足切换条件，系统将激活传感器数据处理模式，并结合两种数据源生成合成坐标数据。这种方法不仅提高了数据处理的效率，还增强了交互的准确性和响应速度。

**Key Innovation (核心创新)**:  
1. 通过融合输入执行器和传感器的运动数据，实现了多源数据的高效整合，提升了数据处理的精度。
2. 设计了操作模式切换机制，能够根据输入执行器的运动数据动态调整设备的工作模式，确保数据处理的连续性和稳定性。
3. 实现了对不同数据格式的兼容处理，通过标准化转换，使得输入执行器和传感器的数据能够无缝融合。
4. 在模式切换过程中，采用数据缓冲技术，避免了数据丢失和延迟，提高了系统的响应速度。
5. 通过优化算法，降低了计算复杂度，使得该方法能够在资源受限的手持设备上高效运行。
6. 该技术可应用于虚拟现实、增强现实和游戏控制器等领域，提供更自然和精准的用户交互体验。
7. 特别适用于需要高精度运动跟踪的场景，如运动捕捉和远程操控，为这些应用提供了可靠的技术支持。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353801)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288266)**
<br/><br/>

---


<br/>

### 63. 使用具有3D虚拟地理围栏的空间感知标签实现无菜单操作

**Title (EN)**: MENULESS OPERATIONS USING SPATIALLY AWARE TAGS WITH 3D VIRTUAL GEO-FENCING  
**Pub. No.**: US20260292445

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Charbel KHAWAND](https://patents.google.com/?inventor=Charbel+KHAWAND&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明描述了使用具有虚拟地理围栏边界的空间感知标签实现无菜单操作的方法。处理器上实现的标签管理器获取与选定的地理围栏区域内的超宽带（UWB）启动的发起设备相关的运动数据。运动数据由选定地理围栏区域内的一个或多个UWB启用的响应设备生成。运动数据包括描述发起设备在选定地理围栏区域内3D运动的数据。标签管理器使用运动数据识别发起设备的3D运动序列。标签管理器使用无菜单操作映射表将3D运动序列映射到区域特定和/或用户特定的操作。标签管理器触发选定的地理围栏区域内的目标计算设备执行映射的操作。目标计算设备可以包括地理围栏区域内的用户设备、物联网（IOT）设备以及发起设备本身。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487358411_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及使用超宽带（UWB）设备和地理围栏实现无菜单操作。

**Background (发明背景)**:  
传统的计算设备或物联网设备通常需要用户通过键盘、鼠标或触摸界面手动输入命令来执行操作。尽管图形用户界面（GUI）和菜单系统提供了便利，但创建和管理地理围栏区域仍然需要复杂的操作步骤。这种方式不仅耗时且不够灵活，还限制了用户的操作效率。

**Summary (发明总览)**:  
本发明提出了一种基于空间感知标签和3D虚拟地理围栏的无菜单操作方法。通过UWB设备收集发起设备的3D运动数据，标签管理器识别运动序列并将其映射到预定义操作。目标设备在无需用户手动输入的情况下执行相应操作。该方法支持用户在不同地理围栏区域内使用不同运动序列执行多样化操作，提升了操作的灵活性和用户便利性。

**Key Innovation (核心创新)**:  
1. 利用UWB技术收集发起设备的3D运动数据，实现对用户动作的精确感知和识别。
2. 通过标签管理器将3D运动序列映射到预定义操作，使用户能够通过特定动作序列触发设备功能。
3. 支持在地理围栏区域内实现无菜单操作，用户无需物理接触目标设备即可执行命令。
4. 提供用户可配置的操作模式，允许用户根据个人需求自定义动作与操作的对应关系。
5. 适用于多种设备，包括用户设备、物联网设备以及发起设备本身，增强了系统的通用性。
6. 在嘈杂或安静环境中均能有效工作，解决了语音命令在特定场景下的局限性。
7. 应用于智能家居、办公环境或公共场所时，能够提供更直观、高效且非接触式的设备控制方式，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358411)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292445)**
<br/><br/>

---


<br/>

### 64. 智能家居与物体交互的空间鼠标

**Title (EN)**: SPATIAL MOUSE FOR SMART HOME AND OBJECT INTERACTIONS  
**Pub. No.**: US20260288246

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Kerkil Choi](https://patents.google.com/?inventor=Kerkil+Choi&country=US&num=100&sort=new), [Honghong Peng](https://patents.google.com/?inventor=Honghong+Peng&country=US&num=100&sort=new), [Shuochen Su](https://patents.google.com/?inventor=Shuochen+Su&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及一种系统，包括一个包含多个传感器的装置，用于检测空间鼠标指向的一个或多个物体。该系统还包括一个处理器，用于处理来自多个传感器的数据，基于处理后的数据识别物体，并基于识别的物体执行命令。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487353779_1.jpg)

**Technical Field (技术领域)**:  
智能家居设备领域，具体涉及用于智能家居和物体交互的空间鼠标技术。

**Background (发明背景)**:  
智能家居技术改变了人们与生活环境的交互方式，通过集成先进技术实现了对家庭功能的自动化和控制。然而，传统指向设备如鼠标和触摸板在智能家居环境中存在局限性，主要表现为二维交互方式无法满足智能家居设备的多样化需求，且操作不够直观和便捷。此外，这些设备不支持自然手势或三维运动，限制了用户体验的流畅性和沉浸感。

**Summary (发明总览)**:  
本发明提出了一种用于智能家居和物体交互的空间鼠标解决方案。该装置通过集成多个传感器检测用户指向的物体，并利用处理器识别物体和执行相应命令。系统支持在头戴式设备上显示指针以确认目标，并通过手势识别实现对智能家居设备的直观控制。本发明相较于传统输入设备，提供了更自然、更精确的三维交互方式，提升了智能家居设备的操作效率和用户体验。

**Key Innovation (核心创新)**:  
1. 通过集成多个传感器实现对用户指向物体的精确定位和识别，支持三维空间内的交互。
2. 在头戴式设备上显示指针并覆盖在检测到的目标物体上，使用户能够直观确认空间鼠标指针的位置。
3. 利用传感器数据识别用户的手势，并根据识别结果执行相应的智能家居设备操作，例如开关灯或调节温度。
4. 结合机器学习算法优化物体识别和手势识别的准确性，提高系统的响应速度和可靠性。
5. 支持与增强现实（AR）和虚拟现实（VR）应用的无缝集成，拓展了空间鼠标的应用场景。
6. 通过手势操作模拟鼠标点击功能，使用户能够以更自然的方式与智能家居系统进行交互。
7. 该技术可应用于智能家居控制、混合现实设备交互等场景，为用户带来更直观、高效和沉浸式的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353779)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288246)**
<br/><br/>

---


<br/>

### 65. 虚拟会议背景冻结

**Title (EN)**: VIRTUAL MEETING BACKGROUND FREEZE  
**Pub. No.**: US20260292106

**Applicant**: Google LLC  
**Inventor**: [Ryan Fedyk](https://patents.google.com/?inventor=Ryan+Fedyk&country=US&num=100&sort=new), [Ahmed Hassan Aly Hassan](https://patents.google.com/?inventor=Ahmed+Hassan+Aly+Hassan&country=US&num=100&sort=new), [Anton Volkov](https://patents.google.com/?inventor=Anton+Volkov&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及用于虚拟会议背景冻结的系统和方法，包括确定虚拟会议参与者的第一客户端设备的视频流背景需要修改，去除视频流第一帧中参与者的图像，使用人工智能（AI）模型生成背景图像填充第一帧中去除参与者图像后的区域。对于视频流的一个或多个第二帧，通过将第二帧中参与者的图像叠加到第一帧的背景图像上，生成合成图像，并使用参与者在第二帧中的位置和大小进行叠加。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487358035_1.jpg)

**Technical Field (技术领域)**:  
虚拟会议技术，具体涉及视频流背景处理和自动画面调整。

**Background (发明背景)**:  
虚拟会议平台允许多个参与者通过网络连接并共享音频和视频流进行高效沟通。然而，现有平台通常无法对齐参与者的面部特征或统一调整其大小，导致视觉显示不真实，增加眼睛疲劳和认知负担，影响用户体验。尽管一些系统使用自动画面调整来保持参与者图像大小一致，但这种调整也会导致背景移动，产生不适感。

**Summary (发明总览)**:  
本发明提出了一种在虚拟会议中冻结参与者背景的方法，通过识别视频流的第一帧作为背景，并使用AI模型去除参与者图像后填充背景。随后，对后续帧中的参与者图像进行定位和大小调整，并将其叠加到固定的背景图像上。这样既保持了参与者的中心位置和统一大小，又避免了背景的移动，从而提升用户体验。

**Key Innovation (核心创新)**:  
1. 通过AI模型处理视频流的第一帧，去除参与者图像并生成静态背景，解决了现有技术中背景随参与者移动的问题。
2. 对后续视频帧中的参与者图像进行定位和大小调整，并将其叠加到固定的背景图像上，实现了自动画面调整与背景冻结的结合。
3. 避免了背景的移动，减少了其他参与者因背景变化而产生的晕动症或不适感，提升了整体观看体验。
4. 通过保持参与者图像的相对居中和统一大小，确保了视觉上的一致性，减少了因画面频繁调整带来的疲劳感。
5. 该方法可应用于大规模虚拟会议平台，支持多达上百个客户端设备同时连接，提升了平台的实用性和用户体验。
6. 通过提供静态背景和动态参与者图像的合成显示，为虚拟会议提供了更接近面对面交流的视觉体验。
7. 该技术特别适用于需要长时间专注的会议场景，如商务会议、在线教学等，能够有效降低参与者的视觉疲劳和认知负担。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358035)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292106)**
<br/><br/>

---


<br/>

### 66. 包含弹性背衬层的可折叠显示器

**Title (EN)**: FOLDABLE DISPLAY COMPRISING AN ELASTIC BACKING LAYER  
**Pub. No.**: US20260293004

**Applicant**: Google LLC  
**Inventor**: [William Riis Hamburgen](https://patents.google.com/?inventor=William+Riis+Hamburgen&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种可折叠显示设备包括外壳和与外壳相连的连续显示器。外壳包括第一组件、第二组件以及连接第一和第二组件并定义折叠轴的铰链组件。连续显示器被配置为围绕折叠轴折叠，并包括显示层（包含光学显示器）、覆盖显示层的盖层以及位于显示层下方的背衬层。背衬层包括弹性基体或片材，以及分散在弹性基体或片材中或位于其上的肋条阵列，这些肋条大致平行于折叠轴排列。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487359027_1.jpg)

**Technical Field (技术领域)**:  
可折叠显示技术领域，具体涉及具有弹性背衬层的柔性显示器结构设计。

**Background (发明背景)**:  
显示设备通常希望尽可能增大显示面积，但较大的显示面积会导致设备体积增大，不便于携带。通过折叠设计可以在保持设备紧凑的同时增大显示面积，但折叠区域容易产生折痕，影响显示效果和使用寿命。现有技术难以在保证折叠灵活性的同时提供足够的机械支撑以减少折痕。

**Summary (发明总览)**:  
本发明提出了一种具有弹性背衬层的可折叠显示器设计方案，通过在显示层下方设置包含弹性基体和肋条阵列的背衬层来实现。该设计允许显示器在折叠时通过弹性基体适应弯曲变形，同时利用肋条阵列提供机械支撑以抵抗剪切力和压缩力，从而减少折痕并保持显示稳定性。这种结构在保持设备便携性的同时，提供了更大的显示面积和更好的用户体验。

**Key Innovation (核心创新)**:  
1. 采用弹性基体和肋条阵列组合的背衬层设计，其中弹性基体提供柔性支撑，肋条阵列则增强机械强度。
2. 肋条阵列沿折叠轴方向排列，确保在折叠过程中不会阻碍显示器的弯曲，同时有效分散剪切力。
3. 通过独立调节背衬层的各向异性特性，实现对不同方向上刚度的精确控制，以适应折叠和展开状态下的不同需求。
4. 在折叠状态下，背衬层能够通过弹性变形吸收压缩力，减少折痕的形成。
5. 在展开状态下，肋条阵列提供足够的支撑力，防止显示器出现下垂或变形。
6. 该设计适用于大尺寸便携式设备，如平板电脑和智能手机，显著提升设备的便携性和显示效果。
7. 通过减少折痕和提升机械稳定性，延长了可折叠显示器的使用寿命，并改善了用户交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487359027)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260293004)**
<br/><br/>

---


<br/>

### 67. 用于在成像传感器细节不足时识别手势的泛光灯LED技术，以及使用这些技术的混合现实系统和方法

**Title (EN)**: Techniques for Using Floodlight LEDs When Imaging Sensors Have an Insufficient Level of Detail for Identifying Hand Gestures, and Mixed-Reality Systems and Methods of Using These Techniques  
**Pub. No.**: US20260292120

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Tsz Ho Yu](https://patents.google.com/?inventor=Tsz+Ho+Yu&country=US&num=100&sort=new), [Yiwen Wu](https://patents.google.com/?inventor=Yiwen+Wu&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种混合现实（MR）头戴式设备。该设备包括一组成像传感器和一组泛光灯发光二极管（泛光灯LED），这些传感器和LED沿头戴式设备的前部布置。当MR头戴式设备呈现MR内容时，如果从成像传感器获取的成像数据细节不足以识别手势，则处理器会控制泛光灯LED照亮包含用户手部的物理空间区域。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487358053_1.jpg)

**Technical Field (技术领域)**:  
混合现实（MR）技术领域，具体涉及用于增强手势识别和用户交互的成像与照明传感器布置技术。

**Background (发明背景)**:  
混合现实头戴式设备能够为用户提供沉浸式和互动性强的MR内容，但这种互动方式对环境条件（如照明）有较高要求。现有的成像传感器在低光照或复杂背景下可能无法提供足够的细节来准确识别手势，从而影响用户体验。因此，需要一种解决方案来确保在各种条件下都能有效识别用户手势。

**Summary (发明总览)**:  
本发明通过在MR头戴式设备中集成泛光灯LED来解决手势识别问题。当成像传感器获取的图像数据不足以识别手势时，设备会激活泛光灯LED，照亮用户手部所在的物理空间区域，从而增强成像效果。这种方法通过动态照明补偿了成像传感器在低光照条件下的不足，提高了手势识别的准确性和可靠性。相较于传统方案，本发明能够在更广泛的环境条件下支持MR交互，提升用户体验。

**Key Innovation (核心创新)**:  
1. 在MR头戴式设备中集成了泛光灯LED，用于在成像数据不足时主动照亮用户手部区域。
2. 通过处理器实时监测成像数据的细节水平，并根据判断结果自动控制泛光灯LED的开关。
3. 采用动态照明技术，在不影响用户视觉体验的前提下，精准照亮需要识别的物理空间区域。
4. 结合成像传感器和泛光灯LED的数据处理算法，优化手势识别的准确性和响应速度。
5. 该方案可与多种输入方式（如肌电信号传感器、惯性测量单元等）协同工作，提升系统的整体交互能力。
6. 适用于MR和AR头戴式设备，以及可穿戴设备等硬件平台，具有广泛的适用性。
7. 通过改善低光照条件下的交互体验，本专利特别适用于需要高精度手势识别的应用场景，如虚拟对象操控、空间交互等。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358053)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292120)**
<br/><br/>

---


<br/>

### 68. 确定自动化助手对话状态的方法

**Title (EN)**: DETERMINING STATE OF AUTOMATED ASSISTANT DIALOG  
**Pub. No.**: US20260290334

**Applicant**: GOOGLE LLC  
**Inventor**: [Abhinav Rastogi](https://patents.google.com/?inventor=Abhinav+Rastogi&country=US&num=100&sort=new), [Larry Paul Heck](https://patents.google.com/?inventor=Larry+Paul+Heck&country=US&num=100&sort=new), [Dilek Hakkani-Tur](https://patents.google.com/?inventor=Dilek+Hakkani-Tur&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及确定包含自动化助手和至少一个用户的电子对话的对话状态，并根据确定的对话状态执行操作。对话状态可以表示为一个或多个槽位，每个槽位对应一个或多个候选值以及每个候选值的相应得分（例如概率）。候选值基于对话过程中用户和/或系统的语言处理来确定。在生成给定对话轮次的槽位候选值得分时，通过使用记忆网络处理用户和系统对话来确定各种特征。这些特征可以进一步用于改进对话状态的确定。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487356082_1.jpg)

**Technical Field (技术领域)**:  
人工智能，自动化助手，自然语言处理

**Background (发明背景)**:  
自动化助手通过各种客户端设备与用户交互，并基于对话状态提供响应内容。现有的对话状态确定方法通常依赖于固定的本体论，难以处理槽位值范围大或不确定的情况。此外，这些方法通常需要针对每个槽位或领域进行定制，导致对新槽位或领域的适应性差，且难以捕捉对话中词语之间的长期依赖关系。

**Summary (发明总览)**:  
本发明提出了一种基于记忆网络的对话状态确定方法，通过处理用户和系统的对话内容来生成槽位候选值及其得分。该方法利用双向记忆网络捕捉自然语言中的长期依赖关系，从而改进对话状态估计的准确性。相较于传统方法，本发明无需针对每个槽位或领域进行定制，能够更灵活地处理新槽位和领域，并提供更准确的对话状态估计。

**Key Innovation (核心创新)**:  
1. 使用双向记忆网络处理对话中的用户和系统话语，捕捉自然语言中的长期依赖关系，从而生成更准确的槽位候选值特征。
2. 通过记忆网络生成的系统话语表示和用户话语表示，生成对话轮次的整体话语表示，用于所有槽位候选值的评分。
3. 为每个槽位候选值生成特定特征，这些特征基于双向记忆网络处理对应候选值时的隐藏状态，并结合对话历史中的得分信息。
4. 引入槽位特征，用于特定槽位的所有候选值评分，槽位特征基于系统话语和用户话语是否实例化该槽位。
5. 支持特殊槽位值（如"未定义"和"不关心"）的得分生成，使对话状态估计更加全面和灵活。
6. 通过记忆网络处理去词汇化的用户话语（即将候选值替换为槽位描述符），以更好地捕捉槽位与候选值之间的关系。
7. 本发明可应用于智能助手、对话系统等领域，能够更准确地理解用户意图并生成更合适的响应，尤其适用于处理复杂和动态变化的对话场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356082)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260290334)**
<br/><br/>

---


<br/>

### 69. 管理语音数据延迟

**Title (EN)**: Managing Utterance Data Latency  
**Pub. No.**: US20260290338

**Applicant**: Google LLC  
**Inventor**: [Sunil Kumar](https://patents.google.com/?inventor=Sunil+Kumar&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本文描述了通过蓝牙低功耗（BLE）管理语音数据延迟的各种方法。该技术使用CIS连接将耳机接收到的语音传输到音频主机（AH）。CIS连接可用于传输语音数据（例如唤醒词后跟用户请求）到计算设备，以减少与虚拟助手交互的延迟，从而改善用户体验或执行其他操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487356087_1.jpg)

**Technical Field (技术领域)**:  
蓝牙低功耗通信技术；
语音数据传输；
无线音频设备延迟管理

**Background (发明背景)**:  
蓝牙技术（如蓝牙经典和蓝牙低功耗）被广泛应用于各种设备，支持电话、语音通话、虚拟助手交互和媒体播放等音频用例。
现有技术中，语音数据通常通过异步面向连接链路（ACL）传输，这可能导致与虚拟助手交互时出现延迟，影响用户体验。
本发明旨在解决在多设备连接场景下，语音数据传输延迟影响虚拟助手响应速度的问题。

**Summary (发明总览)**:  
本发明提出了一种通过蓝牙低功耗（BLE）管理语音数据延迟的方法。
核心思路是使用CIS连接传输语音数据，而不是传统的ACL连接。
该方法包括建立CIS连接以传输耳机检测到的语音数据到计算设备。
相较于现有技术，本发明通过CIS连接传输语音数据，显著减少了与虚拟助手交互的延迟。
该方法还支持多设备连接场景下的高效语音数据传输。

**Key Innovation (核心创新)**:  
1. 使用CIS连接传输语音数据，而不是传统的ACL连接，从而减少延迟。
2. 在耳机端检测语音数据，并确定其包含唤醒词的可能性，以决定是否通过CIS连接传输。
3. 专门为语音数据传输设置较大的CIS连接超时值（例如150或200毫秒），以确保数据传输的可靠性。
4. 支持在多设备连接场景下，通过CIS连接高效传输语音数据，避免因其他设备活动导致的延迟。
5. 实现了耳机与计算设备之间的双CIS连接，其中一个用于语音数据传输，另一个用于音频流量。
6. 耳机之间通过中继链路连接，以支持真无线立体声（TWS）耳机的数据传输。
7. 该技术可应用于智能耳机和虚拟助手交互场景，显著提升用户与语音助手的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356087)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260290338)**
<br/><br/>

---


<br/>

### 70. 使用音频分区的虚拟环境缩放

**Title (EN)**: VIRTUAL ENVIRONMENT SCALING USING AUDIO ZONING  
**Pub. No.**: US20260292436

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Pierre Seigneurbieux](https://patents.google.com/?inventor=Pierre+Seigneurbieux&country=US&num=100&sort=new), [Kent Jolly](https://patents.google.com/?inventor=Kent+Jolly&country=US&num=100&sort=new), [Peter James Alexander](https://patents.google.com/?inventor=Peter+James+Alexander&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种实施方式包括在本地设备上渲染本地音频流和邻域音频流，其中本地音频流包含由本地音频混音器从多个本地音频源生成的本地音频混合，邻域音频流包含由邻域音频混音器从多个邻域音频源生成的邻域音频混合。一种实施方式包括在本地设备上生成输出音频流，该输出音频流包含从与用户共置的音频源收集的音频，该共置音频源与本地设备为其渲染本地音频流和邻域音频流的用户共置。一种实施方式包括将输出音频流发送到本地音频混音器。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
音频处理技术领域，具体涉及虚拟环境中的音频分区和音频流混合。

**Background (发明背景)**:  
在虚拟现实和增强现实应用中，音频环境需要根据用户位置动态调整。
现有技术通常难以有效处理多个音频源并保持音频环境的真实感。
同时，音频混合和渲染的效率问题也限制了用户体验。
本发明旨在解决音频环境缩放中的实时性和真实感问题。

**Summary (发明总览)**:  
本发明提出了一种基于音频分区的虚拟环境缩放方法，通过本地和邻域音频流的分离处理，实现对音频环境的动态调整。
具体实现包括在本地设备上渲染本地和邻域音频流，并收集共置音频源的音频以生成输出音频流。
该方法通过分离音频处理路径，提高了音频环境的真实感和处理效率。
相较于现有技术，本发明能够更有效地处理多源音频并保持音频环境的沉浸感。

**Key Innovation (核心创新)**:  
1. 通过分离本地音频流和邻域音频流，实现对音频环境的分区处理，从而提高音频处理的灵活性和效率。
2. 使用本地音频混音器和邻域音频混音器分别处理不同区域的音频源，确保音频混合的准确性和实时性。
3. 引入共置音频源的概念，通过收集与用户共置的音频源信息，增强音频环境的真实感和沉浸感。
4. 在本地设备上实现音频流的生成和渲染，减少对外部服务器的依赖，提高系统的响应速度和可靠性。
5. 通过优化音频流的发送和接收机制，降低延迟，确保音频环境的同步性和一致性。
6. 该方法可应用于虚拟现实、增强现实和混合现实等场景，提供更自然和沉浸的音频体验。
7. 特别适用于多人互动环境，能够有效处理多个用户的音频需求，提升整体用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358401)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292436)**
<br/><br/>

---


<br/>

### 71. 提供安全自动化助手的方法和系统

**Title (EN)**: METHODS AND SYSTEMS FOR PROVIDING A SECURE AUTOMATED ASSISTANT  
**Pub. No.**: US20260288853

**Applicant**: GOOGLE LLC  
**Inventor**: [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new), [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本文描述的实施方式涉及接收用户输入到自动化助手，处理用户输入以确定是否需要来自服务器和/或第三方应用的数据来执行助手命令中包含的特定操作，并生成提示以请求用户同意将请求传输到服务器和/或第三方应用以获取执行特定操作所需的数据。在用户同意的情况下，可以获取数据并用于执行特定操作。在用户不同意的情况下，可以在客户端设备本地生成数据并用于执行助手命令的替代操作。在各种实施方式中，当用户同意将请求传输到服务器和/或第三方应用时，可以随请求一起发送指示，表明从客户端设备接收的数据不能被存储（例如，非暂时性存储）。换句话说，服务器和/或第三方应用可以利用请求中包含的数据生成响应内容，但在生成响应内容后应丢弃请求中包含的数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354446_1.jpg)

**Technical Field (技术领域)**:  
自动化助手技术领域，具体涉及用户数据安全性和隐私保护。

**Background (发明背景)**:  
自动化助手通过与用户进行人机对话来执行任务，但现有技术中，助手通常依赖云端资源或仅在本地执行，这导致在数据安全性和功能完整性之间存在权衡。依赖云端可能带来隐私风险，而仅在本地执行则限制了助手的功能范围。

**Summary (发明总览)**:  
本发明提出了一种安全自动化助手系统，通过动态判断用户输入是否需要云端或第三方数据来执行特定操作，并在必要时请求用户授权传输数据。如果用户同意，则获取所需数据以提供最佳响应；如果用户拒绝，则使用本地数据执行替代操作。该方法在保证用户数据安全的同时，提供了更灵活和优化的助手功能。

**Key Innovation (核心创新)**:  
1. 实现了自动化助手在云端和本地执行之间的动态切换，根据用户输入和上下文条件决定数据处理方式。
2. 通过机器学习模型对用户输入进行分类，确定是否需要请求用户授权传输数据以执行特定操作。
3. 在用户授权传输数据时，明确指示服务器和第三方应用不得存储来自客户端的数据，确保隐私安全。
4. 在用户拒绝授权时，利用本地数据提供替代操作，例如提供预缓存内容或联系人信息，避免功能完全失效。
5. 使用分类学方法对用户命令进行细粒度分类，例如将搜索查询细分为金融、天气、餐饮等子类别，以实现更精准的授权请求。
6. 通过自然语言处理模型解析用户意图和参数，结合机器学习模型输出，确定用户输入所属的具体类别。
7. 该技术可应用于智能家居、金融服务、法律咨询等场景，在保护用户隐私的同时，提供更智能和个性化的服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354446)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288853)**
<br/><br/>

---


<br/>

### 72. 领域特定对话式自动化助手

**Title (EN)**: DOMAIN-SPECIFIC CONVERSATIONAL AUTOMATED ASSISTANT  
**Pub. No.**: US20260288791

**Applicant**: GOOGLE LLC  
**Inventor**: [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new), [Maryam Karimzadehgan](https://patents.google.com/?inventor=Maryam+Karimzadehgan&country=US&num=100&sort=new), [Lukas Zilka](https://patents.google.com/?inventor=Lukas+Zilka&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及生成领域特定对话式自动化助手的方法和系统。在一些实施例中，使用对话语言模型生成针对一组领域内训练问题的目标答案和目标行动建议。在一些实施例中，对话语言模型进一步用于生成其生成的目标答案的后续问题，并为每个生成的后续问题生成目标答案和目标行动建议。在一些实施例中，处理系统还生成一组领域外训练示例，包括领域外问题、预定的目标答案和预定的目标行动建议。然后训练自动化助手以预测生成的目标答案和目标行动建议。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354377_1.jpg)

**Technical Field (技术领域)**:  
人工智能；对话系统；自动化助手

**Background (发明背景)**:  
近年来，机器学习的发展推动了语言模型的进步。目标是创建一个能够与人类用户进行合理、开放、多轮对话的模型。尽管像GPT-3和最近的LaMDA这样的模型开始实现这一目标，但为了在开放对话中产生合适的结果，这些模型通常非常庞大，运行在极其强大的硬件上，并需要大量涵盖广泛主题的数据进行训练。因此，尽管最先进的对话模型可能能够作为自动化助手，但它们可能比此类任务所需的知识更丰富，并且对于许多设备来说可能太大和/或资源消耗过高。

**Summary (发明总览)**:  
本发明提出了一种利用大型对话语言模型自动生成领域特定训练数据的方法，以训练更小规模的自动化助手。通过使用大型对话模型生成领域内问题的目标答案和行动建议，并进一步生成后续问题和相应的答案及行动建议，系统能够创建大量单轮和多轮对话训练示例。这些训练示例用于训练一个规模更小、适用于特定领域的自动化助手，使其能够在该领域内自然对话并预测何时建议或采取行动。

**Key Innovation (核心创新)**:  
1. 利用大型对话语言模型（如LaMDA或GPT-3）自动生成领域特定训练数据，包括单轮和多轮对话示例。
2. 通过生成后续问题和相应的目标答案及行动建议，构建多轮对话训练示例，提升自动化助手的多轮对话能力。
3. 生成领域外训练示例，包括无法回答的问题和相应的预设答案及行动建议，以增强自动化助手对领域外输入的处理能力。
4. 采用对比损失值的方法训练自动化助手，使其能够根据输入问题生成与目标答案和行动建议相匹配的回答。
5. 训练自动化助手预测是否需要采取行动以及具体行动内容，使其能够在对话中主动建议或执行操作。
6. 通过减少模型参数数量，使自动化助手能够在资源受限的设备（如手机、平板电脑）上运行，同时保持对话的自然性和准确性。
7. 应用于特定领域（如设备操作指导），使自动化助手能够提供精准的问答和行动建议，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354377)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288791)**
<br/><br/>

---


<br/>

### 73. 自动化主题探索

**Title (EN)**: Automated Topic Exploration  
**Pub. No.**: US20260288882

**Applicant**: Google LLC  
**Inventor**: [Jana Stýblová](https://patents.google.com/?inventor=Jana+St%C3%BDblov%C3%A1&country=US&num=100&sort=new), [Cheng-Wei Hu](https://patents.google.com/?inventor=Cheng-Wei+Hu&country=US&num=100&sort=new), [Justin Michael Pacione](https://patents.google.com/?inventor=Justin+Michael+Pacione&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种执行自动化主题探索的方法包括：接收由一个或多个计算设备组成的计算系统发出的启动自动化主题探索的请求；响应该请求，计算系统使用机器学习生成的主题生成模型处理模型输入，以生成主题陈述作为输出；计算系统生成多个信息检索查询，用于查询与主题陈述相关的源文档；计算系统使这些信息检索查询在一个或多个信息检索系统上执行，以返回响应查询的多个候选源文档；计算系统至少收集这些候选源文档的子集，形成建议的源文档集。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354478_1.jpg)

**Technical Field (技术领域)**:  
机器学习；自动化内容探索；信息检索

**Background (发明背景)**:  
在自动化内容探索领域，现有系统生成的内容往往缺乏多样性，导致信息检索和整理过程中出现频繁的冗余。这种重复性不仅浪费计算资源，还降低了系统的效率，因为系统反复处理和呈现相同或密切相关主题的信息。本发明旨在解决这一问题，通过引入机器学习模型生成多样化主题，提高信息检索的效率和多样性。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的自动化主题探索方法，通过用户交互触发主题探索过程，利用机器学习模型生成多样化的主题陈述。随后，系统生成多个信息检索查询以获取相关源文档，并通过过滤和选择机制生成一个推荐文档集。该方法通过减少重复处理和优化信息检索路径，提高了计算效率和用户体验，尤其适用于数字笔记本平台等应用场景。

**Key Innovation (核心创新)**:  
1. 通过用户界面元素触发主题探索，例如"我很好奇"按钮，使用户能够主动发起探索过程。
2. 利用机器学习模型从数据元素语料库中随机选择种子数据（如名词），生成具有吸引力的主题陈述。
3. 采用另一组机器学习模型或启发式方法生成多样化的信息检索查询，确保搜索结果的广度和相关性。
4. 通过机器学习结果选择模型对候选源文档进行过滤和排序，基于如连贯性和渐进复杂性等标准生成推荐文档集。
5. 提供用户界面展示推荐文档集，允许用户选择并在新笔记本中创建包含选定文档的内容。
6. 动态调整数据元素语料库，基于用户信息和当前新闻事件优化主题生成过程。
7. 该方法可应用于数字笔记本平台，帮助用户快速找到相关源文档并创建结构化的学习路径，提高信息获取效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354478)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288882)**
<br/><br/>

---


<br/>

### 74. 表单字段值预测

**Title (EN)**: FORM FIELD VALUE PREDICTION  
**Pub. No.**: US20260289096

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ali ROUDAKI](https://patents.google.com/?inventor=Ali+ROUDAKI&country=US&num=100&sort=new), [Esin SAKA](https://patents.google.com/?inventor=Esin+SAKA&country=US&num=100&sort=new), [Chuang HE](https://patents.google.com/?inventor=Chuang+HE&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明的一些实施例通过提供预测性输入机制来帮助用户在计算机系统中输入文本或其他数据，以完成表单填写。这些实施例收集用户上下文数据，创建包含至少部分上下文数据的提示，将提示提交给预测器，获取预测器的响应，并提供包含或基于预测器响应计算得出的表单字段值建议。一些实施例对上下文数据进行预处理，以验证用户当前是否有权限访问该数据。一些实施例对预测器响应进行后处理，以执行负责任的预测标准、验证用户角色、验证规则或它们的组合。一些实施例包括多个预测器。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354713_1.jpg)

**Technical Field (技术领域)**:  
人工智能；表单自动填充；预测性输入技术

**Background (发明背景)**:  
人工智能模型能够提供各种预测，例如物品分类、事件发生概率或物品相似性等。然而，这些模型有时会输出错误、误导、无关、偏见或冒犯性的结果。尽管人工智能领域已有许多进展，但仍存在改进空间。本发明旨在解决表单填写过程中出现的具体技术挑战，例如数据泄露、权限违规以及预测结果不可靠等问题。

**Summary (发明总览)**:  
本发明提供了一种基于人工智能的表单自动填充技术，通过以下步骤实现：收集用户上下文数据，对数据进行预处理以确保权限合规，将处理后的数据整合到提示中并提交给人工智能模型获取响应，最后将模型响应中的一部分作为表单字段值的预测结果。该技术通过减少用户手动输入时间提高了效率，并通过权限验证和响应后处理机制增强了数据安全性和预测结果的可靠性。

**Key Innovation (核心创新)**:  
1. 通过收集用户上下文数据并验证其访问权限，防止用户访问未授权的数据，从而增强数据安全性。
2. 在提示生成过程中整合预处理后的上下文数据，确保传递给人工智能模型的输入数据合规且无权限违规。
3. 选择合适的人工智能模型作为预测器，根据上下文数据动态调整选择策略，以提高预测准确性。
4. 对模型输出进行后处理，评估其是否符合负责任的人工智能使用标准，避免向用户展示偏见、虚假或误导性数据。
5. 通过规则验证和用户角色匹配机制，确保预测结果符合组织的管理规范和权限限制，避免不必要的资源浪费。
6. 将预测结果应用于表单字段值填充，显著减少用户填写表单的时间，提高工作效率。
7. 本技术可应用于企业级表单解决方案，如Microsoft Power Apps和Microsoft Dynamics 365，为复杂业务流程提供智能化、自动化的数据输入支持。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354713)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289096)**
<br/><br/>

---


<br/>

### 75. 基于自然语言操作指令的图像处理系统和方法

**Title (EN)**: Systems And Methods For Image Manipulation Based On Natural Language Manipulation Instructions  
**Pub. No.**: US20260289845

**Applicant**: Google LLC  
**Inventor**: [Myungsub Choi](https://patents.google.com/?inventor=Myungsub+Choi&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种基于自然语言操作指令的图像处理计算机系统和方法。本发明引入了一个全新的问题领域，即指称对象操作（ROM）。在ROM中，计算机系统旨在根据两个文本描述生成逼真的图像编辑：1）指称输入图像中对象的参考文本；2）描述如何操作被指称对象的靶向文本。本发明所述成功的ROM模型使人们能够仅通过自然语言来操作图像，无需学习复杂的图像编辑软件。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487355539_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及机器学习领域，具体为基于自然语言指令的图像处理技术。

**Background (发明背景)**:  
随着数字内容制作和消费的增加，专业和业余用户对易用的图像和视频编辑工具的需求日益增长。然而，现有工具如专业图像编辑软件通常需要复杂的软件和专业编辑知识。为了使图像编辑对更广泛的用户群体更加友好，最近的研究开始探索使用自然语言进行图像操作，这可以作为一种高度直观的用户界面。现有的方法通常只能对图像进行全局修改，无法对特定对象进行细粒度控制。

**Summary (发明总览)**:  
本发明提出了一种基于自然语言的图像操作方法，通过引入指称对象操作（ROM）这一全新问题领域，实现了更精准的图像编辑。本发明结合了指称图像分割方法和文本引导的扩散模型，使用户能够通过自然语言指令对图像中的特定对象进行操作，而无需复杂的软件操作或专业知识。该方法通过条件无分类器指导方案和局部化排序方法，提升了图像编辑的准确性和鲁棒性。

**Key Innovation (核心创新)**:  
1. 提出了指称对象操作（ROM）这一全新问题领域，通过自然语言指令实现对图像中特定对象的精准操作。
2. 结合了指称图像分割方法和文本引导的扩散模型，实现了基于文本描述的图像编辑。
3. 引入了条件无分类器指导方案，优化了扩散过程的方向性，使编辑结果更符合目标文本描述。
4. 开发了一种新的局部化排序方法，提升了生成编辑的鲁棒性和准确性。
5. 实现了仅在指称区域进行修改的功能，确保编辑后的图像与目标文本描述一致。
6. 提供了无需复杂软件操作或专业知识的图像编辑方式，降低了用户使用门槛。
7. 本发明可应用于智能图像编辑工具、创意设计平台等场景，为用户提供更直观、高效的图像处理体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355539)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289845)**
<br/><br/>

---


<br/>

### 76. 大型语言模型中的指令跟随以减少计算资源消耗

**Title (EN)**: INSTRUCTION FOLLOWING IN LARGE LANGUAGE MODELS TO REDUCE COMPUTATIONAL RESOURCE CONSUMPTION  
**Pub. No.**: US20260289108

**Applicant**: GOOGLE LLC  
**Inventor**: [Ragha Kotikalapudi](https://patents.google.com/?inventor=Ragha+Kotikalapudi&country=US&num=100&sort=new), [Swaroop Mishra](https://patents.google.com/?inventor=Swaroop+Mishra&country=US&num=100&sort=new), [Sahitya Potluri](https://patents.google.com/?inventor=Sahitya+Potluri&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及通过指令分解、自我评估以及可选的渐进式优化来改进大型语言模型（LLM）的指令跟随能力。系统处理器可以获取基于自然语言（NL）的输入，使用LLM生成多个候选响应，并根据NL输入中包含的指令评估这些候选响应，然后逐步优化候选响应，直到满足一个或多个终止条件。在一些实现中，NL输入可以来自客户端设备。在这些实现中，逐步优化的候选响应可以在客户端设备上呈现并响应于NL输入。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354728_1.jpg)

**Technical Field (技术领域)**:  
自然语言处理，
大型语言模型，
指令跟随技术

**Background (发明背景)**:  
大型语言模型（LLM）是一类能够执行各种自然语言处理任务的机器学习模型，如语言生成、机器翻译和问答系统。然而，LLM通常需要大量计算资源，并且容易产生幻觉，即生成与事实不符或无意义的响应。这导致用户需要提供额外的输入来纠正或澄清，从而增加了计算资源的消耗。

**Summary (发明总览)**:  
本发明通过在LLM中引入自我评估和渐进式优化机制来减少计算资源的消耗。其核心思路是让LLM在生成响应时进行自我评估，确保响应符合指令要求，并通过逐步优化来提高响应质量。与现有技术相比，本发明能够减少用户后续输入的次数，提高LLM的指令跟随能力，从而节省计算资源。

**Key Innovation (核心创新)**:  
1. 通过指令分解将复杂指令拆解为更简单的子任务，使LLM能够更准确地理解和执行指令。
2. 引入自我评估机制，LLM在生成响应后自动评估其是否符合输入指令的要求，从而筛选出高质量的响应。
3. 采用渐进式优化方法，逐步改进候选响应，每次迭代选择最有潜力的响应进行优化，以提高最终响应的质量。
4. 在客户端设备上实时呈现逐步优化的响应，使用户能够及时反馈并进一步指导LLM的优化过程。
5. 利用自我评估机制生成合成训练数据，通过标记高质量和低质量响应来微调LLM，从而提高其指令跟随能力。
6. 识别难以处理的NL输入（即"硬"输入），并生成相应的训练数据以专门改进LLM在这些输入上的表现。
7. 将本发明应用于对话系统，如智能助手或聊天机器人，通过持续的人机交互过程帮助用户更高效地完成任务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354728)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289108)**
<br/><br/>

---


<br/>

### 77. 资源高效的多模态自动化代理交互

**Title (EN)**: Resource-Efficient Interaction with a Multi-Modal Automated Agent  
**Pub. No.**: US20260289154

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Jayant SHEKHAR](https://patents.google.com/?inventor=Jayant+SHEKHAR&country=US&num=100&sort=new), [Aman Kumar PANDEY](https://patents.google.com/?inventor=Aman+Kumar+PANDEY&country=US&num=100&sort=new), [Sandra ANIL](https://patents.google.com/?inventor=Sandra+ANIL&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
客户端系统通过代理接口以高效方式与多模态自动化代理进行交互。在提出问题时，客户端系统以预设的图像捕获速率从摄像头或用户界面（UI）系统捕获图像数据实例。客户端系统通过一系列包含内容的消息将捕获的查询数据实例及其伴随的查询数据实例发送到自动化代理，并通过代理接口接收一个或多个来自自动化代理的回复。系统其他特性包括客户端系统对图像数据实例的分辨率降低、仅将图像数据实例的更新部分有选择地转发给代理接口，以及静态或动态地处理图像内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487354779_1.jpg)

**Technical Field (技术领域)**:  
多模态人机交互技术领域，具体涉及资源高效的图像与文本混合交互方法。

**Background (发明背景)**:  
现有的客户端系统通常通过文本或语音消息与自动化代理进行交互，但在无法快速以口头形式传达查询的情况下，这种交互方式效率较低。现有的交互方式未能充分利用图像数据，且在传输过程中可能产生冗余数据，导致资源浪费。

**Summary (发明总览)**:  
本发明提出了一种高效的多模态交互方法，客户端系统通过摄像头或UI系统捕获图像数据，并在提问时将图像数据与查询数据（如音频或文本）一起发送给自动化代理。系统通过降低图像分辨率、仅传输更新部分图像数据等方式减少资源消耗。代理接口根据客户端能力动态插入图像处理指令，从而实现更精准的交互。本发明在不影响交互效果的前提下，显著提升了资源利用效率。

**Key Innovation (核心创新)**:  
1. 通过预设的图像捕获速率在提问时捕获图像数据，并在提问结束时停止捕获，实现精准数据采集。
2. 客户端系统对捕获的图像数据进行分辨率降低处理，例如通过下采样和压缩技术，减少传输数据量。
3. 仅将图像数据的更新部分或变化部分传输给代理接口，避免冗余数据传输，提升传输效率。
4. 当屏幕图像数据未发生变化时，客户端系统不向代理接口提供新的图像数据，进一步节省资源。
5. 代理接口根据客户端的图像捕获能力动态插入图像处理指令（如"视觉提示"），优化多模态交互流程。
6. 通过机器学习模型处理多模态数据，使自动化代理能够更准确地理解用户意图并生成回复。
7. 本技术可应用于智能助手、虚拟客服等场景，在资源受限的设备上提供高效且精准的多模态交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354779)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289154)**
<br/><br/>

---


<br/>

### 78. 公共场所实时繁忙度

**Title (EN)**: Realtime Busyness for Places  
**Pub. No.**: US20260289588

**Applicant**: Google LLC  
**Inventor**: [Frank Russo](https://patents.google.com/?inventor=Frank+Russo&country=US&num=100&sort=new), [Luuk Van Dijk](https://patents.google.com/?inventor=Luuk+Van+Dijk&country=US&num=100&sort=new), [Paul Donnelly](https://patents.google.com/?inventor=Paul+Donnelly&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
通过隐私敏感的方式计算公共场所的实时繁忙度信息，并将其与历史繁忙度信息一起提供显示。首先测量特定公共场所可用的实时位置信息的总量，以确定该场所是否符合隐私资格。如果符合，则基于实时位置信息计算该公共场所的实时繁忙度信息。此外，通过将实时繁忙度信息与历史繁忙度信息进行比较，确定计算出的实时繁忙度信息是否符合准确性资格。如果满足两项资格，则输出该公共场所的实时繁忙度信息。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487355256_1.jpg)

**Technical Field (技术领域)**:  
实时数据处理，位置信息服务，隐私保护技术

**Background (发明背景)**:  
现有地图服务通常提供特定地理位置的历史繁忙度信息，这些信息通常基于数月的访问数据进行平均。然而，长时间的数据聚合需要大量资源，如内存和带宽。此外，对于数据稀疏或噪声较大的小场所，简单的数据平均可能导致结果不准确。本发明旨在解决如何在保护隐私的同时，提供实时且准确的公共场所繁忙度信息的问题。

**Summary (发明总览)**:  
本发明提出了一种实时计算公共场所繁忙度的方法，通过隐私保护机制筛选数据源，并结合历史数据验证信息的准确性。首先，通过对实时位置信息进行聚合和隐私筛选，确定公共场所是否符合隐私资格。然后，基于筛选后的数据计算实时繁忙度，并通过与历史数据的对比验证其准确性。最终，将符合质量要求的实时繁忙度信息提供给用户显示。本发明在保护用户隐私的同时，提高了实时数据的准确性和可用性。

**Key Innovation (核心创新)**:  
1. 通过对用户设备标识符进行哈希处理并统计唯一哈希值，确保在聚合实时位置信息时保护用户隐私。
2. 使用高碰撞率的哈希函数（如布隆过滤器）以较低的计算成本实现对大量标识符的快速处理。
3. 设计了基于数据结构的动态计数机制，每次填充后清空数据结构以减少存储需求并防止长期数据留存。
4. 通过设置阈值（如在1.5天内存储50个唯一哈希值）来判定场所是否符合隐私资格，从而筛选出数据质量较高的场所。
5. 采用第二级数据结构（如10位位向量）对唯一哈希值进行进一步聚合，以实现更细粒度的实时繁忙度计算。
6. 通过将实时繁忙度信息与历史数据进行对比，并结合其他信号进行统计建模，提高信息的准确性。
7. 本发明可应用于地图服务、零售分析等领域，为用户提供实时参考信息，同时保护用户隐私。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355256)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289588)**
<br/><br/>

---


<br/>

### 79. 堆叠用户界面层的倾斜导航

**Title (EN)**: TILT NAVIGATION FOR STACKED USER INTERFACE LAYERS  
**Pub. No.**: US20260288256

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Matthew Joseph SANTONE](https://patents.google.com/?inventor=Matthew+Joseph+SANTONE&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本文介绍了一种用于在智能手机或平板电脑等移动设备上实现堆叠用户界面层倾斜导航的系统。现代移动设备功能强大，已成为许多用户日常生活中不可或缺的一部分。因此，现代软件应用利用不断增长的计算能力和效率，提供了大量多样的功能。不幸的是，功能扩展通常会导致用户界面变得笨重、低效或使用体验不佳。相比之下，本系统将用户界面组织成层，并以堆叠（如卡片堆叠）的形式在移动设备上呈现。通过这种方式，各种用户界面以直观的方式呈现给用户。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487353790_1.jpg)

**Technical Field (技术领域)**:  
移动设备用户界面设计，倾斜感应交互技术，堆叠界面导航

**Background (发明背景)**:  
随着智能手机和平板电脑等移动设备的功能日益强大和多样化，越来越多的用户依赖这些设备完成社交、购物、银行甚至商业运营等重要任务。
相应地，移动设备上的软件应用功能也在不断扩展，利用新的计算能力和效率提供越来越丰富的功能集。
然而，功能扩展导致用户界面变得复杂、低效且使用体验不佳，例如在社交媒体应用中，用户需要多次切换界面才能完成分享图片等操作。
这种复杂性在生产力或专业协作应用中可能导致更严重的问题。

**Summary (发明总览)**:  
本发明提出了一种基于倾斜导航的堆叠用户界面层系统，通过将用户界面组织成堆叠的层来简化移动设备上的操作。
用户通过倾斜设备来切换不同的界面层，系统根据设备的倾斜角度变化来识别用户意图并执行界面切换。
这种导航方式模拟了自然调整视线的方式，减少了多界面切换的复杂性和用户操作负担。
系统通过硬件传感器（如加速度计和陀螺仪）检测设备姿态，并设置默认设备姿态作为基准。
用户界面层可以是同一应用的不同功能模块，也可以是不同应用的界面组合。
倾斜导航提供了一种直观且高效的交互方式，尤其适用于需要频繁切换界面的应用场景。

**Key Innovation (核心创新)**:  
1. 通过硬件传感器（如加速度计和陀螺仪）检测设备倾斜角度变化，实现用户界面层的动态切换。
2. 设置默认设备姿态作为基准，用户通过倾斜设备来触发界面切换，模拟自然调整视线的交互方式。
3. 系统配置倾斜角度阈值，防止误操作，只有当倾斜角度变化超过阈值时才执行界面切换。
4. 在界面切换过程中，通过调整上层界面的透明度来提示用户下方存在其他界面层，提升交互体验。
5. 支持同一应用内不同功能模块的界面层堆叠，以及不同应用界面的组合堆叠，实现多任务处理。
6. 提供平滑的界面过渡效果，使用户在切换界面时感受到无缝衔接，提升操作流畅度。
7. 适用于需要频繁切换界面的应用场景，如文档编辑与即时通讯的协同工作，为用户提供更高效的操作方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353790)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288256)**
<br/><br/>

---


<br/>

### 80. 通过自动化助手命令实现条件性相机控制

**Title (EN)**: CONDITIONAL CAMERA CONTROL VIA AUTOMATED ASSISTANT COMMANDS  
**Pub. No.**: US20260292332

**Applicant**: GOOGLE LLC  
**Inventor**: [Felix Weissenberger](https://patents.google.com/?inventor=Felix+Weissenberger&country=US&num=100&sort=new), [Balint Miklos](https://patents.google.com/?inventor=Balint+Miklos&country=US&num=100&sort=new), [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及一种能够根据用户指定的一个或多个条件来控制相机的自动化助手。当自动化助手检测到特定环境特征出现时，条件即被满足。通过这种方式，用户可以依赖自动化助手来识别并捕捉特定时刻，而无需持续监控相机的取景窗口。在某些实现中，自动化助手捕捉媒体数据的条件可以基于与应用数据及/或其他与自动化助手相关的上下文数据。例如，相机取景窗口中的内容与其他应用界面内容之间的关系可以作为一个条件。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
自动化助手技术；智能相机控制；环境感知与条件触发

**Background (发明背景)**:  
随着智能设备的发展，用户对自动化助手的需求日益增加。现有技术中，相机控制通常需要用户手动操作或预设简单的触发条件。然而，这些方法无法根据复杂的环境特征或应用上下文进行智能判断，导致用户需要持续关注相机画面以捕捉重要时刻。本发明旨在解决这一问题，通过引入基于环境特征和应用上下文的条件性相机控制，提升用户体验。

**Summary (发明总览)**:  
本发明提出了一种基于自动化助手的条件性相机控制方案。用户可以设定特定条件，自动化助手根据这些条件自动识别并捕捉重要时刻。实现路径包括检测环境特征、分析应用上下文数据，并根据这些信息触发相机操作。与传统方法相比，本发明能够智能识别用户需求，减少用户干预，提高捕捉重要时刻的准确性和及时性。

**Key Innovation (核心创新)**:  
1. 通过环境特征检测实现条件触发，例如识别特定场景或物体，从而自动启动相机操作。
2. 结合应用上下文数据进行分析，例如将相机取景内容与应用程序中的其他内容进行关联，以确定捕捉条件。
3. 提供用户自定义条件的功能，允许用户根据个人需求设定触发条件，增强个性化体验。
4. 利用机器学习算法优化条件识别精度，提高在复杂环境下的识别准确率。
5. 实现自动化助手与相机功能的深度整合，支持实时监控和即时响应，减少用户操作步骤。
6. 应用于智能家居、安防监控和日常生活记录等场景，能够在用户未主动操作的情况下捕捉重要时刻。
7. 通过智能条件判断和自动化操作，提升用户捕捉重要时刻的效率和可靠性，同时降低人为疏忽的风险。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358287)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292332)**
<br/><br/>

---


<br/>

### 81. 用于将物品引入环境的站点

**Title (EN)**: Station for inducting item(s) into environment  
**Pub. No.**: US12745012

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Timothy Joseph Jordan](https://patents.google.com/?inventor=Timothy+Joseph+Jordan&country=US&num=100&sort=new), [Allan Katz](https://patents.google.com/?inventor=Allan+Katz&country=US&num=100&sort=new), [Christopher James Thomas](https://patents.google.com/?inventor=Christopher+James+Thomas&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
一种用于将物品引入环境的站点。该站点包括一个用于接收物品的箱体模块，物品可能以盒装形式包装，并配有用于扫描盒子的传感器。站点中的摄像头和照明模块可以在物品从盒子中取出并转移到位于托盘模块上的一个或多个托盘中时读取物品。物品经过摄像头和照明模块上方后被放置到托盘中。传感器用于确定物品被放置到哪一个或哪些托盘中。当托盘装满时，托盘可以被引入环境以进行存储、订单履行等。该站点可用于方便地将物品从盒子中取出并放置到允许自动存储的托盘中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487049556_1.jpg)

**Technical Field (技术领域)**:  
物流自动化技术领域，具体涉及物品分拣和存储的自动化系统。

**Background (发明背景)**:  
随着电子商务的兴起，订单履行、包装和运输的需求显著增加。零售商需要更快速地补充库存，但现有技术无法有效应对这种高频率的补货需求，导致错误和效率低下。

**Summary (发明总览)**:  
本发明提供了一种自动化站点，用于将物品从包装盒中取出并转移到托盘中，以便后续的存储或订单履行。通过集成传感器、摄像头和照明模块，该系统能够高效地识别和跟踪物品的位置。相较于传统的人工操作，本发明提高了物品分拣和存储的效率和准确性，减少了人为错误。

**Key Innovation (核心创新)**:  
1. 采用箱体模块接收包装盒，并通过传感器扫描盒子以获取物品信息，确保物品识别和跟踪的准确性。
2. 集成摄像头和照明模块，在物品从盒子中取出并转移到托盘的过程中进行实时读取和监控。
3. 使用传感器确定物品被放置到哪一个或哪些托盘中，实现对物品位置的精确追踪。
4. 设计托盘模块，当托盘装满时自动将其引入存储环境或订单履行流程，提高操作效率。
5. 通过自动化流程减少人工干预，降低错误率并加快物品分拣和存储速度。
6. 该系统适用于电子商务仓库、零售配送中心等场景，能够处理高频率的物品补充需求。
7. 提供了一种从包装盒到托盘的自动化转移方案，特别适用于需要快速、准确处理大量物品的应用环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487049556)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12745012)**
<br/><br/>

---


<br/>

### 82. 高压釜固化夹具

**Title (EN)**: Autoclave curing jig  
**Pub. No.**: US12741432

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [John Lockleer](https://patents.google.com/?inventor=John+Lockleer&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
本发明涉及用于制造具有光滑凸面的碳纤维部件的装置、组件和工艺。通过将纤维和树脂缠绕在芯模（内模）上形成未固化部件。将一个或多个压板和可选的垫片放置在未固化部件上，并与芯模上的特征对齐。将组件封装在真空袋中并固化。将组件放置在夹具底座上。压缩构件可与夹具底座耦合，以将组件夹持在两者之间。在固化过程中，压缩构件对压板施加压力，将未固化部件压向芯模，从而形成光滑的表面光洁度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487045620_1.jpg)

**Technical Field (技术领域)**:  
碳纤维复合材料制造领域，具体涉及使用内模和高压釜固化工艺制造具有高表面光洁度要求的碳纤维部件。

**Background (发明背景)**:  
在低产量生产中制造碳纤维部件既耗时又昂贵。传统方法通常采用两种主要方式：一种使用分体式外模，另一种使用内模（芯模）。分体式外模方法成本高且复杂，而内模方法难以实现非常光滑的外部表面。本发明旨在解决在低产量生产中制造具有高表面光洁度要求的碳纤维部件时，如何在保持成本效益的同时获得高质量表面光洁度的问题。

**Summary (发明总览)**:  
本发明提出了一种改进的碳纤维部件制造方法，通过在内模外包裹预浸料，并在固化过程中使用夹具施加均匀压力，从而获得高质量的表面光洁度。该方法结合了内模的简单性和外模的表面质量优势，通过优化压力分布和固化过程控制，解决了传统内模方法表面质量不足的问题。

**Key Innovation (核心创新)**:  
1. 采用内模（芯模）作为基础结构，通过在芯模外包裹预浸料形成部件，简化了模具制造过程，降低了成本。
2. 在未固化部件上放置压板和垫片，并通过真空袋封装，确保压力均匀分布，防止气泡和表面缺陷。
3. 使用夹具底座和压缩构件，在固化过程中对压板施加可控压力，进一步确保部件与芯模紧密贴合。
4. 通过优化压力和温度控制参数，在固化过程中实现对部件表面光洁度的精确控制。
5. 该方法结合了内模的简单性和外模的表面质量优势，适用于需要高表面光洁度且产量较低的应用场景。
6. 通过减少对复杂模具的依赖，降低了生产成本和准备时间，同时保持了高质量的表面光洁度。
7. 适用于航空航天、汽车等需要轻量化且对表面质量要求高的领域，能够在低产量生产中实现高效制造。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487045620)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12741432)**
<br/><br/>

---


<br/>

### 83. 用于从分格存储单元中抓取物体的机器人工具及方法

**Title (EN)**: Robotic tool and process for picking objects from compartmented storage units  
**Pub. No.**: US12741816

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Roc Arandes Vilagrasa](https://patents.google.com/?inventor=Roc+Arandes+Vilagrasa&country=US&num=100&sort=new), [Can Erdogan](https://patents.google.com/?inventor=Can+Erdogan&country=US&num=100&sort=new), [Johannes Kulick](https://patents.google.com/?inventor=Johannes+Kulick&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
描述了使用末端执行器从容器中抓取物品的系统和技术。示例系统包括一个包含多个容器的货架。每个容器配置为容纳一个或多个物品。该系统还包括一个具有末端执行器的机械臂，该末端执行器用于从一个或多个容器中抓取目标物品。末端执行器包括：(i) 平行布置的第一和第二板；(ii) 位于第一和第二板之间的可伸缩吸盘。末端执行器配置为延伸可伸缩吸盘以接触目标物品，与目标物品形成密封，在形成密封后，收缩可伸缩吸盘以从容器中移除目标物品，并在收缩可伸缩吸盘后...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US487046044_1.jpg)

**Technical Field (技术领域)**:  
机器人技术；自动化仓储；末端执行器设计

**Background (发明背景)**:  
许多设施（如仓库、工厂、配送中心等）执行物品存储、拣选和运输等任务。这些设施通常使用各种运输设备（如手推车、容器、托盘、箱子等）来运输物品。由于物品种类繁多且尺寸各异，物品在容器中的排列方式也各不相同，因此设计一种能够可靠地从已有多种物品的容器中抓取物品的机器人末端执行器存在困难。

**Summary (发明总览)**:  
本发明提出了一种用于从分格存储单元中抓取物体的机器人工具及方法。其核心思路是设计一种具有可伸缩吸盘的末端执行器，通过平行板结构与吸盘协同工作，实现对不同尺寸和形状物品的可靠抓取。该方法通过吸盘接触目标物品并形成密封，然后通过收缩吸盘将物品从容器中移除，从而解决现有技术中难以适应多种物品的问题。

**Key Innovation (核心创新)**:  
1. 采用平行布置的第一和第二板结构，为吸盘提供稳定的支撑和定位，确保抓取过程中的精确定位。
2. 在平行板之间集成可伸缩吸盘，通过吸盘的伸缩运动实现对目标物品的抓取和释放，适应不同高度和深度的容器。
3. 吸盘设计为可与目标物品形成密封，确保在抓取过程中提供足够的吸附力，适用于各种表面材质的物品。
4. 通过机械臂控制末端执行器的运动轨迹和吸盘的伸缩动作，实现对目标物品的精准抓取和放置。
5. 该设计能够处理容器中多种不同尺寸和形状的物品，提高了机器人抓取系统的通用性和适应性。
6. 适用于仓储和配送中心等场景，能够提高物品拣选效率，减少人工操作的需求，降低运营成本。
7. 通过优化吸盘材料和结构设计，进一步增强对易碎或精密物品的抓取安全性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487046044)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12741816)**
<br/><br/>

---



**Total Patents**: 83  
**Last Updated**: 20261003

---

The Patent Scoop Trio
