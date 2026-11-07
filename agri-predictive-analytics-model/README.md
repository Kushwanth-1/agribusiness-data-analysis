# Agri Predictive Analytics Model

Week 6 project for the Yuva Intern Junior Data Scientist internship.

## Project objective
Forecast district-level crop yield at the end of agricultural week 20 and explain the main drivers to support procurement planning in a fictional Nagpur agritech scenario.

## Data transparency
The internship brief did not provide a dataset. The project uses a seeded synthetic dataset of approximately 350,000 weekly records across six districts and six crops. The results demonstrate the workflow only; they are **not official or observed Vidarbha agricultural statistics**.

## Main deliverables
The following files are currently stored in the repository root:

- [Project report (DOCX)](../Project_Report.docx)
- [Eight-slide findings deck (PPTX)](../Findings_Deck_8_slides.pptx)
- [Analysis notebook (IPYNB)](../agri_yield_analysis.ipynb)
- [Project description (TXT)](../Project_Description.txt)
- [Original project ZIP](../agri-yield-project.zip)

## Model card
- [Model card and intended-use notes](model_card.md)

## Reported evaluation
The report states a test MAE of approximately **1.19 q/ha per district-crop** and a **31% improvement** over the three-year rolling-mean baseline. It also reports that test error was about **40% higher than validation error**, so the stability criterion was not met.

## Repository status and limitations
The report, presentation, notebook and project description are present in the repository root and linked above. The ZIP is retained as an archive. The README and model card are organized in this folder.

A separately uploaded trained model file and a fully extracted source/data directory have **not been independently verified** in this repository. Do not assume those artifacts are available until they are uploaded and checked.
