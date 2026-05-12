---
title: "CadenceRAG: Context-Aware and Dependency-Enhanced Retrieval Augmented Generation for Holistic Video Understanding"
collection: publications
permalink: /publication/2025-CadenceRAG
date: 2025-06-15
venue: 'CVPR 2025 Workshop on IVISE'
paperurl: 'https://openaccess.thecvf.com/content/CVPR2025W/IViSE/papers/Liu_CadenceRAG_Context-Aware_and_Dependency-Enhanced_Retrieval_Augmented_Generation_for_Holistic_Video_CVPRW_2025_paper.pdf'
citation: 'Heng Liu, <b>Siru Jiang</b>, Fangyun Duan, Yongzhe Lyu, Xiusong Wang, Hanlin Ge, Chao Liang. (2025). "CadenceRAG: Context-Aware and Dependency-Enhanced Retrieval Augmented Generation for Holistic Video Understanding." CVPRW 2025.'
# Optional: teaser: /images/cadencerag-framework.png
---

<div style="display: flex; gap: 25px; align-items: flex-start; margin-top: 25px; flex-wrap: wrap;">
  <div style="flex: 0 0 320px; min-width: 300px;">
    <img src="/images/cadence.png" alt="CadenceRAG Framework" style="width: 100%; border-radius: 6px; box-shadow: 0 4px 12px rgba(0,0,0,0.1); border: 1px solid #f0f0f0;">
    <p style="text-align: center; font-size: 0.85em; color: #666; margin-top: 10px;">Figure 1: CadenceRAG Pipeline</p>
  </div>

  <div style="flex: 1; min-width: 300px;">
    <div style="background-color: #fff9db; padding: 10px 15px; border-left: 5px solid #fcc419; margin-bottom: 15px; font-weight: bold; color: #856404;">
      [cite_start]🏆 CVPR 2025 Workshop IVISE QA Track Champion (1st Place) [cite: 21, 22]
    </div>

    <p style="margin-top: 0;">
      This work addresses the challenges of <b>fine-grained alignment</b> between long-text queries and multi-shot videos, as well as <b>sparse target segment retrieval</b>[cite: 22].
    </p>

    <ul style="padding-left: 20px;">
      <li><b>Query Decomposition:</b> Utilizes LLMs to break down complex long queries into temporal sub-queries[cite: 22].</li>
      <li><b>Hierarchical Sliding Window:</b> Employs an efficient algorithm to precisely locate relevant segments within massive video corpora[cite: 22].</li>
      <li><b>Multimodal Fusion:</b> Integrates visual, audio, and textual knowledge to achieve comprehensive video question answering[cite: 22].</li>
    </ul>

    <div style="margin-top: 20px;">
      <a href="https://openaccess.thecvf.com/content/CVPR2025W/IViSE/papers/Liu_CadenceRAG_Context-Aware_and_Dependency-Enhanced_Retrieval_Augmented_Generation_for_Holistic_Video_CVPRW_2025_paper.pdf" target="_blank" style="padding: 6px 16px; border: 1px solid #005088; border-radius: 20px; text-decoration: none; color: #005088; font-weight: 500;">[PDF]</a>
      <a href="#" style="padding: 6px 16px; border: 1px solid #005088; border-radius: 20px; text-decoration: none; color: #005088; font-weight: 500; margin-left: 10px;">[Poster]</a>
    </div>
  </div>
</div>

## Abstract
[cite_start]We propose CadenceRAG, a multimodal Retrieval-Augmented Generation solution for holistic video understanding[cite: 22]. [cite_start]By leveraging hierarchical sliding window algorithms and LLM-based query decomposition, our method effectively bridges the gap between long-text queries and multi-shot video granularity[cite: 22]. [cite_start]The framework achieved a 1st place ranking in the QA task with a score of 7/10[cite: 22].
