![image](https://pharmaphorum.com/wp-content/uploads/2016/07/Technology-digital-data-600x340.jpg)
# Simulating risk factors for heart disease
## Final project: Programming for Data Analysis

**Author:** Caio Forte Ribeiro
<br><br>

***
## About this repository

This repository contains one Jupyter notebook (`simulation.ipynb`) and related data required to run the notebook, as part of the assessment for the module *Programming for Data Analysis* at GMIT (Winter 2021-22). All code was written in Python ([v. 3.8.8](https://www.python.org/downloads/release/python-388/), realeased on Feb 19, 2021).

<br>

***
## Task
Create a dataset that simulates a real-world phenomenon using Python and implement this simulation in a Jupyter notebook. The data should be synteshised and mimic the properties of real (or supposed) data for the chosen phenomenon.

In this project, we simulated the risk factors associated with heart disease, as presented in the [*Framingham Heart Disease Study*](https://en.wikipedia.org/wiki/Framingham_Heart_Study) from 1948.

<br>

***
## Summary
Before the COVID-19 pandemic, heart disease was topping the WHO list of main causes of deaths globally [1]. In the late 1940's, it was the cause of 1 in every 2 deaths in the US, motivating a systematic, long-term study that became known as the Framingham Heart Disease Study, after the name of the town where it has been conducted since 1948 [2]. The study showed, for the first time, that a number of behavioural, physiological, and demographic factors were associated with a greater risk of a person developing heart disease later in life [3].

Among such factors, the following three seem to play an important part:

1. The number of cigarettes smoked per day (the less, the better).
2. Whether the person is obese or not, as well as the degree of overweight, measured by the person's Body Mass Index (BMI).
3. The level of cholesterol in the person's blood (again - the lower, the better) [3].

The goal of this project was to investigate the nature and behaviour of the data related to these risk factors and simulate their properties as closely as possible in a dataset containing random data about:

1. Number of cigarettes per day
2. BMI
3. Cholesterol levels
4. Risk of heart disease

<br>

***
## Requirements
**Quick note:** Before starting with specific requirements, if you're on Windows we recommend that you install a third-party console emulator, such as [Cmder](https://cmder.net/). Mac users can stick with the macOS Console.

To run the Jupyter notebook, you will first need to:
1. Have Python installed in your machine. You can download the latest version [here](https://www.python.org/downloads/).
2. Install Jupyter. This can be done in two ways:
   * Using `pip`: 
   ```
   pip install jupyterlab
   ```
   * Installing [Anaconda](https://docs.anaconda.com/anaconda/install/), which comes with Jupyter pre-installed. 

Specific requirements for running the code, such as additional modules to import, are in the notebook itself.

<br>

***
## How to run the notebook
1. Clone this repository into your local machine.
2. Open Cmdr (or MacOS Console if using a Mac).
3. In the terminal, type:
    ```
    jupyter lab
    ```
4. The Jupyter application should open in your browser. If it doesn't, click [here](https://jupyter-notebook.readthedocs.io/en/stable/troubleshooting.html) for troubleshooting.
5. Navigate through the folders and double-click the file `simulation.ipynb`.
6. In the **Run** tab from the top-left menu, click on **Run All Cells**.
7. If you have an issue while running the notebook, try restarting the Kernel:
   * In the **Run** tab from the top-left menu, click on **Restart Kernel and Run All Cells**.

<br>

***
## Credits
* If you're interested in the Framingham Heart Study, their [webpage](https://framinghamheartstudy.org/) has the most up-to-date information about the third round of analysis that is currently on-going. All collected data for the study is available on request.

* For an exploratory analysis of the data, check out [this page](https://www.kaggle.com/lauriandwu/machine-learning-heart-disease-framingham) on Kaggle. It was heavily used as inspiration for this project.

<br>

***
## References

[1]:  The World Health Organization (2020). [*The top 10 causes of death*](https://www.who.int/news-room/fact-sheets/detail/the-top-10-causes-of-death). Access on 30 Dec, 2021.

[2]:  Mahmood, S. S., Levy, D., Vasan, R. S., & Wang, T. J. (2014). The Framingham Heart Study and the epidemiology of cardiovascular disease: a historical perspective. *Lancet* (London, England), 383(9921), 999–1008. https://doi.org/10.1016/S0140-6736(13)61752-3. Available on: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4159698/. Access on 30 Dec, 2021.

[3]: Gallestey, J. Bacallao (2016, April 22). Framingham Heart Study. *Encyclopedia Britannica*. https://www.britannica.com/event/Framingham-Heart-Studay. Access on 30 Dec, 2021.

<br>

***
## Contact
Feel free to get in touch about this project by sending me an [email](mailto:G00398262@gmit.ie) with your suggestions. 

