---
base_model: HuggingFaceTB/SmolLM-135M-Instruct
datasets:
- generator
library_name: peft
license: apache-2.0
tags:
- trl
- sft
- generated_from_trainer
model-index:
- name: SmolLM-135M-Instruct-medical_meadow_medical_flashcards-100epochs
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# SmolLM-135M-Instruct-medical_meadow_medical_flashcards-100epochs

This model is a fine-tuned version of [HuggingFaceTB/SmolLM-135M-Instruct](https://huggingface.co/HuggingFaceTB/SmolLM-135M-Instruct) on the generator dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.001
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- gradient_accumulation_steps: 2
- total_train_batch_size: 16
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: constant
- lr_scheduler_warmup_ratio: 0.05
- num_epochs: 100

### Training results



### Framework versions

- PEFT 0.12.0
- Transformers 4.44.2
- Pytorch 2.4.1+cu121
- Datasets 3.0.0
- Tokenizers 0.19.1