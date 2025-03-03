<div align="center">
<h2>    
A Reading List for MIA-for-pretrained-LLM (Updated: 03 March 2025)
</div>

<div align="center">
<b>Yifan Ding</b>
</div>

<!-- <div align="center">
<sup>2</sup>Shanghai University of Finance and Economics, Shanghai, China
</div> -->

<br />

<div align="center">
    <a href="https://arxiv.org/abs/2406.05804"><img src="https://img.shields.io/badge/CoLing-2025-b31b1b" alt="Paper"></a>
    <a href="https://github.com/xinzhel/llm-agent-survey"><img src="https://img.shields.io/github/last-commit/xinzhel/llm-agent-survey?color=blue" alt="Github"></a>
    <a href="https://github.com/xinzhel/llm-agent-survey/blob/main/LICENSE"> <img alt="License" src="https://img.shields.io/github/license/xinzhel/llm-agent-survey?color=green"> </a>
</div>



### This Repository vs. Others
Our Github Repository follows the selection criteria below:
- **Allowing Coherent Understanding**: They can be systematically categoried into the unified framework in my survey
  - My Survey: - [A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning](https://arxiv.org/abs/2406.05804)
    - [30 Nov 2024] Accepted at CoLing 2025. Camera-ready version on [arxiv](https://arxiv.org/abs/2406.05804)
    - [23 Oct 2024] Retitled in version 4 on [arxiv](https://arxiv.org/abs/2406.05804v5)
    - [09 Jun 2024] Initial version titled  "A Survey on LLM-Based Agents: Common Workflows and Reusable LLM-Profiled Components" on [arxiv](https://arxiv.org/abs/2406.05804v2)
  -  I am writing a more comprehensive survey under a more flexible, unified framework. ⭐️ STAR this repo to follow.  
- **High Quality**: Papers are published on ICML, ICLR, NeurIPS, *ACL (including EMNLP), and COLING. Or unpublished papers contain useful analysis and insightful novelty 
  - Unpublished papers are marked with 💡 and will be updated upon publication. ⭐️ STAR this repo to stay updated!  
  - Paper Reviews: The paper links to OpenReview (if available) are alwasy given. I often learn much more from and resonate with many reviews about the papers and evaluate some rejected papers with the reviews. (That's why I always like NeurIPS/ICLR papers).

Other Github Repositories summarize related papers with less constrained selection criteria:
* [AGI-Edgerunners/LLM-Agents-Papers](https://github.com/AGI-Edgerunners/LLM-Agents-Papers?tab=readme-ov-file)

Other Github Repositories summarize related papers focusing on specific perspectives:
* [nuster1128/LLM_Agent_Memory_Survey](https://github.com/nuster1128/LLM_Agent_Memory_Survey): Focus on memory



## Table of Contents
- [🎁 Surveys](#gift-surveys)
- [🚀 Tool Use](#rocket-tool-use)
- [🧠 Planning](#brain-planning)
  - [Base Workflows](#base-workflows)
  - [Search Workflows](#search-workflows)
  - [Decomposition](#decomposition)
  - [PDDL + Local Search](#pddl+local-search)
  - [Others](#others)
- [🔄 Feedback Learning](#arrows_counterclockwise-feedback-learning)
- [🧩 Composition](#jigsaw-composition)
  - [Planning + Feedback Learning](#planning--feedback-learning)
  - [Planning + Tool Use](#planning--tool-use)
- [🌍 World Modeling](#world_map-world-modeling)
  <!-- - [LLM as World Models](#llm-as-world-models)
  - [LLM-Generated World Models](#llm-generated-world-models) -->
- [📊 Benchmarks](#bar_chart-benchmarks)
- [📝 Citation](#memo-citation)


## :gift: Surveys
- **Understanding the planning of LLM agents: A survey**, arXiv [[paper]](https://arxiv.org/abs/2402.02716) 💡
- **The Rise and Potential of Large Language Model Based Agents: A Survey**, arxiv [[paper]](https://arxiv.org/abs/2309.07864) 💡
- **A Survey on the Memory Mechanism of Large Language Model based Agents**, arxiv [[paper]](https://arxiv.org/abs/2404.13501) 💡

### :rocket: Tool Use

### :brain: Planning

#### Base Workflows

#### Search Workflows 
Details in [the page (on the way to be publised)](search.md).
<!-- BFS/DFS -->

#### Decomposition

#### PDDL+Local Search

#### Others

### :arrows_counterclockwise: Feedback Learning


### :jigsaw: Composition
#### Planning + Feedback Learning

#### Planning + Tool Use

### :world_map: World Modeling
<!-- #### LLM as World Models -->

### :bar_chart: Benchmarks
#### Tool-Use Benchmarks

#### Planning Benchmarks


## :memo: Citation

If you find our work helpful, you can cite this paper as:

```bibtex
@inproceedings{li2024review,
  title={A Review of Prominent Paradigms for LLM-Based Agents: Tool Use (Including RAG), Planning, and Feedback Learning},
  author={Li, Xinzhe},
  booktitle = "Proceedings of the 31st International Conference on Computational Linguistics",
  year = "2025",  
}
```
