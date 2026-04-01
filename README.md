# README.md

## 🛡️ Gear Score Calculator (WIP)

A specialized tool for calculating gear efficiency based on roll distributions. This project is currently a **Work in Progress**, and the UI/Design is subject to change.

---

## 🚀 Features & Usage

- **Supported Stats:** Currently accepts **Percentage (%)** and **Speed** substats.
- **Rarity Scaling:** Compatible with both **Epic (Purple)** and **Legendary (Orange)** gear, as power-up scaling is identical for the same Gear Score.

## 📊 Statistical Model

Calculations are based on the following roll distributions.

> [!IMPORTANT]  
> These values are derived from personal testing and a limited sample size. They will be updated as more data becomes available.

### Roll Value Reference

| Stat Group            | Roll Values                              |
| :-------------------- | :--------------------------------------- |
| **Speed**             | `1`, `2`                                 |
| **ATK / DEF / HP %**  | `0.6`, `0.8`, `1.0`, `1.2`, `1.4`, `1.6` |
| **Crit Rate**         | `1.0`, `1.2`, `1.4`, `1.6`, `1.8`, `2.0` |
| **Crit DMG**          | `1.5`, `1.8`, `2.1`, `2.4`, `2.7`, `3.0` |
| **Eff Hit / Eff Res** | `1.0`, `1.4`, `1.8`, `2.2`, `2.6`, `3.0` |

---

## ⚠️ Known Behaviors

- **Speed Weighting:** Speed is currently weighted lower in the final score. Because it only rolls between $1$ and $2$ (with $2$ being significantly rarer), gear containing Speed may result in a lower total score compared to other stats.
- **Ongoing Development:** Advanced design elements have not yet been applied.

---

## 🛠 Future Roadmap
- [ ] Add support for flat stat calculations.
