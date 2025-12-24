neeh# SQL LLM Fine-tuning

Fine-tuning a pretrained LLM for Natural Language → SQL using the Spider dataset
and Unsloth for efficient LoRA-based training.

## Trained Model
Model available on Hugging Face:  
[https://huggingface.co/Neeharika20/qwen-spider-lora](https://huggingface.co/Neeharika20/qwen3-4b-nl2sql)

## Highlights
- Base model: Qwen/Qwen3-4B-Instruct-2507
- Fine-tuning method: LoRA
- Dataset: Spider (~7k samples)

## Files
- `sql-llm.ipynb`: training and evaluation notebook

## Notes
Model checkpoints, LoRA adapters, and caches are intentionally excluded from
this repository. Trained weights can be shared via Hugging Face Hub.
