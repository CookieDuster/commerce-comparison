# 🛒 Open eCommerce Platforms Comparison (2026)

### Why this exists
Choosing a commerce engine is often a choice between "marketing fluff" and reality. I built this repo for [eCommerce Platform Comparison tool](https://crystallize.com/compare) in [Crystallize](https://crystallize.com/compare) to move beyond sales decks and create a **community-validated, technical comparison** of modern platforms like Shopify, Crystallize, commercetools, BigCommerce, etc. 

By keeping this data open source, I hope to ensure the specs remain objective, up to date, and useful for architects and founders alike.

---

## 📊 The Comparison Table
> [!TIP]
> **[Click here to view the full Comparison Data](./data/comparison.csv)** > GitHub renders our CSV into a searchable, filterable table automatically.
>
> Release date: 02/03/2026
>
> Commerce Comparison v2.0: 04/14/2026

---

## 🛠 Contribution Guide

I welcome updates to existing platforms or the addition of new ones. To maintain the integrity of the data, please follow these steps:

### 1. Requesting a New Platform
If you want a platform covered but don't have all the data:
* Open a **New Issue**.
* Use the title `[Request]: Platform Name`.
* The community or maintainers will help research the criteria.

### 2. Suggesting Changes (The Pull Request Process)
If you have the data and want to update the table directly:
1. **Fork** this repository.
2. Edit the `data/comparison.csv` file.
3. **Requirement:** If adding a new platform, you **must** provide values for all 45+ criteria across our 5 categories:
   * **Technical** (Architecture, API, etc.)
   * **Features** (PIM, CMS, etc.)
   * **AI** (Agentic Commerce, GenAI, etc.)
   * **Pricing** (Fees, Entry costs, etc.)
   * **Support** (SLAs, Training, etc.)
4. Submit a **Pull Request** with the heading `feat: add [Platform Name]` or `fix: update [Platform Name] specs`.

---

## 📜 License
This project is licensed under the **Creative Commons Attribution 4.0 (CC BY 4.0)**. You are free to share and adapt this data as long as you provide attribution to this repository and the original page from which the project was made, https://crystallize.com/compare.
