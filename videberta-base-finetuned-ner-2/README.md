---
base_model: Fsoft-AIC/videberta-base
tags:
- generated_from_trainer
metrics:
- precision
- recall
- f1
- accuracy
model-index:
- name: videberta-base-finetuned-ner-2
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# videberta-base-finetuned-ner-2

This model is a fine-tuned version of [Fsoft-AIC/videberta-base](https://huggingface.co/Fsoft-AIC/videberta-base) on the None dataset.
It achieves the following results on the evaluation set:
- Loss: 0.0166
- Precision: 0.9824
- Recall: 0.9873
- F1: 0.9849
- Accuracy: 0.9952

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0002
- train_batch_size: 16
- eval_batch_size: 16
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 5

### Training results

| Training Loss | Epoch | Step | Validation Loss | Precision | Recall | F1     | Accuracy |
|:-------------:|:-----:|:----:|:---------------:|:---------:|:------:|:------:|:--------:|
| No log        | 1.0   | 328  | 0.0559          | 0.9156    | 0.9364 | 0.9259 | 0.9794   |
| 0.3316        | 2.0   | 656  | 0.0330          | 0.9612    | 0.9741 | 0.9676 | 0.9899   |
| 0.3316        | 3.0   | 984  | 0.0231          | 0.9748    | 0.9821 | 0.9784 | 0.9930   |
| 0.0377        | 4.0   | 1312 | 0.0174          | 0.9826    | 0.9860 | 0.9843 | 0.9949   |
| 0.0149        | 5.0   | 1640 | 0.0166          | 0.9824    | 0.9873 | 0.9849 | 0.9952   |


### Framework versions

- Transformers 4.33.0
- Pytorch 2.0.0
- Datasets 2.1.0
- Tokenizers 0.13.3
