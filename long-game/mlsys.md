# ML Systems

## Resources

### Tutorials

- [google-research/tuning_playbook](https://github.com/google-research/tuning_playbook): A playbook for systematically maximizing the performance of deep learning models.
- [microsoft/AI-System](https://github.com/microsoft/AI-System): System for AI Education Resource. <https://microsoft.github.io/AI-System>
- [ML system design: 200 case studies to learn from](https://www.evidentlyai.com/ml-system-design)
- [eugeneyan/applied-ml](https://github.com/eugeneyan/applied-ml): 📚 Papers & tech blogs by companies sharing their work on data science & machine learning in production.
- [mit-han-lab/parallel-computing-tutorial](https://github.com/mit-han-lab/parallel-computing-tutorial): This repository introduces several optimization techniques that can be applied to improve the parallelism of matrix multiplication.
- [stas00/ml-engineering](https://github.com/stas00/ml-engineering): Machine Learning Engineering Guides and Tools <https://stasosphere.com/machine-learning/>
- [srush/Autodiff-Puzzles](https://github.com/srush/Autodiff-Puzzles): This notebook contains a series of self-contained puzzles for learning about derivatives in tensor libraries.
- [srush/Tensor-Puzzles](https://github.com/srush/Tensor-Puzzles): Solve puzzles. Improve your pytorch.
- [srush/GPU-Puzzles](https://github.com/srush/GPU-Puzzles): Solve puzzles. Learn CUDA.
- [srush/Transformer-Puzzles](https://github.com/srush/Transformer-Puzzles): Puzzles for exploring transformers
- [Fullstack deep learning](https://fullstackdeeplearning.com/): News, community, and courses for people building AI-powered products.
- [hyperai/tvm-cn](https://github.com/hyperai/tvm-cn): TVM Documentation in Chinese Simplified / TVM 中文文档 <https://tvm.hyper.ai>
- [HazyResearch/aisys-building-blocks](https://github.com/HazyResearch/aisys-building-blocks): Building blocks for foundation models.
- [ML Code Challenges](https://www.deep-ml.com/)
- [TensorGym](https://tensorgym.com/exercises): Elevate Your AI Skills and Interview Confidence with unique exercises!
- [The Tensor Cookbook](https://tensorcookbook.com/): What are Tensor Diagrams? Machine learning involves a lot of tensor manipulation, and it's easy to lose track of the bigger picture when manipulating high-dimensional data using notation designed for vectors and matrices.
  - [The Matrix Cookbook](https://web.archive.org/web/20070126190021/http://matrixcookbook.com/)
- [Explaining RNNs without neural networks](https://explained.ai/rnn/index.html): This article explains how recurrent neural networks (RNN's) work without using the neural network metaphor. It uses a visually-focused data-transformation perspective to show how RNNs encode variable-length input vectors as fixed-length embeddings. Included are PyTorch implementation notebooks that use just linear algebra and the autograd feature.
  - Terence Parr implemented a series of step by step coding examples from basic to advanced
    - SGD (parameters updated after each record)
    - minibatch (parameters updated after a small batch of records)
    - vectorized minibatch (convert for-loop into matrix multiply)
    - vectorized minibatch running on a GPU (use PyTorch to compute on GPU)
- [vopani/jaxton](https://github.com/vopani/jaxton): 100 exercises to learn JAX

### Triton

- [MekkCyber/TritonAcademy](https://github.com/MekkCyber/TritonAcademy): A repository to unravel the language of GPUs, making their kernel conversations easy to understand
- [srush/Triton-Puzzles](https://github.com/srush/Triton-Puzzles): Puzzles for learning Triton
- [rdyro/Pallas-Puzzles](https://github.com/rdyro/Pallas-Puzzles): This is a direct fork of the Triton Puzzles, but adapted for the Pallas language for using a Triton-like kernel language (Pallas) in JAX.
- [rkinas/triton-resources](https://github.com/rkinas/triton-resources): A curated list of resources for learning and exploring Triton, OpenAI's programming language for writing efficient GPU code.
- [Jokeren/triton-samples](https://github.com/Jokeren/triton-samples)
- [Deep-Learning-Profiling-Tools/triton-viz](https://github.com/Deep-Learning-Profiling-Tools/triton-viz): Triton-Viz: A Visualization Toolkit for programming with Triton

### GPU / CUDA

- [Jokeren/Awesome-GPU](https://github.com/Jokeren/Awesome-GPU): Awesome resources for GPUs
- [cuda-mode/resource-stream](https://github.com/cuda-mode/resource-stream): CUDA related news and material links
- [MekkCyber/CutlassAcademy](https://github.com/MekkCyber/CutlassAcademy): A curated collection of resources, tutorials, and best practices for learning and mastering NVIDIA CUTLASS
- [LeetGPU](https://leetgpu.com/challenges): LeetGPU - Online CUDA Playground
- 🌟 [AI-Hypercomputer/gpu-recipes](https://github.com/AI-Hypercomputer/gpu-recipes): Recipes for reproducing training and serving benchmarks for large machine learning models using GPUs on Google Cloud.
- [GPU Glossary | Modal](https://modal.com/gpu-glossary)
- [ashvardanian/cpp-cuda-python-starter-kit](https://github.com/ashvardanian/cpp-cuda-python-starter-kit): Parallel Computing starter project to build GPU & CPU kernels in CUDA & C++ and call them from Python without a single line of CMake using PyBind11 <https://ashvardanian.com/tags/less-slow>
- 🌟 [The Ultra-Scale Playbook - a Hugging Face Space by nanotron](https://huggingface.co/spaces/nanotron/ultrascale-playbook): The ultimate guide to training LLM on large GPU Clusters
  - [huggingface/nanotron](https://github.com/huggingface/nanotron): Minimalistic large language model 3D-parallelism training
  - [huggingface/picotron](https://github.com/huggingface/picotron): Minimalistic 4D-parallelism distributed training framework for education purpose
- [rkinas/cuda-learning](https://github.com/rkinas/cuda-learning): This repository is a curated collection of resources, tutorials, and practical examples designed to guide you through the journey of mastering CUDA programming. Whether you're just starting or looking to optimize and scale your GPU-accelerated applications.
- [gpu-mode/lectures](https://github.com/gpu-mode/lectures): Material for gpu-mode lectures <https://www.youtube.com/@GPUMODE>
- [PaddleJitLab/CUDATutorial](https://github.com/PaddleJitLab/CUDATutorial): A self-learning tutorail for CUDA High Performance Programing.
  - in Chinese
- [gpu-mode/resource-stream](https://github.com/gpu-mode/resource-stream): GPU programming related news and material links <https://discord.gg/gpumode>
- [ENCCS/gpu-programming](https://github.com/ENCCS/gpu-programming): Meta-GPU lesson covering general aspects of GPU programming as well as specific frameworks <https://enccs.github.io/gpu-programming/>
- [leimao/CUTLASS-Examples](https://github.com/leimao/CUTLASS-Examples): CUTLASS and CuTe Examples
- [NVIDIA/accelerated-computing-hub](https://github.com/NVIDIA/accelerated-computing-hub): NVIDIA curated collection of educational resources related to general purpose GPU programming.
- [HanGuo97/cutedsl-utilities](https://github.com/HanGuo97/cutedsl-utilities): No description, website, or topics provided.
- [Cute-DSL – Ian’s Blog](https://ianbarber.blog/2025/07/04/cute-dsl/): In May Nvidia shipped CuTe-DSL, the Python library they teased at GTC earlier in the year that mirrors CUTLASS’s C++ tensor‑layout . Then, at the start of June, the ‑dev label disappeared (so presumably its production ready now). The pitch is simple: Write speed‑of‑light kernels from the comfort of Python. Of course, nothing about CUDA…
- [flashinfer-ai/cubloaty](https://github.com/flashinfer-ai/cubloaty): a size profiler for cuda binary
- [xlite-dev/LeetCUDA](https://github.com/xlite-dev/LeetCUDA): 📚LeetCUDA: Modern CUDA Learn Notes with PyTorch for Beginners🐑, 200+ CUDA Kernels, Tensor Cores, HGEMM, FA-2 MMA.🎉 <https://github.com/xlite-dev/LeetCUDA>
- 🌟 [modular/mojo-gpu-puzzles](https://github.com/modular/mojo-gpu-puzzles): Learn GPU Programming in Mojo🔥 by Solving Puzzles <https://puzzles.modular.com/>

### TPU

- [ayaka14732/tpu-starter](https://github.com/ayaka14732/tpu-starter): Everything you want to know about Google Cloud TPU
- [TG-TG-TG-TG-TG-TG/TPU-Tutorials](https://github.com/TG-TG-TG-TG-TG-TG/TPU-Tutorials): Some of my TPU tutorials that i will post here.
- [jax-ml/scaling-book](https://github.com/jax-ml/scaling-book): Home for "How To Scale Your Model", a short blog-style textbook about scaling LLMs on TPUs <https://jax-ml.github.io/scaling-book/>
- [TPU Deep Dive](https://henryhmko.github.io/posts/tpu/tpu.html): The main strongpoint for TPUs is in their scalability. This is achieved through a co-design of both the hardware side (e.g. energy efficiency and modularity) and the software side (e.g. XLA compiler).
- 🌟 [Tiny TPU](https://www.tinytpu.com/): An attempt to understand and build a TPU-by complete novices.

### Readings

- [Efficient GEMM in CUDA](https://github.com/NVIDIA/cutlass/blob/main/media/docs/efficient_gemm.md)
- [cuda-mode/awesomeMLSys](https://github.com/cuda-mode/awesomeMLSys): An ML Systems Onboarding list
- [A reading list for machine learning systems](https://jeongseob.github.io/readings_mlsys.html)
- [KnowingNothing/compiler-and-arch](https://github.com/KnowingNothing/compiler-and-arch): A list of tutorials, paper, talks, and open-source projects for emerging compiler and architecture
- [zhaochenyang20/Awesome-ML-SYS-Tutorial](https://github.com/zhaochenyang20/Awesome-ML-SYS-Tutorial): My learning notes/codes for ML SYS.
- 🌟 [Python isn't just glue, it's an implicit JIT ecosystem](https://state.smerity.com/smerity/state/01JC39KW1TBEAZTKJJF0BR5ZXD): The ecosystem wears in the desire paths, and when slow Python becomes a problem, the ecosystem doesn't optimize the Python, it paves new roads beneath
- 🌟 [Decorator JITs - Python as a DSL - Eli Bendersky's website](https://eli.thegreenplace.net/2025/decorator-jits-python-as-a-dsl/)
- 🌟 [A note on common mistakes in benchmarking LLM inference engines](https://docs.google.com/document/d/1fEaaIQoRQLbevRu3pj1_ReOklHkoeE7ELqZJ3pnW-K4/mobilebasic): A Note on Common Mistakes in Benchmarking LLM Inference Engines Proper benchmarking is essential for the development and comparison of various inference optimizations.

### Books

- [chenzomi12/DeepLearningSystem](https://github.com/chenzomi12/DeepLearningSystem): Deep Learning System core principles introduction.
- [openmlsys/openmlsys-zh](https://github.com/openmlsys/openmlsys-zh): 《Machine Learning Systems: Design and Implementation》- Chinese Version <https://openmlsys.github.io>
- [chiphuyen/machine-learning-systems-design](https://github.com/chiphuyen/machine-learning-systems-design): A booklet on machine learning systems design with exercises. NOT the repo for the book "Designing Machine Learning Systems" <https://huyenchip.com/machine-learning-systems-design/toc.html>
- [stas00/ml-engineering](https://github.com/stas00/ml-engineering): Machine Learning Engineering Open Book <https://stasosphere.com/machine-learning/>

## Frameworks

### General framework / Training

- [ray-project/ray](https://github.com/ray-project/ray): Ray is a unified framework for scaling AI and Python applications. Ray consists of a core distributed runtime and a toolkit of libraries (Ray AIR) for accelerating ML workloads. <https://ray.io>
- [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb): In-Database Machine Learning <http://mindsdb.com>
- 🌟 [deepspeedai/DeepSpeed](https://github.com/deepspeedai/DeepSpeed): DeepSpeed is a deep learning optimization library that makes distributed training and inference easy, efficient, and effective. <https://www.deepspeed.ai/>
- [keras-team/keras-core](https://github.com/keras-team/keras-core): A multi-backend implementation of the Keras API, with support for TensorFlow, JAX, and PyTorch.
- [online-ml/river](https://github.com/online-ml/river): 🌊 Online machine learning in Python <https://riverml.xyz>
- 🌟 [tinygrad/tinygrad](https://github.com/tinygrad/tinygrad): You like pytorch? You like micrograd? You love tinygrad! ❤️
  - [tinygrad/teenygrad](https://github.com/tinygrad/teenygrad): If tinygrad wasn't small enough for you...
- [intelligent-machine-learning/dlrover](https://github.com/intelligent-machine-learning/dlrover): DLRover: An Automatic Distributed Deep Learning System
- [pycaret/pycaret](https://github.com/pycaret/pycaret): An open-source, low-code machine learning library in Python <https://www.pycaret.org>
- 🌟 [intel/scikit-learn-intelex](https://github.com/intel/scikit-learn-intelex): Intel(R) Extension for Scikit-learn is a seamless way to speed up your Scikit-learn application <https://intel.github.io/scikit-learn-intelex/>
- [mlpack/mlpack](https://github.com/mlpack/mlpack): mlpack: a fast, header-only C++ machine learning library <https://www.mlpack.org/>
- [adap/flower](https://github.com/adap/flower): Flower: A Friendly Federated Learning Framework <https://flower.dev>
- [elixir-nx/nx](https://github.com/elixir-nx/nx): Multi-dimensional arrays (tensors) and numerical definitions for Elixir
- [huggingface/ratchet](https://github.com/huggingface/ratchet): A cross-platform browser ML framework. <https://ratchet.sh>
- 🌟 [mosaicml/composer](https://github.com/mosaicml/composer): Supercharge Your Model Training <http://docs.mosaicml.com>
  - [mosaicml/llm-foundry](https://github.com/mosaicml/llm-foundry): LLM training code for MosaicML foundation models <https://www.mosaicml.com/blog/mpt-7b>
- [pytorch/torchtitan](https://github.com/pytorch/torchtitan): A native PyTorch Library for large model training
- [facebookresearch/fairscale](https://github.com/facebookresearch/fairscale): PyTorch extensions for high performance and large scale training.
- [NVIDIA-Merlin/Merlin](https://github.com/NVIDIA-Merlin/Merlin): NVIDIA Merlin is an open source library providing end-to-end GPU-accelerated recommender systems, from feature engineering and preprocessing to training deep learning models and running inference in production.
- [crabml/crabml](https://github.com/crabml/crabml): crabml is an ongoing experiment that aims to reimplement GGML using Rust.
- [databricks/megablocks](https://github.com/databricks/megablocks): MegaBlocks is a light-weight library for mixture-of-experts (MoE) training.
- [pytorch/tnt](https://github.com/pytorch/tnt): A lightweight library for PyTorch training tools and utilities <https://pytorch.org/tnt/>
- [oumi-ai/oumi](https://github.com/oumi-ai/oumi): Everything you need to build state-of-the-art foundation models, end-to-end. <https://oumi.ai>
- [tensorflow/tensor2tensor](https://github.com/tensorflow/tensor2tensor): Library of deep learning models and datasets designed to make deep learning more accessible and accelerate ML research.
- [d0rc/egg.c](https://github.com/d0rc/egg.c): EGGROLL in C, integer-only training of a language model directly on the CPU
  - [ESHyperscale/nano-egg](https://github.com/ESHyperscale/nano-egg): Evolution Pretraining Fully in Int Formats
- 🌟 [thinking-machines-lab/tinker](https://github.com/thinking-machines-lab/tinker): Training API and CLI

### Optimization

- [optuna/optuna](https://github.com/optuna/optuna): A hyperparameter optimization framework <https://optuna.org>
- [Epistimio/orion](https://github.com/Epistimio/orion): Asynchronous Distributed Hyperparameter Optimization. <https://orion.readthedocs.io>
- [google/vizier](https://github.com/google/vizier): Python-based research interface for blackbox and hyperparameter optimization, based on Google's internal Vizier Service. <https://oss-vizier.readthedocs.io>
- [leopard-ai/betty](https://github.com/leopard-ai/betty): Betty: an automatic differentiation library for generalized meta-learning and multilevel optimization <https://leopard-ai.github.io/betty>
- [facebookresearch/theseus](https://github.com/facebookresearch/theseus): A library for differentiable nonlinear optimization <https://sites.google.com/view/theseus-ai>
- [lucidrains/lion-pytorch](https://github.com/lucidrains/lion-pytorch): 🦁 Lion, new optimizer discovered by Google Brain using genetic algorithms that is purportedly better than Adam(w), in Pytorch
- 🌟 [metaopt/torchopt](https://github.com/metaopt/torchopt): TorchOpt is an efficient library for differentiable optimization built upon PyTorch. <https://torchopt.readthedocs.io>
  - [Introducing TorchOpt: A High-Performance Differentiable Optimization Library for PyTorch](https://medium.com/pytorch/introducing-torchopt-a-high-performance-differentiable-optimization-library-for-pytorch-37c4c0ef6ae1)
- [pytorch/botorch](https://github.com/pytorch/botorch): Bayesian optimization in PyTorch <https://botorch.org/>
- [facebookresearch/nevergrad](https://github.com/facebookresearch/nevergrad): A Python toolbox for performing gradient-free optimization <https://facebookresearch.github.io/nevergrad/>
- [lessw2020/Best-Deep-Learning-Optimizers](https://github.com/lessw2020/Best-Deep-Learning-Optimizers): Collection of the latest, greatest, deep learning optimizers (for Pytorch) - CNN, NLP suitable
- [facebookresearch/schedule_free](https://github.com/facebookresearch/schedule_free): Schedule-Free Optimization in PyTorch

General problems

- [cvxpy/cvxpy](https://github.com/cvxpy/cvxpy): A Python-embedded modeling language for convex optimization problems. <https://www.cvxpy.org>
  - [cvxpy/cvxpylayers](https://github.com/cvxpy/cvxpylayers): Differentiable convex optimization layers
- [ceres-solver/ceres-solver](https://github.com/ceres-solver/ceres-solver): A large scale non-linear optimization library <http://ceres-solver.org>
- [google/or-tools](https://github.com/google/or-tools): Google's Operations Research tools <https://developers.google.com/optimization>
- [coin-or/pulp](https://github.com/coin-or/pulp): A python Linear Programming API <http://coin-or.github.io/pulp/>
- [mlpack/ensmallen](https://github.com/mlpack/ensmallen): A header-only C++ library for numerical optimization -- <http://ensmallen.org>
- [stevengj/nlopt](https://github.com/stevengj/nlopt): library for nonlinear optimization, wrapping many algorithms for global and local, constrained or unconstrained, optimization

### Production-ready network implementation

- [pytorch-labs/segment-anything-fast](https://github.com/pytorch-labs/segment-anything-fast): A batched offline inference oriented version of segment-anything
  - [Accelerating Generative AI with PyTorch: Segment Anything, Fast](https://pytorch.org/blog/accelerating-generative-ai/)

### Inference engine / large-scale deployment

- [flashlight/flashlight](https://github.com/flashlight/flashlight): A C++ standalone library for machine learning <https://fl.readthedocs.io/en/latest>
- [microsoft/torchscale](https://github.com/microsoft/torchscale): Transformers at any scale <https://aka.ms/nlpagi>
- [microsoft/DeepSpeed-MII](https://github.com/microsoft/DeepSpeed-MII): MII makes low-latency and high-throughput inference possible, powered by DeepSpeed.
- [Lightning-AI/lightning](https://github.com/Lightning-AI/lightning): Deep learning framework to train, deploy, and ship AI products Lightning fast. <https://lightning.ai>
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
- 🌟 [ml-explore/mlx](https://github.com/ml-explore/mlx): MLX: An array framework for Apple silicon
- [vllm-project/vllm](https://github.com/vllm-project/vllm): A high-throughput and memory-efficient inference and serving engine for LLMs <https://vllm.readthedocs.io>
- [sgl-project/sglang](https://github.com/sgl-project/sglang): SGLang is a structured generation language designed for large language models (LLMs). It makes your interaction with LLMs faster and more controllable.
  - [Fast and Expressive LLM Inference with RadixAttention and SGLang](https://lmsys.org/blog/2024-01-17-sglang/)
- [neuralmagic/deepsparse](https://github.com/neuralmagic/deepsparse): Sparsity-aware deep learning inference runtime for CPUs <https://neuralmagic.com/deepsparse/>
  - [ml-explore/mlx-examples](https://github.com/ml-explore/mlx-examples): Examples in the MLX framework
  - [MLX Community Projects #654](https://github.com/ml-explore/mlx/discussions/654)
  - [mlx-graphs/mlx-graphs](https://github.com/mlx-graphs/mlx-graphs): Graph Neural Network library made for Apple Silicon <https://mlx-graphs.github.io/mlx-graphs/>
  - [tedwards2412/samplex](https://github.com/tedwards2412/samplex): Package of useful sampling algorithms written in MLX.
- [zml/zml](https://github.com/zml/zml): Any model. Any hardware. Zero compromise. Built with @ziglang / @openxla / MLIR / @bazelbuild <https://docs.zml.ai>
  - Interesting ideas
- [ai-dynamo/dynamo](https://github.com/ai-dynamo/dynamo): A Datacenter Scale Distributed Inference Serving Framework
- [facebookresearch/fastgen](https://github.com/facebookresearch/fastgen): Simple high-throughput inference library
- [trymirai/uzu](https://github.com/trymirai/uzu): A high-performance inference engine for AI models <https://trymirai.com>

### Distribution kits

- [pytorch/PiPPy](https://github.com/pytorch/PiPPy): Pipeline Parallelism for PyTorch
- [meta-pytorch/monarch](https://github.com/meta-pytorch/monarch): PyTorch Single Controller <https://meta-pytorch.org/monarch>

### Workflow pipeline / MLOps

- [aporia-ai/mlops.toys](https://github.com/aporia-ai/mlops.toys): 🎲 A curated list of MLOps projects, tools and resources <https://mlops.toys>
- [GokuMohandas/mlops-course](https://github.com/GokuMohandas/mlops-course): A project-based course on the foundations of MLOps to responsibly develop, deploy and maintain ML. <https://madewithml.com>
- [DataTalksClub/mlops-zoomcamp](https://github.com/DataTalksClub/mlops-zoomcamp): Free MLOps course from DataTalks.Club
- [kubeflow/kubeflow](https://github.com/kubeflow/kubeflow): Machine Learning Toolkit for Kubernetes
- [mlflow/mlflow](https://github.com/mlflow/mlflow): Open source platform for the machine learning lifecycle
- [Netflix/metaflow](https://github.com/Netflix/metaflow): 🚀 Build and manage real-life data science projects with ease! <https://metaflow.org>
- [bentoml/BentoML](https://github.com/bentoml/BentoML): Unified Model Serving Framework 🍱 <https://bentoml.com>
- [bentoml/Yatai](https://github.com/bentoml/Yatai): Model Deployment at Scale on Kubernetes 🦄️ <https://bentoml.com>
- [SeldonIO/seldon-core](https://github.com/SeldonIO/seldon-core): An MLOps framework to package, deploy, monitor and manage thousands of production machine learning models
- 🌟 [skypilot-org/skypilot](https://github.com/skypilot-org/skypilot): SkyPilot is a framework for easily running machine learning workloads on any cloud through a unified interface. <https://skypilot.readthedocs.io>
- [sematic-ai/sematic](https://github.com/sematic-ai/sematic): An open-source ML pipeline development platform
- [uptrain-ai/uptrain](https://github.com/uptrain-ai/uptrain): Your open-source ML monitoring and refinement toolkit. <https://uptrain.ai/>
- [microsoft/SynapseML](https://github.com/microsoft/SynapseML): Simple and Distributed Machine Learning <http://aka.ms/spark>
- 🌟 [Arize-ai/phoenix](https://github.com/Arize-ai/phoenix): ML Observability in a Notebook - Uncover Insights, Surface Problems, Monitor, and Fine Tune your Generative LLM, CV and Tabular Models <https://docs.arize.com/phoenix>
- [eth-easl/orion](https://github.com/eth-easl/orion): An interference-aware scheduler for fine-grained GPU sharing
- [iterative/dvc](https://github.com/iterative/dvc): 🦉 ML Experiments Management with Git <https://dvc.org>
- 🌟 [feathr-ai/feathr](https://github.com/feathr-ai/feathr): Feathr – A scalable, unified data and AI engineering platform for enterprise <https://join.slack.com/t/feathrai/shared_invite/zt-1ffva5u6v-voq0Us7bbKAw873cEzHOSg>
  - in Scala? Interesting
- [featureform/featureform](https://github.com/featureform/featureform): The Virtual Feature Store. Turn your existing data infrastructure into a feature store. <https://www.featureform.com>
- [HumanSignal/label-studio](https://github.com/HumanSignal/label-studio): Label Studio is a multi-type data labeling and annotation tool with standardized output format <https://labelstud.io>
- [comet-ml/kangas](https://github.com/comet-ml/kangas): 🦘 Explore multimedia datasets at scale <https://github.com/comet-ml/kangas/wiki>
- [aimhubio/aim](https://github.com/aimhubio/aim): Aim 💫 — An easy-to-use & supercharged open-source experiment tracker. <https://aimstack.io>
- [facebook/Ax](https://github.com/facebook/Ax): Adaptive Experimentation Platform <https://ax.dev>
- [anyscale/Made-With-ML](https://github.com/anyscale/Made-With-ML):
- [mlop-ai/mlop](https://github.com/mlop-ai/mlop): Next Generation Experimental Tracking for Machine Learning Operations <https://mlop.ai>

### Computing resource scheduler

- [leptonai/gpud](https://github.com/leptonai/gpud): GPUd is designed to ensure GPU efficiency and reliability by actively monitoring GPUs and effectively managing AI/ML workloads.
- [run-ai/genv](https://github.com/run-ai/genv): GPU environment and cluster management with LLM support <https://www.genv.dev>
- [ai-dynamo/grove](https://github.com/ai-dynamo/grove): Kubernetes enhancements for Network Topology Aware Gang Scheduling & Autoscaling
  - previous name: NVIDIA/grove
- [NVIDIA/KAI-Scheduler](https://github.com/NVIDIA/KAI-Scheduler): KAI Scheduler is an open source Kubernetes Native scheduler for AI workloads at large scale
- [NVIDIA/gpu-operator](https://github.com/NVIDIA/gpu-operator): NVIDIA GPU Operator creates, configures, and manages GPUs in Kubernetes <https://docs.nvidia.com/datacenter/cloud-native/gpu-operator/latest/index.html>

## Compiler / Kernel / Low level libs

- [merrymercy/awesome-tensor-compilers](https://github.com/merrymercy/awesome-tensor-compilers): A list of awesome compiler projects and papers for tensor computation and deep learning.
- 🌟 [apache/tvm](https://github.com/apache/tvm): Open deep learning compiler stack for cpu, gpu and specialized accelerators <https://tvm.apache.org>
  - [inducer/loopy](https://github.com/inducer/loopy): A code generator for array-based code on CPUs and GPUs <http://mathema.tician.de/software/loopy>
  - [wzh99/relay-mlir](https://github.com/wzh99/relay-mlir): An MLIR-based toy DL compiler for TVM Relay.
  - [apache/tvm-ffi](https://github.com/apache/tvm-ffi): TVM FFI <https://tvm.apache.org/ffi>
- 🌟 [openai/triton](https://github.com/openai/triton): Development repository for the Triton language and compiler
- 🌟 [llvm/torch-mlir](https://github.com/llvm/torch-mlir): The Torch-MLIR project aims to provide first class support from the PyTorch ecosystem to the MLIR ecosystem.
- 🌟 [openxla/xla](https://github.com/openxla/xla): A machine learning compiler for GPUs, CPUs, and ML accelerators
  - News: [OpenXLA is available now to accelerate and simplify machine learning](https://opensource.googleblog.com/2023/03/openxla-is-ready-to-accelerate-and-simplify-ml-development.html)
  - 🌟 [openxla/stablehlo](https://github.com/openxla/stablehlo): Backward compatible ML compute opset inspired by HLO/MHLO
  - [LaurentMazare/xla-rs](https://github.com/LaurentMazare/xla-rs): Experimentation using the xla compiler from rust
- [tensor-compiler/taco](https://github.com/tensor-compiler/taco): The Tensor Algebra Compiler (taco) computes sparse tensor expressions on CPUs and GPUs <http://tensor-compiler.org>
- [pytorch/glow](https://github.com/pytorch/glow): Compiler for Neural Network hardware accelerators
- [nod-ai/SHARK-Turbine](https://github.com/nod-ai/SHARK-Turbine): Unified compiler/runtime for interfacing with PyTorch Dynamo.
- [modularml/mojo](https://github.com/modularml/mojo): The Mojo Programming Language <https://docs.modular.com/mojo>
- [NVIDIA/tilus](https://github.com/NVIDIA/tilus): Tilus is a tile-level kernel programming language, implemented in Python. <https://nvidia.github.io/tilus/>
- [SzymonOzog/Penny](https://github.com/SzymonOzog/Penny): Hand-Rolled GPU communications library
- 🌟 [NVIDIA/cutile-python](https://github.com/NVIDIA/cutile-python): cuTile is a programming model for writing parallel kernels for NVIDIA GPUs
- [tile-ai/tilelang](https://github.com/tile-ai/tilelang): Domain-specific language designed to streamline the development of high-performance GPU/CPU/Accelerators kernels <https://tilelang.com/>
- [tile-ai/tilescale](https://github.com/tile-ai/tilescale): Tile-based language built for AI computation across all scales <https://tilelang.com/>

### Operator and Kernel

- [mirage-project/mirage](https://github.com/mirage-project/mirage): Mirage: Automatically Generating Fast GPU Kernels without Programming in Triton/CUDA <https://mirage-project.readthedocs.io/>
- [getkeops/keops](https://github.com/getkeops/keops): KErnel OPerationS, on CPUs and GPUs, with autodiff and without memory overflows <https://www.kernel-operations.io>
- [HazyResearch/ThunderKittens](https://github.com/HazyResearch/ThunderKittens): Tile primitives for speedy kernels
  - 🌟 [GPUs Go Brrr](https://hazyresearch.stanford.edu/blog/2024-05-12-tk)
- [pytorch-labs/helion](https://github.com/pytorch-labs/helion): A Python-embedded DSL that makes it easy to write fast, scalable ML kernels with minimal boilerplate.
- [ppl-ai/pplx-kernels](https://github.com/ppl-ai/pplx-kernels): Perplexity GPU Kernels
- [ByteDance-Seed/Triton-distributed](https://github.com/ByteDance-Seed/Triton-distributed): Distributed Triton for Parallel Systems
- [pytorch-labs/tritonbench](https://github.com/pytorch-labs/tritonbench): Tritonbench is a collection of PyTorch custom operators with example inputs to measure their performance.
- [NVIDIA/cuEquivariance](https://github.com/NVIDIA/cuEquivariance): cuEquivariance is a math library that is a collective of low-level primitives and tensor ops to accelerate widely-used models, like DiffDock, MACE, Allegro and NEQUIP, based on equivariant neural networks.
- [huggingface/kernels](https://github.com/huggingface/kernels): Load compute kernels from the Hub
  - I should say Hugging Face is extremely smart to build things like this (unified interfaces and make a hub).
  - The only problem is PyTorch is the only one supported currently (June5 2025).
- [huggingface/kernel-builder](https://github.com/huggingface/kernel-builder): 👷 Build compute kernels
  - [Writing Hub kernels with kernel-builder](https://github.com/huggingface/kernel-builder/blob/main/docs/writing-kernels.md)
- [mirage-project/mirage](https://github.com/mirage-project/mirage): Mirage: Automatically Generating Fast GPU Kernels without Programming in Triton/CUDA <https://mirage-project.readthedocs.io/>
- [Relaxed-System-Lab/Flash-Sparse-Attention](https://github.com/Relaxed-System-Lab/Flash-Sparse-Attention): 🚀🚀 Efficient implementations of Native Sparse Attention <https://github.com/Relaxed-System-Lab/Flash-Sparse-Attention>
- [pytorch/helion](https://github.com/pytorch/helion): A Python-embedded DSL that makes it easy to write fast, scalable ML kernels with minimal boilerplate.

### XLA / MLIR

- [endorlabs/MIRAI](https://github.com/endorlabs/MIRAI): MIRAI is an abstract interpreter for the Rust compiler's mid-level intermediate representation (MIR). It is intended to become a widely used static analysis tool for Rust.
- [raviqqe/melior](https://github.com/raviqqe/melior): The rustic MLIR bindings in Rust <https://raviqqe.github.io/melior/melior/>
- [google/mlir-hs](https://github.com/google/mlir-hs): Haskell bindings for MLIR
- [spcl/pymlir](https://github.com/spcl/pymlir): Python interface for MLIR - the Multi-Level Intermediate Representation
- [AliveToolkit/alive2](https://github.com/AliveToolkit/alive2): Automatic verification of LLVM optimizations
- [iree-org/iree](https://github.com/iree-org/iree): A retargetable MLIR-based machine learning compiler and runtime toolkit. <http://iree.dev/>
- [llvm/eudsl](https://github.com/llvm/eudsl): Embedded Universal DSL: a good DSL for us, by us
- [j2kun/mlir-tutorial](https://github.com/j2kun/mlir-tutorial): MLIR For Beginners tutorial
- [KEKE046/mlir-tutorial](https://github.com/KEKE046/mlir-tutorial): Hands-On Practical MLIR Tutorial
- [ezyang/xla-redist-ref](https://github.com/ezyang/xla-redist-ref): Extract redistribution plans from XLA

### Tensor inference

- 🌟 [NVIDIA/cutlass](https://github.com/NVIDIA/cutlass): CUDA Templates for Linear Algebra Subroutines
- [NVIDIA/cudnn-frontend](https://github.com/NVIDIA/cudnn-frontend): cudnn_frontend provides a c++ wrapper for the cudnn backend API and samples on how to use it
- [NVIDIA/TensorRT](https://github.com/NVIDIA/TensorRT): NVIDIA® TensorRT™, an SDK for high-performance deep learning inference, includes a deep learning inference optimizer and runtime that delivers low latency and high throughput for inference applications. <https://developer.nvidia.com/tensorrt>
- [NVIDIA/accelerated-computing-hub](https://github.com/NVIDIA/accelerated-computing-hub): NVIDIA curated collection of educational resources related to general purpose GPU programming.
- [NVIDIA/cuda-python](https://github.com/NVIDIA/cuda-python): CUDA Python: Performance meets Productivity <https://nvidia.github.io/cuda-python/>
- [NVIDIA/nvmath-python](https://github.com/NVIDIA/nvmath-python): NVIDIA Math Libraries for the Python Ecosystem <https://docs.nvidia.com/cuda/nvmath-python/>
- [google/XNNPACK](https://github.com/google/XNNPACK): High-efficiency floating-point neural network inference operators for mobile, server, and Web
- [Azure/MS-AMP](https://github.com/Azure/MS-AMP): Microsoft Automatic Mixed Precision Library <https://azure.github.io/MS-AMP/>
- [ai-dynamo/nixl](https://github.com/ai-dynamo/nixl): NVIDIA Inference Xfer Library (NIXL)
- [cubed-dev/cubed](https://github.com/cubed-dev/cubed): Scalable array processing with bounded memory <https://cubed-dev.github.io/cubed/>
- [NVIDIA/NVSHMEM](https://github.com/NVIDIA/NVSHMEM): NVIDIA NVSHMEM is a parallel programming interface for NVIDIA GPUs based on OpenSHMEM. NVSHMEM can significantly reduce multi-process communication and coordination overheads by allowing programmers to perform one-sided communication from within CUDA kernels and on CUDA streams.

## Specific Topics

## FAIR specialist

- [facebookresearch/xformers](https://github.com/facebookresearch/xformers): Hackable and optimized Transformers building blocks, supporting a composable construction. <https://facebookresearch.github.io/xformers>
- [facebookresearch/fairseq](https://github.com/facebookresearch/fairseq): Facebook AI Research Sequence-to-Sequence Toolkit written in Python.
- [facebookresearch/metaseq](https://github.com/facebookresearch/metaseq): Repo for external large-scale work
- [facebookresearch/segment-anything](https://github.com/facebookresearch/segment-anything): The repository provides code for running inference with the SegmentAnything Model (SAM), links for downloading the trained model checkpoints, and example notebooks that show how to use the model.
- [facebookresearch/DiT](https://github.com/facebookresearch/DiT): Official PyTorch Implementation of "Scalable Diffusion Models with Transformers"
- [facebookresearch/lingua](https://github.com/facebookresearch/lingua): Meta Lingua: a lean, efficient, and easy-to-hack codebase to research LLMs.
- [facebookresearch/flow_matching](https://github.com/facebookresearch/flow_matching): A PyTorch library for implementing flow matching algorithms, featuring continuous and discrete flow matching implementations. It includes practical examples for both text and image modalities. <http://facebookresearch.github.io/flow_matching>
- [facebookresearch/chai](https://github.com/facebookresearch/chai): CHAI is a library for dynamic pruning of attention heads for efficient LLM inference.
- [facebookresearch/Lyapunov](https://github.com/facebookresearch/Lyapunov): PyTorch original implementation of "Lyapunov functions a long-standing open problem in mathematics, with symbolic transformers" (NeurIPS 2024).

### Reinforcement Learning

- [thu-ml/tianshou](https://github.com/thu-ml/tianshou): An elegant PyTorch deep reinforcement learning library. <https://tianshou.readthedocs.io>
- 🌟 [PufferAI/PufferLib](https://github.com/PufferAI/PufferLib): Simplifying reinforcement learning for complex game environments <https://puffer.ai/>
- [facebookresearch/Pearl](https://github.com/facebookresearch/Pearl): A Production-ready Reinforcement Learning AI Agent Library brought by the Applied Reinforcement Learning team at Meta.
- [CarperAI/trlx](https://github.com/CarperAI/trlx): A repo for distributed training of language models with Reinforcement Learning via Human Feedback (RLHF)
- [huggingface/trl](https://github.com/huggingface/trl): Train transformer language models with reinforcement learning. <http://hf.co/docs/trl>
- [allenai/RL4LMs](https://github.com/allenai/RL4LMs): A modular RL library to fine-tune language models to human preferences <https://rl4lms.apps.allenai.org>
- [THUDM/slime](https://github.com/THUDM/slime): slime is a LLM post-training framework for RL Scaling. <https://thudm.github.io/slime>
- [PrimeIntellect-ai/prime-rl](https://github.com/PrimeIntellect-ai/prime-rl): Decentralized RL Training at Scale

JAX Special

- [keraJLi/rejax](https://github.com/keraJLi/rejax): Hardware-Accelerated Reinforcement Learning Algorithms in pure Jax!
- [luchris429/purejaxrl](https://github.com/luchris429/purejaxrl): Really Fast End-to-End Jax RL Implementations
  - [Achieving Over 4000x Speedups and Meta-Evolving Discoveries with PureJaxRL](https://chrislu.page/blog/meta-disco/)
  - [PureJaxRL Resources](https://github.com/luchris429/purejaxrl/blob/main/RESOURCES.md)
- [RobertTLange/gymnax](https://github.com/RobertTLange/gymnax): RL Environments in JAX 🌍
  - [RobertTLange/gymnax-blines](https://github.com/RobertTLange/gymnax-blines): Baselines for gymnax 🤖
- [Replicable-MARL/MARLlib](https://github.com/Replicable-MARL/MARLlib): One repository is all that is necessary for Multi-agent Reinforcement Learning (MARL) <https://marllib.readthedocs.io>
- [kscalelabs/ksim](https://github.com/kscalelabs/ksim): RL training library for humanoid locomotion and manipulation. Built on top of MuJoCo and JAX. <https://docs.kscale.dev/docs/ksim>

### Language Models / Attention

- [Can You Run This LLM? VRAM Calculator (Nvidia GPU and Apple Silicon)](https://apxml.com/tools/vram-calculator): Calculate the VRAM required to run any large language model.
- 🌟 [pytorch-labs/gpt-fast](https://github.com/pytorch-labs/gpt-fast): Simple and efficient pytorch-native transformer text generation in <1000 LOC of python.
  - [Accelerating Generative AI with PyTorch II: GPT, Fast](https://pytorch.org/blog/accelerating-generative-ai-2/)
  - [Horace He (@cHHillee)'s threads about gpt-fast](https://twitter.com/cHHillee/status/1730293330213531844)
- [shawntan/scattermoe](https://github.com/shawntan/scattermoe): Triton-based implementation of Sparse Mixture of Experts.
- [THUDM/SwissArmyTransformer](https://github.com/THUDM/SwissArmyTransformer): SwissArmyTransformer is a flexible and powerful library to develop your own Transformer variants. <https://THUDM.github.io/SwissArmyTransformer>
- [NVIDIA/FasterTransformer](https://github.com/NVIDIA/FasterTransformer): Transformer related optimization, including BERT, GPT <https://desktop.github.com>
- 🌟 [flashinfer-ai/flashinfer](https://github.com/flashinfer-ai/flashinfer): FlashInfer: Kernel Library for LLM Serving <https://flashinfer.ai>
  - Comprehensive Attention Kernels
  - Optimized Shared-Prefix Batch Decoding
  - Accelerate Attention for Compressed/Quantized KV-Cache
  - no JAX support?
- 🌟 [Dao-AILab/flash-attention](https://github.com/Dao-AILab/flash-attention): Fast and memory-efficient exact attention
- [explosion/curated-transformers](https://github.com/explosion/curated-transformers): 🤖 A PyTorch library of curated Transformer models and their composable components
- [microsoft/vattention](https://github.com/microsoft/vattention): Dynamic Memory Management for Serving LLMs without PagedAttention
- [pytorch-labs/attention-gym](https://github.com/pytorch-labs/attention-gym): Helpful tools and examples for working with flex-attention
  - [FlexAttention: The Flexibility of PyTorch with the Performance of FlashAttention](https://pytorch.org/blog/flexattention/)
- [alpa-projects/alpa](https://github.com/alpa-projects/alpa): Training and serving large-scale neural networks <https://alpa.ai/>
- [FMInference/FlexGen](https://github.com/FMInference/FlexGen): Running large language models on a single GPU for throughput-oriented scenarios.
- 📝 [ModelTC/lightllm](https://github.com/ModelTC/lightllm): LightLLM is a Python-based LLM (Large Language Model) inference and serving framework, notable for its lightweight design, easy scalability, and high-speed performance. <https://desktop.github.com>
- [huggingface/text-generation-inference](https://github.com/huggingface/text-generation-inference): Large Language Model Text Generation Inference <https://huggingface.github.io/text-generation-inference/>
- 🌟 [pytorch/executorch](https://github.com/pytorch/executorch): End-to-end solution for enabling on-device AI across mobile and edge devices for PyTorch models <https://pytorch.org/edge>
- [intel/intel-extension-for-transformers](https://github.com/intel/intel-extension-for-transformers): ⚡ Build your chatbot within minutes on your favorite device; offer SOTA compression techniques for LLMs; run LLMs efficiently on Intel Platforms⚡
- [lm-sys/FastChat](https://github.com/lm-sys/FastChat): An open platform for training, serving, and evaluating large language models. Release repo for Vicuna and Chatbot Arena.
- [alpa-projects/alpa](https://github.com/alpa-projects/alpa): Training and serving large-scale neural networks with auto parallelization. <https://alpa.ai>
- [rustformers/llm](https://github.com/rustformers/llm): Run inference for Large Language Models on CPU, with Rust 🦀🚀🦙
- [mlc-ai/web-llm](https://github.com/mlc-ai/web-llm): Bringing large-language models and chat to web browsers. Everything runs inside the browser with no server support. <https://mlc.ai/web-llm>
- [bentoml/OpenLLM](https://github.com/bentoml/OpenLLM): An open platform for operating large language models(LLMs) in production. Fine-tune, serve, deploy, and monitor any LLMs with ease.
- [predibase/lorax](https://github.com/predibase/lorax): Multi-LoRA inference server that scales to 1000s of fine-tuned LLMs <https://predibase.github.io/lorax/>,
- [guillaumekln/faster-whisper](https://github.com/guillaumekln/faster-whisper): Faster Whisper transcription with CTranslate2

JAX Special

- [kingoflolz/mesh-transformer-jax](https://github.com/kingoflolz/mesh-transformer-jax): Model parallel transformers in JAX and Haiku
- [sanchit-gandhi/whisper-jax](https://github.com/sanchit-gandhi/whisper-jax): This repository contains optimised JAX code for OpenAI's Whisper Model, largely built on the 🤗 Hugging Face Transformers Whisper implementation. Compared to OpenAI's PyTorch code, Whisper JAX runs over 70x faster, making it the fastest Whisper implementation available.
- [salesforce/jaxformer](https://github.com/salesforce/jaxformer): Minimal library to train LLMs on TPU in JAX with pjit().
- [NVIDIA/jaxpp](https://github.com/NVIDIA/jaxpp): JaxPP is a library for JAX that enables flexible MPMD pipeline parallelism for large-scale LLM training
- [NVIDIA/maxtext-jaxpp](https://github.com/NVIDIA/maxtext-jaxpp): Showcase JaxPP with MaxText
- [google/tunix](https://github.com/google/tunix): A JAX-native LLM Post-Training Library

## Jax ecology

- [n2cholas/awesome-jax](https://github.com/n2cholas/awesome-jax): JAX - A curated list of resources https://github.com/google/jax
- [stanford-crfm/levanter](https://github.com/stanford-crfm/levanter): Legibile, Scalable, Reproducible Foundation Models with Named Tensors and Jax
- [probml/dynamax](https://github.com/probml/dynamax): State Space Models library in JAX <https://probml.github.io/dynamax>
- [probml/sts-jax](https://github.com/probml/sts-jax): Structural Time Series in JAX
- [ASEM000/kernex](https://github.com/ASEM000/kernex): Stencil computations in JAX
- [ott-jax/ott](https://github.com/ott-jax/ott): Optimal Transport tools implemented with the JAX framework, to get auto-diff, parallel and jit-able computations. <https://ott-jax.readthedocs.io>
- [JiaYaobo/fenbux](https://github.com/JiaYaobo/fenbux): A Simple Statistical Distribution Library in JAX <https://jiayaobo.github.io/fenbux/>
- [hayden-donnelly/jax-to-cpp](https://github.com/hayden-donnelly/jax-to-cpp): Generate HLO with JAX then execute in C++.
- [young-geng/scalax](https://github.com/young-geng/scalax): A simple library for scaling up JAX programs
- [NIFTy-PPL/JAXbind](https://github.com/NIFTy-PPL/JAXbind): Bind any function written in another language to JAX with support for JVP/VJP/batching/jit compilation
- [brentyi/jaxfg](https://github.com/brentyi/jaxfg): Factor graphs and nonlinear least squares for JAX
- [pasqal-io/horqrux](https://github.com/pasqal-io/horqrux): Jax-based quantum state vector simulator. <https://pasqal-io.github.io/horqrux/latest/>
- [mancusolab/traceax](https://github.com/mancusolab/traceax): Stochastic trace estimation using JAX <https://mancusolab.github.io/traceax/>
- [MatX-inc/seqax](https://github.com/MatX-inc/seqax): seqax = sequence modeling + JAX
- [yklcs/jaxsplat](https://github.com/yklcs/jaxsplat): 3D Gaussian Splatting in JAX <https://jaxsplat.readthedocs.io>
- [epignatelli/navix](https://github.com/epignatelli/navix): Accelerated minigrid environments with JAX
- [erfanzar/EasyDeL](https://github.com/erfanzar/EasyDeL): Accelerate, Optimize performance with streamlined training and serving options with JAX. <https://easydel.readthedocs.io/en/latest/>
- [NVIDIA/JAX-Toolbox](https://github.com/NVIDIA/JAX-Toolbox): JAX-Toolbox
- [deepmodeling/jax-fem](https://github.com/deepmodeling/jax-fem): Differentiable Finite Element Method with JAX
- [brentyi/jaxlie](https://github.com/brentyi/jaxlie): Rigid transforms + Lie groups in JAX
- [pnkraemer/matfree](https://github.com/pnkraemer/matfree): Matrix-free linear algebra in JAX. <https://pnkraemer.github.io/matfree/>
- [deepmodeling/DMFF](https://github.com/deepmodeling/DMFF): DMFF (Differentiable Molecular Force Field) is a Jax-based python package that provides a full differentiable implementation of molecular force field models.
- [ZQZCalin/trainit](https://github.com/ZQZCalin/trainit): Trainit is a machine learning training pipeline based on jax. It is also built on optax for optimizers, equinox for models, wandb for logging, and hydra for convenient configuration management.
- [benabed/clipy](https://github.com/benabed/clipy): pure python clik implementation with jax support.
- [RobertTLange/evosax](https://github.com/RobertTLange/evosax): Evolution Strategies in JAX 🦎
- [jaxleyverse/jaxley](https://github.com/jaxleyverse/jaxley): Differentiable neuron simulations with biophysical detail on CPU, GPU, or TPU. <https://jaxley.readthedocs.io>
- [divyamakkar0/JAXformer](https://github.com/divyamakkar0/JAXformer): This is a zero-to-one guide on scaling modern transformers with n-dimensional parallelism. <https://jaxformer.com>

patrick-kidger

- [patrick-kidger/equinox](https://github.com/patrick-kidger/equinox): Callable PyTrees and filtered transforms => neural networks in JAX. <https://docs.kidger.site/equinox>
- [patrick-kidger/optimistix](https://github.com/patrick-kidger/optimistix): Nonlinear optimisation (root-finding, least squares, ...) in JAX+Equinox. <https://docs.kidger.site/optimistix>
- [patrick-kidger/diffrax](https://github.com/patrick-kidger/diffrax): Numerical differential equation solvers in JAX. Autodifferentiable and GPU-capable. <https://docs.kidger.site/diffrax>
- [patrick-kidger/lineax](https://github.com/patrick-kidger/lineax): Linear solvers in JAX and Equinox. https://docs.kidger.site/lineax
- [patrick-kidger/quax](https://github.com/patrick-kidger/quax): Multiple dispatch over abstract array types in JAX.
- [patrick-kidger/sympy2jax](https://github.com/patrick-kidger/sympy2jax): Turn SymPy expressions into trainable JAX expressions.

Jax ml

- [jax-ml/oryx](https://github.com/jax-ml/oryx): Oryx is a library for probabilistic programming and deep learning built on top of Jax. <https://tensorflow.org/probability/oryx>
- [jax-ml/coix](https://github.com/jax-ml/coix): Inference Combinators in JAX <https://coix.readthedocs.io/en/latest/>
- [jax-ml/bayeux](https://github.com/jax-ml/bayeux): State of the art inference for your bayesian models. <https://jax-ml.github.io/bayeux/>
- [jax-ml/jax-triton](https://github.com/jax-ml/jax-triton): jax-triton contains integrations between JAX and OpenAI Triton
- [jax-ml/jax-ai-stack](https://github.com/jax-ml/jax-ai-stack): No description, website, or topics provided.

Distributed & Parallelism

- [Autodesk/XLB](https://github.com/Autodesk/XLB): XLB: Accelerated Lattice Boltzmann (XLB) based on JAX for Physics-based ML
- [apple/axlearn](https://github.com/apple/axlearn): AXLearn is a library built on top of JAX and XLA to support development of large-scale deep learning models.
- [facebookresearch/minimax](https://github.com/facebookresearch/minimax): Efficient baselines for autocurricula in JAX.
- [mpi4jax/mpi4jax](https://github.com/mpi4jax/mpi4jax): Zero-copy MPI communication of JAX arrays, for turbo-charged HPC applications in Python ⚡ <https://mpi4jax.readthedocs.io/>

PGM / Probabilistic programming

- [vicariousinc/PGMax](https://github.com/vicariousinc/PGMax): Loopy belief propagation for factor graphs on discrete variables, in JAX! <https://pgmax.readthedocs.io>
- [blackjax-devs/blackjax](https://github.com/blackjax-devs/blackjax): BlackJAX is a sampling library designed for ease of use, speed and modularity. <https://blackjax-devs.github.io/blackjax>
- [JaxGaussianProcesses/GPJax](https://github.com/JaxGaussianProcesses/GPJax): Gaussian processes in JAX. <https://docs.jaxgaussianprocesses.com/>
- [pyro-ppl/numpyro](https://github.com/pyro-ppl/numpyro): Probabilistic programming with NumPy powered by JAX for autograd and JIT compilation to GPU/TPU/CPU. <https://num.pyro.ai>
- [geraschenko/gmrfs](https://github.com/geraschenko/gmrfs): Gaussian Markov Random Fields (GMRFs) and Integrated Nested Laplace Approximation (INLA)

### DeepMind specialization

- [Using JAX to accelerate our research](https://www.deepmind.com/blog/using-jax-to-accelerate-our-research)
- [google-deepmind/dm-haiku](https://github.com/google-deepmind/dm-haiku): JAX-based neural network library <https://dm-haiku.readthedocs.io>
- [google-deepmind/optax](https://github.com/google-deepmind/optax): Optax is a gradient processing and optimization library for JAX. <https://optax.readthedocs.io>
- [google-deepmind/rlax](https://github.com/google-deepmind/rlax): RLax (pronounced "relax") is a library built on top of JAX that exposes useful building blocks for implementing reinforcement learning agents. <https://rlax.readthedocs.io>
- 🌟 [google-deepmind/chex](https://github.com/google-deepmind/chex): Chex is a library of utilities for helping to write reliable JAX code. <https://chex.readthedocs.io>
- [google-deepmind/jraph](https://github.com/google-deepmind/jraph): A Graph Neural Network Library in Jax <https://jraph.readthedocs.io/en/latest>
- 🌟 [google-deepmind/mctx](https://github.com/google-deepmind/mctx): Monte Carlo tree search in JAX
- [google-deepmind/distrax](https://github.com/google-deepmind/distrax): Distrax is a lightweight library of probability distributions and bijectors. It acts as a JAX-native reimplementation of a subset of TensorFlow Probability (TFP, https://www.tensorflow.org/probability), with some new features and emphasis on extensibility.
- [google-deepmind/PGMax](https://github.com/google-deepmind/PGMax): Loopy belief propagation for factor graphs on discrete variables in JAX
- [google-deepmind/synjax](https://github.com/google-deepmind/synjax): SynJax is a neural network library for JAX structured probability distributions.
- [google-deepmind/alphatensor](https://github.com/google-deepmind/alphatensor): Discovering faster matrix multiplication algorithms with reinforcement learning
- 🌟 [google-deepmind/penzai](https://github.com/google-deepmind/penzai): A JAX research toolkit for building, editing, and visualizing neural networks. <https://penzai.readthedocs.io/>
- 🌟 [google-deepmind/treescope](https://github.com/google-deepmind/treescope): An interactive HTML pretty-printer for machine learning research in IPython notebooks. <https://treescope.readthedocs.io/>
- 📝 [google-deepmind/launchpad](https://github.com/google-deepmind/launchpad): Launchpad is a library that simplifies writing distributed programs by seamlessly launching them on a variety of different platforms. Switching between local and distributed execution requires only a flag change.
- [google-deepmind/jaxline](https://github.com/google-deepmind/jaxline): JAXline is a distributed JAX training and evaluation framework.
- [google-deepmind/torax](https://github.com/google-deepmind/torax): TORAX: Tokamak transport simulation in JAX <https://torax.readthedocs.io>
- 🌟 [google-deepmind/fancyflags](https://github.com/google-deepmind/fancyflags): A Python library for defining flat or nested dictionary flags.
- [google-deepmind/jax_verify](https://github.com/google-deepmind/jax_verify): Neural network verification in JAX
- [google-deepmind/concordia](https://github.com/google-deepmind/concordia): A library for generative social simulation
- [google-deepmind/uncertain_ground_truth](https://github.com/google-deepmind/uncertain_ground_truth): Dermatology ddx dataset, Jax implementations of Monte Carlo conformal prediction, plausibility regions and statistical annotation aggregation from our recent work on uncertain ground truth (TMLR'23 and ArXiv pre-print). <https://davidstutz.de/projects/monte-carlo-conformal-prediction/>
- [google-deepmind/meltingpot](https://github.com/google-deepmind/meltingpot): A suite of test scenarios for multi-agent reinforcement learning.
- [google-deepmind/dm_pix](https://github.com/google-deepmind/dm_pix): PIX is an image processing library in JAX, for JAX. <https://dm-pix.readthedocs.io>

### Google specialization

- [google/flax](https://github.com/google/flax): Flax is a neural network library for JAX that is designed for flexibility. <https://flax.readthedocs.io>
- 🌟 [google/trax](https://github.com/google/trax): Trax — Deep Learning with Clear Code and Speed
- [google/jaxopt](https://github.com/google/jaxopt): Hardware accelerated, batchable and differentiable optimizers in JAX. <https://jaxopt.github.io>
- [google/orbax](https://github.com/google/orbax): Orbax provides common utility libraries for JAX users. <https://orbax.readthedocs.io/>
- [google/brax](https://github.com/google/brax): Massively parallel rigidbody physics simulation on accelerator hardware.
- [google/paxml](https://github.com/google/paxml): Pax is a Jax-based machine learning framework for training large scale models. Pax allows for advanced and fully configurable experimentation and parallelization, and has demonstrated industry leading model flop utilization rates.
- [google/praxis](https://github.com/google/praxis): No description, website, or topics provided. This is not an officially supported Google product.
- [google/ml_collections](https://github.com/google/ml_collections): ML Collections is a library of Python Collections designed for ML use cases. <https://ml-collections.readthedocs.io/>
- [google/qwix](https://github.com/google/qwix): a Jax quantization library <https://qwix.readthedocs.io>
- [AI-Hypercomputer/maxtext](https://github.com/AI-Hypercomputer/maxtext): A simple, performant and scalable Jax LLM!
- [AI-Hypercomputer/JetStream](https://github.com/AI-Hypercomputer/JetStream): JetStream is a throughput and memory optimized engine for LLM inference on XLA devices, starting with TPUs (and GPUs in future -- PRs welcome).
- [AI-Hypercomputer/maxdiffusion](https://github.com/AI-Hypercomputer/maxdiffusion): MaxDiffusion is a collection of reference implementations of various latent diffusion models written in pure Python/Jax that run on XLA devices including Cloud TPUs and GPUs.
- [google-research/discs](https://github.com/google-research/discs): DISCS: The code base for the Benchmark for Discrete Sampling
- [google-research/gpax](https://github.com/google-research/gpax): Gaussian processes in Jax.
- [google-research/e3x](https://github.com/google-research/e3x): E3x is a JAX library for constructing efficient E(3)-equivariant deep learning architectures built on top of Flax.
- [google-research/scenic](https://github.com/google-research/scenic): Scenic: A Jax Library for Computer Vision Research and Beyond
- [google-research/kauldron](https://github.com/google-research/kauldron): Modular, scalable library to train ML models <https://kauldron.readthedocs.io/>

### Manipulating and transforming Ops

- [google/pyglove](https://github.com/google/pyglove): Manipulating Python Programs
- 🌟 [arogozhnikov/einops](https://github.com/arogozhnikov/einops): Deep learning operations reinvented (for pytorch, tensorflow, jax and others) <https://einops.rocks>
- 🌟 [fferflo/einx](https://github.com/fferflo/einx): Universal Tensor Operations in Einstein-Inspired Notation for Python. <https://einx.readthedocs.io/en/stable/>
- [google-deepmind/tree](https://github.com/google-deepmind/tree): tree is a library for working with nested data structures <https://tree.readthedocs.io>
- [NeilGirdhar/tjax](https://github.com/NeilGirdhar/tjax): Tools for JAX
- [google-research/dataclass_array](https://github.com/google-research/dataclass_array): Dataclasses manipulated as numpy arrays (with batching, reshape, slicing,...) <https://dataclass-array.readthedocs.io>
- [brentyi/jax_dataclasses](https://github.com/brentyi/jax_dataclasses): Pytrees + dataclasses ❤️
- [Artur-Galstyan/statedict2pytree](https://github.com/Artur-Galstyan/statedict2pytree): No description, website, or topics provided.
- 🌟 [metaopt/optree](https://github.com/metaopt/optree): OpTree: Optimized PyTree Utilities <https://optree.readthedocs.io>
- [ayaka14732/einshard](https://github.com/ayaka14732/einshard): High-level array sharding API for JAX <https://einshard.readthedocs.io/>
- [yixiaoer/einshard](https://github.com/yixiaoer/einshard): Einsum-like high-level array sharding API for JAX <https://einshard.readthedocs.io/>
- [pymc-devs/pytensor](https://github.com/pymc-devs/pytensor): PyTensor allows you to define, optimize, and efficiently evaluate mathematical expressions involving multi-dimensional arrays. <https://pytensor.readthedocs.io>
- [alebeck/chunkax](https://github.com/alebeck/chunkax): A lightweight JAX transform for applying functions to array chunks over arbitrary sizes and dimensions.

### Utils

- [xl0/lovely-jax](https://github.com/xl0/lovely-jax): JAX Arrays for human consumption <https://xl0.github.io/lovely-jax>
- [BirkhoffG/jax-dataloader](https://github.com/BirkhoffG/jax-dataloader): Pytorch-like dataloaders in JAX. <https://birkhoffg.github.io/jax-dataloader/>
- [dlwh/jax_sourceror](https://github.com/dlwh/jax_sourceror): Turn jitted jax functions back into python source code
- [ayaka14732/jax-smi](https://github.com/ayaka14732/jax-smi): JAX Synergistic Memory Inspector <https://pypi.org/project/jax-smi/>

## Libraries

- [pytorch/functorch](https://github.com/pytorch/functorch): functorch is JAX-like composable function transforms for PyTorch. <https://pytorch.org/functorch>
- [pytorch/torcharrow](https://github.com/pytorch/torcharrow): A Pandas-inspired DataFrame library for SQL-like transformation with Pythonic and imperative-style API. Typical use case includes data preprocessing in ML models.
- [pytorch-labs/torchfix](https://github.com/pytorch-labs/torchfix): TorchFix - a linter for PyTorch-using code with autofix support
- [pytorch/kineto](https://github.com/pytorch/kineto): A CPU+GPU Profiling library that provides access to timeline traces and hardware performance counters.
- [huggingface/evaluate](https://github.com/huggingface/evaluate): 🤗 Evaluate: A library for easily evaluating machine learning models and datasets. <https://huggingface.co/docs/evaluate>
- [mosaicml/streaming](https://github.com/mosaicml/streaming): A Data Streaming Library for Efficient Neural Network Training <https://streaming.docs.mosaicml.com>
- [rdyro/torch2jax](https://github.com/rdyro/torch2jax): Wraps PyTorch code in a JIT-compatible way for JAX. Supports automatically defining gradients for reverse-mode AutoDiff. <https://rdyro.github.io/torch2jax/>

### Autodiff

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
- [NVIDIA/warp](https://github.com/NVIDIA/warp): A Python framework for high performance GPU simulation and graphics <https://nvidia.github.io/warp/>
- [autodiff/autodiff](https://github.com/autodiff/autodiff): automatic differentiation made easier for C++ <https://autodiff.github.io>
- [charles-r-earp/autograph](https://github.com/charles-r-earp/autograph): A machine learning library for Rust.
- [parrt/autodx](https://github.com/parrt/autodx): Simple automatic differentiation via operator overloading for educational purposes

### Typing

- [patrick-kidger/torchtyping](https://github.com/patrick-kidger/torchtyping): Type annotations and dynamic checking for a tensor's shape, dtype, names, etc.
- [google/jaxtyping](https://github.com/google/jaxtyping): Type annotations and runtime checking for shape and dtype of JAX arrays, and PyTrees.
- [pytorch/ao](https://github.com/pytorch/ao): The missing pytorch dtype and layout library for training and inference
- [stackav-oss/dltype](https://github.com/stackav-oss/dltype): Deep Learning Type Library

### Data store and Data loading

- [dmlc/dlpack](https://github.com/dmlc/dlpack): common in-memory tensor structure <https://dmlc.github.io/dlpack/latest>
- [xtensor-stack/xtensor](https://github.com/xtensor-stack/xtensor): C++ tensors with broadcasting and lazy computing
- [huggingface/safetensors](https://github.com/huggingface/safetensors): Simple, safe way to store and distribute tensors
  - [alvarobartt/safejax](https://github.com/alvarobartt/safejax): Serialize JAX, Flax, Haiku, or Objax model params with 🤗`safetensors` <https://alvarobartt.github.io/safejax/>
- [google/tensorstore](https://github.com/google/tensorstore): Library for reading and writing large multi-dimensional arrays. <https://google.github.io/tensorstore/>
- [mlcommons/croissant](https://github.com/mlcommons/croissant): Croissant is a high-level format for machine learning datasets that brings together four rich layers. <https://mlcommons.org/croissant>
- [facebookresearch/spdl](https://github.com/facebookresearch/spdl): Scalable and Performant Data Loading
- 🌟 [google/grain](https://github.com/google/grain): Library for reading and processing ML training data. <https://google-grain.readthedocs.io>
- [coreweave/tensorizer](https://github.com/coreweave/tensorizer): Module, Model, and Tensor Serialization/Deserialization
- [facebookresearch/stopes](https://github.com/facebookresearch/stopes): A library for preparing data for machine translation research (monolingual preprocessing, bitext mining, etc.) built by the FAIR NLLB team. <https://facebookresearch.github.io/stopes/>
- [google/seqio](https://github.com/google/seqio): Task-based datasets, preprocessing, and evaluation for sequence models.
- [NVIDIA/DALI](https://github.com/NVIDIA/DALI): A GPU-accelerated library containing highly optimized building blocks and an execution engine for data processing to accelerate deep learning training and inference applications. <https://docs.nvidia.com/deeplearning/dali/user-guide/docs/index.html>

### Utils

- [NVIDIA/nvidia-container-toolkit](https://github.com/NVIDIA/nvidia-container-toolkit): Build and run containers leveraging NVIDIA GPUs
- [nvidia/container-images/cuda](https://gitlab.com/nvidia/container-images/cuda): Nvidia CUDA Linux Container Image Sources
  - 🌟 [nvidia/cuda](https://hub.docker.com/r/nvidia/cuda): CUDA and cuDNN images from gitlab.com/nvidia/cuda
  - [Optimizing PyTorch Docker images: how to cut size by 60%](https://mveg.es/posts/optimizing-pytorch-docker-images-cut-size-by-60percent/)
- [aws/deep-learning-containers](https://github.com/aws/deep-learning-containers): AWS Deep Learning Containers (DLCs) are a set of Docker images for training and serving models in TensorFlow, TensorFlow 2, PyTorch, and MXNet. <https://docs.aws.amazon.com/deep-learning-containers/latest/devguide/deep-learning-containers-images.html>
- [replicate/cog](https://github.com/replicate/cog): Containers for machine learning
- [alteryx/featuretools](https://github.com/alteryx/featuretools): An open source python library for automated feature engineering <https://www.featuretools.com>
- [XuehaiPan/nvitop](https://github.com/XuehaiPan/nvitop): An interactive NVIDIA-GPU process viewer and beyond, the one-stop solution for GPU process management. <https://nvitop.readthedocs.io/>
- [Syllo/nvtop](https://github.com/Syllo/nvtop): GPUs process monitoring for AMD, Intel and NVIDIA
- [msminhas93/nviwatch](https://github.com/msminhas93/nviwatch): NviWatch: A blazingly fast rust based TUI for managing and monitoring NVIDIA GPU processes
- [kagehq/gpu-kill](https://github.com/kagehq/gpu-kill): Manage your GPUs across NVIDIA, AMD, Intel, and Apple Silicon systems. <https://gpukill.com>
- [wookayin/gpustat](https://github.com/wookayin/gpustat): 📊 A simple command-line utility for querying and monitoring GPU status
- [google/fiddle](https://github.com/google/fiddle): Fiddle is a Python-first configuration library particularly well suited to ML applications. Fiddle enables deep configurability of parameters in a program, while allowing configuration to be expressed in readable and maintainable Python code.
- [fastai/fastcore](https://github.com/fastai/fastcore): Python supercharged for the fastai library <http://fastcore.fast.ai>
- [parrt/tensor-sensor](https://github.com/parrt/tensor-sensor): The goal of this library is to generate more helpful exception messages for matrix algebra expressions for numpy, pytorch, jax, tensorflow, keras, fastai. <https://github.com/parrt/tensor-sensor>
  - looks great, but no longer active
- [chaunceyjiang/fake-gpu](https://github.com/chaunceyjiang/fake-gpu): This project is designed to simulate GPU information, making it easier to test scenarios where a GPU is not available.
- 🌟 [NVIDIA/nvbandwidth](https://github.com/NVIDIA/nvbandwidth): A tool for bandwidth measurements on NVIDIA GPUs.
- [Lyken17/pytorch-OpCounter](https://github.com/Lyken17/pytorch-OpCounter): Count the MACs / FLOPs of your PyTorch model.
- [aikitoria/nanotrace](https://github.com/aikitoria/nanotrace): Low overhead tracing library and trace visualizer for pipelined CUDA kernels

### Benchmark

- [mli/transformers-benchmarks](https://github.com/mli/transformers-benchmarks): real Transformer TeraFLOPS on various GPUs
- [openai/evals](https://github.com/openai/evals): Evals is a framework for evaluating OpenAI models and an open-source registry of benchmarks.
- [tensorchord/inference-benchmark](https://github.com/tensorchord/inference-benchmark): WIP Benchmark for machine learning model online serving (LLM, embedding, Stable-Diffusion, Whisper)
- [mlcommons/algorithmic-efficiency](https://github.com/mlcommons/algorithmic-efficiency): MLCommons Algorithmic Efficiency is a benchmark and competition measuring neural network training speedups due to algorithmic improvements in both training algorithms and models. <https://mlcommons.org/en/groups/research-algorithms/>
- [mlcommons/training](https://github.com/mlcommons/training): Reference implementations of MLPerf™ training benchmarks <https://mlcommons.org/en/groups/training>
- [mlcommons/inference](https://github.com/mlcommons/inference): Reference implementations of MLPerf™ inference benchmarks <https://mlcommons.org/en/groups/inference>
- [mlcommons/logging](https://github.com/mlcommons/logging): MLPerf™ logging library <https://mlcommons.org/en/groups/best-practices-benchmark-infra>
- [Michaelvll/llm-ie-benchmarks](https://github.com/Michaelvll/llm-ie-benchmarks): A collection of reproducible inference engine benchmarks
  - Actually, I hope to learn how to use skypilot to set up similar environments quickly here.

## Happy small projects (to learn)

- [minitorch/minitorch](https://github.com/minitorch/minitorch): The full minitorch student suite.
- [karpathy/micrograd](https://github.com/karpathy/micrograd): A tiny scalar-valued autograd engine and a neural net library on top of it with PyTorch-like API
- [karpathy/llm.c](https://github.com/karpathy/llm.c): LLM training in simple, raw C/CUDA
- [pranftw/neograd](https://github.com/pranftw/neograd): A deep learning framework created from scratch with Python and NumPy <https://neograd.readthedocs.io>
- [mohammadpz/pytorch_forward_forward](https://github.com/mohammadpz/pytorch_forward_forward): Implementation of Hinton's forward-forward (FF) algorithm - an alternative to back-propagation
- [lucidrains/x-transformers](https://github.com/lucidrains/x-transformers): A simple but complete full-attention transformer with a set of promising experimental features from various papers
- [lucidrains/ring-attention-pytorch](https://github.com/lucidrains/ring-attention-pytorch): Explorations into Ring Attention, from Liu et al. at Berkeley AI
- [lucidrains/vector-quantize-pytorch](https://github.com/lucidrains/vector-quantize-pytorch): Vector (and Scalar) Quantization, in Pytorch
- [sustcsonglin/flash-linear-attention](https://github.com/sustcsonglin/flash-linear-attention): Efficient implementations of state-of-the-art linear attention models in Pytorch and Triton
- [Vchitect/LaVie](https://github.com/Vchitect/LaVie): LaVie: High-Quality Video Generation with Cascaded Latent Diffusion Models
- [HMUNACHI/nanodl](https://github.com/HMUNACHI/nanodl): A Jax-based library for designing and training transformer models from scratch.
- [beresandras/clear-diffusion-keras](https://github.com/beresandras/clear-diffusion-keras): Implementation of denoising diffusion models with schedules, improved sampling, and other extensions using Keras.
- [naklecha/llama3-from-scratch](https://github.com/naklecha/llama3-from-scratch): llama3 implementation one matrix multiplication at a time
- [milton-l/microhaskell](https://github.com/milton-l/microhaskell): Small autodiff lib and a simple working feedforward neural net in Haskell on top of it, from scratch, zero-deps.
- [dorjeduck/momograd](https://github.com/dorjeduck/momograd): A Learning Journey: Micrograd in Mojo 🔥
- [mttga/purejaxql](https://github.com/mttga/purejaxql): Simple single-file baselines for Q-Learning in pure-GPU setting
- [lucidrains/flash-attention-jax](https://github.com/lucidrains/flash-attention-jax): Implementation of Flash Attention in Jax
- [gordicaleksa/get-started-with-JAX](https://github.com/gordicaleksa/get-started-with-JAX): The purpose of this repo is to make it easy to get started with JAX, Flax, and Haiku. It contains my "Machine Learning with JAX" series of tutorials (YouTube videos and Jupyter Notebooks) as well as the content I found useful while learning about the JAX ecosystem. <https://www.youtube.com/c/TheAIEpiphany/>
- [kingoflolz/swarm-jax](https://github.com/kingoflolz/swarm-jax): Swarm training framework using Haiku + JAX + Ray for layer parallel transformer language models on unreliable, heterogeneous nodes
- [smolorg/smolgrad](https://github.com/smolorg/smolgrad): small auto-grad engine inspired from Karpathy's micrograd and PyTorch
- [KellerJordan/modded-nanogpt](https://github.com/KellerJordan/modded-nanogpt): NanoGPT (124M) in 5 minutes
  - Modernized architecture: Rotary embeddings, QK-Norm, and ReLU^2.
  - New optimizer: Muon - Momentum Orthogonalized by Newton-schulz (standalone implementation).
  - Untied head from embedding.
  - Projection and classification layers initialized to zero (muP-like).
  - Architectural shortcuts: value residual and embedding shortcut (partially following https://arxiv.org/abs/2410.17897).
  - Momentum warmup.
  - Tanh soft logit capping (following Gemma 2).
  - FlexAttention with window size warmup.
  - Extra embeddings which are fed into intermediate attention layers.
- [zhuzilin/ring-flash-attention](https://github.com/zhuzilin/ring-flash-attention): Ring attention implementation with flash attention
- [fla-org/flash-linear-attention](https://github.com/fla-org/flash-linear-attention): Efficient implementations of state-of-the-art linear attention models in Pytorch and Triton <https://github.com/fla-org/flash-linear-attention>
- [SonyResearch/micro_diffusion](https://github.com/SonyResearch/micro_diffusion): Official repository for our work on micro-budget training of large-scale diffusion models. <https://arxiv.org/abs/2407.15811>
- [JINO-ROHIT/mini-AutoGrad](https://github.com/JINO-ROHIT/mini-AutoGrad)
  - [symbolic_differentiation.py](https://github.com/JINO-ROHIT/mini-AutoGrad/blob/main/mini-grad/symbolic_differentiation.py)
- [jax-ml/jax-llm-examples](https://github.com/jax-ml/jax-llm-examples)
  - DeepSeek R1
- [Lancern/mini-qwen-py](https://github.com/Lancern/mini-qwen-py): A toy implementation of Qwen3 inference
- [pierrot-lc/jax-gnn](https://github.com/pierrot-lc/jax-gnn): GNN implemented using JAX and Equinox <https://pierrot-lc.dev/posts/2024-09-02_jax-gnn/>
- [karpathy/nanochat](https://github.com/karpathy/nanochat): The best ChatGPT that $100 can buy.
