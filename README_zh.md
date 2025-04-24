# Heygem - Heygen的开源平替产品 [【Switch to English】](./README.md)

## 【致开发者伙伴的重要通知】

**亲爱的Heygem开源社区成员：**

衷心感谢各位对Heygem数字人开源项目的热情关注与积极参与！我们注意到部分开发者在本地部署环节遇到挑战，为更好地满足不同场景需求，现同步告知两项并行服务方案：

| **项目** | **HeyGem开源本地部署**                                                             | **数字人/克隆音API接口服务**                                              |
| -------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------- |
| 使用方式 | 开源本地部署                                                                       | 极速克隆API服务                                                           |
| 推荐     | 技术型用户                                                                         | 业务型用户                                                                |
| 技术门槛 | 具备深度学习框架经验/追求深度定制化/希望参与社区共建的开发者                       | 快速业务集成/专注上层应用开发/需企业级SLA保障的商用场景                   |
| 硬件要求 | 需要购买GPU服务器                                                                  | 无需购买GPU服务器                                                         |
| 定制化   | 可以根据自己的需求对代码进行修改和扩展，完全掌控软件的功能和行为                   | 无法直接修改源代码，只能通过API提供的接口进行功能扩展，灵活性不如开源项目 |
| 技术支持 | 社区支持                                                                           | 动态扩容支持 + 专业技术响应团队                                           |
| 维护成本 | 维护成本高                                                                         | 维护简单                                                                  |
| 口形效果 | 效果可用                                                                           | 效果惊艳且更高清                                                          |
| 商用授权 | 支持全球免费商用（用户量超过10万或年营收达1000万美元以上的企业需签署商业许可协议） | 可商用                                                                    |
| 迭代速度 | 更新慢，Bug修复依赖社区                                                            | 最新模型/算法优先适用，问题修复快                                         |

我们始终秉持开源初心，API服务的推出旨在为不同需求的开发者提供更完整的解决方案矩阵。无论您选择哪种方式，都可随时通过end_sub@hotmail.com获取技术支持文档。期待与各位共同推动数字人技术的普惠发展！

**硅基智能开发者团队**

[**极速克隆API**](https://app.guiji.cn/platform) | [**API文档中心**](https://guiji.cn/digital-docs/introduce/)

[**实时交互SDK**](https://app.guiji.cn/platform) | [**SDK文档中心**](https://guiji.cn/duix-light-document/introduce/)

[**本地实时交互（realtime）duix.ai 开源地址**](https://github.com/GuijiAI/duix.ai) |
[**Android版本**](https://github.com/GuijiAI/duix.ai/blob/main/duix-android/dh_aigc_android/README.md) |
[**IOS版本**](https://github.com/GuijiAI/duix.ai/blob/main/duix-ios/GJLocalDigitalDemo/GJLocalDigitalSDK.md)

<img src="./README_zh.assets/1CB5196D-C989-4577-8C57-DCBA3E0871B2-51277-000008CE6CF0B87B.jpg" width="50%">

## 介绍

<img src="README_zh.assets/image-20250304114114272.png">
Heygem是一款专为Windows系统设计的全离线视频合成工具，它能够精确克隆您的外貌和声音，让您的形象数字化。您可以通过文字和语音驱动虚拟形象，进行视频制作。无需联网，保护隐私的同时，也能享受到便捷和高效的数字体验。

- 核心功能
  - 精确外貌与声音克隆：运用先进的 AI 算法，高精度捕捉真人外貌特征，包括五官形状、面部轮廓等，构建逼真虚拟模型。同时，能精准克隆声音，捕捉并还原人声的细微特征，支持多种声音参数设置，可创造与原声高度相似的克隆效果。
  - 文字和语音驱动虚拟形象：通过自然语言处理技术理解文本内容，将文字转换为自然流畅的语音，实现文字驱动虚拟形象。也可直接使用语音输入，让虚拟形象根据语音的节奏、语调等进行相应的动作和表情变化，使虚拟形象的表现更加自然、生动。
  - 高效视频合成：将数字人的视频画面与声音高度同步，实现自然流畅的口型匹配，智能优化音视频同步效果。
  - 多语言：脚本支持八种语言，英语、日语、韩语、中文、法语、德语、阿拉伯语和西班牙语。
- 显著优势
  - 全离线操作：无需联网即可使用，有效保护用户隐私，让用户在安全、独立的环境中进行创作，避免数据在网络传输过程中可能存在的泄露风险。
  - 简单易用：操作界面简洁直观，即使是没有任何技术背景的小白也能轻松上手，快速掌握软件的使用方法，轻松开启数字人创作之旅。
  - 多模型支持：支持导入多个模型，并通过一键启动包进行管理，方便用户根据不同的创作需求和应用场景选择合适的模型。
- 技术支持
  - 声音克隆技术：利用人工智能等先进技术，根据给定的声音样本生成与之相似或相同声音的技术，涵盖语音中的语境、语调、语速等。
  - 自动语音识别：一种能将人类语音中的词汇内容转换为计算机可读输入，也就是转换为文本格式的技术，让计算机能够 “听懂” 人们说的话。
  - 计算机视觉技术：用于视频合成中的视觉处理，包括面部识别、口型分析等，确保虚拟形象的口型与声音和文字内容相匹配。

## 依赖

1. Nodejs 18
2. Docker Image
   - docker pull guiji2025/fun-asr
   - docker pull guiji2025/fish-speech-ziming
   - docker pull guiji2025/heygem.ai

## 如何安装

<video src="https://cdn.guiji.ai/heygem/heygem-install.mp4" controls="controls" style="max-width: 730px;">
</video>

### 前置条件

1.  必须有 D 盘：主要用于后续数字人、作品等数据存储
    - 空闲空间要求：大于30G
2.  C 盘：用于存储服务镜像文件

    - 空闲空间要求：大于 100G
    - 如果不足 100G，可以在安装完成docker后，在下图的位置重新选一个剩余空间大于 100G 的磁盘文件夹。

      ![output](README_zh.assets/output.png)

3.  系统要求：
    - 目前支持 Windows 10 19042.1526 或更高版本
4.  推荐配置：
    - CPU：第13代英特尔酷睿 i5-13400F
    - 内存：32G及以上（必要）
    - 显卡：rtx-4070
5.  确保有英伟达显卡，并正确安装显卡驱动（必要）

    英伟达驱动下载地址 https://www.nvidia.cn/drivers/lookup/

    ![nvidia](README_zh.assets/nvidia.png)

### 安装 Windows Docker

1. 用wsl --list --verbose命令可以查看本机有没有安装过wsl，如下图就是已经安装过，无需再安装

   ![image-20250310111137019](README_zh.assets/image-20250310111137019.png)

> - 安装wsl的命令：`wsl --install`
> - 由于网络原因，可能失败，多试几次
> - 安装过程中需要设置新的用户名和密码，设置并记住

2. 用wsl --update更新wsl。

   ![updatewsl](README_zh.assets/updatewsl.png)

3. [下载 Docker Windows 版](https://www.docker.com/)，根据机器 CPU 架构选择不同的安装包。

4. 出现这个界面表示安装成功。

   ![61eb4c19-3e7a-4791-a266-de4209690cbd](README_zh.assets/61eb4c19-3e7a-4791-a266-de4209690cbd.png)

5. 运行 Docker

   ![shortcut](README_zh.assets/shortcut.png)

6. 首次运行接受协议和跳过登录

   ![accept](README_zh.assets/accept.png)

   ![576746d5-5215-4973-b1ca-c8d7409a6403](README_zh.assets/576746d5-5215-4973-b1ca-c8d7409a6403.png)

   ![9a10b7b2-1eea-48c1-b7af-34129fe04446](README_zh.assets/9a10b7b2-1eea-48c1-b7af-34129fe04446.png)

### 安装服务端

采用Docker方式安装，docker-compose如下：

1. `docker-compose.yml`文件在`/deploy`目录下。
2. 在`/deploy`目录执行`docker-compose up -d`
3. 耐心等待一段时间（半小时左右，速度取决于网速），下载会消耗70G左右流量，注意连WIFI
4. 看到Dokcer 中出现三个服务，表示成功了

   ![e29d1922-7c58-46b4-b1e9-961f853f26d4](README_zh.assets/e29d1922-7c58-46b4-b1e9-961f853f26d4.png)

### 客户端

1. 直接下载[官方构建的安装包](https://github.com/GuijiAI/HeyGem.ai/releases)
2. 双击`HeyGem-x.x.x-setup.exe`即可安装

## 开放 API

我们开放了模特训练和视频合成的API，Docker 启动后会在本地暴露几个端口，通过`http://127.0.0.1`可以调用。

具体代码可以参考

- src/main/service/model.js
- src/main/service/video.js
- src/main/service/voice.js

### 模特训练

1. 将视频分离为静音视频 + 音频
2. 音频放到`D:\heygem_data\voice\data`下
   > `D:\heygem_data\voice\data`是与`guiji2025/fish-speech-ziming`服务约定的，可以在docker-compose中修改
3. 调用`http://127.0.0.1:18180/v1/preprocess_and_tran`接口
   > 参数示例：
   >
   > ```json
   > {
   >   "format": ".wav",
   >   "reference_audio": "xxxxxx/xxxxx.wav",
   >   "lang": "zh"
   > }
   > ```
   >
   > 返回示例：
   >
   > ```json
   > {
   >   "asr_format_audio_url": "xxxx/x/xxx/xxx.wav",
   >   "reference_audio_text": "xxxxxxxxxxxx"
   > }
   > ```
   >
   > **记录下返回结果后续音频合成需要用到**

### 音频合成

接口：`http://127.0.0.1:18180/v1/invoke`

```json
// 请求参数
{
  "speaker": "{uuid}", // 一个UUID保持唯一即可
  "text": "xxxxxxxxxx", // 需要合成的文本内容
  "format": "wav", // 固定传参
  "topP": 0.7, // 固定传参
  "max_new_tokens": 1024, // 固定传参
  "chunk_length": 100, // 固定传参
  "repetition_penalty": 1.2, // 固定传
  "temperature": 0.7, // 固定传参
  "need_asr": false, // 固定传参
  "streaming": false, // 固定传参
  "is_fixed_seed": 0, // 固定传参
  "is_norm": 0, // 固定传参
  "reference_audio": "{voice.asr_format_audio_url}", // 上一步“模特训练”的返回值
  "reference_text": "{voice.reference_audio_text}" // 上一步“模特训练”的返回值
}
```

### 视频合成

- 合成接口：`http://127.0.0.1:8383/easy/submit`

  ```json
  // 请求参数
  {
    "audio_url": "{audioPath}", // 音频路径
    "video_url": "{videoPath}", // 音频路径
    "code": "{uuid}", // 唯一key
    "chaofen": 0, // 固定值
    "watermark_switch": 0, // 固定值
    "pn": 1 // 固定值
  }
  ```

- 进度查询：`http://127.0.0.1:8383/easy/query?code=${taskCode}`
  > get 请求，参数`taskCode`是上面合成接口的返回值

## 常见问题

[常见问题](./doc/常见问题.md)

## 提问前自查步骤

1. 三个服务是否都是Running状态

   ![e29d1922-7c58-46b4-b1e9-961f853f26d4](./doc/常见问题.assets/e29d1922-7c58-46b4-b1e9-961f853f26d4.png)

2. 确认机器上是有英伟达显卡且正确安装了驱动程序。

   本项目所有算力都在本地，没有英伟达显卡或没有驱动程序，以上三个服务是启动不了的。

3. 确保服务端和客户端都更新到了最新版本，项目刚开源，社区很活跃，更新也比较频繁，说不定你的问题已经在新版中解决了。

   - 服务端：到`/deploy`目录下重新执行`docker-compose up -d`
   - 客户端：`pull`代码后重新`build`

4. [GitHub Issuse](https://github.com/GuijiAI/HeyGem.ai/issues)持续更新，每天都在解决和关闭问题单，经常看看，也许你的问题已经解决了。

## 提问模板

1. 问题描述

   详细描述一下复现步骤，如有截图最好。

2. 提供报错日志

   - 客户端日志获取方式

     ![image-20250308205954494](./doc/常见问题.assets/image-20250308205954494.png)

   - 服务端日志

     找到关键位置，或点开我们的三个Docker服务，如下图操作“复制”。

     ![image-20250308215812201](./doc/常见问题.assets/image-20250308215812201.png)

## 联系我们

```
  James@toolwiz.com
```

## 协议

[LICENSE](./LICENSE)

## 致谢

- ASR 基于 [fun-asr](https://github.com/modelscope/FunASR)
- TTS 基于 [fish-speech-ziming](https://github.com/fishaudio/fish-speech)
