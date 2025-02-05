# Deep Learning for Bela resources

This repository contains resources for using deep learning with Bela. It is a work in progress and will be updated as more resources are created.

## Tutorials

- [pybela-pytorch-xc-tutorial](https://github.com/pelinski/pybela-pytorch-xc-tutorial) - Probably the best place to start, a tutorial with a simple example of collecting a dataset on Bela sensor data, training a PyTorch model and running it in real-time in Bela. Includes cross-compiling example.

## Tools

- [pybela](https://github.com/BelaPlatform/pybela/) - A Python library for interfacing Python with Bela projects. Useful for collecting training data or streaming data between Bela and computer. Includes [tutorials](https://github.com/BelaPlatform/pybela/tree/main/tutorials/notebooks).
- [xc-bela-container](https://github.com/pelinski/xc-bela-container/tree/main) – A container for cross-compiling Bela projects. Useful for compiling projects with deep learning inference engines.
- [DeepLearningForBela](https://github.com/rodrigodzf/DeepLearningForBela) – slightly outdated now, but C++ library but with support for TensorFlow Lite, ArmNN, RTNeural.

## Example projects

- [anira-bela-examples](https://github.com/anira-project/anira-bela-examples) - [anira](https://github.com/anira-project/anira) examples in Bela. Anira is a library for real-time safe neural network on-device inference within audio applications. It supports LibTorch, ONNXRuntime and TensorFlow Lite. Uses xc-bela-container.
- [pybela-drumsynth](https://github.com/jorshi/pybela-drumsynth) - An example of on-device real-time inference with PyTorch on Bela, collecting training data on an audio signal. Uses xc-bela-container.
- [faab-hyperparams](https://github.com/pelinski/faab-hyperparams/tree/main) - An example of real-time inference running on a computer. Sensor data is streamed from Bela to Python, where a PyTorch model is run, and the output is sent back to Bela, all in real-time.

## Inference engines

compiled for Bela (armv7).

- [bela-torch](https://github.com/pelinski/bela-torch)
- [bela-tflite](https://github.com/pelinski/bela-tflite)
- [bela-onnx](https://github.com/pelinski/bela-onnx)
