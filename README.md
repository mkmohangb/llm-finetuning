# llm-finetuning

- fine-tuning a model for [function calling](https://colab.research.google.com/drive/1hykfwiZTN8cIipz_xqlA1xaVR1Wr55Nw?usp=drive_link)
  - Model - Gemma-2-2b-it
  - Dataset - hermes-function-calling-thinking-V1 and add a thinking step (<think></think>)
  - LoRA - ```rank dimension(16), alpha(64), dropout(0.05), target modules to apply LoRA```
  - SFT parameters - ```lr, gradient accumulation, max_grad_norm, warmup_ratio, lr_scheduler_type, weight_decay, gradient_checkpointing```
  - training time - ```30 mins per epoch on A40```
    
- fine-tuning a model on medical CoT data using [unsloth](https://colab.research.google.com/drive/1xcG2axhM6-n6bRanWPfo3IKL6QN0aYrK?usp=drive_link)
  - Model - DeepSeek-R1-Distill-Llama-8B
  - Dataset - medical-o1-reasoning-SFT
  - unsloth's ```FastLanguageModel, load_in_4bit, optim(adamw_8bit), bfloat16```
  - training time - ```20 mins per epoch on T4```
