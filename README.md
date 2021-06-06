# Prediction-of-gross-developers-income-using-public-surveys

We chose to look at the annual data from the Stack Overflow Developer Survey Results, which are open to the public. The survey received answers from 88,883 people who were asked a number of questions. Respondents were largely recruited via Stack Overflow-owned networks. Site messaging, blog content, email lists, Meta posts, banner advertising, and social media posts were the top five sources of respondents.
As being such huge data we’ll have to overcome the following challenges:
* Imputing the data according to the information we need (for example, if a student does not receive compensation, NA is allocated, but this is critical information).
* By removing the parameters that aren't useful (manual or using correlation).
* Creating Categories for compensation instead of being a continuous data. 
* Handling such massive data over the local machine.

After the pre-processing stage, we plan to create our machine learning model to predict compensation using ANN(Artificial Neural Network) Regression.
Through creating the machine learning model we want to answer the following major questions:

  *Question 1:* What are the most widely used coding languages? What are the coding languages with the smallest user base?
  
  *Question 2:* How happy are developers with their coding job?
  
  *Question 3:* How satisfied are you with your job with JavaScript code (the most 	common code)?

Other than these straight forward questions we plan to answer some higher level questions about the open source contribution towards job seeking arena. Open-source benefactors stick to the local area rules of code and follow the prescribed procedures spread out by networks. They befriend individual benefactors who can assist with references.
Then, we utilize a direct AI model to discover coefficients with critical effect on the compensations of expert engineers in India. We have utilized the appropriate responses (i.e., perceptions) from proficient engineers in India to prepare a direct AI model with Python sklearn. We have utilized mathematical factors like work insight (in years), and we utilized a portion of the overview's absolute factors as contribution for the ml model. It represents the variety (scattering) of half of the compensations of expert engineers in the USA. The r² score is above 0.5 for both the train information (70% of perceptions) and the test information (30% of perceptions)

# About Dataset:

Since 2011, Stack Overflow, a well known Q&A site for engineers, has studied countless clients. The yearly studies comprise of inquiries with mathematical answers (e.g., age, compensation) and of inquiries with clear cut answers from different decision alternatives ("pick one" or "pick all that apply"). The 2020 overview contains 61 inquiries (i.e., factors) and almost 65,000 clients from everywhere the world participated. Strikingly, the 2020 overview was led in February, before the World Health Organization proclaimed the Covid flare-up to be a pandemic. 

The column “ConvertedComp” hold the value of the salary of the developer made annually. This is the target value that we are interested to predict in the Model Creation phase of our project.
