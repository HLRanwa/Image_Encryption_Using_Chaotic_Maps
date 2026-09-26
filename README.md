# 🔐 Image Encryption Using Chaotic Maps

A Python-based image encryption project that combines the **Logistic Map** and **Hénon Map** to generate chaotic sequences for secure image pixel permutation and diffusion.

The project demonstrates the application of **chaos theory, cryptography, and image processing** for digital image security.

## ✨ Features

* Logistic Map-based chaotic sequence generation
* Hénon Map-based chaotic sequence generation
* Pixel permutation and diffusion
* Image encryption and decryption
* Histogram analysis
* Pixel correlation analysis
* Entropy-based randomness analysis
* Key sensitivity analysis
* Jupyter Notebook implementation

### Encryption Flow

```text
Input Image
     ↓
Logistic Map
     ↓
Pixel Permutation
     ↓
Hénon Map
     ↓
Pixel Diffusion
     ↓
Encrypted Image
```

The reverse process is used for decryption.

## 🛠️ Tech Stack

* **Python**
* **NumPy**
* **Pillow**
* **Matplotlib**
* **Jupyter Notebook**


## 🚀 Installation

```bash
git clone https://github.com/HLRanw/image-encryption-using-chaotic-maps.git
cd image-encryption-using-chaotic-maps
pip install -r requirements.txt
jupyter notebook
```

Open the `.ipynb` file and run the cells sequentially.

## 📊 Security Analysis

The implementation can be evaluated using:

* **Histogram Analysis** — evaluates pixel distribution
* **Entropy** — measures randomness
* **Correlation Coefficient** — measures neighboring-pixel correlation
* **NPCR** — evaluates pixel change rate
* **UACI** — evaluates average intensity change
* **Key Sensitivity** — evaluates the effect of small key changes

## 🖼️ Results

| Original       | Encrypted       | Decrypted       |
| -------------- | --------------- | --------------- |
| Original Image | Encrypted Image | Recovered Image |


## 🎯 Applications

* Secure image transmission
* Digital image protection
* Multimedia security
* Cybersecurity research
* Cryptography education

## 🔮 Future Scope

* RGB image encryption
* Hybrid chaotic maps
* GPU-based acceleration
* Advanced cryptanalysis
* Web-based encryption interface
* Extended security and performance analysis

## ⚠️ Disclaimer

This project is intended for **educational and research purposes**. It demonstrates a chaos-based image encryption technique and should not be considered a replacement for professionally reviewed cryptographic algorithms such as AES.

## 👨‍💻 Author

**Harlal Ranwa**

B.Tech Computer Science & Engineering
Cybersecurity

## ⭐ Keywords

`Python` `Cryptography` `Cybersecurity` `Image Encryption` `Chaotic Maps` `Logistic Map` `Henon Map` `Image Processing` `Jupyter Notebook`
