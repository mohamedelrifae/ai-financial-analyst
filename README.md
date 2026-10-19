# AI Financial Analyst 📊

I built an AI Financial Analyst that reads a company's financial filing and writes a full investment report, using RAG and AI agents.

## Demo

[![Watch the demo](https://img.youtube.com/vi/TUu2Vwz6Btk/maxresdefault.jpg)](https://youtu.be/TUu2Vwz6Btk)

## What it does
- Indexes the company's annual report (10-K) using RAG
- Three AI agents (CrewAI): Financial Analyst, Market Researcher, Investment Advisor
- Produces financial performance, valuation, SWOT, key risks, and a recommendation
- Built-in verification step (no AI): checks each cited number against the source PDF, recalculates growth rates, and flags any figure it cannot find

## Tech Stack
Python · CrewAI · RAG · Google Gemini API · Streamlit

## Limitations
- Market data (price, P/E, competitors) comes from the web and is not covered by the verification step
- The verification step confirms a number exists in the filing, not that its label is correct
- Tested on Apple and Toyota reports
- Runs on Gemini's free tier, so it can hit rate limits

## Disclaimer
Educational demo only, not financial advice.

📩 Source code available upon request.
