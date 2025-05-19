# Captcha-Decoder and AI-Resistant CAPTCHA Countermeasure System

This project explores the vulnerabilities of traditional CAPTCHA systems in the age of AI and deep learning, and proposes a robust, interactive, clock-based CAPTCHA mechanism that is resistant to automated attacks.

---

## Overview

With the evolution of deep learning and computer vision, AI models are now capable of decoding most traditional alphanumeric CAPTCHAs with high accuracy. This poses a serious threat to web security.

This project is divided into two parts:

1. **CAPTCHA Decoding**  
   Using Convolutional Neural Networks (CNNs) like **MobileNetV2** and **Xception** to decode standard alphanumeric CAPTCHAs.

2. **AI-Resistant Countermeasure**  
   A novel **canvas-based clock CAPTCHA** that requires users to set the correct time on an interactive analog clock—something difficult for bots to solve.

---

## Key Features

### CAPTCHA Decoding using AI
- Train and evaluate CNN models to decode traditional alphanumeric CAPTCHA images.
- **Models used**: MobileNetV2, Xception
- Achieves high accuracy on static CAPTCHA datasets.

### Interactive Clock-Based CAPTCHA (AI-Resistant)
- User must **set the correct time** on an interactive analog clock using the Canvas API.
- Resilient against CNN-based attacks and OCR tools like Tesseract.
- Validates user interaction rather than relying on static image recognition.
- Leverages human intuition and interaction to strengthen authentication.

---

## Tech Stack

### AI and Machine Learning
- **Python**
- **TensorFlow / Keras** – For training CNN models
- **OpenCV** – Image preprocessing and manipulation

### Web Application
- **HTML, CSS, JavaScript** – Frontend for the interactive clock CAPTCHA
- **Canvas API** – Rendering and interacting with the analog clock
- **Flask (Python)** – Backend server for generating and validating CAPTCHA challenges

---

## Conclusion

This project demonstrates the increasing vulnerability of traditional CAPTCHA systems to modern AI models and introduces a **novel, human-centric alternative**. By leveraging **user interaction** and **intuitive tasks** like setting a clock, the **canvas clock CAPTCHA** provides strong resistance to automated attacks, outperforming static CAPTCHA methods in security and usability.

---

## 📂 Repository Structure (Optional)

