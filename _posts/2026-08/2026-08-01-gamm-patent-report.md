---
layout: post
title: "其他专利小快报 2026-08-01"
date: 2026-08-01 18:58:30 +0800
categories: 其他
---

**New Patents**: 33  

---


<br/>

### 1. 人工智能系统中的语音-文本对齐引擎

**Title (EN)**: SPEECH-TEXT ALIGNMENT ENGINE IN AN ARTIFICIAL INTELLIGENCE SYSTEM  
**Pub. No.**: US20260220386

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ruchao FAN](https://patents.google.com/?inventor=Ruchao+FAN&country=US&num=100&sort=new), [Jinyu LI](https://patents.google.com/?inventor=Jinyu+LI&country=US&num=100&sort=new), [Rui ZHAO](https://patents.google.com/?inventor=Rui+ZHAO&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明描述了用于在人工智能系统中提供语音-文本对齐管理的方法、系统及计算机存储介质。该语音处理引擎包括一个作为原始口语与其对应文本表示之间的中介的语音-文本对齐引擎，确保实时处理和翻译任务。语音处理引擎利用语音编码器将口语转换为代表其声学特征的数字化信号。数据随后通过语音-文本对齐引擎，该引擎包括一个用于时间和序列对齐的连接主义时间分类（CTC）层，以及一个用于微调语音嵌入以使其与文本嵌入的潜在空间更紧密匹配的改进型q-former层。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484351224_1.jpg)

**Technical Field (技术领域)**:  
人工智能领域，具体涉及语音处理技术，包括语音-文本对齐、语音编码和大型语言模型集成。

**Background (发明背景)**:  
人工智能系统依赖语音处理技术来理解和处理人类语言，但现有系统在将语音数据与文本模型结合时存在挑战。
由于语音中的不流畅性和文本序列的固定结构差异，传统方法难以高效处理复杂的语音模式。
这导致语音识别、翻译和摘要等任务的效果降低。
本发明旨在解决语音数据与文本模型之间的对齐问题，以提高处理效率和准确性。

**Summary (发明总览)**:  
本发明提出了一种改进的语音处理引擎，通过语音-文本对齐引擎实现高效的语音到文本转换。
该引擎利用CTC层处理时间和序列对齐问题，并通过改进型q-former层调整语音嵌入以匹配文本的潜在空间。
此外，引擎采用了一种令牌交换策略，在训练过程中交换语音和文本的嵌入，以增强对齐效果。
通过这些技术，系统能够更准确地处理复杂的语音数据，并生成更符合文本模型需求的输出。
本发明相较于传统方法，在处理语音数据时提供了更高的准确性和效率。

**Key Innovation (核心创新)**:  
1. 引入CTC层进行时间和序列对齐，解决了语音与文本序列长度不匹配的问题，确保语音数据与文本结构的一致性。
2. 采用改进型q-former层微调语音嵌入，使其与文本嵌入的潜在空间更紧密匹配，提升了语音数据的文本兼容性。
3. 实施令牌交换策略，在训练过程中交换语音和文本的嵌入，增强模型对不同语音模式的适应能力。
4. 通过整合CTC层和q-former层，系统能够更有效地处理包含不流畅性和复杂声学特征的语音数据。
5. 该方法支持实时处理和翻译任务，提高了语音识别、翻译和摘要等任务的效率和准确性。
6. 应用于智能助手和语音交互系统时，能够提供更自然、更准确的语音交互体验。
7. 特别适用于多语言环境下的语音处理任务，解决了跨语言语音对齐的难题。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484351224)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220386)**
<br/><br/>

---


<br/>

### 2. 用于训练和评估自然语言模型的合成对话数据生成方法

**Title (EN)**: Generating Synthetic Conversation Data for Training and Evaluation of Natural Language Models  
**Pub. No.**: US20260220172

**Applicant**: Google LLC  
**Inventor**: [Harsh Lara](https://patents.google.com/?inventor=Harsh+Lara&country=US&num=100&sort=new), [Luke Beck Friedman](https://patents.google.com/?inventor=Luke+Beck+Friedman&country=US&num=100&sort=new), [Sameer Ahuja](https://patents.google.com/?inventor=Sameer+Ahuja&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明主要涉及自动生成编码至少两方自然语言对话的数据的方法和系统。对话数据可通过一个或多个语言生成模型自动生成，因此可称为合成对话数据。合成对话数据可模拟一个或多个假设或真实人类（例如用户）参与对话的言语模式（例如提示、回应提示及其组合）。在各种应用中，合成对话数据被用于训练、预训练、微调及/或评估用于生成合成对话数据的生成语言模型及/或其他生成语言模型的性能。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484350985_1.jpg)

**Technical Field (技术领域)**:  
自然语言处理领域，具体涉及对话数据生成和对话系统训练技术。

**Background (发明背景)**:  
推荐系统是机器学习在工业界的重要成功案例，但现有的大规模推荐系统通常缺乏透明度，用户难以控制推荐结果并探索交互序列。对话推荐系统通过实时对话改善了这些问题，但训练这些系统需要大量真实标注的对话数据。获取足够数量和多样性的训练数据以训练通用性强的对话机器人非常困难。

**Summary (发明总览)**:  
本发明提出了一种通过模拟用户生成合成对话数据的方法，以解决对话系统训练数据不足的问题。该方法利用语言生成模型模拟用户与对话系统的交互，自动生成大量多样化的对话数据。这些数据可用于训练、预训练和微调对话系统，并评估其性能。相比传统依赖人工生成数据的方法，本发明能够快速、经济地生成大量高质量对话数据，提升对话系统的训练效率和效果。

**Key Innovation (核心创新)**:  
1. 通过用户模拟器生成合成对话数据，用户模拟器包含自然语言理解（NLU）模型、响应生成模型和自然语言生成（NLG）模型，能够模拟真实用户的对话行为。
2. 用户模拟器的响应生成模型通过偏好链和意图轨迹进行配置，能够根据对话状态和语义理解生成符合用户偏好的响应。
3. 利用对话模板引导合成对话数据的生成，通过对话主题、偏好链和意图轨迹的组合，实现对对话方向的精确控制。
4. 用户模拟器可与对话代理（如聊天机器人）进行交互，生成用于评估对话代理性能的评估数据，替代传统的人工评估方法。
5. 合成对话数据可用于训练、预训练和微调对话系统，提升其通用性和性能。
6. 本发明可应用于推荐系统、聊天机器人等交互式应用场景，提供高效、低成本的对话数据生成解决方案。
7. 通过模拟大量真实和假设用户，本发明能够生成多样化的对话数据，帮助对话系统更好地适应不同用户需求。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484350985)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220172)**
<br/><br/>

---


<br/>

### 3. 深度感知照片编辑

**Title (EN)**: Depth-Aware Photo Editing  
**Pub. No.**: US20260220803

**Applicant**: Google LLC  
**Inventor**: [Tim Phillip Wantland](https://patents.google.com/?inventor=Tim+Phillip+Wantland&country=US&num=100&sort=new), [Brandon Charles Barbello](https://patents.google.com/?inventor=Brandon+Charles+Barbello&country=US&num=100&sort=new), [Christopher Max Breithaupt](https://patents.google.com/?inventor=Christopher+Max+Breithaupt&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本文描述了用于深度感知图像编辑和交互功能的方法和系统。具体而言，计算机应用程序可利用深度图和分割数据的组合来处理一个或多个图像，并生成这些图像的编辑版本。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484351683_1.jpg)

**Technical Field (技术领域)**:  
图像处理领域，具体涉及基于深度感知和图像分割的智能照片编辑技术。

**Background (发明背景)**:  
现代计算设备通常配备图像捕捉设备，如相机，但这些设备对图像的后处理能力有限。
现有技术主要针对简单的图像校正，如红眼去除等，缺乏对图像深度信息的利用。
传统方法难以实现对图像中不同对象进行智能分割和深度感知的编辑。
本发明旨在结合深度图和分割数据，提供更智能、更精细的图像编辑功能。

**Summary (发明总览)**:  
本发明提出了一种结合深度图和图像分割数据的深度感知照片编辑方法。
通过分析图像的深度信息和分割数据，系统能够智能识别图像中的不同对象和背景。
编辑过程可以实时进行，适用于相机应用的实时取景器或图像的后处理。
该方法利用卷积神经网络（CNN）进行图像分割，并结合立体成像技术生成深度信息。
相较于传统方法，本发明能够实现更精准的对象分割和深度感知编辑。

**Key Innovation (核心创新)**:  
1. 结合深度图和图像分割数据，通过分析像素级深度信息和对象分割掩码，实现对图像中不同对象和背景的智能识别和处理。
2. 利用卷积神经网络（CNN）进行实时图像分割，能够处理视频流（如每秒30帧）和静态图像，并生成精确的分割预测掩码。
3. 采用立体成像技术，通过匹配左右立体图像的像素并计算视差，生成高精度的深度图，支持对场景深度信息的全面感知。
4. 提出了一种基于非重叠图像块的分层深度估计方法，通过从小尺寸图像块到大尺寸图像块的递归匹配，降低计算复杂度并提高深度估计效率。
5. 通过对CNN的训练，使其能够处理第一帧图像或新出现对象的场景，并利用仿射变换的地面真值掩码优化网络对不完整掩码的适应能力。
6. 该技术可应用于相机应用的实时取景器，实现实时深度感知编辑，如智能背景虚化、对象选择和增强现实应用。
7. 独特价值在于提供更智能、更精准的图像编辑功能，提升用户对照片和视频的处理体验，尤其适用于需要深度感知和对象分割的创意内容创作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484351683)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220803)**
<br/><br/>

---


<br/>

### 4. 使用主动声学传感进行佩戴检测和/或可穿戴设备调节检测

**Title (EN)**: On-Head Detection and/or Hearable-Adjustment Detection using Active Acoustic Sensing  
**Pub. No.**: US20260222751

**Applicant**: Google LLC  
**Inventor**: [Xiaoran Fan](https://patents.google.com/?inventor=Xiaoran+Fan&country=US&num=100&sort=new), [Trausti Thormundsson](https://patents.google.com/?inventor=Trausti+Thormundsson&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明描述了使用主动声学传感进行佩戴检测和/或可穿戴设备调节检测的技术和方法。可穿戴设备（例如耳塞）能够执行声波脉搏描记法，这是一种主动声学方法，能够感知用户外耳和中耳的细微生理相关变化。可穿戴设备在用户外耳周围或内部形成至少部分密封，从而在密封、可穿戴设备、耳道和鼓膜之间形成声学回路。通过发送和接收声学信号，可穿戴设备可以识别声学回路的变化，以执行佩戴检测和/或可穿戴设备调节检测的各个方面。可穿戴设备的尺寸、成本和功耗可以...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484353835_1.jpg)

**Technical Field (技术领域)**:  
本专利属于可穿戴设备技术领域，具体涉及使用主动声学传感进行佩戴检测和设备调节检测。

**Background (发明背景)**:  
无线技术在日常生活中变得普遍，使用户能够方便地通信和访问数据。无线可穿戴设备（如无线耳塞和无线耳机）允许用户在听音乐、有声书、播客和视频时自由移动。随着无线可穿戴设备的普及，市场对在不引入硬件变化的情况下为现有设备增加额外功能的需求日益增长。然而，现有技术中的一些设计为了满足尺寸目标而放弃了如佩戴检测和设备调节检测等便利功能。

**Summary (发明总览)**:  
本发明提出了一种使用主动声学传感进行佩戴检测和可穿戴设备调节检测的方法。该方法利用声波脉搏描记法，通过在用户耳道内发送和接收声学信号来感知耳道内的变化，从而判断设备是否被佩戴或用户是否在调整设备。该方法无需额外的硬件组件，如光学或电学传感器，从而降低了设备的尺寸、成本和功耗，提升了用户体验。

**Key Innovation (核心创新)**:  
1. 利用声波脉搏描记法，通过主动声学传感在用户耳道内发送和接收声学信号，实现对设备佩戴状态的检测。
2. 通过在用户外耳周围或内部形成至少部分密封，形成声学回路，利用声学回路的变化来识别设备是否被佩戴或用户是否在调整设备。
3. 无需额外的光学或电学传感器，仅通过声学信号的变化即可实现佩戴检测和设备调节检测，降低了设备的硬件复杂度和成本。
4. 该方法能够在设备尺寸受限的情况下集成额外的功能，提升了设备的紧凑性和功能性。
5. 通过控制与可穿戴设备连接的计算机设备的操作，实现基于佩戴检测和设备调节检测的智能交互。
6. 该技术可应用于无线耳塞和耳机等可穿戴设备，提供更智能的用户体验，例如自动暂停音乐播放或调整音量。
7. 推测该专利可应用于需要低功耗、高精度佩戴检测的场景，如运动监测、健康监测等，为用户提供独特的价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484353835)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260222751)**
<br/><br/>

---


<br/>

### 5. 复杂数据库的大语言模型接口

**Title (EN)**: LARGE LANGUAGE MODEL INTERFACE FOR COMPLEX DATABASES  
**Pub. No.**: US20260220380

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Maria Angels DE LUIS BALAGUER](https://patents.google.com/?inventor=Maria+Angels+DE+LUIS+BALAGUER&country=US&num=100&sort=new), [Sara Malvar MAUA](https://patents.google.com/?inventor=Sara+Malvar+MAUA&country=US&num=100&sort=new), [Swati SHARMA](https://patents.google.com/?inventor=Swati+SHARMA&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明提出了一种新颖的方法和系统，通过使用大语言模型（LLM）创建复杂数据库的便捷接口。该系统包括一个自定义提示生成器，用于将自然语言查询转换为自定义提示。这些提示用于控制LLM与数据库查询工具的交互方式。数据库查询工具以数据库可理解的形式提供查询，并接收来自数据库的响应。该系统适用于获取非自然语言形式的信息，这些信息不适合作为嵌入由LLM处理。从数据库获取的信息被包含在LLM生成的答案中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484351218_1.jpg)

**Technical Field (技术领域)**:  
本专利属于数据库接口技术领域，具体涉及利用大语言模型（LLM）实现对复杂数据库的高效访问。

**Background (发明背景)**:  
复杂数据库中包含大量难以访问的信息，主要由于数据库使用的复杂性以及信息本身的特性，例如难以用关键词索引的信息、不完整或不一致的数据，以及用户难以直观判断响应是否正确。此外，数据库设计也可能带来困难，复杂的搜索和访问方式需要用户学习才能有效使用。当数据库中的信息对需要它的人不可访问时，数据库就无法发挥其作用。改进数据库接口可以简化用户访问复杂数据库中信息的过程。

**Summary (发明总览)**:  
本发明提出了一种利用大语言模型（LLM）作为复杂数据库接口的方案。用户通过自然语言查询与LLM交互，LLM通过自定义提示生成器将查询转换为数据库查询指令。数据库查询工具在LLM的控制下执行查询并返回结果。LLM将结果整合并以自然语言形式反馈给用户。该方案通过对话式交互简化了数据库查询过程，降低了用户使用门槛，并能够处理复杂或非结构化的数据。

**Key Innovation (核心创新)**:  
1. 通过自定义提示生成器将自然语言查询转换为结构化的数据库查询指令，实现用户与数据库的便捷交互。
2. 利用LLM的对话能力，允许用户通过自然语言对查询进行修改和优化，无需掌握数据库命令和功能。
3. 引入数据库查询工具作为独立组件，通过LLM控制实现对特定数据库的精确查询和数据提取。
4. 采用正则表达式搜索技术，从数据库返回的结果中提取特定信息，解决信息冗余或混杂的问题。
5. 通过编排框架管理LLM、数据库查询工具和数据库之间的交互，确保各组件协同工作并共享信息。
6. 应用于生物序列数据处理领域，例如基因序列和蛋白质序列的查询和分析，无需用户理解数据库交互细节。
7. 为生物信息学研究提供支持，通过LLM与数据库的结合实现跨主要谱系的比较分析、基因组特征识别和蛋白质研究。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484351218)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220380)**
<br/><br/>

---


<br/>

### 6. 支持与业务大语言模型强交互的自适应助手大语言模型

**Title (EN)**: SELF-ADJUSTING ASSISTANT LLMS ENABLING ROBUST INTERACTION WITH BUSINESS LLMS  
**Pub. No.**: US20260221150

**Applicant**: Google LLC  
**Inventor**: [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new), [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明提供了一种方法，包括接收用户通过自然语言输入的查询，该查询指定助手界面执行的操作，并选择与助手界面交互的一个或多个业务大语言模型（LLMs）以完成操作。对于每个业务LLM，方法还包括访问适配器模块，将自然语言查询结构化为专门针对相应业务LLM的提示，发送专门针对相应业务LLM的提示以供输入，并接收来自相应业务LLM的响应内容，该内容传达了执行相应操作部分的详细信息。方法还包括基于从每个选定的业务LLM接收的响应内容生成展示内容，以供用户设备输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484352064_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及人工智能领域，具体为大语言模型（LLMs）技术，
重点是自适应助手LLMs与业务LLMs的交互。

**Background (发明背景)**:  
大语言模型（LLMs）正越来越多地被用于提供用户与数字助手界面之间的对话体验。
用户通过自然语言向LLM提出查询，LLM基于查询生成响应。
然而，现有技术中，LLMs在处理复杂业务场景时存在适配性不足的问题，
难以针对不同业务需求进行灵活调整。
本发明旨在解决LLMs在处理多样化业务需求时的交互效率和适配性问题。

**Summary (发明总览)**:  
本发明提出了一种自适应助手大语言模型（LLMs）技术，通过与多个业务LLMs交互来执行用户指定的操作。
该技术首先接收用户的自然语言查询，然后选择合适的业务LLMs进行交互。
对于每个选定的业务LLM，助手LLM通过适配器模块将查询转换为专门设计的提示，
并接收业务LLM的响应内容，最终生成展示内容供用户查看。
该方法通过适配器模块实现了对不同业务LLMs的灵活适配，
提高了交互的鲁棒性和效率。

**Key Innovation (核心创新)**:  
1. 通过适配器模块将自然语言查询转换为专门针对不同业务LLMs的提示，
   实现了与多样化业务LLMs的无缝交互。
2. 提供了用户选择机制，允许用户从多个候选业务LLMs中选择最合适的模型，
   提高了交互的个性化和精准度。
3. 适配器模块支持多种提示生成方式，包括基于历史成功提示的结构化转换和
a   使用专门训练的前缀模型生成软提示，增强了提示的适配性和有效性。
4. 实现了跨云服务提供商的多LLM协同工作，
   支持来自不同云平台的业务LLMs的集成和交互。
5. 提供了用户反馈驱动的提示优化机制，
   通过用户不满意反馈调整提示参数，
   持续改进交互效果。
6. 助手LLM采用编码器-解码器架构，
   并通过适配器模块扩展了解码器功能，
   增强了与业务LLMs的交互能力。
7. 该技术可应用于企业级智能助手产品，
   为用户提供跨业务领域的智能交互体验，
   提升业务处理效率和用户满意度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484352064)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260221150)**
<br/><br/>

---


<br/>

### 7. 在生成内容特定部分启用用户手势以基于这些部分智能选择生成内容

**Title (EN)**: ENABLING USER GESTURES AT PORTIONS OF GENERATIVE CONTENT FOR INTELLIGENT SELECTION OF GENERATIVE CONTENT BASED ON SUCH PORTIONS  
**Pub. No.**: US20260219771

**Applicant**: GOOGLE LLC  
**Inventor**: [Brett Barros](https://patents.google.com/?inventor=Brett+Barros&country=US&num=100&sort=new), [Kimberly Harvey](https://patents.google.com/?inventor=Kimberly+Harvey&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本文所述的实施例涉及一种应用程序，该应用程序能够接收用户对生成内容特定部分的手势输入，从而智能地选择生成内容并/或渲染补充生成内容，而无需用户再次提供详细提示。生成内容的每个部分可以根据构成该部分的术语之间的语义关系来识别。这些生成内容的部分可以是预定的，也可以根据接收到的用户输入（例如手势）来确定。特定部分的生成内容可以分配一个或多个图形用户界面（GUI）特征，以指示该部分生成内容可用于接收一个或多个手势。当用户向特定部分发出手势时...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484350544_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及基于用户手势智能处理生成内容的技术。

**Background (发明背景)**:  
人机对话通常通过自动化助手等交互式软件应用进行，用户通过语音或文本输入与这些助手交互。当用户需要关于生成内容的更详细信息时，通常需要再次输入详细提示，这既耗时又浪费计算资源。此外，响应后续提示生成的补充内容可能与用户需求不相关。

**Summary (发明总览)**:  
本发明提出了一种自动化助手或其他生成式应用，能够接收用户对生成内容语义区分部分的手势输入，以智能选择生成内容的部分、创建补充生成内容或执行其他操作。用户无需提供详细提示即可与生成内容交互。应用通过识别生成内容的语义区分部分并提供相应的GUI提示，使用户能够通过不同类型的手势触发不同的生成内容或操作。例如，单击手势可能请求关于选定部分的额外信息，而长按手势则可能生成更详细的补充内容。

**Key Innovation (核心创新)**:  
1. 通过识别生成内容中的语义区分部分，使用户能够直接通过手势选择特定内容，而无需输入详细提示。
2. 应用在语义区分部分提供GUI提示，告知用户可用的手势操作，提升交互的直观性和便捷性。
3. 根据用户手势类型选择不同的生成模型或生成参数，以提供更符合用户需求的补充内容。
4. 支持多种手势类型，包括单击、长按和二维手势（如滑动），以实现更丰富的交互方式。
5. 结合用户的历史行为、个人知识图谱等上下文数据，生成更个性化的补充内容。
6. 利用大型语言模型（LLM）等先进模型处理用户手势触发的提示，生成高度相关且详细的补充内容。
7. 本专利可应用于智能助手、内容创作工具等领域，为用户提供更高效、更精准的生成内容交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484350544)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260219771)**
<br/><br/>

---


<br/>

### 8. 使用多个入耦合器的平面与曲面组合构造的显示波导

**Title (EN)**: WAVEGUIDES FOR DISPLAYS CONSTRUCTED FROM A COMBINATION OF FLAT AND CURVED SURFACES USING PLURAL INCOUPLERS  
**Pub. No.**: US20260219505

**Applicant**: GOOGLE LLC  
**Inventor**: [Daniel Adema](https://patents.google.com/?inventor=Daniel+Adema&country=US&num=100&sort=new), [Timothy Paul Bodiya](https://patents.google.com/?inventor=Timothy+Paul+Bodiya&country=US&num=100&sort=new), [Shreyas Potnis](https://patents.google.com/?inventor=Shreyas+Potnis&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明涉及一种由平面和曲面组合构成的显示波导，其特点是在波导中以精确角度间隔设置多个入耦合器，这些角度与波导的衍射光栅角度相匹配或对应，从而实现在多个位置向同一光栅结构注入光，同时保持k空间闭合，防止出现非预期的折射或失真。波导中入耦合器和出耦合器周围的区域为平面，而入耦合器和出耦合器之间的区域包含一个或多个曲面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484350255_1.jpg)

**Technical Field (技术领域)**:  
本专利属于增强现实/虚拟现实显示技术领域，具体涉及用于近眼显示设备的波导光学系统。

**Background (发明背景)**:  
头戴式显示器（HMDs）通常使用波导将图像源的光耦合到光导基底中，并通过输出耦合器将光引导至用户眼睛。传统平面波导嵌入曲面透镜时会导致设备外观笨重，而曲面波导则因非平行表面导致光传播角度不一致，产生图像失真和伪影问题。

**Summary (发明总览)**:  
本发明提出了一种新型波导架构，通过在波导中设置多个入耦合器并结合平面与曲面设计，解决了传统曲面波导的光学失真问题。该设计利用平面和曲面波导的组合，使波导更好地适应透镜曲率，同时减少光传播过程中的变形。波导被分为多个分段区域，包括平面和曲面区域，并通过精确角度的入耦合器实现光的有效耦合和传播。

**Key Innovation (核心创新)**:  
1. 采用多个入耦合器以精确角度间隔布置，确保光在波导中以匹配角度注入，从而实现k空间闭合并防止非预期折射或失真。
2. 波导设计结合了平面和曲面区域，其中入耦合器和出耦合器周围区域为平面，而中间区域包含曲面，以更好地适应透镜曲率并减少光传播变形。
3. 通过分段设计，波导被分为多个区域，包括平面和曲面区域，并在关键区域（如入耦合器和出耦合器之间）采用平面设计以减少光传播过程中的变形。
4. 实现了不同视场区域的同时显示，包括重叠和非重叠视场区域，并支持不同分辨率的图像显示，以满足多样化的显示需求。
5. 提供了双眼对齐功能，确保设备佩戴者双眼可见的视场区域具有一致的显示效果，提升用户体验。
6. 该设计可应用于近眼显示设备，如智能眼镜等，在保持光学性能的同时实现更薄、更符合人体工学的设备外观。
7. 通过减少传统平面波导的厚度限制和曲面波导的光学失真问题，本发明为下一代增强现实和虚拟现实设备提供了更优的光学解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484350255)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260219505)**
<br/><br/>

---


<br/>

### 9. 在线会议中用于共享内容的演示者焦点模式

**Title (EN)**: PRESENTER FOCUS MODE FOR SHARING CONTENT IN ONLINE MEETINGS  
**Pub. No.**: US20260222236

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Defne KUDELA](https://patents.google.com/?inventor=Defne+KUDELA&country=US&num=100&sort=new), [Nakul MADAAN](https://patents.google.com/?inventor=Nakul+MADAAN&country=US&num=100&sort=new), [Mihai Alexandru MEDINTU](https://patents.google.com/?inventor=Mihai+Alexandru+MEDINTU&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
一种数据处理系统实现了从第一用户的第一客户端设备接收用户选择信息，该信息指示从一或多个文件的多处位置选择多个内容；分析用户选择信息以提取与每个选择相关联的数据和格式信息；将提取的数据格式化为表示数据和格式信息的数据结构；接收来自第一客户端设备的命令，以通过在线会议平台与参与在线会议的一或多个第二客户端设备共享内容；并且响应于接收内容共享命令：基于表示数据和格式信息的数据结构生成多个用户选择的图形表示；并通过在线会议平台将图形表示提供给第一客户端设备及参与在线会议的一或多个第二客户端设备。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484353267_1.jpg)

**Technical Field (技术领域)**:  
在线会议技术领域，具体涉及内容共享和屏幕协作技术。

**Background (发明背景)**:  
在线会议平台允许用户进行视频会议和协作。屏幕共享功能使用户能够与会议中的其他用户共享设备屏幕上的文档内容。然而，这些文档通常包含评论、更改和修订，可能会使屏幕变得杂乱并分散会议参与者的注意力。此外，用户可能希望共享多个文档的内容，但现有平台只允许用户一次共享一个文档的内容或切换文档，或者用户可能选择共享整个桌面，但这可能会意外暴露敏感信息。因此，需要改进在线会议中的内容共享系统和方法。

**Summary (发明总览)**:  
本发明提出了一种在线会议中的焦点模式内容共享方案。用户可以从一个或多个文件的多个位置选择内容，系统会分析并提取这些选择的数据和格式信息，生成一个包含选定内容的图形表示。该图形表示通过在线会议平台提供给所有参会者，提供了一个清晰、不杂乱的内容视图。该方法通过自动生成结构化的内容布局，提升了会议效率，减少了因切换文档或暴露无关信息而带来的干扰。

**Key Innovation (核心创新)**:  
1. 支持从多个文件或多处位置选择内容，用户可以自由组合需要共享的内容片段。
2. 利用语言模型或预定义模板自动生成选定内容的布局，确保图形表示的整洁和有序。
3. 生成的图形表示仅包含用户选择的内容，屏蔽了无关的评论、标记和格式干扰。
4. 通过分析用户选择信息，系统能够智能识别内容类型并选择最合适的模板进行布局。
5. 提供用户界面，允许用户对选择的内容进行进一步编辑和调整，以满足特定会议需求。
6. 该方法减少了在线会议平台对计算资源的消耗，因为无需频繁切换文档或处理复杂的屏幕内容。
7. 应用于需要高效协作和内容共享的在线会议场景，如远程办公、在线教育和项目讨论等，能够显著提升会议质量和参与者的专注度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484353267)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260222236)**
<br/><br/>

---


<br/>

### 10. 用于文本输入的简略手写技术

**Title (EN)**: ABBREVIATED HANDWRITING TECHNIQUE FOR TEXT INPUT  
**Pub. No.**: US20260219740

**Applicant**: Google LLC  
**Inventor**: [Shumin Zhai](https://patents.google.com/?inventor=Shumin+Zhai&country=US&num=100&sort=new), [Zheer Xu](https://patents.google.com/?inventor=Zheer+Xu&country=US&num=100&sort=new), [Shanqing Cai](https://patents.google.com/?inventor=Shanqing+Cai&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
计算设备可以接收包含一系列手写字符的手写输入指示，其中手写字符序列包括一系列单词缩写。计算设备可以使用语言模型确定与单词缩写序列相对应的一系列候选单词。计算设备可以输出用于在显示设备上显示的用户界面，以呈现候选单词序列。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484350510_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及手写输入和文本预测技术。

**Background (发明背景)**:  
移动计算设备如智能手机和平板电脑通常使用触摸屏进行文本输入，用户可以通过虚拟键盘或手写识别来输入文本。然而，现有技术中，手写输入需要逐字逐字母书写，效率较低且容易出错。本发明旨在解决这一问题，通过简略手写输入提高文本输入的速度和准确性。

**Summary (发明总览)**:  
本发明提出了一种简略手写输入方法，用户无需完整书写每个单词的每个字母，而是可以通过简略模式输入单词缩写。计算设备利用语言模型将这些缩写转换为完整的候选单词序列，并将其展示给用户。这种方法相较于传统手写输入，显著提高了输入速度和效率，同时保持了较高的准确性。

**Key Innovation (核心创新)**:  
1. 用户可以通过简略手写模式输入单词缩写，而无需完整书写每个字母，从而提高输入速度。
2. 利用语言模型对简略手写输入进行分析和预测，生成对应的候选单词序列。
3. 通过用户界面展示候选单词序列，允许用户快速选择所需的单词，提升交互效率。
4. 实现了手写输入与文本预测技术的结合，减少了用户输入错误的可能性。
5. 该技术适用于触摸屏设备，如智能手机和平板电脑，能够在各种应用场景中提供更便捷的文本输入方式。
6. 通过简略手写输入，用户可以更快速地输入短语或句子，尤其在需要快速记录的场景中具有独特价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484350510)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260219740)**
<br/><br/>

---


<br/>

### 11. 安全管理系统中的容器模式管理引擎

**Title (EN)**: CONTAINER MODE MANAGEMENT ENGINE IN A SECURITY MANAGEMENT SYSTEM  
**Pub. No.**: US20260220254

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Jonathan GAZIT](https://patents.google.com/?inventor=Jonathan+GAZIT&country=US&num=100&sort=new), [Dotan PATRICH](https://patents.google.com/?inventor=Dotan+PATRICH&country=US&num=100&sort=new), [Idan GUTMAN](https://patents.google.com/?inventor=Idan+GUTMAN&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明涉及用于提供容器安全计算模式的方法、系统和计算机存储介质，使用安全管理系统中的容器模式管理引擎。容器安全计算模式包括容器优先考虑安全措施和实践的安全状态。容器安全计算模式可分配给容器实例，并通过容器安全代理强制执行。在操作中，初始化容器实例，将其与具有安全计算模式转换控制的容器安全代理关联。基于安全计算模式转换控制，容器实例被转换到安全状态。访问容器实例的容器操作，并根据容器实例的安全状态和安全状态配置限制容器操作的执行。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484351076_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及容器安全技术，具体为通过安全管理系统中的容器模式管理引擎实现容器安全计算模式。

**Background (发明背景)**:  
现代计算环境依赖应用程序和服务完成计算任务，分布式计算系统托管和支持不同类型的应用程序和服务。现有安全管理系统提供安全态势管理和威胁防护，但缺乏全面支持容器实例安全计算模式的计算逻辑和基础设施。容器管理器（如KUBERNETES或DOCKER）虽然管理容器实例，但无法及时有效地配置容器实例的安全计算模式，导致容器实例在运行时缺乏足够的安全保护。

**Summary (发明总览)**:  
本发明提出了一种基于安全管理系统中容器模式管理引擎的容器安全计算模式实现方案。通过容器安全代理和模式管理引擎，容器实例在初始化时关联安全计算模式转换控制，并被转换到安全状态。容器操作根据安全状态和安全状态配置被限制执行。本发明相较于现有技术，通过更全面和高效的安全管理机制，提升了容器实例在运行时对安全威胁的防护能力。

**Key Innovation (核心创新)**:  
1. 提出了容器安全计算模式的概念，通过定义安全状态（如高限制模式或基于策略的限制模式）来规范容器实例的运行行为。
2. 设计了容器模式管理引擎，支持多种安全计算模式转换控制机制（如基于时间、基于报告或基于机器学习），并能识别不同类型的容器实例。
3. 通过容器安全代理实现安全计算模式的转换和强制执行，确保容器实例在运行时处于安全状态。
4. 提供了容器配置操作与安全状态配置的集成方法，在容器实例初始化阶段即完成安全模式的分配和配置。
5. 实现了容器操作在安全状态下的运行时限制机制，通过限制容器对主机系统、网络和外部服务的访问来增强安全性。
6. 解决了传统容器管理器在初始化阶段与运行时安全配置之间的脱节问题，提升了容器安全管理的及时性和效率。
7. 本发明可应用于云原生应用安全防护场景，为容器化应用提供从创建到运行的全生命周期安全保护。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484351076)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220254)**
<br/><br/>

---


<br/>

### 12. 电子表格文档中的人工智能功能

**Title (EN)**: ARTIFICIAL INTELLIGENCE FUNCTION IN SPREADSHEET DOCUMENTS  
**Pub. No.**: US20260220363

**Applicant**: Google LLC  
**Inventor**: [Danielle LaBarbiera Jenks](https://patents.google.com/?inventor=Danielle+LaBarbiera+Jenks&country=US&num=100&sort=new), [Dmitriy Brezhnev](https://patents.google.com/?inventor=Dmitriy+Brezhnev&country=US&num=100&sort=new), [Matthew Jacob Ziegelbaum](https://patents.google.com/?inventor=Matthew+Jacob+Ziegelbaum&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本专利提供了一种在电子表格文档中实现人工智能（AI）功能的技术。用户通过用户界面（UI）访问电子表格文档，并根据与AI模型相关的操作与一个或多个单元格进行交互后提出用户查询。UI会更新以在单元格中包含接收到的用户查询，并显示一个或多个UI元素，使用户能够启动与AI模型相关的操作。在检测到用户与UI元素的交互后，与用户查询相关的提示被作为输入提供给AI模型，并获取AI模型的一个或多个输出，这些输出包括与用户查询相关的响应数据。UI会相应更新。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484351197_1.jpg)

**Technical Field (技术领域)**:  
电子表格文档的人工智能应用领域，具体涉及AI模型驱动的数据处理和用户交互技术。

**Background (发明背景)**:  
人工智能技术，特别是大语言模型（LLMs），已显著提升了自然语言处理能力。然而，现有电子表格系统主要依赖手动输入数据或预设公式进行计算，难以处理大量数据或复杂函数，导致系统资源消耗大、效率低。本发明旨在通过AI技术简化数据维护和分析过程，提升电子表格文档的智能化水平。

**Summary (发明总览)**:  
本发明通过在电子表格文档中集成AI功能，使用户能够以更智能的方式管理和分析数据。用户可以在单元格中输入与AI模型相关的任务查询，平台会提供相应的UI元素以启动AI操作。AI模型的输出结果会直接更新到单元格中，从而实现数据的自动处理和更新。本发明允许用户批量处理多个查询，并通过检测数据变化来动态更新查询结果，从而提高系统效率并减少资源消耗。

**Key Innovation (核心创新)**:  
1. 在电子表格单元格中支持用户输入AI任务查询，例如数据总结或分析请求，使用户能够以自然语言方式与数据交互。
2. 通过检测用户与UI元素的交互，动态提供AI模型输入提示，确保只有在用户明确操作时才触发AI计算，节省系统资源。
3. 支持批量处理多个用户查询，通过分时段提供查询提示，优化AI模型的计算效率并减少系统负载。
4. 根据电子表格文档的历史数据动态调整批量处理大小，实现更智能的资源分配。
5. 当用户更新包含AI查询的单元格数据时，系统会自动标记查询结果为过时，并重新提交AI模型以获取最新结果。
6. 提供用户控制机制，允许用户选择特定单元格范围或跨列的离散单元格进行AI操作，提高操作的灵活性和精确性。
7. 本发明可应用于协作文档平台，通过AI增强的数据处理功能，为团队协作中的数据管理和分析提供智能化解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484351197)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220363)**
<br/><br/>

---


<br/>

### 13. 用于手写文本的自动语言检测系统和方法

**Title (EN)**: SYSTEM AND METHOD FOR AUTOMATIC LANGUAGE DETECTION FOR HANDWRITTEN TEXT  
**Pub. No.**: US20260220365

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Xiao TU](https://patents.google.com/?inventor=Xiao+TU&country=US&num=100&sort=new), [Zhe WANG](https://patents.google.com/?inventor=Zhe+WANG&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明涉及用于手写文本的自动语言检测的方法，由系统和设备执行。在将手写文本的表示发送到语言识别引擎之前执行自动语言检测。手写输入包括一个或多个书写笔画，从输入接口接收，并与输入的坐标和输入时间相关联。手写输入基于坐标和时间被分组为单词。书写笔画被规范化，然后逐个单词进行转换以生成语言向量，例如通过循环神经网络（RNN）。语言向量用于确定手写输入的语言概率。基于语言概率，将手写输入提供给送到特定的语言识别引擎，以在尝试翻译或转录之前确定手写输入的语言。某些语言中存在的符号也可用于语言确定。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484351199_1.jpg)

**Technical Field (技术领域)**:  
手写识别技术领域，具体涉及手写文本的自动语言检测和翻译。

**Background (发明背景)**:  
现有的手写识别系统需要用户手动下载和启用语言包，并在输入时明确告知系统所使用的语言。一些在线翻译系统同时将手写文本的笔画发送到所有可用的语言识别器，这导致资源消耗大且结果混杂，难以有效选择正确结果。这种方法在处理多语言时效率低下且难以扩展。

**Summary (发明总览)**:  
本发明提供了一种高效的手写文本自动语言检测方法，通过在文本翻译之前确定具体语言识别引擎来减少性能损失。该方法接收手写文本输入，将其分组为单词并规范化，然后通过循环神经网络生成语言向量以计算语言概率。基于这些概率，系统选择特定的语言识别引擎进行最终语言确定，从而实现单次翻译。这种方法相比现有技术更加高效，适用于客户端和边缘设备。

**Key Innovation (核心创新)**:  
1. 通过分析手写文本的坐标和时间信息，将笔画分组为单词，实现精准的语言检测基础。
2. 采用循环神经网络（RNN）或双向RNN对单词进行特征提取和语言向量生成，提升语言概率计算的准确性。
3. 在将手写文本发送到特定语言识别引擎之前，使用通用引擎进行初步语言检测，减少资源消耗。
4. 通过软决策机制，根据语言概率选择最合适的语言识别引擎，避免多引擎同时运行带来的资源浪费。
5. 支持实时手写输入和文件存储的手写文本检测，适用范围广泛。
6. 在用户界面上提供语言标记功能，方便用户查看和管理不同语言的手写笔记。
7. 该技术可应用于多语言手写笔记应用、跨语言翻译工具等场景，提供高效准确的语言识别服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484351199)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220365)**
<br/><br/>

---


<br/>

### 14. 用于内容分发的多阶段行动决策

**Title (EN)**: MULTI-STAGE ACTION DETERMINATION FOR CONTENT DELIVERY  
**Pub. No.**: US20260220211

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Changshuai Wei](https://patents.google.com/?inventor=Changshuai+Wei&country=US&num=100&sort=new), [Benjamin Basil Zelditch](https://patents.google.com/?inventor=Benjamin+Basil+Zelditch&country=US&num=100&sort=new), [Xinyan Chen](https://patents.google.com/?inventor=Xinyan+Chen&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明涉及一种方法、系统及设备，包括接收在线系统用户特征数据和第一内容分发行动的数据，将特征数据输入训练好的倾向性机器学习模型，并接收来自该模型的倾向性数据。基于倾向性数据，为用户和第一内容分发行动确定第一内容分发决策。随后，接收用户和第二内容分发行动的第二特征数据，将其输入训练好的倾向性模型，并接收第二倾向性数据。基于第二倾向性数据，为用户和第二内容分发行动确定第二内容分发决策。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484351029_1.jpg)

**Technical Field (技术领域)**:  
本专利属于内容分发领域，具体涉及基于多阶段内容分发行动决策的内容分发技术。

**Background (发明背景)**:  
现有内容分发系统通常通过单一内容分发行动进行内容分发，例如推荐产品、发送推荐内容的时间或频率等。这些系统缺乏对不同变量之间相互作用的理解，导致需要大量时间和训练数据才能产生最优内容推荐。此外，现有系统侧重于短期回报目标，而非长期价值指标，且未充分考虑用户对内容的负面反应。

**Summary (发明总览)**:  
本发明提出了一种基于多阶段内容分发行动决策的内容分发方法，通过将内容分发过程分解为多个阶段（如推荐产品、确定发送时间和频率、选择具体内容），系统能够更全面地理解不同分发行动之间的相互作用。同时，本发明采用长期价值计算方法，结合短期和长期用户反应，优化内容分发决策。这种方法不仅提高了训练数据的有效性，还使系统能够平衡多个性能参数和约束条件，从而提升用户体验并优化分发效果。

**Key Innovation (核心创新)**:  
1. 通过多阶段内容分发行动决策，将内容分发过程分解为多个阶段（如推荐产品、确定发送时间和频率、选择具体内容），以更全面地理解不同分发行动之间的相互作用。
2. 采用训练好的倾向性机器学习模型，根据用户特征数据和分发行动数据生成倾向性数据，从而为每个分发行动提供更精准的决策支持。
3. 结合长期价值计算方法，不仅考虑用户对当前内容的即时反应（如订阅服务），还考虑用户未来的反应（如订阅时长）和对后续内容的反应，以优化分发决策。
4. 使用多目标优化技术，在多个性能参数（如转化倾向和投诉倾向）之间进行权衡，以在最大化转化的同时将投诉控制在最低限度。
5. 通过对不同分发行动进行多阶段优化，系统能够处理更复杂的分发场景，例如在多个活动之间协调分发量，避免用户被过多内容淹没。
6. 本发明能够平衡多个参与方的性能参数和约束条件，例如在单个用户的时间段内限制通知数量，从而改善用户体验并减少负面反应。
7. 该技术可应用于广告、推荐系统、新闻分发等多种场景，通过优化长期价值指标，为内容创作者和用户创造更可持续的价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484351029)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220211)**
<br/><br/>

---


<br/>

### 15. 具有增强强度和刚度的散热轻质光学元件

**Title (EN)**: HEAT DISSIPATIVE AND LIGHTWEIGHT OPTICAL ELEMENTS HAVING INCREASED STRENGTH AND STIFFNESS  
**Pub. No.**: US20260217955

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Christopher Stipe](https://patents.google.com/?inventor=Christopher+Stipe&country=US&num=100&sort=new), [Andrew John Ouderkirk](https://patents.google.com/?inventor=Andrew+John+Ouderkirk&country=US&num=100&sort=new), [Eugene Cho](https://patents.google.com/?inventor=Eugene+Cho&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
一种聚合物薄膜包含分子量至少约为500,000 g/mol的聚乙烯，该薄膜具有至少约80%的可见光谱透明度、体积雾度小于约5%以及至少约10 GPa的面内弹性模量。该聚合物薄膜可具有热导性，并可被整合到光学元件中，用于散热，例如从发光装置散热。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
光学材料技术领域，具体涉及散热光学元件和聚合物薄膜材料。

**Background (发明背景)**:  
传统光学元件在散热和机械性能方面存在不足，难以同时满足高强度、轻质和高效散热的需求。
现有聚合物材料通常难以兼顾高透明度和热导性。
发光装置对光学元件的散热能力要求日益提高，但传统材料难以满足这一需求。
本发明旨在提供一种兼具高强度、高刚度、良好散热性能和光学透明度的聚合物薄膜材料。

**Summary (发明总览)**:  
本发明提出了一种新型聚合物薄膜材料，通过使用高重量分子量的聚乙烯来实现高强度、高刚度以及良好的光学透明度。
该材料通过优化分子结构和工艺参数，兼具热导性，可用于光学元件的散热。
相较于传统材料，本发明在保证光学性能的同时，显著提升了机械强度和散热能力。
该技术为光学元件的轻量化、高性能化和多功能化提供了新的解决方案。

**Key Innovation (核心创新)**:  
1. 采用分子量至少为500,000 g/mol的聚乙烯作为主要材料，通过高重量分子量提升薄膜的机械性能。
2. 通过优化聚合物薄膜的分子结构和制备工艺，实现至少80%的可见光谱透明度和低于5%的体积雾度。
3. 薄膜具有至少10 GPa的面内弹性模量，显著提升了光学元件的强度和刚度。
4. 通过材料改性或掺杂技术，赋予聚合物薄膜热导性，使其能够有效散热。
5. 该材料可被整合到光学元件中，例如用于发光装置的散热，提供了一种轻质且高效的热管理方案。
6. 相较于传统光学材料，本发明在保证光学性能的同时，显著提升了机械强度和散热能力，拓展了光学元件的应用场景。
7. 该技术可应用于高性能光学系统、LED照明设备等领域，提供更可靠、更高效的光学解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484348536)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260217955)**
<br/><br/>

---


<br/>

### 16. 生成式搜索引擎文本文档

**Title (EN)**: GENERATIVE SEARCH ENGINE TEXT DOCUMENTS  
**Pub. No.**: US20260220143

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Mohamed Salman Ismail GADIT](https://patents.google.com/?inventor=Mohamed+Salman+Ismail+GADIT&country=US&num=100&sort=new), [Shivani SRIDHAR](https://patents.google.com/?inventor=Shivani+SRIDHAR&country=US&num=100&sort=new), [Beverly Roberta SHEN](https://patents.google.com/?inventor=Beverly+Roberta+SHEN&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明描述了一种利用生成式文档系统动态构建并提供生成式文本文档的方法，该系统使用一个或多个生成式人工智能（AI）模型。例如，生成式文档系统高效利用各种系统和生成式AI模型来确定用户意图和主题，策划主题章节，并生成包含针对性答案以及精选主题章节的生成式文本文档，以响应搜索查询。在各种实现中，生成式文档系统执行额外的操作，以提高生成文本文档的效率和准确性。此外，在许多情况下，这些生成式文本文档为用户提供交互式、直观、全面且灵活的答案整理奠定了基础。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484350954_1.jpg)

**Technical Field (技术领域)**:  
人工智能；搜索引擎；自然语言处理；生成式AI模型

**Background (发明背景)**:  
近年来，硬件和软件领域取得了重大进展，特别是在互联网搜索领域。现有的系统旨在检索并呈现与用户搜索查询相关的链接和资源列表，并在常见主题上提供直接答案。然而，随着可用资源数量的持续增长，现有系统在提供有用且相关答案方面存在局限性，需要用户付出大量努力。此外，尽管最近有所改进，现有系统在处理日益增长的信息量时，仍面临提供及时准确查询响应的技术挑战。

**Summary (发明总览)**:  
本发明提出了一种基于生成式AI模型的生成式文档系统，用于构建和提供生成式文本文档。该系统通过分析用户搜索意图和主题，利用生成式AI模型生成包含针对性答案和精选主题章节的文本文档。与传统搜索引擎不同，本发明生成的文档不仅包含搜索结果的链接，还整合了AI生成的叙述性内容，从而提供更全面和直观的搜索体验。该系统通过重用生成式文档、并行调用AI模型以及优化生成流程，提高了生成效率和准确性。

**Key Innovation (核心创新)**:  
1. 利用生成式AI模型解析搜索结果链接，生成包含用户查询针对性答案的文本内容，解决了传统搜索引擎结果碎片化的问题。
2. 通过多轮AI模型调用和提示优化，生成包含主题章节和链接引用的结构化文档，提高了搜索结果的组织和可读性。
3. 采用主题章节链接获取和内容策划机制，确保生成内容与原始搜索结果高度相关，减少AI生成内容的幻觉问题。
4. 实现生成式文档的重用机制，对于重复或相似的搜索查询，系统可快速复用已有文档，提升响应效率并降低计算成本。
5. 通过并行调用搜索系统和生成式AI模型，优化文档生成流程，提高整体系统效率。
6. 提供多种输出格式和交互式答案卡片功能，使用户能够获得更丰富和更具针对性的信息。
7. 该系统可应用于智能问答平台、知识库构建和多媒体内容生成等领域，为用户提供更智能和直观的搜索体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484350954)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220143)**
<br/><br/>

---


<br/>

### 17. 电子邮件系统中的电子邮件管理引擎

**Title (EN)**: EMAIL MANAGEMENT ENGINE IN AN ELECTRONIC MAIL SYSTEM  
**Pub. No.**: US20260222372

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Mrinal Kumar SHARMA](https://patents.google.com/?inventor=Mrinal+Kumar+SHARMA&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明提供了一种使用电子邮件管理引擎实现上下文感知外出（OOO）辅助的方法、系统和计算机存储介质。上下文感知OOO辅助支持电子邮件管理操作，通过人工智能和上下文感知为用户不在场期间提供OOO功能。在操作中，首先访问电子邮件消息，确定其所属类别（如会议安排、信息请求或任务委托）。基于类别，执行与该类别相关的多个OOO操作，并根据这些操作生成对电子邮件消息的响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484353417_1.jpg)

**Technical Field (技术领域)**:  
电子邮件管理技术领域，具体涉及基于人工智能和上下文感知的智能外出辅助系统。

**Background (发明背景)**:  
随着分布式计算系统和云平台的普及，电子邮件成为个人和专业交流的主要方式。传统电子邮件系统提供的外出（OOO）功能通常采用通用回复，缺乏上下文感知能力，无法满足不同发件人的具体需求。在协作环境中，这种通用性可能导致沟通延迟和团队效率下降。此外，现有系统对自定义回复的支持有限，难以根据邮件内容或特定条件调整回复内容。

**Summary (发明总览)**:  
本发明提出了一种基于电子邮件管理引擎的智能外出辅助系统，通过人工智能和上下文感知技术提升电子邮件管理效率。该系统能够识别邮件类别（如会议安排、信息请求或任务委托），并执行相应的智能操作，如提供实时可用信息、推荐替代联系人或转发邮件至合适人员。相较于传统OOO功能，本发明实现了动态响应、资源链接访问和文档推荐等功能，为用户不在场期间提供更智能、更高效的邮件管理支持。

**Key Innovation (核心创新)**:  
1. 采用人工智能算法对电子邮件进行智能分类，能够识别如客户查询、团队协作请求、资源请求等不同类型的邮件内容。
2. 提供上下文感知的动态回复功能，根据邮件类别和具体需求生成个性化回复，例如提供相关文档链接、转发邮件至同事或推荐替代联系人。
3. 支持资源链接和文档访问功能，能够在回复中直接提供相关网页链接或文档下载路径，例如在客户请求产品手册时自动附上最新版本链接。
4. 构建了基于工作流的电子邮件管理框架，包括会议安排、信息请求和任务委托等流程，确保不同类型的邮件得到针对性处理。
5. 通过AI驱动的动态响应机制，将传统通用OOO回复升级为智能、互动式的沟通工具，提升用户不在场期间的邮件处理效率。
6. 特别适用于大型组织或协作环境，解决了传统OOO功能在处理复杂邮件场景时的不足，例如避免邮件处理延迟和团队协作中断。
7. 应用于智能电子邮件管理系统中，为用户提供更智能、更高效的外出期间邮件管理解决方案，提升整体办公效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484353417)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260222372)**
<br/><br/>

---


<br/>

### 18. 使用隐蔽滚动图案减少屏幕闪烁

**Title (EN)**: REDUCING SCREEN FLICKER USING A CONCEALED ROLLING PATTERN  
**Pub. No.**: US20260221071

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Xuming DENG](https://patents.google.com/?inventor=Xuming+DENG&country=US&num=100&sort=new), [Muhammad Daniel Sun Bin ABDULLAH](https://patents.google.com/?inventor=Muhammad+Daniel+Sun+Bin+ABDULLAH&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明提供了一种通过隐蔽滚动图案减少屏幕闪烁的方法、系统及计算机程序产品。通过在液晶模块像素上应用可隐蔽的滚动图案（例如，交替电场），使像素显示交替的黑白图案，从而增加移动离子的扩散（例如，释放累积的电荷），减少屏幕闪烁和图像烧屏现象。滚动图案可在低功耗模式（例如，待机、睡眠、关闭）下应用，此时背光关闭，且环境光线低于阈值或显示面板被遮挡（例如，关闭盖子）。当检测到从低功耗模式切换到全功率模式、滚动图案定时器到期、环境光线高于阈值或显示面板未被遮挡、电源缺失或电池电量低于阈值时，滚动图案的应用将被停止。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484351977_1.jpg)

**Technical Field (技术领域)**:  
液晶显示技术；屏幕闪烁与图像烧屏的抑制；低功耗模式下的显示管理

**Background (发明背景)**:  
液晶显示面板（如笔记本电脑或平板电脑）容易出现屏幕闪烁和图像烧屏现象，特别是在显示静态图像较长时间后。现有技术中，虽然面板自刷新功能可以节省静态显示内容的功耗，但也增加了屏幕闪烁和图像烧屏的风险。

**Summary (发明总览)**:  
本发明提出了一种通过隐蔽滚动图案减少屏幕闪烁的技术方案。在低功耗模式下，系统会关闭背光并检测环境光线或显示面板状态，然后应用滚动图案以释放液晶模块中累积的电荷，从而减少屏幕闪烁和图像烧屏现象。当检测到特定事件（如切换到全功率模式或滚动图案定时器到期）时，滚动图案的应用将被停止。本发明通过在低功耗模式下进行电荷管理，提供了更有效的屏幕闪烁和图像烧屏解决方案。

**Key Innovation (核心创新)**:  
1. 通过交替电场诱导液晶模块像素显示黑白交替图案，增加移动离子的扩散，有效释放累积的电荷。
2. 在低功耗模式下应用滚动图案，同时关闭背光并确保环境光线低于阈值或显示面板被遮挡，以避免对用户体验的影响。
3. 基于事件检测机制（如模式切换、定时器到期或电源状态变化）动态控制滚动图案的应用，确保在需要时及时停止。
4. 通过延迟背光开启并应用至少两帧黑色视频，进一步减少屏幕闪烁现象。
5. 允许在静态图像显示时使用更低的刷新率（例如低于20Hz），从而延长电池寿命并减少碳排放。
6. 提供了一种无需用户干预的自动电荷管理方案，适用于长时间显示静态图像的场景。
7. 特别适用于笔记本电脑和平板电脑等便携式设备，能够有效减少因屏幕闪烁和图像烧屏导致的返修率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484351977)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260221071)**
<br/><br/>

---


<br/>

### 19. 现有第三方基于文本的聊天机器人的语音包装器

**Title (EN)**: VOICE WRAPPER(S) FOR EXISTING THIRD-PARTY TEXT-BASED CHATBOT(S)  
**Pub. No.**: US20260222373

**Applicant**: GOOGLE LLC  
**Inventor**: [Sasha Goldshtein](https://patents.google.com/?inventor=Sasha+Goldshtein&country=US&num=100&sort=new), [Yoav Tzur](https://patents.google.com/?inventor=Yoav+Tzur&country=US&num=100&sort=new), [Shlomo Fruchter](https://patents.google.com/?inventor=Shlomo+Fruchter&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明旨在为现有的第三方基于文本的聊天机器人提供语音包装器，使其能够进行相应的语音对话。语音包装器包含多个组件，例如用于处理语音输入并代替现有第三方基于文本的聊天机器人进行响应的输入组件，以及用于减少感知延迟或修改现有第三方基于文本的聊天机器人生成的输出的输出组件。通过选择性地使用语音包装器与现有第三方基于文本的聊天机器人结合，可以节省计算资源，因为语音包装器的处理消耗的计算资源比现有第三方基于文本的聊天机器人更少。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484353418_1.jpg)

**Technical Field (技术领域)**:  
自然语言处理，语音识别，聊天机器人技术

**Background (发明背景)**:  
大型语言模型（LLM）能够执行各种自然语言处理任务，如语言生成、机器翻译和问答，但这些模型通常仅支持基于文本的对话。
现有技术中，LLM的训练数据量巨大，重新训练以支持语音对话需要大量计算资源。
此外，现有LLM的架构和训练数据难以适应语音对话的需求。
因此，需要一种高效的方法使基于文本的聊天机器人能够与用户进行语音对话。

**Summary (发明总览)**:  
本发明通过为现有第三方基于文本的聊天机器人提供语音包装器，使其能够进行语音对话。
语音包装器包含多个组件，如输入检测、自动语音识别（ASR）、自然语言理解（NLU）等，用于处理用户语音输入并生成响应。
通过这种方式，可以减少对现有聊天机器人的计算资源消耗，同时保持其核心功能。
语音包装器还能够处理用户中断、消除歧义，并优化对话的流畅性和响应速度。

**Key Innovation (核心创新)**:  
1. 引入语音包装器架构，通过多个专用组件（如输入检测、ASR、NLU等）处理语音输入并生成响应，替代直接重新训练LLM。
2. 通过输入检测组件判断用户语音是否针对现有聊天机器人，例如通过特定关键词、用户视线方向或设备交互等方式进行判断。
3. 采用硬终点和软终点技术，智能判断用户语音何时结束，并提前处理部分ASR输出以减少响应延迟。
4. 实现中断处理机制，能够区分关键中断和非关键中断，并相应地处理或忽略用户打断的语音输入。
5. 包含消歧义组件，通过上下文数据（如用户资料、位置信息等）自动消除语音输入中的歧义，无需用户额外确认。
6. 通过修改组件优化ASR输出，例如去除填充词或停用词，从而减少处理文本的长度，提高效率。
7. 该技术可应用于智能助手、客服系统等场景，为现有文本型聊天机器人提供无缝的语音交互能力，同时降低开发和维护成本。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484353418)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260222373)**
<br/><br/>

---


<br/>

### 20. 人工智能系统中的领域集成上下文响应引擎

**Title (EN)**: DOMAIN-INTEGRATED CONTEXTUAL RESPONSE ENGINE IN AN ARTIFICIAL INTELLIGENCE SYSTEM  
**Pub. No.**: US20260220141

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Atabak ASHFAQ](https://patents.google.com/?inventor=Atabak+ASHFAQ&country=US&num=100&sort=new), [Haiyuan CAO](https://patents.google.com/?inventor=Haiyuan+CAO&country=US&num=100&sort=new), [Yu Hu](https://patents.google.com/?inventor=Yu+Hu&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明描述了用于提供领域集成上下文响应管理的方法、系统及计算机存储介质，该管理利用人工智能系统中的领域集成上下文响应引擎。领域集成上下文响应管理是一种系统方法，它结合特定行业知识与上下文理解，以生成准确、相关且针对特定行业的用户查询响应。该方法进一步包括使用基于技能蒸馏和知识蒸馏的两步方法对检索增强生成（RAG）任务进行微调，即从更强大的模型（如大语言模型“LLM”）进行技能蒸馏，以及从领域特定数据中进行知识蒸馏。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484350952_1.jpg)

**Technical Field (技术领域)**:  
人工智能；自然语言处理；领域知识集成；检索增强生成（RAG）

**Background (发明背景)**:  
人工智能系统依赖对数据的理解和学习来提供高效的信息检索和响应生成。然而，现有AI系统在处理特定领域数据时存在不足，难以有效整合客户或领域特定知识，导致生成的回答不够准确或相关。此外，这些系统缺乏对领域外问题的有效处理机制，容易生成不准确或虚构的回答。

**Summary (发明总览)**:  
本发明提出了一种领域集成上下文响应管理方法，通过结合领域特定知识与上下文理解来提升AI系统的响应质量。该方法利用领域集成上下文响应资源，通过技能蒸馏和知识蒸馏对RAG任务进行微调，并生成合成数据集以训练小型模型，从而实现对领域内查询的精准处理和对领域外问题的有效拒绝。

**Key Innovation (核心创新)**:  
1. 通过领域集成上下文响应引擎，将特定行业知识与上下文理解结合，提升AI系统生成响应的准确性和相关性。
2. 采用技能蒸馏和知识蒸馏的两步方法，对RAG任务进行微调，其中技能蒸馏来自更强大的模型（如LLM），知识蒸馏来自领域特定数据。
3. 利用合成数据生成器引擎创建合成数据集，包括第一训练数据集和第二训练数据集，以训练小型领域集成上下文响应模型。
4. 通过引用和过滤操作处理查询，引用领域内问题的答案并拒绝回答领域外问题，从而提高响应的可靠性和准确性。
5. 训练过程中使用第一训练数据集处理领域内外问题，使用第二训练数据集处理问题的不同表述版本，以增强模型的泛化能力。
6. 提供基于数据资源、运营资源和接口资源的实现框架，支持AI模型的高效微调和功能实现。
7. 该技术可应用于智能客服、专业咨询等领域，通过提供精准且可追溯的领域特定回答，提升用户对AI系统的信任度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484350952)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260220141)**
<br/><br/>

---


<br/>

### 21. 通过呼叫信令会话提供主叫方身份识别反馈

**Title (EN)**: PROVIDING CALLER IDENTIFICATION FEEDBACK VIA A CALL SIGNALING SESSION  
**Pub. No.**: US20260222488

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Stanley Ohumegbulem OSAJEH](https://patents.google.com/?inventor=Stanley+Ohumegbulem+OSAJEH&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
一种数据处理系统实现了从呼叫信令会话期间接收的呼叫通知消息的路由信息组件中提取用于在受话设备上显示的第二主叫方ID；将提取的第二主叫方ID分配给主叫方身份识别参数的值，该值用于与与主叫设备相关联的第一主叫方ID进行比较，以确定是否存在不匹配；生成包括提取的第二主叫方ID和随机字符串的反馈完整性值，并将反馈完整性值分配给反馈完整性参数，通过跟踪反馈完整性值来确定呼叫路径上对主叫方身份识别参数值的变化；生成对呼叫通知消息的响应，包括主叫方身份识别参数、反馈完整性参数及其各自的参数值；并将响应转发给主叫设备。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484353545_1.jpg)

**Technical Field (技术领域)**:  
本专利属于通信技术领域，具体涉及主叫方身份识别（Caller ID）验证和反馈技术。

**Background (发明背景)**:  
通信服务提供商面临确保主叫方身份识别准确性的挑战，以防止诈骗和骚扰电话。现有的主叫方身份识别验证方法依赖于用户报告问题或使用复杂的技术手段，如光学字符识别（OCR），这些方法效率低下且难以扩展。现有技术无法高效地实时验证主叫方身份识别信息的准确性。

**Summary (发明总览)**:  
本发明提出了一种通过呼叫信令会话（如SIP会话）实现主叫方身份识别反馈的技术方案。该方案通过在呼叫信令消息中插入受话设备显示的主叫方ID，并利用预定义的参数进行跟踪和验证，从而实现对主叫方身份识别信息的自动、高效和规模化检测。该方法无需额外的硬件或软件资源，通过SIP响应将主叫方ID信息反馈给主叫方或主叫方代理，以支持自动化的主叫方身份识别问题检测。

**Key Innovation (核心创新)**:  
1. 通过在SIP呼叫信令会话中嵌入受话设备显示的主叫方ID，实现对主叫方身份识别信息的实时反馈。
2. 利用预定义的主叫方身份识别参数在呼叫通知消息中标记主叫方ID，便于后续处理和验证。
3. 生成包含主叫方ID和随机字符串的反馈完整性值，并通过跟踪该值的变化来检测主叫方身份识别信息的完整性。
4. 通过SIP响应将主叫方ID信息反馈给主叫方或主叫方代理，无需额外的传输通道。
5. 应用预定义的反馈完整性参数来跟踪反馈完整性值的变化，确保主叫方ID在传输过程中的完整性。
6. 通过预定义的主叫方ID完整性参数来跟踪主叫方ID的变化，确保主叫方ID在传输到受话方时的完整性。
7. 该技术可应用于VoIP通信场景，如SIP电话服务，提供高效的主叫方身份识别验证和防欺诈功能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484353545)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260222488)**
<br/><br/>

---


<br/>

### 22. 基于眼动和头部动作识别头戴式设备显示图形元素的技术

**Title (EN)**: TECHNIQUES FOR IDENTIFYING GRAPHICAL ELEMENTS DISPLAYED AT A HEAD-WORN DEVICE BASED ON AN EYE GESTURE AND A MOTIONAL GESTURE  
**Pub. No.**: US20260219731

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Sebastian Sztuk](https://patents.google.com/?inventor=Sebastian+Sztuk&country=US&num=100&sort=new), [Salvael Ortega Estrada](https://patents.google.com/?inventor=Salvael+Ortega+Estrada&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明提供了一种用于智能眼镜用户界面管理的方法。该方法包括基于指示用户瞳孔位置的眼动追踪信号识别用户的眼动，基于眼动评估智能眼镜中显示的应用程序的用户意图，并根据用户意图激活应用程序。同时还提供了一种适用于上述方法的智能眼镜。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484350500_1.jpg)

**Technical Field (技术领域)**:  
本专利属于增强现实智能眼镜用户界面技术领域，具体涉及基于眼动追踪的交互方式。

**Background (发明背景)**:  
在可穿戴设备领域，用户界面对佩戴舒适性、设备有效性和用户体验至关重要。现有智能眼镜的用户界面通常需要用户进行不自然的头部动作或使用手部操作，这不仅影响外观，还可能干扰用户进行其他活动。本发明旨在解决智能眼镜交互方式不够自然和便捷的问题。

**Summary (发明总览)**:  
本发明提出了一种基于眼动追踪的智能眼镜交互方案，通过识别用户的眼动来评估其对应用程序的意图并执行相应操作。该方案利用内置摄像头和眼动追踪技术捕捉用户瞳孔位置和注视方向，并通过分析眼动模式来激活应用程序或执行特定功能。与传统依赖手部或头部动作的交互方式相比，本发明提供了更自然和直观的用户体验。

**Key Innovation (核心创新)**:  
1. 采用眼动追踪技术，通过识别用户瞳孔位置和注视方向来捕捉用户意图，实现无需手部操作的交互方式。
2. 使用内置摄像头和MEMS热镜或全息光学元件组合器等硬件，精确捕捉用户的眼动数据。
3. 结合红外摄像头和图像识别算法（如机器学习、人工智能、神经网络等），提高眼动识别的准确性和响应速度。
4. 通过预选的眼动模式（如注视特定图标一定时间）来执行接听电话、挂断电话等操作。
5. 支持通过眼动与其他可穿戴设备（如腕戴设备）的电磁信号或语音命令结合，实现更复杂的交互功能。
6. 能够在智能眼镜与第二设备（如笔记本电脑）之间实现交互，通过识别用户注视的文本区域来控制光标移动。
7. 应用于增强现实场景中，为用户提供更自然、直观的交互方式，尤其适合在驾驶或户外活动等双手不便操作的情况下使用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484350500)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260219731)**
<br/><br/>

---


<br/>

### 23. 具有预耦合衍射元件的显示装置

**Title (EN)**: DISPLAY WITH PRE-INCOUPLING DIFFRACTIVE ELEMENT  
**Pub. No.**: US20260219503

**Applicant**: GOOGLE LLC  
**Inventor**: [Thomas Hoekman](https://patents.google.com/?inventor=Thomas+Hoekman&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
本发明提供了一种位于光源引擎与波导之间的衍射元件，以及用于眼镜显示器的相应耦合架构。该眼镜显示器包括用于投射显示图像相关光线的光源引擎；包含多个耦合器的波导；以及位于光源引擎与波导之间的衍射元件，用于接收光源引擎投射的光线，将其分裂成多个衍射级次的光线，并将其中一个衍射级次的光线引导至多个耦合器中的一个。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484350253_1.jpg)

**Technical Field (技术领域)**:  
光学显示技术领域，具体涉及眼镜显示器中的光耦合与衍射技术。

**Background (发明背景)**:  
光学组合器用于将环境光与图像源发出的光结合，广泛应用于眼镜显示器中以实现增强现实或混合现实效果。传统眼镜显示器通过波导中的输入耦合器将光线耦合到波导内，并通过输出耦合器将光线引导至用户。然而，现有技术中，单一耦合器会导致光线随距离衰减，造成显示不均匀的问题。尽管通过调制输出耦合器和出瞳扩展器的光栅特征可以改善空间均匀性，但受限于光栅尺寸，其改进效果有限。

**Summary (发明总览)**:  
本发明通过在光源引擎与波导之间插入一个衍射元件，将光源投射的光分裂成多个衍射级次，并分别引导至多个耦合器，从而提高光线耦合的空间均匀性。该方法利用多个耦合器同时接收不同衍射级次的光线，并通过波导中的出瞳扩展器进行扩展，最终实现更均匀的光输出。这种设计减轻了传统技术中仅依赖单一耦合器或出瞳扩展器来提高均匀性的负担。

**Key Innovation (核心创新)**:  
1. 在光源引擎与波导之间引入衍射元件，将入射光分裂成多个衍射级次的光线，以实现光的预扩展。
2. 使用多个耦合器分别接收不同衍射级次的光线，并通过设计耦合器的光栅特征（如高度、填充因子、间距等）来确保每个耦合器的衍射效率和耦合角度一致。
3. 通过波导内的出瞳扩展器对多个耦合器接收的光线进行进一步扩展，以实现更均匀的光输出。
4. 将衍射元件放置在铰链或铰链与光源引擎之间，以适应眼镜显示器的结构设计，同时优化光路布局。
5. 通过对称或不对称地排列多个耦合器，进一步优化光线在波导内的传播路径，提高整体空间均匀性。
6. 该设计有效解决了传统眼镜显示器中因单一耦合器导致的亮度衰减问题，显著提升了显示均匀性。
7. 该技术可应用于增强现实（AR）和混合现实（MR）眼镜显示器，为用户提供更清晰、更均匀的虚拟图像显示效果。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484350253)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260219503)**
<br/><br/>

---


<br/>

### 24. 使用动态语言模型的语音识别

**Title (EN)**: Speech Recognition With Selective Use Of Dynamic Language Models  
**Pub. No.**: US20260221141

**Applicant**: Google LLC  
**Inventor**: [Petar Aleksic](https://patents.google.com/?inventor=Petar+Aleksic&country=US&num=100&sort=new), [Pedro J. Moreno Mengibar](https://patents.google.com/?inventor=Pedro+J.+Moreno+Mengibar&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
一种用于转录语音的计算机实现方法包括：接收表征用户语音的语音数据；使用静态类语言模型生成第一组候选转录结果，该模型包含多个独立于语音或用户预先填充的类；然后确定第一组候选转录结果是否包含类术语。基于是否包含类术语，计算系统决定是否生成动态类语言模型，该模型包含至少一个基于与语音或用户相关的上下文选择的类术语填充的类。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484352054_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术领域，具体涉及使用类语言模型将语音转录为文本。

**Background (发明背景)**:  
语音识别已成为与计算设备交互的常用方式，比传统输入方式更便捷高效。然而，现有技术中，语言模型在处理特定上下文或用户个性化内容时存在不足，导致转录准确性受限。此外，动态生成复杂模型可能增加计算成本和延迟，影响用户体验。本发明旨在解决这些问题，通过选择性使用动态类语言模型提高转录效率和准确性。

**Summary (发明总览)**:  
本发明提出了一种语音识别方法，首先使用预生成的静态类语言模型对语音进行初步解码，以确定是否需要进一步使用动态模型进行细化处理。如果初步解码结果指示语音可能包含类术语，系统将动态生成包含与用户或语音上下文相关的类术语的模型，从而提高转录准确性。这种方法通过延迟生成动态模型，减少了不必要的计算开销和延迟，同时在需要时提供更精准的转录结果。

**Key Innovation (核心创新)**:  
1. 采用静态类语言模型进行初步解码，以快速判断语音是否包含类术语，从而决定是否需要生成动态模型。
2. 基于初步解码结果，动态生成包含与用户或语音上下文相关的类术语的动态类语言模型，以提高转录准确性。
3. 通过选择性生成动态模型，仅在必要时创建用户特定或语音特定的模型，减少了计算开销和延迟。
4. 使用标签搜索技术识别候选转录结果中的类术语，确保动态模型生成的针对性。
5. 静态类语言模型包含预定义的类，如联系人、地点、日期等，这些类独立于用户或语音预先填充。
6. 在生成动态模型时，仅选择与当前语音或用户上下文相关的类进行填充，进一步优化模型效率。
7. 本发明可应用于智能助手、语音转文本服务等场景，在处理包含类术语的语音时提供更快速和准确的转录结果。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484352054)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260221141)**
<br/><br/>

---


<br/>

### 25. 自定心插头

**Title (EN)**: SELF-CENTERING PLUG  
**Pub. No.**: US20260218814

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Errol Mark TAZBAZ](https://patents.google.com/?inventor=Errol+Mark+TAZBAZ&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
一种用于传输流体的自定心插头，包括一个具有从外表面延伸的环形表面的细长主体。位于环形表面与壳体的环形壁之间的垫圈，壳体包围细长主体的一部分。浮动簧环绕细长主体，包括与细长主体的环形肩部接触的远端弹簧端和在壳体内固定的近端弹簧端，其中浮动簧将细长主体的环形表面压向垫圈。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484349491_1.jpg)

**Technical Field (技术领域)**:  
流体传输技术领域，具体涉及用于流体连接的自定心插头。

**Background (发明背景)**:  
在连接流体供应管线时，插头与插座的不当配合会干扰流体传输。现有的自定心机制通常通过轴向移动来抵消重力，但会导致下游软管或其他组件的屈曲问题。此外，这些机制将径向和角度调节耦合在一起，限制了调节能力，并需要更大的包装空间。

**Summary (发明总览)**:  
本发明提出了一种自定心插头，通过独立调节径向和角度偏差，实现与插座的对中。该插头利用浮动簧和环形表面的配合，在不改变长度的情况下实现自定心，避免对下游软管施加压缩负载。同时，本发明允许不同尺寸的耦合件在相同的外壳尺寸内互换，简化了流体连接尺寸的更换过程。

**Key Innovation (核心创新)**:  
1. 采用独立调节径向和角度偏差的设计，实现最大角度和径向调节能力，解决了现有技术中调节能力受限的问题。
2. 利用浮动簧和环形表面的配合，在不改变插头长度的情况下实现自定心，避免对下游软管或其他组件施加压缩负载。
3. 设计了一种可互换的耦合尺寸系列，使得不同尺寸的插头和插座可以在相同的外壳尺寸内工作，简化了流体连接尺寸的更换过程。
4. 通过将径向和角度调节解耦，避免了现有技术中因一个调节维度增加而限制另一个维度的问题。
5. 减少了所需的包装空间，使得在有限空间内实现更大尺寸的流体连接成为可能。
6. 该设计适用于数据中心硬件冷却系统等流体传输应用场景，能够提高连接的可靠性和操作的便捷性。
7. 通过简化更换过程和减少对下游组件的影响，降低了维护成本和复杂性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484349491)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260218814)**
<br/><br/>

---


<br/>

### 26. 血氧饱和度测量

**Title (EN)**: OXYGEN SATURATION MEASUREMENTS  
**Pub. No.**: US20260215706

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Aashna Hemkumar](https://patents.google.com/?inventor=Aashna+Hemkumar&country=US&num=100&sort=new), [Xiyu Duan](https://patents.google.com/?inventor=Xiyu+Duan&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
一种可穿戴设备包括光源、光传感器和处理逻辑。光源用于发射照明光。光传感器用于生成返回光的测量值。处理逻辑用于利用光传感器生成光测量值以产生血氧饱和度测量值。当光测量值低于光阈值时，处理逻辑还会增加后续光测量的采样率并减少后续光测量的模拟偏移。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484349549_1.jpg)

**Technical Field (技术领域)**:  
可穿戴设备技术领域，具体涉及血氧饱和度监测。

**Background (发明背景)**:  
可穿戴设备如智能手表和健身追踪器通常配备用于测量血氧饱和度的传感器。一些设备使用光电容积描记图（PPG）技术，通过发射光并检测血流变化来监测心率和血氧水平。然而，当用户肤色较深或组织灌注较低时，PPG信号会衰减，导致测量性能下降。现有的解决方案通过增加光源驱动电流来补偿，但这会导致功耗增加和LED波长偏移，从而影响测量精度。

**Summary (发明总览)**:  
本发明提出了一种改进血氧饱和度测量精度的方法。当检测到光测量值低于阈值时，系统会提高后续测量的采样率并减少模拟偏移，而不是简单地增加光源亮度。这种方法避免了光源波长的漂移，同时保持了信噪比（SNR），从而在不影响电池寿命的情况下提高了测量精度。

**Key Innovation (核心创新)**:  
1. 通过检测光测量值是否低于阈值来识别低灌注或深肤色用户的情况。
2. 在检测到低光测量值时，增加后续光测量的采样率，以提高信号采集的精度。
3. 减少后续光测量的模拟偏移，以优化动态范围并避免不必要的功耗。
4. 通过调整采样率和模拟偏移而非增加光源电流，避免了LED波长漂移带来的测量误差。
5. 在不同肤色用户中保持相同的LED电流使用，确保测量的一致性和准确性。
6. 该技术适用于智能手表、健身追踪器等可穿戴设备，能够在不影响电池寿命的情况下提供更准确的血氧饱和度测量。
7. 特别适用于需要长时间监测血氧水平的应用场景，如运动监测、睡眠分析和健康追踪。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484349549)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260215706)**
<br/><br/>

---


<br/>

### 27. 通过多因素信号进行安全配件认证

**Title (EN)**: SECURE ACCESSORY AUTHENTICATION VIA MULTIFACTOR SIGNALS  
**Pub. No.**: US20260222213

**Applicant**: Google LLC  
**Inventor**: [Nicholas Sanders](https://patents.google.com/?inventor=Nicholas+Sanders&country=US&num=100&sort=new), [Andrew Felch](https://patents.google.com/?inventor=Andrew+Felch&country=US&num=100&sort=new)  
**Publication Date**: 30.07.2026

**Abstract**:  
一种对接系统可包括一个存储对接标识符的底座，以及一个与该底座对接的电子设备。电子设备可接收对接标识符，获取无线网络信息，并基于对接标识符和其他信息（如无线网络信息）创建哈希值。通过使用存储的哈希值分析该哈希值以识别匹配项。在匹配的情况下，系统可在电子设备保持对接时允许访问受限功能。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484353242_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及电子设备对接与认证技术，具体为通过多因素信号进行安全认证以控制设备功能访问。

**Background (发明背景)**:  
电子设备对接底座在家庭和办公室中广泛使用，用户常希望设备对接时能便捷访问某些功能。然而，这些功能通常受限，需要用户解锁设备才能使用。这种方式存在安全隐患，且用户体验不佳。本发明旨在提供一种安全且便捷的机制，在设备对接时允许访问受限功能，同时防止未经授权的访问。

**Summary (发明总览)**:  
本发明提出了一种基于多因素信号的安全对接认证系统。电子设备通过接收底座的固定标识符并结合无线网络信息生成哈希值，与存储的哈希值进行比对以验证对接环境的安全性。验证通过后，系统允许设备在对接状态下访问受限功能，如智能家居控制或个性化信息展示。该方法通过固定标识符和本地网络信息的结合，提高了认证的准确性和安全性。

**Key Innovation (核心创新)**:  
1. 使用固定底座标识符进行身份识别，该标识符在底座生命周期内保持不变，简化了认证流程并提高了兼容性。
2. 结合无线网络信息（如SSID和密码）生成哈希值，防止底座被移动到其他位置后意外泄露受限功能。
3. 通过远程服务器系统存储和管理哈希值，确保哈希值的安全性和可追溯性，同时避免在服务器上暴露底座标识符。
4. 支持设备与多个底座进行配对，并针对不同底座提供不同的受限功能访问权限，例如家庭和办公室场景下的差异化功能。
5. 在设备对接时，通过用户授权机制进一步增强安全性，确保只有授权用户才能访问受限功能。
6. 利用盐值（salt value）增强哈希值的随机性和安全性，防止潜在的攻击和破解。
7. 本发明可应用于智能家居设备控制、个人信息展示等场景，为用户提供安全便捷的设备对接体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484353242)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260222213)**
<br/><br/>

---


<br/>

### 28. 用于重型机械和设备中创建走道的系统和方法

**Title (EN)**: Systems and methods for creating walkways in heavy machinery and equipment  
**Pub. No.**: US12692074

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Ganesh Krishnamoorthy](https://patents.google.com/?inventor=Ganesh+Krishnamoorthy&country=US&num=100&sort=new), [Michael Alan Bray](https://patents.google.com/?inventor=Michael+Alan+Bray&country=US&num=100&sort=new), [Vivek S. Narayanan](https://patents.google.com/?inventor=Vivek+S.+Narayanan&country=US&num=100&sort=new)  
**Publication Date**: 28.07.2026

**Abstract**:  
本发明公开了用于重型机械和设备中创建走道的系统、方法和装置。在一个实施例中，示例系统包括第一模块、与第一模块耦合的第二模块，其中第二模块包括第一轨道和第二轨道，与第一模块和第二模块耦合的第三模块，其中第三模块具有用于支撑沿系统下部布置的第一组容器和沿系统上部布置的第二组容器的容器矩阵，以及用于将第一组容器从第一位置驱动到第二位置的第一驱动系统，其中第一组容器在第二位置与第一轨道垂直对齐。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484245857_1.jpg)

**Technical Field (技术领域)**:  
重型机械和设备领域，具体涉及物流仓储设备中的容器搬运和走道构建技术。

**Background (发明背景)**:  
随着在线购物的普及，物流中心每天需要处理大量包裹，这对物流效率提出了更高要求。现有的物流设备在处理物品、包装和容器时可能存在效率低下和操作复杂的问题。此外，物流操作中的手动处理可能导致工人受伤风险增加。因此，需要改进物流中心的操作技术，例如拣选、分类和包装技术，以减少人工操作并提高效率。

**Summary (发明总览)**:  
本发明提出了一种用于重型机械和设备中创建走道的创新系统。该系统通过模块化设计，将容器矩阵与轨道系统结合，利用驱动系统实现容器的垂直移动，从而构建动态走道。这种设计能够提高物流中心的操作效率，减少人工操作，并降低工人受伤风险。相较于传统物流设备，本发明通过自动化和模块化设计实现了更灵活、高效的物流操作。

**Key Innovation (核心创新)**:  
1. 采用模块化设计，将第一模块、第二模块和第三模块组合，实现系统的高度灵活性和可扩展性。
2. 引入容器矩阵，支持上下两部分的容器布置，并通过第一驱动系统实现容器的垂直移动。
3. 设计了第一轨道和第二轨道，使容器在滑动过程中能够与轨道垂直对齐，确保移动的稳定性和精确性。
4. 通过自动化滑动系统，减少人工操作，提高物流操作效率，并降低工人受伤风险。
5. 实现了容器在垂直方向上的动态调整，适应不同高度的操作需求，提升了物流设备的适应性。
6. 该系统特别适用于大型物流中心，能够处理大量包裹和容器，优化仓储空间利用。
7. 通过创新的走道构建方式，本发明为物流操作提供了更安全、更高效的工作环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484245857)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12692074)**
<br/><br/>

---


<br/>

### 29. 便携式电机测试设备及使用多种速度斜坡确定电机健康状况的相关方法

**Title (EN)**: Portable motor testing device and associated methods of determining motor health using a plurality of speed ramps  
**Pub. No.**: US12693334

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Ethan Paige](https://patents.google.com/?inventor=Ethan+Paige&country=US&num=100&sort=new), [Wonjae Jang](https://patents.google.com/?inventor=Wonjae+Jang&country=US&num=100&sort=new), [Awadhesh Kumar Thakur](https://patents.google.com/?inventor=Awadhesh+Kumar+Thakur&country=US&num=100&sort=new)  
**Publication Date**: 28.07.2026

**Abstract**:  
便携式手持电机测试设备可用于测试和诊断安装在各种机械或设备中的电机所经历的故障。这些手持设备可包括电源、用户界面、微控制器、电机驱动板以及可更换或可互换的电缆。此外，这些手持设备可配置为连接并安全可靠地测试各种不同类型的电机，包括具有通常未知结构、内部或操作特性的封闭式电机，使用各种组合或序列的电机测试算法。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484247247_1.jpg)

**Technical Field (技术领域)**:  
电机测试技术领域，具体涉及便携式电机故障诊断设备。

**Background (发明背景)**:  
各类机械设备和系统广泛使用各种类型的电机。当这些设备出现故障时，通常需要停机、拆卸电机并进行测试诊断。传统的测试系统通常体积庞大、固定且专用，导致显著的停机时间和成本。因此，需要便携、高效且可靠的测试设备来准确测试和诊断电机故障，同时减少传统固定专用测试系统带来的停机时间、成本和人力。

**Summary (发明总览)**:  
本发明提出了一种便携式电机测试设备，通过集成电源、用户界面、微控制器和可更换电缆等组件，实现对不同类型电机的现场测试。该设备采用多种速度斜坡测试算法，能够在不拆卸电机的情况下诊断故障。其核心改进在于便携性和多功能性，能够适应未知结构的封闭式电机，并提供可靠的测试结果，从而减少停机时间和维护成本。

**Key Innovation (核心创新)**:  
1. 采用便携式手持设计，集成电源、用户界面和微控制器，实现现场快速测试。
2. 使用可更换或可互换电缆，适应不同类型电机的连接需求。
3. 集成多种速度斜坡测试算法，能够在不拆卸电机的情况下进行故障诊断。
4. 具备对封闭式电机的测试能力，即使在电机内部结构未知的情况下也能提供可靠结果。
5. 通过优化测试算法和硬件设计，实现高精度和高可靠性的电机健康评估。
6. 设备支持多种测试组合和序列，能够根据不同电机类型和故障模式进行灵活配置。
7. 应用于工业自动化和设备维护场景，能够显著减少停机时间，降低维护成本。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484247247)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12693334)**
<br/><br/>

---


<br/>

### 30. 模块化存储系统

**Title (EN)**: Modular storage systems  
**Pub. No.**: US12693150

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Matthew Ray DesJardien](https://patents.google.com/?inventor=Matthew+Ray+DesJardien&country=US&num=100&sort=new), [Chelsea Olson](https://patents.google.com/?inventor=Chelsea+Olson&country=US&num=100&sort=new), [Robert M. Riggs](https://patents.google.com/?inventor=Robert+M.+Riggs&country=US&num=100&sort=new)  
**Publication Date**: 28.07.2026

**Abstract**:  
模块化存储系统包括安装在平台下方或与平台相关联的负载传感器。负载传感器以时间间隔对负载信号进行脉冲采样，而不是连续采样，以节省电力。通过脉冲采样信号确定的负载变化来识别与交易相关的物品。平台可以水平或非水平角度对齐，且在平台的前缘安装了带有光伏电池组的光伏电源。当用户伸手越过光伏电池以获取平台上的物品时，该光伏电池产生的电力或电压水平会降低。识别出与电力或电压降低的光伏电池最接近的物品。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484247043_1.jpg)

**Technical Field (技术领域)**:  
仓储与零售技术领域，涉及智能存储系统、传感器技术和光伏供电系统。

**Background (发明背景)**:  
传统仓储和零售设施通常使用货架来存储或展示物品，但现有系统依赖持续运行的计算机系统进行库存监控和交易跟踪，这些系统需要硬接线连接电源和网络，耗电量大且难以在现有设施中改造。此外，现有系统难以在不破坏货架结构的情况下实现灵活安装。

**Summary (发明总览)**:  
本发明提出了一种基于脉冲采样负载传感器和光伏供电的模块化存储系统。通过间歇性采样负载变化来识别物品位置，并利用用户操作对光伏电池的影响来辅助定位。该系统无需硬接线，可灵活部署在现有货架上，同时降低能耗。相较于传统持续运行的计算机系统，本发明在节能和灵活性方面有显著改进。

**Key Innovation (核心创新)**:  
1. 采用脉冲采样技术对负载传感器进行间歇性信号采集，以减少电力消耗，同时准确识别负载变化。
2. 在平台前缘安装光伏电池，利用用户操作对光伏电池的遮挡或影响来辅助定位物品位置。
3. 系统支持平台以水平或非水平角度对齐，适应不同仓储场景的需求。
4. 通过负载变化和光伏电池电压变化的双重检测机制，提高物品定位的准确性和可靠性。
5. 无需硬接线连接电源和网络，模块化设计便于在现有货架上灵活安装和改造。
6. 降低持续运行计算机系统的电力需求，适用于电力供应有限或难以布线的环境。
7. 可应用于智能仓储和零售场景，提供低功耗、高灵活性的物品监控和定位解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484247043)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12693150)**
<br/><br/>

---


<br/>

### 31. 自主移动设备碰撞特征化系统

**Title (EN)**: System to characterize collision of an autonomous mobile device  
**Pub. No.**: US12693681

**Applicant**: AMAZON TECHNOLOGIES, INC.  
**Inventor**: [Shreekant Gayaka](https://patents.google.com/?inventor=Shreekant+Gayaka&country=US&num=100&sort=new), [Chang Young Kim](https://patents.google.com/?inventor=Chang+Young+Kim&country=US&num=100&sort=new), [Xin Yang](https://patents.google.com/?inventor=Xin+Yang&country=US&num=100&sort=new)  
**Publication Date**: 28.07.2026

**Abstract**:  
自主移动设备（AMD）在物理空间中移动。该设备可能会遇到物理空间中的特征，例如地板过渡或可能阻碍运动的障碍物。通过超声波传感器、光学飞行时间传感器、惯性测量单元（IMU）、轮速传感器和电机扭矩传感器等传感器获取传感器数据。基于传感器数据，确定障碍物的位置，并判断该障碍物是否可穿越。如果可穿越，AMD可以继续越过障碍物移动。如果不可穿越，障碍物的位置可能会被添加到用于路线规划的地图中。基于不可穿越障碍物的位置，AMD可以移动到远离障碍物的恢复位置，并恢复移动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484247624_1.jpg)

**Technical Field (技术领域)**:  
自主移动机器人技术领域，具体涉及障碍物检测与碰撞特征化技术。

**Background (发明背景)**:  
自主移动设备在复杂环境中移动时，经常会遇到各种障碍物和地形变化。
现有技术通常依赖于预设地图或简单的传感器反馈，难以有效应对动态障碍物。
这可能导致设备无法准确识别障碍物的可穿越性，影响移动效率和安全性。
本发明旨在解决自主移动设备在动态环境中准确识别障碍物并规划路径的问题。

**Summary (发明总览)**:  
本发明提出了一种自主移动设备碰撞特征化系统，通过多种传感器收集环境数据，实时判断障碍物的可穿越性。
系统能够区分可穿越和不可穿越障碍物，并相应地更新路径规划地图。
当遇到不可穿越障碍物时，设备会移动到预设的恢复位置，然后继续执行任务。
相较于传统方法，本发明提高了设备在复杂环境中的适应性和移动效率。

**Key Innovation (核心创新)**:  
1. 采用超声波传感器、光学飞行时间传感器等多种传感器组合，实现对障碍物的高精度检测和定位。
2. 通过IMU和轮速传感器数据融合，实时判断设备与障碍物的相对运动状态，提高检测可靠性。
3. 基于传感器数据建立可穿越性判断模型，区分可穿越和不可穿越障碍物，并动态更新路径规划地图。
4. 设计了专门的恢复位置机制，当检测到不可穿越障碍物时，设备可自动移动到安全位置并重新规划路径。
5. 通过电机扭矩传感器监测运动状态，进一步优化障碍物检测的准确性和响应速度。
6. 该系统可应用于室内外自主移动机器人，如扫地机器人、物流配送车等，提升其在复杂环境中的导航能力。
7. 独特价值在于增强设备对动态障碍物的适应能力，减少碰撞风险，提高任务执行效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484247624)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12693681)**
<br/><br/>

---


<br/>

### 32. 多插座计算系统的统一散热器

**Title (EN)**: Unitary heatsink for multi-socket computing systems  
**Pub. No.**: US12696426

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [William Mark Megarity](https://patents.google.com/?inventor=William+Mark+Megarity&country=US&num=100&sort=new), [Chetan Sanjay Agarwal](https://patents.google.com/?inventor=Chetan+Sanjay+Agarwal&country=US&num=100&sort=new), [Ali Elashri](https://patents.google.com/?inventor=Ali+Elashri&country=US&num=100&sort=new)  
**Publication Date**: 28.07.2026

**Abstract**:  
一种计算组件系统装置可以包括散热器。第一导热装置可以从散热器向外延伸，以促进从第一插座区域接收热量，第二导热装置可以从散热器向外延伸，以促进从第二插座区域接收热量。例如，第一插座区域和第二插座区域可以各自包括一个处理器或其他产热组件，该组件与一个板耦合，该板又与导热装置耦合，以实现向散热器的热传递，从而使散热器从两个插座区域散发热量。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484250650_1.jpg)

**Technical Field (技术领域)**:  
计算系统散热技术；多插座处理器散热；统一散热解决方案

**Background (发明背景)**:  
计算系统的性能受多种因素影响，其中热管理是一个关键问题。
随着处理器和其他组件的功率增加，散热需求也在上升。
传统散热器设计通常针对单一处理器或插座区域，难以满足多插座系统的需求。
现有技术可能无法有效平衡散热效率与空间利用。
本发明旨在提供一种适用于多插座计算系统的统一散热解决方案。

**Summary (发明总览)**:  
本发明提出了一种统一散热器设计，用于多插座计算系统。
该设计通过扩展多个导热装置，从单一散热器向多个插座区域传递热量。
每个导热装置与处理器或其他产热组件的散热板耦合，实现高效热传导。
这种设计在保持散热效率的同时，简化了系统结构并节省了空间。
相较于传统多散热器方案，本发明提供了更紧凑和经济的解决方案。

**Key Innovation (核心创新)**:  
1. 采用单一散热器设计，通过多个导热装置同时为多个插座区域散热，简化了系统结构。
2. 导热装置与处理器散热板直接耦合，确保高效热传导，减少热阻。
3. 统一散热器设计减少了多散热器所需的额外空间和材料成本。
4. 通过优化导热装置的布局和形状，实现对多插座区域的热量均匀分布。
5. 该设计适用于多处理器服务器或高性能计算系统，解决了传统散热方案在空间和效率上的不足。
6. 统一散热器可以降低系统总重量和复杂性，提高维护便利性。
7. 该方案特别适用于大规模数据中心和云计算平台，提供更可靠的热管理解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484250650)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12696426)**
<br/><br/>

---


<br/>

### 33. 减少回差效应的云台装置

**Title (EN)**: Pan-tilt device that reduces backlash effects  
**Pub. No.**: US12692937

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Chia-Wei Chan](https://patents.google.com/?inventor=Chia-Wei+Chan&country=US&num=100&sort=new), [Chia-Wei Chen](https://patents.google.com/?inventor=Chia-Wei+Chen&country=US&num=100&sort=new), [Matthew J. England](https://patents.google.com/?inventor=Matthew+J.+England&country=US&num=100&sort=new)  
**Publication Date**: 28.07.2026

**Abstract**:  
一种装置包括一个具有一个或多个齿轮的电机，以及与这些齿轮可操作连接的轴。该轴用于调整摄像头的视野。装置还包括一个支架，该支架具有一个通道，轴至少部分地设置在该通道中，以及一个槽道。一个弹簧至少部分地位于支架的槽道内，并被配置用于减少电机中一个或多个齿轮的回差。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US484246809_1.jpg)

**Technical Field (技术领域)**:  
安防监控技术领域，具体涉及云台装置的机械结构设计。

**Background (发明背景)**:  
许多家庭和企业对安全监控有需求，通常使用视频和/或音频设备进行监控。然而，传统的监控设备视野有限，使用支架虽然可以增加视野，但这些支架往往难以控制且运动不平滑。

**Summary (发明总览)**:  
本发明旨在提供一种云台装置，通过在电机齿轮系统中引入弹簧结构来减少回差效应，从而实现更精确和平稳的视野调整。该装置通过在支架中设置弹簧，利用弹簧的弹性力来补偿齿轮间隙，从而提升设备控制精度和运动平稳性。相较于传统云台，本发明在视野调整的精确性和运动平稳性方面有显著改进。

**Key Innovation (核心创新)**:  
1. 在电机齿轮系统中引入弹簧结构，通过弹簧的弹性力补偿齿轮间隙，从而减少回差效应。
2. 设计了带有槽道的支架，弹簧至少部分地设置在槽道内，确保弹簧的稳定性和有效作用。
3. 通过减少齿轮回差，实现云台装置在视野调整时的精确控制，避免传统装置的抖动和不稳定问题。
4. 优化了云台装置的机械结构，使得设备在调整视野时更加平滑，提升用户体验。
5. 该设计适用于安防监控摄像头等需要精确视野调整的场景，能够提供更可靠的监控效果。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US484246809)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12692937)**
<br/><br/>

---



**Total Patents**: 33  
**Last Updated**: 20260801

---

The Patent Scoop Trio
