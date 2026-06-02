<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-02
- 运行时间：2026-06-02 22:55:24 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：5
- 速读区：8

### 今日简报（AI）
今日13篇论文聚焦视频生成效率与图像压缩，精读方向为KV缓存偏置校正与剪枝自适应路由。
最值得关注：《Quantized Keys Steal Attention》攻克视频扩散模型KV缓存压缩偏差；《PARE》实现视频生成的高效剪枝与动态路由。
建议下一步关注HiFloat8量化与超低码率图像压缩的实际部署效果。
- 详情：[/202606/02/README](/202606/02/README)

### 精读区论文标签
1. [Quantized Keys Steal Attention: Bias Correction for KV-Cache Compression in Video Diffusion](/202606/02/2605.26266v1-quantized-keys-steal-attention-bias-correction-for-kv-cache-compression-in-video-diffusion)  
   标签：评分：8.0/10、query:vcodec
   evidence：视频扩散模型中量化KV缓存的偏差校正，与扩散式视频压缩相关
2. [PARE: Pruning and Adaptive Routing for Efficient Video Generation](/202606/02/2605.27336v1-pare-pruning-and-adaptive-routing-for-efficient-video-generation)  
   标签：评分：8.0/10、query:train-trick
   evidence：针对视频扩散变压器的结构感知剪枝与自适应路由
3. [ChWDTA: Channel-wise Wavelet-Domain Transformer Attention and Entropy Modeling for Learned Image Compression](/202606/02/2606.00111v1-chwdta-channel-wise-wavelet-domain-transformer-attention-and-entropy-modeling-for-learned-image-compression)  
   标签：评分：8.0/10、query:entropy-coding
   evidence：通道级小波域注意力与熵建模的端到端图像压缩方法
4. [How Neural Losses Shape VAE Latents](/202606/02/2606.00635v1-how-neural-losses-shape-vae-latents)  
   标签：评分：8.0/10、query:entropy-coding
   evidence：神经损失重塑VAE潜在空间的率失真问题
5. [AdaCodec: A Predictive Visual Code for Video MLLMs](/202606/02/2606.02569v1-adacodec-a-predictive-visual-code-for-video-mllms)  
   标签：评分：8.0/10、query:vcodec
   evidence：利用帧间变化的预测性视觉码

### 速读区论文标签
1. [Boundary-Protection W8A8 HiFloat8 Quantization for Large-Scale Text-to-Video Diffusion Transformers](/202606/02/2606.00957v1-boundary-protection-w8a8-hifloat8-quantization-for-large-scale-text-to-video-diffusion-transformers)  
   标签：评分：7.0/10、query:train-trick
   evidence：针对视频扩散变压器的边界保护量化策略，识别不均匀激活分布
2. [Exploiting Semantic and Pixel Representations for Ultra-Low Bitrate Image Compression](/202606/02/2606.01608v1-exploiting-semantic-and-pixel-representations-for-ultra-low-bitrate-image-compression)  
   标签：评分：7.0/10、query:vcodec
   evidence：基于扩散的超低比特率图像压缩，优化感知率失真
3. [Real-Time Generation of Streamable Talking Portrait Video with Reference-Guided Deep Compression VAEs](/202606/02/2606.01620v1-real-time-generation-of-streamable-talking-portrait-video-with-reference-guided-deep-compression-vaes)  
   标签：评分：7.0/10、query:vcodec
   evidence：生成式视频压缩，包含因果VAE和自回归去噪
4. [Teaching Video Generators to Remember: Eliciting Dynamic Memory for Out-of-Sight State Evolution](/202606/02/2605.25333v1-teaching-video-generators-to-remember-eliciting-dynamic-memory-for-out-of-sight-state-evolution)  
   标签：评分：6.0/10、query:vcodec
   evidence：视频扩散Transformer记忆机制，与基于扩散的视频压缩相关
5. [Accelerating HEVC Intra Partitioning via a CNN-Hierarchical Attention Transformer Hybrid](/202606/02/2605.29063v1-accelerating-hevc-intra-partitioning-via-a-cnn-hierarchical-attention-transformer-hybrid)  
   标签：评分：6.0/10、query:train-trick
   evidence：通过深度学习加速HEVC帧内划分，降低编码复杂度
6. [Decoupled Residual Denoising Diffusion Models for Unified and Data Efficient Image-to-Image Translation](/202606/02/2606.01048v1-decoupled-residual-denoising-diffusion-models-for-unified-and-data-efficient-image-to-image-translation)  
   标签：评分：6.0/10、query:vcodec
   evidence：潜在扩散模型用于图像翻译，方法可迁移到视频
7. [Neural Network Compression by Approximate Differential Equivalence](/202606/02/2606.01402v1-neural-network-compression-by-approximate-differential-equivalence)  
   标签：评分：6.0/10、query:train-trick
   evidence：通过神经元聚合的模型压缩方法可用于轻量化视频编解码器
8. [LongLive-RAG: A General Retrieval-Augmented Framework for Long Video Generation](/202606/02/2606.02553v1-longlive-rag-a-general-retrieval-augmented-framework-for-long-video-generation)  
   标签：评分：6.0/10、query:vcodec
   evidence：自回归视频扩散与检索增强生成框架


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
