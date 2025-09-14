# F1 Data Analysis Portfolio

This GitHub repository presents a collection of my data analysis and machine learning projects applied to Formula 1, developed using the FastF1 Python library. The goal of this portfolio is to showcase my data science skills, from manipulating raw data to building predictive models and creating advanced visualizations.

---

## Repository Structure

- `1.Telemetry_analysis/` : Groups all notebooks for telemetry and performance analysis.
- `2.ML_prediction/` : Contains machine learning projects for predictive modeling.
- `3.Docs/` : Contains project reports and strategic analysis documents.
- `data/` : Contains the FastF1 data cache, organized by year, Grand Prix, and session.

---

## 1.Telemetry Analysis

This folder contains several detailed performance analyses, demonstrating my ability to interpret race data.

### `best_lap_quali.ipynb` — *Qualifying Lap Analysis*
A comparative study of the fastest qualifying laps to identify specific areas on the track where one driver gains or loses time against a direct competitor.

### `best_lap_race.ipynb` — *Race Lap Analysis*
A detailed examination of a driver's best race lap, identifying key moments and areas of advantage on a single lap.

### `tire_degradation.ipynb` — *Tire Degradation Analysis*
An analysis of a driver's performance throughout a Grand Prix. The project focuses on the degradation of each tire compound (Soft, Medium, Hard) and its impact on race pace.

**Skills Used**: `Python`, `FastF1`, `Pandas`, `Matplotlib`, `Numpy`  

---

## 2.Machine Learning prediction

This folder demonstrates my machine learning skills for predictive applications in F1.

### `driver_style.ipynb` — *Clustering drivers style*
Application of unsupervised learning techniques (clustering) to group drivers according to their racing style. The analysis is based on telemetry features such as braking, acceleration, cornering behaviour, and fuel/tire management.
The objective is to highlight similarities and differences between drivers, providing insights into their unique driving profiles.

### `lap_time.ipynb` — *Lap Time Prediction*
Construction of a regression model to predict a driver's lap time based on key variables such as tire age, lap number, and track conditions.

**Skills Used**: `Python`,  `FastF1`, `Scikit-learn`, `Pandas`, `Seaborn`, `Machine Learning`, `Regression`, `Feature Engineering`, `PCA`

---

## 3.Docs

This folder demonstrates my machine learning skills for predictive applications in F1.

### `Book_F1_2024` — *Clustering drivers style*
A comprehensive report summarising the main patterns and insights observed during the 2024 Formula 1 season. It combines statistical analysis, telemetry interpretation, and strategic evaluation to highlight performance differences across drivers and teams.

### `Hungary_2025_PIA_VS_NOR.ipynb` — *Strategic Driver Comparison: Piastri vs Norris*
A detailed head-to-head analysis of Oscar Piastri and Lando Norris during the 2025 Hungarian Grand Prix.
The notebook includes:
  - Driving style and stint comparison
  - Sector-by-sector performance
  - Strategic effectiveness evaluation
  - Tyre management analysis
  - Consistency assessment
  - Strategic synthesis with recommendations for future races
This project demonstrates the ability to combine data analysis, interpretation, and actionable recommendations—a skillset applicable to performance engineering and race strategy.

**Skills Used**: `Python`,  `FastF1`, `Pandas`, `Matplotlib`, `Numpy`, `Data Interpretation`, `Race Strategy`

---

## Installation
Clone this repository and install dependencies with:

```bash
pip install -r requirements.txt
```


To compile LaTeX reports (e.g. `Book_F1_2024`), make sure you have a LaTeX distribution installed that provides the `pdflatex` command:

- **Linux**: TeX Live (`sudo apt install texlive-full && sudo apt install texlive-latex-extra`)
- **macOS**: MacTeX
- **Windows**: MiKTeX

Then run:
```bash
pdflatex main.tex
```

---

## Cleaning LaTeX Auxiliary Files
When compiling LaTeX reports (e.g., Book_F1_2024), several auxiliary files are generated (.aux, .log, .out, etc.). These files are necessary during compilation but are not needed after the PDF is created. To keep the project directory clean, you can remove them safely :

```bash
chmod +x clean.sh
./clean.sh
```

---

## Contact

Feel free to contact me if you have any questions or would like to learn more about these projects.

- LinkedIn: [Laora Aimi](https://www.linkedin.com/in/laora-aimi-493285253)
- Email: laora.aimi@gmail.com