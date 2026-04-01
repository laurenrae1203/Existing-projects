# ============================================================
# README: social-media-engagement-analysis
# ============================================================
# Save this file as README.md inside that GitHub repo

# 📱 Social Media Engagement Analyzer

A Python analysis of 500 simulated social media posts to uncover what drives the highest engagement across platforms, content types, and days of the week.

## 🔍 Key Findings
- **Video content** generates the highest engagement rate — significantly outperforming text and image posts
- **Midweek posts** (Tuesday–Thursday) outperform weekend posts for total engagement
- **TikTok and Instagram** lead all platforms in engagement rate; LinkedIn excels in quality shares
- **Reach strongly correlates with engagement**, making paid amplification worthwhile for top-performing posts

## 📊 What's in the Notebook
- Dataset generation (500 posts across 5 platforms and 5 content types)
- Engagement rate by content type — bar chart
- Best days to post — day-of-week bar chart
- Platform comparison — dual chart (engagement rate + metric breakdown)
- Reach vs. Engagement scatter plot
- Summary table with actionable recommendations

## 🛠️ Tools Used
Python · Pandas · NumPy · Matplotlib · Seaborn

## ▶️ How to Run
1. Clone this repo or open in [Google Colab](https://colab.research.google.com)
2. No external data needed — the dataset is generated inside the notebook
3. Run all cells top to bottom

---

# ============================================================
# README: customer-sentiment-analysis
# ============================================================
# Save this file as README.md inside that GitHub repo

# 💬 Customer Sentiment Analyzer

A Python tool that uses NLP to classify 300 customer reviews as **Positive**, **Neutral**, or **Negative**, then surfaces brand insights by product category.

## 🔍 Key Findings
- The majority of reviews are Positive — overall brand sentiment is healthy
- **Electronics** has the highest proportion of negative reviews, pointing to a potential quality or returns issue
- **Skincare** leads all categories in positive sentiment — a strong signal to increase content investment there
- Mean polarity score is positive, confirming strong overall brand reputation

## 📊 What's in the Notebook
- 300-review dataset across 4 product categories (Skincare, Electronics, Fitness, Apparel)
- Sentiment scoring using TextBlob (polarity scale from −1 to +1)
- Sentiment breakdown pie chart
- Category-level sentiment comparison bar chart
- Top 5 most positive and most negative reviews
- Polarity score distribution histogram

## 🛠️ Tools Used
Python · TextBlob · Pandas · Matplotlib · Seaborn

## ▶️ How to Run
1. Clone this repo or open in Google Colab
2. The notebook installs `textblob` automatically on first run
3. No external data needed — reviews are built into the notebook

---

# ============================================================
# README: marketing-ab-test-analysis
# ============================================================
# Save this file as README.md inside that GitHub repo

# 🧪 Marketing Campaign A/B Test Analysis

A statistical analysis comparing two email marketing campaign variants (10,000 total subscribers) to determine which drives significantly better open rates, click-through rates, and conversions.

## 🔍 Key Findings
- **Campaign B (story-driven)** outperforms Campaign A (discount-led) on every metric
- Open Rate lift: **+28%** — statistically significant ✅
- Click-Through Rate lift: **+33%** — statistically significant ✅
- Conversion Rate lift: **+54%** — statistically significant ✅
- At scale (100K subscribers), Campaign B generates an estimated **$X more revenue**

## 📊 What's in the Notebook
- Simulated dataset of 10,000 subscriber interactions across 2 campaign variants
- Side-by-side bar chart comparison (Open Rate, CTR, Conversion Rate)
- Two-proportion z-test for all three metrics (α = 0.05)
- Lift visualization — green = statistically significant
- Revenue impact estimate and scale projection

## 🛠️ Tools Used
Python · SciPy · Pandas · NumPy · Matplotlib · Seaborn

## ▶️ How to Run
1. Clone this repo or open in Google Colab
2. No external data needed — data is generated inside the notebook
3. Run all cells top to bottom

---

# ============================================================
# README: hashtag-performance-analyzer
# ============================================================
# Save this file as README.md inside that GitHub repo

# #️⃣ Hashtag Performance Analyzer

A Python analysis of 400 Instagram posts across 20 hashtag categories, ranking each hashtag by engagement, engagement rate, reach, and saves to build a smarter content strategy.

## 🔍 Key Findings
- **#travelgram** and **#skincareroutine** dominate total engagement volume
- Engagement Rate reveals niche hashtags often outperform popular ones per impression
- **Saves** (bookmarks) are highest for recipe and skincare hashtags — signaling high-utility content
- The optimal hashtag strategy uses a tiered mix: Power Tags + ER Stars + Save Drivers

## 📊 What's in the Notebook
- 400-post dataset across 20 hashtags with Likes, Comments, Shares, Saves, and Reach
- Top 10 by Average Engagement — horizontal bar chart
- Top 10 by Engagement Rate — horizontal bar chart
- Engagement type breakdown (Likes / Comments / Shares / Saves) per hashtag
- Reach vs. Engagement bubble scatter plot
- Full hashtag scorecard table
- Tiered hashtag strategy recommendation

## 🛠️ Tools Used
Python · Pandas · NumPy · Matplotlib · Seaborn

## ▶️ How to Run
1. Clone this repo or open in Google Colab
2. No external data needed — dataset is generated inside the notebook
3. Run all cells top to bottom
