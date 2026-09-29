---
name: literature-review
description: 为工业设计（含产品设计、交互设计、用户体验、设计研究、人因工程、可持续设计、CMF 等）方向撰写文献综述。当用户要求做文献综述、研究综述、related work、文献梳理、研究现状、国内外研究现状、开题报告的文献部分，或整理参考文献、转换引用格式时使用。支持 GB/T 7714-2015、APA 7、MLA 9、Chicago、IEEE、Harvard 等引用格式。
---

# 工业设计文献综述

按以下流程为用户完成文献综述。每一步都要让用户能核对来源，**绝不编造文献**。

## 0. 先确认需求

开始前确认下面几项；用户没说的，用括号里的默认值，并在开头说明用了默认值：

- **主题与研究问题**：要综述什么？最好能写成 1–3 个研究问题。
- **用途**：课程论文 / 本科毕设 / 硕博开题 / 期刊论文 related work（默认：学位论文开题）。
- **篇幅**：（默认：3000–5000 字）。
- **时间范围**：（默认：近 10 年为主，经典奠基文献不受限）。
- **语言范围**：（默认：中英文文献都要，对应"国内研究现状"和"国外研究现状"）。
- **引用格式**：见 `references/citation-styles.md`（默认：GB/T 7714-2015 顺序编码制）。
- **输出形式**：Markdown / Word（.docx）（默认：仓库里的 Markdown 文件）。

## 1. 检索

### 检索式
- 把研究问题拆成 2–4 个概念块，每块列出中英文同义词，块内用 OR、块间用 AND。
- 在综述末尾的"检索说明"里附上实际使用的检索式、数据库和检索日期。

### 工业设计常用来源
- **中文**：中国知网 CNKI（《包装工程》《装饰》《机械设计》《图学学报》《艺术设计研究》、CSSCI/北大核心）、万方、维普。
- **英文数据库**：Web of Science、Scopus、Google Scholar、ACM Digital Library、IEEE Xplore、ScienceDirect、OpenAlex。
- **核心期刊**：Design Studies、International Journal of Design、Design Issues、She Ji、The Design Journal、CoDesign、Journal of Engineering Design、Research in Engineering Design、Applied Ergonomics、Ergonomics、International Journal of Human-Computer Studies、Journal of Cleaner Production（可持续设计）。
- **会议**：DRS、IASDR、ICED（Design Society）、CHI、DIS、TEI、NordiCHI。
- **经典著作**：可按主题引用 Norman、Krippendorff、Cross、Buchanan、Dorst、Sanders & Stappers、Manzini 等人的奠基文献。

### 检索工具
- 有检索插件或 MCP（如 paper-search / OpenAlex、Exa、PubMed）时优先使用。
- 能联网时可调 OpenAlex API：`https://api.openalex.org/works?search=<关键词>&filter=from_publication_date:2015-01-01&sort=cited_by_count:desc`。
- 不能检索时：请用户提供文献（PDF、知网导出的 RefWorks/EndNote/NoteExpress 文件、BibTeX），只基于这些文献来写。

### 筛选
- 先看标题和摘要初筛，再读全文精筛。纳入和排除标准要写明（主题相关性、文献类型、质量、时间）。
- 记录每一步的文献数量（检索到 → 初筛后 → 精筛后），做系统综述时用 PRISMA 流程图呈现。

## 2. 提取与整理

每篇纳入的文献在 `literature/notes.md`（或用户指定的位置）建一条记录：

| 字段 | 内容 |
|---|---|
| 引用 | 按选定格式写的完整条目 |
| 研究问题 / 目的 | |
| 方法 | 如：文献研究、问卷、访谈、眼动、EEG、用户测试、案例研究、设计实践、参数化或生成式设计、实验 |
| 对象 / 样本 | |
| 主要发现 | |
| 设计启示 | 对设计实践或方法有什么用 |
| 局限 | |
| 主题标签 | 用于后续按主题归类 |

## 3. 综合分析

**按主题组织，不按文献逐篇罗列。** 工业设计综述常用的组织维度：

- **理论视角**：感性工学（Kansei）、情感化设计、以用户为中心的设计、服务设计、可持续或循环设计、包容性设计、设计思维。
- **方法**：定性 / 定量 / 混合；从用户研究到概念生成、评价与验证的完整链条。
- **对象或场景**：产品品类、适老化、医疗、交通、智能家居等。
- **技术**：AIGC 或生成式设计、XR、智能材料、CMF、数字孪生。

每个主题都要写出：共识、分歧、演进脉络和代表文献。可以用对比表格或时间线呈现。

## 4. 撰写结构

1. **引言**：研究背景、综述目的、研究问题、检索说明。
2. **核心概念界定**。
3. **国外研究现状**（按主题分小节）。
4. **国内研究现状**（按主题分小节；期刊论文也可以和国外部分合并，按主题写）。
5. **研究述评**：已有研究的贡献、**不足与空白（研究缺口）**，以及可能的切入点。缺口必须能从前文推出来。
6. **总结与展望**：说明它和用户自己研究的衔接。
7. **参考文献**。

写作要求：
- 用学术书面语，每段都要有论点，避免"某某（2020）研究了……某某（2021）研究了……"式的流水账。
- 每一个事实性陈述都要标注引用。转述时不要歪曲原意，直接引语要加引号并注明页码。

## 5. 引用与核查（必须执行）

- 引用格式按 `references/citation-styles.md` 执行，正文引用和文后列表要一一对应，不能有遗漏或多余。
- **每条文献都必须真实存在。** 只能引用检索到的、或用户提供的文献。核查不了的条目标注【待核实】，并在交付时列出来，**绝不虚构作者、标题、期刊、年份或 DOI**。
- 如果有 DOI，就把 DOI 写上。
- 交付时附一份**核查清单**：文献总数、中英文各多少、近 5 年文献占比、待核实条目。
