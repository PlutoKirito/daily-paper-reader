<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-25
- 运行时间：2026-07-25 21:36:08 UTC
- 运行状态：成功
- 本次总论文数：18
- 精读区：5
- 速读区：13

### 今日简报（AI）
今日精读2篇顶级论文（9.0分），速读13篇，重点关注信息表示极限与极端比特率视频压缩。  
最值得深入的是《Rate-Distortion-Perception Theory》对信息论边界的重构，以及《Group-of-Latents》提出的掩码潜变量生成模型在超低比特率下的感知压缩突破。  
建议普通读者优先精读这两篇高分论文，把握率失真感知权衡与生成式压缩的核心思想，其余速读文章可快速了解向量量化、3D扩散及视觉语言模型剪枝等方向的新进展。
- 详情：[/202607/25/README](/202607/25/README)

### 精读区论文标签
1. [Rate-Distortion-Perception Theory: Redefining the Fundamental Limits of Information Representation](/202607/25/2607.17232v1-rate-distortion-perception-theory-redefining-the-fundamental-limits-of-information-representation)  
   标签：评分：9.0/10、query:vcodec
   evidence：率失真感知理论，直接针对感知率失真优化
2. [Group-of-Latents: Perceptual Video Compression at Extreme Bitrates via Masked Latent Generative Modeling](/202607/25/2607.19437v1-group-of-latents-perceptual-video-compression-at-extreme-bitrates-via-masked-latent-generative-modeling)  
   标签：评分：9.0/10、query:vcodec
   evidence：基于隐扩散的生成式视频压缩
3. [Generative Transmission: Rethinking Computation, Bandwidth, and Memory in Communication](/202607/25/2607.17482v1-generative-transmission-rethinking-computation-bandwidth-and-memory-in-communication)  
   标签：评分：8.0/10、query:vcodec
   evidence：提出基于生成模型的视频传输，超低带宽下侧重感知效用
4. [Wavefront Parallelization for Efficient Learned Image Compression](/202607/25/2607.19082v1-wavefront-parallelization-for-efficient-learned-image-compression)  
   标签：评分：8.0/10、query:entropy-coding
   evidence：无训练的波前并行化加速学习图像压缩中的自回归上下文模型，直接适用于神经熵编码
5. [Importance-Aware OBS Pruning for Diffusion Models](/202607/25/2607.20048v1-importance-aware-obs-pruning-for-diffusion-models)  
   标签：评分：8.0/10、query:train-trick
   evidence：扩散模型的重要性感知剪枝，与轻量码流的模型剪枝相关

### 速读区论文标签
1. [Distributional Matching for Vector Quantization: A Unified Theoretical and Empirical Framework](/202607/25/2607.15933v1-distributional-matching-for-vector-quantization-a-unified-theoretical-and-empirical-framework)  
   标签：评分：7.0/10、query:train-trick
   evidence：提出分布匹配框架用于向量量化，解决码本崩溃和梯度失配问题
2. [Continuous 3-D Latent Diffusion for Medical Generation and Reconstruction](/202607/25/2607.16491v1-continuous-3-d-latent-diffusion-for-medical-generation-and-reconstruction)  
   标签：评分：7.0/10、query:vcodec
   evidence：用于医学生成和重建的连续3D潜在扩散模型
3. [Searching for Task-Specific Vision Paths: Evolutionary Block Pruning Across Vision-Language Models](/202607/25/2607.17052v1-searching-for-task-specific-vision-paths-evolutionary-block-pruning-across-vision-language-models)  
   标签：评分：7.0/10、query:train-trick
   evidence：视觉语言模型的进化块剪枝方法，可迁移至视频编解码器剪枝
4. [SANA-Video 2.0: Hybrid Linear Attention with Attention Residuals for Efficient Video Generation](/202607/25/2607.21553v1-sana-video-20-hybrid-linear-attention-with-attention-residuals-for-efficient-video-generation)  
   标签：评分：7.0/10、query:vcodec
   evidence：混合视频扩散Transformer，利用潜在扩散实现高效视频生成
5. [Test-Time Noise Guided Adaptation for Realistic Autoregressive Video Generation](/202607/25/2607.15849v1-test-time-noise-guided-adaptation-for-realistic-autoregressive-video-generation)  
   标签：评分：6.0/10、query:vcodec
   evidence：提出测试时噪声引导的自适应方法用于自回归视频生成，解决误差累积，与扩散视频压缩直接相关
6. [Efficient Audio-Visual Event Recognition via Knowledge Distillation and Dynamic INT8 Quantization of a Hybrid Cross-Attention Network](/202607/25/2607.16980v1-efficient-audio-visual-event-recognition-via-knowledge-distillation-and-dynamic-int8-quantization-of-a-hybrid-cross-attention-network)  
   标签：评分：6.0/10、query:train-trick
   evidence：知识蒸馏与动态INT8量化用于高效模型压缩；可应用于神经视频压缩训练
7. [CoCurve: Cross-Module Co-Pruning Curvature for Training-Free Structured LLM Pruning](/202607/25/2607.17568v1-cocurve-cross-module-co-pruning-curvature-for-training-free-structured-llm-pruning)  
   标签：评分：6.0/10、query:train-trick
   evidence：Transformer结构化剪枝方法；可迁移至视频编码器剪枝
8. [Pixel-Space Diffusion Transformers](/202607/25/2607.17585v2-pixel-space-diffusion-transformers)  
   标签：评分：6.0/10、query:vcodec
   evidence：讨论潜在空间与像素空间扩散，与视频潜在扩散相关
9. [Surprise Forcing: What to Remember, When to Skip in Long Video Generation](/202607/25/2607.18436v1-surprise-forcing-what-to-remember-when-to-skip-in-long-video-generation)  
   标签：评分：6.0/10、query:vcodec
   evidence：流式自回归扩散用于长视频生成，与潜在扩散相关
10. [Self Gradient Forcing: Native Long Video Extrapolation](/202607/25/2607.20368v1-self-gradient-forcing-native-long-video-extrapolation)  
   标签：评分：6.0/10、query:vcodec
   evidence：自回归视频扩散的双通训练；与潜在扩散及视频压缩训练策略相关
11. [RealVDeblur: One-Step Diffusion for Generalizable Real-World Video Deblurring](/202607/25/2607.20628v1-realvdeblur-one-step-diffusion-for-generalizable-real-world-video-deblurring)  
   标签：评分：6.0/10、query:vcodec
   evidence：视频扩散先验用于恢复
12. [Beyond Independent Optimization: Compression, MoE Routing, and Quantization Interactions in Multimodal Edge Intelligence](/202607/25/2607.20981v1-beyond-independent-optimization-compression-moe-routing-and-quantization-interactions-in-multimodal-edge-intelligence)  
   标签：评分：6.0/10、query:train-trick
   evidence：涵盖低比特量化、边缘部署和token压缩等高效多模态推理技术
13. [ElasticTTT: Prior-Preserving Test-Time Tuning for Video Editing](/202607/25/2607.21529v1-elasticttt-prior-preserving-test-time-tuning-for-video-editing)  
   标签：评分：6.0/10、query:vcodec
   evidence：面向视频编辑的扩散模型测试时调优与先验保持；可应用于生成式视频压缩和扩散模型编解码


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
