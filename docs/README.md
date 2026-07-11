<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-07-11
- 运行时间：2026-07-11 20:22:22 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日共精读6篇、速读11篇，重点聚焦视频生成控制与图像滤波优化。最值得关注的是《Track the Noise》在可控视频生成中提出3D运动一致性噪声，以及《Reduced-complexity Adaptive Loop Filtering》通过输入依赖图滤波降低复杂度。建议普通读者优先精读这两篇高分文章获取核心方法，再根据兴趣扩展速读列表中统一自回归与双向扩散的Flex-Forcing或无损压缩的LUMI。
- 详情：[/202607/11/README](/202607/11/README)

### 精读区论文标签
1. [Track the Noise, Move the World:3D-Grounded Motion-Consistent Noise for Controllable Video Generation](/202607/11/2607.02798v1-track-the-noise-move-the-world3d-grounded-motion-consistent-noise-for-controllable-video-generation)  
   标签：评分：9.0/10、query:vcodec
   evidence：基于潜在扩散的可控视频生成
2. [Reduced-complexity Adaptive Loop Filtering via Input-dependent Graph Filters](/202607/11/2607.04985v1-reduced-complexity-adaptive-loop-filtering-via-input-dependent-graph-filters)  
   标签：评分：9.0/10、query:train-trick
   evidence：基于图的低复杂度自适应环路滤波方法用于视频编解码
3. [DiffCVE: Diffusion-based Compressed Video Enhancement](/202607/11/2607.07195v1-diffcve-diffusion-based-compressed-video-enhancement)  
   标签：评分：9.0/10、query:vcodec
   evidence：基于扩散的压缩视频增强方法，利用编码先验，直接相关于生成式视频压缩
4. [CineMobile: On-Device Image-to-Video Diffusion for Cinematic Camera Motion Generation](/202607/11/2607.03803v1-cinemobile-on-device-image-to-video-diffusion-for-cinematic-camera-motion-generation)  
   标签：评分：8.0/10、query:train-trick
   evidence：蒸馏引导剪枝用于高效移动端视频扩散模型
5. [MobileWan: Closing the Quality Gap for Mobile Video Diffusion](/202607/11/2607.06173v1-mobilewan-closing-the-quality-gap-for-mobile-video-diffusion)  
   标签：评分：8.0/10、query:vcodec
   evidence：通过扩散模型部署实现生成式视频压缩
6. [Towards Robust Semantic Video Transmission over Block Erasure Channels](/202607/11/2607.07823v1-towards-robust-semantic-video-transmission-over-block-erasure-channels)  
   标签：评分：8.0/10、query:entropy-coding
   evidence：面向鲁棒传输的神经视频压缩框架

### 速读区论文标签
1. [Flex-Forcing: Towards a Unified Autoregressive and Bidirectional Video Diffusion Model](/202607/11/2607.03509v1-flex-forcing-towards-a-unified-autoregressive-and-bidirectional-video-diffusion-model)  
   标签：评分：7.0/10、query:vcodec
   evidence：统一视频扩散模型，可实现高效生成；与基于扩散的生成式视频压缩相关
2. [LUMI: Tokenizer-Agnostic LLM-Based Lossless Image Compression](/202607/11/2607.08221v1-lumi-tokenizer-agnostic-llm-based-lossless-image-compression)  
   标签：评分：7.0/10、query:entropy-coding
   evidence：基于LLM的无损压缩概率估计
3. [SLORR: Simple and Efficient In-Training Low-Rank Regularization](/202607/11/2607.08754v1-slorr-simple-and-efficient-in-training-low-rank-regularization)  
   标签：评分：7.0/10、query:train-trick
   evidence：训练中低秩正则化方法用于神经网络压缩，可应用于视频编解码
4. [LongE2V: Long-Horizon Event-based Video Reconstruction, Prediction, and Frame Interpolation with Video Diffusion Models](/202607/11/2607.08770v1-longe2v-long-horizon-event-based-video-reconstruction-prediction-and-frame-interpolation-with-video-diffusion-models)  
   标签：评分：7.0/10、query:vcodec
   evidence：基于事件流的视频帧插值和预测，使用视频扩散模型
5. [Variable Bit-width Quantization: Learning Per-Group Precision for "Bigger-but-Smaller" Language Models](/202607/11/2607.02893v1-variable-bit-width-quantization-learning-per-group-precision-for-bigger-but-smaller-language-models)  
   标签：评分：6.0/10、query:train-trick
   evidence：可微量化优化方法，可迁移至视频压缩潜变量量化
6. [Rethinking Depth Pruning for Vision Transformers: A Heterogeneity-Aware Perspective](/202607/11/2607.03784v1-rethinking-depth-pruning-for-vision-transformers-a-heterogeneity-aware-perspective)  
   标签：评分：6.0/10、query:train-trick
   evidence：视觉Transformer深度剪枝
7. [SAD-LoRA: Spectral Alignment for Low-Rank Knowledge Distillation](/202607/11/2607.04306v1-sad-lora-spectral-alignment-for-low-rank-knowledge-distillation)  
   标签：评分：6.0/10、query:train-trick
   evidence：可迁移至视频编解码训练的知识蒸馏方法
8. [Enhancing Video Physical Consistency via Role-aware Joint Training and Modality-decoupled Denoising](/202607/11/2607.04653v2-enhancing-video-physical-consistency-via-role-aware-joint-training-and-modality-decoupled-denoising)  
   标签：评分：6.0/10、query:vcodec
   evidence：角色感知联合训练与光流辅助视频扩散模型
9. [Discovering shared interpretable operations in image compression autoencoders](/202607/11/2607.04839v1-discovering-shared-interpretable-operations-in-image-compression-autoencoders)  
   标签：评分：6.0/10、query:train-trick
   evidence：研究自编码器内部操作以实现低复杂度图像压缩，可迁移到视频编解码
10. [Semantic Video Communication via Multi-Scale Convolution and Dynamic Routing for Next-Generation Networks](/202607/11/2607.05093v1-semantic-video-communication-via-multi-scale-convolution-and-dynamic-routing-for-next-generation-networks)  
   标签：评分：6.0/10、query:vcodec
   evidence：多尺度时序建模与生成式AI的语义视频通信
11. [FourTune: Towards Fully 4-Bit Efficient Post-Training for Diffusion Models](/202607/11/2607.05711v1-fourtune-towards-fully-4-bit-efficient-post-training-for-diffusion-models)  
   标签：评分：6.0/10、query:train-trick
   evidence：面向扩散模型的4位后训练量化框架，涉及量化感知训练


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
