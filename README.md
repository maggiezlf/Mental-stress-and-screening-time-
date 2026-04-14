# [GameON]

## Project Overview


Our project Gameon is trying to relate the relationships between stress level and screen time/social media time and gaming hours. The society have been developing in a rocket speed, and it worries us that people are leviating stress through screen time. 

## Team Members

- Lifan Zhao - Analysis 
- Ruoyi Xin - Analysis
- Ziyue Lin - Analysis


## Data Description

Describe the dataset(s) used in your project, including:

- https://www.kaggle.com/datasets/waqi786/mental-health-and-technology-usage-dataset
- 10000 unique values
- The data was already cleaned when found




### Key Variables

| Variable Name | Description | Data Type | Units/Format | Notes |
| :-- | :-- | :-- | :-- | :-- |
| [Age] | [Age of participant] | [Numeric] | [Years-Old] | [No special considerations] |
| [Gender] | [Gender of participant] | [Male/Female] | [-] | [No special considerations] |
| [Technology hour] | [Number of hours using Technology] | [Numeric] | [Hours] | [No special considerations] |
| [Social Media hour] | [Number of hours using Socail Media] | [Numeric] | [Hours] | [No special considerations] |
| [Gaming Hour] | [Number of hours Gaming] | [Numeric] | [Hours] | [any special considerations] |
| [Screen Time Hour] | [Number of hours of Screen Time] | [Numeric] | [Hours] | [No special considerations] |
| [Mental Health Level] | [Mental Health Level reported by Participants] | [Poor/Fair/Good/Excellent] | [-] | [No special considerations] |
| [Stress level] | [Stress Level  reported by Participants] | [Low/High] | [-] | [any special considerations] |
| [Sleeping hour] | [Number of hours Sleeping] | [Numeric] | [Hours] | [No special considerations] |

## Methodology

Outline the approach taken to analyze the data, including:

- Used Rstudio to analyze data
- ggplot, bar graphs



## Key Findings

Summarize the main discoveries and insights from your analysis. Include:

- We have currently found that there are no scinificant difference between screen time usage and your mental health level, screen time can exceed 10+ hours even though the participant have excellent mental health state and poor mental health state


## Installation and Setup

Instructions for setting up the project environment:

Rstudio, Set Session Directory, Read csv, import Library tidyverse

## Project Structure

Explain the organization of files and directories in your repository:

```
├── mental_health_and_technology_usage_2024.csv    # Raw and processed data files
├── stress and screening.Rmd          # Process file 1
├── brief descriptions.docx           #Description File
├── Data2.Rmd           # Process file 2
├── requirements.txt    # Required packages
└── README.md           # This file
└── Age_MentalStatus.png # Result visualization
└── TechCategory_MeanHours.png # Result visualization
└── diff_hour_fair.png # Result visualization
└── diff_hours_poor.png  # Result visualization
```


## Usage

Provide instructions on how to run your code and reproduce your results:




```python
#Create Rmd file in R, 
import library(tidyverse)
```


## Future Work

Outline potential next steps or improvements for the project:

- More relationships can be found between hours using the existing templates
- Forecasting model to predict the screen time hour and stress level



## Acknowledgments

Rstudio, Kaggle dataset, Mental Health & Technology Usage Dataset by Waqar Ali, Lifan Zhao, Ruoyi Xin, Ziyue Lin


## Contact Information

lifanz2@illinois.edu

