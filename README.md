# Session-based-Rec-Papers
Papers of Session-based Recommendation from top conf/journals.

 This repo mainly collects some papers on the Session-based Recommendation research (Sequential recommendataion) from the top conference (e.g. KDD, CIKM and AAAI) and journals.

 We will update the latest published papers from time to time... 

-----


  ### Review Paper List
|  Title   |  Authors/Team  |   Key Contributions    |  Source  |
|  ----  | ----  |   ----  | ----  |
| [Performance Comparison of Neural and Non-Neural Approaches to Session-based Recommendation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.473.9437&rep=rep1&type=pdf) |  | Recsys'2019 |

-----

### Research Paper List



#### RNN-based Methods

| Title                                                        | Key Contributions                                | Source     | Chinese Blogs | original code |
| ------------------------------------------------------------ | ------------------------------------------------ | ---------- | ------------- | ------------- |
|                                                              |                                                  |            |               |               |
| [Neural Attentive Session-based Recommendation](https://arxiv.org/pdf/1711.04725.pdf) | GRU+Last item Attention                          | CIKM'2017  |               |               |
| [BERT4Rec: Sequential Recommendation with Bidirectional Encoder Representations from Transformer](https://arxiv.org/pdf/1904.06690.pdf) |                                                  | CIKM'2019  |               |               |
|                                                              |                                                  |            |               |               |
| [Non-invasive Self-attention for Side Information Fusion in Sequential Recommendation]([PRELIMINARY VERSION DO NOT CITE (aaai.org)](https://www.aaai.org/AAAI21Papers/AAAI-5262.LiuC.pdf)) |                                                  | AAAI'2021  |               |               |
| [Incorporating User Micro-behaviors and Item Knowledge into Multi-task Learning for Session-based Recommendation]([Incorporating User Micro-behaviors and Item Knowledge into Multi-task Learning for Session-based Recommendation \|Proceedings of the 43rd International ACM SIGIR Conference on Research and Development in Information Retrieval](https://dl.acm.org/doi/abs/10.1145/3397271.3401098)) | Introcoption interaction type and item knowledge | SIGIR'2020 |               |               |
| [Disentangled Self-Supervision in Sequential Recommenders]([Disentangled Self-Supervision in Sequential Recommenders (researchgate.net)](https://www.researchgate.net/profile/Xin-Wang-532/publication/343785856_Disentangled_Self-Supervision_in_Sequential_Recommenders/links/5f4f9dd392851c250b893dbd/Disentangled-Self-Supervision-in-Sequential-Recommenders.pdf)) |                                                  | KDD'2020   |               |               |





#### GNN-based Methods

|  Title     |   Key Contributions    |  Source  | Chinese Blogs| original code |
|  :----  |  ----  | ----  | ---- | ---- |
| [Self-Supervised Hypergraph Convolutional Networks for Session-based Recommendation](https://arxiv.org/pdf/2012.06852.pdf)|  Global **HyperGraph**  + session-level graph construction | AAAI'2020| ||
|[Handling Information Loss of Graph Neural Networks for Session-based Recommendation](http://www.cse.ust.hk/~raywong/paper/kdd20-informationLoss-GNN.pdf)| session to **Egde order preserved** Multi-graph & **short-cut** graph | KDD'2020| [jianshu](https://www.jianshu.com/p/674fbc3f548a) ||
|[Memory Augmented Graph Neural Networks for Sequential Recommendation](https://ojs.aaai.org/index.php/AAAI/article/download/5945/5801)| short-term user preference (gnn) & long-term preference (shared memory network)    |AAAI'2020| ||
|[DGTN: Dual-channel Graph Transition Network for Session-based Recommendation](https://arxiv.org/pdf/2009.10002.pdf) | model complex transitions between items in different sessions: integrate the target session and  neighbor (similar) sessions into a single graph: (**Intra-session  & Inter-session GNN**) | arxiv |||
|[Cross-Session Aware Temporal Convolutional Network for Session-based Recommendation](GNN-based/Cross-Session%20Aware%20Temporal%20Convolutional%20Network%20for%20Session-based%20Recommendation.pdf)| | 2020 ICDM *wokshop* | ||
|[Global Context Enhanced Graph Neural Networks for Session-based Recommendation](https://arxiv.org/pdf/2106.05081.pdf)| **global context enhanced graph** (neighbor sampling) + session graph | SIGIR'2020| [jianshu](https://www.jianshu.com/p/f843ac348a37) ||
|[Star Graph Neural Networks for Session-based Recommendation](GNN-based/StarGNN.pdf)| capture the item relationship without direct connections, **add virutal node (session-level)** to connect with all items in the current session  |CIKM'2020|||
| [Temporal Augmented Graph Neural Networks for Session-Based Recommendations](https://www4.comp.polyu.edu.hk/~xiaohuang/docs/Huachi_sigir2021.pdf)| build **dynamic graphs** (constructs a graph for each day and merge nodes based on temporal infomation) to capture the drifting user interests| SIGIR'2021 *short*|||
| | | |||
| | | |||
| | | |||
