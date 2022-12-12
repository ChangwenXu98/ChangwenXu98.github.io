---
title: "TransPolymer: a Transformer-based Language Model for Polymer Property Predictions"
collection: talks
type: "Invited Talk"
permalink: /talks/2022-11-25-TransPolymer
venue: "Brown University, CRUNCH Group Seminar"
date: 2022-11-25
location: "Online"
---

[More information here](https://www.youtube.com/watch?v=s8ZQaZ6818c&t=7189s)

**Abstract**

Accurate and efficient prediction of polymer properties is of great significance in polymer development and design. Conventionally, expensive and time-consuming experiments or simulations are required to evaluate the function of polymers. Recently, Transformer models, equipped with attention mechanisms, have exhibited superior performance in various natural language processing tasks. However, such methods have not been investigated in polymer sciences. Herein, we report TransPolymer, a Transformer-based language model for polymer property prediction. Owing to our proposed polymer tokenizer with chemical awareness, TransPolymer can learn representations directly from polymer sequences. The model learns expressive representations by pretraining on a large unlabeled dataset, followed by finetuning the model on downstream datasets concerning various polymer properties. TransPolymer achieves superior performance in all eight datasets and surpasses other baselines significantly on most downstream tasks. Moreover, the improvement by the pretrained TransPolymer over supervised TransPolymer and other language models strengthens the significant benefits of pretraining on large unlabeled data in representation learning. Experiment results further demonstrate the important role of the attention mechanism in understanding polymer sequences. We highlight this model as a promising computational tool for promoting rational polymer design and understanding structure-property relationships from a data science view.