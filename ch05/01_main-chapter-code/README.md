# Chapter 5: Pretraining on Unlabeled Data

### Main Chapter Code

- [ch05.ipynb](ch05.ipynb) contains all the code as it appears in the chapter
- [previous_chapters.py](previous_chapters.py) is a Python module that contains the `MultiHeadAttention` module and `GPTModel` class from the previous chapters, which we import in [ch05.ipynb](ch05.ipynb) to pretrain the GPT model
- [gpt_download.py](gpt_download.py) contains the utility functions for downloading the pretrained GPT model weights
- [exercise-solutions.ipynb](exercise-solutions.ipynb) contains the exercise solutions for this chapter

### Optional Code

- [gpt_train.py](gpt_train.py) is a standalone Python script file with the code that we implemented in [ch05.ipynb](ch05.ipynb) to train the GPT model (you can think of it as a code file summarizing this chapter)
- [gpt_generate.py](gpt_generate.py) is a standalone Python script file with the code that we implemented in [ch05.ipynb](ch05.ipynb) to load and use the pretrained model weights from OpenAI



# 第 5 章：未标记数据的预训练

### 主要章节代码

-[ch05.ipynb](ch05.ipynb) 包含本章中出现的所有代码
-[previous_chapters.py](previous_chapters.py) 是一个 Python 模块，包含前面章节中的 `MultiHeadAttention` 模块和 `GPTModel` 类，我们将其导入到 [ch05.ipynb](ch05.ipynb) 中以预训练 GPT模型
-[gpt_download.py](gpt_download.py) 包含用于下载预训练 GPT 模型权重的实用函数
-[exercise-solutions.ipynb](exercise-solutions.ipynb) 包含本章的练习题

### 可选代码

-[gpt_train.py](gpt_train.py) 是一个独立的 Python 脚本文件，其中包含我们在 [ch05.ipynb](ch05.ipynb) 中实现的代码，用于训练 GPT 模型（您可以将其视为总结的代码文件）本章）
-[gpt_generate.py](gpt_generate.py) 是一个独立的 Python 脚本文件，其中包含我们在 [ch05.ipynb](ch05.ipynb) 中实现的代码，用于加载和使用 OpenAI 的预训练模型权重
