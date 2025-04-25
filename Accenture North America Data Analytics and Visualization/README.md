# Accenture North America Data Analytics & Visualization Job Simulation

## Project Overview
This repository contains my completed project for the **Accenture North America Data Analytics and Visualization Job Simulation** on Forage (April 2025). In this simulation, I acted as a Data Analyst assisting Accenture in supporting their client, **Social Buzz**, a social media company aiming to improve engagement by identifying their top-performing content categories.
The project followed a structured data analytics pipeline—from problem understanding to presentation—culminating in actionable insights tailored to both internal stakeholders and the client.

## Project Understanding Phase
- Reviewed the client brief from **Social Buzz** to understand their key business challenge.
- Identified project requirements and expected deliverables.
- Determined the main focus areas for the Data Analyst role.

## Data Analysis Phase
### 1. Requirements Gathering
- Reviewed 7 datasets provided by the client.
- Analyzed the data model outlining relationships between datasets.
- Selected **three** relevant datasets for the analysis:

    - [**ReactionTypes.csv**](Accenture%20North%20America%20Data%20Analytics%20and%20Visualization/ReactionTypes.csv): 
      Metadata for each type of reaction (e.g., like, love, haha, etc.)
    - [**Content.csv**](Accenture%20North%20America%20Data%20Analytics%20and%20Visualization/Content.csv):
      Contains content IDs, categories, and descriptive metadata for posts shared on the platform.
    - [**Reactions.csv**](Accenture%20North%20America%20Data%20Analytics%20and%20Visualization/Reactions.csv):
      Core dataset that tracks user interactions and reactions to various pieces of content.

     
### 2. Data Cleaning
- Opened and inspected each selected dataset.
- Removed rows with missing or null values.
- Standardized data types for consistency and accuracy.
- Eliminated irrelevant columns based on the business objectives.
- Evaluated the relevance of each feature in context with the business questions.

### 3. Data Modeling
- Used the **Reaction** table as the base.
- Merged in relevant data from the **Content** and **Reaction Types** tables using `VLOOKUP` functions.
- Calculated total popularity scores for content categories using `SUMIF` formulas.
- Identified the **Top 5 Performing Categories** based on calculated popularity scores.
- Produced a final, clean dataset highlighting these top categories.

    [**merged_cleaned_dataset.xlsx**](Accenture%20North%20America%20Data%20Analytics%20and%20Visualization/merged_cleaned_dataset.xlsx): The final merged and cleaned dataset for analysis.

## Presentation Phase
- Created a **PowerPoint deck** summarizing the data analysis and key findings.
- Delivered a **video presentation** articulating insights tailored for both:
  - The client (**Social Buzz**)
  - Internal Accenture stakeholders
 
    - [**Data Analytics template - Task 3_final.pptx**](Accenture%20North%20America%20Data%20Analytics%20and%20Visualization/Data%20Analytics%20template%20-%20Task%203_final.pptx): PowerPoint presentation of the final analysis and key insights.
    
## Tools & Techniques Used
- Microsoft Excel (Data cleaning, VLOOKUP, SUMIF)
- Data modeling & feature selection
- Business-focused communication
- PowerPoint for insights presentation
- Video narration and stakeholder targeting

## Key Outcome
The analysis identified the **Top 5 Content Categories** based on user reactions, offering clear guidance to **Social Buzz** on which content areas to prioritize in their engagement strategy.

## Certificate of Completion  
**Accenture North America Data Analytics and Visualization Virtual Experience Program**  
_Forage, April 2025_

[View Certificate](https://forage-uploads-prod.s3.amazonaws.com/completion-certificates/T6kdcdKSTfg2aotxT/hzmoNKtzvAzXsEqx8_T6kdcdKSTfg2aotxT_jEbwX2TKYBdtWfmBh_1733115409794_completion_certificate.pdf)

*This project was completed as part of the Accenture Virtual Experience Program on Forage. All data is synthetic and provided solely for educational and portfolio purposes.*
