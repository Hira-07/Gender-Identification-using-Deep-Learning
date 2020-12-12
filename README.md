# Gender Identification using Deep Learning
All the coding Scripts here are from the book **[Natural Language Processing with Deep Learning](https://ilmoirfan.com/natural-language-processing-with-deep-learning/ "Named link title")** . To see in details how model works step by step please [refer](https://ilmoirfan.com/natural-language-processing-with-deep-learning/ "Named link title"). <br/>
In these scripts I have used Sample "English Quote Text" data of 50 insatances. I split the dataset in train, test and validation. The results generated here are spurious you can train the model on real world larger datsets to get authentic results.
### Getting Started
* Before running the code: Set variable ***drive_path*** value according to your folder path e.g.  ***drive_path = '/content/drive/My Drive'  <br/>***
* Create a folder named *#Data* having train, test and validation data files. Your data files must be in csv format.

* **Install required libraries:** <br/><br/>

Install PyTorch
<pre><code>pip install torch
</code></pre> 

Install TorchText  
<pre><code>pip install torchtext
</code></pre> 

Install Spacy
<pre><code>python -m spacy download en
</code></pre><br/>


**1.Gender Identification using RNN [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hira-07/Gender-Identification-using-Deep-Learning/blob/master/Gender%20Identification%20using%20RNN.ipynb)** <br/>

**2.Gender Identification using BI RNN [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hira-07/Gender-Identification-using-Deep-Learning/blob/master/Gender%20Identification%20using%20BI%20RNN.ipynb)** <br/>

**3.Gender Identification using LSTM [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hira-07/Gender-Identification-using-Deep-Learning/blob/master/Gender%20Identification%20using%20LSTM.ipynb)** <br/>

**4.Gender Identification using BI LSTM [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hira-07/Gender-Identification-using-Deep-Learning/blob/master/Gender%20Identification%20using%20BI%20LSTM.ipynb)**
