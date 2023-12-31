---
tags:
- generated_from_trainer
metrics:
- rouge
- bleu
model-index:
- name: pegasus_out
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# pegasus_out

This model is a fine-tuned version of [IDEA-CCNL/Randeng-Pegasus-238M-Chinese](https://huggingface.co/IDEA-CCNL/Randeng-Pegasus-238M-Chinese) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 5.5225
- Rouge1: 0.0782
- Rouge2: 0.0288
- Rouge-l: 0.0734
- Bleu: 0.0525
- Gen Len: 18.4042

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 50.0

### Training results



### Framework versions

- Transformers 4.18.0
- Pytorch 1.10.0+cu113
- Datasets 1.17.0
- Tokenizers 0.12.1
