# MarketLens

# AI-Powered Retail Risk Intelligence System

## Overview
Retail investors in the Indian stock market face a major information disadvantage compared to institutional participants. While institutions rely on ownership trends, delivery data, bulk/block deals, and sentiment analytics, retail traders are often driven by news headlines, social media hype, influencer recommendations, and price movements. This imbalance exposes retail investors to manipulation-driven market behavior, commonly referred to as **retail traps**, where retail buying increases as institutions silently exit.

This project aims to bridge that gap by providing **institutional-grade risk intelligence** to retail investors using data analytics and AI.

---

## Problem Statement
Market manipulation in the form of pump-and-dump schemes, fake volume rallies, and coordinated positive news cycles is increasing. Although critical data such as shareholding patterns, delivery percentages, institutional activity, and news sentiment exists, it is:
- Scattered across multiple platforms  
- Unstructured and difficult to analyze  
- Not available in an actionable, real-time format  

As a result, most retail investors react late, follow herd behavior, and incur consistent losses.

---

## Solution
We propose an **AI-powered Risk Intelligence System** that detects retail traps and manipulation by unifying multiple data signals into a single dashboard. The system analyzes ownership shifts, market activity anomalies, and AI-driven news sentiment to generate clear, explainable risk scores for each stock. This enables retail investors to identify high-risk scenarios early and make informed, data-backed decisions instead of relying on hype.

---

## Key Features
- Ownership analytics (Promoter, FII/DII, Retail, Pledge %)
- Market activity forensics (Delivery %, Volume–Price anomalies, Bulk/Block deals)
- AI-powered news sentiment analysis (FinBERT)
- Retail Trap Probability & Market Integrity Scores
- Explainable AI-generated insights
- Unified dashboard for real-time monitoring

---

## System Architecture
1. **Data Collection**
   - Shareholding patterns
   - NSE market activity data
   - Financial news headlines
   - Historical price and volume data

2. **Signal Computation**
   - Detection of red flags (institutional exits, fake rallies, sentiment–fundamental divergence)
   - Identification of positive accumulation patterns

3. **AI Reasoning Layer**
   - Sentiment scoring and hype detection
   - Risk classification (Low / Medium / High)
   - Natural-language explanation generation

4. **User Dashboard**
   - Visual analytics, risk scores, and alerts in one interface

---

## Tech Stack
- **Languages:** Python, JavaScript  
- **Backend:** FastAPI  
- **AI & NLP:** Hugging Face (FinBERT), LangGraph  
- **Data Collection:** Selenium, Beautiful Soup, yfinance  
- **Frontend:** Next.js  
- **Design:** Figma  
- **Execution:** OnDemand  

---

## Impact
- Empowers retail investors with institutional-grade insights  
- Helps avoid manipulation-driven trades  
- Encourages rational, data-driven decision-making  
- Improves transparency in retail participation  



