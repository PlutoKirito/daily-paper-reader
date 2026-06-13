<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-13
- 运行时间：2026-06-13 21:26:51 UTC
- 运行状态：成功
- 本次总论文数：4
- 精读区：1
- 速读区：3

### 今日简报（AI）
今日精读1篇向量量化研究，速读3项覆盖3D流媒体、KV缓存压缩及视频世界模型，整体质量中等。

最值得关注的是向量量化中缓解码本坍塌的NSVQ方法（8分），以及低秩KV缓存压缩STAR-KV的软阈值自适应控制。

建议优先精读NSVQ理解编码器稳定策略，可辅助关注STAR-KV在长文本推理中的压缩潜力。
- 详情：[/202606/13/README](/202606/13/README)

### 精读区论文标签
1. [NSVQ: Mitigating Codebook Collapse by Stabilizing Encoder Drift in Vector Quantization](/202606/13/2606.11363v1-nsvq-mitigating-codebook-collapse-by-stabilizing-encoder-drift-in-vector-quantization)  
   标签：评分：8.0/10、query:train-trick
   evidence：通过分阶段编码器冻结和非平稳嵌入损失缓解码本坍塌

### 速读区论文标签
1. [EvoGS: Constructing Continuous-Layered Gaussian Splatting with Evolution Tree for Scalable 3D Streaming](/202606/13/2606.07179v1-evogs-constructing-continuous-layered-gaussian-splatting-with-evolution-tree-for-scalable-3d-streaming)  
   标签：评分：6.0/10、query:vcodec
   evidence：连续层级表示用于可扩展3D流，直接关联可扩展神经视频编码
2. [STAR-KV: Low-Rank KV Cache Compression via Soft Thresholding for Adaptive Rank Control](/202606/13/2606.08382v1-star-kv-low-rank-kv-cache-compression-via-soft-thresholding-for-adaptive-rank-control)  
   标签：评分：6.0/10、query:train-trick
   evidence：KV缓存压缩中的低秩与量化训练技巧
3. [BiWM: Advancing Open-Source Interactive Video World Models with Bidirectional Autoregression](/202606/13/2606.10135v1-biwm-advancing-open-source-interactive-video-world-models-with-bidirectional-autoregression)  
   标签：评分：6.0/10、query:vcodec
   evidence：双向视频扩散用于交互世界模型，与生成式视频压缩相关


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
