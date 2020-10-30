# Additional libraries

/lib,/lib/x86_64-linux-gnu,/usr,/usr/lib/x86_64-linux-gnu/libfakeroot,/usr/local/cuda,/usr/local/cuda-11.1/targets/x86_64-linux/lib,/home/rush/tools/TensorRT-7.2.1.6


# Build command
bazel build --config=cuda //tensorflow/tools/pip_package:build_pip_package


# Pip generation