# Global Performance of a Skin Disease AI Algorithm

## Overview
This study evaluates the real-world performance of **ModelDerm** ([https://modelderm.com](https://modelderm.com)), an AI model capable of classifying **186 dermatologic conditions** from clinical photographs. The study leveraged:
- **152,443 macroscopic images** of **70 skin conditions** sourced from **9 universities in Korea**.
- **1.69 million AI-driven diagnoses** across **227 countries** over **2.5 years**.
- **Global reader tests** in **138 countries**. [Quiz Statistics](https://modelderm.com/quiz_stat.html)

This study introduces a **novel method** to estimate **real-world sensitivity and specificity**, providing crucial insights into dermatology AI's role in global healthcare.

## Global Disease Distribution
The following figure illustrates the worldwide distribution of skin conditions classified by the algorithm:

![Global Disease Distribution](https://github.com/whria78/nia/blob/main/map/Figure2.jpg)

## How to Use the ModelDerm MySQL Database Dump
The **modelderm.sql.zip** file contains a **MySQL database dump** for ModelDerm. To restore it, follow these steps:

### **1. Extract the Dump File**
```bash
unzip modelderm.sql.zip
```

### **2. Create a New MySQL Database**
```sql
CREATE DATABASE modelderm;
```

### **3. Import the SQL Dump**
```bash
mysql -u [your-username] -p modelderm < modelderm.sql
```
Replace `[your-username]` with your MySQL username.

## Interactive DEMO
Experience **ModelDerm's AI-powered skin disease diagnosis** via our **interactive demo**:
👉 **[Live DEMO](https://whria78.github.io/nia/demo)**

### DEMO Screenshot
![DEMO Screenshot](https://github.com/whria78/nia/blob/main/demo/capture.JPG)

---
For more details, visit **[ModelDerm](https://modelderm.com)** or explore our **[GitHub repository](https://github.com/whria78/nia)**!
