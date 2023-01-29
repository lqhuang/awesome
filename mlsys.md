# ML Systems

## Resources

- [google-research/tuning_playbook](https://github.com/google-research/tuning_playbook):
  A playbook for systematically maximizing the performance of deep learning
  models.
- [chenzomi12/DeepLearningSystem](https://github.com/chenzomi12/DeepLearningSystem):
  Deep Learning System core principles introduction.
- [microsoft/AI-System](https://github.com/microsoft/AI-System): System for AI
  Education Resource. <https://microsoft.github.io/AI-System/>
- [openmlsys/openmlsys-zh](https://github.com/openmlsys/openmlsys-zh): 《Machine
  Learning Systems: Design and Implementation》- Chinese Version
  <https://openmlsys.github.io/>

## Framework

- [Epistimio/orion](https://github.com/Epistimio/orion): Asynchronous
  Distributed Hyperparameter Optimization. <https://orion.readthedocs.io/>
- [optuna/optuna](https://github.com/optuna/optuna): A hyperparameter
  optimization framework <https://optuna.org/>
- [ray-project/ray](https://github.com/ray-project/ray): Ray is a unified
  framework for scaling AI and Python applications. Ray consists of a core
  distributed runtime and a toolkit of libraries (Ray AIR) for accelerating ML
  workloads. <https://ray.io/>
- [dmlc/dlpack](https://github.com/dmlc/dlpack): common in-memory tensor
  structure <https://dmlc.github.io/dlpack/latest>
- [aws/deep-learning-containers](https://github.com/aws/deep-learning-containers):
  AWS Deep Learning Containers (DLCs) are a set of Docker images for training
  and serving models in TensorFlow, TensorFlow 2, PyTorch, and MXNet.
  <https://docs.aws.amazon.com/deep-learning-containers/latest/devguide/deep-learning-containers-images.html>
- [facebookresearch/xformers](https://github.com/facebookresearch/xformers):
  Hackable and optimized Transformers building blocks, supporting a composable
  construction. <https://facebookresearch.github.io/xformers/>
- [tensor-compiler/taco](https://github.com/tensor-compiler/taco): The Tensor
  Algebra Compiler (taco) computes sparse tensor expressions on CPUs and GPUs
  <http://tensor-compiler.org/>
- [xtensor-stack/xtensor](https://github.com/xtensor-stack/xtensor): C++ tensors
  with broadcasting and lazy computing
- [rapidsai/cuml](https://github.com/rapidsai/cuml): cuML - RAPIDS Machine
  Learning Library

## Network implementation

- [hwchase17/langchain](https://github.com/hwchase17/langchain): ⚡ Building
  applications with LLMs through composability ⚡

## Inference engine / large-scale deployment

- [flashlight/flashlight](https://github.com/flashlight/flashlight): A C++
  standalone library for machine learning <https://fl.readthedocs.io/en/latest/>
- [microsoft/torchscale](https://github.com/microsoft/torchscale): Transformers
  at any scale <https://aka.ms/nlpagi>
- [webonnx/wonnx](https://github.com/webonnx/wonnx): A GPU-accelerated ONNX
  inference run-time written 100% in Rust, ready for the web
- [microsoft/DeepSpeed-MII](https://github.com/microsoft/DeepSpeed-MII): MII
  makes low-latency and high-throughput inference possible, powered by
  DeepSpeed.
- [Lightning-AI/lightning](https://github.com/Lightning-AI/lightning): Deep
  learning framework to train, deploy, and ship AI products Lightning fast.
  <https://lightning.ai/>

## Compiler / Low level

- [apache/tvm](https://github.com/apache/tvm): Open deep learning compiler stack
  for cpu, gpu and specialized accelerators <https://tvm.apache.org/>
- [openai/triton](https://github.com/openai/triton): Development repository for
  the Triton language and compiler
- [NVIDIA/cutlass](https://github.com/NVIDIA/cutlass): CUDA Templates for Linear
  Algebra Subroutines
- [NVIDIA/TensorRT](https://github.com/NVIDIA/TensorRT): NVIDIA® TensorRT™, an
  SDK for high-performance deep learning inference, includes a deep learning
  inference optimizer and runtime that delivers low latency and high throughput
  for inference applications. <https://developer.nvidia.com/tensorrt>

## Autodiff

- [facebookresearch/shumai](https://github.com/facebookresearch/shumai): Fast
  Differentiable Tensor Library in JavaScript and TypeScript with Bun +
  Flashlight
- [google/tangent](https://github.com/google/tangent): Source-to-Source
  Debuggable Derivatives in Pure Python
- [aesara-devs/aesara](https://github.com/aesara-devs/aesara): Aesara is a
  Python library for defining, optimizing, and efficiently evaluating
  mathematical expressions involving multi-dimensional arrays.
  <https://aesara.readthedocs.io/>

## Jax eco

- [openxla/xla](https://github.com/openxla/xla): A community-driven and modular
  open source compiler for ML.
- [patrick-kidger/equinox](https://github.com/patrick-kidger/equinox): Callable
  PyTrees and filtered transforms => neural networks in JAX.
  <https://docs.kidger.site/equinox/>
- [google/jaxtyping](https://github.com/google/jaxtyping): Type annotations and
  runtime checking for shape and dtype of JAX arrays, and PyTrees.
- [blackjax-devs/blackjax](https://github.com/blackjax-devs/blackjax): BlackJAX
  is a sampling library designed for ease of use, speed and modularity.
  <https://blackjax-devs.github.io/blackjax/>
- [thomaspinder/GPJax](https://github.com/thomaspinder/GPJax): A didactic
  Gaussian process package for researchers in Jax.
  <https://gpjax.readthedocs.io/en/latest/>
- [patrick-kidger/diffrax](https://github.com/patrick-kidger/diffrax): Numerical
  differential equation solvers in JAX. Autodifferentiable and GPU-capable.
  <https://docs.kidger.site/diffrax/>
- [probml/dynamax](https://github.com/probml/dynamax): State Space Models
  library in JAX <https://probml.github.io/dynamax/>
- [pyro-ppl/numpyro](https://github.com/pyro-ppl/numpyro): Probabilistic
  programming with NumPy powered by JAX for autograd and JIT compilation to
  GPU/TPU/CPU. <https://num.pyro.ai/>
- [jax-ml/oryx](https://github.com/jax-ml/oryx): Oryx is a library for
  probabilistic programming and deep learning built on top of Jax.
  <https://tensorflow.org/probability/oryx>
- [deepmind/distrax](https://github.com/deepmind/distrax): Distrax is a
  lightweight library of probability distributions and bijectors. It acts as a
  JAX-native reimplementation of a subset of TensorFlow Probability (TFP,
  https://www.tensorflow.org/probability), with some new features and emphasis
  on extensibility.
- [deepmind/jraph](https://github.com/deepmind/jraph): A Graph Neural Network
  Library in Jax <https://jraph.readthedocs.io/en/latest/>
- [google/flax](https://github.com/google/flax): Flax is a neural network
  library for JAX that is designed for flexibility.
  <https://flax.readthedocs.io/>
- [google/trax](https://github.com/google/trax): Trax — Deep Learning with Clear
  Code and Speed
- [dm-haiku](https://github.com/deepmind/dm-haiku): JAX-based neural network
  library <https://dm-haiku.readthedocs.io/>
- [kingoflolz/mesh-transformer-jax](https://github.com/kingoflolz/mesh-transformer-jax):
  Model parallel transformers in JAX and Haiku
- [probml/sts-jax](https://github.com/probml/sts-jax): Structural Time Series in
  JAX
- [ASEM000/kernex](https://github.com/ASEM000/kernex): Stencil computations in
  JAX

## Workflow pipeline

- [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow): Machine Learning
  Toolkit for Kubernetes
- [mlflow/mlflow](https://github.com/mlflow/mlflow): Open source platform for
  the machine learning lifecycle
- [Netflix/metaflow](https://github.com/Netflix/metaflow): 🚀 Build and manage
  real-life data science projects with ease! <https://metaflow.org/>
- [bentoml/BentoML](https://github.com/bentoml/BentoML): Unified Model Serving
  Framework 🍱 <https://bentoml.com>
- [bentoml/Yatai](https://github.com/bentoml/Yatai): Model Deployment at Scale
  on Kubernetes 🦄️ <https://bentoml.com/>
- [SeldonIO/seldon-core](https://github.com/SeldonIO/seldon-core): An MLOps
  framework to package, deploy, monitor and manage thousands of production
  machine learning models
- [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot): SkyPilot is
  a framework for easily running machine learning workloads on any cloud through
  a unified interface. <https://skypilot.readthedocs.io/>
- [GokuMohandas/mlops-course](https://github.com/GokuMohandas/mlops-course): A
  project-based course on the foundations of MLOps to responsibly develop,
  deploy and maintain ML. <https://madewithml.com/>
- [sematic-ai/sematic](https://github.com/sematic-ai/sematic): An open-source ML
  pipeline development platform

## Utils

- [patrick-kidger/torchtyping](https://github.com/patrick-kidger/torchtyping):
  Type annotations and dynamic checking for a tensor's shape, dtype, names, etc.
- [tensorchord/envd](https://github.com/tensorchord/envd): 🏕️ Development
  environment for machine learning
- [NVIDIA/nvidia-docker](https://github.com/NVIDIA/nvidia-docker): Build and run
  Docker containers leveraging NVIDIA GPUs
- [huggingface/safetensors](https://github.com/huggingface/safetensors): Simple,
  safe way to store and distribute tensors
- [pytorch/torcharrow](https://github.com/pytorch/torcharrow): A Pandas-inspired
  DataFrame library for SQL-like transformation with Pythonic and
  imperative-style API. Typical use case includes data preprocessing in ML
  models.

## Misc

- [allenai/RL4LMs](https://github.com/allenai/RL4LMs): A modular RL library to
  fine-tune language models to human preferences
  <https://rl4lms.apps.allenai.org/>

## Happy toy

- [minitorch/minitorch](https://github.com/minitorch/minitorch):
- [karpathy/micrograd](https://github.com/karpathy/micrograd): A tiny
  scalar-valued autograd engine and a neural net library on top of it with
  PyTorch-like API
- [geohot/tinygrad](https://github.com/geohot/tinygrad): You like pytorch? You
  like micrograd? You love tinygrad! ❤️
- [pranftw/neograd](https://github.com/pranftw/neograd): A deep learning
  framework created from scratch with Python and NumPy
  <https://neograd.readthedocs.io/>
- [mohammadpz/pytorch_forward_forward](https://github.com/mohammadpz/pytorch_forward_forward):
  Implementation of Hinton's forward-forward (FF) algorithm - an alternative to
  back-propagation
