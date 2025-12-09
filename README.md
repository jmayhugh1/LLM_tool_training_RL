# Description of Files

## requirements
You need a Hugging Face Token and a wandb token to view outputs, running the first cell in each notebook should install all the requirements if in google colab, I would highly suggest downloading and opening in Google Colab. If you have any issues doing so please reach out to jmayhugh@tamu.edu. If you choose not to use google colab please consult the requirements.txt and run ```pip install -r requirements.txt```

## rl_llms.ipynb

This is where the pretrained model is loaded, the xlam tool calling dataset is loaded and the SFT Model is trained.

## GRPO.ipynb

This is where the additional step of fine tuning is done with GRPO, this containts the reward modeling and training.
