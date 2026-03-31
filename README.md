# Projet_06_OCR_Data_Scientist

# Automatic Consumer Goods Classification

## Overview

This project explores how to automatically classify consumer products from marketplace data using both **text** and **images**.

The work combines exploratory NLP, image-based analysis, supervised deep learning with transfer learning, and a small API extraction step to illustrate how external data can enrich a product catalog.

---

## Dataset

The project uses a sample e-commerce dataset based on **Flipkart** product data, including:
- product titles
- product descriptions
- category labels
- and associated product images

The text notebook explicitly works on the file `flipkart_com-ecommerce_sample_1050.csv` and linked product images.

---

## Method

The workflow of the project was:

1. study the feasibility of classification from **text data**
2. preprocess product descriptions with standard NLP cleaning
3. compare text representations such as **Bag of Words**, **TF-IDF**, and embedding-based approaches
4. study the feasibility of classification from **images**
5. build a supervised image classifier with **CNN transfer learning**
6. test an external API extraction example to collect complementary product-related data

---

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- Gensim
- Transformers
- TensorFlow / Keras
- Requests
- Jupyter Notebook

---

## Repository Structure

```bash
.
├── notebooks/
│   ├── 0_text_feasibility analysis.ipynb
│   ├── 1_images_feasibility analysis.ipynb
│   ├── 2_images_supervised_classification.ipynb
│   └── 3_extraction_by_API.ipynb
├── 4_extraction_API_102024.csv
├── 5_presentation_102024.pdf
└── README.md
```

---

## Main Takeaways

This project helped me practice:

- text preprocessing for NLP
- exploratory clustering for classification feasibility
- image-based classification workflows
- transfer learning with CNNs
- and basic API-based data extraction

It was also a good introduction to multimodal product classification.

---

## Limitations

This project has a few important limitations:
- the dataset is relatively small
- the work remains partly exploratory
- and the image/API parts could be pushed further for production use

A natural next step would be to build a more robust multimodal classifier combining text and image features in a single pipeline.

---

## Author

**Jérôme Le Gal**  
Data Science student
