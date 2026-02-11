# HSK-LLM: Hierarchical Spatial Knowledge-Guided Large Language Models for Floor Plan Generation

## 🏠 Abstract

To effectively explore automated generation of floor plans in the architecture industry, some remarkable progress in such a novel feasible paradigm for transforming floor plan design into natural language generation tasks, especially large language models have been witnessed during these years. However, existing methods still face significant challenges in this task, primarily manifested in the lack of effective semantic representations and the difficulty in strictly satisfying complex spatial and geometric constraints, resulting in sub-optimal generation quality. 

To address these issues, this paper proposes a **Hierarchical Spatial Knowledge-Guided Large Language Models (HSK-LLM)** for floor plan generation framework. Specifically:
1. **Macro-View:** We propose a **dual-reference spatial encoding mechanism** to explore multi-view semantic from raw data, effectively resolving the ambiguity in spatial semantic descriptions.
2. **Micro-View:** A group of **explicit constraints** (adjacency topology, boundary, and bounding box) is designed to rigorously regulate the spatial topology logic and geometric accuracy, effectively suppressing geometric hallucinations.

Experimental results demonstrate that our model significantly outperforms baselines, while effectively adhering to complex semantic instructions and explicit geometric constraints.

<p align="center">
  <img src="assets/framework.svg" width="800" title="HSK-LLM Framework">
  <br>
  <em>Figure 1: The overall architecture of the proposed HSK-LLM framework.</em>
</p>

## 🛠️ Installation

```bash
git clone [https://github.com/Zja-33/HSK-LLM.git](https://github.com/Zja-33/HSK-LLM.git)
cd HSK-LLM
pip install -r requirements.txt
