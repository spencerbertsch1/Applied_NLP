# Applied_NLP

Applications of Natural Language Processing - Spring 2019, Tuck School of Business

<img width="300" alt="ml_img" src="https://venturebeat.com/wp-content/uploads/2018/09/natural-language-processing.jpg?fit=400%2C283&strip=all">

[Image source](venturebeat.com/wp-content/uploads/2018/09/natural-language-processing.jpg?fit=400%2C283&strip=all)

This reposityry contains ipython notebooks detailing many applications of natural language processing from simpler scripts relating to dependency parsing to recurrent neural networks used for text generation. It should be noted that I (Spencer) am not the author of the vast majority of the code within these ipython notebooks - they were written by [Professor Dean Alderucci](https://biography.omicsonline.org/united-states-of-america/the-university-of-chicago-booth-school-of-business/dean-alderucci-422234), [LinkedIn](https://www.linkedin.com/in/deanalderucci/). Professor Alderucci was not only a brilliant professor and a great lecturer, but helped all members of this course inside and outside of class learn how to construct clean NLP pipelines in modern data environments. 

## Dependencies

The projects in this repository use a variety of machine learning and deep learning labraries and python packages. In order to run most of the code, you will need to have the current version of Tensorflow installed on your machine. Other important depedencies include Pandas, Numpy, [beautifulsoup4](www.crummy.com/software/BeautifulSoup/) and Matplotlib.

## For MacOS 
Simply open a command window and run the following commands to install the necessary libraries. 

1. Run `pip install --upgrade tensorflow` to make sure your version of TensorFlow is up to date
2. If you're not using a virtual environment, Run: `sudo pip install keras` <br> 
If you're using a virtual environment, Run: `pip install keras` 
3. Run `pip3 install Pandas` 
4. Run `pip3 install numpy` 
5. Run `pip3 matplotlib` 

If there are any other packages not installed when the code is run, simply call python in the terminal to install the necessary packages. 

# NLP Projects

* Simple NLP Analysis
  * [NBA Winner Prediction - PyTorch](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Dense_Fully_Connected_NN/PyTorch/NBA_Example_Feedforward.ipynb)
  * [NBA Winner Prediction - T.F. Keras](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Dense_Fully_Connected_NN/TensorFlow/NBA_Example_DenseNN.ipynb)
  * [Regularization - Mushroom Toxicity](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Regularization/PyTorch/Regularization_Techniques.ipynb)
  * [XOR Example](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Dense_Fully_Connected_NN/XOR/XOR_PyTorch.ipynb)

* Optimization and Regularization 
  * [Mushroom Toxicity Example](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Regularization/PyTorch/Regularization_Techniques.ipynb)
  * [Breast Histology Classification](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Convolutional_Neural_Networks/Breast_Historology_Img_Analysis/Breast_Histology_Classification.ipynb)
  
* Convolutional Networks 
  * [MNIST Classification with 2D ConvNet](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Convolutional_Neural_Networks/MNIST/MNIST_Script.ipynb)
  * [Breast Histology Classification with 3D ConvNet](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Convolutional_Neural_Networks/Breast_Historology_Img_Analysis/Breast_Histology_Classification.ipynb)

* Recurrent Networks 
  * [Sine Wave Prediction](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Recurrent_Neural_Networks/Sine_Wave_Prediction/Sine_Wave_Prediction_RNNs.ipynb)
  * [Naive Stock Market Data Prediction](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Recurrent_Neural_Networks/AAPL_Stock_Prediction/RNN_Finance_Application.ipynb)
  * [Slide Deck - Vanishing and Exploding Gradients](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Recurrent_Neural_Networks/AAPL_Stock_Prediction/Simple%20stock%20prediction%20ecercise.pdf)
  
* Autoencoders
  * [Simple MNIST Autoendocer](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Autoencoders/Simple%20Autoencoder%20Experiments.ipynb)
  
* Final Project - Optimizing Seq2seq Translator 
  * [Optimization notebook](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Final_Project/Translator-PyTorch/Optimized_Seq2seq_Translator.ipynb)
  * [Final slide deck](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Final_Project/RNNs%20Final%20Project%20Presentation.pdf)
  * [Final Paper](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/Final_Project/Optimization_of_Encoder_Decoder_Model_Bertsch.pdf)

* Just for fun! 
  * [TensorFlow.js Model Approximation](https://github.com/spencerbertsch1/Applied-Deep-Learning-ENGG192/blob/master/TensorFlow.js/UserInput_Model/user_input_model.html)
