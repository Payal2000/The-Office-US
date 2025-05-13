# The-Office-US
This project is a visual analytics dashboard for the American TV series **The Office**, built to explore and analyze patterns in episode ratings, votes, and season performance. The dashboard allows users to gain insights into the show's trends over its nine-season run.

## 📁 Dataset Overview

The dataset contains episode-level information across all seasons of *The Office* (US version). It includes metadata such as episode title, rating, number of votes, air date, director, and more.

### 🔢 Dataset Columns

| Column         | Description |
|----------------|-------------|
| `Season`       | Season number (1 to 9) |
| `EpisodeTitle` | Title of the episode |
| `Description`  | Brief summary of the episode plot |
| `Ratings`      | IMDb rating of the episode |
| `Votes`        | Number of user votes on IMDb |
| `Viewership`   | Viewership in millions |
| `Duration`     | Episode duration in minutes |
| `Date`         | Air date of the episode |
| `GuestStars`   | Any notable guest appearances |
| `Director`     | Director(s) of the episode |
| `Writers`      | Writers credited for the episode |


# 📊 The Office TV Series Dashboard

### 🎬 Episode-Level Analysis
Displays detailed information about a selected episode including:
- Season, title, air date
- IMDb rating and total votes
- Synopsis and duration

### Directors Word Cloud
A word cloud of all episode directors sized by frequency of appearance, highlighting prolific contributors like *Paul Feig*, *Randall Einhorn*, and *Ken Kwapis*.

### 📈 Total Episodes by Season
Horizontal bar chart showing the number of episodes per season.

### ⭐ Total Stars by Season and Episode
Box plot visualization of episode IMDb ratings per season, showing spread, median, and outliers.

### 🗳️ Total Votes by Season and Episodes
Stacked bar chart showing total number of votes by season, with some seasons (like 2, 3, and 5) clearly dominating fan engagement.



## 🛠️ Technologies Used

- **Data Source:** Custom CSV dataset of *The Office* episodes
- **Visualization:** Tableau 
- **Tools for Data Cleaning:** Excel
- **Image Editing & Layout:** External graphics for visuals and poster inserts



## 📌 How to Reproduce

1. Clone this repository
2. Open the dataset (`Office_dataset.csv`) in your preferred analysis tool
3. Use Tableau/Power BI or another dashboard tool to recreate the visuals
4. Filter and interact with episode-level analytics, ratings, and directors



## 📎 Future Scope

- Compare the performance of episodes across seasons
- Identify the most and least liked episodes
- Find patterns among high-rated or low-rated directors
- Explore how fan engagement (votes) changes across time



## 📷 Dashboard Preview

<img align="center" alt="zerotwo-pic" height="450" style="border-radius:60px;" src="https://github.com/Payal2000/The-Office-US/blob/main/Dashboard%201.png">


## 📬 Contact

For questions or contributions, please reach out via LinkedIn: [Payal Sanjay Nagaonkar](https://www.linkedin.com/in/payal-sanjay-nagaonkar-76b733188/)
