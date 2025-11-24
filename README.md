# Awesome-Video-Agent

A curated collection of papers, benchmarks, codebases, and other learning resources for building multimodal **video agents**. Inspired by the style of [Awesome Think With Images](https://github.com/zhaochen0110/Awesome_Think_With_Images), this repository organizes the latest progress on perception, reasoning, and action in video-driven systems.

## Table of Contents
- [Updates](#updates)
- [Scope](#scope)
- [Resource Overview](#resource-overview)
- [Papers](#papers)
- [Benchmarks](#benchmarks)
- [Datasets](#datasets)
- [Frameworks & Tooling](#frameworks--tooling)
- [Tutorials & Courses](#tutorials--courses)
- [Contributing](#contributing)
- [License](#license)

## Updates
- **2024-08-12**: Repository initialized with structure modeled after Awesome Think With Images.

## Scope
This list focuses on resources that help build agents capable of understanding, reasoning over, and acting upon video streams. Relevant topics include:
- Multimodal large language models (MLLMs) that ingest video inputs.
- Video captioning, QA, and temporal reasoning.
- Embodied or tool-using agents leveraging video perception.
- Planning, alignment, and safety for video-based autonomy.

## Resource Overview
Use the following sections as anchors for contributions:
- **Papers**: Novel architectures, training strategies, or agent designs centered on video understanding.
- **Benchmarks**: Public leaderboards or evaluation suites targeting temporal reasoning or agent capabilities.
- **Datasets**: Curated video corpora for supervised, self-supervised, or reinforcement learning.
- **Frameworks & Tooling**: Open-source libraries, model checkpoints, evaluation scripts, and agent stacks.
- **Tutorials & Courses**: Blog posts, walkthroughs, and lecture series focused on building video agents.

## Papers
_Organize papers chronologically (newest first) with concise summaries and links to code if available._

| Paper | Release Date | Github |
| --- | --- | --- |
| [V-ReasonBench: Toward Unified Reasoning Benchmark Suite for Video Generation Models](https://arxiv.org/search/?query=V-ReasonBench%3A+Toward+Unified+Reasoning+Benchmark+Suite+for+Video+Generation+Models&searchtype=all&source=header) | 2025-11 | [yangluo7/V-ReasonBench](https://github.com/yangluo7/V-ReasonBench) |
| [Reasoning via Video: The First Evaluation of Video Models’ Reasoning Abilities through Maze-Solving Tasks](https://arxiv.org/search/?query=Reasoning+via+Video%3A+The+First+Evaluation+of+Video+Models%E2%80%99+Reasoning+Abilities+through+Maze-Solving+Tasks&searchtype=all&source=header) | 2025-11 | [ImYangC7/VR-Bench](https://github.com/ImYangC7/VR-Bench) |
| [Thinking with Video: Video Generation as a Promising Multimodal Reasoning Paradigm](https://arxiv.org/search/?query=Thinking+with+Video%3A+Video+Generation+as+a+Promising+Multimodal+Reasoning+Paradigm&searchtype=all&source=header) | 2025-11 | [tongjingqi/Thinking-with-Video](https://github.com/tongjingqi/Thinking-with-Video) |
| [RETHINKING VISUAL INTELLIGENCE: INSIGHTS FROM VIDEO PRETRAINING](https://arxiv.org/search/?query=RETHINKING+VISUAL+INTELLIGENCE%3A+INSIGHTS+FROM+VIDEO+PRETRAINING&searchtype=all&source=header) | 2025-10 | [PabloAcuaviva/visual-intelligence](https://github.com/PabloAcuaviva/visual-intelligence) |
| [Video models are zero-shot learners and reasoners](https://arxiv.org/search/?query=Video+models+are+zero-shot+learners+and+reasoners&searchtype=all&source=header) | 2025-09 | N/A |
| [VMEvalKit](https://arxiv.org/search/?query=VMEvalKit&searchtype=all&source=header) | 2024-07 | [open-compass/VLMEvalKit](https://github.com/open-compass/VLMEvalKit) |

| Paper | Release Date (arXiv v1) | Github |
| --- | --- | --- |
| [AVATAAR: Agentic Video Answering via Temporal Adaptive Alignment and Reasoning](https://arxiv.org/search/?query=AVATAAR%3A+Agentic+Video+Answering+via+Temporal+Adaptive+Alignment+and+Reasoning&searchtype=all&source=header) | 2025-11 | N/A |
| [Agentic Video Intelligence: A Flexible Framework for Advanced Video Exploration and Understanding](https://arxiv.org/search/?query=Agentic+Video+Intelligence%3A+A+Flexible+Framework+for+Advanced+Video+Exploration+and+Understanding&searchtype=all&source=header) | 2025-11 | N/A |
| [Recurrent Attention-based Token Selection for Efficient Streaming Video-LLMs](https://arxiv.org/search/?query=Recurrent+Attention-based+Token+Selection+for+Efficient+Streaming+Video-LLMs&searchtype=all&source=header) | 2025-10 | N/A |
| [VTimeCoT: Thinking by Drawing for Video Temporal Grounding and Reasoning](https://arxiv.org/search/?query=VTimeCoT%3A+Thinking+by+Drawing+for+Video+Temporal+Grounding+and+Reasoning&searchtype=all&source=header) | 2025-10 | N/A |
| [CAViAR: Critic-Augmented Video Agentic Reasoning](https://arxiv.org/search/?query=CAViAR%3A+Critic-Augmented+Video+Agentic+Reasoning&searchtype=all&source=header) | 2025-09 | N/A |
| [VideoForest: Person-Anchored Hierarchical Reasoning for Cross-Video Question Answering](https://arxiv.org/search/?query=VideoForest%3A+Person-Anchored+Hierarchical+Reasoning+for+Cross-Video+Question+Answering&searchtype=all&source=header) | 2025-08 | N/A |
| [VideoDeepResearch: Long Video Understanding With Agentic Tool Using](https://arxiv.org/abs/2506.05936) | 2025-06 | [yhy-2000/VideoDeepResearch](https://github.com/yhy-2000/VideoDeepResearch) |
| [Re-thinking Temporal Search for Long-Form Video Understanding](https://arxiv.org/search/?query=Re-thinking+Temporal+Search+for+Long-Form+Video+Understanding&searchtype=all&source=header) | 2025-06 | [longvideohaystack/tstar](https://github.com/longvideohaystack/tstar) |
| [ReAgent-V: A Reward-Driven Multi-Agent Framework for Video Understanding](https://arxiv.org/search/?query=ReAgent-V%3A+A+Reward-Driven+Multi-Agent+Framework+for+Video+Understanding&searchtype=all&source=header) | 2025-06 | N/A |
| [Deep Video Discovery: Agentic Search with Tool Use for Long-form Video Understanding](https://arxiv.org/search/?query=Deep+Video+Discovery%3A+Agentic+Search+with+Tool+Use+for+Long-form+Video+Understanding&searchtype=all&source=header) | 2025-05 | [microsoft/DeepVideoDiscovery](https://github.com/microsoft/DeepVideoDiscovery) |
| [ViQAgent: Zero-Shot Video Question Answering via Agent with Open-Vocabulary Grounding Validation](https://arxiv.org/search/?query=ViQAgent%3A+Zero-Shot+Video+Question+Answering+via+Agent+with+Open-Vocabulary+Grounding+Validation&searchtype=all&source=header) | 2025-05 | N/A |
| [DrVideo: Document Retrieval Based Long Video Understanding](https://arxiv.org/abs/2505.03817) | 2025-05 | [Upper9527/DrVideo](https://github.com/Upper9527/DrVideo) |
| [MR. Video: “MapReduce” is the Principle for Long Video Understanding](https://arxiv.org/search/?query=MR.+Video%3A+%E2%80%9CMapReduce%E2%80%9D+is+the+Principle+for+Long+Video+Understanding&searchtype=all&source=header) | 2025-04 | [ziqipang/MR-Video](https://github.com/ziqipang/MR-Video) |
| [VideoAgent2: Enhancing the LLM-Based Agent System for Long-Form Video Understanding by Uncertainty-Aware CoT](https://arxiv.org/search/?query=VideoAgent2%3A+Enhancing+the+LLM-Based+Agent+System+for+Long-Form+Video+Understanding+by+Uncertainty-Aware+CoT&searchtype=all&source=header) | 2025-04 | N/A |
| [Agentic Keyframe Search for Video Question Answering](https://arxiv.org/search/?query=Agentic+Keyframe+Search+for+Video+Question+Answering&searchtype=all&source=header) | 2025-03 | [fansunqi/AKeyS](https://github.com/fansunqi/AKeyS) |
| [LVAgent: Long Video Understanding by Multi-Round Dynamical Collaboration of MLLM Agents](https://arxiv.org/abs/2503.01928) | 2025-03 | [64327069/LVAgent](https://github.com/64327069/LVAgent) |
| [AVA: Towards Agentic Video Analytics with Vision Language Models](https://arxiv.org/abs/2503.01556) | 2025-03 | [I-ESC/Project-Ava](https://github.com/I-ESC/Project-Ava) |
| [VCA: Video Curious Agent for Long Video Understanding](https://arxiv.org/search/?query=VCA%3A+Video+Curious+Agent+for+Long+Video+Understanding&searchtype=all&source=header) | 2024-12 | N/A |
| [VideoTree: Adaptive Tree-based Video Representation for LLM Reasoning on Long Videos](https://arxiv.org/abs/2405.05322) | 2024-05 | [Ziyang412/VideoTree](https://github.com/Ziyang412/VideoTree) |
| [MoReVQA: Exploring Modular Reasoning Models for Video Question Answering](https://arxiv.org/search/?query=MoReVQA%3A+Exploring+Modular+Reasoning+Models+for+Video+Question+Answering&searchtype=all&source=header) | 2024-04 | N/A |
| [Chain-of-Frames: Advancing Video Understanding in Multimodal LLMs via Frame-Aware Reasoning](https://arxiv.org/search/?query=Chain-of-Frames%3A+Advancing+Video+Understanding+in+Multimodal+LLMs+via+Frame-Aware+Reasoning&searchtype=all&source=header) | 2024-03 | [SaraGhazanfari/CoF](https://github.com/SaraGhazanfari/CoF) |
| [VideoAgent: A Memory-augmented Multimodal Agent for Video Understanding](https://arxiv.org/search/?query=VideoAgent%3A+A+Memory-augmented+Multimodal+Agent+for+Video+Understanding&searchtype=all&source=header) | 2024-03 | [YueFan1014/VideoAgent](https://github.com/YueFan1014/VideoAgent) |
| [VideoAgent: Long-form Video Understanding with Large Language Model as Agent](https://arxiv.org/search/?query=VideoAgent%3A+Long-form+Video+Understanding+with+Large+Language+Model+as+Agent&searchtype=all&source=header) | 2024-03 | [wxh1996/VideoAgent](https://github.com/wxh1996/VideoAgent) |
| [StreamAgent: Towards Anticipatory Agents for Streaming Video Understanding](https://arxiv.org/search/?query=StreamAgent%3A+Towards+Anticipatory+Agents+for+Streaming+Video+Understanding&searchtype=all&source=header) | 2024-02 | [YuruiAI/DistillDrive](https://github.com/YuruiAI/DistillDrive) |

## Benchmarks
_List benchmarks with key metrics, task coverage, and official evaluation scripts._
- TBD

## Datasets
_Describe dataset scale, modality, licensing, and download links._
- TBD

## Frameworks & Tooling
_Highlight libraries, agents, or reference implementations for video understanding and decision-making._
- TBD

## Tutorials & Courses
_Add learning materials such as blog posts, tutorials, and lecture notes._
- TBD

## Contributing
Contributions are welcome! To add a resource:
1. Open a pull request with a clear title and short description of the change.
2. Place new entries in the appropriate section, sorted newest-first where applicable.
3. Include links to papers, code, and official assets, and note licenses when relevant.

## License
This project is licensed under the [MIT License](LICENSE) unless otherwise noted by individual resources.
