# **Textual Variance and Speed Analysis using BERT**

## 📌 **Project Overview**
This project explores the relationship between **text speed, circuitousness, and engagement** in **brand social media posts**. By leveraging **BERT transformers** and **word embedding techniques**, we analyze how text structure influences user engagement across **60K+ tweets and Instagram posts**. This work was conducted under the guidance of Professor Jeffrey Lee as part of a research study on analyzing tweets and Instagram posts for luxury brands from 2022 Fall to 2023 Spring.



## 🏆 **Key Contributions**
- **Developed a BERT-based model** to compute **text speed** and **circuitousness**, discovering that higher circuitousness and lower speed boost customer engagement.
- **Scraped 60K+ tweets** using **BeautifulSoup** and extracted **textual variance metrics** through **lemmatization and word embedding**.
- **Applied NLP techniques** to analyze **25-brand post sets**, revealing that textual diversity leads to **higher brand engagement levels**.

## 🚀 **Technologies & Tools**
- **Python (NLP & ML Libraries)** – `sentence-transformers`, `nltk`, `scikit-learn`
- **Deep Learning** – `BERT transformers`
- **Web Scraping** – `BeautifulSoup`, `requests`
- **Data Processing & Analysis** – `Pandas`, `NumPy`, `Matplotlib`
- **Optimization Techniques** – `Google OR-Tools`, `scipy.spatial.distance`

## 📂 **Project Structure**
```
📺 Textual_Variance_Analysis
 ├️ 📂 data                 # Collected dataset (tweets, Instagram posts)
 ├️ 📂 models               # Trained BERT and word embedding models
 ├️ 📂 notebooks            # Jupyter/Colab notebooks for processing
 ├️ 📂 scripts              # Python scripts for text analysis
 ├️ 📝 README.md            # Project documentation (this file)
 ├️ 📝 preprocess.py        # Text preprocessing and tokenization
 ├️ 📝 embedding_analysis.py # Word embedding & variance analysis
 ├️ 📝 engagement_analysis.py # Engagement metric calculations
 ├️ 📝 BERT_model.py        # BERT-based text circuitousness computation
```
Notice ⚠️： some of the .py files and data might be missing in this repository, as they require access permission from the professor. However, running the .ipynb file relies on these. Please request access from Professor Jeffrey Lee if needed.

## 🔍 **Methodology**
1. **Data Collection**:
   - Scraped **60K+ tweets and Instagram posts** using **BeautifulSoup**.
   - Extracted **textual features** from 25-brand datasets.

2. **Text Processing & NLP Analysis**:
   - Applied **tokenization, lemmatization, and stopword removal**.
   - Used **BERT word embeddings** to compute **semantic variance**.
   - Performed **POS (Part-of-Speech) tagging**.

3. **Text Speed & Circuitousness Computation**:
   - Calculated **sentence-level textual distance** using **word embeddings**.
   - Used **Google OR-Tools** for **TSP-based sentence reordering analysis**.
   - Measured **average sentence speed** and **circuitousness**.

4. **Engagement Prediction & Insights**:
   - Regressed textual features against **likes, shares, and engagement rate**.
   - Found a **strong inverse correlation** between **text speed & engagement**.
   - Discovered **high variance in sentence structure improves engagement**.

## 📊 **Results & Findings**
- **Brands with higher textual variance** (across 25 posts) had **higher audience engagement**.
- **Posts with greater circuitousness** (i.e., more complex sentence structures) received **more likes and shares**.
- **Text speed had an inverse effect on engagement**, with slower, well-structured posts performing better.

### 📈 **Sample Computation Output**
| Post ID  | Engagement Rate | Text Speed | Circuitousness |
|----------|----------------|------------|---------------|
| 1        | 0.0064         | 364.25     | 1.78          |
| 2        | 0.0075         | 368.07     | 2.12          |
| 3        | 0.0081         | 429.82     | 2.05          |
| 4        | 0.0176         | 421.99     | 2.58          |

## 🎯 **Future Enhancements**
- **Integrate GPT-based text summarization** for better analysis.
- **Expand dataset** to different industries for broader insights.
- **Develop a web dashboard** to visualize textual variance in real-time.

## 🤝 **Contributors**
- **Lesley Zhao** - [GitHub](https://github.com/lesleyzhao)
- **Professor Jeffrey Lee** (Research Advisor)

