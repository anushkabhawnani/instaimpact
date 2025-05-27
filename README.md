# 📊 InstaImpact: Analyzing Instagram Content Effectiveness
InstaImpact is a data-driven analysis of Instagram content performance aimed at understanding what drives engagement. Using real data collected via Apify, this project explores how post types, caption length, sentiment, and hashtags correlate with likes and audience response.

## 🔍 Project Overview
This notebook-based project investigates:

* 📷 Post Types (Reel, Image, Carousel) and how they affect likes
* ✍️ Caption Sentiment & Length and their influence on engagement
* 🏷️ Hashtag Usage and common patterns in high-performing posts

The goal is to identify actionable insights for optimizing Instagram content strategies.

## 📌 Data Source
* Data was collected using the [Apify Instagram Scraper](https://apify.com/apify/instagram-scraper).
* Please ensure you comply with Apify's [Terms of Service](https://apify.com/legal/terms-of-service) and Instagram’s [Platform Policy](https://developers.facebook.com/terms) if reproducing the data collection process.

## 📈 Tools Used
* Python (Pandas, NumPy)
* Plotly for interactive data visualizations
* NLTK / Transformers for sentiment analysis using RoBERTa
* Jupyter Notebook for exploratory data analysis

## 📁 Project Structure
```
instaimpact/
│
├── instaimpact.ipynb       # Main Jupyter notebook with analysis & visuals
├── README.md               # Project documentation         
└── requirements.txt        # Python dependencies
```
## 📦 Setup Instructions
1. Clone the repository:
```
git clone https://github.com/anushkabhawnani/instaimpact.git
cd instaimpact
```
2. Install the required packages:
```
pip install -r requirements.txt
```
3. Launch the notebook:
```
jupyter notebook instaimpact.ipynb
```

## 📌 Conclusion
* **Short captions win:** Posts with <50 characters received the highest average engagement.
* **Reels outperform:** Reels consistently attracted more likes than static images or carousels.
* **Sentiment neutrality rules:** Neutral-toned captions were more prevalent and performed well.
* **Outliers matter:** A few viral posts can heavily skew engagement trends and should be treated carefully in analysis.

## 🚀 Future Work
* Expand dataset across multiple accounts or niches.
* Include engagement metrics beyond likes (e.g., shares, reach).
* Deep-dive into caption semantics using advanced NLP techniques.

## 🙌 Acknowledgements
* **Apify** – for enabling scalable Instagram scraping.
* **Plotly & Pandas** – for data wrangling and visualization.
* **NLP Libraries** – for sentiment analysis

## 📬 Contact
If you have questions, feedback, or would like to collaborate, feel free to reach out!
* [Email](anushkab1411@gmail.com)
* [Linkedin](https://www.linkedin.com/in/anushka-bhawnani-0a3207316/)
* [GitHub](https://github.com/anushkabhawnani)
