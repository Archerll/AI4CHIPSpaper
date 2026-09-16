# Awesome AI for Chips/VLSI/EDA Papers

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green) 

This repository features a curated reading list of papers on AI for Chips/Very Large Scale Integration (VLSI)/Electronic Design Automation (EDA). The papers are primarily categorized by chip design task type.We're continuously improving this repository. In addition to papers accepted by top-tier conferences and journals, we also include the latest research from arXiv.
If you find any relevant papers that should be added, please feel free to submit a pull request (PR) or open an issue.
If you find this repository helpful, please consider giving it a 🌟!

This repository is built upon the survey "[A Survey of Circuit Foundation Model: Foundation AI Models for VLSI Circuit Design and EDA](https://arxiv.org/pdf/2504.03711)" published by Professor Xie Zhiyao's research group.

<details><summary><h2 style="display: inline;">Survey & Benchmark.</h2></summary>

Date|Method|Type|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----|-----
2023-10|[LLM4SS](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10596266)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |Access|LLM for SoC Security: A Paradigm Shift|
2023-12-28|[Llm4eda](https://arxiv.org/pdf/2401.12224)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|Llm4eda: Emerging progress in large language models for electronic design automation|[paper list](https://github.com/Thinklab-SJTU/Awesome-LLM4EDA)
2024-03|[LCM](https://link.springer.com/content/pdf/10.1007/s11432-024-4155-7.pdf)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |SCIS 2024|Large circuit models: opportunities and challenges.|
2024-05|[LFCD]()|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |ISVLSI 2024|Llms and the future of chip design: Unveiling security risks and building trust|
2024-06|[llm-guided](https://dl.acm.org/doi/abs/10.1145/3649476.3660393)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |GLSVLSI 2024|Navigating soc security landscape on llm-guided paths|
2024-10-24|[Llm-aided](https://arxiv.org/pdf/2410.18582)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|Llm-aided efficient hardware design automation|
2024-12|[HdvLlm](https://www.proquest.com/openview/2b7fbab1fe9882dce439c2d611ad0285/1?pq-origsite=gscholar&cbl=2032404)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |Electronics 2025|Hardware design and verification with large language models: A scoping review, challenges, and open issues|
2025-01|[LLM4EDA](https://dl.acm.org/doi/pdf/10.1145/3715324)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |TODAES 2025|A survey of research in large language models for electronic design automation|
2025-03|[🌟FoundationAI](https://arxiv.org/pdf/2504.03711)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|A Survey of Circuit Foundation Model: Foundation AI Models for VLSI Circuit Design and EDA|
2025-08|[LLMsEDA](https://arxiv.org/abs/2508.20030)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|Large Language Models (LLMs) for Electronic Design Automation (EDA)|
2026-01-05|[RTL-OPT](https://arxiv.org/abs/2601.01765)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|A New Benchmark for the Appropriate Evaluation of RTL Code Optimization|
2026-05-26|[AssertLLM2](https://arxiv.org/abs/2605.27472)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|AssertLLM2: A Comprehensive LLM Benchmark for Assertion Generation from Design Specifications|
2026-01-29|[ChipBench](https://arxiv.org/abs/2601.21448)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|ChipBench: A Next-Step Benchmark for Evaluating LLM Performance in AI-Aided Chip Design|[ChipBench](https://github.com/zhongkaiyu/ChipBench)
2026-04-26|[LLMsFailRTL](https://arxiv.org/abs/2606.19347)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv (under submission for EMNLP 2026)|How LLMs Fail and Generalize in RTL Coding for Hardware Design?|
2026-06-08|[RTL-BenchLS](https://arxiv.org/abs/2606.08976)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|RTL-BenchLS: A Large-Scale Benchmark for RTL Reasoning and Generation with Large Language Models|
2026-05-15|[RTL-BenchMT](https://arxiv.org/abs/2605.15537)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |DAC 2026|RTL-BenchMT: Dynamic Maintenance of RTL Generation Benchmark Through Agent-Assisted Analysis and Revision|
2025-06-17|[CVDP](https://arxiv.org/abs/2506.14074)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|Comprehensive Verilog Design Problems: A Next-Generation Benchmark Dataset for Evaluating Large Language Models and Agents on RTL Design and Verification|[CVDP](https://github.com/NVlabs/cvdp_benchmark)
2026-04-16|[HWE-Bench](https://arxiv.org/abs/2604.14709)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|HWE-Bench: Benchmarking LLM Agents on Real-World Hardware Bug Repair Tasks|
2025-07-20|[MMCircuitEval](https://arxiv.org/abs/2507.19525)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |ICCAD 2025|MMCircuitEval: A Comprehensive Multimodal Circuit-Focused Benchmark for Evaluating LLMs|[MMCircuitEval](https://github.com/cure-lab/MMCircuitEval)
2025-07-22|[RealBench](https://arxiv.org/abs/2507.16200)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|RealBench: Benchmarking Verilog Generation Models with Real-World IP Designs|[RealBench](https://github.com/IPRC-DIP/RealBench)
2025-01-20|SimEval|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |ASP-DAC 2025 (pp. 1002-1007)|SimEval: Investigating the Similarity Obstacle in LLM-based Hardware Code Generation|
2025-06-22|LLMsDrivingForce|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |DAC 2025 (62nd ACM/IEEE DAC)|LLMs: A Driving Force in Next Generation Digital Design Automation|
2025-09-05|[RevolutionOrHype](https://arxiv.org/abs/2509.04905)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |ICCAD 2025 (invited panel paper)|Revolution or Hype? Seeking the Limits of Large Models in Hardware Design|
2024-03-12|FutureOrMirage|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |ISPD 2024 (pp. 65-66); extended journal version ACM TODAES 30(6), 2025|Large Language Models for EDA: Future or Mirage?|
2023-09-14|EDA-GNN-Survey|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |ACM TODAES (Trans. on Design Automation of Electronic Systems), Vol. 26, No. 6, 2022/2023|A Comprehensive Survey on Electronic Design Automation and Graph Neural Networks: Theory and Applications|
2023-01-16|[GNN-IC-Reliability-Security](https://arxiv.org/abs/2211.16495)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |ASP-DAC 2023 (pp. 83-90)|Graph Neural Networks: A Powerful and Versatile Tool for Advancing Design, Reliability, and Security of ICs|
</details>

<details><summary><h2 style="display: inline;">HLS</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2023-10-28|[HARP](https://par.nsf.gov/servlets/purl/10539416)|ICCAD 2023|Robust GNN-based Representation Learning for HLS|
 2024-5-25  | [Synthai](https://arxiv.org/pdf/2405.16072?)                 | arXiv        | Synthai: A multi agent generative ai framework for automated modular hls design generation. |
2024-6-13|[ProgSG](https://dl.acm.org/doi/pdf/10.1145/3670474.3685952)|MLCAD 2024|Cross-modality program representation learning for electronic design automation with high-level synthesis.|
 2024-08-13 | [Hlspilot](https://dl.acm.org/doi/pdf/10.1145/3676536.3676781) | ICCAD 2024   | Hlspilot: Llm-based high-level synthesis                     |
 2024-8-19  | [LLMs4HLS](https://dl.acm.org/doi/pdf/10.1145/3676536.3699507) | ICCAD 2024   | Are llms any good for high-level synthesis?                  |
 2024-11-29 | [C2hlsc](https://dl.acm.org/doi/pdf/10.1145/3734524)         | TODAES 2024  | C2hlsc: Leveraging large language models to bridge the software-tohardware design gap |
2025-2-19|[LLM-assisted-HLS](https://dl.acm.org/doi/pdf/10.1145/3658617.3697616)|ASP-DAC 2025|Exploring code language models for automated hls-based hardware generation: Benchmark, infrastructure and analysis|
2025-7-1|[ChatHLS](https://arxiv.org/pdf/2507.00642)|arXiv|ChatHLS: Towards Systematic Design Automation and Optimization for High-Level Synthesis|
2026-04-10|[DiffHLS](https://arxiv.org/abs/2604.09240)|arXiv|DiffHLS: Differential Learning for High-Level Synthesis QoR Prediction with GNNs and LLM Code Embeddings|
2026-02-01|[Pragmas2Partners](https://arxiv.org/abs/2602.01401)|LATTE 2026|From Pragmas to Partners: A Symbiotic Evolution of Agentic High-Level Synthesis|
2025-07-29|[HLSDebugger](https://arxiv.org/abs/2507.21485)|ICCAD 2025|HLSDebugger: Identification and Correction of Logic Bugs in HLS Code with LLM Solutions|[HLSDebugger](https://github.com/hkust-zhiyao/HLSDebugger)
2025-04-20|[HLSTester](https://arxiv.org/abs/2504.14641)|ICCAD 2025|HLSTester: Efficient Testing of Behavioral Discrepancies with LLMs for High-Level Synthesis|
</details>

<details><summary><h2 style="display: inline;">RTL</h2></summary>

Date|Method|Type|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----|-----
2020-8-27|[Dave](https://dl.acm.org/doi/pdf/10.1145/3380446.3430634)||MLCAD 2020|Dave: Deriving automatically verilog from english|
2021-10-10|[Design2Vec](https://proceedings.neurips.cc/paper/2021/file/c5aa65949d20f6b20e1a922c13d974e7-Paper.pdf)||NeurIPS 2021|Learning semantic representations to verify hardware designs|
2022-12-13|[VGen](https://arxiv.org/pdf/2212.11140)🔥||DATE 2023|Benchmarking large language models for automated verilog rtl code generation|[VGen](https://github.com/shailja-thakur/VGen)
2023-2-17|[](https://eprint.iacr.org/2023/212.pdf)|||Generating secure hardware using chatgpt resistant to cwes|
2023-5-22|[Chip-chat](https://arxiv.org/pdf/2305.13243)🔥||MLCAD 2023|Chip-chat: Challenges and opportunities in conversational hardware design|[ChipChatData](https://github.com/MJoergen/ChipChatData)
2023-5-23|[Chipgpt](https://arxiv.org/pdf/2305.14019)🔥||arXiv|Chipgpt: How far are we from natural language hardware design|
2023-7-28|[VeriGen](https://dl.acm.org/doi/pdf/10.1145/3643681)🔥||TODAES 2024|Verigen: A large language model for verilog code generation|[VeriGen](https://github.com/SohamD34/VeriGen?tab=readme-ov-file)
2023-9-14|[Verilogeval](https://arxiv.org/pdf/2309.07544)🔥||ICCAD 2023|Verilogeval: Evaluating large language models for verilog code generation|[verilog-eval](https://github.com/NVlabs/verilog-eval)
2023-9-19|[GPT4AIGChip](https://arxiv.org/pdf/2309.10730)🔥||ICCAD 2023|GPT4AIGChip: Towards next-generation AI accelerator design automation via large language models.|
2023-10-31|[ChipNeMo](https://arxiv.org/pdf/2311.00176)🔥||arXiv|ChipNeMo: Domain-Adapted LLMs for Chip Design|
2023-11-8|[Autochip](https://arxiv.org/pdf/2311.04887)🔥||arXiv|Autochip: Automating hdl generation using llm feedback|[AutoChip](https://github.com/shailja-thakur/AutoChip)
2023-12-8|SNS v2||MICRO 2023|Fast, robust and transferable prediction for hardware logic synthesis|
2023-12-14|[Rtlcoder](https://arxiv.org/pdf/2312.08617)||TCAD 2024|Rtlcoder: Fully open-source and efficient llm-assisted rtl code generation technique|[RTL-Coder](https://github.com/hkustzhiyao/RTL-Coder)
2024-1-12|[AttenSink](https://arxiv.org/pdf/2401.08683)||arxiv|Zero-shot rtl code generation with attention sink augmented large language models|
2024-2-5|[MCTS](https://arxiv.org/pdf/2402.03289)||arxiv|Make every move count: Llm-based high-quality rtl code generation using mcts|
2024-2-23|[Betterv](https://arxiv.org/pdf/2402.03375)||ICML 2024|Betterv: Controlled verilog generation with discriminative guidance|
2024-3-11|[En2asic](https://arxiv.org/pdf/2403.07039?)||arxiv|From english to asic: Hardware implementation with large language model|
2024-3-17|[chipgptft](https://dl.acm.org/doi/pdf/10.1145/3649329.3657356)||DAC 2024|Data is all you need: Finetuning llms for chip design via an automated design-data augmentation framework|[chipgptft](https://github.com/aichipdesign/chipgptft)
2024-4-12|[Creativeval](https://arxiv.org/pdf/2404.08806)||LAD 2024|Creativeval: Evaluating creativity of llm-based hardware code generation|[CreativEval](https://github.com/matthewdelorenzo/CreativEval/)
2024-5-27|[Rtl-repo](https://arxiv.org/pdf/2405.17378?)||LAD 2024|Rtl-repo: A benchmark for evaluating llms on large-scale rtl design projects|[code](https://github.com/AUCOHL/RTL-Repo)
2024-6-6|[Vhdl-eval](https://arxiv.org/pdf/2406.04379?)||LAD 2024|Vhdl-eval: A framework for evaluating large language models in vhdl code generation|
2024-7-2|[Mg-verilog](https://arxiv.org/pdf/2407.01910?)||LAD 2024|Mg-verilog: Multi-grained dataset towards enhanced llm-assisted verilog generation|[code](https://github.com/GATECH-EIC/mg-verilog)
2024-7-4|[CBA](https://arxiv.org/pdf/2407.18326)||arxiv|Classification-based automatic hdl code generation using llms|
2024-7-11|[chipgptv](https://dl.acm.org/doi/pdf/10.1145/3676536.3676679)||ICCAD 2024|Natural language is not enough: Benchmarking multi-modal generative ai for verilog generation|[code](https://github.com/aichipdesign/chipgptv)
2024-7-15|[Codev](https://arxiv.org/pdf/2407.10424)||arxiv|Codev: Empowering llms for verilog generation through multi-level summarization|[CodeV](https://github.com/IPRC-DIP/CodeV)
2024-7-21|[VeriSeek](https://arxiv.org/pdf/2407.18271)||arxiv|Large Language Model for Verilog Generation with Code-Structure-Guided Reinforcement Learning|
2024-7-23|[Origen](https://arxiv.org/pdf/2407.16237?)||ICCAD 2024|Origen: Enhancing rtl code generation with code-to-code augmentation and self-reflection|[OriGen](https://github.com/pku-liang/OriGen)
2024-7-23|[Hp4lcd](https://arxiv.org/pdf/2407.18276?)||MLCAD 2024|Rome was not built in a single step: Hierarchical prompting for llm-based chip design|
2024-7-24|[Autovcoder](https://arxiv.org/pdf/2407.18333?)||ICCD 2024|Autovcoder: A systematic framework for automated verilog code generation using llms|[AutoVCoder](https://github.com/sjtu-zhao-lab/AutoVCoder)
2024-8-15|[Verilogcoder](https://arxiv.org/pdf/2408.08927)||AAAI 2025|Verilogcoder: Autonomous verilog coding agents with graph-based planning and abstract syntax tree (ast)-based waveform tracing tool|[VerilogCoder](https://github.com/NVlabs/VerilogCoder)
2024-8-20|[ReVerilogeval](https://arxiv.org/pdf/2408.11053v1)||arxiv|Revisiting verilogeval: Newer llms, in-context learning, and specification-to-rtl tasks|
2024-9-9|[CoDes](https://dl.acm.org/doi/pdf/10.1145/3670474.3685966)||MLCAD 2024|Chain-of-descriptions: Improving code llms for vhdl code generation and summarization|
2024-9-19|[Craftrtl](https://arxiv.org/pdf/2409.12993?)||ICLR 2025|Craftrtl: High-quality synthetic data generation for verilog code models with correct-by-construction non-textual representations and targeted code repair|[craftrtl](https://github.com/nvlabs/craftrtl)
2024-11-21|[AIVRIL2](https://arxiv.org/pdf/2412.04485)||DATE 2025|Eda-aware rtl generation with large language models|
2024-11-25|[Opl4gpt](https://eprint.iacr.org/2024/1905.pdf)||ASP-DAC 2025|Opl4gpt: An application space exploration of optimal programming language for hardware design by llm|
2024-12-10|[Mage](https://arxiv.org/pdf/2412.07822)||DAC 2025|Mage: A multi-agent engine for automated rtl code generation|[MAGE](https://github.com/stable-lab/MAGE)
2025-1-6|[Rtlsquad](https://arxiv.org/pdf/2501.05470?)||arxiv|Rtlsquad: Multi-agent based interpretable rtl design|
2025-01-09|[HaVen](https://arxiv.org/pdf/2501.04908)||DATE 2025|HaVen: Hallucination-Mitigated LLM for Verilog Code Generation Aligned with HDL Engineers|
2025-2-15|[Lintllm](https://arxiv.org/pdf/2502.10815)||arxiv|Lintllm: An open-source verilog linting framework based on large language models|
2025-2-20|[Deeprtl](https://arxiv.org/pdf/2502.15832?)||ICLR 2025|Deeprtl: Bridging verilog understanding and generation with a unified representation model|
2025-3-4|[CircuitEncoder](https://zhiyaoxie.com/files/ASPDAC25_CircuitEncoder.pdf)||ASP-DAC 2025|A self-supervised, pre-trained, and cross-stage-aligned circuit encoder provides a foundation for various design tasks|
2025-03-18|[VFlow](https://arxiv.org/pdf/2504.03723)||arxiv|VFlow: Discovering Optimal Agentic Workflows for Verilog Generation|
2025-3-19|[Openllm-rtl](https://arxiv.org/pdf/2503.15112)||ICCAD 2024|Openllm-rtl: Open dataset and benchmark for llm-aided design rtl generation|
2025-03-27|[RocketPPA](https://arxiv.org/pdf/2503.21971)||arxiv|RocketPPA: Code-Level Power, Performance, and Area Prediction via LLM and Mixture of Experts|
2025-03-30|[HDLCORE](https://arxiv.org/pdf/2503.16528)||arxiv|HDLCORE: A TRAINING-FREE FRAMEWORK FOR MIT-IGATING HALLUCINATIONS IN LLM-GENERATED HDL|
2025-5-4|[Circuitfusion](https://arxiv.org/pdf/2505.02168)||ICLR 2025|Circuitfusion: multimodal circuit representation learning for agile chip design|[CircuitFusion](https://github.com/hkust-zhiyao/CircuitFusion)
2025-5-9|[Spec2Doc2RTL](https://ieeexplore.ieee.org/abstract/document/11101140)||ISEDA|Spec2Doc2RTL: RTL Generation from Specification with Natural Language Representation|
2025-05-09|[FreeV](https://arxiv.org/pdf/2505.06096?)||DAC 2025|Free and Fair Hardware: A Pathway to Copyright  Infringement-Free Verilog Generation using LLMs|
2025-6-26|[OpenRTLSet](https://ieeexplore.ieee.org/abstract/document/11106163/)||ICLAD 2025|OpenRTLSet: A Fully Open-Source Dataset for Large Language Model-based Verilog Module Design|
2025-6-26|[EvoVerilog](https://arxiv.org/abs/2508.13156)||arxiv|EvoVerilog: Large Langugage Model Assisted Evolution of Verilog Code|
2025-5-21| [LLM4GV](https://ieeexplore.ieee.org/document/10992751)      |      | DATE 2025     | LLM4GV: An LLM-Based Flexible Performance-Aware Framework for GEMM Verilog Generation |     
2025-5-21| [Data Augmentation and RL](https://ieeexplore.ieee.org/abstract/document/10992897)   |      | DATE 2025     | Improving LLM-Based Verilog Code Generation with Data Augmentation and RL |       
2025-5-21| [VToT](https://ieeexplore.ieee.org/document/10993029)        |      | DATE 2025     |VToT: Automatic Verilog Generation via LLMs with Tree of Thoughts Prompting|
|[MetRex](https://dl.acm.org/doi/pdf/10.1145/3658617.3697625)||ASP- DAC 2025|MetRex: A Benchmark for Verilog Code Metric Reasoning Using LLMs|[MetRex](https://github.com/scale-lab/MetRex)
2026-02-10|[ACE-RTL](https://arxiv.org/abs/2602.10218)||arXiv|ACE-RTL: When Agentic Context Evolution Meets RTL-Specialized LLMs|
2025-11-25|[QiMeng-CRUX](https://arxiv.org/abs/2511.20099)||AAAI 2026|QiMeng-CRUX: Narrowing the Gap Between Natural Language and Verilog via Core Refined Understanding eXpression for Circuit Design|[QiMeng-CRUX](https://github.com/Taskii-Lei/QiMeng-CRUX-V)
2026-06-06|[ROSUM-MCTS](https://arxiv.org/abs/2606.07925)||arXiv|ROSUM-MCTS: Monte Carlo Tree Search-Inspired HDL Code Summarization with Structural Rewards|
2026-06-02|[StepPRM-RTL](https://arxiv.org/abs/2606.04246)||DAC 2026|StepPRM-RTL: Stepwise Process-Reward Guided LLM Fine-Tuning for Enhanced RTL Synthesis|
2026-04-16|[VeriGraphi](https://arxiv.org/abs/2604.14550)||arXiv|VeriGraphi: A Multi-Agent Framework of Hierarchical RTL Generation for Large Hardware Designs|
2026-04-20|[VerilogCL](https://arxiv.org/abs/2604.18162)||arXiv|VerilogCL: A Contrastive Learning Framework for Robust LLM-Based Verilog Generation|
2025-10-26|[FADR](https://ece.k-state.edu/research/hardware-security/papers/iccad.pdf)||ICCAD 2025|Building Reasoning LLMs for Hardware Design Generation via Function-Aligned Differentiated Revision|
2025-07-07|[ChipSeek-R1](https://arxiv.org/abs/2507.04736)||ACL 2026|ChipSeek: Optimizing Verilog Generation via EDA-Integrated Reinforcement Learning|
2025-05-30|[CodeV-R1](https://arxiv.org/abs/2505.24183)||NeurIPS 2025|QiMeng-CodeV-R1: Reasoning-Enhanced Verilog Generation|[CodeV-R1](https://github.com/IPRC-DIP/CodeV-R1)
2025-11-20|[CorrectHDL](https://arxiv.org/abs/2511.16395)||arXiv|CorrectHDL: Agentic HDL Design with LLMs Leveraging High-Level Synthesis as Reference|
2025-06-24|[PPA-RTL](https://dl.acm.org/doi/abs/10.1109/DAC63849.2025.11132897)||DAC 2025|Hardware Generation with High Flexibility using Reinforcement Learning Enhanced LLMs|
2026-02-03|[LLM-FSM](https://arxiv.org/abs/2602.07032)||arXiv|LLM-FSM: Scaling Large Language Models for Finite-State Reasoning in RTL Code Generation|
2024-12-09|[PyraNet](https://arxiv.org/abs/2412.06947)||DAC 2025|PyraNet: A Multi-Layered Hierarchical Dataset for Verilog|[PyraNet](https://huggingface.co/datasets/bnadimi/PyraNet-Verilog)
2025-04-20|[ReasoningV](https://arxiv.org/abs/2504.14560)||arXiv|ReasoningV: Efficient Verilog Code Generation with Adaptive Hybrid Reasoning Model|[ReasoningV](https://github.com/BUAA-CLab/ReasoningV)
2025-11-27|[VeriDispatcher](https://arxiv.org/abs/2511.22749)||arXiv|VeriDispatcher: Multi-Model Dispatching through Pre-Inference Difficulty Prediction for RTL Generation Optimization|
2025-07-20|[VeriOpt](https://arxiv.org/abs/2507.14776)||ICCAD 2025|VeriOpt: PPA-Aware High-Quality Verilog Generation via Multi-Role LLMs|
2026-05-26|[Verilog-Evolve](https://arxiv.org/abs/2605.26498)||arXiv|Verilog-Evolve: Feedback-Driven and Skill-Evolving Verilog Generation|
2024-09-04|[RTLRewriter](https://arxiv.org/abs/2409.11414)||ICCAD 2024|RTLRewriter: Methodologies for Large Models aided RTL Code Optimization|
2026-04-21|[ChipCraftBrain](https://arxiv.org/abs/2604.19856)||arXiv|ChipCraftBrain: Validation-First RTL Generation via Multi-Agent Orchestration|
2026-05-13|[ChipMATE](https://arxiv.org/abs/2605.12857)||arXiv|ChipMATE: Multi-Agent Training via Reinforcement Learning for Enhanced RTL Generation|[ChipMATE](https://github.com/zhongkaiyu/ChipMATE)
2026-04-16|[Dr. RTL](https://arxiv.org/abs/2604.14989)||ICCAD 2026|Dr. RTL: Autonomous Agentic RTL Optimization through Tool-Grounded Self-Improvement|
2026-04-25|[LEGO](https://arxiv.org/abs/2604.23355)||ISEDA 2026|LEGO: An LLM Skill-Based Front-End Design Generation Platform|
2026-01-31|[LocalV](https://arxiv.org/abs/2602.00704)||arXiv|LocalV: Exploiting Information Locality for IP-level Verilog Generation|
2026-02-10|[SiliconMind-V1](https://arxiv.org/abs/2603.08719)||arXiv|SiliconMind-V1: Multi-Agent Distillation and Debug-Reasoning Workflows for Verilog Code Generation|
2026-05-20|[Trace2Skill](https://arxiv.org/abs/2605.21810)||arXiv|Trace2Skill: Verifier-Guided Skill Evolution for Long-Context EDA Agents|
2025-11-08|[ArchCraft](https://arxiv.org/abs/2511.06067)||arXiv|Automating Hardware Design and Verification from Architectural Papers via a Neural-Symbolic Graph Framework|
2025-12-05|[ChipMind](https://arxiv.org/abs/2512.05371)||AAAI 2026|ChipMind: Retrieval-Augmented Reasoning for Long-Context Circuit Design Specifications|
2025-12-04|[David vs. Goliath](https://arxiv.org/abs/2512.05073)||arXiv|David vs. Goliath: Can Small Models Win Big with Agentic AI in Hardware Design?|
2026-06-03|[Alpha-RTL (TTT-RTL)](https://arxiv.org/abs/2606.05253)||arXiv|Alpha-RTL: Test-Time Training for RTL Hardware Optimization|
2026-01-26|[EvolVE](https://arxiv.org/abs/2601.18067)||arXiv|EvolVE: Evolutionary Search for LLM-based Verilog Generation and Optimization|[EvolVE](https://github.com/weiber2002/ICRTL)
2026-03-29|[RTLSeek](https://arxiv.org/abs/2603.27630)||DAC 2026|RTLSeek: Boosting the LLM-Based RTL Generation with Multi-Stage Diversity-Oriented Reinforcement Learning|[RTLSeek](https://anonymous.4open.science/r/DAC2026ID71-ACB4/)
2025-11-15|[EARL](https://arxiv.org/abs/2511.12033)||CTS 2026 (Chips to Systems Conference)|EARL: Entropy-Aware RL Alignment of LLMs for Reliable RTL Code Generation|
2025-08-25|[VeriRL](https://arxiv.org/abs/2508.18462)||arXiv|VeriRL: Boosting the LLM-based Verilog Code Generation via Reinforcement Learning|[VeriRL](https://github.com/omniAI-Lab/VeriRL)
2025-11-25|[Invertible-HDL](https://arxiv.org/abs/2512.03053)||arXiv|Mitigating hallucinations and omissions in LLMs for invertible problems: An application to hardware logic design automation|
2025-10-26|LLM4Verilog||ICCAD 2025|LLM4Verilog: Building Large-Scale, High-Quality Data Infrastructure for Verilog Code Generation via Community Efforts|
2025-09-01|SynC-LLM||EMNLP 2025|SynC-LLM: Generation of Large-Scale Synthetic Circuit Code with Hierarchical Language Models|[SynC-LLM](https://github.com/hkust-zhiyao/SynCircuitData)
2025-08-26|[SynCircuit](https://arxiv.org/abs/2509.00071)||DAC 2025|SynCircuit: Automated Generation of New Synthetic RTL Circuits Can Enable Big Data in Circuits|
2026-05-03|[PipeRTL](https://arxiv.org/abs/2605.01836)||arXiv|PipeRTL: Timing-Aware Pipeline Optimization at IR-Level for RTL Generation|
2026-07-17|[RTL-Sequencer](https://arxiv.org/abs/2607.15830)||DAC 2026|RTL-Sequencer: Towards Scalable RTL Timing Prediction with the Sequence-based Paradigm|
2026-04-16|[Self-Evolved ABC](https://arxiv.org/abs/2604.15082)||DAC 2026|Autonomous Evolution of EDA Tools: Multi-Agent Self-Evolved ABC|
2025-01-20|LLSM||ASP-DAC 2025 (30th Asia and South Pacific Design Automation Conference; DOI 10.1145/3658617.3697618)|LLSM: LLM-enhanced Logic Synthesis Model with EDA-guided CoT Prompting, Hybrid Embedding and AIG-tailored Acceleration|
2025-06-01|MOSS||DAC 2025 (62nd ACM/IEEE Design Automation Conference)|MOSS: Multi-Modal Representation Learning on Sequential Circuits|
2024-01-01|[MasterRTL](https://arxiv.org/abs/2311.08441)||IEEE TCAD (DOI 10.1109/TCAD.2024.3420904)|Transferable Presynthesis PPA Estimation for RTL Designs With Data Augmentation Techniques|
</details>

<details><summary><h2 style="display: inline;">Verification & Debug</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2023-06-03|[NL2SVA](https://openreview.net/pdf?id=FKH8qCuM44)|DAV 2023|Towards improving verification productivity with circuitaware translation of natural language to systemverilog assertions|
2023-09-18|[AutoSVA2](https://arxiv.org/pdf/2309.09437)|arxiv|Using LLMs to facilitate formal verification of RTL|
2023-10-06|[LLM4DV](https://arxiv.org/pdf/2310.04535)|FCCM 2025|Llm4dv: Using large language models for hardware test stimuli generation.|[ml4dv](https://github.com/ZixiBenZhang/ml4dv)
2023-11-28|[RTLFixer](https://arxiv.org/pdf/2311.16543)🔥|DAC 2024|Rtlfixer: Automatically fixing rtl syntax errors with large language models|[RTLFixer](https://github.com/NVlabs/RTLFixer)
2024-01-31|[ChIRAAG](https://arxiv.org/pdf/2402.00093)|ISVLSI 2024|Chiraag: Chatgpt informed rapid and automated assertion generation.|[ChIRAAG](https://github.com/karthikmaddala/ChIRAAG)
2024-02-01|[AssertLLM](https://arxiv.org/pdf/2402.00386)|ASP-DAC 2025|AssertLLM: Generating and evaluating hardware verification assertions from design specifications via multi-LLMs.|[AssertLLM](https://github.com/hkust-zhiyao/AssertLLM)
2024-03-18|[HDLDebugger](https://dl.acm.org/doi/pdf/10.1145/3735638)|TODAES 2024|Hdldebugger: Streamlining hdl debugging with large language models|
2024-05-10| [MEIC](https://arxiv.org/pdf/2405.06840)                     | ICCAD 2024   | Meic: Re-thinking rtl debug automation using llms            |
2024-05-31|[VeriAssist](https://arxiv.org/pdf/2406.00115)|arxiv|Towards llm-powered verilog rtl assistant: Self-verification and self-correction|
2024-06-03|[VerilogReader](https://arxiv.org/pdf/2406.04373?)|LAD 2024|Verilogreader: Llm-aided hardware test generation|
2024-06-10||DATE 2024|Llm-based processor verification: A case study for neuronnorphic processor.|
2024-06-24|[Latg](https://arxiv.org/pdf/2406.17132)|arxiv|Llm-aided testbench generation and bug detection for finite-state machines.|
2024-06-26|[AssertionBench](https://arxiv.org/pdf/2406.18627)|arxiv|Assertionbench: A benchmark to evaluate large-language models for assertion generation|
2024-8-15| [Verilogcoder](https://arxiv.org/pdf/2408.08927)             | AAAI 2025    | Verilogcoder: Autonomous verilog coding agents with graph-based planning and abstract syntax tree (ast)-based waveform tracing tool | [VerilogCoder](https://github.com/NVlabs/VerilogCoder) 
 2024-10-01 | [llmrag](https://agra.informatik.uni-bremen.de/doc/konf/LAD2024_KQ.pdf) | LAD 2025     | From bugs to fixes: Hdl bug identification and patching using llms and rag |
2024-10-15|[FVEval](https://arxiv.org/pdf/2410.23299)|DATE 2025|Fveval: Understanding language model capabilities in formal verification of digital hardware|[FVEval](https://github.com/NVlabs/FVEval)
2024-11-25|[UVLLM](https://arxiv.org/pdf/2411.16238)|arxiv|Uvllm: An automated universal rtl verification framework using llms.|
2024-05-29||VTS 2024|Domain-adapted llms for vlsi design and verification: A case study on formal verification|
2025-06-13|[PRO-V](https://arxiv.org/pdf/2506.12200)||PRO-V: An Efficient Program Generation Multi-Agent System for Automatic RTL Verification|
|[CorrectBench](https://ieeexplore.ieee.org/document/10992873)|DATE 2025|CorrectBench: Automatic Testbench Generation with Functional Self-Correction using LLMs for HDL Design|[CorrectBench](https://github.com/AutoBench/CorrectBench)
||||



2026-05-08|[CktFormalizer](https://arxiv.org/abs/2605.07782)|arXiv|CktFormalizer: Autoformalization of Natural Language into Circuit Representations|
2026-04-10|[AgileAssert](https://arxiv.org/abs/2604.08932)|arXiv|From Indiscriminate to Targeted: Functionally Critical Signal-Driven Assertion Generation using LLMs for Efficient RTL Verification|
2026-03-15|[CodeV-SVA](https://arxiv.org/abs/2603.14239)|DAC 2026|QiMeng-CodeV-SVA: Training Specialized LLMs for Hardware Assertion Generation via RTL-Grounded Bidirectional Data Synthesis|[CodeV-SVA](https://github.com/wyt2000/CodeV-SVA)
2026-03-03|[SpecLoop](https://arxiv.org/abs/2603.02895)|arXiv|SpecLoop: An Agentic RTL-to-Specification Framework with Formal Verification Feedback Loop|
2026-06-11|[STG](https://arxiv.org/abs/2606.12983)|arXiv|Structured Testbench Generation for LLM-Driven HDL Design and Verification-Oriented Data Curation|
2026-05-06|[UVMarvel](https://arxiv.org/abs/2605.04704)|DAC 2026|UVMarvel: an Automated LLM-aided UVM Machine for Subsystem-level RTL Verification|
2026-08-10|[CHORUS](https://arxiv.org/abs/2608.10090)|arXiv|CHORUS: Complementary Experts for High-Coverage Testbench Stimulus Generation|
2025-04-28|[UVM^2](https://arxiv.org/abs/2504.19959)|ICCAD 2025|From Concept to Practice: an Automated LLM-aided UVM Machine for RTL Verification|
2026-07-28|[GoGoTB](https://arxiv.org/abs/2607.26181)|ICCAD 2026|GoGoTB: Agentic RTL Verification with Specification-Grounded Coverage Closure|
2025-11-19|[CD-DPO (TB or not TB)](https://arxiv.org/abs/2511.15767)|arXiv|TB or Not TB: Coverage-Driven Direct Preference Optimization for Verilog Stimulus Generation|
2025-08-22|[ARSP](https://arxiv.org/abs/2508.16517)|arXiv|ARSP: Automated Repair of Verilog Designs via Semantic Partitioning|
2025-03-06|[AssertSolver](https://arxiv.org/abs/2503.04057)|DAC 2025|Insights from Rights and Wrongs: A Large Language Model for Solving Assertion Failures in RTL Design|[AssertSolver](https://github.com/SEU-ACAL/reproduce-AssertSolver-DAC-25)
2024-09-23|[LiK](https://arxiv.org/abs/2409.15186)|DAC 2025|Location is Key: Leveraging Large Language Model for Functional Bug Localization in Verilog|
2026-06-22|[VeriPilot](https://arxiv.org/abs/2606.23759)|arXiv|VeriPilot: An LLM-Powered Verilog Debugging Framework|[VeriPilot](https://github.com/YihanWn/VeriPilot)
2026-08-03|[VeriTrace](https://arxiv.org/abs/2608.02878)|ICLAD 2026|VeriTrace: Human-Like Temporal Exploration Completes Agentic Action Space|
2025-03-31|SSF|DATE 2025|Early Functional Safety and PPA Evaluation of Digital Designs|
</details>

<details><summary><h2 style="display: inline;">Security</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2021-12-03|[EZSVR](https://arxiv.org/pdf/2112.02125)🔥|SP 2023|Examining zero-shot vulnerability repair with large language models|
2023-02||TIFS 2024|On hardware security bug code fixes by prompting large language models|
2023-06-24|[SAbyLLM](https://arxiv.org/pdf/2306.14027)|TIFS 2024|(security) assertions by large language models|
2023-08-14|[DIVAS](https://arxiv.org/pdf/2308.06932)|arxiv|Divas: An llm-based end-to-end framework for soc security analysis and policy-based protection|
2023-08-21|[NSPG](https://arxiv.org/pdf/2308.11042)|arxiv|Unlocking hardware security assurance: The potential of llms|
2023-10-10|[SCAR](https://arxiv.org/pdf/2310.06257)|TVLSI 2024|Scar: Power side-channel analysis at rtl level|
2023-11-26|Netlist Whisperer|ASHES 2023|Netlist whisperer: Ai and nlp fight circuit leakage!|
2024-05|[SecRT-LLM](https://www.researchgate.net/profile/Dipayan-Saha/publication/381234667_Empowering_Hardware_Security_with_LLM_The_Development_of_a_Vulnerable_Hardware_Database/links/675936c2138b414414d56fcb/Empowering-Hardware-Security-with-LLM-The-Development-of-a-Vulnerable-Hardware-Database.pdf)|HOST 2024|Empowering hardware security with llm: The development of a vulnerable hardware database|
2024-05|[Self-HWDebug](https://arxiv.org/pdf/2405.12347)|ISVLSI 2024|Self-hwdebug: Automation of llm self-instructing for hardware security verification|
 2024-10-01 | [llmrag](https://agra.informatik.uni-bremen.de/doc/konf/LAD2024_KQ.pdf) | LAD 2025    | From bugs to fixes: Hdl bug identification and patching using llms and rag |
  | [RTL-Breaker](https://ieeexplore.ieee.org/document/10993260) | DATE 2025 | RTL-Breaker: Assessing the Security of LLMs Against Backdoor Attacks on HDL Code Generation |

2025-01-05|[RTLMarker](https://arxiv.org/abs/2501.02446)|ASP-DAC 2025|RTLMarker: Protecting LLM-Generated RTL Copyright via a Hardware Watermarking Framework|
​	</details>

<details><summary><h2 style="display: inline;">Architecture</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2023-06-12|[LCDA](https://arxiv.org/pdf/2306.06923)|arxiv|On the viability of using LLMs for SW/HW co-design: An example in designing CiM DNN accelerators.|
2023-07-17|[QGAS](https://arxiv.org/pdf/2307.08191)|arxiv|Unleashing the potential of LLMs for quantum computing: A study in quantum architecture design|
2023-9-19|[GPT4AIGChip](https://arxiv.org/pdf/2309.10730)🔥|ICCAD 2023|GPT4AIGChip: Towards next-generation AI accelerator design automation via large language models.|
2024-1-24|[SpecLLM](https://arxiv.org/pdf/2401.13266)|arxiv|SpecLLM: Exploring generation and review of vlsi design specification with large language model.|

2025-10-26|MultiModel-DSE|ICCAD 2025|LLM-Augmented Multi-Modal Fusion for SoC Design Space Exploration|
2026-02-06|[Design Conductor (DC)](https://arxiv.org/abs/2603.08716)|arXiv|Design Conductor: An agent autonomously builds a 1.5 GHz Linux-capable RISC-V CPU|
2025-08-08|[MAHL](https://arxiv.org/abs/2508.14053)|ICCAD 2025|MAHL: Multi-Agent LLM-Guided Hierarchical Chiplet Design with Adaptive Debugging|
2026-08-10|[FSGen](https://arxiv.org/abs/2608.09252)|DAC 2026|FSGen: Agile Fused and Sparse Accelerator Generator with Accurate Power Model for LLM Applications|[FSGen](https://github.com/hkust-zhiyao/FSGen)
2026-07-08|[ThermoDSE](https://arxiv.org/abs/2607.07096)|arXiv|ThermoDSE: A Thermal-Aware and Comprehensive Design Space Exploration for Chiplet-Based DNN Accelerators|
2025-06-03|[LPCM](https://arxiv.org/abs/2506.02929)|arXiv|Large Processor Chip Model|
2025-05-06|[State-BSD](https://arxiv.org/abs/2505.03195)|IJCAI 2025|QiMeng-CPU-v2: Automated Superscalar Processor Design by Learning Data Dependencies|
2026-08-26|[Redwood](https://arxiv.org/abs/2608.26418)|arXiv|Redwood: A Frontier AI Accelerator Designed, Verified, and Deployed from Scratch in 2 Weeks by AI|
2024-06-23|ChatCPU|DAC 2024|ChatCPU: An Agile CPU Design & Verification Platform with LLM|
2024-08-03|BSD (Enlightenment-1 / QiMeng-CPU-v1)|IJCAI 2024|Automated CPU Design by Learning from Input-Output Examples|
2023-06-21|[BSD (AlphaChip / Enlightenment)](https://arxiv.org/abs/2306.12456)|National Science Review (NSR)|Pushing the Limits of Machine Design: Automated CPU Design with AI|
</details>

<details><summary><h2 style="display: inline;">Netlist</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2021-11-26| [DeepGate](https://arxiv.org/pdf/2111.14616) | DAC 2022     |DeepGate: Learning neural representations of logic gates|
2023-02-27| [Deepseq](https://arxiv.org/pdf/2302.13608) | DATE         |Deepseq: Deep sequential circuit learning. In Design, Automation and Test in Europe Conference and Exhibition|
2023-03-14| [Gamora](https://arxiv.org/pdf/2303.08256) | DAC 2023     |Gamora: Graph learning based symbolic reasoning for large-scale boolean networks|
2023-05-25| [DeepGate2](https://arxiv.org/pdf/2305.16373) | ICCAD 2023   |DeepGate2: Functionality-aware circuit representation learning|
2022-8-23| [Fgnn](https://www.cse.cuhk.edu.hk/~byu/papers/C142-DAC2022-GCL.pdf) | DAC 2022     |Functionality matters in netlist representation learning|
2024-03-02| [Less is more](https://arxiv.org/pdf/2403.01317) |DAC 2024|Less is more: Hop-wise graph attention for scalable and generalizable learning on circuits|
2024-11-01| [Deepseq2](https://dl.acm.org/doi/pdf/10.1145/3658617.3697594) | ASP-DAC 2025 |Deepseq2: Enhanced sequential circuit learning with disentangled representations|
2025-01-01| [Fgnn2](https://www.cse.cuhk.edu.hk/~byu/papers/J119-TCAD2025-FGNN2.pdf) | TCAD 2024    |Fgnn2: A powerful pre-training framework for learning the logic functionality of circuits|
2025-01-23| [Deepgate4](https://arxiv.org/pdf/2502.01681?) | ICLR 2025    |Deepgate4: Efficient and effective representation learning for circuit design at scale|
2025-2-5| [Deepcell](https://arxiv.org/pdf/2502.06816) | arxiv        |Deepcell: Multiview representation learning for post-mapping netlists|
2025-2-18| [MGVGA](https://arxiv.org/pdf/2502.12732) | ICLR 2025    | Circuit representation learning with masked gatemodeling and verilog-aigalignment |
2025-3-4| [CircuitEncoder](https://zhiyaoxie.com/files/ASPDAC25_CircuitEncoder.pdf) |ASP-DAC 2025|A self-supervised, pre-trained, and cross-stage-aligned circuit encoder provides a foundation for various design tasks|
2025-04-09| [Polargate](https://www.cse.cuhk.edu.hk/~byu/papers/C233-ICCAD2024-PolarGate.pdf) | ICCAD 2024   |Polargate: Breaking the functionality representation bottleneck of and-inverter graph neural network|
2025-04-12| [NetTAG](https://arxiv.org/pdf/2504.09260) | DAC 2025     | Nettag: A multimodal rtl-and-layoutaligned netlist foundation model via text-attributed graph |
 2025-04-13 |[GenEDA](https://arxiv.org/pdf/2504.09485?)|arxiv|GenEDA: Unleashing Generative Reasoning on Netlist via Multimodal Encoder-Decoder Aligned Foundation Model|
2026-08-28|[DeepSeq3](https://arxiv.org/abs/2608.28188)|arXiv|Beyond Flat Netlist: Hierarchical Graph Representation Learning for Scalable Analysis of Sequential Circuits|[DeepSeq3](https://github.com/cure-lab/DeepSeq3)
2025-11-12|[DR-GNN](https://arxiv.org/abs/2511.09593)|AAAI 2026|DynamicRTL: RTL Representation Learning for Dynamic Circuit Behavior|[DR-GNN](https://github.com/magicyang1573/DynamicRTL)
2026-03-10|[WrongCode](https://arxiv.org/abs/2603.09161)|arXiv|Wrong Code, Right Structure: Learning Netlist Representations from Imperfect LLM-Generated RTL|
2025-02-18|[CircuitAR](https://arxiv.org/abs/2502.12751)|arXiv|Architect of the Bits World: Masked Autoregressive Modeling for Circuit Generation Guided by Truth Table|
2022-11-07|[WhyGNN](https://dl.acm.org/doi/10.1145/3508352.3561093)|ICCAD 2022|Why are Graph Neural Networks Effective for EDA Problems?: (Invited Paper)|
2022-09-07|[TAG](https://arxiv.org/abs/2209.03465)|ICCAD 2022|TAG: Learning Circuit Spatial Embedding From Layouts|
</details>

<details><summary><h2 style="display: inline;">Flow & Layout</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2023-08| [ChatEDA](https://arxiv.org/pdf/2308.10204)            | MLCAD 2023 | Chateda: A large language model powered autonomous agent for eda | [ChatEDAv1](https://github.com/wuhy68/ChatEDAv1) 
 2024-07    | RAG-[EDA](https://arxiv.org/pdf/2407.15353)                  | ICCAD 2024 | Customized retrieval augmented generation and benchmarking for eda tool documentation qa | [RAG-EDA](https://github.com/lesliepy99/RAG-EDA) 
 2024-12    | [ChipAlign](https://arxiv.org/pdf/2412.19819?)         | arxiv | Chipalign: Instruction alignment in large language models for chip design via geodesic interpolation |
 2024-05-24 | [LLM4Scldof](https://arxiv.org/pdf/2406.06549?)              | LAD 2024   | Large language model (llm) for standard cell layout design optimization |
 2024-07-15 | [FabGPT](https://arxiv.org/pdf/2407.10810?)                  | ICCAD 2024 | Fabgpt: An efficient large multimodal model for complex wafer defect knowledge queries |
 2024-08-24 | two-[stage](https://ojs.aaai.org/index.php/AAAI/article/view/34479) | AAAI 2024  | Intelligent opc engineer assistant for semiconductor manufacturing |
 2024-11-28 | DRC-[Coder](https://dl.acm.org/doi/pdf/10.1145/3698364.3705347) | arxiv      | Drc-coder: Automated drc checker code generation using llm autonomous agent |

2025-10-18|EDA-Copilot|ACM TODAES 2025|EDA-Copilot: A RAG-Powered Intelligent Assistant for EDA Tools|
2025-02-15|[EDAid](https://arxiv.org/abs/2502.10857)|NAACL 2025|Divergent Thoughts toward One Goal: LLM-based Multi-Agent Collaboration System for Electronic Design Automation|
2026-04-28|[EIM](https://arxiv.org/abs/2604.25191)|DAC 2026|How Can Reinforcement Learning Achieve Expert-level Placement?|
2025-10-01|OptAware-PRTP|IEEE TCAD 2025|An Optimization-Aware Prerouting Timing Prediction Framework Based on Multimodal Learning|
2025-07-02|[CROP](https://arxiv.org/abs/2507.02128)|ICCAD 2025|CROP: Circuit Retrieval and Optimization with Parameter Guidance using LLMs|
2024-06-23|LLM-HD|DAC 2024|LLM-HD: Layout Language Model for Hotspot Detection with GDS Semantic Encoding|
2025-10-27|MM-GRADE|ICCAD 2025|MM-GRADE: A Multi-Modal EDA Tool Documentation QA Framework Leveraging Retrieval Augmented Generation|[MM-GRADE](https://github.com/lesliepy99/MM-GRADE-Benchmarks-ICCAD)
</details>

<details><summary><h2 style="display: inline;">Analog</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2023-12|[LADAC](https://www.techrxiv.org/doi/full/10.36227/techrxiv.170473941.10097233)||Ladac: Large language model-driven auto-designer for analog circuits|
2024-05|[AnalogCoder](https://ojs.aaai.org/index.php/AAAI/article/view/32016)|AAAI 2025|Analogcoder: Analog circuit design via training-free code generation|[AnalogCoder](https://github.com/anonyanalog/AnalogCoder)
2024-05|FLAG|ISCAS 2024|Flag: Formula-llm-based auto-generator for baseband hardware|
2024-04-09|[ADO-LLM](https://dl.acm.org/doi/pdf/10.1145/3676536.3676816)|ISCAS 2024|Ado-llm: Analog design bayesian optimization with in-context learning of large language models|
2024-07|[LaMAGIC](https://arxiv.org/pdf/2407.18269?)||Lamagic: Language-model-based topology generation for analog integrated circuits|
2024-11|Artisan|DAC 2024|Artisan: Automated operational amplifier design via domain-specific large language model|
2024-11-19|[LEDRO](https://arxiv.org/pdf/2411.12930)||Ledro: Llm-enhanced design space reduction and optimization for analog circuits|
2024-12-17|[AnalogXpert](https://arxiv.org/abs/2412.19824)||Analogxpert: Automating analog topology synthesis by incorporating circuit design expertise into large language models|
2025-01-14|[LayoutCopilot](https://ieeexplore.ieee.org/document/10841395)|TCAD 2025|LayoutCopilot: An LLM-Powered Multiagent Collaborative Framework for Interactive Analog Layout Design.|
2025-02-28|[AnalogGenie](https://arxiv.org/pdf/2503.00205)|ICLR 2025|Analoggenie: A generative engine for automatic discovery of analog circuit topologies|[AnalogGenie](https://github.com/xz-group/AnalogGenie)

</details>



