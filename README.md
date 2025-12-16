# Privacy Preserving Similarity Search System in Cloud

## 📌 Project Overview

The **Privacy Preserving Similarity Search System in Cloud** is a secure data analysis application designed to enable similarity search and visualization over sensitive datasets without exposing raw data. The system integrates **data encryption**, **dimensionality reduction (PCA)**, and **visual analytics** to ensure confidentiality while still allowing meaningful insights.

This project is especially useful in domains like **healthcare**, **finance**, and **enterprise analytics**, where data privacy is critical.

---

## 🎯 Objectives

* Protect sensitive data before storing or processing it in the cloud.
* Enable similarity search without revealing original data values.
* Provide visual insights using privacy-safe embeddings.
* Demonstrate practical implementation of privacy-preserving data analytics.

---

## 🛠️ Technologies Used

* **Python**
* **Streamlit** (for interactive web UI)
* **Pandas & NumPy** (data processing)
* **Scikit-learn** (PCA for dimensionality reduction)
* **Cryptography / Custom Encryption Logic**
* **VP-Tree / Distance-based Similarity Search**

---

## 🔐 Key Features

* **CSV Dataset Upload**
* **Missing Value Handling** (auto-filled with 0)
* **Dataset Encryption & Decryption**
* **Privacy-Preserving Similarity Computation**
* **PCA-based Visualization**
* **Scatter Plot & Histogram Views**
* **Dark Mode UI Support**
* **Encrypted Dataset Download**

---

## 📂 System Workflow

1. Upload dataset (CSV file)
2. Handle missing values automatically
3. Encrypt the dataset before processing
4. Compute similarity on encrypted data
5. Reduce dimensions using PCA
6. Visualize embeddings securely
7. Perform similarity queries
8. Decrypt results if authorized

---

### **Image 1: Privacy-Preserving Similarity Search Dashboard**

This image shows the **main application interface** of the system.
![privacy-pic1](https://github.com/user-attachments/assets/aad352a6-0416-4f3d-b516-be91f9fb5f14)

**What it includes:**

* Dataset upload panel
* Raw dataset preview (after missing value handling)
* Encryption, computation, and decryption buttons
* Status messages for processing steps

**Purpose:**

* Acts as the **control center** for the entire system.
* Demonstrates how users can securely upload and process data.
* Ensures users never directly operate on unprotected cloud data.

### **Image 2: Dataset Scatter Plot (PCA Reduced)**

This image displays a **scatter plot of the dataset after PCA dimensionality reduction**.
![privacy-graph1](https://github.com/user-attachments/assets/de995def-084c-4f7a-92e9-cecbd72bcb5c)

**What it shows:**

* Each dot represents a **single data record** from the dataset.
* High-dimensional encrypted data is reduced to **two principal components (X and Y axes)**.
* Points that are **closer together indicate higher similarity**.

**Purpose:**

* Helps visually identify **clusters, patterns, and outliers**.
* Ensures visualization is done on transformed data, not raw sensitive values.
* Useful for understanding similarity relationships in a privacy-safe manner.

---

### **Image 3: Dataset Histogram (First PCA Component)**

This image represents a **histogram of the first principal component** after PCA.
![privacy-graph2](https://github.com/user-attachments/assets/f0355fb9-5cd6-4394-bf0c-3b10a075720c)

**What it shows:**

* X-axis: Values of the first PCA component
* Y-axis: Frequency (count of records)
* Distribution of data along the primary variance direction

**Purpose:**

* Helps analyze **data spread, variance, and skewness**.
* Identifies dominant value ranges in the transformed dataset.
* Assists in detecting anomalies or uneven distributions.

---


https://github.com/user-attachments/assets/fd3ded13-a1b4-4c23-9744-d64c41b2e885


## 🔍 Similarity Search Mechanism

* Data is encrypted before similarity computation.
* Distance-based search (e.g., Euclidean distance) is applied on encrypted or transformed vectors.
* VP-Tree structure enables efficient nearest-neighbor searches.
* Results preserve similarity order without revealing actual values.

---

## 🧠 Use Cases

* Healthcare record similarity analysis
* Secure document or feature matching
* Privacy-aware machine learning preprocessing
* Academic research on secure data mining

---

## ✅ Advantages

* Strong data privacy protection
* Cloud-safe computation
* Interactive and user-friendly UI
* Supports secure analytics and visualization

---

## 🚀 Future Enhancements

* Integration with Homomorphic Encryption
* Role-based access control
* Support for large-scale datasets
* Advanced clustering visualizations
* Cloud deployment with secure key management

---

## 👨‍💻 Author

**Mohammed Nawaz**
Aspiring Computer Science Engineer | Cybersecurity & Privacy Enthusiast

---

## 📜 License

This project is intended for **academic and educational purposes**.
