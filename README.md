# FEDKIM

This is the repo of resource codes for FEDKIM. The implementation is heavily based on codes provided by the authors of [Octavius](https://arxiv.org/abs/2311.02684). 

## Data Preparation

Please refer our [NeurIPS benchmark paper](https://github.com) for the preparation of data. More details can also be found at corresponding [repo](https://github.com/psudslab/FEDMEKI).


## MOE Implementation 

The implementation of our proposed M<sub>3</sub>OE module is available at the [link](https://github.com/XiaochenWang-PSU/FedKIM/blob/master/FedKIM/src/model/Octavius/moe/layer.py). 


## Acknowledgement 

If you find any sources provided in this repo or our paper are useful, please cite our paper using:

```bibtex
@inproceedings{wangfedmeki,
  title={FEDMEKI: A Benchmark for Scaling Medical Foundation Models via Federated Knowledge Injection},
  author={Wang, Jiaqi and Wang, Xiaochen and Lyu, Lingjuan and Chen, Jinghui and Ma, Fenglong},
  booktitle={The Thirty-eight Conference on Neural Information Processing Systems Datasets and Benchmarks Track}
}
```
```bibtex
@inproceedings{wang2024fedkim,
  title={FEDKIM: Adaptive Federated Knowledge Injection into Medical Foundation Models},
  author={Wang, Xiaochen and Wang, Jiaqi and Xiao, Houping and Chen, Jinghui and Ma, Fenglong},
  booktitle={Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing},
  pages={8141--8154},
  year={2024}
}
```
