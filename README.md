# Nonlinear Multiclass Classification with PyTorch - A Typical Workflow
a typical workflow for a nonlinear multi-class classification with PyTorch

In this article, we'll have a look at a typical workflow for a simple nonlinear multiclass classification problem. We'll keep things simple.

## Contents:

### Data Preparation
We'll use custom code to create some nonlinear multiclass data.

![image](https://github.com/user-attachments/assets/dd7e1f85-1a2a-48c4-a9e5-5b8a229b1cc8)

### Model Building
We have the data in place, it's time to build a model. Besides the model, we'll define a loss function and optimizer.

![image](https://github.com/user-attachments/assets/788e52d0-ae21-4394-9c2a-35375755e7b2)

### Model Training
Training the model involves two loops: a training loop, where the model learns the relationships between the features and labels, and a testing loop, where the model is evaluated.

![image](https://github.com/user-attachments/assets/63ecc945-20d5-4ad0-bf5e-42301ba4c807)

### Model Evaluation
Let's evaluate the model and see how it performs on data it never saw.

![image](https://github.com/user-attachments/assets/9796eb9e-cb37-48bd-b19f-c137d5cdbea5)
