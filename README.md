# Impact of Music Type on Short-Term Memory Accuracy

**Project Overview**  
This project investigates the effect of different music types on short-term memory performance using **R**. A factorial experimental design was applied, and data was analyzed using **ANOVA and statistical inference**. The study demonstrates skills in **experimental design, statistical analysis, and data visualization** in R.

---

## Dataset
- Collected from a controlled study with volunteer participants.  
- Variables:
  - `participant_id`: Unique identifier for participants  
  - `music_type`: Type of music played (Classical, Pop, None)  
  - `task_score`: Accuracy on short-term memory tasks  
- Dataset anonymized to protect participant privacy.  

---

## Project Goals
- Determine whether music type influences short-term memory accuracy.  
- Use factorial ANOVA in **R** to test for statistical significance.  
- Visualize results for clear interpretation.  
- Submit findings to the **USCLAP competition**.

---

## Methods
1. **Experimental Design**
   - Factorial design with independent variable: `music_type`  
   - Dependent variable: `task_score`  
   - Participants randomly assigned to different music conditions  

2. **Data Analysis (R)**
   - Performed descriptive statistics using `dplyr`  
   - Conducted factorial ANOVA using `aov()`  
   - Checked assumptions: normality, homogeneity of variance using `shapiro.test()` and `leveneTest()` (from `car` package)  

3. **Visualization**
   - Created bar plots and boxplots using `ggplot2` to illustrate memory performance across music types  

---

## Results
- Music type showed trends in memory performance (replace with your actual findings):  
  - Classical music condition had slightly higher mean accuracy than Pop or No Music  
  - ANOVA results: F = X.XX, p = 0.XXX (replace with your actual p-value)  

---

## Tools & Technologies
- **Language:** R  
- **Packages:** `dplyr`, `ggplot2`, `car`, `stats`  
- **Environment:** RStudio  

---

## Contributions
- Responsibilities included:
  - Experimental design and data collection  
  - Data preprocessing and analysis in R  
  - Visualization and interpretation of results  
  - Report preparation for USCLAP submission  

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/music-memory-study.git
