 **Insights, Conclusions & Recommendations**  
Derived from analysis of **15,000 food delivery orders** across 36 variables, 3 city tiers, and 12 months.

---

1\. Overall Performance Snapshot

| Metric | Value | Context |
| :---- | :---- | :---- |
| Total Orders | 15,000 | — |
| Total Revenue | $1,786,255.27 | — |
| Average Order Value | $113.95 | — |
| Average Delivery Time | 94.1 min | High — a clear area for improvement |
| Average Customer Rating | 3.99 / 5.0 | Below the 4.2–4.5 range of top platforms |
| Cancellation Rate | 13.35% | Elevated — industry leaders target \<8% |
| Delayed Delivery Rate | 9.47% | Directly tied to customer satisfaction |
| Refund Rate | 4.12% | Correlated with delays and cancellations |
| Promo Code Usage | 42.31% | Very high — suggests over-reliance on discounting |

**Takeaway:** The platform generates solid revenue but faces meaningful operational headwinds — particularly delivery time, cancellations, and customer ratings. These are addressable through targeted interventions.

---

**2\. City Tier Analysis**

| City Tier | Orders | Cancellation Rate | Avg Delivery Time | Avg Rating | Revenue Share |
| :---- | :---- | :---- | :---- | :---- | :---- |
| Tier 1 (Metro) | 3,723 | 13.6% | 94.2 min | 3.99 | 24.8% |
| Tier 2 (Urban) | 3,757 | 13.5% | 93.7 min | 3.99 | 24.9% |
| Tier 3 (Sub-urban) | 7,520 | 13.2% | 94.3 min | 4.00 | 50.2% |

![][image1]

**Key Findings**

- **Tier 3 dominates volume and revenue**, contributing more orders than Tier 1 and 2 combined — driven by population spread and less competition from brick-and-mortar dining.  
- **Cancellation rates are nearly identical across all tiers** (\~13–14%), confirming the issue is systemic rather than geography-specific. A platform-wide intervention would have more impact than a city-level fix.  
- **Metro cities do not outperform on delivery time** despite better road infrastructure — higher demand density cancels out the advantage.

**Recommendations**

- Prioritise **Tier 3 partner network expansion** — this segment generates the most revenue but likely has the fewest delivery partners per order.  
- Address cancellations platform-wide rather than by tier — better ETA prediction and pre-order stock checks would benefit all cities equally.

---

**3\. Delivery Performance**  
**3a. Traffic Impact**

| Traffic Level | Avg Delivery Time | Delay Rate |
| :---- | :---- | :---- |
| Low (1–3) | 86.9 min | 9.38% |
| Medium (4–6) | 93.8 min | 9.88% |
| High (7–10) | 99.7 min | 9.22% |

- Orders occurring during high-traffic periods were associated with delivery times that were 12.8 minutes longer on average.  — a 14.7% increase.  
- This has a direct customer experience cost: longer waits, colder food, lower ratings.

**3b. Weather Impact**

| Weather Severity | Avg Delivery Time | Delay Rate |
| :---- | :---- | :---- |
| Mild (0–3) | 88.5 min | 9.33% |
| Moderate (4–6) | 93.3 min | 9.96% |
| Severe (7–10) | 99.0 min | 9.20% |

- Severe weather adds **\~10.6 minutes** over mild conditions.  
- Delay rate doesn't spike as sharply as raw delivery time — suggesting customers may be more tolerant during bad weather, or partners adjust pace proactively.

**3c. Hourly Trends**

| Observation | Detail |
| :---- | :---- |
| Peak order volume | Midnight (00:00) — 659 orders |
| Highest cancellation hour | 00:00 at 16.24% |
| Second-highest cancellation | 05:00 at 15.60% |
| Most reliable window | 16:00–20:00 (evening rush) |

**![][image2]**

- **Late-night orders cancel at significantly higher rates** — partner unavailability, or impulse orders.  
- The standard dinner rush (18:00–20:00) is operationally the most reliable window.

**Recommendations**

- Implement **dynamic ETA buffers** at checkout that factor in live traffic and weather scores.  
- Add **late-night confirmation prompts** ("Your estimated wait is X min — confirm?") to reduce impulse cancellations.  
- Offer **late-night partner incentives** to improve supply during high-cancellation hours.

---

**4\. Customer Insights**  
**4a. Premium vs Non-Premium**

| Metric | Non-Premium | Premium | Difference |
| :---- | :---- | :---- | :---- |
| Avg Order Value | $110.16 | $123.643 | \+12.2% |
| Avg Final Paid | $115.28 | $128.80 | \+11.7% |
| Total Revenue | 1,242,595.34  | 543659.94 | \-56.248%  |
| Avg Discount Amount | 14.94  | 14.91  | Negligible |
| Cancellation Rate | 13.55%  | 12.84 | Negligible |

![][image3]

- Premium customers are **worth significantly more per transaction** but don't cancel less or rate higher.  
- While the promo code customers are worth more per transaction, most of the revenue comes from non-promo code users  
- The average discount amount is similar for both premium and non-premium customers indicating that users who are premium aren’t experiencing a unique benefit.  
- This means premium status is currently a **spending tier,**  — premium customers haven't been given reasons to feel more loyal through service quality.

**Recommendations**

- Build **premium-exclusive service features** (priority dispatch, dedicated support, guaranteed delivery windows) to convert higher spend into higher satisfaction and retention.  
- Use the premium segment to **pilot new features** before platform-wide rollout.

**4b. Loyalty Tier Segmentation**

| Loyalty Tier | Avg Order Value | Cancellation Rate | Promo Usage | Avg Discount Amount |
| :---- | :---- | :---- | :---- | :---- |
| Bronze (0–25) | $113.26 | 12.91% | 41.6% | 14.93 |
| Silver (26–50) | $113.80 | 13.27% | 42.32% | 14.81 |
| Gold (51–75) | $114.35 | 12.97% | 42.56% | 15.01 |
| Platinum (76–100) | $114.40 | 13.42% | 42.80% | 14.98 |

- **Loyalty score has almost no impact on order value or cancellation rate** — a significant finding. A well-designed loyalty programme should produce meaningful behavioural differences between tiers.  
- Promo usage is flat across all tiers (\~42%) and avg discount amount (+-0.2), meaning the programme is not differentiating incentive structures effectively.

**Recommendation**

- **Restructure the loyalty programme** to create genuinely distinct tier benefits (faster delivery, exclusive discounts, priority support).  
- Investigate why **Gold-tier customers cancel most frequently** (14.1%) — this cohort may be the most price-sensitive and expectations-driven.

**4c. Festival & Weekend Effect**

| Period | Avg Order Value | Avg Delivery Time | Cancellation Rate |
| :---- | :---- | :---- | :---- |
| Regular Days | $111.94 | 94.4 min | 13.51% |
| Festival / Weekend | $121.72 | 93.2 min | 12.76% |

- Festivals and weekends drive **8.7% higher order values** and marginally lower cancellations — customers are likely ordering larger group meals.  
- Delivery time is slightly faster on these days, suggesting partner supply scales reasonably well with demand.

**Recommendation**

- Run **targeted promotions on regular weekdays** to close the gap with festival/weekend performance.  
- Use **festival periods for upsell campaigns** (bundles, larger portions) to maximise the already-elevated spend intent.

---

**5\. Partner Performance**

| Experience Level | Avg Delivery Time | Efficiency Score | Delay Rate |
| :---- | :---- | :---- | :---- |
| Junior (1–3 yrs) | 93.79 min | 48.40 | 13.06% |
| Mid (4–7 yrs) | 94.25 min | 54.51 | 9.37% |
| Senior (8–11 yrs) | 94.17 min | 61.81 | 9.16% |
| Expert (12–15 yrs) | 94.24 min | 68.97 | 7.26% |

- **Partner experience has a surprisingly small effect** on delivery time.  
- Efficiency score and Delay rate improve the more experienced the partners are.  
- External factors (traffic, weather, distance) dominate over individual partner skill — meaning **route optimisation and dispatch algorithms matter more than partner tenure**.

**Recommendation**

- **Invest in dispatch and routing technology** rather than focusing solely on partner training — the data suggests algorithmic improvements will yield more impact.  
- Review the **efficiency score metric** — its near-uniformity across experience bands suggests it may not be capturing meaningful variation.

---

**6\. Revenue Analysis**

| Month | Revenue |
| :---- | :---- |
| January | $153,460 |
| August | $155,567 (peak) |
| November | $143,693 (lowest) |

![][image4]

- Revenue is relatively **stable throughout the year** with \~8.2% spread between peak and trough.  
- **August peaks** — likely driven by summer demand, outdoor events, and holidays.  
- **November underperforms** despite being pre-holiday season — warrants investigation.

**Recommendation**

- Investigate November's underperformance and plan a targeted **Q4 promotional push** to capture pre-holiday demand.  
- Study the August drivers and apply successful tactics to lower-performing months.

---

**7\. Top Strategic Recommendations**

| Priority | Action | Expected Impact |
| :---- | :---- | :---- |
| High | Dynamic ETA buffers for traffic and weather at checkout | Reduce expectation gap, improve ratings |
|  High | Late-night confirmation prompts \+ partner incentives | Potentially reduce late-night cancellations.  |
|  Medium | Restructure loyalty programme with meaningful tier benefits | Convert loyalty score into real behavioural change |
|  Medium | Launch premium-exclusive service features | Justify premium tier, improve retention |
|  Medium | Expand Tier 3 delivery partner network | Support the platform's largest revenue segment |
|  Lower | Q4 promotional campaign targeting November dip | Capture estimated $10–15K in incremental revenue |
|  Lower | Invest in dispatch routing algorithm improvements | Reduce delivery time without relying on partner experience |

---

**8\. Analytical Limitations**

- The dataset is **pre-cleaned** — real-world analysis would involve handling missing values, outlier treatment, and data validation.  
- **Correlation ≠ causation** — findings show associations (e.g. high traffic → longer delivery time) that should be validated with A/B testing before acting on.  
- **External benchmarks** are illustrative — actual performance should be assessed against this platform's own historical baselines.  
- The **loyalty programme structure is unknown** — conclusions assume a typical points-based model.  
- Some data in: “tip”, “customer rating”, and “delivery rating” values were left as such since it was uncertain whether these were zero value or if the data was missing; didn’t want to assume customer behavior.. 

---

**9\. Correlation Analysis**  
**9a. What Actually Drives Delivery Time?**  
A Pearson correlation was run across all key numeric variables against delivery time to identify which factors truly matter.

| Correlation Analysis — What Drives Delivery Time & Ratings? |  |  |
| :---- | ----- | :---- |
| Variable | Correlation with Delivery Time | Strength |
| Delivery Distance (km) | 86.39% | Very Strong Positive |
| Delivery Efficiency Score | \-81.92% | Very Strong Negative |
| Preparation Time (min) | 39.41% | Moderate Positive |
| Traffic Level Score | 16.35% | Weak Positive |
| Weather Severity Score | 13.62% | Weak Positive |
| Customer Rating | 0.69% | Negligible |
| Partner Experience(years) | 0.30% | Negligible |

**![][image5]**  
**The single biggest driver of delivery time is distance — by a wide margin.** A correlation of 0.86 means distance alone explains roughly 74% of the variation in delivery time. Traffic and weather, despite their intuitive importance, are comparatively weak individual predictors.

The delivery efficiency score's strong negative correlation (−0.82) makes sense by design — it's largely an inverse measure of delivery time relative to distance.

**Takeaway:** Optimising partner dispatch based on proximity to the customer will have more impact on delivery time than anything else. Partners who are geographically close to an order at the moment it's placed should be prioritised over experience level or rating.

---

**9b. Does Traffic Always Hurt Customer Ratings?**  
Intuitively you'd expect: more traffic → longer wait → lower rating. The data tells a different story.

| Rating vs Operational Conditions (near-zero correlations) |  |
| :---- | ----- |
| Condition | Correlation with Customer Rating |
| Traffic Level Score | 0.79% |
| Weather Severity Score | 0.05% |
| Delivery Time (min) | 0.69% |

**Customer ratings are essentially uncorrelated with every operational metric measured.** Ratings hover around 3.98–4.01 regardless of whether traffic is low or high, weather is mild or severe, or delivery took 50 minutes or 150 minutes.

This doesn't flatten — it's flat the entire way. Looking at ratings by individual traffic score values (1.0 through 10.0), the mean rating stays within a narrow 3.93–4.07 band throughout with no discernible trend.

**Possible explanations:**

- Customers may already expect delays during bad conditions and adjust their expectations accordingly  
- The rating system may suffer from **courtesy bias** — customers default to mid-range scores regardless of experience  
- The most dissatisfied customers may be expressing that via **cancellation rather than low ratings** — meaning the rating data only captures completed orders, which have a survivorship bias toward satisfied customers

**Takeaway:** Customer rating alone is a poor operational KPI for this platform. Cancellation rate and delay rate are more sensitive and honest signals of service quality.

---

**9c. The Compound Effect — Severe Weather \+ High Traffic**  
While traffic and weather are individually weak predictors of delivery time, they **compound meaningfully when combined.** This cross-tabulation shows distribution of cancellations and avg efficiency score.

| Distributions of Cancellations by Traffic Band x Weather Band |  |  |  |
| ----- | ----- | ----- | ----- |
| *COUNTA of Cancellation Flag* | *Weather Band* |  |  |
| *Traffic Band* | Mild Weather | Moderate Weather | Severe Weather |
| Low Traffic | 4.79% | 6.09% | 12.48% |
| Medium Traffic | 6.74% | 8.34% | 13.98% |
| High Traffic | 11.08% | 13.18% | 23.32% |

| Avg Efficiency Score by Traffic Band × Weather Band |  |  |  |
| ----- | ----- | ----- | ----- |
| *AVERAGE of Delivery Efficiency Score* | *Weather Band* |  |  |
| *Traffic Band* | Mild Weather | Moderate Weather | Severe Weather |
| Low Traffic | 76.67 | 70.11 | 62.39 |
| Medium Traffic | 67.34 | 62.58 | 53.70 |
| High Traffic | 58.72 | 51.59 | 45.07 |

**Key observations:**

- **Best-case scenario** (Low traffic \+ Mild weather):  76.67 average efficiency score, 4.79% cancellation distribution   
- **Worst-case scenario** (High traffic \+ Severe weather): 45.07 average efficiency score, **23.32% cancellation distribution**   
- That's a **\+31.6 increase** in delivery efficiency and a **\+18.53 percentage point** spike in cancellations between ideal and worst conditions  
- The High Traffic \+ Severe Weather cell contains the largest distribution of cancellations and also the least efficient delivery score.

**The relationship is additive, not exponential.** Each adverse condition contributes its own independent penalty to delivery time — they don't amplify each other beyond their individual effects. This is actually useful operationally: a model that adds a fixed traffic penalty and a fixed weather penalty to a base ETA estimate would be a reasonable approximation of actual delivery time.

**The cancellation distribution, however, shows a sharper non-linear jump.** Moving from Medium/Moderate (8.34%) to High/Severe (23.32%) is a disproportionately large step — suggesting customers have a tolerance threshold, and when both conditions are bad simultaneously, cancellations spike beyond what either condition produces alone.

**Recommendation:** Build a **real-time risk score** combining traffic and weather severity. When both exceed their respective midpoints simultaneously, trigger proactive communication to customers ("Conditions are challenging tonight — your order may take longer than usual") to manage expectations and reduce reactive cancellations.

---

**9d. Distance is Linear — and the Gap is Large**  
Splitting delivery distance into five equal-sized quintiles reveals a clean, near-linear relationship with delivery time:

| Distance Quintile | Avg Distance | Avg Delivery Time | Delay Rate |
| :---- | :---- | :---- | :---- |
| Q1 (shortest) | 5.3 km | 56 min | 8.79% |
| Q2 | 14.93 km | 81 min | 9.41% |
| Q3 | 25.09 km | 106 min | 8.39% |
| Q4(longest) | 35.05 km | 132 min | 10.26% |

![][image6]  
Each \~10km increase in distance adds roughly **20 minutes** of delivery time with near-perfect consistency. The delay rate, however, is relatively flat across quintiles (\~9%), meaning long-distance orders are not disproportionately delayed — they simply take longer by design.

**Takeaway:** Distance-based delivery fee tiers and ETAs are well-justified by the data. A maximum delivery radius policy could be considered — orders beyond 30km take over 2 hours on average, which is likely to hurt satisfaction regardless of conditions.

---

**10\. What I'd Do With More Data**  
The current dataset is rich, but several analytical questions remain unanswerable without additional data. These represent the natural next steps for deeper analysis:

**Customer-level data**

- With persistent customer IDs across multiple orders, I could calculate **repeat order rate** and **customer lifetime value (CLV)** — the most important metrics for any subscription or loyalty-adjacent platform  
- Knowing whether a customer who cancelled eventually re-ordered (or churned) would allow a proper **churn prediction model**  
- Tracking a customer's rating history over time would reveal whether satisfaction is declining, improving, or stable — the current snapshot can't tell us this

**Restaurant / kitchen-level data**

- The current dataset has “preparation time” but no restaurant identifier. With restaurant IDs I could identify which **specific kitchens are driving preparation delays** — the 0.39 correlation between prep time and delivery time suggests this would be high-value  
- Restaurant-level cancellation rates would reveal whether certain partners are responsible for a disproportionate share of order failures

**Delivery partner granularity**

- Partner experience has negligible correlation with performance (r=0.003), but that's a blunt instrument. With individual partner IDs I could identify **outlier performers** — partners who consistently beat their expected delivery time given distance and conditions  
- This would enable a proper **performance-based dispatch model** rather than the proximity-only recommendation above

**Real-time and sequential data**

- The current data is order-level snapshots. With **timestamped event logs** (order placed → accepted → picked up → delivered) I could pinpoint exactly where time is being lost — whether delays happen between order placement and pickup, or between pickup and delivery  
- This distinction matters enormously: a prep-time delay requires a restaurant intervention; a transit delay requires a routing intervention

**Pricing and elasticity data**

- The flat loyalty tier behaviour (near-identical order values across Bronze–Platinum) might be explained by uniform pricing. With **A/B test data** on discount levels or delivery fee thresholds, I could model price elasticity and determine the optimal discount structure per segment

**What this analysis can't conclude**

- Whether the 13.35% cancellation rate is improving or worsening over time — there's no historical baseline  
- Whether high-loyalty customers were always high-loyalty or were converted by the programme  
- Whether the premium tier was self-selected or assigned — which affects how to interpret the spend differential

---

*Analysis by \[Max Chang-Leng\] · Dataset: food\_delivery\_analytics\_cleaned.csv · 15,000 orders · 36 variables*  


