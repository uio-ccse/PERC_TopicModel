# PERC_TopicModel
LDA Topic Modeling of PERC Papers


## Description
This project focuses on using Latent Dirichlet Allocation to thematically analyze the physics education research literature, in the form of the Physics Education Research Conference (PERC) Proceedings in the 2001-2018 period. 

The code in this repository was developed by [Tor Ole Odden](https://www.mn.uio.no/fysikk/english/people/aca/Tor%20Ole%20Odden/) and [Alessandro Marin](https://www.mn.uio.no/fysikk/english/people/adm/almarin/index.html). The project is described in a paper published in Physical Review Physics Education Research: 

*Tor Ole B. Odden and Alessandro Marin, Marcos D. Caballero*, **Thematic Analysis of 18 Years of Physics Education Research Conference Proceedings using Natural Language Processing** (2020). [link](https://journals.aps.org/prper/abstract/10.1103/PhysRevPhysEducRes.16.010142).



## Jupyter Notebook
See the [PERC_TopicModeling](https://github.com/uio-ccse/PERC_TopicModel/blob/master/PERC_TopicModeling.ipynb) Notebook. This notebook contains an extract of the methods described in the paper. 


## Installation
To run the main notebook [PERC_TopicModeling.ipynb](https://github.com/uio-ccse/PERC_TopicModel/blob/master/PERC_TopicModeling.ipynb) install the required packages:

`pip install -r requirements.txt --user`

The required packages include [Gensim](https://radimrehurek.com/gensim/) (unsupervised semantic modelling on text), [NLTK](http://www.nltk.org/) (Natural Language Tool Kit), [LDAVis](https://github.com/bmabey/pyLDAvis) (interactive topic model visualization), [scikit-learn](https://scikit-learn.org/stable/), along with standard data analysis libraries such as pandas, numpy, and matplotlib.


## Contact
Questions can be directed to [Tor Ole Odden](https://www.mn.uio.no/fysikk/english/people/aca/Tor%20Ole%20Odden/)
