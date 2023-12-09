2023年度的 AI 顶会和顶刊已经出炉，在此把关于 Differential Privacy 的部分筛选出来，以供后续学习，整理内容已同步在我的 [Blog](https://blog.lfd-world.online/2023/12/07/2023-ai-ccf-a-differential-privacy-yi-kui-chi-xu-geng-xin-zhong/)。

- [人工智能](#人工智能)
  - [AAAI](#aaai)
  - [NeurlPS](#neurlps)
  - [ACL](#acl)
  - [CVPR](#cvpr)
  - [ICML](#icml)
  - [IJCAI](#ijcai)

## 人工智能

### AAAI

| paper                                                        | authors                | code                                                         |
| ------------------------------------------------------------ | ---------------------- | ------------------------------------------------------------ |
| [Differentially Private Nonlinear Causal Discovery from Numerical Data](https://ojs.aaai.org/index.php/AAAI/article/view/26452) | Hao Zhang              | [url](https://github.com/Causality-Inference/PCD)            |
| [DPAUC: Differentially Private AUC Computation in Federated Learning](https://ojs.aaai.org/index.php/AAAI/article/view/26770) | Jiankai Sun            | [url](https://github.com/bytedance/fedlearner/tree/master/example/privacy/DPAUC) |
| [XRand: Differentially Private Defense against Explanation-Guided Attacks](https://ojs.aaai.org/index.php/AAAI/article/view/26401) | Truc Nguyen            | none                                                         |
| [Differentially Private Learning with Per-Sample Adaptive Clipping](https://ojs.aaai.org/index.php/AAAI/article/view/26242) | Tianyu Xia             | none                                                         |
| [Differentially Private Heatmaps](https://ojs.aaai.org/index.php/AAAI/article/view/25933) | Badih Ghazi            | none                                                         |
| [Integer Subspace Differential Privacy](https://ojs.aaai.org/index.php/AAAI/article/view/25895) | Prathamesh Dharangutte | none                                                         |
| [Two Views of Constrained Differential Privacy: Belief Revision and Update](https://arxiv.org/abs/2303.00228) | Likang Liu             | none                                                         |
| [Differentially Private Fair Division](https://ojs.aaai.org/index.php/AAAI/article/view/25721) | Pasin Manurangsi       | none                                                         |
| [Differentially Private Condorcet Voting](https://ojs.aaai.org/index.php/AAAI/article/view/25714) | Zhechen Li             | none                                                         |

### NeurlPS

官方暂未发布。

### ACL 

| paper                                                        | authors            | code                                                         |
| ------------------------------------------------------------ | ------------------ | ------------------------------------------------------------ |
| [Synthetic Text Generation with Differential Privacy: A Simple and Practical Recipe](https://arxiv.org/abs/2210.14348) | Xiang Yue          | [url](https://github.com/microsoft/dp-transformers)          |
| [A Customized Text Sanitization Mechanism with Differential Privacy](https://aclanthology.org/2023.findings-acl.355/) | Sai Chen           | [url](https://github.com/sai4july/CusText)                   |
| [DP-BART for Privatized Text Rewriting under Local Differential Privacy](https://arxiv.org/abs/2302.07636) | Timour Igamberdiev | [url](https://github.com/trusthlt/dp-bart-private-rewriting) |
| [Federated Learning of Gboard Language Models with Differential Privacy](https://arxiv.org/abs/2305.18465) | Zheng Xu           | none                                                         |

### CVPR

| paper                                                        | authors        | code                                                         |
| ------------------------------------------------------------ | -------------- | ------------------------------------------------------------ |
| [Learning to Generate Image Embeddings with User-Level Differential Privacy](https://openaccess.thecvf.com/content/CVPR2023/html/Xu_Learning_To_Generate_Image_Embeddings_With_User-Level_Differential_Privacy_CVPR_2023_paper.html) | Zheng Xu       | [url](https://github.com/google-research/federated/tree/master/dp_visual_embeddings) |
| [Federated Learning in Non-IID Settings Aided by Differentially Private Synthetic Data](https://openaccess.thecvf.com/content/CVPR2023W/FedVision/html/Chen_Federated_Learning_in_Non-IID_Settings_Aided_by_Differentially_Private_Synthetic_CVPRW_2023_paper.html) | Huancheng Chen | none                                                         |
| [Make Landscape Flatter in Differentially Private Federated Learning](https://openaccess.thecvf.com/content/CVPR2023/html/Shi_Make_Landscape_Flatter_in_Differentially_Private_Federated_Learning_CVPR_2023_paper.html) | Yifan Shi      | none                                                         |

### ICML

| paper                                                        | authors                   | code                                                         |
| ------------------------------------------------------------ | ------------------------- | ------------------------------------------------------------ |
| [The Saddle-Point Method in Differential Privacy](https://proceedings.mlr.press/v202/alghamdi23a.html) | Wael Alghamdi             | [url](https://github.com/Felipe-Gomez/saddlepoint_accountant) |
| [Differentially Private Distributed Bayesian Linear Regression with MCMC](https://proceedings.mlr.press/v202/alparslan23a.html) | Baris Alparslan           | [url](https://github.com/sinanyildirim/Bayesian_DP_dist_LR)  |
| [Differentially Private Optimization on Large Model at Small Cost](https://proceedings.mlr.press/v202/bu23a.html) | Zhiqi Bu                  | [url](https://github.com/awslabs/fast-differential-privacy)  |
| [Streaming Submodular Maximization with Differential Privacy](https://proceedings.mlr.press/v202/chaturvedi23a.html) | Anamay Chaturvedi         | [url](https://github.com/thydnguyen/PrivSubmodularOpt)       |
| [Differentially Private Hierarchical Clustering with Provable Approximation Guarantees](https://arxiv.org/abs/2302.00037) | Jacob Imola               | [url](https://bitbucket.org/jjimola/dphc/src/master/)        |
| [The Test of Tests: A Framework for Differentially Private Hypothesis Testing](https://proceedings.mlr.press/v202/kazan23a.html) | Zeki Kazan                | [url](https://github.com/diff-priv-ht/test-of-tests)         |
| [Multi-Task Differential Privacy Under Distribution Skew](https://proceedings.mlr.press/v202/krichene23a.html) | Walid Krichene            | [url](https://github.com/google-research/google-research/tree/master/) |
| [Differential Privacy has Bounded Impact on Fairness in Classification](https://proceedings.mlr.press/v202/mangold23a.html) | Paul Mangold              | [url](https://github.com/pmangold/fairness-privacy)          |
| [Differentially Private Sharpness-Aware Training](https://arxiv.org/abs/2306.05651) | Jinseong Park             | [url](https://github.com/jinseongP/DPSAT)                    |
| [Differential Privacy, Linguistic Fairness, and Training Data Influence: Impossibility and Possibility Theorems for Multilingual Language Models](https://proceedings.mlr.press/v202/rust23a.html) | Phillip Rust              | [url](https://github.com/xplip/multilingual-lm-objectives)   |
| [Bayesian Estimation of Differential Privacy](https://proceedings.mlr.press/v202/zanella-beguelin23a.html) | Santiago Zanella-Beguelin | [url](https://github.com/microsoft/responsible-ai-toolbox-privacy) |
| [Differentially Private Episodic Reinforcement Learning with Heavy-tailed Rewards](https://arxiv.org/abs/2306.01121) | Yulian Wu                 | none                                                         |
| [Fully-Adaptive Composition in Differential Privacy](https://proceedings.mlr.press/v202/whitehouse23a.html) | Justin Whitehouse         | none                                                         |
| [Concurrent Shuffle Differential Privacy Under Continual Observation](https://arxiv.org/abs/2301.12535) | Jay Tenenbaum             | none                                                         |
| [Sketching Meets Differential Privacy: Fast Algorithm for Dynamic Kronecker Projection Maintenance](https://proceedings.mlr.press/v202/song23i.html) | Zhao Song                 | none                                                         |
| [DIFF2: Differential Private Optimization via Gradient Differences for Nonconvex Distributed Learning](https://arxiv.org/abs/2302.03884) | Tomoya Murata             | none                                                         |
| [Online Local Differential Private Quantile Inference via Self-normalization](https://proceedings.mlr.press/v202/liu23q.html) | Yi Liu                    | none                                                         |
| [The Price of Differential Privacy under Continual Observation](https://proceedings.mlr.press/v202/jain23b.html) | Palak Jain                | none                                                         |
| [Federated Linear Contextual Bandits with User-level Differential Privacy](https://proceedings.mlr.press/v202/huang23q.html) | Ruiquan Huang             | none                                                         |
| [Constant Matters: Fine-grained Error Bound on Differentially Private Continual Observation](https://proceedings.mlr.press/v202/fichtenberger23a.html) | Hendrik Fichtenberger     | none                                                         |
| [Beyond Uniform Lipschitz Condition in Differentially Private Optimization](https://proceedings.mlr.press/v202/das23c.html) | Rudrajit Das              | none                                                         |
| [Differentially Private Stochastic Convex Optimization under a Quantile Loss Function](https://proceedings.mlr.press/v202/chen23d.html) | Du Chen                   | none                                                         |
| [Label differential privacy and private training data release](https://proceedings.mlr.press/v202/busa-fekete23a.html) | Robert Istvan Busa-Fekete | none                                                         |
| [Faster Rates of Convergence to Stationary Points in Differentially Private Optimization](https://proceedings.mlr.press/v202/arora23a.html) | Raman Arora               | none                                                         |

### IJCAI

| paper                                                        | authors       | code |
| ------------------------------------------------------------ | ------------- | ---- |
| [Fast and Differentially Private Fair Clustering](https://www.ijcai.org/proceedings/2023/656) | Junyoung Byun | none |
| [Differentially Private Partial Set Cover with Applications to Facility Location](https://arxiv.org/abs/2207.10240) | George Z. Li  | none |
| [DPMAC: Differentially Private Communication for Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2308.09902) | Canzhe Zhao   | none |
| [Model Conversion via Differentially Private Data-Free Distillation](https://arxiv.org/abs/2304.12528) | Bochao Liu    | none |