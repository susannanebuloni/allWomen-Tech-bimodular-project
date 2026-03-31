# 📊allWomen-Tech-bimodular-project
# 😊 What Makes People Happy? A Data Analysis of Global Happiness

The `World Happiness Report` is a landmark survey of the state of global happiness that ranks 156 countries by how happy their citizens perceive themselves to be. Over the last year’s, `World Happiness Report` focuses on happiness and the community: how happiness has evolved over the past dozen years, with a focus on the technologies, social norms, conflicts and government policies that have driven those changes.

<img src="https://allthatsinteresting.com/wordpress/wp-content/uploads/2016/03/giphy-4.gif" width="700px">

**Dataset information**

The information in the datasets is based on answers to the most life evaluation address inquired within the survey. This address, known as the Cantril step, asks respondents to think of a step with the most excellent conceivable life for them being a 10 and the most exceedingly bad conceivable life being a and to rate their claim current lives on that scale.


The Happiness Score is explained by the following factors:

- `Overall rank`: happiness rank of the different countries
- `Country o region`
- `Score`:  is a national average of the responses to the main life evaluation question asked in the Gallup World Poll (GWP), which uses the Cantril Ladder. Ranges from [0-10]
- `GDP per capita`
- `Healthy Life Expectancy`: score that goes from [0-1], being 1 the ones that have more confidence in terms of healthy life
- `Social support`: it indicates how people are appreciating the social support by governments, and it that ranges from [0-2]
- `Freedom to make life choices` score that ranges from 0 to 1, being 1 the ones that feel more free
- `Generosity`:score that ranges from 0 to 1, being 1 the ones that feel more generosity
- `Perceptions of corruption`: perception of corruption on the country that it goes from  0 to 1. The higher this value is the lower perception of corruption
- `year`

---

## 🚀 Project Overview

This project explores the key factors that influence **global happiness levels**, using data from the *World Happiness Report*.

The goal is to answer a simple but powerful question:

> Which factors matter most for living a happier life?

By analyzing economic, social, and behavioral indicators across countries, this project uncovers the **main drivers of happiness** and how they interact.

---

## 🎯 Objectives

* Identify the most important factors influencing happiness
* Analyze relationships between economic and social variables
* Understand how happiness varies across countries and time
* Provide insights for both policy and individual well-being

---

## 🌍 Dataset

The dataset is based on the **World Happiness Report**, which measures happiness using the **Cantril Ladder** (a scale from 0 to 10 representing life satisfaction).

Key variables include:

* Happiness Score
* GDP per capita
* Social support
* Freedom to make life choices
* Generosity
* Perceptions of corruption
* Year (2018–2019)

---

## 🧠 Methodology

### Data Cleaning & Preparation

* Removed irrelevant columns
* Standardized country names (e.g., Macedonia → North Macedonia)
* Handled missing values by filtering and validation
* Ensured consistency across numerical and categorical variables

### Outlier Treatment

* Applied **IQR method** and **Z-score analysis**
* Capped extreme values instead of removing them
* Preserved meaningful variations in the data

### Exploratory Data Analysis (EDA)

* Distribution analysis (histograms, KDE plots)
* Correlation analysis between variables
* Bivariate and multivariate analysis
* Comparative analysis across years

---

## 📊 Key Findings

### 1. Happiness is Normally Distributed

* Global happiness scores follow a **bell-shaped distribution**
* Most countries cluster around a moderate level of happiness

---

### 2. The Two Main Drivers of Happiness

#### 💰 Economic Prosperity (GDP per capita)

* Strong positive correlation with happiness
* Provides stability and access to resources

#### 🤝 Social Support

* Equally important as economic factors
* Reflects trust, community, and emotional well-being

---

### 3. The “Dual Foundation” of Happiness

* The happiest countries combine:

  * High GDP
  * Strong social support

👉 Neither factor alone is enough—**they must work together**

---

### 4. Weak Predictors

* Generosity and perception of corruption show **weak or inconsistent relationships** with happiness

---

### 5. Stability Over Time

* Happiness patterns remain **consistent between 2018 and 2019**
* Suggests structural (not temporary) drivers of happiness

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 💡 Key Takeaway

> Happiness is built on a dual foundation: economic security and social connection.

Focusing on only one dimension limits overall well-being—true happiness emerges from the **interaction between wealth and community**.

---

## 👩‍💻 Author

**Susanna Nebuloni**
Tech Support Engineer transitioning into Data & Machine Learning

---

