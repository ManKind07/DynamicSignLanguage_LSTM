# DynamicSignLanguage_LSTM
Real-Time Sign Language AI: An end-to-end computer vision pipeline featuring MediaPipe coordinate extraction, Gaussian noise data augmentation, and an optimized Bidirectional LSTM with anti-flicker inference

# Real-Time Sign Language Detection AI

This project is an end-to-end machine learning pipeline that translates sign language into text in real-time using a standard webcam. It uses **MediaPipe Holistic** to extract facial, hand, and pose coordinates, and feeds them into a custom **Bidirectional LSTM** neural network. 

**Key Features:**
* **Custom Dataset Collection:** Built-in OpenCV data collection tool with pacing controls.
* **Gaussian Noise Augmentation:** Automatically expands the dataset and improves model spatial invariance.
* **Optimized LSTM Architecture:** Lightweight (< 1MB) sequential model with dropout regularization and a widened dense funnel to prevent bottlenecking.
* **Real-Time Inference:** Bypasses standard Keras prediction overhead for lag-free OpenCV webcam tracking.
* **Anti-Flicker Stabilizer:** Uses frame-skipping and consecutive-frame logic to ensure smooth, readable UI text during sign transitions.

<img width="758" height="582" alt="Screenshot 2026-04-06 024252" src="https://github.com/user-attachments/assets/d26a936a-fbd8-4093-92db-d174578d1510" />

<img width="750" height="193" alt="Screenshot 2026-04-06 040749" src="https://github.com/user-attachments/assets/75167326-2c1a-4084-82cd-e7139d517c4f" />

<img width="760" height="671" alt="Screenshot 2026-04-06 031716" src="https://github.com/user-attachments/assets/ec7db850-5f37-4bae-9a4e-833ae642a705" />
