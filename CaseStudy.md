# AI Developer Productivity Analysis

## Executive Summary
This analysis explores how **coding hours, cognitive load, sleep, and caffeine intake**
affect AI developers’ productivity and commit performance.

The goal was to identify patterns that can improve both **efficiency and well-being**.

The dataset, originally sourced from Kaggle, was enriched with **synthetic data**
(developer IDs, team assignments, and weekly intervals) to enable deeper analysis.

An interactive **Power BI dashboard** with six analytical views highlights relationships
between key productivity factors.

**Key findings** indicate that:
- Increased AI usage significantly boosts commit volume  
- Insufficient sleep and high caffeine intake raise cognitive load  
- Higher cognitive load negatively affects focus and performance  

Additionally, higher caffeine consumption correlates with increased AI usage and a higher
number of commits, suggesting that developers rely on both **AI tools and coffee**
during intense coding periods.

---

## Analytical Goals & Business Questions
The objective was to identify which factors most influence developer productivity and to
derive **actionable insights** for improving performance.

**Key business questions:**
- How does AI usage influence coding productivity and commits?
- What is the impact of sleep and distractions on cognitive load?
- How does caffeine consumption affect focus and performance?
- How can data-driven insights support a healthier and more efficient workflow?

---

## Dataset & Preparation
The dataset includes:
- **60 developers**
- **3 teams**
- **15 weeks** of activity tracking

**Key variables:**
- Coding hours  
- AI usage  
- Commits  
- Bugs  
- Sleep hours  
- Distractions  
- Caffeine intake  
- Cognitive load  

**Data preparation steps:**
- Data cleaning and transformation in Power BI  
- Added a **weekly interval table** for time-based analysis  
- Created **Developer ID** and **Team** fields to enable individual and team-level insights  

---

## Dashboard Overview
The dashboard consists of **six analytical views**:

### Coding
- Strong positive correlation between **AI usage and commit volume**
- Simulation model estimates that **each additional AI hour increases commits by**:
  - ~1.0 for Juniors  
  - ~1.3 for Mid-level developers  
  - ~0.8 for Seniors  

### Sleep
- Fewer sleep hours correspond to:
  - Higher distraction levels  
  - Increased cognitive load  
- Developers with better sleep maintain higher focus and productivity

### Bugs
- Bug frequency is directly influenced by:
  - Sleep deprivation  
  - Distractions  
  - Elevated cognitive load  

### Load
- Cognitive load increases with:
  - Reduced sleep  
  - Higher distraction levels  
- Average cognitive load across all teams remains around **level 4**

### Coffee
- Caffeine intake increases with:
  - Coding hours  
  - Commit volume  
- Excessive consumption:
  - Raises cognitive strain  
  - Lowers self-assessed performance  

---

## Interactive Tooltips
To improve readability and contextual understanding, several **custom tooltips**
were implemented. They provide dynamic comparisons, explain key metrics, and help
users quickly interpret changes.

**Tooltip measures:**
- `TooltipTextCommitsAIUsage` *(Change vs Last Week)*  
  Shows week-over-week changes in commits and AI usage with visual indicators  

- `TooltipSimulation` *(Growth vs Previous Hour)*  
  Displays projected commit growth compared to the previous AI usage hour  

- `TooltipSleepDistraction` *(Summary)*  
  Summarizes weekly averages of sleep hours and distractions  

- `Tooltip_Coffee_Productivity` *(Productivity)*  
  Compares current vs previous coding hours and caffeine intake, showing:
  - Percentage changes  
  - Productivity ratio (commits/hour)  

---

## Key Insights & Recommendations

### Key Insights
- AI usage strongly increases productivity and commit frequency  
- Reduced sleep and frequent distractions significantly raise cognitive load  
- Higher caffeine intake boosts short-term focus but harms long-term performance  
- Mid-level developers show the best balance between efficiency and workload  

### Recommendations
- Encourage broader adoption of AI tools through targeted team training  
- Promote healthy work habits and better sleep hygiene  
- Monitor caffeine intake and cognitive load as part of well-being programs  
- Use dashboard insights for regular workload balancing and performance reviews  

---

## Future Improvements
- Use real or larger datasets for improved accuracy  
- Implement forecasting models to predict commit trends  
- Add additional filters (e.g., by project or role)  
- Define clear productivity KPIs for easier tracking  
- Explore personalized recommendations based on sleep, AI usage, and workload patterns  
