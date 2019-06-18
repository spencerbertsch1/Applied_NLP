# Applied_NLP

Applications of Natural Language Processing - Spring 2019, Tuck School of Business

<img width="300" alt="ml_img" src="https://venturebeat.com/wp-content/uploads/2018/09/natural-language-processing.jpg?fit=400%2C283&strip=all">

[Image source](venturebeat.com/wp-content/uploads/2018/09/natural-language-processing.jpg?fit=400%2C283&strip=all)

This reposityry contains ipython notebooks detailing many applications of natural language processing from simpler scripts relating to dependency parsing to recurrent neural networks used for text generation. It should be noted that I (Spencer) am not the author of the vast majority of the code within these ipython notebooks - they were written by [Professor Dean Alderucci](https://biography.omicsonline.org/united-states-of-america/the-university-of-chicago-booth-school-of-business/dean-alderucci-422234), [LinkedIn](https://www.linkedin.com/in/deanalderucci/). Professor Alderucci was not only a brilliant professor and a great lecturer, but helped all members of this course - inside and outside of class - learn how to construct clean NLP pipelines in modern data environments. 

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

* Web Scraping
  * [Scrape the SEC Webpages for 10-Ks](https://github.com/spencerbertsch1/Applied_NLP/blob/master/Web_Scraping/Class_1_Scrape_SEC_Pages.ipynb)
  * [Scraping the Tuck Factuly Page](https://github.com/spencerbertsch1/Applied_NLP/blob/master/Web_Scraping/Class_1_Scrape_web_pages.ipynb)

* Dependency Parsing
  * [Single Sentence Dependency Parse](https://github.com/spencerbertsch1/Applied_NLP/blob/master/Dependency%20Parsing/Class_1_Dependency_Parse.ipynb)
  
* Named Entity Recognition (NER) 
  * [NER Example](https://github.com/spencerbertsch1/Applied_NLP/blob/master/Named%20Entity%20Recognition/Class_2_NER.ipynb)

* POS TAgging
  * [POS Tagging and Frequency ANalysis](https://github.com/spencerbertsch1/Applied_NLP/blob/master/POS%20Tagging/Parts_of_Speech.ipynb)
  
* Regular Expressions
  * [Regular Expressions for Online Reviews](https://github.com/spencerbertsch1/Applied_NLP/blob/master/Regualr_Expressions/Class_1_Hotel_reviews_and_regular_expressions.ipynb)
  
* Text Generation
  * [Shakespeare Text Generator](https://github.com/spencerbertsch1/Applied_NLP/blob/master/Text%20Generation/Class_4_Text_Generator_Shakespeare.ipynb)
  * [Review Text Generator](https://github.com/spencerbertsch1/Applied_NLP/blob/master/Text%20Generation/Week_4_Text_Generator_Hotel.ipynb)
  
