========================================================================
README: Multi-Platform Cyberbullying and Toxic Span Detection Dataset
========================================================================

1. DATASET OVERVIEW
-------------------
- File Name: Cyberbullying_Toxic_Span_Research_Dataset.csv
- Total Records: 75,000
- Digital Platforms Included: Facebook (FB), Instagram (IG), Reddit, and News Portals.
- Classification Type: Multi-class Text Classification & Token/Character-level Sequence Tagging.

2. FEATURE DEFINITIONS (6 COLUMNS)
-----------------------------------
- id: A unique incremental identifier for each row record.
- text: The social media textual entry containing raw linguistic contextual indicators.
- label: Categorical target classifying the type of harassment or toxicity (7 distinct classes).
- platform: The digital ecosystem from which the communication behavior is monitored.
- toxic_span_start: Character index where the offensive/toxic phrase begins within the text string (-1 denotes Non-Toxic or no specific span).
- toxic_span_end: Character index where the offensive/toxic phrase terminates within the text string (-1 denotes Non-Toxic or no specific span).

3. BALANCED DATA DISTRIBUTION
------------------------------
The dataset maintains an exceptionally strict and balanced distribution across classes and platforms:

Class Distribution (7 Labels):
- Racism_Xenophobia: 10,715 records
- Misogyny_Sexism: 10,715 records
- Homophobia_LGBTQphobia: 10,714 records
- Religious_Hate: 10,714 records
- Harassment_Stalking: 10,714 records
- Profanity_Insult: 10,714 records
- Non_Toxic (Control group): 10,714 records

Platform Distribution:
- Facebook (FB): 18,867 records
- News_Portal: 18,844 records
- Instagram (IG): 18,689 records
- Reddit: 18,600 records

4. CORE ADVANTAGES FOR RESEARCH
--------------------------------
- Explainable Content Moderation: Instead of just predicting if a sentence is toxic, the character-level spans enable AI architectures to highlight exactly WHY a post is flagged.
- Multi-Platform Generalization: Merging data from FB, IG, Reddit, and News Portals reduces platform bias, training models that generalize exceptionally well across different internet registers.
- Perfectly Balanced: Helps avoid multi-class imbalance issues during model optimization.

5. LICENSING & CITATION
-----------------------
Distributed under Creative Commons Attribution 4.0 International (CC BY 4.0). 
Please cite this dataset repository and its official DOI if utilized in any academic, industrial, or commercial publications.
========================================================================