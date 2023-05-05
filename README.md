# open-chat-video-editor
Open Chat Video Editor是开源的短视频生成和编辑工具，整体技术框架如下：

![sys](https://user-images.githubusercontent.com/21036347/236424150-ff67dd18-5c6e-41ff-a865-340e63e8ff98.png)

目前具有以下特点：
- 1、**一键生成可用的短视频**，包括：配音、背景音乐、字幕等。

- 2、算法和数据均基于开源项目，方便技术交流和学习
- 3、支持多种输入数据，方便对各种各样的数据，一键转短视频，目前支持：
- [x] **短句转短视频**(Text2Video): 根据输入的简短文字，文本模型自动生成生成文案，并自动生成短视频
- [x] **网页链接转短视频**(URL2Video): 自动对网页的内容进行提取，生成视频文案，并自动生成短视频
- [ ] **长视频转短视频**(Long Video to Short Video): 对输入的长视频进行自动分析和自动摘要，并生成短视频
- 4、涵盖**生成模型**和**多模态检索模型**等多种主流算法和模型

文本生成上，支持：
- [x] ChatGPT 
- [ ] BELLE
- [ ] Alpaca
- [ ] Dolly 
等多种模型

视觉信息生成上，支持图像和视频两种模态，生成方式上，支持检索和生成两种模型，目前共有6种模式：
- [x] 图像检索
- [x] 图像生成（stable diffusion）
- [x] 先图像检索，再基于stable diffusion 进行图像生成
- [x] 视频检索
- [ ] 视频生成（stable diffusion）
- [ ] 视频检索后，再基于stable diffusion 进行视频生成






