# Modeling Heart Diseases
## Flatiron Mod 3 Project

**Authors**: Andy Peng

The contents of this repository detail an analysis of the module one project. This analysis is detailed in hopes of making the work accessible and replicable.


### Business problem:

I am tasked to investigate heart diseases for a hospital. For this project we will be looking at a data set of patients in a hospital some with heart diseases and some without heart diseases. The main goal of this project is to keep an eye out for certain features that will allow us to categorize this patient as having heart disease.


### Data
Data can include whether the patient have heart disease or not and features relating to the individual such as age, sex, chest pain, resting blood pressure, maximum heart rate, etc.


## Methods
- Descriptive Analysis
- Modeling
- Choices made
- key relevant findings from exploritory data analysis

## Results


#### Visual 1
![graph1](./Image/WaterFrontView.png)
> Box plot graph of Water Front View VS House Prices

#### Visual 2
![graph2](./Image/zipcodes.png)
> Zip Code's Average Housing Prices

#### Visual 3
![graph3](./Image/InteractiveMapping3.png)
> Mapping of Zip Code's Average Housing Prices

#### Visual 4
![graph4](./Image/SqftLivingPrice.png)
> Footage of the house vs Housing Prices


## Recommendations:

To summarize everything above, we can see from above that to correctly classified a patient as having heart disease we need to consider the following features.

1) Gener of the individual - Males have a higher chance at having heart disease than females.

2) Asymptomatic Chest Pain - Individuals with this type of chest pain have a high chance of having heart disease

3) Reversable Defect - If the thalium stress result turns out to be reversable defect, the individual would have a high chance of having heart disease.

4) Age & Maxium Heart Rate - As you get older, your maximum heart rate goes down. We can see that individuals that have heart disease tend to be older and have a lower maximum heart rate.

Our modeling shows that .... is the best model for our problem. This is because we want a model that generates a high recall value in order to minimize the chance of us classifying an individual as false negatives. We are classifying individuals with heart disease, if we classify someone with no heart disease and they do have it would be really bad. For other modelings that we did, please review the codes above.


## Limitations & Next Steps

There are many features that we haven't considered. For example whether the family has a genetic disorder, body fat percentage, and the individual's diet.


### For further information
Please review the narrative of our analysis in [our jupyter notebook](./Housing_Price.ipynb) or review our [presentation](./SampleProjectSlides.pdf)

For any additional questions, please contact **andypeng93@gmail.com)


##### Repository Structure:

Here is where you would describe the structure of your repoistory and its contents, for example:

```

├── README.md                       <- The top-level README for reviewers of this project.
├── Housing_Prices.ipynb             <- narrative documentation of analysis in jupyter notebook
├── presentation.pdf                <- pdf version of project presentation
└── images
    └── images                          <- both sourced externally and generated from code

```
