# 数据可视化项目 (Data Visualization Project)

这是一个数据可视化实践项目，包含多个数据分析与可视化的 Jupyter Notebook 示例。
如果 GitHub 无法加载，[请点击这里查看 Notebook](https://nbviewer.org/github/captain2003white/dv-for-uber/blob/main/4320251005_ChengJingyun18th-WUTNOV25.ipynb)

## 📋 项目简介

本项目展示了如何使用 Python 进行数据分析和可视化，涵盖了以下内容：
- 数据加载与预处理
- 数据转换与清洗
- 使用 Matplotlib、Seaborn 和 Plotly 进行数据可视化
- 时间序列分析
- 地理数据可视化

## 📁 项目结构

```
.
├── 4320251005_ChengJingyun18th-WUTNOV25.ipynb  # Uber 数据分析与可视化
├── DataViz_Prac2_together.ipynb                # CO₂ 排放数据可视化实践
├── uber-raw-data-apr14.csv                     # Uber 2014年4月原始数据
├── d2.csv                                       # 数据集2
└── README.md                                    # 项目说明文档
```

## 🚀 快速开始

### 环境要求

- Python 3.7+
- Jupyter Notebook 或 JupyterLab

### 安装依赖

```bash
pip install pandas numpy matplotlib seaborn plotly
```

或者使用项目中的安装命令（在 Notebook 中运行）：

```python
!pip install pandas numpy matplotlib seaborn plotly
```

## 📊 项目内容

### 1. Uber 数据分析 (`4320251005_ChengJingyun18th-WUTNOV25.ipynb`)

该 Notebook 包含以下分析内容：
- **数据加载**：使用 pandas 读取 CSV 文件
- **数据转换**：
  - 日期时间转换
  - 提取日期、星期、小时等信息
- **可视化分析**：
  - 按日期（DoM）的频率分布直方图
  - 按小时和星期的分布分析
  - 工作日与小时的交叉分析热力图
  - 经纬度数据的地理分布可视化

### 2. CO₂ 排放数据可视化 (`DataViz_Prac2_together.ipynb`)

该 Notebook 包含以下内容：
- **数据集**：
  - CO₂ 排放数据（Our World in Data）
  - World Bank 指标数据
- **数据清洗**：处理缺失值
- **可视化类型**：
  - 折线图（时间序列）
  - 柱状图
  - 直方图
  - 散点图
  - 箱线图/小提琴图
- **交互式可视化**：使用 Plotly Express 创建交互式图表

## 🛠️ 技术栈

- **Python**: 主要编程语言
- **Pandas**: 数据处理与分析
- **NumPy**: 数值计算
- **Matplotlib**: 基础数据可视化
- **Seaborn**: 统计图表绘制
- **Plotly**: 交互式可视化

## 📝 使用说明

1. 克隆或下载本项目到本地
2. 确保已安装所需的 Python 包
3. 打开 Jupyter Notebook
4. 运行相应的 Notebook 文件查看分析结果

## 📄 数据说明

- `uber-raw-data-apr14.csv`: 包含 2014 年 4 月 Uber 的出行数据，包含日期时间、经纬度等信息
- `d2.csv`: 辅助数据集

## 👤 作者信息

- **学生**: ChengJingYun
- **课程**: WUT_Nov2025
- **指导教师**: Mano Joseph MATHEW

## 📚 学习目标

通过本项目，您将学习到：
- 使用 Jupyter 环境进行数据分析
- 数据加载、转换和清洗的基本技巧
- 选择合适的图表类型进行数据可视化
- 使用多种可视化库创建美观的图表
- 通过可视化传达数据洞察

## 🔗 相关资源

- [Pandas 文档](https://pandas.pydata.org/docs/)
- [Matplotlib 文档](https://matplotlib.org/stable/contents.html)
- [Seaborn 文档](https://seaborn.pydata.org/)
- [Plotly 文档](https://plotly.com/python/)

## 📌 注意事项

- 数据文件较大，建议使用 Git LFS 或从其他来源下载
- 运行 Notebook 前请确保已安装所有依赖包
- 部分可视化可能需要较长的运行时间

---

**"通过可视化信息，我们将其转化为可以用眼睛探索的景观。一种信息地图。当你在信息中迷失时，信息地图是很有用的。"**

