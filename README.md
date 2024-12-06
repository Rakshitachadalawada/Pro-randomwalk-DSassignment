# Pro-randomwalk-DSassignment
# Penguin Dataset Analysis 🐧  

This repository contains an analysis of the **Palmer Penguins dataset**, focusing on exploring the data, identifying patterns, and applying preprocessing techniques. The project includes various tasks such as handling missing values, visualizing distributions, detecting outliers, and performing normalization.  

---

## Dataset Overview 📊  
The dataset provides information about three penguin species (*Adelie*, *Gentoo*, and *Chinstrap*) across three islands in Antarctica.  

### Features:  
- **species**: Penguin species (Adelie, Gentoo, Chinstrap)  
- **island**: Island where the penguin was found (Biscoe, Dream, Torgersen)  
- **bill_length_mm**: Length of the penguin's bill (mm)  
- **bill_depth_mm**: Depth of the penguin's bill (mm)  
- **flipper_length_mm**: Length of the penguin's flipper (mm)  
- **body_mass_g**: Body mass of the penguin (g)  
- **sex**: Gender of the penguin  

---

## Tasks Performed 🛠  

### **1. Data Cleaning**  
- Handled missing values by removing rows with incomplete data.  
- Ensured all features were correctly formatted.  

### **2. Analysis**  
- Found the average body mass of Gentoo penguins.  
- Compared distributions of `bill_length_mm` and `bill_depth_mm` across species using skewness and kurtosis.  

### **3. Outlier Detection**  
- Identified outliers using the **IQR method** for numerical features.  

### **4. Visualization**  
- Plotted various graphs (scatter, histograms, etc.) to visualize the relationship between `bill_length_mm` and `bill_depth_mm`.  

### **5. Normalization**  
- Applied **z-score normalization** to standardize numerical features for better comparisons.  

### **6. Insights**  
- Identified the species with the longest flipper length on each island.  

---

## Setup and Usage 🚀  

### **Requirements**  
- Python 3.7+  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, `sklearn`  


