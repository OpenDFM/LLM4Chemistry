## LLM4Chemistry

<a>
  <a href="https://arxiv.org/abs/2412.19994">
  <img alt="Static Badge" src="https://img.shields.io/badge/arxiv-2412.19994-blue">
</a>
This repository collects papers on Large Language Model for Chemistry.

> 😎 Welcome to recommend missing papers through Adding Issues or Pull Requests.

## Contents

- [Large Language Model for Chemistry (LLM4Chemistry)](#llm4chemistry)
  - [Contents](#contents)
  - [Fine-tuning LLM for Chemistry](#fine-tuning-llm-for-chemistry)
  - [Multi-Modal Chemistry LLM](#multi-modal-chemistry-llm)
  - [LLM as A Chemistry Agent](#llm-as-a-chemistry-llm)
  - [LLM Chemistry Benchmark](#llm-chemistry-benchmark)
  - [Related Works](#related-works)

### Fine-tuning LLM for Chemistry

- `2022.05` Foundation Models of Scientific Knowledge for Chemistry: Opportunities, Challenges and Lessons Learned. [ACL Workshop](https://aclanthology.org/2022.bigscience-1.12.pdf)
- `2022.11` Galactica: A large language model for science. [arXiv](https://arxiv.org/abs/2211.09085)
- `2022.11` Is GPT-3 all you need for machine learning for chemistry? [NIPS2022 Workshop](https://openreview.net/pdf?id=dgpgTEZ6G__)
- `2023.08` Fine-tuning GPT-3 for machine learning electronic and functional properties of organic molecules. [Chemical Science](https://pubs.rsc.org/en/content/articlepdf/2024/sc/d3sc04610a)
- `2023.08` HoneyBee: Progressive Instruction Finetuning of Large Language Models for Materials Science. [EMNLP2023](https://aclanthology.org/2023.findings-emnlp.380.pdf)
- `2023.10` MatChat: A Large Language Model and Application Service Platform for Materials Science. [Chinese Physics B](https://arxiv.org/abs/2310.07197)
- `2024.01` ChemDFM: Dialogue Foundation Model for Chemistry. [arXiv](https://arxiv.org/abs/2401.14818)
- `2024.01` Structured information extraction from scientific text with large language models. [Nature Communication](https://www.nature.com/articles/s41467-024-45563-x)
- `2024.02` Leveraging large language models for predictive chemistry. [Nature Machine Intelligence](https://www.nature.com/articles/s42256-023-00788-1)
- `2024.03` SciGLM: Training Scientific Language Models with Self-Reflective Instruction Annotation and Tuning. [arXiv](https://arxiv.org/abs/2401.07950)
- `2024.03` Domain-Agnostic Molecular Generation with Chemical Feedback. [ICLR2024](https://arxiv.org/pdf/2301.11259)
- `2024.04` ChemLLM: A Chemical Large Language Model. [arXiv](https://arxiv.org/abs/2402.06852)
- `2024.04` BatGPT-Chem: A Foundation Large Model For Chemical Engineering. [chemRxiv](https://chemrxiv.org/engage/chemrxiv/article-details/661df07a418a5379b0ef8906)
- `2024.04` Mol-Instructions: A Large-Scale Biomolecular Instruction Dataset for Large Language Models. [ICLR2024](https://openreview.net/forum?id=Tlsdsb6l9n)
- `2024.04` LlaSMol: Advancing Large Language Models for Chemistry with a Large-Scale, Comprehensive, High-Quality Instruction Tuning Dataset. [arXiv](https://arxiv.org/abs/2402.09391)
- `2024.05` nach0: Multimodal Natural and Chemical Languages Foundation Model. [Chemical Science](https://arxiv.org/pdf/2311.12410)
- `2024.06` Fine-tuning large language models for chemical text mining. [Chemical Science](https://pubs.rsc.org/en/content/articlehtml/2024/sc/d4sc00924j)
- `2024.06` MolecularGPT: Open Large Language Model (LLM) for Few-Shot Molecular Property Prediction. [arXiv](https://arxiv.org/pdf/2406.12950v1)
- `2024.06` SynAsk: Unleashing the Power of Large Language Models in Organic Synthesis. [arXiv](https://arxiv.org/pdf/2406.04593)
- `2024.06` PRESTO: Progressive Pretraining Enhances Synthetic Chemistry Outcomes. [arXiv](https://arxiv.org/pdf/2406.13193)
- `2024.09` SciDFM: A Large Language Model with Mixture-of-Experts for Science. [arXiv](https://arxiv.org/pdf/2409.18412)

### Multi-Modal Chemistry LLM

- `2023.03` Uni-Mol: A Universal 3D Molecular Representation Learning Framework. [ICLR](https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/6402990d37e01856dc1d1581/original/uni-mol-a-universal-3d-molecular-representation-learning-framework.pdf)
- `2023.05` DrugChat: Towards Enabling ChatGPT-Like Capabilities on Drug Molecule Graphs. [arXiv](https://arxiv.org/pdf/2309.03907)
- `2023.06` MolCA: Molecular Graph-Language Modeling with Cross-Modal Projector and Uni-Modal Adapter. [EMNLP2023](https://aclanthology.org/2023.emnlp-main.966/)
- `2023.06` MolFM: A Multimodal Molecular Foundation Model. [arXiv](https://arxiv.org/pdf/2307.09484)
- `2023.08` BioMedGPT: Open Multimodal Generative Pre-trained Transformer for BioMedicine. [arXiv](https://arxiv.org/pdf/2308.09442)
- `2023.09` 3D-MOLM: TOWARDS 3D MOLECULE-TEXT INTERPRETATION IN LANGUAGE MODELS. [ICLR2024](https://openreview.net/forum?id=xI4yNlkaqh)
- `2023.11` InstructMol: Multi-Modal Integration for Building a Versatile and Reliable Molecular Assistant in Drug Discovery. [arXiv](https://arxiv.org/pdf/2311.16208)
- `2023.12` MoleculeGPT: Instruction Following Large Language Models for Molecular Property Prediction. [NIPS Workshop](https://ai4d3.github.io/papers/34.pdf)
- `2024.01` MolTC: Towards Molecular Relational Modeling In Language Models [ACL2024](https://arxiv.org/pdf/2402.03781)
- `2024.01` ReactXT: Understanding Molecular “Reaction-ship” viaReaction-Contextualized Molecule-Text Pretraining. [ACL2024](https://arxiv.org/pdf/2405.14225)
- `2024.03` GIT-Mol: A multi-modal large language model for molecular science with graph, image, and text. [arXiv](https://arxiv.org/pdf/2308.06911)
- `2024.06` HIGHT: Hierarchical Graph Tokenization for Graph-Language Alignment. [arXiv](https://arxiv.org/pdf/2406.14021)
- `2024.06` 3D-MolT5: Towards Unified 3D Molecule-Text Modeling with 3D Molecular Tokenization. [arXiv](https://arxiv.org/pdf/2406.05797)
- `2024.06` MolX: Enhancing Large Language Models for Molecular Learning with A Multi-Modal Extension. [arXiv](https://arxiv.org/pdf/2406.06777)
- `2024.07` MolLM: a unified language model for integrating biomedical text with 2D and 3D molecular representations. [Bioinformatics](https://academic.oup.com/bioinformatics/article/40/Supplement_1/i357/7700902)
- `2024.08` UniMoT: Unified Molecule-Text Language Model with Discrete Token Representation. [arXiv](https://arxiv.org/pdf/2408.00863)
- `2024.08` ChemVLM: Exploring the Power of Multimodal Large Language Models in Chemistry Area. [arXiv](https://arxiv.org/abs/2408.07246)
- `2024.09` ChemDFM-X: Towards Large Multimodal Model for Chemistry. [arXiv](https://arxiv.org/pdf/2409.13194)

### LLM as A Chemistry Agent

- `2023.09` Generative Retrieval-Augmented Ontologic Graph and Multiagent Strategies for Interpretive Large Language Model-Based Materials Design. [ACS Engineering Au](https://pubs.acs.org/doi/10.1021/acsengineeringau.3c00058)
- `2023.10` Large language models for chemistry robotics. [Autonomous Robots](https://doi.org/10.1007/s10514-023-10136-2)
- `2023.10` Monte Carlo Thought Search: Large Language Model Querying for Complex Scientific Reasoning in Catalyst Design. [EMNLP2023](https://arxiv.org/pdf/2310.14420)
- `2023.11` Chemist-X: Large Language Model-empowered Agent for Reaction Condition Recommendation in Chemical Synthesis. [arXiv](https://arxiv.org/abs/2311.10776)
- `2023.12` Autonomous chemical research with large language models. [Nature](https://www.nature.com/articles/s41586-023-06792-0)
- `2024.01` Structured Chemistry Reasoning with Large Language Models. [ICML2024](https://openreview.net/pdf/c5751a6913a0d8e993413d692b638af70ee7f2bd.pdf)
- `2024.01` ChemReasoner: Heuristic Search over a Large Language Model's Knowledge Space using Quantum-Chemical Feedback. [ICML2024](https://arxiv.org/abs/2402.10980)
- `2024.02` An Autonomous Large Language Model Agent for Chemical Literature Data Mining. [arXiv](https://arxiv.org/abs/2402.12993)
- `2024.03` From Artificially Real to Real: Leveraging Pseudo Data from Large Language Models for Low-Resource Molecule Discovery. [AAAI2024](https://arxiv.org/pdf/2309.05203)
- `2024.03` DRAK: Unlocking Molecular Insights with Domain-Specific Retrieval-Augmented Knowledge in LLMs. [arXiv](https://arxiv.org/pdf/2406.18535)
- `2024.04` Integrating Chemistry Knowledge in Large Language Models via Prompt Engineering. [arXiv](https://arxiv.org/pdf/2404.14467)
- `2024.04` Large Language Models are In-Context Molecule Learners. [arXiv](https://arxiv.org/pdf/2403.04197)
- `2024.04` A Self-feedback Knowledge Elicitation Approach for Chemical Reaction Predictions. [arXiv](https://arxiv.org/pdf/2404.09606)
- `2024.04` Large Language Models Open New Way of AI-Assisted Molecule Design for Chemists. [ChemRxiv](https://chemrxiv.org/engage/chemrxiv/article-details/66220456418a5379b0297f8d)
- `2024.05` Augmenting large language models with chemistry tools. [Nature Machine Intelligence](https://www.nature.com/articles/s42256-024-00832-8)
- `2024.05` ChatMOF: an artificial intelligence system for predicting and generating metal-organic frameworks using large language models. [Nature Communications](https://www.nature.com/articles/s41467-024-48998-4)
- `2024.06` LLaMP: Large Language Model Made Powerful for High-fidelity Materials Knowledge Retrieval and Distillation. [arXiv](https://arxiv.org/pdf/2401.17244)


### LLM Chemistry Benchmark

- `2017.09` Crowdsourcing multiple choice science questions. [ACL Workshop](https://aclanthology.org/W17-4413.pdf)
- `2020.09` ChemistryQA: A Complex Question Answering Dataset from Chemistry. [OpenReview](https://openreview.net/pdf?id=oeHTRAehiFF)
- `2023.01` Assessment of chemistry knowledge in large language models that generate code. [Digital Discovery](https://pubs.rsc.org/en/content/articlelanding/2023/dd/d2dd00087c)
- `2023.03` Do Large Language Models Understand Chemistry? A Conversation with ChatGPT. [Journal of Chemical Information and Modeling](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00285)
- `2023.06` Empowering Molecule Discovery for Molecule-Caption Translation with Large Language Models: A ChatGPT Perspective. [TKDE](https://arxiv.org/abs/2306.06615)
- `2023.07` Can Large Language Models Empower Molecular Property Prediction? [arXiv](https://arxiv.org/pdf/2307.07443)
- `2023.10` ReLM: Leveraging Language Models for Enhanced Chemical Reaction Prediction. [arXiv](https://arxiv.org/pdf/2310.13590)
- `2023.10` GPT-MolBERTa: GPT Molecular Features Language Model for molecular property. [arXiv](https://arxiv.org/pdf/2310.03030)
- `2023.12` What can Large Language Models do in chemistry? A comprehensive benchmark on eight tasks. [NeurIPS2023](https://arxiv.org/abs/2305.18365)
- `2023.12` SciMT-Safety: Control Risk for Potential Misuse of Artificial Intelligence in Science. [arXiv](https://arxiv.org/abs/2312.06632)
- `2024.01` SciEval: A Multi-Level Large Language Model Evaluation Benchmark for Scientific Research. [AAAI2024](https://ojs.aaai.org/index.php/AAAI/article/view/29872/31521)
- `2024.01` SciAssess: Benchmarking LLM Proficiency in Scientific Literature Analysis. [arXiv](https://arxiv.org/abs/2403.01976)
- `2024.02` Scientific Language Modeling: A Quantitative Review of Large Language Models in Molecular Science. [arXiv](https://arxiv.org/pdf/2402.04119)
- `2024.02` Building a Dataset for Language+Molecules. [arXiv](https://arxiv.org/pdf/2403.00791)
- `2024.03` Benchmarking Large Language Models for Molecule Prediction Tasks. [arXiv](https://arxiv.org/abs/2403.05075)
- `2024.03` MoleculeQA: A Dataset to Evaluate Factual Accuracy in Molecular Comprehension. [arXiv](https://arxiv.org/pdf/2403.08192)
- `2024.03` Benchmarking Large Language Models for Molecule Prediction Tasks. [arXiv](https://arxiv.org/pdf/2403.05075)
- `2024.02` SciBench: Evaluating College-Level Scientific Problem-Solving Abilities of Large Language Models. [arXiv](https://arxiv.org/abs/2307.10635)
- `2024.04` Are large language models superhuman chemists? [arXiv](https://arxiv.org/pdf/2404.01475)
- `2024.06` SciKnowEval: Evaluating Multi-level Scientific Knowledge of Large Language Models. [arXiv](https://arxiv.org/pdf/2406.09098)
- `2024.07` ScholarChemQA: Unveiling the Power of Language Models in Chemical Research Question Answering. [arXiv](https://arxiv.org/pdf/2407.16931v1)
- `2024.09` VisScience: An Extensive Benchmark for Evaluating K12 Educational Multi-modal Scientific Reasoning. [arXiv](https://arxiv.org/pdf/2409.13730)
- `2024.09` ChemEval: A Comprehensive Multi-Level Chemical Evalution for Large Language Models. [arXiv](https://arxiv.org/pdf/2409.13989)
- `2024.10` Unraveling Molecular Structure: A Multimodal Spectroscopic Dataset for Chemistry. [NIPS2024](https://arxiv.org/abs/2407.17492)
- `2024.10` MassSpecGym: A benchmark for the discovery and  identification of molecules. [NIPS2024](https://arxiv.org/abs/2410.23326)
- `2024.10` Can LLMs Solve Molecule Puzzles? A Multimodal Benchmark for Molecular Structure Elucidation. [NIPS2024](https://kehanguo2.github.io/Molpuzzle.io/paper/SpectrumLLM__Arxiv_.pdf)
- `2024.10` DFT: A Universal Quantum Chemistry Dataset of Drug-Like Molecules and a Benchmark for Neural Network Potentials. [NIPS2024](https://arxiv.org/pdf/2406.14347)
- `2024.12` TOMG-Bench: Evaluating LLMs on Text-based Open Molecule Generation. [arXiv](https://arxiv.org/pdf/2412.14642)

### Related Works

- `2023.04` A Systematic Survey of Chemical Pre-trained Models. [IJCAI2023](https://www.ijcai.org/proceedings/2023/0760.pdf)
- `2023.09` Large Language Models in Molecular Discovery. [NIPS2023 Workshop](https://neurips.cc/virtual/2023/75777)
- `2024.01` Scientific Large Language Models: A Survey on Biological & Chemical Domains. [arXiv](https://arxiv.org/abs/2401.14656)
- `2024.01` From Words to Molecules: A Survey of Large Language Models in Chemistry. [IJCAI2024](https://arxiv.org/pdf/2402.01439)
- `2024.03` Bridging Text and Molecule: A Survey on Multimodal Frameworks for Molecule. [arXiv](https://arxiv.org/pdf/2403.13830)
- `2024.03` Leveraging Biomolecule and Natural Language through Multi-Modal Learning: A Survey. [arXiv](https://arxiv.org/pdf/2403.01528)
- `2024.06` A Comprehensive Survey of Scientific Large Language Models and Their Applications in Scientific Discovery. [arXiv](https://arxiv.org/pdf/2406.10833)
- `2024.07` A Review of Large Language Models and Autonomous Agents in Chemistry. [arXiv](https://arxiv.org/pdf/2407.01603)
