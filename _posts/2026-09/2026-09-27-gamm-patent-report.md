---
layout: post
title: "其他专利小快报 2026-09-27"
date: 2026-09-27 14:58:37 +0800
categories: 其他
---

**New Patents**: 33  

---


<br/>

### 1. 在线文档编辑器中的表格单元格拆分

**Title (EN)**: TABLE CELL SPLITTING IN AN ONLINE DOCUMENT EDITOR  
**Pub. No.**: US20260289098

**Applicant**: GOOGLE LLC  
**Inventor**: [Tomer Aberbach](https://patents.google.com/?inventor=Tomer+Aberbach&country=US&num=100&sort=new), [Gregory George Galante](https://patents.google.com/?inventor=Gregory+George+Galante&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明描述了在线文档编辑器中表格单元格拆分的相关技术。方法包括：响应于拆分表格单元格的请求，确定目标行数和目标列数，自动在单元格行旁插入行以达到目标行数，自动在单元格列旁插入列以达到目标列数，并自动合并单元格初始边界内的单元格组，每组跨越确定的行数和列数。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354715_1.jpg)

**Technical Field (技术领域)**:  
在线文档编辑技术，具体涉及表格处理和单元格操作。

**Background (发明背景)**:  
在线文档编辑器允许多用户协作创建、查看和编辑文档，支持多种格式设置，包括字符格式和段落格式，以及表格的创建和编辑。然而，现有技术通常不支持将表格单元格拆分为多个单元格，或需要引入新的存储和布局原语，这增加了工程负担并使系统复杂化。

**Summary (发明总览)**:  
本发明提供了一种基于现有存储和布局原语实现表格单元格拆分的技术方案。通过在控制器层面操作，避免引入新的存储和布局原语，降低了工程复杂性和资源消耗，同时保持了在线文档编辑器的简洁性和资源效率。该方法支持复杂的单元格拆分操作，仅需有限的用户输入即可完成。

**Key Innovation (核心创新)**:  
1. 利用现有行、列、普通单元格和合并单元格的存储和布局原语实现单元格拆分，避免引入新的存储结构。
2. 通过计算目标行数和列数，并基于单元格跨越的行数和列数自动插入新行和新列，实现精确的拆分布局。
3. 采用分组合并策略，将拆分后的单元格区域自动合并为指定数量的行组和列组，保持表格结构的完整性。
4. 通过计算行因子和列因子，优化插入行的数量和位置，确保拆分后的单元格尺寸均匀分布。
5. 针对跨越多行或多列的单元格，先解合并再进行拆分操作，并重新计算受影响单元格的位置和跨度。
6. 支持通过单次或双次用户交互（如点击）触发拆分操作，提升用户操作的便捷性。
7. 该技术适用于需要高效表格处理功能的在线文档编辑产品，能够在保持低资源消耗的同时实现复杂的单元格操作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354715)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289098)**
<br/><br/>

---


<br/>

### 2. 多轮对话中基于生成模型的视觉内容保存

**Title (EN)**: PRESERVATION OF VISUAL CONTENT ACROSS MULTI-TURN DIALOGS WITH GENERATIVE MODEL(S)  
**Pub. No.**: US20260289126

**Applicant**: GOOGLE LLC  
**Inventor**: [Agoston Weisz](https://patents.google.com/?inventor=Agoston+Weisz&country=US&num=100&sort=new), [Alessandro Agostini](https://patents.google.com/?inventor=Alessandro+Agostini&country=US&num=100&sort=new), [François-Xavier Aubet](https://patents.google.com/?inventor=Fran%C3%A7ois-Xavier+Aubet&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及在多轮对话中处理视觉内容。在对话期间接收包含自然语言内容和视觉内容的用户输入。如果在对话中首次接收到视觉内容，则处理该视觉内容以生成相应的视觉内容标记化表示。该标记化表示可以与对话或用户账户关联并缓存在数据库中。如果对话中后续引用该视觉内容，则从数据库中检索相应的视觉内容标记化表示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354748_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及多轮对话中视觉内容的处理与保存。

**Background (发明背景)**:  
当前生成模型（如大语言模型）已展现出强大的语义生成和组合能力，并在大规模语言数据集上进行了训练。一些模型还扩展了对视觉内容（如图像、视频等）的理解能力。然而，现有技术主要依赖视觉内容的文本描述进行处理，这可能导致信息丢失，尤其是在多轮对话中。这种方法可能需要额外的交互来获取视觉内容的详细信息，从而浪费计算和网络资源并延长交互时间。

**Summary (发明总览)**:  
本发明提出了一种在多轮人机对话中处理视觉内容的方法。通过检测对话中的视觉内容，系统生成其标记化表示并存储在数据库中。当对话中再次引用该视觉内容时，系统直接从数据库中检索标记化表示，避免重复计算。这种方法不仅节省了计算资源，还减少了延迟，并确保后续响应包含准确的信息，避免了仅依赖文本描述带来的信息损失。

**Key Innovation (核心创新)**:  
1. 通过检测对话中的视觉内容，生成其标记化表示（如图像标记或数值向量），实现对视觉内容的精确表示。
2. 将视觉内容的标记化表示缓存在与对话或用户账户关联的数据库中，避免重复计算，提高处理效率。
3. 在多轮对话中，通过检索缓存的标记化表示，快速生成对用户后续查询的响应，减少延迟。
4. 利用生成模型处理视觉内容和自然语言输入的标记化表示，结合对话上下文，生成更准确和全面的响应。
5. 通过在服务器端存储图像表示，减少数据传输量，节省网络资源并降低响应生成延迟。
6. 使用结构化文件记录对话历史，包括用户输入、虚拟助手输入以及视觉内容的相关元数据（如图像描述、对象检测结果等），以支持更复杂的对话理解。
7. 本发明可应用于虚拟助手、聊天机器人等场景，通过更高效地处理视觉内容，提升用户体验并降低计算资源消耗。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354748)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289126)**
<br/><br/>

---


<br/>

### 3. 用于个性化即时查询建议的媒体消费上下文

**Title (EN)**: MEDIA CONSUMPTION CONTEXT FOR PERSONALIZED INSTANT QUERY SUGGEST  
**Pub. No.**: US20260288857

**Applicant**: GOOGLE LLC  
**Inventor**: [Dhruv Bakshi](https://patents.google.com/?inventor=Dhruv+Bakshi&country=US&num=100&sort=new), [Jakob Nicolaus Foerster](https://patents.google.com/?inventor=Jakob+Nicolaus+Foerster&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及生成搜索查询建议的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。一种方法包括在搜索会话期间接收请求以获取建议的搜索查询；响应于接收建议搜索查询的请求，识别与媒体内容项相关联的实体；基于识别的实体生成建议的搜索查询；并提供数据以在用户界面中呈现生成的建议搜索查询。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354450_1.jpg)

**Technical Field (技术领域)**:  
本专利属于搜索引擎技术领域，具体涉及利用用户媒体消费历史生成个性化搜索建议的技术。

**Background (发明背景)**:  
用户通常通过输入查询向搜索引擎请求信息，搜索引擎处理查询并返回相关信息。然而，现有技术难以根据用户的媒体消费历史提供个性化的搜索建议，导致搜索结果不够精准或相关。本发明旨在解决这一问题，通过分析用户的媒体消费内容来生成更符合用户兴趣的搜索建议。

**Summary (发明总览)**:  
本发明提出了一种系统，通过分析用户的媒体消费历史来生成个性化的即时搜索建议。系统识别用户消费过的媒体内容及其相关实体，如演员、歌手、导演等，并在用户请求搜索建议时，基于这些实体生成建议的搜索查询。相较于传统方法，本发明利用用户的媒体消费数据，使搜索建议更加个性化和精准。

**Key Innovation (核心创新)**:  
1. 通过识别用户消费过的媒体内容中的实体（如演员、导演、歌手等），生成与用户兴趣高度相关的搜索建议。
2. 在搜索会话期间接收用户请求后，系统会分析当前时间窗口内的媒体消费数据，以确定与用户当前兴趣相关的实体。
3. 支持基于音频片段的请求处理，能够识别用户当前背景音频中的实体，从而生成更贴合用户情境的搜索建议。
4. 提供两种请求模式：一种包含用户输入的部分查询字符，另一种则完全基于用户的媒体消费历史，无需用户输入任何字符。
5. 利用媒体消费数据库存储用户已消费的内容信息，确保搜索建议的生成基于用户实际消费过的内容。
6. 通过自动补全生成器（auto-completion generator）将识别出的实体转化为具体的搜索建议，并将其呈现给用户。
7. 本专利可应用于智能搜索引擎、媒体推荐系统等场景，为用户提供更个性化和精准的搜索体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354450)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288857)**
<br/><br/>

---


<br/>

### 4. 内容过渡方法

**Title (EN)**: Transitioning Of Content  
**Pub. No.**: US20260292298

**Applicant**: Google LLC  
**Inventor**: [Robert Benea](https://patents.google.com/?inventor=Robert+Benea&country=US&num=100&sort=new), [Andrej Cedilnik](https://patents.google.com/?inventor=Andrej+Cedilnik&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种内容过渡的安排方案。通过接收与媒体播放设备相关联的第一信号，其中包含第一用户识别信息，可以识别出第一用户。基于第一用户的识别，可以在媒体播放设备上呈现媒体内容。接收与媒体播放设备相关联的第二信号后，可以确定第一用户已离开媒体播放设备。在确定第一用户已离开后，媒体播放设备将不再呈现媒体内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487358248_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及内容显示技术领域，具体涉及基于面部识别的自动内容过渡技术。

**Background (发明背景)**:  
随着内容分发渠道的增加，用户在不同设备间切换内容的需求变得复杂。现有的方法通常需要用户手动操作，包括设备认证、内容定位和播放进度查找等步骤。这不仅耗时，还降低了用户体验。本发明旨在解决用户在不同设备间无缝过渡内容的问题。

**Summary (发明总览)**:  
本发明提出了一种基于面部识别的内容过渡系统和方法。通过摄像头捕捉图像，系统识别用户面部并检索用户标识符，从而选择并显示相应的节目内容。当检测到用户离开当前设备时，系统可以自动在另一设备上继续播放内容，无需用户手动操作。这种方法利用计算机视觉算法和面部识别技术，实现了用户在不同设备间无缝过渡内容的目标。

**Key Innovation (核心创新)**:  
1. 通过摄像头捕捉图像并使用面部识别技术识别用户身份，实现用户与设备的自动关联。
2. 基于用户标识符选择并显示相应的节目内容，无需用户手动搜索或认证。
3. 利用计算机视觉算法（如Eigenfaces、主成分分析、Fisherfaces等）进行人脸检测和识别，确保识别的准确性和效率。
4. 记录会话标识符、用户标识符和其他相关信息，以支持跨设备的内容过渡。
5. 通过检测和识别多个观看者并关联当前节目信息，处理多用户场景下的内容过渡需求。
6. 在用户离开当前设备时，系统自动在另一设备上继续播放内容，实现无缝过渡。
7. 该技术可应用于家庭娱乐系统、智能家居设备等场景，为用户提供个性化的无缝内容体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358248)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292298)**
<br/><br/>

---


<br/>

### 5. 自然语言生成

**Title (EN)**: NATURAL LANGUAGE GENERATION  
**Pub. No.**: US20260289186

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Xiaohu Liu](https://patents.google.com/?inventor=Xiaohu+Liu&country=US&num=100&sort=new), [Chenlei Guo](https://patents.google.com/?inventor=Chenlei+Guo&country=US&num=100&sort=new), [Bharath Bhimanaik Kumar](https://patents.google.com/?inventor=Bharath+Bhimanaik+Kumar&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明描述了一种使用模型生成对用户输入的响应的技术，该响应与确定为与用户输入相关的个性相关。系统接收用户输入及其相关上下文数据，通过用户输入数据和/或上下文数据确定与用户输入相关的个性（例如，包括个性类型和/或个性特征）。系统生成一个提示，指导模型生成与个性相对应的用户输入响应。模型处理该提示以生成与个性相对应的用户输入响应。在某些实施例中，模型生成对系统另一组件的请求，以生成信息。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354813_1.jpg)

**Technical Field (技术领域)**:  
人工智能，自然语言处理，个性化的对话系统

**Background (发明背景)**:  
自然语言处理系统已经发展到人类可以通过语音和自然语言文本与计算设备进行交互的程度。然而，现有系统通常无法根据用户输入生成具有特定个性的响应，导致交互体验较为单一和缺乏个性化。现有的语言模型在生成符合特定个性或角色的对话时存在不足，难以满足用户对更自然、独特和个性化互动的需求。

**Summary (发明总览)**:  
本发明提出了一种基于用户输入和上下文数据确定相关个性的方法，并利用该个性生成个性化响应。系统通过分析用户输入和上下文信号确定合适的个性类型或特征，并使用这些信息指导语言模型生成符合个性的响应。模型可以请求系统其他组件提供特定数据或生成特定文本，以实现个性化的自然语言生成。此外，系统还可以对生成的响应进行评估，以进一步优化个性化的交互体验。

**Key Innovation (核心创新)**:  
1. 通过分析用户输入和上下文数据，系统能够动态确定与用户输入相关的个性类型和特征，从而实现更精准的个性化响应。
2. 使用个性数据生成个性化提示，指导语言模型生成符合特定个性的响应，例如通过个性特定的自然语言生成技术。
3. 系统能够请求其他组件提供与个性相关的特定信息或执行特定任务，例如调用个性特定的技能或应用。
4. 支持生成多模态响应，包括文本、语音、图像等，以增强个性化和互动体验。
5. 通过对生成的个性响应进行评估，系统能够不断优化个性化的交互效果。
6. 本发明可以应用于数字助理、客户服务机器人、虚拟角色互动等场景，为用户提供更自然、独特和个性化的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354813)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289186)**
<br/><br/>

---


<br/>

### 6. 基于人工智能的电子文档辅助内容生成技术

**Title (EN)**: ARTIFICIAL INTELLIGENCE (AI)-BASED TECHNIQUES FOR SECONDARY CONTENT OF ELECTRONIC DOCUMENTS  
**Pub. No.**: US20260289068

**Applicant**: Google LLC  
**Inventor**: [Aizaz Ahmed](https://patents.google.com/?inventor=Aizaz+Ahmed&country=US&num=100&sort=new), [Bruno Miguel Bras Silva](https://patents.google.com/?inventor=Bruno+Miguel+Bras+Silva&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及基于人工智能的电子文档辅助内容生成方法与系统。通过识别用户提供的电子文档中的主要内容，将其作为输入传递给人工智能模型，并获取一个或多个输出结果。这些输出结果包括与主要内容的风格、格式或上下文相对应的辅助内容。电子文档通过用户关联的客户端设备进行展示，主要内容位于文档的第一区域，而辅助内容则位于主要内容的背景或与第一区域相邻的第二区域中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354682_1.jpg)

**Technical Field (技术领域)**:  
人工智能辅助内容生成技术，
电子文档设计与排版，
生成式人工智能应用

**Background (发明背景)**:  
在协作文档平台中，用户通常需要手动选择和配置与主要内容相关的辅助内容，如背景图像或设计元素，以提升文档的美观性和吸引力。然而，手动选择和配置辅助内容既耗时又难以确保其与主要内容的风格和上下文相匹配。现有的AI工具虽然可以生成包含目标内容的电子文档，但无法仅生成辅助内容，同时允许用户对主要内容进行控制。这导致用户需要反复调整AI生成的文档，消耗大量计算资源，降低系统效率。

**Summary (发明总览)**:  
本发明提供了一种基于人工智能的电子文档辅助内容生成方法。用户首先提供电子文档的主要内容，系统将其作为输入传递给AI模型。AI模型根据主要内容的风格、格式或上下文生成相应的辅助内容。生成的辅助内容可以包括背景图像、颜色或附加图像等元素。系统将主要内容与辅助内容整合后，通过用户设备展示文档。本发明通过AI模型自动生成辅助内容，减少了用户手动配置的时间消耗，并确保辅助内容与主要内容的协调性，从而提升了文档的整体设计质量和用户体验。

**Key Innovation (核心创新)**:  
1. 通过AI模型自动生成与主要内容风格、格式或上下文相匹配的辅助内容，如背景图像或颜色，提升文档设计效率。
2. 提供用户偏好的风格或格式数据作为AI模型输入，确保生成的辅助内容符合用户的个性化需求。
3. 利用生成式AI模型，根据主要内容动态生成辅助内容，而非仅从预定义数据库中检索，提高内容的相关性和独特性。
4. 支持用户通过自然语言描述目标特征，系统将其转化为AI模型输入，从而实现更精准的辅助内容生成。
5. 在生成辅助内容时，系统考虑主要内容在文档中的布局和排版，确保辅助内容与主要内容在视觉上协调一致。
6. 通过AI模型生成辅助内容的同时，允许用户对主要内容进行独立编辑和控制，保持用户对文档内容的掌控力。
7. 本发明可应用于协作文档平台、演示文稿制作工具等场景，为用户提供智能化的文档设计辅助，提升工作效率和文档质量。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354682)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289068)**
<br/><br/>

---


<br/>

### 7. 使用语言模型神经网络完成任务

**Title (EN)**: TASK COMPLETION USING A LANGUAGE MODEL NEURAL NETWORK  
**Pub. No.**: US20260289251

**Applicant**: Google LLC  
**Inventor**: [Omar Abdelaziz](https://patents.google.com/?inventor=Omar+Abdelaziz&country=US&num=100&sort=new), [Martin Baeuml](https://patents.google.com/?inventor=Martin+Baeuml&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及用于自动化与用户界面交互以执行任务的计算机实现方法、系统及设备，其通过语言模型神经网络实现。方法包括接收描述任务的输入；确定描述任务的数据；并通过语言模型神经网络执行任务，具体为重复执行以下操作：获取从描述任务的数据派生的第一输入子序列；获取从当前用户界面的图像派生的第二输入子序列；基于第一输入子序列和第二输入子序列生成输出数据，描述要在当前用户界面中执行的一个或多个操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354886_1.jpg)

**Technical Field (技术领域)**:  
人工智能；人机交互；自动化任务执行

**Background (发明背景)**:  
自动化助手通过各种计算设备与用户交互并执行任务，但现有技术通常依赖用户手动操作界面元素或依赖应用程序的公开API。
对于缺乏公开API的应用程序或复杂界面，自动化任务执行变得困难。
此外，编写和维护自动化脚本需要大量人力和计算资源。

**Summary (发明总览)**:  
本发明提出了一种基于语言模型神经网络的技术方案，通过自动化与用户界面的交互来完成任务。
该方案通过接收任务描述，解析任务数据，并利用语言模型神经网络生成操作序列。
这些操作序列指导用户界面从当前状态逐步过渡到目标状态，从而实现任务的自动化执行。
相较于传统方法，本发明无需依赖公开API或手动编写脚本，能够在更广泛的任务环境中实现自动化。

**Key Innovation (核心创新)**:  
1. 利用语言模型神经网络生成操作序列，通过解析任务描述和当前用户界面图像来指导任务执行。
2. 通过光学字符识别（OCR）、文本提取神经网络或图像嵌入神经网络获取用户界面的关键信息。
3. 支持模拟用户输入（如语音、键盘、鼠标、触摸屏等），以实现对用户界面的全面控制。
4. 引入历史数据处理机制，使语言模型神经网络能够参考之前的操作，提高任务执行的连贯性和准确性。
5. 训练语言模型神经网络时，使用用户与设备的交互数据，通过最小化损失函数优化模型参数，确保生成的操作序列更符合实际需求。
6. 实现了对私有应用、遗留应用等缺乏公开API的应用程序的自动化任务执行。
7. 降低了创建和维护自动化脚本的成本，同时提高了任务执行的灵活性和可扩展性，适用于多种计算设备和任务环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354886)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289251)**
<br/><br/>

---


<br/>

### 8. 具有自动说话人轮换检测功能的流式语音到语音模型

**Title (EN)**: STREAMING SPEECH-TO-SPEECH MODEL WITH AUTOMATIC SPEAKER TURN DETECTION  
**Pub. No.**: US20260290315

**Applicant**: Google LLC  
**Inventor**: [Fadi Biadsy](https://patents.google.com/?inventor=Fadi+Biadsy&country=US&num=100&sort=new), [Oleg Rybakov](https://patents.google.com/?inventor=Oleg+Rybakov&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种用于语音到语音模型中的轮换检测方法包括接收作为语音到语音（S2S）模型输入的对应于用户语音的声学帧序列。在多个输出步骤中的每一步，该方法还包括：由S2S模型的音频编码器生成对应声学帧的高级特征表示；基于音频编码器在相应输出步骤生成的高级特征表示，由S2S模型的轮换检测器确定语音是否在相应输出步骤处处于断点。当轮换检测器确定语音处于断点时，该方法包括将由S2S模型的语音解码器输出的输出音频帧序列合成为代表用户语音的合成语音的时间域音频波形。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487356061_1.jpg)

**Technical Field (技术领域)**:  
语音处理技术领域，具体涉及流式语音到语音转换及说话人轮换检测技术。

**Background (发明背景)**:  
现有的语音到语音（S2S）模型通常需要用户手动指示输入语音的开始和结束，这限制了其在实时应用中的便利性。此外，现有技术难以处理非典型语音或跨语言转换场景中的流畅性需求。本发明旨在解决这些问题，通过自动检测说话人轮换并实时生成合成语音，提升用户体验。

**Summary (发明总览)**:  
本发明提出了一种流式语音到语音模型，通过自动检测说话人轮换，实现实时语音转换。其核心思路是使用音频编码器生成声学帧的高级特征表示，并基于这些特征由轮换检测器判断是否处于说话轮换的断点。当检测到断点时，语音解码器将生成合成语音的音频帧序列并合成为时间域音频波形。该方法无需用户手动指示语音的开始和结束，能够处理非典型语音和跨语言转换场景。

**Key Innovation (核心创新)**:  
1. 通过音频编码器实时生成声学帧的高级特征表示，为轮换检测提供基础。
2. 采用深度神经网络作为轮换检测器，精准判断说话人轮换的断点位置。
3. 轮换检测器输出位或概率分布，以指示当前帧是否为断点帧，提高检测可靠性。
4. 语音解码器根据音频编码器生成的高级特征表示，实时生成合成语音的音频帧序列。
5. 支持非典型语音转换，将用户的不流畅语音转换为流畅的合成语音。
6. 支持跨语言转换，将用户语音转换为另一种语言的合成语音。
7. 适用于实时语音翻译和辅助交流产品，为用户提供流畅的语音交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356061)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260290315)**
<br/><br/>

---


<br/>

### 9. 微流控热管理系统和方法

**Title (EN)**: SYSTEMS AND METHODS FOR MICROFLUIDIC THERMAL MANAGEMENT  
**Pub. No.**: US20260293048

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ruslan NAGIMOV](https://patents.google.com/?inventor=Ruslan+NAGIMOV&country=US&num=100&sort=new), [Bharath RAMAKRISHNAN](https://patents.google.com/?inventor=Bharath+RAMAKRISHNAN&country=US&num=100&sort=new), [Husam Atallah ALISSA](https://patents.google.com/?inventor=Husam+Atallah+ALISSA&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种热管理设备包括具有第一周边侧和第二周边侧的微流控体积，以及至少一个热元件；微流控体积的第一端口；第二端口；位于第一端口的入口阀；位于第二端口的出口阀；以及与入口阀和/或出口阀的部分机械连接的阀压电元件，用于移动至少一个阀的部分并选择性地允许流体通过微流控体积流动。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487359076_1.jpg)

**Technical Field (技术领域)**:  
微流控技术领域，具体涉及电子设备的热管理系统。
涉及微流控冷却和压电驱动阀控制技术。

**Background (发明背景)**:  
传统热管理通过热扩散器将处理器等热源的热量传导至散热片或环境空气，但需要较大的体积和质量。
微流控冷却虽然可以直接对热源进行冷却，但现有技术对温度变化的响应速度和冷却效率仍有不足。
本发明旨在提供一种更高效、更灵活的热管理方案，以应对快速变化的散热需求。

**Summary (发明总览)**:  
本发明提出了一种基于微流控技术的热管理系统，通过压电驱动阀控制冷却液在微流控通道中的流动路径和流量。
该系统能够根据热源的实际散热需求，动态调整冷却液的流动模式，实现精准的热管理。
相较于传统热扩散器，本发明具有更快的响应速度和更高的冷却效率，同时减少了系统体积和重量。
通过实时监测温度、功耗或工作负载，系统可以预测并主动调整冷却策略。

**Key Innovation (核心创新)**:  
1. 采用压电驱动阀控制微流控通道的流体流动，通过施加调节电压或电流控制阀的开闭，实现对冷却液流动的精确控制。
2. 包含双向流体歧管设计，允许冷却液在微流控通道中双向流动，从而优化冷却路径并提高散热效率。
3. 通过测量热源的温度、功耗或工作负载，实时监测散热需求，并根据预测的散热需求主动调整冷却液流量和流动路径。
4. 使用压电膜片作为泵送元件，通过施加电压使其变形，从而改变微流控通道的体积，推动冷却液流动。
5. 实现了对微流控通道中冷却液流动的动态调节，能够快速响应热源的热量变化，提供及时有效的冷却。
6. 该系统可应用于处理器、图形处理器、存储器等各类电子元件的热管理，尤其适用于对散热要求高且空间受限的设备。
7. 通过精准控制冷却液流动路径和流量，本发明能够降低热扩散器的体积和重量，同时提高散热效率，为电子设备的小型化和高性能化提供支持。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487359076)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260293048)**
<br/><br/>

---


<br/>

### 10. 跨域内容融合

**Title (EN)**: CROSS-DOMAIN CONTENT BLENDING  
**Pub. No.**: US20260289874

**Applicant**: Google LLC  
**Inventor**: [Miquel Angel Farré Guiu](https://patents.google.com/?inventor=Miquel+Angel+Farr%C3%A9+Guiu&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及用于融合来自不同领域内容的方法、系统及设备，包括编码在计算机存储介质上的计算机程序。方法包括从给定内容提供商获取一组文本和一组图像，这些内容被指定用于创建数字组件；将显著性模型应用于电子文档以识别电子文档中的显著区域；构建一组修改，这些修改不会导致电子文档中的显著区域被文本或图像覆盖；确定电子文档的视觉特征；接收来自客户端设备的请求，以将来自不同领域的内容整合到电子文档中；根据构建的修改和确定的电子文档视觉特征，对文本或图像进行视觉修改；响应接收到的内容请求，向客户端设备提供经过视觉修改的数字组件。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487355571_1.jpg)

**Technical Field (技术领域)**:  
跨域内容融合技术，
涉及数字内容整合与视觉呈现优化，
特别是跨域数字组件的实时视觉调整。

**Background (发明背景)**:  
在现有技术中，来自不同领域的内容（如网页和第三方广告）通常在视觉上存在显著差异，导致用户体验不佳。这种差异可能源于内容提供方的不同以及安全限制，使得跨域内容难以实时调整。此外，数字组件通常需要在极短时间内提供，难以进行复杂的视觉优化，从而影响整体视觉一致性。

**Summary (发明总览)**:  
本发明提出了一种跨域内容融合方法，通过机器学习模型识别电子文档中的显著区域，并构建不影响这些区域的文本和图像修改方案。系统根据电子文档的视觉特征，对来自不同领域的内容进行实时视觉调整，使其与主文档内容无缝融合。该方法结合了预处理和实时处理技术，确保数字组件在严格时间限制内进行视觉优化，从而提升整体视觉一致性和用户体验。

**Key Innovation (核心创新)**:  
1. 通过机器学习训练的显著性模型识别电子文档中的显著区域，确保文本和图像的修改不会覆盖这些区域，从而保护关键内容。
2. 构建文本和图像的修改方案，包括调整文本排版和图像形状，并通过计算机视觉技术验证修改是否影响显著区域。
3. 根据电子文档的视觉特征（如目标排版和目标形状），对数字组件进行动态调整，使其与主文档内容在视觉上保持一致。
4. 针对数字组件的预期受众特性（如年龄、兴趣等），进一步优化图像形状和内容布局，以提升用户参与度。
5. 对于包含视频内容的数字组件，系统根据电子文档的上下文确定视频的起始播放点，而非从视频开头播放，从而提高内容相关性。
6. 通过实时处理技术，在数百毫秒内完成数字组件的视觉调整，确保在严格时间限制内提供优化后的内容。
7. 本发明可应用于跨域广告投放、网页内容整合等场景，提供无缝的视觉体验，同时提升用户满意度和资源利用效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355571)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289874)**
<br/><br/>

---


<br/>

### 11. 人工智能驱动的头脑风暴会议引导与模板化

**Title (EN)**: ARTIFICIAL INTELLIGENCE DRIVEN LEADING AND TEMPLATIZING OF IDEATION SESSION  
**Pub. No.**: US20260291766

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Sarah Ragab Ismail SALEH](https://patents.google.com/?inventor=Sarah+Ragab+Ismail+SALEH&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种数据处理系统实现了在与会者关联的多个客户端设备之间的在线会议期间检测触发条件发生的情况，该触发条件表明应启动用于收集参与者想法的头脑风暴会议；根据与在线会议相关的会议信息选择头脑风暴会议模板，每个头脑风暴会议模板包括一个自然语言提示模板，该模板包含对语言模型的指令，以生成特定类型头脑风暴会议的议程并根据议程进行会议；基于头脑风暴会议模板的自然语言提示模板构建提示；并提供该提示。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
人工智能，会议管理，协作工具

**Background (发明背景)**:  
在线会议和协作工具在现代工作环境中越来越普遍，但传统的头脑风暴会议通常缺乏结构化流程，导致效率低下和参与度不足。现有的会议管理系统无法根据会议的具体需求自动生成合适的议程或引导流程。

**Summary (发明总览)**:  
本发明提出了一种基于人工智能的会议引导系统，通过检测会议中的触发条件自动启动头脑风暴会议，并利用预定义的模板生成个性化的会议议程。该系统通过自然语言处理技术，根据会议类型和目标自动构建会议流程，从而提高会议效率和参与度。

**Key Innovation (核心创新)**:  
1. 通过检测会议中的触发条件（如关键词、情绪变化或特定时间点）自动启动头脑风暴会议，确保会议流程的及时性和准确性。
2. 利用预定义的头脑风暴会议模板库，根据会议的主题、参与人数和目标自动选择最合适的模板，提供个性化的会议引导。
3. 基于自然语言处理技术，生成包含详细指令的会议议程，指导语言模型根据特定类型的头脑风暴会议生成结构化的会议流程。
4. 通过构建动态提示，将会议模板与实时会议数据结合，确保会议引导的灵活性和适应性。
5. 提供一个用户友好的界面，允许会议主持人实时调整会议议程和引导流程，以应对会议中的突发情况。
6. 通过结构化的会议流程和引导，提升参与者的积极性和创造力，从而提高头脑风暴会议的整体效果。
7. 该系统可应用于企业会议、创意工作坊和团队协作场景，帮助组织更高效地收集和整理创意想法。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487357663)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260291766)**
<br/><br/>

---


<br/>

### 12. 扩展现实表面输入系统、设备和方法

**Title (EN)**: SYSTEMS, DEVICES, AND METHODS FOR EXTENDED-REALITY SURFACE TYPING  
**Pub. No.**: US20260288249

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Karol Constantine Hatzilias](https://patents.google.com/?inventor=Karol+Constantine+Hatzilias&country=US&num=100&sort=new), [Jingming Dong](https://patents.google.com/?inventor=Jingming+Dong&country=US&num=100&sort=new), [Guangxun Liao](https://patents.google.com/?inventor=Guangxun+Liao&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种增强现实头戴式系统，包括用于物体追踪的第一外向摄像头和用于深度感测的第二外向摄像头，其中第二外向摄像头的分辨率高于第一外向摄像头。第一和第二外向摄像头用于提供图像数据，供人工智能助手在第一时间点处理用户查询的上下文AI使用。第一和第二外向摄像头还用于捕捉与增强现实头戴式设备的第一视野相关的图像数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353782_1.jpg)

**Technical Field (技术领域)**:  
本专利属于扩展现实（XR）交互技术领域，具体涉及增强现实（AR）和混合现实（MR）头戴式设备中的表面输入技术。

**Background (发明背景)**:  
混合现实设备需要提供无缝且沉浸式的扩展现实环境，用户可以通过手势识别、眼动追踪和/或身体追踪技术与设备交互。然而，现有技术在平衡外形尺寸、重量、功耗、效率、成本、速度以及处理速度、组件视觉隐蔽性和无缝用户界面特性等竞争性约束方面仍存在挑战。

**Summary (发明总览)**:  
本发明提供了一种优化后的增强现实头戴式系统，通过优化摄像头位置减少视觉遮挡，同时降低光学或机械组件的视觉显著性，从而实现更自然和沉浸式的用户交互体验。该系统利用多个外向摄像头进行物体追踪和上下文AI辅助的表面输入，支持虚拟键盘投影到物理表面或以3D全息键盘形式显示，用户可通过手势或其他输入设备进行交互。

**Key Innovation (核心创新)**:  
1. 采用双摄像头设计，其中第二摄像头具有更高分辨率，用于深度感测和物体追踪，提升交互精度。
2. 通过优化摄像头位置减少视觉遮挡，同时降低光学或机械组件的视觉显著性，提升用户体验。
3. 支持虚拟扩展现实键盘的投影，可将键盘投射到物理表面或以3D全息形式显示，适应不同使用场景。
4. 允许用户通过手势（如手指动作）和/或其他输入设备（如触控笔或触觉反馈手套）与虚拟键盘进行交互。
5. 系统集成了人工智能助手，可根据用户查询提供上下文相关的AI辅助功能，提升交互智能性。
6. 设备可与智能手表、中间处理设备等外部设备协同工作，形成完整的扩展现实交互系统。
7. 应用于日常办公、远程协作和沉浸式娱乐等场景，为用户提供更自然、高效的扩展现实交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353782)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288249)**
<br/><br/>

---


<br/>

### 13. 使用机器学习估计物体的3D形状

**Title (EN)**: USING MACHINE LEARNING TO ESTIMATE A 3D SHAPE OF OBJECTS  
**Pub. No.**: US20260284891

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Hakan Boyraz](https://patents.google.com/?inventor=Hakan+Boyraz&country=US&num=100&sort=new), [Charles Swan](https://patents.google.com/?inventor=Charles+Swan&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明公开了用于机器人放置物体的3D形状估计的系统和方法。系统可以从不同视角捕捉物体的图像并生成特征。系统使用机器学习模型（例如神经网络）将体素投影到图像中的不同位置。系统基于对应于这些不同位置的初始特征，使用机器学习模型生成体素的第二特征。系统基于第二特征确定体素是否指示物体。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
机器人技术；计算机视觉；3D重建

**Background (发明背景)**:  
在机器人操作中，准确估计物体的3D形状对于物体抓取和放置至关重要。
现有技术通常依赖于复杂的传感器或计算成本高的算法。
这些方法在处理遮挡和视角变化时存在局限性。
本发明旨在提供一种更高效且适应性强的3D形状估计方法。

**Summary (发明总览)**:  
本发明提出了一种基于机器学习的3D形状估计方法，通过多视角图像分析实现物体形状的精确重建。
系统首先从不同视角捕捉物体图像并提取特征。
然后利用神经网络将体素与图像中的具体位置关联起来。
通过分析这些关联特征，系统能够判断体素是否属于目标物体。
相较于传统方法，本发明在处理复杂场景和遮挡问题时表现更优。

**Key Innovation (核心创新)**:  
1. 使用多视角图像生成初始特征，通过神经网络提取物体的空间信息。
2. 采用体素投影技术，将3D体素与2D图像中的具体位置对应起来。
3. 基于对应位置的初始特征，生成体素的第二特征以增强形状估计的准确性。
4. 通过机器学习模型分析第二特征，判断体素是否属于目标物体。
5. 该方法能够有效处理遮挡和视角变化问题，提高3D重建的鲁棒性。
6. 应用于机器人抓取和放置任务中，可实现更精准的物体操作。
7. 相比传统方法，本发明在计算效率和适应性方面具有显著优势。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487350075)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260284891)**
<br/><br/>

---


<br/>

### 14. 集成镜头的头戴式设备

**Title (EN)**: HEAD-MOUNTED DEVICE HAVING LENS INTEGRATED WITH FRAME  
**Pub. No.**: US20260287906

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Sarat Babu](https://patents.google.com/?inventor=Sarat+Babu&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种头戴式显示器（HMD）包括结构框架、波导、目镜侧镜头和世界侧镜头。波导用于将显示光引导至眼球盒区域。目镜侧镜头或世界侧镜头作为一体成型的连续折射材料集成到结构框架中。目镜侧镜头具有第一光学功率，用于将显示光聚焦到眼球盒区域。世界侧镜头具有第二光学功率，第一光学功率和第二光学功率的组合将场景光聚焦到眼球盒区域。波导位于目镜侧镜头和世界侧镜头之间。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
头戴式显示技术；光学系统集成；增强现实/虚拟现实设备

**Background (发明背景)**:  
头戴式显示器（HMD）通常需要复杂的光学系统来提供清晰的显示效果和舒适的视觉体验。
现有技术中，光学组件通常作为独立部件组装，导致设备体积大且重量增加。
此外，传统设计难以同时优化显示光和场景光的聚焦效果，影响用户体验。
本发明旨在通过集成光学组件来简化设备结构并提升光学性能。

**Summary (发明总览)**:  
本发明提出了一种新型头戴式显示器，通过将光学镜头与设备框架集成来简化结构。
采用一体成型的光学材料，将目镜侧镜头或世界侧镜头直接嵌入框架中。
波导被设计为在目镜侧镜头和世界侧镜头之间传递显示光。
通过组合两种光学镜头的光学功率，实现显示光和场景光的精确聚焦。
这种设计减少了独立光学组件的数量，缩小了设备体积并提升了光学性能。

**Key Innovation (核心创新)**:  
1. 将目镜侧镜头或世界侧镜头作为一体成型的连续折射材料集成到设备框架中，简化了光学组件的组装过程。
2. 采用波导在目镜侧镜头和世界侧镜头之间传递显示光，优化了光路设计并减少了光损失。
3. 通过组合目镜侧镜头和世界侧镜头的光学功率，实现显示光和场景光的精确聚焦，提升了视觉体验。
4. 光学镜头的集成设计减少了独立组件的数量，降低了设备重量和体积。
5. 该设计使得光学系统更紧凑，同时保持了高性能的光学特性，适用于需要轻量化设计的增强现实和虚拟现实设备。
6. 通过优化光学镜头的材料和成型工艺，提升了设备的耐用性和生产成本效益。
7. 该技术特别适用于需要长时间佩戴的头戴式设备，如增强现实眼镜或虚拟现实头盔，为用户提供更舒适的使用体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353406)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260287906)**
<br/><br/>

---


<br/>

### 15. 基于手持设备运动生成合成坐标数据的方法和系统

**Title (EN)**: SYSTEMS AND METHODS FOR GENERATING SYNTHESIZED COORDINATE DATA BASED ON HANDHELD DEVICE MOTION  
**Pub. No.**: US20260288266

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Sheng Shen](https://patents.google.com/?inventor=Sheng+Shen&country=US&num=100&sort=new), [Paul Austin Buckley](https://patents.google.com/?inventor=Paul+Austin+Buckley&country=US&num=100&sort=new), [Qingyi Dong](https://patents.google.com/?inventor=Qingyi+Dong&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种生成合成坐标数据的方法。该方法包括从手持设备的输入执行器接收第一运动数据，第一运动数据代表输入执行器的运动并对应于第一数据格式，确定输入执行器是否满足操作模式切换条件，基于满足操作模式切换条件，至少部分地激活手持设备在第二模式下的操作，从手持设备的传感器接收第二运动数据，第二运动数据代表手持设备的运动并对应于第二数据格式，当手持设备在第二模式下运行时，生成合成坐标数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353801_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及人机交互技术，具体为基于运动传感器的数据处理和坐标生成技术。

**Background (发明背景)**:  
传统的手持设备通常依赖单一的运动传感器或输入执行器来捕捉用户动作，但这种方式在精度和灵活性上存在局限。
现有技术难以在复杂运动场景中准确捕捉用户意图，且不同数据格式之间的转换效率较低。
本发明旨在解决上述问题，通过结合多种数据源和模式切换机制，提高数据生成精度和系统响应能力。

**Summary (发明总览)**:  
本发明提出了一种基于手持设备运动生成合成坐标数据的方法。
该方法通过检测输入执行器的运动数据并判断是否满足模式切换条件，
在满足条件时切换到传感器模式，
并结合两种模式下的运动数据生成更精确的合成坐标数据。
相较于传统方法，本发明通过多源数据融合提高了数据精度和系统适应性。

**Key Innovation (核心创新)**:  
1. 通过检测输入执行器的运动数据并判断模式切换条件，实现从单一模式到多模式的动态切换。
2. 结合输入执行器和传感器的运动数据，采用数据融合技术生成合成坐标数据，提高了数据精度。
3. 设计了数据格式转换机制，确保不同数据源之间的兼容性和高效处理。
4. 通过模式切换机制，系统能够根据用户操作实时调整数据采集方式，优化了响应速度和准确性。
5. 该方法可应用于虚拟现实、增强现实和游戏控制等领域，提供了更自然和精准的人机交互体验。
6. 通过多源数据融合，解决了传统方法在复杂运动场景中数据精度不足的问题。
7. 推测该技术可应用于手持游戏控制器或运动捕捉设备，为用户提供更流畅和精准的操作体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353801)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288266)**
<br/><br/>

---


<br/>

### 16. 使用空间感知标签和3D虚拟地理围栏的无菜单操作

**Title (EN)**: MENULESS OPERATIONS USING SPATIALLY AWARE TAGS WITH 3D VIRTUAL GEO-FENCING  
**Pub. No.**: US20260292445

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Charbel KHAWAND](https://patents.google.com/?inventor=Charbel+KHAWAND&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明描述了使用具有虚拟地理围栏边界的空间感知标签实现无菜单操作的方法。处理器上实现的标签管理器获取选定地理围栏区域内与超宽带（UWB）启动的发起设备相关的运动数据。运动数据由选定地理围栏区域内的一个或多个UWB启用的响应设备生成，包含描述发起设备在选定地理围栏区域内3D运动的数据。标签管理器使用运动数据识别发起设备的3D运动序列，并通过无菜单操作映射表将3D运动序列映射到区域特定和/或用户特定的操作。标签管理器触发选定地理围栏区域内的目标计算设备执行映射的操作。目标计算设备可以包括地理围栏区域内的用户设备、物联网（IoT）设备以及发起设备本身。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487358411_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及使用超宽带（UWB）设备和地理围栏实现无菜单操作。

**Background (发明背景)**:  
传统的计算设备或物联网设备通常需要用户通过键盘、鼠标或其他输入设备手动输入命令来启动操作。尽管图形用户界面（GUI）和菜单提供了便利，但创建和管理地理围栏区域仍需用户通过键盘或触摸屏进行操作，这既耗时又不灵活。本发明旨在解决这一问题，通过空间感知标签和3D虚拟地理围栏实现无需手动输入的无菜单操作。

**Summary (发明总览)**:  
本发明提出了一种基于空间感知标签和3D虚拟地理围栏的无菜单操作方法。用户使用UWB设备在地理围栏区域内进行特定3D运动序列，这些运动序列被标签管理器识别并映射到预定义的操作。目标计算设备根据映射结果执行相应操作，无需用户手动输入命令。该方法提高了操作的灵活性和用户便利性，尤其适用于需要非接触式或非语音命令的场景。

**Key Innovation (核心创新)**:  
1. 通过UWB设备实现空间感知标签，精确捕捉用户3D运动数据，包括方向、速度、高度等参数。
2. 利用地理围栏技术划分操作区域，不同区域可定义不同的操作序列，实现区域特定的无菜单操作。
3. 标签管理器将用户运动序列映射到预定义操作，通过映射表实现灵活且可配置的操作指令集。
4. 支持多种目标设备，包括用户设备、IoT设备和发起设备本身，扩展了应用场景。
5. 允许用户在不接触目标设备的情况下进行操作，提升了操作的便利性和适用性，例如在嘈杂或安静环境中使用。
6. 通过UWB设备实现非接触式命令输入，避免了传统键盘和触摸屏的限制，提高了用户交互效率。
7. 应用于智能家居、办公环境或公共场所等场景，提供了一种新颖且高效的无菜单操作方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358411)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292445)**
<br/><br/>

---


<br/>

### 17. 用于智能家居和物体交互的空间鼠标

**Title (EN)**: SPATIAL MOUSE FOR SMART HOME AND OBJECT INTERACTIONS  
**Pub. No.**: US20260288246

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Kerkil Choi](https://patents.google.com/?inventor=Kerkil+Choi&country=US&num=100&sort=new), [Honghong Peng](https://patents.google.com/?inventor=Honghong+Peng&country=US&num=100&sort=new), [Shuochen Su](https://patents.google.com/?inventor=Shuochen+Su&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及一种系统，包括一个装置，该装置配备多个传感器，用于检测空间鼠标指向的一个或多个物体。该系统还包括一个处理器，用于处理来自多个传感器的数据，基于处理后的数据识别物体，并根据识别的物体执行命令。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353779_1.jpg)

**Technical Field (技术领域)**:  
智能家居设备领域，具体涉及用于智能家居和物体交互的空间鼠标技术。

**Background (发明背景)**:  
智能家居技术改变了人们与生活环境的交互方式，通过集成先进技术实现家庭功能的自动化和控制。然而，传统指向设备如鼠标和触控板主要针对二维平面交互，在智能家居环境中存在局限性，难以实现对分布式设备的精确和直观控制。本发明旨在解决传统设备在智能家居场景中交互不便的问题。

**Summary (发明总览)**:  
本发明提出了一种空间鼠标技术，通过集成多个传感器和处理器，实现对智能家居环境中物体的三维交互。该技术通过传感器捕捉用户指向的数据，识别目标物体，并在头戴设备上显示指针以确认目标位置。同时，系统支持手势识别，通过第二只手的手势执行对目标物体的操作命令。这种方法提供了一种更自然、直观的交互方式，提升了智能家居设备的控制精度和用户体验。

**Key Innovation (核心创新)**:  
1. 通过集成多传感器技术，实现对用户指向的精确三维空间检测和物体识别。
2. 在头戴设备上显示指针并叠加在目标物体上，使用户能够直观确认空间鼠标的指向位置。
3. 利用机器学习算法识别用户的手势，并根据手势和目标物体执行相应的操作命令。
4. 支持多种智能家居设备的交互，例如通过握拳控制灯泡开关或通过手势调节智能恒温器的温度。
5. 提供了一种更自然和直观的用户界面，减少了传统设备在智能家居环境中交互的认知负担。
6. 扩展了交互方式的应用场景，不仅限于智能家居，还支持增强现实（AR）和虚拟现实（VR）应用。
7. 通过这种空间鼠标技术，用户可以更高效地管理智能家居设备，并实现更沉浸式的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353779)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288246)**
<br/><br/>

---


<br/>

### 18. 包含弹性背衬层的可折叠显示器

**Title (EN)**: FOLDABLE DISPLAY COMPRISING AN ELASTIC BACKING LAYER  
**Pub. No.**: US20260293004

**Applicant**: Google LLC  
**Inventor**: [William Riis Hamburgen](https://patents.google.com/?inventor=William+Riis+Hamburgen&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种可折叠显示设备包括外壳和与外壳相连的连续显示器。外壳包括第一组件、第二组件以及连接第一和第二组件并定义折叠轴的铰链组件。连续显示器被配置为围绕折叠轴折叠，并包括显示层（包含光学显示器）、覆盖显示层的盖层以及位于显示层下方的背衬层。背衬层包括弹性基体或片材，以及分散在弹性基体或片材中或位于其上的肋条阵列，这些肋条大致平行于折叠轴排列。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487359027_1.jpg)

**Technical Field (技术领域)**:  
可折叠显示技术领域，具体涉及具有弹性背衬层的折叠显示器。

**Background (发明背景)**:  
显示设备通常希望尽可能增大显示面积，但较大的显示设备可能变得笨重且不便携带。通过折叠设计可以增加显示面积，但折叠区域容易产生折痕，影响显示效果。本发明旨在提供一种能够折叠且减少折痕的显示器结构。

**Summary (发明总览)**:  
本发明提出了一种可折叠的连续显示器设计，通过在显示层下方加入弹性背衬层来增强折叠区域的机械性能。背衬层包含弹性基体和沿折叠轴排列的肋条阵列，既能提供柔性支撑以适应折叠，又能在展开状态下提供足够的刚性支撑。这种设计在保持设备便携性的同时，提升了折叠显示器的耐用性和显示效果。

**Key Innovation (核心创新)**:  
1. 采用弹性基体和肋条阵列组合的背衬层结构，其中弹性基体提供柔性支撑，肋条阵列提供刚性支撑。
2. 肋条阵列沿折叠轴方向排列，确保在折叠过程中不会阻碍显示器的弯曲，同时增强折叠区域的机械稳定性。
3. 通过独立调节背衬层的各向异性特性，如不同方向的刚度，优化了折叠显示器的折叠性能和展开状态下的显示效果。
4. 背衬层的设计能够有效分散和抵抗连续显示器在操作过程中受到的剪切力，减少折痕和其他变形。
5. 铰链组件与背衬层协同工作，确保折叠过程顺畅且折叠后显示器能够紧密贴合，减少不必要的应力集中。
6. 该设计适用于大尺寸便携设备，如平板电脑和智能手机，提升了设备的便携性和显示效果。
7. 通过减少折痕和提升折叠耐用性，本发明为折叠显示设备提供了更可靠的用户体验，延长了设备的使用寿命。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487359027)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260293004)**
<br/><br/>

---


<br/>

### 19. 用于在成像传感器细节不足时识别手势的泛光灯LED技术，以及使用这些技术的混合现实系统和方法

**Title (EN)**: Techniques for Using Floodlight LEDs When Imaging Sensors Have an Insufficient Level of Detail for Identifying Hand Gestures, and Mixed-Reality Systems and Methods of Using These Techniques  
**Pub. No.**: US20260292120

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Tsz Ho Yu](https://patents.google.com/?inventor=Tsz+Ho+Yu&country=US&num=100&sort=new), [Yiwen Wu](https://patents.google.com/?inventor=Yiwen+Wu&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明提供了一种混合现实（MR）头戴式设备。该设备包括一组成像传感器和一组泛光灯发光二极管（泛光灯LED），这些传感器和LED沿头戴式设备的前部布置。当MR头戴式设备呈现MR内容时，如果从成像传感器获取的成像数据细节不足以识别手势，则处理器会控制一个或多个泛光灯LED照亮包含用户手部的物理空间区域。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487358053_1.jpg)

**Technical Field (技术领域)**:  
混合现实技术领域，具体涉及用于增强手势识别和交互的照明与成像传感器布置技术。

**Background (发明背景)**:  
混合现实头戴式设备能够为用户提供沉浸式和互动性强的MR内容，但这种互动方式对环境条件（如照明）有较高要求。现有的成像传感器在某些情况下可能无法提供足够的细节来准确识别用户的手势，从而影响交互体验。因此，需要一种解决方案来应对这些挑战。

**Summary (发明总览)**:  
本发明提出了一种结合泛光灯LED和成像传感器的混合现实头戴式设备方案。当检测到成像数据不足以识别手势时，系统会激活泛光灯LED以增强照明，从而提高手势识别的准确性。该方案通过动态调整照明条件，解决了现有技术中因环境光不足导致的手势识别问题，提升了用户与MR内容的交互体验。

**Key Innovation (核心创新)**:  
1. 集成泛光灯LED与成像传感器，通过协同工作动态调整照明条件，解决了环境光不足导致的手势识别问题。
2. 在检测到成像数据细节不足时，处理器自动控制泛光灯LED照亮用户手部区域，实现精准照明。
3. 设备支持多种输入方式，包括空中手势和表面接触手势，并可与肌电传感器、惯性测量单元等传感器结合使用。
4. 设备可与智能手表、中间处理设备等外部设备协同工作，形成一个完整的扩展现实交互系统。
5. 通过非接触式和接触式手势检测技术，提供了更自然和直观的用户交互方式。
6. 该方案可应用于MR和AR头戴式设备，以及智能服装等可穿戴设备，为用户提供更丰富的交互体验。
7. 特别适用于需要高精度手势识别的应用场景，如虚拟对象操控、远程控制等，为扩展现实应用带来独特价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358053)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292120)**
<br/><br/>

---


<br/>

### 20. 使用音频分区的虚拟环境缩放

**Title (EN)**: VIRTUAL ENVIRONMENT SCALING USING AUDIO ZONING  
**Pub. No.**: US20260292436

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Pierre Seigneurbieux](https://patents.google.com/?inventor=Pierre+Seigneurbieux&country=US&num=100&sort=new), [Kent Jolly](https://patents.google.com/?inventor=Kent+Jolly&country=US&num=100&sort=new), [Peter James Alexander](https://patents.google.com/?inventor=Peter+James+Alexander&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种实施例包括在本地设备上渲染本地音频流和邻域音频流，其中本地音频流包含由本地音频混音器从多个本地音频源生成的本地音频混合，邻域音频流包含由邻域音频混音器从多个邻域音频源生成的邻域音频混合。一种实施例包括在本地设备上生成一个输出音频流，该音频流包含从与用户共置的音频源收集的音频，该共置音频源与本地设备为其渲染本地音频流和邻域音频流的用户共置。一种实施例包括将输出音频流发送到本地音频混音器。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
音频处理技术领域，具体涉及虚拟环境中的音频分区和音频流管理。

**Background (发明背景)**:  
在虚拟现实和增强现实应用中，音频环境通常需要根据用户的位置和周围环境动态调整。现有的音频处理方法在处理多用户场景或复杂音频环境时存在不足，难以实现精确的音频分区和空间化效果。本发明旨在解决在虚拟环境中实现精确音频分区和动态音频缩放的问题。

**Summary (发明总览)**:  
本发明提出了一种在虚拟环境中通过音频分区实现音频缩放的技术方案。通过在本地设备上处理本地音频流和邻域音频流，并结合共置音频源的输出音频流，本发明能够实现更精确的音频空间化和动态音频缩放。该方法通过分离本地和邻域音频源，并结合用户位置进行音频混合，提供了更沉浸式的音频体验。

**Key Innovation (核心创新)**:  
1. 通过本地音频混音器和邻域音频混音器分别处理本地和邻域音频源，实现音频流的精确分区。
2. 生成包含共置音频源的输出音频流，确保用户周围的音频环境与实际位置一致。
3. 将输出音频流发送回本地音频混音器，实现音频流的动态调整和实时更新。
4. 通过分离处理本地和邻域音频流，减少音频处理的复杂性和延迟，提高音频空间化的精度。
5. 结合用户位置和音频源位置进行音频混合，提供更沉浸式的虚拟环境音频体验。
6. 该技术可应用于虚拟现实、增强现实和多人在线游戏等场景，提供更自然和真实的音频环境。
7. 通过动态调整音频流，实现音频环境的实时缩放，适应用户在不同虚拟环境中的需求。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358401)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292436)**
<br/><br/>

---


<br/>

### 21. 提供安全自动化助手的方法和系统

**Title (EN)**: METHODS AND SYSTEMS FOR PROVIDING A SECURE AUTOMATED ASSISTANT  
**Pub. No.**: US20260288853

**Applicant**: GOOGLE LLC  
**Inventor**: [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new), [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及接收用户输入以调用自动化助手，处理用户输入以确定是否需要从服务器和/或第三方应用程序获取数据以执行助手命令的特定操作，并生成提示以请求用户同意向服务器和/或第三方应用程序发送请求以获取执行特定操作所需的数据。在用户同意的情况下，可以获取数据并用于执行特定操作。在用户不同意的情况下，可以在客户端设备本地生成数据并用于执行助手命令的替代操作。在各种实现中，当用户同意向服务器和/或第三方应用程序发送请求时，可以随请求一起发送指示，表明从客户端设备接收的数据不能被存储（例如，非持久性存储）。换句话说，服务器和/或第三方应用程序可以利用请求中包含的数据生成响应内容，但在生成响应内容后应丢弃请求中包含的数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354446_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及自动化助手技术，具体涉及用户数据安全性和隐私保护领域。

**Background (发明背景)**:  
自动化助手通过与用户进行人机对话来执行任务，但现有技术中，助手要么完全依赖云端资源，要么仅在本地执行，这导致在数据安全性和功能完整性之间存在矛盾。
当助手依赖云端时，用户数据隐私可能受到威胁；而仅在本地执行时，助手的功能可能受限，无法提供最佳结果。
本发明旨在解决这一矛盾，通过动态切换云端和本地执行模式，在保证数据安全的同时提供最佳用户体验。

**Summary (发明总览)**:  
本发明提出了一种安全自动化助手系统，通过以下方式实现：
1. 接收用户输入并识别其中的助手命令。
2. 判断是否需要从服务器或第三方应用获取数据以执行命令。
3. 在需要时，提示用户是否同意发送请求以获取数据。
4. 根据用户同意与否，选择在云端或本地执行操作。
5. 在云端执行时，确保数据不被持久存储。
6. 在本地执行时，利用本地数据提供替代方案。
本发明通过动态切换执行模式，在保证用户数据安全的同时，提供更智能的助手服务。

**Key Innovation (核心创新)**:  
1. 引入基于用户输入和命令类别的动态执行模式切换机制，根据命令类型决定是否需要云端数据支持。
2. 实现用户同意驱动的数据请求机制，只有在用户明确同意的情况下才向服务器或第三方应用发送数据请求。
3. 采用本地数据处理作为云端执行的替代方案，确保在用户拒绝数据请求时仍能提供基本功能。
4. 在云端执行时，通过附加指令确保接收到的用户数据不被持久存储，从而增强隐私保护。
5. 基于机器学习模型对用户输入进行分类和意图识别，以确定命令所属的类别并触发相应的处理流程。
6. 提供细粒度的命令分类体系，例如将搜索查询细分为金融、天气、地点等多个子类别，以实现更精准的隐私控制。
7. 本发明可应用于智能家居、虚拟助手等场景，在保护用户隐私的同时提供更智能、更个性化的服务。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354446)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288853)**
<br/><br/>

---


<br/>

### 22. 领域特定对话式自动化助手

**Title (EN)**: DOMAIN-SPECIFIC CONVERSATIONAL AUTOMATED ASSISTANT  
**Pub. No.**: US20260288791

**Applicant**: GOOGLE LLC  
**Inventor**: [Matthew Sharifi](https://patents.google.com/?inventor=Matthew+Sharifi&country=US&num=100&sort=new), [Maryam Karimzadehgan](https://patents.google.com/?inventor=Maryam+Karimzadehgan&country=US&num=100&sort=new), [Lukas Zilka](https://patents.google.com/?inventor=Lukas+Zilka&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明涉及生成领域特定对话式自动化助手的方法和系统。在一些示例中，使用对话语言模型针对一组领域内训练问题生成目标答案和目标行动建议。在一些示例中，该对话语言模型进一步用于生成其生成的目标答案的后续问题，并为每个生成的后续问题生成目标答案和目标行动建议。在一些示例中，处理系统还生成一组领域外训练示例，包括一个领域外问题、一个预定的目标答案（例如“我不知道”，“我无法回答”）和一个预定的目标行动建议（例如0，“无”）。然后训练自动化助手以预测生成的目标答案和目标行动建议。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354377_1.jpg)

**Technical Field (技术领域)**:  
人工智能领域，专注于对话式语言模型和自动化助手技术。

**Background (发明背景)**:  
机器学习的发展推动了语言模型的进步，但现有技术中的对话模型通常规模庞大且资源消耗高，难以在许多设备上运行。尽管这些模型能够进行开放式的多轮对话，但它们对于自动化助手任务来说可能过于复杂且不必要。本发明旨在解决如何在资源受限的设备上实现高效且功能适当的领域特定对话助手的问题。

**Summary (发明总览)**:  
本发明提出了一种利用大型对话语言模型自动生成领域特定训练数据的方法，以训练更小规模的自动化助手。通过使用大型模型生成单轮和多轮对话的训练示例以及相关的行动建议，可以训练出一个资源需求更小但仍能自然对话的助手。该助手能够理解并响应特定领域的问题，并在必要时建议或执行相关操作，从而在资源受限的设备上实现高效的领域特定对话。

**Key Innovation (核心创新)**:  
1. 使用大型对话语言模型（如LaMDA、GPT-3）生成领域内训练问题和对应的目标答案及行动建议，以构建高质量的训练数据集。
2. 通过生成后续问题并提供相应的目标答案和行动建议，实现多轮对话训练数据的自动生成。
3. 生成领域外训练示例，包括无法回答的问题和相应的预设答案及行动建议，以提高模型的鲁棒性和准确性。
4. 训练一个规模更小的自动化助手，使其能够在特定领域内进行自然对话，并预测何时需要建议或执行操作。
5. 通过比较自动化助手的预测与目标答案和行动建议，计算损失值并调整模型参数，以优化助手的表现。
6. 实现了在资源受限的设备（如手机、平板电脑、智能家居设备）上运行高效对话助手的可能性。
7. 应用于设备操作指导等特定领域场景，提供精准的问答和行动建议，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354377)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288791)**
<br/><br/>

---


<br/>

### 23. 人工智能自动化审查代理流程

**Title (EN)**: ARTIFICIAL INTELLIGENCE-AUTOMATED REVIEW OF AGENTIC FLOWS  
**Pub. No.**: US20260288566

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Duc Minh LE](https://patents.google.com/?inventor=Duc+Minh+LE&country=US&num=100&sort=new), [Neelanjan Hector JACOB](https://patents.google.com/?inventor=Neelanjan+Hector+JACOB&country=US&num=100&sort=new), [Shane Anil PEREIRA](https://patents.google.com/?inventor=Shane+Anil+PEREIRA&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种用于人工智能自动化审查代理流程的计算系统包括处理电路，该电路配置为在人工智能代理中实现代理流程。该代理包括助手、用户代理和审查者。用户代理接收与事件相关的信息以及处理事件的指令。在助手和用户代理之间的第一次对话中，用户代理接收工具推荐，并在执行推荐工具后向助手返回工具响应。助手生成工具响应报告并将其发送给用户代理。在用户代理和审查者之间的第二次对话中，用户代理将工具响应报告发送给审查者，审查者审查工具响应报告中的错误，并在检测到一个或多个错误时将这些错误返回给用户代理。用户代理将这些检测到的错误转发给助手。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354130_1.jpg)

**Technical Field (技术领域)**:  
人工智能；自动化代理流程；多智能体系统

**Background (发明背景)**:  
代理系统利用人工智能模型或代理来执行复杂任务并做出独立决策，无需持续的人工监督。然而，当代理流程中的助手得出错误结论或产生幻觉时，后续的工具调用和响应可能会出错。现有的代理系统通常依赖人工审查和验证来确保准确性，这既耗时又昂贵且难以扩展。本发明旨在解决代理流程中错误检测和修正的自动化问题。

**Summary (发明总览)**:  
本发明提出了一种包含助手、用户代理和审查者的自动化代理流程审查系统。用户代理接收事件信息并执行助手推荐的工具，生成工具响应报告。审查者对工具响应报告进行审查，识别错误并反馈给用户代理。用户代理将错误信息传递给助手以进行修正。该系统通过在代理流程中引入自动化审查机制，提高了AI自动化任务和多代理代理流程的准确性和效率，尤其适用于网络安全等领域。

**Key Innovation (核心创新)**:  
1. 引入了审查者角色作为代理流程中的独立审查模块，能够对助手和用户代理之间的交互进行自动化审查。
2. 通过用户代理将工具响应报告传递给审查者，审查者能够识别代理流程中的错误并反馈给助手，实现错误修正的自动化。
3. 在多代理系统中，每个代理都配备审查者模块，能够对不同方面的代理流程进行独立审查，提高整体系统的可靠性和准确性。
4. 在网络安全领域，审查者能够对安全事件调查流程进行自动化审查，实现无需人工干预的安全事件分类和报告。
5. 通过在代理流程中实时检测和修正错误，减少了错误传播的可能性，提高了AI代理系统的整体效率和准确性。
6. 该系统特别适用于需要高可靠性和准确性的应用场景，如网络安全、金融分析和医疗诊断等。
7. 通过自动化审查机制，本发明能够显著降低人工审查的成本和复杂性，同时提高代理系统的可扩展性和适应性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354130)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288566)**
<br/><br/>

---


<br/>

### 24. 表单字段值预测

**Title (EN)**: FORM FIELD VALUE PREDICTION  
**Pub. No.**: US20260289096

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ali ROUDAKI](https://patents.google.com/?inventor=Ali+ROUDAKI&country=US&num=100&sort=new), [Esin SAKA](https://patents.google.com/?inventor=Esin+SAKA&country=US&num=100&sort=new), [Chuang HE](https://patents.google.com/?inventor=Chuang+HE&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明的一些实施例通过提供预测性输入机制来帮助用户在计算机系统中输入文本或其他数据，以完成表单填写。这些实施例收集用户上下文数据，创建包含至少部分上下文数据的提示，将提示提交给预测器，获取预测器的响应，并提供包含或由预测器响应计算得出的表单字段值建议。一些实施例对上下文数据进行预处理，以验证用户当前是否有权限访问该数据。一些实施例对预测器响应进行后处理，以执行负责任的预测标准、验证用户角色、验证规则或它们的组合。一些实施例包括多个预测器。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354713_1.jpg)

**Technical Field (技术领域)**:  
人工智能；表单自动化；预测性输入技术

**Background (发明背景)**:  
人工智能模型能够提供各种预测，但有时输出结果可能包含错误、误导性或不当内容。现有的表单填写技术虽然利用了AI模型，但在数据安全性和预测准确性方面仍存在不足。本发明旨在解决表单填写过程中数据泄露风险高、预测结果不可靠以及用户体验不佳的问题。

**Summary (发明总览)**:  
本发明通过提供预测性输入机制来优化表单填写过程。其核心思路是收集用户上下文数据，对数据进行预处理以确保权限合规性，然后将其整合到提示中并提交给AI模型。模型返回的响应经过后处理以确保其符合负责任的AI使用标准，并验证其与用户角色和规则的一致性。最终，预测结果被用于自动填充表单字段，从而减少用户填写时间并提高数据安全性。

**Key Innovation (核心创新)**:  
1. 通过收集用户上下文数据并验证其访问权限，确保预测过程中不涉及用户无权访问的数据，从而防止数据泄露。
2. 采用预处理机制，根据上下文数据选择最合适的AI模型作为预测器，以提高预测准确性，例如使用语言模型预测文本摘要。
3. 对AI模型的输出进行后处理，评估其是否符合负责任的AI使用标准，避免向用户展示偏见、毒性或误导性数据。
4. 通过规则验证机制，确保预测结果符合组织或行政角色的限制，例如防止超出用户权限范围的资源请求被提交。
5. 将预测结果与表单字段标签进行负责任使用标准的交叉检查，防止滥用标签值导致模型产生不当输出。
6. 通过减少用户手动输入和验证的时间，提高表单填写效率，同时确保数据安全性和预测结果的可靠性。
7. 本发明可应用于企业级表单解决方案，如Microsoft Power Apps™和Microsoft Dynamics 365™，为用户提供智能化的表单填写体验，同时满足企业数据安全和管理需求。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354713)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289096)**
<br/><br/>

---


<br/>

### 25. 堆叠用户界面层的倾斜导航

**Title (EN)**: TILT NAVIGATION FOR STACKED USER INTERFACE LAYERS  
**Pub. No.**: US20260288256

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Matthew Joseph SANTONE](https://patents.google.com/?inventor=Matthew+Joseph+SANTONE&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本文介绍了一种在智能手机或平板电脑等移动设备上实现堆叠用户界面层倾斜导航的系统。现代移动设备功能强大，已成为许多用户日常生活中不可或缺的一部分。因此，现代软件应用利用日益增长的计算能力和效率，提供大量多样的功能。不幸的是，功能扩展通常会导致用户界面变得笨重、低效和/或使用体验不佳。相比之下，本系统将用户界面组织成层，并在移动设备上以堆叠（例如，堆叠卡片）的形式呈现。通过这种方式，各种用户界面以直观的方式呈现给用户。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487353790_1.jpg)

**Technical Field (技术领域)**:  
移动设备用户界面设计，
倾斜感应交互技术，
多任务处理界面管理

**Background (发明背景)**:  
随着智能手机和平板电脑等移动设备的功能日益强大，用户越来越多地依赖这些设备完成社交、购物、银行甚至商业运营等重要任务。
这导致移动设备上的软件应用功能不断扩展，利用更高的计算能力和效率提供更多功能。
然而，功能扩展也带来了用户界面复杂、效率低下和使用体验不佳的问题。
例如，在社交媒体应用中，用户需要多次切换界面才能完成图片的拍摄、编辑、发布和分享。
这种复杂性在生产力或专业协作应用中可能导致更严重的问题。

**Summary (发明总览)**:  
本发明提出了一种基于倾斜导航的堆叠用户界面层系统，通过将用户界面组织成堆叠的层来简化移动设备上的操作。
用户通过倾斜设备来切换不同的界面层，模拟自然调整视线的方式，从而实现更直观的交互体验。
该系统利用设备上的硬件传感器（如加速度计和陀螺仪）来检测倾斜角度，并根据预设的阈值进行界面切换。
这种设计减少了用户对按钮和菜单的依赖，使多任务处理更加高效和流畅。

**Key Innovation (核心创新)**:  
1. 通过硬件传感器（如加速度计和陀螺仪）检测设备的倾斜角度，实现用户界面层的动态切换。
2. 设置默认设备姿势和阈值偏差，防止误操作，只有在用户明确意图时才进行界面切换。
3. 支持单个应用内不同功能模块的界面层堆叠，以及跨应用的多任务处理配置。
4. 通过调整界面层的透明度来提示用户下方存在其他界面层，但保持其不可交互以避免误操作。
5. 提供平滑的倾斜导航体验，使用户在界面层之间切换时感觉像是在调整视线，而非操作多个屏幕。
6. 应用于社交媒体、邮件、个人规划等应用中，可显著简化复杂操作流程，提高用户效率。
7. 特别适用于需要频繁切换功能模块的生产力和协作工具，为用户提供更直观高效的多任务处理方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487353790)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288256)**
<br/><br/>

---


<br/>

### 26. 基于任务的多任务机器学习模型搜索系统

**Title (EN)**: Search System Having Task-Based Machined-Learned Models  
**Pub. No.**: US20260288891

**Applicant**: Google LLC  
**Inventor**: [Lakshmi Kumar Dabbiru](https://patents.google.com/?inventor=Lakshmi+Kumar+Dabbiru&country=US&num=100&sort=new), [Abhishek Shrivastava](https://patents.google.com/?inventor=Abhishek+Shrivastava&country=US&num=100&sort=new), [Hinali Naimish Marfatia](https://patents.google.com/?inventor=Hinali+Naimish+Marfatia&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明描述了一种基于任务的搜索系统。计算系统可接收来自用户设备的与任务相关的第一用户查询。使用一个或多个机器学习模型，系统可确定与任务相关的第一子任务和第二子任务，其中第一子任务具有较高的第一用户交互得分，第二子任务具有较低的第二用户交互得分。系统可针对第一子任务执行第一次查询搜索，以获取与第一子任务相关的第一内容项；针对第二子任务执行第二次查询搜索，以获取与第二子任务相关的第二内容项。随后，系统可在用户设备的显示屏上呈现第一内容项和第二内容项，并根据第一用户交互得分高于第二用户交互得分，将第一内容项显示在第二内容项之上。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487354488_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及机器学习领域，具体为基于多任务机器学习模型的搜索系统。

**Background (发明背景)**:  
现有搜索系统通常依赖单一查询处理机制，难以有效理解用户任务的复杂性和层次性。传统方法在处理多步骤任务时，无法智能地分解任务并提供相关的内容推荐。此外，现有系统对用户交互数据的利用不足，难以动态调整搜索结果以适应用户需求的变化。本发明旨在解决这些问题，通过多任务机器学习模型实现更智能、更精准的搜索体验。

**Summary (发明总览)**:  
本发明提出了一种基于任务分解和多任务机器学习模型的搜索系统。该系统能够将用户查询分解为多个子任务，并根据用户交互数据确定各子任务的优先级。系统会针对每个子任务执行搜索，并按照交互得分排序展示结果。通过这种方式，系统能够更智能地理解用户意图，提供更精准的搜索结果。此外，系统还集成了强化学习机制，能够根据用户反馈不断优化搜索结果排序。

**Key Innovation (核心创新)**:  
1. 采用多任务机器学习模型，将用户查询智能分解为多个子任务，并确定各子任务的优先级。
2. 基于用户交互数据计算子任务的交互得分，并根据得分对搜索结果进行排序展示。
3. 集成了强化学习机制，通过用户反馈（如点击、滚动等）不断优化搜索结果的排序和展示。
4. 能够从内容提供商获取客户账户的网页资源，并使用机器学习模型将产品与子任务关联。
5. 在内容提供商的用户界面上展示子任务作为潜在的目标，用于赞助内容的精准投放。
6. 系统能够根据用户交互动态更新搜索结果页面，例如在滚动时添加与当前子任务相关的新内容项。
7. 应用于电子商务或内容推荐场景时，可提供更精准的产品推荐和广告投放，提升用户体验和转化率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487354488)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260288891)**
<br/><br/>

---


<br/>

### 27. 利用生成模型生成长篇内容的摘要

**Title (EN)**: UTILIZING GENERATIVE MODEL IN GENERATING SUMMARY OF LONG-FORM CONTENT  
**Pub. No.**: US20260290331

**Applicant**: GOOGLE LLC  
**Inventor**: [Agoston Weisz](https://patents.google.com/?inventor=Agoston+Weisz&country=US&num=100&sort=new), [Michael Andrew Goodman](https://patents.google.com/?inventor=Michael+Andrew+Goodman&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本发明利用大语言模型（LLM）生成长篇内容（如有声书）的摘要。实施例首先判断长篇内容的标记长度是否超过LLM的最大标记长度。如果超过，则将长篇内容或其转录文本分割成至少第一部分和第二部分。基于第一部分生成第一摘要，再结合第一摘要和第二部分生成第二摘要。最终可生成一个包含第一和第二摘要的总体摘要。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487356079_1.jpg)

**Technical Field (技术领域)**:  
自然语言处理领域，具体涉及长篇内容摘要生成技术。

**Background (发明背景)**:  
近年来，数字格式的媒体消费显著增长，例如有声书、播客等长篇音频内容越来越受欢迎。然而，由于时间限制或设备性能限制，用户难以完整消费这些长篇内容。现有的生成模型技术在处理长篇内容时受到标记长度的限制，难以生成有效的摘要。此外，现有技术也无法在摘要中指示原始内容中不同部分对应的语音来源。

**Summary (发明总览)**:  
本发明提出了一种利用生成模型生成长篇内容摘要的方法，通过将长篇内容分割成多个部分并逐段生成摘要，最终整合成总体摘要。具体实现上，首先对长篇内容进行语音识别生成文本，然后根据生成模型的最大处理长度进行分割。对于每个分割后的部分，生成相应的摘要，并结合前一部分的摘要生成下一部分的摘要，最终整合成完整的摘要。本发明解决了现有技术无法处理超长文本的问题，并确保摘要的连贯性和准确性。

**Key Innovation (核心创新)**:  
1. 通过对长篇内容进行分段处理，解决了现有生成模型因标记长度限制无法处理长篇内容的问题。
2. 采用逐步生成摘要的方法，先对第一部分生成摘要，再结合第一部分摘要和第二部分内容生成第二部分摘要，确保摘要的连贯性。
3. 提出了基于最大标记长度的自适应分割策略，可根据生成模型和硬件限制动态调整分割粒度。
4. 在生成后续部分的摘要时，将前一部分的摘要作为上下文输入，确保整体摘要的逻辑性和流畅性。
5. 可对生成模型进行微调，省略显式的指令输入，使模型能够更自然地理解摘要生成任务。
6. 支持将长篇内容分割成多个部分并生成多个子摘要，最终整合成完整的总体摘要。
7. 本发明可应用于有声书、播客、视频等长篇音频或视频内容的摘要生成，为用户节省时间并提供便捷的内容获取方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487356079)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260290331)**
<br/><br/>

---


<br/>

### 28. 使用帧提示生成视频

**Title (EN)**: VIDEO GENERATION USING FRAME PROMPTING  
**Pub. No.**: US20260289847

**Applicant**: GOOGLE LLC  
**Inventor**: [Anthony Lui](https://patents.google.com/?inventor=Anthony+Lui&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
一种从源视频生成新视频的方法包括获取源视频，识别源视频中包含多个连续帧的视频片段，获取对应于不同视频片段的帧子集，通过生成式人工智能（AI）模型生成与每个帧子集对应的新的视频片段，并将这些新的视频片段组合生成包含多个新视频片段的新视频。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487355542_1.jpg)

**Technical Field (技术领域)**:  
数字视频生成技术领域，具体涉及使用生成式人工智能从源视频生成新视频的技术。

**Background (发明背景)**:  
在某些场景下，从源视频中创造性地生成新视频，同时保持源视频的某些特性是很有价值的。例如，在数字广告中，内容提供商可能希望提供多样化的主题视频广告以吸引观众或测试不同版本的效果。然而，现有生成式AI模型在生成新视频时容易偏离源视频的上下文或产生荒谬内容。

**Summary (发明总览)**:  
本发明提出了一种基于源视频生成新视频的系统和方法。该方法通过"帧提示"技术识别源视频中的视频片段，并从每个片段中选择部分帧作为输入提供给生成式AI模型，从而生成新的视频片段。这些新片段与源视频片段结合，生成一个整体上更贴合源视频上下文的新视频。这种方法既保持了源视频的风格和内容边界，又为生成式AI提供了创造性的发挥空间。

**Key Innovation (核心创新)**:  
1. 采用帧提示技术，通过选择源视频中多个视频片段的帧子集作为输入，生成与源视频上下文更一致的新视频。
2. 使用生成式AI模型（如多模态大语言模型）处理帧子集，生成新的视频片段，从而实现对源视频的创造性编辑。
3. 通过仅使用源视频片段的部分帧作为输入，在保持源视频风格的同时，为生成式AI提供更大的创作自由度。
4. 相比传统方法，本发明通过跨多个视频片段的帧子集生成新视频，有效减少了生成内容偏离源视频上下文或出现荒谬内容的问题。
5. 在数字广告场景中，本发明能够更好地保留源视频中已被验证为有效的风格或主题，同时允许生成式AI探索新的创意变体以提升广告效果。
6. 通过将源视频片段与新生成视频片段结合，本发明提供了一种灵活的视频生成方案，既能保持源视频的核心特质，又能引入创新元素。
7. 本专利可应用于视频广告、影视制作和内容创作等领域，为视频创作者提供更高效、更具创意的视频生成工具。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487355542)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260289847)**
<br/><br/>

---


<br/>

### 29. 通过自动化助手命令实现条件化相机控制

**Title (EN)**: CONDITIONAL CAMERA CONTROL VIA AUTOMATED ASSISTANT COMMANDS  
**Pub. No.**: US20260292332

**Applicant**: GOOGLE LLC  
**Inventor**: [Felix Weissenberger](https://patents.google.com/?inventor=Felix+Weissenberger&country=US&num=100&sort=new), [Balint Miklos](https://patents.google.com/?inventor=Balint+Miklos&country=US&num=100&sort=new), [Victor Carbune](https://patents.google.com/?inventor=Victor+Carbune&country=US&num=100&sort=new)  
**Publication Date**: 24.09.2026

**Abstract**:  
本文所述的实施例涉及一种自动化助手，该助手能够根据用户指定的一个或多个条件来控制相机。当自动化助手检测到特定环境特征出现时，条件即可满足。通过这种方式，用户可以依赖自动化助手来识别和捕捉特定时刻，而无需持续监控相机的取景窗口。在某些实施例中，自动化助手捕获媒体数据的条件可以基于与自动化助手相关联的应用数据和其他上下文数据。例如，相机取景窗口中的内容与其他应用界面内容之间的关系可以作为一个条件。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
智能相机控制技术；自动化助手应用；
环境感知与条件触发技术

**Background (发明背景)**:  
随着智能相机和自动化助手的普及，用户对相机自动捕捉功能的需求日益增长。
现有技术中，相机控制通常依赖用户手动操作或预设的简单触发条件。
这导致用户需要持续关注相机画面，难以捕捉到意外或特定时刻。
本发明旨在解决这一问题，通过引入更智能的条件触发机制来自动控制相机。

**Summary (发明总览)**:  
本发明提出了一种基于自动化助手的智能相机控制系统，通过用户定义的条件来自动捕捉特定场景。
该系统能够识别环境特征、应用数据或上下文信息，并基于这些信息判断是否满足预设条件。
当条件满足时，自动化助手将自动控制相机进行拍摄，无需用户持续干预。
相较于传统方法，本发明提供了更智能、更精准的自动捕捉能力，提升了用户体验。
该系统特别适用于需要捕捉特定场景或事件的应用场景，如家庭监控、运动记录等。

**Key Innovation (核心创新)**:  
1. 通过自动化助手实现相机控制的智能化，用户可预设环境特征作为触发条件，例如特定物体出现或特定声音被检测到。
2. 引入应用数据和上下文信息的集成分析，例如将相机画面内容与其他应用界面的内容进行关联，以实现更精准的条件触发。
3. 提供灵活的触发条件设置，用户可以根据需求自定义条件组合，例如时间、地点、人物等多种条件的逻辑组合。
4. 采用机器学习算法优化环境特征识别能力，提高对复杂场景的识别准确率。
5. 实现自动化捕捉与用户通知的无缝对接，例如在检测到特定事件时自动启动录像或拍照功能。
6. 应用于家庭监控、运动记录等场景，能够在关键时刻自动捕捉重要画面，减少用户操作负担。
7. 通过自动化助手与相机的深度整合，提供更智能、更便捷的拍摄体验，特别适合需要高效捕捉特定场景的用户。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487358287)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260292332)**
<br/><br/>

---


<br/>

### 30. 物料搬运设备中堵塞包裹的解堵机制

**Title (EN)**: Mechanism(s) for de-jamming packages within material handling equipment (MHE)  
**Pub. No.**: US12741819

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Nivedita Ravi](https://patents.google.com/?inventor=Nivedita+Ravi&country=US&num=100&sort=new), [Fernando Ruch](https://patents.google.com/?inventor=Fernando+Ruch&country=US&num=100&sort=new), [Moses Trevor Dardik](https://patents.google.com/?inventor=Moses+Trevor+Dardik&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
本发明涉及一种系统，包括一个或多个解堵机构，该机构配置有楔形部件，能够从缩回状态移动到伸出状态，其中楔形部件至少部分地插入用于处理包裹的物料搬运设备中。该系统接收与物料搬运设备中包裹相关的数据，并在第一时间点使楔形部件从缩回状态移动到伸出状态，并在第二时间点使楔形部件从伸出状态返回缩回状态。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487046047_1.jpg)

**Technical Field (技术领域)**:  
物料搬运技术领域，具体涉及自动化解堵系统。

**Background (发明背景)**:  
现代仓库、配送中心、机场和制造设施等环境中广泛使用物料搬运设备（如滑槽）来转移物品。然而，在滑槽的弯道处或滑槽与传送带的交汇处，物品容易发生堵塞、堆积或卡住。这种堵塞问题也出现在传送带、漏斗、滑道等其他类型的物料搬运设备中。堵塞会导致处理效率下降，通常需要人工干预才能清除，并可能造成物品积压。

**Summary (发明总览)**:  
本发明提出了一种自动化解堵系统，通过在物料搬运设备中引入可移动的楔形部件来缓解堵塞问题。该系统通过接收包裹数据，智能控制楔形部件的伸缩动作，在堵塞发生时自动介入并清除障碍。相较于传统的人工干预方式，本发明能够提高处理效率，减少停机时间，并降低人工成本。

**Key Innovation (核心创新)**:  
1. 设计了一种可伸缩的楔形解堵机构，能够在物料搬运设备中自动移动以清除堵塞。
2. 系统通过接收包裹数据，实时监测物料搬运设备的状态，并在检测到堵塞时触发解堵机制。
3. 楔形部件的移动路径和伸出深度经过优化设计，以确保在清除堵塞的同时不会对包裹造成损坏。
4. 采用时间点控制策略，在第一和第二时间点分别控制楔形部件的伸出和缩回，实现精确的解堵操作。
5. 该系统可应用于多种类型的物料搬运设备，包括滑槽、传送带、漏斗和滑道等，具有广泛的适用性。
6. 通过自动化解堵机制，减少了人工干预的需求，提高了物料搬运的整体效率和可靠性。
7. 适用于高流量物流环境，能够有效防止因堵塞导致的停机问题，提升整体运营效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487046047)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12741819)**
<br/><br/>

---


<br/>

### 31. 用于将物品引入环境的站点

**Title (EN)**: Station for inducting item(s) into environment  
**Pub. No.**: US12745012

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Timothy Joseph Jordan](https://patents.google.com/?inventor=Timothy+Joseph+Jordan&country=US&num=100&sort=new), [Allan Katz](https://patents.google.com/?inventor=Allan+Katz&country=US&num=100&sort=new), [Christopher James Thomas](https://patents.google.com/?inventor=Christopher+James+Thomas&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
一种用于将物品引入环境的站点。该站点包括一个用于接收物品的箱体模块，物品可能包装在盒子中，并配有用于扫描盒子的传感器。站点中的摄像头和照明模块可以在物品从盒子中取出并转移到位于托盘模块上的一个或多个托盘中时读取物品。物品可能会经过摄像头和照明模块，然后被放置到托盘中。传感器用于确定物品被放置到哪一个或多个托盘中。当托盘装满时，托盘可以被引入环境进行存储、订单履行等。该站点可用于方便地将物品从盒子中取出并放置到允许自动存储的托盘中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487049556_1.jpg)

**Technical Field (技术领域)**:  
物流自动化领域，具体涉及物品分拣与存储技术。

**Background (发明背景)**:  
随着电子商务的兴起，订单履行、包装和运输的需求显著增加。零售商需要以更快的速度补货，但现有技术无法有效应对补货速度的提升，导致错误和效率低下。现有系统难以在高速运转的同时保持准确性。

**Summary (发明总览)**:  
本发明提出了一种自动化站点，用于将物品从包装盒中取出并转移到托盘中，以便后续存储或订单履行。该系统通过传感器扫描包装盒，摄像头和照明模块识别物品，并使用传感器追踪物品放置到托盘的位置。当托盘装满时，系统自动将其引入存储环境。该发明通过自动化流程减少了人工操作，提高了物品分拣和存储的效率和准确性。

**Key Innovation (核心创新)**:  
1. 采用箱体模块接收包装盒，并通过传感器扫描包装盒以识别物品信息，确保物品在转移过程中的可追溯性。
2. 集成摄像头和照明模块，在物品从包装盒中取出时进行实时识别和验证，提高分拣准确性。
3. 使用托盘模块接收物品，并通过传感器追踪物品放置到托盘的位置，实现对托盘装填状态的精确监控。
4. 设计了自动化的托盘引入机制，当托盘装满时，系统自动将其引入存储环境，减少人工干预。
5. 通过模块化设计，站点可以灵活配置以适应不同规模和类型的物品处理需求。
6. 该系统特别适用于电子商务仓库，能够有效应对高速订单履行环境下的物品分拣和存储需求。
7. 通过减少人工操作和错误，该发明提高了物流中心的整体效率和可靠性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487049556)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12745012)**
<br/><br/>

---


<br/>

### 32. 高压釜固化夹具

**Title (EN)**: Autoclave curing jig  
**Pub. No.**: US12741432

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [John Lockleer](https://patents.google.com/?inventor=John+Lockleer&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
本发明涉及用于制造具有光滑凸面的碳纤维部件的装置、组件和工艺。通过在芯模（内模）上缠绕纤维和树脂来形成未固化部件。在未固化部件上放置一个或多个压板以及可选的垫片，使其与芯模上的特征对齐。将组件封装在真空袋中并固化。将组件放置在夹具底座上，并通过压缩部件将组件夹持在底座之间。压缩部件对压板施加压力，在固化过程中将未固化部件压向芯模，从而形成光滑的表面效果。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487045620_1.jpg)

**Technical Field (技术领域)**:  
碳纤维复合材料制造领域，具体涉及使用内模制造具有高表面质量要求的碳纤维部件的工艺和设备。

**Background (发明背景)**:  
碳纤维部件的低产量生产通常耗时且成本高。现有技术主要采用两种方法：一种使用分体式外模，另一种使用内模（芯模）。外模方法成本高且复杂，而内模方法虽然成本低且准备时间短，但难以获得非常光滑的外部表面。本发明旨在解决使用内模制造碳纤维部件时难以获得高表面质量的问题。

**Summary (发明总览)**:  
本发明提出了一种通过内模制造碳纤维部件的新方法，通过在固化过程中对部件施加精确的压缩力来获得光滑的表面效果。该方法使用压板和垫片来确保部件与内模的紧密接触，并通过真空袋和夹具系统来均匀分布压力，从而在不使用复杂外模的情况下实现高质量的表面光洁度。

**Key Innovation (核心创新)**:  
1. 采用内模（芯模）作为基础，通过在芯模上缠绕纤维和树脂来形成未固化部件，降低了模具成本和准备时间。
2. 使用压板和垫片来确保未固化部件与芯模的紧密接触，并通过精确对齐来保证部件的形状精度。
3. 通过真空袋封装组件，并在固化过程中使用夹具系统对压板施加均匀的压力，从而实现对未固化部件的均匀压缩。
4. 在固化过程中，通过压缩部件对压板施加可控的压力，确保部件表面光滑且符合高公差要求。
5. 该方法结合了内模的低成本优势和精确压缩技术，解决了传统内模方法难以获得高表面质量的问题。
6. 适用于需要高表面质量且产量较低的应用场景，如航空航天和高端体育器材制造。
7. 通过减少对复杂外模的依赖，降低了生产成本和制造周期，同时保证了部件的强度和表面质量。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487045620)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12741432)**
<br/><br/>

---


<br/>

### 33. 用于从分格存储单元中抓取物体的机器人工具及方法

**Title (EN)**: Robotic tool and process for picking objects from compartmented storage units  
**Pub. No.**: US12741816

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Roc Arandes Vilagrasa](https://patents.google.com/?inventor=Roc+Arandes+Vilagrasa&country=US&num=100&sort=new), [Can Erdogan](https://patents.google.com/?inventor=Can+Erdogan&country=US&num=100&sort=new), [Johannes Kulick](https://patents.google.com/?inventor=Johannes+Kulick&country=US&num=100&sort=new)  
**Publication Date**: 22.09.2026

**Abstract**:  
描述了使用末端执行器从容器中抓取物品的系统和技术。一个示例系统包括一个包含多个容器的货架。每个容器被配置用于容纳一个或多个物品。该系统还包括一个具有末端执行器的机械臂，该末端执行器用于从一个或多个容器中抓取目标物品。末端执行器包括：(i) 平行布置的第一和第二板，以及 (ii) 位于第一和第二板之间的可伸缩吸盘。末端执行器被配置为延伸可伸缩吸盘以接触目标物品，与目标物品形成密封，在形成密封后，收缩可伸缩吸盘以从容器中移除目标物品，并在收缩可伸缩吸盘后...

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-09/US487046044_1.jpg)

**Technical Field (技术领域)**:  
机器人技术；自动化仓储；末端执行器设计

**Background (发明背景)**:  
许多设施（如仓库、工厂、配送中心等）执行物品存放、拣选、运输等任务。这些设施通常使用各种运输设备（如手推车、容器、托盘、箱子等）将物品运输到设施内外不同位置。由于物品种类繁多且尺寸各异，物品在容器中的排列方式也各不相同，因此设计一个能够可靠地从已有多种物品的容器中抓取物品的机器人末端执行器存在困难。

**Summary (发明总览)**:  
本发明提出了一种用于从分格存储单元中抓取物品的机器人工具及方法。其核心思路是设计一个具有可伸缩吸盘的末端执行器，通过平行板结构与吸盘协同工作，实现对目标物品的精确定位和抓取。该方法通过吸盘与物品的密封接触，确保抓取过程的稳定性和可靠性，相较于传统方法提高了抓取不同尺寸和形状物品的适应性。

**Key Innovation (核心创新)**:  
1. 采用平行布置的第一和第二板结构，为吸盘提供稳定的支撑和定位，确保抓取过程中的精确定位。
2. 设计可伸缩吸盘，能够根据物品尺寸和形状进行自适应调整，实现对不同类型物品的有效抓取。
3. 通过吸盘与目标物品的密封接触，确保抓取过程中的稳定性和可靠性，避免物品滑落或损坏。
4. 末端执行器能够在抓取后收缩吸盘，将目标物品从容器中移除，操作过程流畅且高效。
5. 该设计适用于包含多种尺寸和形状物品的复杂存储环境，扩展了机器人在仓储和物流中的应用场景。
6. 通过优化吸盘和板结构，减少了对复杂传感器和算法的依赖，降低了系统成本和复杂性。
7. 该技术可应用于自动化仓储和配送中心，提高物品拣选效率，减少人工操作需求。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US487046044)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12741816)**
<br/><br/>

---



**Total Patents**: 33  
**Last Updated**: 20260927

---

The Patent Scoop Trio
