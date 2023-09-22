---
license: cc-by-nc-4.0
base_model: nguyenvulebinh/wav2vec2-base-vi-vlsp2020
tags:
- generated_from_trainer
metrics:
- wer
model-index:
- name: wav2vec2-base-vi-vlsp2020-demo
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# wav2vec2-base-vi-vlsp2020-demo

This model is a fine-tuned version of [nguyenvulebinh/wav2vec2-base-vi-vlsp2020](https://huggingface.co/nguyenvulebinh/wav2vec2-base-vi-vlsp2020) on the None dataset.
It achieves the following results on the evaluation set:
- Loss: 0.2292
- Wer: 0.0840

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0001
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 3

### Training results

| Training Loss | Epoch | Step | Validation Loss | Wer    |
|:-------------:|:-----:|:----:|:---------------:|:------:|
| 0.7245        | 1.0   | 692  | 0.2790          | 0.1101 |
| 0.5746        | 2.0   | 1384 | 0.2467          | 0.0919 |
| 0.4068        | 3.0   | 2076 | 0.2292          | 0.0840 |


### Framework versions

- Transformers 4.33.2
- Pytorch 2.0.1+cu118
- Datasets 2.14.5
- Tokenizers 0.13.3
