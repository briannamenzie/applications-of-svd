## **Image Compression & PCA on NBA Player Statistics**
This project explores two applications of linear algebra:

### **1. Image Compression using SVD**

- Used SVD to compress a 5712×4284 image of my dog Zoe.
- Generated k-rank approximations (k= 1, 5, 10, 50, 100)
- Compared how rank reduction affects image quality and reconstruction.
- Outputs include rank-k approximations of the original image.

### **2. Principal Component Analysis (PCA) on NBA Player Statistics**

- Used the 2023–2024 NBA player dataset (after cleaning and selecting numeric features).
- Standardized features and performed PCA to reduce dimensionality (572x16 after cleaning).
- First 7 PCs explain >90% variance.
- The first three principal components explained ~74% of total variance, revealing key player performance patterns.
  - PC1 = overall activity
  - PC2 = playmaker vs. scorer
  - PC3 = center vs perimeter

### **Notes**
- These projects were completed as part of a school assignment and are intended for personal learning. The code is not modular or optimized—I’m simply sharing my work.
