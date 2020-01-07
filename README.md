# API_ML_AI_museum

# 「 妈妈我想去博物馆 」：博物馆APP需求文档

|  发布日期 | 2019/12/12  |  
| :----------: | :-----------:|  
|  产品名称 |  妈妈我想去博物馆  |
|  文件现状 |  已完成  |
|  文件主人 | 陈佳琳  |   
|  关键词  |  观展互动游戏、实时讲解、儿童视角  |

# 第一部分 价值主张
### 1. 加值宣言
#### 一句话版本
**比知识更重要的是让孩子们爱上博物馆**
#### 一段话版本
博物馆记录着人类漫长历史和复杂社会关系，以其实物性、经典性和现场感的特点，对孩子的教育起着无可替代的作用。「 妈妈我想去博物馆 」通过兼顾游戏化设计和知识性普及的「 寻宝记 」功能，调动孩子好奇心和观览兴趣；同时采用地理围栏及时检测游客位置并提供语音导览，达成便捷观展体验。  
**而我们所有行动最终都仍将回落于“比知识更重要的是让孩子们爱上博物馆”这一核心。**

### 2. 核心价值
**最小可行性产品**：为孩子提供观展时的碎片寻宝游戏，在游戏化中普及知识；及时语音导览创造舒适观展体验。

---
# 第二部分 市场分析&竞品分析
### 一、市场分析
#### 1. 市场背景
信息化浪潮席卷全球，世界范围内大大小小的博物馆都在积极建立自己的数字化系统，以各种方式各种应用宣传馆藏文物和展品，在这种趋势下， **博物馆等机构面临的已经不是要不要数字化而是如何数字化的问题**了。尤其是博物馆实行免费开放以来，博物馆成为服务全体社会公众的社会文化教育机构，但**大多数博物馆的教育形式比较单一，更缺乏受众群体针对性（儿童、青少年、成年）**，而移动互联网技术和智能手机的普及恰好为博物馆提升教育服务功能提供机会。
#### 2. 市场分析
目前国内外市场中相关的博物馆App（Louvre HD、苏州博物馆、i Museum、i Daily、e-Museum等）正在逐渐趋同，**基本以导览讲解、藏品介绍功能为主**。虽然模仿和学习已经形成相对成熟的模式，能够极大地降低开发设计成本，也更易于减轻用户的认知成本，然而在功能、内容都趋同的情况下，难免使观众对这些同质化的App感到抵触，进而影响其应用与推广。
### 二、竞品分析

|  竞品  |  类别  |  价值功能  |  特点  |
| :----------: | :-----------:| :-----------|  :-----------:|
|  掌上故宫 |  线下导览类  |  针对故宫全景导览和路线规划  |  全景导览、路线规划  |  
|  故宫全景游 |  线下导览类  |  3D实景导游，语音讲解  |  3D实景导览  |
|  爱去博物馆  |  线下导览类  |  帮助推荐国内外知名博物馆游览线路  |  推荐路线涵盖国内外  |  
|  上海自然博物馆  |  线下馆内互动类  |  AR实景呈现，上海博物馆中的部分动物标本实体化、动态化、场景化  |  AR实景呈现标本  |  
|  北京自然博物馆  |  线下馆内互动类  |  展品互动单元开展主题切入、定位找寻的服务，通过命题促使用户寻找答案  |  观展互动性、定位找寻  |  
|  每日故宫  |  线上静态类  |  日历形式，每日推出展品一件  |  IP化呈现、趣味性  |

#### 竞品小结
总结以上竞品，功能形式以博物馆内路径导览居多，同时导览方式均配以虚拟现实技术，增强访客观展时的即时性与沉浸感。此外，博物馆APP注重提升博物馆与访客的有效互动，期望借互动提升访客观赏趣味性。

---
# 第三部分 产品说明
### 1. 定位
「 妈妈我想去博物馆 」通过兼顾游戏化设计和知识性普及的「 寻宝记 」功能，调动孩子好奇心和观览兴趣；同时采用地理围栏及时检测游客位置并提供语音导览，达成便捷观展体验。而我们所有行动最终都将落脚于“比知识更重要的是让孩子们爱上博物馆”这一核心。

### 2. 问题（用户痛点）
1. 安静的博物馆，安静的文物，晦涩难懂的介绍词，这一切显然超越了孩子的认知界限，勾不起孩子的兴趣。
2. 如何让文物对着孩子“说话”？让孩子和博物馆产生良性互动？进而让孩子获取超越文物本身传递的价值？

### 3. 目标
1. 鼓励更多孩童走进博物馆
2. 增强观览趣味性，达到享受博物馆的目的
2. 让父母更放心，更轻松的带孩子来博物馆

### 4. 目标用户
以未成年儿童为主要面向体验群体、未成年儿童的父母、观展小白、独自观展者

### 5. 用户需求
**（使用的人工智能要反映到需求列表中）**  
|  用户需求 |  对应功能  |  可行API  |  重要程度 |  
| :---------- | :-----------:|  :-----------:|  :-----------:|  
|  父母希望可以让孩子**观览的更有趣**，不因为枯燥乏味而缺乏耐心闹脾气 |  寻宝记  |  [Face++场景与物体识别API](https://www.faceplusplus.com.cn/scene-and-object-recognition/)  | 重要 |  
|  父母/孩子观览时，想**更全面又便捷**的了解到每一展览的背景信息及创作内涵 |  请你听  |  [高德地理围栏API](https://lbs.amap.com/api/webservice/guide/api/geofence_service)  | 重要 |
#### 人工智能概率性：
1. 用户上传的照片不清晰导致识别失败时，弹窗提醒用户需要重新上传清晰照片，并提供拍摄角度以提高识别率。
2. 因网络、设备连接等硬件问题导致的使用问题，为用户检测出问题种类并提供如重启或重新连接网络的具体解决方法，让用户有途径且更有耐心解决问题。
### 6. 具体使用场景
- 场景1：豆妈很希望小豆能多到博物馆接受熏陶，启迪智慧，但想到上次带他去时调皮不耐烦的场景，豆妈觉得双方都很辛苦。昨天听桃子妈讲最近用了一个叫「 妈妈我想去博物馆 」的app，里面有专门为小朋友设计的观展寻宝游戏，现在桃子去博物馆更加乐在其中了。
- 场景2：豆妈每次去博物馆，看到有意思的文物总会扫描文物展柜上的二维码来获取其相关信息，但要逐个扫码豆妈觉得很麻烦，有时候遇到人多时扫码并不方便。自从用了「 妈妈我想去博物馆 」app，豆妈只要走进每个展馆的范围内，app便会提供语音导览及文物介绍，豆妈想要了解那个文物在平台上挑选点击即可，不用再逐一扫码阅读了，更加随心所欲。
- 场景:3：大豆是个爱逛博物馆看展的少年，但每次去博物馆到不同的展馆总得拿不同的介绍册去了解，不擅长整理的他家里堆积了很多观展册。使用了「 妈妈我想去博物馆 」app后，在进入到感兴趣的展馆时收藏平台上同步的电子介绍册即可，日后做观展回顾时也比较方便。

### 7. 功能目标 & 优先级顺序

|  功能名称 | 实现形式  |  核心价值  |  优先级顺序  |  
| :----------: | :-----------| :----------: | :----------: |
|  **寻宝记** |  「 寻宝记 」模块提供所在馆内已有文物的正面照碎片，用户通过寻找到该碎片对应的文物并拍照上传，识别结果正确即寻宝成功，同时可获得该文物详细讲解。  |  趣味性 + 知识性  |  优先  |
|  **请你听** |  用户入馆后打开APP并允许访问位置信息，当用户走到不同展馆时，获取用户地理围栏并投送对应展馆的语音导览，用户只需点击聆听即可。   |  便利性 + 及时性  |  优先  |

### 8. 使用者交互设计
#### 8.1 产品功能结构图
![](https://upload-images.jianshu.io/upload_images/9515896-c1f3f7edfda1a074.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 8.2 产品信息结构图
![](https://upload-images.jianshu.io/upload_images/9515896-da7f9c0ed3eee30f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 8.3 产品结构图
![](https://upload-images.jianshu.io/upload_images/9515896-3f24862906c22405.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 8.1 主要功能交互设计 + 信息设计
![](https://upload-images.jianshu.io/upload_images/9515896-70d113f1fb5f969d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![](https://upload-images.jianshu.io/upload_images/9515896-e418395912bcfa26.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
### 9. 清单
#### [交互原型文档链接](http://tropicallll.gitee.io/api_final_museum)
