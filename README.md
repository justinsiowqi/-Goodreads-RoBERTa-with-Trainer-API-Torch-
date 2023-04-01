# 📗 Goodreads: RoBERTa with Trainer API (Torch)

## Use Book Reviews to Predict Ratings

<div align="center">
    <img src="https://raw.githubusercontent.com/justinsiowqi/-Goodreads-RoBERTa-with-Trainer-API-Torch-/main/BERT.png" alt="Sesame Street" style="width: 500px;"> 
</div>
<div align="center">
  © Sesame Street (1969 TV Series)
</div>

<div>
    
&nbsp;
    
Welcome back to Part 2 of the series! 

In the [previous notebook](https://www.kaggle.com/code/justinsiow/goodreads-distilbert-automodel-tensorflow), we used the HuggingFace transformers library to predict book ratings. Specifically, we created a **DistilBERT** AutoTokenizer and AutoModel and achieved an accuracy of **0.56808**. 

In this notebook, we will take advantage of two other HuggingFace libraries (**datasets** and **evaluate**) to process the data and evaluate the model's performance. Instead of using the DistilBERT model, we will use a bigger model called **RoBERTa** and train it using the **Trainer API**. By increasing the amount of training data twofold, we managed to get a better accuracy of **0.59792**.

## Getting Started

These steps will guide you in running the project on your own computer.

### Prerequisites

* Python 3.10.8

### Installing

```
install datasets
install evaluate
install pandas
install numpy
install torch 
install transformers
```
