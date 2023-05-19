# ⚔🛡 Awesome Backdoor Attack and Defense in Deep Learning

This repository contains backdoor learning papers published on top conference and journals, ranging from 2016 to 2023. 

# Table of contents
- [⚔🛡 Awesome Backdoor Attack and Defense in Deep Learning](#-awesome-backdoor-attack-and-defense-in-deep-learning)
- [Table of contents](#table-of-contents)
- [📃Survey](#survey)
- [⚔Attack](#attack)
  - [Computer Vision](#computer-vision)
  - [Natural Language Processing](#natural-language-processing)
  - [Graph Neural Networks](#graph-neural-networks)
- [🛡Defense](#defense)
  - [Before-training](#before-training)
  - [In-training](#in-training)
  - [Post-training](#post-training)
- [Others](#others)
- [⚙Toolbox](#toolbox)

# 📃Survey
| Year | Venue                        | Paper                                                                                                                                                           |
| ---- | ---------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2023 | arXiv                        | [Adversarial Machine Learning: A Systematic Survey of Backdoor Attack, Weight Attack and Adversarial Example](https://arxiv.org/pdf/2012.10544.pdf)                                      |
| 2022 | TPAMI                        | [Data Security for Machine Learning: Data Poisoning, Backdoor Attacks, and Defenses](https://arxiv.org/pdf/2012.10544.pdf)                                      |
| 2022 | TNNLS                        | [Backdoor Learning: A Survey](https://www.researchgate.net/publication/343006441_Backdoor_Learning_A_Survey)                                                    |
| 2022 | IEEE Wireless Communications | [Backdoor Attacks and Defenses in Federated Learning: State-of-the-art, Taxonomy, and Future Directions](https://ieeexplore.ieee.org/abstract/document/9806416) |
| 2021 | Neurocomputing               | [Defense against Neural Trojan Attacks: A Survey](https://www.sciencedirect.com/science/article/pii/S0925231220316350)                                          |
| 2020 | ISQED                        | [A Survey on Neural Trojans](https://eprint.iacr.org/2020/201.pdf)                                                                                              |


# ⚔Attack

## Computer Vision
| Year | Venue        | Paper                                                        | Code                                                         |
| ---- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2023 | ICML 2023 | [Chameleon: Adapting to Peer Images for Planting Durable Backdoors in Federated Learning](https://arxiv.org/abs/2304.12961) |  |
| 2023 | ICLR 2023    | [TrojText: Test-time Invisible Textual Trojan Insertion](https://openreview.net/forum?id=ja4Lpp5mqc2) | [:octocat:](https://github.com/UCF-ML-Research/TrojText)  |
| 2023 | ICLR 2023    | [Few-shot Backdoor Attacks via Neural Tangent Kernels](https://openreview.net/forum?id=a70lGJ-rwy) |   |
| 2023 | ICLR 2023    | [Revisiting the Assumption of Latent Separability for Backdoor Defenses](https://openreview.net/forum?id=_wSHsgrVali) | [:octocat:](https://github.com/Unispac/Circumventing-Backdoor-Defenses)  |
| 2023 | ICLR 2023    | [The Dark Side of AutoML: Towards Architectural Backdoor Search](https://openreview.net/forum?id=bsZULlDGXe) | [:octocat:](https://github.com/ain-soph/nas_backdoor)  |
| 2023 | ICLR 2023    | [Clean-image Backdoor: Attacking Multi-label Models with Poisoned Labels Only](https://openreview.net/forum?id=rFQfjDC9Mt) | |
| 2023 | CVPR 2023    | [Architectural Backdoors in Neural Networks](https://arxiv.org/abs/2206.07840) | |
| 2023 | CVPR 2023    | [How to Backdoor Diffusion Models?](https://arxiv.org/abs/2206.07840) | [:octocat:](https://github.com/IBM/BadDiffusion)|
| 2023 | CVPR 2023    | Color Backdoor: A Robust Poisoning Attack in Color Space| |
| 2023 | CVPR 2023    | [You Are Catching My Attention: Are Vision Transformers Bad Learners Under Backdoor Attacks?](https://openreview.net/forum?id=7P_yIFi6zaA) | |
| 2023 | CVPR 2023    | The Dark Side of Dynamic Routing Neural Networks: Towards Efficiency Backdoor Injection | [:octocat:](https://github.com/SeekingDream/CVPR23_EfficFrog) |
| 2023 | CVPR 2023    | [Backdoor Attacks Against Deep Image Compression via Adaptive Frequency Trigger](https://arxiv.org/abs/2302.14677) ||
| 2023 | SIGIR 2023 | [Manipulating Federated Recommender Systems: Poisoning with Synthetic Users and Its Countermeasures](https://arxiv.org/abs/2304.03054) ||
| 2022 | AAAI 2022    | [Backdoor Attacks on the DNN Interpretation System](https://ojs.aaai.org/index.php/AAAI/article/view/19935) ||
| 2022 | AAAI 2022    | [Faster Algorithms for Weak Backdoors](https://ojs.aaai.org/index.php/AAAI/article/view/20288) ||
| 2022 | AAAI 2022    | [Finding Backdoors to Integer Programs: A Monte Carlo Tree Search Framework](https://ojs.aaai.org/index.php/AAAI/article/view/20293) |                                                              |
| 2022 | AAAI 2022    | [Hibernated Backdoor: A Mutual Information Empowered Backdoor Attack to Deep Neural Networks](https://ojs.aaai.org/index.php/AAAI/article/view/21272) |                                                              |
| 2022 | AAAI 2022    | [On Probabilistic Generalization of Backdoors in Boolean Satisfiability](https://ojs.aaai.org/index.php/AAAI/article/view/21277) |                                                              |
| 2022 | CCS 2022     | [Backdoor Attacks on Spiking NNs and Neuromorphic Datasets](https://doi.org/10.1145/3548606.3563532) | [:octocat:](https://github.com/GorkaAbad/NeuromorphicBackdoors) |
| 2022 | CCS 2022     | [LoneNeuron: A Highly-Effective Feature-Domain Neural Trojan Using Invisible and Polymorphic Watermarks](https://doi.org/10.1145/3548606.3560678) |                                                              |
| 2022 | CVPR 2022    | [BppAttack: Stealthy and Efficient Trojan Attacks against Deep Neural Networks via Image Quantization and Contrastive Adversarial Learning](https://doi.org/10.1109/CVPR52688.2022.01465) |                                                              |
| 2022 | CVPR2022     | [Backdoor Attacks on Self-Supervised Learning](https://doi.org/10.1109/CVPR52688.2022.01298) | [:octocat:](https://github.com/UMBCvision/SSL-Backdoor) |
| 2022 | CVPR 2022    | [DEFEAT: Deep Hidden Feature Backdoor Attacks by Imperceptible Perturbation and Latent Representation Constraints](https://doi.org/10.1109/CVPR52688.2022.01478) ||
| 2022 | CVPR2022    | [Dual-Key Multimodal Backdoors for Visual Question Answering](https://doi.org/10.1109/CVPR52688.2022.01494) | [:octocat:](https://github.com/SRI-CSL/TrinityMultimodalTrojAI)|
| 2022 | CVPR 2022    | [FIBA: Frequency-Injection based Backdoor Attack in Medical Image Analysis](https://doi.org/10.1109/CVPR52688.2022.02021) | [:octocat:](https://github.com/HazardFY/FIBA)                |
| 2022 | CVPR 2022    | [Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks.](https://doi.org/10.1109/CVPR52688.2022.01299) |                                                              |
| 2022 | ECCV 2022    | [An Invisible Black-Box Backdoor Attack Through Frequency Domain](https://doi.org/10.1007/978-3-031-19778-9_23) | [:octocat:](https://github.com/SoftWiser-group/FTrojan)      |
| 2022 | ECCV 2022    | [RIBAC: Towards Robust and Imperceptible Backdoor Attack against Compact DNN](https://doi.org/10.1007/978-3-031-19772-7_41) | [:octocat:](https://github.com/huyvnphan/ECCV2022-RIBAC)     |
| 2022 | EUROSP 2022  | [Dynamic Backdoor Attacks Against Machine Learning Models](https://doi.org/10.1109/EuroSP53844.2022.00049) |                                                              |
| 2022 | EUROSP 2022  | [TrojanZoo: Towards Unified, Holistic, and Practical Evaluation of Neural Backdoors](https://doi.org/10.1109/EuroSP53844.2022.00048) | [:octocat:](https://github.com/ain-soph/trojanzoo)           |
| 2022 | ICASSP 2022  | [Invisible and Efficient Backdoor Attacks for Compressed Deep Neural Networks](https://doi.org/10.1109/ICASSP43922.2022.9747582) |                                                              |
| 2022 | ICASSP 2022  | [Stealthy Backdoor Attack with Adversarial Training](https://doi.org/10.1109/ICASSP43922.2022.9746008) |                                                              |
| 2022 | ICASSP 2022  | [When Does Backdoor Attack Succeed in Image Reconstruction? A Study of Heuristics vs. Bi-Level Solution](https://doi.org/10.1109/ICASSP43922.2022.9746433) |                                                              |
| 2022 | ICASSP2022 | [Object-Oriented Backdoor Attack Against Image Captioning](https://doi.org/10.1109/ICASSP43922.2022.9746440) | |
| 2022 | ICLR 2022    | [Few-Shot Backdoor Attacks on Visual Object Tracking](https://openreview.net/forum?id=qSV5CuSaK_a) | [:octocat:](https://github.com/HXZhong1997/FSBA)             |
| 2022 | ICLR 2022    | [How to Inject Backdoors with Better Consistency: Logit Anchoring on Clean Data](https://openreview.net/forum?id=Bn09TnDngN) |                                                              |
| 2022 | ICLR 2022    | [Poisoning and Backdooring Contrastive Learning](https://openreview.net/forum?id=iC4UHbQ01Mp) |                                                              |
| 2022 | ICML2022 | [Neurotoxin: Durable Backdoors in Federated Learning](https://proceedings.mlr.press/v162/zhang22w.html) | |
| 2022 | IJCAI 2022   | [Data-Efficient Backdoor Attacks](https://doi.org/10.24963/ijcai.2022/554) | [:octocat:](https://github.com/xpf/Data-Efficient-Backdoor-Attacks) |
| 2022 | IJCAI2022 | [Membership Inference via Backdooring](https://doi.org/10.24963/ijcai.2022/532) | [:octocat:](https://github.com/HongshengHu/membership-inference-via-backdooring) |
| 2022 | IJCAI 2022   | [Eliminating Backdoor Triggers for Deep Neural Networks Using Attention Relation Graph Distillation](https://doi.org/10.24963/ijcai.2022/206) |                                                              |
| 2022 | IJCAI 2022   | [Imperceptible Backdoor Attack: From Input Space to Feature Representation](https://doi.org/10.24963/ijcai.2022/242) | [:octocat:](https://github.com/Ekko-zn/IJCAI2022-Backdoor)   |
| 2022 | MM 2022      | [Backdoor Attacks on Crowd Counting](https://doi.org/10.1145/3503161.3548296) | [:octocat:](https://github.com/Nathangitlab/Backdoor-Attacks-on-Crowd-Counting) |
| 2022 | MM 2022      | [BadHash: Invisible Backdoor Attacks against Deep Hashing with Clean Label](https://doi.org/10.1145/3503161.3548272) |                                                              |
| 2022 | NeurIPS 2022 | [Marksman Backdoor: Backdoor Attacks with Arbitrary Target Class](https://openreview.net/pdf/db491ee3cff9f8c9a87b1206e94fda5d277c7b32.pdf) |                                                              |
| 2022 | NeurIPS 2022 | [Handcrafted Backdoors in Deep Neural Networks](https://openreview.net/pdf/340575746ae594a5fd043ca5d3075ff65abd9a24.pdf) |                                                              |
| 2022 | NIPS2022 | [Untargeted Backdoor Watermark: Towards Harmless and Stealthy Dataset Copyright Protection](https://openreview.net/pdf/59189794e612834ea8d509a71f501144e4bf881d.pdf) | [:octocat:](https://github.com/THUYimingLi/Untargeted_Backdoor_Watermark) |
| 2022 | NeurIPS 2022 | [Sleeper Agent: Scalable Hidden Trigger Backdoors for Neural Networks Trained from Scratch](https://openreview.net/pdf/d9cc18a9db99b77f760aec0f53633607a0d43f44.pdf) | [:octocat:](https://github.com/hsouri/Sleeper-Agent)         |
| 2022 | TDSC 2022    | [One-to-N & N-to-One: Two Advanced Backdoor Attacks Against Deep Learning Models](https://doi.org/10.1109/TDSC.2020.3028448) |                                                              |
| 2022 | TIFS 2022    | [Dispersed Pixel Perturbation-Based Imperceptible Backdoor Trigger for Image Classifier Models](https://doi.org/10.1109/TIFS.2022.3202687) |                                                              |
| 2022 | TIFS 2022    | [Stealthy Backdoors as Compression Artifacts](https://doi.org/10.1109/TIFS.2022.3160359) | [:octocat:](https://github.com/yulongtzzz/Stealthy-Backdoors-as-Compression-Artifacts) |
| 2022 | TIP 2022     | [Poison Ink: Robust and Invisible Backdoor Attack](https://doi.org/10.1109/TIP.2022.3201472) |                                                              |
| 2021 | AAAI 2021    | [Backdoor Decomposable Monotone Circuits and Propagation Complete Encodings](https://ojs.aaai.org/index.php/AAAI/article/view/16501) |                                                              |
| 2021 | AAAI 2021 | [DeHiB: Deep Hidden Backdoor Attack on Semi-supervised Learning via Adversarial Perturbation](https://ojs.aaai.org/index.php/AAAI/article/view/17266) | |
| 2021 | AAAI 2021    | [Deep Feature Space Trojan Attack of Neural Networks by Controlled Detoxification](https://ojs.aaai.org/index.php/AAAI/article/view/16201) | [:octocat:](https://github.com/Megum1/DFST)                  |
| 2021 | CVPR 2021    | [Backdoor Attacks Against Deep Learning Systems in the Physical World](https://openaccess.thecvf.com/content/CVPR2021/html/Wenger_Backdoor_Attacks_Against_Deep_Learning_Systems_in_the_Physical_World_CVPR_2021_paper.html) |                                                              |
| 2021 | ICCV 2021    | [A Backdoor Attack against 3D Point Cloud Classifiers](https://doi.org/10.1109/ICCV48922.2021.00750) | [:octocat:](https://github.com/zhenxianglance/PCBA)          |
| 2021 | ICCV 2021    | [CLEAR: Clean-up Sample-Targeted Backdoor in Neural Networks](https://doi.org/10.1109/ICCV48922.2021.01614) |                                                              |
| 2021 | ICCV 2021    | [Invisible Backdoor Attack with Sample-Specific Triggers](https://doi.org/10.1109/ICCV48922.2021.01615) | [:octocat:](https://github.com/yuezunli/ISSBA)               |
| 2021 | ICCV 2021    | [LIRA: Learnable, Imperceptible and Robust Backdoor Attacks](https://doi.org/10.1109/ICCV48922.2021.01175) | [:octocat:](https://github.com/sunbelbd/invisible_backdoor_attacks) |
| 2021 | ICCV 2021    | [PointBA: Towards Backdoor Attacks in 3D Point Cloud](https://doi.org/10.1109/ICCV48922.2021.01618) | [:octocat:](https://github.com/zhenxianglance/PCBA)          |
| 2021 | ICCV 2021    | [Rethinking the Backdoor Attacks' Triggers: A Frequency Perspective](https://doi.org/10.1109/ICCV48922.2021.01616) | [:octocat:](https://github.com/YiZeng623/frequency-backdoor) |
| 2021 | ICLR 2021    | [WaNet - Imperceptible Warping-based Backdoor Attack](https://openreview.net/forum?id=eEn8KTtJOx) | [:octocat:](https://github.com/VinAIResearch/Warping-based_Backdoor_Attack-release) |
| 2021 | ICML 2021    | [Just How Toxic is Data Poisoning? A Unified Benchmark for Backdoor and Data Poisoning Attacks](http://proceedings.mlr.press/v139/schwarzschild21a.html) | [:octocat:](https://github.com/aks2203/poisoning-benchmark)  |
| 2021 | IJCAI 2021   | [Backdoor DNFs](https://doi.org/10.24963/ijcai.2021/194)     |                                                              |
| 2021 | IJCAI 2021 | [BACKDOORL: Backdoor Attack against Competitive Reinforcement Learning](https://doi.org/10.24963/ijcai.2021/509) | |
| 2021 | NeurIPS 2021 | [Backdoor Attack with Imperceptible Input and Latent Modification](https://proceedings.neurips.cc/paper/2021/hash/9d99197e2ebf03fc388d09f1e94af89b-Abstract.html) |                                                              |
| 2021 | NeurIPS 2021 | [Excess Capacity and Backdoor Poisoning](https://proceedings.neurips.cc/paper/2021/hash/aaebdb8bb6b0e73f6c3c54a0ab0c6415-Abstract.html) | [:octocat:](https://github.com/narenmanoj/mnist-adv-training) |
| 2021 | TDSC 2021    | [Invisible Backdoor Attacks on Deep Neural Networks Via Steganography and Regularization](https://doi.org/10.1109/TDSC.2020.3021407) |                                                              |
| 2021 | TIFS2021 | [Deep Neural Backdoor in Semi-Supervised Learning: Threats and Countermeasures](https://doi.org/10.1109/TIFS.2021.3116431) | |
| 2021 | KDD2021 | [What Do You See?: Evaluation of Explainable Artificial Intelligence (XAI) Interpretability through Neural Backdoors](https://doi.org/10.1145/3447548.3467213) | |
| 2021 | USS 2021     | [Blind Backdoors in Deep Learning Models](https://www.usenix.org/conference/usenixsecurity21/presentation/bagdasaryan) | [:octocat:](https://github.com/ebagdasa/backdoors101)        |
| 2020 | AAAI 2020    | [Hidden Trigger Backdoor Attacks](https://ojs.aaai.org/index.php/AAAI/article/view/6871) | [:octocat:](https://github.com/UMBCvision/Hidden-Trigger-Backdoor-Attacks) |
| 2020 | CCS 2020     | [Composite Backdoor Attack for Deep Neural Network by Mixing Existing Benign Features](https://doi.org/10.1145/3372297.3423362) |                                                              |
| 2020 | CIKM 2020    | [Can Adversarial Weight Perturbations Inject Neural Backdoors](https://doi.org/10.1145/3340531.3412130) | [:octocat:](https://github.com/goel96vibhor/AdvWeightPerturbations) |
| 2020 | CVPR 2020    | [Clean-Label Backdoor Attacks on Video Recognition Models](https://openaccess.thecvf.com/content_CVPR_2020/html/Zhao_Clean-Label_Backdoor_Attacks_on_Video_Recognition_Models_CVPR_2020_paper.html) | [:octocat:](https://github.com/ShihaoZhaoZSH/Video-Backdoor-Attack) |
| 2020 | ECCV 2020    | [Reflection Backdoor: A Natural Backdoor Attack on Deep Neural Networks](https://doi.org/10.1007/978-3-030-58607-2_11) | [:octocat:](https://github.com/DreamtaleCore/Refool)         |
| 2020 | KDD 2020     | [An Embarrassingly Simple Approach for Trojan Attack in Deep Neural Networks](https://doi.org/10.1145/3394486.3403064) | [:octocat:](https://github.com/trx14/TrojanNet)              |
| 2020 | MM 2020      | [GangSweep: Sweep out Neural Backdoors by GAN](https://doi.org/10.1145/3394171.3413546) |                                                              |
| 2020 | NeurIPS 2020 | [Input-Aware Dynamic Backdoor Attack](https://proceedings.neurips.cc/paper/2020/hash/234e691320c0ad5b45ee3c96d0d7b8f8-Abstract.html) | [:octocat:](https://github.com/VinAIResearch/input-aware-backdoor-attack-release) |
| 2020 | NeurIPS 2020 | [On the Trade-off between Adversarial and Backdoor Robustness](https://proceedings.neurips.cc/paper/2020/hash/8b4066554730ddfaa0266346bdc1b202-Abstract.html) | [:octocat:](https://github.com/nthu-datalab/On.the.Trade-off.between.Adversarial.and.Backdoor.Robustness) |
| 2020 | AISTATS 2020 | [How To Backdoor Federated Learning](http://proceedings.mlr.press/v108/bagdasaryan20a.html) | [:octocat:](https://github.com/ebagdasa/backdoor_federated_learning) |
| 2020 | ICLR2020 | [DBA: Distributed Backdoor Attacks against Federated Learning](https://openreview.net/forum?id=rkgyS0VFvr) | [:octocat:](https://github.com/AI-secure/DBA) |
| 2020 | NIPS2020 | [Attack of the Tails: Yes, You Really Can Backdoor Federated Learning](https://proceedings.neurips.cc/paper/2020/hash/b8ffa41d4e492f0fad2f13e29e1762eb-Abstract.html) | [:octocat:](https://github.com/pps-lab/fl-analysis) |
| 2019 | CCS 2019     | [Latent Backdoor Attacks on Deep Neural Networks](https://doi.org/10.1145/3319535.3354209) | [:octocat:](https://github.com/Huiying-Li/Latent-Backdoor)   |
| 2018 | USS2018 | [Turning Your Weakness Into a Strength: Watermarking Deep Neural Networks by Backdooring](https://www.usenix.org/conference/usenixsecurity18/presentation/adi) | [:octocat:](https://github.com/adiyoss/WatermarkNN) |
| 2018 | NDSS 2018    | [Trojaning Attack on Neural Networks](http://wp.internetsociety.org/ndss/wp-content/uploads/sites/25/2018/02/ndss2018_03A-5_Liu_paper.pdf) | [:octocat:](https://github.com/PurduePAML/TrojanNN)          |


## Natural Language Processing

| Year | Venue       | Paper                                                                                                                                                        | Code                                                                                         |
| ---- | ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------- |
| 2023 | ICML 2023 | [Poisoning Language Models During Instruction Tuning](https://arxiv.org/abs/2305.00944) | [:octocat:](https://github.com/AlexWan0/Poisoning-Instruction-Tuned-Models) |
| 2023 | ICLR 2023 | [TrojText: Test-time Invisible Textual Trojan Insertion](https://openreview.net/forum?id=ja4Lpp5mqc2) | [:octocat:](https://github.com/UCF-ML-Research/TrojText) |
| 2022 | ICLR 2022    | [BadPre: Task-agnostic Backdoor Attacks to Pre-trained NLP Foundation Models](https://openreview.net/forum?id=Mng8CQ9eBW)                                    | [:octocat:](https://github.com/kangjie-chen/BadPre)                                          |
| 2022 | IJCAI 2022   | [PPT: Backdoor Attacks on Pre-trained Models via Poisoned Prompt Tuning](https://doi.org/10.24963/ijcai.2022/96)                                             |                                                                                              |
| 2022 | MM 2022      | [Opportunistic Backdoor Attacks: Exploring Human-imperceptible Vulnerabilities on Speech Recognition Systems](https://doi.org/10.1145/3503161.3548261)       |                                                                                              |
| 2022 | NeurIPS 2022 | [BadPrompt: Backdoor Attacks on Continuous Prompts](https://openreview.net/pdf/5c4cf5b33c7da305a496573c8b6b363f56143e32.pdf)                                 | [:octocat:](https://github.com/papersPapers/BadPrompt)                                       |
| 2022 | NeurIPS 2022 | [Handcrafted Backdoors in Deep Neural Networks](https://openreview.net/pdf/340575746ae594a5fd043ca5d3075ff65abd9a24.pdf)                                     |                                                                                              |
| 2022 | USS 2022     | [Hidden Trigger Backdoor Attack on NLP Models via Linguistic Style Manipulation](https://www.usenix.org/conference/usenixsecurity22/presentation/pan-hidden) |                                                                                              |
| 2022 | USS 2022 | [FLAME: Taming Backdoors in Federated Learning](https://www.usenix.org/conference/usenixsecurity22/presentation/nguyen) | |
| 2021 | ACL 2021     | [Hidden Killer: Invisible Textual Backdoor Attacks with Syntactic Trigger](https://doi.org/10.18653/v1/2021.acl-long.37)                                     | [:octocat:](https://github.com/thunlp/HiddenKiller)                                          |
| 2021 | ACL 2021     | [Rethinking Stealthiness of Backdoor Attack against NLP Models](https://doi.org/10.18653/v1/2021.acl-long.431)                                               | [:octocat:](https://github.com/lancopku/SOS)                                                 |
| 2021 | ACL 2021     | [Turn the Combination Lock: Learnable Textual Backdoor Attacks via Word Substitution](https://doi.org/10.18653/v1/2021.acl-long.377)                         | [:octocat:](https://github.com/thunlp/BkdAtk-LWS)                                            |
| 2021 | CCS 2021     | [Backdoor Pre-trained Models Can Transfer to All](https://doi.org/10.1145/3460120.3485370)                                                                   | [:octocat:](https://github.com/thunlp/OpenBackdoor)                                          |
| 2021 | CCS 2021     | [Hidden Backdoors in Human-Centric Language Models](https://doi.org/10.1145/3460120.3484576)                                                                 | [:octocat:](https://github.com/lishaofeng/NLP_Backdoor)                                      |
| 2021 | EMNLP 2021   | [Backdoor Attacks on Pre-trained Models by Layerwise Weight Poisoning](https://doi.org/10.18653/v1/2021.emnlp-main.241)                                      |                                                                                              |
| 2021 | EMNLP 2021   | [Mind the Style of Text! Adversarial and Backdoor Attacks Based on Text Style Transfer](https://doi.org/10.18653/v1/2021.emnlp-main.374)                     | [:octocat:](https://paperswithcode.com/paper/?acl=2021.emnlp-main.374)                       |
| 2021 | EUROSP 2021  | [Trojaning Language Models for Fun and Profit](https://doi.org/10.1109/EuroSP51992.2021.00022)                                                               | [:octocat:](https://github.com/alps-lab/trojan-lm)                                           |
| 2021 | ICASSP 2021  | [Backdoor Attack Against Speaker Verification](https://doi.org/10.1109/ICASSP39728.2021.9413468)                                                             | [:octocat:](https://github.com/zhaitongqing233/Backdoor-attack-against-speaker-verification) |
| 2023 | NDSS 2023 | [BadGPT: Exploring Security Vulnerabilities of ChatGPT via Backdoor Attacks to InstructGPT ](https://arxiv.org/abs/2304.12298) |  |

## Graph Neural Networks

| Year | Venue       | Paper                                                        | Code                                                         |
| ---- | ----------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2022 | CCS 2022    | [Clean-label Backdoor Attack on Graph Neural Networks](https://doi.org/10.1145/3548606.3563531) |                                                              |
| 2022 | ICMR 2022   | [Camouflaged Poisoning Attack on Graph Neural Networks](https://dl.acm.org/doi/abs/10.1145/3512527.3531373) | [:octocat:](https://github.com/chao92/GAFNC)                 |
| 2022 | RAID 2022   | [Transferable Graph Backdoor Attack](https://dl.acm.org/doi/10.1145/3545948.3545976) |                                                              |
| 2021 | SACMAT 2021 | [Backdoor Attacks to Graph Neural Networks](https://dl.acm.org/doi/10.1145/3450569.3463560) | [:octocat:](https://github.com/zaixizhang/graphbackdoor)     |
| 2021 | USS 2021    | [Graph Backdoor](https://www.usenix.org/conference/usenixsecurity21/presentation/xi) | [:octocat:](https://github.com/HarrialX/GraphBackdoor)       |
| 2021 | WiseML 2021 | [Explainability-based Backdoor Attacks Against Graph Neural Network](https://dl.acm.org/doi/abs/10.1145/3468218.3469046) | [:octocat:](https://github.com/xujing1994/Explanability_bkd_gnn) |

# 🛡Defense

## Before-training

| Year | Venue                | Paper                                                        | Code                                                      |
| ---- | -------------------- | ------------------------------------------------------------ | --------------------------------------------------------- |
| 2023 | USENIX Security 2023 | [How to Sift Out a Clean Data Subset in the Presence of Data Poisoning? ](http://arxiv.org/abs/2210.06516) | [:octocat:](https://github.com/ruoxi-jia-group/Meta-Sift) |

## In-training

| 2023 | CVPR 2023    | [Backdoor Defense via Adaptively Splitting Poisoned Dataset](https://arxiv.org/abs/2303.12993) | [:octocat:](https://github.com/KuofengGao/ASD) |
| 2023 | CVPR 2023    | [Backdoor Defense via Deconfounded Representation Learning](https://arxiv.org/abs/2303.06818) | [:octocat:](https://github.com/zaixizhang/CBD) |


## Post-training
| Year | Venue                | Paper                                                        | Code                                                         |
| ---- | -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 2023 | CVPR 2023            | [Backdoor Cleansing with Unlabeled Data](https://arxiv.org/abs/2211.12044) | [:octocat:](https://github.com/luluppang/BCU)                |
| 2023 | CVPR 2023            | [Progressive Backdoor Erasing via connecting Backdoor and Adversarial Attacks](https://arxiv.org/abs/2202.06312) | [:octocat:](https://github.com/SeekingDream/CVPR23_EfficFrog) |
| 2023 | CVPR 2023            | [MEDIC: Remove Model Backdoors via Importance Driven Cloning](https://openreview.net/forum?id=qHcR93949op) |                                                              |
| 2023 | CVPR 2023            | [Detecting Backdoors During the Inference Stage Based on Corruption Robustness Consistency](https://arxiv.org/abs/2303.18191) |                                                              |
| 2023 | CVPR 2023            | [Detecting Backdoors in Pre-trained Encoders](https://arxiv.org/abs/2303.15180) | [:octocat:](https://github.com/GiantSeaweed/DECREE)          |
| 2023 | CVPR 2023            | [Defending Against Patch-based Backdoor Attacks on Self-Supervised Learning](https://arxiv.org/abs/2304.01482) | [:octocat:](https://github.com/UCDvision/PatchSearch)        |
| 2023 | CVPR 2023            | [Single Image Backdoor Inversion via Robust Smoothed Classifiers](https://arxiv.org/abs/2304.01482) | [:octocat:](https://github.com/locuslab/smoothinv)           |
| 2023 | CVPR 2023            | [Don't FREAK Out: A Frequency-Inspired Approach to Detecting Backdoor Poisoned Samples in DNNs](https://arxiv.org/abs/2303.13211) |                                                              |
| 2023 | ICLR 2023            | [UNICORN: A Unified Backdoor Trigger Inversion Framework](https://openreview.net/forum?id=Mj7K4lglGyj) | [:octocat:](https://github.com/RU-System-Software-and-Security/UNICORN) |
| 2023 | ICLR 2023            | [Distilling Cognitive Backdoor Patterns within an Image](https://openreview.net/forum?id=S3D9NLzjnQ5) | [:octocat:](https://github.com/HanxunH/CognitiveDistillation) |
| 2023 | ICLR 2023            | [SCALE-UP: An Efficient Black-box Input-level Backdoor Detection via Analyzing Scaled Prediction Consistency](https://openreview.net/forum?id=o0LFPcoFKnr) | [:octocat:](https://github.com/JunfengGo/SCALE-UP%7D)        |
| 2023 | ICLR 2023            | [FLIP: A Provable Defense Framework for Backdoor Mitigation in Federated Learning](https://openreview.net/forum?id=Xo2E217_M4n) | [:octocat:](https://github.com/KaiyuanZh/FLIP)               |
| 2023 | ICLR 2023            | [Towards Robustness Certification Against Universal Perturbations](https://openreview.net/forum?id=7GEvPKxjtt) | [:octocat:](https://github.com/KaiyuanZh/FLIP)               |
| 2023 | ICLR 2023            | [Incompatibility Clustering as a Defense Against Backdoor Poisoning Attacks](https://openreview.net/forum?id=mkJm5Uy4HrQ) |                                                              |
| 2023 | ACL 2023             | [Defending against Insertion-based Textual Backdoor Attacks via Attribution](https://arxiv.org/abs/2305.02394) |                                                              |
| 2023 | ACL 2023             | [Diffusion Theory as a Scalpel: Detecting and Purifying Poisonous Dimensions in Pre-trained Language Models Caused by Backdoor or Bias](https://arxiv.org/abs/2305.04547) |                                                              |
| 2023 | USENIX Security 2023 | [PORE: Provably Robust Recommender Systems against Data Poisoning Attacks](https://arxiv.org/abs/2303.14601) |                                                              |


# ⚙Toolbox

| Name            | Venue        | Paper                                                        | Code                                                    |
| --------------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------- |
| BackdoorBench   | NeurIPS 2022 | [BackdoorBench: A Comprehensive Benchmark of Backdoor Learning](https://arxiv.org/abs/2206.12654) | [:octocat:](https://github.com/SCLBD/backdoorbench)     |
| OpenBackdoor    | NeurIPS 2022 | [A Unified Evaluation of Textual Backdoor Learning: Frameworks and Benchmarks](https://arxiv.org/abs/2206.08514) | [:octocat:](https://github.com/thunlp/OpenBackdoor)     |
| TrojanZoo       | EuroS&P 2022 | [TrojanZoo: Towards Unified, Holistic, and Practical Evaluation of Neural Backdoors]() | [:octocat:](https://github.com/ain-soph/trojanzoo)      |
| BackdoorBox     |              | [BackdoorBox: An Open-sourced Python Toolbox for Backdoor Attacks and Defenses](https://arxiv.org/abs/2302.01762) | [:octocat:](https://github.com/THUYimingLi/BackdoorBox) |
| BackdoorToolbox |              |                                                              | [:octocat:](https://github.com/vtu81/backdoor-toolbox)  |
