<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-05-20 ~ 2026-05-29
- 运行时间：2026-05-29 09:04:44 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：7
- 速读区：12

### 今日简报（AI）
今日AI日报（5.20-5.29）重点推荐两篇高分论文：JLT提出DiT中潜在预测的清洁范式（9.0），FRAPPE用投影追踪编码器实现全输入残差自编码（9.0），均在生成与表征学习上取得突破。

速读中值得关注的还有Scale When Needed与JacQuant两种高效量化感知训练方法（8.0），以及一步式离散扩散蒸馏技术（7.0），适合关注模型轻量化与生成加速的读者。

建议优先精读JLT与FRAPPE原论文理解核心思路，再结合速读中的量化与蒸馏方法验证实际部署效果。
- 详情：[/20260520-20260529/README](/20260520-20260529/README)

### 精读区论文标签
1. [JLT: Clean-Latent Prediction in Latent Diffusion Transformers](/20260520-20260529/2605.27102v1-jlt-clean-latent-prediction-in-latent-diffusion-transformers)  
   标签：评分：9.0/10、query:vcodec
   evidence：潜在扩散变换器中的干净潜在预测
2. [FRAPPE: Full Input, Residual Output Autoencoding with Projection Pursuit Encoder](/20260520-20260529/2605.28992v1-frappe-full-input-residual-output-autoencoding-with-projection-pursuit-encoder)  
   标签：评分：9.0/10、query:vcodec
   evidence：提出用于媒体压缩的全输入残差输出自编码框架，具有率失真-复杂度权衡和自然通道重要性排序
3. [Parallel Context Modeling for Sliding Window Attention in Neural Video Coding](/20260520-20260529/2605.20977v1-parallel-context-modeling-for-sliding-window-attention-in-neural-video-coding)  
   标签：评分：8.0/10、query:entropy-coding
   evidence：神经视频编码中的并行上下文建模及熵编码模块优化
4. [Q-ARVD: Quantizing Autoregressive Video Diffusion Models](/20260520-20260529/2605.21072v1-q-arvd-quantizing-autoregressive-video-diffusion-models)  
   标签：评分：8.0/10、query:train-trick
   evidence：自回归视频扩散模型量化
5. [FAST-ME: Foundation-aware Adaptive Stopping for Motion Estimation for Efficient IoT Video Analysis](/20260520-20260529/2605.23428v1-fast-me-foundation-aware-adaptive-stopping-for-motion-estimation-for-efficient-iot-video-analysis)  
   标签：评分：8.0/10、query:train-trick
   evidence：面向IoT的低复杂度运动估计
6. [Paris 2.0: A Decentralized Diffusion Model for Video Generation](/20260520-20260529/2605.26064v2-paris-20-a-decentralized-diffusion-model-for-video-generation)  
   标签：评分：8.0/10、query:vcodec
   evidence：去中心化扩散模型进行视频生成
7. [NeR-SC: Adapting Neural Video Representation to Screen Content](/20260520-20260529/2605.27024v1-ner-sc-adapting-neural-video-representation-to-screen-content)  
   标签：评分：8.0/10、query:vcodec
   evidence：为屏幕内容视频调整的神经表示编码框架

### 速读区论文标签
1. [Scale When Needed: Adaptive Neuron-level Mixed Precision Quantization Aware Training](/20260520-20260529/2605.25054v1-scale-when-needed-adaptive-neuron-level-mixed-precision-quantization-aware-training)  
   标签：评分：8.0/10、query:train-trick
   evidence：神经元级混合精度量化感知训练，自适应位宽扩展，直接匹配视频编码中的量化感知训练需求
2. [JacQuant: STE-Free Quantization-Aware Training via Learned Jacobian Surrogates](/20260520-20260529/2605.25469v1-jacquant-ste-free-quantization-aware-training-via-learned-jacobian-surrogates)  
   标签：评分：8.0/10、query:train-trick
   evidence：通过学习的雅可比替代实现无STE量化感知训练
3. [One-Step Distillation of Discrete Diffusion Image Generators via Fixed-Point Iteration](/20260520-20260529/2605.21484v1-one-step-distillation-of-discrete-diffusion-image-generators-via-fixed-point-iteration)  
   标签：评分：7.0/10、query:train-trick
   evidence：扩散模型的单步蒸馏方法，可用于高效视频编解码器训练
4. [Φ-Noise: Training-Free Temporal Video Conditioning via Phase-Based Noise Manipulation](/20260520-20260529/2605.24509v1--noise-training-free-temporal-video-conditioning-via-phase-based-noise-manipulation)  
   标签：评分：7.0/10、query:vcodec
   evidence：使用潜在视频扩散模型和基于相位的噪声条件方法
5. [Motion-Compensated Weight Compression](/20260520-20260529/2605.24754v1-motion-compensated-weight-compression)  
   标签：评分：7.0/10、query:vcodec
   evidence：提出运动补偿权重压缩，采用层间预测和率失真优化熵模型，类似于视频压缩中的运动补偿
6. [From Contrast to Consistency: Rethinking Event-based Continuous-Time Optical Flow Estimation](/20260520-20260529/2605.25570v1-from-contrast-to-consistency-rethinking-event-based-continuous-time-optical-flow-estimation)  
   标签：评分：7.0/10、query:vcodec
   evidence：基于事件相机的连续光流估计与混合监督，直接匹配视频压缩中的运动估计需求
7. [Paris 2.0: A Decentralized Diffusion Model for Video Generation](/20260520-20260529/2605.26064v1-paris-20-a-decentralized-diffusion-model-for-video-generation)  
   标签：评分：7.0/10、query:vcodec
   evidence：Paris 2.0 是一种去中心化的视频生成扩散模型，为视频压缩提供生成式先验
8. [Multi-Teacher Knowledge Distillation via Teacher-Informed Mixture Priors](/20260520-20260529/2605.27967v1-multi-teacher-knowledge-distillation-via-teacher-informed-mixture-priors)  
   标签：评分：7.0/10、query:train-trick
   evidence：多教师知识蒸馏方法，可直接应用于视频压缩模型训练
9. [LANCE: Locally Adaptive Neural Context Estimation for Overfitted Image Compression](/20260520-20260529/2605.20672v1-lance-locally-adaptive-neural-context-estimation-for-overfitted-image-compression)  
   标签：评分：6.0/10、query:entropy-coding
   evidence：过拟合图像压缩中的局部自适应神经上下文估计与空间超先验
10. [AIR: Amortized Image Reconstruction Framework for Self-Supervised Feed-Forward 2D Gaussian Splatting](/20260520-20260529/2605.20820v1-air-amortized-image-reconstruction-framework-for-self-supervised-feed-forward-2d-gaussian-splatting)  
   标签：评分：6.0/10、query:train-trick
   evidence：预测-优化-蒸馏多阶段训练策略
11. [Adaptive Signal Resuscitation: Channel-wise Post-Pruning Repair for Sparse Vision Networks](/20260520-20260529/2605.21426v1-adaptive-signal-resuscitation-channel-wise-post-pruning-repair-for-sparse-vision-networks)  
   标签：评分：6.0/10、query:train-trick
   evidence：通道级剪枝后修复方法，可迁移至视频压缩模型剪枝
12. [ReMATF: Recurrent Motion-Adaptive Multi-scale Turbulence Mitigation for Dynamic Scenes](/20260520-20260529/2605.21440v1-rematf-recurrent-motion-adaptive-multi-scale-turbulence-mitigation-for-dynamic-scenes)  
   标签：评分：6.0/10、query:vcodec
   evidence：轻量级递归运动自适应时间融合模块


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
