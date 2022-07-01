L1 6/28/2022

Colab
- Set up everything (Github, join Zoom, Google colab)
- Using colab (mount Google drive and use df, can use linux commands, get virtual machine in the google cloud)
- VM=12.68 GB of RAM
- Free GPU and TPU to go on local computer
- Can upload files to Github, then can download it as a csv and upload directly to Notebooks

RSTUDIO
- install packages 
- <- is basically equal
- can mainpulate into minimum and maximum like filters
- to make markdown, go to plus thing on the left and do markdown, add chunks with the green chunk thing
- can "knit" into pdf or html (MAKE SURE TO CHANGE OUTPUT!)
- basically write boxplots as how you think about it
- sapply: take in list and output as vector (sapply(obj, fun))
- in this case our function was class, which returns all the elements of the class attribute (in this case the Class column))
- press source to run entire file
- more + export to download r file for git
- need to save file w name before running 

L2 6/30/2022
- Can use visual studio code as a IDE for different languages LOCALLY (if you want to open files, use terminals, etc.)
- wget + link of file downloads file locally if you use terminal
- miniconda can open a virtual environment (conda env list)
- anaconda download allows for you to download packages in certain environments without affecting other environments
- https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf
- plots can be deceptive
- star = significant, if number of coefficient > 9 that increases odds, confounding variables 
- only use variables that would affect it
- for linear graphs: assumption is made that data is distributed normally, the variation in the data is uniform
- in python, use sklearn to make linear regression, sklearn.mertics to import classification report on the probability of something 
- need to edit it to find probability
- negative correlations vs positive correlations indicate hypothesis acceptance
- classification model is used in logistic regression, has a categorical response
- regression model: linear regression, has a continuous response
