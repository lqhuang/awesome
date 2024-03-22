# ML Systems

## Resources

### Tutorials

- [google-research/tuning_playbook](https://github.com/google-research/tuning_playbook): A playbook for systematically maximizing the performance of deep learning models.
- [microsoft/AI-System](https://github.com/microsoft/AI-System): System for AI Education Resource. <https://microsoft.github.io/AI-System>
- [ML system design: 200 case studies to learn from](https://www.evidentlyai.com/ml-system-design)
- [eugeneyan/applied-ml](https://github.com/eugeneyan/applied-ml): 📚 Papers & tech blogs by companies sharing their work on data science & machine learning in production.
- [mit-han-lab/parallel-computing-tutorial](https://github.com/mit-han-lab/parallel-computing-tutorial): This repository introduces several optimization techniques that can be applied to improve the parallelism of matrix multiplication.
- [ayaka14732/tpu-starter](https://github.com/ayaka14732/tpu-starter): Everything you want to know about Google Cloud TPU
- [stas00/ml-engineering](https://github.com/stas00/ml-engineering): Machine Learning Engineering Guides and Tools <https://stasosphere.com/machine-learning/>
- [srush/Autodiff-Puzzles](https://github.com/srush/Autodiff-Puzzles): This notebook contains a series of self-contained puzzles for learning about derivatives in tensor libraries.
- [srush/Tensor-Puzzles](https://github.com/srush/Tensor-Puzzles): Solve puzzles. Improve your pytorch.
- [srush/GPU-Puzzles](https://github.com/srush/GPU-Puzzles): Solve puzzles. Learn CUDA.
- [srush/Transformer-Puzzles](https://github.com/srush/Transformer-Puzzles): Puzzles for exploring transformers
- [Fullstack deep learning](https://fullstackdeeplearning.com/): News, community, and courses for people building AI-powered products.
- [hyperai/tvm-cn](https://github.com/hyperai/tvm-cn): TVM Documentation in Chinese Simplified / TVM 中文文档 <https://tvm.hyper.ai>
- [HazyResearch/aisys-building-blocks](https://github.com/HazyResearch/aisys-building-blocks): Building blocks for foundation models.
- [jessevig/bertviz](https://github.com/jessevig/bertviz): BertViz: Visualize Attention in NLP Models (BERT, GPT2, BART, etc.) <https://towardsdatascience.com/deconstructing-bert-part-2-visualizing-the-inner-workings-of-attention-60a16d86b5c1>

### Books

- [chenzomi12/DeepLearningSystem](https://github.com/chenzomi12/DeepLearningSystem): Deep Learning System core principles introduction.
- [openmlsys/openmlsys-zh](https://github.com/openmlsys/openmlsys-zh): 《Machine Learning Systems: Design and Implementation》- Chinese Version <https://openmlsys.github.io>
- [chiphuyen/machine-learning-systems-design](https://github.com/chiphuyen/machine-learning-systems-design): A booklet on machine learning systems design with exercises. NOT the repo for the book "Designing Machine Learning Systems" <https://huyenchip.com/machine-learning-systems-design/toc.html>
- [d2l-ai/d2l-zh](https://github.com/d2l-ai/d2l-zh): 《动手学深度学习》：面向中文读者、能运行、可讨论。中英文版被 60 个国家的 400 所大学用于教学。 <http://zh.d2l.ai>
- [stas00/ml-engineering](https://github.com/stas00/ml-engineering): Machine Learning Engineering Open Book <https://stasosphere.com/machine-learning/>

## Framework and libraries

### General framework

- [ray-project/ray](https://github.com/ray-project/ray): Ray is a unified framework for scaling AI and Python applications. Ray consists of a core distributed runtime and a toolkit of libraries (Ray AIR) for accelerating ML workloads. <https://ray.io>
- [google-research/torchsde](https://github.com/google-research/torchsde): Differentiable SDE solvers with GPU support and efficient sensitivity analysis.
- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb): In-Database Machine Learning <http://mindsdb.com>
- [microsoft/DeepSpeed](https://github.com/microsoft/DeepSpeed): DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective. <https://www.deepspeed.ai/>
- [keras-team/keras-core](https://github.com/keras-team/keras-core): A multi-backend implementation of the Keras API, with support for TensorFlow, JAX, and PyTorch.
- [online-ml/river](https://github.com/online-ml/river): 🌊 Online machine learning in Python <https://riverml.xyz>
- 🌟 [geohot/tinygrad](https://github.com/geohot/tinygrad): You like pytorch? You like micrograd? You love tinygrad! ❤️ <https://tinygrad.org/>
- [intelligent-machine-learning/dlrover](https://github.com/intelligent-machine-learning/dlrover): DLRover: An Automatic Distributed Deep Learning System
- [thu-ml/tianshou](https://github.com/thu-ml/tianshou): An elegant PyTorch deep reinforcement learning library. <https://tianshou.readthedocs.io>
- [pycaret/pycaret](https://github.com/pycaret/pycaret): An open-source, low-code machine learning library in Python <https://www.pycaret.org>
- 🌟 [intel/scikit-learn-intelex](https://github.com/intel/scikit-learn-intelex): Intel(R) Extension for Scikit-learn is a seamless way to speed up your Scikit-learn application <https://intel.github.io/scikit-learn-intelex/>
- [mlpack/mlpack](https://github.com/mlpack/mlpack): mlpack: a fast, header-only C++ machine learning library <https://www.mlpack.org/>
- [adap/flower](https://github.com/adap/flower): Flower: A Friendly Federated Learning Framework <https://flower.dev>
- [facebookresearch/Pearl](https://github.com/facebookresearch/Pearl): A Production-ready Reinforcement Learning AI Agent Library brought by the Applied Reinforcement Learning team at Meta.
- [salesforce/jaxformer](https://github.com/salesforce/jaxformer): Minimal library to train LLMs on TPU in JAX with pjit().
- [elixir-nx/nx](https://github.com/elixir-nx/nx): Multi-dimensional arrays (tensors) and numerical definitions for Elixir
- [CarperAI/trlx](https://github.com/CarperAI/trlx): A repo for distributed training of language models with Reinforcement Learning via Human Feedback (RLHF)

### Optimization

- [optuna/optuna](https://github.com/optuna/optuna): A hyperparameter optimization framework <https://optuna.org>
- [Epistimio/orion](https://github.com/Epistimio/orion): Asynchronous Distributed Hyperparameter Optimization. <https://orion.readthedocs.io>
- [google/vizier](https://github.com/google/vizier): Python-based research interface for blackbox and hyperparameter optimization, based on Google's internal Vizier Service. <https://oss-vizier.readthedocs.io>
- [leopard-ai/betty](https://github.com/leopard-ai/betty): Betty: an automatic differentiation library for generalized meta-learning and multilevel optimization <https://leopard-ai.github.io/betty>
- [facebookresearch/theseus](https://github.com/facebookresearch/theseus): A library for differentiable nonlinear optimization <https://sites.google.com/view/theseus-ai>
- [cvxpy/cvxpy](https://github.com/cvxpy/cvxpy): A Python-embedded modeling language for convex optimization problems. <https://www.cvxpy.org>
- [ceres-solver/ceres-solver](https://github.com/ceres-solver/ceres-solver): A large scale non-linear optimization library <http://ceres-solver.org>
- [google/or-tools](https://github.com/google/or-tools): Google's Operations Research tools <https://developers.google.com/optimization>
- [lucidrains/lion-pytorch](https://github.com/lucidrains/lion-pytorch): 🦁 Lion, new optimizer discovered by Google Brain using genetic algorithms that is purportedly better than Adam(w), in Pytorch
- 🌟 [metaopt/torchopt](https://github.com/metaopt/torchopt): TorchOpt is an efficient library for differentiable optimization built upon PyTorch. <https://torchopt.readthedocs.io>
  - [Introducing TorchOpt: A High-Performance Differentiable Optimization Library for PyTorch](https://medium.com/pytorch/introducing-torchopt-a-high-performance-differentiable-optimization-library-for-pytorch-37c4c0ef6ae1)
- [pytorch/botorch](https://github.com/pytorch/botorch): Bayesian optimization in PyTorch <https://botorch.org/>
- [facebookresearch/nevergrad](https://github.com/facebookresearch/nevergrad): A Python toolbox for performing gradient-free optimization <https://facebookresearch.github.io/nevergrad/>

### Network implementation

- [facebookresearch/xformers](https://github.com/facebookresearch/xformers): Hackable and optimized Transformers building blocks, supporting a composable construction. <https://facebookresearch.github.io/xformers>
- [facebookresearch/fairseq](https://github.com/facebookresearch/fairseq): Facebook AI Research Sequence-to-Sequence Toolkit written in Python.
- [facebookresearch/metaseq](https://github.com/facebookresearch/metaseq): Repo for external large-scale work
- [facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything): The repository provides code for running inference with the SegmentAnything Model (SAM), links for downloading the trained model checkpoints, and example notebooks that show how to use the model.
- [tensorflow/tensor2tensor](https://github.com/tensorflow/tensor2tensor): Library of deep learning models and datasets designed to make deep learning more accessible and accelerate ML research.
- [kingoflolz/mesh-transformer-jax](https://github.com/kingoflolz/mesh-transformer-jax): Model parallel transformers in JAX and Haiku
- [sanchit-gandhi/whisper-jax](https://github.com/sanchit-gandhi/whisper-jax): This repository contains optimised JAX code for OpenAI's Whisper Model, largely built on the 🤗 Hugging Face Transformers Whisper implementation. Compared to OpenAI's PyTorch code, Whisper JAX runs over 70x faster, making it the fastest Whisper implementation available.
- [guillaumekln/faster-whisper](https://github.com/guillaumekln/faster-whisper): Faster Whisper transcription with CTranslate2
- 🌟 [google/trax](https://github.com/google/trax): Trax — Deep Learning with Clear Code and Speed
- [google/maxtext](https://github.com/google/maxtext): A simple, performant and scalable Jax LLM!
- [google/maxdiffusion](https://github.com/google/maxdiffusion): MaxDiffusion is a Latent Diffusion model written in pure Python/Jax and targeting Google Cloud TPUs.
- [NVIDIA-Merlin/Merlin](https://github.com/NVIDIA-Merlin/Merlin): NVIDIA Merlin is an open source library providing end-to-end GPU-accelerated recommender systems, from feature engineering and preprocessing to training deep learning models and running inference in production.
- 🌟 [Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention): Fast and memory-efficient exact attention
- [explosion/curated-transformers](https://github.com/explosion/curated-transformers): 🤖 A PyTorch library of curated Transformer models and their composable components
- [THUDM/SwissArmyTransformer](https://github.com/THUDM/SwissArmyTransformer): SwissArmyTransformer is a flexible and powerful library to develop your own Transformer variants. <https://THUDM.github.io/SwissArmyTransformer>
- [NVIDIA/FasterTransformer](https://github.com/NVIDIA/FasterTransformer): Transformer related optimization, including BERT, GPT <https://desktop.github.com>
- 🌟 [flashinfer-ai/flashinfer](https://github.com/flashinfer-ai/flashinfer): FlashInfer: Kernel Library for LLM Serving <https://flashinfer.ai>
  - Comprehensive Attention Kernels
  - Optimized Shared-Prefix Batch Decoding
  - Accelerate Attention for Compressed/Quantized KV-Cache
  - no JAX support?
- [pytorch-labs/segment-anything-fast](https://github.com/pytorch-labs/segment-anything-fast): A batched offline inference oriented version of segment-anything
  - [Accelerating Generative AI with PyTorch: Segment Anything, Fast](https://pytorch.org/blog/accelerating-generative-ai/)
- 🌟 [pytorch-labs/gpt-fast](https://github.com/pytorch-labs/gpt-fast): Simple and efficient pytorch-native transformer text generation in <1000 LOC of python.
  - [Accelerating Generative AI with PyTorch II: GPT, Fast](https://pytorch.org/blog/accelerating-generative-ai-2/)
  - [Horace He (@cHHillee)'s threads about gpt-fast](https://twitter.com/cHHillee/status/1730293330213531844)
- [facebookresearch/DiT](https://github.com/facebookresearch/DiT): Official PyTorch Implementation of "Scalable Diffusion Models with Transformers"
- [crabml/crabml](https://github.com/crabml/crabml): crabml is an ongoing experiment that aims to reimplement GGML using Rust.

### Inference engine / large-scale deployment

- [flashlight/flashlight](https://github.com/flashlight/flashlight): A C++ standalone library for machine learning <https://fl.readthedocs.io/en/latest>
- [microsoft/torchscale](https://github.com/microsoft/torchscale): Transformers at any scale <https://aka.ms/nlpagi>
- [microsoft/DeepSpeed-MII](https://github.com/microsoft/DeepSpeed-MII): MII makes low-latency and high-throughput inference possible, powered by DeepSpeed.
- [Lightning-AI/lightning](https://github.com/Lightning-AI/lightning): Deep learning framework to train, deploy, and ship AI products Lightning fast. <https://lightning.ai>
- [alpa-projects/alpa](https://github.com/alpa-projects/alpa): Training and serving large-scale neural networks <https://alpa.ai/>
- [FMInference/FlexGen](https://github.com/FMInference/FlexGen): Running large language models on a single GPU for throughput-oriented scenarios.
- [NolanoOrg/cformers](https://github.com/NolanoOrg/cformers): SoTA Transformers with C-backend for fast inference on your CPU.
- [NVlabs/tiny-cuda-nn](https://github.com/NVlabs/tiny-cuda-nn): Lightning fast C++/CUDA neural network framework
- 🌟 [pytorch/TensorRT](https://github.com/pytorch/TensorRT): PyTorch/TorchScript/FX compiler for NVIDIA GPUs using TensorRT <https://pytorch.org/TensorRT>
- [webonnx/wonnx](https://github.com/webonnx/wonnx): A GPU-accelerated ONNX inference run-time written 100% in Rust, ready for the web
- 🌟 [ggerganov/ggml](https://github.com/ggerganov/ggml): Tensor library for machine learning
- 📝 [mosecorg/mosec](https://github.com/mosecorg/mosec): A high-performance serving framework for ML models, offers dynamic batching and multi-stage pipeline to fully exploit your compute machine <https://mosecorg.github.io/mosec/>
- [autonomi-ai/nos](https://github.com/autonomi-ai/nos): ⚡️ Nitrous oxide for your AI infrastructure. <https://docs.nos.run/>
- [iqiyi/xgboost-serving](https://github.com/iqiyi/xgboost-serving): A flexible, high-performance serving system for machine learning models
- [facebookincubator/AITemplate](https://github.com/facebookincubator/AITemplate): AITemplate is a Python framework which renders neural network into high performance CUDA/HIP C++ code. Specialized for FP16 TensorCore (NVIDIA GPU) and MatrixCore (AMD GPU) inference.
- 📝 [triton-inference-server/pytriton](https://github.com/triton-inference-server/pytriton): PyTriton is a Flask/FastAPI-like interface that simplifies Triton's deployment in Python environments. <https://triton-inference-server.github.io/pytriton/>
- [triton-inference-server/server](https://github.com/triton-inference-server/server): The Triton Inference Server provides an optimized cloud and edge inferencing solution. <https://docs.nvidia.com/deeplearning/triton-inference-server/user-guide/docs/index.html>
- [kserve/kserve](https://github.com/kserve/kserve): Standardized Serverless ML Inference Platform on Kubernetes <https://kserve.github.io/website/>
- 📝 [ModelTC/lightllm](https://github.com/ModelTC/lightllm): LightLLM is a Python-based LLM (Large Language Model) inference and serving framework, notable for its lightweight design, easy scalability, and high-speed performance. <https://desktop.github.com>
- [huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference): Large Language Model Text Generation Inference <https://huggingface.github.io/text-generation-inference/>
- 🌟 [pytorch/executorch](https://github.com/pytorch/executorch): End-to-end solution for enabling on-device AI across mobile and edge devices for PyTorch models <https://pytorch.org/edge>
- [intel/intel-extension-for-transformers](https://github.com/intel/intel-extension-for-transformers): ⚡ Build your chatbot within minutes on your favorite device; offer SOTA compression techniques for LLMs; run LLMs efficiently on Intel Platforms⚡
- [neuralmagic/deepsparse](https://github.com/neuralmagic/deepsparse): Sparsity-aware deep learning inference runtime for CPUs <https://neuralmagic.com/deepsparse/>
- [lm-sys/FastChat](https://github.com/lm-sys/FastChat): An open platform for training, serving, and evaluating large language models. Release repo for Vicuna and Chatbot Arena.
- [FMInference/FlexGen](https://github.com/FMInference/FlexGen): Running large language models on a single GPU for throughput-oriented scenarios.
- [alpa-projects/alpa](https://github.com/alpa-projects/alpa): Training and serving large-scale neural networks with auto parallelization. <https://alpa.ai>
- 🌟 [ml-explore/mlx](https://github.com/ml-explore/mlx): MLX: An array framework for Apple silicon
  - [ml-explore/mlx-examples](https://github.com/ml-explore/mlx-examples): Examples in the MLX framework
  - [MLX Community Projects #654](https://github.com/ml-explore/mlx/discussions/654)
  - [mlx-graphs/mlx-graphs](https://github.com/mlx-graphs/mlx-graphs): Graph Neural Network library made for Apple Silicon <https://mlx-graphs.github.io/mlx-graphs/>
  - [tedwards2412/samplex](https://github.com/tedwards2412/samplex): Package of useful sampling algorithms written in MLX.
- [rustformers/llm](https://github.com/rustformers/llm): Run inference for Large Language Models on CPU, with Rust 🦀🚀🦙
- [vllm-project/vllm](https://github.com/vllm-project/vllm): A high-throughput and memory-efficient inference and serving engine for LLMs <https://vllm.readthedocs.io>
- [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm): Bringing large-language models and chat to web browsers. Everything runs inside the browser with no server support. <https://mlc.ai/web-llm>
- [bentoml/OpenLLM](https://github.com/bentoml/OpenLLM): An open platform for operating large language models(LLMs) in production. Fine-tune, serve, deploy, and monitor any LLMs with ease.
- [predibase/lorax](https://github.com/predibase/lorax): Multi-LoRA inference server that scales to 1000s of fine-tuned LLMs <https://predibase.github.io/lorax/>

### Benchmark

- [mli/transformers-benchmarks](https://github.com/mli/transformers-benchmarks): real Transformer TeraFLOPS on various GPUs
- [openai/evals](https://github.com/openai/evals): Evals is a framework for evaluating OpenAI models and an open-source registry of benchmarks.
- [tensorchord/inference-benchmark](https://github.com/tensorchord/inference-benchmark): WIP Benchmark for machine learning model online serving (LLM, embedding, Stable-Diffusion, Whisper)
- [mlcommons/algorithmic-efficiency](https://github.com/mlcommons/algorithmic-efficiency): MLCommons Algorithmic Efficiency is a benchmark and competition measuring neural network training speedups due to algorithmic improvements in both training algorithms and models. <https://mlcommons.org/en/groups/research-algorithms/>
- [mlcommons/training](https://github.com/mlcommons/training): Reference implementations of MLPerf™ training benchmarks <https://mlcommons.org/en/groups/training>
- [mlcommons/inference](https://github.com/mlcommons/inference): Reference implementations of MLPerf™ inference benchmarks <https://mlcommons.org/en/groups/inference>
- [mlcommons/logging](https://github.com/mlcommons/logging): MLPerf™ logging library <https://mlcommons.org/en/groups/best-practices-benchmark-infra>

### Platform / Workflow pipeline / MLOps

- [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow): Machine Learning Toolkit for Kubernetes
- [mlflow/mlflow](https://github.com/mlflow/mlflow): Open source platform for the machine learning lifecycle
- [Netflix/metaflow](https://github.com/Netflix/metaflow): 🚀 Build and manage real-life data science projects with ease! <https://metaflow.org>
- [bentoml/BentoML](https://github.com/bentoml/BentoML): Unified Model Serving Framework 🍱 <https://bentoml.com>
- [bentoml/Yatai](https://github.com/bentoml/Yatai): Model Deployment at Scale on Kubernetes 🦄️ <https://bentoml.com>
- [SeldonIO/seldon-core](https://github.com/SeldonIO/seldon-core): An MLOps framework to package, deploy, monitor and manage thousands of production machine learning models
- [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot): SkyPilot is a framework for easily running machine learning workloads on any cloud through a unified interface. <https://skypilot.readthedocs.io>
- [GokuMohandas/mlops-course](https://github.com/GokuMohandas/mlops-course): A project-based course on the foundations of MLOps to responsibly develop, deploy and maintain ML. <https://madewithml.com>
- [sematic-ai/sematic](https://github.com/sematic-ai/sematic): An open-source ML pipeline development platform
- [uptrain-ai/uptrain](https://github.com/uptrain-ai/uptrain): Your open-source ML monitoring and refinement toolkit. <https://uptrain.ai/>
- [microsoft/SynapseML](https://github.com/microsoft/SynapseML): Simple and Distributed Machine Learning <http://aka.ms/spark>
- 🌟 [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix): ML Observability in a Notebook - Uncover Insights, Surface Problems, Monitor, and Fine Tune your Generative LLM, CV and Tabular Models <https://docs.arize.com/phoenix>
- [eth-easl/orion](https://github.com/eth-easl/orion): An interference-aware scheduler for fine-grained GPU sharing
- [iterative/dvc](https://github.com/iterative/dvc): 🦉 ML Experiments Management with Git <https://dvc.org>

## Tensor inference

- [NVIDIA/cutlass](https://github.com/NVIDIA/cutlass): CUDA Templates for Linear Algebra Subroutines
- [NVIDIA/TensorRT](https://github.com/NVIDIA/TensorRT): NVIDIA® TensorRT™, an SDK for high-performance deep learning inference, includes a deep learning inference optimizer and runtime that delivers low latency and high throughput for inference applications. <https://developer.nvidia.com/tensorrt>
- [google/XNNPACK](https://github.com/google/XNNPACK): High-efficiency floating-point neural network inference operators for mobile, server, and Web
- [Azure/MS-AMP](https://github.com/Azure/MS-AMP): Microsoft Automatic Mixed Precision Library <https://azure.github.io/MS-AMP/>

## Compiler

- [merrymercy/awesome-tensor-compilers](https://github.com/merrymercy/awesome-tensor-compilers): A list of awesome compiler projects and papers for tensor computation and deep learning.
- 🌟 [apache/tvm](https://github.com/apache/tvm): Open deep learning compiler stack for cpu, gpu and specialized accelerators <https://tvm.apache.org>
  - [wzh99/relay-mlir](https://github.com/wzh99/relay-mlir): An MLIR-based toy DL compiler for TVM Relay.
- 🌟 [openai/triton](https://github.com/openai/triton): Development repository for the Triton language and compiler
- 🌟 [llvm/torch-mlir](https://github.com/llvm/torch-mlir): The Torch-MLIR project aims to provide first class support from the PyTorch ecosystem to the MLIR ecosystem.
- 🌟 [openxla/xla](https://github.com/openxla/xla): A machine learning compiler for GPUs, CPUs, and ML accelerators
  - News: [OpenXLA is available now to accelerate and simplify machine learning](https://opensource.googleblog.com/2023/03/openxla-is-ready-to-accelerate-and-simplify-ml-development.html)
  - 🌟 [openxla/stablehlo](https://github.com/openxla/stablehlo): Backward compatible ML compute opset inspired by HLO/MHLO
  - [LaurentMazare/xla-rs](https://github.com/LaurentMazare/xla-rs): Experimentation using the xla compiler from rust
- [tensor-compiler/taco](https://github.com/tensor-compiler/taco): The Tensor Algebra Compiler (taco) computes sparse tensor expressions on CPUs and GPUs <http://tensor-compiler.org>
- [pytorch/glow](https://github.com/pytorch/glow): Compiler for Neural Network hardware accelerators
- [statusfailed/catgrad](https://github.com/statusfailed/catgrad): a categorical deep learning compiler
  - [ArXiv - Reverse derivative categories](https://arxiv.org/abs/1910.07065)
- [nod-ai/SHARK-Turbine](https://github.com/nod-ai/SHARK-Turbine): Unified compiler/runtime for interfacing with PyTorch Dynamo.

## Autodiff

- [facebookresearch/shumai](https://github.com/facebookresearch/shumai): Fast Differentiable Tensor Library in JavaScript and TypeScript with Bun + Flashlight
- [google/tangent](https://github.com/google/tangent): Source-to-Source Debuggable Derivatives in Pure Python
  - [srush/tangent](https://github.com/srush/tangent): Source-to-Source Debuggable Derivatives in Pure Python
  - [srush/triton-autodiff](https://github.com/srush/triton-autodiff): Experiment of using Tangent to autodiff triton
- [aesara-devs/aesara](https://github.com/aesara-devs/aesara): Aesara is a Python library for defining, optimizing, and efficiently evaluating mathematical expressions involving multi-dimensional arrays. <https://aesara.readthedocs.io>
- [google/autobound](https://github.com/google/autobound): AutoBound automatically computes upper and lower bounds on functions.
- [gtn-org/gtn](https://github.com/gtn-org/gtn): Automatic differentiation with weighted finite-state transducers.
- [mitsuba-renderer/drjit](https://github.com/mitsuba-renderer/drjit): Dr.Jit — A Just-In-Time-Compiler for Differentiable Rendering
- [taichi-dev/taichi](https://github.com/taichi-dev/taichi): Productive & portable high-performance programming in Python. <https://taichi-lang.org>
- [taichi-dev/difftaichi](https://github.com/taichi-dev/difftaichi): 10 differentiable physical simulators built with Taichi differentiable programming (DiffTaichi, ICLR 2020)

## Jax ecology

- [n2cholas/awesome-jax](https://github.com/n2cholas/awesome-jax): JAX - A curated list of resources https://github.com/google/jax
- [patrick-kidger/equinox](https://github.com/patrick-kidger/equinox): Callable PyTrees and filtered transforms => neural networks in JAX. <https://docs.kidger.site/equinox>
- [patrick-kidger/optimistix](https://github.com/patrick-kidger/optimistix): Nonlinear optimisation (root-finding, least squares, ...) in JAX+Equinox. <https://docs.kidger.site/optimistix>
- [patrick-kidger/diffrax](https://github.com/patrick-kidger/diffrax): Numerical differential equation solvers in JAX. Autodifferentiable and GPU-capable. <https://docs.kidger.site/diffrax>
- [patrick-kidger/quax](https://github.com/patrick-kidger/quax): Multiple dispatch over abstract array types in JAX.
- [stanford-crfm/levanter](https://github.com/stanford-crfm/levanter): Legibile, Scalable, Reproducible Foundation Models with Named Tensors and Jax
- [blackjax-devs/blackjax](https://github.com/blackjax-devs/blackjax): BlackJAX is a sampling library designed for ease of use, speed and modularity. <https://blackjax-devs.github.io/blackjax>
- [JaxGaussianProcesses/GPJax](https://github.com/JaxGaussianProcesses/GPJax): Gaussian processes in JAX. <https://docs.jaxgaussianprocesses.com/>
- [pyro-ppl/numpyro](https://github.com/pyro-ppl/numpyro): Probabilistic programming with NumPy powered by JAX for autograd and JIT compilation to GPU/TPU/CPU. <https://num.pyro.ai>
- [jax-ml/oryx](https://github.com/jax-ml/oryx): Oryx is a library for probabilistic programming and deep learning built on top of Jax. <https://tensorflow.org/probability/oryx>
- [vicariousinc/PGMax](https://github.com/vicariousinc/PGMax): Loopy belief propagation for factor graphs on discrete variables, in JAX! <https://pgmax.readthedocs.io>
- [probml/dynamax](https://github.com/probml/dynamax): State Space Models library in JAX <https://probml.github.io/dynamax>
- [probml/sts-jax](https://github.com/probml/sts-jax): Structural Time Series in JAX
- [ASEM000/kernex](https://github.com/ASEM000/kernex): Stencil computations in JAX
- [metaopt/optree](https://github.com/metaopt/optree): OpTree: Optimized PyTree Utilities <https://optree.readthedocs.io>
- [ott-jax/ott](https://github.com/ott-jax/ott): Optimal Transport tools implemented with the JAX framework, to get auto-diff, parallel and jit-able computations. <https://ott-jax.readthedocs.io>
- [Autodesk/XLB](https://github.com/Autodesk/XLB): XLB: Accelerated Lattice Boltzmann (XLB) based on JAX for Physics-based ML
- [xl0/lovely-jax](https://github.com/xl0/lovely-jax): JAX Arrays for human consumption <https://xl0.github.io/lovely-jax>
- [apple/axlearn](https://github.com/apple/axlearn): AXLearn is a library built on top of JAX and XLA to support development of large-scale deep learning models.
- [facebookresearch/minimax](https://github.com/facebookresearch/minimax): Efficient baselines for autocurricula in JAX.
- [JiaYaobo/fenbux](https://github.com/JiaYaobo/fenbux): A Simple Statistical Distribution Library in JAX <https://jiayaobo.github.io/fenbux/>
- [hayden-donnelly/jax-to-cpp](https://github.com/hayden-donnelly/jax-to-cpp): Generate HLO with JAX then execute in C++.
- [young-geng/scalax](https://github.com/young-geng/scalax): A simple library for scaling up JAX programs

### DeepMind specialization

- [Using JAX to accelerate our research](https://www.deepmind.com/blog/using-jax-to-accelerate-our-research)
- [google-deepmind/jax](https://github.com/google-deepmind/jax): DeepMind JAX Ecosystem
- [google-deepmind/dm-haiku](https://github.com/google-deepmind/dm-haiku): JAX-based neural network library <https://dm-haiku.readthedocs.io>
- [google-deepmind/optax](https://github.com/google-deepmind/optax): Optax is a gradient processing and optimization library for JAX. <https://optax.readthedocs.io>
- [google-deepmind/rlax](https://github.com/google-deepmind/rlax): RLax (pronounced "relax") is a library built on top of JAX that exposes useful building blocks for implementing reinforcement learning agents. <https://rlax.readthedocs.io>
- [google-deepmind/chex](https://github.com/google-deepmind/chex): Chex is a library of utilities for helping to write reliable JAX code. <https://chex.readthedocs.io>
- [google-deepmind/jraph](https://github.com/google-deepmind/jraph): A Graph Neural Network Library in Jax <https://jraph.readthedocs.io/en/latest>
- 🌟 [google-deepmind/mctx](https://github.com/google-deepmind/mctx): Monte Carlo tree search in JAX
- [google-deepmind/distrax](https://github.com/google-deepmind/distrax): Distrax is a lightweight library of probability distributions and bijectors. It acts as a JAX-native reimplementation of a subset of TensorFlow Probability (TFP, https://www.tensorflow.org/probability), with some new features and emphasis on extensibility.
- [google-deepmind/PGMax](https://github.com/google-deepmind/PGMax): Loopy belief propagation for factor graphs on discrete variables in JAX
- [google-deepmind/synjax](https://github.com/google-deepmind/synjax): SynJax is a neural network library for JAX structured probability distributions.
- [google-deepmind/alphatensor](https://github.com/google-deepmind/alphatensor): Discovering faster matrix multiplication algorithms with reinforcement learning

### Google specialization

- [google/flax](https://github.com/google/flax): Flax is a neural network library for JAX that is designed for flexibility. <https://flax.readthedocs.io>
- [google/trax](https://github.com/google/trax): Trax — Deep Learning with Clear Code and Speed
- [google/jaxopt](https://github.com/google/jaxopt): Hardware accelerated, batchable and differentiable optimizers in JAX. <https://jaxopt.github.io>
- [google/paxml](https://github.com/google/paxml): Pax is a Jax-based machine learning framework for training large scale models. Pax allows for advanced and fully configurable experimentation and parallelization, and has demonstrated industry leading model flop utilization rates.
- [google/orbax](https://github.com/google/orbax): Orbax provides common utility libraries for JAX users. <https://orbax.readthedocs.io/>
- [google-research/discs](https://github.com/google-research/discs): DISCS: The code base for the Benchmark for Discrete Sampling

This is not an officially supported Google product.

- [google-research/gpax](https://github.com/google-research/gpax): Gaussian processes in Jax.
- [google-research/e3x](https://github.com/google-research/e3x): E3x is a JAX library for constructing efficient E(3)-equivariant deep learning architectures built on top of Flax.

## Libraries

- [pytorch/functorch](https://github.com/pytorch/functorch): functorch is JAX-like composable function transforms for PyTorch. <https://pytorch.org/functorch>
- [pytorch/torcharrow](https://github.com/pytorch/torcharrow): A Pandas-inspired DataFrame library for SQL-like transformation with Pythonic and imperative-style API. Typical use case includes data preprocessing in ML models.
- [pytorch-labs/torchfix](https://github.com/pytorch-labs/torchfix): TorchFix - a linter for PyTorch-using code with autofix support
- [pytorch/kineto](https://github.com/pytorch/kineto): A CPU+GPU Profiling library that provides access to timeline traces and hardware performance counters.
- [dmlc/dlpack](https://github.com/dmlc/dlpack): common in-memory tensor structure <https://dmlc.github.io/dlpack/latest>
- [xtensor-stack/xtensor](https://github.com/xtensor-stack/xtensor): C++ tensors with broadcasting and lazy computing
- [rapidsai/cuml](https://github.com/rapidsai/cuml): cuML - RAPIDS Machine Learning Library
- [huggingface/safetensors](https://github.com/huggingface/safetensors): Simple, safe way to store and distribute tensors
  - [alvarobartt/safejax](https://github.com/alvarobartt/safejax): Serialize JAX, Flax, Haiku, or Objax model params with 🤗`safetensors` <https://alvarobartt.github.io/safejax/>
- [huggingface/evaluate](https://github.com/huggingface/evaluate): 🤗 Evaluate: A library for easily evaluating machine learning models and datasets. <https://huggingface.co/docs/evaluate>
- [google/pyglove](https://github.com/google/pyglove): Manipulating Python Programs
- [arogozhnikov/einops](https://github.com/arogozhnikov/einops): Deep learning operations reinvented (for pytorch, tensorflow, jax and others) <https://einops.rocks>
- [google/tensorstore](https://github.com/google/tensorstore): Library for reading and writing large multi-dimensional arrays. <https://google.github.io/tensorstore/>
- [google-deepmind/tree](https://github.com/google-deepmind/tree): tree is a library for working with nested data structures <https://tree.readthedocs.io>
- [google-research/dataclass_array](https://github.com/google-research/dataclass_array): Dataclasses manipulated as numpy arrays (with batching, reshape, slicing,...) <https://dataclass-array.readthedocs.io>
- [brentyi/jax_dataclasses](https://github.com/brentyi/jax_dataclasses): Pytrees + dataclasses ❤️
- [patrick-kidger/torchtyping](https://github.com/patrick-kidger/torchtyping): Type annotations and dynamic checking for a tensor's shape, dtype, names, etc.
- [google/jaxtyping](https://github.com/google/jaxtyping): Type annotations and runtime checking for shape and dtype of JAX arrays, and PyTrees.
- [mosaicml/streaming](https://github.com/mosaicml/streaming): A Data Streaming Library for Efficient Neural Network Training <https://streaming.docs.mosaicml.com>

## Utils

- [NVIDIA/nvidia-docker](https://github.com/NVIDIA/nvidia-docker): Build and run Docker containers leveraging NVIDIA GPUs
- [aws/deep-learning-containers](https://github.com/aws/deep-learning-containers): AWS Deep Learning Containers (DLCs) are a set of Docker images for training and serving models in TensorFlow, TensorFlow 2, PyTorch, and MXNet. <https://docs.aws.amazon.com/deep-learning-containers/latest/devguide/deep-learning-containers-images.html>
- [replicate/cog](https://github.com/replicate/cog): Containers for machine learning
- [alteryx/featuretools](https://github.com/alteryx/featuretools): An open source python library for automated feature engineering <https://www.featuretools.com>
- [XuehaiPan/nvitop](https://github.com/XuehaiPan/nvitop): An interactive NVIDIA-GPU process viewer and beyond, the one-stop solution for GPU process management. <https://nvitop.readthedocs.io/>
- [Syllo/nvtop](https://github.com/Syllo/nvtop): GPUs process monitoring for AMD, Intel and NVIDIA
- [wookayin/gpustat](https://github.com/wookayin/gpustat): 📊 A simple command-line utility for querying and monitoring GPU status
- [facebook/Ax](https://github.com/facebook/Ax): Adaptive Experimentation Platform <https://ax.dev>
- [google/fiddle](https://github.com/google/fiddle): Fiddle is a Python-first configuration library particularly well suited to ML applications. Fiddle enables deep configurability of parameters in a program, while allowing configuration to be expressed in readable and maintainable Python code.

## Misc

- [allenai/RL4LMs](https://github.com/allenai/RL4LMs): A modular RL library to fine-tune language models to human preferences <https://rl4lms.apps.allenai.org>

## Happy small projects (to learn)

- [minitorch/minitorch](https://github.com/minitorch/minitorch): The full minitorch student suite.
- [karpathy/micrograd](https://github.com/karpathy/micrograd): A tiny scalar-valued autograd engine and a neural net library on top of it with PyTorch-like API
- [pranftw/neograd](https://github.com/pranftw/neograd): A deep learning framework created from scratch with Python and NumPy <https://neograd.readthedocs.io>
- [mohammadpz/pytorch_forward_forward](https://github.com/mohammadpz/pytorch_forward_forward): Implementation of Hinton's forward-forward (FF) algorithm - an alternative to back-propagation
- [tinygrad/teenygrad](https://github.com/tinygrad/teenygrad): If tinygrad wasn't small enough for you...
- [lucidrains/x-transformers](https://github.com/lucidrains/x-transformers): A simple but complete full-attention transformer with a set of promising experimental features from various papers
- [lucidrains/ring-attention-pytorch](https://github.com/lucidrains/ring-attention-pytorch): Explorations into Ring Attention, from Liu et al. at Berkeley AI
- [lucidrains/vector-quantize-pytorch](https://github.com/lucidrains/vector-quantize-pytorch): Vector (and Scalar) Quantization, in Pytorch
- [sustcsonglin/flash-linear-attention](https://github.com/sustcsonglin/flash-linear-attention): Efficient implementations of state-of-the-art linear attention models in Pytorch and Triton
- [Vchitect/LaVie](https://github.com/Vchitect/LaVie): LaVie: High-Quality Video Generation with Cascaded Latent Diffusion Models
- [HMUNACHI/nanodl](https://github.com/HMUNACHI/nanodl): A Jax-based library for designing and training transformer models from scratch.
