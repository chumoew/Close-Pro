<div>

[**English**](README_en.md)

</div>

# Close+

**Close+** 是一个基于Xposed框架的Android广告屏蔽工具，致力于提供一个无广告的应用浏览体验，旨在优化用户体验并减少干扰。请在LSPosed框架环境中使用。

Adlose的核心功能是阻止应用内的广告SDK初始化加载，并拦截应用广告请求以屏蔽广告。


## 主要特性

功能支持(顺序)：

- **精准处理**：阻止应用内广告SDK初始化。
- **广告请求拦截**：拦截屏蔽应用的网络广告请求。
- **传感器监听移除**：用于禁用摇一摇等基于传感器的广告跳转。
- **免Root使用**：可通过LSPatch，NPatch等基于LSPosed核心的免 Root Xposed框架的应用。


## 支持的应用范围

Close+支持众多流行的Android应用，包括但不限于：

- 视频播放应用
- 阅读和新闻应用
- 商务办公应用
- 社交和通讯应用


## 广告SDK处理

Close+能够处理应用内包含以下在内的多种SDK类型：

- ADSuyiSdk Ads
- AdScope
- Ali BaiChuan Ads
- Applovin Sdk
- Appic Ads
- Baidu Ads
- BJXingu Ads
- ByteDance (Pangolin) Ads
- ByteDance (Pangolin) GroMore
- FaceBook Ads
- Google Ads
- Google FireBase Crashlytics Sdk
- Huawei Ads
- Inmobi Ads
- Kwai Ads
- MeiShu Ads
- Mintegral Ads
- Mbridge Ads
- Pinduoduo Ads
- Qumeng Ads
- Sigmob Ads
- Tanx Ads
- Tencent Ads
- Tencent SDK
- TopOn SDK (anythink)
- TradPlus Ads
- Umeng SDK
- Unity3d Ads
- Vungle Sdk
- XiaoChuang Ads (ZuiYou)
- XinwuPaijin Ads
- Xiaomi Ads
- Pangolin advertisement

## 使用指南

在安装Close+之前，请确保您的设备已经安装基于LSPosed核心的免Root Xposed框架的应用。

1. 下载并安装Close模块，或使用Root Xposed框架应用内置。
2. 在免Root Xposed模块管理器中激活Close模块。
3. 在模块作用域中选择您希望去除广告的应用。
4. 启动AdClose模块，选择并点击应用列表，启用相应的Hook功能。


## 如何贡献

如果您对Close+有改进建议，或发现Bug，欢迎通过Issues反馈。


## 支持我们

如果Close+对您有帮助，请给予我们Star支持！这是我们持续改进的最大动力。

