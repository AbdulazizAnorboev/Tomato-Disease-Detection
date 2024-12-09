# Base dependencies needed for running YOLOv5
gitpython>=3.1.30
matplotlib>=3.3
numpy>=1.22.2
opencv-python>=4.1.1
Pillow>=10.0.1
psutil  # For monitoring system resources
PyYAML>=5.3.1
requests>=2.23.0
scipy>=1.4.1
thop>=0.1.1  # For FLOPs computation
torch>=1.8.0  # PyTorch, see https://pytorch.org/get-started/locally
torchvision>=0.9.0
tqdm>=4.64.0
ultralytics>=8.0.147  # YOLOv5 specific utilities

# Optional dependencies for enhanced plotting
pandas>=1.1.4
seaborn>=0.11.0

# Dependencies for deployment and distribution
setuptools>=65.5.1  # Ensures compatibility and security fixes

# Uncomment below if exporting models to other formats
# coremltools>=6.0  # CoreML export
# onnx>=1.10.0  # ONNX export
# onnx-simplifier>=0.4.1  # Simplifies ONNX models
# nvidia-pyindex  # Required for TensorRT export
# nvidia-tensorrt  # TensorRT export
# scikit-learn<=1.1.2  # Used for CoreML quantization
# tensorflow>=2.4.0  # TensorFlow exports (-cpu, -aarch64, -macos)
# tensorflowjs>=3.9.0  # TensorFlow.js export
# openvino-dev>=2023.0  # OpenVINO export

# Uncomment for optional extras
# tensorboard>=2.4.1  # For visualizing learning metrics
# clearml>=1.2.0  # For experiment tracking
# comet  # For online experiment tracking
# ipython  # For interactive development in Jupyter notebooks
# mss  # For taking screenshots
# albumentations>=1.0.3  # For advanced image augmentation
# pycocotools>=2.0.6  # For working with COCO data
