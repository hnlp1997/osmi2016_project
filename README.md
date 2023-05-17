# Mental Health in Tech 2016 Project (Python)

This was a final project for my first MSBA course at Santa Clara University - Data Analytics with Python. Our task was to team up with 3-4 classmates, find any public dataset online that seemed interesting, and uncover 3 major findings for it. My awesome partners were [Aaron Huang](https://www.linkedin.com/in/aaron-huang-scu/), [Aditi Bagepalli](https://www.linkedin.com/in/aditibagepalli/), and [Brian Beams](https://www.linkedin.com/in/brimism/). 

After a few days of contemplating over which dataset we were going to use (scrolling through [Kaggle](https://www.kaggle.com/)), Aaron found the OSMI (Open Sourcing Mental Illness) 2016 Survey dataset, which we all mutually agreed was the most interesting and informative: https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016. The survey's purpose is to assess attitudes toward mental health in the tech industry, analyze the prevalance of mental health disorders in tech, and determine possible solutions to raise awareness and improve working conditions for those with mental health issues.

![Initial dataset](https://cdn.discordapp.com/attachments/663146570765566003/1108196651962744913/image.png "Preview of the Dataset")

In this dataset, there is a total of 1433 rows and 63 columns (i.e. 1433 survey respondents, 63 questions asked). 
Ideally, we would've used an OSMI post-COVID survey to have more real-time data; unfortunately, the number of respondents decreased dramatically after 2016 and especially for [2021](https://www.kaggle.com/osmihelp/osmh-2021-mental-health-in-tech-survey-results) (only 131 answers).

Our project primarily utilizes Python packages such as Pandas, seaborn for visualization, and sklearn for machine learning. Some highlights of the project were the data cleaning (funnily enough), finding insights, the regression model, and the decision tree. Check out the [Jupyter notebook](https://github.com/hnlp1997/osmi2016_project/blob/main/osmi_2016_survey.ipynb) linked in this repo for further analysis.

![Sought MH Treatment](https://cdn.discordapp.com/attachments/663146570765566003/1108205072015433898/image.png "Breakdown by Gender")

Our conclusion in our analysis is that women and non-binary tech employees proporitionally seek mental health treatment the least in comparison to male employees. In order to reduce the likelihood of mental health disorders for tech workers, it is recommended that employers allocate proper resources for mental health treatment, nurture more human connection in the workspace by organizing events such as healing circles and outdoor retreats, and offer more paid time off. 

Overall, I was able to implement a lot of techniques and concepts I learned from class in the project and gained a lot of experience using Python. Click [here](https://docs.google.com/presentation/d/1bptm0tnY-efi9nXrIC0u8oaniwjNyZmMG4kg3KxuXWk/edit?usp=sharing) to view our presentation slides and learn more about our thought process.

