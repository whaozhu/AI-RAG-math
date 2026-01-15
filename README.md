# AI-RAG-math 

## 简介

此 RAG（检索增强生成）多轮问答系统基于最新数学学术论文作为外部文档，专注于解决特定数学问题。系统能够从专业文献中检索相关信息，提供准确、渐进式的数学问题解答。

## 目标

- 利用最新数学研究成果增强解答能力
- 实现从基础解释到深度分析的多轮渐进式问答
- 解决数学研究中术语解释碎片化问题

## 功能

- **知识检索**：系统能够从外部数学文献中检索相关信息。
- **多轮对话**：支持与用户进行多轮交互，逐步解决问题。
- **问题解答**：针对特定数学问题提供准确的答案。

## 说明
thesis-some chapter.txt文件是RAG系统的外部文档。 它是基于我的博士论文相关章节的latex版本建立的。

相关论文  1. “On the geometry of punctual Hilbert schemes on singular curves and their motivic zeta functions”,  M.Hajli, H.Mourtada, W.Zhu， https://arxiv.org/abs/2509.06761
         2. “Reduced Hilbert schemes for irreducible curve singularities”, G.Pfister and J.H.M. Steenbrink

### 环境

- Python 3.12.3
- 相关依赖库（具体见 `requirements.txt`）

### 安装步骤

1. **克隆仓库**

   ```bash
   git clone https://github.com/whaozhu/AI-RAG-math.git
   cd AI-RAG-math

2. 安装依赖库：

   pip install -r requirements.txt

3. 配置环境变量：
创建 .env 文件，添加：
DASHSCOPE_API_KEY = api_key
