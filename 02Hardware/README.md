<!--Copyright © ZOMI 适用于[License](https://github.com/chenzomi12/DeepLearningSystem)版权许可-->

# === 二、AI芯片体系结构 ===

AI硬件体系结构主要是指AI芯片，这里就很硬核了，从芯片的基础到AI芯片的范围都会涉及，芯片设计需要考虑上面AI框架的前端、后端编译，而不是停留在天天喊着吊打英伟达，被现实打趴。

> 欢迎大家使用的过程中发现bug或者勘误直接提交PR到开源社区哦！

> 请大家尊重开源和ZOMI的努力，引用PPT的内容请规范转载标明出处哦！

## 课程简介

- **《AI 计算体系概述》**：深入深度学习计算模式，从而理解“计算”需要什么。通过AI芯片关键指标，了解AI芯片要更好的支持“计算”，需要关注那些重点工作。最后通过深度学习的计算核心“矩阵乘”来看对“计算”的实际需求和情况，为了提升计算性能、降低功耗和满足训练推理不同场景应用，对“计算”引入 TF32/BF16 等复杂多样的比特位宽。

- **《AI 芯片基础》**：简单从CPU开始看通用逻辑架构（冯诺依曼架构）开始，通过打开计算的本质（数据与时延）从而引出对于并行计算GPU作用和解决的业务场景，到目前最火的AI芯片NPU。最后迈入超异构并行CPU、GPU、NPU并存的计算系统架构黄金十年。

- **《GPU 原理详解》**：主要是深入地讲解GPU的工作原理，其最重要的指标是计算吞吐和存储和传输带宽，并对英伟达的GPU的十年5代架构进行梳理。此外，《NVIDIA GPU详解》英伟达架构里面专门为AI而生的 Tensor Core 和 NVLink 对AI加速尤为重要，因此重点对 Tensor Core 和 NVLink 进行深入剖析其发展、演进和架构。

- **《国外AI芯片》**：深入地剖析国外 Google TPU 和特斯拉 DOJO 相关 AI 芯片的架构，以TPU为主主要使用了数据流（Data FLow）的方式的脉动阵列来加速矩阵的运算，而特斯拉则使用了近存计算（Near Memory）两种不同的产品形态。

- **《国内AI芯片》**：深入地解读国内 AI 初创芯片厂商如国内第一AI芯片上市公司寒武纪、国内造GPU声势最大的壁仞科技、腾讯重头的燧原科技等科技公司的 AI 芯片架构。

希望这个系列能够给大家、朋友们带来一些些帮助，也希望自己能够继续坚持完成所有内容哈！

## 课程细节

> *建议优先下载或者使用PDF版本，PPT版本会因为字体缺失等原因导致版本很丑哦~*