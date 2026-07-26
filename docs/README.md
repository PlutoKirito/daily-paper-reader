<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-26
- 运行时间：2026-07-26 21:32:04 UTC
- 运行状态：成功
- 本次总论文数：16
- 精读区：4
- 速读区：12

### 今日简报（AI）
今日共处理16篇论文，精读4篇聚焦极端比特率感知视频压缩与图像编码并行化加速。最值得关注的是《Group-of-Latents》通过掩码潜变量生成实现超低比特率视频压缩，以及《Wavefront Parallelization》用波前并行化显著提升图像编码效率。建议普通读者优先精读这两篇：前者解决极端压缩下的感知质量，后者突破编码速度瓶颈。
- 详情：[/202607/26/README](/202607/26/README)

### 精读区论文标签
1. [Group-of-Latents: Perceptual Video Compression at Extreme Bitrates via Masked Latent Generative Modeling](/202607/26/2607.19437v1-group-of-latents-perceptual-video-compression-at-extreme-bitrates-via-masked-latent-generative-modeling)  
   标签：评分：10.0/10、query:vcodec
   evidence：基于扩散Transformer的生成式视频压缩，使用掩码潜变量建模
2. [Wavefront Parallelization for Efficient Learned Image Compression](/202607/26/2607.19082v1-wavefront-parallelization-for-efficient-learned-image-compression)  
   标签：评分：8.0/10、query:train-trick
   evidence：加速自回归上下文模型，实现低复杂度编码
3. [BLUE: Semantics-Preserving Video Compression for Efficient Vision-Language Surveillance Analytics](/202607/26/2607.19515v1-blue-semantics-preserving-video-compression-for-efficient-vision-language-surveillance-analytics)  
   标签：评分：8.0/10、query:vcodec
   evidence：保持语义的视频压缩，与生成式视频压缩和感知优化一致
4. [Ms. Forcing: Efficient Streaming Video Generation with Multi-Scale Patchification and Attention](/202607/26/2607.20940v1-ms-forcing-efficient-streaming-video-generation-with-multi-scale-patchification-and-attention)  
   标签：评分：8.0/10、query:vcodec
   evidence：高效流式视频生成：多尺度分块与注意力

### 速读区论文标签
1. [Efficient Audio-Visual Event Recognition via Knowledge Distillation and Dynamic INT8 Quantization of a Hybrid Cross-Attention Network](/202607/26/2607.16980v1-efficient-audio-visual-event-recognition-via-knowledge-distillation-and-dynamic-int8-quantization-of-a-hybrid-cross-attention-network)  
   标签：评分：7.0/10、query:train-trick
   evidence：结合知识蒸馏和INT8量化实现高效模型，可应用于视频压缩训练
2. [Pixel-Space Diffusion Transformers](/202607/26/2607.17585v1-pixel-space-diffusion-transformers)  
   标签：评分：7.0/10、query:vcodec
   evidence：像素空间扩散Transformer，与潜扩散相关
3. [ERank in Latent Space as an Image-Complexity and Richness Measure](/202607/26/2607.19315v2-erank-in-latent-space-as-an-image-complexity-and-richness-measure)  
   标签：评分：7.0/10、query:entropy-coding
   evidence：提出与码率相关的ERank度量，可用于率失真优化
4. [VQ-Transplant: Efficient VQ-Module Integration for Pre-trained Visual Tokenizers](/202607/26/2607.19575v1-vq-transplant-efficient-vq-module-integration-for-pre-trained-visual-tokenizers)  
   标签：评分：7.0/10、query:vcodec
   evidence：即插即用的向量量化模块集成到分词器
5. [Importance-Aware OBS Pruning for Diffusion Models](/202607/26/2607.20048v1-importance-aware-obs-pruning-for-diffusion-models)  
   标签：评分：7.0/10、query:train-trick
   evidence：提出扩散模型的重要性感知剪枝，与轻量化编解码器剪枝相关
6. [Source-Prior-Driven Selective Adaptation for Efficient Diffusion Model Finetuning](/202607/26/2607.20913v1-source-prior-driven-selective-adaptation-for-efficient-diffusion-model-finetuning)  
   标签：评分：7.0/10、query:vcodec
   evidence：用于高效扩散模型微调的选择性适配方法
7. [VibeVoice-ASR-BitNet Technical Report](/202607/26/2607.21075v1-vibevoice-asr-bitnet-technical-report)  
   标签：评分：7.0/10、query:train-trick
   evidence：针对ASR模型压缩的渐进式量化感知训练
8. [HarmoHOI: Harmonizing Appearance and 3D Motion for Multi-view Hand-Object Interaction Synthesis](/202607/26/2607.17097v1-harmohoi-harmonizing-appearance-and-3d-motion-for-multi-view-hand-object-interaction-synthesis)  
   标签：评分：6.0/10、query:vcodec
   evidence：基于扩散的多视角视频生成，可应用于生成式视频压缩
9. [Mage-Flow: An Efficient Native-Resolution Foundation Model for Image Generation and Editing](/202607/26/2607.19064v1-mage-flow-an-efficient-native-resolution-foundation-model-for-image-generation-and-editing)  
   标签：评分：6.0/10、query:vcodec
   evidence：高效的潜在扩散图像生成模型，可迁移至视频压缩
10. [Beyond Independent Optimization: Compression, MoE Routing, and Quantization Interactions in Multimodal Edge Intelligence](/202607/26/2607.20981v1-beyond-independent-optimization-compression-moe-routing-and-quantization-interactions-in-multimodal-edge-intelligence)  
   标签：评分：6.0/10、query:train-trick
   evidence：综述涵盖视觉标记压缩和边缘部署量化
11. [Self-Supervised Learning of Structured Dynamics from Videos](/202607/26/2607.21576v1-self-supervised-learning-of-structured-dynamics-from-videos)  
   标签：评分：6.0/10、query:vcodec
   evidence：自监督学习结构化动态包含运动分解，与联合运动估计相关
12. [GraphVid: Interactive Graph-Controllable Video Generation](/202607/26/2607.21580v1-graphvid-interactive-graph-controllable-video-generation)  
   标签：评分：6.0/10、query:vcodec
   evidence：图条件视频生成模型，与潜在扩散和生成式视频压缩相关


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
