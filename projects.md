# Projects

This section showcases my data science projects, research questions, and data stories created throughout my coursework.

---

## 1. Pokémon TCG 2025 Market Price Analysis

### How much did 2025 Pokémon TCG products rise above retail?

For this project, I analyzed Pokémon TCG products released in 2025 to compare retail price baselines with secondary market prices. I used Python, pandas, API data, and data visualizations to determine which sets and product types experienced the largest price markups.

**Tools Used:**  
`Python` · `Pandas` · `Matplotlib` · `Jupyter Notebook` · `API`

**Skills Demonstrated:**  
Data Collection · Data Cleaning · Data Analysis · Data Visualization

### [ View Full Pokémon TCG Analysis →](https://github.com/LockdownKam/Data-Structures-Portfolio/blob/main/pokemon_tcg_market_analysis.ipynb)

---

### Project Highlights

- Analyzed **7 Pokémon TCG sets released in 2025**
- Compared retail price baselines with secondary market prices
- Examined differences between multiple sealed product types
- Calculated dollar price differences and percentage markups
- Created visualizations to compare sets and product categories

---

## 2. Freshwater Fish Habitat Prediction

### Can machine learning predict whether a freshwater fish species prefers flowing-water or still-water habitats?

For this project, I used the FishTraits dataset to investigate whether biological and environmental characteristics can be used to predict freshwater fish habitat preference. I used body size, feeding ecology, life-history traits, and environmental characteristics to compare multiple machine-learning models.

**Tools Used:**  
`Python` · `Pandas` · `Matplotlib` · `Scikit-learn` · `Jupyter Notebook`

**Skills Demonstrated:**  
Data Cleaning · Exploratory Data Analysis · Feature Selection · Classification · Model Evaluation · Cross-Validation · Hyperparameter Tuning

### [View Full Fish Habitat Analysis →](https://github.com/LockdownKam/Data-Structures-Portfolio/blob/main/Aquarium_Research_Project.ipynb)

### Variables Used

The final model used 13 biological and environmental features:

| Variable | Description |
|---|---|
| `MAXTL` | Maximum total body length |
| `MATUAGE` | Age at maturity |
| `LONGEVITY` | Longevity of the species |
| `FECUNDITY` | Reproductive output |
| `BENTHIC` | Benthic or bottom-feeding behavior |
| `SURWCOL` | Surface or water-column feeding behavior |
| `ALGPHYTO` | Feeding on algae or phytoplankton |
| `MACVASCU` | Feeding on aquatic vascular plants |
| `DETRITUS` | Feeding on detritus |
| `INVLVFSH` | Feeding on invertebrates |
| `FSHCRCRB` | Feeding on larger prey such as fish, crayfish, crabs, or frogs |
| `MINTEMP` | 30-year average minimum January temperature at the species' range centroid |
| `MAXTEMP` | 30-year average maximum July temperature at the species' range centroid |

---

### Project Highlights

- Analyzed 809 freshwater fish species with 110 original variables
- Created a classification target for flowing-water and still-water habitat preference
- Compared a baseline classifier, Decision Tree, and Random Forest
- Used balanced accuracy to account for class imbalance
- Used 5-fold cross validation and hyperparameter tuning to improve model performance
- Selected a tuned Random Forest with 71.9% balanced accuracy
- Improved recall for still-water species from 45% to 59%
- Used permutation importance and error analysis to interpret model performance

---
