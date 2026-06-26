# Lenovo ISG AI Sales Copilot（AI销售解决方案助手）

> 本项目为个人学习项目（Personal Learning Project），模拟 Lenovo ISG（Infrastructure Solutions Group）售前 AI 解决方案设计流程，不代表联想官方产品。

---

# 项目背景 | Project Background

随着生成式 AI（Generative AI）在企业中的快速应用，越来越多的客户希望部署 AI 基础设施（AI Infrastructure），但往往不知道如何规划整体方案。

本项目基于 **Meta Llama 3.2 + Hugging Face Transformers + Gradio**，开发了一个 AI Sales Copilot，用于模拟 Lenovo ISG 售前咨询流程。

系统能够根据客户行业、业务需求以及业务挑战，自动生成 AI 基础设施解决方案建议（AI Solution Recommendation），帮助销售团队提高售前分析效率。

---

# 项目目标 | Project Objective

模拟 Lenovo ISG 售前咨询（Pre-sales Consulting）的完整流程：

✅ Customer Summary（客户背景分析）

✅ Business Challenges（业务挑战分析）

✅ Lenovo AI Solution Recommendation（AI解决方案推荐）

✅ Sales Strategy（销售策略建议）

✅ Next Follow-up Actions（下一步销售行动）

✅ AI Opportunity Assessment（AI商机评分）

整个分析流程均由 **Meta Llama 3.2** 自动生成。

---

# 技术栈 | Tech Stack

- Python
- Meta Llama 3.2
- Hugging Face Transformers
- PyTorch
- Gradio
- Google Colab

---

# 项目功能 | Features

### Customer Summary

自动分析客户企业背景。

---

### Business Challenges

识别客户当前业务痛点。

例如：

- Data Privacy
- Compliance
- Scalability
- High Availability
- Cost Optimization

---

### Lenovo AI Solution Recommendation

根据客户需求生成完整 AI Solution Architecture，包括：

- AI Infrastructure Strategy
- GPU Resource Planning
- High-performance Storage Architecture
- Private AI Strategy
- Hybrid AI Deployment Strategy
- Security & Compliance
- AI Lifecycle Management
- Expected Business Value


---

### Sales Strategy

自动生成销售沟通建议，包括：

- 如何切入客户需求
- 如何突出业务价值
- 如何推进下一阶段沟通

---

### Next Follow-up Actions

自动生成下一步销售计划，例如：

- Schedule Follow-up Meeting
- Proof of Concept (POC)
- Architecture Workshop
- Proposal Preparation

---

### AI Opportunity Assessment

自动评估销售机会，包括：

- Opportunity Score（0-100）
- Priority（High / Medium / Low）
- Business Reasons
- Recommended Next Sales Action

---

# Demo Scenarios（案例演示）

目前支持多个行业：

Healthcare（医疗）

Finance（金融）

Manufacturing（制造业）

未来可扩展：

- Retail
- Education
- Government
- Telecom
- Energy

---

# Gradio Demo

本项目集成了 Gradio Web Interface。

销售人员无需编写代码，仅需输入：

- Industry
- Company
- Country
- Budget
- Business Need
- Business Challenge

系统即可自动生成完整 AI 售前解决方案。

---

## Demo Screenshots

### 1. AI Sales Copilot Interface

<img width="1440" height="778" alt="    AI-generated Lenovo ISG Solution Recommendation" src="https://github.com/user-attachments/assets/12a2513b-68f5-4c3e-93de-18ec4e0ee43c" />


### 2. Example Input (BMW Manufacturing Case)

<img width="1440" height="777" alt="BMW Manufacturing" src="https://github.com/user-attachments/assets/5ad7b354-3e16-4e8a-8335-bba93f0c135d" />


### 3. AI-generated Lenovo ISG Solution Recommendation

<img width="1439" height="633" alt="BMW_Output1" src="https://github.com/user-attachments/assets/290843f0-5a04-45ae-9914-7b3a76467fe8" />

<img width="1440" height="631" alt="BMW_Output2" src="https://github.com/user-attachments/assets/86ae27f2-e02b-4ff0-9cae-15d76c067717" />

<img width="1440" height="636" alt="BMW_Output3" src="https://github.com/user-attachments/assets/4bc18837-2bd2-48fb-aa18-025cec177a70" />


# Business Value（项目价值）

本项目展示了 Generative AI 在企业售前咨询（Pre-sales Consulting）中的应用价值。

能够帮助企业：

- 提高需求分析效率
- 标准化售前方案输出
- 提升销售沟通效率
- 辅助 AI Opportunity Qualification
- 提高 Solution Recommendation 一致性

---

# Future Improvements（未来计划）

- Retrieval-Augmented Generation（RAG）
- Vector Database（向量数据库）
- Multi-Agent Collaboration
- PDF Proposal 自动生成
- CRM Integration（Salesforce / Dynamics）
- Customer Knowledge Base

---

# Author

**Jianan(Rebecca) Li**

Master of Quantitative Management (Business Analytics)

2026

---
