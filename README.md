# DL-Project-Music-Genre-Classfication


Music is like a mirror, and it tells people a lot about who you are and what you care about, whether you like it or not. We love to say “you are what you stream,”.Companies nowadays use music classification, either to be able to place recommendations to their customers (such as Spotify, Soundcloud) or simply as a product (for example Shazam). Determining music genres is the first step in that direction. Machine Learning techniques have proved to be quite successful in extracting trends and patterns from the large pool of data. The same principles are applied in Music Analysis also.This project is aimed at using the KNN classification algorithm to detect the genre of music from an audio file. The ability to classify an audio file and categorise them according to their genres, has proven to put a huge impact on services mentioned above. This way, they engage their customers more by predicting what type of music a particular customer is interested in and further applying state of the art deep learning methods to give recommendations.


Project Flow:
Download/Create the dataset;
Process the audio files and load the data into Numpy Arrays;
Train and Test split on complete dataset;
Build the classifier : Defining Functions and calling them as needed;
Finding accuracy on Test Data ;
Build a Web application using flask for the same;


To complete this project you should have the following softwares  and packages 
Anaconda Navigator :
 Anaconda Navigator is a free and open-source distribution of the Python and R programming languages for data science and machine learning related applications. It can be installed on Windows, Linux, and macOS.Conda is an open-source, cross-platform,  package management system. Anaconda comes with so very nice tools like JupyterLab, Jupyter Notebook,
QtConsole, Spyder, Glueviz, Orange, Rstudio, Visual Studio Code. For this project, we will be using Jupiter notebook and spyder



Flask App : has all the files necessary to build the flask application. 
templates folder has the HTML page.
uploads folder has the uploads made by the user.
app.py is the python script for server side computing.
my.dat is the file that contains the saved data (machine-readable format).
Dataset :  The dataset can be easily downloaded from the link given in below and we need to just put the genre folders as our dataset. Here we have named it as Music Genres and there are 10 subclasses which contain audio files (our actual data).
Python file : these are the files which we have used to train the model, named as “music genre classification train.py”. It contains all the necessary functions required for the KNN as well as handling audio data.
Data file :  this is originally created data file after training and then put into the flask folder for our flask app to access it and run the model while deployment. It contains information about all the audio clips present and stored as 
Wav files : These are some test files which we have used for testing the final application.
