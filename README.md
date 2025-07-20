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
2025-03|[FoundationAI](https://arxiv.org/pdf/2504.03711)|![suervey](https://img.shields.io/badge/-suervey-brightgreen) |arXiv|A Survey of Circuit Foundation Model: Foundation AI Models for VLSI Circuit Design and EDA|

</details>

<details><summary><h2 style="display: inline;">HLS</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2023-10-28|[HARP](https://par.nsf.gov/servlets/purl/10539416)|ICCAD 2023|Robust GNN-based Representation Learning for HLS|
 2024-5-25  | [Synthai](https://arxiv.org/pdf/2405.16072?)                 | arXiv        | Synthai: A multi agent generative ai framework for automated modular hls design generation. |
 2024-08-13 | [Hlspilot](https://dl.acm.org/doi/pdf/10.1145/3676536.3676781) | ICCAD 2024   | Hlspilot: Llm-based high-level synthesis                     |
 2024-8-19  | [LLMs4HLS](https://dl.acm.org/doi/pdf/10.1145/3676536.3699507) | ICCAD 2024   | Are llms any good for high-level synthesis?                  |
 2024-11-29 | [C2hlsc](https://dl.acm.org/doi/pdf/10.1145/3734524)         | TODAES 2024  | C2hlsc: Leveraging large language models to bridge the software-tohardware design gap |
2025-2-19|[LLM-assisted-HLS](https://dl.acm.org/doi/pdf/10.1145/3658617.3697616)|ASP-DAC 2025|Exploring code language models for automated hls-based hardware generation: Benchmark, infrastructure and analysis|
2024-6-13|[ProgSG](https://dl.acm.org/doi/pdf/10.1145/3670474.3685952)|MLCAD 2024|Cross-modality program representation learning for electronic design automation with high-level synthesis.|

</details>

<details><summary><h2 style="display: inline;">RTL</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2020-8-27|[Dave](https://dl.acm.org/doi/pdf/10.1145/3380446.3430634)|MLCAD 2020|Dave: Deriving automatically verilog from english|
2021-10-10|[Design2Vec](https://proceedings.neurips.cc/paper/2021/file/c5aa65949d20f6b20e1a922c13d974e7-Paper.pdf)|NeurIPS 2021|Learning semantic representations to verify hardware designs|
2022-12-13|[VGen](https://arxiv.org/pdf/2212.11140)🔥|DATE 2023|Benchmarking large language models for automated verilog rtl code generation|[VGen](https://github.com/shailja-thakur/VGen)
2023-2-17|[](https://eprint.iacr.org/2023/212.pdf)||Generating secure hardware using chatgpt resistant to cwes|
2023-5-22|[Chip-chat](https://arxiv.org/pdf/2305.13243)🔥|MLCAD 2023|Chip-chat: Challenges and opportunities in conversational hardware design|[ChipChatData](https://github.com/MJoergen/ChipChatData)
2023-5-23|[Chipgpt](https://arxiv.org/pdf/2305.14019)🔥|arXiv|Chipgpt: How far are we from natural language hardware design|
2023-7-28|[Verigen](https://dl.acm.org/doi/pdf/10.1145/3643681)🔥|TODAES 2024|Verigen: A large language model for verilog code generation|
2023-9-14|[Verilogeval](https://arxiv.org/pdf/2309.07544)🔥|ICCAD 2023|Verilogeval: Evaluating large language models for verilog code generation|[verilog-eval](https://github.com/NVlabs/verilog-eval)
2023-9-19|[GPT4AIGChip](https://arxiv.org/pdf/2309.10730)🔥|ICCAD 2023|GPT4AIGChip: Towards next-generation AI accelerator design automation via large language models.|
2023-10-31|[ChipNeMo](https://arxiv.org/pdf/2311.00176)🔥|arXiv|ChipNeMo: Domain-Adapted LLMs for Chip Design|
2023-11-8|[Autochip](https://arxiv.org/pdf/2311.04887)🔥|arXiv|Autochip: Automating hdl generation using llm feedback|[AutoChip](https://github.com/shailja-thakur/AutoChip)
2023-12-8|SNS v2|MICRO 2023|Fast, robust and transferable prediction for hardware logic synthesis|
2023-12-14|[Rtlcoder](https://arxiv.org/pdf/2312.08617)|TCAD 2024|Rtlcoder: Fully open-source and efficient llm-assisted rtl code generation technique|[RTL-Coder](https://github.com/hkustzhiyao/RTL-Coder)
2024-1-12|[AttenSink](https://arxiv.org/pdf/2401.08683)|arxiv|Zero-shot rtl code generation with attention sink augmented large language models|
2024-2-5|[MCTS](https://arxiv.org/pdf/2402.03289)|arxiv|Make every move count: Llm-based high-quality rtl code generation using mcts|
2024-2-23|[Betterv](https://arxiv.org/pdf/2402.03375)|ICML 2024|Betterv: Controlled verilog generation with discriminative guidance|
2024-3-11|[En2asic](https://arxiv.org/pdf/2403.07039?)|arxiv|From english to asic: Hardware implementation with large language model|
2024-3-17|[chipgptft](https://dl.acm.org/doi/pdf/10.1145/3649329.3657356)|DAC 2024|Data is all you need: Finetuning llms for chip design via an automated design-data augmentation framework|[chipgptft](https://github.com/aichipdesign/chipgptft)
2024-4-12|[Creativeval](https://arxiv.org/pdf/2404.08806)|LAD 2024|Creativeval: Evaluating creativity of llm-based hardware code generation|[CreativEval](https://github.com/matthewdelorenzo/CreativEval/)
2024-5-27|[Rtl-repo](https://arxiv.org/pdf/2405.17378?)|LAD 2024|Rtl-repo: A benchmark for evaluating llms on large-scale rtl design projects|[code](https://github.com/AUCOHL/RTL-Repo)
2024-6-6|[Vhdl-eval](https://arxiv.org/pdf/2406.04379?)|LAD 2024|Vhdl-eval: A framework for evaluating large language models in vhdl code generation|
2024-7-2|[Mg-verilog](https://arxiv.org/pdf/2407.01910?)|LAD 2024|Mg-verilog: Multi-grained dataset towards enhanced llm-assisted verilog generation|[code](https://github.com/GATECH-EIC/mg-verilog)
2024-7-4|[CBA](https://arxiv.org/pdf/2407.18326)|arxiv|Classification-based automatic hdl code generation using llms|
2024-7-11|[chipgptv](https://dl.acm.org/doi/pdf/10.1145/3676536.3676679)|ICCAD 2024|Natural language is not enough: Benchmarking multi-modal generative ai for verilog generation|[code](https://github.com/aichipdesign/chipgptv)
2024-7-15|[Codev](https://arxiv.org/pdf/2407.10424)|arxiv|Codev: Empowering llms for verilog generation through multi-level summarization|[CodeV](https://github.com/IPRC-DIP/CodeV)
2024-7-21|[VeriSeek](https://arxiv.org/pdf/2407.18271)|arxiv|Large Language Model for Verilog Generation with Code-Structure-Guided Reinforcement Learning|
2024-7-23|[Origen](https://arxiv.org/pdf/2407.16237?)|ICCAD 2024|Origen: Enhancing rtl code generation with code-to-code augmentation and self-reflection|[OriGen](https://github.com/pku-liang/OriGen)
2024-7-23|[Hp4lcd](https://arxiv.org/pdf/2407.18276?)|MLCAD 2024|Rome was not built in a single step: Hierarchical prompting for llm-based chip design|
2024-7-24|[Autovcoder](https://arxiv.org/pdf/2407.18333?)|ICCD 2024|Autovcoder: A systematic framework for automated verilog code generation using llms|[AutoVCoder](https://github.com/sjtu-zhao-lab/AutoVCoder)
2024-8-15|[Verilogcoder](https://arxiv.org/pdf/2408.08927)|AAAI 2025|Verilogcoder: Autonomous verilog coding agents with graph-based planning and abstract syntax tree (ast)-based waveform tracing tool|[VerilogCoder](https://github.com/NVlabs/VerilogCoder)
2024-8-20|[ReVerilogeval](https://arxiv.org/pdf/2408.11053v1)|arxiv|Revisiting verilogeval: Newer llms, in-context learning, and specification-to-rtl tasks|
2024-9-9|[CoDes](https://dl.acm.org/doi/pdf/10.1145/3670474.3685966)|MLCAD 2024|Chain-of-descriptions: Improving code llms for vhdl code generation and summarization|
2024-9-19|[Craftrtl](https://arxiv.org/pdf/2409.12993?)|ICLR 2025|Craftrtl: High-quality synthetic data generation for verilog code models with correct-by-construction non-textual representations and targeted code repair|[craftrtl](https://github.com/nvlabs/craftrtl)
2024-11-21|[AIVRIL2](https://arxiv.org/pdf/2412.04485)|DATE 2024|Eda-aware rtl generation with large language models|
2024-11-25|[Opl4gpt](https://eprint.iacr.org/2024/1905.pdf)|ASP-DAC 2025|Opl4gpt: An application space exploration of optimal programming language for hardware design by llm|
2024-12-10|[Mage](https://arxiv.org/pdf/2412.07822)|arxiv|Mage: A multi-agent engine for automated rtl code generation|[MAGE](https://github.com/stable-lab/MAGE)
2025-1-6|[Rtlsquad](https://arxiv.org/pdf/2501.05470?)|arxiv|Rtlsquad: Multi-agent based interpretable rtl design|
2025-2-15|[Lintllm](https://arxiv.org/pdf/2502.10815)|arxiv|Lintllm: An open-source verilog linting framework based on large language models|
2025-2-20|[Deeprtl](https://arxiv.org/pdf/2502.15832?)|ICLR 2025|Deeprtl: Bridging verilog understanding and generation with a unified representation model|
2025-3-4|[CircuitEncoder](https://zhiyaoxie.com/files/ASPDAC25_CircuitEncoder.pdf)|ASP-DAC 2025|A self-supervised, pre-trained, and cross-stage-aligned circuit encoder provides a foundation for various design tasks|
2025-3-19|[Openllm-rtl](https://arxiv.org/pdf/2503.15112)|ICCAD 2024|Openllm-rtl: Open dataset and benchmark for llm-aided design rtl generation|
2025-5-4|[Circuitfusion](https://arxiv.org/pdf/2505.02168)|ICLR 2025|Circuitfusion: multimodal circuit representation learning for agile chip design|[CircuitFusion](https://github.com/hkust-zhiyao/CircuitFusion)

</details>

<details><summary><h2 style="display: inline;">Verification & Debug</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;">Security</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;">Architecture</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;">Flow & Layout</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----

</details>

<details><summary><h2 style="display: inline;">Analog</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----

</details>
