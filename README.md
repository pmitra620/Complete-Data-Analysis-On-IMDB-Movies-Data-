# 🎬 Complete Data Analysis on IMDb Movie Dataset

This project offers an in-depth analytical exploration of the **IMDb Random Movie Dataset**, aimed at uncovering key insights around profitability, ratings, genres, release timing, return on investment (ROI), and other influencing factors in the film industry. It equips **producers, investors, and moviegoers** with data-backed evidence to make smarter decisions around film financing, marketing, and viewership.

📊 Conducted by **Purushottam Mitra**  
📧 Email: pmitra620@gmail.com

---

## 🧠 Project Objective

To perform a comprehensive data analysis on a real-world IMDb movie dataset (sourced from Kaggle), exploring:

- Which months generate the most profitable movie releases
- Genres that perform best in terms of quantity, quality (IMDb score), and ROI
- Top-performing directors by IMDb rating
- Influence of movie characteristics like budget, release date, and color on success

> 📎 *This analysis enables investors to better predict box office success and allows audiences to identify content worth watching.*

---

## 🧾 Dataset Summary

| Attribute       | Description |
|----------------|-------------|
| Rows           | 3,726 movies |
| Columns        | 20 attributes |
| Derived Columns| Profit, Return on Investment (ROI) |
| Source         | [Kaggle - IMDb Random Movie Dataset](https://www.kaggle.com) |

### 📌 Key Columns Analyzed

- `Title`, `Director`, `Actor`, `Language`, `Country`, `Genre`, `Budget`, `Revenue`, `Release Date`, `IMDb Score`, `Movie Color`
- Derived: `Profit = Revenue - Budget`, `ROI = Profit / Budget`, `Release Month`

---

## 🎯 Analytical Objectives & Key Findings

| Objective No. | Analysis Focus | Summary Insight |
|---------------|----------------|------------------|
| 1️⃣ | **Most Profitable Month** | October & November yield highest profits. |
| 2️⃣ | **Month with Most Releases** | March, April, and November are busiest months. |
| 3️⃣ | **Genre vs Rating Distribution** | R-rated: Action, Biography, Thriller; PG-13: Animation, Sci-Fi. |
| 4️⃣ | **Most Released Genre** | Comedy dominates release count, followed by Action & Drama. |
| 5️⃣ | **Budget vs IMDb Score** | No strong correlation. High budget ≠ high IMDb score. |
| 6️⃣ | **Genre vs IMDb Score** | Comedy receives highest IMDb ratings. |
| 7️⃣ | **Top Directors by IMDb Score** | Spielberg, James Mangold, John Singleton lead the chart. |
| 8️⃣ | **Movie Color vs IMDb Score** | Colored films significantly outperform black-and-white ones. |
| 9️⃣ | **Top 10 Expensive Films** | “The Host” leads; others include “Lady Vengeance”, “Fateless”. |
| 🔟 | **Top 20 Movies by Profit** | Avatar, Jurassic World, and Titanic top the list. |
| 1️⃣1️⃣ | **Genre with Highest ROI** | Horror has highest ROI, followed by Biography and Comedy. |
| 1️⃣2️⃣ | **Movie Releases Over Time** | Massive surge from 1999 to 2014 compared to 1920–1990. |

---

## 📈 Visual Analysis

Visualizations were created to support all 12 analytical goals using bar plots, histograms, line graphs, and pie charts in Excel and PowerPoint.

| Visual Type | Used For |
|-------------|----------|
| Bar Charts | Genre distribution, Top movies by profit |
| Line Graphs | Movie releases over time |
| Pie Charts | Movie color ratios, release month contributions |
| Histograms | IMDb score distributions |

> 📎 View the complete slide deck: [`PURUSHOTTAM MITRA REPORT DSDEC01.pptx`](./PURUSHOTTAM%20MITRA%20REPORT%20DSDEC01%20(1).pptx)

---

## 💡 Strategic Conclusions

- **Best time to release a movie**: October–November for maximum profit potential
- **Most audience-favored genres**: Comedy (high volume & ratings), Horror (high ROI)
- **Budget insight**: High budgets don't guarantee high IMDb scores
- **Visual characteristics**: Colored, visually appealing films perform significantly better
- **Director patterns**: Established directors consistently perform well across metrics

---

## 📁 Project Structure

IMDb-Movie-Data-Analysis/
│
├── PURUSHOTTAM MITRA PROJECT DSDEC01.xlsx # Cleaned and processed dataset
├── PURUSHOTTAM MITRA REPORT DSDEC01.pptx # Final presentation/report
├── README.md # This file
├── LICENSE (optional)
└── /assets (optional) # Screenshots and charts

yaml
Copy
Edit

---

## 🛠 Tools & Technologies

| Tool         | Purpose                                |
|--------------|----------------------------------------|
| **Excel**    | Data cleaning, calculations, ROI logic |
| **PowerPoint** | Visual storytelling and business reporting |
| **Pandas / Python** *(optional)* | Data wrangling (if extended) |
| **Matplotlib / Seaborn** *(optional)* | Plotting advanced visuals |

---

## 📣 Recommendations for Film Industry Stakeholders

| Role       | Suggested Action |
|------------|------------------|
| 🎬 Producers | Target high-ROI genres like Horror; release during Oct–Nov |
| 💰 Investors | Prioritize directors with strong IMDb track records |
| 📊 Analysts  | Consider genre and seasonal trends when greenlighting projects |
| 🎟️ Audience  | Favor Comedy, Action, and Biography for high IMDb-rated content |

---

## 👤 Author

**Purushottam Mitra**  
📧 Email: pmitra620@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/yourprofile)  
🌐 Portfolio: [yourportfolio.com](https://yourportfolio.com)

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](./LICENSE) file for usage terms.

---

## ⭐ Show Your Support

If you found this project useful or insightful:

- 🌟 Star this repository
- 🧠 Use this project as a case study in data analysis
- 🔗 Connect with me for more projects and collaborations

---

## 🙏 Acknowledgements

- IMDb for the source data  
- Kaggle community for open datasets  
- Microsoft Excel & PowerPoint for enabling clear business communication
