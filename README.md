# ✈️ AeroValue: Competitive Positioning Strategy via User-Generated Data

## 📊 Project Overview
The European low-cost carrier (LCC) market is highly profitable but structurally broken, defined by a massive "trust deficit" fueled by hidden fees and operational anxiety. 

This project provides a data-driven market entry roadmap for a challenger airline, **AeroValue**. By utilizing advanced text-mining and sentiment analysis on over 9,500 verified customer reviews alongside macro-level search trends, this analysis decodes the emotional and operational drivers of passenger satisfaction to locate an undefended, high-yield market opening.

**[👉 View the full interactive HTML Data Report here]**

## 🛠️ Tech Stack & Methodology
* **Language:** R
* **Data Collection:** Web Scraping (`rvest`), API Integration (`gtrendsR`)
* **NLP & Text Mining:** Sentiment Analysis (`syuzhet`), Tokenization (`tidytext`), Word Clouds
* **Statistical Modeling:** Multidimensional Scaling (MDS) for emotional positioning
* **Data Visualization:** `ggplot2`, Boxplots, Bar Distributions

## 💡 Key Insights
1. **The Bar is Incredibly Low:** Across major competitors (Ryanair, easyJet, Norwegian, Jet2), dissatisfaction exceeds 81%. Even market leaders leave a vast majority of customers unhappy.
2. **Hidden Fees Drive High "Anger":** Sentiment analysis reveals Ryanair dominates industry "Anger" scores, entirely driven by punitive gate fees (e.g., 55 EUR boarding pass charges) and strict baggage rules.
3. **Leisure Travelers Feel the Pain:** Text-mining confirms solo and couple leisure travelers generate the most negative reviews, specifically targeting algorithmic seat-splitting and gate-check anxiety.
4. **The "White Space" Market Gap:** MDS emotional mapping proves AeroValue can comfortably position itself in an undefended middle-ground: delivering the operational reliability and "Trust" of Jet2 without requiring the expensive premium hardware of Norwegian Air.

## 🎯 Strategic Recommendations (The 4Ps)
* **Product:** Implement a standardized "weekend backpack" allowance to eliminate gate-check anxiety and invest in proactive, automated re-booking via a mobile app.
* **Price:** Abandon "drip pricing." Introduce an all-in basic fare and a "togetherness guarantee" (free seating for couples) to eliminate industry-standard algorithmic penalties.
* **Place:** Avoid saturated mega-hubs (like Stansted or Gatwick) and utilize under-served secondary airports to lower Air Traffic Control friction and ensure smooth turnarounds.
* **Promotion:** Aggressively contrast AeroValue's transparent pricing with competitor hidden fees. Tagline: *"The fare you see is the fare you pay."*

## 📂 Repository Contents
* `/data`: Scraped review datasets for the 4 major airlines.
* `/notebooks`: The raw `.Rmd` script detailing the scraping, NLP, and modeling logic.
* `/docs`: The knitted interactive HTML report.
* `/presentation`: The executive slide deck summarizing the strategy.
