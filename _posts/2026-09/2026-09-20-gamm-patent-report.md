---
layout: post
title: "其他专利小快报 2026-09-20"
date: 2026-09-20 14:58:59 +0800
categories: 其他
---

**New Patents**: 45  

---


<br/>

### 1. 基于上下文感知的浏览器功能推荐

**Title (EN)**: CONTEXT-AWARE BROWSER FEATURE RECOMMENDATIONS  
**Pub. No.**: US20260277401

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Kyle Matthew MILLER](https://patents.google.com/?inventor=Kyle+Matthew+MILLER&country=US&num=100&sort=new), [Lia Xian JOHANSEN](https://patents.google.com/?inventor=Lia+Xian+JOHANSEN&country=US&num=100&sort=new), [Hariharan RAGUNATHAN](https://patents.google.com/?inventor=Hariharan+RAGUNATHAN&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本系统和方法使网页浏览器能够根据网页内容向用户推荐或呈现功能。这些功能可能包括可执行的各种操作以及用于查看网页内容的不同显示配置，并且可能针对网页上存在的内容类型而特定。此外，当检测到表明意图安排或配置浏览器标签页的触发条件时，这些功能可能会呈现给用户。这些功能可以以瞬态图形元素的形式呈现，以说明该功能。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905156_1.jpg)

**Technical Field (技术领域)**:  
网页浏览器技术领域，具体涉及基于内容感知的用户界面推荐和交互优化。

**Background (发明背景)**:  
网页浏览器是用户访问互联网的重要工具，但传统浏览器在呈现网页内容时缺乏对不同内容类型的针对性优化。
现有浏览器通常以统一的方式显示所有网页内容，未能根据内容类型提供定制化的功能或交互方式。
这导致用户在使用浏览器时可能错过更高效或更合适的浏览选项。
本发明旨在通过提供基于网页内容的智能功能推荐来改善用户体验。

**Summary (发明总览)**:  
本发明提出了一种基于上下文感知的浏览器功能推荐框架。
当用户与浏览器交互（如拖动标签页）时，系统会根据网页内容类型推荐相应的功能或显示配置。
这些推荐以图形元素的形式呈现，用户可以通过拖放操作选择所需功能。
推荐的功能和配置会因网页内容而异，例如视频内容会推荐多媒体播放选项。
系统还会结合用户的历史行为数据进一步优化推荐结果。
这种机制使浏览器能够更智能地预测用户意图并提供更高效的内容呈现方式。

**Key Innovation (核心创新)**:  
1. 基于网页内容类型的智能功能推荐系统，通过分析网页内容类型（如视频、音频、文本等）来推荐相应的操作和显示配置。
2. 交互式用户界面设计，当用户执行特定操作（如拖动标签页）时，动态显示相关功能的图形元素。
3. 瞬态预览功能，在用户将标签页拖动到推荐功能上时，提供即时预览以帮助用户做出选择。
4. 结合用户历史行为数据，对推荐结果进行个性化调整，提高推荐的准确性和用户满意度。
5. 优化计算效率，通过上下文感知和用户行为分析减少不必要的计算资源消耗。
6. 图形元素与动作的动态关联，用户可以通过简单的拖放操作快速应用推荐的功能或配置。
7. 适用于多媒体内容丰富的网页场景，如视频网站、在线教育平台等，为用户提供更便捷的浏览和交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905156)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260277401)**
<br/><br/>

---


<br/>

### 2. 基于人工智能的多模态元素导向分层图形设计系统与方法

**Title (EN)**: AI-BASED SYSTEM AND METHOD FOR MULTIMODAL ELEMENT-ORIENTED, LAYERED GRAPHIC DESIGN  
**Pub. No.**: US20260278871

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Danqing HUANG](https://patents.google.com/?inventor=Danqing+HUANG&country=US&num=100&sort=new), [Ji LI](https://patents.google.com/?inventor=Ji+LI&country=US&num=100&sort=new), [Mingxi CHENG](https://patents.google.com/?inventor=Mingxi+CHENG&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种数据处理系统实现了接收用户请求以在图形设计中布局多模态设计元素；应用第一生成模型根据内容属性将设计元素在初始层和至少两个预定义层中进行分类；应用第二生成模型按顺序处理各层，直到渲染最终合成图像，具体包括：将初始层处理为初始图像，对于每个预定义层：将该层每个设计元素的内容属性和前导图像编码为组合嵌入，将组合嵌入投影以匹配第二生成模型骨干所需的隐藏状态维度，基于组合嵌入预测该层每个设计元素的位置和大小属性，并将该层每个设计元素根据预测的位置和大小属性放置到预定义层上以渲染合成图像，将放置的预定义层叠加在前导图像上作为合成图像，其中前导图像从初始图像开始；将最终合成图像提供给客户端设备；并使客户端设备的用户界面显示最终合成图像。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906774_1.jpg)

**Technical Field (技术领域)**:  
人工智能；图形设计自动化；多模态生成模型

**Background (发明背景)**:  
人工智能有潜力通过自动化提高效率和节省时间，其中图形设计自动化是一个重要领域。现有的基于扩散的文本生成图像技术虽然能改进设计创作，但主要关注视觉元素的生成，且高度依赖人工模板进行布局指导。多模态设计元素的布局（如图像、标题、装饰元素等）是一个复杂且耗时的过程，而现有的AI布局设计方法未能全面考虑所有元素内容。

**Summary (发明总览)**:  
本发明提出了一种基于人工智能的多模态元素导向分层图形设计方法，通过引入分层规划与设计合成阶段，实现对多模态设计元素的智能布局。该方法首先使用生成模型将设计元素分类到不同层中，然后通过逐层处理预测每个元素的位置和大小属性，最终生成包含所有元素内容的完整图形设计。与现有技术相比，本发明能够更全面地考虑元素内容并自动生成布局，无需依赖人工模板。

**Key Innovation (核心创新)**:  
1. 引入了分层规划阶段，通过多模态生成模型（如GPT-4）将多模态设计元素根据内容属性分类到不同层中，例如背景层、核心视觉对象层、文本层等。
2. 采用逐层处理机制，每一层的设计合成都基于当前层和所有前导层的内容属性进行预测，确保最终设计包含所有元素内容的综合考量。
3. 使用视觉编码器和投影器将设计元素的内容属性编码并投影到合适的隐藏状态维度，以支持后续的位置和大小属性预测。
4. 设计合成模型通过预测每个元素的位置和大小属性，生成包含当前层和前导层内容的合成图像，逐步构建最终图形设计。
5. 该方法无需依赖人工模板，能够自动生成符合视觉层次和内容逻辑的图形设计，显著提升设计效率和效果。
6. 适用于多种应用场景，如海报、邀请函、横幅等，能够处理复杂的图形设计任务并生成高质量的输出。
7. 通过整合多模态元素内容，本发明能够生成更具表现力和信息丰富度的图形设计，为创意设计领域提供新的技术手段。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906774)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278871)**
<br/><br/>

---


<br/>

### 3. 部件锁定

**Title (EN)**: Part Retention  
**Pub. No.**: US20260277276

**Applicant**: Tung Yuen LAU  
**Inventor**: [Tung Yuen Lau](https://patents.google.com/?inventor=Tung+Yuen+Lau&country=US&num=100&sort=new), [Shuanghu Zhang](https://patents.google.com/?inventor=Shuanghu+Zhang&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及具有可拆卸部件的设备，例如脚垫或垫片。一个示例包括包含电子组件的外壳以及设置在外壳中的插座。脚组件可设置在插座中。脚组件可包括锁定机构，该锁定机构通过机械方式阻止脚组件从插座中移除，除非受到磁场作用以重新排列锁定机构并解除对脚组件移除的阻挡。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905020_1.jpg)

**Technical Field (技术领域)**:  
本发明属于电子设备领域，具体涉及可拆卸部件的锁定与解锁技术。

**Background (发明背景)**:  
传统上，计算设备等接触各种工作表面的设备通常使用弹性聚合物脚垫或垫片。然而，这些传统脚垫在反复拆卸后容易失去固定力，且难以实现精确的锁定控制。本发明旨在提供一种可重复拆卸且保持高固定力的解决方案。

**Summary (发明总览)**:  
本发明提出了一种可拆卸部件的锁定机制，通过磁力控制锁定和解锁过程。部件默认处于锁定状态，通过磁力触发锁定机构的变化实现解锁。重新安装后，部件会自动锁定，无需额外操作。该方案解决了传统弹性脚垫反复拆卸后固定力下降的问题，并提供了更可靠的锁定控制。

**Key Innovation (核心创新)**:  
1. 采用磁力控制的锁定机制，通过外部磁场触发锁定机构的变化，实现部件的锁定和解锁。
2. 锁定机构默认处于锁定状态，通过弹簧或类似偏置元件提供持续的锁定力，确保部件的高固定性。
3. 使用磁力克服偏置元件的力，使锁定机构从锁定状态切换到解锁状态，从而允许部件拆卸。
4. 重新安装部件后，锁定机构在移除磁力的情况下自动恢复到锁定状态，无需额外操作。
5. 该方案避免了传统弹性脚垫在反复拆卸后固定力下降的问题，提供了更持久的固定性能。
6. 锁定机构的设计允许精确控制锁定和解锁过程，适用于需要频繁拆卸和安装的部件。
7. 该技术可应用于电子设备的外壳、脚垫等部件，提供可靠的固定和便捷的拆卸功能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905020)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260277276)**
<br/><br/>

---


<br/>

### 4. 使用增量去噪分数的图像编辑

**Title (EN)**: IMAGE EDITING USING DELTA DENOISING SCORES  
**Pub. No.**: US20260278879

**Applicant**: Google LLC  
**Inventor**: [Kfir Aberman](https://patents.google.com/?inventor=Kfir+Aberman&country=US&num=100&sort=new), [Amir Hertz](https://patents.google.com/?inventor=Amir+Hertz&country=US&num=100&sort=new), [Daniel Cohen-Or](https://patents.google.com/?inventor=Daniel+Cohen-Or&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及使用增量去噪分数编辑图像的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906782_1.jpg)

**Technical Field (技术领域)**:  
本专利属于图像生成与编辑领域，具体涉及基于神经网络的图像优化和图像翻译技术。

**Background (发明背景)**:  
神经网络被广泛用于图像生成任务，但现有技术如基于扩散模型的评分蒸馏采样（SDS）存在生成结果模糊的问题。
SDS在编辑现有图像时容易导致图像中未编辑部分出现过度模糊。
本发明旨在解决上述问题，通过改进的评分技术实现更精准的图像编辑。

**Summary (发明总览)**:  
本发明提出了一种基于增量去噪分数（DDS）的图像编辑方法。
该方法利用训练好的扩散神经网络，通过比较参考图像-文本对与目标图像-文本对的得分差异来优化图像。
DDS技术能够有效区分编辑区域和未编辑区域，从而在保留源图像特征的同时实现精准编辑。
此外，本发明还提出了一种无需成对训练数据的图像到图像翻译神经网络训练方法，实现了零样本图像翻译。

**Key Innovation (核心创新)**:  
1. 提出了增量去噪分数（DDS）技术，通过比较参考图像-文本对与目标图像-文本对的得分差异来优化图像编辑。
2. DDS技术能够区分编辑区域和未编辑区域，仅对目标文本描述中指定的图像部分进行修改，避免了SDS方法中常见的过度模糊问题。
3. 利用DDS技术，系统可以估计并去除SDS方法中引入的不良梯度方向，从而获得更清晰的梯度用于图像更新。
4. DDS支持无掩码的提示到提示图像编辑，仅通过修改图像的文本描述即可实现精准编辑。
5. 提出了使用DDS训练图像到图像翻译神经网络的方法，无需成对训练数据即可实现零样本图像翻译。
6. 该训练方法适用于单任务和多任务图像翻译神经网络，且支持合成图像和真实图像的混合训练。
7. 本发明可应用于图像编辑和图像翻译领域，尤其适用于需要保留源图像特征并精准修改特定部分的场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906782)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278879)**
<br/><br/>

---


<br/>

### 5. 用于安全传输语音信号的系统和方法

**Title (EN)**: SYSTEM AND METHOD FOR SECURELY TRANSMITTING VOICE SIGNALS  
**Pub. No.**: US20260279371

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Dushyant SHARMA](https://patents.google.com/?inventor=Dushyant+SHARMA&country=US&num=100&sort=new), [Patrick A. NAYLOR](https://patents.google.com/?inventor=Patrick+A.+NAYLOR&country=US&num=100&sort=new), [Chandramouli Shama SASTRY](https://patents.google.com/?inventor=Chandramouli+Shama+SASTRY&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种用于安全传输语音信号的方法、计算机程序产品和计算系统。编码器接收包含第一语音的内容成分和说话人成分的语音信号。使用机器学习处理语音信号的说话人成分以生成说话人嵌入。使用机器学习并基于至少说话人嵌入处理语音信号的内容成分，以生成最小化说话人信息的内容嵌入。内容嵌入被传输到解码器以恢复接收的语音信号。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907318_1.jpg)

**Technical Field (技术领域)**:  
本专利属于语音信号处理领域，具体涉及语音信号的安全传输和隐私保护技术。

**Background (发明背景)**:  
现代语音激活接口和通信软件需要高效压缩语音信号以进行网络或无线电传输。现有的语音编解码器方法主要关注音频信号的压缩效率，而未考虑语音隐私问题。在传输过程中，语音信号可能被截获，导致不仅信号内容被泄露，而且说话人身份也可能被识别。

**Summary (发明总览)**:  
本发明提出了一种通过分离和处理语音信号中的说话人信息和内容信息来增强语音传输安全性的方法。系统通过机器学习技术对接收到的语音信号进行编码，生成去除了说话人信息的内容嵌入，并在传输过程中保护隐私。解码器接收处理后的信号后，重新组合内容信息和说话人信息以恢复语音信号。该方法还支持说话人信息的可选水印和比特流加扰，以确保传输过程中的隐私保护。

**Key Innovation (核心创新)**:  
1. 通过机器学习技术分离语音信号中的说话人信息和内容信息，确保内容嵌入中最小化说话人信息。
2. 在编码过程中对说话人信息进行处理，支持无说话人信息（机器人语音）或特定说话人声音的传输，并在解码时进行逆向语音转换。
3. 提供说话人信息的水印功能，允许在需要时通过水印识别说话人身份，同时支持通过隐式语音转换恢复原始语音信号。
4. 引入比特流加扰组件，通过私有密钥控制，防止中间截获的比特流被轻易解码为可理解的信号。
5. 在训练阶段，系统通过多轮迭代处理，使传输的内容信息中无法推断出说话人身份，从而增强隐私保护。
6. 该方法可应用于智能音箱、语音通信等场景，提供安全可靠的语音传输解决方案。
7. 通过对说话人信息的操控，系统还支持在传输过程中进行语音转换，为隐私保护和语音个性化提供灵活性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907318)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279371)**
<br/><br/>

---


<br/>

### 6. 优化用户交互和大型语言模型任务选择

**Title (EN)**: Optimizing User Interactions and Task Selection for Large Language Models  
**Pub. No.**: US20260278007

**Applicant**: Google LLC  
**Inventor**: [Adam Joshua Bignell](https://patents.google.com/?inventor=Adam+Joshua+Bignell&country=US&num=100&sort=new), [Miguel de Andrés-Clavera](https://patents.google.com/?inventor=Miguel+de+Andr%C3%A9s-Clavera&country=US&num=100&sort=new), [Scott Bradley Huffman](https://patents.google.com/?inventor=Scott+Bradley+Huffman&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及接收文本查询数据，使用机器学习生成的嵌入模型生成文本查询的嵌入表示，并访问由嵌入生成模型为多个文档块生成的多个块嵌入。文档被组织成多个文档子集，获取选定文档子集的数据信息。通过对文本嵌入与选定文档子集内的块嵌入进行相似性搜索，识别出与文本查询语义相似的块嵌入，并将对应的文档块在用户界面中显示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905824_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及大型语言模型技术，具体涉及用户交互优化和任务选择。

**Background (发明背景)**:  
大型语言模型能够执行多种语言任务，如文本简化、生成对立观点、头脑风暴和对话式回答。然而，由于其任务种类繁多，在特定时间点选择合适的任务变得困难。现有的方法难以有效平衡用户需求与模型能力，导致交互效率低下。

**Summary (发明总览)**:  
本发明提出了一种优化用户与大型语言模型交互的方法，通过对用户查询进行语义分析，筛选相关文档子集，并利用相似性搜索定位关键文档块。这些文档块既可以直接展示给用户，也可以作为输入提供给大型语言模型以生成更精准的输出。本发明通过任务选择和语义探索的结合，提升了用户与模型交互的效率和准确性。

**Key Innovation (核心创新)**:  
1. 通过机器学习生成的嵌入模型，将用户查询和文档块转换为语义嵌入表示，实现高效的语义相似性搜索。
2. 将文档组织成多个子集，并根据用户选择进行筛选，缩小相似性搜索的范围，提高处理效率。
3. 在用户界面中直接展示与查询语义相关的文档块，并提供详细的引用信息，方便用户快速获取所需内容。
4. 将识别出的文档块作为输入生成提示语，输入大型语言模型进行处理，从而生成更符合用户需求的语言输出。
5. 支持用户指定特定任务（如简化、总结、生成对立观点等），并利用模型执行相应任务以满足多样化需求。
6. 通过结合语义搜索和任务选择，本发明实现了用户与大型语言模型交互的个性化与智能化。
7. 本发明可应用于智能助手、文档检索系统和对话式AI产品中，为用户提供更精准、高效的信息获取和任务处理体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905824)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278007)**
<br/><br/>

---


<br/>

### 7. 用于扩展现实应用的电子图像稳定方法

**Title (EN)**: ELECTRONIC IMAGE STABILIZATION FOR EXTENDED REALITY APPLICATION  
**Pub. No.**: US20260278950

**Applicant**: Google LLC  
**Inventor**: [Kinjal Ajitkumar Bhavsar](https://patents.google.com/?inventor=Kinjal+Ajitkumar+Bhavsar&country=US&num=100&sort=new), [Chucai Yi](https://patents.google.com/?inventor=Chucai+Yi&country=US&num=100&sort=new), [Fuhao Shi](https://patents.google.com/?inventor=Fuhao+Shi&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种方法，包括使用惯性数据生成网格，该网格表示设备在真实世界环境中的部分区域中的运动，基于图像数据和网格生成稳定图像数据，并基于稳定图像数据生成稳定虚拟数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906860_1.jpg)

**Technical Field (技术领域)**:  
扩展现实技术领域，具体涉及电子图像稳定与运动跟踪结合的软件技术。

**Background (发明背景)**:  
扩展现实（XR）技术旨在增强用户对物理或虚拟世界的感知，并结合引人入胜的数字环境。这些技术通常集成在消费级移动设备中，如智能手机、眼镜和其他可穿戴设备，其用户体验依赖于实时视频捕获和播放。然而，现有技术中通过相机硬件进行电子图像稳定（EIS）和光学图像稳定（OIS）存在不足，尤其是在合并虚拟内容时难以实现理想效果。

**Summary (发明总览)**:  
本发明提出了一种结合电子图像稳定（EIS）和运动跟踪的软件方法，以改进扩展现实（XR）体验中的视频稳定性。通过同步图像数据和惯性数据，在软件中执行EIS和运动跟踪，生成用于生成稳定图像的EIS变形网格数据。该方法利用设备运动数据生成网格，将不稳定图像转换为稳定图像，并将虚拟内容与稳定图像对齐，从而实现虚拟内容在图像上的准确定位。

**Key Innovation (核心创新)**:  
1. 使用惯性数据生成设备运动网格，通过软件实现图像稳定，而非依赖相机硬件。
2. 将惯性测量单元（IMU）数据应用于图像稳定过程，确保用户运动成为稳定化的一个元素。
3. 通过同步图像数据和惯性数据生成EIS变形网格数据，实现视频流的稳定化。
4. 采用可逆矩阵映射图像数据，将不稳定图像转换为稳定图像，同时对齐虚拟内容。
5. 确保虚拟内容与稳定图像使用相同的数据进行稳定化处理，保证虚拟内容在图像上的准确定位。
6. 该方法解决了传统硬件稳定方法中虚拟内容无法准确定位的问题。
7. 应用于AR/XR/VR设备中，可提供更自然、更精准的混合现实体验，尤其在用户移动或设备抖动情况下表现突出。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906860)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278950)**
<br/><br/>

---


<br/>

### 8. 相机中的水平锁定模式

**Title (EN)**: Level Lock Mode on Camera  
**Pub. No.**: US20260281550

**Applicant**: Google LLC  
**Inventor**: [Kun Wang](https://patents.google.com/?inventor=Kun+Wang&country=US&num=100&sort=new), [Li Wei](https://patents.google.com/?inventor=Li+Wei&country=US&num=100&sort=new), [Wei Hong](https://patents.google.com/?inventor=Wei+Hong&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种方法包括基于用户对相机的定位推断用户意图以拍摄水平图像。基于推断出的用户意图，该方法包括使取景器进入水平锁定模式，其中水平锁定模式包括在取景器中显示预览水平图像，且预览水平图像根据相机相对于水平方向的姿态进行旋转。该方法还包括接收指示捕获图像的信号。基于取景器处于水平锁定模式，该方法包括提供捕获的水平图像，其中捕获的水平图像根据相机相对于水平方向的姿态进行旋转。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486909707_1.jpg)

**Technical Field (技术领域)**:  
图像处理技术领域，具体涉及相机取景器的水平锁定功能。

**Background (发明背景)**:  
在拍摄场景照片时，用户可能希望获得水平对齐的图像。然而，由于难以找到参考水平线或相机难以保持稳定，用户难以在整个拍摄过程中维持水平位置。此外，按下快门按钮时的外力可能导致相机位置偏移，从而影响图像质量。现有的图像稳定技术或后期处理方法无法完全解决这一问题。

**Summary (发明总览)**:  
本发明提出了一种通过水平锁定模式来捕获水平图像的方法。在相机取景器处于活动状态时，系统会推断用户意图以拍摄水平图像，并使取景器进入水平锁定模式。在该模式下，预览图像会根据相机姿态进行旋转并显示为水平图像。当接收到捕获图像的信号时，系统会进一步旋转捕获的图像以确保其水平对齐，从而提供更准确的结果预览。

**Key Innovation (核心创新)**:  
1. 通过传感器数据（如重力传感器和陀螺仪）实时计算预览图像的旋转角度，确保取景器中的图像始终处于水平位置。
2. 在取景器中引入水平锁定模式，通过图形锁图标等用户界面元素明确指示当前图像是否已水平对齐。
3. 在用户按下快门或触发自动快门时，系统会进一步旋转捕获的图像以确保其水平对齐，从而解决外力导致的相机位置偏移问题。
4. 通过在取景器中实时显示旋转后的预览图像，为用户提供准确的最终图像预测，提升用户体验。
5. 该方法适用于多种设备，包括手机相机、独立相机以及通过远程设备控制的相机，适应性强。
6. 通过结合硬件传感器和软件算法，实现更精准的水平图像捕获，弥补了传统图像稳定技术的不足。
7. 该技术特别适用于手持拍摄场景，能够有效补偿因手部抖动或按快门时的外力导致的图像倾斜问题。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486909707)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260281550)**
<br/><br/>

---


<br/>

### 9. 用于测量血流量的微型化阻抗体积描记传感器计算设备

**Title (EN)**: Computing Device Having Miniaturized Impedance Plethysmography Sensor for Measuring Blood Flow  
**Pub. No.**: US20260272323

**Applicant**: Google LLC  
**Inventor**: [Seamus David Thomson](https://patents.google.com/?inventor=Seamus+David+Thomson&country=US&num=100&sort=new), [Seobin Jung](https://patents.google.com/?inventor=Seobin+Jung&country=US&num=100&sort=new), [Debanjan Mukherjee](https://patents.google.com/?inventor=Debanjan+Mukherjee&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种用户计算设备，包括一个外壳和一个位于外壳上的阻抗体积描记（IPG）传感器。该IPG传感器配有一对微型化的激励电极和一对微型化的感应电极，整体尺寸适合放置在用户指尖下方。IPG传感器配置为生成指示用户指尖随时间变化的阻抗的IPG数据。用户计算设备还包括一个处理器，用于接收IPG数据，基于IPG数据生成脉动信号以推导用户的血压或血压的替代指标，并基于脉动信号确定用户的血压或血压的替代指标。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486904617_1.jpg)

**Technical Field (技术领域)**:  
生物医学传感器技术领域，具体涉及用于血流测量的微型化阻抗体积描记传感器。

**Background (发明背景)**:  
指尖血流测量是血压研究中的重要领域，但基于光学原理的光电容积描记图（PPG）方法存在信号易受干扰、可靠性不足的问题。
此外，将PPG传感器集成到适合指尖使用的消费电子产品中也面临空间和结构设计的挑战。
现有技术难以在小型化设备中实现准确且稳定的血压测量。
本发明旨在通过生物阻抗传感技术解决上述问题。

**Summary (发明总览)**:  
本发明提出了一种基于微型化阻抗体积描记（IPG）传感器的用户计算设备，用于监测血压。
该设备通过在用户指尖位置部署微型IPG传感器，采集随时间变化的阻抗数据。
处理器基于采集到的数据生成脉动信号，并据此计算用户的血压或血压替代指标。
与现有PPG技术相比，本发明采用生物阻抗方法，在更小的空间内实现了更稳定的血流测量。
该设计特别适用于智能手机、可穿戴设备等消费电子产品。

**Key Innovation (核心创新)**:  
1. 采用四电极IPG传感器设计，包括两个用于注入小交流电的外电极和两个用于测量电压的内电极，实现了精准的阻抗测量。
2. 传感器采用干电极生物阻抗技术，无需导电凝胶即可在指尖获取可靠的脉动信号，适合日常使用。
3. 传感器尺寸微型化，可集成到智能手机侧边按钮等狭小空间内，提供无缝的用户交互体验。
4. 通过在绝缘基板材料上略微抬高电极（数十至数百微米），优化了电极与指尖的接触效果，提高了信号质量。
5. 可选配光学模块（PPG），并将其与IPG电极集成，实现光学和阻抗传感的协同工作，提升测量准确性。
6. 传感器不仅适用于指尖，还可扩展应用于颈部、手腕等具有较深动脉血流的位置，扩展了应用场景。
7. 特别适用于AR/VR头戴设备等可穿戴设备，在有限接触面积下实现可靠的生物信号采集。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486904617)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260272323)**
<br/><br/>

---


<br/>

### 10. 渐进式文本缩放系统与方法

**Title (EN)**: SYSTEMS AND METHODS FOR PROGRESSIVE TEXT ZOOM  
**Pub. No.**: US20260278239

**Applicant**: Google LLC  
**Inventor**: [Eric Aboussouan](https://patents.google.com/?inventor=Eric+Aboussouan&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本技术提供了一种动态、可扩展的方式来调整电子文档和其他数字材料的文本内容的详细程度。该技术对文本应用了缩放概念，可以通过数值衡量文档的详细程度或细节水平。这使得用户能够在阅读时通过用户界面对文本进行"缩放"，从而快速调整显示的细节量，以提供比原始内容更多或更少的细节，从而提高读者高效浏览和理解大型文档的能力。系统可以调整整个文档或文档特定部分的详细程度，并使用经过训练的详细程度分类器来支持摘要生成器。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906078_1.jpg)

**Technical Field (技术领域)**:  
本发明属于文本处理技术领域，具体涉及基于机器学习的文本摘要生成和动态缩放技术。

**Background (发明背景)**:  
随着信息系统的普及，用户可以快速访问大量电子文档，但高效浏览和理解长文本内容仍存在挑战。现有技术如文本摘要工具缺乏上下文敏感性，而交互式电子书和超链接文档等方法也存在功能局限或阅读体验不佳的问题。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的渐进式文本缩放技术，通过训练摘要生成模块实现文本详细程度的动态调整。用户可以通过图形用户界面选择缩放级别，系统将实时生成对应详细程度的文本内容。该技术结合了抽取式和生成式摘要方法，并考虑了上下文和细微差别等因素，以提升阅读体验和理解效率。

**Key Innovation (核心创新)**:  
1. 引入文本"缩放"概念，通过数值化衡量文本详细程度，使用户能够动态调整阅读内容的详细程度。
2. 采用基于神经网络的机器学习模型，结合抽取式和生成式摘要方法，实现文本内容的智能压缩和扩展。
3. 系统可根据用户选择的缩放级别实时生成对应详细程度的文本内容，支持多种缩放方式，如按百分比或字数调整。
4. 在生成新文本时，系统考虑了上下文信息和细微差别因素，如情感分析、模糊语言检测等，以保持文本的准确性和连贯性。
5. 缩放功能可应用于整个文档或特定部分，并支持在保留文档整体布局的同时替换文本内容。
6. 训练过程中使用了特定于章节的特征，以学习不同章节的摘要模式，从而提高摘要的针对性和准确性。
7. 该技术可应用于学术论文、新闻报道、法律文件等场景，为用户提供更高效、更灵活的文本阅读和理解方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906078)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278239)**
<br/><br/>

---


<br/>

### 11. 显示系统热传导带状膜

**Title (EN)**: DISPLAY THERMAL STRAP FILM  
**Pub. No.**: US20260277008

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Jun Young Choi](https://patents.google.com/?inventor=Jun+Young+Choi&country=US&num=100&sort=new), [Kyung Won Park](https://patents.google.com/?inventor=Kyung+Won+Park&country=US&num=100&sort=new), [Zuoqian Wang](https://patents.google.com/?inventor=Zuoqian+Wang&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本公开的显示系统包括一个具有内表面的外壳，以及一个或多个放置在外壳内的显示设备。该显示系统还包括一个柔性散热片，该散热片连接在显示设备的一个表面与外壳的内表面之间，以实现显示设备与外壳之间的热耦合。此外，还公开了其他各种方法、系统以及计算机可读介质。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
显示技术领域，具体涉及显示设备的热管理技术。

**Background (发明背景)**:  
随着显示设备性能的提升，其工作过程中产生的热量也显著增加。
传统的散热方案通常依赖于外壳材料或简单的散热结构，难以满足高效散热的需求。
现有技术中缺乏有效的热耦合解决方案，导致显示设备的热量无法及时散发。
本发明旨在提供一种改进的热管理方案，以解决上述问题。

**Summary (发明总览)**:  
本发明提出了一种用于显示系统的热传导带状膜方案，通过在显示设备与外壳之间设置柔性散热片，实现高效的热耦合。
该方案利用柔性材料的特点，能够适应不同形状和尺寸的显示设备。
相较于传统散热方案，本发明提供了更灵活、更高效的热管理方式。
该设计不仅提升了散热效率，还能减少显示设备的热应力，延长其使用寿命。

**Key Innovation (核心创新)**:  
1. 采用柔性散热片设计，使其能够适应不同形状和尺寸的显示设备，实现更广泛的应用场景。
2. 通过在显示设备与外壳之间建立热耦合路径，有效提升了热传导效率。
3. 使用高导热材料制造散热片，确保热量能够快速从显示设备传导至外壳。
4. 柔性散热片的结构设计使其能够承受反复的弯曲和拉伸，保持长期稳定性。
5. 该方案不仅适用于平面显示设备，还能应用于曲面或异形显示设备，拓展了应用范围。
6. 通过优化散热路径和材料选择，减少了显示设备的热应力，延长了设备的使用寿命。
7. 该技术可应用于智能手机、平板电脑、显示器等消费电子产品，提供更可靠的热管理解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486904726)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260277008)**
<br/><br/>

---


<br/>

### 12. 构建实用型行动项系统

**Title (EN)**: BUILDING A PRAGMATIC ACTION-ITEM SYSTEM  
**Pub. No.**: US20260278496

**Applicant**: Google LLC  
**Inventor**: [Olivier Siohan](https://patents.google.com/?inventor=Olivier+Siohan&country=US&num=100&sort=new), [Kishan Sachdeva](https://patents.google.com/?inventor=Kishan+Sachdeva&country=US&num=100&sort=new), [Joshua Maynez](https://patents.google.com/?inventor=Joshua+Maynez&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种方法包括获取多方通信会话期间多个对话行为的记录，并从记录中提取与多方通信会话结束后预期完成的任务相关联的多个提取型行动项。该方法还包括使用配置为接收从记录中提取的提取型行动项的抽象型行动项识别模型，生成一个或多个抽象型行动项。每个抽象型行动项与一个或多个与同一任务相关联的提取型行动项的相应组相关联。对于每个抽象型行动项，该方法还包括在图形用户界面中呈现与相应抽象型行动项相关的信息。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906360_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及会议记录自动化处理技术，具体为会议行动项的智能识别与生成。

**Background (发明背景)**:  
会议行动项是会议决策信息的核心，用于明确后续步骤，但现有技术仅通过对话的二元分类来识别行动项，未充分利用对话上下文。此外，现有技术缺乏处理训练数据不足的解决方案，导致识别准确性不足。

**Summary (发明总览)**:  
本发明提出了一种智能化的会议行动项管理系统，通过提取和抽象两个阶段处理会议对话记录。系统首先识别对话中的具体行动项，然后通过聚类生成更高级别的抽象行动项，并提供任务摘要和截止日期预测。相较于传统方法，本发明通过上下文理解和智能生成技术提高了行动项识别的准确性和实用性。

**Key Innovation (核心创新)**:  
1. 采用预训练的BERT或扩展的ETC模型进行对话行为分类，精准识别包含行动项的对话内容。
2. 通过抽象型行动项识别模型，将多个提取型行动项聚类成与同一任务相关的组，生成更高级别的抽象行动项。
3. 利用文本生成模型为每个抽象行动项生成简洁的任务摘要，清晰描述待完成任务。
4. 引入截止日期预测模型，根据相关提取型行动项预测任务完成时间，并支持用户反馈以优化预测准确性。
5. 系统支持用户反馈机制，通过用户对任务摘要和截止日期预测的反馈不断优化模型性能。
6. 应用于会议记录自动化处理场景，能够有效减轻会议参与者记录负担，提高会议效率和后续任务执行效率。
7. 独特价值在于结合提取和抽象两个阶段，既保证行动项的准确性，又提供更高级别的任务组织和预测功能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906360)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278496)**
<br/><br/>

---


<br/>

### 13. 通过耳机为多个用户提供内容生成群组自动化助手会话

**Title (EN)**: GENERATING A GROUP AUTOMATED ASSISTANT SESSION TO PROVIDE CONTENT TO A PLURALITY OF USERS VIA HEADPHONES  
**Pub. No.**: US20260279357

**Applicant**: GOOGLE LLC  
**Inventor**: [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new), [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及创建群组自动化助手会话并处理针对群组中包含的用户的请求。多个用户可以表示创建群组的意图，包括选择执行于用户设备上的自动化助手，并提供由用户设备的麦克风捕获的音频数据。作为响应，所选自动化助手处理音频数据并生成响应，通过执行所选自动化助手的设备的一个或多个扬声器提供。此外，履行数据被提供给执行在其他设备上的自动化助手，并且作为响应，接收履行数据的自动化助手生成响应，通过与执行次级自动化助手的设备相关联的扬声器呈现。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907302_1.jpg)

**Technical Field (技术领域)**:  
本专利属于人机交互技术领域，具体涉及群组语音助手会话的创建与管理。

**Background (发明背景)**:  
人机对话可以通过被称为自动化助手（chat bots）的交互式软件应用实现，用户可以通过语音或文本输入与自动化助手进行交互。现有的自动化助手通常在单个设备上运行，处理单个用户的请求。然而，在多人共同参与的场景中，如何协调多个设备上的自动化助手并实现群组级别的交互仍存在不足。本发明旨在解决在群组环境中，多个用户如何通过各自的耳机共享一个自动化助手会话的问题。

**Summary (发明总览)**:  
本发明提出了一种在群组环境中使用自动化助手的方法，通过耳机为多个用户提供内容。多个用户可以加入一个群组会话，其中一个主自动化助手被选为处理所有用户请求的核心助手。主助手处理来自群组中任何用户的请求，并通过相关设备的扬声器提供响应。其他设备上的次级助手接收履行数据，以渲染内容给各自的用户。本发明通过协调多个设备上的自动化助手，实现了群组用户之间的无缝交互和内容共享。

**Key Innovation (核心创新)**:  
1. 通过耳机实现群组自动化助手会话，支持多个用户同时参与并共享一个会话。
2. 主自动化助手被选为处理群组请求的核心助手，能够处理来自任何群组成员的请求。
3. 次级自动化助手接收主助手提供的履行数据，以在各自设备上渲染内容，确保所有用户都能听到响应。
4. 支持用户通过语音指令或特定操作（如按钮点击）显式或隐式地创建群组会话。
5. 能够根据用户位置、接触历史或日历信息智能判断用户创建群组会话的意图。
6. 新用户加入群组会话时，可以接收会话中已发生事件的摘要，确保信息同步。
7. 本发明可应用于虚拟现实环境或元宇宙场景中，通过监测用户虚拟形象的位置来创建群组会话，提供沉浸式协作体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907302)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279357)**
<br/><br/>

---


<br/>

### 14. 使用文本生成图像的机器学习模型生成用户特定内容

**Title (EN)**: User-Specific Content Generation Using Text-To-Image Machine-Learned Models  
**Pub. No.**: US20260278018

**Applicant**: Google LLC  
**Inventor**: [Arash Sadr](https://patents.google.com/?inventor=Arash+Sadr&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明提出了一种使用文本生成图像的机器学习模型来展示内容项的技术。例如，系统可以获取与用户相关的个性化数据以及商家的资产数据。此外，系统可以使用文本生成模型处理用户个性化数据和商家资产数据，以生成一个或多个模型生成的术语。系统还可以使用图像生成模型处理这些模型生成的术语，以生成一个或多个模型生成的图像。系统可以根据这些模型生成的图像确定内容项。随后，系统可以在用户的用户设备的显示屏上展示包含该内容项的图形用户界面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905836_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及人工智能和机器学习领域，具体为基于文本生成图像的内容生成技术。

**Background (发明背景)**:  
图像查询能够提供更定制化的结果，因为图像可以包含无法用简短文字描述的特征。现有的图像生成系统通常使用自由文本输入框来接收文本并生成图像，但用户在使用时可能难以选择合适的词汇。此外，人工智能生成图像的过程可能不直观、开放且耗时。本发明旨在解决用户难以生成符合需求的图像内容的问题。

**Summary (发明总览)**:  
本发明提出了一种基于用户个性化数据和商家资产数据生成用户特定内容的方法。系统首先使用文本生成模型处理用户数据和商家数据，生成定制化的文本术语。然后，这些术语被输入到图像生成模型中，生成符合用户需求的图像内容项。系统允许用户对生成的内容进行修改，并将修改请求发送给商家以更新内容。本发明通过结合用户数据和商家数据，实现了更精准和个性化的内容生成。

**Key Innovation (核心创新)**:  
1. 利用机器学习模型（如大型语言模型）自动生成基于用户个性化数据和商家资产数据的用户特定术语。
2. 将生成的术语输入到文本生成图像模型中，生成符合用户需求的图像内容项。
3. 提供交互式用户界面，允许用户对生成的术语和图像进行修改，并将修改请求发送给商家以更新内容。
4. 结合搜索引擎数据（如时尚知识数据和近期趋势数据）来优化生成的用户特定术语，提高内容的相关性和时效性。
5. 通过数据集生成模型生成多个数据集，用户可以选择特定数据集来搜索不同商家的数据库，以获取相关产品图像。
6. 生成的图像内容项可以包含指向商家产品购买界面的链接，促进用户购买行为。
7. 本发明可应用于电子商务、广告和个性化推荐等领域，为用户提供高度定制化的视觉内容，提升用户体验和商家销售转化率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905836)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278018)**
<br/><br/>

---


<br/>

### 15. 免唤醒词自动化助手响应的抢占式呈现

**Title (EN)**: HOT-WORD FREE PRE-EMPTION OF AUTOMATED ASSISTANT RESPONSE PRESENTATION  
**Pub. No.**: US20260279344

**Applicant**: GOOGLE LLC  
**Inventor**: [Pu-sen Chao](https://patents.google.com/?inventor=Pu-sen+Chao&country=US&num=100&sort=new), [Alex Fandrianto](https://patents.google.com/?inventor=Alex+Fandrianto&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
在自动化助手响应的呈现过程中，如果接收到一个免唤醒词的语音输入且该输入被判定很可能针对自动化助手，则可以选择性地抢占当前响应的呈现。判定语音输入是否针对自动化助手可通过在响应呈现期间对接收到的音频数据执行语音分类操作来实现。基于此判定，当前响应可以被另一个与后续接收到的语音输入相关的响应所取代。此外，用于确定用户与自动化助手对话结束时会话终止时长的持续时间可以基于响应的呈现完成时间动态控制。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907289_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及自动化助手系统的语音交互和响应管理。

**Background (发明背景)**:  
自动化助手通过语音识别和自然语言处理与用户进行对话，但现有技术通常要求用户在使用前明确唤醒助手，这导致交互不够自然，影响用户体验。此外，助手在对话过程中对后续语音输入的响应能力有限，难以实现流畅的连续对话。

**Summary (发明总览)**:  
本发明提出了一种免唤醒词即可抢占式响应用户语音输入的自动化助手技术。通过在助手响应呈现期间实时监听音频输入，并使用语音分类技术判断输入是否针对助手，系统能够在必要时立即中断当前响应并处理新的用户指令。同时，系统能够根据响应的完成时间动态调整会话监测时长，从而优化资源使用并提升交互流畅度。

**Key Innovation (核心创新)**:  
1. 通过免唤醒词语音输入的实时监听和分类，实现自动化助手响应的抢占式呈现，提升交互的自然性和流畅度。
2. 使用基于神经网络的分类器对音频数据进行分类，生成声学和语义特征向量以判断输入是否针对助手。
3. 在助手设备本地或远程服务器上执行语音分类和响应生成操作，灵活适应不同设备配置。
4. 在助手响应呈现期间进行声学回声消除，滤除自身音频输出对语音输入的影响，提高识别准确性。
5. 通过说话人识别技术判断新输入是否来自同一用户，确保交互的连贯性和安全性。
6. 根据响应完成时间动态调整会话监测时长，避免过早或过晚终止会话，优化资源使用。
7. 该技术可应用于智能家居、车载助手等场景，提供更自然和高效的免唤醒词交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907289)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279344)**
<br/><br/>

---


<br/>

### 16. 抓取系统

**Title (EN)**: Gripping System  
**Pub. No.**: US20260273774

**Applicant**: Google LLC  
**Inventor**: [Zack Tokarczyk](https://patents.google.com/?inventor=Zack+Tokarczyk&country=US&num=100&sort=new), [Nathanael Arling Worden](https://patents.google.com/?inventor=Nathanael+Arling+Worden&country=US&num=100&sort=new), [Ryan Schiller](https://patents.google.com/?inventor=Ryan+Schiller&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明主要涉及一种用于抓取不同厚度且处于任意位置或方向的硬盘的抓取系统。该系统包括两个用于夹持硬盘的臂，以及沿每个臂长度方向设置的至少一条传送带，用于将硬盘移向或移离系统。臂通过枢轴连接，以便能够夹持不同宽度的硬盘。传送带在硬盘被夹持后提供更好的控制，通过传送带施加的力可将硬盘固定在位，防止其下垂或移位。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486901153_1.jpg)

**Technical Field (技术领域)**:  
自动化抓取技术领域，具体涉及硬盘抓取与固定系统。

**Background (发明背景)**:  
传统抓取系统在抓取运输包装中的硬盘时存在困难，因为不同制造商的硬盘特征差异较大，例如长度未完全标准化。硬盘在包装中通常部分暴露，位置和方向不可预测。传统抓取器难以牢固抓取硬盘，快速移动时容易导致硬盘在抓取器内下垂。因此，现有抓取系统对硬盘的抓取和固定不可靠。

**Summary (发明总览)**:  
本发明提出了一种新型硬盘抓取系统，通过可枢轴连接的机械臂和传送带设计，实现对不同尺寸硬盘的灵活抓取和固定。该系统通过传感器和摄像头检测硬盘位置和方向，并利用传送带将硬盘沿抓取轴线移动至安全位置。相较于传统抓取系统，本发明提供了更可靠的抓取和固定能力，适应性强，能够处理硬盘在包装中的各种位置和方向。

**Key Innovation (核心创新)**:  
1. 采用可枢轴连接的机械臂设计，使系统能够适应不同宽度的硬盘，并通过传送带提供稳定的夹持力，防止硬盘在抓取过程中移位或下垂。
2. 在每个机械臂上设置至少一条传送带，传送带与臂的内部表面垂直布置，形成抓取通道，确保硬盘在移动过程中保持稳定。
3. 配备多物理场传感器，用于监测系统振动、冲击和温度等状态，并根据预设阈值进行调节，提高系统可靠性和安全性。
4. 集成摄像头和激光测距传感器，用于精确定位硬盘的位置和方向，并通过机械臂的移动实现精准抓取。
5. 设计了多轴运动机构，通过多个移动部件的协同工作，实现机械臂在多个方向上的旋转和移动，以适应不同抓取场景。
6. 包含电流监测传感器，用于检测硬盘是否到达终点挡块，从而判断抓取是否完成。
7. 本系统不仅适用于数据中心或计算环境中的硬盘抓取，还可扩展应用于其他需要精确抓取和固定的应用场景，如自动化生产线等。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486901153)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260273774)**
<br/><br/>

---


<br/>

### 17. 多深度去模糊

**Title (EN)**: Multi-Depth Deblur  
**Pub. No.**: US20260278751

**Applicant**: Google LLC  
**Inventor**: [Leung Chun Chan](https://patents.google.com/?inventor=Leung+Chun+Chan&country=US&num=100&sort=new), [Tongyang Liu](https://patents.google.com/?inventor=Tongyang+Liu&country=US&num=100&sort=new), [Li Wei](https://patents.google.com/?inventor=Li+Wei&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种方法包括从传感器接收图像。基于该图像，确定至少一个包含图像中感兴趣区域的像素区域。进一步确定该至少一个像素区域的深度信息。基于该至少一个像素区域的深度信息，从多个去模糊模型中选择至少一个去模糊模型应用于该至少一个像素区域。应用所选择的至少一个去模糊模型以确定包含该至少一个像素区域的去模糊图像，其中该至少一个像素区域基于深度信息被去模糊。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906640_1.jpg)

**Technical Field (技术领域)**:  
图像处理领域，具体涉及基于深度信息的图像去模糊技术。

**Background (发明背景)**:  
现代计算设备广泛配备图像捕捉功能，但拍摄过程中常出现部分区域失焦的问题。
现有技术通常采用统一的去模糊算法处理图像，可能导致处理后的图像失真或不自然。
本发明旨在解决不同深度区域需要不同去模糊处理的问题。

**Summary (发明总览)**:  
本发明提出了一种多深度去模糊方法，通过对图像中不同感兴趣区域进行深度测量，并根据深度信息选择不同的去模糊模型进行处理。
该方法首先识别图像中的感兴趣区域，然后计算这些区域的深度信息。
基于深度信息，系统从多个去模糊模型中选择合适的模型进行应用，从而实现更自然、更精准的去模糊效果。
相较于传统方法，本发明能够根据不同深度区域的特点进行差异化处理，提升图像的真实感和清晰度。

**Key Innovation (核心创新)**:  
1. 通过识别图像中的感兴趣区域并计算其深度信息，实现对不同区域的差异化处理。
2. 基于深度信息，从多个去模糊模型中选择合适的模型进行应用，确保处理效果更符合实际需求。
3. 采用单流和双流两种去模糊方法，其中双流方法适用于深度值较大的区域，以弥补单传感器信息的不足。
4. 深度信息的获取不仅依赖图像本身，还可结合其他传感器数据（如LIDAR）以提高精度。
5. 系统可处理存储在设备上的图像或实时显示的图像视图，提供更广泛的应用场景。
6. 通过差异化去模糊处理，显著提升图像的自然度和清晰度，尤其适用于包含多个深度层次的复杂场景。
7. 适用于智能手机、相机等设备，可用于人像、风景等多种场景，为用户提供更优质的图像处理体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906640)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278751)**
<br/><br/>

---


<br/>

### 18. 数字助理应用程序与导航应用程序之间的接口

**Title (EN)**: INTERFACING BETWEEN DIGITAL ASSISTANT APPLICATIONS AND NAVIGATION APPLICATIONS  
**Pub. No.**: US20260279347

**Applicant**: GOOGLE LLC  
**Inventor**: [Vikram Aggarwal](https://patents.google.com/?inventor=Vikram+Aggarwal&country=US&num=100&sort=new), [Moises Morgenstern Gali](https://patents.google.com/?inventor=Moises+Morgenstern+Gali&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及在网络计算机环境中多个应用程序之间的接口系统和方法。数据处理系统可以访问导航应用程序，以检索对应于导航应用程序视口中显示的地理区域参考框架内的多个点位置。每个点位置可以具有标识符。数据处理系统可以解析输入音频信号以识别请求和指示词。数据处理系统可以根据从输入音频信号中解析出的指示词和点位置的标识符，在参考框架内识别点位置。数据处理系统可以生成包括所识别点位置的操作数据结构。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907291_1.jpg)

**Technical Field (技术领域)**:  
网络计算机环境中的多应用接口技术，
语音识别与导航应用交互

**Background (发明背景)**:  
在网络计算机环境中，数字助理应用通常依赖服务器处理客户端设备的功能请求。
过多的网络数据传输可能导致设备无法及时处理数据或响应请求。
现有技术中，语音接口与图形用户界面应用的交互存在挑战，特别是在需要减少网络传输的情况下。
本发明旨在解决语音请求与导航应用交互时的网络传输效率问题。

**Summary (发明总览)**:  
本发明提出了一种在网络计算机环境中实现数字助理与导航应用高效交互的方案。
系统通过解析语音输入，识别用户请求和指示词，并基于指示词在导航应用的地理区域中定位目标点。
通过生成操作数据结构并传输至客户端设备，系统能够启动导航应用的导航引导过程。
相较于现有技术，本发明通过优化语音请求处理和减少不必要的数据传输，提高了交互效率和响应速度。

**Key Innovation (核心创新)**:  
1. 通过解析输入音频信号，识别用户请求和指示词，并基于指示词在导航应用的地理区域中精确定位目标点。
2. 利用导航应用提供的参考框架和点位置标识符，结合客户端设备的速度和方向数据，提高定位准确性。
3. 通过语义知识图谱计算点位置标识符与搜索词之间的语义距离，优化目标点的选择过程。
4. 根据辅助词确定视口子区域，并从对应子区域的点位置中选择目标点，提升交互的精准度。
5. 支持连续语音输入处理，通过分析短时间内接收的多个语音信号，进一步细化目标点选择。
6. 生成包含请求类型和目标点的操作数据结构，并传输至导航应用，触发相应的导航引导过程。
7. 本发明可应用于车载导航系统或智能助手，实现更智能的语音导航交互，提升用户体验并减少网络负载。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907291)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279347)**
<br/><br/>

---


<br/>

### 19. 非分数像素位移技术提升像素性能

**Title (EN)**: NON-FRACTIONAL PIXEL SHIFTING TO IMPROVE PIXEL PERFORMANCE  
**Pub. No.**: US20260279237

**Applicant**: GOOGLE LLC  
**Inventor**: [Stuart James Myron Nicholson](https://patents.google.com/?inventor=Stuart+James+Myron+Nicholson&country=US&num=100&sort=new), [Jeffrey Tang Fung Li](https://patents.google.com/?inventor=Jeffrey+Tang+Fung+Li&country=US&num=100&sort=new), [Craig Homer Peters](https://patents.google.com/?inventor=Craig+Homer+Peters&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本文描述了用于减轻显示系统中像素性能差异的非分数像素位移系统和方法。一个示例显示系统包括用于向用户呈现的显示器、包含第一像素和第二像素的像素面板以及像素控制器。第一像素相对于某一标准具有第一性能能力，第二像素相对于该标准具有第二性能能力。像素控制器通过执行以下操作使显示系统呈现帧：在第一子帧期间使第一像素发出的第一光在显示器的像素位置显示，以及在第二子帧期间使第二像素发出的第二光在显示器的像素位置显示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907174_1.jpg)

**Technical Field (技术领域)**:  
显示技术领域，具体涉及像素位移技术。

**Background (发明背景)**:  
数字编码图像可以通过多种设备上的不同类型显示器呈现给观众。然而，由于制造过程中不可避免的挑战，像素面板中的像素性能往往存在显著差异。这种差异在相邻像素之间尤为明显，可能导致显示质量下降和用户体验受损。

**Summary (发明总览)**:  
本发明提出了一种非分数像素位移技术，通过在每帧的不同子帧期间将像素阵列整体位移整数像素距离来改善像素性能。该方法通过在每帧的不同时间段内将性能正常的像素位移到性能欠佳像素的位置，从而减少用户对欠佳像素的感知，提升整体显示效果。这种方法不仅提高了像素均匀性，还减少了欠佳像素的可见性，并可能提高制造良率。

**Key Innovation (核心创新)**:  
1. 通过非分数像素位移技术，将像素阵列在每帧的不同子帧期间整体位移整数像素距离，例如上下左右移动一个或多个像素位置。
2. 在每帧的不同子帧中，将性能正常的像素位移到性能欠佳像素的位置，从而减少用户对欠佳像素的感知。
3. 通过在每帧中交替显示不同像素的光输出，提升特定像素位置的感知性能，例如亮度、效率和色度。
4. 特别适用于微发光二极管（microLED）等对像素性能差异敏感的显示技术，通过减少相邻像素的性能差异来提升显示质量。
5. 提供了一种提高显示系统制造良率的方法，通过减少对欠佳像素的依赖，降低因过多缺陷像素导致的废品率。
6. 该技术可应用于虚拟现实（VR）、增强现实（AR）和其他对像素均匀性和显示质量要求较高的设备。
7. 通过减少欠佳像素的可见性，该技术提升了用户对显示质量的整体感知，尤其在动态画面中效果更为显著。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907174)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279237)**
<br/><br/>

---


<br/>

### 20. 优化选择语言任务以增强与大型语言模型的交互

**Title (EN)**: Optimizing Selection of Language Tasks to Enhance Interactions with Large Language Models  
**Pub. No.**: US20260278290

**Applicant**: Google LLC  
**Inventor**: [Adam Joshua Bignell](https://patents.google.com/?inventor=Adam+Joshua+Bignell&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及获取用户交互信息，包括用户生成的文本查询和从多个可选任务元素中选择的特定任务元素。通过机器学习生成的嵌入模型生成文本查询的文本嵌入，并针对多个文档片段的多个块嵌入执行相似性搜索，以识别与文本查询在语义上相似的文档片段。基于识别出的文档片段，使用大型语言模型处理提示以执行与所选任务元素相关的任务，并获取大型语言模型基于提示处理生成的文本输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906133_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及大型语言模型技术领域，具体涉及用户与大型语言模型交互过程中任务选择和执行的优化技术。

**Background (发明背景)**:  
大型语言模型经过大规模数据集训练，能够执行多种语言任务，如文本简化、生成对立观点、头脑风暴和对话式回答等。然而，由于可执行任务种类繁多，在特定时刻选择合适的任务变得困难。现有的交互方式难以动态用户需求动态调整任务选择，影响了交互效率和用户体验。

**Summary (发明总览)**:  
本发明提出了一种优化用户与大型语言模型交互的方法，通过分析用户输入的文本查询和选择的特定任务元素，利用嵌入模型生成文本嵌入并执行相似性搜索，识别相关文档片段。基于这些片段，系统动态选择并执行最合适的语言任务，从而提升交互效率和用户体验。该方法通过智能化的任务选择机制，使大型语言模型能够更精准地响应用户需求。

**Key Innovation (核心创新)**:  
1. 通过机器学习生成的嵌入模型，将用户文本查询转换为文本嵌入，实现对用户意图的精准表示。
2. 针对多个文档片段的块嵌入执行相似性搜索，识别与用户查询语义相关的文档内容，为任务选择提供依据。
3. 基于识别出的文档片段和用户选择的特定任务元素，动态选择最合适的语言任务，提高任务选择的精准度。
4. 利用大型语言模型处理基于文档片段的提示，执行选定的任务，确保输出结果与用户需求高度相关。
5. 通过用户交互信息的持续获取和分析，实现任务选择的动态调整，适应用户需求的实时变化。
6. 该方法可应用于智能助手、对话系统和内容生成平台等场景，提升人机交互的自然度和效率。
7. 独特价值在于通过智能化的任务选择机制，使大型语言模型能够更高效地服务于用户需求，减少人工干预。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906133)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278290)**
<br/><br/>

---


<br/>

### 21. 用于调节可调镜头的带通孔镜头筒

**Title (EN)**: LENS BARREL WITH VIA FOR ADJUSTING TUNABLE LENS  
**Pub. No.**: US20260276939

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Lidu Huang](https://patents.google.com/?inventor=Lidu+Huang&country=US&num=100&sort=new), [Michael Andrew Brookmire](https://patents.google.com/?inventor=Michael+Andrew+Brookmire&country=US&num=100&sort=new), [Vijay Kumar](https://patents.google.com/?inventor=Vijay+Kumar&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种成像设备包括一个用于固定可调镜头的镜头筒。导电通孔贯穿镜头筒，使得电信号能够调节镜头筒所固定的该可调镜头的光学功率。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486904649_1.jpg)

**Technical Field (技术领域)**:  
相机光学系统，具体涉及集成可调镜头的镜头筒技术。

**Background (发明背景)**:  
可穿戴设备（如头戴式设备）通常包含一个或多个相机，但这些设备尺寸小且对功耗要求严格，因此其光学组件通常较为基础，例如典型的光学组件通常为单一广角镜头，缺乏动态调节焦点的能力。

**Summary (发明总览)**:  
本发明提出了一种集成可调镜头的镜头筒设计，用于小型成像设备，如可穿戴设备。该镜头筒能够在内部光学串联固定普通镜头和可调镜头，并通过内置电极将可调镜头与控制电路连接，实现光学功率的动态调节。相比传统方案，本发明将可调镜头集成到镜头筒内部，简化了光学系统的整体结构，并提高了镜头间的对准精度。

**Key Innovation (核心创新)**:  
1. 镜头筒内部集成了可调镜头和普通镜头，通过光学串联方式排列，实现紧凑型光学系统设计。
2. 内置电极穿过镜头筒，直接连接可调镜头与控制电路板（PCB），确保电信号传输的稳定性和可靠性。
3. 通过集成设计，将可调镜头与镜头筒一体化，避免了传统方案中可调镜头与镜头筒分离导致的复杂对准问题。
4. 镜头筒结构紧凑，适用于小型化设备，如头戴式显示器等对尺寸要求严格的设备。
5. 相比传统方案，本发明减少了光学系统的总长度（沿光轴方向），提升了空间利用率。
6. 该设计可与人工现实系统（如VR、AR、MR）结合使用，为动态光学调节提供支持。
7. 应用于需要快速对焦或光学变焦的成像设备中，能够提升成像质量和用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486904649)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260276939)**
<br/><br/>

---


<br/>

### 22. 通过生成式机器学习模型生成定制化数字地图

**Title (EN)**: Generating a Customized Digital Map Via a Generative Machine-Learned Model  
**Pub. No.**: US20260276401

**Applicant**: Google LLC  
**Inventor**: [Quinn Thuy Tran](https://patents.google.com/?inventor=Quinn+Thuy+Tran&country=US&num=100&sort=new), [Joseph Edwin Johnson, JR.](https://patents.google.com/?inventor=Joseph+Edwin+Johnson%2C+JR.&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种用于生成定制化数字地图的计算系统，包括一个或多个存储器用于存储指令，以及一个或多个处理器用于执行指令以执行操作。操作包括：通过用户界面提供包含多个图形对象的位置的数字地图，这些图形对象与多个地图层中的第一地图层相关联；通过生成式机器学习模型处理输入，以定制与至少一个图形对象相关联的一个或多个特征，从而生成定制化数字地图，该地图描绘了位置，包括具有一个或多个定制特征的至少一个图形对象；并基于定制生成定制地图层。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486904053_1.jpg)

**Technical Field (技术领域)**:  
数字地图生成技术领域，具体涉及基于生成式机器学习模型的定制化地图生成。

**Background (发明背景)**:  
现有技术中，用户计算设备通常需要从服务器下载地图和卫星图像/图块以用于导航应用。尽管存在允许用户自定义地图的API，但服务器渲染定制图块后，用户设备仍需下载这些图块。这种方法消耗大量网络资源（如带宽）。此外，地图定制过程依赖于服务器渲染，限制了实时性和灵活性。

**Summary (发明总览)**:  
本发明提出了一种基于生成式机器学习模型的定制化数字地图生成方法。通过在用户设备上部署生成式模型，用户可以直接输入定制需求，模型将生成包含定制特征的地图部分，并与服务器提供的其他部分无缝融合。该方法减少了网络带宽消耗，提高了地图定制的实时性和灵活性。

**Key Innovation (核心创新)**:  
1. 在用户设备上部署生成式机器学习模型，实现本地化地图定制，减少对服务器渲染的依赖。
2. 通过接收用户输入的语义描述，生成定制化地图区域，例如通过文本查询指定特定对象或特征。
3. 结合设备渲染和服务器渲染，设备生成部分定制地图区域，服务器提供剩余部分，并通过机器学习模型进行平滑和混合。
4. 支持用户选择用户界面元素以生成定制地图层，地图层生成基于用户信息和位置上下文信息。
5. 提供默认图块作为参考，生成式模型基于默认图块和用户输入生成包含定制特征的地图。
6. 支持用户指定在生成定制地图时省略或减少特定内容，例如去除某些地理信息或标记。
7. 应用于导航、虚拟现实和增强现实等领域，为用户提供高度个性化的地图体验，同时降低网络带宽需求。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486904053)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260276401)**
<br/><br/>

---


<br/>

### 23. 定向照明器和具有可切换扩散器的显示装置

**Title (EN)**: DIRECTIONAL ILLUMINATOR AND DISPLAY APPARATUS WITH SWITCHABLE DIFFUSER  
**Pub. No.**: US20260276984

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Sihui He](https://patents.google.com/?inventor=Sihui+He&country=US&num=100&sort=new), [Jacques Gollier](https://patents.google.com/?inventor=Jacques+Gollier&country=US&num=100&sort=new), [Maxwell Parsons](https://patents.google.com/?inventor=Maxwell+Parsons&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种用于显示装置的定向照明器包括一个可切换扩散器，用于调节照明显示面板的光束的发散度。可调节的发散度转化为显示装置视窗处可调节的出瞳尺寸，可与用户眼睛的瞳孔尺寸匹配，从而提供可配置的瞳孔照明。在照明光束的光路中使用可倾斜反射器可以改变视窗处出瞳的位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486904700_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及可调光学设备，具体为用于视觉显示系统的光导，以及光导和视觉显示系统的组件、模块和方法。

**Background (发明背景)**:  
视觉显示设备用于向观众提供图像、视频和数据等信息，广泛应用于娱乐、教育、工程、科学、专业培训、广告等领域。近眼显示设备（NED）通常用于个人用户，如虚拟现实（VR）、增强现实（AR）和混合现实（MR）应用。然而，现有技术中的显示设备往往体积大、重量重且耗电量大，影响用户体验。此外，激光照明容易产生斑点现象，且高度准直的激光束可能导致显示装置的出瞳尺寸减小。

**Summary (发明总览)**:  
本发明提出了一种基于光导的定向照明器，通过可切换扩散器调节光束的发散度，从而优化显示装置的出瞳尺寸和位置，减少斑点现象并提高光利用效率。该照明器可与眼动追踪系统配合，根据用户瞳孔尺寸和位置动态调整照明光束的发散度和方向。本发明通过可切换扩散器和可倾斜反射器的组合，实现了更灵活和高效的照明控制。

**Key Innovation (核心创新)**:  
1. 采用可切换扩散器调节照明光束的发散度，通过控制空间或时间上的振幅或相位延迟，实现对出瞳尺寸和位置的精确控制。
2. 使用可切换扩散器增加照明光束的时间平均发散度，减少斑点现象并提高图像质量。
3. 结合眼动追踪系统，动态调整照明光束的发散度和方向，以匹配用户瞳孔尺寸和位置，提升显示效果和舒适度。
4. 可切换扩散器可包括多种技术实现，如可切换偏振体积全息图、可切换Pancharatnam-Berry相液晶光栅、流体光栅或基于聚合物的表面浮雕光栅结构。
5. 在反射式显示面板的应用中，光导被放置在显示面板和物镜之间，使图像光通过光导和物镜传播至视窗。
6. 通过表面波或体积波声学致动器在光导中形成声波，实现可切换扩散器的功能。
7. 本发明可应用于近眼显示设备，提供更紧凑、高效的照明方案，提升用户体验，尤其适用于虚拟现实、增强现实等应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486904700)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260276984)**
<br/><br/>

---


<br/>

### 24. 无代码开发平台中的人工智能上下文指导用于管理和治理

**Title (EN)**: Artificial Intelligence Contextual Guidance for Administration and Governance in No-Code Development Platforms  
**Pub. No.**: US20260277600

**Applicant**: Google LLC  
**Inventor**: [Shawn Earl Crabtree](https://patents.google.com/?inventor=Shawn+Earl+Crabtree&country=US&num=100&sort=new), [Gabriel Thomas Moothart](https://patents.google.com/?inventor=Gabriel+Thomas+Moothart&country=US&num=100&sort=new), [Chien-Chia Chen](https://patents.google.com/?inventor=Chien-Chia+Chen&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种方法包括获取用户输入交互，该交互选择显示在图形用户界面（GUI）上的第一个图形表示。该方法包括基于用户输入交互检索应用程序定义。应用程序定义包括无代码应用程序的模式和应用程序模板。该方法包括检索与无代码应用程序相关的上下文信息。该方法包括基于应用程序定义和上下文信息生成一个使用提示，以总结无代码应用程序的使用历史。该方法包括基于使用提示生成使用响应。使用响应包括无代码应用程序的使用历史摘要。该方法包括将无代码应用程序的使用历史摘要的第二个图形表示传输到GUI。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905374_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及无代码开发平台的管理和治理领域，具体涉及人工智能驱动的上下文指导技术。

**Background (发明背景)**:  
无代码开发平台的出现使不具备编程技能的用户能够创建和部署应用程序，从而革新了软件开发。然而，这种便捷性也带来了IT治理的挑战。IT管理员难以获取无代码应用程序的可见性，例如其功能和用途模式，这阻碍了有效监督和一致政策的执行。

**Summary (发明总览)**:  
本发明提供了一种基于人工智能的无代码开发平台管理和治理方法。该方法通过用户交互选择无代码应用程序的图形表示，检索应用程序定义和上下文信息，并生成使用提示以总结应用程序的使用历史。基于这些信息，系统生成使用响应并将其以图形方式呈现给用户。本发明通过人工智能模型（如大语言模型）处理数据，提供对无代码应用程序的深入洞察，包括功能总结、使用模式分析和政策建议，从而提升IT治理效率。

**Key Innovation (核心创新)**:  
1. 通过用户交互选择无代码应用程序的图形表示，检索应用程序定义和上下文信息，实现对应用程序的精准识别。
2. 利用应用程序定义和上下文信息生成使用提示，并基于此生成使用响应，提供应用程序使用历史的详细摘要。
3. 引入预训练的人工智能模型（如大语言模型）处理数据，确保对无代码应用程序的复杂逻辑和用途进行准确分析和总结。
4. 提供对无代码应用程序功能的总结，基于配置特征信息生成功能提示，并生成功能响应以描述应用程序的主要功能。
5. 基于策略集和应用策略子集生成策略提示，推荐未应用的政策并自动应用这些政策，或推荐移除不必要的政策。
6. 通过对无代码应用程序相关数据进行转换处理，生成更准确的使用提示，提升治理的自动化和智能化水平。
7. 本专利可应用于企业级无代码平台管理，为IT管理员提供智能化的治理工具，确保应用程序符合安全协议和业务标准，同时优化资源分配和风险控制。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905374)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260277600)**
<br/><br/>

---


<br/>

### 25. 基于分层深度图像的三维对象生成建模

**Title (EN)**: GENERATIVE MODELING OF THREE-DIMENSIONAL OBJECT WITH LAYERED DEPTH IMAGES  
**Pub. No.**: US20260278972

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Haoyu Wu](https://patents.google.com/?inventor=Haoyu+Wu&country=US&num=100&sort=new), [Sunil Sharadchandra Hadap](https://patents.google.com/?inventor=Sunil+Sharadchandra+Hadap&country=US&num=100&sort=new), [Meher Gitika Karumuri](https://patents.google.com/?inventor=Meher+Gitika+Karumuri&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
该系统基于输入的二维图像生成具有分层深度图像的三维模型。在训练过程中，分层深度图像是从现有的三维模型中提取的。系统训练机器学习模型以从物体的输入图像预测多个分层深度图像。系统将生成的多个分层深度图像与为物体提取的分层深度图像进行比较，以在训练期间更新机器学习模型。在推理阶段，系统接收物体的输入图像。系统将机器学习模型应用于输入图像以输出预测的分层深度图像。系统从预测的分层深度图像生成三维模型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906885_1.jpg)

**Technical Field (技术领域)**:  
计算机视觉与三维建模技术领域，具体涉及基于分层深度图像的生成式三维建模。

**Background (发明背景)**:  
传统三维建模方法通常依赖专业设备进行扫描，并由三维艺术家进行后期处理，过程耗时且资源消耗大。现有的三维模型生成方法难以满足虚拟试穿等应用场景对大量三维模型的需求，导致用户体验受限。

**Summary (发明总览)**:  
本发明提出了一种基于分层深度图像的三维模型生成方法，通过机器学习模型从二维图像预测分层深度图像，并生成三维模型。该方法利用分层深度图像作为三维表示形式，显著降低了计算资源消耗，并提高了建模效率。与传统方法相比，本发明能够快速生成高细节度的三维模型，尤其适用于大规模商品目录的虚拟试穿等应用场景。

**Key Innovation (核心创新)**:  
1. 采用分层深度图像作为三维表示形式，通过机器学习模型从二维图像预测多个分层深度图像，简化了三维建模过程。
2. 使用现有三维模型生成训练数据，训练机器学习模型以提高预测精度和三维重建质量。
3. 通过差分渲染技术对生成模型进行微调，进一步优化分层深度图像的预测结果。
4. 相较于传统方法（如NeRF、pi-GAN和DeepSDF），本发明显著降低了训练和推理阶段的计算资源消耗，例如减少了对GPU内存的需求。
5. 利用二维图像空间表示三维数据，实现了内存效率的提升，并能够直接应用先进的二维生成建模技术（如GANs和扩散模型）。
6. 能够在几秒钟内完成三维模型的估计，而传统方法可能需要数小时，显著提高了处理速度。
7. 适用于大规模商品目录的虚拟试穿等应用场景，能够为大量商品快速生成高质量的三维模型，提升用户购物体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906885)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278972)**
<br/><br/>

---


<br/>

### 26. 用户介入的热词/关键词检测

**Title (EN)**: USER MEDIATION FOR HOTWORD/KEYWORD DETECTION  
**Pub. No.**: US20260279349

**Applicant**: GOOGLE LLC  
**Inventor**: [Aleks Kracun](https://patents.google.com/?inventor=Aleks+Kracun&country=US&num=100&sort=new), [Niranjan Subrahmanya](https://patents.google.com/?inventor=Niranjan+Subrahmanya&country=US&num=100&sort=new), [Aishanee Shah](https://patents.google.com/?inventor=Aishanee+Shah&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本文描述了用于改进机器学习模型和用于确定是否启动自动化助手功能的阈值的技术。方法包括：通过客户端设备的一个或多个麦克风接收捕获用户语音的音频数据；使用机器学习模型处理音频数据以生成预测输出，该输出指示音频数据中存在一个或多个热词的可能性；确定预测输出满足次级阈值，该次级阈值比主阈值更少指示音频数据中存在一个或多个热词；在确定预测输出满足次级阈值时，提示用户指示...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907293_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术领域；
自动化助手系统；
机器学习模型优化。

**Background (发明背景)**:  
自动化助手通过语音与用户交互，但为了保护隐私和节省资源，通常只在检测到特定热词后才执行功能。现有的热词检测模型依赖于预设的阈值来触发后续处理，但存在误报和漏报的问题。误报会导致资源浪费，而漏报则会影响用户体验。

**Summary (发明总览)**:  
本发明提出了一种通过自动调整阈值来改进自动化助手功能触发机制的方法。该方法利用客户端设备上的机器学习模型处理音频数据，生成预测输出，并根据预测结果决定是否启动自动化助手功能。通过分析用户界面输入和其他数据，本发明能够判断决策是否正确，并在发现错误时自动调整阈值，从而减少误报和漏报的发生。

**Key Innovation (核心创新)**:  
1. 通过机器学习模型处理音频数据，生成热词存在的概率预测输出。
2. 采用主阈值和次级阈值机制，在次级阈值满足时提示用户确认，提高检测准确性。
3. 根据用户界面输入和其他数据，动态判断决策的正确性，并自动调整阈值以减少误报和漏报。
4. 实现了阈值的自动迭代优化，通过反复调整适应用户行为和环境变化，例如在用户使用噪声设备时降低阈值。
5. 支持对非唤醒词热词模型的阈值调整，例如检测到特定音频（如计时器警报）时执行相应操作。
6. 在检测到错误决策时，基于预测输出与真实输出的比较生成梯度，并使用梯度更新机器学习模型的权重。
7. 该技术可应用于智能家居设备、语音助手系统等场景，提升用户交互的准确性和效率，同时减少资源浪费。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907293)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279349)**
<br/><br/>

---


<br/>

### 27. 柔性金刚石散热片

**Title (EN)**: FLEXIBLE DIAMOND HEAT SPREADER  
**Pub. No.**: US20260282908

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Nazila Dadvand](https://patents.google.com/?inventor=Nazila+Dadvand&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及一种装置，包括在基板上形成的至少一个半导体封装，以及布置在该至少一个半导体封装上的金刚石散热片。基板和金刚石散热片均为柔性。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486900063_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及散热技术领域，具体为柔性金刚石散热片。

**Background (发明背景)**:  
随着电子设备不断向小型化和高性能方向发展，其内部的热负荷显著增加。处理器、电源管理IC、存储模块和射频芯片等半导体组件在工作时会产生大量热量，若热量无法有效管理，将导致设备性能下降、寿命缩短甚至故障。现有的散热片通常采用高平面导热材料，如热解石墨、铜或铝，但这些材料在复杂几何形状或多层结构中的适应性不足。

**Summary (发明总览)**:  
本发明提出了一种柔性金刚石散热片技术，通过在柔性基板上形成金刚石层，并对其表面进行处理以增强附着力，从而实现高导热性和柔性。该散热片可应用于各种电子设备，包括可穿戴设备等复杂几何结构的产品。其主要创新点在于利用金刚石的高导热性和电绝缘性，解决了传统散热片在复杂结构或天线附近应用的限制问题。

**Key Innovation (核心创新)**:  
1. 采用金刚石作为散热材料，利用其高导热性实现高效热传导。
2.在柔性基板上沉积金刚石层，并通过表面处理技术增强其柔韧性，使其能够弯曲而不影响导热性能。
3.通过在金刚石层两侧添加柔性封装层，提供机械支撑并确保其在弯曲时不会损坏。
4.该散热片具有电绝缘性，可靠近天线等敏感组件使用，避免对无线通信造成干扰。
5.封装层与金刚石层的结合通过表面处理工艺实现，确保了良好的附着力和耐用性。
6.该技术适用于可穿戴设备等需要复杂几何形状和柔性设计的电子产品。
7.相较于传统散热片，本发明在保持高效散热的同时，提供了更高的设计灵活性和适应性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486900063)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260282908)**
<br/><br/>

---


<br/>

### 28. 基于偏置转录的语音识别器训练方法

**Title (EN)**: Training Speech Recognizers Based On Biased Transcriptions  
**Pub. No.**: US20260279342

**Applicant**: Google LLC  
**Inventor**: [Dragan Zivkovic](https://patents.google.com/?inventor=Dragan+Zivkovic&country=US&num=100&sort=new), [Ágoston Weisz](https://patents.google.com/?inventor=%C3%81goston+Weisz&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明提供了一种方法，包括接收用户通过用户设备发出的语音命令的偏置转录，该偏置转录被偏置以包含特定于用户的偏置短语集合中的偏置短语。该方法还包括指示在用户设备上执行的应用程序执行由偏置转录指定的语音命令的操作，并接收一个或多个用户行为信号，这些信号是对应用程序执行偏置转录指定的操作的响应。该方法进一步包括基于输入到置信度模型的这些用户行为信号，生成偏置转录的置信度分数作为置信度模型的输出，并根据置信度模型输出的置信度分数，对语音识别器进行训练。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907287_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术领域，具体涉及基于偏置转录的语音识别器训练。

**Background (发明背景)**:  
自动语音识别（ASR）系统广泛应用于移动设备等设备中，使用户能够通过语音命令与设备交互。然而，当用户说出ASR系统未知的独特词汇（如联系人姓名、媒体内容标题或地址）时，ASR系统可能会生成不准确的转录。现有的ASR系统在处理这些独特词汇时存在识别准确率低的问题。

**Summary (发明总览)**:  
本发明提出了一种基于偏置转录的语音识别器训练方法，通过识别语音命令中的特定载体短语，并使用与该载体短语相关的用户特定偏置短语集合对候选转录进行偏置，从而生成更准确的偏置转录。系统根据用户行为信号评估偏置转录的置信度，并使用高置信度的偏置转录对语音识别器进行训练。这种方法能够有效提高语音识别器对用户特定词汇的识别准确率。

**Key Innovation (核心创新)**:  
1. 通过识别语音命令中的特定载体短语（如"呼叫..."、"播放..."等），确定需要偏置的词汇类型，从而实现对用户特定词汇的精准识别。
2. 使用用户特定的偏置短语集合对候选转录进行偏置处理，确保识别结果更符合用户的个性化需求。
3. 基于用户行为信号（如用户是否执行了语音命令指定的操作）生成置信度分数，评估偏置转录的准确性。
4. 只有当置信度分数满足预设阈值时，才将偏置转录与音频数据配对生成个性化训练数据对，用于训练语音识别器，确保训练数据的质量。
5. 偏置模型采用外部语言模型（如神经有限状态转换器），提高偏置处理的效率和准确性。
6. 语音识别器采用端到端模型，结合语言模型，进一步提升识别性能。
7. 本发明可应用于语音助手、语音拨号、媒体播放控制、导航等场景，显著提升用户在使用语音命令时的体验和效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907287)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279342)**
<br/><br/>

---


<br/>

### 29. 自动立体显示系统及其使用方法

**Title (EN)**: AUTOSTEREOSCOPIC DISPLAY SYSTEMS AND METHODS FOR USING THE SAME  
**Pub. No.**: US20260281293

**Applicant**: GOOGLE LLC  
**Inventor**: [Xuejian Li](https://patents.google.com/?inventor=Xuejian+Li&country=US&num=100&sort=new), [Haiwei Chen](https://patents.google.com/?inventor=Haiwei+Chen&country=US&num=100&sort=new), [Steven A. Cholewiak](https://patents.google.com/?inventor=Steven+A.+Cholewiak&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种自动立体显示系统可确定立体图像对，包括左眼图像和右眼图像。该系统可确定用于形成左眼图像的第一组子像素的第一照明参数，以及用于形成右眼图像的第二组子像素的第二照明参数，其中第一照明参数包括在第一组子像素的周边区域降低亮度的第一强度分布，从而减少串扰。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486909424_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及自动立体显示技术，具体涉及减少串扰的像素照明参数优化技术。

**Background (发明背景)**:  
自动立体显示技术通过为观看者的左右眼分别显示立体图像来提供三维深度感知，而无需佩戴特殊头戴设备，如3D眼镜。然而，现有技术存在串扰问题，即一个图像的光线错误地到达另一只眼睛，导致3D图像质量下降。这种问题可能由制造或物理限制、材料中的光学散射等原因引起。

**Summary (发明总览)**:  
本发明提出了一种改进的自动立体显示系统，通过优化像素照明参数来减少串扰问题。该系统通过调整子像素的亮度分布，特别是周边像素的亮度，来降低图像间的光干扰，从而提升3D图像质量。该方法适用于多用户场景，如视频会议，可为不同位置的观看者提供独立的3D视频流。

**Key Innovation (核心创新)**:  
1. 通过调整子像素的照明参数，特别是周边像素的亮度分布，减少立体图像对之间的光串扰。
2. 采用可调节背光技术，为不同位置的观看者提供独立的全分辨率3D视频流。
3. 在多用户场景中，通过优化像素分配，确保每个用户都能从各自视角获得清晰的3D图像。
4. 针对人眼间的区域（interocular region）进行像素照明优化，进一步降低串扰影响。
5. 在视频会议等应用中，通过改进的3D显示技术提升远程参与者的视觉体验，使其更自然逼真。
6. 该技术可应用于多种消费电子产品，包括电视、笔记本电脑、平板电脑和游戏设备。
7. 通过减少串扰，该系统提升了3D显示的视觉质量和观看舒适度，尤其在多用户环境中表现突出。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486909424)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260281293)**
<br/><br/>

---


<br/>

### 30. 与电子表格编程语言中程序合成相关的用户界面

**Title (EN)**: USER INTERFACE(S) RELATED TO SYNTHESIZING PROGRAMS IN A SPREADSHEET PROGRAMMING LANGUAGE  
**Pub. No.**: US20260278259

**Applicant**: GOOGLE LLC  
**Inventor**: [Rishabh Singh](https://patents.google.com/?inventor=Rishabh+Singh&country=US&num=100&sort=new), [Aaron Zemach](https://patents.google.com/?inventor=Aaron+Zemach&country=US&num=100&sort=new), [Chiraag Galaiya](https://patents.google.com/?inventor=Chiraag+Galaiya&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明描述了自动合成包含一个或多个电子表格编程语言函数的程序的技术。方法包括：在电子表格的第一个单元格中接收用户输入；使用该输入作为第一个示例自动合成程序，该程序包含至少一个电子表格编程语言函数，并在执行时生成与第一个示例匹配的输出；确定与第一个单元格相关的至少一个附加单元格；确定显示触发条件是否满足；如果满足显示触发条件，则在每个附加单元格中显示程序对应的输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906099_1.jpg)

**Technical Field (技术领域)**:  
电子表格编程；自动化程序合成；用户界面

**Background (发明背景)**:  
电子表格应用程序通常使用电子表格编程语言处理数据，但用户常需手动输入数据，这既耗时又占用存储资源。
当数据源发生变化时，用户需手动更新所有相关单元格。
非专业用户可能不熟悉或不愿使用电子表格编程语言中的函数来自动获取数据。
现有方法效率低下且难以维护。
本发明旨在解决这些问题，通过自动合成程序来提高效率并减少用户工作量。

**Summary (发明总览)**:  
本发明提出了一种自动合成电子表格程序的方法，通过用户提供的示例自动生成包含电子表格编程语言函数的程序。
该方法首先接收用户输入作为示例，然后自动生成程序并确定相关单元格。
当满足显示触发条件时，程序输出会显示在相关单元格中。
系统通过评估程序复杂度和置信度来优化资源使用。
用户可以接受或拒绝自动合成的程序，并根据反馈调整显示触发条件。

**Key Innovation (核心创新)**:  
1. 通过用户输入的示例自动合成包含电子表格编程语言函数的程序，简化了数据处理流程。
2. 引入显示触发条件机制，根据程序复杂度和置信度决定是否显示自动合成的程序输出，避免使用过于复杂的程序以节省系统资源。
3. 允许用户通过用户界面元素或键盘快捷键接受或拒绝自动合成的程序，提供直观的交互方式。
4. 在用户接受程序后，用程序输出替换用户输入，并使用不同的字体、样式或颜色区分显示结果，提高可读性。
5. 支持基于多个用户输入示例合成程序，扩展了程序的适用性和准确性。
6. 提供用户反馈机制，根据用户交互调整显示触发条件，优化用户体验。
7. 该技术可应用于数据分析和报告生成等场景，通过自动化程序合成提高工作效率并减少人为错误。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906099)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278259)**
<br/><br/>

---


<br/>

### 31. 带隐藏缝线活页铰链的线切割检修面板

**Title (EN)**: FILAMENT CUT ACCESS PANEL WITH CONCEALED SEAM LIVING HINGE  
**Pub. No.**: US20260277278

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Melvine Axel N’DOUMI](https://patents.google.com/?inventor=Melvine+Axel+N%E2%80%99DOUMI&country=US&num=100&sort=new), [Keegan JOHN TRESTER](https://patents.google.com/?inventor=Keegan+JOHN+TRESTER&country=US&num=100&sort=new), [Michael Gordon OLDANI](https://patents.google.com/?inventor=Michael+Gordon+OLDANI&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明公开了一种线切割检修面板，用于移除计算设备机箱上的隐藏检修面板。在制造过程中，线被放置在计算设备纺织覆盖层下方。拉动线的自由端以切割纺织覆盖层，从而允许移除检修面板，使设备内部组件可进行维修或更换。当拉动线以创建检修线时，纺织覆盖层下方的预刻痕引导线的移动，使得纺织覆盖层沿着与检修面板和机箱之间的缝线相对应的特定路径被切割。检修面板可以通过活页铰链铰接到机箱上。活页铰链允许检修面板相对于机箱旋转。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905022_1.jpg)

**Technical Field (技术领域)**:  
计算设备维修技术领域，具体涉及一种用于隐藏检修面板的线切割机制。

**Background (发明背景)**:  
计算设备通常需要检修面板以便授权人员进行维修或更换内部组件。现有技术中，检修面板通常可见且需要工具拆卸，这可能导致设备外观损坏或维修困难。对于纺织覆盖的计算设备，传统的检修方式容易破坏纺织材料的美观和结构完整性。

**Summary (发明总览)**:  
本发明提供了一种隐藏式检修面板解决方案，通过在纺织覆盖层下方预埋线缆，用户只需拉动线缆即可沿着预定义路径切割纺织层，从而移除检修面板。检修面板通过活页铰链与机箱连接，便于打开和关闭。该方案无需特殊工具或专业知识，且对设备外观影响较小，维修后可恢复接近原始的无缝外观。

**Key Innovation (核心创新)**:  
1. 采用隐藏式线切割机制，通过预埋线缆实现对纺织覆盖层的可控切割，确保检修路径精确且外观无明显损坏。
2. 在纺织层下方预刻划引导线，使得线缆切割时能沿着特定路径进行，避免误操作导致的不规则切割。
3. 使用活页铰链连接检修面板与机箱，允许面板以可控角度打开，方便内部组件的维修和更换。
4. 检修后可通过磁铁、粘合剂或卡扣等二次固定方式重新固定检修面板，恢复设备原始外观。
5. 检修面板在未使用时完全隐藏，减少意外开启或损坏的可能性，提升设备整体耐用性和美观性。
6. 该方案适用于纺织覆盖的计算设备，如键盘等，解决了传统检修方式对纺织材料造成的结构性破坏问题。
7. 通过隐藏式设计提升用户体验，即使在无需检修的情况下，用户也无需担心检修面板影响设备外观或使用。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905022)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260277278)**
<br/><br/>

---


<br/>

### 32. 使用生成图像模型的自适应视频会议体验

**Title (EN)**: ADAPTIVE TELECONFERENCING EXPERIENCES USING GENERATIVE IMAGE MODELS  
**Pub. No.**: US20260278869

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Andrew D. WILSON](https://patents.google.com/?inventor=Andrew+D.+WILSON&country=US&num=100&sort=new), [Shwetha RAJARAM](https://patents.google.com/?inventor=Shwetha+RAJARAM&country=US&num=100&sort=new), [Nels NUMAN](https://patents.google.com/?inventor=Nels+NUMAN&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及使用生成图像模型提供自适应视频会议体验。例如，所公开的实施例可以利用生成图像模型的修复和/或图像到图像的风格转换模式来生成视频会议的图像。这些图像可以根据与视频会议相关的提示生成。用户可以叠加在这些生成的图像上，从而呈现出用户处于生成图像模型所创建的环境中的效果。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906769_1.jpg)

**Technical Field (技术领域)**:  
视频会议技术领域，具体涉及利用生成图像模型生成会议背景和用户叠加的技术。

**Background (发明背景)**:  
视频会议是计算设备的重要应用场景之一，参与者通过网络进行音频和/或视频交流。现有的视频会议通常将参与者显示在用户界面的不同区域，或者采用简单的方法将参与者放置在通用空间中，如会议室。这些方法往往使参与者处于陌生且不自然的环境中，导致会议疲劳、用户参与度降低，并阻碍参与者之间的对话流畅性。

**Summary (发明总览)**:  
本发明提出了一种利用生成图像模型提升视频会议体验的技术方案。通过分析参与者的背景信息或用户选择的图像，生成图像模型可以生成适合会议主题的背景图像，并将参与者叠加在这些背景上，从而创造更自然和熟悉的会议环境。该方法利用上下文信息（如用户背景或自然语言提示）来定制会议环境，显著改善了传统视频会议中常见的生硬和不自然的问题。

**Key Innovation (核心创新)**:  
1. 利用生成图像模型的修复功能，根据参与者的背景信息生成融合后的会议背景，解决了传统视频会议中背景生硬的问题。
2. 通过自然语言提示作为额外上下文，生成图像模型能够根据会议主题定制背景图像，提升了会议环境的适应性和沉浸感。
3. 支持用户选择图像作为输入，生成图像模型能够将用户选择的图像转换为适合视频会议的背景，提供个性化的会议环境。
4. 采用图像叠加技术，将参与者叠加在生成的背景图像上，使用户看起来像处于同一个虚拟空间中，增强了参与者的互动体验。
5. 通过对生成图像模型进行微调，使其能够根据不同会议场景生成多样化的背景图像，满足不同会议需求。
6. 该技术可应用于虚拟会议室、远程协作平台等场景，为用户提供更自然、更具沉浸感的视频会议体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906769)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278869)**
<br/><br/>

---


<br/>

### 33. 人工智能系统中的生成式动画引擎

**Title (EN)**: GENERATIVE ANIMATIONS ENGINE IN AN ARTIFICIAL INTELLIGENCE SYSTEM  
**Pub. No.**: US20260278903

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Zeinab KAZEMI ALAMOUTI](https://patents.google.com/?inventor=Zeinab+KAZEMI+ALAMOUTI&country=US&num=100&sort=new), [Fatima Zohra Daha](https://patents.google.com/?inventor=Fatima+Zohra+Daha&country=US&num=100&sort=new), [Andrew John Moroney](https://patents.google.com/?inventor=Andrew+John+Moroney&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明描述了用于在人工智能系统中提供生成式动画管理的方法、系统及计算机存储介质。生成式动画引擎利用大语言模型算法生成动画设计对象，其基于包含用户提示和元提示的双组件输入提示进行操作。元提示指定了动画对象的参数化模式，包括行为动态、时间属性、插值技术及其他属性的约束。操作上，系统访问与生成生成式动画相关的输入，该输入包含用于生成生成式动画的上下文数据。基于输入生成元提示，并基于元提示生成动画对象，动画对象包含计算出的动画参数。动画对象被传递以生成生成式动画。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906809_1.jpg)

**Technical Field (技术领域)**:  
人工智能技术领域，具体涉及生成式动画生成与管理技术。

**Background (发明背景)**:  
传统设计平台依赖手动输入，用户需通过复杂的用户界面手动指定设计元素、动画和过渡效果，这要求用户具备专业技能且耗时。现有AI技术虽能自动化部分设计任务，但动画生成仍依赖预定义模板，缺乏动态适应性和上下文感知能力，难以生成符合用户意图的个性化动画。

**Summary (发明总览)**:  
本发明提出了一种基于人工智能的生成式动画引擎，通过大语言模型处理用户提示和结构化元提示，生成符合设计需求的动态动画。该引擎利用参数化模式定义动画行为、时间和插值等属性，并结合零样本和多样本学习生成动画对象。动画对象无缝集成到设计元素中，实现上下文感知和程序化生成动画，提升了动画生成效率和用户体验。

**Key Innovation (核心创新)**:  
1. 采用双组件输入提示机制，将用户提示与结构化元提示结合，通过元提示定义动画参数化模式，实现对动画行为、时间和插值等属性的精确控制。
2. 利用大语言模型（LLM）生成结构化动画对象（如JSON格式），并通过零样本和多样本学习提供示例输出，指导LLM生成符合设计需求的动画模式。
3. 实施多阶段元提示设计，包括情感基调分析、引导式动画生成和渲染优化，确保动画生成过程符合用户意图并与设计框架无缝集成。
4. 通过上下文驱动的方法分析用户输入中的情感线索和上下文提示，使LLM能够根据语气、事件类型和受众匹配适当的动画风格。
5. 采用情感检测和主题识别技术，将关键词映射到相应的动画风格，例如将"庆祝"、"兴奋"等词映射到高能量动画，将"放松"、"内省"等词映射到简约或舒缓风格。
6. 提供基于文本描述的动画生成方式，降低了用户对动画制作专业技能的要求，使非专业用户也能轻松创建复杂动画。
7. 该技术可应用于在线广告、演示文稿和数字媒体内容创作等领域，为用户提供快速生成高质量、个性化动画的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906809)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278903)**
<br/><br/>

---


<br/>

### 34. 动态深度图像的捕获与编辑技术

**Title (EN)**: TECHNIQUES TO CAPTURE AND EDIT DYNAMIC DEPTH IMAGES  
**Pub. No.**: US20260281298

**Applicant**: Google LLC  
**Inventor**: [Mira Leung](https://patents.google.com/?inventor=Mira+Leung&country=US&num=100&sort=new), [Steve Perry](https://patents.google.com/?inventor=Steve+Perry&country=US&num=100&sort=new), [Fares Alhassen](https://patents.google.com/?inventor=Fares+Alhassen&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明描述了一种计算机实现的方法，包括使用一个或多个摄像头捕获图像数据，其中图像数据包括主图像及其相关深度值。该方法进一步包括将图像数据编码为图像格式。编码后的图像数据包括以图像格式编码的主图像和图像元数据，图像元数据包含一个设备元素，该元素包括指示图像类型的配置文件元素和第一个摄像头元素，其中第一个摄像头元素包括图像元素和基于深度值的深度图。该方法还包括在编码后，将图像数据存储在基于图像格式的文件容器中。该方法还包括使主图像被显示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486909430_1.jpg)

**Technical Field (技术领域)**:  
图像处理技术领域，具体涉及动态深度图像的捕获、编码、存储和编辑。

**Background (发明背景)**:  
随着移动设备和其他智能设备的普及，用户越来越多地使用这些设备捕获包含深度信息的图像。然而，现有技术缺乏对深度图像的统一处理标准，不同设备和应用程序之间的互操作性较差，导致深度图像的编辑和共享受限。此外，现有技术难以在图像编辑过程中有效利用深度信息进行高级操作，如焦点调整和对象分割。

**Summary (发明总览)**:  
本发明提出了一种统一框架，用于捕获、编码、存储和编辑动态深度图像。该方法通过在图像文件中嵌入深度信息和设备元数据，实现了跨设备和跨应用程序的互操作性。用户可以基于深度信息进行高级图像编辑，如焦点调整、对象分割和三维图像生成。本发明通过扩展现有图像格式，使其能够支持深度图像和增强现实图像的存储和操作，从而提升了图像处理的多功能性和灵活性。

**Key Innovation (核心创新)**:  
1. 提出了一个统一的图像编码框架，将主图像、深度图和设备元数据整合到一个文件容器中，实现了跨设备和跨应用程序的互操作性。
2. 通过将深度值转换为整数格式并基于图像格式进行压缩，优化了深度图的存储效率。
3. 引入镜头焦距模型，使用户能够基于目标焦距调整图像焦点，实现动态模糊效果。
4. 支持对主图像进行裁剪和缩放操作，并自动更新深度图以保持深度信息的准确性。
5. 利用多个深度图生成三维图像，并支持用户进行倾斜和平移操作以查看不同视角。
6. 通过深度图生成分割掩码，使用户能够选择和提取图像中的特定对象。
7. 本专利可应用于增强现实、图像编辑和三维成像等领域，为用户提供更丰富的图像处理功能和更自然的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486909430)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260281298)**
<br/><br/>

---


<br/>

### 35. 手持控制器顶部盖板内外部照明源布置以辅助人工现实系统进行位置追踪的装置及其使用方法

**Title (EN)**: ARRANGEMENTS OF ILLUMINATION SOURCES WITHIN AND OUTSIDE OF A DIGIT-OCCLUDED REGION OF A TOP COVER OF A HANDHELD CONTROLLER TO ASSIST WITH POSITIONAL TRACKING OF THE CONTROLLER BY AN ARTIFICIAL-REALITY SYSTEM, AND SYSTEMS AND METHODS OF USE THEREOF  
**Pub. No.**: US20260278966

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Howard Sun](https://patents.google.com/?inventor=Howard+Sun&country=US&num=100&sort=new), [Dustin Tiffany](https://patents.google.com/?inventor=Dustin+Tiffany&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种用于人工现实系统的手持控制器，包括一个顶部盖板，其表面被周界包围。该表面具有一个用户手指放置的遮挡区域，以及一个与遮挡区域分离的不同区域。第一个照明源位于顶部盖板周界的第一位置处，当手持控制器处于第一组姿态之一时，该位置对人工现实系统的摄像头可见。第二个照明源位于顶部盖板周界的第二位置处，当手持控制器处于第二组姿态之一时，该位置对摄像头可见。第三个照明源...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906877_1.jpg)

**Technical Field (技术领域)**:  
人工现实系统领域，具体涉及用于辅助控制器位置追踪的照明源布置技术。

**Background (发明背景)**:  
人工现实系统，如虚拟现实头显及其控制器，通常包括手持控制器，用户通过操控控制器向游戏系统发送指令以控制游戏或模拟。传统控制器在用户操作时可能会遮挡用于位置追踪的某些区域，这会影响追踪精度，可能导致用户体验下降或潜在的安全隐患。

**Summary (发明总览)**:  
本发明提出了一种改进的手持控制器照明源布置方案，通过在控制器顶部盖板的不同区域和周界布置多个照明源，确保在用户操作过程中尽可能多的照明源对摄像头可见。这些照明源将数据传输给人工现实系统的摄像头，使系统能够准确判断控制器的位置。本发明通过优化照明源的位置，最大化其在各种操作姿态下的可见性，同时减少用户手指遮挡的影响，从而提升位置追踪的可靠性和用户体验。

**Key Innovation (核心创新)**:  
1. 在手持控制器顶部盖板的遮挡区域内沿周界设置多个照明源，分别在不同的控制器姿态下对摄像头可见，确保在用户操作过程中至少有一个照明源可见。
2. 在顶部盖板的平坦表面和倾斜表面分别布置照明源，通过多角度布置提高照明源在各种姿态下的可见性。
3. 在控制器的手柄区域设置照明源，进一步增强在复杂操作场景下的追踪稳定性。
4. 通过合理布局照明源的位置，使其在用户手指遮挡某一照明源时，其他照明源仍能保持对摄像头的可见性。
5. 优化照明源在控制器表面的分布，使摄像头能够接收足够的数据进行精确的位置判断。
6. 该设计可应用于虚拟现实游戏控制器等设备，提升人工现实系统对控制器位置的追踪精度和可靠性。
7. 通过减少用户操作时的遮挡影响，本发明能够有效降低因位置判断错误导致的安全风险，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906877)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278966)**
<br/><br/>

---


<br/>

### 36. 使用多模型架构从上下文数据实时生成自然语音音频内容

**Title (EN)**: Real-Time Generation of Natural-Sounding Audio Content From Context Data Using a Multi-Model Architecture  
**Pub. No.**: US20260279336

**Applicant**: Google LLC  
**Inventor**: [Usama Bin Shafqat](https://patents.google.com/?inventor=Usama+Bin+Shafqat&country=US&num=100&sort=new), [Simon Tokumine](https://patents.google.com/?inventor=Simon+Tokumine&country=US&num=100&sort=new), [David Charles Black](https://patents.google.com/?inventor=David+Charles+Black&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明提供了用于从各种输入数据自动生成自然语音音频内容的计算机系统和相关方法。该方法解决了传统机器学习在音频内容生成任务中遇到的多个技术难题，例如音频内容生硬、语气过于夸张、过渡不自然、语调单一以及对话长度受限等问题。这些问题导致生成的对话缺乏吸引力和真实感。此外，本发明通过将音频内容的脚本或大纲生成与自然语音音频内容的生成分离，实现了可扩展的个性化音频内容生成。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907280_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及机器学习领域，具体为基于上下文数据生成自然语音音频内容的技术。

**Background (发明背景)**:  
在自动化音频内容生成领域，如何高效准确地处理大规模、多样化的数据集以生成自然且上下文相关的音频内容是一个重大技术挑战。传统系统在处理大量文本和多模态数据（如视频）时往往面临计算需求高的问题，导致内容生成延迟、错误和效率低下。此外，现有方法生成的音频内容容易出错或缺乏人类语言的细微差别，影响用户体验和内容实用性。

**Summary (发明总览)**:  
本发明提出了一种基于多模型架构的音频内容生成方法，通过分离上下文数据处理和音频生成任务来提高生成效率和音频质量。该方法首先使用一个机器学习模型处理上下文数据生成音频脚本，然后使用另一个更轻量级的模型对脚本进行优化，使其更接近人类语言特征。最后，系统将优化后的脚本转换为自然语音音频内容。本发明通过这种分离式架构实现了实时生成和大规模个性化音频内容生成，同时提升了音频的自然度和互动性。

**Key Innovation (核心创新)**:  
1. 采用多模型架构，将音频脚本生成和自然语音音频生成分离，从而减少实时计算资源消耗并提高生成效率。
2. 使用第一个机器学习模型处理大规模上下文数据生成初始脚本，该模型可离线运行以优化性能。
3. 第二个机器学习模型对初始脚本进行优化，增加人类语言特征，如语音、语调和情感表达，使其更自然。
4. 第二个模型可进行在线推理，并可基于用户偏好进行微调，以生成个性化的音频内容。
5. 系统支持实时用户交互，用户可以通过命令或问题动态影响音频内容生成，提高互动性和用户体验。
6. 第二个模型可使用包含不流畅语言特征的训练数据集进行微调，以生成更接近人类对话的音频内容。
7. 该技术可应用于虚拟学习环境、互动播客、体育解说和自动化新闻报道等领域，为用户提供高质量的自然语音音频内容。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907280)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279336)**
<br/><br/>

---


<br/>

### 37. 多字符键输入机制

**Title (EN)**: INPUT MECHANISM WITH MULTI-CHARACTER KEYS  
**Pub. No.**: US20260277432

**Applicant**: Google LLC  
**Inventor**: [Carlos Andres Moran Madrigal](https://patents.google.com/?inventor=Carlos+Andres+Moran+Madrigal&country=US&num=100&sort=new), [Shumin Zhai](https://patents.google.com/?inventor=Shumin+Zhai&country=US&num=100&sort=new), [Zhi Li](https://patents.google.com/?inventor=Zhi+Li&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种示例方法包括输出图形用户界面，该界面包括：一个包含多个字符键的图形键盘，多个字符键包括二到八个字符键；一个文本编辑区域；以及一个单词建议区域。该方法还包括检测与多个字符键中特定字符键相关联的呈现敏感显示位置处的第一次用户输入。响应于检测到第一次用户输入，确定与特定字符键相关联的第一个字符。该方法还包括在文本编辑区域内显示第一个字符，并在单词建议区域内显示一组建议单词。该方法还包括...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905189_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及多字符键图形键盘输入机制。

**Background (发明背景)**:  
可穿戴设备和移动设备等计算设备使用图形键盘收集用户输入。现有技术中，图形键盘通过抽象层将触摸或指针坐标转换为离散输入事件，并通过查找表将输入事件映射到对应的Unicode字符或命令序列。然而，传统图形键盘通常采用单字符键设计，输入效率较低且占用屏幕空间较大。

**Summary (发明总览)**:  
本发明提出了一种基于多字符键的图形键盘输入方案，通过使用二到八个字符键，每个键对应多个字符来减少键盘占用的屏幕空间。系统通过用户输入检测特定键，并结合解码器预测后续字符以生成候选单词。输入机制支持长按操作和焦点区域切换，允许用户通过输入设备在文本编辑区域和单词建议区域之间切换焦点，从而提高输入效率和用户体验。

**Key Innovation (核心创新)**:  
1. 采用二到八个多字符键设计，每个键对应多个字符，显著减少键盘占用的屏幕空间。
2. 通过检测用户输入位置并结合解码器预测后续字符，生成与特定键相关联的候选单词。
3. 支持长按操作，用户可以通过长按某个键调出该键对应的所有字符，并通过输入设备（如旋钮）选择所需字符。
4. 提供焦点区域切换功能，用户可以通过输入设备在文本编辑区域和单词建议区域之间切换焦点。
5. 实现了字符替换功能，用户可以在文本编辑区域通过焦点区域指示的字符进行替换，并实时更新建议单词。
6. 提高了输入效率，尤其适用于小屏幕设备或需要快速输入的场景。
7. 应用于可穿戴设备、移动设备等小型计算设备，为用户提供更便捷的文本输入方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905189)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260277432)**
<br/><br/>

---


<br/>

### 38. 用于增强现实头戴设备的分布式传感系统

**Title (EN)**: DISTRIBUTED SENSING FOR AUGMENTED REALITY HEADSETS  
**Pub. No.**: US20260278813

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Michael Goesele](https://patents.google.com/?inventor=Michael+Goesele&country=US&num=100&sort=new), [Richard Andrew Newcombe](https://patents.google.com/?inventor=Richard+Andrew+Newcombe&country=US&num=100&sort=new), [Yujia Chen](https://patents.google.com/?inventor=Yujia+Chen&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明公开了一种用于增强现实设备的分布式成像系统。该系统包括与多个空间分布的传感设备通信的计算模块。计算模块基于执行局部特征匹配计算处理来自传感设备的输入图像，以生成相应的第一输出图像。计算模块还基于执行光流对应计算处理输入图像，以生成相应的第二输出图像集。计算模块进一步配置为计算性地组合第一和第二输出图像，以生成第三输出图像。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486906709_1.jpg)

**Technical Field (技术领域)**:  
增强现实技术领域，具体涉及多摄像头成像和分布式传感。

**Background (发明背景)**:  
增强现实系统通常需要处理复杂的三维环境映射，同时面临计算速度、带宽、延迟和内存需求的限制。
对于可穿戴设备，功耗和散热问题进一步限制了设计选择。
现有AR传感系统难以在性能、效率和设备物理约束之间取得平衡。
此外，摄像头等传感器的数量、类型和空间分布的选择也受到工业设计和美学考虑的影响。

**Summary (发明总览)**:  
本发明提出了一种分布式成像系统，通过整合多个空间分布的摄像头和智能计算模块，提升增强现实设备的成像质量。
系统采用局部特征匹配和光流计算相结合的方法，生成高分辨率图像。
通过优化传感器的采样率和触发时序，系统在保持低功耗的同时实现了更精细的图像重建。
该方案特别适用于可穿戴设备，如AR眼镜，在不增加设备体积和重量的情况下提升了成像性能。

**Key Innovation (核心创新)**:  
1. 采用分布式摄像头架构，通过主摄像头和多个辅助摄像头协同工作，实现场景的广角覆盖和高分辨率成像。
2. 利用局部特征匹配和光流计算相结合的方法，通过神经网络编码器和解码器生成高分辨率图像，提升图像细节表现。
3. 应用视差约束优化像素级对应关系计算，确保不同摄像头图像之间的精确对齐，提高图像融合质量。
4. 通过调整辅助摄像头的采样率和触发时序，在保证成像质量的同时降低系统功耗，适应可穿戴设备的需求。
5. 设计了一种基于退化滤波器和注意力机制的图像融合方法，通过多层次特征融合生成更高质量的最终图像。
6. 辅助摄像头采用重叠视野设计，并通过同态变换集计算光流，进一步提升图像重建的准确性和一致性。
7. 该系统可应用于AR眼镜等可穿戴设备，在不增加设备体积和重量的情况下，提供更清晰、更流畅的增强现实视觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486906709)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260278813)**
<br/><br/>

---


<br/>

### 39. 辅助用户与大型语言模型交互的方法

**Title (EN)**: ASSISTING USER(S) IN INTERACTIONS WITH LARGE LANGUAGE MODEL(S)  
**Pub. No.**: US20260277398

**Applicant**: GOOGLE LLC  
**Inventor**: [Xiao Ma](https://patents.google.com/?inventor=Xiao+Ma&country=US&num=100&sort=new), [Ariel Liu](https://patents.google.com/?inventor=Ariel+Liu&country=US&num=100&sort=new), [Quoc Le](https://patents.google.com/?inventor=Quoc+Le&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
本发明涉及一种由一个或多个处理器实现的方法，包括：接收大型语言模型（LLM）的输入提示；生成第一LLM输出，用于生成与输入提示的各个子提示相关联的一组用户界面（UI）元素；基于第一LLM输出，渲染用户设备上的UI元素集；接收基于用户与UI元素集中一个或多个UI元素的交互而产生的进一步用户输入；以及在确定满足一个或多个终止条件时，基于生成可用于生成最终响应的第二LLM输出，生成对输入提示的最终响应；并使最终响应在用户设备上被渲染。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905153_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及人机交互技术，具体涉及大型语言模型与用户界面的集成应用。

**Background (发明背景)**:  
生成模型，特别是大型语言模型（LLM），已被用于处理自然语言内容并生成响应输出。然而，现有技术在处理复杂输入提示时存在不足，例如包含多个子任务或涉及多个实体的提示难以有效处理。此外，传统的基于文本的对话应用在用户交互的灵活性和结构化方面存在局限。

**Summary (发明总览)**:  
本发明通过将用户界面（如图形用户界面）与使用自然语言提示与LLM交互的能力相结合，利用自然语言的灵活性，同时最大化用户界面的结构化和易用性。具体实现包括：将输入提示分解为多个子提示，生成相应的UI元素集供用户交互，并根据用户反馈生成最终响应。本发明相较于现有技术，通过结构化的用户界面和交互式元素，提升了处理复杂输入提示的能力和用户体验。

**Key Innovation (核心创新)**:  
1. 将输入提示分解为多个子提示，并通过LLM生成相应的用户界面元素，实现复杂任务的模块化处理。
2. 提供交互式UI元素（如按钮、选项卡等），使用户能够逐步提供信息并细化任务需求，增强交互的灵活性和准确性。
3. 支持在用户交互过程中动态生成和更新子提示和UI元素，例如通过调用LLM生成新的交互选项或调整现有选项。
4. 引入外部工具或API调用机制，针对特定查询（如天气查询、事实核查等）提供更准确和客观的响应，减少LLM的幻觉问题。
5. 允许用户通过自然语言文本输入提供额外信息，LLM可据此调整子提示和UI元素，确保最终响应充分考虑用户偏好和上下文。
6. 通过限制节点和层数（如限制为一层子提示），简化交互结构，提高系统处理效率和用户理解度。
7. 本发明可应用于智能家居、任务规划、虚拟助手等场景，为用户提供更直观、高效和个性化的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905153)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260277398)**
<br/><br/>

---


<br/>

### 40. 多轴销关节铰链

**Title (EN)**: MULTI-AXIS PIN JOINT HINGE  
**Pub. No.**: US20260277279

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Nicholas Benjamin WENDT](https://patents.google.com/?inventor=Nicholas+Benjamin+WENDT&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
笔记本电脑或平板电脑等计算设备可能使用各种类型的铰链来连接显示组件与键盘组件，或者将支架或其他配件连接到平板电脑上。向用户呈现连续的视觉印象表明计算设备整体质量更高，因此是可取的。本发明公开的多轴销关节铰链既隐藏了铰链的某些部分，又在连接组件之间保持了最小且一致的间隙。铰链包括三个销关节，用于将第一和第二连接件连接到平板和支架上。例如，当每个销关节在铰链的运动范围内旋转时，所有旋转轴都相交于与旋转轴重合的一点。因此，旋转轴保持在固定位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486905023_1.jpg)

**Technical Field (技术领域)**:  
计算设备铰链技术领域，具体涉及多轴销关节铰链设计。

**Background (发明背景)**:  
计算设备通常使用铰链连接其多个组件，例如笔记本电脑的显示屏和键盘，或平板电脑的机身和支架。传统铰链如桶形铰链或连续铰链存在可见的铰链组件和间隙，影响设备整体视觉一致性。隐藏式铰链虽然解决了部分问题，但通常设计复杂且易磨损。本发明旨在提供一种既保持视觉一致性又具备可靠性和耐用性的铰链解决方案。

**Summary (发明总览)**:  
本发明提出了一种多轴销关节铰链，通过三个销关节连接两个连接件和一个旋转轴，实现计算设备组件之间的旋转连接。该铰链设计隐藏了铰链组件，并在运动范围内保持连接组件之间的最小且一致的间隙。其核心思路是采用销关节代替滑动轴承，简化结构并提高可靠性，同时提供与传统隐藏式铰链相当的运动范围。

**Key Innovation (核心创新)**:  
1. 采用三个销关节设计，实现多轴旋转运动，确保旋转轴始终相交于一点，从而保持连接组件的视觉一致性。
2. 使用销关节代替滑动轴承，简化铰链结构，减少零件数量，提高可靠性和耐用性。
3. 铰链设计隐藏了铰链组件，并在运动范围内保持连接组件之间的最小且一致的间隙，提升设备整体视觉品质。
4. 通过将计算设备的一个组件（例如支架）作为铰链机制中的一个连接件，减少零件数量并优化空间利用。
5. 提供至少135度的运动范围，与传统桶形铰链和隐藏式铰链相当，满足多种使用场景的需求。
6. 相较于传统隐藏式铰链，本发明采用更简单的设计，减少了复杂滑动轴承的磨损问题，提升了长期使用可靠性。
7. 该铰链设计适用于笔记本电脑和平板电脑等便携式计算设备，能够在有限空间内提供高质量的旋转连接解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486905023)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260277279)**
<br/><br/>

---


<br/>

### 41. 基于机器学习的头戴设备稳健语音通信方法

**Title (EN)**: Machine Learning Based Robust Voice Communication Via Head-Worn Device  
**Pub. No.**: US20260279329

**Applicant**: Google LLC  
**Inventor**: [Jamie Alexander Zyskowski](https://patents.google.com/?inventor=Jamie+Alexander+Zyskowski&country=US&num=100&sort=new), [Thomás William Inskip, VI](https://patents.google.com/?inventor=Thom%C3%A1s+William+Inskip%2C+VI&country=US&num=100&sort=new), [Naomi Nicole De Ocampo](https://patents.google.com/?inventor=Naomi+Nicole+De+Ocampo&country=US&num=100&sort=new)  
**Publication Date**: 17.09.2026

**Abstract**:  
一种方法包括接收来自麦克风的音频信号，该信号代表由用户发声和环境噪声引起的介质振动。该方法还包括接收来自与用户头部接触的振动传感器的惯性信号，该信号代表由用户发声引起的头部振动。该方法还包括获取代表用户声音的语音嵌入。该方法进一步包括通过机器学习模型基于音频信号、惯性信号和语音嵌入生成合成的波形，该波形代表用户的声音发声且独立于环境噪声。该方法还包括输出合成的波形。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486907273_1.jpg)

**Technical Field (技术领域)**:  
语音通信技术领域，具体涉及基于机器学习的噪声抑制和语音增强技术。

**Background (发明背景)**:  
在嘈杂环境中使用语音通信设备时，环境噪声会干扰用户语音，导致通信质量下降。现有的音频去噪方法在处理时间变化的噪声时效果有限，且可能需要多个传感器或高计算成本。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的语音通信系统，通过头戴设备中的麦克风和振动传感器分别捕捉音频信号和头部振动信号，并结合用户语音的语音嵌入，生成去噪后的合成语音波形。该系统无需依赖文本转语音的中间步骤，能够在保留用户语音特征的同时有效去除环境噪声。相较于传统方法，本发明在噪声抑制和语音保真度方面具有显著优势。

**Key Innovation (核心创新)**:  
1. 利用头戴设备中的骨传导传感器捕捉仅包含用户语音的惯性信号，实现对环境噪声的物理隔离。
2. 通过机器学习模型将音频信号、惯性信号和用户语音嵌入结合，生成高质量的合成语音波形。
3. 语音嵌入模型通过在无噪声环境下采集的语音样本生成用户语音的数值表示，确保合成语音的自然度。
4. 波形合成模型直接映射音频和惯性信号到合成波形，无需依赖文本转语音的中间步骤，保留语音的韵律特征。
5. 系统可针对不同传感器位置和方向训练特定的模型实例，以适应不同头戴设备的硬件特性，提升合成语音质量。
6. 该技术可应用于嘈杂环境中的语音通信，如工厂、演唱会或多人交谈场合，提供清晰可靠的语音通信体验。
7. 通过去除噪声并保留用户语音特征，该系统可提升语音通信的清晰度和可懂度，同时减少用户疲劳。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486907273)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260279329)**
<br/><br/>

---


<br/>

### 42. 使用语言模型进行视觉事件处理

**Title (EN)**: Visual event processing using language models  
**Pub. No.**: US12738060

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Kent V Lam](https://patents.google.com/?inventor=Kent+V+Lam&country=US&num=100&sort=new), [Amey Laxman Gawde](https://patents.google.com/?inventor=Amey+Laxman+Gawde&country=US&num=100&sort=new), [Kevin Roderick Sellon](https://patents.google.com/?inventor=Kevin+Roderick+Sellon&country=US&num=100&sort=new)  
**Publication Date**: 15.09.2026

**Abstract**:  
本发明涉及使用多模态语言模型进行视觉事件处理的系统和方法，包括在第一设备接收代表用户命令的第一用户输入数据，以存储随时间发生的视觉、听觉或其他类型事件的发生情况，该事件与涉及运动、声音或其他可检测物理刺激的物理活动相关联。描述该活动的活动指示符可存储在第一设备中。第一设备的功能可以扩展，以处理来自第二设备传感器的数据。因此，存储在第一设备中的活动指示符可用于处理请求模型从数据中识别活动的第一查询。模型可以确定数据描绘了活动，并生成第一输出（自然语言）。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486646077_1.jpg)

**Technical Field (技术领域)**:  
本发明属于多模态人工智能领域，具体涉及基于语言模型的视觉事件识别与处理技术。

**Background (发明背景)**:  
随着语音接口设备的普及，用户对设备在环境中执行复杂任务的需求日益增加。现有的设备通常只能处理单一类型的数据（如语音或图像），难以实现跨模态的事件识别和处理。本发明旨在解决多设备、多模态数据融合处理的问题，实现对复杂物理活动的智能识别和记录。

**Summary (发明总览)**:  
本发明提出了一种基于多模态语言模型的视觉事件处理方法，通过接收用户命令来记录特定类型事件的发生情况，并利用存储的活动指示符处理跨设备的数据查询。系统能够从多模态数据中识别物理活动，并生成自然语言输出。该方法通过扩展单一设备的功能，实现了对多设备数据的协同处理，提升了事件识别的准确性和效率。

**Key Innovation (核心创新)**:  
1. 实现了多模态数据融合处理，将视觉、听觉及其他物理刺激数据整合到统一的事件识别框架中。
2. 通过用户命令存储活动指示符，允许用户自定义需要记录的事件类型，增强了系统的灵活性和可扩展性。
3. 扩展了单一设备的功能，使其能够处理来自其他设备传感器的数据，实现跨设备协同工作。
4. 利用语言模型从多模态数据中识别物理活动，并生成自然语言描述，提升了人机交互的自然度。
5. 提供了数据查询接口，用户可以通过自然语言请求模型识别特定活动，增强了系统的易用性。
6. 该技术可应用于智能家居、运动监测等领域，例如识别用户的日常活动模式或运动类型。
7. 通过多设备数据融合和自然语言输出，为用户提供更智能、更直观的活动记录和分析体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486646077)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12738060)**
<br/><br/>

---


<br/>

### 43. 具有操作控制的视觉化结构化响应

**Title (EN)**: Visually structured responses with action controls  
**Pub. No.**: US12737370

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Vinayshekhar Bannihatti Kumar](https://patents.google.com/?inventor=Vinayshekhar+Bannihatti+Kumar&country=US&num=100&sort=new), [Rashmi Gangadharaiah](https://patents.google.com/?inventor=Rashmi+Gangadharaiah&country=US&num=100&sort=new), [Manoj Ghuhan Arivazhagan](https://patents.google.com/?inventor=Manoj+Ghuhan+Arivazhagan&country=US&num=100&sort=new)  
**Publication Date**: 15.09.2026

**Abstract**:  
本发明公开了系统和用于智能呈现用户界面的方法，这些用户界面基于对用户意图或需求的判断动态生成。例如，根据用户请求或操作，本发明实施例可以动态生成并向用户呈现一个或多个与用户相关的组件。这些组件可以在提供商网络环境中的任何位置生成和呈现，从控制台或主页引导用户使用服务并/或响应用户查询，到在软件开发服务中为开发者提供代码或其他请求内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486645316_1.jpg)

**Technical Field (技术领域)**:  
人工智能与机器学习领域，具体涉及基于用户意图生成动态用户界面和交互组件的技术。

**Background (发明背景)**:  
机器学习（ML）和人工智能（AI）技术近年来取得了显著进展，特别是大型语言模型（LLMs）能够理解和生成类人文本。然而，现有系统在动态生成用户界面和交互组件时，往往缺乏对用户意图的精准理解和响应能力。这导致用户在使用服务或查询信息时，可能需要经历繁琐的步骤或面对不相关的界面元素。本发明旨在解决这一问题，通过智能生成与用户需求高度相关的界面组件，提升用户体验。

**Summary (发明总览)**:  
本发明提出了一种基于用户意图动态生成用户界面的方法，通过机器学习技术理解用户需求并提供相应的操作控制。具体实现路径包括利用大型语言模型分析用户输入，识别用户意图，并生成包含相关操作选项的视觉化组件。这些组件可以嵌入到不同的网络环境或软件服务中，为用户提供个性化的交互体验。与现有技术相比，本发明能够更精准地理解用户需求，并提供更智能、更直观的操作引导。

**Key Innovation (核心创新)**:  
1. 利用大型语言模型（LLMs）分析用户输入，精准识别用户意图，为动态生成用户界面提供基础。
2. 基于意图分析结果，动态生成包含相关操作选项的视觉化组件，确保用户界面与用户需求高度相关。
3. 组件生成机制支持在不同的网络环境或软件服务中嵌入，例如控制台、主页或软件开发工具中，提供一致的用户体验。
4. 通过无监督学习技术，模型能够不断优化对用户意图的理解，提高生成组件的准确性和实用性。
5. 引入操作控制功能，允许用户通过视觉化组件直接执行相关操作，减少操作步骤，提升交互效率。
6. 应用于客户支持、软件开发、医疗和教育等领域，能够为用户提供个性化的服务引导和内容推荐。
7. 独特价值在于通过智能生成用户界面，提升用户在使用复杂系统时的操作便捷性和满意度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486645316)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12737370)**
<br/><br/>

---


<br/>

### 44. 使用机器学习模型在直播视频上提供图形叠加的计算机实现方法

**Title (EN)**: Computer-implemented methods for providing graphic overlays on live videos using a machine learning model  
**Pub. No.**: US12739464

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Amit Adam](https://patents.google.com/?inventor=Amit+Adam&country=US&num=100&sort=new), [Avi Avraham Ben-Cohen](https://patents.google.com/?inventor=Avi+Avraham+Ben-Cohen&country=US&num=100&sort=new), [Ran Schley](https://patents.google.com/?inventor=Ran+Schley&country=US&num=100&sort=new)  
**Publication Date**: 15.09.2026

**Abstract**:  
描述了使用机器学习模型在直播视频上提供图形叠加的技术。根据一些示例，一种计算机实现方法包括：在现场制作服务处接收事件的直播流；由现场制作服务的机器学习模型生成第一帧中事件比赛场地的多个点的第一组表面锚定坐标的第一推断，以及这些点的第一组可见性概率；由现场制作服务的机器学习模型生成第二帧中事件比赛场地的至少一个点的第二组表面锚定坐标的第二推断。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486647618_1.jpg)

**Technical Field (技术领域)**:  
计算机视觉；机器学习；视频处理
实时图形叠加技术

**Background (发明背景)**:  
在视频内容制作中，尤其是体育赛事等直播场景中，常常需要在视频中叠加图形元素。
传统方法依赖于人工分析视频帧或预先校准场地与视频帧之间的对齐关系，
这不仅耗时且复杂，还难以应对实时性和动态性要求。
本发明旨在解决上述问题，提供一种更高效、更自动化的图形叠加方法。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的实时视频图形叠加方法。
其核心思路是使用机器学习模型自动识别视频中比赛场地的关键点坐标和可见性，
并据此生成动态的图形叠加效果。
相较于传统方法，本发明无需人工干预或复杂的预校准过程，
能够适应直播视频的实时变化，提高图形叠加的准确性和效率。

**Key Innovation (核心创新)**:  
1. 利用机器学习模型实时识别视频中比赛场地的关键点坐标，
   通过表面锚定坐标的推断实现精确的图形叠加定位。
2. 通过计算关键点的可见性概率，
   动态调整图形叠加的显示效果，确保图形与场地的一致性。
3. 采用现场制作服务架构，
   实现对直播视频流的即时处理和图形叠加，
   避免延迟和人工干预。
4. 机器学习模型能够适应不同视角和变焦，
   通过多帧推断提高图形叠加的稳定性和准确性。
5. 该方法无需预先校准场地与视频帧，
   简化了制作流程，适用于多种体育赛事和直播场景。
6. 推测该技术可应用于体育赛事直播、虚拟广告投放、
   以及增强现实（AR）内容制作等领域，
   为内容创作者提供更灵活、更高效的图形叠加解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486647618)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12739464)**
<br/><br/>

---


<br/>

### 45. 用于检测物品放置或移除的电容式垫子

**Title (EN)**: Capacitive mat for detecting placement or removal of items  
**Pub. No.**: US12736420

**Applicant**: AMAZON TECHNOLOGIES, INC.  
**Inventor**: [Rachid M. Alameh](https://patents.google.com/?inventor=Rachid+M.+Alameh&country=US&num=100&sort=new), [Jiri Slaby](https://patents.google.com/?inventor=Jiri+Slaby&country=US&num=100&sort=new), [Gregory Donald Hager](https://patents.google.com/?inventor=Gregory+Donald+Hager&country=US&num=100&sort=new)  
**Publication Date**: 15.09.2026

**Abstract**:  
一种电容式垫子包括第一组作为传感电极的导体，应用于基板的第一侧，以及第二组作为屏蔽电极的导体，应用于基板的第二侧。基板的上部和下部外层覆盖在导体组上。基板和外层可由柔性材料制成。垫子中的电路确定与垫子某区域中物体相关的导体的电容。为了减少厚度和提高柔韧性，屏蔽电极可用于确定地参考值，从而省略使用单独的地电极。垫子上的导电区域可用于与相邻垫子耦合，允许多个垫子连接。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US486644270_1.jpg)

**Technical Field (技术领域)**:  
传感器技术领域，具体涉及电容式检测技术，用于物品存在性监测。

**Background (发明背景)**:  
零售商、批发商、分销商等实体通常需要管理库存物品。现有技术中，物品的监测通常依赖人工或简单的传感器，可能导致效率低下或错误。本发明旨在提供一种更精确、高效的物品监测方法，以改进库存管理和订单履行。

**Summary (发明总览)**:  
本发明提出了一种基于电容原理的垫子，用于检测物品的放置或移除。通过在柔性基板的两侧布置传感电极和屏蔽电极，并利用电路测量电容变化来识别物品的存在状态。该设计省略了传统地电极的使用，通过屏蔽电极实现地参考值的确定，从而减少了整体厚度并提高了灵活性。多个垫子可以通过导电区域相互连接，实现更大范围的监测。

**Key Innovation (核心创新)**:  
1. 采用双面电极设计，传感电极和屏蔽电极分别位于基板的两侧，通过屏蔽电极确定地参考值，省略了单独的地电极。
2. 使用柔性材料制造基板和外层，使垫子具有更好的柔韧性和适应性，适用于各种形状的表面。
3. 通过电路测量电容变化，实现对物品放置或移除的精确检测，避免了传统传感器可能出现的误报或漏报。
4. 垫子上的导电区域允许多个垫子相互连接，形成更大的监测区域，适用于大型仓储或零售环境。
5. 整体设计减少了厚度和复杂性，提高了垫子的耐用性和易用性，降低了维护成本。
6. 该技术可应用于库存管理、零售展示、仓储监测等多种场景，提供实时、准确的物品存在性数据。
7. 通过优化电极布局和电路设计，实现了更高的检测精度和更低的功耗，延长了设备的使用寿命。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US486644270)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12736420)**
<br/><br/>

---



**Total Patents**: 45  
**Last Updated**: 20260920

---

The Patent Scoop Trio
