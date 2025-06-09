
# 🎥 Analysis of Different Technologies in Demand on YouTube

## 📌 Objective
The purpose of this project is to analyze the popularity and demand for various **technologies and programming languages** across YouTube channels. By exploring tutorial playlists, view counts, and engagement metrics, this project identifies **trending tech skills** and compares their visibility and learner interest on YouTube.

## 📊 Dataset Overview
The dataset contains curated or scraped data from YouTube, including:
- `Channel Name`
- `Playlist Title`
- `Technology/Topic`
- `Number of Videos`
- `Total Views`
- `Average Views per Video`
- `Upload Frequency`
- `Date Collected`

## 🔍 Key Analytical Questions
- Which programming languages and tools have the highest viewership?
- How does the average view count vary across technologies?
- Are there specific channels dominating in particular tech niches?
- Which emerging technologies (like AI, DevOps, Blockchain) are gaining traction?

## 📈 Visualizations & Insights
- **Bar plots** of total views by technology
- **Heatmaps** of average views across topics and channels
- **Trend charts** for rising vs. declining tech interest
- **Bubble plots** showing tech popularity vs. number of tutorials

## 📁 Folder Structure
```
youtube-tech-analysis/
├── analysis_notebook.ipynb      # Jupyter notebook with all analyses
├── data/                        # Dataset files (CSV/Excel)
├── plots/                       # Exported graphs and charts
├── README.md                    # Project documentation
└── reports/                     # Summary insights or presentation slides
```

## 🚀 Tools & Libraries Used
- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn`, `plotly` – visualizations
- `YouTube Data API` or `scraping` (if applicable)

## 💡 Key Findings (Example)
> - Python and JavaScript dominate in total views.
> - Machine Learning tutorials have higher average engagement per video.
> - Niche topics like Go, Rust, and Blockchain are emerging but underrepresented.

## ✅ Future Enhancements
- Add **real-time YouTube API integration** to refresh data
- Create an **interactive dashboard** with Streamlit or Dash
- Predict **future trends** using time series or regression models

## 🙌 Acknowledgments
- Data sources: YouTube public playlists
- Tools: Python, Jupyter Notebook, YouTube API
