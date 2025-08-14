# E-Commerce Product Image Classification

## Project Overview
A pipeline that classifies product images into 50 different e-commerce categories (see below). The project includes a custom web scraper that collected 12,500+ product images across the categories ranging from electronics to home goods, followed by fine-tuning Google's Vision Transformer (ViT) model to achieve 95%+ classification accuracy.

Built using PyTorch and Transformers for deep learning, and BeautifulSoup for web-crawling.

## 50 Categories
!(ecommerce-product-classifier/categories.png)

## Setup & Usage
1. Clone the repository
2. Copy `.env.template` to `.env` and add your Hugging Face API token and Decodo auth.
3. As code is all in notebook, no install needed from your terminal. Just run the notebook.

## Model Performance
- **Training Accuracy**: 97%
- **Test Accuracy**: 97%
- **Training Time**: It takes two hours to crawl for pictures, three hours for image processing, and and additional three hours to train A100 GPU.