
# 💄 Bangladeshi Cosmetic Products Image Classifier

An intelligent Android application that uses **TensorFlow Lite** and **on-device machine learning** to classify **50+ popular Bangladeshi cosmetic, skincare, and hygiene products** in real time through camera-based image recognition.

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge\&logo=android\&logoColor=white)
![TensorFlowLite](https://img.shields.io/badge/TensorFlow_Lite-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge\&logo=openjdk\&logoColor=white)

---

## 📱 App Preview

<div align="center">

-- App Logo --

![pic1](https://i.postimg.cc/k4q3Vwyh/1.png)



-- App UI Interface --

![pic2](https://i.postimg.cc/Bnhf82zD/Screenshot-2025-11-24-191027.png)



-- Android Studio Working Space --

![pic3](https://i.postimg.cc/nck65vpw/Screenshot-2025-11-24-191133.png)


![pic4](https://i.postimg.cc/KYdVLfDn/Screenshot-2025-11-24-191150.png)


![pic5](https://i.postimg.cc/kXfpwqvN/Screenshot-2025-11-24-191211.png)


-- Android Studio ( Camera Classification & Results Screen ) --

![pic6](https://i.postimg.cc/mgj6XR3N/Screenshot-2025-11-24-190423.png)


</div>

---

## ✨ Features

* **📸 Real-time Camera Classification**
  Instantly detect cosmetic products using your device camera.

* **🤖 TensorFlow Lite Model**
  On-device ML model trained on Bangladeshi cosmetic datasets.

* **🎯 High Accuracy**
  Predicts top results with confidence percentages.

* **🧴 Covers 50+ Product Types**
  Includes soaps, shampoos, face washes, oils, lotions, toothpaste, tissues, and more.

* **⚡ Fast & Lightweight**
  Powered by TFLite — no internet required for inference.

* **🎨 Clean & Simple UI**
  Smooth material-design interface for effortless use.

---

## 🛠️ Technologies Used

* **Android SDK**
* **TensorFlow Lite**
* **Java**
* **CameraX / MediaStore APIs**
* **Material Design Components**

---

## 📦 Installation

### Prerequisites

* Android Studio (Arctic Fox or newer)
* Android SDK 24+
* Minimum device API Level: **24**

### Build Steps


git clone https://github.com/omijr123/BangladeshiCosmeticProductsImageClassifier.git


1. Open the folder in **Android Studio**
2. Let Gradle sync automatically
3. Connect your Android device / use emulator
4. **Run the project**

---

## 🧴 Supported Cosmetic Product Classes

The model identifies **50+ Bangladeshi cosmetic products**, including:

### 🧼 Soaps

* Lux Purple Lotus & Cream
* Dove Beauty Bar White
* Sandalina Sandal & Rose Soap
* Meril Milk & Beli Soap Bar
* Studio X Clean & Fresh Soap (Men)

### 🚿 Shampoos

* Clear Men Anti-Dandruff Shampoo
* Sunsilk Thick & Long Shampoo
* Tresemmé Keratin Smooth Shampoo

### 🧴 Creams, Lotions & Oils

* Fair & Lovely Advanced Multi Vitamin Cream
* Jui Coconut Oil
* Nivea Soft Light Moisturiser
* Nivea Intensive Moisture Body Milk
* Vaseline Deep Restore Lotion

### 🧼 Handwash

* Lifebuoy Handwash Total
* Dettol Handwash Original

### 😌 Facial Care

* Clean & Clear Foaming Face Wash
* Men’s Glow & Handsome Face Wash

### 🧻 Tissue & Hygiene

* Fresh Perfumed Facial Tissue
* Bashundhara Gold Toilet Tissue

### 🪥 Dental Care

* Pepsodent Germi Check+ Toothpaste

### 📋 FullLabel List

*(Extracted from your project’s MainActivity.java)*

<details>
<summary>Click to view all product classes</summary>

Clear Men Anti-Dandruff Shampoo
Sunsilk Thick & Long Shampoo
Fair & Lovely Advanced Multi Vitamin Cream
Lux Purple Lotus & Cream Bar Soap
Dove Beauty Bar White
Sandalina Sandal & Rose Soap
Meril Milk & Beli Soap Bar
Men's Glow & Handsome Face Wash
Studio X Clean & Fresh Soap
Jui Coconut Oil
Tresemmé Keratin Smooth Shampoo
Nivea Soft Moisturiser
Nivea Intensive Moisture Body Milk
Lifebuoy Total Handwash Pump
Dettol Original Liquid Handwash
Clean & Clear Foaming Face Wash
Vaseline Deep Restore Lotion
Fresh Perfumed Facial Tissue
Bashundhara Gold Toilet Tissue
Pepsodent Germi Check+ Toothpaste
*(… and more depending on dataset)*

</details>

---

## 🚀 Usage

1. Launch the app
2. Allow camera permissions
3. Point camera at a cosmetic product
4. Capture image
5. View:

   * **Top prediction**
   * **Confidence percentage**
   * **Alternative predictions**

---

## 🏗️ Project Structure


app/
├── src/main/
│   ├── java/com/example/bangladeshicosmeticproductsimageclassifier/
│   │   └── MainActivity.java     # Core logic & TFLite inference
│   ├── ml/model.tflite           # Model file
│   ├── res/layout/activity_main.xml
│   ├── res/values/strings.xml
│   └── AndroidManifest.xml
├── build.gradle.kts
└── settings.gradle.kts


---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch
3. Commit changes
4. Open a Pull Request

### Suggestions for Improvement

* Add more cosmetic classes
* Improve training dataset
* Add offline image upload support
* Implement history & analytics
* Add multi-language support

---

## 📄 License

This project is released under the **MIT License**.

---

## 🙏 Acknowledgments

* TensorFlow Lite team
* Android developer community
* Everyone contributing to open-source ML apps

---

## 📞 Contact

For questions or collaboration:

* **GitHub:** [@omijr123](https://github.com/omijr123)
* **Project Link:**
  [https://github.com/omijr123/BangladeshiCosmeticProductsImageClassifier](https://github.com/omijr123/BangladeshiCosmeticProductsImageClassifier)

---


