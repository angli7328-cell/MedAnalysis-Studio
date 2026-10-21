# MedAnalysis Studio

**Offline AI-Powered Medical Statistical Analysis Software**

**本地化人工智能医学统计分析软件 | 中文 / English**

MedAnalysis Studio is a desktop application for medical research, epidemiology, biostatistics, and public health education. It combines a locally deployed large language model with professional statistical tools, enabling users to perform medical data analysis through natural language.

MedAnalysis Studio 是一款面向临床科研、流行病学、卫生统计学及医学教学的智能统计分析软件。研究人员无需编写程序，即可通过自然语言完成数据处理、统计分析、可视化和报告生成。

## Key Features | 核心功能

* **Natural Language Statistical Analysis** — 使用中文或英文描述分析需求，自动识别分析任务并调用统计工具。
* **93 Statistical Tools** — 集成93项统计工具，覆盖12个功能模块。
* **Local AI Inference** — 内置 EpiMind 本地推理引擎，基于 Qwen2 系列量化模型。
* **Offline Operation** — 模型推理与统计计算均在本地执行，无需连接云端AI服务。
* **Dual Verification** — 采用数值核验与统计方法学审计机制。
* **Bilingual Interface** — 支持中文与英文界面切换及双语交互。
* **Research Visualization** — 支持常见医学统计图形及专业科研可视化。
* **Report Generation** — 可生成 Word、HTML 和 Markdown 分析报告。

## Statistical Modules | 统计功能模块

| Module                   | 模块     |
| ------------------------ | ------ |
| Data Management          | 数据管理   |
| Data Cleaning            | 数据清洗   |
| Descriptive Statistics   | 描述性统计  |
| Hypothesis Testing       | 假设检验   |
| Regression Analysis      | 回归分析   |
| Survival Analysis        | 生存分析   |
| Epidemiological Analysis | 流行病学分析 |
| Machine Learning         | 机器学习   |
| Time Series Analysis     | 时间序列分析 |
| Data Visualization       | 数据可视化  |
| Report Generation        | 报告生成   |
| Privacy Protection       | 隐私保护   |

## System Requirements | 系统要求

| Item                | Requirement                      |
| ------------------- | -------------------------------- |
| Operating System    | Windows 10 / 11 (64-bit)         |
| Memory              | 8 GB minimum, 16 GB recommended  |
| Storage             | 15 GB minimum, 20 GB recommended |
| Processor           | 64-bit x86 CPU                   |
| GPU                 | Optional NVIDIA GPU acceleration |
| Internet            | Not required for analysis        |
| Python Installation | Not required                     |

## Download | 软件下载

**Latest version: v1.0.1 (Windows Portable)**

[Download the latest release](https://github.com/angli7328-cell/MedAnalysis-Studio/releases/latest)

*The download link will become available after the first release is published.*

软件下载链接将在首个正式版本发布后启用。

## Installation | 安装与启动

MedAnalysis Studio is distributed as a portable Windows application and does not require a separate Python installation.

由于程序包含本地大语言模型，发布文件可能分为多个压缩分卷。

1. Download all release archive parts into the same folder.
2. Use 7-Zip to extract the first `.7z.001` file.
3. Extract the resulting ZIP archive.
4. Open the extracted application folder.
5. Launch `MedAnalysis Studio.exe`.
6. Wait until EpiMind finishes loading.

请保持程序主文件与 `resources` 目录位于同一软件文件夹中，不要单独移动可执行文件。

## Basic Usage | 基本使用

**Step 1 — Import Data / 导入数据**

支持 CSV、Excel、SPSS、Stata、SAS、Parquet 等多种数据格式。

**Step 2 — Ask a Statistical Question / 输入分析问题**

Example:

`按treatment分组，生成age、sex、bmi和sbp的基线特征表。`

Or in English:

`Calculate descriptive statistics for age, BMI, and systolic blood pressure in dataset df1.`

**Step 3 — Review Results / 查看分析结果**

系统生成分析计划，执行统计计算，并展示结果与核验信息。

**Step 4 — Export / 导出**

保存统计表格、图形或完整分析报告。

## Local AI Engine | 本地推理引擎

EpiMind is the integrated inference engine of MedAnalysis Studio. It uses a locally deployed quantized model from the Qwen2 family.

The language model is responsible for interpreting statistical requests and coordinating tools, while statistical computations are performed by dedicated analysis functions.

EpiMind 为系统内部推理引擎的名称，并非独立预训练的基础大语言模型。

## Intended Use | 适用范围

MedAnalysis Studio is designed for medical research, statistical education, epidemiological studies, and exploratory data analysis.

It is not intended to replace professional statistical review or provide independent clinical diagnosis or treatment decisions.

## Feedback | 问题反馈

Users can submit bug reports and feature suggestions through the [GitHub Issues](https://github.com/angli7328-cell/MedAnalysis-Studio/issues) section.

欢迎通过 Issues 反馈软件运行问题、功能建议及使用体验。

## Acknowledgements | 致谢

MedAnalysis Studio incorporates open-source technologies and a quantized model from the Qwen2 family. Third-party components remain subject to their respective licenses and attribution requirements.

---

**MedAnalysis Studio — Making Medical Statistical Analysis More Accessible.**
