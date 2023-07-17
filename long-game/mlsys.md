# ML Systems

## Resources

### Tutorials

- [google-research/tuning_playbook](https://github.com/google-research/tuning_playbook):
  A playbook for systematically maximizing the performance of deep learning
  models.
- [microsoft/AI-System](https://github.com/microsoft/AI-System): System for AI
  Education Resource. <https://microsoft.github.io/AI-System>
- [ML system design: 200 case studies to learn from](https://www.evidentlyai.com/ml-system-design)

### Books

- [chenzomi12/DeepLearningSystem](https://github.com/chenzomi12/DeepLearningSystem):
  Deep Learning System core principles introduction.
- [openmlsys/openmlsys-zh](https://github.com/openmlsys/openmlsys-zh): 《Machine
  Learning Systems: Design and Implementation》- Chinese Version
  <https://openmlsys.github.io>
- [chiphuyen/machine-learning-systems-design](https://github.com/chiphuyen/machine-learning-systems-design):
  A booklet on machine learning systems design with exercises. NOT the repo for
  the book "Designing Machine Learning Systems"
  <https://huyenchip.com/machine-learning-systems-design/toc.html>
- [d2l-ai/d2l-zh](https://github.com/d2l-ai/d2l-zh): 《动手学深度学习》：面向中
  文读者、能运行、可讨论。中英文版被 60 个国家的 400 所大学用于教学。
  <http://zh.d2l.ai>

## Framework

- [ray-project/ray](https://github.com/ray-project/ray): Ray is a unified
  framework for scaling AI and Python applications. Ray consists of a core
  distributed runtime and a toolkit of libraries (Ray AIR) for accelerating ML
  workloads. <https://ray.io>
- [google-research/torchsde](https://github.com/google-research/torchsde):
  Differentiable SDE solvers with GPU support and efficient sensitivity
  analysis.
- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb): In-Database Machine
  Learning <http://mindsdb.com>
- [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed): DeepSpeed is a
  deep learning optimization library that makes distributed training and
  inference easy, efficient, and effective. <https://www.deepspeed.ai/>
- [keras-team/keras-core](https://github.com/keras-team/keras-core): A
  multi-backend implementation of the Keras API, with support for TensorFlow,
  JAX, and PyTorch.

### Optimization

- [optuna/optuna](https://github.com/optuna/optuna): A hyperparameter
  optimization framework <https://optuna.org>
- [Epistimio/orion](https://github.com/Epistimio/orion): Asynchronous
  Distributed Hyperparameter Optimization. <https://orion.readthedocs.io>
- [google/vizier](https://github.com/google/vizier): Python-based research
  interface for blackbox and hyperparameter optimization, based on Google's
  internal Vizier Service. <https://oss-vizier.readthedocs.io>
- [leopard-ai/betty](https://github.com/leopard-ai/betty): Betty: an automatic
  differentiation library for generalized meta-learning and multilevel
  optimization <https://leopard-ai.github.io/betty>
- [facebookresearch/theseus](https://github.com/facebookresearch/theseus): A
  library for differentiable nonlinear optimization
  <https://sites.google.com/view/theseus-ai>
- [cvxpy/cvxpy](https://github.com/cvxpy/cvxpy): A Python-embedded modeling
  language for convex optimization problems. <https://www.cvxpy.org>
- [ceres-solver/ceres-solver](https://github.com/ceres-solver/ceres-solver): A
  large scale non-linear optimization library <http://ceres-solver.org>
- [google/or-tools](https://github.com/google/or-tools): Google's Operations
  Research tools <https://developers.google.com/optimization>
- [lucidrains/lion-pytorch](https://github.com/lucidrains/lion-pytorch): 🦁
  Lion, new optimizer discovered by Google Brain using genetic algorithms that
  is purportedly better than Adam(w), in Pytorch
- 🌟 [metaopt/torchopt](https://github.com/metaopt/torchopt): TorchOpt is an
  efficient library for differentiable optimization built upon PyTorch.
  <https://torchopt.readthedocs.io>
  - [Introducing TorchOpt: A High-Performance Differentiable Optimization Library for PyTorch](https://medium.com/pytorch/introducing-torchopt-a-high-performance-differentiable-optimization-library-for-pytorch-37c4c0ef6ae1)

### Network implementation

- [facebookresearch/xformers](https://github.com/facebookresearch/xformers):
  Hackable and optimized Transformers building blocks, supporting a composable
  construction. <https://facebookresearch.github.io/xformers>
- [facebookresearch/fairseq](https://github.com/facebookresearch/fairseq):
  Facebook AI Research Sequence-to-Sequence Toolkit written in Python.
- [francois-rozet/zuko](https://github.com/francois-rozet/zuko): Normalizing
  flows in PyTorch <https://zuko.readthedocs.io>
- [deepmind/alphatensor](https://github.com/deepmind/alphatensor): Discovering
  faster matrix multiplication algorithms with reinforcement learning
- [facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything):
  The repository provides code for running inference with the SegmentAnything
  Model (SAM), links for downloading the trained model checkpoints, and example
  notebooks that show how to use the model.
- [google/maxtext](https://github.com/google/maxtext): A simple, performant and
  scalable Jax LLM!
- [kingoflolz/mesh-transformer-jax](https://github.com/kingoflolz/mesh-transformer-jax):
  Model parallel transformers in JAX and Haiku
- [sanchit-gandhi/whisper-jax](https://github.com/sanchit-gandhi/whisper-jax):
  This repository contains optimised JAX code for OpenAI's Whisper Model,
  largely built on the 🤗 Hugging Face Transformers Whisper implementation.
  Compared to OpenAI's PyTorch code, Whisper JAX runs over 70x faster, making it
  the fastest Whisper implementation available.
- [tensorflow/tensor2tensor](https://github.com/tensorflow/tensor2tensor):
  Library of deep learning models and datasets designed to make deep learning
  more accessible and accelerate ML research.
- 🌟 [google/trax](https://github.com/google/trax): Trax — Deep Learning with
  Clear Code and Speed
- [NVIDIA-Merlin/Merlin](https://github.com/NVIDIA-Merlin/Merlin): NVIDIA Merlin
  is an open source library providing end-to-end GPU-accelerated recommender
  systems, from feature engineering and preprocessing to training deep learning
  models and running inference in production.
- 🌟
  [HazyResearch/flash-attention](https://github.com/HazyResearch/flash-attention):
  Fast and memory-efficient exact attention

### Inference engine / large-scale deployment

- [flashlight/flashlight](https://github.com/flashlight/flashlight): A C++
  standalone library for machine learning <https://fl.readthedocs.io/en/latest>
- [microsoft/torchscale](https://github.com/microsoft/torchscale): Transformers
  at any scale <https://aka.ms/nlpagi>
- [microsoft/DeepSpeed-MII](https://github.com/microsoft/DeepSpeed-MII): MII
  makes low-latency and high-throughput inference possible, powered by
  DeepSpeed.
- 🌟 [Lightning-AI/lightning](https://github.com/Lightning-AI/lightning): Deep
  learning framework to train, deploy, and ship AI products Lightning fast.
  <https://lightning.ai>
- [alpa-projects/alpa](https://github.com/alpa-projects/alpa): Training and
  serving large-scale neural networks <https://alpa.ai/>
- [mli/transformers-benchmarks](https://github.com/mli/transformers-benchmarks):
  real Transformer TeraFLOPS on various GPUs
- [FMInference/FlexGen](https://github.com/FMInference/FlexGen): Running large
  language models on a single GPU for throughput-oriented scenarios.
- [openai/evals](https://github.com/openai/evals): Evals is a framework for
  evaluating OpenAI models and an open-source registry of benchmarks.
- [NolanoOrg/cformers](https://github.com/NolanoOrg/cformers): SoTA Transformers
  with C-backend for fast inference on your CPU.
- [NVlabs/tiny-cuda-nn](https://github.com/NVlabs/tiny-cuda-nn): Lightning fast
  C++/CUDA neural network framework
- 🌟 [pytorch/TensorRT](https://github.com/pytorch/TensorRT):
  PyTorch/TorchScript/FX compiler for NVIDIA GPUs using TensorRT
  <https://pytorch.org/TensorRT>
- 🌟 [apple/ml-stable-diffusion](https://github.com/apple/ml-stable-diffusion):
  Stable Diffusion with Core ML on Apple Silicon
- [webonnx/wonnx](https://github.com/webonnx/wonnx): A GPU-accelerated ONNX
  inference run-time written 100% in Rust, ready for the web
- 🌟 [ggerganov/ggml](https://github.com/ggerganov/ggml): Tensor library for
  machine learning
- 🌟📝 [mosecorg/mosec](https://github.com/mosecorg/mosec): A high-performance
  serving framework for ML models, offers dynamic batching and multi-stage
  pipeline to fully exploit your compute machine
  <https://mosecorg.github.io/mosec/>
- [iqiyi/xgboost-serving](https://github.com/iqiyi/xgboost-serving): A flexible,
  high-performance serving system for machine learning models
- [facebookincubator/AITemplate](https://github.com/facebookincubator/AITemplate):
  AITemplate is a Python framework which renders neural network into high
  performance CUDA/HIP C++ code. Specialized for FP16 TensorCore (NVIDIA GPU)
  and MatrixCore (AMD GPU) inference.
- [tensorchord/inference-benchmark](https://github.com/tensorchord/inference-benchmark):
  WIP Benchmark for machine learning model online serving (LLM, embedding,
  Stable-Diffusion, Whisper)
- 📝
  [triton-inference-server/pytriton](https://github.com/triton-inference-server/pytriton):
  PyTriton is a Flask/FastAPI-like interface that simplifies Triton's deployment
  in Python environments. <https://triton-inference-server.github.io/pytriton/>

## Tensor inference / Compiler / Low level

- [apache/tvm](https://github.com/apache/tvm): Open deep learning compiler stack
  for cpu, gpu and specialized accelerators <https://tvm.apache.org>
- 🌟 [openai/triton](https://github.com/openai/triton): Development repository
  for the Triton language and compiler
- [NVIDIA/cutlass](https://github.com/NVIDIA/cutlass): CUDA Templates for Linear
  Algebra Subroutines
- [NVIDIA/TensorRT](https://github.com/NVIDIA/TensorRT): NVIDIA® TensorRT™, an
  SDK for high-performance deep learning inference, includes a deep learning
  inference optimizer and runtime that delivers low latency and high throughput
  for inference applications. <https://developer.nvidia.com/tensorrt>
- [openxla/xla](https://github.com/openxla/xla): A machine learning compiler for
  GPUs, CPUs, and ML accelerators
  - News:
    [OpenXLA is available now to accelerate and simplify machine learning](https://opensource.googleblog.com/2023/03/openxla-is-ready-to-accelerate-and-simplify-ml-development.html)
- [tensor-compiler/taco](https://github.com/tensor-compiler/taco): The Tensor
  Algebra Compiler (taco) computes sparse tensor expressions on CPUs and GPUs
  <http://tensor-compiler.org>
- [google/XNNPACK](https://github.com/google/XNNPACK): High-efficiency
  floating-point neural network inference operators for mobile, server, and Web
- 🌟 [geohot/tinygrad](https://github.com/geohot/tinygrad): You like pytorch?
  You like micrograd? You love tinygrad! ❤️ <https://tinygrad.org/>

## Platform framework / Workflow pipeline / MLOps

- [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow): Machine Learning
  Toolkit for Kubernetes
- [mlflow/mlflow](https://github.com/mlflow/mlflow): Open source platform for
  the machine learning lifecycle
- [Netflix/metaflow](https://github.com/Netflix/metaflow): 🚀 Build and manage
  real-life data science projects with ease! <https://metaflow.org>
- [bentoml/BentoML](https://github.com/bentoml/BentoML): Unified Model Serving
  Framework 🍱 <https://bentoml.com>
- [bentoml/Yatai](https://github.com/bentoml/Yatai): Model Deployment at Scale
  on Kubernetes 🦄️ <https://bentoml.com>
- [SeldonIO/seldon-core](https://github.com/SeldonIO/seldon-core): An MLOps
  framework to package, deploy, monitor and manage thousands of production
  machine learning models
- [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot): SkyPilot is
  a framework for easily running machine learning workloads on any cloud through
  a unified interface. <https://skypilot.readthedocs.io>
- [GokuMohandas/mlops-course](https://github.com/GokuMohandas/mlops-course): A
  project-based course on the foundations of MLOps to responsibly develop,
  deploy and maintain ML. <https://madewithml.com>
- [sematic-ai/sematic](https://github.com/sematic-ai/sematic): An open-source ML
  pipeline development platform
- [uptrain-ai/uptrain](https://github.com/uptrain-ai/uptrain): Your open-source
  ML monitoring and refinement toolkit. <https://uptrain.ai/>
- [microsoft/SynapseML](https://github.com/microsoft/SynapseML): Simple and
  Distributed Machine Learning <http://aka.ms/spark>
- 🌟 [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix): ML Observability
  in a Notebook - Uncover Insights, Surface Problems, Monitor, and Fine Tune
  your Generative LLM, CV and Tabular Models <https://docs.arize.com/phoenix>

## Autodiff

- [facebookresearch/shumai](https://github.com/facebookresearch/shumai): Fast
  Differentiable Tensor Library in JavaScript and TypeScript with Bun +
  Flashlight
- [google/tangent](https://github.com/google/tangent): Source-to-Source
  Debuggable Derivatives in Pure Python
- [aesara-devs/aesara](https://github.com/aesara-devs/aesara): Aesara is a
  Python library for defining, optimizing, and efficiently evaluating
  mathematical expressions involving multi-dimensional arrays.
  <https://aesara.readthedocs.io>
- [google/autobound](https://github.com/google/autobound): AutoBound
  automatically computes upper and lower bounds on functions.

## Jax ecology

- [n2cholas/awesome-jax](https://github.com/n2cholas/awesome-jax): JAX - A
  curated list of resources https://github.com/google/jax
- [openxla/xla](https://github.com/openxla/xla): A community-driven and modular
  open source compiler for ML.
- [patrick-kidger/equinox](https://github.com/patrick-kidger/equinox): Callable
  PyTrees and filtered transforms => neural networks in JAX.
  <https://docs.kidger.site/equinox>
- [stanford-crfm/levanter](https://github.com/stanford-crfm/levanter): Legibile,
  Scalable, Reproducible Foundation Models with Named Tensors and Jax
- [blackjax-devs/blackjax](https://github.com/blackjax-devs/blackjax): BlackJAX
  is a sampling library designed for ease of use, speed and modularity.
  <https://blackjax-devs.github.io/blackjax>
- [JaxGaussianProcesses/GPJax](https://github.com/JaxGaussianProcesses/GPJax):
  Gaussian processes in JAX. <https://docs.jaxgaussianprocesses.com/>
- [patrick-kidger/diffrax](https://github.com/patrick-kidger/diffrax): Numerical
  differential equation solvers in JAX. Autodifferentiable and GPU-capable.
  <https://docs.kidger.site/diffrax>
- [probml/dynamax](https://github.com/probml/dynamax): State Space Models
  library in JAX <https://probml.github.io/dynamax>
- [pyro-ppl/numpyro](https://github.com/pyro-ppl/numpyro): Probabilistic
  programming with NumPy powered by JAX for autograd and JIT compilation to
  GPU/TPU/CPU. <https://num.pyro.ai>
- [jax-ml/oryx](https://github.com/jax-ml/oryx): Oryx is a library for
  probabilistic programming and deep learning built on top of Jax.
  <https://tensorflow.org/probability/oryx>
- [vicariousinc/PGMax](https://github.com/vicariousinc/PGMax): Loopy belief
  propagation for factor graphs on discrete variables, in JAX!
  <https://pgmax.readthedocs.io>
- [google/flax](https://github.com/google/flax): Flax is a neural network
  library for JAX that is designed for flexibility.
  <https://flax.readthedocs.io>
- [google/trax](https://github.com/google/trax): Trax — Deep Learning with Clear
  Code and Speed
- [google/jaxopt](https://github.com/google/jaxopt): Hardware accelerated,
  batchable and differentiable optimizers in JAX. <https://jaxopt.github.io>
- [probml/sts-jax](https://github.com/probml/sts-jax): Structural Time Series in
  JAX
- [ASEM000/kernex](https://github.com/ASEM000/kernex): Stencil computations in
  JAX
- [metaopt/optree](https://github.com/metaopt/optree): OpTree: Optimized PyTree
  Utilities <https://optree.readthedocs.io>
- [ott-jax/ott](https://github.com/ott-jax/ott): Optimal Transport tools
  implemented with the JAX framework, to get auto-diff, parallel and jit-able
  computations. <https://ott-jax.readthedocs.io>
- [Autodesk/XLB](https://github.com/Autodesk/XLB): XLB: Accelerated Lattice
  Boltzmann (XLB) based on JAX for Physics-based ML

### DeepMind specialization

- [Using JAX to accelerate our research](https://www.deepmind.com/blog/using-jax-to-accelerate-our-research)
- [deepmind/jax](https://github.com/deepmind/jax): DeepMind JAX Ecosystem
- [deepmind/dm-haiku](https://github.com/deepmind/dm-haiku): JAX-based neural
  network library <https://dm-haiku.readthedocs.io>
- [deepmind/optax](https://github.com/deepmind/optax): Optax is a gradient
  processing and optimization library for JAX. <https://optax.readthedocs.io>
- [deepmind/rlax](https://github.com/deepmind/rlax): RLax (pronounced "relax")
  is a library built on top of JAX that exposes useful building blocks for
  implementing reinforcement learning agents. <https://rlax.readthedocs.io>
- [deepmind/chex](https://github.com/deepmind/chex): Chex is a library of
  utilities for helping to write reliable JAX code.
  <https://chex.readthedocs.io>
- [deepmind/jraph](https://github.com/deepmind/jraph): A Graph Neural Network
  Library in Jax <https://jraph.readthedocs.io/en/latest>
- 🌟 [deepmind/mctx](https://github.com/deepmind/mctx): Monte Carlo tree search
  in JAX
- [deepmind/distrax](https://github.com/deepmind/distrax): Distrax is a
  lightweight library of probability distributions and bijectors. It acts as a
  JAX-native reimplementation of a subset of TensorFlow Probability (TFP,
  https://www.tensorflow.org/probability), with some new features and emphasis
  on extensibility.
- [deepmind/PGMax](https://github.com/deepmind/PGMax): Loopy belief propagation
  for factor graphs on discrete variables in JAX

## Libraries

- [dmlc/dlpack](https://github.com/dmlc/dlpack): common in-memory tensor
  structure <https://dmlc.github.io/dlpack/latest>
- [xtensor-stack/xtensor](https://github.com/xtensor-stack/xtensor): C++ tensors
  with broadcasting and lazy computing
- [rapidsai/cuml](https://github.com/rapidsai/cuml): cuML - RAPIDS Machine
  Learning Library
- [pytorch/functorch](https://github.com/pytorch/functorch): functorch is
  JAX-like composable function transforms for PyTorch.
  <https://pytorch.org/functorch>
- [pytorch/torcharrow](https://github.com/pytorch/torcharrow): A Pandas-inspired
  DataFrame library for SQL-like transformation with Pythonic and
  imperative-style API. Typical use case includes data preprocessing in ML
  models.
- [huggingface/safetensors](https://github.com/huggingface/safetensors): Simple,
  safe way to store and distribute tensors
- [huggingface/evaluate](https://github.com/huggingface/evaluate): 🤗 Evaluate:
  A library for easily evaluating machine learning models and datasets.
  <https://huggingface.co/docs/evaluate>
- [google/pyglove](https://github.com/google/pyglove): Manipulating Python
  Programs
- [arogozhnikov/einops](https://github.com/arogozhnikov/einops): Deep learning
  operations reinvented (for pytorch, tensorflow, jax and others)
  <https://einops.rocks>
- [deepmind/tree](https://github.com/deepmind/tree): tree is a library for
  working with nested data structures <https://tree.readthedocs.io>
- [brentyi/jax_dataclasses](https://github.com/brentyi/jax_dataclasses):
  Pytrees + dataclasses ❤️
- [patrick-kidger/torchtyping](https://github.com/patrick-kidger/torchtyping):
  Type annotations and dynamic checking for a tensor's shape, dtype, names, etc.
- [google/jaxtyping](https://github.com/google/jaxtyping): Type annotations and
  runtime checking for shape and dtype of JAX arrays, and PyTrees.
- [pytorch/kineto](https://github.com/pytorch/kineto): A CPU+GPU Profiling
  library that provides access to timeline traces and hardware performance
  counters.
- [mosaicml/streaming](https://github.com/mosaicml/streaming): A Data Streaming
  Library for Efficient Neural Network Training
  <https://streaming.docs.mosaicml.com>

## Utils

- [tensorchord/envd](https://github.com/tensorchord/envd): 🏕️ Development
  environment for machine learning
- [NVIDIA/nvidia-docker](https://github.com/NVIDIA/nvidia-docker): Build and run
  Docker containers leveraging NVIDIA GPUs
- [aws/deep-learning-containers](https://github.com/aws/deep-learning-containers):
  AWS Deep Learning Containers (DLCs) are a set of Docker images for training
  and serving models in TensorFlow, TensorFlow 2, PyTorch, and MXNet.
  <https://docs.aws.amazon.com/deep-learning-containers/latest/devguide/deep-learning-containers-images.html>
- [replicate/cog](https://github.com/replicate/cog): Containers for machine
  learning
- [alteryx/featuretools](https://github.com/alteryx/featuretools): An open
  source python library for automated feature engineering
  <https://www.featuretools.com>
- [XuehaiPan/nvitop](https://github.com/XuehaiPan/nvitop): An interactive
  NVIDIA-GPU process viewer and beyond, the one-stop solution for GPU process
  management. <https://nvitop.readthedocs.io/>
- [Syllo/nvtop](https://github.com/Syllo/nvtop): GPUs process monitoring for
  AMD, Intel and NVIDIA
- [wookayin/gpustat](https://github.com/wookayin/gpustat): 📊 A simple
  command-line utility for querying and monitoring GPU status

## Misc

- [allenai/RL4LMs](https://github.com/allenai/RL4LMs): A modular RL library to
  fine-tune language models to human preferences
  <https://rl4lms.apps.allenai.org>

## Happy toy

- [minitorch/minitorch](https://github.com/minitorch/minitorch):
- [karpathy/micrograd](https://github.com/karpathy/micrograd): A tiny
  scalar-valued autograd engine and a neural net library on top of it with
  PyTorch-like API
- [pranftw/neograd](https://github.com/pranftw/neograd): A deep learning
  framework created from scratch with Python and NumPy
  <https://neograd.readthedocs.io>
- [mohammadpz/pytorch_forward_forward](https://github.com/mohammadpz/pytorch_forward_forward):
  Implementation of Hinton's forward-forward (FF) algorithm - an alternative to
  back-propagation