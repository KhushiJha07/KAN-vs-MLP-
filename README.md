

**README**

 Machine Learning vs. KAN 

**Description:**

This repository contains code for comparing the performance of traditional machine learning algorithms and Kolmogorov Arnold Networks (KANs) on four different classification datasets:

1. **MNIST Handwritten Digits:** Classification of handwritten digits (0-9).
2. **Flower Species:** Classification of different flower species (e.g., Iris, etc.).
3. **Heart Disease:** Prediction of heart disease presence/absence.
4. **Skin Infection:** Classification of different skin infection types.


Kolmogorov-Arnold Networks (KANs) are promising alternatives of Multi-Layer Perceptrons (MLPs). KANs have strong mathematical foundations just like MLPs: 
MLPs are based on the universal approximation theorem, while KANs are based on Kolmogorov-Arnold representation theorem. KANs and MLPs are dual: KANs have activation functions on edges, 
while MLPs have activation functions on nodes. This simple change makes KANs better (sometimes much better!) than MLPs in terms of both model accuracy and interpretability. 

In simple words : you have to manually decide a activation function for MLPs at each layer while the optimizer learns the best possible values of weights(w) and biases(b) for your network , 
                  but in KAN networks the model can automatically learn the best possible activation function to be used at each layer . 

link for official pykan github repo : [https://github.com/KindXiaoming/pykan](https://github.com/KindXiaoming/pykan)  


**License:**
MIT License

Copyright (c) 2024 Ziming Liu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



