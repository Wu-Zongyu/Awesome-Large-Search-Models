# Awesome-Large-Search-Models  
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![GitHub stars](https://img.shields.io/github/stars/Wu-Zongyu/Awesome-Large-Search-Models)
- 📖 **Awesome-Large-Search-Models** contains the latest paper and blogs about **search-oriented large (reasoning) language models** (**large search models**). Example papers include reinforcement learning-based methods. This repo also has other resources like datasets and popular frameworks.
- 🌟 Please consider starring us if our repo is helpful.
- 📮 Feel free to open an issue or pull a request if you think I missed some work.

## Table of Contents
- [Methods](#methods)
  - [Training-based Approaches](#training-based-approaches)
  - [Training-Free Approaches](#training-free-approaches)
- [Datasets](#datasets)
- [Surveys](#surveys)
- [Other Useful Resources](#other-useful-resources)

## 🔥 News
* Jun 9, 2025: We create this repo to include papers and resources on search-oriented large language models!
  
## Methods
### Training-based Approaches
| Time    | Title                                                                                               | Venue | Paper                                                                                                        | Code                                                       |
|---------|-----------------------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| 2025.06 | **CIIR@LiveRAG 2025: Optimizing Multi-Agent Retrieval Augmented Generation through Self-Training**         | arXiv | [Link](https://arxiv.org/abs/2506.10844)                                                                     |  - |
| 2025.06 | **Knowledgeable-r1: Policy Optimization for Knowledge Exploration in Retrieval-Augmented Generation**         | arXiv | [Link](https://arxiv.org/abs/2506.05154)                                                                     |  - |
| 2025.06 | **Coordinating Search-Informed Reasoning and Reasoning-Guided Search in Claim Verification**         | arXiv | [Link](https://arxiv.org/abs/2506.07528)                                                                     |  -  |
| 2025.06 | **R-Search: Empowering LLM Reasoning with Search via Multi-Reward Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2506.04185)                                                                     | [Link](https://github.com/QingFei1/R-Search)               |
| 2025.05 | **WebDancer: Towards Autonomous Information Seeking Agency**         | arXiv | [Link](https://arxiv.org/abs/2505.22648)                                                                     | [link](https://github.com/Alibaba-NLP/WebAgent) |
| 2025.05 | **Pangu DeepDiver: Adaptive Search Intensity Scaling via Open-Web Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2505.24332)                                                                     | -|
| 2025.05 | **R3-RAG: Learning Step-by-Step Reasoning and Retrieval for LLMs via Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2505.23794)                                                                     | [Link](https://github.com/Yuan-Li-FNLP/R3-RAG)|
| 2025.06 | **Learning to Route Queries Across Knowledge Bases for Step-wise Retrieval-Augmented Reasoning**         | arXiv | [Link](https://arxiv.org/abs/2505.22095)                                                                     |  [Link](https://github.com/OpenBMB/R1-Router) |
| 2025.05 | **VRAG-RL: Empower Vision-Perception-Based RAG for Visually Rich Information Understanding via Iterative Reasoning with Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2505.22019)   |        [Link](https://github.com/Alibaba-NLP/VRAG)|
| 2025.05 | **EvolveSearch: An Iterative Self-Evolving Search Agent**         | arXiv | [Link](https://arxiv.org/abs/2505.22501)                                                                     | -|
| 2025.05 | **MaskSearch: A Universal Pre-Training Framework to Enhance Agentic Search Capability**         | arXiv | [Link](https://arxiv.org/abs/2505.20285)                                                                     | [Link](https://github.com/Alibaba-NLP/MaskSearch)     |
| 2025.05 | **LeTS: Learning to Think-and-Search via Process-and-Outcome Reward Hybridization**         | arXiv | [Link](https://arxiv.org/abs/2505.17447)                                                                     | -|
| 2025.05 | **Search Wisely: Mitigating Sub-optimal Agentic Searches By Reducing Uncertainty**         | arXiv | [Link](https://arxiv.org/abs/2505.17281)                                                                     | -|
| 2025.05 | **R1-Searcher++: Incentivizing the Dynamic Knowledge Acquisition of LLMs via Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2505.17005)                                                                     | [Link](https://github.com/RUCAIBox/R1-Searcher-plus)|
| 2025.05 | **SimpleDeepSearcher: Deep Information Seeking via Web-Powered Reasoning Trajectory Synthesis**         | arXiv | [Link](https://arxiv.org/abs/2505.16834)                                                                     | [Link](https://github.com/RUCAIBox/SimpleDeepSearcher)     |
| 2025.05 | **$O^2$-Searcher: A Searching-based Agent Model for Open-Domain Open-Ended Question Answering**         | arXiv | [Link](https://arxiv.org/abs/2505.16582)                                                                     | [Link](https://github.com/KnowledgeXLab/O2-Searcher) | 
| 2025.05 | **An Empirical Study on Reinforcement Learning for Reasoning-Search Interleaved LLM Agents**         | arXiv | [Link](https://arxiv.org/abs/2505.15117)                                                                     | [Link](https://github.com/PeterGriffinJin/Search-R1)   
| 2025.05 | **StepSearch: Igniting LLMs Search Ability via Step-Wise Proximal Policy Optimization**         | arXiv | [Link](https://arxiv.org/abs/2505.15107)                                                                     | [Link](https://github.com/Zillwang/StepSearch)   
| 2025.05 | **Process vs. Outcome Reward: Which is Better for Agentic RAG Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2505.14069)                                                                     | [Link](https://github.com/wlzhang2020/ReasonRAG)
| 2025.05 | **Search and Refine During Think: Autonomous Retrieval-Augmented Reasoning of LLMs**         | arXiv | [Link](https://arxiv.org/abs/2505.11277)                                                                     | [Link](https://github.com/syr-cn/AutoRefine) | 
| 2025.05 | **Scent of Knowledge: Optimizing Search-Enhanced Reasoning with Information Foraging**         | arXiv | [Link](https://arxiv.org/abs/2505.09316)                                                                     | - | 
| 2025.05 | **ZeroSearch: Incentivize the Search Capability of LLMs without Searching**         | arXiv | [Link](https://arxiv.org/abs/2505.04588)                                                                     | [Link](https://github.com/Alibaba-NLP/ZeroSearch)  
| 2025.04 | **WebThinker: Empowering Large Reasoning Models with Deep Research Capability**         | arXiv | [Link](https://arxiv.org/abs/2504.21776)                                                                     | [Link](https://github.com/RUC-NLPIR/WebThinker)  
| 2025.04 | **ReZero: Enhancing LLM search ability by trying one-more-time**         | arXiv | [Link](https://arxiv.org/abs/2504.11001)                                                                     | - |
| 2025.04 | **Multimodal-Search-R1: Incentivizing LMMs to Search**                                                                            | Blog  | [Link](https://kimingng.notion.site/MMSearch-R1-Incentivizing-LMMs-to-Search-1bcce992031880b2bc64fde13ef83e2a) | [Link](https://github.com/EvolvingLMMs-Lab/multimodal-search-r1) |
| 2025.04 | **DeepResearcher: Scaling Deep Research via Reinforcement Learning in Real-world Environments**     | arXiv | [Link](https://arxiv.org/abs/2504.03160)                                                                     | [Link](https://github.com/GAIR-NLP/DeepResearcher)       |
| 2025.03 | **Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning**     | arXiv | [Link](https://arxiv.org/abs/2503.09516)                                                                     | [Link](https://github.com/PeterGriffinJin/Search-R1)       |
| 2025.02 | **DeepRetrieval: Hacking Real Search Engines and Retrievers with Large Language Models via Reinforcement Learning**     | arXiv | [Link]()                                                                     | [Link](https://github.com/pat-jj/DeepRetrieval)       |




### Training-Free Approaches
| Time    | Title                                                                                               | Venue | Paper                                                                                                        | Code                                                       |
|---------|-----------------------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| 2025.05 | **ManuSearch: Democratizing Deep Search in Large Language Models with a Transparent and Open Multi-Agent Framework**      | arXiv | [Link](https://arxiv.org/abs/2505.18105)                  | [Link](https://github.com/RUCAIBox/ManuSearch)    |
| 2025.01 | **Search-o1: Agentic Search-Enhanced Large Reasoning Models**      | arXiv | [Link](https://arxiv.org/abs/2501.05366)                  | [Link](https://github.com/sunnynexus/Search-o1)    |
| 2022.10 | **ReAct: Synergizing Reasoning and Acting in Language Models**      | ICLR'2023 | [Link](https://openreview.net/forum?id=WE_vluYUL-X)                  | [Link](https://github.com/ysymyth/ReAct)    |
| 2022.12 | **Interleaving Retrieval with Chain-of-Thought Reasoning for Knowledge-Intensive Multi-Step Questions**      | ACL'2023 | [Link](https://arxiv.org/abs/2212.10509)                  | [Link](https://github.com/stonybrooknlp/ircot)    |
| 2022.10 | **Decomposed Prompting: A Modular Approach for Solving Complex Tasks**      | ICLR'2023 | [Link](https://openreview.net/forum?id=_nGgzQjzaRy)                  | [Link](https://github.com/allenai/DecomP)    |

## Datasets

| Name    | Type                                                                                               | Link          |
|---------|-----------------------------------------------------------------------------------------------------|-------|
| NQ | One-hop QA      | [Link](https://github.com/google-research-datasets/natural-questions) | 
| TriviaQA | One-hop QA      | [Link](https://nlp.cs.washington.edu/triviaqa/) | 
| PopQA | One-hop QA      | [Link](https://huggingface.co/datasets/akariasai/PopQA) | 
| SQuAD | One-hop QA      | [Link](https://rajpurkar.github.io/SQuAD-explorer/) | 
| CommonSenseQA | One-hop QA      | [Link](https://huggingface.co/datasets/tau/commonsense_qa) | 
| HotpotQA | Multi-hop QA      | [Link](https://hotpotqa.github.io/) | 
| Bamboogle | Multi-hop QA      | [Link](https://huggingface.co/datasets/chiayewken/bamboogle) | 
| 2WikiMultiHopQA | Multi-hop QA      | [Link](https://github.com/Alab-NII/2wikimultihop) | 
| Musique | Multi-hop QA      | [Link](https://github.com/StonyBrookNLP/musique) | 

## Surveys
| Time    | Title                                                                                               | Venue | Paper                                                                                                        | 
|---------|-----------------------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------|
| 2025.06 | **Reasoning RAG via System 1 or System 2: A Survey on Reasoning Agentic Retrieval-Augmented Generation for Industry Challenges**      | arXiv | [Link](https://arxiv.org/abs/2506.10408)                  | 

## Other Useful Resources
- **OpenRLHF**: https://github.com/OpenRLHF/OpenRLHF
- **FlashRAG_datasets**: https://huggingface.co/datasets/RUC-NLPIR/FlashRAG_datasets
- **verl**: https://github.com/volcengine/verl
- **LLaMA-Factory**: https://github.com/hiyouga/LLaMA-Factory
- **EasyRL**: https://github.com/alibaba/EasyReinforcementLearning

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Wu-Zongyu/Awesome-Large-Search-Models&type=Date)](https://www.star-history.com/#Wu-Zongyu/Awesome-Large-Search-Models&Date)

