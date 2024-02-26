
<h1 align="center"><span>YOLOv9 TensorRT C++</span></h1>

This repository provides a C++ implementation of the state-of-the-art [YOLOv9](https://github.com/WongKinYiu/yolov9) object detection model, optimized with TensorRT for real-time inference and combined with the [ByteTracker](https://github.com/Vertical-Beach/ByteTrack-cpp) object tracker.

<p align="center" margin: 0 auto;>
  <img src="assets/demo.gif" width="300px" />
  <img src="assets/demo2.gif" width="315px" /> 
</p>

## 🚀 Usage

``` shell
yolov9-bytetrack-trt.exe yolov9-c.engine test.mp4 # the video path
```

## 🛠️ Setup

We refer to our [docs/INSTALL.md](https://github.com/spacewalk01/tensorrt-yolov9/blob/main/docs/INSTALL.md) for detailed installation instructions.

## 👏 Acknowledgement

This project is based on the following awesome projects:
- [Yolov9](https://github.com/WongKinYiu/yolov9) - YOLOv9: Learning What You Want to Learn Using Programmable Gradient Information.
- [TensorRT](https://github.com/NVIDIA/TensorRT/tree/release/8.6/samples) - TensorRT samples and api documentation.
- [TensorRTx](https://github.com/wang-xinyu/tensorrtx) - Implementation of popular deep learning networks with TensorRT network definition API.
