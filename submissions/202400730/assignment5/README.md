# Assignment 5: Model Training Report

## 1. Model Architecture
* **Model:** Random Forest Classifier (Scikit-learn)
* **Input Features:** 수면시간, 식사여부, 스트레스, 주종(One-Hot Encoding), 음주량
* **Output:** 숙취 발생 여부 (0: Safe, 1: Hangover)

## 2. Evaluation Results
* **Accuracy:** 0.6
* **F1-Score:** 0.58
* **Insight:** 데이터 양이 적지만(50건), Random Forest 모델이 컨디션과 음주량의 복합적인 관계를 잘 학습하여 유의미한 예측 결과를 보여줍니다.

## 3. Model Weights Link
* [https://drive.google.com/file/d/1afMO_Ca0660h2V5LvfGwl97RGiyHRZLY/view?usp=sharing]