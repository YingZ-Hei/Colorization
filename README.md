# 🌈 Colorization

## 📌 Introduction
Image colorization is a challenging task in computer vision, requiring models to predict realistic and appropriate colors for grayscale images. In this work, we investigate the generalizability of a deep learning-based colorization model across different image domains, including flowers, natural landscapes, and animated faces.

Our approach utilizes the **CIELAB color space** and a **CNN based on a pretrained ResNet-18 architecture** to colorize images. Additionally, we explore the impact of different loss functions on colorization performance. Through experiments on three different applications, we analyze how model performance varies across image types and optimization objectives. Our results highlight the challenges of generalizing a single colorization model to diverse image applications.

---

## 📂 Dataset
The datasets used in this project include:

- **Flowers**: [Oxford 17 Flowers Dataset](https://www.robots.ox.ac.uk/~vgg/data/flowers/17/index.html)
- **Animated Faces**: [Gochiusa Faces Dataset](https://www.kaggle.com/datasets/rignak/gochiusa-faces/data)
- **Landscapes**: [Landscape Image Colorization Dataset](https://www.kaggle.com/datasets/theblackmamba31/landscape-image-colorization/data)

---

## ⚙️ Installation
To set up the project, follow these steps:

```sh
# Clone the repository
git clone https://github.com/YingZ-Hei/Colorization.git
cd Colorization

# Install dependencies
pip install -r requirements.txt

## 📊 Model Architecture
Our model is based on a pretrained ResNet-18 backbone and operates in the CIELAB color space. The L-channel is used as input, while the model predicts the a and b color channels.

📜 License
This project is licensed under the MIT License.
