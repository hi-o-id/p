---
layout: post
title: "其他专利小快报 2026-08-29"
date: 2026-08-30 01:08:22 +0800
categories: 其他
---

**New Patents**: 43  

---


<br/>

### 1. 支持视觉描述性文本查询

**Title (EN)**: SUPPORTING VISUALLY DESCRIPTIVE TEXT QUERIES  
**Pub. No.**: US20260252623

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Arnab Dhua](https://patents.google.com/?inventor=Arnab+Dhua&country=US&num=100&sort=new), [Venkata Vijaya Bhargava Punnamaraju](https://patents.google.com/?inventor=Venkata+Vijaya+Bhargava+Punnamaraju&country=US&num=100&sort=new), [Vamsi Salaka](https://patents.google.com/?inventor=Vamsi+Salaka&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明公开了支持多模态搜索的方法，包括确定何时使用多模态搜索可能有益，并提示用户使用多种搜索方式。在至少一个实施例中，用户输入的文本查询会被分析，以确定该查询是否至少部分地视觉描述了搜索目标。如果是，则提示用户提供另一种类型的搜索标准，例如代表搜索目标的图像。该图像可以由用户拍摄或上传，也可以基于搜索查询从推荐图像集中选择，或使用至少包含搜索查询的信息生成。一旦提供，图像数据中的相关图像特征将被提取，并与文本查询一起用于定位相关内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570316_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及信息检索领域，具体为多模态搜索技术，包括文本和图像特征的联合搜索。

**Background (发明背景)**:  
在许多情况下，用户使用基于文本的查询来搜索内容，例如产品信息或文章。然而，当用户尝试描述具有视觉特征的对象时，传统的基于文本的搜索索引通常无法有效处理视觉描述性术语，导致搜索结果质量较差。此外，用户可能不知道或不了解其他搜索方式的存在，或者不知道何时使用这些方式更有效。本发明旨在解决现有技术中视觉描述性文本查询搜索结果不准确的问题。

**Summary (发明总览)**:  
本发明提出了一种多模态搜索方法，通过分析用户输入的文本查询以确定其是否包含视觉描述性内容，并在必要时提示用户补充其他类型的搜索信息，例如图像。系统会提取图像特征并与文本查询结合使用，以提高搜索结果的准确性。用户可以修改或更新查询和图像信息，以获得更相关的搜索结果。该方法适用于多种搜索界面和应用场景，如移动应用、网站和AI助手。

**Key Innovation (核心创新)**:  
1. 通过轻量级分类器实时分析用户输入的文本查询，判断其是否包含视觉描述性内容，从而确定是否需要补充其他搜索方式。
2. 利用大语言模型（LLM）的中间层推理结果训练分类器，以提高对视觉描述性文本的识别准确性。
3. 提示用户通过拍摄、上传或选择推荐图像等方式提供图像数据，并使用编码器模型提取相关图像特征。
4. 将文本查询和图像特征转换为搜索向量或潜在空间中的点，以实现更精准的内容定位。
5. 提供用户界面，允许用户修改或更新文本查询和图像信息，以获得动态调整的搜索结果。
6. 该方法可应用于多种搜索场景，如电子商务平台、在线服务和AI助手，提升搜索结果的相关性和用户满意度。
7. 通过结合文本和图像特征，本发明解决了传统文本搜索在处理视觉描述性查询时的不足，为用户提供更直观和准确的搜索体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570316)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252623)**
<br/><br/>

---


<br/>

### 2. 在协作会话中图形化表示人工智能代理参与者

**Title (EN)**: GRAPHICALLY REPRESENTING AN AI AGENT PARTICIPANT IN A COLLABORATION SESSION  
**Pub. No.**: US20260253296

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Daniel ROSENSTEIN](https://patents.google.com/?inventor=Daniel+ROSENSTEIN&country=US&num=100&sort=new), [Richard Jason ORTEGA](https://patents.google.com/?inventor=Richard+Jason+ORTEGA&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本系统实施了一种技术，用于在至少一个人类参与者、至少一个机器人设备参与者和至少一个人工智能代理参与者之间执行协作会话。该协作会话可以与在地理环境中完成的任务相关联。系统根据不同类型（例如，通用型人工智能代理参与者、特定型人工智能代理参与者）图形化表示协作会话中的人工智能代理参与者。这种图形化表示确保了协作的顺畅性，并为人类参与者提供了视觉反馈元素，以指示哪些人工智能代理参与者正在积极参与以及这些参与者目前在协作会话中的具体操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571057_1.jpg)

**Technical Field (技术领域)**:  
协作机器人技术领域，具体涉及人工智能代理与机器人设备协作执行任务。

**Background (发明背景)**:  
机器人设备在现代社会中应用日益广泛，其执行的任务也愈发复杂和相互关联。然而，现有系统难以有效协调机器人设备完成复杂任务，特别是在多组织、多设备协作的场景中。
此外，在应对如自然灾害等大规模事件时，不同组织的人员和设备难以高效协作。

**Summary (发明总览)**:  
本发明提出了一种协作会话系统，通过图形化表示人工智能代理参与者，促进人类、机器人设备和人工智能代理之间的协作。该系统允许不同组织使用异构机器人设备的人员通过中央系统快速连接并协作完成任务。人工智能代理作为接口，提供了任务协调和执行的支持。
系统通过机器人代理（robot agent）使机器人设备能够参与协作会话，并支持多种传感器数据的传输。协作会话适用于不同规模的任务，从小型办公室任务到大规模灾害响应均可应用。

**Key Innovation (核心创新)**:  
1. 通过图形化界面直观展示人工智能代理参与者的类型和状态，帮助人类参与者快速了解协作动态。
2. 引入机器人代理（robot agent），使机器人设备能够通过下载和安装该代理参与协作会话，并支持多种传感器数据的传输。
3. 设计了基于任务的协作框架，将任务分解并分配给不同的人类和机器人角色，确保协作的高效性。
4. 实现了异构机器人设备之间的无缝协作，即使这些设备原本不具备相互通信的能力。
5. 通过人工智能代理提供智能协调功能，减少人类对机器人设备工作细节的认知负担，提高协作效率。
6. 支持多组织、多设备的大规模协作，特别适用于灾害响应等复杂场景。
7. 适用于从小型办公室任务到大规模灾害响应等多种应用场景，为不同规模的任务提供灵活的协作解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571057)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253296)**
<br/><br/>

---


<br/>

### 3. 辅助摄影构图系统

**Title (EN)**: AIDED SYSTEM OF PHOTOGRAPHY COMPOSITION  
**Pub. No.**: US20260255053

**Applicant**: Google LLC  
**Inventor**: [John CHANG](https://patents.google.com/?inventor=John+CHANG&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种媒体应用从服务器接收一组构图类型中的第一种构图类型的标识，用于应用在用户设备捕获的初始图像上。当检测到初始图像中有一个或多个人时，媒体应用生成一个修改后的图像，即从初始图像中移除一个或多个人以获得修改后的图像。媒体应用根据第一种构图类型的相应构图规则对修改后图像中的至少一个候选位置进行评分。媒体应用在用户设备的取景器上提供图形引导，以指导用户拍摄最终图像，其中图形引导指示了最终图像中一个或多个人推荐的位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485572995_1.jpg)

**Technical Field (技术领域)**:  
图像处理技术领域，具体涉及智能摄影构图辅助技术。

**Background (发明背景)**:  
随着移动设备普及，用户拍摄并分享照片的需求日益增长。然而，手动构图存在诸多困难，如建筑物倾斜、对象失焦等。此外，用户设备进行高强度计算也存在限制。现有的摄影辅助工具难以动态调整构图以适应拍摄场景的变化。

**Summary (发明总览)**:  
本发明提供了一种智能摄影构图系统，通过服务器和用户设备协作实现动态构图辅助。系统首先根据用户设备位置选择合适的构图类型，并生成去除人物的修改图像以分析构图效果。随后，系统基于构图规则对候选位置进行评分，并通过取景器提供图形引导，帮助用户调整拍摄角度和人物位置，最终实现理想构图。相较于传统方法，本发明能够动态调整构图建议，适应拍摄场景的变化。

**Key Innovation (核心创新)**:  
1. 通过服务器根据用户设备地理位置选择合适的构图类型，实现个性化构图建议。
2. 生成去除人物的修改图像以简化构图分析，并基于全景图像数据提供构图参考。
3. 利用全景图像的显著性地图和构图评分，为候选位置提供精确评分。
4. 根据人物高度和拍摄距离调整人物在修改图像中的大小，确保构图合理性。
5. 通过取景器提供实时图形引导，并根据用户设备移动动态更新推荐构图位置。
6. 在用户裁剪图像时，将显著性点作为元数据存储，确保重要元素不被遗漏。
7. 本发明可应用于智能相机应用，为用户提供实时构图建议，提升拍摄体验，尤其适用于旅游摄影和风景拍摄场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485572995)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260255053)**
<br/><br/>

---


<br/>

### 4. 使用扩散模型生成视频

**Title (EN)**: GENERATING VIDEOS USING DIFFUSION MODELS  
**Pub. No.**: US20260253399

**Applicant**: Google LLC  
**Inventor**: [Jonathan Ho](https://patents.google.com/?inventor=Jonathan+Ho&country=US&num=100&sort=new), [Tim Salimans](https://patents.google.com/?inventor=Tim+Salimans&country=US&num=100&sort=new), [Alexey Alexeevich Gritsenko](https://patents.google.com/?inventor=Alexey+Alexeevich+Gritsenko&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明涉及一种用于生成基于输入条件的输出视频的方法、系统及装置，包括编码在计算机存储介质上的计算机程序。在一个方面，该方法包括接收输入；初始化当前中间表示；通过在多个迭代中更新当前中间表示来生成输出视频，其中每次更新包括：使用配置为处理中间输入以生成噪声输出的扩散模型处理当前中间表示的迭代中间输入；并使用该迭代的噪声输出更新当前中间表示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571171_1.jpg)

**Technical Field (技术领域)**:  
本发明属于视频生成技术领域，具体涉及基于扩散模型的视频生成技术。

**Background (发明背景)**:  
机器学习模型通过接收输入并基于输入生成输出，例如预测输出。一些机器学习模型是参数化模型，基于输入和模型参数值生成输出；一些是深度模型，通过多层模型处理输入生成输出。现有的基于扩散的视频生成系统通常使用图像扩散模型逐帧预测视频帧，例如使用循环神经网络自回归预测视频的下一帧。这种方法可能导致生成的视频与输入视频之间缺乏时间一致性。

**Summary (发明总览)**:  
本发明提出了一种基于扩散神经网络生成视频的系统。该系统通过联合建模整个视频或帧块，并使用3D视频架构生成视频，从而实现比现有系统更高的感知质量。系统使用由输入视频引导调整的扩散模型，能够生成具有时间一致性的较长视频。系统还支持视频预测、条件视频生成和无条件视频生成等多种任务，并利用图像和视频数据联合训练扩散模型以提高样本质量。

**Key Innovation (核心创新)**:  
1. 采用3D视频架构联合建模整个视频或帧块，而非逐帧预测，从而提高视频的感知质量。
2. 使用由输入视频引导调整的扩散模型，确保生成的较长视频与输入视频之间的时间一致性。
3. 通过联合训练扩散模型，利用图像和视频数据增加训练数据的多样性和数量，提升模型性能。
4. 采用因式分解的时空注意力机制，使模型能够高效处理视频和独立图像，简化训练过程并节省计算资源。
5. 支持条件视频生成，例如文本条件下的视频生成，通过修改扩散采样器生成反映文本内容的视频。
6. 在训练过程中，系统能够仅使用视频的一小部分帧进行训练，从而降低训练成本并提高效率。
7. 该技术可应用于视频预测、长视频生成等领域，为需要高质量视频生成的应用场景提供高效解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571171)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253399)**
<br/><br/>

---


<br/>

### 5. 感官分组计时器的增强控制方法

**Title (EN)**: ENHANCED CONTROLS FOR SENSORY GROUP TIMERS  
**Pub. No.**: US20260252301

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Edward Richard EUCLIDE](https://patents.google.com/?inventor=Edward+Richard+EUCLIDE&country=US&num=100&sort=new), [Defne KUDELA](https://patents.google.com/?inventor=Defne+KUDELA&country=US&num=100&sort=new), [Tiphanie LAU](https://patents.google.com/?inventor=Tiphanie+LAU&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明提供了一种用于感官分组计时器的增强控制技术。在线会议中，系统允许用户指定一个由部分参会者组成的子组。该子组可以是会议中进行演示的参会者子集、在线谈判会议中的保密子组，或任何其他希望仅向其显示私有分组计时器的子组，同时仍与子组外的其他参会者保持沟通。系统允许子组内的参会者控制仅在指定子组内共享的分组计时器。在线会议中，分组计时器仅向子组显示，而不会向子组外的其他用户显示计时器存在的通知。当子组与其他参会者共享内容、视频流、音频流、文件及/或聊天消息时，系统利用权限防止分组计时器显示在子组外人员的设备上。系统还提供感官适配功能，包括对视觉通知、声音和触觉的定制，这些都比传统计时器视觉化的干扰更小。在某些实施例中，系统可以生成集成到用户界面框架中的动画，或配置为用户界面背景中的半透明水印图像的动画。这些动画以不引人注目的方式显示计时器的进度，而无需使用侵入性通知或占用大量屏幕空间。例如，本发明将日出动画集成到用户界面框架中以表示分组计时器的开始，将日落动画表示特定时间段的结束。在另一个示例中，会议用户界面的背景图像可能显示一个从白天场景过渡到夜间场景的城市图像，以指示计时器已达到特定时间段的结束。这些动画可以与微妙的音效和触觉反馈相结合，为特定参与者提供通知。本发明允许系统提供计时器状态，同时最大限度地减少屏幕空间的使用，并为共享内容留出更多空间。这些技术还适应了对强光或其他干扰性通知敏感的参与者。此外，本发明生成的动画使用户能够轻松查看其特定任务的计时器状态，而无需会议参与者花时间计算他们还剩多少时间用于会议的具体环节。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569966_1.jpg)

**Technical Field (技术领域)**:  
在线会议技术领域，具体涉及感官分组计时器的控制方法。

**Background (发明背景)**:  
现有的协作系统允许用户通过视频流、音频流、共享文件、聊天消息等方式进行沟通，但缺乏有效的工具来帮助会议参与者协调特定任务。例如，一些系统只有一个集中式会议计时器，无法为多个演示者提供共享的时间感知。此外，集中式计时器要求每个演示者反复计算剩余时间并与其他演示者协调，这会分散演示的注意力并对观众造成干扰。一些系统允许用户使用计时器应用程序，但这会占用大量屏幕空间并可能对某些参与者造成干扰。如果子组与其他参会者进行谈判，则不希望共享子组之间的计时器状态。传统的计时器显示还会产生干扰性通知，通常缺乏感官适配。

**Summary (发明总览)**:  
本发明提出了一种用于在线会议的感官分组计时器控制方法，允许用户指定一个子组并控制仅在该子组内共享的计时器。该方法通过权限控制确保计时器仅对子组成员可见，并通过定制化的视觉、声音和触觉通知提供感官适配，减少干扰。本发明还集成了动画效果，以直观且不显眼的方式显示计时器状态，从而提高用户体验并减少对会议进程的干扰。

**Key Innovation (核心创新)**:  
1. 允许用户指定会议中的子组，并控制仅在该子组内共享的分组计时器。
2. 通过权限控制确保分组计时器仅对子组成员可见，防止子组外的用户看到计时器通知。
3. 提供定制化的视觉、声音和触觉通知，以减少对会议进程的干扰，并适应对强光或其他干扰性通知敏感的参与者。
4. 集成了动画效果，例如日出和日落动画，以直观且不显眼的方式显示计时器状态。
5. 动画可以配置为用户界面框架的一部分或作为半透明水印图像集成到背景中，最大限度地减少屏幕空间的使用。
6. 通过动画和微妙的音效协调，为特定参与者提供通知，而不会干扰其他参会者。
7. 本发明适用于在线会议中的演示协调、保密谈判等场景，能够在不分散注意力的情况下提供有效的计时器控制。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569966)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252301)**
<br/><br/>

---


<br/>

### 6. 使多个客户端设备的显示器能够与虚拟机交互的技术

**Title (EN)**: ENABLING DISPLAYS FROM MULTIPLE CLIENT DEVICES TO INTERACT WITH A VIRTUAL MACHINE  
**Pub. No.**: US20260252367

**Applicant**: Microsoft Technology Licensing, LLC.  
**Inventor**: [Sandeep PATNAIK](https://patents.google.com/?inventor=Sandeep+PATNAIK&country=US&num=100&sort=new), [Andrew Charles HAMMOND](https://patents.google.com/?inventor=Andrew+Charles+HAMMOND&country=US&num=100&sort=new), [Jordan Emil MARCHESE](https://patents.google.com/?inventor=Jordan+Emil+MARCHESE&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本文描述的技术使远程桌面应用程序能够向多个客户端设备关联的显示器提供视觉内容，而不仅限于作为活动端点的主客户端设备。远程桌面软件允许用户从远程位置访问和控制计算机或服务器。通常，远程桌面会话仅限于通过与主客户端通信连接的显示器显示内容。本文所述的技术扩展了显示选项，包括用户其他安装了远程桌面应用程序的客户端设备的显示器。例如，用户可以在主客户端上访问虚拟机，但使用辅助客户端的屏幕查看虚拟机提供的额外内容。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570036_1.jpg)

**Technical Field (技术领域)**:  
远程桌面技术；多设备显示协同；虚拟化计算

**Background (发明背景)**:  
现代操作系统能够将内容显示在多个外部显示器上，但远程桌面会话通常仅限于与主客户端直接连接的显示器。现有的远程桌面技术无法充分利用用户拥有的其他设备显示器，这限制了用户在使用远程桌面时的可视范围和工作效率。

**Summary (发明总览)**:  
本发明通过远程桌面应用程序实现了跨多个客户端设备的显示协同，允许用户将虚拟机的视觉内容扩展到其他设备的显示器上。该技术通过识别用户设备上的可用显示器，并允许用户选择这些显示器来扩展显示选项。实现方式包括主客户端和辅助客户端之间的连接管理，以及虚拟机的显示发现功能。相较于传统远程桌面技术，本发明提供了更灵活的多设备显示解决方案。

**Key Innovation (核心创新)**:  
1. 实现了远程桌面应用程序对多个客户端设备显示器的支持，通过主客户端和辅助客户端的协同工作来扩展显示选项。
2. 引入了三种连接类型：全连接、图形连接和后台连接，以适应不同的使用场景和设备性能需求。
3. 通过后台连接保持对非活动客户端设备的监控，确保在需要时能够快速建立全连接或图形连接。
4. 提供了图形模式和非图形模式两种运行模式，以优化不同类型客户端设备的资源使用和显示效果。
5. 实现了基于距离阈值的显示选择机制，通过限制辅助客户端设备的选择范围来增强安全性，防止意外的内容泄露。
6. 在主客户端上提供显示选择界面，用户可以通过该界面选择并使用辅助客户端设备上的显示器。
7. 该技术可应用于虚拟桌面基础设施（VDI）和云计算平台，为用户提供更灵活、安全的多设备显示解决方案，特别适用于需要多屏协作的办公场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570036)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252367)**
<br/><br/>

---


<br/>

### 7. 用于指示对象以补充生成式输出请求的交互式图形用户界面元素

**Title (EN)**: INTERACTIVE GUI ELEMENTS FOR INDICATING OBJECTS TO SUPPLEMENT REQUESTS FOR GENERATIVE OUTPUT  
**Pub. No.**: US20260252207

**Applicant**: GOOGLE LLC  
**Inventor**: [Ramprasad Sedouram](https://patents.google.com/?inventor=Ramprasad+Sedouram&country=US&num=100&sort=new), [Karthik Srinivas](https://patents.google.com/?inventor=Karthik+Srinivas&country=US&num=100&sort=new), [Dharma Teja](https://patents.google.com/?inventor=Dharma+Teja&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本文所述实施例涉及一种图形用户界面（GUI）元素，该元素可在界面中被操控以指示特定对象和/或感兴趣的特征，以便在提供生成式输出时考虑用户的单独请求。可以在显示界面（如触摸屏和/或虚拟或增强现实显示界面）上提供一种或多种GUI元素，从而允许GUI元素与渲染的或实体对象相关联。当用户与GUI元素交互时，GUI元素可以根据交互特征和/或特定对象的特征表现出响应行为。当识别出感兴趣的对象时，可以执行处理以识别有关该对象的信息。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569863_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及增强生成式人工智能交互的图形用户界面技术。

**Background (发明背景)**:  
人机对话通常通过自动化助手进行，用户通过语音或文本输入请求。然而，现有自动化助手在缺乏上下文时难以提供准确的响应。例如，用户在查看显示界面时提出关于特定内容的查询，助手可能基于整个显示内容而非用户关注的具体对象生成输出，导致用户需要重复请求，浪费计算资源。此外，处理非特定显示内容会消耗大量处理带宽。

**Summary (发明总览)**:  
本发明提出了一种基于用户可配置GUI元素位置和自然语言输入的生成式输出方法。GUI元素可以在显示界面上移动，并与显示对象关联。用户通过多模态输入（如触摸、语音、注视等）操控GUI元素的位置和属性。当用户发出生成式请求时，系统会分析GUI元素指示的对象，并结合自然语言输入生成更准确的输出。这种方法减少了处理无关内容的需求，提高了生成式输出的准确性和效率。

**Key Innovation (核心创新)**:  
1. 引入可移动、可配置的GUI元素，用户可通过触摸、语音、注视等多模态输入操控其位置和属性。
2. GUI元素能够动态响应用户交互和对象特征，例如通过流体行为（如亲水性、疏水性）增强交互体验。
3. 系统通过图像识别技术识别GUI元素指示的对象，并结合自然语言输入生成更准确的生成式输出。
4. 采用局部图像处理服务裁剪GUI内容，减少非相关内容的处理，提高处理效率。
5. 通过分析自然语言输入的模糊性并结合图像数据生成消歧数据，从而提高生成式输出的准确性。
6. GUI元素可以出现在增强现实设备中，与现实世界中的对象相邻或叠加，增强现实交互体验。
7. 该技术可应用于智能助手、虚拟现实、增强现实等场景，为用户提供更直观、更准确的生成式交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569863)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252207)**
<br/><br/>

---


<br/>

### 8. 在扩展现实中提供可解释人工智能的系统和方法

**Title (EN)**: SYSTEM AND METHOD FOR PROVIDING EXPLAINABLE ARTIFICIAL INTELLIGENCE WITHIN EXTENDED REALITY  
**Pub. No.**: US20260253267

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Xuhai Xu](https://patents.google.com/?inventor=Xuhai+Xu&country=US&num=100&sort=new), [Mengjie Yu](https://patents.google.com/?inventor=Mengjie+Yu&country=US&num=100&sort=new), [Tanya Renee Jonker](https://patents.google.com/?inventor=Tanya+Renee+Jonker&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本文描述的特征主要涉及在扩展现实中提供可解释的人工智能（XAI）。具体而言，在获取包括环境信息、用户状态信息和用户档案信息在内的输入数据后，扩展现实系统通过头戴式设备确定向用户呈现的虚拟内容。该系统还会识别与该虚拟内容相关的额外上下文因素，包括系统目标、用户目标、用户当前状态、用户位置、当前时间和用户当前环境。然后，这些额外的上下文细节被用来确定描述虚拟内容一个或多个方面的XAI内容（例如，虚拟内容如何基于输入数据被确定）。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571024_1.jpg)

**Technical Field (技术领域)**:  
扩展现实技术领域，具体涉及在扩展现实中应用可解释人工智能的技术。

**Background (发明背景)**:  
扩展现实（XR）技术正广泛应用于虚拟现实（VR）、增强现实（AR）和混合现实（MR）等领域。然而，AI生成的内容通常缺乏透明度，用户难以理解其生成逻辑或原因。这可能导致用户忽略或禁用AI生成的内容，从而影响其扩展现实体验。本发明旨在通过提供可解释的人工智能（XAI）技术来解决这一问题，使用户能够理解AI生成内容的推理过程。

**Summary (发明总览)**:  
本发明提出了一种在扩展现实中集成可解释人工智能的系统和方法。该系统通过头戴式设备获取用户的环境信息、状态信息和偏好数据，并基于这些数据生成虚拟内容。同时，系统识别与虚拟内容相关的上下文因素，并生成描述虚拟内容生成过程的XAI内容。最终，系统将虚拟内容和XAI内容一起呈现给用户，从而提高用户对AI生成内容的理解和信任。

**Key Innovation (核心创新)**:  
1. 通过头戴式设备实时获取用户的环境信息、状态信息和用户档案信息，确保虚拟内容的生成基于最新的用户数据。
2. 利用机器学习和人工智能模型，根据输入数据生成个性化的虚拟内容，提高用户体验的沉浸感和互动性。
3. 识别与虚拟内容相关的系统目标、用户目标和用户当前状态等上下文因素，确保XAI内容的准确性和相关性。
4. 生成描述虚拟内容生成过程的XAI内容，使用户能够理解AI生成内容的推理过程，增强用户对系统的信任。
5. 将虚拟内容和XAI内容同时呈现给用户，通过扩展现实环境提供直观的解释和互动。
6. 该技术可应用于游戏、教育、医疗和工业等多个领域，例如在工业培训中提供可解释的AI指导，或在教育中提供互动式学习体验。
7. 通过提供可解释的AI内容，本发明不仅提升了用户体验，还促进了用户对AI技术的理解和接受度。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571024)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253267)**
<br/><br/>

---


<br/>

### 9. 用于液晶显示照明的激光耦合背光单元

**Title (EN)**: LASER COUPLED BACKLIGHT UNIT FOR LIQUID CRYSTAL DISPLAY ILLUMINATION  
**Pub. No.**: US20260251937

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Julia Majors](https://patents.google.com/?inventor=Julia+Majors&country=US&num=100&sort=new), [Yang Zhao](https://patents.google.com/?inventor=Yang+Zhao&country=US&num=100&sort=new), [Yoshitaka Sato](https://patents.google.com/?inventor=Yoshitaka+Sato&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种液晶显示（LCD）设备包括一个背光单元，该背光单元配置有相干光源用于发射光线；一个位于背光单元前方的液晶面板，液晶面板包含多个液晶单元，用于调制背光单元发射的光线，通过调整通过其中的光的偏振来控制液晶单元以显示图像；以及一对位于液晶面板相对两侧的偏振器，偏振器配置为在液晶单元以预定方式定向时允许调制后的光线通过。

**Patent Drawings**:

![Patent Drawing]()

**Technical Field (技术领域)**:  
液晶显示技术领域，具体涉及背光单元与激光光源的结合应用。

**Background (发明背景)**:  
液晶显示设备通常依赖背光单元提供均匀照明以实现图像显示。传统背光单元使用非相干光源，存在能耗较高和亮度均匀性不足的问题。此外，现有技术难以在保证高亮度输出的同时实现精确的局部调光控制。本发明旨在解决这些问题，提供一种更高效、更精确的背光解决方案。

**Summary (发明总览)**:  
本发明提出了一种将激光光源与液晶显示背光单元相结合的创新方案。通过使用相干光源，提供了更高的亮度和更精确的光线控制。实现路径包括优化激光光源与液晶面板的耦合方式，以及改进偏振器的配置以适应激光光源的特性。与传统背光技术相比，本发明在能耗控制和显示质量方面实现了显著改进。

**Key Innovation (核心创新)**:  
1. 采用激光作为背光光源，通过相干光源提供更高的亮度和更精确的光线控制。
2. 设计了激光光源与液晶面板的耦合结构，确保光线能够高效传输并均匀分布。
3. 改进了偏振器的配置，使其能够更好地适应激光光源的特性，提高光能利用率。
4. 通过局部调光控制技术，实现更精细的亮度调节和更高的对比度。
5. 优化了激光光源的散热设计，延长了设备使用寿命并提高了稳定性。
6. 该技术可应用于高端液晶显示器，如电视和显示器，提供更优质的视觉体验。
7. 相比传统背光技术，本发明在能耗和显示质量方面具有独特优势，尤其适用于对画质要求较高的应用场景。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569569)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260251937)**
<br/><br/>

---


<br/>

### 10. 半导体芯片保护封装

**Title (EN)**: SEMICONDUCTOR DIE PROTECTING PACKAGES  
**Pub. No.**: US20260255710

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Rajendra D Pendse](https://patents.google.com/?inventor=Rajendra+D+Pendse&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种图像传感器包括基板、半导体芯片、模塑材料和微型挡坝。半导体芯片通过引线键合连接在基板顶部。半导体芯片的顶面设有二维像素阵列。模塑材料沉积在半导体芯片的顶面上，其高度超过引线键合的高度。微型挡坝设置在半导体芯片的顶面上，位于二维像素阵列和模塑材料之间，用于防止模塑材料进入半导体芯片的功能区域。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485573716_1.jpg)

**Technical Field (技术领域)**:  
半导体封装技术，具体涉及图像传感器芯片的封装工艺。

**Background (发明背景)**:  
电子封装如图像传感器、传感器和显示器的制造过程中，通常会因组装和制造过程中的机械损伤导致5%-20%的损失。
例如，在引线键合阶段或模塑过程中，半导体芯片可能会受到损坏。
此外，封装过程中传感器芯片的部分区域可能会受到污染，从而影响芯片中电子元件的感测或像素功能。

**Summary (发明总览)**:  
本发明提出了一种新型封装结构，通过在半导体芯片表面设置微型挡坝来保护芯片表面免受模塑材料的污染和机械损伤。
该结构在模塑过程中覆盖敏感区域，并在后续工艺中移除以暴露功能区域。
相较于传统腔体模塑工艺，本发明能够有效减少芯片表面污染和损坏，提高产品良率。

**Key Innovation (核心创新)**:  
1. 采用微型挡坝结构，在半导体芯片表面形成保护屏障，防止模塑材料进入敏感区域。
2. 微型挡坝由环氧树脂材料制成，包含基础材料和硬化剂，能够在模塑过程中提供可靠的防护。
3. 通过在封装过程中设置临时保护结构（如牺牲盖板），并在后续工艺中移除，实现对芯片表面的保护。
4. 该结构适用于晶圆级封装工艺，可在芯片切割前完成封装组件的安装，进一步提高生产效率。
5. 创新性地结合了引线键合和模塑工艺，通过微型挡坝的设置，解决了传统工艺中芯片表面易受污染和损坏的问题。
6. 该技术可应用于图像传感器、MEMS传感器和显示芯片等对表面洁净度和完整性要求高的半导体器件。
7. 通过减少封装过程中的良率损失，本发明能够降低生产成本，提高图像传感器等产品的可靠性和性能。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485573716)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260255710)**
<br/><br/>

---


<br/>

### 11. 位置与导航助手

**Title (EN)**: LOCATION AND NAVIGATION ASSISTANT  
**Pub. No.**: US20260251458

**Applicant**: MICROSOFT TECHNOLOGY LICENSING, LLC  
**Inventor**: [Tezan SAHU](https://patents.google.com/?inventor=Tezan+SAHU&country=US&num=100&sort=new), [Pravin Vithalrao BHANDAKKAR](https://patents.google.com/?inventor=Pravin+Vithalrao+BHANDAKKAR&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本文所述用于室内环境自动导航辅助的系统。通常情况下，在不熟悉的室内环境中导航是一项具有挑战性的任务，尤其对于大型环境如企业办公室、大学校园、购物中心和医院等更是如此。因此，本系统利用包含室内环境相关信息的参考数据库，例如描绘各种位置的图像、描述图像的注释以及展示室内环境布局的平面图。参考数据库与多模态语言模型结合使用，利用参考数据库收集的知识提供位置识别和直观的导航。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569038_1.jpg)

**Technical Field (技术领域)**:  
室内导航技术领域，具体涉及基于多模态语言模型和参考数据库的智能导航系统。

**Background (发明背景)**:  
在大型或复杂的室内环境中导航非常困难，例如企业办公室、大学校园和医院等。传统的GPS技术在室内环境下由于信号弱和精度不足而无法有效工作。现有的室内导航系统虽然利用了射频、Wi-Fi和蓝牙信号以及计算机视觉和传感器技术，但这些方法在处理大型室内环境时仍面临技术挑战，例如需要详细的平面图或无法捕捉环境间的细微连接。

**Summary (发明总览)**:  
本发明提出了一种基于参考数据库和多模态语言模型的室内导航辅助系统。通过收集室内环境的图像、注释和平面图，并利用多模态语言模型进行语义理解和检索增强生成（RAG），系统能够提供准确的定位和直观的导航指令。管理员可以轻松配置参考数据库，用户通过上传当前环境的图像并输入自然语言查询，即可获得基于视觉地标的导航指引。

**Key Innovation (核心创新)**:  
1. 利用多模态语言模型结合参考数据库，通过检索增强生成（RAG）技术，实现对室内环境的准确理解和导航。
2. 通过图像、文本注释和室内平面图的综合处理，构建包含语义信息的参考数据库，支持高效索引和搜索。
3. 采用数值表示（嵌入）技术，将图像和文本内容转化为多维向量，实现对语义内容的精准捕捉和匹配。
4. 提供灵活的参考数据库配置方式，管理员可以通过智能手机或360度相机轻松采集和标注数据，降低技术门槛。
5. 用户通过上传当前环境的图像并输入自然语言查询，系统能够识别用户位置并提供基于视觉地标的直观导航指令。
6. 消除对专用传感器或设备的依赖，用户只需使用智能手机等现有设备即可与系统交互，提升便捷性。
7. 应用于大型室内环境如购物中心、医院和大学校园等场景，能够提供高效、精准的导航服务，提升用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569038)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260251458)**
<br/><br/>

---


<br/>

### 12. 增强型视觉指示器用于实时文本通信的指定参与者

**Title (EN)**: ENHANCED VISUAL INDICATORS FOR DESIGNATED PARTICIPANTS COMMUNICATING REAL-TIME TEXT  
**Pub. No.**: US20260254782

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Christopher M. SANO](https://patents.google.com/?inventor=Christopher+M.+SANO&country=US&num=100&sort=new), [Brett D. HUMPHREY](https://patents.google.com/?inventor=Brett+D.+HUMPHREY&country=US&num=100&sort=new), [Noe BARRAGAN](https://patents.google.com/?inventor=Noe+BARRAGAN&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明提供了一种增强型控制方法，用于在在线会议中通过实时文本（RTT）通信的参与者提供归属感的视觉指示器。同时，本发明还提供了对在线会议期间RTT文本转语音转换的动态控制。RTT的显示和文本转语音转换使用户能够听到和看到通过RTT共享的内容。如果某人在RTT模式下通信文本时被指定为具有特定前提条件，其姓名和/或图像将被突出显示。该系统还将此类用户识别为“活跃发言者”，以便在会议记录中公平记录RTT共享的内容，并用于生成会议记录、摘要、任务等的AI模型中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485572697_1.jpg)

**Technical Field (技术领域)**:  
在线会议技术领域，具体涉及实时文本通信和视觉指示器技术。

**Background (发明背景)**:  
现有的协作系统允许用户通过视频、音频、文件共享和聊天消息等方式进行沟通，但这些系统通常无法为所有用户提供公平的参与体验。例如，对于聋哑人、听力障碍者或因环境限制无法发言的用户，现有系统无法提供公平的参与环境。此外，现有系统缺乏对主要依赖文本通信的用户的视觉聚焦功能，且在处理非语言用户与视障用户的沟通时存在不足。

**Summary (发明总览)**:  
本发明提供了一种增强型控制方法，通过实时文本（RTT）通信为在线会议中的参与者提供公平的参与体验。该方法集成了RTT、实时视频流、实时音频流、聊天消息、实时字幕和其他共享会议内容，使用户能够通过视觉和听觉获取RTT共享的内容。系统通过生成视觉指示器来突出显示正在提供RTT的用户的视频、图像或姓名，使其在会议中如同活跃发言者一样受到关注。此外，系统还根据用户的前提条件动态调整视觉指示器的显示，确保非语言用户能够获得公平的会议归属感。

**Key Innovation (核心创新)**:  
1. 集成了实时文本（RTT）、视频流、音频流、聊天消息和实时字幕，提供了一个统一的会议体验平台。
2. 通过视觉指示器突出显示正在提供RTT的用户的视频、图像或姓名，使其在会议中如同活跃发言者一样受到关注。
3. 根据用户的前提条件（如在公共场所、无法发言、聋哑或听力障碍）动态调整视觉指示器的显示，确保公平参与。
4. 将RTT贡献者识别为“活跃发言者”，确保其内容在会议记录和AI生成的会议摘要中得到公平记录。
5. 允许用户通过手动选择或自动配置文件指定其前提条件，例如非语言参与者或特定环境限制。
6. 通过文本转语音转换技术，使用户能够听到RTT共享的内容，进一步提升会议的可访问性。
7. 应用于在线会议和协作平台，为聋哑人、听力障碍者和其他非语言用户提供公平的参与环境，同时提高会议记录的准确性和AI处理效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485572697)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260254782)**
<br/><br/>

---


<br/>

### 13. 具有可定制纹理模拟的自适应触觉反馈触控板

**Title (EN)**: ADAPTIVE TACTILE FEEDBACK TOUCHPAD WITH CUSTOMIZABLE TEXTURE SIMULATOR  
**Pub. No.**: US20260252176

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Roei Shlomo MENASHOF](https://patents.google.com/?inventor=Roei+Shlomo+MENASHOF&country=US&num=100&sort=new), [Lior ZAGIEL](https://patents.google.com/?inventor=Lior+ZAGIEL&country=US&num=100&sort=new), [Oren ISTRIN](https://patents.google.com/?inventor=Oren+ISTRIN&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种具有可定制纹理模拟的自适应触觉反馈触控板通过感知触摸输入属性（如输入位置和力度）并从时间序列的触摸输入中确定额外的触摸属性（如方向和速度），来适应性地提供与不同纹理相关的逼真、细腻的触觉反馈。通过在触控板的一个或多个轴上实现的触觉致动器，可以控制不同的振幅（例如，权重）以提供一致的触觉感受，无论用户触摸和移动手指的位置和方向如何。可以基于模拟的纹理和输入速度选择触觉波形，而波形振幅可以基于输入力度、方向和速度来确定。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569828_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及触控设备中的触觉反馈技术。

**Background (发明背景)**:  
现有的计算设备通常使用触控板作为触摸敏感表面来控制设备，但这些触控板提供的触觉反馈较为基础，难以模拟不同材质的真实触感。
传统触觉反馈在触觉致动器的布局和反馈一致性方面存在不足，尤其是在用户交互面积较大时。
现有技术难以在触控板上提供与不同材质表面相关的细腻且一致的触觉反馈。

**Summary (发明总览)**:  
本发明提出了一种具有可定制纹理模拟的自适应触觉反馈触控板，通过感知触摸输入的位置、力度等属性，并结合方向和速度等额外属性，动态调整触觉反馈。
该触控板通过在多个轴上布置触觉致动器，并基于用户触摸的模拟纹理和输入速度选择波形，同时根据力度、方向和速度调整振幅，从而提供一致且逼真的触觉体验。
相较于传统触控板，本发明能够更细腻地模拟不同材质的触感，并适应用户不同的触摸方式，提升用户体验。

**Key Innovation (核心创新)**:  
1. 通过感知触摸输入的位置、力度、方向和速度等属性，实现对触觉反馈的动态调整，从而提供更细腻的触觉体验。
2. 在触控板的一个或多个轴上布置触觉致动器，并通过控制振幅来确保用户在不同位置和方向触摸时获得一致的触觉反馈。
3. 基于模拟的纹理和输入速度选择触觉波形，并结合输入力度、方向和速度确定振幅，以实现对不同材质的逼真模拟。
4. 触控板集成了波形选择器、触摸传感器、属性确定器、振幅选择器和致动器控制器等模块，共同协作以实现自适应触觉反馈。
5. 用户可以通过应用程序界面选择希望模拟的表面类型，操作系统通信接口将选择结果传递给触控板，从而实现个性化的触觉反馈。
6. 该技术能够模拟如纸张、帆布、织物等不同材质的触感，并通过微振动和触觉脉冲增强用户对触控板交互的真实感。
7. 应用于笔记本电脑、平板电脑等设备时，能够显著提升用户与设备交互的沉浸感和操作精度，尤其适用于需要精细触觉反馈的应用场景，如绘图和游戏。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569828)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252176)**
<br/><br/>

---


<br/>

### 14. 在环境计算环境中生成基于雷达的手势检测事件

**Title (EN)**: Generating Radar-Based Gesture Detection Events in an Ambient Compute Environment  
**Pub. No.**: US20260252179

**Applicant**: Google LLC  
**Inventor**: [Eiji Hayashi](https://patents.google.com/?inventor=Eiji+Hayashi&country=US&num=100&sort=new), [Jaime Lien](https://patents.google.com/?inventor=Jaime+Lien&country=US&num=100&sort=new), [Nicholas Edward Gillian](https://patents.google.com/?inventor=Nicholas+Edward+Gillian&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本专利描述了用于在环境计算环境中生成基于雷达的手势检测事件的技术和方法。与依赖物理用户界面的智能设备相比，带有雷达系统的智能设备可以通过提供免视交互和更少认知负担的手势用户界面来支持环境计算。雷达系统使用环境计算机器学习模块，能够快速识别用户在一米或两米范围内执行的手势。为了降低误报率，系统中的手势去抖动器会评估环境计算机器学习模块生成的类别概率。特别是，当手势类别的概率在连续多个帧中超过第一阈值时，手势去抖动器会识别该手势。第一阈值用于平衡雷达系统的召回率和误报性能。通过适当设置第一阈值，手势去抖动器可以改善用户体验。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485569833_1.jpg)

**Technical Field (技术领域)**:  
环境计算技术领域，具体涉及基于雷达的手势识别和智能设备交互。

**Background (发明背景)**:  
随着智能设备的普及，用户在日常生活中越来越多地使用它们。然而，与智能设备的交互可能既繁琐又低效。例如，依赖物理界面的设备需要用户通过触摸进行操作，这会分散用户对主要任务的注意力。为解决这一问题，一些智能设备支持环境计算，但面临功耗、环境变化、背景噪声、设备尺寸和用户隐私等挑战。

**Summary (发明总览)**:  
本发明提出了一种基于雷达的环境计算解决方案，通过雷达系统实现免视手势交互，提升智能设备的使用体验。该系统使用机器学习模块识别用户手势，并结合手势去抖动机制降低误报率。与传统设备相比，本发明无需物理接触，适应多种环境条件，并提供更好的隐私保护。

**Key Innovation (核心创新)**:  
1. 采用低功耗雷达传感器，功耗低于二十毫瓦，尺寸为四毫米乘六毫米，适合集成到小型智能设备中。
2. 使用环境计算机器学习模块，能够在两米范围内快速识别用户手势，支持远距离交互。
3. 引入手势去抖动机制，通过评估连续帧中的手势类别概率来降低误报率，提高识别准确性。
4. 雷达系统对温度和光照变化不敏感，相比红外传感器和摄像头具有更好的环境适应性。
5. 雷达传感器不捕捉用户的空间结构或语音信息，提供更强的隐私保护。
6. 系统可嵌入塑料、玻璃等不影响射频信号传播的材料中，进一步增强其实用性。
7. 适用于智能家居、办公环境等场景，为用户提供无缝且不干扰主要任务的交互方式。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485569833)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252179)**
<br/><br/>

---


<br/>

### 15. 表单字段自动补全

**Title (EN)**: AUTO-COMPLETION OF FORM FIELDS  
**Pub. No.**: US20260252795

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Liang GU](https://patents.google.com/?inventor=Liang+GU&country=US&num=100&sort=new), [Matthew Reinhard HOHENSEE](https://patents.google.com/?inventor=Matthew+Reinhard+HOHENSEE&country=US&num=100&sort=new), [Nathan Joseph IMSE](https://patents.google.com/?inventor=Nathan+Joseph+IMSE&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明公开了一种以低延迟方式在网页表单中提供自动补全预测的技术。服务访问网页表单中的字段，并使客户端设备进入活动状态，允许其向服务器提交自动补全预测请求。在接收到针对该字段的用户输入之前，服务接收包含该字段自动补全预测的索引数据结构。服务随后使客户端设备进入暂停状态。索引数据结构被本地保存。服务通过本地查询保存的数据结构来显示字段的预测，避免向服务器发送网络请求以获取更多预测。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570505_1.jpg)

**Technical Field (技术领域)**:  
网页表单技术；自动补全预测；低延迟数据处理

**Background (发明背景)**:  
网页表单是允许用户输入数据的交互式网页元素，广泛应用于各种在线服务中。现有技术通过检测数据模式来预测用户输入，但存在预测延迟高、无法根据用户输入动态调整预测结果的问题。此外，传统方法通常只提供单一预测，无法满足用户多样化输入需求。

**Summary (发明总览)**:  
本发明通过在客户端本地存储预加载的自动补全预测数据，并动态调整预测结果来改进网页表单的自动补全功能。具体实现包括：客户端在用户输入前接收并保存服务器提供的预测数据索引结构；根据用户输入实时查询本地数据并显示预测结果；并在用户选择预测结果后更新字段内容。相较于传统方法，本发明减少了网络请求次数，提高了预测的实时性和准确性。

**Key Innovation (核心创新)**:  
1. 通过在用户输入前预加载并本地存储包含预测结果的索引数据结构，减少了对服务器的依赖和延迟。
2. 客户端在暂停状态下本地查询保存的索引数据，避免了不必要的网络请求，提高了效率。
3. 实现了基于用户输入动态调整预测结果的功能，例如用户输入单个字符后，客户端可查询索引数据并提供更精准的预测。
4. 支持在用户输入过程中持续提供多个预测选项，而非仅提供单一预测，增强了用户体验。
5. 在用户选择某个预测结果后，客户端将设备状态从暂停切换回活动状态，以便进行后续的自动补全操作。
6. 该技术不仅适用于基于MRU（最近更新表单）的预测，还支持从用户地址簿、电子邮件文本等多种数据源生成预测。
7. 应用于在线表单填写场景时，本发明能有效提升用户输入效率，尤其在处理长文本或复杂数据时提供更智能的辅助。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570505)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252795)**
<br/><br/>

---


<br/>

### 16. 人工现实环境中的自动固定半径边界

**Title (EN)**: Automatic Fixed-Radius Boundary for Artificial Reality Environments  
**Pub. No.**: US20260253343

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Audrey MULLER](https://patents.google.com/?inventor=Audrey+MULLER&country=US&num=100&sort=new), [Christopher Richard TANNER](https://patents.google.com/?inventor=Christopher+Richard+TANNER&country=US&num=100&sort=new), [Shen LI](https://patents.google.com/?inventor=Shen+LI&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明提供了一种用于访问人工现实（XR）体验的自动固定半径边界系统。该系统无需用户使用XR设备环视现实环境或手动绘制边界，而是通过深度感应在用户移动时动态识别边界内的障碍物，从而自动创建固定大小的边界。该系统无需识别障碍物本身，也无需扫描用户远距离外的整个现实空间。当检测到障碍物时，XR系统可以根据条件（例如用户或身体部位接近障碍物）以网格或透视方式显示障碍物。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571109_1.jpg)

**Technical Field (技术领域)**:  
人工现实（XR）技术领域，具体涉及自动边界生成技术。

**Background (发明背景)**:  
随着人工现实设备日益普及，其应用也变得更加复杂。现有的混合现实（MR）和增强现实（AR）应用结合了真实世界图像与虚拟对象，而虚拟现实（VR）应用则提供完全沉浸式的3D计算机环境。然而，现有技术通常需要用户手动设置边界或扫描环境，这既耗时又可能影响用户体验。本发明旨在解决这一问题，通过自动生成固定半径边界来简化XR体验的设置过程。

**Summary (发明总览)**:  
本发明提出了一种自动固定半径边界系统，通过深度感应技术动态识别用户周围环境中的障碍物，从而在XR系统周围创建固定大小的边界。该系统无需用户手动设置或扫描整个环境，只需在用户移动时持续更新边界内的障碍物信息。当用户静止时，系统可自动切换到静态边界模式，停止环境扫描和边界更新。此外，该系统还支持多用户边界共享，通过共享深度数据和位置信息来识别视野外的障碍物，从而提高XR体验的安全性和沉浸感。

**Key Innovation (核心创新)**:  
1. 通过深度感应技术自动创建固定半径边界，无需用户手动设置或扫描整个环境。
2. 动态识别用户移动过程中边界内的障碍物，并基于条件（如接近障碍物）以网格或透视方式显示障碍物。
3. 在用户静止时自动切换到静态边界模式，停止环境扫描和边界更新以节省系统资源。
4. 支持多用户边界共享，通过共享时间戳深度数据和相机位置数据来识别视野外的障碍物。
5. 利用共享定位地图和最新的深度数据来发现用户边界内的物体，即使这些物体未被当前XR系统直接扫描。
6. 通过共享用户位置和身体部位位置信息，确定用户是否处于其他用户的边界内，从而提高多用户环境下的安全性。
7. 该技术可应用于VR、AR、MR等多种人工现实场景，为用户提供更安全、更便捷的XR体验，尤其适合需要快速设置边界的应用场景，如家庭娱乐或办公环境。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571109)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253343)**
<br/><br/>

---


<br/>

### 17. 人工现实系统中用于听力增强的控制和模式

**Title (EN)**: Hearing Enhancement Controls and Modes for Artificial Reality Systems  
**Pub. No.**: US20260253596

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Vicki CHANG](https://patents.google.com/?inventor=Vicki+CHANG&country=US&num=100&sort=new), [Holly Marie ORMSETH](https://patents.google.com/?inventor=Holly+Marie+ORMSETH&country=US&num=100&sort=new), [Camila Cortes DE ALMEIDA E DE VINCENZO](https://patents.google.com/?inventor=Camila+Cortes+DE+ALMEIDA+E+DE+VINCENZO&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明涉及人工现实（XR）系统中的听力增强控制和模式。听力增强系统可以为佩戴XR系统（例如增强现实（AR）眼镜）的用户提供增强的听力，例如通过突出特定声音来增强对话的可听度。在某些实现中，系统可以1）选择特定声音进行增强，2）应用过滤器以消除选定声音之外的其他声音，3）根据过滤后声音信号中确定的残留噪声量来设置放大量，从而使用户无法感知残留噪声。在某些实现中，系统可以根据确定的周围噪声量来设置放大量。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571390_1.jpg)

**Technical Field (技术领域)**:  
人工现实技术领域，具体涉及增强现实（AR）系统中的智能听力增强技术。

**Background (发明背景)**:  
现有的听力设备如耳机、助听器等通过放大环境声音来补偿用户的听力损失，但难以在嘈杂环境中区分目标声音和背景噪声。传统设备通常会放大所有声音，包括不需要的噪声，导致用户难以专注于目标声音。本发明旨在解决在复杂声学环境中有效增强目标声音并减少干扰噪声的问题。

**Summary (发明总览)**:  
本发明提出了一种用于人工现实系统的智能听力增强方案，通过分析环境噪声水平来选择性地增强目标声音。该系统能够根据声源位置动态调整放大区域，并应用噪声抑制技术以减少残留噪声对用户的干扰。与传统设备相比，本发明通过智能选择和增强目标声音，同时控制残留噪声水平，提供了更清晰、更专注的听觉体验。

**Key Innovation (核心创新)**:  
1. 通过麦克风阵列分析声源方向性，智能选择目标音频信号进行增强，例如优先增强用户前方的声音。
2. 应用自适应噪声抑制技术，根据环境噪声水平动态调整噪声过滤强度，确保残留噪声低于环境噪声水平。
3. 提供三种工作模式："焦点模式"用于高噪声环境，"环绕模式"用于低噪声环境，"自适应模式"根据用户移动动态调整增强区域。
4. 采用预设变换函数优化噪声抑制参数，在减少噪声的同时避免对目标声音产生过多失真。
5. 通过用户手势（如三指长按）激活系统，提供直观的用户交互方式。
6. 将听力增强功能集成到人工现实设备中，例如AR眼镜，实现音频与视觉信息的无缝融合。
7. 应用于日常对话、嘈杂环境中的语音识别等场景，为用户提供更清晰、更专注的听觉体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571390)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253596)**
<br/><br/>

---


<br/>

### 18. 基于兴趣区域的音频信号选择性增强方法

**Title (EN)**: SELECTIVE ENHANCEMENT OF AUDIO SIGNALS FROM ZONES OF INTEREST  
**Pub. No.**: US20260255124

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Buye Xu](https://patents.google.com/?inventor=Buye+Xu&country=US&num=100&sort=new), [Anjali Induchoodan Menon](https://patents.google.com/?inventor=Anjali+Induchoodan+Menon&country=US&num=100&sort=new), [Calvin Murdock](https://patents.google.com/?inventor=Calvin+Murdock&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种计算机实现的方法包括：通过可穿戴设备的运动传感器接收指示用户运动的运动数据；从运动数据中确定声学场景中的听觉兴趣区域；通过可穿戴设备的音频传感器捕获声学场景的音频信号；并向用户呈现音频，其中对来自听觉兴趣区域的至少一个音频信号相对于声学场景中的其他音频信号进行选择性增强。还公开了其他各种方面。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485573074_1.jpg)

**Technical Field (技术领域)**:  
音频增强技术领域，具体涉及基于运动传感器数据选择性增强特定方向音频信号的可穿戴设备技术。

**Background (发明背景)**:  
传统的可穿戴音频系统通常假设正前方是语音增强的期望方向，这要求用户不自然地朝向说话者转动头部，并在头部移动或多人同时讲话时可能丢失音频信号。此外，现有技术通常依赖摄像头或持续音频处理来定位说话者，这些方法耗电量大、存在隐私问题，并且在嘈杂的多说话者环境中性能下降。同时，许多解决方案仅关注声源定位，而忽略了用户的意图，即用户希望关注哪个说话者。

**Summary (发明总览)**:  
本发明提出了一种基于运动传感器数据的音频增强方法，通过智能眼镜上的惯性测量单元（IMU）捕捉用户的头部运动数据，识别用户感兴趣的声音区域，并选择性地增强来自这些区域的音频信号。该方法无需持续使用摄像头或复杂的音频处理管道，节省了电力并保护了用户隐私，同时在嘈杂环境中保持性能稳定。通过分析用户的自然头部运动，系统能够推断用户意图并自动增强目标方向的声音，从而提供更清晰的对话体验。

**Key Innovation (核心创新)**:  
1. 利用智能眼镜上的IMU传感器捕捉用户头部运动数据，通过分析短时间窗口内的头部方向变化来推断用户的听觉兴趣区域。
2. 通过运动数据而非持续摄像头或全音频处理管道来定位声源，节省电力并保护用户隐私。
3. 采用世界锁定的音频增强机制，确保音频增强效果与用户的头部姿态无关，提升用户体验的稳定性。
4. 在嘈杂和多说话者环境中，通过选择性增强特定区域的音频信号来提高语音清晰度。
5. 将用户意图融入音频增强决策，通过分析自然头部运动来预测用户希望关注的说话者。
6. 该技术可应用于智能眼镜等可穿戴设备，为用户提供更自然的音频增强体验，特别适用于多人对话场景。
7. 通过减少对持续音频处理和摄像头的依赖，该方法在保持性能的同时降低了设备的功耗需求。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485573074)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260255124)**
<br/><br/>

---


<br/>

### 19. 基于多模态语言模型的开放词汇机器人控制

**Title (EN)**: OPEN-VOCABULARY ROBOTIC CONTROL USING MULTI-MODAL LANGUAGE MODELS  
**Pub. No.**: US20260249453

**Applicant**: Google LLC  
**Inventor**: [Teddey Ming Xiao](https://patents.google.com/?inventor=Teddey+Ming+Xiao&country=US&num=100&sort=new), [Chelsea Breanna Finn](https://patents.google.com/?inventor=Chelsea+Breanna+Finn&country=US&num=100&sort=new), [Austin Charles Stone](https://patents.google.com/?inventor=Austin+Charles+Stone&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明涉及用于控制与环境交互的智能体的方法和系统。一种方法包括：接收环境的观察图像；接收输入文本序列；生成包括观察图像的目标定位输入；使用目标定位神经网络处理目标定位输入，生成识别观察图像中一个或多个目标位置的目标定位输出；基于观察图像、输入文本序列和目标定位输出生成策略输入；使用策略神经网络处理策略输入，生成定义智能体动作的策略输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485566814_1.jpg)

**Technical Field (技术领域)**:  
机器人控制技术领域，具体涉及基于多模态语言模型和视觉-语言模型的智能体控制。

**Background (发明背景)**:  
神经网络被广泛应用于智能体控制，但传统方法难以处理未见过的新目标或环境。现有技术通常需要大量训练数据来适应新场景，且难以实现快速泛化。本发明旨在解决机器人控制中面对新目标或环境时的适应性问题，通过结合视觉-语言模型和机器人控制策略，实现对未见过的目标或环境的有效控制。

**Summary (发明总览)**:  
本发明提出了一种基于多模态语言模型的机器人控制方法，通过结合视觉-语言模型和机器人控制策略，使机器人能够理解并执行涉及新目标或环境的指令。系统首先利用视觉-语言模型从观察图像中提取目标定位信息，然后结合自然语言指令和提取的视觉信息生成控制策略。该方法无需对机器人控制策略进行大量训练即可实现对新场景的快速适应，从而实现零样本泛化。

**Key Innovation (核心创新)**:  
1. 利用视觉-语言模型从观察图像中提取目标定位信息，实现对图像中目标的精准识别和定位。
2. 结合自然语言指令和视觉信息生成机器人控制策略，使机器人能够理解复杂指令并执行相应动作。
3. 通过预训练的视觉-语言模型，无需大量额外训练即可实现对新目标或环境的快速适应。
4. 采用零样本学习方法，使机器人控制策略能够适应未见过的目标或环境，提升泛化能力。
5. 减少对训练数据的需求，降低计算和内存资源的消耗，提高系统效率。
6. 应用于机器人控制领域，可用于家庭服务机器人、工业自动化等场景，实现对复杂环境的智能交互。
7. 独特价值在于通过多模态融合实现对未知场景的快速适应，显著提升机器人在动态环境中的适应性和灵活性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485566814)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260249453)**
<br/><br/>

---


<br/>

### 20. 用于会议自动召唤的智能代理

**Title (EN)**: INTELLIGENT AGENT FOR AUTO-SUMMONING TO MEETINGS  
**Pub. No.**: US20260254865

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Ryen W. WHITE](https://patents.google.com/?inventor=Ryen+W.+WHITE&country=US&num=100&sort=new), [Gerald HASLHOFER](https://patents.google.com/?inventor=Gerald+HASLHOFER&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
智能代理可以在会议中代表非参与者以虚拟形式存在，监控会议参与者之间的数据通信，并识别与非参与者相关的适当触发事件或情况。例如，代理可以检测针对非参与者的提问或非参与者有能力回答的问题。当识别出与非参与者相关的事件时，非参与者可能会被自动召唤参加会议。自动召唤可以通过实时向非参与者传达有关识别事件的信息来执行。传达有关识别事件的信息可以通过多种通信渠道或方式传输，包括即时消息聊天、短信、电子邮件、电话、建立视频通话、传呼机等。如果非参与者邀请人在自动召唤时正在参加另一个会议，系统可能会管理从当前会议中的离开（例如，发送带有离开通知的消息，并可选择性地通知他们将返回会议），将他们传送到新会议，并在他们返回当前会议时宣布他们的返回。在某些示例中，非参与者可能不需要加入会议。例如，系统可以将他们参与的需求简化为一个简单的问题（例如，是/否问题），非参与者可以在任何设置下轻松回答，甚至可能无需加入会议。相关方面包括考虑非参与者的当前上下文，评估他们加入会议是否可行，并自动选择适当的参与方式。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485572788_1.jpg)

**Technical Field (技术领域)**:  
会议协作技术领域，具体涉及智能代理在会议中的自动参与和通信监控。

**Background (发明背景)**:  
随着电子通信渠道的普及，虚拟会议变得越来越普遍。然而，会议安排困难以及参与者无法全程参与的问题常常影响会议效率。当非参与者需要提供关键信息或决策时，其缺席可能导致会议效果下降。此外，非参与者无法实时获取会议相关信息也可能对其后续行动产生负面影响。现有的会议系统缺乏有效机制来应对这些问题。

**Summary (发明总览)**:  
本发明提出了一种智能代理系统，能够在会议中代表无法参与的非参与者进行虚拟存在。该系统通过监控会议通信，识别与非参与者相关的重要事件，并在必要时自动召唤非参与者加入会议或提供简化的交互方式。智能代理可以实时传递会议关键信息，并根据非参与者的当前状态选择合适的通信方式，从而在不干扰其正在进行的工作的情况下提高会议效率。

**Key Innovation (核心创新)**:  
1. 智能代理代表非参与者虚拟参与会议，通过监控会议通信数据，识别需要非参与者注意的事件，例如提问或特定话题的讨论。
2. 系统能够实时检测并分析会议中的关键事件，例如用户被提及或需要其专业知识的问题，从而触发自动召唤机制。
3. 通过多种通信渠道（如即时消息、短信、电子邮件等）向非参与者传达事件信息，并允许其选择最合适的参与方式，例如直接加入会议或通过简化的问答方式提供输入。
4. 在非参与者被召唤时，系统会管理其在不同会议之间的切换，例如发送通知消息，并在必要时将其传送回原会议。
5. 系统包含优先级组件，用于评估召唤的紧急程度，并决定是否中断当前会议或对多个召唤进行排序。
6. 智能代理可以自动生成简化的查询问题，例如是/否问题，以便非参与者无需加入会议即可提供必要的信息。
7. 该技术可应用于需要多方参与的协作场景，例如企业会议或决策讨论，通过提高非参与者的参与效率，为会议带来更高效的决策流程和更及时的信息交流。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485572788)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260254865)**
<br/><br/>

---


<br/>

### 21. 基于人工智能驱动的概念可视化创作

**Title (EN)**: Al-POWERED CONCEPT-DRIVEN VISUALIZATION AUTHORING  
**Pub. No.**: US20260252541

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Bongshin Lee](https://patents.google.com/?inventor=Bongshin+Lee&country=US&num=100&sort=new), [Chenglong Wang](https://patents.google.com/?inventor=Chenglong+Wang&country=US&num=100&sort=new), [John Roger Thompson](https://patents.google.com/?inventor=John+Roger+Thompson&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明提供了一种方法、计算机程序产品和计算系统，用于处理生成有关多个数据概念的视觉化表示的请求。通过程序合成器和生成模型对现有数据概念进行转换，生成用于视觉化表示的新数据概念。通过处理新数据概念到视觉化表示的视觉通道的映射来渲染视觉化表示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570227_1.jpg)

**Technical Field (技术领域)**:  
人工智能驱动的数据可视化技术领域，具体涉及数据概念转换和自动生成视觉化表示。

**Background (发明背景)**:  
现有的可视化工具通常要求用户将数据转换为特定格式以创建所需的视觉化表示。当数据格式与特定视觉化输入不兼容或难以转换时，用户需要使用专门的程序或外部数据处理工具进行修改。这种过程繁琐且效率低下。

**Summary (发明总览)**:  
本发明提出了一种基于人工智能的视觉化创作新范式，通过分离高层次视觉化意图和低层次数据转换步骤，利用程序合成器和生成式多模态模型实现自动化数据转换。该方法允许用户使用自然语言或现有数据概念示例定义数据概念，并将其绑定到视觉通道。系统自动生成所需视觉化表示并提供反馈，帮助用户理解数据转换过程。

**Key Innovation (核心创新)**:  
1. 通过程序合成器和生成式多模态模型实现数据概念的自动转换，消除了用户手动数据处理的负担。
2. 分离高层次视觉化意图和低层次数据转换步骤，使用户能够专注于定义视觉化目标而非数据格式。
3. 提供交互式视觉化创作工具，用户可以通过自然语言或现有数据概念示例定义新数据概念。
4. 系统能够生成候选数据转换并提供转换过程描述，帮助用户理解数据转换逻辑。
5. 支持从多个现有数据概念中生成新数据概念，并通过视觉通道映射实现自动渲染。
6. 应用于数据分析和商业智能领域，能够快速生成复杂数据关系的视觉化表示。
7. 独特价值在于降低数据处理门槛，提高视觉化创作效率，并支持非技术用户进行高级数据分析和视觉化。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570227)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252541)**
<br/><br/>

---


<br/>

### 22. 用于保护语言模型的安全威胁情报方法

**Title (EN)**: THREAT INTELLIGENCE APPROACH FOR SECURING LANGUAGE MODELS  
**Pub. No.**: US20260252694

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Asaf HARARI](https://patents.google.com/?inventor=Asaf+HARARI&country=US&num=100&sort=new), [Idan HEN](https://patents.google.com/?inventor=Idan+HEN&country=US&num=100&sort=new), [Tamer SALMAN](https://patents.google.com/?inventor=Tamer+SALMAN&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种检测对语言模型的恶意输入的方法包括：获取针对语言模型的第一个输入；生成嵌入第一个输入内容的第一嵌入向量；以及确定第一嵌入向量与存储在已知威胁数据库中的多个嵌入向量之间计算出的相似性度量值。这些嵌入向量对应于试图从语言模型或其他人工智能工具中提取未授权信息的恶意输入。该方法还包括分析相似性度量值，以识别在已知威胁数据库中满足与第一嵌入向量的预定义相似性标准的相似嵌入向量，并在识别出相似嵌入向量后，阻止第一个输入被语言模型处理。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570393_1.jpg)

**Technical Field (技术领域)**:  
人工智能安全领域，具体涉及语言模型的安全防护和恶意输入检测。

**Background (发明背景)**:  
基于网络的应用程序越来越多地使用语言模型或人工智能工具来增强服务。然而，这些工具容易受到恶意用户通过复杂手段绕过系统提示以提取敏感信息的攻击。现有的基于二次语言模型的检测方法存在覆盖范围不足和误报率高的问题，导致难以实时实施安全机制。

**Summary (发明总览)**:  
本发明提出了一种基于向量数学的恶意输入检测方法，通过将输入转换为嵌入向量并与已知威胁数据库中的嵌入向量进行比较来评估相似性。当相似性达到预定义标准时，输入被标记为恶意并触发相应的补救措施。该方法通过减少误报和提高对新变种威胁的适应性，提供了更可靠的安全解决方案。

**Key Innovation (核心创新)**:  
1. 采用向量数学方法而非传统的人工智能模型来检测恶意输入，避免了模型过拟合问题，从而降低了误报率。
2. 使用嵌入向量将输入内容转换为数值表示，并通过计算余弦相似度或点积来量化语义相似性，实现对恶意输入的高效检测。
3. 创建一个已知威胁数据库，存储恶意输入的嵌入向量及其元数据，如越狱策略类型和威胁严重程度，以便进行精确匹配和分类。
4. 实时更新嵌入数据库，新检测到的恶意输入立即被添加，确保对重复或相似输入的即时识别，无需重新训练语言模型。
5. 通过元数据对检测到的恶意输入进行分类，包括越狱策略、威胁级别和目标数据类型，从而为安全响应提供可解释的依据。
6. 提供详细的威胁报告，包括请求用户信息、威胁类型和严重程度，帮助服务提供商采取适当的补救措施。
7. 该方法可应用于各种基于语言模型的应用程序，如聊天机器人和AI助手，为其提供智能化的安全防护，抵御复杂的越狱攻击。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570393)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252694)**
<br/><br/>

---


<br/>

### 23. 使用可穿戴设备检测亚音言语的方法和系统

**Title (EN)**: Methods And Systems For Detecting Sub-Vocal Speech Using Wearable Devices  
**Pub. No.**: US20260253591

**Applicant**: Meta Platforms Technologies, LLC  
**Inventor**: [Emily Mittag Mugler](https://patents.google.com/?inventor=Emily+Mittag+Mugler&country=US&num=100&sort=new), [Andrew Maimone](https://patents.google.com/?inventor=Andrew+Maimone&country=US&num=100&sort=new), [Chuming Zhao](https://patents.google.com/?inventor=Chuming+Zhao&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种检测言语的方法包括接收来自用户佩戴的可穿戴设备的一个或多个传感器的信号。这些传感器配置为接触用户头部或面部，并检测与用户发音活动相关的肌肉收缩或振动。该方法还包括基于一个或多个传感器的信号确定与用户发音活动对应的言语。例如，用户佩戴智能眼镜时可以在不发出可听声音的情况下默默发出命令，智能眼镜可以通过检测与用户发音活动相关的肌肉收缩和/或振动来确定言语。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571383_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及可穿戴设备的语音检测技术，具体为使用可穿戴设备中配置的传感器检测亚音言语。

**Background (发明背景)**:  
可穿戴计算设备在消费市场中日益普及，这些设备通常集成了语音交互界面。然而，现有语音识别系统依赖麦克风捕捉的语音，在公共场合或嘈杂环境中存在隐私问题和识别准确性问题。背景噪音可能干扰语音识别，导致误触发或无法识别有效语音输入。

**Summary (发明总览)**:  
本发明提出了一种通过检测与发音活动相关的肌肉收缩或振动来理解用户言语的技术方案。可穿戴设备配备多种传感器，包括检测面部和下颌肌肉活动的传感器、接触式皮肤振动传感器、运动传感器和传统麦克风。系统根据用户说话方式（如大声说话、低语或默读）和环境噪声水平选择合适的传感器组合，从而实现准确识别。例如，在嘈杂环境中可依赖肌肉活动传感器，而在安静图书馆中则使用检测细微肌肉活动的传感器。

**Key Innovation (核心创新)**:  
1. 通过集成多种传感器（如肌电电极、接触式麦克风）实现对亚音言语的检测，包括肌肉收缩和皮肤振动信号的捕捉。
2. 采用自适应传感器选择机制，根据用户说话方式（大声、低语或默读）和环境噪声水平动态切换传感器组合。
3. 利用面部肌肉活动和皮肤振动信号进行语音识别，即使在完全无声的情况下也能准确理解用户意图。
4. 在嘈杂环境中通过优先使用肌肉活动传感器而非麦克风，避免背景噪音干扰，提高识别准确性。
5. 通过检测细微肌肉活动，实现对默读言语的识别，为用户提供更私密的交互方式。
6. 可应用于智能眼镜、智能手表等可穿戴设备，支持在不便出声的场景下进行语音交互。
7. 提升可穿戴设备在公共场合或安静环境中的用户体验，使用户能够更自然地与设备互动，同时保护隐私。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571383)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253591)**
<br/><br/>

---


<br/>

### 24. 基于生物特征认证的显示文档或内容访问控制方法及系统，可修改认证触发频率或时间表

**Title (EN)**: BIOMETRIC AUTHENTICATION-BASED ACCESS TO DISPLAYED DOCUMENTS OR CONTENT WITH MODIFIABLE FREQUENCY OR SCHEDULE FOR TRIGGERING AUTHENTICATION PROCESSES  
**Pub. No.**: US20260252673

**Applicant**: Microsoft Technology Licensing, LLC  
**Inventor**: [Katharine Ormond HOLDSWORTH](https://patents.google.com/?inventor=Katharine+Ormond+HOLDSWORTH&country=US&num=100&sort=new), [Abhilasha BHARGAV-SPANTZEL](https://patents.google.com/?inventor=Abhilasha+BHARGAV-SPANTZEL&country=US&num=100&sort=new), [Md. Nazmus SAKIB](https://patents.google.com/?inventor=Md.+Nazmus+SAKIB&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明提供了一种基于生物特征认证的访问控制系统和方法，用于显示文档或内容，并可修改触发认证过程的频率或时间表。计算系统接收包括当前位置数据、用户访问级别数据和文档安全级别数据在内的多种数据。基于这些数据的组合，计算系统确定在当前位置显示一个或多个文档时的安全风险等级，并根据该安全风险等级设置或修改触发认证验证过程的频率或时间表。在某些示例中，认证验证过程包括使用计算系统的摄像头捕获一个或多个图像，并基于对图像的分析确定除第一用户之外的任何个体是否在显示屏幕的可视范围内。如果确定一个或多个个体在显示屏幕的可视范围内，认证验证过程进一步确定这些个体是否有权查看显示屏幕上的文档。如果确定至少有一个个体无权查看显示的文档，认证验证过程将执行一个或多个操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570370_1.jpg)

**Technical Field (技术领域)**:  
信息安全领域，具体涉及基于生物特征认证的动态访问控制技术。

**Background (发明背景)**:  
随着用户习惯于在公共场所（如机场、咖啡店、餐厅等）工作，攻击者利用各种手段（如恶意热点、会话劫持、偷窥等）获取用户设备上的敏感信息。现有技术难以在保证安全性的同时，不对用户体验造成过大影响。本发明旨在解决在动态环境下平衡安全性和用户体验的问题。

**Summary (发明总览)**:  
本发明提出了一种基于生物特征认证的动态访问控制方法，通过实时威胁情报分析，结合计算系统的当前位置、网络连接状态和上下文信息，动态调整认证验证过程的频率和强度。该方法利用摄像头捕捉图像，检测是否有未经授权的个体在屏幕可视范围内，并根据检测结果采取相应措施。本发明在增强安全性的同时，避免了对系统资源的过度消耗和对用户体验的负面影响。

**Key Innovation (核心创新)**:  
1. 结合多种数据源（如位置、网络、用户访问级别和文档安全级别）进行安全风险评估，实现动态调整认证触发频率。
2. 利用摄像头图像分析技术，检测显示屏幕可视范围内是否存在未经授权的个体。
3. 基于检测结果执行相应的安全措施，例如锁定屏幕、模糊显示内容或提示用户。
4. 通过实时威胁情报分析，平衡安全性和用户体验，避免对系统资源的过度消耗。
5. 提供可配置的认证触发频率和时间表，允许用户根据实际需求进行个性化设置。
6. 适用于移动办公场景下的敏感信息保护，例如在公共场所处理机密文件或访问受保护内容。
7. 独特价值在于提供了一种智能化的安全解决方案，既能有效防止信息泄露，又能保持良好的用户体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570370)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252673)**
<br/><br/>

---


<br/>

### 25. 基于情感自动检测的情感化文本转语音

**Title (EN)**: Emotive Text-To-Speech with Auto Detection of Emotions  
**Pub. No.**: US20260253578

**Applicant**: Google LLC  
**Inventor**: [Arindrima Datta](https://patents.google.com/?inventor=Arindrima+Datta&country=US&num=100&sort=new), [Rakesh Narayan Iyer](https://patents.google.com/?inventor=Rakesh+Narayan+Iyer&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
一种提供情感化文本转语音的方法包括获取由助手大语言模型（LLM）在用户与助手LLM对话期间对用户输入的查询生成的自然语言响应的输入文本，并使用助手LLM基于情感检测任务提示处理输入文本，以预测作为助手LLM输出的自然语言响应的情感状态。该方法还包括基于助手LLM预测的自然语言响应的情感状态，确定输入文本的情感嵌入。情感嵌入指定了用于将输入文本合成为富有表现力的语音的自然语言响应的情感状态。该方法进一步包括指示文本转语音（TTS）模型处理输入文本和情感嵌入，以生成传达自然语言响应情感状态的合成语音表示。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485571369_1.jpg)

**Technical Field (技术领域)**:  
语音合成技术领域，具体涉及情感化文本转语音和情感自动检测。

**Background (发明背景)**:  
大语言模型（LLM）越来越多地被用于提供用户与数字助手界面之间的对话体验。然而，LLM生成的语音响应通常缺乏情感，听起来单调且不自然。尽管已有手动注入情感或使用高度专业化的语音生成模块的解决方案，但这些方法在处理日益增长的合成语音量和新兴语音优先技术时，成本高昂且耗时。本发明旨在解决这一问题，通过自动检测情感并生成富有表现力的语音来提升用户体验。

**Summary (发明总览)**:  
本发明提出了一种自动检测情感并生成情感化语音的方法。其核心思路是使用助手LLM对用户查询的响应文本进行情感状态预测，并基于预测结果生成情感嵌入。随后，指示TTS模型结合输入文本和情感嵌入，生成富有表现力的合成语音。与现有技术相比，本发明通过自动情感检测和情感嵌入的结合，提供了更自然、更具表现力的语音输出，减少了人工干预和专用语音模块的需求。

**Key Innovation (核心创新)**:  
1. 通过助手LLM对输入文本进行情感状态预测，利用情感检测任务提示引导LLM识别情感状态。
2. 采用少样本学习示例，为助手LLM提供上下文学习，使其能够更准确地检测输入文本的情感状态。
3. 使用微调提示嵌入，通过软提示引导助手LLM在固定参数条件下检测情感状态，提升情感检测的灵活性和准确性。
4. 在情感检测过程中，助手LLM通过处理用户查询的文本表示生成自然语言响应，并基于情感检测提示预测情感状态。
5. 通过访问二维嵌入空间，将预测的情感状态映射到相应的情感嵌入中，为TTS模型提供情感指导。
6. 指示TTS模型结合输入文本和情感嵌入，生成传达情感状态的合成语音。
7. 本发明可应用于虚拟助手、语音导航和内容朗读等场景，为用户提供更自然、更具表现力的语音交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485571369)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260253578)**
<br/><br/>

---


<br/>

### 26. 浏览器中的草稿助手

**Title (EN)**: DRAFTING ASSISTANT FOR A BROWSER  
**Pub. No.**: US20260252790

**Applicant**: GOOGLE LLC  
**Inventor**: [Benjamin Albert Azose](https://patents.google.com/?inventor=Benjamin+Albert+Azose&country=US&num=100&sort=new), [Max Benjamin Christoff](https://patents.google.com/?inventor=Max+Benjamin+Christoff&country=US&num=100&sort=new)  
**Publication Date**: 27.08.2026

**Abstract**:  
本发明涉及一种草稿助手，用于帮助用户生成提示，以供语言模型为网页上的文本框生成响应。草稿助手接收用户关于文本框输入的提示，通过整合从网页中识别的上下文信息生成修改后的提示，并将修改后的提示提供给生成性语言模型。生成性语言模型为修改后的提示生成响应，响应呈现给用户并可作为文本框的输入。草稿助手根据网页上下文动态地构建/增强提示，从而促进生成性语言模型生成更准确和相关的响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485570500_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及浏览器内嵌的生成性人工智能辅助工具。

**Background (发明背景)**:  
随着互联网的普及，用户在网页上输入文本的需求日益增加，例如撰写评论、发表评论、填写调查问卷等。然而，用户在生成符合上下文的高质量文本时常常面临困难。现有的文本输入方式缺乏智能化的辅助工具，导致用户需要花费更多时间和精力来编辑和完善输入内容。本发明旨在通过生成性人工智能技术，为用户提供智能化的文本生成辅助工具，提升用户体验并提高输入效率。

**Summary (发明总览)**:  
本发明提出了一种浏览器内的草稿助手工具，通过生成性人工智能技术帮助用户生成网页文本框的输入内容。该工具接收用户输入的初步提示，结合网页上下文信息对提示进行智能修改，并利用生成性语言模型生成更符合上下文的响应。相较于现有技术，本发明通过在浏览器内集成生成性语言模型，减少了用户与设备的交互次数，并利用网页上下文信息生成更高质量和相关性的文本内容。

**Key Innovation (核心创新)**:  
1. 通过智能分析网页上下文信息，动态修改用户输入的提示，从而生成更符合网页主题和文本框类型的提示内容。
2. 在浏览器内集成生成性语言模型，减少用户在不同应用间切换的需求，提升使用便捷性。
3. 提供用户对修改后提示的编辑权限，允许用户根据需要调整提示内容，确保生成内容的准确性和个性化。
4. 通过计算网页的可信度评分，为用户提供安全保护，例如在不可信网站上自动添加提示词以防止用户泄露敏感信息。
5. 利用网页的元数据（如文本框属性、页面主题等）生成特定指令，指导生成性语言模型生成符合特定风格或格式的文本内容。
6. 工具界面设计为浏览器侧边栏或浮动窗口，防止被网页内容仿冒，提升用户对工具的信任度。
7. 应用于撰写评论、发表评论、填写调查问卷等场景，通过智能辅助功能提升用户生成文本的效率和质量，尤其适用于移动设备等屏幕空间有限的设备。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485570500)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US20260252790)**
<br/><br/>

---


<br/>

### 27. 自动化集装箱堆叠站

**Title (EN)**: Automated container stacking stations  
**Pub. No.**: US12715715

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Dragan Pajevic](https://patents.google.com/?inventor=Dragan+Pajevic&country=US&num=100&sort=new), [Tim Martin](https://patents.google.com/?inventor=Tim+Martin&country=US&num=100&sort=new), [Kevin John Trenholme](https://patents.google.com/?inventor=Kevin+John+Trenholme&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明公开了自动化集装箱堆叠站的系统和方法。在一个实施例中，示例系统包括一个具有第一侧和第二侧的壳体，一个用于将第一集装箱从第一位置提升到第二位置并从第二位置下降到第三位置的提升组件，使得第一集装箱堆叠在第二集装箱上，以及一个具有第一集装箱接合构件和第二集装箱接合构件的集装箱居中组件，该集装箱居中组件用于将第一集装箱对齐到预定位置。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485342533_1.jpg)

**Technical Field (技术领域)**:  
物流自动化领域，具体涉及集装箱堆叠和定位技术。

**Background (发明背景)**:  
随着在线购物的普及，订单履行变得日益复杂。例如，履行中心每天可能需要处理超过一百万个包裹。这种需求对物流处理订单和包裹的效率提出了更高要求。现有的订单履行操作，如拣选、分类和包装技术，存在效率不足的问题，限制了整体吞吐量和可持续性。

**Summary (发明总览)**:  
本发明旨在通过自动化集装箱堆叠系统提高物流中心的处理效率。其核心思路是设计一个能够自动提升、下降和精确定位集装箱的堆叠站。通过集成提升机构和集装箱居中组件，系统能够实现集装箱的自动堆叠和排列，从而优化物流中心的操作流程。相较于传统人工操作，本发明提高了堆叠精度和效率，减少了人为错误。

**Key Innovation (核心创新)**:  
1. 集成提升组件，通过精确控制实现集装箱的自动提升和下降，确保堆叠过程的安全性和准确性。
2. 设计集装箱居中组件，通过第一和第二集装箱接合构件实现集装箱的精确定位，避免堆叠过程中的错位问题。
3. 壳体结构设计具有第一侧和第二侧，为集装箱提供稳定的支撑和导向，确保堆叠过程的稳定性。
4. 通过自动化操作减少人工干预，降低了人力成本和操作错误率，提高了整体物流效率。
5. 该系统适用于高吞吐量的物流中心，能够处理大量集装箱的堆叠需求，适应现代化物流中心的运作模式。
6. 创新性地结合提升和居中功能，实现集装箱的自动化堆叠，简化了物流中心的操作流程。
7. 该技术可应用于大型仓储和配送中心，为提高物流效率和可持续性提供了一种有效的解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485342533)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12715715)**
<br/><br/>

---


<br/>

### 28. 微型驱动单元及其操作方法

**Title (EN)**: Micro drive units and associated methods of operation  
**Pub. No.**: US12717353

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Yuri Anatoly Ivanov](https://patents.google.com/?inventor=Yuri+Anatoly+Ivanov&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
微型驱动单元可以包括简单、小型、轻量、安全、快速、高效、灵活且适应性强的机器人驱动单元。这些微型驱动单元可以单独操作以执行各种物料搬运操作，或者可以集体以组的形式操作，例如移动组、临时输送装置或临时运动场，以执行各种物料搬运操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485344340_1.jpg)

**Technical Field (技术领域)**:  
机器人技术领域，具体涉及用于物料搬运的微型机器人驱动单元及其操作方法。

**Background (发明背景)**:  
许多公司使用物料搬运设施存储、包装和运输物品或物品组。现有技术中，自动化设备如输送带或自动导引车（AGV）通常体积大、成本高、结构复杂、固定且专用，缺乏灵活性。
因此，需要一种快速、简单、轻量、安全、高效且灵活的机器人驱动单元及其操作方法，以满足物料搬运设施的需求。

**Summary (发明总览)**:  
本发明提出了一种新型微型机器人驱动单元，旨在解决现有自动化设备灵活性不足和适应性差的问题。
该驱动单元采用模块化设计，可单独或集群工作，通过智能协作形成临时输送系统或运动场。
相较于传统设备，本发明具有更高的灵活性、可扩展性和适应性，能够快速响应不同场景的物料搬运需求。

**Key Innovation (核心创新)**:  
1. 采用模块化设计，将微型驱动单元设计为独立且可互换的模块，便于快速部署和重组。
2. 引入集群协作算法，使多个微型驱动单元能够协同工作，形成临时输送装置或运动场。
3. 集成轻量化材料和高效能源管理系统，确保设备小型化同时保持足够的动力和续航能力。
4. 配备智能传感器和路径规划系统，使驱动单元能够自主避障并优化运动路径。
5. 提供灵活的编程接口，允许用户根据具体应用场景自定义驱动单元的行为和协作模式。
6. 应用于物料搬运设施时，可替代传统固定输送系统，提供更高的空间利用率和操作灵活性。
7. 特别适用于动态和复杂环境，如临时仓储或快速分拣场景，提供独特的操作价值。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485344340)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12717353)**
<br/><br/>

---


<br/>

### 29. 增强型多语言视频屏幕文字提取

**Title (EN)**: Enhanced multilingual video on-screen text extraction  
**Pub. No.**: US12718609

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Yundi Jiang](https://patents.google.com/?inventor=Yundi+Jiang&country=US&num=100&sort=new), [Trung Kien Nguyen](https://patents.google.com/?inventor=Trung+Kien+Nguyen&country=US&num=100&sort=new), [Changhyeok Lee](https://patents.google.com/?inventor=Changhyeok+Lee&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明涉及用于多语言视频屏幕文字提取的设备、系统和方法，包括以下步骤：通过一种语言无关的机器学习模型提取视频帧采样子集中的第一文字组的边界框；输出边界框的像素坐标和第一文字组的预测分类；接收视频帧采样子集中检测到的非项目叠加文字；基于接收到的检测到的非项目叠加文字，识别视频帧采样子集中的第二文字组；为第二文字组识别出各自的开始时间，即第二文字组的相应文字首次出现的时间，以及各自的结束时间，即第二文字组的相应文字消失的时间。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345729_1.jpg)

**Technical Field (技术领域)**:  
本发明属于视频处理领域，具体涉及多语言视频中的文字识别与提取技术。

**Background (发明背景)**:  
视频中包含的文字可能难以识别和跨帧追踪。自动将视频帧中的文字从一种语言翻译成另一种语言存在挑战。现有的机器学习模型在视频文字识别和提取方面需要改进。现有技术难以有效处理多语言文字和复杂的视频背景。

**Summary (发明总览)**:  
本发明提出了一种增强型多语言视频文字提取方法，通过语言无关的机器学习模型识别和提取视频中的文字。该方法能够识别不同语言的文字，并跟踪文字在视频中的出现和消失时间。相较于现有技术，本发明提高了多语言文字识别的准确性和效率，并能够处理复杂的视频背景和叠加文字。

**Key Innovation (核心创新)**:  
1. 采用语言无关的机器学习模型，实现对多语言文字的通用识别，无需针对特定语言进行训练。
2. 通过提取边界框和像素坐标，精确定位视频中文字的位置，并输出预测分类结果。
3. 引入非项目叠加文字检测机制，能够区分视频中的前景文字和背景干扰，提高识别准确性。
4. 为识别出的文字组记录出现和消失时间，支持跨帧追踪文字的动态变化。
5. 结合时间戳信息，能够生成文字出现和消失的完整时间线，支持后续的文字翻译和字幕生成。
6. 该方法适用于包含多语言文字和复杂背景的视频场景，如新闻报道、电影和在线视频平台。
7. 通过提高多语言文字提取的准确性和效率，本发明能够支持更高效的视频内容翻译和字幕制作。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345729)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12718609)**
<br/><br/>

---


<br/>

### 30. 语言模型处理

**Title (EN)**: Language model processing  
**Pub. No.**: US12718010

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Xiaohu Liu](https://patents.google.com/?inventor=Xiaohu+Liu&country=US&num=100&sort=new), [Chenlei Guo](https://patents.google.com/?inventor=Chenlei+Guo&country=US&num=100&sort=new), [Ruhi Sarikaya](https://patents.google.com/?inventor=Ruhi+Sarikaya&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明描述了利用用户提供的反馈来生成对之前用户输入的修订响应并重新训练语言模型的技术。通过分类器处理用户输入及其对应的对话历史，以确定用户输入是否包含与第一语言模型生成的之前响应相关的用户反馈。第二语言模型使用用户输入生成提示，指导第一语言模型生成包含用户反馈的修订响应。将之前的用户输入和修订响应添加到训练数据集中，以训练第一语言模型生成未来与用户反馈相关的响应。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345065_1.jpg)

**Technical Field (技术领域)**:  
自然语言处理领域，具体涉及语言模型的用户反馈处理和模型训练。

**Background (发明背景)**:  
自然语言处理系统已经发展到用户可以通过语音和自然语言文本与计算设备进行交互的程度。
现有技术通过识别用户输入数据的各种特征来理解用户意图。
然而，现有系统在处理用户反馈并利用这些反馈改进模型方面存在不足。
这导致模型难以根据用户反馈进行动态调整和优化。
本发明旨在解决如何有效利用用户反馈改进语言模型的问题。

**Summary (发明总览)**:  
本发明提出了一种利用用户反馈改进语言模型响应的方法。
首先，通过分类器识别用户输入中的反馈信息。
然后，使用第二语言模型生成包含反馈的提示，指导第一语言模型生成修订后的响应。
将修订后的响应和原始输入加入训练数据，以增强模型对用户反馈的适应性。
相较于现有技术，本发明能够动态调整模型输出，使其更符合用户期望。

**Key Innovation (核心创新)**:  
1. 通过分类器识别用户输入中的反馈信息，确保反馈被准确捕捉。
2. 使用第二语言模型生成包含用户反馈的提示，指导第一语言模型生成修订响应。
3. 将修订后的响应和原始输入加入训练数据集，以增强模型对用户反馈的适应性。
4. 通过动态调整模型输出，使其更符合用户期望，提高人机交互的自然度。
5. 实现了用户反馈的闭环处理，从识别到应用再到训练，形成完整的反馈循环。
6. 适用于对话系统、虚拟助手等场景，能够显著提升用户满意度。
7. 通过持续学习和改进，使语言模型能够更好地适应用户需求和偏好。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345065)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12718010)**
<br/><br/>

---


<br/>

### 31. 语音处理功能与组织系统的集成

**Title (EN)**: Integration of speech processing functionality with organization systems  
**Pub. No.**: US12718816

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Gonzalo Alvarez Barrio](https://patents.google.com/?inventor=Gonzalo+Alvarez+Barrio&country=US&num=100&sort=new), [Shantanu Vikas Kurhekar](https://patents.google.com/?inventor=Shantanu+Vikas+Kurhekar&country=US&num=100&sort=new), [Bharath Bhimanaik Kumar](https://patents.google.com/?inventor=Bharath+Bhimanaik+Kumar&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明公开了语音处理功能与组织系统集成的系统和方法。例如，可以创建语音界面应用程序，为与组织相关的设备启用语音界面功能。组织空间的空间标识符可以被创建并与语音界面应用程序关联。与空间标识符相关的设备可以通过无线网络标识符启用语音界面应用程序的使用，这些标识符与空间和组织相关联。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345959_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术；智能设备控制系统；组织管理系统

**Background (发明背景)**:  
语音界面设备通常与账户关联，账户详情将设备与设备使用的功能关联。现有的语音界面设备在控制和管理方面存在不足，例如难以实现对多个设备或空间的统一管理。本发明旨在解决语音界面设备在组织环境中的集成和控制问题。

**Summary (发明总览)**:  
本发明提出了一种将语音处理功能与组织系统集成的技术方案。通过创建空间标识符并将其与语音界面应用程序关联，实现对组织内设备的统一语音控制。设备通过与空间或组织相关的无线网络标识符进行设置，从而启用语音界面功能。这种方法提供了一种集中管理组织内语音设备的新方式。

**Key Innovation (核心创新)**:  
1. 创建空间标识符并将其与语音界面应用程序关联，实现对组织内空间的语音识别和设备管理。
2. 通过无线网络标识符设置设备，使其能够利用语音界面应用程序进行操作，从而实现设备与空间的自动关联。
3. 提供一种集中管理组织内多个语音设备的方法，通过空间标识符和无线网络标识符的结合，实现设备的统一控制。
4. 允许用户通过语音命令控制组织内的设备，提升操作的便捷性和效率。
5. 实现了语音界面应用程序与组织系统的深度集成，支持根据组织结构和空间布局进行设备管理。
6. 通过无线网络标识符的关联，确保设备在特定空间或组织内的安全性和准确性。
7. 本发明可应用于智能办公、智能家居等场景，提供高效、便捷的语音控制解决方案。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345959)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12718816)**
<br/><br/>

---


<br/>

### 32. 基于交互式扩散的图像生成

**Title (EN)**: Interactive diffusion-based image generation  
**Pub. No.**: US12718426

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Karim Bouyarmane](https://patents.google.com/?inventor=Karim+Bouyarmane&country=US&num=100&sort=new), [Suren Suren Kumar](https://patents.google.com/?inventor=Suren+Suren+Kumar&country=US&num=100&sort=new), [Amirhossein Tavanaei](https://patents.google.com/?inventor=Amirhossein+Tavanaei&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明提供了一种图像生成系统，该系统使用潜在扩散模型，能够在保留对象和图像细节的同时，将对象虚拟地放置到图像中。图像生成系统可以接收用户提供的图像，并指示图像中要放置对象的区域，然后使用该对象的参考产品图像生成插入选定区域的图像，同时保留图像的细节。该系统可能利用双编码器系统以及生成的引导图像来执行图像生成。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345528_1.jpg)

**Technical Field (技术领域)**:  
人工智能图像生成技术，具体涉及基于扩散模型的图像合成与编辑。

**Background (发明背景)**:  
生成式人工智能模型能够生成文本、图像和多媒体等多种内容。现有扩散模型虽然能够根据文本或图像输入生成新图像，但在处理复杂场景或保留原始图像细节方面存在不足。本发明旨在解决在图像中插入对象时，如何有效保留原始图像和目标对象的细节问题。

**Summary (发明总览)**:  
本发明提出了一种基于交互式扩散的图像生成方法，通过潜在扩散模型实现对象在图像中的虚拟插入。该方法利用用户输入的图像和目标区域，结合对象的参考图像，生成融合后的图像。系统采用双编码器架构，并使用引导图像来优化生成效果。与传统方法相比，本发明在保留图像细节和对象特征方面具有显著改进。

**Key Innovation (核心创新)**:  
1. 采用潜在扩散模型，在图像中插入对象时能够有效保留原始图像的细节和目标对象的特征。
2. 使用双编码器系统，一个编码器处理原始图像，另一个编码器处理目标对象的参考图像，从而实现更精准的图像融合。
3. 通过生成引导图像，指导扩散过程，确保插入的对象与原始图像在光照、透视和风格上的一致性。
4. 系统能够接收用户指定的图像区域作为插入位置，提供更高的交互性和灵活性。
5. 在图像生成过程中，利用注意力机制来协调对象与背景的融合，提升生成图像的自然度。
6. 该技术可应用于虚拟试穿、产品展示和图像编辑等领域，为用户提供更真实、更便捷的图像生成体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345528)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12718426)**
<br/><br/>

---


<br/>

### 33. 用于检测输送带裂纹的检测系统

**Title (EN)**: Detection system for detecting cracks in conveyor belt  
**Pub. No.**: US12715707

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Jaroslaw Robert Fydrych](https://patents.google.com/?inventor=Jaroslaw+Robert+Fydrych&country=US&num=100&sort=new), [Rafi Joseph Magholian](https://patents.google.com/?inventor=Rafi+Joseph+Magholian&country=US&num=100&sort=new), [Jaroslaw Talaska](https://patents.google.com/?inventor=Jaroslaw+Talaska&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
一种检测系统用于监测输送带，以确定输送带是否存在裂纹。该检测系统可确定输送带在滑轮上滚动时的标准位置，以及与检测输送带在滑轮上滚动时位移相关的位移位置。检测系统接收来自布置在滑轮附近的传感器的信号，并确定该信号与输送带超出位移位置的位移相关。基于至少部分信号，检测系统可确定该位移与输送带中的裂纹相关。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485342524_1.jpg)

**Technical Field (技术领域)**:  
输送设备技术领域，具体涉及输送带裂纹检测技术。

**Background (发明背景)**:  
现代环境如仓库、配送中心、机场和制造设施中广泛使用输送机来运输物品。输送机通常采用输送带，通过滑轮和电机驱动。随着时间推移，输送带可能磨损并需要更换。如果未能及时监测更换，输送带可能导致运输效率下降、输送机损坏或运输物品受损。

**Summary (发明总览)**:  
本发明提出了一种用于检测输送带裂纹的检测系统。其核心思路是通过监测输送带在滑轮上的运动状态来识别裂纹。具体实现路径包括：确定输送带的标准位置和位移位置，接收传感器信号并分析位移是否超出正常范围，从而判断是否存在裂纹。该系统相较于现有技术，能够更精准地识别输送带的异常位移并及时发现裂纹问题。

**Key Innovation (核心创新)**:  
1. 通过监测输送带在滑轮上的标准位置和位移位置，建立输送带运动状态的基准模型。
2. 利用布置在滑轮附近的传感器实时采集输送带运动数据，确保数据采集的准确性和及时性。
3. 通过分析传感器信号，识别输送带超出正常位移范围的异常情况，从而判断是否存在裂纹。
4. 系统能够区分正常磨损和裂纹导致的位移变化，提高检测的准确性和可靠性。
5. 采用非接触式传感器设计，避免对输送带运行造成干扰，延长设备使用寿命。
6. 该系统可应用于各种类型的输送带，包括但不限于皮带式和链式输送带，具有广泛的适用性。
7. 通过及时发现输送带裂纹问题，可有效预防输送机故障和运输物品损坏，提高生产效率和安全性。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485342524)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12715707)**
<br/><br/>

---


<br/>

### 34. 移动物品识别装置

**Title (EN)**: Mobile item identifying apparatus  
**Pub. No.**: US12716768

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Jacob A. Siegel](https://patents.google.com/?inventor=Jacob+A.+Siegel&country=US&num=100&sort=new), [Nicholas Franklin](https://patents.google.com/?inventor=Nicholas+Franklin&country=US&num=100&sort=new), [Joseph Harkness](https://patents.google.com/?inventor=Joseph+Harkness&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
智能购物车包括一个带有轮子的框架，用于在支撑表面上移动，并可与其他智能购物车嵌套。智能购物车包含一个通过称重模块连接到框架的篮子，称重模块位于篮子第一端附近，用于确定放置在篮子中的物品的重量。称重模块包括三个垂直于篮子长度方向排列的负载传感器，其中两个负载传感器位于篮子中部附近，一个负载传感器位于篮子第一端附近。负载传感器提供模拟信号，通过嵌入式电路板转换为数字信号，以确定放置在篮子中的物品的重量。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485343697_1.jpg)

**Technical Field (技术领域)**:  
智能购物车技术领域，具体涉及物品称重和自动结算技术。

**Background (发明背景)**:  
在零售店或超市中，顾客通常使用传统购物车选购商品，并在结账时进行人工结算。这种方式耗时且成本高。智能购物车旨在解决这些问题，通过集成电子设备实现自动化操作，如商品定位和自动结算，从而提升顾客购物体验。

**Summary (发明总览)**:  
本发明提出了一种智能购物车，通过集成称重传感器和嵌入式计算系统，实现对购物车内物品的自动称重和计价。智能购物车采用多个负载传感器来提高称重精度，并通过嵌入式电路板将模拟信号转换为数字信号。相较于传统购物车，本发明减少了人工结算的需求，提高了购物效率并降低了运营成本。

**Key Innovation (核心创新)**:  
1. 采用三个垂直于篮子长度方向排列的负载传感器，其中两个位于篮子中部，一个位于第一端，以提高称重精度和稳定性。
2. 通过嵌入式电路板将负载传感器的模拟信号转换为数字信号，实现对物品重量的精确计算。
3. 智能购物车的框架设计支持与其他购物车嵌套，便于在不使用时节省空间。
4. 集成称重模块和嵌入式系统，实现对购物车内物品的实时称重和计价，减少人工结算需求。
5. 智能购物车可与店内其他电子设备（如条码扫描器、位置传感器）协同工作，提供更全面的自动化购物体验。
6. 通过集成电池供电，并在不使用时通过多种充电系统进行充电，确保设备的持续运行。
7. 应用于超市和零售店场景，能够有效提升顾客购物效率，降低运营成本，并改善整体购物体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485343697)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12716768)**
<br/><br/>

---


<br/>

### 35. 从搜索语料库中呈现建议

**Title (EN)**: Presenting suggestions from search corpora  
**Pub. No.**: US12717473

**Applicant**: GOOGLE LLC  
**Inventor**: [Alastair Tse](https://patents.google.com/?inventor=Alastair+Tse&country=US&num=100&sort=new), [John Nicholas Jitkoff](https://patents.google.com/?inventor=John+Nicholas+Jitkoff&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明涉及一种计算机实现的用户界面方法，包括在触摸屏上显示一个定义有顶部边缘和底部边缘的键盘表示，以及与键盘相邻的内容区域。该方法进一步包括接收用户向键盘底部边缘方向拖动的输入。该方法还包括从触摸屏上移除键盘，并将内容区域扩展到键盘先前占据的区域。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485344472_1.jpg)

**Technical Field (技术领域)**:  
人机交互技术领域，具体涉及移动设备上的触摸屏用户界面设计和软件键盘管理。

**Background (发明背景)**:  
随着移动设备的普及，用户对直观且高效的用户界面需求日益增加。现有技术中，移动设备上的软件键盘占用屏幕空间，影响内容显示和操作效率。尤其是在单手操作或屏幕空间有限的情况下，用户体验不佳。本发明旨在解决在触摸屏设备上优化键盘显示与内容区域切换的问题。

**Summary (发明总览)**:  
本发明提出了一种通过用户拖动操作来隐藏软件键盘并扩展内容显示区域的方法。用户可以通过向键盘底部边缘拖动来移除键盘，使内容区域占据更多屏幕空间。该方法还包括在拖动过程中动态调整键盘外观，例如滑动或压缩键盘。此外，系统可根据用户选择自动重新显示键盘。本发明通过简化用户操作，提升了移动设备上的交互效率和用户体验。

**Key Innovation (核心创新)**:  
1. 通过用户向键盘底部边缘的拖动操作触发键盘隐藏，实现单手操作的便捷性。
2. 在拖动过程中动态调整键盘外观，例如滑动或压缩键盘，提供直观的用户反馈。
3. 在移除键盘后，系统可根据用户选择自动重新显示键盘，例如在用户点击文本输入框时。
4. 在键盘和内容区域之间显示用户可选择的控件，这些控件根据用户已输入的文本提供搜索建议。
5. 搜索应用可与操作系统集成，识别特定的拖动手势以隐藏键盘，并提供更强大的搜索功能。
6. 通过记录用户交互数据并获得用户同意后，系统可个性化搜索结果的呈现方式。
7. 本发明特别适用于移动设备上的搜索应用场景，通过优化屏幕空间利用，提升用户搜索体验和效率。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485344472)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12717473)**
<br/><br/>

---


<br/>

### 36. 使用热传感器进行表面敲击和触摸定位

**Title (EN)**: Surface tap and touch localization using thermal sensors  
**Pub. No.**: US12717446

**Applicant**: GOOGLE LLC  
**Inventor**: [Karan Ahuja](https://patents.google.com/?inventor=Karan+Ahuja&country=US&num=100&sort=new), [Mar Gonzalez Franco](https://patents.google.com/?inventor=Mar+Gonzalez+Franco&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
一种方法包括确定用户身体部位相对于表面的姿态。该表面与用户佩戴的设备生成的虚拟界面相关联。该方法还包括接收指示用户身体部位与表面部分接触的热数据。该方法进一步包括使用热数据确定相对于虚拟界面的接触位置。该方法还包括使用热数据确定与接触相关的交互类型。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485344443_1.jpg)

**Technical Field (技术领域)**:  
扩展现实（XR）技术领域，具体涉及使用热传感器进行用户交互检测和定位。

**Background (发明背景)**:  
扩展现实（XR）设备融合了物理和虚拟世界，包括虚拟现实（VR）、增强现实（AR）和混合现实（MR）。这些设备通过阻挡现实世界（VR）、将数字内容叠加到现实世界（AR）或无缝融合数字和物理元素（MR）来使用户沉浸在数字环境中。现有的XR设备主要依赖摄像头和运动传感器进行交互检测，但在复杂环境中可能存在精度不足或交互方式受限的问题。

**Summary (发明总览)**:  
本发明提出了一种基于热传感器的新型用户交互检测方法，通过检测用户身体部位与表面之间的接触并分析热数据来确定交互位置和类型。该方法首先确定用户相对于虚拟界面对应表面的姿态，然后利用热数据识别接触位置，并进一步分析交互类型。与传统方法相比，本发明利用热数据提高了交互检测的准确性和可靠性，尤其适用于复杂环境下的用户交互。

**Key Innovation (核心创新)**:  
1. 利用热传感器检测用户与表面之间的接触，通过热数据识别交互位置，实现高精度定位。
2. 通过分析热数据的变化模式，确定用户交互的类型，例如敲击、滑动或长按等。
3. 将热传感器数据与用户姿态数据结合，提升交互检测的准确性和可靠性。
4. 在虚拟界面中映射热数据检测结果，实现用户与虚拟内容的无缝交互。
5. 相比传统摄像头和运动传感器方案，热传感器方案在低光或遮挡环境下表现更稳定。
6. 该技术可应用于XR设备，如AR眼镜和VR头显，提升用户交互的自然性和沉浸感。
7. 独特价值在于提供了一种新的交互检测维度，特别适用于需要精细控制和复杂交互的应用场景，如工业培训或医疗模拟。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485344443)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12717446)**
<br/><br/>

---


<br/>

### 37. 使用深度学习模型在直播视频上提供三维图形叠加的计算机实现方法

**Title (EN)**: Computer-implemented methods for providing three-dimensional graphic overlays on live videos using a depth machine learning model  
**Pub. No.**: US12718454

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Ran Schley](https://patents.google.com/?inventor=Ran+Schley&country=US&num=100&sort=new), [Gabriel Pragier](https://patents.google.com/?inventor=Gabriel+Pragier&country=US&num=100&sort=new), [Lior Fritz](https://patents.google.com/?inventor=Lior+Fritz&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
描述了使用深度学习模型在直播视频上提供图形叠加的技术。根据一些示例，一种计算机实现方法包括：接收体育赛事的直播流；确定直播流中显示的体育赛事比赛场地与直播流帧之间的映射；通过机器学习模型生成深度图，该深度图基于输入的映射和帧中显示的多个运动员的指示，指示单个运动员的相应深度；并且基于深度图将图形插入直播流的帧中。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345556_1.jpg)

**Technical Field (技术领域)**:  
计算机视觉与图形处理领域，具体涉及基于深度学习的实时视频图形叠加技术。

**Background (发明背景)**:  
服务提供商或内容创作者通常使用数据中心向用户或客户端提供内容，例如体育赛事的视频。在视频中包含图形叠加可能是有益的，但现有技术通常耗时且复杂，且计算资源有限，仅能生成二维图形，无法处理有运动员或障碍物的复杂场景。

**Summary (发明总览)**:  
本发明提出了一种在体育赛事直播视频中动态叠加三维图形的解决方案。其核心思路是结合深度学习模型和实时视频流处理技术，通过分析比赛场地与视频帧的映射关系，生成运动员的深度信息，并基于此将三维图形精确叠加到视频中。与现有技术相比，本发明能够处理复杂的动态场景，并提供更逼真的图形叠加效果。

**Key Innovation (核心创新)**:  
1. 利用深度学习模型生成视频帧中运动员的深度图，从而实现对运动员位置的精确识别。
2. 通过将比赛场地映射到视频帧，建立场地与视频帧之间的空间关系，为图形叠加提供基础。
3. 基于生成的深度图，将三维图形动态插入直播视频帧中，实现逼真的叠加效果。
4. 采用机器学习模型处理复杂场景，包括多个运动员和动态障碍物，提升图形叠加的准确性和适应性。
5. 优化了实时视频处理流程，确保图形叠加的实时性和流畅性。
6. 该技术可应用于体育赛事直播，为观众提供增强现实体验，例如在比赛画面中叠加虚拟标识或信息。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345556)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12718454)**
<br/><br/>

---


<br/>

### 38. 个性化设备例程

**Title (EN)**: Personalized device routines  
**Pub. No.**: US12719963

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Sven Eberhardt](https://patents.google.com/?inventor=Sven+Eberhardt&country=US&num=100&sort=new), [Soyoung Kim](https://patents.google.com/?inventor=Soyoung+Kim&country=US&num=100&sort=new), [Maisie Wang](https://patents.google.com/?inventor=Maisie+Wang&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明涉及个性化设备例程的系统和方法，包括确定与用户账户数据相关联的设备，并生成设备使用数据以指示智能设备在一段时间内的使用情况。使用数据可用于识别候选智能设备、时间指示符和触发事件类型，以与候选例程相关联。基于使用数据和所涉及的触发事件类型，可以向用户推荐一个或多个候选例程，以实现设备例程推荐的个性化。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485347223_1.jpg)

**Technical Field (技术领域)**:  
智能设备自动化领域，具体涉及基于用户行为模式的设备例程推荐技术。

**Background (发明背景)**:  
随着智能设备（如语音接口设备）的普及，用户需要更智能的设备交互方式。现有的设备例程通常基于预设规则或简单的用户输入，缺乏对用户行为模式的深入理解。这导致设备例程的适用性和个性化程度不足，难以满足用户的个性化需求。

**Summary (发明总览)**:  
本发明通过分析用户设备使用数据，识别用户行为模式，并基于这些模式生成个性化的设备例程推荐。具体实现路径包括收集设备使用数据、识别关键触发事件和时间模式，以及推荐优化的设备例程。本发明相较于现有技术的主要改进在于引入了数据驱动的个性化推荐机制，使得设备例程更加贴合用户的实际使用习惯。

**Key Innovation (核心创新)**:  
1. 通过分析用户账户数据，识别与用户相关的智能设备及其使用模式，实现对用户行为的深入理解。
2. 生成设备使用数据，包括设备使用频率、时间段和交互类型，为个性化推荐提供数据基础。
3. 基于使用数据识别候选智能设备、时间指示符和触发事件类型，构建候选例程库。
4. 采用数据驱动的方法，根据用户历史行为和偏好推荐最相关的设备例程，提高推荐的精准度。
5. 实现例程的动态调整，根据用户行为变化自动更新推荐例程，保持例程的适应性和实用性。
6. 通过识别时间模式和触发事件类型，优化设备例程的执行时机，提高设备响应效率和用户体验。
7. 本专利可应用于智能家居、语音助手等场景，为用户提供个性化的设备交互方案，提升智能设备的使用便捷性和智能化水平。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485347223)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12719963)**
<br/><br/>

---


<br/>

### 39. 基于编码光图案调整镜头位置的设备和方法

**Title (EN)**: Devices and methods for adjusting lens positions based on encoded light patterns  
**Pub. No.**: US12717137

**Applicant**: META PLATFORMS TECHNOLOGIES, LLC  
**Inventor**: [Brian Wheelwright](https://patents.google.com/?inventor=Brian+Wheelwright&country=US&num=100&sort=new), [Jacques Gollier](https://patents.google.com/?inventor=Jacques+Gollier&country=US&num=100&sort=new), [Ying Geng](https://patents.google.com/?inventor=Ying+Geng&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
一种用于提供位置引导光的设备包括第一设备和第二设备。第一设备包括用于输出第一光的第一光源、用于输出第二光的第二光源，以及用于引导第一光和第二光沿不同方向传播的第一光学元件，使得第一光和第二光沿第一参考轴在空间上分离。第二设备包括用于输出第三光的第三光源、用于输出第四光的第四光源，以及用于引导第三光和第四光沿不同方向传播的第二光学元件，使得第三光和第四光沿与第一参考轴大致平行或垂直的第二参考轴在空间上分离。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485344103_1.jpg)

**Technical Field (技术领域)**:  
显示设备领域，具体涉及头戴式显示设备的光学调节技术。

**Background (发明背景)**:  
头戴式显示设备正成为向用户提供视觉信息的重要工具。不同用户具有不同的瞳距，而错误的瞳距设置会导致视觉失真。此外，用户眼睛与显示设备出瞳（例如最后一个镜头）之间的距离也需要适当，否则会降低视场角，影响用户体验。现有的瞳距和眼距调节方法通常需要专业人员的协助，否则用户难以准确设置。

**Summary (发明总览)**:  
本发明提供了一种通过编码光图案辅助用户调整头戴式显示设备光学组件位置的方法。该方法利用空间分离的光束作为引导信号，帮助用户调整镜头组的位置，以实现准确的瞳距和眼距设置。通过第一和第二光源发出的光束在空间上的分离和交叉，用户可以直观地判断并调整设备的位置，从而优化视觉体验。

**Key Innovation (核心创新)**:  
1. 采用空间分离的光束作为瞳距和眼距调节的引导信号，通过第一光和第二光的空间偏移提供调整提示。
2. 设计了第一光学元件，用于引导第一光和第二光沿不同方向传播，确保光束在空间上的分离。
3. 通过第二设备发出的第三光和第四光，进一步增强调整精度，确保用户能够准确设置瞳距。
4. 利用光束交叉点作为参考，用户可以通过观察光束是否正确相交来判断调整是否准确。
5. 提供了一种无需专业设备即可实现瞳距和眼距精确调整的方法，降低了用户使用门槛。
6. 该技术可应用于头戴式显示设备，通过优化光学组件的位置，提升用户的视觉体验和设备易用性。
7. 特别适用于需要频繁调整光学设置的应用场景，如多用户共享设备或不同视力条件的用户使用同一设备时。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485344103)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12717137)**
<br/><br/>

---


<br/>

### 40. 基于传感器输出的设备交互检测与分类

**Title (EN)**: Detection and classification of interaction with device based on sensor output  
**Pub. No.**: US12717420

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Niranjan Thontadarya](https://patents.google.com/?inventor=Niranjan+Thontadarya&country=US&num=100&sort=new), [Santhosh Kumar Vojjala](https://patents.google.com/?inventor=Santhosh+Kumar+Vojjala&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明描述了一种基于传感器输出检测和分类设备交互的技术。在一个示例中，设备通过对传感器输出信号进行采样，生成第一、第二和第三离散样本。设备基于第一测量窗口生成代表输出信号第一部分的第一值，并基于该第一值确定检测到与设备的交互。随后，设备基于第二测量窗口生成代表输出信号第二部分的第二值，并基于第一值和第二值生成指示交互分类的分类数据。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485344415_1.jpg)

**Technical Field (技术领域)**:  
传感器技术；人机交互；信号处理

**Background (发明背景)**:  
随着智能设备的普及，用户与设备的交互方式日益多样化，如语音控制、触摸操作等。现有技术中，设备通常依赖单一传感器或简单的信号处理方法进行交互检测，难以应对复杂场景下的交互识别需求。这可能导致误判或漏判，影响用户体验。

**Summary (发明总览)**:  
本发明提出了一种基于多测量窗口的传感器信号处理方法，用于检测和分类用户与设备的交互。通过对传感器输出信号进行分段采样和分析，设备能够更准确地识别交互类型并作出响应。该方法通过结合多个测量窗口的数据，提高了交互检测的准确性和可靠性，相较于传统方法具有更高的鲁棒性。

**Key Innovation (核心创新)**:  
1. 采用多测量窗口技术，将传感器输出信号分段处理，实现对交互信号的精细化分析。
2. 通过生成多个离散样本和对应的值，构建交互检测的多层次模型，提高检测精度。
3. 基于第一值和第二值的联合分析，实现对交互类型的分类，区分不同类型的用户操作。
4. 利用时间序列分析技术，对传感器信号进行动态监测，适应不同场景下的交互模式。
5. 通过优化测量窗口的设置和采样策略，减少误判和漏判，提升交互识别的可靠性。
6. 该技术可应用于智能音箱、智能家居设备等，支持语音、触摸等多种交互方式。
7. 独特价值在于提升设备对复杂交互场景的适应能力，为用户提供更自然和精准的交互体验。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485344415)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12717420)**
<br/><br/>

---


<br/>

### 41. 自电容传感器装置的操作方法

**Title (EN)**: Operation of self-capacitive sensor apparatus  
**Pub. No.**: US12718193

**Applicant**: AMAZON TECHNOLOGIES, INC.  
**Inventor**: [Rachid M. Alameh](https://patents.google.com/?inventor=Rachid+M.+Alameh&country=US&num=100&sort=new), [Frederick Hershel Savage](https://patents.google.com/?inventor=Frederick+Hershel+Savage&country=US&num=100&sort=new), [Jiri Slaby](https://patents.google.com/?inventor=Jiri+Slaby&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
一种用于库存位置的装置，用于存放物品，包括一组传感器元件。每个传感器元件包含多个导电元件，这些导电元件可以作为自电容传感器进行驱动。一组或多个传感器元件可以与特定通道相关联。基于自电容值的变化和这种关联，可以确定用户与之交互的通道。在设置过程中，可以确定与特定通道相关联的传感器元件组。在操作期间，可以驱动导电元件以补偿由于环境温度或物品变化引起的自电容变化。补偿后的电容数据可用于确定交互。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345269_1.jpg)

**Technical Field (技术领域)**:  
本发明涉及库存管理技术，具体为基于自电容传感器的物品检测与交互识别技术。

**Background (发明背景)**:  
在库存管理中，实时监控物品数量和移动对于高效运营至关重要。现有技术通常依赖人工操作或简单的传感器系统，难以准确跟踪物品位置和状态变化。本发明旨在解决库存管理中物品交互检测的准确性问题，特别是在复杂环境或高密度存储场景下。

**Summary (发明总览)**:  
本发明提出了一种基于自电容传感器的库存管理方案，通过布置传感器阵列来检测物品的交互行为。传感器元件被组织成多个通道，每个通道对应特定的物品存放区域。通过分析自电容值的变化，系统能够识别用户与特定通道的交互行为。该方案通过温度补偿机制提高了检测精度，并利用设置过程中的关联数据实现更可靠的物品跟踪。

**Key Innovation (核心创新)**:  
1. 采用自电容传感器阵列技术，通过多个导电元件的协同工作，实现对物品交互的高精度检测。
2. 设计了通道关联机制，将传感器元件与特定物品存放区域进行绑定，提升了检测的针对性和准确性。
3. 引入温度补偿算法，通过实时监测环境温度变化并调整电容值，有效减少了误报和漏报。
4. 在设置过程中，通过对传感器元件的校准和通道关联的确定，确保系统在不同环境下的稳定性和可靠性。
5. 通过补偿后的电容数据进行分析，能够更准确地识别用户与物品的交互行为。
6. 该方案特别适用于高密度存储环境，如仓库、图书馆和博物馆等场景，能够有效提升库存管理的效率和准确性。
7. 通过减少人工干预和误操作，该技术可广泛应用于自动化库存管理和智能零售等领域。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345269)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12718193)**
<br/><br/>

---


<br/>

### 42. 多结果呈现

**Title (EN)**: Multiple results presentation  
**Pub. No.**: US12718803

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Dongmin Kim](https://patents.google.com/?inventor=Dongmin+Kim&country=US&num=100&sort=new), [Mohammad Kachuee](https://patents.google.com/?inventor=Mohammad+Kachuee&country=US&num=100&sort=new), [Chetan Nagaraj Naik](https://patents.google.com/?inventor=Chetan+Nagaraj+Naik&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
在一些公开的实施例中，接收并处理与语音对应的音频数据，以确定至少第一自然语言理解（NLU）假设和第二NLU假设。对于该语音，确定第一NLU假设可能比第二NLU假设更准确，并使设备呈现与第一NLU假设对应的内容。设备还可以显示一个图形用户界面（GUI）元素，该元素可被选择以执行与第二NLU假设对应的操作。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345944_1.jpg)

**Technical Field (技术领域)**:  
语音识别技术领域，具体涉及自然语言理解（NLU）处理和多结果呈现。

**Background (发明背景)**:  
语音识别系统已经发展到人类可以通过语音与计算设备进行交互的程度。这些系统使用技术来识别人类用户所说话语的词汇。
现有的语音识别和自然语言理解处理技术虽然能够实现基于语音命令的设备控制，但在处理歧义或多可能的理解结果时缺乏灵活性。
本发明旨在解决在语音处理中处理多个可能理解结果的问题，并提供更直观的结果呈现方式。

**Summary (发明总览)**:  
本发明提出了一种处理语音输入并呈现多个理解结果的方法。
首先，系统接收语音输入并生成多个NLU假设。
然后，系统确定哪个假设最可能准确，并优先呈现该结果。
同时，系统提供一个可交互的界面元素，允许用户选择执行次优的NLU假设对应的操作。
这种设计在保证主要结果准确性的同时，也为用户提供了处理其他可能性的途径。

**Key Innovation (核心创新)**:  
1. 通过接收语音输入并生成多个NLU假设，系统能够处理语音中的歧义或多种可能的理解结果。
2. 系统采用优先级判定机制，确定哪个NLU假设最可能准确，并优先呈现该结果。
3. 提供可交互的GUI元素，允许用户选择执行次优的NLU假设对应的操作，从而提高交互的灵活性和用户的控制力。
4. 通过这种多结果呈现方式，系统能够在保证主要结果准确性的同时，为用户提供了处理其他可能性的途径。
5. 该方法可以应用于智能助手、语音控制设备等场景，提升用户在使用语音交互时的体验和效率。
6. 通过提供次优结果的访问路径，系统能够更好地适应用户的不同需求和偏好。
7. 这种设计在语音识别和自然语言理解处理中引入了新的交互模式，填补了现有技术在处理多可能结果方面的空白。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345944)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12718803)**
<br/><br/>

---


<br/>

### 43. 用于预测性模拟结果的交互式用户界面

**Title (EN)**: Interactive user interface for predictive simulation results  
**Pub. No.**: US12717989

**Applicant**: Amazon Technologies, Inc.  
**Inventor**: [Andrew Chester Russell](https://patents.google.com/?inventor=Andrew+Chester+Russell&country=US&num=100&sort=new), [Abraham Cantwell](https://patents.google.com/?inventor=Abraham+Cantwell&country=US&num=100&sort=new), [Thomas Tyler Parsons](https://patents.google.com/?inventor=Thomas+Tyler+Parsons&country=US&num=100&sort=new)  
**Publication Date**: 25.08.2026

**Abstract**:  
本发明公开了用于预测性模拟结果的交互式用户界面的各种实施例，这些结果是通过对模拟空间进行自动采样得到的。在一些实施例中，系统配置为接收清单和输入数据对象，以在模拟器上执行模拟项目。系统可以根据模拟项目的采样空间标准生成模拟项目的样本输入空间样本。执行模拟项目以基于输入数据对象生成模拟输出。可以基于至少部分模拟输出训练机器学习模型。系统可以配置为生成用户界面，以基于查询显示模拟项目的预测性模拟输出。

**Patent Drawings**:

![Patent Drawing]({{ site.baseurl }}/assets/images/2026-08/US485345042_1.jpg)

**Technical Field (技术领域)**:  
本专利涉及模拟仿真技术领域，具体涉及基于机器学习的预测性模拟结果交互式展示技术。

**Background (发明背景)**:  
模拟器在探索新设计配置或商业理念时具有重要价值，能够在实施前发现潜在瓶颈或意外运行状态。然而，即使是简单的模型也可能包含数百万种潜在配置，模拟过程可能需要数小时才能完成。这种复杂性限制了模拟技术的实际应用效率。

**Summary (发明总览)**:  
本发明提出了一种基于自动采样和机器学习的预测性模拟结果交互展示方法。系统通过自动采样生成模拟输入样本，执行模拟并训练机器学习模型，最终生成用户界面以展示预测结果。该方法通过减少模拟次数和利用机器学习加速预测过程，显著提升了模拟效率。用户可以通过交互式界面快速获取不同配置下的模拟结果，从而优化决策过程。

**Key Innovation (核心创新)**:  
1. 通过自动采样技术生成模拟输入样本空间，减少了需要执行的模拟次数，提高了模拟效率。
2. 利用机器学习模型对模拟输出进行训练，实现了从有限样本中快速预测模拟结果的功能。
3. 提供了交互式用户界面，允许用户实时查询和查看不同配置下的预测性模拟结果。
4. 系统能够根据用户输入动态调整采样策略，优化模拟结果的准确性和覆盖范围。
5. 通过将机器学习与模拟技术结合，解决了传统模拟方法在处理复杂模型时的效率问题。
6. 该技术可应用于产品设计优化、流程改进和风险评估等场景，帮助用户快速评估多种方案。
7. 独特价值在于提供了一种高效、直观的模拟结果展示方式，使用户能够更快速地做出明智决策。

**[View Full Patent @ WIPO](https://patentscope2.wipo.int/search/en/detail.jsf?docId=US485345042)**  
**[View Full Patent @ Google Patents](https://patents.google.com/patent/US12717989)**
<br/><br/>

---



**Total Patents**: 43  
**Last Updated**: 20260829

---

The Patent Scoop Trio
