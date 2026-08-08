# SubspaceHunter-SAO

<h3 align="center">
中文 | <a href="README.en.md">English</a>
</h3>

<p align="center">
  <img src="docs/images/readme-hero.png" alt="SubspaceHunter-SAO 项目 Logo" width="720">
</p>

SubspaceHunter-SAO 是一个开源的可商用的 Unity XR(VR+MR) 动作游戏项目框架以及可商用的原创美术资产、代码、特效、UI等；围绕类似 SAO 风格的交互、战斗和场景体验进行开发的项目。
项目在2022年由年仅22岁的Hexin Wang 在UCAS大学的宿舍中开发并免费发布下载；国内外社交媒体上传播的刀剑神域VR、SAO、Sword Art Online、以及2023年的Quest3 SAO视频均出自于此项目；
项目发起的初心是为了构建一个完全沉浸式基于脑机接口的无限庞大的多人在线虚拟世界，但由于当时技术不发达以及AI尚未崛起的原因，凭借个人的力量无法实现如此宏大的计划；在2026年Hexin Wang
转向World Model创业创立了Cardinal AI，希望能通过AIGC能力解决大规模3D可交互内容的生产力需求，让每一个人都能制作初属于自己的3A世界。本项目将会作为Cardinal AI开发的官方教程与最佳
实践案例，通过教程的形式教学如何通过Cardinal AI开发出一款VRMMO多人在线动作游戏。 


## 通过本项目你将学会/获得
1. 如何构建支持 Meta Quest 等 XR 一体机应用的开发、环境设置
2. 如何优化 VR 场景性能以及渲染处理
3. 带有物理的冷兵器刀剑战斗系统、魔法战斗系统、枪械战斗系统
4. 敌人角色物理系统打击感模拟（打击特效、音效）
5. 九种可拓展的敌人行为树 AI 战斗逻辑、技能设计、距离控制、动画控制
6. XR 设备粒子特效系统的处理与优化
7. XR 原生的手势追踪 UI 交互系统与 UI 动画构建
8. MR 场景下与环境相融合的阴影处理
9. XR 设备串流调试与开发
10. 9 个关卡场景、数种武器道具、十几种不同风格的士兵级、领主级、Boss 级敌人美术资产
11. 学会使用 Cardinal AI 生成配音、音乐、3D 模型、UI 等 AIGC 功能辅助开发<br>
https://www.bilibili.com/video/BV13h4y1B71P/<br>
https://www.bilibili.com/video/BV1za41197PR/<br>
https://www.bilibili.com/video/BV1jX4y1H76f/<br>
https://www.bilibili.com/video/BV1mW421X7jg/<br>

## 开源、可商用资产说明

原创美术资源统一集中在改目录下： Assets/SubspaceHunter/Model/SubspaceHunter-model 

项目中的UI交互、动画、物理系统模拟、战斗逻辑与行为树设计均为原创可商业化使用

<img src="docs/images/readme-characters.png" alt="SubspaceHunter-SAO 角色与敌人资产展示" width="100%">

<img src="docs/images/readme-public-demo.png" alt="SubspaceHunter-SAO 公开 Demo 展示" width="100%">

<img src="docs/images/readme-mr-demo.png" alt="SubspaceHunter-SAO MR 战斗展示" width="100%">

<img src="docs/images/readme-scene-collage.png" alt="SubspaceHunter-SAO 场景展示合集" width="100%">


## 由Hexin Wang 团队制作但不允许商业使用、仅供交流学习的SAO资产

希斯克里夫、青眼恶魔、狗头人领主、石头人、食人花、判教徒尼古拉斯、狗头人骑士、野猪

<img src="docs/images/readme-third-party-assets.png" alt="SubspaceHunter-SAO 第三方资产与 IP 相关资产展示" width="100%">

<img src="docs/images/readme-sao-scenes.png" alt="SubspaceHunter-SAO SAO 场景资产展示" width="100%">

## 第三方资产Package如需商业化需取得授权

项目中涉及第三方资产包、插件、SDK 和库时，商业化前需要由使用者自行确认授权范围、购买状态和再分发条款。当前审计清单见 [docs/THIRD_PARTY_ASSET_PACKAGES.zh-CN.md](docs/THIRD_PARTY_ASSET_PACKAGES.zh-CN.md)。

## 项目架构与功能逻辑

代码模块、公开 Demo 场景入口、战斗/敌人/武器/技能/UI 等系统说明见 [docs/ARCHITECTURE.zh-CN.md](docs/ARCHITECTURE.zh-CN.md)。

## Unity 版本

- Unity Editor：`2021.3.45f1`
- 主要目标平台：Android / Quest / PCVR 设备
- XR 相关包：Oculus XR、OpenXR、XR Management


## 快速开始

1.下载Github仓库资产<br>
2.使用 Unity `2021.3.45f1` 打开<br>
3.载资产Unitypackage包，链接: https://pan.baidu.com/s/15FRPMi91qJzsarMVTewV6g?pwd=bx4w 提取码: bx4w <br>
4.将unitypackage导入项目<br>
5.找到Assets/PublicDemo/PublicScenes/文件夹，下面包含多个样例场景
6.All_Enemy中包含了所有敌人的演示，运行场景后可以直接看到说有敌人的战斗状态

## 由Hexin Wang 创立的SpatialXR社区提供免费的VR/MR开发教程

https://www.bilibili.com/video/BV17KG46TEw2/

## Cardinal AI | 世界模型驱动的3D可交互内容生成Agent

开发者招聘：
团队已完成千万级Pre-Seed融资。公司目前正在高速发展期，需要一名经验成熟与优秀职业素养的AIAgent应用的前后端开发工程师，
主导或协作2C产品研发全流程。该岗位负责与算法团队合作搭建具身智能/游戏生成两种场景下应用产品的工程落地与应用开发，
建立全链路Al Agent体系。目前期权池充足，根据实际工作成果与能力授予期权奖励<br>
联系王师傅：z04041015

1.官网：https://www.cardinal-agi.com/<br>
2.效果演示：https://www.bilibili.com/video/BV18ERbBNENp/<br>
3.测试Q群：104716484<br>

<img src="docs/images/readme-cardinal-ai.png" alt="Cardinal AI 可用于 3D 可交互内容生成的工作流展示" width="100%">

## 贡献注意事项

- 不要提交 `Library/`、`Temp/`、`Logs/`、`UserSettings/`、`.csproj` 或 `.sln` 文件。
- 确认可再分发的大体量二进制资源可使用unitypackage通过网盘链接的形式提交。
- 提交 Unity 资源时必须保留对应 `.meta` 文件。
- 不要提交 API Key、服务凭证、签名文件、私有数据库或其他敏感信息。
- 国内项目交流Q群：303140187

## Star History

<a href="https://www.star-history.com/?repos=whx-prog%2FSubspaceHunter-SAO&type=date&legend=top-left">
 <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=whx-prog/SubspaceHunter-SAO&type=date&legend=top-left" />
</a>
