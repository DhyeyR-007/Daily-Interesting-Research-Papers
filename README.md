# Daily Digest




## Interesting papers:

1. Class-Modulated Top-𝐾 Logit Adjustment for long-tailed visual recognition
2. Plug-and-Play Reweighting for Resilient Collaborative Decision-Making in Connected Autonomous Driving
3. SearchAD: Large-Scale Rare Image Retrieval Dataset for Autonomous Driving
4. Selectivity Drives Efficiency: Dataset Pruning for Visual Place Recognition
5. Are All Tokens Necessary for Visual Place Recognition? An Empirical Study of Token Reduction for Efficient Inference.

## Place Recognition-specific papers:

1. **Filter Early, Match Late: Improving Network-Based Visual Place Recognition (IROS 2019)**: The authors investigate feature map filtering in CNNs for VPR, probing which individual feature maps encode which visual features, with the objective of removing feature maps that detract from recognizing locations across appearance changes. Their results reveal the inner workings of the network — demonstrating that a neural network can have a portion of its feature maps completely removed and yet a holistic feature vector can still be extracted from a higher convolutional layer.
2. **Feature Map Filtering: Improving Visual Place Recognition with Convolutional Calibration (ACRA 2018)**: A precursor to the above. This paper proposes calibrating a CNN-based VPR system by selecting the subset of feature maps that best encodes the visual features consistent between two different appearances of the same location — which is essentially an analysis of what each convolutional filter is doing.
3. **Semantic Reinforced Attention Learning for VPR  (ICRA 2021)**: By exploiting the interpretability of a local weighting scheme, the authors propose a semantic constrained initialization so that local attention can be reinforced by semantic priors. This involves an analysis of what NetVLAD-style clusters encode semantically.
4. **A Hierarchical Dual Model of Environment- and Place-Specific Utility for VPR (RA-L/IROS 2021)**: This paper presents an approach to deduce two key types of utility for VPR: the utility of visual cues specific to an environment, and to a particular place. They estimate the environment- and place-specific utility of VLAD clusters in an unsupervised manner and provide analysis demonstrating that unsupervised cluster selection results in semantically meaningful results, and that finer-grained categorization often has higher utility for VPR than high-level semantic categorization (e.g. building, road). This is a form of mechanistic analysis of what NetVLAD's internal clusters are actually encoding.
5. **VDNA-PR: Using General Dataset Representations for Robust Sequential Visual Place Recognition (ICRA 2024)**




## Datasets:


| Dataset                                       | Notes |
|----------------------------------------------|-------|
| nuScenes (MTGS: Multi-Traversal Gaussian Splatting) |       |
| S3E: A Multi-Robot Multimodal Dataset for Collaborative SLAM |       |
|FoMo: A Multi-Season Dataset for Robot Navigation in Foret Montmorency (2026) | 
| CU-Multi: A Dataset for Multi-Robot Collaborative Perception               |       |
| Multiagent Multitraversal Multimodal Self-Driving: Open MARS Dataset |       |
| ROVER: A Multi-Season Dataset for Visual SLAM|       |








