---
layout: homepage
---

## About
I’m a PhD student in Artificial Intelligence. My research focuses on making deep learning models more trustworthy and reliable. I want to ensure that the models I train solve the actual problem, not just find shortcuts in the data. To achieve this, I explore different approaches, such as designing neural networks that are easier to interpret, measuring how certain models are in their predictions, and using special layers to guide the model's output.

## Education
- Ph.D., Artificial Intelligence |	*(Ongoing)*
- M.S., Computer Science&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;*(Greatest Distinction)*
- B.S., Applied Information Technology |	*(Great Distinction)*



## Work Experience

### AI Researcher @ Antwerp University (2023 - Ongoing)

- Research in self-supervised learning, focusing on generative models and models designed for easier interpretability. Within one year, I submitted two main-author AI research papers to top-tier venues (one fundamental and one applied).
- Teaching the lab sessions for Artificial Intelligence, Artificial Neural Networks, Numerical Linear Algebra,  Advanced Programming in C++, and Distributed Systems.

###  Mathematics Tutor @ BijlesHuis (2022 - Ongoing)

- Part-time tutoring of mathematics at different levels... from high school to university.

### Computer Vision Research Engineer @ Puratos (2022, Internship)

- Automatically measure bread porosity through conventional image segmentation.
<p align="center">
	<img src="assets/image-20240928005412193.png" alt="image-20230613111315897" style="zoom:45%;" />
</p>



### Data Engineer @ Achmea (the Netherlands) (2020, Internship)
- I created a machine learning pipeline that allows employees to quickly build their own machine-learning models  (Similar to AutoML). 
- The developed product includes a web application where users can annotate image data and train new models. 
- Several evaluation techniques have been implemented to assess the models. When a model does not perform satisfactorily, the web application automatically generates advice on how to improve model performance.

<p align="center">
	<img src="assets/stack.png" alt="image-20230613111315897" style="zoom:85%;" />
</p>

Grade: 16/20
Technologies:

- Machine Learning: Python, TensorFlow, Keras, YOLOv3
- Software development: Angular, .NET CORE, Azure Services (e.g. Azure Databricks, Azure Blob Storage)




## Projects

### Smooth InfoMax - Research paper on neural networks that are better interpretable by design.
Deep Neural Networks are inherently difficult to interpret, mostly due to the large numbers of neurons to analyze and the disentangled nature of the concepts learned by these neurons. Instead, I propose to solve this through interpretability constraints to the model, allowing for easier post-hoc interpretability. 
<p align="center">
	<img src="https://github.com/fdenoodt/Smooth-InfoMax/raw/main/assets/image-20230613111315897.png" alt="image-20230613111315897" style="zoom:30%;" />
</p>
- [Publication](https://arxiv.org/abs/2408.12936).
- [GitHub](https://github.com/fdenoodt/Smooth-InfoMax)

### Image colorization - Paper implementation
For a school group assignment, 2 fellow students and I implemented an image colorization model using PyTorch, based on the paper "Colorful Image Colorization" by Richard Zhang, Phillip Isola, and Alexei A. Efros. The paper proposes a method for converting grayscale images to color using an autoencoder-based Neural Network.

The images below show some of our results; **row 1:** ground truth images, **row 2:** grayscale images serving as input, and **row 3:** model predictions. It seems to work quite well.
<p align="center">
	<img src="assets/image-20230119140203674.png" alt="image" style="zoom:30%;" />
</p>
[Report](https://github.com/WardGauderis/Image-Colourisation/blob/main/report.pdf), [GitHub](https://github.com/WardGauderis/Image-Colourisation)

### Pokémon Generator based on Transfer Learning

For a computational creativity assignment, I generated fake Pokémon images using the open-source text-to-image model ruDALLE. I fine-tuned the model on images of a specific Pokémon type and also used the pretrained weights to generate outlines of Pokémon sketches. The generation of the names was also automated; the creative system took a few input words, made some permutations, and selected the best permutation, evaluated using a linear classifier trained on Pokémon names. The linear classifier then ranked the generated names and selected the most plausible option.

<p align="center">
	<img src="assets/image-20221226162855553.png" alt="image" style="zoom:30%;" />
</p>
[Report](./pokemon_character_design.pdf)

### Image recognition alarm
Because waking up can be hard, I made a smart alarm to help me out. The alarm contains a camera that is pointed at my bed and detects when I sleep. When it is time to wake up, the alarm continues to play music while I stay in bed. Only when I walk out of bed, the alarm will stop. The alarm consists of a Raspberry Pi, a camera, and speakers. The front end is developed in `Angular`.

The Artificial Neural Network consists of a convolutional neural network developed in `python` using the `Keras` library.  
<p align="center">
	<img src="assets/image-20221226150245847.png" alt="image" style="zoom:30%;" />
</p>
[GitHub](https://github.com/oBoii/alarm)

### Two genetic algorithms for solving the Traveling Salesmen Problem 
The methods consist of **a conventional selection-mutation-crossover approach** and a more **research-oriented approach** based on gradient-descent-based for discrete domains. The second is done by extending the Plackett-Luce model with a new probability representation, defined as a first-order Markov chain, as shown below:
<div style="text-align: center;">
<img src="assets/image-20240910204235783.png" alt="equation" width="350"/>
</div>
While the equations may look fancy, it doesn't really work that well in practice (that's the downside of building upon less-established methods I guess 😅).

[Report](https://github.com/fdenoodt/evolution-assignment-2023-indiv/blob/main/text_indiv/r0698535_final.pdf), [GitHub](https://github.com/fdenoodt/evolution-assignment-2023-indiv)


### SVM Kernel Experiment

For this school group project, we were tasked to come up with three research questions and investigate them. One of the questions we focused on involved comparing the capability of different kernels in **support vector machines (SVM)** on non-linearly separable data. Specifically, the radial basis function (RBF), the polynomial, and the linear kernel were compared on a synthetic two-dimensional dataset. Given the image below, it appears that the RBF does best.
<p align="center">
	<img src="assets/image-20221226154655480.png" alt="image" style="zoom:30%;" />
</p>
[GitHub](https://github.com/WardGauderis/SFML)



### Wine temperature forecasting
A research project with a real business case for a real company (QelviQ), where the goal was to predict the optimal temperature for wine bottles based on their labels. The project was divided into three main modules: a computer vision module to extract text from the bottle labels, a data interpretation module that transformed the raw text into meaningful knowledge, and a temperature prediction module that used this information to predict the exact temperature. I worked on the data interpretation module, which involved extracting features such as the bottle name, year, wine name, and the regions of the included ingredients.


### Kaggle competition - Appliances regression
I completed a machine learning project where I used regression techniques to predict the energy consumption of appliances in a house. I experimented with different regression models such as **linear regression**, **decision trees**, **boosting regression**, and **support vector regression**. I also went through the full machine learning pipeline, including data visualization, data preprocessing, cross-validation for time series data, feature engineering, and model training with parameter tuning. 
<p align="center">
	<img src="assets/image-20240910000816399.png" alt="image" style="zoom:30%;" />
</p>
[GitHub](https://github.com/fdenoodt/machine-learning-challenge/blob/master/PROJECT.ipynb)

