# ADA_Project
## AbstractFor the ADA's project we were inspired by a project called "GoodCityLife" lead by Luca Maria Aiello, Daniele Quercia, two data scientists of Nokia Bell labs and Rossano Schifanella, an assistant professor in computer science at the University of Turin. The main goal of their project was the following:Built new maps of 2 cities (London and Boston) based on one human emotion: happiness. With these new maps, people are not only able to find the shortest path from A to B, but also to find a path that optimize happiness. For this purpose, they developed an algorithm that try to optimize both shortness and happiness. Following this algorithm, people can take a path a few minutes longer than the shortest path, but 10 times happier and more pleasant since there are less cars and more trees on the roadside, for instance.Our goal in this Project is to build a "Happy Swiss Map" inspired by GoodCityLife work. Thanks to our professor Michele Catasta, we will have access to a large dataset of Instagram informations. We will focus in this project on the text part of each instagram. Considering the fact that these informations are coming from social medias and therefore are not always telling the truth, we will have to make the best approximation of the degree of happiness of each node.## What kind of data do we have ?Our first work will be to study our instagram dataset. We have in hand a dataset of very noisy data and we have to clean them. This is the text pre-processing part, which code can be find in file text_process.py.

## Machine learning pipeline

We follow a standard pipeline using Naive Bayes multiclassification method that trains on 20% of the dataset and predict the 80% others.## Geo-localizationAny localization information was given in our dataset, then we decided to find it by ourselves. The algorithm is based on the tag list of every instagram. The code can be found in localization.py
## VisualizationOur final step is to create a cartography of Switzerland that we can visualize. You can see all the result in the file Pr�sentation.ipynb, and for more details about how the visualization were done (the code), all the necessary is in visualization.ipynb


## Conclusion

Finally, to see all the pipeline in one script, in_one_script.ipynb resume the all reasoning, all the functions used in in_one_script.ipynb are concatenated in functions.py. Before all, this project�s aim was to introduce myself to big data calculus and learn Spark a language that can parallelize algorithms. Even if the final results are not relevant, the only fact that all the steps above mentioned have been run on the almost 10-millions instagrams is a success. Don�t forget to see the �Pr�sentation� file that give a better idea of what was done.
