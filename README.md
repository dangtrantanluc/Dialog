# DialogSum - Fine Tuning
This is my personal project, where I will fine-tune Microsoft’s Phi-2, a relatively small 2.7B parameter model that has demonstrated near state-of-the-art performance among models with fewer than 13 billion parameters.

For this, I will use QLoRA (Efficient Fine-Tuning of Quantized LLMs), an advanced and highly efficient fine-tuning technique. It works by quantizing a pretrained LLM to just 4 bits and adding small Low-Rank Adapters (LoRA).

This approach allows for fine-tuning LLMs using just a single GPU, making it highly accessible. The technique is supported by the PEFT library.
