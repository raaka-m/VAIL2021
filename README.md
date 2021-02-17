# VAIL2021

Responses

Day 1 (2/8/2021)

I hope to learn more about machine learning and data analytics/visualization through VAIL. Additionally, I hope to gain more exposure to different industries, job pathways, and learn from speakers. Above all, I hope to connect with a network of like-minded students and inspiring mentors!

Day 2 (2/9/2021)
1. Supervised learning is when a computer is able to create a function h(x) based on training data; then, it uses that function on another set of data. On the other hand, unsupervised learning is when a computer must find patterns and correlations on its own using a particular set of data.
2. The statement "Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries" is FALSE. Scikit-Learn is built on top of these common data and math libraries.

Day 3 (2/10/2021)

1. Tensors are a mathematical representation of a physical entity that may be characterized by magnitude and multiple directions. They are a generalization of a matrix that can be represented using multi-dimensional arrays. We can manipulate them using different operations. They are ranked based on their dimensions.
2. When you compile in TensorFlow, you define a loss function, an optimizer, and a metric.

Day 4 (2/11/2021)

Dataset: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia
Problem: Recently, numerous studies have shown that AI and ML models have higher accuracy at diagnosing patients than doctors. However, there need to be specific algorithms
and models developed for each condition/disease/etc. and their respective diagnostic tools which is extremely time consuming.
Solution: We should develop a solution that can help those in the healthcare industry with diagnoses by creating our own deep learning algorithm. Specifically, we want to develop a CNN that can correctly classify x-rays of patients with pneumonia. We chose a CNN because they are strong at image recognition and is ideal for processing 2D images.

Citations: 
https://towardsdatascience.com/ai-diagnoses-disease-better-than-your-doctor-study-finds-a5cc0ffbf32

Day 5 (2/12/2021)

The code is in the repository.

Day 8 (2/15/2021)

The code is in the repository.

Day 9 (2/16/2021)
1. I think AI and ML concepts were used to mimic the way I picked candidates. Then, the game used this algorithm to pick sample candidates after the process became automated.
2. An example of a biased ML model is facial recognition technology. Many reports have demonstrated that the recognition software is more inaccurate for POC, women, children, and the elderly. My suggestion to improving this is using more data from more types of people to train the technology. Additionally, hiring a more diverse set of individuals who can help change the technology will reflect in the potential reduction of bias in the technology. I picked this technology because the implications of this technology being biased are severe. Police have been using this technology to identify individuals. If the technology is inaccurate, POC, women, children, and elderly are more at risk for being inaccurately identified and having their lives being completely uprooted.

Day 10 (2/17/2021)

There are differences between fully connected neural networks and convolutional neural networks in the context for image recognition. 

Fully Connected Neural Networks: Images are a large input for a neural network; this requires a huge number of connections and network parameters.
Convolutional Neural Networks: utilize the smaller details of an image. Uses these details to analyze each feature individually, which is used to make decisions about the whole image. Additionally, the CNN has a fully connected layer between the convolution/pooling layers and the classification decision.

CNN Layers:

Convolutional: scans a few pixels, creates a feature map, predicts the classification of each feature
Pooling layer: reduces information in each feature which retaining most important information 
*Note: there are usually several rounds of the aforementioned steps*
Fully connected input layer: uses output and puts them into a format (single vector) that can be used for the next stage.
First fully connected layer: applies weights to features to predict correct classification
Fully connected output layer: final probabilities for each classification

Applications of Fully Connected Neural Networks and CNNS:

CNN: Image recognition
Fully Connected Neural Network: Deep learning
