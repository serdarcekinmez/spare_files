<<<<<<< HEAD
# spare_files_
Jedha story_teller project

As many of generators and fine_tuning files have been used in 'Stroy Teller' project, most of them they are stored on this Github page for future uses or future model comparisons. 

Please use pp versions.
fine-tune in sentences bases
In paragraphe based model some issues countered.
Training batch=8 epoch =3 takes about 1h / book
=======
---
license: apache-2.0
tags:
- generated_from_keras_callback
model-index:
- name: CSerdar014191/distilgpt2_test01_finetune
  results: []
---

<!-- This model card has been generated automatically according to the information Keras had access to. You should
probably proofread and complete it, then remove this comment. -->

# CSerdar014191/distilgpt2_test01_finetune

This model is a fine-tuned version of [distilgpt2](https://huggingface.co/distilgpt2) on an unknown dataset.
It achieves the following results on the evaluation set:
- Train Loss: 3.8469
- Validation Loss: 3.9551
- Epoch: 0

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- optimizer: {'name': 'AdamWeightDecay', 'learning_rate': 2e-05, 'decay': 0.0, 'beta_1': 0.9, 'beta_2': 0.999, 'epsilon': 1e-07, 'amsgrad': False, 'weight_decay_rate': 0.01}
- training_precision: float32

### Training results

| Train Loss | Validation Loss | Epoch |
|:----------:|:---------------:|:-----:|
| 3.8469     | 3.9551          | 0     |


### Framework versions

- Transformers 4.27.4
- TensorFlow 2.12.0
- Datasets 2.11.0
- Tokenizers 0.13.3
>>>>>>> fine_tuner/main
