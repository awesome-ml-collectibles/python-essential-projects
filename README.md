# Python Essential Projects

## Prerequisties

1. Install Python 3.4+, Anaconda( or miniconda).
   - Install Python
   - Miniconda
2. Text editor, prefer VS Code.
3. Setup Python development environment.

   - Install required extensions.
   - Setup conda env

     - Open VS Code Settings `ctrl+,`, open with json
     - Add following values

       ```json
       "python.pythonPath":"C:\\Users\\<Username>\\miniconda3\\condabin\\conda.bat",
       "python.terminal.activateEnvironment": true
       ```

4. Install required Python packages.

   ```bash
   conda env create -f env.yml
   ```

## 1. Uber Trips Analysis

Since it was founded in 2009, Uber has become one of the most famous unicorn companies, offering its services to more than 80 countries worldwide.

This Python project for beginners aims to analyze Uber rides to detect specific patterns, such as the busiest day or the time with the lowest number of rides.

And as you might expect, this is the easiest project to start with. You will get familiar with the common steps of analyzing a dataset and how to draw insights from data through visualizing the relationship between different variables.

In my opinion, there are 3 main reasons why this is an interesting Python project to try out. First, it’s really easy and doesn’t take much time. Second, since it’s famous, thousands of people have shared their code on GitHub and Kaggle, so you have the chance to discover different ways to analyze the same dataset. And, finally, despite its simplicity, this quick project is quite useful because it will help you solidify the foundational rules of coding in Python.

**What Will You Learn from This Python Project?**

- Read a dataset and display records from it
- Use your detective’s hat and uncover hidden patterns in data
- Find the relationship between different variables
- Draw insights by visualizing these relationships

You can download source code [here](https://365datascience.com/resources/downloadables/Python-Projects-Uber-Trips-Analysis.zip)

## 3. Parkinson Prediction

Can you improve people’s health and save their lives with just a few lines of code?

The answer is yes.

Data science has countless applications in healthcare, and one of them is to predict certain diseases, especially chronic ones. Consider this. If you’re planning to go out, you normally check the weather news the day before so that you can prepare. if it’s going to rain, you’ll grab an umbrella and wear a raincoat. And if the forecast says it is going to be hot, you’ll wear light clothes. The same approach is valid for disease prevention. If you are aware of the risk to catch a certain disease, you will have the time to think and prepare, which can save a lot of suffering and money.

In this project, you’ll carefully analyze a dataset of 195 records to predict the likelihood of having [Parkinson’s disease](https://www.nia.nih.gov/health/parkinsons-disease) using an [XGBBoost model](https://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning/).

So, what is special about this Python project for beginners?

Until now, Parkinson’s disease can neither be diagnosed nor treated. The doctor assesses the symptoms and decides based on the medical history. The idea of this project is to predict the risk of having the disease according to some attributes, such as the patient’s average vocal fundamental frequency. Those with a higher risk of developing Parkinson's will require constant medical attention and that will slow down the progression of symptoms, thus alleviating pain and suffering.

**What Will You Learn from This Python Project?**

- Read and explore data
- Understand the relationship between different variables through visualization
- Carry out feature selection to determine the variables that are most related to the target output.
- Build a machine learning model
- Use metrics, such as accuracy and ROC curve, to evaluate the model’s performance.
- Save the trained model into a file to be used for future predictions.

You can download source code [here](https://365datascience.com/resources/downloadables/Python-Projects-Predicting-Parkinsons-Disease.zip)
