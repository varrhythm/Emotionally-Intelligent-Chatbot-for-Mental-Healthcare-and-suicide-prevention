# Emotionally-Intelligent-Chatbot-for-Mental-Healthcare-and-suicide-prevention
To provide a free service of interaction with a machine, the objective of “Emotionally Aware Chatbot” is to provide mental healthcare to those who are mentally-ill anywhere and anytime. It raises the question of what role, if any, the chatbot should play in suicide prevention. With this chatbot, we expect to reach as many mentally-ill people as possible by hosting this on web domains of known hospitals or counselors. If it is easy to detect mental health issues at the correct time and provide suitable help, it might save precious lives. If integrated with the hospital systems, this would provide an effective way to automate the work.

Software Used
1.	“VS” Code: Visual Studio Code was the code used for most part of the project.

2.	Sublimetext Code Editor: Initial code development was done using sublime text editor that helped in formatting the python code & rightly placing it before moving to the “VS” code.

3.	Python: The Artificial Intelligent Algorithms used in “Sentiment Analysis” that is the “Random Forest Classifier” and the “Logistic Regression Classifier” were coded using python. There were several Python packages used in the creation of the project as listed below:

4.	Csv Files: Data from the extracted from the datasets which are stored as csv files. The 2 datasets that have been imported in our project are “labelledData.csv” on which the random forest algorithm has been applied and the other “emotion.csv” on which logistic regression algorithm has been used.

5.	Google Form: A google form had been generated in order to collect major healthcare issues faced by the people in general. We got responses from many people and through it we could classify our intents as depression, anxiety, paranoia, sleeping disorder, substance abuse and personality disorder. Most of the corner cases problems are also covered in these. 

6.	Python environment setup packages:
Venv

7.	Python packages for Data-Retrieval: (Used when the bag of words are processed using the Random forest classifier)
BeautifulSoup4

8.	Python packages used in the given project:
a.	Pandas: It is used to retrieve data from the dataset into the data frame.
b.	Numpy: N-dimensional array for numerical computation
c.	Sci-kit learn: Python modules for machine learning and data mining.
d.	Matplotlib: 2D Plotting library for Python
e.	Re: It is used for doing Regular Expression pattern matching in Python.
f.	Time: It is used to work with real-time data in Python.
g.	Spacy: It is used to do entity extraction and intent classification by importing the specific modules.
h.	Nltk: Natural language toolkit.

9.	Python packages for Data-Cleansing: (Used when the bag of words are processed using the Random forest classifier)
StopWords



Instructions to execute the code:
I.	Python Environment Setup:
1.	Install “Anaconda PROMPT”.
2.	Create an environment for the project to install all the python libraries separately. The following command creates a virtual environment for the project. Run the command in the terminal in the directory you want to create the virtual environment.
python3 -m venv tutorial-env
tutorial-env\Scripts\activate.bat
3.	The above two commands create and start the virtual environment.
4.	Install the required packages using the pip command in that virtual environment.
pip install pandas as pd
pip install time
pip install re
pip install -U scikit-learn
python -m pip install -U pip
python -m pip install -U matplotlib
pip install spacy
5.	After installation of all the libraries the python code can be executed normally in any python code as in VS Code.
6. Run Anaconda Prompt and give the following commands to get started with the code execution:
>(Type the name of the directory or disk where the project is saved, for ex if saved in    “D” disk then type “d:” or “D:” )
>cd(name_of _the_directory)
>py(name_of_the_python_file)
