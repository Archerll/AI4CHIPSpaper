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
            |                                                              |              |                                                              |                                                        
            |                                                              |              |                                                              |                                                        

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

​	</details>

<details><summary><h2 style="display: inline;">Architecture</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2023-06-12|[LCDA](https://arxiv.org/pdf/2306.06923)|arxiv|On the viability of using LLMs for SW/HW co-design: An example in designing CiM DNN accelerators.|
2023-07-17|[QGAS](https://arxiv.org/pdf/2307.08191)|arxiv|Unleashing the potential of LLMs for quantum computing: A study in quantum architecture design|
2023-9-19|[GPT4AIGChip](https://arxiv.org/pdf/2309.10730)🔥|ICCAD 2023|GPT4AIGChip: Towards next-generation AI accelerator design automation via large language models.|
2024-1-24|[SpecLLM](https://arxiv.org/pdf/2401.13266)|arxiv|SpecLLM: Exploring generation and review of vlsi design specification with large language model.|

</details>

<details><summary><h2 style="display: inline;">Flow & Layout</h2></summary>

Date|Method|Conference|Paper Title and Paper Interpretation (In Chinese)|Code
-----|----|-----|-----|-----
2023-08| ChatEDA [216]                                                | MLCAD 2023 | Chateda: A large language model powered autonomous agent for eda | [ChatEDAv1](https://github.com/wuhy68/ChatEDAv1) 
 2024-07    | RAG-EDA                                                      |            | Customized retrieval augmented generation and benchmarking for eda tool documentation qa | [RAG-EDA](https://github.com/lesliepy99/RAG-EDA) 
 2024-12    | ChipAlign [221]                                              |            | Chipalign: Instruction alignment in large language models for chip design via geodesic interpolation |                                                  
 2024-05-24 | [LLM4Scldof](https://arxiv.org/pdf/2406.06549?)              | LAD 2024   | Large language model (llm) for standard cell layout design optimization |                                                  
 2024-07-15 | [FabGPT](https://arxiv.org/pdf/2407.10810?)                  | ICCAD 2024 | Fabgpt: An efficient large multimodal model for complex wafer defect knowledge queries |                                                  
 2024-08-24 | two-[stage](https://ojs.aaai.org/index.php/AAAI/article/view/34479) | AAAI 2024  | Intelligent opc engineer assistant for semiconductor manufacturing |                                                  
 2024-11-28 | DRC-[Coder](https://dl.acm.org/doi/pdf/10.1145/3698364.3705347) | arxiv      | Drc-coder: Automated drc checker code generation using llm autonomous agent |                                                  

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
2025-02-28|[AnalogGenie](https://arxiv.org/pdf/2503.00205)|ICLR 2025|Analoggenie: A generative engine for automatic discovery of analog circuit topologies|[AnalogGenie](https://github.com/xz-group/AnalogGenie)

</details>
