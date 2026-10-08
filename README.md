<div align="center">

<h1>FinCon</h1>

<p><b>A Synthesized LLM Multi-Agent System with Conceptual Verbal Reinforcement for Enhanced Financial Decision Making</b></p>

[![arXiv](https://img.shields.io/badge/arXiv-2407.06567-b31b1b.svg)](https://arxiv.org/abs/2407.06567)
[![NeurIPS 2024](https://img.shields.io/badge/NeurIPS-2024-blue.svg)](https://arxiv.org/abs/2407.06567)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

<a href="https://arxiv.org/abs/2407.06567">Paper</a>

</div>

## Overview

FinCon is an LLM-based multi-agent framework with **con**ceptual verbal reinforcement for diverse **fin**ancial tasks. Inspired by the organizational structure of real-world investment firms, it uses a manager–analyst communication hierarchy, and a risk-control component episodically triggers self-critique to update systematic investment beliefs, which are propagated as verbal reinforcement to the agents that need them. FinCon is evaluated on financial tasks including single-stock trading and portfolio management.

## Code Release Status

We apologize for the delay in open-sourcing this project.
Our data agent currently relies on several commercial APIs, which makes it challenging to release the full system and associated data directly.
We are actively working on de-anonymizing and restructuring the components, and plan to release the code within the next 3–4 months.

While we are preparing the open-source release of this project, please feel free to explore our single-agent projects below, where we have open-sourced the full codebase and the majority of the dataset. They support rapid deployment for verification and experimentation.

## Related Open-Source Projects

### 1. InvestorBench

This project introduces key design principles for LLM-based single-agent systems tailored to trading tasks. We also systematically benchmark the performance of different LLMs across a range of trading tasks.

🚀 **InvestorBench has been accepted by ACL 2025 Main** · [Paper](https://aclanthology.org/2025.acl-long.126/) · [Code](https://github.com/felis33/INVESTOR-BENCH)

```bibtex
@inproceedings{li-etal-2025-investorbench,
    title = "{INVESTORBENCH}: A Benchmark for Financial Decision-Making Tasks with {LLM}-based Agent",
    author = "Li, Haohang and Cao, Yupeng and Yu, Yangyang and Javaji, Shashidhar Reddy and Deng, Zhiyang and He, Yueru and Jiang, Yuechen and Zhu, Zining and Subbalakshmi, Koduvayur and Xiong, Guojun and others",
    booktitle = "Proceedings of the 63rd Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers)",
    month = jul,
    year = "2025",
    address = "Vienna, Austria",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.acl-long.126/",
    doi = "10.18653/v1/2025.acl-long.126",
    pages = "2509--2525",
    ISBN = "979-8-89176-251-0"
}
```

### 2. Agent Market Arena (AMA)

This is a testbed environment for testing and evaluating trading agents. The testbed provides a standardized framework for wrapping agents as HTTP endpoints and calling them for trading decisions.

🚀 **AMA has been accepted by WWW 2026** · [Paper](https://arxiv.org/abs/2510.11695) · [Code](https://github.com/The-FinAI/Agent_Market_Arena) · [Live Arena](https://huggingface.co/spaces/TheFinAI/Agent-Market-Arena)

```bibtex
@article{qian2025agents,
  title={When agents trade: Live multi-market trading benchmark for llm agents},
  author={Qian, Lingfei and Peng, Xueqing and Wang, Yan and Zhang, Vincent Jim and He, Huan and Smith, Hanley and Han, Yi and He, Yueru and Li, Haohang and Cao, Yupeng and others},
  journal={arXiv preprint arXiv:2510.11695},
  year={2025}
}
```

## Citation

If you find FinCon useful, we would appreciate it if you consider citing our work:

```bibtex
@article{yu2024fincon,
  title={Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making},
  author={Yu, Yangyang and Yao, Zhiyuan and Li, Haohang and Deng, Zhiyang and Jiang, Yuechen and Cao, Yupeng and Chen, Zhi and Suchow, Jordan and Cui, Zhenyu and Liu, Rong and others},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={137010--137045},
  year={2024}
}
```

## License

The code in this repository is released under the [MIT License](LICENSE). Datasets and models on Hugging Face keep their own licenses, stated on each card.

---

<div align="center">

Built by [The Fin AI](https://thefin.ai) · [Hugging Face](https://huggingface.co/TheFinAI) · [GitHub](https://github.com/The-FinAI)

</div>
