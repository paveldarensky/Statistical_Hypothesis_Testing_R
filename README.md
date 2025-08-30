# 📊 Statistical Hypothesis Testing (R)

## 🌍 EN

### 📌 About  
This project demonstrates the generation of random samples from a **normal distribution** and the application of statistical hypothesis testing in R.  
It covers four scenarios with different combinations of means and variances between two samples (**X1** and **X2**).  

### 🔑 Features  
- ✅ Generation of two samples `X1` and `X2` (N = 100) from normal distributions with different parameters.  
- ✅ Four scenarios:  
  1. Equal means and equal variances.  
  2. Different means, equal variances.  
  3. Equal means, different variances.  
  4. Different means, different variances.  
- ✅ Statistical analysis:  
  - Shapiro–Wilk test (normality).  
  - Student’s t-test (equality of means).  
  - F-test (equality of variances).  
- ✅ Visualization:  
  - Histograms with density estimates and mean lines.  
  - Boxplots (whisker plots) for group comparison.  

### 📂 Project Structure  
- **Data generation** – creation of `X1`, `X2` using `rnorm()`.  
- **Hypothesis testing** – `shapiro.test()`, `t.test()`, `var.test()`.  
- **Visualization** – `ggplot2` histograms, density plots, boxplots.  

### 🖼️ Screenshots  
- 📊 Histogram + density curves with mean lines.  
- 📦 Boxplots for comparison of `X1` and `X2`.  

---

## 🌍 RU

### 📌 О проекте  
Проект посвящён генерации случайных выборок из **нормального распределения** и проверке статистических гипотез в языке R.  
Рассматриваются четыре ситуации с разными сочетаниями математических ожиданий и дисперсий двух выборок (**X1** и **X2**).  

### 🔑 Возможности  
- ✅ Генерация двух выборок `X1` и `X2` (N = 100) из нормального распределения с различными параметрами.  
- ✅ Четыре сценария:  
  1. Равные средние и равные дисперсии.  
  2. Разные средние, равные дисперсии.  
  3. Равные средние, разные дисперсии.  
  4. Разные средние и разные дисперсии.  
- ✅ Статистический анализ:  
  - Критерий Шапиро–Уилка (нормальность).  
  - t-критерий Стьюдента (равенство средних).  
  - F-критерий (равенство дисперсий).  
- ✅ Визуализация:  
  - Гистограммы с оценкой плотности и средними значениями.  
  - Boxplot (коробки с усами) для сравнения `X1` и `X2`.  

### 📂 Структура проекта  
- **Генерация данных** – создание `X1`, `X2` через `rnorm()`.  
- **Проверка гипотез** – `shapiro.test()`, `t.test()`, `var.test()`.  
- **Визуализация** – гистограммы и boxplot с помощью `ggplot2`.  

### 🖼️ Скриншоты  
- 📊 Гистограммы + оценки плотности с линиями средних.  
- 📦 Boxplot для сравнения `X1` и `X2`.  
