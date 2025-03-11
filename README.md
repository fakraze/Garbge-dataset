
# Garbage Dataset

This dataset contains **5 categories** of garbage images for classification tasks:
| Category  | Number of Images |
|-----------|----------------|
| **Cardboard** | 305 |
| **Glass** | 112 |
| **Plastic** | 100 |
| **Metal** | 113 |
| **Paper** | 100 |

Total images: **730**

## Dataset Structure

```
├── dataset
│   | cardboard
│     ├── 1.jpg
│     ├── 2.jpg
│     ├── 3.jpg
│     ├── ...
│   | glass
│     ├── 1.jpg
│     ├── 2.jpg
│     ├── 3.jpg
│     ├── ...
│   | plastic 
│     ├── 1.jpg
│     ├── 2.jpg
│     ├── 3.jpg
│     ├── ...
│   | metal  
│     ├── 1.jpg
│     ├── 2.jpg
│     ├── 3.jpg
│     ├── ...
│   | paper
│     ├── 1.jpg
│     ├── 2.jpg
│     ├── 3.jpg
│     ├── ...
```

---

## **📌 Data Type**
- **Image Format:** `.jpg`
- **Image Resolution:** `256x256`
- **Color Mode:** RGB
- **Data Labels:** 5 categories (cardboard, glass, plastic, metal, paper)

---

## **📌 External Sources**
- We used [This Kaggle dataset](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification/data) as a reference.

---

## 📌 Data Collection Conditions  
- **Image Size:** All images were resized to **256×256** pixels for consistency.  
- **Data Augmentation:** No artificial augmentation was applied.

---

## 📌 Data Collection Process  
This dataset was collected by **曾紹幃** and **林悦揚**.  
We utilized images from [this Kaggle dataset](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification/data) to perform reverse image search on Google for dataset expansion.  

- **Plastic** and **Paper** were collected by **曾紹幃**.  
- **Cardboard**, **Glass**, and **Metal** were collected by **林悦揚**.  

---

## **📌 Example Images**
| Cardboard | Glass | Plastic | Metal | Paper |
|-----------|-------|---------|-------|-------|
| ![1](https://github.com/user-attachments/assets/399873fc-16ae-4436-a9d9-d1c51ec53597) | ![1](https://github.com/user-attachments/assets/8292ea02-2282-4cbc-9db3-00d6e514ac29) | ![1](https://github.com/user-attachments/assets/2487b036-fd12-4a92-8490-26d971e37416) | ![1](https://github.com/user-attachments/assets/5a02ffd7-1f60-4f9b-b004-7a43bb81b238) | ![1](https://github.com/user-attachments/assets/3afffac0-582d-4a26-b4fd-ca3828f8216d)|

---

