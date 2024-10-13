# 📊 Statistics in Connected Healthcare
### Hasso Plattner Institute

---

## 📖 Overview

Welcome to our repository for the course **Statistics in Connected Healthcare** at the Hasso Plattner Institute! This study explores the impact of phone usage on acceleration levels during various activities, specifically focusing on sitting and walking with a smartphone.

---

## 🎯 Study Goals

The primary objective of this study is to distinguish between phone usage and non-usage by analyzing accelerometer data collected from **15 participants**. Each participant engaged in four distinct activities for at least **20 seconds** each:

1. **Sitting** with the phone in their pocket
2. **Sitting** while playing a mobile game (which requires tilting the phone)
3. **Walking** with the phone in their pocket
4. **Walking** while playing the mobile game (which requires tilting the phone)

For the mobile game, we used the **Classic Labyrinth 3D Maze** game, which involves tilting the phone. You can find the game here:
- [App Store](https://apps.apple.com/us/app/classic-labyrinth-3d-maze/id1229581951)
- [Play Store](https://play.google.com/store/apps/details?id=de.pictofun.labyrinthone&hl=en&gl=US&pli=1)

Additionally, we collected acceleration data using the **Sensor Log** app by HFalan:
- [Sensor Log App](https://m.apkpure.com/sensor-log/com.hfalan.activitylog)

---

## 📋 Data Collection Methodology

- **Single Phone**: A single phone was used for data collection.
  
- **Background Data Collection**: The Sensor Log app collected data in the background.

- **Game Scenario**: Participants played the labyrinth maze game with the goal of acquiring as many keys as possible.

- **Game Duration**: 20-30 seconds.

- **Data Duration**: Accelerometer data was recorded for 15-20 seconds.
---

## Hypotheses
- **H1_sit**: The mean acceleration magnitude while sitting with the phone is different from while sitting without the phone.  

- **H0_sit**: The mean acceleration magnitude while sitting with the phone is equal to while sitting without the phone.  

---
- **H1_walk**: The mean acceleration magnitude while walking with the phone is less than while walking without the phone.  

- **H0_walk**: The mean acceleration magnitude while walking with the phone is greater than or equal to while walking without the phone.  

---
<img width="400" alt="Screenshot 2024-10-13 at 9 58 58 PM" src="https://github.com/user-attachments/assets/ea9d2e82-a9d4-4fa7-b3c9-3e0dcf8a1e50">

## Statistical Methods Used

1. **T-Test**: Assuming normal distribution.
2. **Wilcoxon Signed-Rank Test**: No assumption of normal distribution.

## Key Findings
Both the **t-test** and the **Wilcoxon Signed-Rank Test** reject the null hypotheses H0_sit and H0_walk. This indicates that phone usage can be detected based on acceleration levels during both sitting and walking activities. 

---

## Conclusion

The results demonstrate the potential of machine learning approaches in activity recognition using smartphone accelerometers. We identified significant differences in acceleration, but limitations in sample size and demographic homogeneity (ages 18 to 30) indicate the need for broader studies. Future research should focus on natural phone usage behaviors over extended periods and include a more diverse participant pool.

---

## 🚀 Getting Started

To reproduce the analysis or work with the data, clone this repository and open the **`final_report_analysis.Rmd`** file in RStudio.
