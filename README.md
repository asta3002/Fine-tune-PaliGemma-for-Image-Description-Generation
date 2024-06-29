# Fine-tune-PaliGemma-for-Image-Description-Generation
This repository is for fine-tuning PaliGemma for image description generation task
# Fine Tuning
The notebook Finetune_paligemma.ipynb fine tunes paligemma model, on "ImageinWords" Dataset. The notebook utlizes JAX library and quantization to run the model on colab's T4 GPU
# ImageInWords Dataset
An image captioning dataset, called [**ImageInWords**](https://google.github.io/imageinwords/), is chosen for the assignment. It’s designed using a human-in-the-loop annotation framework for curating hyper-detailed image descriptions, to overcome missing information, visual inconsistencies, and hallucinations, in fine-tuned models. It consists of 400 samples.
# Demo
The notebook PaliGemma_Demo.ipynb constructs a Gradio Demo for the fine-tuned model, where input is the image URL.




