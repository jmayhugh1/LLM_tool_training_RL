# Cost-Aware Tool Usage for LLMs

## Requirements

A Hugging Face and Wandb token are need to view outputs. Running the first cell in each notebook should install all the requirements. It is highly suggested to open and run in Google Colab. If you have any issues doing so please reach out to jmayhugh@tamu.edu or Janshyam03@tamu.edu. If you choose not to use google colab please consult the requirements.txt and run ```pip install -r requirements.txt```

## rl_llms.ipynb

This is where the pretrained model is loaded, the xlam tool calling dataset is loaded and the SFT Model is trained. All cells can be run sequentially.

## GRPO.ipynb

This is where the additional step of fine tuning is done with GRPO, this containts the reward modeling and training. All cells can be run sequentially.
