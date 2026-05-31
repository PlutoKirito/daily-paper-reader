<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-31
- 运行时间：2026-05-31 20:20:29 UTC
- 运行状态：成功
- 本次总论文数：15
- 精读区：3
- 速读区：12

### 今日简报（AI）
今日推荐15篇论文，重点精读量化训练与视频生成两大方向，均获8分高分。  
最值得关注的是《Scale When Needed》的自适应混合精度量化训练和《Paris 2.0》的去中心化视频扩散模型，速读中HEVC分区加速（7分）也值得一瞥。  
建议优先精读两篇8分论文，再快速浏览速读列表中的编码与融合方向以拓展视野。
- 详情：[/202605/31/README](/202605/31/README)

### 精读区论文标签
1. [Scale When Needed: Adaptive Neuron-level Mixed Precision Quantization Aware Training](/202605/31/2605.25054v1-scale-when-needed-adaptive-neuron-level-mixed-precision-quantization-aware-training)  
   标签：评分：8.0/10、query:train-trick
   evidence：神经元级混合精度量化感知训练方法可直接用于视频编码模型
2. [Paris 2.0: A Decentralized Diffusion Model for Video Generation](/202605/31/2605.26064v1-paris-20-a-decentralized-diffusion-model-for-video-generation)  
   标签：评分：8.0/10、query:vcodec
   evidence：去中心化扩散模型用于视频生成
3. [JLT: Clean-Latent Prediction in Latent Diffusion Transformers](/202605/31/2605.27102v2-jlt-clean-latent-prediction-in-latent-diffusion-transformers)  
   标签：评分：8.0/10、query:vcodec
   evidence：研究潜在扩散Transformer中的纯净潜在预测，直接针对潜在扩散技术

### 速读区论文标签
1. [Accelerating HEVC Intra Partitioning via a CNN-Hierarchical Attention Transformer Hybrid](/202605/31/2605.29063v1-accelerating-hevc-intra-partitioning-via-a-cnn-hierarchical-attention-transformer-hybrid)  
   标签：评分：7.0/10、query:train-trick
   evidence：利用深度学习加速HEVC帧内划分，降低复杂度
2. [CodecSplat: Ultra-Compact Latent Coding for Feed-Forward 3D Gaussian Splatting](/202605/31/2605.25563v1-codecsplat-ultra-compact-latent-coding-for-feed-forward-3d-gaussian-splatting)  
   标签：评分：6.0/10、query:entropy-coding
   evidence：用于3D表示的熵编码场景位流
3. [DRFusion: Drift-Resilient Temporally Consistent Infrared-Visible Video Fusion](/202605/31/2605.25775v1-drfusion-drift-resilient-temporally-consistent-infrared-visible-video-fusion)  
   标签：评分：6.0/10、query:vcodec
   evidence：基于扩散的历史条件运动生成视频融合
4. [Max-Window Scale Estimation for Near-Lossless HiF8 W8A8 Quantization-Aware Training](/202605/31/2605.26189v1-max-window-scale-estimation-for-near-lossless-hif8-w8a8-quantization-aware-training)  
   标签：评分：6.0/10、query:train-trick
   evidence：HiF8 W8A8量化感知训练失败模式分析，延迟张量缩放技术，可应用于视频编码量化
5. [Quantized Keys Steal Attention: Bias Correction for KV-Cache Compression in Video Diffusion](/202605/31/2605.26266v1-quantized-keys-steal-attention-bias-correction-for-kv-cache-compression-in-video-diffusion)  
   标签：评分：6.0/10、query:vcodec
   evidence：量化KV缓存偏置校正、视频扩散、Jensen偏置
6. [O-MARC: Omni Memory-Augmented Compression Distillation for Efficient Video Understanding](/202605/31/2605.26584v1-o-marc-omni-memory-augmented-compression-distillation-for-efficient-video-understanding)  
   标签：评分：6.0/10、query:train-trick
   evidence：面向视频理解的压缩蒸馏，内存增强压缩，知识蒸馏用于高效模型
7. [AdaMerge: Salience-Aware Adaptive Token Merging for Training-Free Acceleration of Vision Transformers](/202605/31/2605.27465v1-adamerge-salience-aware-adaptive-token-merging-for-training-free-acceleration-of-vision-transformers)  
   标签：评分：6.0/10、query:train-trick
   evidence：令牌合并加速视觉Transformer，可直接应用于使用ViT的视频编码模型
8. [Not All NVFP4 QAT Recipes Are Equal: How Architecture and Scale Shape Model Quality for Anomaly Segmentation](/202605/31/2605.27616v1-not-all-nvfp4-qat-recipes-are-equal-how-architecture-and-scale-shape-model-quality-for-anomaly-segmentation)  
   标签：评分：6.0/10、query:train-trick
   evidence：面向异常分割的FP4量化感知训练，其QAT方法可应用于视频编码模型量化
9. [Structure over Pixels: Learning Variable-Length Visual Programs](/202605/31/2605.27696v2-structure-over-pixels-learning-variable-length-visual-programs)  
   标签：评分：6.0/10、query:entropy-coding
   evidence：使用率失真探测学习可变长度视觉令牌序列；适用于神经编解码器的率失真优化
10. [Sequential Neural Probabilistic Amplitude Shaping: Learning the Channel's Language](/202605/31/2605.28143v1-sequential-neural-probabilistic-amplitude-shaping-learning-the-channels-language)  
   标签：评分：6.0/10、query:entropy-coding
   evidence：神经概率幅度整形结合算术分布匹配，与熵编码相关
11. [DriveWAM: Video Generative Priors Enable Scalable World-Action Modeling for Autonomous Driving](/202605/31/2605.28544v1-drivewam-video-generative-priors-enable-scalable-world-action-modeling-for-autonomous-driving)  
   标签：评分：6.0/10、query:vcodec
   evidence：视频扩散变换器、生成式先验、联合流匹配目标
12. [KGEdit: Ambiguity-Aware Knowledge Graphs for Training-Free Precise Video Generation and Editing](/202605/31/2605.29509v1-kgedit-ambiguity-aware-knowledge-graphs-for-training-free-precise-video-generation-and-editing)  
   标签：评分：6.0/10、query:vcodec
   evidence：知识图谱引导的视频扩散生成与编辑


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
