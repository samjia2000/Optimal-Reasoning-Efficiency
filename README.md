# Optimal-Reasoning-Efficiency

In this work, we introduce the *reasoning efficiency frontiers*, empirical upper bounds derived from fine-tuning base LRMs (DeepSeek-R1-Distill-Qwen-1.5B/7B and Qwen3-4B/8B) across diverse approaches and training configurations. Our major contributions are:

- **REG (Reasoning Efficiency Gap)**: an unified metric that measures the gap of a fine-tuned LRM to the efficiency frontiers.
- **REO-RL**: a class of RL algorithms that minimizes the efficiency gap by improving rewards under a sparse set of token budgets.

# Reasoning Efficiency Frontiers

We evaluate the reasoning efficiency frontiers for DeepSeek-R1-Distill-Qwen-1.5B/7B and Qwen3-4B/8B on four mathematical reasoning benchmarks: AMC 2023, AIME 2024\&2025, and Minerva Math. These frontiers are provided in [data/frontiers](data/frontiers).

# TODO

- [x] Efficiency Frontiers
- [ ] Evaluation Scripts for REG
- [ ] REO-RL Implementation

# Citation


```
@misc{gao2025faroptimalreasoningefficiency,
      title={How Far Are We from Optimal Reasoning Efficiency?}, 
      author={Jiaxuan Gao and Shu Yan and Qixin Tan and Lu Yang and Shusheng Xu and Wei Fu and Zhiyu Mei and Kaifeng Lyu and Yi Wu},
      year={2025},
      eprint={2506.07104},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2506.07104}, 
}
```