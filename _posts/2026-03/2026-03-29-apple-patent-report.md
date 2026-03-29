---
layout: post
title: "Apple 专利小快报 2026-03-29"
date: 2026-03-29 12:00:00 +0800
categories: Apple
---

**New Patents**: 33  

---


<br/>

### 1. 头戴式计算设备的散热风扇控制

**Title (EN)**: FAN CONTROL FOR HEADSET COMPUTING DEVICE  
**Pub. No.**: US20260089874

**Applicant**: Apple Inc.  
**Inventor**: [Kartik R. Venkatraman](https://patents.google.com/?inventor=Kartik+R.+Venkatraman&assignee=Apple&country=US&num=100&sort=new), [Archana Venkatesh](https://patents.google.com/?inventor=Archana+Venkatesh&assignee=Apple&country=US&num=100&sort=new), [Prateek Malhotra](https://patents.google.com/?inventor=Prateek+Malhotra&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明涉及用于控制头戴式计算设备及其他设备组件的电路、方法和装置。示例性实施例可判断头戴式计算设备是否正在被佩戴。如果设备未被佩戴，则可停止风扇运行；如果设备正在被佩戴，则可判断设备温度是否高于第一温度阈值。如果是，则启动风扇；如果设备温度低于第一温度阈值，则关闭风扇。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476396146_1.jpg)

**Technical Field (技术领域)**:  
头戴式计算设备散热控制技术，
智能风扇控制算法，
温度感应与设备状态监测

**Background (发明背景)**:  
近年来，头戴式计算设备等可穿戴设备的市场需求迅速增长。然而，现有技术中缺乏针对设备佩戴状态和温度变化进行智能风扇控制的解决方案。这可能导致设备过热或不必要的能耗。本发明旨在解决这一问题，通过智能控制风扇运行状态来优化设备散热并延长使用寿命。

**Summary (发明总览)**:  
本发明提供了一种智能风扇控制方案，通过监测头戴式计算设备的佩戴状态和温度来动态调整风扇运行。当设备被佩戴且温度超过设定阈值时启动风扇；未佩戴时则关闭风扇。此外，本发明还引入了温度迟滞机制和多级温度阈值控制，以防止风扇频繁启停并优化散热效率。本发明相较于传统方法，通过智能感知设备状态和温度变化，实现了更精准的散热控制。

**Key Innovation (核心创新)**:  
1. 佩戴状态感知与风扇控制联动：
通过传感器检测头戴式计算设备是否被佩戴，当设备被摘下时自动关闭风扇，避免不必要的能耗。
2. 基于温度阈值的智能风扇启动机制：
当设备温度超过第一温度阈值时启动风扇；当温度低于第二温度阈值时关闭风扇，通过温度差值实现风扇启停的迟滞控制，防止风扇频繁开关。
3. 多级温度控制策略：
采用多个温度阈值控制风扇速度，例如在温度超过第一阈值时以低速运行风扇，超过更高阈值时以高速运行，以平衡散热效果和噪音控制。
4. 动态调整运行进程：
当设备温度过高时，可自动降低或停止部分后台进程以加速散热，待温度恢复正常后再恢复运行，从而增强散热效率。
5. 风扇运行时间控制：
在设备被摘下后，风扇可继续运行一段时间以确保设备充分散热，防止因余热导致的后续温度升高。
6. 用户接近度感知：
通过与用户配对的配件（如手表或手机）判断用户是否在设备附近，当用户远离且温度过高时保持风扇运行，确保设备安全。
7. 应用场景与价值：
本发明适用于各类头戴式计算设备，如VR/AR头显等，通过智能散热控制提升设备可靠性和用户体验，同时延长设备使用寿命。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476396146)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089874)**
<br/><br/>

---


<br/>

### 2. 基于情境的数字助手响应

**Title (EN)**: CONTEXTUAL DIGITAL ASSISTANT RESPONSES  
**Pub. No.**: US20260086628

**Applicant**: Apple Inc.  
**Inventor**: [William CARUSO](https://patents.google.com/?inventor=William+CARUSO&assignee=Apple&country=US&num=100&sort=new), [Andrew MUEHLHAUSEN](https://patents.google.com/?inventor=Andrew+MUEHLHAUSEN&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明公开了基于非语言输入和低功耗情境收集提供操作辅助的示例方法。例如，根据情境选择非语言音频事件，并在检测到活跃的非语言音频事件时，根据检测到的音频为用户提供操作辅助；或者，检测到活跃音频事件会触发收集图像情境以提供操作辅助。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392562_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及三维音频效果领域，具体涉及基于情境的非语言音频事件检测和操作辅助技术。

**Background (发明背景)**:  
近年来，计算机系统与三维场景交互或提供三维场景的技术发展迅速。然而，现有系统在处理情境感知和操作辅助时，往往依赖高功耗的数据收集和分析，例如图像数据处理，导致响应速度慢且耗电量大。此外，用户需要频繁手动请求操作辅助，降低了交互效率。

**Summary (发明总览)**:  
本发明提出了一种基于情境的非语言音频事件检测和操作辅助方法。系统首先根据情境信息选择并激活相关非语言音频事件。当检测到这些音频事件时，系统执行相应的操作辅助。此外，系统还可以根据音频事件触发图像数据的收集，以提供更精准的操作辅助。这种方法通过减少数据处理量和用户手动输入，提高了交互效率和设备电池续航能力。

**Key Innovation (核心创新)**:  
1. 基于情境选择非语言音频事件：
系统根据当前情境信息选择相关非语言音频事件，并将其激活。这种方法确保系统只响应与当前情境相关的音频事件，从而提高操作辅助的准确性和效率。
2. 低功耗音频事件检测：
通过音频传感器实时监测环境音频，并在检测到激活的非语言音频事件时触发操作辅助。这种方法避免了高功耗的图像数据处理，降低了系统功耗。
3. 音频触发图像数据收集：
在检测到特定音频事件后，系统会触发图像数据的收集，以提供更精准的操作辅助。这种多模态数据融合的方式提高了操作辅助的准确性和可靠性。
4. 动态更新激活音频事件集：
根据情境变化动态更新激活的非语言音频事件集，确保系统始终响应与当前情境相关的音频事件。这种动态更新机制增强了系统的适应性和灵活性。
5. 减少用户手动输入：
通过主动检测音频事件并执行操作辅助，减少了用户手动请求操作辅助的需求。这种方法提高了用户交互的便捷性和效率。
6. 提高隐私保护：
仅在必要时收集图像数据，并限制数据收集的范围和时间，从而提高了用户隐私保护。这种方法确保图像数据的收集和使用更加安全和合理。
7. 应用场景与价值：
本发明可应用于智能助手、智能家居和可穿戴设备等领域。例如，在智能助手中，系统可以自动识别用户环境中的特定声音并提供相应的操作辅助，如播放音乐或发送消息，从而提升用户体验和设备智能化水平。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392562)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086628)**
<br/><br/>

---


<br/>

### 3. 干眼症预测

**Title (EN)**: DRY-EYE PREDICTION  
**Pub. No.**: US20260083323

**Applicant**: Apple Inc.  
**Inventor**: [Irene CHEN](https://patents.google.com/?inventor=Irene+CHEN&assignee=Apple&country=US&num=100&sort=new), [Emmanuel B. ALABI](https://patents.google.com/?inventor=Emmanuel+B.+ALABI&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
电子设备通过一个或多个传感器获取包括一个或双眼的图像在内的数据，并提取用户一个或双眼的一个或多个特征。根据确定满足一个或多个标准，包括至少一个基于用户一个或双眼特征的眨眼条件标准，电子设备预测与用户一个或双眼相关的干眼症风险。在某些示例中，根据确定存在干眼症风险，电子设备提供一种或多种缓解措施。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476391759_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及眼动监测技术领域，具体为通过传感器数据预测干眼症风险并提供缓解措施。

**Background (发明背景)**:  
随着可穿戴计算设备的普及，一些设备使用摄像头拍摄眼睛图像以跟踪视线方向。然而，现有技术缺乏对干眼症风险的有效预测和缓解机制。
本发明旨在解决这一问题，通过分析眨眼行为等特征预测干眼症风险，并提供相应的缓解措施。

**Summary (发明总览)**:  
本发明提出了一种基于传感器数据的干眼症预测方法，通过分析用户眼睛的图像数据（如热成像和可见光图像）来识别眨眼条件，从而预测干眼症风险。
该方法利用电子设备上的传感器提取眼睛的空间特征，并通过分割技术识别眼睛的不同区域和特征。
系统根据设定的标准判断用户是否存在干眼症风险，并在必要时提醒用户或建议缓解措施，例如调整屏幕亮度和风扇速度以诱导眨眼行为。
相较于现有技术，本发明提供了一种主动监测和缓解干眼症的方法，提升了用户的使用体验和眼部健康保护。

**Key Innovation (核心创新)**:  
1. 通过热成像和可见光图像传感器获取眼睛数据，实现对眨眼条件的精确监测。
技术实现：利用电子设备上的图像传感器捕捉用户眼睛的实时图像数据。
功能：提供高精度的眨眼行为数据，为干眼症预测提供基础。
2. 基于传感器数据提取眼睛的空间特征并进行区域分割。
技术实现：使用图像处理算法分割眼睛的不同区域，并根据温度变化确定冷却速率。
功能：识别眼睛的关键区域和特征，为干眼症风险评估提供依据。
3. 根据眨眼条件和其他特征判断干眼症风险。
技术实现：设定多个标准，包括眨眼频率、眼睛温度变化等，以综合评估干眼症风险。
功能：实现对干眼症风险的智能预测，及时提醒用户。
4. 提供干眼症缓解措施，如调整屏幕亮度和风扇速度。
技术实现：通过控制电子设备的硬件参数（如屏幕亮度和风扇速度）来影响用户的眨眼行为。
功能：主动干预，预防或缓解干眼症症状。
5. 提醒用户并建议医疗跟进。
技术实现：当检测到干眼症风险时，通过电子设备向用户发送通知，并建议进行医疗咨询。
功能：提高用户对干眼症的重视程度，促进及时治疗。
6. 适用于头戴式设备等可穿戴电子产品。
技术实现：将传感器集成到头戴式设备中，实现对用户眼睛的持续监测。
功能：提供便携式的干眼症监测和缓解方案，特别适合长时间使用电子设备的用户。
7. 创新性地结合硬件控制和软件算法，实现对干眼症的主动管理。
技术实现：通过硬件控制和软件算法的协同工作，实时调整设备参数以适应用户的眼部状态。
功能：提供个性化的干眼症管理方案，提升用户的使用舒适度和眼部健康。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476391759)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260083323)**
<br/><br/>

---


<br/>

### 4. 液体摄入速率和体积的追踪

**Title (EN)**: TRACKING RATE AND VOLUME OF LIQUID CONSUMPTION  
**Pub. No.**: US20260087659

**Applicant**: Apple Inc.  
**Inventor**: [Max Zadeh](https://patents.google.com/?inventor=Max+Zadeh&assignee=Apple&country=US&num=100&sort=new), [Shubham Agrawal](https://patents.google.com/?inventor=Shubham+Agrawal&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明公开了用于确定用户液体摄入速率和体积的设备、系统和方法，基于可穿戴设备传感器数据确定的用户属性。例如，过程可获取可穿戴设备上至少一个传感器的传感器数据，该传感器数据对应于用户在液体摄入事件中摄入液体时的活动。基于传感器数据，过程可进一步确定与用户活动相关的液体摄入类型。基于传感器数据和液体摄入类型，过程可进一步确定与活动相关的摄入速率和摄入体积。可选地，可向用户提供反馈。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476393700_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及液体摄入监测领域，具体涉及基于可穿戴设备传感器数据确定液体摄入速率和体积的技术。

**Background (发明背景)**:  
现有用户监测和反馈技术在准确性和效率方面存在改进空间。传统方法难以准确追踪液体摄入的速率和体积，且缺乏对用户行为的实时分析能力。本发明旨在通过可穿戴设备传感器数据提供更精确的液体摄入监测，并提供个性化的反馈。

**Summary (发明总览)**:  
本发明通过可穿戴设备传感器数据确定用户液体摄入的速率和体积。其核心思路是使用传感器数据（如音频、IMU、视觉和生物特征数据）来识别液体摄入活动，并通过液体摄入模型（如机器学习模型或基于规则的模型）计算摄入速率和体积。系统可实时处理数据，并根据用户行为提供个性化反馈。与现有技术相比，本发明提高了液体摄入监测的准确性和用户反馈的个性化程度。

**Key Innovation (核心创新)**:  
1. 利用可穿戴设备传感器数据（如音频、IMU、视觉和生物特征数据）识别液体摄入活动，通过多源数据融合提高液体摄入监测的准确性。
2. 采用液体摄入模型（如机器学习模型或基于规则的模型）实时处理传感器数据，计算液体摄入速率和体积，实现精准监测。
3. 在用户注册过程中对液体摄入模型进行个性化定制，根据用户的特定行为模式调整模型参数，提高监测精度。
4. 提供基于液体摄入类型（如饮用方式、液体种类、液体特性等）的反馈，例如正常饮用、啜饮、使用吸管等不同方式的区分。
5. 结合环境上下文信息（如环境类型、时间段等）提供更智能的液体摄入建议，例如在不同时间段调整液体摄入量。
6. 通过分析液体特性（如粘度、是否含碳酸、温度等）优化液体摄入监测算法，提升对不同类型液体的适应性。
7. 本发明可应用于健康监测、饮食管理、运动追踪等场景，帮助用户追踪液体摄入量、卡路里摄入等健康指标，提供个性化的健康建议。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476393700)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260087659)**
<br/><br/>

---


<br/>

### 5. 基于用户中心坐标系统的连续手势运动映射

**Title (EN)**: Motion Mapping for Continuous Gestures Using User-Centric Coordinate System  
**Pub. No.**: US20260086652

**Applicant**: Apple Inc.  
**Inventor**: [Vinay Chawda](https://patents.google.com/?inventor=Vinay+Chawda&assignee=Apple&country=US&num=100&sort=new), [Chase B. Lortie](https://patents.google.com/?inventor=Chase+B.+Lortie&assignee=Apple&country=US&num=100&sort=new), [Daniel J. Brewer](https://patents.google.com/?inventor=Daniel+J.+Brewer&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明提供了一种用户输入运动映射技术，包括检测用户的输入运动，确定用户中心球坐标系中输入运动的起点，基于确定的起点计算输入运动的弧长，将输入运动的弧长映射到用户输入组件的二维平面，并根据该映射呈现用户输入组件在二维平面上的运动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392589_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及人机交互技术，具体为扩展现实（XR）环境中的手势输入映射技术。

**Background (发明背景)**:  
扩展现实（XR）环境允许用户通过电子设备感知和交互虚拟对象。现有的XR系统通过跟踪用户的物理运动来调整虚拟对象的特性，但用户的手势输入常因人体解剖学限制而产生误操作或抖动问题。现有技术难以准确反映用户意图，影响交互体验。

**Summary (发明总览)**:  
本发明提出了一种基于用户中心坐标系统的运动映射方法，通过将用户的手势运动从球坐标系映射到二维平面坐标系来解决现有技术中的问题。具体实现路径包括：检测用户输入运动，确定运动起点，计算弧长，并将其映射到用户界面平面。本发明通过分解手臂运动的生物力学链，精确计算肩、肘、腕关节的旋转对运动的影响，从而更准确地反映用户意图，提升设备对用户输入的分析能力和用户界面的交互体验。

**Key Innovation (核心创新)**:  
1. 采用用户中心球坐标系进行运动映射，通过检测用户关节位置（如肩、肘、腕）确定运动起点，解决了现有技术中因解剖学限制导致的误操作问题。
2. 通过计算输入运动的弧长并将其映射到二维用户界面平面，实现了更符合用户自然运动习惯的交互方式，减少了意外输入和抖动现象。
3. 创新性地分解手臂运动的生物力学链，分别计算肩、肘、腕关节旋转对运动的影响，从而更准确地反映用户意图，提升输入精度。
4. 在用户界面中呈现运动时，采用向量叠加的方式，将各关节旋转产生的运动分量整合为完整的运动轨迹，确保映射的准确性。
5. 通过更频繁或更精确地获取关节位置（如肩、肘、腕、指尖），结合上下文信息（如手势中心点的运动），提高了用户输入运动的跟踪精度。
6. 本发明可应用于XR系统中的手势交互场景，如AR/MR/VR环境中的虚拟对象操控，为用户提供更自然和精准的交互体验。
7. 特别适用于需要高精度输入的场景，如虚拟键盘输入、3D对象操控等，通过减少误操作和提升交互效率，显著改善用户体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392589)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086652)**
<br/><br/>

---


<br/>

### 6. 基于用户注视的摄像头选择

**Title (EN)**: CAMERA SELECTION BASED ON GAZE  
**Pub. No.**: US20260089387

**Applicant**: Apple Inc.  
**Inventor**: [William D. LINDMEIER](https://patents.google.com/?inventor=William+D.+LINDMEIER&assignee=Apple&country=US&num=100&sort=new), [Devin W. CHALMERS](https://patents.google.com/?inventor=Devin+W.+CHALMERS&assignee=Apple&country=US&num=100&sort=new), [Sean B. KELLY](https://patents.google.com/?inventor=Sean+B.+KELLY&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种电子设备，例如头戴式设备，与一个或多个输入设备通信，包括具有第一镜头的第一摄像头和具有第二镜头的第二摄像头。在某些示例中，该电子设备检测用户对三维环境内物体的注视，并基于第一镜头捕获的图像提取与该物体相关的数据。根据提取的数据，在满足一个或多个标准的情况下，包括当数据质量指标低于质量指标阈值时满足的标准，电子设备基于第二镜头捕获的图像提取数据；如果不满足这些标准，则电子设备不会基于第二镜头捕获的图像提取数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476395611_1.jpg)

**Technical Field (技术领域)**:  
用户交互式摄像头系统；
基于用户注视和图像质量的自适应摄像头选择技术。

**Background (发明背景)**:  
电子设备通常配备多个摄像头，如广角镜头或长焦镜头，用户根据图像需求选择不同镜头进行拍摄。现有多摄像头系统在处理用户注视和图像质量时缺乏智能切换机制，可能导致不必要的传感器激活和资源浪费。本发明旨在解决这一问题，通过基于用户注视和图像质量智能选择摄像头，提高系统效率并优化资源利用。

**Summary (发明总览)**:  
本发明提出了一种基于用户注视的智能摄像头选择方法。电子设备通过检测用户注视方向，识别三维环境中的目标物体，并使用广角镜头初步提取数据。当数据质量低于预设阈值时，系统自动切换到长焦镜头以获取更高质量的数据。该方法通过智能镜头切换，减少传感器持续工作时间，降低处理器和内存负载，节省电池寿命并提高系统响应速度。相较于传统方法，本发明在图像质量和系统效率之间实现了更好的平衡。

**Key Innovation (核心创新)**:  
1. 基于用户注视的感兴趣区域识别：
技术详解：利用用户注视方向确定三维环境中的目标区域。
实现方式：通过摄像头捕捉用户视线方向，结合环境摄像头数据定位目标物体。
功能或解决的问题：提高目标物体识别精度，减少无关区域的数据处理。
2. 质量指标驱动的镜头切换机制：
技术详解：设定图像质量阈值，当数据质量低于阈值时触发镜头切换。
实现方式：实时监测图像质量指标，如清晰度、噪声水平等。
功能或解决的问题：确保图像质量满足任务需求，避免低质量数据影响后续处理。
3. 镜头类型自适应选择：
技术详解：根据目标物体类型和距离选择合适的镜头。
实现方式：分析物体特征和距离信息，动态调整镜头参数。
功能或解决的问题：处理不同场景下的物体识别需求，提高识别准确性和系统鲁棒性。
4. 资源优化管理：
技术详解：通过智能镜头选择减少传感器工作时间，降低处理器和内存负载。
实现方式：仅在必要时激活特定镜头，并限制图像处理区域。
功能或解决的问题：延长电池寿命，降低设备热负荷，节省计算和存储资源。
5. 用户交互增强：
技术详解：将用户注视与语音或文本查询结合，提高操作准确性。
实现方式：分析用户注视区域与查询内容的关联性。
功能或解决的问题：提供更精准的设备响应，提升用户体验。
6. 镜头不可用时的备用方案：
技术详解：当某个镜头不可用时，系统自动切换到备用镜头。
实现方式：监测镜头状态，动态调整镜头选择策略。
功能或解决的问题：确保系统持续可用，提高系统可靠性。
7. 应用场景与价值：
推测应用场景：增强现实（AR）设备、智能眼镜、虚拟现实（VR）系统等。
独特价值：提供更高效、更精准的视觉数据处理能力，提升设备在复杂环境下的适应性和用户体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476395611)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089387)**
<br/><br/>

---


<br/>

### 7. 可穿戴电子设备

**Title (EN)**: WEARABLE ELECTRONIC DEVICE  
**Pub. No.**: US20260086374

**Applicant**: Apple Inc.  
**Inventor**: [Alison B. Shutzberg](https://patents.google.com/?inventor=Alison+B.+Shutzberg&assignee=Apple&country=US&num=100&sort=new), [Brynna E. Freitag](https://patents.google.com/?inventor=Brynna+E.+Freitag&assignee=Apple&country=US&num=100&sort=new), [Ibuki Kamei](https://patents.google.com/?inventor=Ibuki+Kamei&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种可穿戴显示设备包括框架和与框架连接的显示窗口。该设备包括一个固定臂，其近端部分包括一个与显示框架铰接的外壳，外壳的远端与近端相对，并在两者之间定义一个端口。固定臂还包括一个与远端连接的远端部分，该远端部分定义了一个具有可调节曲率的内部体积。可穿戴显示设备可以包括一个布置在第一内部体积中的柔性管道，柔性管道定义了第二内部体积，以及一个布置在第一内部体积中的扬声器，第二内部体积用于将声音从扬声器引导至端口。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392281_1.jpg)

**Technical Field (技术领域)**:  
可穿戴电子设备领域，具体涉及头戴式设备中的扬声器系统和组件。

**Background (发明背景)**:  
头戴式设备（HMD）通常包括显示屏、观看框架、固定臂、扬声器、电池、波导等组件，这些组件协同工作以提供沉浸式体验。然而，这些组件需要电池供电，占用设备内部空间，限制了电池容量。此外，许多组件位于固定臂中，而固定臂的弯曲部分通常不具有灵活性，无法容纳更多组件。因此，需要一种能够灵活布置组件以增加电池容量并延长设备运行时间的HMD。

**Summary (发明总览)**:  
本发明提出了一种新型可穿戴电子设备，通过在固定臂中集成可弯曲的扬声器组件和柔性管道，解决了现有设备中组件布置和空间利用的问题。该设备将扬声器布置在固定臂的远端，利用柔性管道将声音引导至用户耳部，同时在近端容纳更大的电池。这种设计不仅提高了音质和隐私性，还平衡了设备重量，提升了佩戴舒适度。

**Key Innovation (核心创新)**:  
1. 可调节曲率的固定臂设计：通过在固定臂远端设置可调节曲率的内部体积，使设备能够适应不同用户的头部和耳部形状和尺寸，从而提高佩戴舒适性和稳定性。
2. 柔性管道与扬声器集成：柔性管道内置于固定臂内部，定义了第二内部体积，用于将扬声器的声音引导至用户耳部。该设计确保了声音传输的稳定性和音质，同时允许固定臂弯曲。
3. 扬声器作为配重：扬声器布置在固定臂远端，起到配重作用，减轻用户鼻子承受的重量集中，减少长时间佩戴时的疲劳感。
4. 槽管结构：柔性管道采用槽管设计，在弯曲时保持横截面积和内径不变，防止管道塌陷或产生褶皱，从而保证声音传输的连续性和质量。
5. 柔性部分与包覆材料：在固定臂远端设置柔性部分，并使用包覆材料进行加固，确保柔性管道在弯曲过程中不受损坏，同时增强整体结构强度。
6. 声学密封设计：在固定臂近端设置声学密封，靠近端口位置，减少声音泄漏，提高音质和用户隐私性。
7. 应用场景与价值：这种设计特别适用于虚拟现实和增强现实头戴式设备，能够在保证音质的同时，为其他组件（如电池、处理器）提供更多空间，提升设备整体性能和用户体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392281)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086374)**
<br/><br/>

---


<br/>

### 8. 多模式显示装置

**Title (EN)**: Display with Multiple Operating Modes  
**Pub. No.**: US20260086404

**Applicant**: Apple Inc.  
**Inventor**: [Guanjun Tan](https://patents.google.com/?inventor=Guanjun+Tan&assignee=Apple&country=US&num=100&sort=new), [Andrew Lin](https://patents.google.com/?inventor=Andrew+Lin&assignee=Apple&country=US&num=100&sort=new), [Lingtao Wang](https://patents.google.com/?inventor=Lingtao+Wang&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种电子设备包括显示面板。显示面板发出的光线通过透镜组件聚焦到观看者。在显示面板和透镜组件之间设置有线性偏振器、液晶单元、四分之一波片和几何相位光栅。该显示装置可运行于多种模式。在高分辨率模式下，液晶单元在第一和第二状态之间切换。在高刷新率模式下，液晶单元运行于第三状态。在高分辨率模式下，显示分辨率是高刷新率模式的两倍；在高刷新率模式下，显示刷新率是高分辨率模式的两倍。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392314_1.jpg)

**Technical Field (技术领域)**:  
显示技术领域，具体涉及可切换分辨率和刷新率的显示系统。

**Background (发明背景)**:  
电子设备通常配备显示面板，如液晶显示器或有机发光二极管显示器。头戴式显示设备如虚拟现实眼镜使用透镜，但可能存在分辨率或刷新率不足的问题。现有的显示技术难以同时满足高分辨率和高刷新率的需求。

**Summary (发明总览)**:  
本发明提供了一种可切换分辨率和刷新率的显示技术，通过在显示面板和透镜组件之间设置液晶单元、几何相位光栅等光学元件，实现显示模式切换。在高分辨率模式下，显示分辨率提升；在高刷新率模式下，刷新率提高。该技术通过调整液晶单元状态来改变光路，从而实现不同模式间的切换。

**Key Innovation (核心创新)**:  
1. 采用液晶单元和几何相位光栅组合，通过切换液晶单元状态改变光路，实现显示模式切换。
技术详解：液晶单元在第一和第二状态间切换以改变偏振方向，从而影响光路，实现高分辨率模式；在第三状态时提供高刷新率模式。
2. 在高分辨率模式下，显示分辨率提升至高刷新率模式的两倍。
技术详解：通过调整液晶单元状态，使光线通过几何相位光栅时产生干涉效应，从而提高分辨率。
3. 在高刷新率模式下，显示刷新率提升至高分辨率模式的两倍。
技术详解：液晶单元在第三状态时允许光线直接通过，减少光路复杂性，从而提高刷新率。
4. 使用四分之一波片和线性偏振器组合，优化光束偏振状态。
技术详解：四分之一波片将线偏振光转换为圆偏振光，线性偏振器根据液晶单元状态选择性地通过不同偏振方向的光线。
5. 线性偏振器在不同模式下对光束的透射率进行精确控制。
技术详解：在高分辨率模式下，线性偏振器主要通过第一输出光束；在高刷新率模式下，主要通过第二输出光束；在中间状态下，透射率均衡。
6. 通过物理像素对应虚拟像素的方式，实现分辨率和刷新率的动态调整。
技术详解：每个物理像素对应两个虚拟像素，在高分辨率模式下，两个虚拟像素亮度相同；在高刷新率模式下，亮度不同。
7. 本发明可应用于虚拟现实、增强现实等头戴式显示设备，提供更清晰和流畅的视觉体验。
功能价值：解决了传统头戴式显示设备在分辨率和刷新率之间难以兼顾的问题，提升了用户体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392314)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086404)**
<br/><br/>

---


<br/>

### 9. 确定共处物理环境中的电子设备位置的系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR DETERMINING LOCATIONS OF COLLOCATED ELECTRONIC DEVICES  
**Pub. No.**: US20260089783

**Applicant**: Apple Inc.  
**Inventor**: [Tommy ROCHETTE](https://patents.google.com/?inventor=Tommy+ROCHETTE&assignee=Apple&country=US&num=100&sort=new), [Jiwoo JANG](https://patents.google.com/?inventor=Jiwoo+JANG&assignee=Apple&country=US&num=100&sort=new), [Patrick PIEMONTE](https://patents.google.com/?inventor=Patrick+PIEMONTE&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明涉及一种系统和方法，用于确定共处物理环境中的电子设备的位置。具体包括：1) 第一设备显示可选择元素以基于第二设备在物理环境中的姿态建立多用户通信会话；2) 根据第二用户接受会话请求的设备类型启动不同类型的会话；3) 在多用户通信会话中，第一用户和第二用户可向未参与会话的第三设备传输第一设备和第二设备之间的物理环境的共享坐标系；4) 在检测到共处时，向第三设备传输不同设备的共享原点。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476396046_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及增强现实和虚拟现实技术，具体涉及多用户通信中电子设备的空间定位和坐标系共享。

**Background (发明背景)**:  
现有技术中，计算机图形环境提供二维和/或三维环境，用户可查看虚拟对象。在一些情况下，多个电子设备通过通信呈现三维环境。然而，现有技术缺乏有效的机制来确定共处物理环境中的设备位置，尤其是在多用户通信会话中。这导致用户体验不佳，特别是在涉及空间交互和内容共享时。本发明旨在解决这一问题，通过提供一种确定共处设备位置并共享坐标系的方法。

**Summary (发明总览)**:  
本发明提供了一种系统和方法，用于在多用户通信会话中确定共处物理环境中的电子设备位置。其核心思路是：1) 通过设备间的地图数据共享确定共享参考原点；2) 计算设备坐标系与共享原点的偏移量；3) 基于用户设备类型启动不同类型的通信会话；4) 在会话中检测共处设备并动态调整空间布局。本发明通过共享坐标系和动态位置跟踪，提升了多用户通信中的空间一致性和用户体验。

**Key Innovation (核心创新)**:  
1. 共享参考原点的确定：通过第一设备和第二设备分别生成的地图数据，确定物理环境中的共享参考原点，从而实现设备间的精确定位。
2. 设备坐标系的偏移计算：第一设备计算其自身坐标系与共享参考原点的偏移量，并将相关数据发送给第二设备，使第二设备能够确定第一设备相对于共享原点的位置。
3. 基于设备类型的会话启动：根据第二用户接受会话请求的设备类型，第一设备启动不同类型的通信会话，例如基于增强现实设备或传统移动设备的会话。
4. 会话中动态检测共处设备：在多用户通信会话中，第一设备检测与第一用户共处的第三用户，并响应性地向第三设备传输共享坐标系信息，而无需第三用户参与当前会话。
5. 空间群组和空间真理的实现：在多用户通信会话中，空间群组定义了用户和内容的位置安排，用户在相同群组内体验到一致的空间真理，即虚拟对象与用户之间的空间关系保持一致。
6. 混合空间群组的处理：对于包含非共处用户的混合空间群组，系统通过空间安排确保用户和内容的位置一致性，使用户在不同物理环境中仍能保持空间真理。
7. 应用于增强现实和虚拟现实场景：本发明可应用于增强现实和虚拟现实场景，例如多人游戏、虚拟会议和远程协作，提供更自然和一致的空间交互体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476396046)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089783)**
<br/><br/>

---


<br/>

### 10. 基于用户查询和注视的图像处理系统与方法

**Title (EN)**: SYSTEMS AND METHODS OF PROCESSING BASED ON USER QUERIES AND GAZE  
**Pub. No.**: US20260087850

**Applicant**: Apple Inc.  
**Inventor**: [William D. LINDMEIER](https://patents.google.com/?inventor=William+D.+LINDMEIER&assignee=Apple&country=US&num=100&sort=new), [Devin W. CHALMERS](https://patents.google.com/?inventor=Devin+W.+CHALMERS&assignee=Apple&country=US&num=100&sort=new), [Sean B. KELLY](https://patents.google.com/?inventor=Sean+B.+KELLY&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明提供了一种电子设备与一个或多个输入设备通信的方法，用于检测用户的输入和注视方向。电子设备根据输入捕获一个或多个图像，并利用检测到的注视方向和输入的部分内容，从捕获的图像中识别出至少一个子集图像。如果满足特定条件，电子设备将基于对输入、捕获图像和识别出的子集图像的处理，通过处理电路执行操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476393911_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及人机交互技术，具体包括基于用户注视和查询的图像处理与操作执行。

**Background (发明背景)**:  
电子设备如手机和笔记本电脑通常配备数字助理，可以接收自然语言输入并执行相应操作。然而，现有技术难以准确理解用户意图，特别是在复杂场景中。
本发明旨在解决现有技术中用户输入与设备响应之间的匹配精度问题，通过结合用户注视和查询来提高操作的准确性。

**Summary (发明总览)**:  
本发明提出了一种结合用户注视和查询的图像处理方法。电子设备通过摄像头捕捉环境图像，并利用用户的注视方向确定图像中的兴趣区域。
该方法将用户查询（如语音或文本输入）与注视信息结合，识别出用户感兴趣的对象或区域，从而执行更精准的操作。
相较于传统方法，本发明通过整合多模态输入（注视、图像、查询），提升了设备对用户意图的理解能力和操作的准确性。

**Key Innovation (核心创新)**:  
1. 通过用户注视确定图像兴趣区域：
   技术详解：利用摄像头捕捉环境图像，并通过检测用户的注视方向确定图像中的兴趣区域。
   实现方式：使用眼动追踪摄像头捕捉用户注视点，并将其映射到环境图像坐标。
   功能或解决的问题：解决了传统方法中无法精确定位用户关注对象的问题。
2. 结合用户查询优化兴趣区域识别：
   技术详解：将用户查询（如语音或文本输入）与注视信息结合，进一步细化兴趣区域的特征。
   实现方式：通过自然语言处理技术解析用户查询，并将其与注视信息融合。
   功能或解决的问题：提高了对用户意图的理解精度，避免了仅依赖注视信息可能产生的误判。
3. 多模态输入融合处理：
   技术详解：将图像、注视方向和用户查询作为输入，通过处理电路进行综合分析。
   实现方式：使用多模态融合算法，将不同类型的数据进行整合和关联。
   功能或解决的问题：提升了设备对复杂场景的处理能力，使操作更加智能和精准。
4. 动态调整兴趣区域：
   技术详解：根据用户注视的实时变化动态调整兴趣区域。
   实现方式：持续监测用户注视点，并根据注视轨迹实时更新兴趣区域。
   功能或解决的问题：解决了静态兴趣区域无法适应用户行为变化的问题。
5. 提升操作准确性：
   技术详解：通过整合多模态输入，生成更准确的兴趣区域和操作指令。
   实现方式：利用机器学习模型对多模态数据进行训练和预测。
   功能或解决的问题：提高了设备对用户意图的响应准确性，减少了误操作。
6. 应用于头戴式设备：
   技术详解：将本发明应用于头戴式设备，利用其独特的硬件配置实现更自然的人机交互。
   实现方式：结合头戴式设备的摄像头和眼动追踪功能，优化用户体验。
   功能或解决的问题：提供了更便捷和直观的交互方式，特别适用于增强现实和虚拟现实场景。
7. 独特价值：
   技术详解：通过结合注视和查询，本发明能够实现更智能和个性化的操作执行。
   实现方式：利用个性化模型分析用户行为和偏好。
   功能或解决的问题：为用户提供更符合其需求的交互体验，特别适用于需要高精度和快速响应的应用场景，如导航、图像识别和智能助理。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476393911)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260087850)**
<br/><br/>

---


<br/>

### 11. 个性化液体摄入率的注册方法

**Title (EN)**: METHODS FOR ENROLLMENT OF PERSONALIZED LIQUID CONSUMPTION RATE  
**Pub. No.**: US20260087096

**Applicant**: Apple Inc.  
**Inventor**: [Ioana Negoita](https://patents.google.com/?inventor=Ioana+Negoita&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明公开了用于生成用于确定和记录用户液体摄入率和类型的个性化模型的注册过程的设备、系统和方法。例如，过程可从可穿戴设备上的传感器获取传感器数据。传感器数据对应于用户使用特定液体摄入技术摄入预定量的液体时的相关属性。传感器数据用于个性化液体摄入模型，以预测液体摄入事件的特点。过程还可使用个性化液体摄入模型来识别与用户使用特定液体摄入技术摄入预定量的液体相关的第一特征。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476393077_1.jpg)

**Technical Field (技术领域)**:  
本专利属于液体摄入监测技术领域，具体涉及通过可穿戴设备传感器数据生成个性化液体摄入模型的方法。

**Background (发明背景)**:  
现有用户监测技术在液体摄入监测方面存在准确性和效率不足的问题。传统方法难以准确区分不同的液体摄入方式，也无法精确记录液体摄入量。本发明旨在通过传感器数据和个性化模型提高液体摄入监测的准确性和效率。

**Summary (发明总览)**:  
本发明提出了一种通过可穿戴设备传感器数据生成个性化液体摄入模型的方法。用户使用不同的液体摄入方式摄入预定量的液体，设备记录相关传感器数据，包括音频、头部运动、加速度计数据和视觉数据等。这些数据用于训练或个性化液体摄入模型，以预测液体摄入事件的特点，如液体类型、摄入量、摄入方式和温度等。该模型可用于液体摄入跟踪，如摄入量或热量监测。本发明通过多维度数据融合和个性化模型实现了液体摄入监测的精确化和智能化。

**Key Innovation (核心创新)**:  
1. 通过可穿戴设备传感器数据（如音频、IMU、加速度计数据）捕捉用户液体摄入行为，实现对不同液体摄入方式的精确识别。
2. 利用传感器数据训练个性化液体摄入模型，通过机器学习或规则模型预测液体摄入事件的特点，如液体类型、摄入量和摄入方式。
3. 记录用户使用不同液体摄入技术（如正常饮用、吞咽、啜饮、使用吸管等）时的音频特征，形成声音签名，用于识别液体摄入方式。
4. 通过头部运动数据（如头部姿势、上下运动）分析用户液体摄入时的动作特征，提高液体摄入事件检测的准确性。
5. 结合视觉传感器数据（如液体、容器、环境背景）进行多模态数据融合，进一步提升液体摄入监测的可靠性。
6. 将生物特征数据（如心率）纳入模型训练，以更全面地分析用户液体摄入行为。
7. 本发明可应用于智能水杯、健康监测设备等场景，为用户提供个性化的液体摄入跟踪和健康建议。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476393077)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260087096)**
<br/><br/>

---


<br/>

### 12. 使用三维音频效果提供数字助手响应

**Title (EN)**: PROVIDING DIGITAL ASSISTANT RESPONSES USING THREE-DIMENSIONAL AUDIO EFFECTS  
**Pub. No.**: US20260089457

**Applicant**: Apple Inc.  
**Inventor**: [Elena J. NATTINGER](https://patents.google.com/?inventor=Elena+J.+NATTINGER&assignee=Apple&country=US&num=100&sort=new), [Anna L. BREWER](https://patents.google.com/?inventor=Anna+L.+BREWER&assignee=Apple&country=US&num=100&sort=new), [Devin W. CHALMERS](https://patents.google.com/?inventor=Devin+W.+CHALMERS&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明公开了使用三维音频效果提供数字助手响应的示例方法。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476395687_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及三维音频技术领域，具体涉及通过三维音频效果增强数字助手交互体验的技术。

**Background (发明背景)**:  
近年来，计算机系统与三维场景的交互技术取得了显著发展，包括物理场景和扩展现实场景。然而，现有技术中，数字助手与用户交互时缺乏空间感知能力，导致用户难以快速定位信息源或理解交互内容。本发明旨在通过三维音频效果提升数字助手交互的精准性和用户体验。

**Summary (发明总览)**:  
本发明提出了一种基于三维音频效果增强数字助手交互体验的方法。通过检测用户意图和场景中的对象，数字助手能够将语音响应虚拟地定位在三维场景中的不同位置，从而引导用户注意力并增强空间感知。当用户意图明确且满足特定条件时，语音响应的不同部分会从不同对象的位置发出；当意图不明确或条件不满足时，语音响应则从默认位置发出。这种方法提高了交互的精确性和效率，减少了用户操作的复杂性。

**Key Innovation (核心创新)**:  
1. 通过三维音频效果将数字助手的语音响应虚拟地定位在三维场景中的不同位置，实现更直观的交互体验。
技术实现：利用传感器数据检测用户意图和场景中的对象，根据对象位置计算音频输出位置。
功能：引导用户注意力至相关对象，提升交互效率。
2. 根据用户意图将语音响应的不同部分从不同对象的位置发出，增强空间感知。
技术实现：检测用户意图后，将语音响应分段并分别定位到不同对象的位置。
功能：帮助用户理解交互内容并快速定位信息源。
3. 当用户意图不明确或条件不满足时，语音响应从默认位置发出，避免用户注意力分散。
技术实现：检测用户意图和场景条件，若不满足特定条件则选择默认位置输出语音。
功能：防止用户被无关信息干扰，提高交互准确性。
4. 通过调整语音响应的虚拟位置与实际对象位置的距离，优化音频定位效果。
技术实现：根据对象位置和用户需求动态调整音频输出位置的距离参数。
功能：增强音频定位的准确性和用户体验。
5. 利用传感器数据实时检测用户意图和场景变化，动态调整语音响应位置。
技术实现：传感器数据实时分析用户行为和场景变化，动态更新音频输出位置。
功能：提供更自然和流畅的交互体验。
6. 在扩展现实场景中应用三维音频效果，增强沉浸感。
技术实现：将三维音频技术与虚拟现实或增强现实系统结合。
功能：提升用户在虚拟环境中的空间感知和交互体验。
7. 通过三维音频效果优化设备交互效率，延长电池寿命。
技术实现：减少用户重复操作和误操作，提高交互效率。
功能：降低设备功耗，延长使用时间。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476395687)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089457)**
<br/><br/>

---


<br/>

### 13. 带有公共显示的头戴式设备

**Title (EN)**: Head-Mounted Device with Publicly Viewable Display  
**Pub. No.**: US20260086757

**Applicant**: Apple Inc.  
**Inventor**: [Jonathan P. Ive](https://patents.google.com/?inventor=Jonathan+P.+Ive&assignee=Apple&country=US&num=100&sort=new), [Julian Hoenig](https://patents.google.com/?inventor=Julian+Hoenig&assignee=Apple&country=US&num=100&sort=new), [Julian Jaede](https://patents.google.com/?inventor=Julian+Jaede&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种头戴式设备可佩戴在用户面部。该设备包括一个向内显示用户视图的显示屏，用于向用户呈现虚拟现实图像等向内图像。同时，该设备还具有一个公共显示屏幕，用于向用户周围的人呈现公共图像。这些公共图像可以覆盖用户面部的面部特征。公共图像可以包括用户面部特征的捕捉图像或其他内容，可以包括计算机生成的图形（如用户面部特征图形），可以包含捕捉图像内容和叠加图形的混合内容（如用户面部特征图形），或可以包含其他公共内容。用户监测传感器（如摄像头和注视检测传感器）、环境传感器以及头戴式设备中的其他电路可以收集用于调整公共图像的信息。公共内容可以反映环境条件、头戴式设备用户的状态、头戴式设备周围人的身份和其他属性，以及用户和周围人的其他属性。这种公共内容可以作为图形界面，帮助人们与头戴式显示器进行互动。因此，在头戴式显示器上呈现公共内容有助于促进用户与他人之间的互动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392705_1.jpg)

**Technical Field (技术领域)**:  
电子设备技术领域，具体涉及头戴式显示设备。

**Background (发明背景)**:  
头戴式设备如虚拟现实眼镜和混合现实眼镜可以为用户提供虚拟内容，但这些设备通常会使用户与周围环境隔离。现有头戴式设备无法让周围人识别用户身份或了解用户状态，导致用户与周围人的互动受到限制。

**Summary (发明总览)**:  
本发明提出了一种新型头戴式设备，通过在设备上增加公共显示屏幕，向周围人展示用户面部特征或相关信息，解决了用户与周围人互动受限的问题。该设备利用摄像头和传感器收集用户和环境信息，并通过计算机生成图形或捕捉图像生成公共内容。公共显示屏幕可以显示用户身份、状态以及用户当前观看的内容，从而帮助周围人判断是否适合与用户互动。这种设计在不影响用户虚拟体验的同时，促进了用户与外界的互动。

**Key Innovation (核心创新)**:  
1. 公共显示屏幕设计：通过在头戴式设备上增加公共显示屏幕，覆盖用户面部特征，向周围人展示用户身份、状态等信息。
2. 图像生成与处理：利用摄像头捕捉用户面部特征，并通过计算机生成图形或混合内容生成公共图像，确保图像清晰且与用户状态匹配。
3. 用户与环境信息整合：结合用户监测传感器和环境传感器收集的信息，动态调整公共显示内容，反映用户当前状态和环境条件。
4. 互动促进机制：通过显示用户身份和状态信息，帮助周围人判断是否适合与用户互动，从而促进用户与外界的互动。
5. 多样化信息展示方式：公共内容可以通过状态指示灯、显示屏、扬声器或无线传输等方式呈现，适应不同场景和用户需求。
6. 用户隐私保护：在展示公共内容时，确保不泄露用户敏感信息，仅显示经过筛选和处理的必要信息。
7. 应用场景与价值：适用于虚拟现实、增强现实等场景，在不影响用户沉浸体验的同时，增强用户与周围人的互动，为社交互动提供新的可能性。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392705)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086757)**
<br/><br/>

---


<br/>

### 14. 电子显示图像粘滞补偿

**Title (EN)**: Electronic Display Image Sticking Compensation  
**Pub. No.**: US20260087960

**Applicant**: Apple Inc.  
**Inventor**: [Hyunsoo Kim](https://patents.google.com/?inventor=Hyunsoo+Kim&assignee=Apple&country=US&num=100&sort=new), [Hyunwoo Nho](https://patents.google.com/?inventor=Hyunwoo+Nho&assignee=Apple&country=US&num=100&sort=new), [Jie Won Ryu](https://patents.google.com/?inventor=Jie+Won+Ryu&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明提供用于补偿图像数据以减少或消除图像粘滞现象的电子设备、电路和方法。该电子设备包括电子显示器和图像处理电路。图像处理电路可调整用于在电子显示器上显示的图像数据，以补偿电子显示器上的电荷捕获，从而减少或消除图像粘滞现象。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476394033_1.jpg)

**Technical Field (技术领域)**:  
电子显示技术领域，具体涉及图像数据处理和显示像素补偿技术。

**Background (发明背景)**:  
电子设备广泛使用电子显示器显示图像，但显示像素电路中的电荷捕获现象会导致图像粘滞问题，即前一个图像在显示结束后仍微弱可见。现有的图像处理方法未能有效解决这一问题，导致显示质量下降。

**Summary (发明总览)**:  
本发明提出了一种通过调整图像数据来补偿电子显示器中电荷捕获引起的图像粘滞现象的方法。核心思路是根据当前和之前的图像数据估算显示像素行为的变化，并生成校正电压以补偿电荷捕获的影响。该方法通过在电压域进行像素级校正，并结合时间因素动态调整校正参数，从而实现更准确的图像补偿。相较于现有技术，本发明能够更有效地减少图像粘滞现象，提高显示质量。

**Key Innovation (核心创新)**:  
1. 基于电荷捕获和释放的像素行为建模：通过建立显示像素的指数或拉伸指数模型，估算电荷捕获对像素行为的影响，从而实现更准确的补偿。
2. 动态校正电压生成：根据当前和之前的图像数据以及时间因素，生成初始校正电压，并结合饱和时间调整，生成最终校正电压。
3. 像素级补偿机制：针对每个显示像素进行独立补偿，通过将校正电压与当前图像数据的电压值结合，生成补偿后的电压值，确保每个像素的显示效果准确。
4. 电压域到灰度域的转换与逆转换：先将图像数据从灰度值转换为数字电压值进行补偿计算，再将补偿后的电压值转换回灰度域，确保补偿过程与显示系统兼容。
5. 补偿频率控制：由于电荷捕获是一个缓慢的过程，校正电压的重新计算频率远低于每帧图像的刷新频率，例如每10帧、每30帧或每分钟计算一次，从而降低计算负担。
6. 补偿参数自适应调整：基于全局亮度值和电压水平等参数动态调整补偿参数，确保在不同显示条件下都能有效减少图像粘滞现象。
7. 应用场景与价值：本发明可应用于计算机、手机、平板、电视、虚拟现实头显和车载仪表盘等各类电子设备中，能够显著改善图像显示质量，提升用户体验，尤其在长时间显示静态图像的场景中效果更为突出。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476394033)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260087960)**
<br/><br/>

---


<br/>

### 15. 使用移动设备的自助式视力测试

**Title (EN)**: SELF-GUIDED VISION TEST USING MOBILE DEVICE  
**Pub. No.**: US20260083322

**Applicant**: Apple Inc.  
**Inventor**: [Ioana NEGOITA](https://patents.google.com/?inventor=Ioana+NEGOITA&assignee=Apple&country=US&num=100&sort=new), [Ian PERRY](https://patents.google.com/?inventor=Ian+PERRY&assignee=Apple&country=US&num=100&sort=new), [Finnegan N. SINCLAIR](https://patents.google.com/?inventor=Finnegan+N.+SINCLAIR&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种自助式视力测试方法包括：在与第二电子设备通信的第一电子设备上，获取指示第二电子设备相对于第一电子设备或第一电子设备用户的位置的数据，同时目标在第一电子设备上移动；使用一个或多个第一图像传感器跟踪用户的视线方向；并基于目标位置与视线方向之间的关系，当目标相对于第一电子设备或第一电子设备用户移动时，呈现异常眼动指示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476391748_1.jpg)

**Technical Field (技术领域)**:  
自助式视力测试技术领域，涉及头戴式设备和移动设备的结合应用。

**Background (发明背景)**:  
现有的计算机平台能够提供用于导航二维和/或三维环境的眼动追踪功能，但这些平台在自助式视力测试中的应用有限。传统方法通常需要专业设备或人工指导，难以实现便捷的自我测试。本发明旨在提供一种基于头戴式设备和移动设备的自助式视力测试方法，以解决传统方法不便捷的问题。

**Summary (发明总览)**:  
本发明提出了一种基于头戴式设备和移动设备的自助式视力测试系统和方法。该系统通过头戴式设备上的图像传感器跟踪用户的眼动，同时利用移动设备显示视觉目标并移动该目标。移动设备上的传感器记录目标位置，并与用户的眼动数据进行比较，以评估用户眼动与目标移动的匹配能力。本发明相较于传统方法，实现了无需专业设备或人工指导的便捷自我测试。

**Key Innovation (核心创新)**:  
1. 结合头戴式设备和移动设备进行视力测试：
通过头戴式设备上的图像传感器跟踪用户眼动，同时利用移动设备显示视觉目标并移动目标，实现对用户眼动与目标移动匹配能力的评估。
2. 实时追踪目标位置与用户视线方向：
移动设备上的图像传感器实时记录目标位置，头戴式设备上的传感器记录用户视线方向，通过比较两者关系，评估用户的眼动控制能力。
3. 异常眼动检测与提示：
系统根据目标位置与用户视线方向的关系，检测异常眼动，并在检测到异常时向用户呈现提示信息，帮助用户了解自身视力状况。
4. 无需专业设备或人工指导：
用户可以独立使用该系统进行视力测试，无需专业设备或人工指导，提高了测试的便捷性和可操作性。
5. 动态视觉目标移动路径设计：
移动设备可以设计多种视觉目标移动路径，模拟不同场景下的眼动需求，提供更全面的视力评估。
6. 数据记录与分析：
系统记录用户的眼动数据和目标移动轨迹，并进行后续分析，为用户提供详细的视力评估报告。
7. 应用于家庭视力监测和远程医疗：
该系统可以应用于家庭环境中的视力监测，并支持远程医疗应用，为用户提供便捷的视力健康管理服务。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476391748)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260083322)**
<br/><br/>

---


<br/>

### 16. 用于管理数字身份信息的用户界面

**Title (EN)**: USER INTERFACES FOR MANAGING DIGITAL IDENTIFICATION INFORMATION  
**Pub. No.**: US20260089500

**Applicant**: Apple Inc.  
**Inventor**: [Haya Iris V. GAVIOLA](https://patents.google.com/?inventor=Haya+Iris+V.+GAVIOLA&assignee=Apple&country=US&num=100&sort=new), [Virakri JINANGKUL](https://patents.google.com/?inventor=Virakri+JINANGKUL&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本公开内容主要涉及数字身份信息的管理。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476395735_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面领域，具体涉及用于管理数字身份信息的用户界面技术。

**Background (发明背景)**:  
计算机系统存储用户信息，如图像、文档等，并可将其传输至其他系统以执行各种操作。然而，现有管理数字身份信息的技术通常繁琐且效率低下，例如使用复杂的用户界面或需要多次按键操作。这些方法耗时且浪费用户时间和设备能量，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种更快速、更高效管理数字身份信息的方法和用户界面。通过接收物理身份凭证信息，并根据凭证类型提供不同的操作指导，优化了用户交互流程。该方法减少了用户的认知负担，提高了人机交互效率，并节省了设备能耗，尤其适用于电池供电设备。

**Key Innovation (核心创新)**:  
1. 根据物理身份凭证类型提供定制化操作指导：通过识别凭证类型，系统自动显示相应的操作指示，例如放置位置或扫描方式，从而简化用户操作流程。
2. 动态调整用户界面：根据不同类型的物理身份凭证，系统动态调整显示内容，例如调整扫描区域或提示信息，确保用户能够快速准确地完成操作。
3. 优化用户交互流程：通过减少不必要的用户输入步骤，例如简化身份信息录入流程，降低了用户操作复杂度，提升了整体效率。
4. 提升设备能效：针对电池供电设备，通过优化用户界面和操作流程，减少了处理器和显示组件的能耗，延长了设备续航时间。
5. 增强安全性：通过提供明确的操作指导，例如正确的凭证放置位置或扫描方式，降低了因用户误操作导致的安全风险。
6. 兼容多种身份凭证类型：系统能够识别并处理不同类型的物理身份凭证，例如身份证、驾照等，提供了更广泛的应用场景支持。
7. 应用于智能设备身份认证场景：本发明可应用于智能手机、平板电脑等智能设备，为用户提供更便捷、安全的身份信息管理方式，尤其适用于移动支付、身份验证等场景。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476395735)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089500)**
<br/><br/>

---


<br/>

### 17. 提供输出的技术

**Title (EN)**: TECHNIQUES FOR PROVIDING OUTPUTS  
**Pub. No.**: US20260089823

**Applicant**: Apple, Inc.  
**Inventor**: [Brian T. GLEESON](https://patents.google.com/?inventor=Brian+T.+GLEESON&assignee=Apple&country=US&num=100&sort=new), [Steven J. TAYLOR](https://patents.google.com/?inventor=Steven+J.+TAYLOR&assignee=Apple&country=US&num=100&sort=new), [Thomas S. HULBERT](https://patents.google.com/?inventor=Thomas+S.+HULBERT&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本公开内容涉及提供输出的技术。根据一些实施例，提供了用于输出内容的技术。根据其他实施例，提供了用于输出照明的方法。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476396089_1.jpg)

**Technical Field (技术领域)**:  
计算机用户界面领域，具体涉及设备支架的输出技术，包括语音输入响应和事件驱动的照明输出。

**Background (发明背景)**:  
电子设备通常通过通知提醒用户事件发生，但现有技术常使用复杂且耗时的用户界面，例如多次按键或击键操作。这些方法效率低下，浪费用户时间和设备能量，尤其对电池供电设备影响较大。

**Summary (发明总览)**:  
本发明提供了一种更快速、高效的输出方法及界面，通过设备支架实现语音输入响应和事件驱动的照明输出。这些方法利用设备支架的输入设备检测语音或事件，并基于检测结果通过输出设备或光源提供相应反馈，从而减少用户认知负担，提高人机交互效率，并节省设备能耗。

**Key Innovation (核心创新)**:  
1. 通过设备支架的输入设备检测语音输入，并基于语音输入生成相应输出。
实现方式：利用支架的语音识别模块捕捉用户语音指令，解析后通过支架的显示屏或扬声器输出结果。
功能：提供更便捷的语音控制方式，减少用户操作步骤。
2. 设备支架在检测到外部设备事件后，根据事件类型以特定方式点亮支架的照明部分。
实现方式：支架内置传感器检测外部设备事件，处理器判断事件类型并控制光源以预设方式发光。
功能：提供直观的视觉通知，减少用户对设备屏幕的依赖。
3. 支架通过附件点固定外部设备，并保持其在物理环境中的特定姿态。
实现方式：支架设计包含可调节的机械结构或磁性连接装置，确保外部设备稳固且定位准确。
功能：优化设备使用角度，提升用户交互体验。
4. 支架的输出基于外部设备通知内容进行定制化显示。
实现方式：支架与外部设备通信，接收通知数据并解析后控制输出设备显示相应内容。
功能：提供更丰富的通知反馈方式，增强用户对设备状态的感知。
5. 通过非易失性存储介质存储程序指令，实现支架的输入输出功能。
实现方式：程序指令存储在支架的存储器中，由处理器执行以控制输入输出流程。
功能：确保支架在断电后仍能快速恢复功能，提高系统可靠性。
6. 支架支持多种输入方式，包括但不限于语音输入。
实现方式：支架集成多种传感器，如麦克风、触控传感器等，以适应不同用户交互需求。
功能：提供更灵活的交互方式，提升用户操作的便利性。
7. 本发明可应用于智能家居设备、办公设备支架等场景，为用户提供更智能、更高效的设备交互体验。
独特价值：通过创新的输入输出方式，简化用户操作流程，提升设备智能化水平。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476396089)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089823)**
<br/><br/>

---


<br/>

### 18. 基于接触条件的生理传感增强

**Title (EN)**: AUGMENTING PHYSIOLOGICAL SENSING BASED ON CONTACT CONDITION  
**Pub. No.**: US20260083333

**Applicant**: Apple Inc.  
**Inventor**: [Ashkan OJAGHI](https://patents.google.com/?inventor=Ashkan+OJAGHI&assignee=Apple&country=US&num=100&sort=new), [Adriaan J. TAAL](https://patents.google.com/?inventor=Adriaan+J.+TAAL&assignee=Apple&country=US&num=100&sort=new), [Hany M. ARAFA](https://patents.google.com/?inventor=Hany+M.+ARAFA&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
可穿戴设备可包括一个或多个温度传感器。温度传感器的数据提供信息，用于确定佩戴电子设备的用户的体温。体温测定的准确性取决于电子设备与用户接触条件的变量。通过确定电子设备与用户的接触条件，包括对应于一个或多个热发射器处于激活状态时的测量值，电子设备可以选择性地确定接触条件或校正因子，从而更准确地确定用户的温度。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476391870_1.jpg)

**Technical Field (技术领域)**:  
电子设备技术领域，具体涉及基于温度传感的接触检测和体温测量。

**Background (发明背景)**:  
电子设备通常配备多种传感器，如触摸传感器和光学传感器。温度传感器也是常见组件之一。现有技术中，体温测量容易受到设备与用户接触状态的影响，导致测量误差。本发明旨在通过温度数据检测接触条件，并校正体温测量结果，以提高测量的准确性。

**Summary (发明总览)**:  
本发明提出了一种利用温度信息检测可穿戴电子设备与用户接触状态的方法，并进一步通过温度传感器数据确定用户体温。系统通过分析热发射器激活和关闭时的温度信息，计算接触条件的校正因子，从而提高体温测量的准确性。该方法减少了系统误差和用户操作误差，改善了人机交互体验。

**Key Innovation (核心创新)**:  
1. 通过温度传感器数据检测电子设备与用户的接触条件，利用热发射器激活和关闭时的温度变化来推断接触状态。
2. 基于热发射器激活时的温度上升数据，通过外推法检测稳态温度，从而确定接触条件的校正因子。
3. 将校正因子应用于体温测量算法，补偿因接触不良导致的测量误差，提高体温测量的准确性。
4. 系统结合热发射器和温度传感器数据，通过算法区分环境温度和人体温度的影响，增强测量的可靠性。
5. 通过温度数据的实时分析，动态调整校正参数，适应不同的佩戴状态和环境条件。
6. 该方法减少了用户因佩戴不当导致的测量误差，提升了设备的易用性和测量结果的可靠性。
7. 本发明可应用于健康监测设备，如智能手表和健身追踪器，为用户提供更准确的体温数据和健康建议。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476391870)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260083333)**
<br/><br/>

---


<br/>

### 19. 电子指向设备虚拟交点触觉反馈

**Title (EN)**: VIRTUAL INTERSECTION HAPTIC FEEDBACK FOR ELECTRONIC POINTING DEVICES  
**Pub. No.**: US20260086643

**Applicant**: Apple Inc.  
**Inventor**: [Benjamin R. BLACHNITZKY](https://patents.google.com/?inventor=Benjamin+R.+BLACHNITZKY&assignee=Apple&country=US&num=100&sort=new), [Arun Rakesh YOGANANDAN](https://patents.google.com/?inventor=Arun+Rakesh+YOGANANDAN&assignee=Apple&country=US&num=100&sort=new), [Nicolai GEORG](https://patents.google.com/?inventor=Nicolai+GEORG&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明涉及基于模拟工具与虚拟内容之间的虚拟交点生成电子指向设备触觉反馈响应的系统和方法。在一些示例中，电子设备（例如计算系统）具有与电子设备通信耦合的电子输入设备，并配置为接收来自电子设备的命令，以基于模拟工具和/或呈现虚拟交点的虚拟内容的特性生成触觉反馈（例如振动）模式。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392578_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及虚拟现实/增强现实中的触觉反馈技术。

**Background (发明背景)**:  
现有计算机系统使用摄像头捕捉图像和视频，并显示包含物理对象和虚拟对象的3D环境。然而，现有系统难以在虚拟交互中提供逼真的触觉反馈，导致用户体验不足。本发明旨在解决在虚拟环境中模拟真实触觉反馈的技术问题。

**Summary (发明总览)**:  
本发明提出了一种基于用户手部姿态生成电子指向设备触觉反馈的系统和方法。通过将电子指向设备与虚拟工具对应，当虚拟工具与虚拟对象发生交点时，设备会生成相应的触觉反馈。触觉反馈的特性（如振幅、频率、时序等）基于虚拟交点的程度、虚拟工具的运动学特性和虚拟对象的属性动态调整。本发明通过模拟真实交互中的触觉反馈，提升了虚拟环境中的操作体验。

**Key Innovation (核心创新)**:  
1. 虚拟交点触觉反馈机制：通过检测模拟工具与虚拟对象的空间交点，触觉反馈的生成基于交点的程度（如重叠量或交点面积），实现了更精准的触觉模拟。
2. 触觉反馈特性动态调整：触觉反馈的振幅、频率、内容、时序和空间分布等特性根据虚拟交点的具体参数（如交点深度、面积）进行动态调整，增强了触觉反馈的真实感。
3. 虚拟工具运动学特性集成：触觉反馈特性还基于虚拟工具的运动学参数（如速度、加速度）进行计算，使得触觉反馈更符合真实物理交互的规律。
4. 虚拟对象属性映射：触觉反馈特性还考虑了虚拟对象的属性（如表面纹理、材质），通过将虚拟对象的特性映射到触觉反馈中，进一步提升了交互的真实感。
5. 模拟工具尺寸和方向的影响：触觉反馈会根据模拟工具的尺寸和相对于虚拟对象的方向进行调整，使得触觉反馈更符合实际使用场景。
6. 触觉反馈的精细化控制：通过分离控制触觉反馈的不同特性（如振幅、频率、时序），系统能够更精细地模拟不同类型的触觉交互。
7. 应用场景与价值推测：本发明可应用于虚拟现实、增强现实和远程操控等领域，通过提供更真实的触觉反馈，提升用户在虚拟环境中的操作精度和沉浸感。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392578)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086643)**
<br/><br/>

---


<br/>

### 20. 用于提供应用功能和设备功能的设备、方法和图形用户界面

**Title (EN)**: Devices, Methods, and Graphical User Interfaces for Providing Application Functions and Device Functions  
**Pub. No.**: US20260086710

**Applicant**: Apple Inc.  
**Inventor**: [Gemma A. Roper](https://patents.google.com/?inventor=Gemma+A.+Roper&assignee=Apple&country=US&num=100&sort=new), [Nicolas V. Scapel](https://patents.google.com/?inventor=Nicolas+V.+Scapel&assignee=Apple&country=US&num=100&sort=new), [James H. Foster](https://patents.google.com/?inventor=James+H.+Foster&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
第一计算机系统显示一个用户界面，该界面根据第一操作环境提供对第一组功能的访问。在显示用户界面的同时，计算机系统检测到其已连接到另一计算机系统，并作出响应：如果另一计算机系统根据第二操作环境运行，则第一计算机系统切换到根据第二操作环境运行，包括向另一计算机系统提供指令以根据第二操作环境执行第二组操作；如果另一计算机系统根据第三操作环境运行，则计算机系统切换到根据第三操作环境运行。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392652_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及具有输入设备（如触摸屏）的电子设备领域，具体涉及用于提供应用功能和设备功能的用户界面技术。

**Background (发明背景)**:  
近年来，计算机系统和电子计算设备的使用显著增加，包括智能手机、个人电脑、可穿戴设备和智能家居设备等。随着处理能力和存储容量的提升，这些设备的功能不断扩展。然而，用户在访问这些功能时常常遇到困难，甚至不知道某些功能的存在。不同设备之间功能的冗余和复杂性导致用户管理困难，硬件组件的重复也增加了制造和维护成本。现有的功能访问方法效率低下或需要用户具备预知识，导致用户不满和设备功耗增加。

**Summary (发明总览)**:  
本发明提出了一种改进的计算机系统功能访问方法，通过检测设备间的连接并根据不同操作环境自动切换界面和功能集来提升用户体验和设备间互操作性。该方法通过动态调整用户界面显示的内容，减少用户输入次数和操作复杂度，从而实现更高效的人机交互。对于电池供电设备，该方法还能节省电力并延长电池使用时间。

**Key Innovation (核心创新)**:  
1. 动态环境切换机制：
技术详解：计算机系统通过检测与其他设备的连接状态，识别目标设备的操作环境（如第二或第三操作环境），并自动切换自身的运行模式。
实现方式：利用连接协议和操作环境识别算法，实时监测连接状态并切换界面和功能集。
功能或解决的问题：解决了不同设备间功能冗余和用户操作复杂的问题，提升了设备间的互操作性。
2. 上下文感知用户界面：
技术详解：系统根据当前上下文（如用户位置、时间、设备状态等）调整显示的用户界面内容。
实现方式：通过传感器数据和用户行为分析，动态调整界面元素和功能选项。
功能或解决的问题：提供了更个性化的功能访问方式，减少了用户导航和输入的负担。
3. 指令交互协议：
技术详解：计算机系统在切换到另一操作环境时，向目标设备发送指令以执行特定操作。
实现方式：定义标准化的指令集和通信协议，确保不同设备间的兼容性和功能一致性。
功能或解决的问题：实现了设备间功能的协同工作，减少了用户在不同设备间切换的复杂性。
4. 减少用户输入：
技术详解：通过自动检测环境和用户行为，减少用户手动输入和导航操作。
实现方式：利用传感器数据和预设规则，自动调整界面和功能选项。
功能或解决的问题：提升了用户体验，降低了用户操作难度和错误率。
5. 节能优化：
技术详解：在电池供电设备中，系统根据使用场景优化功能调用和界面更新频率。
实现方式：动态调整处理器性能和显示刷新率，关闭不必要的功能模块。
功能或解决的问题：延长了电池使用时间，减少了不必要的功耗。
6. 跨设备功能集成：
技术详解：系统支持将不同设备的功能集成到一个统一的用户界面中。
实现方式：通过云服务和本地网络，实现设备间功能的协同和共享。
功能或解决的问题：使用户能够在一个设备上访问和控制多个设备的功能，提升了整体使用效率。
7. 预测性功能推荐：
技术详解：系统根据用户历史行为和当前上下文，预测用户可能需要的功能并提前推荐。
实现方式：利用机器学习算法分析用户数据，生成个性化的功能推荐列表。
功能或解决的问题：进一步简化了用户操作流程，提升了功能访问的便捷性和效率。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392652)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086710)**
<br/><br/>

---


<br/>

### 21. 用于调整设备设置的设备、方法和图形用户界面

**Title (EN)**: DEVICES, METHODS, AND GRAPHICAL USER INTERFACES FOR ADJUSTING DEVICE SETTINGS  
**Pub. No.**: US20260086619

**Applicant**: Apple Inc.  
**Inventor**: [Tim H. CORNELISSEN](https://patents.google.com/?inventor=Tim+H.+CORNELISSEN&assignee=Apple&country=US&num=100&sort=new), [Dana F. SEGLER, JR.](https://patents.google.com/?inventor=Dana+F.+SEGLER%2C+JR.&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本公开内容主要涉及用于调整设备设置的设备、技术和/或用户界面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392553_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及增强现实和虚拟现实技术领域，具体涉及通过输入设备调整光学设备参数的用户界面和方法。

**Background (发明背景)**:  
近年来，增强现实计算机系统的发展显著增加。现有技术中，用户与虚拟/增强现实环境的交互通常依赖复杂的输入设备，如摄像头、控制器等。然而，现有系统存在反馈反馈不足、操作步骤繁琐、控制界面复杂等问题，导致用户认知负担重且体验不佳。此外，这些方法耗时长，对电池供电设备来说能耗较高。

**Summary (发明总览)**:  
本发明提出了一种改进的设备设置调整方法，通过检测用户身体部位相对于光学镜头的运动来调整光学镜头的光学参数。该方法通过简化用户输入与设备响应的关联，使用户操作更加直观高效。与传统方法相比，本发明减少了用户输入的复杂性和数量，降低了认知负担，尤其适用于电池供电设备以节省能耗。本发明可应用于虚拟现实、增强现实设备以及便携式电子设备。

**Key Innovation (核心创新)**:  
1. 通过检测用户身体部位相对于光学镜头的运动来触发光学参数调整，例如光学镜头的焦距或光学功率变化。
实现方式：利用摄像头或运动传感器捕捉用户动作，并与预设的运动模式进行匹配。
功能：实现无需手动调节的自动光学参数调整，提升用户体验。
2. 系统根据用户动作是否符合预设标准来决定是否调整光学参数。
实现方式：设定运动检测的阈值或模式识别算法，区分有效和无效的用户动作。
功能：防止误触发，确保光学参数调整的准确性和可靠性。
3. 光学参数调整包括从第一光学功率调整到第二光学功率。
实现方式：通过电控光学元件（如液晶透镜）实现光学功率的动态变化。
功能：提供连续可调的光学参数，适应不同用户的视觉需求。
4. 系统可应用于头戴式显示器等设备，通过眼动追踪或手部动作识别来控制光学参数。
实现方式：集成眼动追踪模块和手部动作传感器，实时捕捉用户行为。
功能：提供更自然的交互方式，减少对传统控制器的依赖。
5. 该方法可减少用户输入次数和复杂度，降低认知负担。
实现方式：通过预设的交互模式和智能识别算法简化用户操作。
功能：提升用户操作效率，尤其适用于虚拟现实和增强现实环境。
6. 该方法适用于电池供电设备，通过减少不必要的操作步骤来节省能耗。
实现方式：优化算法和硬件控制逻辑，降低系统功耗。
功能：延长设备续航时间，提升用户体验。
7. 本发明可应用于虚拟现实、增强现实设备以及便携式电子设备，提供更自然、高效的交互方式。
独特价值：提升用户沉浸感和操作效率，同时降低设备能耗，扩展了应用场景。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392553)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086619)**
<br/><br/>

---


<br/>

### 22. 集成光源的紧凑型相机系统

**Title (EN)**: COMPACT CAMERA SYSTEM WITH INTEGRATED LIGHT SOURCE  
**Pub. No.**: US20260089380

**Applicant**: Apple Inc.  
**Inventor**: [Julien Vittu](https://patents.google.com/?inventor=Julien+Vittu&assignee=Apple&country=US&num=100&sort=new), [Guy Lederman](https://patents.google.com/?inventor=Guy+Lederman&assignee=Apple&country=US&num=100&sort=new), [Katya Gotlib](https://patents.google.com/?inventor=Katya+Gotlib&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明描述了具有集成光源的相机系统。该相机系统可包括印刷电路板、相机模块、支架、第一个光源和一组电连接件。印刷电路板具有柔性部分和刚性部分。相机模块安装在印刷电路板的刚性部分上，并包括镜头筒。第一个光源安装在支架的顶面上。一组电连接件位于印刷电路板的刚性部分与支架之间。支架至少部分包围镜头筒。支架至少安装在印刷电路板的刚性部分上。第一个光源通过一组电连接件与印刷电路板电连接。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476395603_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及相机系统技术领域，具体为集成光源的紧凑型相机系统。

**Background (发明背景)**:  
现代消费电子产品如智能手机、平板电脑和计算机通常集成了相机模块。相机模块的成像能力不断提升，并开始采用多摄像头系统和深度传感器。然而，在低光条件下，相机需要光源模块来辅助成像。传统设计中，光源模块通常作为独立组件存在，这增加了相机系统的整体尺寸和复杂性。

**Summary (发明总览)**:  
本发明提出了一种集成光源的紧凑型相机系统，通过将光源模块与相机模块整合到一个共同的结构中，减少了相机系统的整体尺寸并简化了设计。
该系统利用支架或第二印刷电路板将光源精确定位在相机模块附近，确保光源的光场与相机模块的视野一致。
通过这种设计，相机系统能够在不显著增加其尺寸的情况下提供闪光功能，同时减少光源对相机成像的干扰。

**Key Innovation (核心创新)**:  
1. 采用柔性印刷电路板设计，通过柔性部分连接刚性部分和支架，实现紧凑布局并减少空间占用。
2. 支架设计用于固定光源并包围镜头筒，确保光源与相机模块的光轴对齐，从而提供均匀照明并减少图像失真。
3. 在支架顶部安装光源，并通过电连接件与印刷电路板连接，实现光源与相机模块的电气集成。
4. 使用第二印刷电路板作为光源载体，其第一部分覆盖相机模块顶部，并通过柔性部分与第一印刷电路板连接，提供更灵活的布局选择。
5. 通过调整光源的光锥与相机模块的光锥相对位置，减少光源光线通过相机镜头进入相机模块内部的可能性，从而降低反射和图像不均匀性。
6. 支持在支架上安装多个光源，以增强照明效果并适应不同场景的照明需求。
7. 本发明可应用于智能手机、平板电脑、可穿戴设备等消费电子产品中，为小型化设备提供高效、紧凑的成像解决方案。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476395603)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089380)**
<br/><br/>

---


<br/>

### 23. 具有可调节输入阈值的输入系统

**Title (EN)**: INPUT SYSTEMS WITH ADJUSTABLE INPUT THRESHOLDS  
**Pub. No.**: US20260086655

**Applicant**: Apple Inc.  
**Inventor**: [Denis G. Chen](https://patents.google.com/?inventor=Denis+G.+Chen&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种电子设备可包括输入系统，该系统包括位于电子设备外部的可接触输入部件，用于接收用户施加的输入力；一个由于输入力而发生偏转的梁结构；一个应变传感系统；以及一个通过输入部件的移动而被触发的开关。当开关被触发时，电子设备可使用应变传感系统提供的信号来确定开关的触发力，并进一步使用确定的触发力来确定与按钮部分按压相关的阈值。电子设备可包括提供温度信号的温度传感器。电子设备可使用温度信号来确定要应用的偏移量。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392592_1.jpg)

**Technical Field (技术领域)**:  
电子设备输入系统，具体涉及利用多模态信息调节输入阈值的输入系统。

**Background (发明背景)**:  
电子设备通常使用物理按键接收用户输入，例如通过按钮接收用户施加的输入力来控制设备功能。现有技术中，按钮的力感应机制可能因温度变化、材料疲劳等因素导致测量不准确，从而影响设备操作的准确性。

**Summary (发明总览)**:  
本发明提出了一种基于多模态信息调节输入阈值的输入系统。通过结合力感应组件和温度传感器的数据，系统能够动态调整输入阈值，从而更准确地识别用户的部分按压和完全按压操作。系统通过分析应变传感系统的输出信号和温度变化，校正信号偏差，确保在不同使用条件下都能准确响应用户输入。

**Key Innovation (核心创新)**:  
1. 结合应变传感系统和温度传感器数据，通过分析温度变化对输出信号的影响，实现对输入阈值的动态调节。
技术实现：利用负温度系数（NTC）传感器监测温度变化，并根据温度变化范围调整输出信号的偏移量。
功能：提高系统在温度变化环境下的测量精度。
2. 通过检测开关触发时的输出信号，确定触发力并调整部分按压的阈值。
技术实现：监测开关触发时的应变传感信号，计算触发力，并根据触发力调整部分按压的阈值。
功能：确保部分按压检测的准确性，适应不同用户按压力度。
3. 采用线性拟合方法处理应变传感系统的输出信号，去除异常数据点，提高信号处理的可靠性。
技术实现：对输出信号进行线性拟合，并根据拟合结果去除异常数据点。
功能：减少噪声干扰，提高部分按压检测的稳定性。
4. 识别用户按压的不同接触位置，并针对不同位置分别计算触发力。
技术实现：通过触摸传感器确定用户按压的接触位置，并根据接触位置计算对应的触发力。
功能：提高系统对不同按压位置的响应精度，适应用户多样化的按压习惯。
5. 在按钮的不同操作状态下执行不同的设备操作，例如部分按压和完全按压对应不同的功能。
技术实现：根据应变传感信号和开关状态判断按钮的操作状态，并执行相应的设备操作。
功能：提供更丰富的用户交互方式，提升设备操作效率。
6. 通过多模态信息融合（力感应和触摸输入）实现更复杂的用户交互。
技术实现：结合触摸传感器和应变传感系统的数据，识别用户的触摸位置和按压力度。
功能：支持更复杂的用户手势和交互方式，例如触摸加力组合操作。
7. 应用于需要高精度输入检测的设备，例如智能手机、平板电脑等，提升用户体验。
功能：提供更准确、更可靠的输入检测，确保用户意图被准确识别和执行。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392592)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086655)**
<br/><br/>

---


<br/>

### 24. 用于车辆显示屏输出的带逐向导航模式的地图应用

**Title (EN)**: Mapping Application With Turn-By-Turn Navigation Mode For Output To Vehicle Display  
**Pub. No.**: US20260085942

**Applicant**: Apple Inc.  
**Inventor**: [Bradford A. Moore](https://patents.google.com/?inventor=Bradford+A.+Moore&assignee=Apple&country=US&num=100&sort=new), [Emanuele Vulcano](https://patents.google.com/?inventor=Emanuele+Vulcano&assignee=Apple&country=US&num=100&sort=new), [Jorge Fino](https://patents.google.com/?inventor=Jorge+Fino&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明提供了一种在移动设备上运行的方法。该方法渲染一个动画导航展示，用于输出到移动设备之外的外部显示屏。该导航展示包括一个显示至少部分目的地的路线动画地图。同时，该方法在移动设备的显示屏上显示有关路线中某个操作的导航信息，而不显示相同的动画地图。在某些实施例中，所显示的操作信息包括图形指令和文本指令，用于指示下一个操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476391802_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及移动设备与车辆导航系统的交互技术，具体为多设备导航用户界面生成和同步显示技术。

**Background (发明背景)**:  
便携式媒体设备（如智能手机）能够运行先进的地图和导航应用，但驾驶时操作这些应用可能因设备屏幕小而困难。此外，车辆内置导航系统虽然屏幕大且位置方便，但功能通常不如移动设备上的导航应用全面。本发明旨在解决移动设备导航应用与车辆导航系统之间的功能差异和用户体验问题。

**Summary (发明总览)**:  
本发明提供了一种集成地图和导航应用，可在移动设备上运行并同时生成多个用户界面，分别输出到移动设备和连接的车辆显示屏。该应用能够识别车辆显示屏类型并自动适配相应的用户界面。用户在车辆界面和移动设备界面上均可与应用交互，且不同界面根据设备能力提供不同的交互方式。应用还提供目的地搜索、预测路线规划、近期位置推荐等功能，并通过逐向导航模式在车辆显示屏和移动设备上显示不同的导航信息。

**Key Innovation (核心创新)**:  
1. 多设备用户界面同步生成技术：
实现方式：应用在移动设备上运行，同时生成适用于移动设备和车辆显示屏的用户界面。
功能：确保用户在不同设备上获得一致且适配的导航体验。
2. 车辆显示屏类型自动识别与适配：
实现方式：应用连接车辆后识别显示屏类型（如高质量触摸屏、低质量触摸屏、非触摸屏），并自动输出适配的用户界面。
功能：提供针对不同车辆显示屏的优化交互方式，提升用户体验。
3. 预测路线规划功能：
实现方式：应用分析移动设备上的日历、过往路线数据以及实时交通信息，生成预测路线。
功能：帮助用户在驾驶时快速选择最佳路线，减少决策时间。
4. 逐向导航模式下的差异化显示：
实现方式：车辆显示屏显示用户的当前位置和即将到来的路线，而移动设备显示屏则显示即将到来的操作指示。
功能：确保驾驶员在驾驶时能够专注于车辆显示屏，同时通过移动设备获取详细的操作指导。
5. 车辆显示屏上的操作表示优化：
实现方式：在车辆接近下一个操作点时，车辆显示屏显示带有箭头和文本指示的操作表示。
功能：提供直观的操作指导，帮助驾驶员准确执行导航指令。
6. 近期位置推荐功能：
实现方式：应用提供近期搜索结果和导航目的地，并通过车辆界面快速访问。
功能：简化用户重复搜索和导航操作，提高使用效率。
7. 语音交互支持：
实现方式：用户可通过移动设备或车辆的内置麦克风进行语音搜索。
功能：提供更安全的操作方式，减少驾驶员分心的风险。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476391802)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260085942)**
<br/><br/>

---


<br/>

### 25. 在第一电子设备和第二电子设备之间转移内容呈现的系统和方法

**Title (EN)**: SYSTEMS AND METHODS OF TRANSFERRING PRESENTATION OF CONTENT BETWEEN A FIRST ELECTRONIC DEVICE AND A SECOND ELECTRONIC DEVICE  
**Pub. No.**: US20260086758

**Applicant**: Apple Inc.  
**Inventor**: [Devin W. CHALMERS](https://patents.google.com/?inventor=Devin+W.+CHALMERS&assignee=Apple&country=US&num=100&sort=new), [Austin P. SOUSA](https://patents.google.com/?inventor=Austin+P.+SOUSA&assignee=Apple&country=US&num=100&sort=new), [Giancarlo YERKES](https://patents.google.com/?inventor=Giancarlo+YERKES&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明涉及用于在计算系统的第一电子设备和第二电子设备之间转移内容呈现的系统和方法。在一些实施例中，当第一内容在三维环境中通过第一电子设备呈现时，计算系统通过第二电子设备的一个或多个输入设备检测到第一输入。在确定第一输入满足一个或多个第一标准后，计算系统将第一内容的呈现从第一电子设备转移到第二电子设备。转移第一内容的呈现包括停止在第一电子设备的一个或多个第一显示器上呈现第一内容，并在第二电子设备的一个或多个第二显示器上呈现第一内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392706_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及人机交互技术，具体为跨设备内容呈现转移技术，包括三维环境中的内容呈现和用户输入驱动的设备间内容切换。

**Background (发明背景)**:  
随着计算机图形技术的发展，二维和三维虚拟环境被广泛应用于用户界面设计中。然而，现有技术中内容呈现通常局限于单一设备，用户在不同设备间切换内容时体验不佳。现有多设备协作方案存在操作复杂、切换不流畅等问题。本发明旨在解决跨设备内容呈现转移过程中用户体验不足的问题，通过简化用户操作实现无缝切换。

**Summary (发明总览)**:  
本发明提出了一种在计算系统的多个电子设备之间转移内容呈现的方法。当第一电子设备在三维环境中呈现内容时，用户通过第二电子设备的输入设备触发转移操作。系统检测输入并判断是否符合预设标准，若满足则将内容呈现从第一设备转移到第二设备。实现方式包括停止在第一设备上的内容呈现，并在第二设备上重新呈现内容。本发明通过简化用户操作流程，实现跨设备内容呈现的无缝切换，提升了用户交互体验。

**Key Innovation (核心创新)**:  
1. 通过第二电子设备的输入设备（如触摸手势）触发内容呈现转移，用户只需简单操作即可实现跨设备内容切换。
技术细节：系统识别触摸输入（如滑动手势）并判断是否符合预设标准（如滑动方向、速度等）。
实现方式：利用触摸传感器和手势识别算法检测用户输入。
功能：简化用户操作流程，提升交互效率。
2. 在三维环境中呈现内容时，系统支持多种对象锁定模式（如世界锁定、头部锁定、身体锁定等），以适应不同使用场景。
技术细节：对象可选择与世界、用户头部或身体保持固定相对位置和方向。
实现方式：利用传感器数据（如头部追踪）动态调整对象位置和方向。
功能：提供更自然和沉浸的用户体验，适应不同应用需求。
3. 转移过程中，第一电子设备停止呈现内容，第二电子设备开始呈现内容，实现无缝切换。
技术细节：系统同步控制两台设备的显示状态，确保内容呈现的连续性。
实现方式：利用网络通信协议在设备间传输状态信息和内容数据。
功能：避免内容呈现中断，提升用户体验。
4. 三维对象在转移后可保持与用户的相对位置和方向，确保用户在不同设备上获得一致的视觉体验。
技术细节：系统根据用户视角调整对象呈现方式。
实现方式：利用头部追踪和空间定位技术。
功能：提供一致的用户体验，避免因设备切换导致的空间感知混乱。
5. 系统支持根据用户头部倾斜角度调整对象位置，实现基于用户动作的动态对象定位。
技术细节：对象位置随用户头部倾斜角度变化而调整。
实现方式：利用陀螺仪和加速度计数据计算头部倾斜角度。
功能：提供更自然的交互方式，增强沉浸感。
6. 对象在三维环境中可选择固定方向或随用户动作调整方向，适应不同应用场景需求。
技术细节：系统根据对象类型和用户偏好选择合适的锁定模式。
实现方式：预设不同锁定模式的参数和规则。
功能：提供灵活的交互方式，满足不同应用场景的需求。
7. 本发明可应用于增强现实、虚拟现实和混合现实场景，为用户提供跨设备无缝内容呈现体验。
独特价值：提升多设备协作效率，增强用户沉浸感，拓展应用场景。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392706)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086758)**
<br/><br/>

---


<br/>

### 26. 基于姿态的电子指向设备触觉反馈

**Title (EN)**: POSE-BASED HAPTIC FEEDBACK FOR ELECTRONIC POINTING DEVICES  
**Pub. No.**: US20260086645

**Applicant**: Apple Inc.  
**Inventor**: [Benjamin R. BLACHNITZKY](https://patents.google.com/?inventor=Benjamin+R.+BLACHNITZKY&assignee=Apple&country=US&num=100&sort=new), [Nicolai GEORG](https://patents.google.com/?inventor=Nicolai+GEORG&assignee=Apple&country=US&num=100&sort=new), [Carmine ELVEZIO](https://patents.google.com/?inventor=Carmine+ELVEZIO&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明涉及基于用户手部姿态生成电子指向设备触觉反馈响应的系统和方法。在一些示例中，电子设备（例如计算系统）与电子指向设备有线或无线连接，并根据检测到的用户手部姿态向电子指向设备发送指令以生成触觉反馈（例如振动）模式。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392580_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及基于手部姿态的触觉反馈技术。

**Background (发明背景)**:  
现有计算机系统使用摄像头捕捉图像或视频，并显示包含物理对象和虚拟对象的3D环境。然而，现有技术缺乏对用户手部姿态的触觉反馈支持，难以提供更直观的交互体验。本发明旨在通过基于手部姿态的触觉反馈增强用户与电子指向设备的交互体验。

**Summary (发明总览)**:  
本发明提出了一种基于用户手部姿态生成电子指向设备触觉反馈的方法。通过传感器和摄像头检测用户手部在指向设备上的位置、方向和施加的力度，系统能够生成相应的触觉反馈模式，例如振动模式或立体触觉效果。该方法结合用户视线和虚拟3D环境中的指向设备位置，进一步优化触觉反馈的生成，从而提供更自然和直观的交互体验。

**Key Innovation (核心创新)**:  
1. 基于手部姿态的触觉反馈生成技术，通过传感器和摄像头检测用户手部在指向设备上的位置、方向和力度，实现精确的触觉反馈控制。
2. 触觉反馈模式与手部姿态的实时联动，例如振动模式根据手部姿态动态调整，提供更直观的交互体验。
3. 立体触觉效果的实现，在指向设备的一端或多端生成基于手部位置的触觉反馈，增强用户对设备操控的感知。
4. 结合用户视线信息的触觉反馈，通过眼动追踪摄像头捕捉用户视线，将视线与手部姿态结合生成更智能的触觉反馈。
5. 虚拟3D环境中的指向设备位置与触觉反馈的结合，根据设备在虚拟环境中的位置调整触觉反馈模式，提升虚拟现实应用的沉浸感。
6. 触觉反馈的硬件实现方案，包括在指向设备内部集成力传感器和振动模块，确保触觉反馈的准确性和可靠性。
7. 本发明可应用于虚拟现实、增强现实和游戏控制器等领域，为用户提供更自然和沉浸式的交互体验。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392580)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086645)**
<br/><br/>

---


<br/>

### 27. 基于环境上下文接收和呈现通知

**Title (EN)**: RECEIVING AND PRESENTING NOTIFICATIONS BASED ON ENVIRONMENTAL CONTEXT  
**Pub. No.**: US20260089251

**Applicant**: Apple Inc.  
**Inventor**: [Jessica TRINH](https://patents.google.com/?inventor=Jessica+TRINH&assignee=Apple&country=US&num=100&sort=new), [Benjamin S. PHIPPS](https://patents.google.com/?inventor=Benjamin+S.+PHIPPS&assignee=Apple&country=US&num=100&sort=new), [Alexandria G. HESTON](https://patents.google.com/?inventor=Alexandria+G.+HESTON&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明涉及基于环境上下文接收和呈现通知的系统和方法，尤其涉及在扩展现实设备上不同忙碌程度下接收和呈现通知。在一些示例中，电子设备在第一忙碌程度下接收通知，并根据用户与通知发送者的先前交互和/或通知内容确定通知的重要性。当通知的重要性超过第一忙碌程度的重要性阈值时，电子设备呈现通知指示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476395462_1.jpg)

**Technical Field (技术领域)**:  
本专利属于扩展现实技术领域，具体涉及基于环境上下文和用户忙碌程度管理通知呈现的技术。

**Background (发明背景)**:  
现有计算机图形环境提供二维和/或三维虚拟对象显示，用户可通过电子设备查看这些对象。然而，在不同忙碌程度下如何智能管理通知呈现仍存在不足。现有的通知系统通常不考虑用户的当前活动状态或环境上下文，可能导致用户分心或错过重要信息。本发明旨在解决这一问题，通过根据用户忙碌程度和环境上下文智能管理通知呈现，提升用户体验。

**Summary (发明总览)**:  
本发明提出了一种基于环境上下文和用户忙碌程度智能管理通知呈现的方法。

核心思路是：
1. 电子设备在不同忙碌程度下接收通知。
2. 根据用户与通知发送者的历史交互和通知内容评估通知的重要性。
3. 在特定忙碌程度下，只有当通知的重要性超过预设阈值时，才向用户呈现通知指示。

相较于现有技术，本发明通过考虑用户忙碌程度和环境上下文，提供了更智能的通知管理方式，避免用户被不重要的通知打扰，同时确保重要信息及时传达。

**Key Innovation (核心创新)**:  
1. 根据用户忙碌程度动态调整通知呈现策略，通过检测用户当前的活动状态或环境上下文（如工作、休息或运动），实现更智能的通知管理。
2. 基于用户与通知发送者的历史交互数据（如回复频率、互动时长）以及通知内容的关键字分析，评估通知的重要性，从而决定是否呈现通知。
3. 在扩展现实设备上实现多层次忙碌程度检测，通过传感器数据和用户行为模式分析，精确判断用户当前的活动状态。
4. 设计通知重要性阈值系统，根据不同的忙碌程度设定不同的阈值，确保在用户忙碌时只呈现最重要的通知。
5. 采用机器学习算法持续优化通知呈现策略，通过分析用户对通知的响应模式（如忽略、查看或回复），自动调整通知优先级。
6. 在高忙碌程度下，通过简化的视觉或听觉提示（如轻微震动或简短提示音）告知用户有重要通知，而不会过度干扰其当前活动。
7. 本发明可应用于智能眼镜、虚拟现实头显等扩展现实设备，为用户提供无缝且不打扰的通知体验，尤其适用于工作场景或需要高度专注的任务中。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476395462)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089251)**
<br/><br/>

---


<br/>

### 28. 头戴式显示设备的显示调整

**Title (EN)**: DISPLAY ADJUSTMENT FOR A HEAD-MOUNTABLE DISPLAY DEVICE  
**Pub. No.**: US20260086317

**Applicant**: Apple Inc.  
**Inventor**: [Alexander B von Schulmann](https://patents.google.com/?inventor=Alexander+B+von+Schulmann&assignee=Apple&country=US&num=100&sort=new), [Trevor S Chambers](https://patents.google.com/?inventor=Trevor+S+Chambers&assignee=Apple&country=US&num=100&sort=new), [Matin Seadat Beheshti](https://patents.google.com/?inventor=Matin+Seadat+Beheshti&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种头戴式显示设备包括一个框架和一个带有第一光学模块和第二光学模块的显示器，这两个光学模块彼此偏移。该头戴式显示设备还包括一个瞳距调整机构，用于调整第一光学模块和第二光学模块之间的距离，使其与用户的瞳距相同。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392219_1.jpg)

**Technical Field (技术领域)**:  
头戴式显示设备领域，具体涉及光学模块瞳距调整技术。

**Background (发明背景)**:  
随着便携式计算技术的进步，头戴式显示设备的使用日益普及。这些设备的显示器通常包含一个或多个光学模块，用于向用户的眼睛呈现图像。不同用户具有独特的瞳距，这会影响显示设备的最佳使用效果。现有的头戴式显示设备缺乏有效的瞳距调整机制，无法为每个用户提供最佳体验。

**Summary (发明总览)**:  
本发明提出了一种具有瞳距调整机制的头戴式显示设备，通过调整光学模块之间的距离来适应不同用户的瞳距。该机制利用线性驱动器、齿轮组或滑轮系统等机械结构，实现光学模块的同步或独立调整，从而优化显示效果。本发明的主要改进在于提供了一种用户友好的调整方式，减少了调整误差并提高了调整效率。

**Key Innovation (核心创新)**:  
1. 采用线性驱动器与中央柱结构结合的瞳距调整机制，通过第一线性驱动器和第二线性驱动器分别连接中央柱与第一、第二光学模块，实现光学模块的独立或同步调整。
2. 使用齿轮组（特别是螺旋齿轮）作为调整核心，其中第一齿条与第二齿条分别与螺旋齿轮的上下部分啮合，确保在调整过程中齿条之间互不干扰，提高调整精度。
3. 设计了一种基于滑轮和电缆的调整系统，电缆穿过中央柱和两侧滑轮并连接到光学模块，通过手动或自动方式调整电缆张力，实现光学模块的精确移动。
4. 引入张力滑轮以限制电缆的蠕变现象，确保调整过程中光学模块位置的稳定性。
5. 调整机构可手动操作，用户通过移动任一光学模块即可同时调整两个模块的位置，简化了调整过程并减少了调整误差。
6. 调整路径设计为非平行和非共线，以适应头戴式设备贴合人脸曲线的需求，确保在调整过程中光学模块始终保持正确的相对位置。
7. 该技术可应用于各种头戴式显示设备，如虚拟现实（VR）和增强现实（AR）设备，为用户提供个性化的视觉体验，并提高设备的易用性和舒适度。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392219)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086317)**
<br/><br/>

---


<br/>

### 29. 多用户通信会话中基于表面的交互与操作

**Title (EN)**: SURFACE-BASED INTERACTIONS AND OPERATIONS WITHIN MULTI-USER COMMUNICATION SESSIONS  
**Pub. No.**: US20260087759

**Applicant**: Apple Inc.  
**Inventor**: [Connor A. SMITH](https://patents.google.com/?inventor=Connor+A.+SMITH&assignee=Apple&country=US&num=100&sort=new), [Anish KANNAN](https://patents.google.com/?inventor=Anish+KANNAN&assignee=Apple&country=US&num=100&sort=new), [Kevin LEE](https://patents.google.com/?inventor=Kevin+LEE&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明涉及在多用户通信会话中相对于三维环境表面显示虚拟内容的方法和系统，以及在三维环境中相对于表面垂直移动虚拟内容的方法和系统。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476393811_1.jpg)

**Technical Field (技术领域)**:  
本专利属于多用户三维通信技术领域，具体涉及基于物理表面的虚拟内容显示与空间交互技术。

**Background (发明背景)**:  
现有计算机图形环境提供二维和三维虚拟对象显示，但多用户通信会话中虚拟对象的空间一致性存在问题。
用户通过不同设备参与会话时，虚拟对象的位置和空间关系可能因设备视角不同而出现偏差。
本发明旨在解决多用户通信中虚拟对象的空间同步问题，确保虚拟内容与物理表面之间的空间关系一致。

**Summary (发明总览)**:  
本发明提出了一种在多用户通信会话中基于三维环境表面显示和操作虚拟内容的方法。
通过同步用户视角和物理表面，虚拟内容可以相对于不同表面进行关联和移动。
系统能够根据用户输入调整虚拟对象的位置，并实时更新其在三维环境中的显示高度。
本发明通过空间同步机制确保不同用户对虚拟对象的空间感知一致，提升了多用户协作的准确性和沉浸感。

**Key Innovation (核心创新)**:  
1. 虚拟内容与物理表面关联技术：
通过接收用户请求，将虚拟对象与三维环境中的特定表面进行关联。
实现方式包括接收用户输入并解析关联指令，将虚拟对象的空间坐标与目标表面坐标对齐。
该技术解决了虚拟对象在三维环境中空间定位不明确的问题。
2. 基于用户视角的虚拟对象垂直移动：
系统能够根据用户输入在三维环境中垂直移动虚拟对象及其关联的用户虚拟形象。
通过检测用户输入（如手势或语音指令），系统调整虚拟对象的高度，并实时更新显示。
该机制确保了用户对虚拟对象空间位置的直观控制。
3. 多用户空间同步机制：
在多用户通信会话中，系统维护虚拟对象与用户视角的空间一致性。
当虚拟对象移动时，系统触发空间细化过程，重新计算用户虚拟形象和虚拟对象的位置关系。
这保证了不同用户对虚拟对象空间位置的感知一致，避免了空间错位问题。
4. 用户界面交互技术：
用户可以通过注视点跟踪选择界面元素，并通过手势输入进行确认和操作。
系统支持通过输入设备检测用户手势，以实现对三维环境中对象的移动和旋转控制。
这种交互方式提高了用户操作的便捷性和自然性。
5. 空间组概念的应用：
系统引入了空间组概念，将多用户通信会话中的参与者划分为不同的空间组。
每个空间组具有独立的空间排列规则，确保组内用户和虚拟对象的空间关系一致。
这使得多用户协作更加有序和高效。
6. 空间细化过程：
当共享虚拟对象移动时，系统启动空间细化过程，调整用户虚拟形象和虚拟对象的位置。
该过程确保了空间同步性，使用户在不同设备上获得一致的空间体验。
空间细化是维持多用户通信中空间一致性的关键技术手段。
7. 应用场景与价值：
本发明可应用于虚拟会议、远程协作和多人游戏等场景。
通过提供精确的空间同步和直观的交互方式，本专利提升了多用户通信的沉浸感和协作效率。
其独特价值在于实现了虚拟对象与物理表面之间的无缝交互，为多用户通信带来了新的可能性。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476393811)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260087759)**
<br/><br/>

---


<br/>

### 30. 带有可调节头带的头戴式设备

**Title (EN)**: Head-Mounted Devices with Adjustable Headbands  
**Pub. No.**: US20260086603

**Applicant**: Apple Inc.  
**Inventor**: [Andrew Gallaher](https://patents.google.com/?inventor=Andrew+Gallaher&assignee=Apple&country=US&num=100&sort=new), [Jackson C Masters](https://patents.google.com/?inventor=Jackson+C+Masters&assignee=Apple&country=US&num=100&sort=new), [Erin N Mieth](https://patents.google.com/?inventor=Erin+N+Mieth&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种头戴式设备可包括用于向用户呈现图像的光学组件。头戴式设备的外壳通过头带系统支撑在用户头部前方，位于用户眼睛前方。头带系统包括一个或多个头带部分，可通过收紧或松开来调整头带系统的贴合度。为确保单个头带部分的多部分被调整相同的量，可以使用对称移动多部分的调节器。头带系统可通过一个或多个闩锁固定在头戴式设备上的一个支点上。一个或多个可拆卸组件，如可拆卸电池和/或配重，可附加到头带部分之一。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392535_1.jpg)

**Technical Field (技术领域)**:  
电子设备领域，具体涉及头戴式设备的头带系统。
涉及头带调节、佩戴舒适性优化及配重平衡技术。

**Background (发明背景)**:  
头戴式设备通常需要头带或头带来固定在用户头部。
现有头带系统可能难以实现均匀调节，导致佩戴不适。
部分设备可能因重量分布不均而影响用户体验。
本发明旨在提供一种可均匀调节且可平衡重量的头带系统。

**Summary (发明总览)**:  
本发明提供了一种带有可调节头带的头戴式设备，通过对称调节机制实现头带的均匀收紧或松开，提升佩戴舒适度。
头带系统采用对称伸缩设计，可通过旋钮、电机或手动方式调节。
头带部分可包含伸缩管、可扩展连接件以及配重组件，以适应不同头型并平衡设备重量。
本发明相较于传统头带系统，提供了更便捷的调节方式和更舒适的佩戴体验。

**Key Innovation (核心创新)**:  
1. 对称调节机制：通过对称伸缩设计（如对称伸缩旋钮、齿轮和丝杆或齿条和小齿轮系统），实现头带各部分均匀收紧或松开，确保佩戴时受力均匀，提升舒适度。
2. 可调节伸缩管：头带部分采用伸缩管设计，可根据用户头部尺寸调整长度，并通过覆盖伸缩管的垫子增加佩戴舒适性。
3. 可扩展连接件：头带部分之间设置可扩展连接件，根据用户头部大小自动调整，适应不同头型。
4. 配重平衡系统：头带可附加可移动或可拆卸的配重组件，用于平衡头戴式设备的重量，减少对头部的压力。
5. 闩锁固定机制：头带系统通过闩锁固定在头戴式设备的支点上，确保牢固连接，同时便于拆卸和调整。
6. 模塑结构设计：头带部分采用模塑结构（如格子结构和/或模塑椭圆形结构），并带有肋条以增加柔韧性，提升佩戴舒适度。
7. 应用于头戴式设备：如VR/AR头显等，可提供更舒适的佩戴体验，并适用于长时间使用场景。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392535)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086603)**
<br/><br/>

---


<br/>

### 31. 基于状态的电子设备操作

**Title (EN)**: STATE-BASED OPERATION OF ELECTRONIC DEVICES  
**Pub. No.**: US20260086605

**Applicant**: Apple Inc.  
**Inventor**: [Thomas G Salter](https://patents.google.com/?inventor=Thomas+G+Salter&assignee=Apple&country=US&num=100&sort=new), [Sam D Smith](https://patents.google.com/?inventor=Sam+D+Smith&assignee=Apple&country=US&num=100&sort=new), [Devin W Chalmers](https://patents.google.com/?inventor=Devin+W+Chalmers&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明涉及用于操作头戴式设备的方法、系统及设备。具体而言，头戴式设备可根据当前设备状态切换不同的操作模式。所述头戴式设备可配置为在多个候选设备状态中运行。在这些候选设备状态中，头戴式设备可佩戴在用户身体的相应部位。当头戴式设备在这些不同的身体佩戴状态之间移动时，其当前操作模式可能会发生变化。在某些情况下，多个候选设备状态可能包括一个或多个附加设备状态，且头戴式设备在进入这些附加设备状态时可能会改变其当前操作模式。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476392538_1.jpg)

**Technical Field (技术领域)**:  
本专利属于头戴式设备技术领域，具体涉及基于设备状态自动切换操作模式的技术。

**Background (发明背景)**:  
头戴式设备通常用于向用户提供信息，例如通过虚拟现实、增强现实或混合现实系统显示视觉信息、音频输出和/或触觉反馈。用户可以通过触摸输入、语音命令等方式与设备交互以控制其操作。然而，现有技术中，头戴式设备在不同佩戴位置或使用场景下的操作模式切换不够智能化和自动化，可能导致用户体验不佳或操作不便。本发明旨在解决这一问题，通过自动识别设备状态并切换相应的操作模式来提升设备的适应性和用户体验。

**Summary (发明总览)**:  
本发明提出了一种基于设备状态自动切换操作模式的头戴式设备操作方法。核心思路是根据设备当前状态（如佩戴位置或配置）选择合适的操作模式。实现路径包括识别设备当前状态、确定其属于多个候选状态中的哪一个，并切换到对应的操作模式。当设备状态发生变化时，系统会相应地更新操作模式。此外，本发明还引入了过渡操作模式，以应对状态切换过程中的特殊需求。这种方法相较于现有技术，能够更智能地适应用户的使用场景，提升设备的灵活性和用户体验。

**Key Innovation (核心创新)**:  
1. 设备状态识别机制：通过检测头戴式设备的朝向和配置来确定其当前状态，例如面部佩戴、额头佩戴或躯干佩戴状态。
实现方式：利用内置传感器（如陀螺仪、加速度计）和/或眼动追踪器来获取设备的空间位置和姿态信息。
功能：实现对设备佩戴位置的精确识别，为后续操作模式切换提供依据。
2. 多状态操作模式切换：针对不同的身体佩戴状态（如面部、额头、躯干），预设对应的操作模式。
实现方式：建立状态与操作模式的映射关系，根据识别到的状态自动切换模式。
功能：确保设备在不同佩戴位置下提供最佳的功能和交互体验。
3. 过渡操作模式：当设备状态发生变化时，引入过渡操作模式以处理状态切换过程中的特殊需求。
实现方式：设置状态切换的触发条件和过渡逻辑。
功能：保证状态切换过程的平稳性和用户操作的连续性。
4. 附加设备状态处理：除了身体佩戴状态外，还支持对附加状态（如放置在桌面、连接充电设备）的识别和模式切换。
实现方式：通过检测设备与外部环境的物理接触或连接状态来判断附加状态。
功能：扩展设备的应用场景，提高设备的适应性和实用性。
5. 默认操作模式：当检测到无法识别的设备状态时，自动切换到默认操作模式以保证设备的基本功能。
实现方式：预设默认模式，并在无法匹配任何候选状态时触发。
功能：确保设备在异常情况下仍能正常工作，避免用户困惑。
6. 眼动追踪集成：利用眼动追踪器提供的信息来辅助设备状态识别。
实现方式：将眼动数据与空间位置数据结合分析。
功能：提高状态识别的准确性和响应速度，特别是在用户视线变化频繁的场景下。
7. 应用场景与价值：适用于虚拟现实、增强现实和混合现实系统，以及需要频繁切换使用场景的便携式设备。
独特价值：提供更智能、更灵活的操作模式切换机制，提升用户体验和设备易用性。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476392538)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260086605)**
<br/><br/>

---


<br/>

### 32. 基于活动窗口和分块图像处理的系统与方法

**Title (EN)**: ACTIVE WINDOW AND TILE-BASED IMAGE PROCESSING SYSTEMS AND METHODS  
**Pub. No.**: US20260087589

**Applicant**: Apple Inc.  
**Inventor**: [Jim C. Chou](https://patents.google.com/?inventor=Jim+C.+Chou&assignee=Apple&country=US&num=100&sort=new), [Sorin C. Cismas](https://patents.google.com/?inventor=Sorin+C.+Cismas&assignee=Apple&country=US&num=100&sort=new), [Ran Hao](https://patents.google.com/?inventor=Ran+Hao&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
一种设备包括用于显示基于处理后的图像数据的图像帧的显示器和图像处理电路。图像处理电路可确定与图像帧的一部分相关联的活动窗口，并根据活动窗口相对于图像帧的位置确定分块的位置。此外，分块的集合可封装活动窗口。图像处理电路还可获取对应于分块的输入图像数据的各个部分，并独立处理每个分块以生成处理后的图像数据的各个部分。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476393622_1.jpg)

**Technical Field (技术领域)**:  
图像处理技术领域，具体涉及基于活动窗口和分块处理的电子显示图像处理。

**Background (发明背景)**:  
现代电子设备广泛使用电子显示器来呈现视觉信息，如文本、静态图像和视频。然而，随着显示器分辨率和刷新率的提高，处理全帧图像数据变得资源密集且耗时。此外，现有技术难以在带宽和实时性限制下高效处理图像数据。

**Summary (发明总览)**:  
本发明提出了一种基于活动窗口和分块处理的图像处理方法，通过将图像帧划分为多个分块并独立处理每个分块来提高处理效率。核心思路是首先确定图像帧中的活动窗口，然后根据活动窗口的位置划分分块并处理这些分块。这种方法通过减少不必要的处理区域和实现并行处理，显著提升了处理效率并降低了延迟。

**Key Innovation (核心创新)**:  
1. 基于活动窗口的图像帧分块技术，通过确定活动窗口的位置来划分分块，从而避免对整个图像帧进行不必要的处理。
2. 分块独立处理机制，每个分块的处理结果与其他分块无关，允许并行处理多个分块以减少处理时间。
3. 邻居数据共享机制，通过使用邻居行缓冲区和邻居列缓冲区来共享相邻分块的数据，减少重复数据获取，提高处理效率。
4. 动态调整分块大小和位置的技术，根据图像帧大小、输入图像数据特性和处理需求（如缩放、旋转、颜色适应）来优化分块参数。
5. 图像处理电路中的MSR（内存到内存缩放和旋转）模块设计，能够高效处理输入图像数据并调整像素值的缩放、方向和颜色/亮度属性。
6. 通过减少重复数据获取和优化DMA（直接内存访问）使用，进一步提升处理效率并降低系统资源消耗。
7. 本发明可应用于虚拟现实设备、车载仪表盘和高分辨率显示器等场景，能够在保证实时性的同时提升图像质量并降低功耗。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476393622)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260087589)**
<br/><br/>

---


<br/>

### 33. 中断媒体播放的方法和设备

**Title (EN)**: Method and Device for Interrupting Media Playback  
**Pub. No.**: US20260089361

**Applicant**: Apple Inc.  
**Inventor**: [Jessica Trinh](https://patents.google.com/?inventor=Jessica+Trinh&assignee=Apple&country=US&num=100&sort=new), [Brian W. Temple](https://patents.google.com/?inventor=Brian+W.+Temple&assignee=Apple&country=US&num=100&sort=new), [Eddy Zexin Liang](https://patents.google.com/?inventor=Eddy+Zexin+Liang&assignee=Apple&country=US&num=100&sort=new)  
**Publication Date**: 26.03.2026

**Abstract**:  
本发明的一些实施例包括：在通过计算系统呈现媒体时，从物理环境中获取音频样本；在获取音频样本后，确定音频样本的类别；基于确定的音频样本类别确定音频样本的优先级值；在确定音频样本的优先级值满足中断标准后，判断计算系统的用户是否对音频样本做出反应；如果在预定时间内用户未对音频样本做出反应，则修改媒体的呈现。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-03/US476395583_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及媒体播放控制领域，具体为在检测到声音时中断或修改媒体播放的技术。

**Background (发明背景)**:  
在用户消费媒体内容（如看电影或听音乐）时，可能会错过重要的环境声音，如门铃或婴儿的哭声。然而，对每个声音都中断媒体播放会严重影响用户体验，例如对背景噪音的误判。本发明旨在解决这一问题，通过智能判断声音的重要性来决定是否中断媒体播放。

**Summary (发明总览)**:  
本发明提出了一种智能中断媒体播放的方法，通过分析环境中的音频样本并判断其优先级来决定是否中断媒体播放。
首先，系统在播放媒体时持续采集环境音频样本，并对其分类以确定声音类型。
接着，根据声音类型赋予优先级值，并判断该值是否满足中断标准。
如果满足，系统会进一步判断用户是否对声音做出反应。
若用户未在预定时间内做出反应，系统将自动中断或修改媒体播放。
本发明通过智能判断声音的重要性，避免了不必要的播放中断，提升了用户体验。

**Key Innovation (核心创新)**:  
1. 音频样本采集与分类技术：通过在播放媒体时持续采集环境音频样本，并利用分类算法确定声音类型，实现对环境声音的智能识别。
2. 优先级值评估机制：根据音频样本的分类结果，系统会赋予其相应的优先级值，该值基于声音的重要性和紧急程度进行动态调整。
3. 中断标准判断逻辑：系统根据优先级值判断是否满足中断标准，只有当声音的重要性达到预设阈值时，才会触发后续的用户反应检测。
4. 用户反应检测机制：在触发中断标准后，系统会检测用户是否对声音做出反应，例如是否移动或操作设备，以避免误判。
5. 媒体播放修改策略：如果用户未在预定时间内做出反应，系统将自动中断或降低媒体播放音量，确保用户能够及时注意到重要声音。
6. 智能误判过滤：通过结合音频分类和用户反应检测，系统能够有效过滤掉不重要的环境噪音，避免不必要的播放中断。
7. 应用场景与价值：本发明可应用于智能家居、媒体播放设备等场景，为用户提供更智能、更人性化的媒体播放体验，尤其在需要兼顾媒体消费和环境感知的情境中具有独特价值。

**[View Full Patent @ WIPO](https://patentscope.wipo.int/search/en/detail.jsf?docId=US476395583)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260089361)**
<br/><br/>

---



**Total Patents**: 33  
**Last Updated**: 20260329

---

The Patent Scoop Trio
