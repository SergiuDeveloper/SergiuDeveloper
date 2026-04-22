# Sergiu Nistor

**AI Research Engineer** focused on deep learning and scalable ML infrastructure. I'm drawn to the unsolved parts of the field, where the science is still being written and the engineering hasn't caught up yet, and building the systems that make those ideas real.

[![Website](https://img.shields.io/badge/Website-sergiu--nistor.com-black?style=flat-square&logo=firefox)](https://sergiu-nistor.com/)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-sergiu--nistor-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/sergiu-nistor-76786014a)

[![Calendly](https://img.shields.io/badge/Calendly-Book%20a%20call-006BFF?style=flat-square&logo=calendly)](https://calendly.com/sergiunistor/30min)

[![Substack](https://img.shields.io/badge/Substack-Deep%20Learning%20Beyond%20the%20Plateau-orange?style=flat-square&logo=substack)](https://sergiunistor.substack.com/)

---

## Projects

| Project                                                                                                               | Description                                                                                                                                                                                                                           |
| --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**yoro-full-pretraining**](https://github.com/SergiuDeveloper/yoro-full-pretraining)                                 | Novel LLM architecture (**YORO**) where the reasoning block runs once at prefill and is reused across all token generation steps - O(1) reasoning cost vs O(T). Pretrained from scratch on 10B tokens with 8×H100s and DeepSpeed ZeRO |
| [**yoro-finetuning**](https://github.com/SergiuDeveloper/yoro-finetuning)                                             | Fine-tuning stage for YORO: freeze the reasoning block, train lightweight adaptation/compensation/concatenation subnets via knowledge distillation with temperature-scaled soft labels                                                |
| [**llm-layer-prefetch**](https://github.com/SergiuDeveloper/llm-layer-prefetch)                                       | Pipelined layer-streaming system enabling full LLM inference at a fraction of the model's VRAM footprint - disk, CPU, and GPU transfers overlapped in parallel                                                                        |
| [**cuda-kernel-verifier**](https://github.com/SergiuDeveloper/cuda-kernel-verifier)                                   | Runtime correctness checker for custom CUDA/Triton kernels - decorator-based, outlier-biased sampling, zero training graph impact                                                                                                     |
| [**self-attention-cuda-kernel-comparison**](https://github.com/SergiuDeveloper/self-attention-cuda-kernel-comparison) | Benchmarks of hand-written CUDA C, Numba, and Triton self-attention kernels vs PyTorch SDPA across sequence lengths, batch sizes, and head dims                                                                                       |
| [**mojo-tensor**](https://github.com/SergiuDeveloper/mojo-tensor)                                                     | GPU-accelerated deep learning framework in **Mojo** - tensors, autograd, and neural network layers with custom GPU kernel implementations                                                                                             |
| [**distributed-llama.cpp**](https://github.com/SergiuDeveloper/distributed-llama.cpp)                                 | Distributed LLM inference across machines: routes OpenAI-compatible requests to llama.cpp nodes with automatic model distribution, load balancing, and mutual TLS                                                                     |

---

## Skills

**Languages** · Python · C · C++ · Go · Mojo · Java · JavaScript

**DL / ML** · DeepSpeed · PyTorch · TensorFlow · Keras · CUDA · scikit-learn

**Training** · Pretraining · Distributed Training · Fine-Tuning · PEFT · SFT · RLHF · RLAIF · DPO · GRPO · LoRA · QLoRA · Unsloth

**GenAI** · Transformers · Diffusers · vLLM · LangChain · LangGraph · LlamaIndex · llama.cpp

**Infrastructure** · Docker · Kubernetes · AWS · GCP · Azure · Terraform
