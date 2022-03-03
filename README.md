# AMR parsing paper collection

In this page we collect papers about English AMR parsing in recent years(2019-2022). Papers count table is as follow:

| Year  |  ACL  | NAACL | AAAI  | IJCAI | EMNLP | COLING | TKDE  | NeurIPS | total |
| :---: | :---: | :---: | :---: | :---: | :---: | :----: | :---: | :-----: | :---: |
| 2022  |   -   |   -   |   -   |   -   |   -   |   -    |   0   |    -    |   0   |
| 2021  |   0   |   1   |   1   |   0   |   2   |   -    |   0   |    1    |   5   |
| 2020  |   2   |   -   |   0   |   0   |   1   |   0    |   0   |    0    |   3   |
| 2019  |   3   |   0   |   0   |   1   |   1   |   -    |   0   |    0    |   5   |
|       |
| total |   5   |   1   |   1   |   1   |   4   |   0    |   0   |    1    |  13   |

Grids marked with a '-' indicates the conference is not yet started, not held in that year, or proceedings is not yet available.

## Paper Collection

### 2022

nothing here yet...

### 2021

- EMNLP 2021: Structure-aware Fine-tuning of Sequence-to-sequence Transformers for Transition-based AMR Parsing.\[[paper](https://aclanthology.org/2021.emnlp-main.507.pdf)\]
- EMNLP 2021: A Differentiable Relaxation of Graph Segmentation and Alignment for AMR Parsing.\[[paper](https://aclanthology.org/2021.emnlp-main.714.pdf)\]
- NAACL 2021: AMR Parsing with Action-Pointer Transformer.[[paper](https://aclanthology.org/2021.naacl-main.443.pdf)]
- NeurIPS 2021: Ensembling Graph Predictions for AMR Parsing[[paper](https://proceedings.neurips.cc//paper/2021/file/479b4864e55e12e0fb411eadb115c095-Paper.pdf)][[code](https://github.com/ibm/graph_ensemble_learning)]
- AAAI 2021: One SPRING to Rule Them Both: Symmetric AMR Semantic Parsing and Generation without a Complex Pipeline[[paper](https://ojs.aaai.org/index.php/AAAI/article/view/17489/17296)][[code](https://github.com/SapienzaNLP/spring)]

### 2020

- EMNLP 2020: Improving AMR Parsing with Sequence-to-Sequence Pre-training.[[paper](https://aclanthology.org/2020.emnlp-main.196.pdf)][[code](https://github.com/xdqkid/S2S-AMR-Parser)]
- ACL 2020: AMR Parsing via Graph-Sequence Iterative Inference.[[paper](https://aclanthology.org/2020.acl-main.119.pdf)][[code](https://github.com/jcyk/AMR-gs)]
- ACL 2020: AMR Parsing with Latent Structural Information.[[paper](https://aclanthology.org/2020.acl-main.397.pdf)]

### 2019

- EMNLP 2019: Core Semantic First: A Top-down Approach for AMR Parsing.[[paper](https://aclanthology.org/D19-1393.pdf)][[code](https://github.com/jcyk/AMR-parser)]
- ACL 2019: AMR Parsing as Sequence-to-Graph Transduction.[[paper](https://aclanthology.org/P19-1009.pdf)][[code](https://github.com/sheng-z/stog)]
- ACL 2019: SemBleu: A Robust Metric for AMR Parsing Evaluation.[[paper](https://aclanthology.org/P19-1446.pdf)][[code](https://github.com/freesunshine0316/sembleu)] *Note: this paper is about a new evaluation method(metric), but not a new method*
- ACL 2019: Rewarding Smatch: Transition-Based AMR Parsing with Reinforcement Learning[[paper](https://aclanthology.org/P19-1451.pdf)]
- IJCAI 2019: Modeling Source Syntax and Semantics for Neural AMR Parsing[[paper](https://www.ijcai.org/proceedings/2019/0691.pdf)]

## Top smatches

AMR 2.0(LDC2017T10), top 2 models of each year:

|  Yr   | Smatch | Paper name                                                                                                     |
| :---: | :----: | :------------------------------------------------------------------------------------------------------------- |
| 2021  | 86.26  | Ensembling Graph Predictions for AMR Parsing\[NeurIPS2021\]                                                    |
| 2021  |  84.7  | Structure-aware Fine-tuning of Sequence-to-sequence Transformers for Transition-based AMR Parsing\[EMNLP2021\] |
| 2020  |  81.4  | Improving AMR Parsing with Sequence-to-Sequence Pre-training\[EMNLP2020\]                                      |
| 2020  |  81.3  | Pushing the Limits of AMR Parsing with Self-Learning\[Findings of ACL 2020\]                                   |
| 2019  |  77.0  | Broad-Coverage Semantic Parsing as Transduction[IJCNLP2019]                                                    |
| 2019  |  76.3  | AMR Parsing as Sequence-to-Graph Transduction[ACL2019]                                                         |

AMR 3.0(LDC2020T02), top 3 models of each year(currently 2021 only):

|  Yr   | Smatch | Paper name                                                                                             |
| :---: | :----: | :----------------------------------------------------------------------------------------------------- |
| 2021  | 84.87  | Ensembling Graph Predictions for AMR Parsing\[NeurIPS2021\]                                            |
| 2021  |  83.0  | One SPRING to Rule Them Both: Symmetric AMR Semantic Parsing and Generation without a Complex Pipeline |
| 2021  |  82.7  | Structure-aware Fine-tuning of Sequence-to-sequence Transformers for Transition-based AMR Parsing      |

As for AMR 1.0, it is a little bit old(2014) and small, so few articles still use this corpora as benchmark. Therefore it is not listed.
