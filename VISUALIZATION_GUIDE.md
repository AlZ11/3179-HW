# Interactive Visualization Guide

## 1. Birth Rate vs Death Rate Analysis

### What It Shows

A scatter plot comparing birth rates (x-axis) and death rates (y-axis) across 60 countries worldwide.

### Key Features

- **Diagonal Reference Line (y=x)**:

  - Countries **above** the line are **growing** (births > deaths)
  - Countries **below** the line are **declining** (deaths > births)
  - Countries **on** the line have stable populations

- **Point Size**: Represents population (larger circles = more populous countries)

- **Color Coding**: By continent
  - 🔴 Africa
  - 🔵 Asia
  - 🟢 Europe
  - 🟣 North America
  - 🟠 South America
  - 🟤 Oceania

### Interactive Elements

✅ **Click legend** to filter by continent → unselected continents fade to gray  
✅ **Click points** to highlight specific countries  
✅ **Hover** to see detailed tooltips with exact rates and population

### Insights to Discover

- African countries cluster in the high birth rate, moderate death rate zone → rapid growth
- European countries near the diagonal with low birth rates → aging populations
- Asian countries show diverse patterns reflecting varying development stages
- Some European countries below the diagonal → population decline

---

## 2. Leading Causes of Death Worldwide

### What It Shows

An interactive donut chart displaying the top 15 causes of death globally, with annual deaths and percentages.

### Disease Categories

- 🫀 **Cardiovascular Diseases** (red) - Heart disease, stroke, hypertensive disease
- 🎗️ **Cancers** (purple) - Lung, colon, breast, stomach, prostate, pancreatic
- 🦠 **Infectious Diseases** (blue) - COVID-19, respiratory infections, TB, HIV/AIDS, malaria
- 🫁 **Respiratory Diseases** (teal) - COPD
- 🧬 **Organ Diseases** (orange) - Kidney, liver, cirrhosis
- 🚑 **Injuries** (gray) - Road injuries, falls, drowning
- 🧠 **Mental Health & Violence** (dark orange) - Suicide, homicide
- 🩺 **Metabolic Disorders** (green) - Diabetes
- 🧠 **Neurological Conditions** (dark red) - Alzheimer's and dementias
- ⚙️ **Other** (dark gray) - Various other causes

### Interactive Elements

✅ **Click legend categories** to filter by disease type → unselected categories fade  
✅ **Click chart segments** to highlight specific causes  
✅ **Hover** to see:

- Exact cause name
- Disease category
- Annual deaths (with formatting)
- Percentage of total deaths

### Key Statistics

- **#1 Cause**: Ischaemic Heart Disease (16.0% - 9.2M deaths/year)
- **#2 Cause**: COVID-19 (12.0% - 6.9M deaths/year)
- **#3 Cause**: Stroke (10.8% - 6.2M deaths/year)
- **Cardiovascular total**: 26.8% of all deaths
- **Cancer total**: ~9% of all deaths (multiple types)
- **Infectious diseases**: Significant burden, especially in developing nations

### Health Insights Panel

Accompanying text boxes provide context:

- Cardiovascular disease dominance
- COVID-19 pandemic impact
- Cancer burden by type
- Aging-related conditions (Alzheimer's)

---

## How to Use Both Visualizations Together

### Comparative Analysis

1. **Click Africa** in Birth/Death Rate chart → see high growth rates
   - Then look at Death Causes → infectious diseases prominent
2. **Click Europe** in Birth/Death Rate chart → see aging populations
   - Then look at Death Causes → cardiovascular and dementia prominent
3. **Identify trends**:
   - Growing populations → more infectious disease challenges
   - Aging populations → more chronic diseases (cardiovascular, dementia, cancer)

### Data Exploration Workflow

1. Start with **Birth/Death Rate** to understand demographic trends
2. Use **continent filter** to focus on specific regions
3. Switch to **Death Causes** to see health challenges
4. Use **category filter** to focus on disease types
5. Hover over specific data points for detailed statistics

---

## Technical Implementation

### Data Format

**birth_death_rates.csv**:

```csv
country,continent,year,birth_rate,death_rate,population
China,Asia,2024,7.52,7.37,1416096094
```

**death_causes.csv**:

```csv
cause,deaths,percentage,category
Ischaemic Heart Disease,9158203,16.0,Cardiovascular Diseases
```

### Visualization Technology

- **Library**: Vega-Lite v5
- **Chart Types**:
  - Scatter plot with layered reference line
  - Arc/donut chart with transforms
- **Interactivity**:
  - Parameter selections
  - Conditional encodings
  - Legend binding

### Responsive Design

- Container-based widths adapt to screen size
- Touch-friendly interactions
- Accessible tooltips
- Color-blind friendly palettes

---

## Data Sources & Reliability

All data sourced from internationally recognized organizations:

1. **[Our World in Data](https://ourworldindata.org/)** - Birth/death rates

   - Compiled from UN and Human Mortality Database
   - Peer-reviewed methodology
   - Regular updates

2. **[World Health Organization (WHO)](https://www.who.int/data/gho)** - Death causes

   - Global Health Estimates
   - Standardized international classification
   - Comprehensive country coverage

3. **[World Bank](https://data.worldbank.org/)** - Population data
   - Official national statistics
   - Quality-assured datasets

---

## Next Steps

To deploy these visualizations:

1. **Commit to GitHub**:

   ```bash
   git add data/birth_death_rates.csv data/death_causes.csv
   git add plots/birthDeathRate.json plots/deathCauses.json
   git add index.html css/styles.css plots/scatter.json
   git commit -m "Add birth/death rate and death causes visualizations"
   git push origin main
   ```

2. **Test Online**:

   - Visit your GitHub Pages URL
   - Verify all visualizations load
   - Test interactivity on mobile and desktop

3. **Share & Analyze**:
   - Use for presentations
   - Extract insights for reports
   - Compare demographic patterns

---

## Troubleshooting

### Visualizations Not Loading?

- ✅ Check browser console for errors
- ✅ Ensure files are pushed to GitHub
- ✅ Wait 1-2 minutes for GitHub Pages to update
- ✅ Clear browser cache and refresh

### Data Not Showing?

- ✅ Verify CSV files are in `data/` folder
- ✅ Check GitHub repo has files in correct locations
- ✅ Ensure CSV format is correct (no extra commas/quotes)

### Interactivity Not Working?

- ✅ Enable JavaScript in browser
- ✅ Use modern browser (Chrome, Firefox, Safari, Edge)
- ✅ Check for console errors
- ✅ Try different interaction (click vs hover)

---

**Happy Data Exploring! 📊✨**
