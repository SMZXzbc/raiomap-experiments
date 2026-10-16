# P0：三维几何正对照

使用确定性射线几何，检验正确建筑/植被高度是否比空间错置高度更接近LOS/NLOS参考。本实验为26母图、78 Tx，不调用VLM。

正确高度在主AUROC与8×8相关性比较中具有可检测价值，正对照通过。错误高度保持二维掩膜与高度多重集合，检验的是高度空间位置。LOS-floor主分析接收高度为0m；RadioMap的1.5m接收高度属于另一口径。

## 结果图片

### 正确与错误高度输入

![正确与错误高度输入](figures/01_correct_wrong_height.png)

### 高度直方图保持检查

![高度直方图保持检查](figures/02_height_histogram_preservation.png)

### 二维掩膜一致性检查

![二维掩膜一致性检查](figures/03_mask_identity.png)

### 射线与接收高度定义

![射线与接收高度定义](figures/04_ray_height_schematic.png)

### 二值与比例参考的区别

![二值与比例参考的区别](figures/05_binary_vs_fraction.png)

### 主结果：NLOS AUROC

![主结果：NLOS AUROC](figures/06_primary_auroc.png)

### 主结果：NLOS相关性

![主结果：NLOS相关性](figures/07_primary_rho.png)

### 逐母图效应

![逐母图效应](figures/08_per_mother_effect.png)

### 高度分层对照

![高度分层对照](figures/10_height_strata.png)

### 射线采样敏感性

![射线采样敏感性](figures/11_ray_sampling_sensitivity.png)

### 接收高度敏感性

![接收高度敏感性](figures/12_receiver_height_sensitivity.png)

### 成功案例

![成功案例](figures/13_success_case.png)

### 失败案例

![失败案例](figures/14_failure_case.png)

P0只证明在该评价定义下高度有信息，不能据此推断VLM会用好高度或RadioMap一定改善。[返回本组目录](../README.md)。

[返回实验总览](../../README.md)
