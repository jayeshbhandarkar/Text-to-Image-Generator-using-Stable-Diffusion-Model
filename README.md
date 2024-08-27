# Text-to-Image and Multilingual Text-to-Image Generator using Stable Diffusion Model

## Project Overview
This repository contains two Notebooks: MultilingualTextToImageGenerator.ipynb and TextToImageGenerator.ipynb. These notebooks demonstrate how to generate images from text inputs using various machine learning libraries and models, including Stable Diffusion and Google Translate for multilingual support.

### 1. MultilingualTextToImageGenerator.ipynb
This notebook allows users to input text in multiple languages and generates corresponding images. The process involves translating the text into English using the googletrans library and then using a text-to-image model to create images.

### 2. TextToImageGenerator.ipynb
This notebook focuses on generating images from English text inputs directly without translation. It utilizes advanced deep learning models to interpret the text and create detailed images.

## Dependencies
The notebooks use the following libraries and packages:

- googletrans
- Translator
- Path
- tqdm
- torch
- pandas
- numpy
- StableDiffusionPipeline
- diffusers
- transformers
- pipeline
- matplotlib
- cv2

## Installation
To run these notebooks, you need to install the required libraries. You can install them using pip command:

```
   pip install googletrans tqdm torch pandas numpy diffusers transformers matplotlib cv2
```

## Usage

`STEP 1` - Clone the repository:
```
  git clone https://github.com/jayeshbhandarkar/MultilingualTextToImageGenerator.git
  cd MultilingualTextToImageGenerator
```

```
  git clone https://github.com/jayeshbhandarkar/TextToImageGenerator.git
  cd TextToImageGenerator
```
----
`STEP 2` - Install the required libraries (if not already installed).

----
`STEP 3` - Open Google Colab and run the project.

---
`STEP 4` - Follow the instructions within the notebooks to input text and generate images.

---

#### Note : Use your own hugging face api key.

## License
This project is licensed under the [MIT License](LICENSE).

⬤ Please do ⭐ the Repository, if it helped you in anyway.
