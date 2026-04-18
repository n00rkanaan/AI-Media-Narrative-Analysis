# AI-Media-Narrative-Analysis
**Finalist — Rutgers RAISE-26 (Responsible AI for Social Empowerment) Competition**, selected as 1 of 9 undergraduate finalist teams out of 188 registered teams nationwide.

---

## Overview
This project analyzes how media narratives shape public perception of artificial intelligence.  

Using large-scale NLP techniques, we examine how AI is portrayed across thousands of news headlines and whether it is framed as enhancing human capabilities or challenging human autonomy.

---

## Research Question
**How does media portrayal of AI reflect and shape its impact on human behavior?**

---

## Key Insights
- AI coverage is event-driven  
  Media attention spikes during major breakthroughs and public debates  

- Sentiment varies by domain  
  - Science → mostly positive  
  - Finance → more negative  
  - Business and society → mixed  

- AI is framed in two main ways  
  - Enhancing human ability  
  - Challenging human autonomy  

- Majority framing favors augmentation  
  Media more often presents AI as assisting humans, while still highlighting autonomy concerns  

---

## Methods
We applied Natural Language Processing (NLP) techniques to analyze large-scale text data:

- **Semantic Embeddings**  
  - Model: all-MiniLM-L6-v2  
  - Captures meaning beyond keywords  

- **Clustering**  
  - Algorithm: KMeans  
  - Groups headlines into thematic narratives  

- **Sentiment Analysis**  
  - Model: DistilBERT (SST-2)  
  - Identifies positive vs negative tone  

- **LLM Classification**  
  - Model: DistilBART-MNLI  
  - Classifies whether AI is framed as:
    - Enhancing human agency  
    - Challenging human agency  

---

## Results
- Identified five major narrative clusters:
  - Scientific and medical applications  
  - Market predictions and finance  
  - Business adoption  
  - Operational optimization  
  - Societal impact  

- Found clear sentiment patterns by domain  
- Quantified AI framing (enhance vs challenge) across headlines  

---

## Data Note
The dataset used in this project is not publicly included due to access restrictions from the Rutgers RAISE competition.  

However, the methodology is reproducible using similar news datasets.

---

## Impact
This project demonstrates how media narratives:
- Influence public trust in AI  
- Shape adoption and resistance  
- Provide early signals for policy and ethical considerations  

---

## Recognition
Finalist — Rutgers RAISE Competition (2026)

---

## Team
- Noor Kanaan  
- Amy Arias  
- Justin Lema  
- Raynelis Villa  

---

## Future Work
- Analyze full article content instead of only headlines  
- Compare narratives across regions and media sources  
- Apply more advanced clustering and topic modeling  

---
