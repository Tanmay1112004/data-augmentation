# 📸 Image Data Augmentation Playground

An interactive, real-time web application designed to help developers and data scientists visualize how **ImageDataGenerator** parameters transform their datasets. Stop guessing your augmentation values—see them in action.

---
## Demo Images

![demo](data-augmentation/Data Augmentation/screenshots/Screenshot 2025-09-02 083142.pngatmain·Tanmay1112004/data-augmentation)                                                                                    ![demo](data-augmentation/Data Augmentation/screenshots/Screenshot 2025-09-02 083208.pngatmain.Tanmay1112004/data-augmentation)                                                                                    ![demo](data-augmentation/Data Augmentation/screenshots/Screenshot 2025-09-02 083422.pngatmain·Tanmay1112004/data-augmentation)                                                                                    ![demo](data-augmentation/Data Augmentation/screenshots/Screenshot 2025-09-02 083557.pngatmain·Tanmay1112004/data-augmentation)                                                                                    ![demo](data-augmentation/Data Augmentation/screenshots/Screenshot 2025-09-02 083641.pngatmain·Tanmay1112004/data-augmentation)

---

## 🚀 Key Features

* **Real-time Interaction:** Tweak parameters and see results instantly via a sleek Gradio interface.
* **Comprehensive Controls:** * **Geometric:** Rotation, Width/Height shifts, Shear, and Zoom.
* **Logic:** Horizontal/Vertical flips and Fill Mode selection (`nearest`, `reflect`, etc.).


* **Batch Preview:** Generates multiple augmented samples simultaneously to show the variance in your settings.
* **One-Click Deployment:** Optimized for both local environments and **Google Colab**.

---

## 🛠️ Technical Stack

| Component | Technology |
| --- | --- |
| **Deep Learning** | TensorFlow / Keras |
| **Frontend UI** | Gradio |
| **Image Processing** | Pillow / NumPy |
| **Language** | Python 3.8+ |

---

## 📥 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/image-data-augmentation-gradio.git
cd image-data-augmentation-gradio

```

### 2. Install Dependencies

```bash
pip install -r requirements.txt

```

---

## ▶️ How to Use

### Local Execution

Simply launch the script to start the local web server:

```bash
python app.py

```

### Google Colab Quickstart

If you're running in a notebook, ensure the libraries are present:

```python
!pip install gradio tensorflow --quiet

# Import and launch within the cell
import app 
# (Or paste your app.py code directly)

```

---

## 📂 Project Structure

```text
📦 image-data-augmentation-gradio
 ┣ 📂 demo                # UI Screenshots & GIFs
 ┣ 📜 app.py              # Main Gradio application logic
 ┣ 📜 requirements.txt    # Project dependencies
 ┗ 📜 README.md           # Documentation

```

---

## 🎨 Visual Preview

> **Pro Tip:** Use the "Fill Mode" toggle to see how the model handles empty pixels created by rotations or shifts.

<div align="center">
<img src="demo/demo.png" alt="App Demo" width="850" style="border-radius: 10px;">
</div>

---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and create.

1. **Fork** the Project.
2. Create your **Feature Branch** (`git checkout -b feature/AmazingFeature`).
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`).
4. **Push** to the Branch (`git push origin feature/AmazingFeature`).
5. Open a **Pull Request**.

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---
