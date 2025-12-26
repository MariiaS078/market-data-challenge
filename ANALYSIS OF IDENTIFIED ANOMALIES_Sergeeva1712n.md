 **ANALYSIS OF IDENTIFIED ANOMALIES**

**1\. ETH/BTC Price Over Time**

**Specific Anomalous Periods**

1.  **September 1 – early September 2**
    - Price declines from approximately **0.0410 BTC to 0.0400 BTC**
    - The drop occurs in discrete steps rather than a smooth downward trend
2.  **September 2 – early September 3**
    - Continued price decrease to around **0.0390 BTC**
    - Several sharp short-term downward spikes are visible
3.  **September 3 (morning to midday)**
    - Rapid recovery from approximately **0.0390 BTC to 0.0398 BTC**
    - The speed of recovery exceeds that of a typical organic correction

**Interpretation**

Such abrupt price changes are consistent with **aggressive order execution** or **liquidity gaps**, rather than organic market consensus. This behavior is often observed in environments with aggressive execution strategies, temporary liquidity gaps, or sudden information shocks.

**2\. Abnormal Volume Spikes**

**Observations**

Trade sizes are highly uneven, with frequent isolated spikes exceeding **600–700 units**, while the majority of trades remain significantly smaller.

Higher concentrations of large trades are observed around:

- **September 1, ~12:00**
- **September 2, ~12:00**
- **September 3, ~12:00**

**Detected anomaly**

- Repeated large-volume trades appear sporadically throughout the dataset, particularly during periods of price movement acceleration.

**Interpretation**

Such volume spikes may indicate:

- Execution of large hidden orders,
- Algorithmic slicing of large positions,
- Potential **wash trading** or artificial volume inflation.

The lack of smooth volume distribution supports the presence of non-random trading behavior.

**3\. Sharp Price Movements (Pump-and-Dump Patterns)**

**Observations**

Several sharp downward and upward price movements are detected, exceeding normal return thresholds.

**September 1 (Morning)**

- Short-term price fluctuations around **0.0410 BTC**
- Sudden downward moves followed by immediate recoveries

**September 2 (Late Night)**

- Abrupt decline from approximately **0.0398 BTC to 0.0394 BTC**
- Limited consolidation following the movement

**September 3 (Morning)**

- Sharp drop to approximately **0.0389 BTC**
- Followed by a rapid upward correction

**Interpretation**

These patterns are characteristic of short-term price dislocation events, often observed in momentum-ignition or stop-triggering environments

**4\. Order Book Imbalance**

**Observations**

The imbalance oscillates between negative and strongly positive values, with several abrupt regime shifts.

**Early September 1**

- Imbalance remains negative **(~ −0.003 to −0.002)**, indicating sell-side dominance

**Mid September 1 (06:00–12:00)**

- Sudden reversal from negative to positive imbalance **(~ +0.0015)**
- The transition occurs almost instantaneously

**September 2 – Early September 3**

- Sustained positive imbalance **(~ +0.003 to +0.0045)**, indicating prolonged buy-side pressure

**Mid September 3**

- Large spike to approximately **+0.007**, followed by unstable fluctuations

**Detected anomaly**

- **September 3:** Imbalance reaches values above **0.006**, indicating significantly more bid liquidity than ask liquidity.
- Earlier periods show negative imbalance, suggesting selling pressure.

**Interpretation**

Sudden shifts in order book imbalance suggest non-organic liquidity signaling behavior, such as spoofing or strategic order placement..., such as spoofing or strategic order placement, intended to influence market sentiment without execution.

**5\. Trade Size Distribution**

The distribution of trade sizes is **highly right-skewed**, with the presence of extreme outliers.

**Key Observations**

- The majority of trades are clustered between **0 and ~50 units**
- A long tail extends to approximately **700 units**
- A limited number of very large trades (**\>500 units**) are clearly visible

**Observations**

The distribution is **highly right-skewed**, with:

- A large mass of very small trades,
- A long tail of rare but extremely large trades.

**Interpretation**

This structure is typical of markets influenced by **algorithmic and strategic traders**, where small trades probe the market while large trades move prices. The heavy tail increases the likelihood of price impact anomalies.

**6\. Trade Clustering Over Time**

**Late September 1 – Early September 2**

- Trade count spikes to approximately **15 trades per interval**, compared to a baseline of **1–2**

**Mid September 2**

- Additional cluster reaching approximately **10 trades**

**Mid September 3**

- Repeated sharp spikes around **8–10 trades**

**Observations**

Trade activity is not uniformly distributed. Instead, it occurs in **bursts**, with isolated spikes reaching **10–15 trades per interval**.

**Detected anomaly**

- **September 1–2:** Several dense clusters of trades appear in short intervals.
- Extended periods of low activity are followed by sudden bursts.

**Interpretation**

Trade clustering is a known indicator of **coordinated trading**, often associated with algorithmic execution, momentum ignition, or manipulation strategies.

**7\. Buy vs Sell Trade Imbalance**

**1\. September 1 (approximately 10:00–14:00)**

- **Sell trades spike** from a baseline of **0–1 trades/min** to a peak of approximately **14 trades/min**
- Buy trades during the same period remain at **~0–1 trades/min**
- Net imbalance reaches approximately **−13 trades/min** (sell-dominated)

This represents a **\>10× increase** relative to baseline activity.

**2\. September 2 (approximately 11:00–13:00)**

- Sell-side trades increase abruptly to approximately **9–10 trades/min**
- Buy-side trades remain low at **0–2 trades/min**
- The spike duration is short-lived (tens of minutes), followed by a rapid return to near-zero activity

This indicates **concentrated sell pressure**, not sustained participation.

**3\. September 3 (approximately 11:30–13:00)**

- Buy-side trades spike to approximately **10 trades/min**
- Sell-side trades remain below **1–2 trades/min**
- Net imbalance flips to approximately **+8 to +9 trades/min** (buy-dominated)

**Observations**

Extended intervals show strong dominance of one trade direction.

**Detected anomaly**

- **September 1:** SELL trades peak at **14 trades per minute**, with minimal BUY activity.
- **September 3:** BUY trades dominate, reaching **10 trades per minute**.

**Interpretation**

Directional dominance suggests **accumulation or distribution phases**, potentially driven by large players strategically entering or exiting positions.

**8\. Rolling Price Volatility**

**1\. September 1 – Early September 2**

- Rolling volatility fluctuates between approximately:
    - **0.0024 (lower bound)**
    - **0.0029 (upper bound)**
- Average volatility during this phase: **~0.0026**

This represents a **high-volatility regime**, consistent with unstable price formation.

**2\. September 2 (Midday)**

- Volatility drops sharply from approximately **0.0023** to **0.0008**
- Absolute decrease: **~0.0015**
- Relative decrease: **~65%**

Such a sharp contraction occurs over a short time window, rather than gradually.

**3\. September 3 (Late Morning to Midday)**

- Volatility spikes from approximately **0.0015** to a peak of **~0.0031**
- Absolute increase: **~0.0016**
- Relative increase: **~107%**

This is the **highest volatility level** observed across the entire period.

**4\. Late September 3**

- Volatility collapses from **~0.0014** to **~0.0006**
- Relative decrease: **~57%**
- Occurs rapidly, not through progressive normalization

**Numerical Interpretation**

- Low-volatility regime: **0.0006–0.0010**
- High-volatility regime: **0.0024–0.0031**
- Regime shift magnitude: **2×–3×**
- Transitions occur abruptly, often within short time spans

**Interpretation**

This pattern reflects **temporary market instability**, often caused by sudden order flow imbalances or aggressive trading strategies.

**9\. Price Change vs Trade Size**

**1\. Small Trades (0–20 units)**

**Observed behavior:**

- Trade sizes clustered between **0 and ~20**
- Price returns range from approximately:
    - **−0.010 to +0.005**
- Extremely high dispersion relative to trade size

**Interpretation:**

Very small trades are associated with **disproportionately large price movements**. This suggests:

- Low liquidity at the top of the order book
- Sensitivity to micro-orders
- Potential quote manipulation or rapid order placement/removal

In a liquid market, trades of this size would typically have **near-zero price impact**.

**2\. Medium Trades (20–300 units)**

**Observed behavior:**

- Dense cluster between **20 and ~300 units**
- Price returns mostly constrained within:
    - **−0.003 to +0.003**
- Highest point density occurs around:
    - Trade sizes **~50–150**
    - Price return **~0.000**

**Interpretation:**

This range represents the **most stable execution regime**:

- Trades are large enough to be absorbed by liquidity
- Price discovery appears relatively efficient
- This likely reflects “normal” market behavior

This cluster serves as a **baseline** for comparison.

**3\. Large Trades (300–700 units)**

**Observed behavior:**

- Sparse but clearly visible points between **300 and 700 units**
- Price returns expand again, reaching approximately:
    - **−0.005 to +0.008**
- Several outliers observed:
    - Around **500–600 units**, price returns exceed **+0.005**
    - One extreme positive outlier near **~500 units** reaches **~+0.013**

**Interpretation:**

Large trades exhibit **renewed price impact**, indicating:

- Liquidity exhaustion
- Market depth limitations
- Potential intentional price movement

Such trades are capable of **moving the market**, rather than passively executing.

**Key Anomalous Characteristics**

**Non-Monotonic Price Impact**

Instead of price impact increasing smoothly with trade size:

- Very small trades → **high relative impact**
- Medium trades → **low impact**
- Very large trades → **high impact again**

This **U-shaped relationship** is atypical for purely organic markets.

**Final Assessment**

Taken together, the nine identified anomalies form a **coherent and mutually reinforcing pattern**. The market behavior during the analyzed period is best characterized as:

- structurally unstable,
- dominated by strategic or algorithmic participation,
- and only partially driven by organic price discovery.

While the analysis does not assert malicious intent, the observed dynamics are **consistent with environments where market participants actively influence price behavior**, rather than passively respond to it.
