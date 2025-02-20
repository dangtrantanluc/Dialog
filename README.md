# Dialog
This is my personal project, I will fine-tune Microsoft's Phi-2 relatively small 2.7B model - which has "showcased a nearly state-of-the-art performance among models with less than 13 billion parameters" - on your own data!

Here I will use QLoRA (Efficient Finetuning of Quantized LLMs), a highly efficient fine-tuning technique that involves quantizing a pretrained LLM to just 4 bits and adding small “Low-Rank Adapters”.

This unique approach allows for fine-tuning LLMs using just a single GPU! This technique is supported by the PEFT library.
