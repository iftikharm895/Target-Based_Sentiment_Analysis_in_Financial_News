# Leveraging Large Language Models for Target-Specific Sentiment Analysis in Financial News

## 📌 Project Overview
This research advances target-based financial sentiment analysis (TBFSA) by evaluating Large Language Models (LLMs) in zero-shot / few-shot learning paradigms. We benchmark state-of-the-art LLMs against traditional approaches: 

| Category | Models |
|----------|--------|
| **LLMs** | GPT-4, GPT-4o, GPT-o1, DeepSeek-R1, Llama-3-8B, Gemma-2-9B, Gemma-2-27B |
| **Fine-Tune Transformer-Based Models** | FinBERT, FinBERT-Tone, DistilFinRoBERTa, DeBERTa v3-base-ABSA-V1.1 |
| **Lexicon-Based Methods** | VADER, TextBlob |

## 📂 Dataset Discription
The dataset contains financial news articles about major stock companies (Alphabet, Amazon, Netflix, Nvidia) collected from the Bloomberg Terminal. Each article was manually annotated by three annotators for: 1.**Target Entity Identification** 2. **Target-Specific Sentiment Labeling**  
### Dataset Structure:
#### Format: CSV  
#### Columns:  
o	Publishing Date: Article publication date  
o	Publishing Time: Article publication time  
o ID: Unique news article identifier  
o	Target: The company to which the sentiment analysis applies.   
o	URL: The direct link to the full news article  
o	Manual: The manually assigned sentiment score (-1 = Negative, 0 = Neutral, +1 = Positive) reflects the evaluated sentiment toward the target  

**Source:** Bloomberg Terminal (September 4, 2023, to January 30, 2024)  
**Size:** 1,334 manually annotated news texts    
**Targets:** Alphabet, Amazon, Netflix, Nvidia    

**Annotation Quality:**  
- Entity Identification: Krippendorff's α = 0.96
- Sentiment Labels: Krippendorff's α = 0.81
  
**Access Note:** Full text distribution restricted by copyright - URLs provided for reproducibility via Bloomberg Terminal access.
  
## 📝 Annotation Guidelines 
The annotation process for target-based financial sentiment analysis—covering entity identification and target-specific sentiment labeling—followed detailed guidelines documented in Annotation_Guidelines.docx.
