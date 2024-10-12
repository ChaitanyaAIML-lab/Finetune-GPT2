# Finetune-GPT2-Model-on-downstream-tasks

This repository contains code and resources for fine-tuning the GPT-2 model on downstream tasks using the Hugging Face's transformers library. The project utilizes text data from "The Buddha's Path of Virtue: A Translation of the Dhammapada by F. L. Woodward", available through Project Gutenberg.

## Objectives

By the end of this experiment, you will be able to:
- Load and pre-process data from a text file.
- Load and use a pre-trained tokenizer.
- Finetune a GPT-2 language model on a specific text dataset.

## Dataset Description

The dataset used in this project is taken from one of Project Gutenberg's eBooks named "The Buddha's Path of Virtue: A Translation of the Dhammapada by F. L. Woodward". This dataset includes a variety of teachings and philosophies attributed to Buddha, providing a rich linguistic resource for language modeling.

### Requirements
Before starting, ensure that you have Python installed on your system and the following Python packages:
- `transformers`
- `torch`
- `datasets`
- `tokenizers`

You can install these packages using pip:
```bash
pip install transformers torch datasets tokenizers
```

