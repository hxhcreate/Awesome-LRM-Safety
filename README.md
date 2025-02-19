# Awesome Large Reasoning Model (LRM) Safety 🔥

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Auto Update](https://github.com/wonderNefelibata/Awesome-LRM-Safety/actions/workflows/arxiv-update.yml/badge.svg)

A curated list of **security and safety research** for Large Reasoning Models (LRMs) like DeepSeek-R1, OpenAI o1, and other cutting-edge models. Focused on identifying risks, mitigation strategies, and ethical implications.

---

## 📜 Table of Contents
- [Awesome Large Reasoning Model (LRM) Safety 🔥](#awesome-large-reasoning-model-lrm-safety-)
  - [📜 Table of Contents](#-table-of-contents)
  - [🚀 Motivation](#-motivation)
  - [📰 Latest arXiv Papers (Auto-Updated)](#-latest-arxiv-papers-auto-updated)
  - [🔑 Key Safety Domains(coming soon)](#-key-safety-domainscoming-soon)
  - [📚 Research Papers(coming soon)](#-research-paperscoming-soon)
    - [Foundational Works](#foundational-works)
    - [Attack Vectors](#attack-vectors)
    - [Defense Mechanisms](#defense-mechanisms)
  - [🛠️ Projects \& Tools(coming soon)](#️-projects--toolscoming-soon)
    - [Model-Specific Resources](#model-specific-resources)
    - [General Tools(coming soon)](#general-toolscoming-soon)
  - [🤝 Contributing](#-contributing)
  - [📄 License](#-license)
  - [❓ FAQ](#-faq)

---

## 🚀 Motivation
Large Reasoning Models (LRMs) are revolutionizing AI capabilities in complex decision-making scenarios. However, their deployment raises critical safety concerns:
- **Adversarial attacks** on reasoning pipelines
- **Privacy leakage** through multi-step reasoning
- **Ethical risks** in high-stakes domains (e.g., healthcare, finance)
- **Systemic failures** in autonomous systems
This repository aims to catalog research addressing these challenges and promote safer LRM development.

---

## 📰 Latest arXiv Papers (Auto-Updated)
<!-- LATEST_PAPERS_START -->


| Date       | Title                                      | Authors           | Abstract Summary          |
|------------|--------------------------------------------|-------------------|---------------------------|
| 2025-02-17 | [Can LLMs Simulate Social Media Engagement? A Study on Action-Guided Response Generation](http://arxiv.org/abs/2502.12073v1) | Zhongyi Qiu, Hanjia Lyu et al. | Social media enables dynamic user engagement with trending topics, and recent research has explored the potential of large language models (LLMs) for ... |
| 2025-02-17 | [TokenSkip: Controllable Chain-of-Thought Compression in LLMs](http://arxiv.org/abs/2502.12067v1) | Heming Xia, Yongqi Li et al. | Chain-of-Thought (CoT) has been proven effective in enhancing the reasoning capabilities of large language models (LLMs). Recent advancements, such as... |
| 2025-02-17 | [PhysReason: A Comprehensive Benchmark towards Physics-Based Reasoning](http://arxiv.org/abs/2502.12054v1) | Xinyu Zhang, Yuxuan Dong et al. | Large language models demonstrate remarkable capabilities across various domains, especially mathematics and logic reasoning. However, current evaluat... |
| 2025-02-17 | [SafeChain: Safety of Language Models with Long Chain-of-Thought Reasoning Capabilities](http://arxiv.org/abs/2502.12025v1) | Fengqing Jiang, Zhangchen Xu et al. | Emerging large reasoning models (LRMs), such as DeepSeek-R1 models, leverage long chain-of-thought (CoT) reasoning to generate structured intermediate... |
| 2025-02-17 | [Atom of Thoughts for Markov LLM Test-Time Scaling](http://arxiv.org/abs/2502.12018v1) | Fengwei Teng, Zhaoyang Yu et al. | Large Language Models (LLMs) achieve superior performance through training-time scaling, and test-time scaling further enhances their capabilities by ... |
| 2025-02-17 | [LIMR: Less is More for RL Scaling](http://arxiv.org/abs/2502.11886v1) | Xuefeng Li, Haoyang Zou et al. | In this paper, we ask: what truly determines the effectiveness of RL training data for enhancing language models' reasoning capabilities? While recent... |
| 2025-02-17 | [Hypothesis-Driven Theory-of-Mind Reasoning for Large Language Models](http://arxiv.org/abs/2502.11881v1) | Hyunwoo Kim, Melanie Sclar et al. | Existing LLM reasoning methods have shown impressive capabilities across various tasks, such as solving math and coding problems. However, applying th... |
| 2025-02-17 | [StructTransform: A Scalable Attack Surface for Safety-Aligned Large Language Models](http://arxiv.org/abs/2502.11853v1) | Shehel Yoosuf, Temoor Ali et al. | In this work, we present a series of structure transformation attacks on LLM alignment, where we encode natural language intent using diverse syntax s... |
| 2025-02-17 | [BaxBench: Can LLMs Generate Correct and Secure Backends?](http://arxiv.org/abs/2502.11844v1) | Mark Vero, Niels Mündler et al. | The automatic generation of programs has long been a fundamental challenge in computer science. Recent benchmarks have shown that large language model... |
| 2025-02-17 | [video-SALMONN-o1: Reasoning-enhanced Audio-visual Large Language Model](http://arxiv.org/abs/2502.11775v1) | Guangzhi Sun, Yudong Yang et al. | While recent advancements in reasoning optimization have significantly enhanced the capabilities of large language models (LLMs), existing efforts to ... |
| 2025-02-17 | [SQL-o1: A Self-Reward Heuristic Dynamic Search Method for Text-to-SQL](http://arxiv.org/abs/2502.11741v1) | Shuai Lyu, Haoran Luo et al. | The Text-to-SQL(Text2SQL) task aims to convert natural language queries into executable SQL queries. Thanks to the application of large language model... |
| 2025-02-17 | [Connecting Earth and Moon via the L1 Lagrangian point](http://arxiv.org/abs/2502.11694v1) | A. K. de Almeida Jr, V. M. de Oliveira et al. | The renewed global interest in lunar exploration requires new orbital strategies to ensure flight safety which can benefit extended lunar missions and... |
| 2025-02-17 | [RIDE: Enhancing Large Language Model Alignment through Restyled In-Context Learning Demonstration Exemplars](http://arxiv.org/abs/2502.11681v1) | Yuncheng Hua, Lizhen Qu et al. | Alignment tuning is crucial for ensuring large language models (LLMs) behave ethically and helpfully. Current alignment approaches require high-qualit... |
| 2025-02-17 | [DELMAN: Dynamic Defense Against Large Language Model Jailbreaking with Model Editing](http://arxiv.org/abs/2502.11647v1) | Yi Wang, Fenghua Weng et al. | Large Language Models (LLMs) are widely applied in decision making, but their deployment is threatened by jailbreak attacks, where adversarial users m... |
| 2025-02-17 | [Enhancing Out-of-Distribution Detection in Medical Imaging with Normalizing Flows](http://arxiv.org/abs/2502.11638v1) | Dariush Lotfi, Mohammad-Ali Nikouei Mahani et al. | Out-of-distribution (OOD) detection is crucial in AI-driven medical imaging to ensure reliability and safety by identifying inputs outside a model's t... |
| 2025-02-17 | [GraphThought: Graph Combinatorial Optimization with Thought Generation](http://arxiv.org/abs/2502.11607v1) | Zixiao Huang, Lifeng Guo et al. | Large language models (LLMs) have demonstrated remarkable capabilities across various domains, especially in text processing and generative tasks. Rec... |
| 2025-02-17 | [Runtime Enforcement of CPS against Signal Temporal Logic](http://arxiv.org/abs/2502.11584v1) | Han Su, Saumya Shankar et al. | Cyber-Physical Systems (CPSs), especially those involving autonomy, need guarantees of their safety. Runtime Enforcement (RE) is a lightweight method ... |
| 2025-02-17 | [Language Complexity Measurement as a Noisy Zero-Shot Proxy for Evaluating LLM Performance](http://arxiv.org/abs/2502.11578v1) | Birger Moell, Johan Boye | Large Language Models (LLMs) have made significant strides in natural language generation but often face challenges in tasks requiring precise calcula... |
| 2025-02-17 | [Large Language Models and Mathematical Reasoning Failures](http://arxiv.org/abs/2502.11574v1) | Johan Boye, Birger Moell | This paper investigates the mathematical reasoning capabilities of large language models (LLMs) using 50 newly constructed high-school-level word prob... |
| 2025-02-17 | [Equilibrate RLHF: Towards Balancing Helpfulness-Safety Trade-off in Large Language Models](http://arxiv.org/abs/2502.11555v1) | Yingshui Tan, Yilei Jiang et al. | Fine-tuning large language models (LLMs) based on human preferences, commonly achieved through reinforcement learning from human feedback (RLHF), has ... |

<!-- LATEST_PAPERS_END -->
<!-- HISTORICAL_PAPERS_START -->

<details>
<summary>📚 View Historical Papers (83 entries)</summary>



| Date       | Title                                      | Authors           | Abstract Summary          |
|------------|--------------------------------------------|-------------------|---------------------------|
| 2025-02-17 | [Evaluating o1-Like LLMs: Unlocking Reasoning for Translation through Comprehensive Analysis](http://arxiv.org/abs/2502.11544v1) | Andong Chen, Yuchen Song et al. | The o1-Like LLMs are transforming AI by simulating human cognitive processes, but their performance in multilingual machine translation (MMT) remains ... |
| 2025-02-17 | [AURORA:Automated Training Framework of Universal Process Reward Models via Ensemble Prompting and Reverse Verification](http://arxiv.org/abs/2502.11520v1) | Xiaoyu Tan, Tianchu Yao et al. | The reasoning capabilities of advanced large language models (LLMs) like o1 have revolutionized artificial intelligence applications. Nevertheless, ev... |
| 2025-02-17 | [Adversary-Aware DPO: Enhancing Safety Alignment in Vision Language Models via Adversarial Training](http://arxiv.org/abs/2502.11455v1) | Fenghua Weng, Jian Lou et al. | Safety alignment is critical in pre-training large language models (LLMs) to generate responses aligned with human values and refuse harmful queries. ... |
| 2025-02-17 | [AGrail: A Lifelong Agent Guardrail with Effective and Adaptive Safety Detection](http://arxiv.org/abs/2502.11448v1) | Weidi Luo, Shenghong Dai et al. | The rapid advancements in Large Language Models (LLMs) have enabled their deployment as autonomous agents for handling complex tasks in dynamic enviro... |
| 2025-02-17 | [AGrail: A Lifelong Agent Guardrail with Effective and Adaptive Safety Detection](http://arxiv.org/abs/2502.11448v2) | Weidi Luo, Shenghong Dai et al. | The rapid advancements in Large Language Models (LLMs) have enabled their deployment as autonomous agents for handling complex tasks in dynamic enviro... |
| 2025-02-17 | [What's in a Query: Polarity-Aware Distribution-Based Fair Ranking](http://arxiv.org/abs/2502.11429v1) | Aparna Balagopalan, Kai Wang et al. | Machine learning-driven rankings, where individuals (or items) are ranked in response to a query, mediate search exposure or attention in a variety of... |
| 2025-02-17 | [Detecting and Filtering Unsafe Training Data via Data Attribution](http://arxiv.org/abs/2502.11411v1) | Yijun Pan, Taiwei Shi et al. | Large language models (LLMs) are vulnerable to unsafe training data that even small amounts of unsafe data can lead to harmful model behaviors. Detect... |
| 2025-02-17 | [CCJA: Context-Coherent Jailbreak Attack for Aligned Large Language Models](http://arxiv.org/abs/2502.11379v1) | Guanghao Zhou, Panjia Qiu et al. | Despite explicit alignment efforts for large language models (LLMs), they can still be exploited to trigger unintended behaviors, a phenomenon known a... |
| 2025-02-17 | [HI-GVF: Shared Control based on Human-Influenced Guiding Vector Fields for Human-multi-robot Cooperation](http://arxiv.org/abs/2502.11370v1) | Pengming Zhu, Zongtan Zhou et al. | Human-multi-robot shared control leverages human decision-making and robotic autonomy to enhance human-robot collaboration. While widely studied, exis... |
| 2025-02-17 | [Sparse Autoencoder Features for Classifications and Transferability](http://arxiv.org/abs/2502.11367v1) | Jack Gallifant, Shan Chen et al. | Sparse Autoencoders (SAEs) provide potentials for uncovering structured, human-interpretable representations in Large Language Models (LLMs), making t... |
| 2025-02-17 | [VLDBench: Vision Language Models Disinformation Detection Benchmark](http://arxiv.org/abs/2502.11361v1) | Shaina Raza, Ashmal Vayani et al. | The rapid rise of AI-generated content has made detecting disinformation increasingly challenging. In particular, multimodal disinformation, i.e., onl... |
| 2025-02-17 | [A Framework for Learning Scoring Rules in Autonomous Driving Planning Systems](http://arxiv.org/abs/2502.11352v1) | Zikang Xiong, Joe Kurian Eappen et al. | In autonomous driving systems, motion planning is commonly implemented as a two-stage process: first, a trajectory proposer generates multiple candida... |
| 2025-02-16 | [Leveraging Multimodal-LLMs Assisted by Instance Segmentation for Intelligent Traffic Monitoring](http://arxiv.org/abs/2502.11304v1) | Murat Arda Onsu, Poonam Lohan et al. | A robust and efficient traffic monitoring system is essential for smart cities and Intelligent Transportation Systems (ITS), using sensors and cameras... |
| 2025-02-16 | [MC-BEVRO: Multi-Camera Bird Eye View Road Occupancy Detection for Traffic Monitoring](http://arxiv.org/abs/2502.11287v1) | Arpitsinh Vaghela, Duo Lu et al. | Single camera 3D perception for traffic monitoring faces significant challenges due to occlusion and limited field of view. Moreover, fusing informati... |
| 2025-02-16 | [Soteria: Language-Specific Functional Parameter Steering for Multilingual Safety Alignment](http://arxiv.org/abs/2502.11244v1) | Somnath Banerjee, Sayan Layek et al. | Ensuring consistent safety across multiple languages remains a significant challenge for large language models (LLMs). We introduce Soteria, a lightwe... |
| 2025-02-16 | [LLMs and Childhood Safety: Identifying Risks and Proposing a Protection Framework for Safe Child-LLM Interaction](http://arxiv.org/abs/2502.11242v1) | Junfeng Jiao, Saleh Afroogh et al. | This study examines the growing use of Large Language Models (LLMs) in child-centered applications, highlighting safety and ethical concerns such as b... |
| 2025-02-16 | [Can't See the Forest for the Trees: Benchmarking Multimodal Safety Awareness for Multimodal LLMs](http://arxiv.org/abs/2502.11184v1) | Wenxuan Wang, Xiaoyuan Liu et al. | Multimodal Large Language Models (MLLMs) have expanded the capabilities of traditional language models by enabling interaction through both text and i... |
| 2025-02-16 | [Quantifying the Capability Boundary of DeepSeek Models: An Application-Driven Performance Analysis](http://arxiv.org/abs/2502.11164v1) | Shiguo Lian, Kaikai Zhao et al. | DeepSeek-R1, known for its low training cost and exceptional reasoning capabilities, has achieved state-of-the-art performance on various benchmarks. ... |
| 2025-02-16 | [Safety Evaluation of DeepSeek Models in Chinese Contexts](http://arxiv.org/abs/2502.11137v1) | Wenjing Zhang, Xuejiao Lei et al. | Recently, the DeepSeek series of models, leveraging their exceptional reasoning capabilities and open-source strategy, is reshaping the global AI land... |
| 2025-02-16 | [Ramp Up NTT in Record Time using GPU-Accelerated Algorithms and LLM-based Code Generation](http://arxiv.org/abs/2502.11110v1) | Yu Cui, Hang Fu et al. | Homomorphic encryption (HE) is a core building block in privacy-preserving machine learning (PPML), but HE is also widely known as its efficiency bott... |
| 2025-02-16 | [Knowledge Graph-Driven Retrieval-Augmented Generation: Integrating Deepseek-R1 with Weaviate for Advanced Chatbot Applications](http://arxiv.org/abs/2502.11108v1) | Alexandru Lecu, Adrian Groza et al. | Large language models (LLMs) have significantly advanced the field of natural language generation. However, they frequently generate unverified output... |
| 2025-02-16 | [Talk Structurally, Act Hierarchically: A Collaborative Framework for LLM Multi-Agent Systems](http://arxiv.org/abs/2502.11098v1) | Zhao Wang, Sota Moriyama et al. | Recent advancements in LLM-based multi-agent (LLM-MA) systems have shown promise, yet significant challenges remain in managing communication and refi... |
| 2025-02-16 | [Mixture of Tunable Experts - Behavior Modification of DeepSeek-R1 at Inference Time](http://arxiv.org/abs/2502.11096v1) | Robert Dahlke, Henrik Klagges et al. | We present the Mixture-of-Tunable-Experts (MoTE), a method that extends the Mixture-of-Experts architecture of Large Language Models (LLMs). Without a... |
| 2025-02-16 | [SafeDialBench: A Fine-Grained Safety Benchmark for Large Language Models in Multi-Turn Dialogues with Diverse Jailbreak Attacks](http://arxiv.org/abs/2502.11090v1) | Hongye Cao, Yanming Wang et al. | With the rapid advancement of Large Language Models (LLMs), the safety of LLMs has been a critical concern requiring precise assessment. Current bench... |
| 2025-02-16 | [SafeDialBench: A Fine-Grained Safety Benchmark for Large Language Models in Multi-Turn Dialogues with Diverse Jailbreak Attacks](http://arxiv.org/abs/2502.11090v2) | Hongye Cao, Yanming Wang et al. | With the rapid advancement of Large Language Models (LLMs), the safety of LLMs has been a critical concern requiring precise assessment. Current bench... |
| 2025-02-16 | [Rewrite to Jailbreak: Discover Learnable and Transferable Implicit Harmfulness Instruction](http://arxiv.org/abs/2502.11084v1) | Yuting Huang, Chengyuan Liu et al. | As Large Language Models (LLMs) are widely applied in various domains, the safety of LLMs is increasingly attracting attention to avoid their powerful... |
| 2025-02-16 | [ClimateLLM: Efficient Weather Forecasting via Frequency-Aware Large Language Models](http://arxiv.org/abs/2502.11059v1) | Shixuan Li, Wei Yang et al. | Weather forecasting is crucial for public safety, disaster prevention and mitigation, agricultural production, and energy management, with global rele... |
| 2025-02-16 | [A Physics-Informed Machine Learning Framework for Safe and Optimal Control of Autonomous Systems](http://arxiv.org/abs/2502.11057v1) | Manan Tayal, Aditya Singh et al. | As autonomous systems become more ubiquitous in daily life, ensuring high performance with guaranteed safety is crucial. However, safety and performan... |
| 2025-02-16 | [Reasoning-Augmented Conversation for Multi-Turn Jailbreak Attacks on Large Language Models](http://arxiv.org/abs/2502.11054v1) | Zonghao Ying, Deyue Zhang et al. | Multi-turn jailbreak attacks simulate real-world human interactions by engaging large language models (LLMs) in iterative dialogues, exposing critical... |
| 2025-02-16 | [Reasoning-Augmented Conversation for Multi-Turn Jailbreak Attacks on Large Language Models](http://arxiv.org/abs/2502.11054v2) | Zonghao Ying, Deyue Zhang et al. | Multi-turn jailbreak attacks simulate real-world human interactions by engaging large language models (LLMs) in iterative dialogues, exposing critical... |
| 2025-02-16 | [Prompt Inject Detection with Generative Explanation as an Investigative Tool](http://arxiv.org/abs/2502.11006v1) | Jonathan Pan, Swee Liang Wong et al. | Large Language Models (LLMs) are vulnerable to adversarial prompt based injects. These injects could jailbreak or exploit vulnerabilities within these... |
| 2025-02-16 | [Fine-Tuning Hard-to-Simulate Objectives for Quadruped Locomotion: A Case Study on Total Power Saving](http://arxiv.org/abs/2502.10956v1) | Ruiqian Nai, Jiacheng You et al. | Legged locomotion is not just about mobility; it also encompasses crucial objectives such as energy efficiency, safety, and user experience, which are... |
| 2025-02-15 | [Fundamental Principles of Linguistic Structure are Not Represented by o3](http://arxiv.org/abs/2502.10934v1) | Elliot Murphy, Evelina Leivada et al. | A core component of a successful artificial general intelligence would be the rapid creation and manipulation of grounded compositional abstractions a... |
| 2025-02-15 | [Semantic Specialization in MoE Appears with Scale: A Study of DeepSeek R1 Expert Specialization](http://arxiv.org/abs/2502.10928v1) | Matthew Lyle Olson, Neale Ratzlaff et al. | DeepSeek-R1, the largest open-source Mixture-of-Experts (MoE) model, has demonstrated reasoning capabilities comparable to proprietary frontier models... |
| 2025-02-15 | [A Tutorial on LLM Reasoning: Relevant Methods behind ChatGPT o1](http://arxiv.org/abs/2502.10867v1) | Jun Wang | OpenAI o1 has shown that applying reinforcement learning to integrate reasoning steps directly during inference can significantly improve a model's re... |
| 2025-02-15 | [LintLLM: An Open-Source Verilog Linting Framework Based on Large Language Models](http://arxiv.org/abs/2502.10815v1) | Zhigang Fang, Renzhi Chen et al. | Code Linting tools are vital for detecting potential defects in Verilog code. However, the limitations of traditional Linting tools are evident in fre... |
| 2025-02-15 | [Distraction is All You Need for Multimodal Large Language Model Jailbreaking](http://arxiv.org/abs/2502.10794v1) | Zuopeng Yang, Jiluan Fan et al. | Multimodal Large Language Models (MLLMs) bridge the gap between visual and textual data, enabling a range of advanced applications. However, complex i... |
| 2025-02-15 | [New Stress-dependent Elastic Wave Velocity Models for Reservoir Rocks with Applications](http://arxiv.org/abs/2502.10766v1) | Rong Zhao, Chunguang Li | This study presents new elastic velocity-effective stress laws for reservoir rocks. These models are grounded in previously established correlations b... |
| 2025-02-15 | [PropNet: a White-Box and Human-Like Network for Sentence Representation](http://arxiv.org/abs/2502.10725v1) | Fei Yang | Transformer-based embedding methods have dominated the field of sentence representation in recent years. Although they have achieved remarkable perfor... |
| 2025-02-15 | [Non-Negotiated Implicit ETSI VAM Clustering](http://arxiv.org/abs/2502.10617v1) | Felipe Valle, Daniel Bleckert et al. | Including Vulnerable Road User (VRU) in Cooperative Intelligent Transport Systems (C-ITS) framework aims to increase road safety. However, this approa... |
| 2025-02-14 | [Reachability-Aware Reinforcement Learning for Collision Avoidance in Human-Machine Shared Control](http://arxiv.org/abs/2502.10610v1) | Shiyue Zhao, Junzhi Zhang et al. | Human-machine shared control in critical collision scenarios aims to aid drivers' accident avoidance through intervening only when necessary. Existing... |
| 2025-02-14 | [Adaptive Neural Networks for Intelligent Data-Driven Development](http://arxiv.org/abs/2502.10603v1) | Youssef Shoeb, Azarm Nowzad et al. | Advances in machine learning methods for computer vision tasks have led to their consideration for safety-critical applications like autonomous drivin... |
| 2025-02-14 | [MM-RLHF: The Next Step Forward in Multimodal LLM Alignment](http://arxiv.org/abs/2502.10391v1) | Yi-Fan Zhang, Tao Yu et al. | Despite notable advancements in Multimodal Large Language Models (MLLMs), most state-of-the-art models have not undergone thorough alignment with huma... |
| 2025-02-14 | [Open-Source AI-Powered Optimization in Scalene: Advancing Python Performance Profiling with DeepSeek-R1 and LLaMA 3.2](http://arxiv.org/abs/2502.10299v1) | Saem Hasan, Sanju Basak | Python's flexibility and ease of use come at the cost of performance inefficiencies, requiring developers to rely on profilers to optimize execution. ... |
| 2025-02-14 | [Safety Blind Spot in Remote Driving: Considerations for Risk Assessment of Connection Loss Fallback Strategies](http://arxiv.org/abs/2502.10243v1) | Leon Johann Brettin, Niklas Braun et al. | As part of the overall goal of driverless road vehicles, remote driving is a major emerging field of research of its own. Current remote driving conce... |
| 2025-02-14 | [Safe platooning control of connected and autonomous vehicles on curved multi-lane roads](http://arxiv.org/abs/2502.10180v1) | Xiao Chen, Zhiqi Tang et al. | This paper investigates the safe platoon formation tracking and merging control problem of connected and automated vehicles (CAVs) on curved multi-lan... |
| 2025-02-14 | [Small Models, Big Impact: Efficient Corpus and Graph-Based Adaptation of Small Multilingual Language Models for Low-Resource Languages](http://arxiv.org/abs/2502.10140v1) | Daniil Gurgurov, Ivan Vykopal et al. | Low-resource languages (LRLs) face significant challenges in natural language processing (NLP) due to limited data. While current state-of-the-art lar... |
| 2025-02-14 | [Provably Efficient RL under Episode-Wise Safety in Linear CMDPs](http://arxiv.org/abs/2502.10138v1) | Toshinori Kitamura, Arnob Ghosh et al. | We study the reinforcement learning (RL) problem in a constrained Markov decision process (CMDP), where an agent explores the environment to maximize ... |
| 2025-02-14 | [Leveraging V2X for Collaborative HD Maps Construction Using Scene Graph Generation](http://arxiv.org/abs/2502.10127v1) | Gamal Elghazaly, Raphael Frank | High-Definition (HD) maps play a crucial role in autonomous vehicle navigation, complementing onboard perception sensors for improved accuracy and saf... |
| 2025-02-14 | [VLM-Guard: Safeguarding Vision-Language Models via Fulfilling Safety Alignment Gap](http://arxiv.org/abs/2502.10486v1) | Qin Liu, Fei Wang et al. | The emergence of vision language models (VLMs) comes with increased safety concerns, as the incorporation of multiple modalities heightens vulnerabili... |
| 2025-02-14 | [X-Boundary: Establishing Exact Safety Boundary to Shield LLMs from Multi-Turn Jailbreaks without Compromising Usability](http://arxiv.org/abs/2502.09990v1) | Xiaoya Lu, Dongrui Liu et al. | Despite the rapid development of safety alignment techniques for LLMs, defending against multi-turn jailbreaks is still a challenging task. In this pa... |
| 2025-02-14 | [V2V-LLM: Vehicle-to-Vehicle Cooperative Autonomous Driving with Multi-Modal Large Language Models](http://arxiv.org/abs/2502.09980v1) | Hsu-kuang Chiu, Ryo Hachiuma et al. | Current autonomous driving vehicles rely mainly on their individual sensors to understand surrounding scenes and plan for future trajectories, which c... |
| 2025-02-14 | [RoadFed: A Multimodal Federated Learning System for Improving Road Safety](http://arxiv.org/abs/2502.09978v1) | Yachao Yuan, Yali Yuan et al. | Internet of Things (IoTs) have been widely applied in Collaborative Intelligent Transportation Systems (C-ITS) for the prevention of road accidents. A... |
| 2025-02-14 | [Diverse Inference and Verification for Advanced Reasoning](http://arxiv.org/abs/2502.09955v1) | Iddo Drori, Gaston Longhitano et al. | Reasoning LLMs such as OpenAI o1, o3 and DeepSeek R1 have made significant progress in mathematics and coding, yet find challenging advanced tasks suc... |
| 2025-02-14 | [A Preliminary Exploration with GPT-4o Voice Mode](http://arxiv.org/abs/2502.09940v1) | Yu-Xiang Lin, Chih-Kai Yang et al. | With the rise of multimodal large language models, GPT-4o stands out as a pioneering model, driving us to evaluate its capabilities. This report asses... |
| 2025-02-14 | [Granite Vision: a lightweight, open-source multimodal model for enterprise Intelligence](http://arxiv.org/abs/2502.09927v1) | Granite Vision Team, Leonid Karlinsky et al. | We introduce Granite Vision, a lightweight large language model with vision capabilities, specifically designed to excel in enterprise use cases, part... |
| 2025-02-14 | [AutoS$^2$earch: Unlocking the Reasoning Potential of Large Models for Web-based Source Search](http://arxiv.org/abs/2502.09913v1) | Zhengqiu Zhu, Yatai Ji et al. | Web-based management systems have been widely used in risk control and industrial safety. However, effectively integrating source search capabilities ... |
| 2025-02-14 | [Stretching Rubber, Not Budgets: Accurate Parking Utilization on a Shoestring](http://arxiv.org/abs/2502.09877v1) | Christopher K. Allsup | Effective parking management is essential for ensuring accessibility, safety, and convenience in master-planned communities, particularly in active ad... |
| 2025-02-14 | [Learning to Calibrate for Reliable Visual Fire Detection](http://arxiv.org/abs/2502.09872v1) | Ziqi Zhang, Xiuzhuang Zhou et al. | Fire is characterized by its sudden onset and destructive power, making early fire detection crucial for ensuring human safety and protecting property... |
| 2025-02-13 | [Suture Thread Modeling Using Control Barrier Functions for Autonomous Surgery](http://arxiv.org/abs/2502.09813v1) | Kimia Forghani, Suraj Raval et al. | Automating surgical systems enhances precision and safety while reducing human involvement in high-risk environments. A major challenge in automating ... |
| 2025-02-13 | [AgentGuard: Repurposing Agentic Orchestrator for Safety Evaluation of Tool Orchestration](http://arxiv.org/abs/2502.09809v1) | Jizhou Chen, Samuel Lee Cong | The integration of tool use into large language models (LLMs) enables agentic systems with real-world impact. In the meantime, unlike standalone LLMs,... |
| 2025-02-13 | [Enhancing Jailbreak Attacks via Compliance-Refusal-Based Initialization](http://arxiv.org/abs/2502.09755v1) | Amit Levi, Rom Himelstein et al. | Jailbreak attacks aim to exploit large language models (LLMs) and pose a significant threat to their proper conduct; they seek to bypass models' safeg... |
| 2025-02-13 | [Knowledge Integration Strategies in Autonomous Vehicle Prediction and Planning: A Comprehensive Survey](http://arxiv.org/abs/2502.10477v1) | Kumar Manas, Adrian Paschke | This comprehensive survey examines the integration of knowledge-based approaches into autonomous driving systems, with a focus on trajectory predictio... |
| 2025-02-13 | [Making Them a Malicious Database: Exploiting Query Code to Jailbreak Aligned Large Language Models](http://arxiv.org/abs/2502.09723v1) | Qingsong Zou, Jingyu Xiao et al. | Recent advances in large language models (LLMs) have demonstrated remarkable potential in the field of natural language processing. Unfortunately, LLM... |
| 2025-02-13 | [Learning to Coordinate with Experts](http://arxiv.org/abs/2502.09583v1) | Mohamad H. Danesh, Tu Trinh et al. | When deployed in dynamic environments, AI agents will inevitably encounter challenges that exceed their individual capabilities. Leveraging assistance... |
| 2025-02-13 | [Enhancing Traffic Safety Analysis with Digital Twin Technology: Integrating Vehicle Dynamics and Environmental Factors into Microscopic Traffic Simulation](http://arxiv.org/abs/2502.09561v1) | Guanhao Xu, Jianfei Chen et al. | Traffic safety is a critical concern in transportation engineering and urban planning. Traditional traffic safety analysis requires trained observers ... |
| 2025-02-13 | [A Survey of Reinforcement Learning for Optimization in Automation](http://arxiv.org/abs/2502.09417v1) | Ahmad Farooq, Kamran Iqbal | Reinforcement Learning (RL) has become a critical tool for optimization challenges within automation, leading to significant advancements in several a... |
| 2025-02-13 | [A hierarchical approach for assessing the vulnerability of tree-based classification models to membership inference attack](http://arxiv.org/abs/2502.09396v1) | Richard J. Preen, Jim Smith | Machine learning models can inadvertently expose confidential properties of their training data, making them vulnerable to membership inference attack... |
| 2025-02-13 | [TRIFFID: Autonomous Robotic Aid For Increasing First Responders Efficiency](http://arxiv.org/abs/2502.09379v1) | Jorgen Cani, Panagiotis Koletsis et al. | The increasing complexity of natural disaster incidents demands innovative technological solutions to support first responders in their efforts. This ... |
| 2025-02-13 | [Mitigating multiple single-event upsets during deep neural network inference using fault-aware training](http://arxiv.org/abs/2502.09374v1) | Toon Vinck, Naïn Jonckers et al. | Deep neural networks (DNNs) are increasingly used in safety-critical applications. Reliable fault analysis and mitigation are essential to ensure thei... |
| 2025-02-13 | [AI Safety for Everyone](http://arxiv.org/abs/2502.09288v2) | Balint Gyevnar, Atoosa Kasirzadeh | Recent discussions and research in AI safety have increasingly emphasized the deep connection between AI safety and existential risk from advanced AI ... |
| 2025-02-13 | [Safety Evaluation of Human Arm Operations Using IMU Sensors with a Spring-Damper-Mass Predictive Model](http://arxiv.org/abs/2502.09241v1) | Musab Zubair Inamdar, Seyed Amir Tafrishi | This paper presents a novel approach to real-time safety monitoring in human-robot collaborative manufacturing environments through a wrist-mounted In... |
| 2025-02-13 | [Early Validation of High-level Requirements on Cyber-Physical Systems](http://arxiv.org/abs/2502.09236v1) | Ondřej Vašíček | The overarching, broad topic of my research are advancements in the area of safety-critical, cyber-physical systems (CPS) development with emphasis on... |
| 2025-02-13 | [Data2Concept2Text: An Explainable Multilingual Framework for Data Analysis Narration](http://arxiv.org/abs/2502.09218v1) | Flavio Bertini, Alessandro Dal Palù et al. | This paper presents a complete explainable system that interprets a set of data, abstracts the underlying features and describes them in a natural lan... |
| 2025-02-13 | [FLAME: Flexible LLM-Assisted Moderation Engine](http://arxiv.org/abs/2502.09175v1) | Ivan Bakulin, Ilia Kopanichuk et al. | The rapid advancement of Large Language Models (LLMs) has introduced significant challenges in moderating user-model interactions. While LLMs demonstr... |
| 2025-02-13 | [Improving TCM Question Answering through Tree-Organized Self-Reflective Retrieval with LLMs](http://arxiv.org/abs/2502.09156v1) | Chang Liu, Ying Chang et al. | Objectives: Large language models (LLMs) can harness medical knowledge for intelligent question answering (Q&A), promising support for auxiliary diagn... |
| 2025-02-13 | [LLM-Driven Augmented Reality Puppeteer: Controller-Free Voice-Commanded Robot Teleoperation](http://arxiv.org/abs/2502.09142v1) | Yuchong Zhang, Bastian Orthmann et al. | The integration of robotics and augmented reality (AR) presents transformative opportunities for advancing human-robot interaction (HRI) by improving ... |
| 2025-02-13 | [Pulling Back the Curtain: Unsupervised Adversarial Detection via Contrastive Auxiliary Networks](http://arxiv.org/abs/2502.09110v1) | Eylon Mizrahi, Raz Lapid et al. | Deep learning models are widely employed in safety-critical applications yet remain susceptible to adversarial attacks -- imperceptible perturbations ... |
| 2025-02-13 | [Logical Reasoning in Large Language Models: A Survey](http://arxiv.org/abs/2502.09100v1) | Hanmeng Liu, Zhizhang Fu et al. | With the emergence of advanced reasoning models like OpenAI o3 and DeepSeek-R1, large language models (LLMs) have demonstrated remarkable reasoning ca... |
| 2025-02-13 | [Adapting Language-Specific LLMs to a Reasoning Model in One Day via Model Merging - An Open Recipe](http://arxiv.org/abs/2502.09056v2) | Kunat Pipatanakul, Pittawat Taveekitworachai et al. | This paper investigates data selection and model merging methodologies aimed at incorporating advanced reasoning capabilities such as those of DeepSee... |
| 2025-02-13 | [The Hidden Dimensions of LLM Alignment: A Multi-Dimensional Safety Analysis](http://arxiv.org/abs/2502.09674v1) | Wenbo Pan, Zhichao Liu et al. | Large Language Models' safety-aligned behaviors, such as refusing harmful queries, can be represented by linear directions in activation space. Previo... |
| 2025-02-13 | [Are Smarter LLMs Safer? Exploring Safety-Reasoning Trade-offs in Prompting and Fine-Tuning](http://arxiv.org/abs/2502.09673v1) | Ang Li, Yichuan Mo et al. | Large Language Models (LLMs) have demonstrated remarkable success across various NLP benchmarks. However, excelling in complex tasks that require nuan... |
| 2025-02-13 | [CoCreatAR: Enhancing Authoring of Outdoor Augmented Reality Experiences Through Asymmetric Collaboration](http://arxiv.org/abs/2502.08981v1) | Nels Numan, Gabriel Brostow et al. | Authoring site-specific outdoor augmented reality (AR) experiences requires a nuanced understanding of real-world context to create immersive and rele... |

</details>

<!-- HISTORICAL_PAPERS_END -->
---

## 🔑 Key Safety Domains(coming soon)
| Category               | Key Challenges                          | Related Topics                          |
|------------------------|-----------------------------------------|------------------------------------------|
| **Adversarial Robustness** | Prompt injection, Reasoning path poisoning | Red teaming, Formal verification        |
| **Privacy Preservation**  | Intermediate step memorization, Data leakage | Differential privacy, Federated learning|
| **Ethical Alignment**     | Value locking, Contextual moral reasoning | Constitutional AI, Value learning       |
| **System Safety**         | Cascading failures, Reward hacking       | Safe interruptibility, System monitoring|
| **Regulatory Compliance** | Audit trails, Explainability requirements | Model cards, Governance frameworks      |

---

## 📚 Research Papers(coming soon)
### Foundational Works
- [2023] [Towards Safer Large Reasoning Models: A Survey of Risks in Multistep Reasoning Systems](https://arxiv.org/abs/example )  
  *Comprehensive taxonomy of LRM safety risks*

### Attack Vectors
- [2024] [Hidden Triggers in Reasoning Chains: New Attack Surfaces for LRMs](https://arxiv.org/abs/example )  
  *Demonstrates adversarial manipulation of reasoning steps*

### Defense Mechanisms
- [2024] [Reasoning with Guardrails: Constrained Decoding for LRM Safety](https://arxiv.org/abs/example )  
  *Novel approach to step-wise constraint enforcement*

*(Add your collected papers here with proper categorization)*

---

## 🛠️ Projects & Tools(coming soon)
### Model-Specific Resources
- **DeepSeek-R1 Safety Kit**  
  Official safety evaluation toolkit for DeepSeek-R1 reasoning modules

- **OpenAI o1 Red Teaming Framework**  
  Adversarial testing framework for multi-turn reasoning tasks

### General Tools(coming soon)
- [ReasonGuard](https://github.com/example/reasonguard )  
  Real-time monitoring for reasoning chain anomalies

- [Ethos](https://github.com/example/ethos )  
  Ethical alignment evaluation suite for LRMs

---

## 🤝 Contributing
We welcome contributions! Please:
1. Fork the repository
2. Add resources via pull request
3. Ensure entries follow the format:
   ```markdown
   - [Year] [Paper Title](URL)  
     *Brief description (5-15 words)*
   ```
4. Maintain topical categorization

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 📄 License
This project is licensed under the MIT License - see [LICENSE](LICENSE) for details.

---

## ❓ FAQ
**Q: How do I stay updated?**  
A: Watch this repo and check the "Recent Updates" section (coming soon).

**Q: Can I suggest non-academic resources?**  
A: Yes! Industry reports and blog posts are welcome if they provide novel insights.

**Q: How are entries verified?**  
A: All submissions undergo community review for relevance and quality.

---

> *"With great reasoning power comes great responsibility."* - Adapted from [AI Ethics Manifesto]
