# 📸 Image Data Augmentation Playground

An interactive, real-time web application built to help developers and data scientists **visualize and fine-tune image augmentation strategies** using TensorFlow’s `ImageDataGenerator`.

Stop guessing augmentation parameters.
See transformations live.
Optimize with confidence.

---

## 🎨 Live Preview



---

## 📌 Project Overview

This application provides a **hands-on augmentation sandbox** where users can:

* Adjust transformation parameters
* Instantly visualize augmented outputs
* Compare batch variations
* Understand the impact of fill modes

It’s designed for:

* ML beginners learning augmentation
* Data scientists tuning CV pipelines
* Interview demos
* Dataset experimentation before training

---

## 🚀 Key Features

### ⚡ Real-Time Interaction

Adjust sliders and toggles to instantly preview transformed images via a sleek **Gradio** interface.

### 🎛 Comprehensive Controls

#### 🔹 Geometric Transformations

* Rotation range
* Width & height shifts
* Shear transformations
* Zoom range

#### 🔹 Logical Transformations

* Horizontal flip
* Vertical flip
* Fill mode selection:

  * `nearest`
  * `reflect`
  * `wrap`
  * `constant`

### 🧪 Batch Preview Mode

Generate multiple augmented samples simultaneously to observe dataset variance.

### ☁️ Flexible Deployment

* Run locally
* Run in Google Colab
* Lightweight and fast

---

## 🧠 Why This Project Matters

Data augmentation directly impacts:

* Model generalization
* Overfitting reduction
* Robustness to spatial transformations
* Real-world performance

This project demonstrates understanding of **preprocessing pipelines**—a critical yet often overlooked part of deep learning workflows.

---

## 🛠 Technical Stack

| Component           | Technology         |
| ------------------- | ------------------ |
| Deep Learning       | TensorFlow / Keras |
| Augmentation Engine | ImageDataGenerator |
| Frontend UI         | Gradio             |
| Image Processing    | Pillow / NumPy     |
| Language            | Python 3.8+        |

---

## 📂 Project Structure

```id="p1x9va"
image-data-augmentation-gradio/
│
├── demo/                # Screenshots & GIF previews
├── app.py               # Main Gradio application
├── requirements.txt     # Dependencies
└── README.md            # Documentation
```

Minimal structure. Clean separation of concerns.

---

## 📥 Installation & Setup

### 1️⃣ Clone the Repository

```bash id="xv8nqw"
git clone https://github.com/Tanmay1112004/image-data-augmentation-gradio.git
cd image-data-augmentation-gradio
```

### 2️⃣ Install Dependencies

```bash id="lmf2qt"
pip install -r requirements.txt
```

---

## ▶️ How to Use

### 🔹 Local Execution

```bash id="3rbqjk"
python app.py
```

Launches a local Gradio server.

---

### 🔹 Google Colab Quickstart

```python
!pip install gradio tensorflow --quiet

import app
```

Or paste the app code directly inside a notebook cell.

---

## 🎯 What This Project Demonstrates

* Practical understanding of data preprocessing
* Mastery of augmentation hyperparameters
* Interactive ML tool building
* Clean UI + backend integration
* Rapid ML experimentation workflow

This is an excellent portfolio project for:

* Computer Vision internships
* ML Engineering roles
* AI-focused software development

---

## 💡 Pro Tip

Experiment with **Fill Mode** while applying large rotations or shifts to understand how edge pixels are reconstructed.
This directly affects model robustness in real-world data.

---

## 🔮 Future Enhancements

* Real-time webcam augmentation
* Augmentation comparison charts
* Integration with tf.data pipeline
* Save augmented datasets
* Dockerized deployment

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push and open a Pull Request

Contributions are welcome and appreciated.

---

## 📜 License

MIT License

---

### 👨‍💻 Author

**Tanmay**

Open to opportunities in:

* Machine Learning
* Computer Vision
* Deep Learning Engineering
* AI Product Development

---

