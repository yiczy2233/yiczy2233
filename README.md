# 👨‍💻 Zoey Cai | Technical Artist & Digital Twin Developer

> **"Elegance is the art of concealing complexity behind simplicity."**
> *—— 将复杂的数字孪生逻辑，转化为简约的交互视觉。*

---

## 🏗️ 职业特质 (Professional Focus)
我致力于在 **工业 4.0** 与 **数字孪生** 领域寻找技术与美学的平衡。通过 Unity 与 WebGL 技术，将复杂的物理世界映射为直观、优雅的数字世界。

- 🎓 **Unity 开发者**: 专注 WebGL 端的数字孪生性能优化。
- 🎨 **视觉构建者**: 熟练使用 Blender 进行工业建模，追求 PBR 材质下的极简工业风。
- ✍️ **DaC 践行者**: 坚持“图表即代码”，利用 Mermaid 进行系统架构的逻辑建模。

---

## 🛠️ 技术栈 (Technical Stack)

### 核心引擎与视觉
![Unity](https://img.shields.io/badge/Unity-222222?style=for-the-badge&logo=unity&logoColor=white)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=for-the-badge&logo=webgl&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)

### 逻辑与工程
- **语言**: C# (Unity), JavaScript (Web), PowerShell (Automation)
- **文档与可视化**: Mermaid, Markdown, Obsidian
- **工具链**: pnpm, Vite, Git (Workflow optimization)

---

## 🏢 数字孪生项目逻辑 (System Architecture)

这是我处理数字孪生项目时的典型逻辑流（以粮库可视化为例）：

```mermaid
graph LR
    subgraph Physical_World[物理世界]
        Sensor[传感器/物联网数据]
        Structure[粮库建筑实体]
    end

    subgraph Digital_Twin[数字孪生系统]
        direction TB
        Logic{Unity 核心逻辑}
        Visual[Blender 精模 / WebGL 渲染]
        UI[简约交互界面]
    end

    Sensor -->|数据流| Logic
    Structure -->|几何抽象| Visual
    Logic & Visual --> UI
    UI -->|用户体验| Result[优雅的决策支持]

    style Digital_Twin fill:#f9f9f9,stroke:#333,stroke-width:2px
