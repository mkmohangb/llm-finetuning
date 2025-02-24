# llm-finetuning

- fine-tuning a model for [function calling](https://colab.research.google.com/drive/1hykfwiZTN8cIipz_xqlA1xaVR1Wr55Nw?usp=drive_link)
  - Model - Gemma-2-2b-it
  - Dataset - hermes-function-calling-thinking-V1
  - LoRA - ```rank dimension(16), alpha(64), dropout(0.05), target modules to apply LoRA```
  - SFT parameters - ```lr, gradient accumulation, max_grad_norm, warmup_ratio, lr_scheduler_type, weight_decay, gradient_checkpointing```
- fine-tuning using [unsloth](https://colab.research.google.com/drive/1xcG2axhM6-n6bRanWPfo3IKL6QN0aYrK?usp=drive_link)
