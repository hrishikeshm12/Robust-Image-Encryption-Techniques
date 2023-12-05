# Robust-Image-Encryption-Techniques



## Overview

This project focuses on implementing image encryption using AES, Elliptical Curve Cryptography, and chaotic maps. The efficiency of each method is compared based on key sensitivity, adjacent pixel autocorrelation, and intensity histograms. The study explores the effectiveness of these techniques, providing insights for secure image encryption.
![image](https://github.com/hrishikeshm12/Robust-Image-Encryption-Techniques/assets/65590350/5cb1cb14-683c-46d9-a36a-81e9d9eea215)


## Key Metrics

- **Intensity Histogram:** Evaluates the randomness of the ciphertext image.
- **Adjacent Pixel Autocorrelation:** Measures information redundancy reduction.
- **Key Sensitivity:** Assesses the impact of slight key changes on encrypted images.

## Results

- **AES Image Encryption (Rubik’s Cube Method):** Outperformed simple AES, enhancing resistance to attacks.
- **Chaotic Maps (Arnold Cat, Henon, Logistic):** Logistic Chaos Maps exhibited superior performance in both intensity histogram and adjacent pixel autocorrelation.

## Recommendation

A combined system of AES and Logistic Chaos Maps is suggested as one of the most secure image encryption approaches. The project emphasizes the importance of careful algorithm selection for robust image security.

---
