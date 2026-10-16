# Tx条件空间语义

检验根据RGB与Tx标记生成的8×8空间先验，是否与真实Path Gain/LOS代理对齐，并随Tx位置正确变化。26母图，每图3个Tx，共78份先验；独立统计单位为母图。

部分场景级空间对应较弱但非随机，尚未通过完整Tx特异性标准。H1的Correct相关系数为0.1150，Wrong-Tx为0.0874，Geometry为0.3391；服务商与场景构成的敏感性限制了总体解释。

## 结果图片

### 四类对照箱线图

![四类对照箱线图](figures/01_四类对照箱线图.png)

### 逐母图Correct减Wrong-Tx

![逐母图Correct减Wrong-Tx](figures/02_逐mother_Correct减WrongTx.png)

### 母图级Correct与Wrong-Tx散点

![母图级Correct与Wrong-Tx散点](figures/03_mother级Correct与WrongTx散点图.png)

### 逐一留出母图的稳定性

![逐一留出母图的稳定性](figures/04_leave_one_mother_out稳定性.png)

### 相对成功的空间热力图案例

![相对成功的空间热力图案例](figures/Correct空间热力图典型成功案例.png)

### 失败的空间热力图案例

![失败的空间热力图案例](figures/Correct空间热力图典型失败案例.png)

### 服务商与场景构成敏感性

![服务商与场景构成敏感性](figures/provider敏感性对比图.png)

相关性不等于真实绕射路径、因果解释或下游收益；服务商间的差异也不能脱离场景分配直接归因。[返回本组目录](../README.md)。

[返回实验总览](../../README.md)
