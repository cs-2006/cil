# Computational Intelligence Lab 2024 - Tweet sentiment classification

This file describes the submitted code and provides the instructions on how to run the experiments run by our group.

## File description

 - ```qwen2.ipynb``` - The Jupyter notebook based on the template implemented by Unsloth (https://huggingface.co/unsloth). It implements the run using the LM Qwen2
 - ```yesno_llama3.ipynb``` - The Jupyter notebook very similar to the one above (also based on Unsloth template). The major difference is the use of the LM Llama3 instead of Qwen2
 - ```bert_new.ipynb``` - The Jupyter notebook with the implementation of our method utilising BERT
 - ```best_score_approach.ipynb``` - The Jupyter notebook implementing our best scoring method, which is based on BERTweet
 - ```hashtag_segmentation.ipynb``` - The Jupyter notebook which implements the preprocessing step we tried out for our methods
 - ```requirements.txt``` - A file listing the necessary Python libraries in order to run the notebooks

## Instructions on running the code

The code has been run on Python 3.10, likely it can also be run on the newer versions.

In order to run the code, we suggest installing all the necessary packages by running the command:

```
pip install -r requirements.txt
```

Additionally, for running the notebooks ```qwen2.ipynb``` and ```yesno_llama3.ipynb```, once has to install additional packages related to Unsloth implementation. For the detailed instructions, we link to the authors' page: https://github.com/unslothai/unsloth/tree/main?tab=readme-ov-file#-installation-instructions.

Otherwise, one has to potentially edit the filepaths to the datasets used in the notebooks in order to run the notebooks locally.

Afterwards, one should be able to run the notebooks locally and reproduce our results.
