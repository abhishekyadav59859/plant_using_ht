
# 🌿 Plant Disease Prediction App

Welcome to the **Plant Disease Prediction App**, an AI-powered tool to detect plant diseases from leaf images using deep learning and intelligent knowledge retrieval.

## 🔗 Live Demo

👉 [https://plant-using-ht.onrender.com](https://plant-using-ht.onrender.com)

> ⚠️ **Please note:** This project is hosted on **Render's free tier**, so it may take a few seconds to load **if it hasn’t been accessed in the past 15 minutes**.   
> As a student, I currently cannot afford the paid Render plan. Thank you for your patience and support!

---

## 🔍 Project Overview

This system is designed to help **farmers, researchers, and gardeners** by providing **instant, reliable plant disease detection** from leaf images. It uses a **Convolutional Neural Network (CNN)** model for classification, along with **Wikipedia** and **Gemini 1.5 Flash (Google AI)** to provide disease-related information and suggested remedies.

---

## 📦 Dataset & Model

The model is trained using the **PlantVillage dataset** and saved in `.h5` format.

📁 [Download the trained model file (.h5)](https://drive.google.com/file/d/1Ms1HkwFo7im2Yh6V9Hn90jE_qERJl96y/view?usp=drive_link)

---

## 💻 Technologies Used

| Technology         | Purpose                                             |
|--------------------|-----------------------------------------------------|
| **TensorFlow / Keras** | Deep learning & CNN for image classification     |
| **HTML, CSS, JS**      | Frontend for web interface                       |
| **Flask**              | Python-based backend for handling requests       |
| **Streamlit**          | Additional UI layer for dynamic rendering        |
| **Wikipedia API**      | Primary source for disease info                  |
| **Gemini 1.5 Flash**   | AI-generated fallback responses for reliability  |
| **NumPy & Pillow**     | Image and data processing                        |

---

## 🔧 Key Features

- ✅ Upload plant leaf images to predict diseases in real time  
- ✅ Display disease name, symptoms, and cure suggestions  
- ✅ Dual-source knowledge (Wikipedia + Gemini AI)  
- ✅ Fully responsive UI for mobile and desktop  
- ✅ Lightweight, fast, and informative  
- ✅ AI fallback ensures no empty responses  

---

## 🧠 How It Works

1. User uploads an image of a diseased leaf.
2. The backend (Flask + TensorFlow) runs inference using the trained CNN model.
3. Once the disease is identified:
   - The app fetches detailed info from **Wikipedia**.
   - If Wikipedia lacks data, **Gemini 1.5 Flash** generates a reliable fallback answer.
4. The user is shown disease name, symptoms, and treatment steps.

---

## 📍 Real-World Applications

- 🚜 Crop disease detection for farmers  
- 🧪 Tools for agriculture and biology researchers  
- 📱 Instant mobile diagnostics in remote areas  
- 🎓 Projects for AI and bioinformatics students  
- 💡 Use in tech fairs, hackathons, and exhibitions  

---

## 📬 Developer’s Note

> “This project is a meaningful blend of AI, computer vision, and real-world utility. It was made with a lot of learning, passion, and love for solving genuine problems in agriculture.”

Built with ❤️ as part of a student innovation journey. Inspired by a conversation titled **"Plant Disease Prediction App"** with ChatGPT (OpenAI), which guided the AI logic, deployment, and design philosophy.

---

## 🙌 Support & Contact

Feel free to reach out if you'd like to contribute, share feedback, or showcase this project :
- GitHub: [https://github.com/abhishekyadav59859](https://github.com/abhishekyadav59859)
- Email: [abhishekyadav59859@gmail.com](mailto:abhishekyadav59859@gmail.com)
- LinkedIn: [LinkedIn Profile](https://in.linkedin.com/in/abhishekyadav59859)


💚 *Let’s make agriculture smarter — one leaf at a time.*
