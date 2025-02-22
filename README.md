# 🎵 Music Genre Classification and Algorithm Performance Analysis

## 📌 Project Overview
This project focuses on the **automatic classification of music genres** using machine learning techniques. The **GTZAN dataset** was utilized, which consists of **1,000 tracks from 10 different genres**. The primary goal is to **train and compare various classification algorithms** and identify the most effective model for music genre classification.

## 🗂 Dataset: GTZAN
The dataset includes **30-second .wav files** from the following genres:
- Blues
- Classical
- Country
- Disco
- Hip-Hop
- Jazz
- Metal
- Pop
- Reggae
- Rock

Each genre contains **100 tracks**, totaling **1,000 songs**.

## ⚙️ Methods and Tools
- **Platform:** MATLAB
- **Tool:** MATLAB Classification Learner App
- **Preprocessing:** The dataset was converted into **1D input signals** before classification.

## 📊 Machine Learning Algorithms Used
A total of **11 classification algorithms** were tested:

| Algorithm               | Accuracy (%) |
|-------------------------|-------------|
| Fine Tree              | 36.57       |
| Medium Tree            | 38.83       |
| Coarse Tree            | 40.18       |
| Linear SVM             | 58.01       |
| Quadratic SVM          | 59.82       |
| Fine KNN               | 38.15       |
| Medium KNN             | 36.34       |
| Coarse KNN             | 25.06       |
| Boosted Trees          | 49.89       |
| Narrow Neural Network  | 52.14       |
| Medium Neural Network  | 55.30       |

## 🏆 Best Performing Model
The **Quadratic SVM algorithm** achieved the **highest accuracy (59.82%)**, making it the most effective model for classifying music genres.

## 🎛 User Interface
A **MATLAB App Designer-based GUI** was developed, allowing users to:
- **Upload** a music file
- **Select** a classification algorithm
- **View** the predicted genre
- **Visualize** the frequency spectrum of the uploaded track

## 📌 Key Findings
- The **Quadratic SVM model** demonstrated superior classification performance.
- **Linear SVM and Neural Networks** also produced promising results.
- **KNN-based models performed poorly**, especially with large neighbor values.
- **Confusion matrices** showed that **higher accuracy models classified genres more effectively**.

- 
## 📷 Screenshots

### 🎛 User Interface
Below is a screenshot of the developed MATLAB application interface:

![User Interface](Screenshots/Ekran%20G%C3%B6r%C3%BCnt%C3%BCs%C3%BC%20(525).png)

![User Interface 2](Screenshots/Ekran%20G%C3%B6r%C3%BCnt%C3%BCs%C3%BC%20(526).png)



### 📊 Model Performance
The following image displays the classification results:

![Classification Results](Screenshots/Ekran%20Görüntüsü%20(527).png)


