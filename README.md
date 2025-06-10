# Awesome-Large-Search-Models

- 📖 This repo contains papers (blogs) and resources that design search-oriented large language models (large reasoning models). Example papers include reinforcement learning-based methods. Feel free to open an issue if you think I missed some work!  
- 🌟 Please consider starring us if our repo is helpful!

## Table of Contents

- [Methods](#methods)
  - [Training-based Approaches](#training-based-approaches)
  - [Training-Free Approaches](#training-free-approaches)
- [Datasets](#datasets)
- [Other Useful Resources](#other-useful-resources)
## Methods
### Training-based Approaches
| Time    | Title                                                                                               | Venue | Paper                                                                                                        | Code                                                       |
|---------|-----------------------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| 2025.06 | **R-Search: Empowering LLM Reasoning with Search via Multi-Reward Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2506.04185)                                                                     | [Link](https://github.com/QingFei1/R-Search)               |
| 2025.05 | **Pangu DeepDiver: Adaptive Search Intensity Scaling via Open-Web Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2505.24332)                                                                     | -|
| 2025.05 | **VRAG-RL: Empower Vision-Perception-Based RAG for Visually Rich Information Understanding via Iterative Reasoning with Reinforcement Learning**         | arXiv | [Link]([https://arxiv.org/abs/2505.24332](https://arxiv.org/abs/2505.22019))                                                                     | [Link](https://github.com/Alibaba-NLP/VRAG)|
| 2025.05 | **EvolveSearch: An Iterative Self-Evolving Search Agent**         | arXiv | [Link](https://arxiv.org/abs/2505.22501)                                                                     | -|
| 2025.05 | **MaskSearch: A Universal Pre-Training Framework to Enhance Agentic Search Capability**         | arXiv | [Link](https://arxiv.org/abs/2505.20285)                                                                     | [Link](https://github.com/Alibaba-NLP/MaskSearch)     |
| 2025.05 | **LeTS: Learning to Think-and-Search via Process-and-Outcome Reward Hybridization**         | arXiv | [Link](https://arxiv.org/abs/2505.17447)                                                                     | -|
| 2025.05 | **Search Wisely: Mitigating Sub-optimal Agentic Searches By Reducing Uncertainty**         | arXiv | [Link](https://arxiv.org/abs/2505.17281)                                                                     | -|
| 2025.05 | **R1-Searcher++: Incentivizing the Dynamic Knowledge Acquisition of LLMs via Reinforcement Learning**         | arXiv | [Link](https://arxiv.org/abs/2505.17005)                                                                     | [Link](https://github.com/RUCAIBox/R1-Searcher-plus)|
| 2025.05 | **$O^2$-Searcher: A Searching-based Agent Model for Open-Domain Open-Ended Question Answering**         | arXiv | [Link](https://arxiv.org/abs/2505.16582)                                                                     | [Link](https://github.com/KnowledgeXLab/O2-Searcher) | 
| 2025.05 | **An Empirical Study on Reinforcement Learning for Reasoning-Search Interleaved LLM Agents**         | arXiv | [Link](https://arxiv.org/abs/2505.15117)                                                                     | [Link](https://github.com/PeterGriffinJin/Search-R1)   
| 2025.05 | **StepSearch: Igniting LLMs Search Ability via Step-Wise Proximal Policy Optimization**         | arXiv | [Link](https://arxiv.org/abs/2505.15107)                                                                     | [Link](https://github.com/Zillwang/StepSearch)   
| 2025.05 | **Search and Refine During Think: Autonomous Retrieval-Augmented Reasoning of LLMs**         | arXiv | [Link](https://arxiv.org/abs/2505.11277)                                                                     | [Link](https://github.com/syr-cn/AutoRefine) | 
| 2025.05 | **Scent of Knowledge: Optimizing Search-Enhanced Reasoning with Information Foraging**         | arXiv | [Link](https://arxiv.org/abs/2505.09316)                                                                     | - | 
| 2025.05 | **ZeroSearch: Incentivize the Search Capability of LLMs without Searching**         | arXiv | [Link](https://arxiv.org/abs/2505.04588)                                                                     | [Link](https://github.com/Alibaba-NLP/ZeroSearch)  
| 2025.04 | **Multimodal-Search-R1: Incentivizing LMMs to Search**                                                                            | Blog  | [Link](https://kimingng.notion.site/MMSearch-R1-Incentivizing-LMMs-to-Search-1bcce992031880b2bc64fde13ef83e2a) | [Link](https://github.com/EvolvingLMMs-Lab/multimodal-search-r1) |
| 2025.03 | **Search-R1: Training LLMs to Reason and Leverage Search Engines with Reinforcement Learning**     | arXiv | [Link](https://arxiv.org/abs/2503.09516)                                                                     | [Link](https://github.com/PeterGriffinJin/Search-R1)       |


### Training-Free Approaches
| Time    | Title                                                                                               | Venue | Paper                                                                                                        | Code                                                       |
|---------|-----------------------------------------------------------------------------------------------------|-------|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| 2025.01 | **Search-o1: Agentic Search-Enhanced Large Reasoning Models**      | arXiv | [Link](https://arxiv.org/abs/2501.05366)                  | [Link](https://github.com/sunnynexus/Search-o1)    |
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

## Other Useful Resources
- **OpenRLHF**: https://github.com/OpenRLHF/OpenRLHF
- **FlashRAG_datasets**: https://huggingface.co/datasets/RUC-NLPIR/FlashRAG_datasets
- **verl**: https://github.com/volcengine/verl
- **LLaMA-Factory**: https://github.com/hiyouga/LLaMA-Factory
- **EasyRL**: https://github.com/alibaba/EasyReinforcementLearning

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Wu-Zongyu/Awesome-Large-Search-Models&type=Date)](https://www.star-history.com/#Wu-Zongyu/Awesome-Large-Search-Models&Date)

