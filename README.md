# Showcase Erik Bamberg for research-projects-ml

This Git repository showcases some machine-learning research projects I have been working on and tested overtime.
The repository doesn't contains productivity ready code.The projects are mostly code based on tutorial and getting started blogs I played around out of interest and curiosity.

Two notable projects: the finetuning of LLama 3.1 and the implementation of Control Nets with diffusers.


## Project 1: LLM Finetuning of LLama 3.1
### Overview
This project focuses on the finetuning of LLama 3.1, a at the time of implemeting state-of-the-art large language model (LLM). LLama 3.1 is renowned for its capabilities in natural language understanding and generation, making it a powerful tool for various applications, including chatbots, content creation, and language translation.

### Key Features
Advanced Natural Language Processing: LLama 3.1 excels in understanding and generating human-like text, making it suitable for a wide range of NLP tasks.

Customization through Finetuning: This project demonstrates how to finetune LLama 3.1 for specific applications, enhancing its performance and relevance to particular use cases.

### Implementation Details
The finetuning process involves adjusting the model's parameters to better suit specific datasets and tasks. This project includes examples for setting up the finetuning environment, preparing the dataset, and executing the finetuning process. 
The project uses the small versionn of Llame and uses optimizations to run the finetune process on GoogleColab Notebook, but the same fine-tuning concept can be used to train larger model-versions on multiple GPU'.s 
By following these example, developers can customize LLama 3.1 to meet their unique requirements.

## Project 2: Diffusers - How to Use Control Nets
### Overview
This project focuses on the use of Control Nets with diffusers. Diffusers are a type of neural network architecture designed for various image and signal processing tasks. Especially for Image-Generation. Control Nets, in this context, provide a mechanism to guide the diffusion process, improving the model's ability to generate and refine outputs.

### Key Features
Enhanced Image Processing: Diffusers with Control Nets are particularly effective in image denoising, inpainting, and super-resolution tasks.

Guided Diffusion: Control Nets allow for more precise control over the diffusion process, leading to higher quality and more accurate results.

### Implementation Details
This project provides some test use cases which are implemented uses Control Nets with diffusers. It includes sample code for integrating Control Nets into existing diffuser models.

## Project 3: Running MLFlow server/UI on Google colab
utilities/examples_MLFlow_InColab_with_NGROK
### Overview
This projects focused on running mlFlow in a Colab Notebook and make the UI endpoint accessible from outside of Google Colab.

### Key Features
Run MLFlow UI and use NGROK to publish the endpoint so that your MLFLow Service is accessible through the internet.

###  Implementation Details
This project makes use of NGROK. see  ngrok.com for more details



