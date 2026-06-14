<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-14
- 运行时间：2026-06-14 21:40:22 UTC
- 运行状态：成功
- 本次总论文数：10
- 精读区：3
- 速读区：7

### 今日简报（AI）
今日聚焦混合精度量化、联合源信道生成编码及视频生成等方向的10篇论文，其中3篇精读、7篇速读。
最值得精读的论文是《JOMP》和《JSCGC》，前者提出视频编码中的混合精度量化与缓存策略联合优化（9.0分），后者实现无线生成通信的源信道生成联合编码（8.0分）。
建议优先阅读这两篇精读论文，尤其是JOMP的联合优化思路可复用于高效视频压缩场景，而JSCGC对低能耗无线传输有启发。
- 详情：[/202606/14/README](/202606/14/README)

### 精读区论文标签
1. [JOMP: Jointly-Optimized Mixed-Precision Quantization Across Neural Video Coding Frameworks and Buffering Strategies](/202606/14/2606.13110v1-jomp-jointly-optimized-mixed-precision-quantization-across-neural-video-coding-frameworks-and-buffering-strategies)  
   标签：评分：9.0/10、query:train-trick
   evidence：神经视频编码框架的混合精度量化
2. [JSCGC: Joint Source-Channel-Generation Coding for Wireless Generative Communications](/202606/14/2606.12858v1-jscgc-joint-source-channel-generation-coding-for-wireless-generative-communications)  
   标签：评分：8.0/10、query:vcodec
   evidence：生成通信范式，使用生成解码器进行感知率失真优化
3. [Dual-Constrained Diffusion Image Compression for Operational Rate-Distortion-Perception Optimization](/202606/14/2606.13366v1-dual-constrained-diffusion-image-compression-for-operational-rate-distortion-perception-optimization)  
   标签：评分：8.0/10、query:vcodec
   evidence：扩散解码器的率失真感知优化

### 速读区论文标签
1. [RAPID: Layer-Wise Redundancy-Aware Pruning and Importance-Driven Token Merging for Efficient ViT](/202606/14/2606.08156v1-rapid-layer-wise-redundancy-aware-pruning-and-importance-driven-token-merging-for-efficient-vit)  
   标签：评分：7.0/10、query:train-trick
   evidence：提出层级感知的剪枝方法，可迁移至轻量级视频编解码器
2. [Understanding Quantization-Aware Training: Gradients at Quantized Weights Bias to the Low-Loss Basin](/202606/14/2606.09012v1-understanding-quantization-aware-training-gradients-at-quantized-weights-bias-to-the-low-loss-basin)  
   标签：评分：7.0/10、query:train-trick
   evidence：量化感知训练理论可应用于视频编码模型
3. [Ultra Flash: Scaling Real-Time Streaming Video Generation to High Resolutions](/202606/14/2606.09150v1-ultra-flash-scaling-real-time-streaming-video-generation-to-high-resolutions)  
   标签：评分：7.0/10、query:vcodec
   evidence：利用扩散模型实现实时高分辨率视频生成，与潜在扩散相关
4. [Making Time Editable in Video Diffusion Transformers](/202606/14/2606.10183v1-making-time-editable-in-video-diffusion-transformers)  
   标签：评分：7.0/10、query:vcodec
   evidence：视频扩散Transformer时间编辑，与潜在扩散相关
5. [NSVQ: Mitigating Codebook Collapse by Stabilizing Encoder Drift in Vector Quantization](/202606/14/2606.11363v1-nsvq-mitigating-codebook-collapse-by-stabilizing-encoder-drift-in-vector-quantization)  
   标签：评分：7.0/10、query:train-trick
   evidence：针对码本崩溃的向量量化训练策略，可应用于视频压缩潜变量
6. [Benchmarking Neural Speech Compression from a Rate-Distortion Perspective](/202606/14/2606.11631v1-benchmarking-neural-speech-compression-from-a-rate-distortion-perspective)  
   标签：评分：7.0/10、query:entropy-coding
   evidence：从率失真角度基准测试神经语音压缩，研究熵约束编码
7. [LGVSC: A Large-Model-Driven Generative Video Semantic Communication Framework](/202606/14/2606.12899v1-lgvsc-a-large-model-driven-generative-video-semantic-communication-framework)  
   标签：评分：7.0/10、query:vcodec
   evidence：生成式视频语义通信框架


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
