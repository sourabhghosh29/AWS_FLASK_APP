# UFC MMA Predictor

The UFC MMA Predictor is a web app to predict fights exclusively in the Ultimate Fighting Championship (UFC). Please use at your own discretion as there is no guarentee of profit. **The machine learning model behind this web app currently gives a 70.4% accuracy**. This is also considered a professional project of mine. 

Here you will find the following documents:

* Python scripts to the web app
* Integration with AWS S3 Buckets and deployment on AWS EBS

# Getting Started

Here are a few information you need to have before using the web app:

* Fight card information (who is fighting who)
* Fighter information (weightclass and name)
* Betting odds (preferred decimal odds), knowing who is the favourite and underdog fighter beforehand

## Things to note

Here are some of the trends that have been spotted in recent MMA years to note:

* Picking favourite only gives 60% chance of winning in long term
* Fights go on longer in general 
* Southpaws win 53% of their fights, as opposed to 48% for orthodox fighters 
* Fighters who switch stances have an even higher success rate than both orthodox and southpaw fighters, with a combined win percentage of 57%
Project Description: ML Powered UFC Fights historical analytics website and Machine learning fight predictions for odds generation and tweaking

AWS Infrastructure Used:

AWS Elastic Beanstalk (Flask App User Login Module)
AWS EC2 instances (Dash App: Analytics websites module)
Amazon SageMaker
Amazon S3
AWS CloudWatch
Project Credits:

Aditya Tornekar
Sourabh Ghosh
Shreyas Sadagopan
Rishabh Agarwal
Demo
![Demo](https://user-images.githubusercontent.com/54787115/113495280-79050000-94be-11eb-88d8-efa3b94c7ceb.png)
