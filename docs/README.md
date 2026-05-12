<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-12
- 运行时间：2026-05-12 21:43:44 UTC
- 运行状态：成功
- 本次总论文数：21
- 精读区：8
- 速读区：13

### 今日简报（AI）
今日精选 21 篇前沿成果，重点突破轻量化实时神经编解码与高效图像压缩技术。
LiVeAction 以非对称设计实现 9.5 分实时性能，Cool-chic 5.0 则显著加速了过拟合图像压缩。
推荐关注神经编解码的工程化落地，以及 3DGS 与扩散模型在端侧的剪枝量化方案。
- 详情：[/202605/12/README](/202605/12/README)

### 精读区论文标签
1. [LiVeAction: a Lightweight, Versatile, and Asymmetric Neural Codec Design for Real-time Operation](/202605/12/2605.06628v1-liveaction-a-lightweight-versatile-and-asymmetric-neural-codec-design-for-real-time-operation)  
   标签：评分：9.5/10、query:entropy-coding
   evidence：用于实时运行的轻量级非对称神经编解码器设计
2. [Cool-chic 5.0: Faster Encoding and Inter-Feature Entropy Modeling for Overfitted Image Compression](/202605/12/2605.02726v1-cool-chic-50-faster-encoding-and-inter-feature-entropy-modeling-for-overfitted-image-compression)  
   标签：评分：9.0/10、query:entropy-coding
   evidence：过拟合图像压缩中的特征间熵建模与解码器架构更新
3. [Tube-Structured Incremental Semantic HARQ for Generative Video Receivers](/202605/12/2605.09897v1-tube-structured-incremental-semantic-harq-for-generative-video-receivers)  
   标签：评分：9.0/10、query:vcodec
   evidence：用于从紧凑语义重建视频的生成式语义通信
4. [Reconstruction or Semantics? What Makes a Latent Space Useful for Robotic World Models](/202605/12/2605.06388v1-reconstruction-or-semantics-what-makes-a-latent-space-useful-for-robotic-world-models)  
   标签：评分：8.5/10、query:vcodec
   evidence：评估潜在扩散模型（LDM）和潜在空间在基于视频的世界模型中的效用
5. [Continuous First, Discrete Later: VQ-VAEs Without Dimensional Collapse](/202605/12/2605.06870v1-continuous-first-discrete-later-vq-vaes-without-dimensional-collapse)  
   标签：评分：8.5/10、query:train-trick
   evidence：引入预热阶段训练策略和率失真理论，以防止VQ-VAE维度坍缩。
6. [Forcing-KV: Hybrid KV Cache Compression for Efficient Autoregressive Video Diffusion Models](/202605/12/2605.09681v1-forcing-kv-hybrid-kv-cache-compression-for-efficient-autoregressive-video-diffusion-models)  
   标签：评分：8.5/10、query:vcodec
   evidence：自回归视频扩散模型的KV缓存压缩
7. [What Matters in Practical Learned Image Compression](/202605/12/2605.05148v1-what-matters-in-practical-learned-image-compression)  
   标签：评分：8.0/10、query:entropy-coding
   evidence：针对感知质量和运行时间进行联合优化，并使用神经架构搜索
8. [ViTok-v2: Scaling Native Resolution Auto-Encoders to 5 Billion Parameters](/202605/12/2605.05331v1-vitok-v2-scaling-native-resolution-auto-encoders-to-5-billion-parameters)  
   标签：评分：8.0/10、query:entropy-coding
   evidence：扩展原生分辨率自编码器用于图像重建与生成

### 速读区论文标签
1. [GETA-3DGS: Automatic Joint Structured Pruning and Quantization for 3D Gaussian Splatting](/202605/12/2605.02086v1-geta-3dgs-automatic-joint-structured-pruning-and-quantization-for-3d-gaussian-splatting)  
   标签：评分：8.0/10、query:train-trick
   evidence：用于3DGS压缩的联合结构化剪枝与量化框架
2. [Video Generation with Predictive Latents](/202605/12/2605.02134v1-video-generation-with-predictive-latents)  
   标签：评分：8.0/10、query:vcodec
   evidence：用于潜视频生成建模和预测性重建的视频VAE
3. [TOC-SR: Task-Optimal Compact diffusion for Image Super Resolution](/202605/12/2605.02767v1-toc-sr-task-optimal-compact-diffusion-for-image-super-resolution)  
   标签：评分：8.0/10、query:train-trick
   evidence：紧凑扩散骨干网络发现与生成式蒸馏以提升效率
4. [DiBA: Diagonal and Binary Matrix Approximation for Neural Network Weight Compression](/202605/12/2605.05994v1-diba-diagonal-and-binary-matrix-approximation-for-neural-network-weight-compression)  
   标签：评分：8.0/10、query:train-trick
   evidence：用于神经网络权重压缩和减少存储的矩阵近似
5. [SoLAR: Error-Resilient Streamable Long-Horizon Free-Viewpoint Video Reconstruction with Anchor Activation and Latent Recalibration](/202605/12/2605.07346v1-solar-error-resilient-streamable-long-horizon-free-viewpoint-video-reconstruction-with-anchor-activation-and-latent-recalibration)  
   标签：评分：8.0/10、query:entropy-coding
   evidence：体积视频表示的率失真优化框架
6. [Amortized-Precision Quantization for Early-Exit Vision Transformers](/202605/12/2605.07317v1-amortized-precision-quantization-for-early-exit-vision-transformers)  
   标签：评分：7.5/10、query:train-trick
   evidence：为视觉Transformer提出摊销精度量化（APQ）以优化位宽
7. [Edge-Efficient Image Restoration: Transformer Distillation into State-Space Models](/202605/12/2605.02794v1-edge-efficient-image-restoration-transformer-distillation-into-state-space-models)  
   标签：评分：7.0/10、query:train-trick
   evidence：轻量化架构的特征蒸馏替代方案
8. [Rethinking Temporal Consistency in Video Object-Centric Learning: From Prediction to Correspondence](/202605/12/2605.03650v1-rethinking-temporal-consistency-in-video-object-centric-learning-from-prediction-to-correspondence)  
   标签：评分：7.0/10、query:vcodec
   evidence：重新思考视频中从预测到对应的时域一致性
9. [Real Image Denoising with Knowledge Distillation for High-Performance Mobile NPUs](/202605/12/2605.03680v1-real-image-denoising-with-knowledge-distillation-for-high-performance-mobile-npus)  
   标签：评分：7.0/10、query:train-trick
   evidence：针对移动端NPU的轻量级学生网络知识蒸馏
10. [SlimDiffSR: Toward Lightweight and Efficient Remote Sensing Image Super-Resolution via Diffusion Model Distillation](/202605/12/2605.02198v1-slimdiffsr-toward-lightweight-and-efficient-remote-sensing-image-super-resolution-via-diffusion-model-distillation)  
   标签：评分：6.5/10、query:train-trick
   evidence：用于轻量化超分辨率的扩散模型蒸馏
11. [Learning to Focus Synthetic Aperture Radar On-line with State-Space Models](/202605/12/2605.10340v1-learning-to-focus-synthetic-aperture-radar-on-line-with-state-space-models)  
   标签：评分：6.5/10、query:train-trick
   evidence：使用教师-学生蒸馏和多阶段损失进行模型训练
12. [GemDepth: Geometry-Embedded Features for 3D-Consistent Video Depth](/202605/12/2605.10525v1-gemdepth-geometry-embedded-features-for-3d-consistent-video-depth)  
   标签：评分：6.5/10、query:vcodec
   evidence：引入几何嵌入模块用于帧间相机位姿预测和运动感知。
13. [WindowQuant: Mixed-Precision KV Cache Quantization based on Window-Level Similarity for VLMs Inference Optimization](/202605/12/2605.02262v1-windowquant-mixed-precision-kv-cache-quantization-based-on-window-level-similarity-for-vlms-inference-optimization)  
   标签：评分：6.0/10、query:train-trick
   evidence：基于窗口级相似度的混合精度KV缓存量化


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
