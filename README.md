# Deep_Learning_and_Human_Data

Course unit contents:

Part I – Introduction (2 hours)
- Intro: course outline, graduation rules, office hours, etc.
- Applications: health, activity-aware services, security and emergency management, authentication systems, analyzing human dynamics, natural language processing

Part II – Vector Quantization (18 hours)
- Vector quantization (VQ):
--- Aims, quality metrics
--- Clustering 1: K-means, soft K-means, Expectation Maximization (EM)
--- Clustering 1: X-means, DBSCAN (density based clustering)
- Unsupervised VQ algorithms:
--- Self-Organizing Maps (SOM), Gas Neural Networks (GNG): theory and algorithms
- Application to quasi-periodic biometric signals (ECG):
-- Signal pre-processing, normalization, segmentation
--- Dictionary learning: concepts, architectures
--- Efficient representation of ECG signals: description of state-of-the-art algorithms
--- Unsupervised dictionary designs for ECG via GNG-based dictionaries
--- Final system design and numerical results

Part III - Deep Neural Networks (16 hours)
- Review: gradient descent and general concepts (supervised learning, overfitting, cost models, etc.)
- Review: Feed Forward Neural Networks: models, training, back-propagation
- Convolutional Neural Networks (CNN): structure, description of constituting blocks, training, batch normalization
- Autoencoder architectures for unsupervised feature extraction
-- denoising autoencoders
- Recurrent neural networks (RNN) for the analysis of temporal sequences. Example: natural language processing
- Residual convolutional neural networks (ResNets)
- Attention mechanisms for CNN (images) and RSS (temporal sequences). Training mechanisms and application examples (e.g., text translation models)
- Transformer architectures: step-by-step explanation of the working principles and of the main constituting blocks, training methods, application examples and trends

Part IV: Laboratory classes (12 hours)
In the laboratory classes the students will go through a guided tour through the construction of Python code for neural networks, writing all the building blocks related to: the creation of the neural network structure and its training using several gradient descent-based algorithms. The students will be exposed to Python programming, including the use of the Keras and TensorFlow frameworks for the implementation and training of neural network structures. The software composing the different blocks of the presented neural network architectures will be pre-written and checked for correctness, so that the students, after attempting to implement their own version of it, will succeed to combine the various blocks and complete the assigned task. Upon connecting the blocks into the selected neural network architecture, the obtained neural network models will be trained using several gradient descent algorithms, and tested against selected and real datasets. The topics that will be covered are:

- Introduction to Python programming
- Feed forward neural networks
- Convolutional neural networks (CNN)
- Recurrent Neural Networks (RNN)
- Advanced mechanisms (implementation): batch normalization, residual networks (ResNets), autoencoders, inception layers



Exam: development of a project and its report 
