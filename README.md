# E-Commerce Product Classifier
A pipeline that classifies product images into 50 different e-commerce categories (see below). The project includes a custom web scraper that collected 12,500+ product images across the categories ranging from electronics to home goods, followed by fine-tuning Google's Vision Transformer (ViT) model to achieve 95%+ classification accuracy.

Built using PyTorch and Transformers for deep learning, and BeautifulSoup for web-crawling.

## 50 Categories
![alt text](https://github.com/khayreali/ecommerce-product-classifier/blob/main/categories.png "Logo Title Text 1")

## Notes 
Copy `.env.template` to `.env` and add your Hugging Face API token. This is needed to pull in the Google transformer model, or the model of your choice.
As code is all in notebook, no install needed from your terminal. Just run the notebook.

## Model Performance
**Training Accuracy**: ~97%
**Test Accuracy**: ~97%
**Training Time**: ~With A100GPU, it takes two hours to crawl for pictures, three hours for image processing, and and additional three hours to train A100 GPU. It's a lengthy pipeline, with room for improvement, but duration is 
