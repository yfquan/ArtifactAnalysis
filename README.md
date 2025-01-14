# **Artifact Analysis in Egg Inc.**
*January 2, 2025*

## **Introduction**
**Egg, Inc.** is an idle game where players build and optimize their egg farms. The game features several key mechanics, including:
- **Hen Houses**: Increase chicken capacity and egg production.
- **Vehicles**: Improve egg transportation efficiency.
- **Research**: Unlocks upgrades that boost egg value and farm productivity.
- **Artifacts**: Special items that enhance gameplay with various bonuses.

Artifacts play a crucial role in **boosting egg production and earnings**. They come in different **rarities** (Common, Rare, Epic, Legendary) and **tiers** (T1 to T4). Players can obtain artifacts in two ways:
1. **Spaceship Missions** – Launching missions from the home farm.
2. **Crafting** – Using the Hall of Artifacts to create and upgrade artifacts.

### **Objective of the Analysis**
This report examines the **effectiveness of targeting specific artifacts** via spaceship missions. Key questions include:
- How effective is **spaceship targeting** in acquiring specific artifacts?
- Does targeting improve the drop rate of **Legendary artifacts**?
- When is **crafting** a better alternative than direct spaceship drops?

---

## **Data Collection**
The dataset originates from **player-submitted spaceship data**, aggregated via Discord and the Egg, Inc. data tracker.

### **Data Fields**
- **Ship Type**: Type of spaceship used.
- **Ship Duration**: Length of the mission.
- **Target Artifact**: The artifact the player aimed to obtain.
- **Collected Artifact Data**: Includes tier, rarity, and total number of drops.

---

## **Key Findings**

### **1. Spaceship Targeting and Artifact Drop Rates**
- Spaceships **return more artifacts when targeting specific ones**.
- However, **Legendary drop rates remain relatively constant**, regardless of targeting.
- Certain artifacts (e.g., **Demeter’s Necklace, Beak of Midas**) saw a **3-4x increase** in drop rates when targeted.

### **2. Legendary Artifact Drop Rates**
- Most artifacts show **higher drop rates when targeted**, but not all.
- **Light of Eggendil and Ship in a Bottle** drop so infrequently that **targeting them is ineffective**.
- **Targeting certain artifacts may reduce the drop rates of other legendaries**.

### **3. Statistical Testing**
Two statistical methods were used to analyze drop rate differences:
1. **Two-Proportion Z-Test** – Checks if targeting significantly affects drop rates.
2. **Simulation-Based Testing** – Models random drop distributions to test for anomalies.

Results:
- **Targeting significantly increases artifact drops** for most items.
- **Some artifacts show no meaningful benefit from targeting**.

### **4. Time Required for Legendary Artifacts**
- On average, **players need weeks to months** of spaceship launches to obtain a **single Legendary artifact**.
- **The most efficient artifacts to target** for legendaries are:
  - **Demeter’s Necklace**
  - **Aurelian Brooch**
  - **Neodymium Medallion**
  - **Beak of Midas**

---

## **Artifact Drop Rate Summary**
| **Artifact**         | **Untargeted Drop Rate (%)** | **Targeted Drop Rate (%)** | **Increase (%)** |
|----------------------|---------------------------|---------------------------|----------------|
| **Demeter’s Necklace** | 1.42% | 5.55% | **+390.4%** |
| **Beak of Midas**     | 0.53% | 1.99% | **+378.1%** |
| **Aurelian Brooch**   | 0.96% | 3.59% | **+373.3%** |
| **Neodymium Medallion** | 0.96% | 3.58% | **+373.2%** |
| **Mercury’s Lens**    | 0.03% | 0.11% | **+367.7%** |

- **Legendary drops remain extremely rare** even when targeting.
- **Some artifacts have diminishing returns from targeting**.

---

## **Conclusions & Recommendations**
1. **Targeting boosts artifact drop rates**, but the effectiveness varies.
2. **Legendary artifacts remain extremely difficult to acquire**, even when targeted.
3. **Crafting may be a more viable option** for some high-value artifacts.
4. **Players should prioritize targeting artifacts with the highest drop rate increase** (e.g., Demeter’s Necklace).
5. **Targeting is ineffective for extremely rare artifacts** like Light of Eggendil and Ship in a Bottle.

---

## **Final Takeaways**
- **Targeting works best for mid-to-high-tier artifacts**.
- **Legendary targeting has limited benefits**, making crafting a **more reliable alternative**.
- **Future optimizations** should focus on balancing spaceship missions with crafting to maximize artifact acquisition.
