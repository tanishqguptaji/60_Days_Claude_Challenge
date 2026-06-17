# Day 17 – AI Vehicle Cost & Fuel Analysis Dashboard

## Objective

Today’s challenge focused on using Claude as a Data Analyst to transform a raw CSV dataset into a fully interactive HTML dashboard.

The goal was to:

- Analyze vehicle fuel data
- Compute business metrics automatically
- Generate interactive visualizations
- Build a complete dashboard without manual coding

---

# Vehicle Information

| Parameter | Value |
|------------|--------|
| Vehicle | Maruti Suzuki Ciaz Zeta |
| Fuel Type | Petrol (E20) |
| Vehicle Age | 4 Years |
| Monthly Usage | 30,000 KM |
| Analysis Type | Fuel Cost & Environmental Comparison |

---

# Dashboard Generated

The generated dashboard included:

### KPI Cards

- Petrol Cost per KM
- E85 Cost per KM
- E85 Running Premium
- E85 Break-even Price
- Monthly Fuel Cost

---

# Key Metrics

| Metric | Value |
|----------|----------|
| Petrol Cost/km | ₹6.15 |
| E85 Cost/km | ₹6.37 |
| E85 Premium | +3.57% |
| Break-even Price | ₹79.10/L |
| Monthly Petrol Cost | ₹1,84,629 |

---

# Cost Per KM Comparison

| Fuel Type | Cost/km |
|------------|----------|
| EV | ₹1.75 |
| CNG | ₹3.32 |
| Diesel | ₹4.67 |
| Petrol | ₹6.15 |
| E85 | ₹6.37 |

### Observation

EV showed the lowest operating cost while E85 turned out to be slightly more expensive than Petrol despite its lower pump price.

---

# CO₂ Emission Analysis

| Fuel | CO₂ (kg/km) |
|--------|------------|
| E85 | 0.070 |
| EV | 0.091 |
| CNG | 0.125 |
| Petrol | 0.171 |
| Diesel | 0.179 |

### Observation

E85 emerged as the most environmentally friendly fuel option with the lowest CO₂ emissions.

---

# Vehicle Age Analysis

The dashboard analyzed how operating costs change as vehicles age.

### Current Vehicle Age

4 Years

### Age Category

Mid-Life (3–5 Years)

### Petrol Cost

₹5.85/km

### E85 Cost

₹6.67/km

### Observation

Operating costs gradually increase as vehicles age due to maintenance and efficiency losses.

---

# E85 Paradox Analysis

One of the most interesting findings from the dashboard.

## Pump Price Advantage

Petrol Price: ₹100/L

E85 Price: ₹82/L

Savings at Pump:

18%

---

## Running Cost Penalty

Because E85 delivers lower mileage:

- Petrol Mileage: 16.27 km/L
- E85 Mileage: 12.87 km/L

Running Cost Increase:

+3.57%

---

## Break-even Price

Calculated Break-even Price:

₹79.10/L

### Insight

E85 would only become economically beneficial if its market price falls below ₹79.10 per litre.

---

# E85 Overall Score

| Category | Score |
|-----------|--------|
| Cost | 0/4 |
| CO₂ | 3/3 |
| Refuel Time | 2/2 |
| Maintenance | 0.75/1 |

### Final Score

5.75 / 10

---

# Fuel Comparison Summary

## Petrol

### Advantages

- Widely available
- Good mileage

### Limitations

- Higher fuel price
- High emissions

---

## E85

### Advantages

- Lowest CO₂ emissions
- Low maintenance cost

### Limitations

- Lower mileage
- More expensive per kilometer

---

## CNG

### Advantages

- Lower running cost
- Cleaner than Petrol

### Limitations

- Tank space usage
- Longer refueling time

---

## Diesel

### Advantages

- Strong mileage
- Suitable for long-distance driving

### Limitations

- Highest emissions
- Higher maintenance

---

## Electric Vehicle

### Advantages

- Lowest running cost
- Lowest maintenance cost

### Limitations

- Charging time
- Charging infrastructure dependency

---

# Dashboard Features Implemented

- Interactive KPI Cards
- Cost Analysis Charts
- SVG Doughnut Charts
- Vehicle Age Trend Analysis
- Fuel Comparison Cards
- E85 Economics Calculator
- Environmental Impact Dashboard
- Responsive Design
- Dark Theme UI

---

# Key Learnings

1. AI can perform complete CSV-based data analysis.
2. Business metrics can be generated automatically from raw data.
3. Dashboards can be built without traditional BI tools.
4. SVG-based visualizations provide lightweight interactive reporting.
5. Data storytelling is as important as data processing.
6. Economic decisions often differ from environmental decisions.
---

# Final Insight

Raw data becomes valuable only when converted into actionable insights.

This challenge demonstrated how AI can bridge the gap between data collection and decision-making by automatically generating analytics dashboards from structured datasets.

---

Challenge: ABTalks 60-Day Claude Challenge – Day 17
