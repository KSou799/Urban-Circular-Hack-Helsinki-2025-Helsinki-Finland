# FlexiCity – Helsinki Energy Peak Simulator

**Built at Urban Circular Hack Helsinki 2025** — Helsinki, Finland  

---

## Overview

Helsinki experiences a sharp electricity price spike every evening around **7 pm**. Residents plug in EVs, turn on heating, cook dinner, and run appliances at the same time. This surge raises electricity prices, stresses the grid, and can force the city to plan **major grid upgrades costing over €2 billion** — projects that take **5–7 years** to complete.  

**FlexiCity** is a simulator that demonstrates how **smart scheduling of flexible devices** can flatten peak demand, saving money for users, reducing CO₂ emissions, and easing pressure on the city’s electricity infrastructure.

---

## The Problem — The 7 pm Spike

Using **Helen’s hourly electricity prices**, we identified the evening peak:

| Time | Price (cents/kWh) |
|------|-------------------|
| 02:00 | 8.52 (cheapest) |
| 17:00 | 18.60 ↑ |
| 18:00 | 21.53 ↑ |
| **19:00** | **22.68 — daily peak** |
| 21:00 | 17.09 ↓ |

When everyone consumes electricity simultaneously, prices rise, infrastructure is strained, and costly grid reinforcements become necessary.

---

## How FlexiCity Works

The simulator shows the effect of shifting flexible devices like **EV chargers, heat pumps, and dishwashers** away from peak hours:

- **BEFORE:** Default scheduling — devices run according to typical user habits.  
- **AFTER:** Smart scheduling — flexible devices shift to off-peak hours.  

**Controls:**
1. **Flex participation slider** — Set how many users/devices participate.  
2. **Grid vs Price slider** — Optimize for grid stability or cost savings.  
3. **Auto-find buttons** — Automatically find optimal settings.  

**Scenario options:**  
- **Baseline:** Typical Helsinki weekday  
- **Winter:** Higher demand from heating, EVs, and saunas 🇫🇮  
- **2030 Future:** 90% higher overall demand due to electrification, with a cleaner grid from renewables  

---

## Results & Benefits

**Users:**  
- Save up to **€16+ per day** on electricity bills  
- Reduce personal carbon footprint  

**City:**  
- Lower peak demand → delays or avoids **€2 billion+ grid upgrades**  
- Reduced strain on the electricity network → easier integration of EVs and electric heating  

**Environment:**  
- Flatter demand curves → less reliance on fossil fuel backup power  
- Avoid up to **3,400+ tCO₂ per year**  

---

## Screenshot

![FlexiCity App Screenshot](screenshot.png)  

The top graph shows the typical evening peak, while the bottom shows flattened demand after smart scheduling.

---

## Getting Started

**Requirements:** Python 3.8+ (no extra libraries needed)  

```bash
git clone https://github.com/KSou799/Urban-Circular-Hack-Helsinki-2025-Helsinki-Finland.git
cd Urban-Circular-Hack-Helsinki-2025-Helsinki-Finland
python Hackathon_energy.py
