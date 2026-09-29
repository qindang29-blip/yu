# 引用格式速查

示例用的都是真实文献：
- Dorst（2011）：Design Studies 上的期刊论文。
- Norman（2013）：专著。
- 柳冠中（2006）：中文专著。

## 怎么选

| 格式 | 适用场景 |
|---|---|
| **GB/T 7714-2015**（默认） | 国内学位论文、中文期刊（《包装工程》《装饰》等）。多数高校要求用它 |
| **APA 7** | 设计研究、人因、HCI 类英文期刊（International Journal of Design、Applied Ergonomics 等） |
| **Harvard** | Design Studies、The Design Journal 等 Elsevier / Taylor & Francis 设计期刊，英国高校 |
| **IEEE** | 偏工程的设计研究、IEEE 会议 |
| **Chicago**（作者-年份 或 注释-书目） | 设计史、设计理论、人文取向的论文 |
| **MLA 9** | 艺术与人文类课程论文 |
| **ACM** | CHI、DIS 等 ACM 会议（用 ACM 官方模板自动生成） |

**学校或期刊有自己的模板时，以模板为准。**

---

## GB/T 7714-2015

分两种制式：**顺序编码制**（默认）和**著者-出版年制**。

### 文献类型标识

| 标识 | 文献类型 |
|---|---|
| [M] | 专著 |
| [J] | 期刊 |
| [C] | 会议论文集 |
| [D] | 学位论文 |
| [R] | 报告 |
| [S] | 标准 |
| [P] | 专利 |
| [N] | 报纸 |
| [EB/OL] | 网络资源 |

### 顺序编码制

正文按引用先后编号，写成上标：`……设计思维的核心在于框架建构[1]。`

- 同一处引用多篇：`[1,3]` 或 `[2-4]`。
- 引用同一文献的不同页码：写作 `[1]15`。

文后列表示例：

```
[1] DORST K. The core of 'design thinking' and its application[J]. Design Studies, 2011, 32(6): 521-532. DOI: 10.1016/j.destud.2011.07.006.
[2] NORMAN D A. The design of everyday things[M]. Revised and expanded ed. New York: Basic Books, 2013.
[3] 柳冠中. 事理学论纲[M]. 长沙: 中南大学出版社, 2006.
```

著录规则：
- 作者超过 3 人时，只列前 3 人，后面加"，等"（英文文献加", et al."）。
- 西文作者姓全大写、名缩写且不加缩写点，比如 `DORST K`。
- 标点一律用英文半角。
- 期刊条目的格式为：`年, 卷(期): 起-止页`。

### 著者-出版年制

正文写作：`（Dorst, 2011）`、`（柳冠中, 2006）`。文后列表先按语种分集（中文在前），再按著者字母顺序和出版年排列：

```
柳冠中, 2006. 事理学论纲[M]. 长沙: 中南大学出版社.
DORST K, 2011. The core of 'design thinking' and its application[J]. Design Studies, 32(6): 521-532.
```

---

## APA 7

正文引用有两种写法：
- 括号式：`(Dorst, 2011)`。
- 叙述式：`Dorst (2011)`。

作者人数不同时：
- 两位作者：`(Sanders & Stappers, 2008)`。
- 三位及以上：`(Author et al., 2020)`。

```
Dorst, K. (2011). The core of 'design thinking' and its application. Design Studies, 32(6), 521–532. https://doi.org/10.1016/j.destud.2011.07.006

Norman, D. A. (2013). The design of everyday things (Rev. and expanded ed.). Basic Books.
```

著录规则：
- 列表按作者姓氏字母顺序排列，用悬挂缩进。
- 期刊名和卷号用斜体，书名用斜体。

---

## Harvard

正文写作：`(Dorst 2011)` 或 `(Dorst 2011, p. 525)`。

```
Dorst, K. (2011) 'The core of "design thinking" and its application', Design Studies, 32(6), pp. 521–532. doi:10.1016/j.destud.2011.07.006.

Norman, D.A. (2013) The design of everyday things. Rev. and expanded edn. New York: Basic Books.
```

各期刊的 Harvard 变体细节不同，以投稿指南为准。

---

## IEEE

正文按引用先后编号，写在方括号里：`[1]`。

```
[1] K. Dorst, "The core of 'design thinking' and its application," Design Studies, vol. 32, no. 6, pp. 521–532, 2011, doi: 10.1016/j.destud.2011.07.006.
[2] D. A. Norman, The Design of Everyday Things, rev. and expanded ed. New York, NY, USA: Basic Books, 2013.
```

---

## Chicago（作者-年份）

正文写作：`(Dorst 2011, 525)`。

```
Dorst, Kees. 2011. "The Core of 'Design Thinking' and Its Application." Design Studies 32 (6): 521–32. https://doi.org/10.1016/j.destud.2011.07.006.

Norman, Donald A. 2013. The Design of Everyday Things. Rev. and expanded ed. New York: Basic Books.
```

注释-书目体用脚注，书目部分格式与上面相近，只是年份放在末尾。

---

## MLA 9

正文写作：`(Dorst 525)`。

```
Dorst, Kees. "The Core of 'Design Thinking' and Its Application." Design Studies, vol. 32, no. 6, 2011, pp. 521–32, https://doi.org/10.1016/j.destud.2011.07.006.

Norman, Donald A. The Design of Everyday Things. Revised and expanded ed., Basic Books, 2013.
```

---

## 文献管理工具

推荐用 Zotero（安装 GB/T 7714 的 CSL 样式）或 NoteExpress / EndNote 统一管理，再导出 BibTeX 或 RIS 给我，我可以批量转换格式。
