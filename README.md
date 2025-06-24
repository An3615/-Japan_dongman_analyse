# 日本动漫数据分析项目 | Power BI 实战案例

**动漫行业数据可视化 · 多工具协同分析 · 商业智能报告展示**

---

## 项目简介

本项目基于 B 站平台的日本动漫数据，构建一个完整的数据分析流程：从数据采集、清洗、入库，到可视化展示。通过 Power BI 打造直观、交互性强的可视化报表，帮助用户洞察动漫作品的流行趋势、受众偏好和市场表现。

数据说明：  
- 数据来源于 B 站网页，通过爬虫获取
- 抓取对象为 **非电影类的日本动漫作品**

---

## 主要分析内容

- 动漫发行数量与趋势分析  
- 动漫评分与热度分布  
- 不同年份、类型作品的变化情况  
- 用户偏好与作品受欢迎程度对比
- 等等  

---

## 使用技术与工具

| 工具/平台         | 作用说明                     |
|------------------|------------------------------|
| **后羿采集器**       | 网页爬取 B 站动漫数据             |
| **Jupyter Notebook** | 使用 Python 进行数据清洗与处理     |
| **MySQL**         | 存储结构化清洗后的数据           |
| **Power BI Desktop** | 数据可视化分析与报表设计         |

---

## 项目实现流程

1. **数据采集**：使用后羿采集器爬取 B 站日本动漫信息，保存为 `raw1.csv`
2. **数据清洗**：利用 Jupyter Notebook 编写脚本处理数据，去除冗余、修复缺失项
3. **数据入库**：将清洗后的数据写入本地 MySQL 数据库
4. **可视化分析**：
   - Power BI 连接 MySQL 数据库
   - 构建数据模型与图表，制作交互式报表

- 后羿采集器
![image](https://github.com/user-attachments/assets/258e82d0-cea3-45fc-9f6f-8da2f96e149d)
- `raw1.csv`文件示例
![image](https://github.com/user-attachments/assets/b1135fe0-26a3-4f1e-9891-ff97951d550b)
- 清洗后的数据示例（MySQL）
![image](https://github.com/user-attachments/assets/ecebb2af-bd2f-4368-8d47-6e4362998f8b)
- BI可视化分析示例
![image](https://github.com/user-attachments/assets/e8e38b78-3e96-4a9e-a994-10ae746a1f38)
![image](https://github.com/user-attachments/assets/1c7bbf3c-4305-4b4a-acfb-92daa8c8b0c9)

---

## 📁 项目结构说明

```text
Japan_dongman_analyse/
├── data/
│ ├── raw1.csv # 原始采集数据
│ └── 数据清洗.ipynb # Python 数据清洗脚本
├── bi主题设置/
│ ├── background.pptx # 用于编辑可视化背景
│ ├── background1.png
│ ├── bi.json # BI 主题配色文件
│ └── Sales Analytical Report Insights.png # 本项目所用的BI主题所需的参考报表
├── 动漫数据分析报表.pbix # Power BI 报表文件（主文件）
└── README.md # 项目说明文档（本介绍文件）
```

## 项目价值

- 熟练掌握从数据采集、数据清洗、MySQL 数据的应用与管理、可视化分析的全流程
- 锻炼数据建模能力与报表设计能力
- 实战运用 Power BI 制作专业级动态仪表板

---

## 数据来源与许可说明

数据抓取自 B 站公开网页，仅用于学习与非商业目的的分析演示。若涉及隐私或侵权，请联系项目作者下线相关内容。

---

## 联系方式

- GitHub: [@An3615](https://github.com/An3615)
- Email: 1840349950@qq.com

---
