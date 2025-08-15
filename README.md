# How Hidden Layer Size Shapes Neural Network Performance

This project explores **Fully Connected Neural Networks (FCNNs)** by analyzing their structure and evaluating their performance on the **MNIST dataset**.

---

## Objective
- Quantify how network architecture impacts parameter growth.  
- Evaluate how varying hidden-layer width influences accuracy and loss.  
- Provide practical guidance on balancing model complexity, generalization, and efficiency.  

---

## Methodology

### Part 1 — Architecture Analysis
- Defined sample FCNN architectures in Keras (`Dense` layers with ReLU/Softmax).  
- Calculated neurons, weights, biases, and total parameters layer by layer.  
- Highlighted how design choices directly affect parameter scale.  

### Part 2 — MNIST Experiment
- Trained single-hidden-layer MLPs with hidden sizes: `[1, 5, 10, 20, 50, 100, …]`.  
- Evaluated models over multiple runs to average results.  
- Plotted performance metrics (accuracy and loss) against hidden size.  

---

## Results

### Example Network Architecture
<img width=45% height=40% alt="image" src="https://github.com/user-attachments/assets/954d7d73-2d35-429b-a06d-2237b343c053" />
<img width=45% height=40% alt="image" src="https://github.com/user-attachments/assets/feea1d85-3252-4ac7-8323-a55804bc82cf" />


### Accuracy vs Neurons | Loss vs Neurons
<img width=90% height="470" alt="image" src="https://github.com/user-attachments/assets/0b634cef-feb0-48cf-b26b-0ac4192c23d4" />


---

## 🔍 Key Insights
- Parameter counts scale rapidly with hidden size.  
- Accuracy improves with more neurons but shows diminishing returns.  
- Very wide networks risk overfitting.  
- Choosing the right hidden-layer size is a balance between accuracy, generalization, and efficiency.  

---

## How to Run
Run in **Google Colab** (no setup needed):  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nipun-taneja/fcnn-mnist-analysis/blob/main/FCNN_MNIST_Project.ipynb)

---

## ✍️ Author
Nipun Taneja – MS in Artificial Intelligence @ SFSU  
[LinkedIn](https://www.linkedin.com/in/nipun-taneja) | [GitHub](https://github.com/nipun-taneja)
