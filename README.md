## Dashboard created from Meta AI, Uploaded data in Meta AI and gives command and my things abount data to create dashboard as per data, and Meta AI created Dashboard for me.
Just Exploring AI tools that how I can use it for my Data analysis and visualizations.


# IPLTeam-Wise-Interactive-Dashboard
IPL matches data from 2008 to 2022, covers to all mazor visuals
## ✨ Features (Version 2 Upgrade)
- **Team selector chips** — horizontal scrollable, team colors (CSK yellow, MI blue, RCB red, KKR purple...)
- **Click to filter entire dashboard**: KPI cards, top batters, runs-per-over, boundaries, insights all update
- **Dynamic team theme** — background gradient & accent adapts on team click
- Charts:
  - Horizontal bar for Top 5 batters (team-wise)
  - Area chart for runs per over (0-19) — Powerplay / Middle / Death splits
  - Donut for Fours vs Sixes vs Singles
  - Team runs comparison when "All Teams" selected
- **Search bar** for batter/bowler
- **Auto Insights box** — 3 context-aware insights per team selection
- Click interactions: bar click highlights batter, chip animates with glow
- Modern dark UI, glassmorphism, fully responsive

## 📊 Data Embedded
- Overall: 950 matches, 225954 balls, 296097 runs, 11151 wickets
- Teams: 18 franchises (including defunct: Pune Warriors, Deccan Chargers, Kochi Tuskers, etc.)
- Top batters overall: Kohli 6634, Dhawan 6244, Warner 5883...
- Team-wise object: total_runs, balls, wickets, matches, top_batters[5], runs_per_over[0-19], fours, sixes

## 🛠️ Tech Stack
- React + TypeScript
- Recharts for charts
- Tailwind CSS + Lucide Icons
- Glassmorphism, backdrop-blur, gradients

## 🚀 How to Run
```bash
npm install
npm run dev
```
Build output: `ipl_team_wise_filter.html`

## 📁 Structure
```
App.tsx
 - TEAM_DATA (embedded object)
 - TEAM_COLORS mapping
 - Filters & derived stats via useMemo
 - Charts (Bar, Area, Pie)
```

## 🔮 Roadmap v3 Ideas
- Bowler economy vs team heatmap
- Venue wise filter
- Player vs Player matchup
- Export PNG

## 📝 License
MIT — for learning & portfolio. Data source: IPL official stats 2008-2022.

---
Built with ❤️ for cricket analytics fans. Click a team chip & feel the stadium!
