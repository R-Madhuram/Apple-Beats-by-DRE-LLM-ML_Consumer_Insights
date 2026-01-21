# Applied ML & LLM-Based Consumer Experience Insights 
![Externship](https://img.shields.io/badge/Externship-Apple%20%7C%20Beats%20by%20Dre-darkred)
![Language](https://img.shields.io/badge/Language-Python-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-NLP-orange)
![LLM](https://img.shields.io/badge/LLM-Gemini%20AI-purple)
![Focus](https://img.shields.io/badge/Focus-Consumer%20Insights-red)
![Output](https://img.shields.io/badge/Output-Business%20Recommendations-success)


This repository contains an **applied machine learning and analytics case study** completed during an externship with **Apple’s Beats by Dre – Consumer Experience team**.

The objective of the project was to synthesize **large-scale qualitative and quantitative consumer feedback** into **executive-ready insights** that could inform product positioning, customer experience improvements, and conversion strategy.

> ⚠️ **Note on Data Privacy**  
> All underlying datasets used in this project are **proprietary and redacted** due to confidentiality requirements.  
> This repository focuses on **methodology, analysis workflow, and insight generation**, rather than raw data sharing.
> All analysis were discussed with the stakeholders although not endorsed by Apple Inc. 

---

### 1. Business Problem/Objective
---
- Mature Bluetooth audio market with intense competition  
- High volume of fragmented consumer feedback (reviews + surveys)  
- Limited data-backed understanding of:
  - Early purchase friction
  - Conversion drivers
  - Retention and repeat intent

**Goal:**  
Turn unstructured customer feedback into **actionable business insights** using a combination of qualitative & quantitative Python-based analytics:
  - Data VIsualizations
  - Traditional NLP/ML
  - LLM-assisted analysis

### 📊 2.Outcomes & Impact
---
- Identified customer journey friction points  
- Recommended actions to reduce early purchase friction (~8%)  
- Highlighted strong preference (~71%) for ecosystem-led positioning  
- Informed conversion strategy with data-backed insights  

Final deliverables focused on **decision-ready insights**, not deployment.

- Executive case summary (LinkedIn artifact / PDF): [https://www.linkedin.com/in/madhuram-ravichandran/overlay/1767840450470/single-media-viewer/](https://www.linkedin.com/in/madhuram-ravichandran/overlay/1767840450470/single-media-viewer/?profileId=ACoAAANJFTIBGuLan1TbHlSvC18Ua__Azx-qGWs)
- Presentation materials (optional future addition if needed)

### 3. Analysis Approach (Layered by Design)
---
Analysis was intentionally structured in increasing levels of complexity:

      Survey Analytics --> Traditional ML / NLP Sentiment Analysis --> GenAI/LLM-Based Insight Extraction & Visualization

This layered approach enabled:
- Pattern identification across large datasets
- Scalability of qualitative analysis
- Progressive refinement of insights for business decision-making


### 📂 4. Repository Structure & Notebook Walkthrough
---
The project is organized as a **notebook-driven analytical workflow**, reflecting the business scope and timeline of the externship.

**i. AmazonReviews_EDA.ipynb**: Exploratory Data Analysis
Purpose:
- Understand review distributions and metadata
- Identify recurring themes and patterns
- Surface early signals of customer friction
Key techniques:
- Text exploration
- Distribution analysis
- Review pattern discovery


**ii. DATA_Cleaning_Amazon_Reviews.ipynb**: Data Cleaning & Preprocessing
Purpose:
- Prepare unstructured text for modeling
- Ensure consistency and analytical reliability
Key steps:
- Normalization and filtering
- Handling duplicates and missing values
- Text preprocessing for NLP pipelines


**iii. Sentiment_Analysis.ipynb**: Traditional ML / NLP Sentiment Analysis
Purpose:
- Establish interpretable sentiment baselines
Techniques:
- TextBlob and VADER sentiment scoring
- Aggregation of sentiment by theme and intensity
- Comparison across product features and experience stages
Focus:
- Interpretability over raw accuracy
- Business relevance over model complexity


**iv. GEMENINAI_Sentiment_Analysis.ipynb**: LLM-Based Sentiment & Insight Extraction
Purpose:
- Scale qualitative insight discovery using LLMs
Approach:
- Prompt-driven LLM analysis to extract:
  - Key business themes
  - Sentiment analytics
  - Competitor insights
LLMs were used to **surface patterns**, not to decide conclusions.


**v. GEMINIAI_Viz.ipynb**: LLM Insight Visualization
Purpose:
- Translate LLM outputs into visual summaries
- Explore how this layer could feed into a future ML pipeline
Includes:
- Charts derived from LLM-based insights
- Exploratory visuals for executive storytelling

### 🛠️ Leveraging AI Coding Assistants
---
AI coding assistants were **actively encouraged and extensively used** throughout this project.

How AI was used:
- Generating draft code for:
  - Data transformations
  - Exploratory analysis
  - NLP workflows
- Accelerating iteration and experimentation

All insights were:
- Validated against data limitations
- Reviewed with stakeholders
- Modified or discarded when misaligned with business context

This reinforced that **AI improves productivity**, but **human judgment drives impact**.

### Future Extensions
---
If extended beyond the externship scope, next steps would include:
- Refactoring logic into reusable Python modules
- Introducing pipeline-based processing for larger data volumes
- Enabling periodic re-runs to refresh insights
- Stronger integration between ML outputs and business KPIs


### Key Skills Demonstrated
---
- Applied Machine Learning & NLP  
- LLM-assisted qualitative analysis  
- Python analytics workflows  
- Business-focused ML decision-making  
- Stakeholder communication & insight translation

---

*This project reflects my approach to applied ML:  
start simple, validate assumptions, iterate thoughtfully & collaboratively, and connect technical work to business stakeholders.*


