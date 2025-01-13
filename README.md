# TimmWrapper Examples with 🤗 Transformers 🚀

This repository contains a collection of **Jupyter Notebooks** demonstrating how to use `TimmWrapper` from the 🤗 `transformers` library to integrate **timm models** effortlessly. The notebooks cover a wide range of use cases, including pipelines, quantization, fine-tuning, LoRA, and model compilation.

## Notebooks Overview 📚  

| **Notebook**         | **Description**                                          |
|----------------------|----------------------------------------------------------|
| `#01_pipelines.ipynb` | Use **pipeline API** with any `timm` model.              |
| `#02_auto_class.ipynb` | Explore **Auto Classes** to load `timm` models easily.  |
| `#03_quantization.ipynb` | Apply **8-bit quantization** for efficient inference. |
| `#04_sft.ipynb`       | Perform **supervised fine-tuning** with the Trainer API. |
| `#05_sft_lora.ipynb`  | Fine-tune using **LoRA adapters** for efficient training.|
| `#06_use_lora.ipynb`  | **Load and use LoRA fine-tuned models** for inference.   |
| `#07_compile.ipynb`   | Speed up inference using **`torch.compile`**.            |

## **How to Get Started** 🛠️  

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/timmwrapper-examples.git
   cd timmwrapper-examples
   ```

2. **Install required packages**:
   ```bash
   pip install -U transformers timm gradio bitsandbytes
   ```

3. **Run the notebooks**:
   ```bash
   jupyter notebook
   ```

## What's Covered? 🤖  

- ✅ Using **`TimmWrapper`** with the **pipeline API** for image classification.  
- ✅ Loading models with **Auto Classes**.  
- ✅ Applying **8-bit quantization** with `bitsandbytes`.  
- ✅ **Fine-tuning** using the Trainer API.  
- ✅ Efficient training with **LoRA** adapters.  
- ✅ Speeding up inference with **`torch.compile`**.


## Example Models on Hugging Face Hub 🧩  

[Hugging Face Collection](https://huggingface.co/collections/ariG23498/timmwrapper-6777b85f1e8d085d3f1374a1)

| **Model**                                                   | **Description**           |
|-------------------------------------------------------------|---------------------------|
| [vit_base_patch16_224_food101](https://huggingface.co/ariG23498/vit_base_patch16_224.augreg2_in21k_ft_in1k.ft_food101) | Fine-tuned on Food101.     |
| [vit_base_patch16_224_lora_food101](https://huggingface.co/ariG23498/vit_base_patch16_224.augreg2_in21k_ft_in1k.lora_ft_food101) | LoRA fine-tuned version.   |


## Contributions 🤝  
Feel free to open issues or submit pull requests if you have suggestions or improvements!

Note: This README was created with the help of ChatGPT 4.
