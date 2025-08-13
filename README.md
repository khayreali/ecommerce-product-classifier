# E-Commerce Product Image Classification

## Project Overview
A ML pipeline that classifies product images into 50 different e-commerce categories. The project includes a custom web scraper that collected 12,500+ product images across categories ranging from electronics to home goods, followed by fine-tuning Google's Vision Transformer (ViT) model to achieve 95%+ classification accuracy.
Built using PyTorch and Transformers for deep learning, and BeautifulSoup for web-crawling.

## 50 Categories
!(ecommerce-product-classifier/categories.png)
## Setup & Usage
1. Clone the repository
2. Copy `.env.template` to `.env` and add your Hugging Face API token. This is needed to pull in the Google transformer model, or the model of your choice.
3. As code is all in notebook, no install needed from your terminal. Just run the notebook.

## Model Performance
- **Training Accuracy**: ~
- **Test Accuracy**: ~
- **Training Time**: ~ hours on A100 GPU
