<img src ="images/animals_wordcloud.png" alt="wordcloud" style="width: auto; height: 200">

<br />

![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# Animal Adoption Project

*The dataset used in this project is taken from Kaggle and contains synthetic, Creative Commons publicly licensed data. The scenario and business requirements described in this project are fictional and are created solely for the purpose of this analysis.*


## Dataset Content

The data consists of 2007 rows and 13 columns:

`PetID`: Unique identifier for each pet\
`PetType`: Type of pet (e.g., Dog, Cat, Bird, Rabbit)\
`Breed`: Specific breed of the pet\
`AgeMonths`: Age of the pet in months\
`Color`: Color of the pet\
`Size`: Size category of the pet (Small, Medium, Large)\
`WeightKg`: Weight of the pet in kilograms\
`Vaccinated`: Vaccination status of the pet (0 - Not vaccinated, 1 - Vaccinated)\
`HealthCondition`: Health condition of the pet (0 - Healthy, 1 - Medical condition)\
`TimeInShelterDays`: Duration the pet has been in the shelter (days)\
`AdoptionFee`: Adoption fee charged for the pet (in dollars)\
`PreviousOwner`: Whether the pet had a previous owner (0 - No, 1 - Yes)\
`AdoptionLikelihood`: Likelihood of the pet being adopted (0 - Unlikely, 1 - Likely)


## Business Requirements

The manager of an animal rescue centre in Indiana has requested an analysis of the centre’s existing adoption data to better understand which factors influence an animal’s likelihood of being adopted. This project will explore trends within the dataset and identify the characteristics most strongly associated with successful adoptions.

Effective prediction of adoption likelihood would help the rescue centre prioritise animal care,  optimise its resources and improve operational planning. If the project outcomes demonstrate clear value, the approach will be expanded to include data from additional rescue centres across the state.

The rescue centre is one of many in a group of centres under the same company umbrella. They have requested that, where possible, the brand colour lilac be used in the dashboard. This will help if the dashboard is presented to management and trustees.

## Hypothesis and how to validate?
* List here your project hypothesis(es) and how you envision validating it (them)

* H1: Younger animals are more likely to get adopted
  - Null hypothesis: Age has no effect on the likelihood of an animal being adopted
  - Alternative hypothesis: Younger animals are more likely to be adopted


## Project Plan
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Dashboard Design
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Conclusions

Hypothesis 1: the alternate hypothesis is correct: Younger animals are more likely to be adopted. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.


## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience?

* In notebook 02_eda_visuals I had some trouble creating a heatmap. There are so many variables in the correlation that it was difficult to glean any information. I tried a few times, with the aid of generative AI, to manipulate the heatmap using the original correlated dataframe. However, it was taking a long time and I didn't want to get bogged down so early on. Therefore I decided to create a simpler correlated dataframe with just the variables I was interested in. This made for a clearer and more useful heatmap. I now know that correlation tables are something I need to learn in more depth.

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- Data sourced from Kaggle: https://www.kaggle.com/datasets/rabieelkharoua/predict-pet-adoption-status-dataset/data
- The data is shared under the Creative Commons Licence: CC BY 4.0 International
- https://doi.org/10.34740/kaggle/ds/5242440
- In notebook 03_hypothesis_1.ipynb the definitions of alpha and p-value were taken from the Code Institute's Learning Management System, from the Foundational Data Analysis Techniques section. 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- Photo at the bottom of the readme file <a href="https://www.vecteezy.com/free-vector/rabbit">Rabbit Vectors by Vecteezy</a>
- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements

* I would like to say a huge thank you to my Tutor and Data Coaches at Code Institute for their teaching, advice and support.
* I am grateful to my fellow September 2025 cohort: for the help and the laughs.

<img src ="images/rabbit_running.jpg" alt="rabbit_running" style="width: 100px; height: auto; float:right">