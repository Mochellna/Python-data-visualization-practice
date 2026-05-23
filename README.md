# 🐧 Palmer Penguins Data Visualization Analysis  
# 帕默群岛企鹅数据可视化分析

---

## 项目概览 / Project Overview

本项目基于 Palmer Penguins 数据集，通过数据可视化与探索性分析，研究企鹅种类、性别以及所在岛屿，与企鹅身体特征（包括体重、嘴峰长度、嘴峰深度、鳍长度）之间的关系。

通过本项目，练习使用 Python 进行数据读取、数据探索、统计分析以及数据可视化，为后续更深入的数据分析与机器学习建模打下基础。

---

## 数据概览 / Data Overview

- **样本数量**：334 条企鹅样本数据
- **数据来源**：南极洲帕默群岛三个岛屿
- **企鹅种类**：Adelie、Chinstrap、Gentoo
- **分析目标：**
  - 不同企鹅种类之间的身体特征差异
  - 性别与体重、鳍长度之间的关系
  - 岛屿分布与企鹅特征之间的联系

---

## 数据字段说明 / Data Description

| 字段名 | 含义 |
|------|------|
| species | 企鹅种类 |
| island | 企鹅所在岛屿 |
| culmen_length_mm | 企鹅嘴峰长度（mm） |
| culmen_depth_mm | 企鹅嘴峰深度（mm） |
| flipper_length_mm | 企鹅鳍长度（mm） |
| body_mass_g | 企鹅体重（g） |
| sex | 企鹅性别 |

---

## 分析目标 / Objectives

本项目希望通过可视化分析回答以下问题：

1. **不同种类企鹅的身体特征是否存在明显差异？**

2. **性别是否会影响企鹅体重与鳍长度？**
   
3. **不同岛屿上的企鹅分布情况如何？**
   
4. **企鹅各项身体指标之间是否存在相关性？**

---

## 分析流程 / Analysis Process

本项目主要围绕企鹅数据的探索性分析与可视化展开，流程包括：

1. **数据读取与基础检查**
   - 查看数据结构与字段类型
   - 检查缺失值与异常值

2. **数据清洗**
   - 处理缺失值
   - 删除异常记录
   - 统一字段格式

3. **数据可视化分析**
   - 不同企鹅种类的身体属性分布
   - 性别与体重、鳍长度的关系
   - 岛屿分布与企鹅种类关系
   - 特征变量之间的相关性分析

4. **数据洞察总结**
   - 对不同种类企鹅特征差异进行总结
   - 分析体型特征与性别、岛屿之间的关联

---

## 分析结论 / Key Findings

- **Gentoo 企鹅整体体型最大，平均体重最高**
- **雄性企鹅普遍比雌性更重**
- **鳍长度与体重存在明显正相关关系**
- **不同岛屿上的企鹅种类分布存在差异**

---

## 技术栈 / Tech Stack

- **语言**: Python
- **库**: Pandas, NumPy, Matplotlib, Seaborn
- **工具**: Jupyter Notebook, VSCode, Git & GitHub

---

## 项目结构 / Project Structure

```text
Penguins-Visualization/
│
├── Penguins.csv
├── penguins_analysis.ipynb
├── README.md
├── requirements.txt
│
└── images/
    ├── species_distribution.png
    ├── body_mass_boxplot.png
    └── correlation_heatmap.png
```

---

## 复现指南 / Reproduction Guide

### 1. 克隆仓库

```bash
git clone https://github.com/Mochellna/Python-data-visualization-practice.git
```

### 2. 安装依赖

```bash
pip install -r requirements.txt
```

### 3. 打开 Notebook

在 Jupyter Notebook 中打开：

```text
penguins_analysis.ipynb
```

### 4. 运行项目

按顺序运行 Notebook 单元格，即可复现完整的数据分析与可视化流程。

