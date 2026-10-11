---
layout: post
title: "其他专利小快报 2026-10-11"
date: 2026-10-11 17:26:19 +0800
categories: 其他
---

**New Patents**: 32  

---


<br/>

### 1. 用于指定请求生成视觉内容首选表示的可视化编辑器

**Title (EN)**: VISUAL EDITOR FOR SPECIFYING PREFERRED REPRESENTATION OF REQUESTED GENERATIVE VISUAL CONTENT  
**Pub. No.**: US20260311404

**Applicant**: GOOGLE LLC  
**Inventor**: [Raviteja Govindaraju](https://patents.google.com/?inventor=Raviteja+Govindaraju&country=US&num=100&sort=new), [Ramprasad Sedouram](https://patents.google.com/?inventor=Ramprasad+Sedouram&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及一种生成式应用，该应用在接收到生成视觉内容的请求时提供视觉内容编辑器。该编辑器可提供用户请求的生成视觉内容的中间表示，允许用户调整该中间表示。这些调整可以包括对中间表示进行注释、调整方向、缩放、视角或其他特征。随后，这些对中间表示的修改将与用户的初始请求一起处理，以最终生成所请求的生成视觉内容。生成视觉内容可以包括生成图像内容等。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138075_1.jpg)

**Technical Field (技术领域)**:  
生成式人工智能技术领域，具体涉及生成视觉内容的用户交互式编辑和优化。

**Background (发明背景)**:  
在人与计算机的交互中，用户常通过自然语言向自动化助手请求生成视觉内容，如图像或视频。然而，现有技术中生成的内容可能无法完全满足用户需求，导致用户需要重复提交请求。这不仅浪费计算资源，还增加了服务器负担。本发明旨在通过提供一种用户可编辑的中间表示来减少资源浪费并提高生成内容的准确性。

**Summary (发明总览)**:  
本发明提出了一种生成式应用，通过提供生成视觉内容的中间表示，允许用户通过可视化编辑器进行调整。用户可以修改方向、缩放、视角等特征，从而优化生成结果。中间表示是生成内容的简化版本，占用较少的计算资源。用户完成编辑后，系统将修改后的中间表示与初始请求一起处理，以生成最终内容。这种方法减少了重复请求，提高了生成效率，并允许用户更直观地提供视觉细节。

**Key Innovation (核心创新)**:  
1. 提供生成视觉内容的中间表示，用户可通过可视化编辑器进行交互式调整，例如调整方向、缩放、视角等特征。
2. 中间表示是生成内容的简化版本，占用较少的内存和处理资源，从而减少延迟并提高编辑效率。
3. 用户通过图形用户界面（GUI）选择元素来修改中间表示，例如调整缩放级别、修改时间强度、地理定位或运动速度。
4. 本地计算设备使用轻量级机器学习模型生成中间表示和交互式GUI元素，减少对远程服务器的依赖并提高响应速度。
5. 用户完成编辑后，修改后的中间表示和初始请求一起发送到远程设备进行详细生成，从而减少重复请求并提高生成准确性。
6. 本发明结合了多种机器学习模型，包括基于Transformer、扩散模型和生成对抗网络（GAN）的模型，以实现多模态输入和输出处理。
7. 该技术可应用于生成图像、视频等视觉内容场景，通过减少资源浪费和提升用户交互体验，为生成式应用提供更高效和直观的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138075)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311404)**
<br/><br/>

---


<br/>

### 2. 多通道语音隐私处理系统和方法

**Title (EN)**: SYSTEM AND METHOD FOR MULTI-CHANNEL SPEECH PRIVACY PROCESSING  
**Pub. No.**: US20260311677

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Dushyant SHARMA](https://patents.google.com/?inventor=Dushyant+SHARMA&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种方法、计算机程序产品和计算系统，用于从单个麦克风接收语音信号。识别语音信号中的敏感语音成分，并在识别出敏感语音成分后，通过从语音信号中移除敏感语音成分来生成过滤后的语音信号。同时生成语音信号的语音风格转换。对过滤后的语音信号和语音信号的语音风格转换进行语音处理。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138376_1.jpg)

**Technical Field (技术领域)**:  
语音处理技术领域，具体涉及语音隐私保护和多通道语音处理技术。

**Background (发明背景)**:  
语音处理系统中用户的声音被视为个人可识别信息（PII）。现有技术通过语音风格转换（VST）或语音转换（VC）算法将声音转换为授权演员的声音，以保护隐私。然而，这种方法可能导致后续的自动语音识别（ASR）等语音处理系统性能下降，因为转换过程通常无法很好地模拟背景声学特性。

**Summary (发明总览)**:  
本发明提出了一种多通道语音隐私处理方法，通过单麦克风接收语音信号并识别其中的敏感成分，然后生成过滤后的语音信号和语音风格转换版本。系统利用多通道架构同时处理原始信号和去标识化信号，以在保护隐私的同时保持语音处理系统的性能。本发明通过使用注册训练语音作为转换目标，提供了更可靠的去标识化效果，并允许在训练和测试过程中灵活混合使用去标识化和原始数据。

**Key Innovation (核心创新)**:  
1. 采用多通道架构，通过单麦克风接收的语音信号同时生成过滤后的语音信号和语音风格转换版本，实现隐私保护与语音处理性能的平衡。
2. 使用注册训练语音作为语音转换的目标声音，确保转换后的声音具有更好的可识别性和一致性，避免了传统方法中声音不可控的问题。
3. 在训练和测试过程中灵活混合使用去标识化和原始数据，允许在保护隐私的同时充分利用现有数据资源，提升语音处理系统的训练效果。
4. 通过单目标或多目标语音转换策略，提供更灵活的隐私保护方案，适应不同场景下的隐私需求。
5. 结合文本到语音（TTS）系统，进一步增强去标识化效果，提供更多样化的声音转换选择。
6. 提出的方法在保护用户隐私的同时，最大限度地减少对自动语音识别（ASR）等下游语音处理系统性能的影响，例如降低词错误率（WER）。
7. 本专利可应用于智能语音助手、呼叫中心语音处理等场景，为隐私保护提供创新解决方案，同时保持高质量的语音处理性能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138376)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311677)**
<br/><br/>

---


<br/>

### 3. 基于情感的对话热点检测

**Title (EN)**: SENTIMENT-BASED CONVERSATION HOTSPOT DETECTION  
**Pub. No.**: US20260311692

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Gizem Tabak](https://patents.google.com/?inventor=Gizem+Tabak&country=US&num=100&sort=new), [Masahito Togami](https://patents.google.com/?inventor=Masahito+Togami&country=US&num=100&sort=new), [Michael Mark Goodwin](https://patents.google.com/?inventor=Michael+Mark+Goodwin&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本系统包括机器学习模型，能够接收代表对话会话语音的音频信息，将其分割成多个音频片段。使用基于音调的情感分析模型评估第一个音频片段以生成情感概率，并确定第一个正面情感概率是否超过阈值。然后生成第一个音频片段的文本表示，并使用主题识别模型评估该文本表示以生成指示主题的主题结果。系统进一步评估第二个音频片段以生成第二组情感概率，并确定第二个正面情感概率。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138393_1.jpg)

**Technical Field (技术领域)**:  
语音处理与情感分析领域，具体涉及基于音频的情感检测和主题识别技术。

**Background (发明背景)**:  
现有技术通常通过处理音频输入来确定对话中的情感，例如将对话的文本转录本输入机器学习模型以确定相关情感。然而，这种方法需要生成整个对话的转录本，资源消耗大且效率低下。此外，仅分析文本会丢失情感的其他指示信息（如语调），可能导致情感判断错误。本发明旨在解决这些问题，通过使用对话的音频信息识别情感，并仅对感兴趣的情感部分生成文本表示以识别主题。

**Summary (发明总览)**:  
本发明提出了一种基于音频情感分析的系统，通过分析对话中的音频信息来识别情感，并仅对情感相关的部分生成文本以识别主题。该系统首先使用基于音调的模型分析音频片段的情感概率，然后对高情感概率的片段进行文本转录并识别主题。通过这种方式，系统能够高效地识别对话中的热点情感和热点主题，并提供多种输出形式，如热图、词云或叙述文本。相较于传统方法，本发明减少了处理时间和资源消耗，同时提高了情感判断的准确性。

**Key Innovation (核心创新)**:  
1. 通过基于音调的模型分析音频片段的情感概率，保留情感判断中的语调信息，提高情感识别的准确性。
2. 仅对情感概率超过阈值的音频片段进行文本转录，减少了转录文本的处理量和资源消耗。
3. 使用主题识别模型分析转录文本以识别对话中的主题，并将其与情感概率关联，形成情感-主题关联。
4. 提供多种输出形式（如热图、词云或叙述文本）来展示情感-主题关联，便于用户理解和应用。
5. 通过对多个对话会话的情感-主题关联进行分析，确定热点话题和情感趋势，支持更深入的数据洞察。
6. 系统可处理来自通信设备的音频数据，并结合对话元数据（如客户信息、对话历史）进行更全面的情感和主题分析。
7. 本发明可应用于客户服务场景，帮助客服人员快速识别客户情感和关键话题，提升服务质量和客户满意度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138393)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311692)**
<br/><br/>

---


<br/>

### 4. 人机协作强化学习的计算机平台

**Title (EN)**: Computer Platform for Human-in-the-Loop Reinforcement Learning  
**Pub. No.**: US20260310983

**Applicant**: Google LLC  
**Inventor**: [Amit Mohan Joshi](https://patents.google.com/?inventor=Amit+Mohan+Joshi&country=US&num=100&sort=new), [Yilun Liu](https://patents.google.com/?inventor=Yilun+Liu&country=US&num=100&sort=new), [Phillip Edward Dieter Maier](https://patents.google.com/?inventor=Phillip+Edward+Dieter+Maier&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种计算机实现的方法包括接收由外部计算系统提供的一个或多个机器学习模型的信息，提供用于获取人机协作强化学习（HITL RL）反馈的预定义代码段，识别一个或多个预定义代码段的选择，并基于所选的一个或多个预定义代码段生成一个配置为应用于一个或多个机器学习模型以获取与这些模型的性能相关的反馈的HITL RL框架。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489137614_1.jpg)

**Technical Field (技术领域)**:  
人工智能领域，具体涉及人机协作强化学习技术。

**Background (发明背景)**:  
人机协作强化学习（HITL RL）结合了人工智能和人类专家的优势，通过人机交互提升学习效率。然而，现有技术中，HITL RL的实施通常需要复杂的定制化开发，难以快速部署和调整。此外，在反馈机制和用户交互方式上缺乏灵活性，影响了其在关键领域的应用效果。本发明旨在解决这些问题，提供一个灵活且易于使用的平台来支持HITL RL的实施。

**Summary (发明总览)**:  
本发明提出了一种基于预定义代码段的HITL RL平台，允许用户快速部署机器学习模型并获取反馈以改进模型性能。该平台通过提供多种反馈选项和机制，使用户能够灵活地选择适合其应用场景的反馈方式。平台还支持对机器学习模型的动态更新和优化，从而提升模型的学习效率和准确性。本发明通过简化HITL RL的实施流程，降低了开发难度，并扩展了其应用范围。

**Key Innovation (核心创新)**:  
1. 提供预定义代码段库，用户可快速选择和配置HITL RL框架，简化部署流程。
2. 支持多种反馈机制，包括二元反馈、评分量表、自然语言反馈、交互式反馈和A/B测试反馈，满足不同应用需求。
3. 平台内置API和库，支持对机器学习模型的动态更新和优化，提升学习效率。
4. 针对不同类型的机器学习模型（如生成模型）提供定制化的预定义代码段，增强平台适应性。
5. 支持并行实施多个机器学习模型，并分别获取用户反馈以进行独立优化。
6. 提供输入过滤功能，可根据内容忽略或阻止部分输入被模型处理，提高系统鲁棒性。
7. 反馈结果可与外部系统共享，促进跨系统协作和模型优化，适用于自动驾驶、医疗诊断等高风险领域。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489137614)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260310983)**
<br/><br/>

---


<br/>

### 5. 大语言模型提示的自动调优

**Title (EN)**: AUTOMATIC TUNING OF LLM PROMPTS  
**Pub. No.**: US20260310980

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Shanu KUMAR](https://patents.google.com/?inventor=Shanu+KUMAR&country=US&num=100&sort=new), [Shubhanshu KHANDELWAL](https://patents.google.com/?inventor=Shubhanshu+KHANDELWAL&country=US&num=100&sort=new), [Akhila YESANTARAO VENKATA](https://patents.google.com/?inventor=Akhila+YESANTARAO+VENKATA&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本技术自动调优大语言模型（LLM）的提示以提高性能。系统接收LLM提示作为输入，对其进行优化，并输出更有效的提示。优化过程涉及将提示转换为层次化的提示树，该树将提示组织成不同的部分和子部分。这种结构化格式允许针对特定组件进行系统性的改进，而无需更改整个提示。系统采用演员/评论家学习模型，其中评论家评估演员生成的提示并提供反馈以指导未来的提示生成决策。演员根据反馈执行操作，持续改进其性能。迭代过程生成替代提示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489137611_1.jpg)

**Technical Field (技术领域)**:  
人工智能技术领域，具体涉及大语言模型（LLM）提示调优。

**Background (发明背景)**:  
神经网络是人工智能的关键组成部分，广泛应用于从图像识别到自然语言处理等领域。大语言模型（LLM）通过理解上下文预测句子中的下一个词，从而生成类人文本。然而，LLM的输入提示通常复杂且冗长，优化这些提示以提高模型性能是一项挑战。现有的手动优化方法耗时且效率低下。

**Summary (发明总览)**:  
本发明提出了一种自动优化LLM提示的技术，通过将提示转换为层次化的提示树结构，并利用演员/评论家学习模型进行迭代优化。系统通过分析提示的结构和语义，生成改进后的提示，从而提高LLM的输出质量和效率。该方法相较于传统手动优化方法，能够显著减少优化时间并提升提示质量。

**Key Innovation (核心创新)**:  
1. 采用层次化提示树结构，将复杂提示分解为节点和边，便于系统化分析和优化。
2. 使用演员/评论家学习模型，其中评论家评估提示的有效性并提供反馈，演员根据反馈调整提示生成策略。
3. 通过初步反思和错误评估反思两种类型的反馈机制，分别针对提示的结构语义和输出错误进行优化。
4. 引入迭代优化过程，通过生成多个替代提示并使用验证数据集进行评分，筛选出高质量提示作为下一轮优化的种子。
5. 采用探索/利用方法，在优化过程中既保留高质量提示，又探索低分提示以避免局部最优。
6. 优化后的提示系统能够减少LLM的运算成本并加快响应时间，适用于实时应用场景如客户服务和数据处理。
7. 本技术可应用于商业化LLM提示优化，通过提高提示质量和效率，提升LLM在复杂任务中的表现。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489137611)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260310980)**
<br/><br/>

---


<br/>

### 6. 生成式自定义贴纸

**Title (EN)**: Generative Custom Stickers  
**Pub. No.**: US20260311399

**Applicant**: Google LLC  
**Inventor**: [Jiawei Chen](https://patents.google.com/?inventor=Jiawei+Chen&country=US&num=100&sort=new), [Jiabao Guo](https://patents.google.com/?inventor=Jiabao+Guo&country=US&num=100&sort=new), [Rongjing Xiang](https://patents.google.com/?inventor=Rongjing+Xiang&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种方法，包括由计算设备获取包含待生成图像描述的图像生成提示。该方法进一步包括由计算设备将该图像生成提示提供给机器学习模型。该方法进一步包括由计算设备从机器学习模型获取图像。该方法进一步包括由计算设备输出包含该图像的图形用户界面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138070_1.jpg)

**Technical Field (技术领域)**:  
人工智能图像生成技术，具体涉及利用机器学习模型生成和修改视觉表达。

**Background (发明背景)**:  
用户通过计算设备进行通信时，通常会使用文本和图像等多媒体内容。现有的通信工具允许用户插入图像作为回应，但缺乏生成个性化视觉表达的能力。现有技术难以根据用户输入自动生成符合创意需求的图像，同时保持文本的可读性和图像的合理性。

**Summary (发明总览)**:  
本发明提出了一种利用机器学习模型生成个性化视觉表达的方法。用户可以通过输入图像、文字描述或手势等方式提供创意提示，机器学习模型将根据这些提示生成符合用户创意的图像。该方法能够生成包含创意文本和视觉元素的图像，同时确保文本的可读性和图像的合理性。相较于现有技术，本发明实现了用户与机器学习模型之间的无缝交互，提升了图像生成过程的创意性和灵活性。

**Key Innovation (核心创新)**:  
1. 通过机器学习模型实现图像的自动生成，用户只需提供文字描述或图像提示即可获得符合创意的结果。
2. 支持多种输入方式，包括文字描述、现有图像修改提示、手势绘图等，提供了多样化的创作途径。
3. 生成的图像不仅包含创意视觉元素，还能保持文本的可读性，避免生成混乱或不可理解的文本。
4. 利用图形用户界面输出结果，用户可以直观地查看和使用生成的图像。
5. 机器学习模型经过优化，能够在生成图像时平衡创意性和合理性，确保结果符合用户预期。
6. 该技术可应用于即时通讯工具、社交媒体平台等场景，为用户提供个性化的视觉表达工具。
7. 通过支持多种创意元素的融合，如表情符号和艺术字体，本发明为用户提供了更丰富的创作可能性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138070)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311399)**
<br/><br/>

---


<br/>

### 7. 通过耳塞增强的对话式人工智能与情境感知

**Title (EN)**: EARBUD-ENHANCED CONVERSATIONAL AI WITH AMBIENT AWARENESS  
**Pub. No.**: US20260311695

**Applicant**: GOOGLE LLC  
**Inventor**: [Shahabuddin Kakargola](https://patents.google.com/?inventor=Shahabuddin+Kakargola&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及一种或多种电子设备，其配置为从耳塞中识别与用户语音记录相关的数据，以及从排除用户语音的环境录音中识别第二数据。基于这些数据，可以生成关于环境录音中某一部分的第三数据。第三数据可以存储以供后续与对话式人工智能助手使用。一些实施例能够区分用户的声音与其他环境中的声音。一些实施例允许用户跨多个会话继续与AI进行讨论，并回顾之前的讨论。其他实施例也可以被描述和/或主张。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138396_1.jpg)

**Technical Field (技术领域)**:  
本专利属于智能语音交互领域，具体涉及耳塞设备与对话式人工智能的结合应用。

**Background (发明背景)**:  
近年来，个人数字助手的使用有所增加，但这些助手通常无法进行复杂的讨论或自然的对话。传统的对话式人工智能技术在与耳塞等可穿戴设备集成时，主要关注捕捉佩戴设备的用户输入，这限制了系统对外部对话和环境背景的理解和处理能力。现有的电话录音解决方案无法有效区分用户的声音和其他环境声音，这使得构建对交互及其背景的全面理解变得困难。此外，传统系统缺乏跨多个会话无缝继续与AI助手讨论的能力，阻碍了用户利用之前建立的情境。

**Summary (发明总览)**:  
本发明提出了一种基于耳塞的对话式人工智能技术，通过耳塞捕捉用户的语音和环境声音，并分离处理用户声音和环境中的其他声音。系统能够生成关于环境录音的特定数据，并将其存储以供后续使用。该技术允许用户跨多个会话继续与AI助手进行讨论，并回顾之前的对话内容。与现有技术相比，本发明通过耳塞的音频处理能力实现了用户声音与环境声音的分离，并支持更自然的对话式交互。

**Key Innovation (核心创新)**:  
1. 通过耳塞设备捕捉用户的语音和环境声音，并分离处理用户声音和其他环境声音。
2. 利用音频处理技术从环境录音中提取特定部分的数据，例如会议中同事的孤立声音。
3. 支持跨多个会话继续与AI助手进行讨论，通过保存多个录音文件来保持对话的连续性。
4. 在耳塞中实现音频处理以去除背景噪音，不仅能净化用户的语音，还能净化环境中其他人的声音。
5. 通过蓝牙、Wi-Fi或蜂窝协议等无线连接方式，将处理后的音频数据从耳塞发送到配套设备。
6. 配套设备运行的人工智能助手能够基于接收到的音频数据生成响应，并支持多模态交互。
7. 本技术可应用于会议记录、远程协作等场景，提供更精准的语音分离和更自然的对话体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138396)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311695)**
<br/><br/>

---


<br/>

### 8. 微流体印刷电路板冷却

**Title (EN)**: MICROFLUIDIC PRINTED CIRCUIT BOARD COOLING  
**Pub. No.**: US20260313782

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Shubhangi TEWARI](https://patents.google.com/?inventor=Shubhangi+TEWARI&country=US&num=100&sort=new), [Bharath RAMAKRISHNAN](https://patents.google.com/?inventor=Bharath+RAMAKRISHNAN&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种微流体印刷电路板（PCB），包括：多个层；一个连接到微流体PCB的发热组件；以及一个应用于一个或多个层的微流体通道网络，并与发热组件保持热传导接触，该微流体通道网络与一个或多个层的导电迹线电隔离。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489140681_1.jpg)

**Technical Field (技术领域)**:  
电子设备散热技术领域，具体涉及微流体冷却技术在印刷电路板中的应用。

**Background (发明背景)**:  
印刷电路板（PCB）是电子设备中用于支撑和连接电子元件的基础组件。
传统PCB散热主要依赖外部散热器和空气对流，难以满足高功率密度电路的散热需求。
随着电子设备性能提升，PCB上的高电流密度信号和快速开关电源产生大量热量，散热问题日益突出。
现有技术缺乏高效的集成化散热解决方案。

**Summary (发明总览)**:  
本发明提出了一种集成微流体冷却系统的PCB设计，通过在PCB内部构建微流体通道网络，实现对发热组件的直接冷却。
该系统采用多层PCB结构，在不影响电路功能的前提下，将微流体通道与发热组件进行热传导连接。
通过在通道中循环冷却液，有效带走热量，提升散热效率。
相较于传统散热方式，本发明提供了一种更紧凑、高效的散热解决方案。

**Key Innovation (核心创新)**:  
1. 在PCB内部集成微流体通道网络，实现与发热组件的直接热传导接触，提升散热效率。
2. 采用多层PCB结构，将微流体通道与电路迹线电隔离，确保电路功能不受影响。
3. 在微流体通道网络中引入闭环冷却液循环系统，通过微流体泵驱动冷却液流动，增强散热能力。
4. 设计了封闭循环的微流体通道网络，避免冷却液泄漏并提高系统可靠性。
5. 通过在PCB内部直接冷却发热组件，减少了对外部散热器的依赖，节省了空间并简化了系统设计。
6. 该技术特别适用于数据中心等高密度电子设备环境，可有效解决高功率密度PCB的散热问题。
7. 提供了一种集成化的散热解决方案，可应用于高性能计算、5G基站等对散热要求高的场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489140681)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260313782)**
<br/><br/>

---


<br/>

### 9. 使用屏幕理解技术分析语义用户会话

**Title (EN)**: ANALYZING SEMANTIC USER SESSIONS USING SCREEN UNDERSTANDING  
**Pub. No.**: US20260311448

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Eric Chris Wolfgang SOMMERLADE](https://patents.google.com/?inventor=Eric+Chris+Wolfgang+SOMMERLADE&country=US&num=100&sort=new), [Justin James WAGLE](https://patents.google.com/?inventor=Justin+James+WAGLE&country=US&num=100&sort=new), [Sunando SENGUPTA](https://patents.google.com/?inventor=Sunando+SENGUPTA&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明提供了一种用于分析语义会话的技术及相关实现。一种实现包括计算系统，其包含：处理电路和存储指令的存储器，在执行期间使处理电路执行以下步骤：接收多个屏幕截图图像；对于每个屏幕截图图像：识别截图图像上的一个或多个图像区域和一个或多个文本区域；并使用人工智能模块基于一个或多个图像区域和一个或多个文本区域生成截图图像的特征；生成包含节点和边的用户活动图，其中节点对应多个屏幕截图图像，边对应基于多个屏幕截图图像生成的特征的节点对之间的共性；并基于语义关系从用户活动图中识别一个或多个节点簇。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138124_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及用户行为分析领域，具体涉及利用屏幕截图图像和人工智能技术进行语义用户会话的识别和分析。

**Background (发明背景)**:  
屏幕截图是记录计算机屏幕内容的一种常用方式，但截图通常以无结构的方式存储，难以有效检索和利用。现有技术主要依赖时间戳进行用户会话的划分，但这种方法在用户多任务或返回之前活动时容易产生逻辑不一致的问题。本发明旨在解决现有技术无法准确识别和分析语义用户会话的不足。

**Summary (发明总览)**:  
本发明提出了一种基于屏幕理解技术的语义用户会话分析方法，通过人工智能模块对屏幕截图图像中的图像区域和文本区域进行分析，生成特征并构建用户活动图。该方法利用语义关系对截图进行聚类，形成语义用户会话，从而实现更准确的用户活动识别和搜索功能。与传统基于时间的方法相比，本发明能够更准确地识别用户的多任务行为和活动切换，提升用户对历史会话的检索效率。

**Key Innovation (核心创新)**:  
1. 利用人工智能模块对屏幕截图图像中的图像区域和文本区域进行特征提取，实现对用户活动内容的语义理解。
2. 构建用户活动图，通过节点和边表示截图图像及其共性关系，从而识别用户活动中的语义关系。
3. 基于语义关系对用户活动进行聚类，形成语义用户会话，解决了传统时间划分方法在多任务场景下的逻辑不一致问题。
4. 提供基于自然语言和图像查询的搜索功能，使用户能够快速准确地找到所需的会话信息。
5. 通过连接具有相似提取信息和元数据的语义用户会话，增强搜索和个性化推荐体验。
6. 将语义用户会话信息存储在逻辑组织结构中，为用户提供强大的搜索和访问能力。
7. 本发明可应用于智能助手、用户行为分析工具等场景，为用户提供个性化的信息检索和活动回顾功能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138124)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311448)**
<br/><br/>

---


<br/>

### 10. 保护用户免受非预期跟踪

**Title (EN)**: PROTECTING USERS FROM UNWANTED TRACKING  
**Pub. No.**: US20260313368

**Applicant**: Google LLC  
**Inventor**: [Zachary Abraham Eddinger](https://patents.google.com/?inventor=Zachary+Abraham+Eddinger&country=US&num=100&sort=new), [David Lazarov](https://patents.google.com/?inventor=David+Lazarov&country=US&num=100&sort=new), [Siddika Parlak Polatkan](https://patents.google.com/?inventor=Siddika+Parlak+Polatkan&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种方法，包括由计算设备检测其附近的跟踪设备。该方法进一步包括由计算设备确定该跟踪设备是否已知。如果确定跟踪设备对计算设备是未知的，则计算设备向远程计算系统发送包含跟踪设备位置的位置报告。该方法还包括由计算设备接收来自远程计算系统的命令，以使跟踪设备进入非预期跟踪预防模式。最后，计算设备通过至少发送命令给跟踪设备，使其进入非预期跟踪预防模式。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489140224_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及用户隐私保护技术，具体为通过检测和阻止非预期跟踪设备来保护用户免受跟踪。

**Background (发明背景)**:  
低能耗跟踪设备通常用于通过众包定位系统跟踪各种设备或物品。这些设备会发出低能耗无线信号，其他设备可以检测到并将其标识符和位置发送给跟踪设备服务提供商。然而，这些跟踪设备可能体积小，用户可能无法察觉其存在，从而导致用户被跟踪而不自知。

**Summary (发明总览)**:  
本发明提出了一种通过计算设备检测并阻止非预期跟踪的方法。计算设备检测到附近的未知跟踪设备后，会向远程系统报告其位置。远程系统根据情况决定是否将跟踪设备置于非预期跟踪预防模式，并发送相应命令给计算设备。计算设备随后执行命令，阻止跟踪行为。这种方法使用户能够及时获知被跟踪的情况，并限制跟踪设备对个人的跟踪行为。

**Key Innovation (核心创新)**:  
1. 通过计算设备检测附近未知跟踪设备，并识别其位置，实现对潜在跟踪行为的主动监测。
2. 计算设备将跟踪设备的哈希公钥报告给远程系统，确保数据传输的安全性和隐私性。
3. 远程系统根据接收到的信息决定是否将跟踪设备置于非预期跟踪预防模式，并发送相应命令。
4. 计算设备能够接收并执行远程系统的命令，通过与跟踪设备通信使其进入预防模式，从而阻止跟踪行为。
5. 该方法引入了多因素决策机制，远程系统可根据用户偏好、跟踪设备类型等因素决定具体操作策略。
6. 通过限制跟踪设备的位置获取请求，进一步降低被跟踪的风险。
7. 本专利可应用于智能设备、穿戴设备等场景，为用户提供隐私保护功能，防止未经授权的跟踪行为。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489140224)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260313368)**
<br/><br/>

---


<br/>

### 11. 基于框架的智能穿戴设备光通知系统

**Title (EN)**: FRAME-BASED LIGHT NOTIFICATIONS ON A WEARABLE DEVICE  
**Pub. No.**: US20260309984

**Applicant**: Google LLC  
**Inventor**: [Shiblee Hasan](https://patents.google.com/?inventor=Shiblee+Hasan&country=US&num=100&sort=new), [Natalie Sonsogno Hirano](https://patents.google.com/?inventor=Natalie+Sonsogno+Hirano&country=US&num=100&sort=new), [David Meisenholder](https://patents.google.com/?inventor=David+Meisenholder&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及一种系统，包括头戴式设备的框架和控制器。该系统进一步包括至少一个发光二极管（LED），其位于面向用户的框架部分，并基于控制器的指令向用户眼睛方向发射光线。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489136515_1.jpg)

**Technical Field (技术领域)**:  
智能穿戴设备技术领域，具体涉及头戴式设备的光学通知系统。

**Background (发明背景)**:  
头戴式设备通常用于增强现实、虚拟现实或信息显示等应用，但现有技术难以在不干扰用户当前活动的情况下提供有效通知。例如，智能眼镜可能需要避免遮挡用户视野或发出声音通知。本发明旨在解决这一问题。

**Summary (发明总览)**:  
本发明提出了一种基于头戴式设备框架的光学通知系统，通过在框架上安装LED灯，向用户眼睛方向发射光线以提供通知。该系统可使用扩散层或液晶层来调节光线输出，从而实现柔和且可定制的通知效果。与传统依赖设备主显示器的通知方式不同，本发明提供了一种独立的、面向用户的通知界面。

**Key Innovation (核心创新)**:  
1. 在头戴式设备框架上集成LED灯，通过向用户眼睛方向发射光线实现通知功能，避免了遮挡用户视野或发出声音干扰。
2. 使用扩散层调节LED光线输出，使光线更加均匀柔和，提升视觉舒适度并减少刺眼感。
3. 采用液晶层（LCD）技术，通过控制液晶旋转偏振光，实现对LED光线的动态调节，可显示图像或字符以增强通知效果。
4. 结合环境光传感器和眼动追踪技术，根据环境光线强度和用户注视方向动态调整LED亮度或选择通知LED的位置。
5. 提供直接显示功能，LED阵列可直接向用户显示通知内容，无需依赖设备主显示系统。
6. 在无内容显示的情况下，液晶层可与框架颜色融合，减少光源对用户的视觉干扰。
7. 该技术可应用于智能眼镜等设备，提供如音量调节、来电提醒等独立于主显示器的通知功能，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489136515)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260309984)**
<br/><br/>

---


<br/>

### 12. 混合现实工作流程生成

**Title (EN)**: MIXED REALITY WORKFLOW GENERATION  
**Pub. No.**: US20260311435

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Edward Sean Lloyd RINTEL](https://patents.google.com/?inventor=Edward+Sean+Lloyd+RINTEL&country=US&num=100&sort=new), [Prashant VAIDYANATHAN](https://patents.google.com/?inventor=Prashant+VAIDYANATHAN&country=US&num=100&sort=new), [Paul Kerr GRANT](https://patents.google.com/?inventor=Paul+Kerr+GRANT&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明描述了一种生成混合现实工作流程的计算机实现方法。该方法包括识别一系列任务，并通过分析定义第一用户在与第一位置中的对象交互时执行的过程的数据，生成输入任务到对象映射。该映射将每个任务映射到相应任务中使用的对象。确定输入任务到对象映射中每个对象的特定于任务非空间特征，并用于将输入任务到对象映射中的每个对象映射到在第二位置中识别的候选对象，以生成输出任务到对象映射。使用任务序列、第二位置中每个候选对象的位置数据以及输出任务到对象映射来生成映射工作流程，然后将其输出到第二位置的设备。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138110_1.jpg)

**Technical Field (技术领域)**:  
混合现实技术领域，具体涉及工业应用中的混合现实工作流程生成与执行。

**Background (发明背景)**:  
头戴式显示器（HMD）和混合现实（MR）应用在工业领域的应用日益普及，用于辅助流程指导或故障排除。现有技术通常需要手动创建MR工作流程，且当流程或设备发生变化时，需要重复整个创建过程。此外，现有方法依赖于空间约束或对象标识符进行映射，灵活性不足。

**Summary (发明总览)**:  
本发明提出了一种基于非空间特征的混合现实工作流程生成与执行方法。该方法通过分析第一用户执行过程任务的过程，生成任务到对象映射，并利用对象的特定于任务的非空间特征，将该映射动态应用于第二位置的不同设备布局。该方法无需依赖空间约束或对象标识符，能够在不同布局的多个位置重复使用同一工作流程，从而提高流程的适应性和效率。

**Key Innovation (核心创新)**:  
1. 通过分析第一用户执行过程任务的过程，生成任务到对象映射，并利用对象的特定于任务的非空间特征进行映射。
2. 确定对象的特定于任务非空间特征，包括任务执行所需的能力和相关的环境约束，例如照明要求或障碍物限制。
3. 利用非空间特征而非空间约束或对象标识符，将第一位置的工作流程动态映射到第二位置的不同设备布局。
4. 支持在第二位置中识别具有相似非空间特征的对象，从而实现工作流程的灵活应用，无需完全相同的设备或布局。
5. 通过选择第二位置中更高效或更合适的设备，优化工作流程的执行路径，例如缩短流程时间或减少设备使用数量。
6. 允许在具有安全和/或安全限制的第二位置中执行工作流程，即使第一用户无法在该位置进行记录。
7. 应用于工业环境中的流程指导或故障排除，能够在不同设备布局和位置间快速部署和调整MR工作流程，提高操作效率和适应性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138110)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311435)**
<br/><br/>

---


<br/>

### 13. 针对不活跃消费者的数字广告活动价值动态调整方法

**Title (EN)**: Dynamically Adjusting Digital Component Campaign Values For Disengaged Consumers  
**Pub. No.**: US20260311218

**Applicant**: Google LLC  
**Inventor**: [Srinivas Rajamani](https://patents.google.com/?inventor=Srinivas+Rajamani&country=US&num=100&sort=new), [Manish Kurse](https://patents.google.com/?inventor=Manish+Kurse&country=US&num=100&sort=new), [Geoffrey Levine](https://patents.google.com/?inventor=Geoffrey+Levine&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明主要涉及在选择数字广告时确定消费者是否属于不活跃消费者或符合条件的不活跃消费者。通过训练和使用人工智能模型预测消费者是否属于不活跃消费者或符合条件的不活跃消费者，生成一个概率值，该概率值代表用户属于上述类别的可能性。该概率值可用于在拍卖时动态调整商家的出价，以确保其数字广告被选中。在某些情况下，该概率值还可用于在商家数字广告展示后动态调整转化价值。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489137872_1.jpg)

**Technical Field (技术领域)**:  
数字广告投放；人工智能预测模型；消费者行为分析

**Background (发明背景)**:  
商家通常会创建数字广告活动以获取、保留或重新吸引消费者。为了重新吸引之前参与过的消费者，商家通常会为特定消费者群体提高出价和/或转化价值。这导致商家需要创建多个广告活动，增加了时间和计算成本，并可能导致商家在拍卖时与自己竞争。本发明旨在解决上述问题，通过智能预测消费者状态并动态调整广告策略来提高效率。

**Summary (发明总览)**:  
本发明提出了一种基于人工智能的动态广告优化方法，通过预测消费者是否属于不活跃或符合条件的不活跃消费者来调整广告出价和转化价值。该方法利用机器学习模型分析消费者行为数据，生成概率预测值，并据此在广告拍卖时动态调整商家的出价策略。此外，该方法还支持在广告展示后根据预测结果调整转化价值，从而实现更精准的广告投放和资源优化。

**Key Innovation (核心创新)**:  
1. 引入不活跃消费者和符合条件的不活跃消费者的分类标准，通过商家定义的标准（如转化时间间隔、转化频率等）进行识别。
2. 利用人工智能模型（如机器学习模型）预测消费者属于不活跃或符合条件的不活跃类别的概率，为广告出价提供数据支持。
3. 在广告拍卖时，根据预测概率动态调整出价值，确保广告被选中，同时避免过度竞价。
4. 在广告展示后，根据预测概率调整转化价值，例如将不活跃消费者转化价值与预测概率相乘，实现更精准的价值评估。
5. 针对高价值不活跃消费者（符合特定价值标准的消费者）进行特别处理，通过调整其转化价值来优化广告效果。
6. 支持对新消费者和新符合条件消费者的预测和出价调整，进一步扩展了广告投放的覆盖范围。
7. 本方法可应用于电商平台、社交媒体广告等场景，帮助商家更高效地重新吸引不活跃消费者，同时优化广告预算使用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489137872)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311218)**
<br/><br/>

---


<br/>

### 14. 在远程桌面环境中实现高动态范围显示技术

**Title (EN)**: IMPLEMENTING HIGH DYNAMIC RANGE DISPLAY TECHNOLOGY IN A REMOTE DESKTOP ENVIRONMENT  
**Pub. No.**: US20260313171

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Artem BELKINE](https://patents.google.com/?inventor=Artem+BELKINE&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明提供了一种方法、计算机系统和计算机存储介质，用于促进高动态范围（HDR）显示技术在远程桌面环境中的实现。在实施例中，远程桌面服务器的视频驱动程序获取用于在远程桌面客户端设备上呈现的图形数据。基于使用HDR视频编码器进行编码的指示，图形数据被提供给与视频驱动程序逻辑分离的HDR视频编码器。随后，通过HDR视频编码器对图形数据进行编码，并将编码后的图形数据提供给远程桌面服务器的终端服务中的远程访问协议栈，以将编码后的图形数据传输到关联的远程桌面客户端设备。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489140006_1.jpg)

**Technical Field (技术领域)**:  
远程桌面技术；高动态范围（HDR）显示；视频编码与传输。

**Background (发明背景)**:  
远程桌面服务允许用户通过另一设备访问和控制远程计算机或虚拟机，提供虚拟桌面体验。传统实现中，远程桌面服务器通过远程桌面协议（RDP）栈对数据进行编码后再传输给客户端设备。然而，这种方式需要大量计算资源来同步和复制未编码数据到RDP栈进行编码，尤其在显示器分辨率提高时，CPU和内存资源消耗显著增加。例如，HDR显示器由于像素密度更高，可能需要双倍的内存和CPU资源进行编码。

**Summary (发明总览)**:  
本发明通过在视频驱动程序中执行数据编码，显著提升了HDR显示技术在远程桌面环境中的实现效率。具体实现方式是将数据编码过程与数据获取过程合并，避免了传统方法中数据在视频驱动程序和RDP栈之间的同步和复制操作。通过这种方式，编码后的数据可以直接传输给远程桌面客户端设备，从而减少CPU和内存资源的消耗。本发明相较于现有技术的主要改进在于优化了数据处理流程，降低了系统资源消耗，并支持更高分辨率的HDR显示器。

**Key Innovation (核心创新)**:  
1. 在视频驱动程序中集成HDR视频编码器，实现数据获取与编码过程在同一进程中完成，避免了数据同步和复制带来的资源消耗。
2. 通过逻辑分离的视频编码管理器管理HDR视频编码器，确保视频驱动程序作为纯驱动运行，不直接参与数据编码或封装。
3. 利用监控配置数据来建立HDR虚拟显示器，使视频驱动程序能够获取每像素8字节的图形数据，从而支持更高保真度的图像表示。
4. 视频编码管理器负责与RDP栈的内部协议通信，确保编码后的数据能够高效传输到远程桌面客户端设备。
5. 通过减少CPU和内存资源的消耗，本发明能够支持多HDR显示器的同时使用，提升远程桌面环境的整体性能。
6. 本发明特别适用于需要处理高分辨率图形数据的应用场景，如专业图形设计、4K视频会议等。
7. 通过优化数据处理流程，本发明能够显著提升远程桌面环境中HDR显示技术的实现效率，为用户提供更流畅的视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489140006)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260313171)**
<br/><br/>

---


<br/>

### 15. 利用音频匹配提升视频内容项之间的视觉匹配召回率

**Title (EN)**: Leveraging Audio Matches to Improve Visual Matching Recall Between Video Content Items  
**Pub. No.**: US20260313192

**Applicant**: Google LLC  
**Inventor**: [Mayank Kandpal](https://patents.google.com/?inventor=Mayank+Kandpal&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
在第一视频内容项和第二视频内容项之间执行音频匹配以识别匹配的音频片段。基于匹配的音频片段，生成第一视频内容项与第二视频内容项之间的视觉相似度值。从生成的视觉相似度值中选择前预定百分比的最高视觉相似度值。执行集中度分析以确定所选的前预定百分比的最高视觉相似度值是否沿着与匹配音频片段相对应的时间对齐方向呈对角线模式分布。基于集中度分析确定第一视频内容项与第二视频内容项之间的匹配。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489140030_1.jpg)

**Technical Field (技术领域)**:  
本专利属于多媒体内容匹配技术领域，具体涉及利用音频匹配优化视频内容视觉匹配的技术。

**Background (发明背景)**:  
在数字内容平台中，内容匹配对于版权保护、内容审核和媒体检索等应用至关重要。随着用户生成内容（UGC）和编辑工具的普及，传统的视觉匹配方法在处理经过视觉修改的内容时面临挑战，例如裁剪、叠加和缩放效果，这些修改会降低匹配准确率和召回率。现有技术通常独立处理视觉和音频数据，未能有效利用音频线索来指导视觉匹配，导致资源浪费和检测效率低下。

**Summary (发明总览)**:  
本发明提出了一种结合音频匹配与视觉匹配的内容识别方法，通过音频匹配确定视频内容项之间的匹配音频片段，并基于此定义视觉搜索空间。随后在搜索空间内执行视觉匹配，并通过集中度分析检测高相似度值的分布模式，从而确定视频内容项之间的匹配关系。该方法通过音频匹配引导视觉匹配，显著提高了对复杂视觉变换内容的检测效率与准确性。

**Key Innovation (核心创新)**:  
1. 通过音频匹配识别视频内容项之间的匹配音频片段，并基于此定义视觉搜索空间，从而减少视觉匹配的搜索范围。
2. 在视觉搜索空间内生成视觉相似度值，并选择前预定百分比的最高相似度值进行集中度分析，有效过滤噪声数据。
3. 通过检测高相似度值是否沿时间对齐方向呈对角线模式分布，判断视频内容项之间是否存在匹配关系。
4. 采用集中度分析技术，识别视觉相似度值的集群分布模式，提高对复杂视觉变换（如裁剪、叠加和缩放）的检测能力。
5. 通过音频匹配引导视觉匹配，优化了计算资源分配，提升了匹配效率，同时保持了高召回率。
6. 该方法特别适用于处理经过复杂视觉修改的视频内容，例如非中心裁剪、叠加效果和缩放效果。
7. 本发明可应用于版权保护、内容审核和媒体检索等领域，能够更准确地识别经过视觉修改的重复或衍生内容。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489140030)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260313192)**
<br/><br/>

---


<br/>

### 16. 从直播视频流生成短视频

**Title (EN)**: GENERATING SHORT VIDEOS FROM LIVE VIDEO STREAMS  
**Pub. No.**: US20260313209

**Applicant**: Google LLC  
**Inventor**: [Xinru Yang](https://patents.google.com/?inventor=Xinru+Yang&country=US&num=100&sort=new), [Hui Miao](https://patents.google.com/?inventor=Hui+Miao&country=US&num=100&sort=new), [Yi Zhang](https://patents.google.com/?inventor=Yi+Zhang&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及使用神经网络处理视频数据的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。在一个方面，获取视频内容的直播流。对于直播视频内容中的多个连续时间间隔中的每个时间间隔：基于使用多模态神经网络系统处理多模态输入来生成候选短视频。从为多个连续时间间隔生成的候选短视频中选择一个或多个短视频。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489140049_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及视频处理技术，具体为基于多模态神经网络从直播视频流中自动生成短视频。

**Background (发明背景)**:  
随着互联网的发展，视频数据的传播变得广泛，直播视频流成为一种流行的视频数据类型。短视频近年来也因其适合社交媒体平台和用户短注意力而流行。然而，现有的短视频生成方法通常需要人工干预，且无法实时处理直播内容。本发明旨在解决自动生成短视频并减少人工参与的问题。

**Summary (发明总览)**:  
本发明提出了一种自动生成短视频的方法，通过多模态神经网络系统实时处理直播视频流。该系统利用直播视频内容的多模态数据，包括创作者的内容流和观众的行为数据，在多个连续时间间隔内生成候选短视频，并从中选择最佳短视频进行展示。该方法无需用户手动操作，能够实时生成短视频并提供更精准的内容摘要。

**Key Innovation (核心创新)**:  
1. 利用多模态神经网络系统处理直播视频流的多模态数据，包括视觉数据、音频数据和观众行为数据，从而生成候选短视频。
2. 通过自动语音识别（ASR）模型将创作者的语音内容转录为文本，并将其作为多模态输入的一部分，以提高短视频内容的准确性。
3. 采用提议神经网络生成候选短视频的时间戳，定义短视频的开始和结束时间，从而实现精准的视频片段选择。
4. 使用选择器神经网络根据内容标准和重要性评分从候选短视频中选择最佳短视频，确保生成的短视频具有高代表性和吸引力。
5. 提供实时生成的短视频作为创作者内容流的摘要，帮助用户快速预览直播内容，而无需观看整个直播视频。
6. 生成的短视频可以存储在数据库中，而无需存储原始的创作者和观众内容流，从而节省存储资源。
7. 本发明可应用于直播平台，实现自动化的短视频生成和发布，提升用户体验并减少人工编辑成本。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489140049)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260313209)**
<br/><br/>

---


<br/>

### 17. 基于信息检索反馈的强化学习

**Title (EN)**: Reinforcement Learning With Information Retrieval Feedback  
**Pub. No.**: US20260311065

**Applicant**: Google LLC  
**Inventor**: [Hyun Jin Park](https://patents.google.com/?inventor=Hyun+Jin+Park&country=US&num=100&sort=new), [Chang Wan Ryu](https://patents.google.com/?inventor=Chang+Wan+Ryu&country=US&num=100&sort=new), [Dongseong Hwang](https://patents.google.com/?inventor=Dongseong+Hwang&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明提供了一种用于生成训练机器学习代理模型的反馈信号的计算机实现方法。该方法包括获取机器学习代理模型的输出，该输出基于一系列前序状态生成下一个状态特征。通过使用机器学习奖励模型处理输出和前序状态序列，生成一个质量指标，用于指示在考虑前序状态的情况下下一个状态特征的质量。机器学习奖励模型通过从参考数据源检索参考数据，并基于相应的训练输入、训练输出和参考数据计算一个或多个质量指标来进行训练。该方法还包括将质量指标输出到模型训练器，以基于质量指标更新机器学习代理模型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489137705_1.jpg)

**Technical Field (技术领域)**:  
机器学习领域，具体涉及强化学习中的反馈信号生成和模型训练。

**Background (发明背景)**:  
传统的机器学习模型通过执行指令并根据参数化模型生成输出，然后使用评估指标来改进模型性能。然而，现有技术依赖于人工反馈或手工设计的启发式方法进行反馈，这可能导致训练效率低下且成本高昂。此外，这些方法难以保证反馈的一致性和准确性。本发明旨在通过机器学习奖励模型自动生成反馈信号，减少对人工干预的依赖，提高训练效率和一致性。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习奖励模型的强化学习训练方法。该方法通过生成质量指标作为反馈信号，用于训练机器学习代理模型。奖励模型通过访问参考数据源来提高反馈信号的准确性，从而减少对人工反馈的依赖。相较于现有技术，本发明通过自动化的反馈生成机制，提高了训练效率，降低了成本，并实现了更一致和准确的模型训练。

**Key Innovation (核心创新)**:  
1. 引入机器学习奖励模型，通过处理代理模型的输出和前序状态序列，生成质量指标作为反馈信号。
2. 奖励模型通过检索参考数据源并计算质量指标进行训练，确保反馈信号的准确性和可靠性。
3. 采用监督模型（可结合人工标注）生成参考质量指标，用于训练奖励模型，从而将更广泛的世界知识融入反馈信号。
4. 通过直接检索参考数据源或使用基于参考数据生成的训练数据，奖励模型能够更有效地生成与监督模型一致的质量信号。
5. 该方法减少了人工反馈的使用，降低了训练成本，同时提高了反馈信号的一致性和准确性。
6. 通过更高效的反馈机制，训练过程更加节能，减少了与模型训练相关的碳排放和资源消耗。
7. 本发明可应用于各种需要强化学习的场景，如对话系统、机器人控制和复杂任务求解等，能够显著提升代理模型的性能和训练效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489137705)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311065)**
<br/><br/>

---


<br/>

### 18. 计算设备耳机输入

**Title (EN)**: COMPUTING DEVICE HEADSET INPUT  
**Pub. No.**: US20260310399

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Kenneth P. HINCKLEY](https://patents.google.com/?inventor=Kenneth+P.+HINCKLEY&country=US&num=100&sort=new), [Michel PAHUD](https://patents.google.com/?inventor=Michel+PAHUD&country=US&num=100&sort=new), [Mar Gonzalez FRANCO](https://patents.google.com/?inventor=Mar+Gonzalez+FRANCO&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及计算设备耳机输入。通过处理耳机设备中一个或多个传感器的数据来识别隐式和/或显式用户输入，并确定用户输入的上下文，从而处理识别出的输入并生成影响计算设备行为的操作。因此，耳机设备可用于控制一个或多个计算设备。与其他可穿戴设备相比，耳机设备更为普及，因此能够提供更便捷、更直观的用户输入，而不仅仅是提供音频输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489136970_1.jpg)

**Technical Field (技术领域)**:  
本发明属于人机交互技术领域，具体涉及利用耳机设备传感器进行用户输入识别与控制的技术。

**Background (发明背景)**:  
耳机设备通常用于体验计算设备的音频输出，因此被广泛接受并具有既定的使用规范。然而，耳机设备的输入功能通常有限，即使它们已经非常普及。现有的耳机设备主要作为输出设备使用，尽管一些耳机配备了传感器，也主要用于控制音频播放。

**Summary (发明总览)**:  
本发明提出了一种通过耳机设备传感器数据识别用户输入并控制计算设备的方法。通过处理传感器数据，识别用户的显式或隐式输入，并结合上下文生成相应的操作指令，从而实现对计算设备的控制。该方法利用耳机设备的普及性和用户接受度，提供更便捷和直观的控制方式。此外，本发明还支持通过扩展设备增强耳机功能，并可应用于多种计算设备，包括移动设备、台式机及游戏主机等。

**Key Innovation (核心创新)**:  
1. 通过耳机设备的传感器数据识别用户的显式和隐式输入，例如头部运动、触摸输入、手势和嘴部动作等。
2. 结合用户输入的上下文信息（如应用类型、地理位置、耳机连接方式等）生成相应的操作指令。
3. 支持耳机设备与多个计算设备之间的双向通信，并根据用户头部朝向或注视目标动态切换控制目标设备。
4. 通过扩展设备（如附加传感器或输入控制模块）增强耳机功能，使用户能够根据不同场景选择不同的输入方式。
5. 在用户隐私保护方面，部分处理在耳机设备本地完成，减少对外部计算资源的依赖。
6. 支持虚拟在场技术，为非视频参与者生成虚拟形象，并通过耳机设备控制其动作和表情。
7. 可应用于多种场景，例如在视频会议中通过耳机控制虚拟形象，或在游戏和媒体播放中实现更直观的控制方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489136970)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260310399)**
<br/><br/>

---


<br/>

### 19. 用户通道与数字资产双向交互的装置和方法

**Title (EN)**: APPARATUS AND METHOD FOR BI-DIRECTIONAL INTERACTION BETWEEN USER CHANNELS AND A DIGITAL ASSET  
**Pub. No.**: US20260312784

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Andrei PAPANCEA](https://patents.google.com/?inventor=Andrei+PAPANCEA&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
在一个实施例中，通过第一通道接收与数字资产相关的请求。通过第一通道向计算设备发送第二通道的连接信息。第一通道和第二通道被同步。接收与数字资产相关的终端用户输入和数字资产的上下文信息。将终端用户输入分类为第一类或第二类中的至少一类。当终端用户输入被分类为第一类时，通过第一通道向计算设备发送包括第一类指示和相关元数据的指令，以使计算设备执行该指令。当终端用户输入被分类为第二类时，通过第二通道向计算设备发送消息，以使计算设备输出消息的内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489139585_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及多通道同步交互和数字资产操作。

**Background (发明背景)**:  
现有技术在用户访问信息和导航图形用户界面时存在挑战，例如由于用户残疾或用户体验不佳。传统界面缺乏自然语言交互，用户难以直接表达需求。在复杂应用中，用户难以找到特定功能或信息，尤其是在移动设备或用户操作不便的情况下。现有解决方案通常依赖交互式语音应答（IVR）系统，但这些系统在处理复杂任务时效率低下且容易导致用户挫折感。

**Summary (发明总览)**:  
本发明提出了一种多通道同步交互方法，通过连接用户与数字资产（如网站）的多个交互通道，实现更自然和高效的操作。用户可以通过对话通道（如聊天或语音）与系统交互，系统将相关操作指令发送到非对话通道（如网站或移动应用）。系统能够理解用户意图并根据上下文提供精准反馈，从而简化复杂任务的操作流程，提升用户体验。

**Key Innovation (核心创新)**:  
1. 实现了对话通道（如聊天或语音）与非对话通道（如网站或移动应用）的双向同步交互。
2. 通过自然语言处理技术，将用户输入分类为不同类别，并生成相应的指令或消息。
3. 支持基于上下文的操作，例如在特定页面或应用中提供精准的问答反馈。
4. 允许用户定义自定义操作，例如触发移动应用或网站上的独特功能。
5. 提供了跨平台的无缝体验，无需依赖现有的API系统即可实现复杂任务的自动化处理。
6. 通过同步多个通道，解决了传统IVR系统在处理复杂任务时的局限性和用户挫折感。
7. 应用于导航教育平台、管理个人财务、填写在线表格或与智能家居设备交互等场景，提升了用户操作的直观性和效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489139585)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260312784)**
<br/><br/>

---


<br/>

### 20. 用于提供基于网络的服务的用户界面的复合身份表示

**Title (EN)**: COMPOSITE IDENTITY REPRESENTATION FOR PROVIDING USER INTERFACES OF NETWORK-BASED SERVICES  
**Pub. No.**: US20260312959

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ariel Nicolas GORDON](https://patents.google.com/?inventor=Ariel+Nicolas+GORDON&country=US&num=100&sort=new), [Michael Aaron BRASKET](https://patents.google.com/?inventor=Michael+Aaron+BRASKET&country=US&num=100&sort=new), [Kundan BHARTI](https://patents.google.com/?inventor=Kundan+BHARTI&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
识别生成表示第一用户的在线状态的用户界面元素的触发条件，其中第一用户关联服务的第一个账户和第二个账户。基于第一用户的标识符，识别出复合身份数据结构，该结构同时标识第一个账户和第二个账户。响应于数据结构标识第一用户与两个账户关联，应用选择规则以基于与第一个账户或第二个账户相关的活动确定统一的在线状态。将用户界面元素提供给查看用户的设备，以单一表示形式呈现跨第一个账户和第二个账户的统一在线状态。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489139774_1.jpg)

**Technical Field (技术领域)**:  
网络身份管理；复合身份数据结构；用户界面优化

**Background (发明背景)**:  
网络服务涵盖计算、存储、通信等功能，为组织和个人提供远程资源访问和管理。然而，在多租户环境中，跨组织协作需要共享资源，这带来了访问策略和安全管理的复杂性。现有的代理账户或影子账户方法虽然提供了外部访问途径，但导致用户身份碎片化，影响用户体验并增加管理负担。

**Summary (发明总览)**:  
本发明提出了一种复合身份数据结构，用于整合代表同一用户的多个代理账户信息。通过该结构，系统能够基于资源请求智能选择合适的账户进行访问，从而实现无缝的资源访问体验。同时，该结构还用于改进用户界面，通过统一展示用户信息，减少身份碎片化带来的混淆，提升整体协作效率。

**Key Innovation (核心创新)**:  
1. 提出了复合身份数据结构，用于聚合同一用户的多个代理账户信息，实现用户身份的集中管理。
2. 采用启发式规则识别和关联属于同一用户的不同代理账户，确保身份匹配的准确性。
3. 在资源访问过程中，系统根据复合身份数据结构智能选择合适的账户进行访问，避免用户手动切换账户。
4. 通过即时（JIT）账户配置机制，自动为用户创建必要的代理账户类型，以满足特定资源访问需求，提升访问灵活性。
5. 在用户界面中统一展示用户信息，整合多个账户的属性如头像、在线状态、位置和职位等，提供更完整和一致的用户视图。
6. 简化搜索功能，将多个身份表示合并为单一搜索结果，减少用户认知负担，提高查找效率。
7. 该技术特别适用于企业协作平台，可提升跨组织协作的安全性和用户体验，例如在Microsoft Teams等应用中提供更流畅的外部用户访问体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489139774)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260312959)**
<br/><br/>

---


<br/>

### 21. 视频游戏帮助会话的跟踪与表示

**Title (EN)**: TRACKING AND REPRESENTING VIDEO GAME HELP SESSIONS  
**Pub. No.**: US20260306949

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Monica Ann ADJEMIAN](https://patents.google.com/?inventor=Monica+Ann+ADJEMIAN&country=US&num=100&sort=new), [Jennifer R. GURIEL](https://patents.google.com/?inventor=Jennifer+R.+GURIEL&country=US&num=100&sort=new), [Gershom PAYZER](https://patents.google.com/?inventor=Gershom+PAYZER&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及跟踪和表示视频游戏中的帮助会话，其中视频游戏玩家由助手（例如，另一位视频游戏玩家或训练有素的机器学习模型）提供帮助。例如，本发明的实施方式可以通过图形化修改可控制实体（如角色或车辆）来传达当前视频游戏玩家正在接受助手帮助的信息。作为另一个例子，本发明的实施方式可以通过图形化修改游戏成就来指示某个成就是在助手的帮助下获得的。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489133170_1.jpg)

**Technical Field (技术领域)**:  
视频游戏技术领域，具体涉及游戏内帮助会话的跟踪与表示。

**Background (发明背景)**:  
视频游戏玩家在游戏中常遇到困难情况，如难以击败的敌人、难以找到的物品或难以完成的关卡等。玩家通常通过在线论坛或视频寻求其他玩家的帮助，但这些方法较为基础且效率低下。现有的游戏内帮助方式也难以区分玩家自身操作与助手操作，且难以确定成就的归属。

**Summary (发明总览)**:  
本发明提出了一种跟踪和表示视频游戏帮助会话的方法，通过记录帮助会话的起始状态、更新状态以及成就的归属来实现更清晰的游戏内帮助体验。具体实现包括从玩家保存的游戏状态中获取帮助会话的起始状态，初始化帮助会话，跟踪会话后的游戏状态更新，并在玩家接受更新状态且成就发生在帮助会话期间时，记录成就并指示成就是在助手帮助下获得的。相较于现有技术，本发明能够更准确地跟踪和表示帮助会话中的操作和成就归属。

**Key Innovation (核心创新)**:  
1. 通过图形化修改游戏中的可控制实体（如角色或车辆）来直观显示当前玩家正在接受助手帮助，提升玩家对帮助状态的感知。
2. 通过图形化修改游戏成就，清晰指示成就的获得是否依赖于助手的帮助，解决了成就归属不明确的问题。
3. 利用机器学习模型（如支持向量机、决策树、随机森林或神经网络）来自动检测帮助会话的触发条件和结束条件，实现智能化的帮助会话管理。
4. 在帮助会话结束后，系统会获取更新后的游戏状态，并根据玩家的接受情况更新用户数据库，准确记录帮助会话中的成就。
5. 系统能够区分玩家自身操作与助手操作，确保成就记录的准确性，并提供更公平的游戏成就统计。
6. 本发明可应用于多人在线游戏或单人游戏中的合作模式，通过提供更智能和直观的帮助体验，提升玩家互动性和游戏体验。
7. 通过准确跟踪和表示帮助会话，本发明能够帮助游戏开发者更好地理解玩家行为，优化游戏设计和平衡性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489133170)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260306949)**
<br/><br/>

---


<br/>

### 22. 角偏移显示与照明

**Title (EN)**: ANGULAR OFFSET DISPLAY AND ILLUMINATION  
**Pub. No.**: US20260309985

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Fei Chen](https://patents.google.com/?inventor=Fei+Chen&country=US&num=100&sort=new), [Scott Jeffrey Woltman](https://patents.google.com/?inventor=Scott+Jeffrey+Woltman&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及一种显示系统，包括硅基液晶（LCOS）显示器和光源层。LCOS显示器由按行和列排列形成矩形的LCOS显示像素组成，能够驱动数字偏移图像至LCOS显示像素的角偏移部分，该部分相对于由行和列形成的矩形呈角偏移。光源层包含一系列光源，这些光源以特定角度排列，以角偏移的方式照亮LCOS显示像素的角偏移部分。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489136516_1.jpg)

**Technical Field (技术领域)**:  
光学技术领域，具体涉及角偏移显示与照明技术。

**Background (发明背景)**:  
现代显示技术包括液晶显示器（LCD）、投影仪、有机发光二极管（OLED）阵列和硅基液晶（LCOS）显示器等。显示器的性能指标如亮度和对比度在不同应用场景中各有优劣。在增强现实（AR）眼镜等应用中，LCOS显示器的设计通常受限于其矩形像素阵列与波导的配合，导致整体外形设计自由度较低，可能产生不必要的突起。

**Summary (发明总览)**:  
本发明提出了一种角偏移显示与照明技术，通过在LCOS显示器的像素阵列上驱动数字偏移图像，并利用角偏移的光源层进行照明，实现了在不显著降低分辨率的情况下，提升头戴式显示器（HMD）如AR眼镜的设计自由度。该技术允许显示组件以更紧凑、更理想的外形集成，同时仍能有效将显示光传递至波导以呈现虚拟图像。

**Key Innovation (核心创新)**:  
1. 通过在LCOS显示器的像素阵列上驱动数字偏移图像，实现图像的角偏移显示，从而允许显示组件以更紧凑的外形集成。
2. 利用角偏移的光源层，仅照亮LCOS显示像素的角偏移部分，避免了对未驱动像素的照明，提高了照明效率。
3. 通过减少对LCOS显示器的整体照明区域，优化了显示器的能耗管理，同时保持了图像质量。
4. 在不显著降低分辨率的情况下，通过角偏移技术提升了HMD设备的设计自由度，解决了传统矩形像素阵列与波导配合时的设计限制。
5. 实现了更紧凑的AR眼镜外形，避免了因传统设计导致的突起，提升了设备的佩戴舒适性和美观度。
6. 通过调整光源角度和LCOS显示器的驱动模式，精确控制显示光的方向和强度，优化了虚拟图像的呈现效果。
7. 该技术可应用于AR眼镜等头戴式显示设备，提供更优的显示解决方案，尤其在小型化设计和视觉体验提升方面具有独特价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489136516)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260309985)**
<br/><br/>

---


<br/>

### 23. 面向特定受众的媒体内容生成的人工智能代理架构

**Title (EN)**: AI AGENT ARCHITECTURE FOR AUDIENCE-SPECIFIC MEDIA CONTENT GENERATION  
**Pub. No.**: US20260311384

**Applicant**: GOOGLE LLC  
**Inventor**: [Joseph Patrick Timmons](https://patents.google.com/?inventor=Joseph+Patrick+Timmons&country=US&num=100&sort=new), [John Scott Penberthy](https://patents.google.com/?inventor=John+Scott+Penberthy&country=US&num=100&sort=new), [Nicholas Earl Losier](https://patents.google.com/?inventor=Nicholas+Earl+Losier&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种自动生成与产品和受众相关的媒体内容的方法，包括使用一组训练有素的人工智能（AI）代理生成创意简报。生成创意简报包括使用受众推断AI代理根据至少一个受众参数推断受众的一个或多个特征，使用设置AI代理根据至少一个产品参数和推断出的受众特征生成设置描述符，使用场景代理根据至少一个产品参数和推断出的受众特征生成场景描述符，以及使用创意简报AI代理根据设置描述符和场景描述符生成创意简报。该方法还包括使用AI代理根据参数和/或推断结果生成媒体内容的音频（例如旁白和/或音乐）。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138053_1.jpg)

**Technical Field (技术领域)**:  
数字媒体生成技术，具体涉及使用生成式人工智能根据动态变化的源信息生成高质量媒体内容。

**Background (发明背景)**:  
在数字广告等领域，定制化媒体内容的需求日益增长，但现有生成式AI模型常生成低质量内容，存在视觉不一致、主题不准确等问题。传统方法依赖人工密集的后期处理或分散的AI工具，导致效率低下且结果欠佳。

**Summary (发明总览)**:  
本发明提出了一种基于AI代理的媒体内容生成方法，通过协调多个专门化的AI代理完成特定任务，从而生成符合产品与受众参数的高质量媒体内容。AI代理分别用于推断受众特征、生成设置和场景描述符，并最终生成创意简报以驱动生成式AI模型产出内容。该方法通过分阶段处理和AI代理的协同工作，确保内容在关键方面（如视觉质量、受众相关性等）达到高标准，同时具备高度的可扩展性和适应性。

**Key Innovation (核心创新)**:  
1. 采用多AI代理协同工作架构，通过分工协作实现媒体内容生成过程的模块化与专业化。
2. 使用受众推断AI代理基于受众参数进行深度特征提取，确保内容与受众特征高度匹配。
3. 通过设置AI代理和场景AI代理分别生成设置描述符和场景描述符，实现对媒体内容细节的精准控制。
4. 引入创意简报AI代理整合各描述符，生成综合创意简报，为生成式AI模型提供更精确的生成指令。
5. 采用AI驱动的"actor-critic"模型，通过质量评估引擎生成反馈并迭代改进内容质量，提升生成内容的整体质量。
6. 利用在线学习机制，将质量评估反馈转化为长期学习数据，持续优化AI代理的性能。
7. 该技术可应用于数字广告、品牌宣传等领域，通过自动化生成高质量媒体内容，提高内容创作效率并确保品牌一致性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138053)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311384)**
<br/><br/>

---


<br/>

### 24. 基于像素的可导航模拟环境自动化测试

**Title (EN)**: PIXEL-BASED AUTOMATED TESTING OF A NAVIGABLE SIMULATED ENVIRONMENT  
**Pub. No.**: US20260310593

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Guoqing LIU](https://patents.google.com/?inventor=Guoqing+LIU&country=US&num=100&sort=new), [Li ZHAO](https://patents.google.com/?inventor=Li+ZHAO&country=US&num=100&sort=new), [Tao QIN](https://patents.google.com/?inventor=Tao+QIN&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种用于基于像素的可导航模拟环境自动化测试的计算系统，包括一个或多个处理器，用于在运行时推理阶段执行应用程序测试程序。该程序包含一个经过训练的机器学习模型，用于检测被测应用程序中的错误。通过对象检测模块处理模拟环境的屏幕图像，以确定屏幕图像中是否存在关键对象。如果屏幕图像中存在关键对象，则应用程序测试程序执行对象调查模块，生成调查输入以调查关键对象。如果屏幕图像中不存在关键对象，则应用程序测试程序执行环境探索模块，生成环境探索动作作为模拟用户输入提供给被测应用程序。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489137185_1.jpg)

**Technical Field (技术领域)**:  
软件测试技术领域，具体涉及基于机器学习的自动化测试和模拟环境导航。

**Background (发明背景)**:  
随着虚拟现实、计算机游戏和模拟器等虚拟环境应用程序的规模和复杂性增加，传统的基于人工测试和脚本测试的方法变得耗时且效率低下。依赖程序内部状态信息的测试方法难以适应快速变化的开发周期，且需要深度集成源代码，限制了测试算法的应用范围。

**Summary (发明总览)**:  
本发明提出了一种基于像素的自动化测试系统，通过机器学习模型检测虚拟环境中的错误。系统通过对象检测模块识别关键对象，并使用对象调查模块进行详细分析。如果未检测到关键对象，则调用环境探索模块生成探索动作。该方法无需依赖程序内部状态信息，减少了对源代码的依赖，提高了测试效率和覆盖范围。

**Key Innovation (核心创新)**:  
1. 采用基于像素的图像处理技术，通过对象检测模块识别屏幕图像中的关键对象，无需依赖程序内部状态信息。
2. 使用专门训练的对象检测神经网络，先用公共数据集进行预训练，再针对被测应用程序的屏幕图像进行微调，提高检测准确性。
3. 对象调查模块包含一个经过人工测试会话数据训练的对象调查神经网络，能够生成有效的调查输入以分析关键对象。
4. 环境探索模块采用目标神经网络和预测神经网络，通过蒸馏损失函数训练预测网络，生成探索动作以最大化预期奖励。
5. 目标神经网络随机初始化并固定，其输出作为预测网络的真实标签，确保探索动作的多样性和有效性。
6. 该系统能够自动生成模拟用户输入，无需人工干预，适用于各种虚拟环境应用程序的自动化测试。
7. 应用于虚拟现实、计算机游戏和模拟器等场景，能够提高测试效率，减少人工成本，并提升程序质量。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489137185)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260310593)**
<br/><br/>

---


<br/>

### 25. 基于机器学习语言模型的自主视觉信息查询

**Title (EN)**: Autonomous Visual Information Seeking with Machine-learned Language Models  
**Pub. No.**: US20260310717

**Applicant**: Google LLC  
**Inventor**: [Ahmet Iscen](https://patents.google.com/?inventor=Ahmet+Iscen&country=US&num=100&sort=new), [Alireza Fathi](https://patents.google.com/?inventor=Alireza+Fathi&country=US&num=100&sort=new), [Ziniu Hu](https://patents.google.com/?inventor=Ziniu+Hu&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及生成视觉信息查询响应的系统和方法，包括获取输入数据、通过一个或多个机器学习模型处理输入数据、将数据发送到数据处理工具，并根据输入数据和工具的输出生成响应。机器学习模型可迭代处理数据以生成规划数据，包括对数据处理工具的应用程序接口调用。这些模型可用于规划、推理和生成响应，以获取和生成视觉信息查询的响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489137323_1.jpg)

**Technical Field (技术领域)**:  
人工智能，机器学习，自然语言处理，视觉信息处理

**Background (发明背景)**:  
大型语言模型在语言理解和预测方面表现出色，但在处理特定事实查询时可能遇到困难。此外，语言模型通常未针对非文本或非嵌入数据训练，例如无法有效处理与图像相关的视觉信息查询。理解更广泛的世界信息也具有挑战性，例如识别物体位置或确定图像来源，仅依赖文本搜索可能难以实现。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习语言模型的视觉信息查询系统，通过结合图像数据和文本查询，利用多个数据处理工具进行多阶段处理。系统首先通过机器学习模型生成规划数据，指导数据处理工具进行对象检测和图像分割等操作。随后，基于工具的输出结果，系统进一步生成查询请求以调用搜索引擎等工具，最终生成自然语言形式的响应。本发明通过多工具协作和迭代处理，实现了更智能和精准的视觉信息查询。

**Key Innovation (核心创新)**:  
1. 通过机器学习语言模型生成规划数据，指导数据处理工具的调用顺序和操作，实现多阶段数据处理。
2. 结合图像数据和文本查询，利用对象检测模型生成图像中的对象边界框和分类信息，为后续处理提供基础。
3. 基于对象检测结果，生成针对特定图像区域的查询请求，调用图像搜索引擎等工具获取相关网络资源。
4. 通过机器学习模型对文本数据和工具输出进行联合处理，生成自然语言形式的最终响应，提升查询结果的准确性和可读性。
5. 系统采用迭代规划机制，允许根据前一步的输出动态调整后续处理步骤，实现更灵活的信息查询流程。
6. 机器学习模型通过用户行为数据进行训练，学习用户在不同信息查询任务中的决策序列和偏好，提升系统对用户需求的理解能力。
7. 本发明可应用于智能问答系统、图像识别平台和互联网信息检索等领域，为用户提供更智能和高效的视觉信息查询体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489137323)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260310717)**
<br/><br/>

---


<br/>

### 26. 使用多模态语言模型控制机器人

**Title (EN)**: CONTROLLING ROBOTS USING MULTI-MODAL LANGUAGE MODELS  
**Pub. No.**: US20260307248

**Applicant**: Google LLC  
**Inventor**: [Peter Raymond Florence](https://patents.google.com/?inventor=Peter+Raymond+Florence&country=US&num=100&sort=new), [Danny Michael Driess](https://patents.google.com/?inventor=Danny+Michael+Driess&country=US&num=100&sort=new), [Igor Mordatch](https://patents.google.com/?inventor=Igor+Mordatch&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明涉及用于控制与环境交互的智能体（例如机器人）的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。在一个方面，该方法包括：接收环境的观察数据；接收描述机器人需执行任务的输入文本序列；在嵌入空间中生成输入文本序列的编码表示；在嵌入空间中生成每个观察数据的对应编码表示；生成包含输入文本序列编码表示和每个观察数据编码表示的输入标记序列；使用语言模型神经网络处理输入标记序列。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489133497_1.jpg)

**Technical Field (技术领域)**:  
机器人控制技术；多模态语言模型；机器人任务规划

**Background (发明背景)**:  
机器人规划涉及安排机器人执行任务的物理操作，例如服务机器人完成家务任务。现有的机器人规划系统通常依赖预定义的命令或动作序列，灵活性不足。此外，传统方法难以有效整合来自不同传感器的多模态数据（如文本和图像），限制了机器人的任务执行能力。

**Summary (发明总览)**:  
本发明提出了一种基于多模态语言模型的机器人规划系统，通过处理多模态输入（如文本描述和图像观察）生成机器人执行任务的详细动作序列。该系统利用预训练语言模型的知识，结合多模态提示，实现从任务描述生成高质量规划。与传统方法相比，该系统允许用户使用自然语言控制机器人，减少了控制迭代次数，提高了计算资源利用效率。

**Key Innovation (核心创新)**:  
1. 采用多模态语言模型，将文本描述与图像观察数据融合处理，实现机器人任务规划的语义理解。
2. 通过预训练语言模型引入丰富的语义知识，提升机器人对复杂任务的执行能力。
3. 支持自然语言输入，用户无需记忆特定命令词或短语即可控制机器人。
4. 生成包含多个连续动作的规划序列，减少控制迭代次数，提高计算资源利用效率。
5. 能够整合来自不同传感器模态的数据（如视觉、触觉等），增强机器人对环境的感知能力。
6. 适用于广泛的任务类型，包括家务机器人、工业机器人等，具有较强的通用性。
7. 通过多模态输入生成高质量规划，提升机器人在复杂环境中的任务执行可靠性和效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489133497)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260307248)**
<br/><br/>

---


<br/>

### 27. 自适应用户界面

**Title (EN)**: Adaptive User Interfaces  
**Pub. No.**: US20260310403

**Applicant**: Google LLC  
**Inventor**: [Gaetano Ling](https://patents.google.com/?inventor=Gaetano+Ling&country=US&num=100&sort=new), [Amelia Schladow](https://patents.google.com/?inventor=Amelia+Schladow&country=US&num=100&sort=new), [Matthew Sibigtroth](https://patents.google.com/?inventor=Matthew+Sibigtroth&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明描述了用于自适应用户界面（UI）的系统和相关技术。在某些方面中，具有显示屏、扬声器以及UI管理器的计算设备被配置为输出包括多个图形用户界面（GUI）元素的GUI。UI管理器接收用户对GUI元素的第一选择（例如，触摸输入），并确定与所选GUI元素相关联的一个或多个操作。UI管理器输出这些操作以供显示，并接收用户对操作的选择（例如，语音输入），然后根据第二选择执行该操作。通过这种方式，UI管理器使用户能够通过触摸和语音输入无缝地与计算设备进行交互。这种灵活性提高了用户体验并增加了用户与计算设备交互的效率。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489136974_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及自适应用户界面，包括触摸输入和语音输入的交互方式。

**Background (发明背景)**:  
计算设备（如智能手机、智能手表、平板电脑和计算机）通常使用用户界面（UI）来促进用户与设备之间的交互。现有的UI主要依赖触摸输入和语音输入，但这些方式存在不足：触摸输入需要用户全神贯注并具备精细的运动技能，而语音输入则可能使用不自然的关键词、效率低下且难以发现可用功能。此外，用户通常需要在这两种交互方式之间进行选择，即使某些任务更适合结合使用触摸和语音输入。

**Summary (发明总览)**:  
本发明提出了一种自适应用户界面系统，通过结合触摸和语音输入来优化用户与计算设备的交互方式。该系统允许用户通过触摸选择UI元素，然后通过语音选择具体操作，从而实现无缝切换和交互。这种方法不仅提高了交互的灵活性，还优化了用户操作效率，解决了现有单一交互方式存在的不足。

**Key Innovation (核心创新)**:  
1. 通过UI管理器实现触摸输入和语音输入的无缝结合，用户可以选择最适合的交互方式完成任务。
2. 接收用户对GUI元素的第一选择后，UI管理器动态生成并显示与该元素相关联的操作选项。
3. 支持用户通过语音输入选择具体操作，UI管理器根据选择执行相应功能，实现多模态交互。
4. 优化了交互流程，减少了用户在不同交互方式之间切换的时间和认知负担。
5. 通过动态调整UI元素和操作选项的显示方式，提升了用户对可用功能的发现性。
6. 适用于智能手机、平板电脑等设备，尤其在复杂任务处理和用户操作效率提升方面具有独特价值。
7. 改善了用户与计算设备交互的整体体验，使交互更加直观、高效和灵活。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489136974)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260310403)**
<br/><br/>

---


<br/>

### 28. 用于个性化响应的查询重播在由大语言模型驱动的助手中的应用

**Title (EN)**: QUERY REPLAY FOR PERSONALIZED RESPONSES IN AN LLM POWERED ASSISTANT  
**Pub. No.**: US20260311689

**Applicant**: Google LLC  
**Inventor**: [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new), [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种用于个性化响应的方法包括接收用户发出的自然语言查询，该查询请求助手大语言模型（LLM）的响应，并处理该自然语言查询以从用户之前输入的用于指导助手LLM对相应前次响应进行优化的细化查询日志中识别出与自然语言查询相关的首选细化查询。该方法还包括使用自然语言查询和识别出的相关首选细化查询来提示助手LLM生成对自然语言查询的个性化响应。该方法还包括提供从用户设备输出的个性化响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489138390_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及大语言模型驱动的助手中的个性化响应技术，具体为基于查询重播的个性化响应生成。

**Background (发明背景)**:  
智能设备上的对话助手应用越来越普及，用户通过自然对话与助手互动以完成任务或获取信息。然而，现有技术难以准确识别用户的永久偏好、随时间变化的偏好以及上下文相关的偏好，导致个性化响应效果有限。

**Summary (发明总览)**:  
本发明提出了一种通过查询重播实现个性化响应的方法。其核心思路是分析用户的历史细化查询日志，识别与当前查询相关的首选细化查询，并结合该首选细化查询生成个性化响应。具体实现路径包括：接收用户查询，识别相关细化查询，生成个性化响应并输出。本发明相较于现有技术的主要改进在于通过利用用户的历史细化查询来增强响应的个性化程度，从而提供更贴合用户需求的响应。

**Key Innovation (核心创新)**:  
1. 通过分析用户的历史细化查询日志，识别与当前查询相关的首选细化查询，从而实现更精准的个性化响应。
2. 采用两轮交互机制：首轮生成非个性化响应，次轮结合首选细化查询生成个性化响应，确保响应的准确性和个性化。
3. 将首选细化查询结构化为细化提示，并与用户查询组合成复合提示，用于指导大语言模型生成个性化响应。
4. 通过在细化提示中添加自然语言个性化响应指令，或在基础响应中突出显示、注释或调整格式等方式，增强响应的个性化效果。
5. 为每个细化查询分配置信值，并根据置信值阈值决定是否使用该细化查询来生成个性化响应，提高响应的可靠性。
6. 将用户查询嵌入到向量空间中，并与历史查询嵌入进行相似度计算，以找到最相关的细化查询，提升匹配的准确性。
7. 本发明可应用于智能助手、聊天机器人等产品中，为用户提供更贴合个人偏好和需求的个性化服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489138390)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311689)**
<br/><br/>

---


<br/>

### 29. 使用电致变色面元选择视场区域

**Title (EN)**: FIELD OF VIEW AREA SELECTION USING ELECTROCHROMIC FACETS  
**Pub. No.**: US20260309999

**Applicant**: GOOGLE LLC  
**Inventor**: [Daniel Adema](https://patents.google.com/?inventor=Daniel+Adema&country=US&num=100&sort=new), [Shreyas Potnis](https://patents.google.com/?inventor=Shreyas+Potnis&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
为了增加头戴式显示器（HWD）的视场（FOV）区域，该HWD包括一个光学引擎，用于向光导发射代表一个或多个图像的显示光。此外，HWD包括具有一个或多个电致变色面元的电致变色反射器。这些电致变色面元被配置为根据其各自的状态引导显示光，使得显示光沿着光导中的多个路径之一传播。通过增加显示光在光导中传播的路径数量，FOV区域得以增加。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489136531_1.jpg)

**Technical Field (技术领域)**:  
头戴式显示技术；
电致变色光学系统；
视场扩展技术

**Background (发明背景)**:  
现有头戴式显示器通常通过将光束从投影仪耦合到光导的入射器来向用户显示图像。光束在光导内部通过全内反射传播，直到被出射器引导出光导并朝向用户，从而在HWD的视场区域中呈现图像。为了增加用户的视场区域，一些HWD使用能够提供更多角度光束的投影仪，但这会增加投影仪的尺寸和功耗，从而增加HWD的整体尺寸并影响用户体验。

**Summary (发明总览)**:  
本发明提出了一种通过电致变色反射器增加头戴式显示器（HWD）视场区域的技术。HWD包含一个光学引擎，用于发射显示光，并通过光导内的电致变色面元控制显示光的传播路径。电致变色面元根据其状态选择不同的传播路径，从而增加显示光在光导中的传播路径数量，实现视场区域的扩展。这种方法避免了使用更大的光学引擎或扫描镜，从而减小了HWD的尺寸并提升了用户体验。

**Key Innovation (核心创新)**:  
1. 采用电致变色面元作为光路控制器，通过改变其状态（反射或透射）来引导显示光传播路径。
2. 在光导内部集成电致变色反射器，使其能够动态调整显示光的传播路径，从而增加视场区域。
3. 通过控制电致变色面元的状态，实现显示光在多个路径上的选择性传播，扩展了HWD的视场覆盖范围。
4. 使用镜面控制电路根据用户视线实时调整电致变色面元的状态，优化显示效果并提升用户体验。
5. 将电致变色面元与反射面元结合，通过透射和反射的组合实现更复杂的视场区域控制。
6. 该技术避免了使用更大的光学引擎或扫描镜，从而减小了HWD的尺寸并降低了功耗。
7. 应用于增强现实（AR）或虚拟现实（VR）头戴式显示器，能够提供更宽广的视场区域，提升沉浸感和视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489136531)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260309999)**
<br/><br/>

---


<br/>

### 30. 设备端机器学习平台

**Title (EN)**: ON-DEVICE MACHINE LEARNING PLATFORM  
**Pub. No.**: US20260311067

**Applicant**: Google LLC  
**Inventor**: [Hrishikesh Aradhye](https://patents.google.com/?inventor=Hrishikesh+Aradhye&country=US&num=100&sort=new), [Wolfgang Grieskamp](https://patents.google.com/?inventor=Wolfgang+Grieskamp&country=US&num=100&sort=new), [Daniel Ramage](https://patents.google.com/?inventor=Daniel+Ramage&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明提供了一种设备端机器学习系统和方法。该平台支持设备端预测、训练、数据收集等功能。平台包含一个上下文提供模块，可将上下文特征安全注入训练样本和/或用于生成预测/推理的客户端输入数据中。平台支持集中化的训练样本收集、模型训练，并可作为服务向应用程序或其他客户端提供机器学习模型的使用。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489137707_1.jpg)

**Technical Field (技术领域)**:  
机器学习领域，具体涉及设备端机器学习平台和模型管理技术。

**Background (发明背景)**:  
近年来，机器学习被广泛应用于提升计算设备的服务质量。传统方案通常在服务器端集中收集训练数据并训练模型，用户设备需通过网络传输数据以获取推理结果。这种方式存在数据安全风险、网络流量增加和延迟问题。某些应用虽然内置了机器学习模型，但这种架构实现复杂且资源消耗大。

**Summary (发明总览)**:  
本发明提出了一种设备端机器学习平台，通过在设备本地集中管理训练数据和模型，提供了预测、训练和数据收集等机器学习功能。平台通过API接口与应用程序交互，支持上下文特征的安全注入，并提供集中化的模型训练和数据管理服务。这种架构避免了数据传输风险，降低了网络负载，并简化了应用开发流程。

**Key Innovation (核心创新)**:  
1. 实现了设备端机器学习平台，通过本地化处理数据来避免网络传输风险，提升数据安全性和处理效率。
2. 提供了上下文提供模块，可将设备上下文特征安全注入训练样本和输入数据中，提高模型预测的准确性和相关性。
3. 设计了集中化的示例数据库，支持多应用的数据收集和管理，并提供灵活的存储选项参数配置。
4. 通过预测API接口，应用程序可方便地调用设备端机器学习模型进行推理，无需自行实现模型管理。
5. 平台支持模型缓存机制，可重复利用已下载的预测计划和参数，优化资源使用效率。
6. 提供了训练数据收集API，应用程序可在线补充和管理训练样本，支持动态更新训练数据集。
7. 该平台可应用于移动设备上的智能应用开发，如个性化推荐、图像识别等场景，显著提升应用智能化水平并降低开发复杂度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489137707)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260311067)**
<br/><br/>

---


<br/>

### 31. 虚拟环境中流媒体内容提供者的多模态定位

**Title (EN)**: MULTI-MODAL LOCALIZATION OF STREAMING CONTENT PROVIDERS IN A VIRTUAL ENVIRONMENT  
**Pub. No.**: US20260310282

**Applicant**: GOOGLE LLC  
**Inventor**: [Ruofei Du](https://patents.google.com/?inventor=Ruofei+Du&country=US&num=100&sort=new), [David Kim](https://patents.google.com/?inventor=David+Kim&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
一种在虚拟环境中渲染移动设备图像的技术，包括结合深度图像、超宽带（UWB）信号和惯性测量单元（IMU）信号来跟踪移动设备的位置和方向。深度图像可通过头戴式显示器（HMD）获取的RGB图像生成。UWB和IMU信号由HMD生成，但在某些实现中，UWB和IMU信号也可由移动设备生成。在一些实现中，深度图像足以跟踪移动设备的位置和方向。在一些实现中，UWB和IMU信号的组合足以跟踪移动设备的位置和方向。在一些实现中，结合深度图像...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-10/US489136842_1.jpg)

**Technical Field (技术领域)**:  
虚拟现实技术领域，具体涉及虚拟环境中移动设备的多模态定位与交互。

**Background (发明背景)**:  
虚拟现实系统通过生成虚拟环境让用户与其中的对象进行交互。传统VR头显使用外部标记（如二维码）来跟踪移动设备的位置和方向，但这种方法限制了设备在日常使用中的便利性，且精度不足以支持阅读文本或游戏等应用。本发明旨在解决无需外部标记即可实现高精度定位的技术难题。

**Summary (发明总览)**:  
本发明提出了一种在虚拟环境中精确定位和渲染移动设备图像的方法，通过结合深度图像、UWB信号和IMU信号进行多模态跟踪。该方法利用机器学习引擎处理不同速率的传感器数据，输出移动设备在虚拟环境中的位置和方向值，从而实现虚拟对象的高精度渲染。该方案无需外部标记，通过多模态数据融合实现自校准，提升了跟踪精度。

**Key Innovation (核心创新)**:  
1. 采用多模态传感器数据融合技术，结合深度图像、UWB信号和IMU信号进行移动设备定位。
2. 通过机器学习引擎处理不同速率的传感器数据（深度图像30Hz、IMU信号100Hz、UWB信号10Hz），实现高精度位置和方向估计。
3. 利用HMD获取的RGB图像生成深度图像，并通过机器学习模型将其转换为适用于定位的深度数据。
4. 支持移动设备与虚拟对象的高精度交互，例如将移动设备作为虚拟游戏中的球拍使用。
5. 实现用户手指在移动设备附近的精确定位和交互，例如在距离设备2厘米内进行触控操作。
6. 通过多模态数据融合实现自校准，提升跟踪精度，无需依赖外部标记。
7. 应用于虚拟现实中的移动设备交互场景，使用户能够在佩戴HMD时无缝使用移动设备进行阅读、游戏等操作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489136842)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260310282)**
<br/><br/>

---


<br/>

### 32. 偏振敏感生物特征监测

**Title (EN)**: POLARIZATION SENSITIVE BIOMETRIC MONITORING  
**Pub. No.**: US20260305947

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Mantas Zurauskas](https://patents.google.com/?inventor=Mantas+Zurauskas&country=US&num=100&sort=new), [Robert Dale Cavin](https://patents.google.com/?inventor=Robert+Dale+Cavin&country=US&num=100&sort=new)  
**Publication Date**: 08.10.2026

**Abstract**:  
本发明公开了一种方法，包括捕获从皮肤反射的光，并检测反射光中的偏振光信号。该方法还包括分析检测到的偏振光信号，检测偏振光信号中的镜面反射光分量和/或漫反射光分量，并根据对镜面反射光分量和/或漫反射光分量的分析来确定生物特征测量值。本发明还公开了其他各种方法、系统以及计算机可读介质。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
生物特征识别技术领域，具体涉及利用偏振光进行皮肤反射光分析以获取生物特征信息的技术。

**Background (发明背景)**:  
生物特征监测技术在现代安全与身份识别领域应用广泛，但传统方法易受环境光干扰且测量精度有限。现有的光学生物特征检测方法通常无法有效区分镜面反射和漫反射成分，导致信号噪声较高。本发明旨在通过分析偏振光信号中的不同光成分来提高生物特征测量的准确性和可靠性。

**Summary (发明总览)**:  
本发明提出了一种基于偏振光的生物特征监测方法，通过捕获并分析皮肤反射光的偏振特性来获取生物特征信息。该方法通过分离镜面反射光和漫反射光成分，分别分析其特征，从而实现更精确的生物特征测量。与传统方法相比，本发明能够有效减少环境光干扰，提高测量精度和稳定性。

**Key Innovation (核心创新)**:  
1. 通过偏振光检测技术，捕获皮肤反射光中的偏振信号，实现对生物特征信息的精确捕捉。
2. 分离并分析反射光中的镜面反射光和漫反射光成分，分别提取其特征以提高信号质量。
3. 采用偏振分析算法，区分不同光成分的偏振特性，从而减少环境光和表面反射的干扰。
4. 通过对镜面反射光和漫反射光的独立分析，提供更丰富的生物特征数据维度。
5. 该方法可应用于皮肤表面光学特性的高精度测量，如皮肤水分含量、纹理特征等。
6. 在身份识别、医疗监测等领域，该技术能够提供更可靠和稳定的生物特征数据。
7. 相比于传统光学方法，本发明在复杂光照环境下表现出更强的鲁棒性和适应性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US489136421)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260305947)**
<br/><br/>

---



**Total Patents**: 32  
**Last Updated**: 20261011

---

The Patent Scoop Trio
