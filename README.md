# SQL LLM Fine-tuning

Fine-tuning a pretrained LLM for Natural Language → SQL using the Spider dataset
and Unsloth for efficient LoRA-based training.

## Highlights
- Base model: Qwen (specify exact variant)
- Fine-tuning method: LoRA
- Dataset: Spider (~7k samples)
- Environment: JupyterHub (college server)

## Files
- `sql-llm.ipynb`: training and evaluation notebook

## Notes
Model checkpoints, LoRA adapters, and caches are intentionally excluded from
this repository. Trained weights can be shared via Hugging Face Hub.
