<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-01
- 运行时间：2026-08-01 21:34:05 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：5
- 速读区：8

### 今日简报（AI）
今日精读13篇论文，聚焦生成式视频压缩，两篇满分工作《Generative Video Compression with Adaptive Score Distillation》与《ReGenVC》最值得关注，均实现超低码率下的高质量编码；速读中《SPRKD》等三篇涉及知识蒸馏与高斯泼溅压缩，值得顺带一阅。建议优先复现ReGenVC的实时编码流程，再结合SPRKD验证蒸馏对压缩模型的轻量化效果。
- 详情：[/202608/01/README](/202608/01/README)

### 精读区论文标签
1. [Generative Video Compression with Adaptive Score Distillation](/202608/01/2607.22772v1-generative-video-compression-with-adaptive-score-distillation)  
   标签：评分：10.0/10、query:vcodec
   evidence：直接面向生成式视频压缩，使用从零训练的视频扩散模型与自适应分数蒸馏
2. [ReGenVC: End-to-End Real-Time Generative Video Coding at Ultra-Low Bitrate](/202608/01/2607.28144v1-regenvc-end-to-end-real-time-generative-video-coding-at-ultra-low-bitrate)  
   标签：评分：10.0/10、query:vcodec
   evidence：端到端生成式视频编码，扩散解码器实现超低码率
3. [Codebook Capacity Governs Perceptual Quality Across Resolutions in Hierarchical Discrete Video Compression](/202608/01/2607.23366v1-codebook-capacity-governs-perceptual-quality-across-resolutions-in-hierarchical-discrete-video-compression)  
   标签：评分：9.0/10、query:vcodec
   evidence：分层离散视频压缩；码本容量与分辨率、感知质量的关系
4. [ENCORE: Event-Assisted Complementary Motion Refinement for Learned Video Compression](/202608/01/2607.28020v1-encore-event-assisted-complementary-motion-refinement-for-learned-video-compression)  
   标签：评分：9.0/10、query:vcodec
   evidence：事件辅助互补运动细化用于学习型视频压缩
5. [OmniCache: Multidimensional Hierarchical Feature Caching For Diffusion Models](/202608/01/2607.23844v1-omnicache-multidimensional-hierarchical-feature-caching-for-diffusion-models)  
   标签：评分：8.0/10、query:vcodec
   evidence：面向视频扩散模型的多维特征缓存，直接涉及潜在扩散与帧间/运动冗余

### 速读区论文标签
1. [SPRKD: Effective Knowledge Distillation for Deep Neural Networks via Saddle Region Approximation](/202608/01/2607.23346v1-sprkd-effective-knowledge-distillation-for-deep-neural-networks-via-saddle-region-approximation)  
   标签：评分：7.0/10、query:train-trick
   evidence：通用知识蒸馏方法，可应用于轻量化神经编解码器训练
2. [GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](/202608/01/2607.24403v1-gensplatcodec-feed-forward-gaussian-splatting-compression-via-one-step-diffusion)  
   标签：评分：7.0/10、query:vcodec
   evidence：使用一步扩散的生成式压缩，用于低码率解码
3. [Mage-VL: An Efficient Codec-Native Streaming Multimodal Foundation Model](/202608/01/2607.24904v1-mage-vl-an-efficient-codec-native-streaming-multimodal-foundation-model)  
   标签：评分：7.0/10、query:vcodec
   evidence：利用I/P帧间的运动向量与残差能量进行选择性编码，联合实现压缩与流式感知
4. [VAD to the Bone: Ultra-Tiny Speech Activity Detection for Edge Deployment](/202608/01/2607.25870v1-vad-to-the-bone-ultra-tiny-speech-activity-detection-for-edge-deployment)  
   标签：评分：7.0/10、query:train-trick
   evidence：面向边缘部署的剪枝、自蒸馏与量化感知训练，可迁移到神经视频编码器的训练技巧
5. [Soft-Constrained Optimization of Latent Space in Variational Autoencoders](/202608/01/2607.23751v1-soft-constrained-optimization-of-latent-space-in-variational-autoencoders)  
   标签：评分：6.0/10、query:entropy-coding
   evidence：VAE潜在空间的熵约束优化，适用于神经编解码器的熵约束与率失真建模
6. [Noise-Free One-Step LoRA for Task-Driven Image Restoration with Diffusion Priors](/202608/01/2607.25390v1-noise-free-one-step-lora-for-task-driven-image-restoration-with-diffusion-priors)  
   标签：评分：6.0/10、query:vcodec
   evidence：基于扩散先验与LoRA的任务驱动图像恢复，与编码中的感知质量及生成式先验相关
7. [ScalablePromptus: Scalable and High-Fidelity Prompt-Based Video Streaming](/202608/01/2607.26106v1-scalablepromptus-scalable-and-high-fidelity-prompt-based-video-streaming)  
   标签：评分：6.0/10、query:vcodec
   evidence：基于提示的生成式视频流，具有可扩展性和鲁棒性，与生成式视频压缩高度相关
8. [Flow Map Learning via Nongradient Vector Flow](/202608/01/2607.26398v1-flow-map-learning-via-nongradient-vector-flow)  
   标签：评分：6.0/10、query:vcodec
   evidence：提出SGFlow学习扩散/流模型的流映射，避免昂贵的反向传播，可加速潜在扩散采样


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
