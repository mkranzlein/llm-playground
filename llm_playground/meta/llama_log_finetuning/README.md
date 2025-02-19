_Following along with [bokoo/llama3-lora-finetune](https://github.com/bokoo/llama3-lora-finetune/tree/main)_

 **Goal: Finetune [LLama 3.2](https://www.llama.com/docs/model-cards-and-prompt-formats/llama3_2/) to explain synthetic log files**

 Input: 
>[2025-01-06 18:03:49] #Candy - ID: 86023 - Unit: Shipping Service | Message: Type15 event occurred

Expected output:
>This is an error log indicating a request timeout occurred in Shipping Service.

The original repo uses [`bitsandbytes`](https://huggingface.co/docs/bitsandbytes/main/en/index) for quantization and [`peft`](https://huggingface.co/docs/hub/peft) for LoRA, both from Hugging Face.

What's what?

- [LLama 3.2 Finetuning.ipynb](./LLama%203.2%20Finetuning.ipynb): most of the (re)implementation is in this notebook
- [train_logs.txt](./train_logs.txt): dataset for finetuning, copied from the original repo. See [here](https://raw.githubusercontent.com/bokoo/llama3-lora-finetune/refs/heads/main/train_logs.txt).