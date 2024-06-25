# AI Infra

## Concepts intro

Hugging Face articles:

- Model parallelism basis: https://huggingface.co/docs/transformers/v4.15.0/en/parallelism#zero-data-parallel
- FSDP: https://huggingface.co/docs/accelerate/en/usage_guides/fsdp
- Deepspeed: https://huggingface.co/docs/accelerate/en/usage_guides/deepspeed
- Megatron-LM: https://huggingface.co/docs/accelerate/en/usage_guides/megatron_lm


## Some Best Practices

- https://github.com/microsoft/DeepSpeed
- https://github.com/NVIDIA/Megatron-LM


# LLM

## Optimization

Training Optimization: https://developer.nvidia.com/blog/mastering-llm-techniques-training
Inference Optimization: https://developer.nvidia.com/blog/mastering-llm-techniques-inference-optimization

## Application

RAG: https://www.youtube.com/watch?v=YuRFba27_1w
Agent: https://www.youtube.com/watch?v=q1XFm21I-VQ

# MLOps

## Intro

https://madewithml.com/

## Application

https://www.youtube.com/watch?v=45Zs12Xlg2g

# Papers

## Communication

- [Two-Tree Algorithms for Full Bandwidth Broadcast, Reduction and Scan](Two-Tree%20Algorithms%20for%20Full%20Bandwidth%20Broadcast%2C%20Reduction%20and%20Scan.pdf)
- [TPU v4 An Optically Reconfigurable Supercomputer for Machine Learning with Hardware Support for Embeddings](TPU%20v4%20An%20Optically%20Reconfigurable%20Supercomputer%20for%20Machine%20Learning%20with%20Hardware%20Support%20for%20Embeddings.pdf)

## Megatron-LM

- [Megatron-LM Training Multi-Billion Parameter Language Models Using Model Parallelism](Megatron-LM%20Training%20Multi-Billion%20Parameter%20Language%20Models%20Using%20Model%20Parallelism.pdf)
- [Efficient Large-Scale Language Model Training on GPU Clusters Using Megatron-LM](Efficient%20Large-Scale%20Language%20Model%20Training%20on%20GPU%20Clusters%20Using%20Megatron-LM.pdf)
- [Reducing Activation Recomputation in Large Transformer Models](Reducing%20Activation%20Recomputation%20in%20Large%20Transformer%20Models.pdf)

## Zero
- [ZeRO Memory Optimizations Toward Training Trillion Parameter Models](./ZeRO%20Memory%20Optimizations%20Toward%20Training%20Trillion%20Parameter%20Models.pdf)

## Megascale

- [MegaScale Scaling Large Language Model Training to More Than 10,000 GPUs](./MegaScale%20Scaling%20Large%20Language%20Model%20Training%20to%20More%20Than%2010,000%20GPUs.pdf)

# Cautious

Something critical:

- Do not try to use LLM to enhance the learning process, such generating questions and answers. You will get nothing.
- Consult the expert to save most of the time.

# Acknowledgement

Thanks to [Liyue Zhang](https://github.com/haswelliris) and [Guangnan Feng](https://github.com/NoBugEveryDay)
