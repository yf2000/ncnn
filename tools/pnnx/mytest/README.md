## git test

## 支持大部分常用的 CNN 网络

- Classical CNN:
  [VGG](https://github.com/BVLC/caffe/wiki/Model-Zoo#models-used-by-the-vgg-team-in-ilsvrc-2014)
  [AlexNet](https://github.com/BVLC/caffe/tree/9b891540183ddc834a02b2bd81b31afae71b2153/models/bvlc_alexnet)
  [GoogleNet](https://github.com/BVLC/caffe/tree/9b891540183ddc834a02b2bd81b31afae71b2153/models/bvlc_googlenet)
  Inception
  ...
- Practical CNN:
  [ResNet](https://github.com/tornadomeet/ResNet)
  [DenseNet](https://github.com/liuzhuang13/DenseNet)
  [SENet](https://github.com/hujie-frank/SENet)
  [FPN](https://github.com/unsky/FPN)
  ...
- Light-weight CNN:
  [SqueezeNet](https://github.com/forresti/SqueezeNet)
  [MobileNetV1](https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet_v1.md)
  [MobileNetV2/V3](https://github.com/tensorflow/models/blob/master/research/slim/nets/mobilenet/README.md)
  [ShuffleNetV1](https://github.com/farmingyard/ShuffleNet)
  [ShuffleNetV2](https://github.com/opconty/keras-shufflenetV2)
  [MNasNet](https://github.com/tensorflow/models/tree/master/research/slim/nets/nasnet)
  ...
- Face Detection:
  [MTCNN](https://github.com/ipazc/mtcnn)
  [RetinaFace](https://github.com/biubug6/Pytorch_Retinaface)
  [scrfd](https://github.com/nihui/ncnn-android-scrfd)
  ...
- Detection:
  [VGG-SSD](https://github.com/lzx1413/CAFFE_SSD)
  [MobileNet-SSD](https://github.com/chuanqi305/MobileNet-SSD)
  [SqueezeNet-SSD](https://github.com/chuanqi305/SqueezeNet-SSD)
  [MobileNetV2-SSDLite](https://github.com/chuanqi305/MobileNetv2-SSDLite)
  [MobileNetV3-SSDLite](https://github.com/XiaoyuHuang96/MobilenetV3SSDLite-tfkeras)
  ...
- Detection:
  [Faster-RCNN](https://github.com/rbgirshick/py-faster-rcnn)
  [R-FCN](https://github.com/daijifeng001/R-FCN)
  ...
- Detection:
  [YOLOv2](https://github.com/longcw/yolo2-pytorch)
  [YOLOv3](https://github.com/ultralytics/yolov3)
  [MobileNet-YOLOv3](https://github.com/eric612/MobileNet-YOLO)
  [YOLOv4](https://github.com/Tianxiaomo/pytorch-YOLOv4)
  [YOLOv5](https://github.com/ultralytics/yolov5)
  [YOLOv7](https://github.com/WongKinYiu/yolov7)
  [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX)
  ...
- Detection:
  [NanoDet](https://github.com/RangiLyu/nanodet)
- Segmentation:
  [FCN](https://github.com/unsky/FPN)
  [PSPNet](https://github.com/hszhao/PSPNet)
  [UNet](https://github.com/zhixuhao/unet)
  [YOLACT](https://github.com/dbolya/yolact)
  ...
- Pose Estimation:
  [SimplePose](https://github.com/dog-qiuqiu/Ultralight-SimplePose)
  ...

---

## HowTo

**[how to build ncnn library](https://github.com/Tencent/ncnn/wiki/how-to-build) on Linux / Windows / macOS / Raspberry Pi3, Pi4 / Android / NVIDIA Jetson / iOS / WebAssembly / AllWinner D1 / Loongson 2K1000**

- [Build for Linux / NVIDIA Jetson / Raspberry Pi3, Pi4 / POWER9](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-linux)
- [Build for Windows x64 using VS2017](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-windows-x64-using-visual-studio-community-2017)
- [Build for macOS](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-macos)
- [Build for ARM Cortex-A family with cross-compiling](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-arm-cortex-a-family-with-cross-compiling)
- [Build for Hisilicon platform with cross-compiling](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-hisilicon-platform-with-cross-compiling)
- [Build for Android](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-android)
- [Build for iOS on macOS with xcode](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-ios-on-macos-with-xcode)
- [Build for WebAssembly](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-webassembly)
- [Build for AllWinner D1](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-allwinner-d1)
- [Build for Loongson 2K1000](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-loongson-2k1000)
- [Build for Termux on Android](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-termux-on-android)
- [Build for QNX](https://github.com/Tencent/ncnn/wiki/how-to-build#build-for-qnx)

**[download prebuild binary package for android and ios](https://github.com/Tencent/ncnn/releases)**

**[use ncnn with alexnet](https://github.com/Tencent/ncnn/wiki/use-ncnn-with-alexnet) with detailed steps, recommended for beginners :)**

**[ncnn 组件使用指北 alexnet](https://github.com/Tencent/ncnn/wiki/use-ncnn-with-alexnet.zh) 附带详细步骤，新人强烈推荐 :)**

**[use netron for ncnn model visualization](https://netron.app)**

**[out-of-the-box web model conversion](https://convertmodel.com/#outputFormat=ncnn)**

[ncnn low-level operation api](https://github.com/Tencent/ncnn/wiki/low-level-operation-api)

[ncnn param and model file spec](https://github.com/Tencent/ncnn/wiki/param-and-model-file-structure)

[ncnn operation param weight table](https://github.com/Tencent/ncnn/wiki/operation-param-weight-table)

[how to implement custom layer step by step](https://github.com/Tencent/ncnn/wiki/how-to-implement-custom-layer-step-by-step)

---

## FAQ

**[ncnn throw error](https://github.com/Tencent/ncnn/wiki/FAQ-ncnn-throw-error)**

**[ncnn produce wrong result](https://github.com/Tencent/ncnn/wiki/FAQ-ncnn-produce-wrong-result)**

**[ncnn vulkan](https://github.com/Tencent/ncnn/wiki/FAQ-ncnn-vulkan)**

---

## Features

- Supports convolutional neural networks, supports multiple input and multi-branch structure, can calculate part of the branch
- No third-party library dependencies, does not rely on BLAS / NNPACK or any other computing framework
- Pure C++ implementation, cross-platform, supports Android, iOS and so on
- ARM NEON assembly level of careful optimization, calculation speed is extremely high
- Sophisticated memory management and data structure design, very low memory footprint
- Supports multi-core parallel computing acceleration, ARM big.LITTLE CPU scheduling optimization
- Supports GPU acceleration via the next-generation low-overhead Vulkan API
- Extensible model design, supports 8bit quantization and half-precision floating point storage, can import caffe/pytorch/mxnet/onnx/darknet/keras/tensorflow(mlir) models
- Support direct memory zero copy reference load network model
- Can be registered with custom layer implementation and extended
- Well, it is strong, not afraid of being stuffed with 卷 QvQ

## 功能概述

- 支持卷积神经网络，支持多输入和多分支结构，可计算部分分支
- 无任何第三方库依赖，不依赖 BLAS/NNPACK 等计算框架
- 纯 C++ 实现，跨平台，支持 Android / iOS 等
- ARM Neon 汇编级良心优化，计算速度极快
- 精细的内存管理和数据结构设计，内存占用极低
- 支持多核并行计算加速，ARM big.LITTLE CPU 调度优化
- 支持基于全新低消耗的 Vulkan API GPU 加速
- 可扩展的模型设计，支持 8bit [量化](tools/quantize) 和半精度浮点存储，可导入 caffe/pytorch/mxnet/onnx/darknet/keras/tensorflow(mlir) 模型
- 支持直接内存零拷贝引用加载网络模型
- 可注册自定义层实现并扩展
- 恩，很强就是了，不怕被塞卷 QvQ

---

## supported platform matrix



## Project examples

- <https://github.com/nihui/ncnn-android-squeezenet>
- <https://github.com/nihui/ncnn-android-styletransfer>
- <https://github.com/nihui/ncnn-android-mobilenetssd>
- <https://github.com/moli232777144/mtcnn_ncnn>
- <https://github.com/nihui/ncnn-android-yolov5>
- <https://github.com/xiang-wuu/ncnn-android-yolov7>
- <https://github.com/nihui/ncnn-android-scrfd> 🤩
- <https://github.com/shaoshengsong/qt_android_ncnn_lib_encrypt_example>


- <https://github.com/mizu-bai/ncnn-fortran> Call ncnn from Fortran

- <https://github.com/k2-fsa/sherpa> Use ncnn for real-time speech
  recognition (i.e., speech-to-text); also support embedded devices and provide
  mobile Apps (e.g., Android App)

---

