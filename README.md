# 🏏 Cricket Best 11 — Power BI Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Cricket](https://img.shields.io/badge/Sport-Cricket-green?style=for-the-badge)
![T20 World Cup](https://img.shields.io/badge/Tournament-T20%20World%20Cup-orange?style=for-the-badge)

An interactive Power BI dashboard for analyzing and selecting the optimal **Final 11** cricket team based on player performance data from the **ICC Men's T20 World Cup**. The dashboard breaks down players by role, visualizes their key statistics, and allows users to interactively build their best possible XI.

---

## 📸 Dashboard Preview

| Page | Description |
|------|-------------|
| Power Hitters / Openers | Top-order aggressive batters |
| Anchors / Middle Order | Consistent run-scorers and stabilizers |
| Finishers / Lower Order | All-rounders who finish innings |
| All Rounders | Balanced batting and bowling contributors |
| Specialist Fast Bowlers | Wicket-taking specialists and tail-enders |
| Final 11 Builder | Custom team selection with combined stats |

---

## 🔍 Key Features

- **Role-based tabs**: Navigate between Power Hitters, Anchors, Finishers, All Rounders, and Fast Bowlers
- **Qualifier / Super 12 toggle**: Filter data by tournament stage
- **Interactive player selection**: Click a player name to see individual or combined performance metrics
- **Trend sparklines**: Batting average, strike rate, balls faced, boundary %, and economy over time
- **Scatter plot quadrant analysis**: Visualize players by two dimensions (e.g., Batting Avg vs Strike Rate, Economy vs Bowling Strike Rate)
- **Dynamic team stats**: Final 11 page auto-aggregates team-level performance as players are added

---

## 🗂️ File Structure

```
Cricket-Best-11.pbix       # Main Power BI report file
README.md                  # Project documentation
```

---

## 🚀 Getting Started

### Prerequisites
- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free download)
- Windows OS (Power BI Desktop is Windows-only; use Power BI Service on other platforms)

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/cricket-best-11.git
   cd cricket-best-11
   ```

2. **Open the file**
   - Launch Power BI Desktop
   - Go to `File → Open` and select `Cricket-Best-11.pbix`

3. **Explore the dashboard**
   - Use the top navigation tabs to switch between player roles
   - Click player names to highlight individual stats
   - Navigate to **Final 11** to build your custom team

---

## 📐 Data & Metrics Reference

| Metric | Description |
|--------|-------------|
| Batting Average | Runs scored per innings dismissed |
| Strike Rate | Runs scored per 100 balls faced |
| Boundary % | Percentage of runs scored via boundaries |
| Economy | Runs conceded per over bowled |
| Bowling Strike Rate | Balls bowled per wicket taken |
| Dot Ball % | Percentage of deliveries that were dot balls |
| Bowling Average | Runs conceded per wicket taken |

---

## 🏆 Tournament Context

This dashboard is built on data from the **ICC Men's T20 World Cup**, covering both the **Qualifier** and **Super 12** stages. Player data includes all nations that participated across both rounds.

---

## 🛠️ Built With

- **Microsoft Power BI Desktop**
- **DAX** (Data Analysis Expressions) for calculated measures
- **Power Query** for data transformation
- Custom dark theme with ICC T20 World Cup branding



- ICC for T20 World Cup match data
- Inspiration from data-driven cricket analytics
