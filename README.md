# Market Reactions to FOMC Announcements

This capstone paper examines how financial markets respond to Federal Open Market Committee (FOMC) communication by combining high-frequency monetary policy surprises with FinBERT-based sentiment scores derived from post-meeting statements.

## 📄 Paper

* **[Capstone Paper](https://github.com/kmanu15/Market-Reactions-to-FOMC-Announcements-Captsone-/blob/main/Capstone_Paper.pdf)** – Full capstone paper (MQE, UCLA)

## 📌 Key Findings

1. **Monetary Policy Surprises Move Markets as Expected**
   * A 100 basis point hawkish ME surprise is associated with an 8.7–10.2% decline in S&P 500 returns within the event window.
   * Treasury yields rise across all maturities following a hawkish surprise, with the largest response at the 2-year maturity.

2. **Statement Sentiment Independently Drives Equity Returns**
   * FinBERT-based sentiment provides incremental explanatory power for S&P 500 returns even after controlling for the policy surprise.
   * More optimistic communication is associated with higher equity returns, suggesting tone functions as an independent signal about the economic outlook.

3. **Sentiment Conditions Treasury Yield Responses, Not Levels**
   * Statement tone does not independently shift the 10-year Treasury yield.
   * However, optimistic communication amplifies the yield response to hawkish directional surprises, while pessimistic tone attenuates it — consistent with a non-linear market correction mechanism.

## 💻 Code

* **[capstone.ipynb](https://github.com/kmanu15/Market-Reactions-to-FOMC-Announcements-Captsone-/blob/main/capstone.ipynb)** – Full analysis including data processing, FinBERT sentiment scoring, and event-study regressions

## 📊 Data

* **[U.S. Monetary Policy Event-Study Database (USMPD)](https://doi.org/10.24148/wp2025-30)** – High-frequency surprise measures from Acosta et al. (2025)
* **FinBERT Sentiment Scores** – Extended from Osowska & Wójcik (2023) through the most recent FOMC statement using the FinBERT model (Yang et al., 2020)
