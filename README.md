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
