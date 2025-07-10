# 📸 Cricket Legends Image Classifier 🏏

Welcome to the **Cricket Legends Image Classification Project**, a deep learning application that classifies images of 30 cricket legends using a Convolutional Neural Network (CNN) built with TensorFlow and deployed using Gradio! 🚀

---

## 🔥 Project Highlights

- ✅ Trained using **MobileNetV2** as base model  
- 🧠 30 legendary cricketers including **Sachin Tendulkar**, **MS Dhoni**, **Virat Kohli**, and more  
- 🖼️ Supports **batch image uploads**  
- 💡 **Accuracy** output in filename: `Sachin_Tendulkar_93.42%.jpg`  
- 🌐 Deployed on **Hugging Face Spaces** with Gradio  
- 📁 Zips & downloads output images with prediction names  

---

## 🧰 Tech Stack

| Tool/Library        | Use Case                         |
|---------------------|----------------------------------|
| TensorFlow/Keras 🧠 | Model architecture & training    |
| OpenCV / PIL 🖼️     | Image processing                 |
| NumPy 🔢            | Data manipulation                |
| Gradio 🌐           | Web UI for model interaction     |
| Hugging Face 🚀     | App deployment                   |


---

## 🚀 How It Works

### 1️⃣ Model Training (`train_model.ipynb`)

- ✅ Used `MobileNetV2` as feature extractor  
- 🔄 Applied **data augmentation** (flip, rotation, zoom)  
- 🧠 Added custom dense layers + dropout  
- 💾 Saved as `model.keras`

---

### 2️⃣ Gradio Interface (`app.py`)

- 📂 Accepts `.zip` folder of images  
- 🏷️ Predicts class for each image  
- 📸 Saves each prediction as `Name_Accuracy.jpg`  
- 📦 Outputs final `results.zip`  


---

## 🧪 Example Prediction Output

| Input Image | Prediction |
|-------------|-------------|
| `don.jpg` | `Don_Bradman_97.61%.jpg` |
| `lara.png` | `Brian_Lara_91.12%.jpg` |
| `sachin.jpeg` | `Sachin_Tendulkar_93.42%.jpg` |

---

## 📦 Deployment on Hugging Face

- App successfully deployed on [Hugging Face Spaces](https://huggingface.co/spaces/tarunkkk/New3)  
- Upload `.zip`, see predictions, download results  
- Supports `.jpg`, `.jpeg`, `.png`  

---

## 📈 Model Performance

| Metric         | Value     |
|----------------|-----------|
| Accuracy       | ✅ ~72%    |
| Loss           | ❌ ~20.3   |
| Optimizer      | `Adam`    |
| Epochs         | `20`      |



---

## 🙌 Credits

Developed by **Tarun Kusumba** as part of the **Atom Systems AI Projects**.  
Special thanks to mentors & managers for guidance! 👨‍🏫

---

