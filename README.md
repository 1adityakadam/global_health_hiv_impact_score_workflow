# Global Health Impact (GHI) Project — HIV 2015 Impact Score

# 📌 Overview

This repository contains my submission for the Global Health Impact (GHI) Project Data Team selection task.

The objective of this project is to compute the Impact Score for each country listed in the HIV 2015 ORS dataset, using all available drugs and following the methodology outlined in the provided reference materials.

# 🎯 Task Objective

Calculate Impact Scores for each country in the HIV 2015 ORS dataset

Implement the full workflow in Python, including:

Entity mapping

Data processing

Impact score computation

# 📂 Repository Contents

File	Description
Hiv_2015_entity_map.ipynb	Main notebook implementing the workflow (entity mapping → calculations → final scores)
impact_score.csv	Final output containing computed Impact Scores per country
README.md	Project documentation
(Optional) requirements.txt	Dependencies (if included)

# 🧠 Methodology

The workflow follows the structure demonstrated in the HIV 2013 reference notebook and the Model PDF, adapted for the HIV 2015 dataset.

Key Steps:

Data Loading

Import the HIV 2015 ORS dataset

Entity Mapping

Map drugs, countries, and related entities

Ensure consistency with reference structures

Data Cleaning & Preparation

Handle missing values

Align dataset with model requirements

Impact Score Calculation

Implement formula based on:

Drug efficacy

Disease burden

Coverage and access factors

Follow logic described in the Model Reference Document

Output Generation

Export final results to impact_score.csv

# 📖 References Used

HIV 2015 ORS Dataset
HIV 2013 ORS Dataset
All data files are inside Data folder.

Model Reference Document (tmi13706-sup-0001-supinfo.docx)

HIV 2013 Example Notebook

Entity_Map (ReadMe).MD

# ⚙️ How to Run

Clone the repository:

git clone <your-repo-link>
cd <repo-name>

Install dependencies (if applicable):

pip install -r requirements.txt

Run the notebook:

jupyter notebook Hiv_2015_entity_map.ipynb
# 📊 Output

The final output file:

impact_score.csv

Contains:

Country-wise Impact Scores

Computed based on all drugs in the dataset

# ⚠️ Notes

All work was done locally; no shared Google files were modified.

The implementation closely follows the structure of the HIV 2013 example while adapting to HIV 2015 data.

Assumptions were made where necessary to align missing or ambiguous fields with the model.

# 🚀 Submission

This repository is submitted as part of the GHI selection process.