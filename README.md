AutoML is and apply automatic machine learning to a business analytics problem with the H2O AutoML interface in Python. H2O's AutoML automates the process of training and tuning a large selection of models, allowing the user to focus on other aspects of the data science and machine learning pipeline such as data pre-processing, feature engineering and model deployment.

For a brief introduction to AutoML, please take a few minutes to read ![The different flavors of AutoML](https://www.h2o.ai/blog/the-different-flavors-of-automl/) by ![Erin LeDell](https://dlab.berkeley.edu/people/erin-ledell), the Chief Machine Learning Scientist at H2O.ai. For a more detailed coverage of H2O's AutoML, I encourage you to read Parul Pandey's fanastic ![Deep Dive Into H2O's AutoML](https://www.h2o.ai/blog/a-deep-dive-into-h2os-automl/). ![Parul ](https://medium.com/@parulnith) is a data scientist at H2O.ai and the First Indian Woman Kaggle Grandmaster in the Kernel Category!


## Who is H2O.ai?
H2O.ai company aims to create open-source machine learning products to make machine learning accessible and allow users to extract insights from data, without needing expertise in deploying or tuning machine learning models. They provide a range of products like 

**H2O:** This is an open-source, memory inclusive and distributed machine learning platform to build supervised and unsupervised machine learning models. It also includes a user-friendly UI platform called Flow where you can create these models. 

**Sparkling water:** This platform is an integration of Spark and H2O for existing Spark ecosystem users to build their models. 

**Deepwater:** Deepwater is an integration of H2O with Tensorflow, Caffe and MXNet. They are used to work on GPU based models used in deep learning and reinforcement learning. 

**Steam:** Steam is an enterprise product that allows you to deploy models that you build. You can also convert a trained model into an API for others to access. 

## Features and capabilities

The H2O platform has a set of different features and capabilities that are discussed below. 

**Clusters:** H2O is a java virtual machine capable of performing parallel computations for machine learning on clusters. Clusters are software with one or multiple nodes. These can be launched in your laptop, a server or multiple machines if more than one node is used. Memory is stored in a compressed columnar format, allowing you to read the data in parallel.  A cluster memory capacity is a sum of memories across all H2O nodes in the cluster. This is a much more flexible and efficient way of modelling because not only does it provide better efficiency for CPU but also provides great flexibility while scaling the model. These clusters are what make H2O fast. 

**Flow:** Flow is an interactive user interface that allows you to execute code, write text and plot graphs. It is similar to notebooks like jupyter notebook or collaboratory notebook. The uniqueness of this is it does not display the output just as plain text, it allows you to point and click and interact with objects in the form of tabular data. Flow runs on your localhost. Flow supports REST API, R scripts, and CoffeeScript and no programming experience is required to run H2O Flow. You can click your way through any H2O operation without ever writing a single line of code. 

![Flow-H2O](https://github.com/tapti-tech/H2O-AutoML/blob/master/Flow-H2O.jpg)

The above picture is taken from the official documentation of H2O and represents the flow interface. 


**AutoML:** Automatic ML is designed to have as few parameters as possible while modelling so that all the user has to do is upload a dataset, distinguish between features and target for prediction and set the number of trainable models. Every other process is automated with a goal of finding the best fitting model for that dataset. AutoML is also known for being able to select and build high accuracy ensemble models. 

H2O’s goal to make ML easy for everyone and to democratize AI is growing at a rapid pace. With tools like these, it is possible to try and bridge the gap between supply and demand of machine learning engineers. H2O platforms are powerful for developers to explore multiple techniques and to build models in a short period of time.

