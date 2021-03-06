# V100
当今市场上数据中心 GPU 中的精尖之作。NVIDIA®Tesla® V100 是当今市场上为加速人工智能、高性能计算和图形的数据中心 GPU 中的精尖之作。NVIDIA® Tesla® V100 采用全新一代 NVIDIA Volta 架构，可在单个 GPU 中提供高达 100 个 CPU 的性能，助力数据科学家、研究人员和工程师解决以前无法应对的难题。


|xxx|xxx|xxx|
|:---|:---|:---|
||zzz|zzz|
||zzz|zz|
|zzzzz|zzz|zzz|zzzz|


| 规格    | NVIDIA® Tesla®V100 PCIe NVIDIA® Tesla®V100 XM2|
| :----------- | :------------------------- |
| GPU架构   | NVIDIA Volta                                  |
|  NVIDIA Tensor核心数量 | 640                                            |
|  NVIDIA® CUDA®核心数量 | 5120                                           |
| 双精度性能            | 7 TFLOPS 7.8 TFLOPS                            |
| 单精度性能            | 14 TFLOPS 15.7 TFLOPS                          |
| Tensor性能            | 112 TFLOPS 125 TFLOPS                         |
| GPU内存               | 32 GB HBM2                                    |
| 显存带宽              | 900GB/秒                                       |
| 互联带宽              | 32GB/秒 300GB/秒                               |
| 系统接口              | PCIe Gen3 NVIDIA NVLink                        |
| 外形尺寸              | PCIe全高/全长 SXM2                              |
| 最大功耗              | 250W 300W                                      |
| ECC                   | 是                                              |
| 散热方案              | 被动式                                          |
|计算API|NVIDIA® CUDA®、Directcompute、OpenCL™、OpenACC|

# T4
利用全球性能超强劲的扩展加速器 NVIDIA® T4 GPU 打造动力澎湃的服务器。它的 70 瓦半高设计由 NVIDIA Turing™ Tensor 核心提供动力支持，具有革命性的多精度推理性能，可加速各种当今热门的应用程序。这款先进的 GPU 封装在外形小巧的 70 瓦低能耗 PCle 中，且针对服务器横向扩展进行了优化，专为提供杰出的 AI 性能而打造。

| GPU架构 | NVIDIA Turing|
|:-------------------------|:-------------------------|
| NVIDIA Turing Tensor核心数量 | 320 |
| NVIDIA CUDA®核心数量 | 2560 |
| 单精度 | 8.1 TFLOPS |
| 混合精度（FP16/FP32） | 65 TFLOPS |
| INT8 | 130 TOPS |
| INT4 | 260 TOPS |
| GPU显存 | 16 GB GDDR6 300GB/s |
| ECC | 支持 |
| 互联带宽 | 32 GB/秒 |
| 系统接口 | X16 PCI3 Gen3 |
| 外形尺寸 | PCIe半高卡 |
| 散热解决方案 | 被动式 |
| 计算API | CUDA NVIDIA TensorRT™ ONNX |


# A100

|规格 | 适用于 NVLink 的 A100 | 适用于 PCIe 的 A100 |
|:------|:----------|:-----------|
|FP64 峰值性能| 9.7 TF |9.7 TF|
|FP64 Tensor Core 峰值性能| 19.5 TF| 19.5 TF|
|FP32 峰值性能| 19.5 TF |19.5 TF|
|TF32 Tensor Core 峰值性能 156 TF | 312 TF* 156 TF | 312 TF*|
|BFLOAT16 Tensor Core 峰值性能 312 TF | 624 TF* 312 TF | 624 TF*|
|FP16 Tensor Core 峰值性能 312 TF | 624 TF* 312 TF | 624 TF*|
|INT8 Tensor Core 峰值性能 624 TOPS | 1,248 TOPS* 624 TOPS | 1,248 TOPS*|
|INT4 Tensor Core 峰值性能 1,248 TOPS | 2,496 TOPS* 1,248 TOPS | 2,496 TOPS*|
|GPU 显存 |40 GB| 40 GB|
|GPU 显存带宽| 1,555 GB/s |1,555 GB/s|
|互联带宽| "NVIDIA NVLink 600 GB/sPCIe Gen4 64 GB/s" |"NVIDIA NVLink 600 GB/s**PCIe Gen4 64 GB/s"|
|多实例 GPU | Various instance sizes with up to 7MIGs @5GB| Various instance sizes with up to 7MIGs @5GB|
|外形尺寸 |4/8 SXM on NVIDIA HGX™ A100 |PCIe|
|最大 TDP 功耗| 400W |250W|
|提供顶级应用性能| 100%| 90%|

\* 采用稀疏技术
\* * SXM 版 GPU 通过 HGX A100 服务器主板连接，PCIe 版 GPU 通过 NVLink 可桥接多达两个 GPU