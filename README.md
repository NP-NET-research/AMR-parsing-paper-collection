# AMR parsing paper collection

In this page we collect papers about English AMR parsing in recent years(2019-2022). Papers count table is as follow:

| Year  |  ACL  | NAACL | AAAI  | IJCAI | EMNLP | COLING | TKDE  | NeurIPS | total |
| :---: | :---: | :---: | :---: | :---: | :---: | :----: | :---: | :-----: | :---: |
| 2022  |   -   |   -   |   -   |   -   |   -   |   -    |   0   |    -    |   0   |
| 2021  |   0   |   1   |   1   |   0   |   2   |   -    |   0   |    1    |   5   |
| 2020  |   2   |   -   |   0   |   0   |   2   |   0    |   0   |    0    |   4   |
| 2019  |   3   |   0   |   0   |   1   |   1   |   -    |   0   |    0    |   5   |
|       |
| total |   5   |   1   |   1   |   1   |   5   |   0    |   0   |    1    |  14   |

Grids marked with a '-' indicates the conference is not yet started, not held in that year, or proceedings is not yet available.

## Paper Collection

### 2022

nothing here yet...

### 2021

- EMNLP 2021: Structure-aware Fine-tuning of Sequence-to-sequence Transformers for Transition-based AMR Parsing. [[paper](https://aclanthology.org/2021.emnlp-main.507.pdf)]
- EMNLP 2021: A Differentiable Relaxation of Graph Segmentation and Alignment for AMR Parsing. [[paper](https://aclanthology.org/2021.emnlp-main.714.pdf)]
- NAACL 2021: AMR Parsing with Action-Pointer Transformer. [[paper](https://aclanthology.org/2021.naacl-main.443.pdf)]
- NeurIPS 2021: Ensembling Graph Predictions for AMR Parsing. [[paper](https://proceedings.neurips.cc//paper/2021/file/479b4864e55e12e0fb411eadb115c095-Paper.pdf)][[code](https://github.com/ibm/graph_ensemble_learning)]
- AAAI 2021: One SPRING to Rule Them Both: Symmetric AMR Semantic Parsing and Generation without a Complex Pipeline. [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/17489/17296)][[code](https://github.com/SapienzaNLP/spring)]

### 2020

- EMNLP 2020: Improving AMR Parsing with Sequence-to-Sequence Pre-training. [[paper](https://aclanthology.org/2020.emnlp-main.196.pdf)][[code](https://github.com/xdqkid/S2S-AMR-Parser)]
- EMNLP 2020: Fast semantic parsing with well-typedness guarantees. [[paper](https://aclanthology.org/2020.emnlp-main.323.pdf)][[code](https://github.com/coli-saar/am-parser)] *note: this paper is mainly about speed rather than accuracy*
- ACL 2020: AMR Parsing via Graph-Sequence Iterative Inference. [[paper](https://aclanthology.org/2020.acl-main.119.pdf)][[code](https://github.com/jcyk/AMR-gs)]
- ACL 2020: AMR Parsing with Latent Structural Information. [[paper](https://aclanthology.org/2020.acl-main.397.pdf)]

### 2019

- EMNLP 2019: Core Semantic First: A Top-down Approach for AMR Parsing. [[paper](https://aclanthology.org/D19-1393.pdf)][[code](https://github.com/jcyk/AMR-parser)]
- EMNLP 2019: Broad-Coverage Semantic Parsing as Transduction. [[paper](https://aclanthology.org/D19-1392.pdf)]
- ACL 2019: AMR Parsing as Sequence-to-Graph Transduction. [[paper](https://aclanthology.org/P19-1009.pdf)][[code](https://github.com/sheng-z/stog)]
- ACL 2019: SemBleu: A Robust Metric for AMR Parsing Evaluation. [[paper](https://aclanthology.org/P19-1446.pdf)][[code](https://github.com/freesunshine0316/sembleu)] *Note: this paper is about a new evaluation method(metric), but not a new method*
- ACL 2019: Rewarding Smatch: Transition-Based AMR Parsing with Reinforcement Learning. [[paper](https://aclanthology.org/P19-1451.pdf)]
- ACL 2019: Compositional Semantic Parsing across Graphbanks. [[paper](https://aclanthology.org/P19-1450.pdf)][[code](https://github.com/coli-saar/am-parser)]
- IJCAI 2019: Modeling Source Syntax and Semantics for Neural AMR Parsing. [[paper](https://www.ijcai.org/proceedings/2019/0691.pdf)]

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

## Benchmark count

In this section we record papers referenced as SOTA methods in recent years. Papers published before 2017 is not included.

| 2019  | 2020  | 2021  | AMR2.0 |          From          | Authors                     | Paper name                                                                                                | links                                                                                                                |
| :---: | :---: | :---: | :----: | :--------------------: | :-------------------------- | :-------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------- |
|   0   |   0   |   1   |  76.8  |       EMNLP 2021       | C.Lyu et al.                | A Differentiable Relaxation of Graph Segmentation and Alignment for AMR Parsing                           | [[PDF](https://aclanthology.org/2021.emnlp-main.714.pdf)]                                                            |
|   0   |   0   |   3   |  84.5  |       AAAI 2021        | M.Bevilacqua et al.         | One SPRING to Rule Them Both: Symmetric AMR Semantic Parsing and Generation without a Complex Pipeline    | [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/17489/17296)][[code](https://github.com/SapienzaNLP/spring)] |
|   0   |   0   |   2   |  82.6  |       NAACL 2021       | J.Zhou et al.               | AMR Parsing with Action-Pointer Transformer                                                               | [[PDF](https://aclanthology.org/2021.naacl-main.443.pdf)]                                                            |
|   0   |   2   |   5   |  80.2  |        ACL 2020        | D.Cai, W.Lam                | AMR Parsing via Graph-Sequence Iterative Inference                                                        | [[PDF](https://aclanthology.org/2020.acl-main.119.pdf)][[code](https://github.com/jcyk/AMR-gs)]                      |
|   0   |   0   |   2   |  79.7  | findings of EMNLP 2020 | R.F.Astudillo et al.        | Transition-based Parsing with Stack-Transformers                                                          | [[PDF](https://aclanthology.org/2020.findings-emnlp.89.pdf)][[code](https://github.com/IBM/transition-amr-parser)]   |
|   0   |   0   |   3   |  81.4  |       EMNLP 2020       | D.Xu et al.                 | Improving AMR Parsing with Sequence-to-Sequence Pre-training                                              | [[PDF](https://aclanthology.org/2020.emnlp-main.196.pdf)][[code](https://github.com/xdqkid/S2S-AMR-Parser)]          |
|   0   |   0   |   3   |  81.3  | findings of EMNLP 2020 | Y.Lee et al.                | Pushing the Limits of AMR Parsing with Self-Learning                                                      | [[PDF](https://aclanthology.org/2020.findings-emnlp.288.pdf)]                                                        |
|   0   |   0   |   1   |  77.1  |       EMNLP 2020       | M.Lindemann et al.          | Fast semantic parsing with well-typedness guarantees                                                      | [[PDF](https://aclanthology.org/2020.emnlp-main.323.pdf)][[code](https://github.com/coli-saar/am-parser)]            |
|   0   |   0   |   1   |  77.5  |        ACL 2020        | Q.Zhou et al.               | AMR Parsing with Latent Structural Information                                                            | [[PDF](https://aclanthology.org/2020.acl-main.397.pdf)]                                                              |
|   2   |   3   |   4   |  75.5  |        ACL 2019        | T.Naseem, et al.            | Rewarding Smatch: Transition-Based AMR Parsing with Reinforcement Learning                                | [[PDF](https://aclanthology.org/P19-1451.pdf)]                                                                       |
|   3   |   3   |   2   |  76.3  |        ACL 2019        | S.Zhang et al.              | AMR Parsing as Sequence-to-Graph Transduction                                                             | [[PDF](https://aclanthology.org/P19-1009.pdf)][[code](https://github.com/sheng-z/stog)]                              |
|   0   |   4   |   4   |  77.0  |       EMNLP 2019       | S.Zhang et al.              | Broad-Coverage Semantic Parsing as Transduction                                                           | [[PDF](https://aclanthology.org/D19-1392.pdf)]                                                                       |
|   0   |   1   |   1   |  74.3  |       IJCAI 2019       | D.Ge et al.                 | Modeling Source Syntax and Semantics for Neural AMR Parsing                                               | [[PDF](https://www.ijcai.org/proceedings/2019/0691.pdf)]                                                             |
|   1   |   4   |   1   |  75.3  |        ACL 2019        | M.Lindemann et al.          | Compositional Semantic Parsing across Graphbanks                                                          | [[PDF](https://aclanthology.org/P19-1450.pdf)][[code](https://github.com/coli-saar/am-parser)]                       |
|   1   |   3   |   3   |  73.2  |       EMNLP 2019       | D.Cai, W.Lam                | Core Semantic First: A Top-down Approach for AMR Parsing                                                  | [[PDF](https://aclanthology.org/D19-1393.pdf)][[code](https://github.com/jcyk/AMR-parser)]                           |
|   5   |   3   |   2   |  74.4  |        ACL 2018        | C.Lyu, I.Titov              | AMR Parsing as Graph Prediction with Latent Alignment                                                     | [[PDF](https://aclanthology.org/P18-1037.pdf)][[code](https://github.com/ChunchuanLv/AMR_AS_GRAPH_PREDICTION)]       |
|   4   |   2   |   1   |  71.0  |        ACL 2018        | J.Groschwitz et al.         | AMR dependency parsing with a typed semantic algebra                                                      | [[PDF](https://aclanthology.org/P18-1170.pdf)]                                                                       |
|   5   |   3   |   1   |  69.8  |       EMNLP 2018       | Z.Guo, W.Lu                 | Better Transition-Based AMR Parsing with a Refined Search Space                                           | [[PDF](https://aclanthology.org/D18-1198.pdf)]                                                                       |
|   2   |   2   |   1   |   -    |       EMNLP 2017       | C.Wang, N.Xue               | Getting the most out of AMR parsing                                                                       | [[PDF](https://aclanthology.org/D17-1129.pdf)]                                                                       |
|   4   |   1   |   2   |  71.0  |       CLIN* 2017       | R.vNoord,J.Bos              | Neural Semantic Parsing by Character-based Translation: Experiments with Abstract Meaning Representations | [[PDF](https://clinjournal.org/clinj/article/view/72/64)][[code](https://github.com/RikVN/AMR)]                      |
|   4   |   0   |   0   |  61.9  |    SemEval 2017 T9     | J.Buys, P.Blunsom           | Neural AMR Parsing with Pointer-Augmented Attention                                                       | [[PDF](https://aclanthology.org/S17-2157.pdf)]                                                                       |
|   1   |   0   |   0   |  68.3  |       2017EMNLP        | M.Ballesteros, Y.Al-Onaizan | AMR Parsing using Stack-LSTMs                                                                             | [[PDF](https://aclanthology.org/D17-1130.pdf)]                                                                       |
*CLIN:[Computational Linguistics in the Netherlands Journal](https://clinjournal.org/)
