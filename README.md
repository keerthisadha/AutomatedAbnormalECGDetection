# Automated Abnormal ECG Detection  for Early Heart Disease Diagnosis

### Overview

This project focuses on developing a **wireless ECG monitoring system** using Arduino Uno that transmits data to another device via WiFi or Bluetooth. The collected ECG data will be processed and analyzed using a **machine learning (ML) model** to provide insights into cardiac health. The system aims to detect abnormalities, such as arrhythmias and other cardiac conditions, in real-time, thereby enabling **early diagnosis** and continuous monitoring of heart function.

---

### Abstract

The project aims to create a **wireless ECG monitoring system** utilizing Arduino Uno, which captures real-time ECG signals using an ECG sensor module and transmits the data via **WiFi or Bluetooth** to another device for further processing. The collected data is analyzed using **machine learning (ML) models** to detect potential cardiac abnormalities, including arrhythmias and heart failure. The system incorporates real-time monitoring and data transmission capabilities, making it a valuable tool for cardiac health analysis. This project combines hardware design, wireless communication, and ML-based health diagnostics to provide real-time, actionable insights into the user’s cardiac condition, improving **health monitoring** and **intervention strategies**.

---

### Methodology

1. **ECG Signal Acquisition**: 
   - Arduino Uno equipped with an ECG sensor module collects **real-time ECG signals** from the user.
  
2. **Wireless Data Transmission**: 
   - WiFi or Bluetooth modules enable the system to **transmit ECG data** wirelessly to a computer or smartphone for further processing.

3. **Preprocessing of ECG Data**:
   - Collected ECG signals are preprocessed by removing noise, applying filtering techniques, and detecting the R-peaks (QRS complex) for accurate analysis.
  
4. **ML Model Development**:
   - A **LSTM-based model** is trained using the MIT-BIH Arrhythmia dataset to classify different types of arrhythmias.
   - Data augmentation techniques like signal scaling and noise addition are applied to enhance model performance.
   - The model analyzes key health metrics, including **arrhythmias, QT intervals, ST segment, and heart rate variability**.

5. **Real-Time Monitoring and Display**:
   - The user interface provides a **real-time display** of ECG waveforms and health analysis results, enabling continuous monitoring.
  
6. **Health Analysis**:
   - The ML model detects **cardiac conditions** like arrhythmia, heart failure risk, and myocardial infarction through signal classification.

7. **Testing and Refinement**:
   - System functionality is tested, and the **accuracy of the ML model** is evaluated using metrics like precision, recall, and F1-score.

---

### Conclusion

The project successfully developed a **wireless ECG monitoring system** using Arduino Uno and machine learning for cardiac health analysis. The real-time transmission and ML-based diagnostics provide **early detection** of cardiac abnormalities, potentially improving patient outcomes through timely intervention. The system's **high accuracy**, as demonstrated by the LSTM-based model, makes it a promising tool for **telemedicine** and routine health monitoring. Further refinements, including model optimization and validation, will ensure the system's reliability in real-world applications.
