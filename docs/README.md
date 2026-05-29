<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-29
- 运行时间：2026-05-29 22:05:09 UTC
- 运行状态：成功
- 本次总论文数：14
- 精读区：4
- 速读区：10

### 今日简报（AI）
1) 今日聚焦视频编码加速与IoT分析效率，精读两项高分研究，另涉图像压缩、光流估计与视频生成新方向。
2) 最值得关注：CNN-层次注意力Transformer混合模型大幅加速HEVC帧内分区（9.0/10）；以及面向IoT视频分析的自适应运动估计停止策略（8.0/10）。
3) 建议优先深入精读这两篇，尤其对视频编码或端侧AI应用感兴趣的读者，可重点学习其混合模型与资源自适应机制。
- 详情：[/202605/29/README](/202605/29/README)

### 精读区论文标签
1. [Accelerating HEVC Intra Partitioning via a CNN-Hierarchical Attention Transformer Hybrid](/202605/29/2605.29063v1-accelerating-hevc-intra-partitioning-via-a-cnn-hierarchical-attention-transformer-hybrid)  
   标签：评分：9.0/10、query:train-trick
   evidence：直接通过CNN-Transformer混合加速HEVC帧内分区预测，降低编码复杂度
2. [FAST-ME: Foundation-aware Adaptive Stopping for Motion Estimation for Efficient IoT Video Analysis](/202605/29/2605.23428v1-fast-me-foundation-aware-adaptive-stopping-for-motion-estimation-for-efficient-iot-video-analysis)  
   标签：评分：8.0/10、query:vcodec
   evidence：块运动估计框架可直接应用于帧间预测网络优化
3. [LC-Flow: Learning Local Continuous Optical Flow and Confidence from events](/202605/29/2605.24604v1-lc-flow-learning-local-continuous-optical-flow-and-confidence-from-events)  
   标签：评分：8.0/10、query:vcodec
   evidence：从事件学习连续光流，与运动估计和压缩联合学习相关
4. [Scale When Needed: Adaptive Neuron-level Mixed Precision Quantization Aware Training](/202605/29/2605.25054v1-scale-when-needed-adaptive-neuron-level-mixed-precision-quantization-aware-training)  
   标签：评分：8.0/10、query:train-trick
   evidence：神经元级混合精度量化感知训练可直接用于视频编码模型

### 速读区论文标签
1. [Efficient Learned Image Compression without Entropy Coding](/202605/29/2605.23323v1-efficient-learned-image-compression-without-entropy-coding)  
   标签：评分：7.0/10、query:vcodec
   evidence：无熵编码的多码率学习图像压缩
2. [From Contrast to Consistency: Rethinking Event-based Continuous-Time Optical Flow Estimation](/202605/29/2605.25570v2-from-contrast-to-consistency-rethinking-event-based-continuous-time-optical-flow-estimation)  
   标签：评分：7.0/10、query:vcodec
   evidence：光流估计方法可迁移至视频压缩中的运动估计
3. [OSP-Next: Efficient High-Quality Video Generation with Sparse Sequence Parallelism, HiF8 Quantization, and Reinforcement Learning](/202605/29/2605.28691v1-osp-next-efficient-high-quality-video-generation-with-sparse-sequence-parallelism-hif8-quantization-and-reinforcement-learning)  
   标签：评分：7.0/10、query:vcodec
   evidence：结合稀疏注意力、量化和强化学习的高效视频生成
4. [Veda: Scalable Video Diffusion via Distilled Sparse Attention](/202605/29/2605.30325v1-veda-scalable-video-diffusion-via-distilled-sparse-attention)  
   标签：评分：7.0/10、query:vcodec
   evidence：使用潜在扩散变换器进行视频生成
5. [DecQ: Detail-Condensing Queries for Enhanced Reconstruction and Generation in Representation Autoencoders](/202605/29/2605.22777v1-decq-detail-condensing-queries-for-enhanced-reconstruction-and-generation-in-representation-autoencoders)  
   标签：评分：6.0/10、query:vcodec
   evidence：潜扩散模型、表示自编码器、细节浓缩查询提升重建质量
6. [JetViT: Efficient High-Resolution Vision Transformer with Post-Training Attention Search](/202605/29/2605.26636v1-jetvit-efficient-high-resolution-vision-transformer-with-post-training-attention-search)  
   标签：评分：6.0/10、query:train-trick
   evidence：训练后注意力搜索提高ViT推理效率，与低复杂度编解码器相关
7. [Timestep-Aware SVDQuant-GPTQ for W4A4 Quantization of Wan2.2-I2V](/202605/29/2605.27003v1-timestep-aware-svdquant-gptq-for-w4a4-quantization-of-wan22-i2v)  
   标签：评分：6.0/10、query:vcodec
   evidence：视频扩散模型的量化
8. [PARE: Pruning and Adaptive Routing for Efficient Video Generation](/202605/29/2605.27336v1-pare-pruning-and-adaptive-routing-for-efficient-video-generation)  
   标签：评分：6.0/10、query:train-trick
   evidence：视频扩散变换器的剪枝与自适应路由
9. [Structure over Pixels: Learning Variable-Length Visual Programs](/202605/29/2605.27696v2-structure-over-pixels-learning-variable-length-visual-programs)  
   标签：评分：6.0/10、query:entropy-coding
   evidence：率失真探针用于分词器学习，方法论上类似于超先验结构
10. [VideoMLA: Low-Rank Latent KV Cache for Minute-Scale Autoregressive Video Diffusion](/202605/29/2605.30351v1-videomla-low-rank-latent-kv-cache-for-minute-scale-autoregressive-video-diffusion)  
   标签：评分：6.0/10、query:vcodec
   evidence：低秩潜在KV缓存用于视频扩散


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
