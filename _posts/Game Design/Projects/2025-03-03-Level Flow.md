---
title: "Unity关卡设计蓝图插件：Level Flow"
date: 2025-03-03 00:00:00 +0800
categories: [Game Design, Projects]
tags: [Game Project, Level Design]
---

![Logo](/assets/img/GameDesign/Projects/Level%20Flow/Level%20Flow.png)
*Logo*

## 工具功能
- 丰富的控制结点：方便开发者控制物体移动、光源、特效、镜头行为等等
- 流程图：在流程图中快速编写关卡逻辑，使关卡实时相应玩家动作
- 参数平滑插值：提供Unity曲线、DoTween集成，以创建平滑的变化效果
- 各种结点模板：方便开发者快速创建自定义结点
- 实时读取与保存：方便开发调试

## 项目描述
插件以Uniny Visual Scripting为基础，添加完善了结点和逻辑，使原有工具成为了一个可用于辅助游戏关卡开发的流程图编辑工具，方便开发者能够在编辑器中实时调整流程图的结点、参数、连接顺序，并以此处理游戏对玩家的实时响应。

插件采用了以功能结点作为基础模板，在其之上构建功能结点的架构，通过这样的架构，减少了结点编程的工作量，同时在用户需要自定义结点的时候，也可以通过模板快速构建。

<!-- The plugin is built upon Unity Visual Scripting, enhancing and refining nodes and logic to transform the original tool into a flowchart editing utility that aids in game level development. It allows developers to adjust the nodes, parameters, and connection sequences of the flowchart in real-time within the editor, thereby facilitating the game's real-time responses to player actions. -->

<!-- The plugin employs a foundational architecture where functional nodes serve as base templates, upon which additional functional nodes are constructed. This architecture significantly reduces the workload associated with node programming. Moreover, when users require custom nodes, they can swiftly assemble them utilizing these functional templates. -->

![Flow Example](/assets/img/GameDesign/Projects/Level%20Flow/flow.png){: w="600"}
*流程图实例*

### 工具启发
插件启发自波兰开发商CD Projekt Red的开发管线、《赛博朋克2077》的任务编辑工具，以及我在快手游戏实习时接触到的关卡制作管线。

<!-- The plugin draws inspiration from the development pipeline of Polish developer CD Projekt Red, as well as the mission editing tools used in "Cyberpunk 2077." -->

![Quest Tool for Cyberpunk](/assets/img/GameDesign/Projects/Level%20Flow/cyber.png){: w="600"}
*Cyberpunk 2077 任务工具*

## 截图
![nodes](/assets/img/GameDesign/Projects/Level%20Flow/nodes.png){: w="600"}
*Abundant control nodes.*
![light](/assets/img/GameDesign/Projects/Level%20Flow/light.png){: w="600"}
*Detailed control nodes. (using Lighting as an example)*
![light2](/assets/img/GameDesign/Projects/Level%20Flow/light2.png){: w="600"}
*Customized sub-graph*
![curve](/assets/img/GameDesign/Projects/Level%20Flow/curve.png){: w="600"}
*Curve parameters for smooth control.*
![code](/assets/img/GameDesign/Projects/Level%20Flow/code.png){: w="600"}
*Node template code: enabling developers to quickly create custom nodes.*

## 开发人员
- Development: 韩浩天（Me）
- Mentor：谢文军

> If you have any questions please feel free to contact me<br>
