# EEG Time-Series Analysis Using Multiscale Entropy  
This project analyzes EEG time-series data from three groups of children:  
- **Healthy individuals**  
- **ADD (Attention Deficit Disorder)**  
- **ADHD (Attention Deficit Hyperactivity Disorder)**  

Using **Multiscale Entropy (MSE)** and statistical measures, the study compares signal complexity across electrode channels to reveal meaningful physiological differences between the groups.

---

## 🧠 Abstract  
The multiscale entropy method is used to study correlation and complexity in time-series signals at multiple scales. By coarse-graining the EEG time series and calculating sample entropy at each scale, it becomes possible to identify patterns of signal stability, randomness, and correlation.

This method has been widely used for biological signals such as heart-rate variability and human motion dynamics. Prior research shows that multiscale entropy can distinguish between healthy individuals and those with specific neurological or physiological disorders.

In this project, we apply multiscale entropy to EEG data from healthy children, children with ADD, and children with ADHD. Our findings indicate that the MSE method is effective for differentiating between these three groups and may support mental disorder diagnostics.

---

## 🎯 Objectives  
- Analyze EEG time-series recordings using multiscale entropy  
- Compare entropy trends between healthy, ADD, ADHD-I, and ADHD-C groups  
- Use frequency-domain analysis (FFT) to observe power differences  
- Apply descriptive statistics (mean, variance, standard deviation) to group-level entropy curves  
- Identify patterns that may help distinguish neurological conditions  

---

## 📊 Methods Summary  
This analysis includes:

### **1. Time-Series Pattern Examination**  
Raw EEG time-series signals were plotted to observe general behavior across subjects and conditions.

### **2. Frequency-Domain Analysis (FFT)**  
FFT was applied to the signals to evaluate dominant frequency components and compare spectral characteristics between groups.

### **3. Multiscale Entropy (MSE)**  
- Time-series were coarse-grained across increasing scale factors  
- Sample entropy was computed for each scale  
- Entropy curves were compared across electrodes and participant groups  

### **4. Statistical Analysis**  
Group-level metrics such as:
- Mean entropy  
- Variance  
- Standard deviation  
were calculated to identify consistent differences between conditions.

---

## 📌 Key Findings 
- Multiscale entropy revealed **clear differences** between healthy and disordered groups.  
- Pink-noise-like behavior appeared in more stable groups, while high-variance entropy curves indicated reduced signal complexity in ADD/ADHD.  
- FFT revealed frequency distinctions between healthy subjects and those with attentional disorders.  
- Statistical metrics confirmed that entropy variability was significantly higher in ADD/ADHD groups.  
- Overall, MSE proved to be a **useful method for distinguishing neurological conditions**.

---

## 🧩 Technologies Used  
- **Python** (NumPy, SciPy, Matplotlib)  
- **Signal processing**  
- **Multiscale entropy algorithms**  
- **Statistical data analysis**

---

## 📚 Keywords  
Multiscale Entropy · Time Series · EEG · Correlation · ADD · ADHD-I · ADHD-C

---

## 🔎 About the Data  
EEG recordings were analyzed from multiple electrodes and compared across the three groups. The entropy plots reveal behavioral and physiological differences that may support diagnostic insights.


---


 
