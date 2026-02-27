# FinCon


## Citation
If you find FinCon useful, we would appreciate it if you consider citing our work:
```md
@article{yu2024fincon,
  title={Fincon: A synthesized llm multi-agent system with conceptual verbal reinforcement for enhanced financial decision making},
  author={Yu, Yangyang and Yao, Zhiyuan and Li, Haohang and Deng, Zhiyang and Jiang, Yuechen and Cao, Yupeng and Chen, Zhi and Suchow, Jordan and Cui, Zhenyu and Liu, Rong and others},
  journal={Advances in Neural Information Processing Systems},
  volume={37},
  pages={137010--137045},
  year={2024}
}
```

## Code
We apologize for the delay in open-sourcing this project.<br>
Our data agent currently relies on several commercial APIs, which makes it challenging to release the full system and associated data directly.<br>
We are actively working on de-anonymizing and restructuring the components, and plan to release the code within the next 3–4 months.<br>

While we are preparing the open-source release of this project, please feel free to explore our Single-Agent projects, where we have open-sourced the full codebase and the majority of the dataset. It supports rapid deployment for verification and experimentation.

### 1. InvestorBench
This project introduces key design principles for LLM-based single-agent systems tailored to trading tasks. We also systematically benchmark the performance of different LLMs across a range of trading tasks.<br>

🚀 **InvestorBench has been accepted by ACL 2025 main ([Paper](https://aclanthology.org/2025.acl-long.126/)) ([Code](https://github.com/felis33/INVESTOR-BENCH)) <br>**

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
This is a testbed environment for testing and evaluating trading agents. The testbed provides a standardized framework for wrapping agents as HTTP endpoints and calling them for trading decisions.<br>

🚀 **AMA has been accepted by WWW 2026 ([Paper](https://arxiv.org/pdf/2510.11695)) ([Code](https://github.com/The-FinAI/Agent_Market_Arena)) <br>**
```bibtex
@article{qian2025agents,
  title={When agents trade: Live multi-market trading benchmark for llm agents},
  author={Qian, Lingfei and Peng, Xueqing and Wang, Yan and Zhang, Vincent Jim and He, Huan and Smith, Hanley and Han, Yi and He, Yueru and Li, Haohang and Cao, Yupeng and others},
  journal={arXiv preprint arXiv:2510.11695},
  year={2025}
}
```
