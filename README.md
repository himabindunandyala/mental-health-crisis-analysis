#  The Silent Epidemic: America's Mental Health Crisis

> *"1 in 5 Americans will experience a mental health condition this year. Most will never get help."*

**By Hima Bindu Nandyala**

---

##  Overview

This project investigates one of the most underdiscussed public 
health crises in the United States - the growing gap between 
mental illness prevalence and treatment access.

Using data storytelling, I analyzed over a decade of mental 
health data across all 50 states to answer one question:

> **Why does the U.S. fail to treat the majority of people 
> who need mental health care, and what can fix it?**

---

##  Key Numbers

| Stat | Value |
|---|---|
| Americans with mental illness | 57.8 Million |
| Receiving zero treatment | 55% |
| Substance use disorder untreated | 80% |
| Economic cost per year | $280 Billion |
| Youth suicide rank | #2 cause of death (ages 10–34) |

---

##  Storytelling Structure

| Step | Title | What It Shows |
|---|---|---|
| 1 | The Hook | People-grid visual, 11 of 100 Americans face it alone |
| 2 | The Context | Prevalence trends 2011-2023, state choropleth map |
| 3 | The Conflict | Treatment gap across 9 conditions, OLS regression |
| 4 | The Journey | Age, gender, barriers, COVID impact, word cloud |
| 5 | The Resolution | Cost vs impact charts, treatment funnel |
| 6 | The Call to Action | Priority matrix, top 3 policy interventions |
| 7 | The Emotional Appeal | Gen Z crisis, spending vs suicide rates |

---

##  Data Types Analyzed

- **Numerical** - prevalence rates, spending, provider counts, regression outputs
- **Categorical** - conditions, age groups, gender, regions, barriers
- **Text** - word cloud from mental health survey themes
- **Image** - people-grid infographic from population data

---

##  Tools & Libraries

```python
pandas        # data manipulation
numpy         # numerical analysis
plotly        # interactive + animated charts
matplotlib    # static visualizations
seaborn       # heatmaps and styled plots
wordcloud     # text data analysis
statsmodels   # OLS regression
scipy         # Pearson correlation
```

---
##   Interactive Dashboard
Alongside the notebook, this project includes a standalone interactive dashboard that brings all 7 storytelling stages to life in a single HTML file no Python or Jupyter required.

- **Link to Dashboard**

file:///C:/Users/himab/Downloads/mental_health_dashboard.html

---

##  Project Files

```
.
├── mental_health_crisis_project.ipynb   # Full analysis notebook (7 storytelling steps)
├── mental_health_dashboard.html         # Standalone interactive dashboard
└── README.md                            # This file
```

##  Key Findings

1. **The crisis keeps growing** - prevalence rose every year from 2011 to 2023, with the sharpest jump during COVID-19.
2. **55% receive no treatment** - substance use disorder and PTSD have the largest untreated populations.
3. **Young adults are most at risk** - ages 18–25 have the highest prevalence but the lowest treatment rates.
4. **Geography determines access** - states with more providers and higher spending have measurably better outcomes.
5. **Investment saves lives** - states that spend more on mental health have lower youth suicide rates.

---

##  Top 3 Policy Recommendations

| Priority | Action | Est. Cost | People Reached |
|:---:|---|:---:|:---:|
| 1 | Fund & expand the 988 Crisis Lifeline | $1.2B/yr | 2.3M |
| 2 | Make telehealth mental health coverage permanent | $2.1B/yr | 5.7M |
| 3 | Expand school-based mental health counseling | $3.5B/yr | 4.3M youth |

---

*Mental health is not only a healthcare problem, but it also affects real people, families, and communities every day.*
*The data makes one thing clear: improving access to care is no longer a choice, but a necessity.*
