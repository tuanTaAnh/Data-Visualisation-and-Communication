# Hotel Booking Demand — Pricing & Cancellation Insights for Revenue Management

This repository contains my **M512B Individual Final Project** for the module **Data Visualisation and Communication (WS1225)**.

The project uses the **Hotel Booking Demand** dataset to build an **explanatory data analysis notebook** for a hotel revenue and operations audience. The goal is not just to explore the data, but to communicate clear business insights through well-designed charts and concise storytelling.

---

## Project overview

Hotels do not just need more bookings — they need the **right bookings**.

This project looks at hotel performance from several connected angles:

- room price levels (**ADR**)
- cancellation risk
- differences between **City** and **Resort** hotels
- booking segment quality
- room-type mismatch and operational pressure
- demand patterns over time

The notebook is written as if it were delivered to a **hotel revenue and operations team**, with each chart designed to support a business decision.

---

## Main business questions

The notebook focuses on questions such as:

1. What does the hotel’s normal ADR look like?
2. Do City and Resort hotels need different pricing strategies?
3. When does cancellation risk become serious?
4. Which market segments are more valuable?
5. Which room types create more operational pressure?
6. When is demand highest, and how should the hotel prepare?

---

## Repository contents

- `[GH1046139] Ta Anh Tuan - M512B - Data Visualisation and Communication.ipynb`  
  Main Jupyter Notebook

- `[GH1046139] Ta Anh Tuan - M512B - Data Visualisation and Communication.html`  
  Exported HTML version for submission

- `hotel_bookings.csv`  
  Dataset used in the notebook

---

## Dataset

This project uses the **Hotel Booking Demand** dataset, which contains booking records for **City Hotel** and **Resort Hotel**.

### Sources
- Original article: Antonio, N., de Almeida, A. and Nunes, L. (2019) *Hotel booking demand datasets*, *Data in Brief*, 22, pp. 41–49.
- Kaggle dataset page:  
  <https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand>
- GitHub repository mirror:  
  <https://github.com/mpolinowski/hotel-booking-dataset>
- Raw CSV mirror used in this project:  
  <https://raw.githubusercontent.com/mpolinowski/hotel-booking-dataset/master/datasets/hotel_bookings.csv>

---

## Methods used

The notebook includes:

- data loading
- data cleaning and preprocessing
- feature engineering
- explanatory data visualisation
- business interpretation of each chart
- final recommendations

Some of the main preprocessing steps include:

- converting month names into numeric values
- creating a proper arrival date
- calculating total stay nights
- clipping ADR outliers for clearer charts
- grouping lead time into business-readable bins

---

## Chart types used

The project uses a range of chart types, including:

- histogram
- box plot
- line chart
- dumbbell chart
- bubble scatter plot
- horizontal bar chart
- scatter plot with trend lines
- area chart

These were selected to match the business question behind each insight and to support clearer storytelling.

---

## How to run the notebook

1. Clone or download this repository
2. Make sure the file `hotel_bookings.csv` is in the same folder as the notebook
3. Open the notebook in Jupyter Notebook or JupyterLab
4. Run all cells in order

### Main Python libraries
- `pandas`
- `numpy`
- `matplotlib`

---

## Output

The main final deliverable is the **HTML-exported notebook**, which presents:

- business context
- data quality discussion
- preprocessing steps
- 8 explanatory insights
- conclusion and recommendations
- references

---

## Academic note

This repository was created for an **individual university assignment**.  
If this GitHub link is included in the submitted report, the repository should **not be updated after the submission deadline**.

---

## Author

**Anh Tuan Ta**  
MSc Data Science, AI and Digital Business  
Gisma University of Applied Sciences

LinkedIn:  
<https://www.linkedin.com/in/ta-anh-tuan-ai-engineer>