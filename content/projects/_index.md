---
title: "项目经历"
layout: "projects"
ShowToc: false
---

以下是三个核心技术项目的展示。每个项目我分别从**算法研发**、**量化分析**、**数据工程**、**产品管理**四种视角做了不同侧重的描述。

---

### 🧠 神经网络架构稳定性研究
*2026.03 — 至今 | 负责人*

量化 2 万—5 万参数 MLP 的混沌动力学特性，通过随机 SVD 降维（复杂度降低 10—12 倍）与全参数统计扫描（r=0.63, p<0.01），揭示架构参数与频域稳定性的显著相关性。

→ [查看详情](neural-dynamics/) · 技术栈：Python / PyTorch / CUDA / NumPy / SciPy

---

### 📸 大规模图像数据处理与还原技术探索
*2025.03 — 2026.03 | 负责人*

对 CelebA 90,000+ 图像构建 PDE 演化模拟管道，通过三重质量控制筛选出 10,240 张高质量样本，建立 MAE/MSE 量化评估体系，验证端到端可行性。

→ [查看详情](image-encryption/) · 技术栈：Python / PyTorch / NumPy / Pandas / Matplotlib

---

### 🔬 科学编程与数值方法系列项目
*2024.09 — 2026.01 | 负责人*

系统实现 Monte Carlo 积分（10 万样本，精度 10⁻³）、PDE 数值求解（1000×1000 参数扫描）、PINN 构建（误差 10⁻⁵）和时间序列分析，覆盖多种数值计算与统计方法。

→ [查看详情](scientific-computing/) · 技术栈：Python / NumPy / SciPy / PyTorch / Matplotlib
